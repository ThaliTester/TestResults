#### Test 79751015e87fad4_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
08-05 14:14:01.467   765  3081 D SSRM:n  : SIOP:: AP = 310, PST = 310, CUR = 450
--------- beginning of main
08-05 14:14:02.166   305   305 E SMD     : DCD ON
,08-05 14:14:02.626  7486  7486 D AndroidRuntime: 
08-05 14:14:02.626  7486  7486 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-05 14:14:02.636  7486  7486 D AndroidRuntime: CheckJNI is OFF
08-05 14:14:02.636  7486  7486 D AndroidRuntime: readGMSProperty: start
08-05 14:14:02.636  7486  7486 D AndroidRuntime: readGMSProperty: already setted!!
08-05 14:14:02.636  7486  7486 D AndroidRuntime: readGMSProperty: end
08-05 14:14:02.636  7486  7486 D AndroidRuntime: addProductProperty: start
08-05 14:14:02.796  7486  7486 E AffinityControl: AffinityControl: registerfunction enter
08-05 14:14:02.826  7486  7486 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-05 14:14:02.826   765  1452 E PersonaManagerService: inState():  stateMachine is null !!
08-05 14:14:02.826   765  1452 I PersonaManagerService: PersonaId don't exist
08-05 14:14:02.826   765  1452 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-05 14:14:02.826   765  1452 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-05 14:14:02.826   765  1452 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
08-05 14:14:02.826   765  1452 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-05 14:14:02.836   765  1452 W ActivityManager: mDVFSHelper.acquire()
08-05 14:14:02.836   765  1452 D FocusedStackFrame: Set to : 0
08-05 14:14:02.836   765  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:02.846   765  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:02.846   765  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:02.846   765  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:02.896   765  1452 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7501 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-05 14:14:02.906  7501  7501 E Zygote  : MountEmulatedStorage()
08-05 14:14:02.906  7501  7501 E Zygote  : v2
08-05 14:14:02.906  7501  7501 I libpersona: KNOX_SDCARD checking this for 10079
08-05 14:14:02.906  7501  7501 I libpersona: KNOX_SDCARD not a persona
08-05 14:14:02.906   765  1059 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-05 14:14:02.906   765  1059 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 14:14:02.906   765  1059 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-05 14:14:02.906   765  1059 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-05 14:14:02.906  7501  7501 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 14:14:02.906  7501  7501 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-05 14:14:02.906  7486  7486 D AndroidRuntime: Shutting down VM
08-05 14:14:02.916  7501  7501 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-05 14:14:02.936  7501  7501 D TimaKeyStoreProvider: TimaSignature is unavailable
08-05 14:14:02.936  7501  7501 D ActivityThread: Added TimaKeyStore provider
08-05 14:14:02.946   765  1647 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-05 14:14:02.946   765  1647 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
08-05 14:14:02.946   765  1647 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-05 14:14:02.946   765  1647 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-05 14:14:02.946   765  1647 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
08-05 14:14:02.966   765  3081 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:02.976  1440  1440 D SurfaceWidgetView: destroyHardwareResources():977897910
08-05 14:14:02.986  7501  7501 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
08-05 14:14:02.996   765  3081 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:03.046   266   402 I SurfaceFlinger: id=8 Removed Mauncher (6/8)
08-05 14:14:03.046   266   400 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
08-05 14:14:03.046  1767  1777 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
08-05 14:14:03.046  1440  1440 V ActivityThread: updateVisibility : ActivityRecord{30965ee3 token=android.os.BinderProxy@2c144af7 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-05 14:14:03.046  1440  1440 D Launcher: onTrimMemory. Level: 20
08-05 14:14:03.086  7501  7501 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
08-05 14:14:03.086  7501  7501 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
08-05 14:14:03.096  7501  7501 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2284-2287)
08-05 14:14:03.096  7501  7501 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 14:14:03.116  7501  7501 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {27edbd19}
08-05 14:14:03.116  7501  7501 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 14:14:03.116  7501  7501 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-05 14:14:03.146  7501  7501 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-05 14:14:03.146  7501  7501 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-05 14:14:03.156  7501  7501 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-05 14:14:03.186  7501  7501 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
08-05 14:14:03.186  7501  7501 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
08-05 14:14:03.186  7501  7501 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,08-05 14:14:03.196  7501  7501 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
08-05 14:14:03.196  7501  7501 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
08-05 14:14:03.196  7501  7501 I Adreno-EGL: Build Date: 11/19/14 Wed
08-05 14:14:03.196  7501  7501 I Adreno-EGL: Local Branch: mybranch5813579
08-05 14:14:03.196  7501  7501 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
08-05 14:14:03.196  7501  7501 I Adreno-EGL: Local Patches: NONE
08-05 14:14:03.196  7501  7501 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,08-05 14:14:03.316  7501  7542 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,08-05 14:14:03.346  7501  7501 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-05 14:14:03.356  7501  7501 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-05 14:14:03.366  7501  7501 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-05 14:14:03.376  7501  7501 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 14:14:03.376  7501  7501 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-05 14:14:03.436  7501  7501 D Activity: performCreate Call secproduct feature valuefalse
08-05 14:14:03.436  7501  7501 D Activity: performCreate Call debug elastic valuetrue
,08-05 14:14:03.446  7501  7555 D OpenGLRenderer: Render dirty regions requested: true
,08-05 14:14:03.446   765  1452 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-05 14:14:03.446   765  1452 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-05 14:14:03.446   765   765 D PersonaManagerService: getPersonasForUser(): returning null!
08-05 14:14:03.446   765  1452 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-05 14:14:03.446   765   765 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-05 14:14:03.476   266   266 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,08-05 14:14:03.476   765  1057 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-05 14:14:03.476   765  1057 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-05 14:14:03.486   765  1059 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-05 14:14:03.486   765  1059 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 14:14:03.486   765  1059 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-05 14:14:03.486   765  1059 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-05 14:14:03.486  7501  7555 I OpenGLRenderer: Initialized EGL, version 1.4
,08-05 14:14:03.496  7501  7555 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xb3bc6218 ,&mEglDisplay = 1 , &mEglConfig = 8 
,08-05 14:14:03.496  7501  7555 D OpenGLRenderer: Enabling debug mode 0
,08-05 14:14:03.516  7501  7501 V ActivityThread: updateVisibility : ActivityRecord{2fcc5ecb token=android.os.BinderProxy@353e1a45 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-05 14:14:03.536   765  1706 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-05 14:14:03.546   765  7559 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-05 14:14:03.546  1739  1739 I SamsungIME: getCurrentCandidateView
,08-05 14:14:03.556  7501  7501 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-05 14:14:03.556  7501  7501 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@353e1a45 time:362741
,08-05 14:14:03.556   765  1059 W ActivityManager: mDVFSHelper.release()
08-05 14:14:03.556   765  1059 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{16c5f769 u0 com.test.thalitest/.MainActivity t99} time:362746
,08-05 14:14:03.606  7501  7501 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7501
,08-05 14:14:03.616  1739  1739 D SamsungIME: Dismiss ExpandCandiate
,08-05 14:14:03.676  7501  7501 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-05 14:14:03.696  1739  1739 I SamsungIME: getDebugLevel  : 0x4f4c
,08-05 14:14:03.726  1739  1739 I SamsungIME: getDebugLevel  : 0x4f4c
,08-05 14:14:03.736  1739  1739 I SamsungIME: KeybaordView init() : load resources
,08-05 14:14:03.756  1739  1739 I SamsungIME: getCurrentKeyboard
08-05 14:14:03.756  1739  1739 I SamsungIME: getTextKeyboard
,08-05 14:14:03.776  1739  1739 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-05 14:14:03.776  7501  7562 D jxcore_app_log: JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1357923200
,08-05 14:14:03.786  7501  7562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-05 14:14:03.786  7501  7562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-05 14:14:03.786  7501  7562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-05 14:14:03.786  7501  7562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-05 14:14:03.786  7501  7562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-05 14:14:03.786  7501  7562 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@191690bb added. We now have 1 listener(s)
,08-05 14:14:03.796  7501  7562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:1F:C9:5E
,08-05 14:14:03.796  7501  7562 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,08-05 14:14:03.796  7501  7562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-05 14:14:03.796  7501  7562 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-05 14:14:03.806  7501  7562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-05 14:14:03.806  7501  7562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-05 14:14:03.806  7501  7562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-05 14:14:03.806  7501  7562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:1F:C9:5E
08-05 14:14:03.806  7501  7562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-05 14:14:03.806  7501  7562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-05 14:14:03.806  7501  7562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-05 14:14:03.806  7501  7562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-05 14:14:03.806  7501  7562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-05 14:14:03.806  7501  7562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-05 14:14:03.806  7501  7562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-05 14:14:03.806  7501  7562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-05 14:14:03.806  7501  7562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-05 14:14:03.806  7501  7562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-05 14:14:03.806  7501  7562 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2190d016 added. We now have 1 listener(s)
08-05 14:14:03.806  7501  7562 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 14:14:03.806  7501  7562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 14:14:03.816  7501  7562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-05 14:14:03.816  7501  7562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-05 14:14:03.816  7501  7562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-05 14:14:03.816  7501  7562 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-05 14:14:03.816  7501  7562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 14:14:03.816  7501  7562 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:1F:C9:5E
,08-05 14:14:03.816   765  3349 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:03.826  7501  7562 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-05 14:14:03.826  7501  7562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:03.826  7501  7562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:03.826  7501  7562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:03.826  7501  7562 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:03.826  7501  7562 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:03.826  7501  7562 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:03.826  7501  7562 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 14:14:03.826  7501  7562 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 14:14:03.826  7501  7562 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-05 14:14:03.826  7501  7562 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 14:14:03.826   765  1677 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:03.826  7501  7562 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-05 14:14:03.826  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:03.826   765  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:03.826  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:03.846  7501  7501 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-05 14:14:04.116  1739  7565 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-05 14:14:04.486   765  1677 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-05 14:14:04.486   765  1677 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4328, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
08-05 14:14:04.486   765  1677 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
08-05 14:14:04.486   765   765 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-05 14:14:04.486   765  1677 D BatteryService: stay LED for fully charged
,08-05 14:14:04.486  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-05 14:14:04.486  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
08-05 14:14:04.486   765   765 I MotionRecognitionService: Plugged
08-05 14:14:04.486   765   765 I MotionRecognitionService: setPowerConnected  = true
,08-05 14:14:04.486  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
08-05 14:14:04.486  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-05 14:14:04.486  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-05 14:14:04.486  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-05 14:14:04.486  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-05 14:14:04.486  3004  3076 D HeadsetStateMachine: Disconnected process message: 10
,08-05 14:14:04.666  7501  7570 W jxcore-log: Initializing JXcore engine
,08-05 14:14:04.676  7501  7570 W jxcore-log: JXcore engine is ready
,08-05 14:14:04.736  1843  1843 E auditd  : In denial and Property audit_ondenial is set to 1 
,08-05 14:14:04.736  1843  1843 E audit   : type=1400 msg=audit(1470399244.736:203): avc:  denied  { ioctl } for  pid=7570 comm="Thread-1224" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-05 14:14:04.736   765  1041 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
08-05 14:14:04.736  1843  1843 E audit   :  SEPF_SM-N9005_5.0-1_0032
08-05 14:14:04.736  1843  1843 E audit   : 
08-05 14:14:04.736  1843  1843 E audit   : type=1300 msg=audit(1470399244.736:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=1 a3=980e48d8 items=0 ppid=337 ppcomm=main pid=7570 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1224" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
,08-05 14:14:04.736  1843  1843 E audit   : type=1320 msg=audit(1470399244.736:203): 
08-05 14:14:04.736   765  1041 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,08-05 14:14:04.736   765  1041 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,08-05 14:14:04.746  6711  6711 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,08-05 14:14:04.746  6711  6711 D SecurityLogAgent:  SeDenialReceiver : File path = null
,08-05 14:14:04.756  7501  7570 W jxcore-log: Starting JXcore engine
,08-05 14:14:04.846  7501  7570 W jxcore-log: Platform android
08-05 14:14:04.846  7501  7570 W jxcore-log: 
08-05 14:14:04.846  7501  7570 W jxcore-log: Process ARCH arm
08-05 14:14:04.846  7501  7570 W jxcore-log: 
,08-05 14:14:05.086  7501  7570 I jxcore-log: JXcore Cordova bridge is ready!
08-05 14:14:05.086  7501  7570 I jxcore-log: 
,08-05 14:14:05.086  7501  7570 W jxcore-log: JXcore engine is started
,08-05 14:14:05.086  7501  7562 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-05 14:14:05.096  7501  7501 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-05 14:14:05.156   305   305 E SMD     : DCD ON
,08-05 14:14:05.476   346   346 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 14:14:06.476   346   346 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 14:14:07.476   346   346 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 14:14:08.156   305   305 E SMD     : DCD ON
,08-05 14:14:08.476   346   346 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 14:14:09.476   346   346 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 14:14:10.476   346   346 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,08-05 14:14:11.156   305   305 E SMD     : DCD ON
,08-05 14:14:11.516   765  3081 D SSRM:n  : SIOP:: AP = 360, PST = 315, CUR = 450
,08-05 14:14:12.866   765  1065 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-05 14:14:14.156   305   305 E SMD     : DCD ON
,08-05 14:14:14.536   765   784 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-05 14:14:14.536   765   784 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
08-05 14:14:14.536   765   784 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
08-05 14:14:14.536   765   784 D BatteryService: stay LED for fully charged
08-05 14:14:14.536   765   765 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-05 14:14:14.546   765   765 I MotionRecognitionService: Plugged
08-05 14:14:14.546   765   765 I MotionRecognitionService: setPowerConnected  = true
,08-05 14:14:14.546  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-05 14:14:14.546  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-05 14:14:14.556  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,08-05 14:14:14.556  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-05 14:14:14.556  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-05 14:14:14.556  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-05 14:14:14.556  3004  3004 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-05 14:14:14.556  3004  3076 D HeadsetStateMachine: Disconnected process message: 10
,08-05 14:14:17.156   305   305 E SMD     : DCD ON
,08-05 14:14:17.286   765  3114 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-05 14:14:20.056   765  1346 E Watchdog: !@Sync 12
,08-05 14:14:20.156   305   305 E SMD     : DCD ON
,08-05 14:14:20.576  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-05 14:14:20.576  7501  7570 I jxcore-log: 
,08-05 14:14:20.586  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-05 14:14:20.586  7501  7570 I jxcore-log: 
,08-05 14:14:20.586   765  1322 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:20.586  7501  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:20.586  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:20.586  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:20.586  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:20.586  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:20.586  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:20.586  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 14:14:20.586  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 14:14:20.596  7501  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 14:14:20.596  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-05 14:14:20.596  7501  7570 I jxcore-log: 
,08-05 14:14:20.596  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-05 14:14:20.596  7501  7570 I jxcore-log: 
,08-05 14:14:20.936  7501  7570 D ExecuteNativeTests: Running unit tests
,08-05 14:14:21.036  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 14:14:21.036  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b added. We now have 2 listener(s)
,08-05 14:14:21.036  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
08-05 14:14:21.036  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 14:14:21.036  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 14:14:21.036  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-05 14:14:21.036  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 added. We now have 2 listener(s)
08-05 14:14:21.036  7501  7570 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:21.036  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 14:14:21.036  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 14:14:21.046   765  1452 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.046  7501  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:21.046  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:21.046  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:21.046  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:21.046  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:21.046  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:21.046  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 14:14:21.046  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 14:14:21.046  7501  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:21.046  7501  7570 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 14:14:21.046   765  1677 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.046  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:21.046   765  1706 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.056  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:21.056  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-05 14:14:21.056  7501  7570 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 14:14:21.056  7501  7570 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-05 14:14:21.056  7501  7570 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-05 14:14:21.056  7501  7570 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-05 14:14:21.056  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 14:14:21.056  7501  7570 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 14:14:21.056  7501  7570 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 14:14:21.056  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 14:14:21.056  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:21.056  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:21.056  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.056  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 14:14:21.056  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:21.056  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 14:14:21.066  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b removed from the list
08-05 14:14:21.066  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.066  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 removed from the list
08-05 14:14:21.066  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.066  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:21.066  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.066  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:21.066  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:21.066  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:21.066  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 14:14:21.066  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
,08-05 14:14:21.066  7501  7570 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-05 14:14:21.066  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:21.066  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:21.066  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:21.066  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-05 14:14:21.066  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.066  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.066  7501  7570 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b not in the list
08-05 14:14:21.066  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.066  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.066  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.066  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.066  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.066  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.066  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:21.066  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:21.066  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:21.066  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.066  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
,08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-05 14:14:21.076  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:21.076  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-05 14:14:21.076  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:21.076  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.076  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.076  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.076  7501  7570 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b not in the list
08-05 14:14:21.076  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.076  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.076  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.076  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.076  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:21.076  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.076  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.086  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:21.086  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:21.086  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.086  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
,08-05 14:14:21.086  7501  7570 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-05 14:14:21.086  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 14:14:21.086   765  1677 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.086  7501  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:21.086  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:21.086  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:21.086  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:21.086  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:21.086  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:21.086  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 14:14:21.086  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 14:14:21.086  7501  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:21.086  7501  7570 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 14:14:21.086   765  1578 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.086  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:21.086   765  1289 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:21.086  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 14:14:21.086  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-05 14:14:21.096  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:21.096  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 14:14:21.096  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:21.096  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-05 14:14:21.096  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-05 14:14:21.096  7501  7570 E BluetoothAdapter: bluetooth le advertising not supported
,08-05 14:14:21.096  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-05 14:14:21.096  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-05 14:14:21.106  7501  7570 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-05 14:14:21.106  7501  7570 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,08-05 14:14:21.106  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-05 14:14:21.106  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-05 14:14:21.106  7501  7570 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-05 14:14:21.106  7501  7570 I io.jxcore.node.ConnectionHelper: start: OK
,08-05 14:14:21.106  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 14:14:21.106  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:21.106  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:21.106  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.106  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.106  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-05 14:14:21.106  7501  7570 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b not in the list
08-05 14:14:21.106  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 14:14:21.116  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.116  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.116  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:21.116  7501  7570 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-05 14:14:21.116  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 14:14:21.116   765  1322 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.116  7501  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:21.116  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:21.116  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:21.116  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:21.116  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:21.116  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:21.116  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 14:14:21.116  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 14:14:21.116  7501  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 14:14:21.116  7501  7570 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 14:14:21.116   765  1437 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.116  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 14:14:21.116  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 14:14:21.116  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-05 14:14:21.116  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:21.116  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-05 14:14:21.116  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:21.116   765  1237 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.126  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:21.126  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-05 14:14:21.126  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-05 14:14:21.126  7501  7570 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-05 14:14:21.126  7501  7570 I io.jxcore.node.ConnectionHelper: start: OK
,08-05 14:14:21.126  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:21.126  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:21.126  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 14:14:21.126  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.126  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.126  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:21.126  7501  7570 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b not in the list
08-05 14:14:21.126  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.126  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
,08-05 14:14:21.126  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.126  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.126  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.136  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:21.136  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:21.136  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:21.136  7501  7570 D BluetoothLeScanner: could not find callback wrapper
,08-05 14:14:21.136  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:21.136  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.136  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
,08-05 14:14:21.136  7501  7570 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-05 14:14:21.136  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 14:14:21.136   765  3410 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.136  7501  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:21.136  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:21.136  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:21.136  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:21.136  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:21.136  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:21.136  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 14:14:21.136  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 14:14:21.136  7501  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 14:14:21.136  7501  7570 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 14:14:21.136   765  1322 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.136  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:21.136   765  1467 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.146  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:21.146  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 14:14:21.146  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 14:14:21.146  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 14:14:21.146  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:21.146  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-05 14:14:21.146  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-05 14:14:21.146  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-05 14:14:21.146  7501  7570 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-05 14:14:21.146  7501  7570 I io.jxcore.node.ConnectionHelper: start: OK
08-05 14:14:21.146  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:21.146  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:21.146  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 14:14:21.146  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:21.146  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:21.146  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 14:14:21.146  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.146  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.146  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:21.146  7501  7570 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b not in the list
08-05 14:14:21.146  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 14:14:21.146  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.146  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.146  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.146  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.146  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:21.146  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:21.146  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-05 14:14:21.156  7501  7570 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:21.156  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:21.156  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.156  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
,08-05 14:14:21.156  7501  7570 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-05 14:14:21.156  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:21.156  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-05 14:14:21.156  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:21.156  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.156  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.156  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.156  7501  7570 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b not in the list
08-05 14:14:21.156  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 14:14:21.156  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.156  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.156  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.156  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.156  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.156  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:21.156  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:21.156  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:21.156  7501  7570 D BluetoothLeScanner: could not find callback wrapper
,08-05 14:14:21.156  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:21.156  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.156  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
,08-05 14:14:21.156  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-05 14:14:21.156  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 14:14:21.156  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:21.156  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:21.156  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.156  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.156  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:21.156  7501  7570 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b not in the list
08-05 14:14:21.156  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.156  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.156  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.156  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.156  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.156  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 14:14:21.156  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.156  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-05 14:14:21.156  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:21.156  7501  7570 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:21.156  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:21.156  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.156  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
,08-05 14:14:21.156  7501  7570 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-05 14:14:21.156  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:21.156  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:21.156  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 14:14:21.156  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.166  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.166  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.166  7501  7570 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b not in the list
08-05 14:14:21.166  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.166  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.166  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
,08-05 14:14:21.166  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.166  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.166  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.166  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:21.166  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:21.166  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:21.166  7501  7570 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:21.166  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:21.166  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 14:14:21.166  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
,08-05 14:14:21.166  7501  7570 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-05 14:14:21.166  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:21.166  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:21.166  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:21.166  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-05 14:14:21.166  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.166  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.166  7501  7570 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b not in the list
08-05 14:14:21.166  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.166  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.166  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.166  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 14:14:21.166  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.166  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.166  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:21.166  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:21.166  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:21.166  7501  7570 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:21.166  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:21.166  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.166  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
,08-05 14:14:21.166  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-05 14:14:21.166  7501  7570 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 14:14:21.166  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 14:14:21.166  7501  7570 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 14:14:21.166  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-05 14:14:21.166  7501  7570 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-05 14:14:21.166  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:21.166  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:21.166  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:21.166  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.166  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.166  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.176  7501  7570 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b not in the list
,08-05 14:14:21.176  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.176  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.176  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.176  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.176  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.176  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:21.176  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:21.176  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:21.176  7501  7570 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:21.176  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-05 14:14:21.176  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.176  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
,08-05 14:14:21.176  7501  7570 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 14:14:21.176  7501  7570 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-05 14:14:21.176  7501  7570 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 14:14:21.176  7501  7570 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-05 14:14:21.176  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-05 14:14:21.176  7501  7570 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-05 14:14:21.176  7501  7570 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 14:14:21.176  7501  7570 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-05 14:14:21.186  7501  7570 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 14:14:21.186  7501  7570 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 14:14:21.186  7501  7570 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-05 14:14:21.186  7501  7570 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 14:14:21.186  7501  7570 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-05 14:14:21.186  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-05 14:14:21.186  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-05 14:14:21.186  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-05 14:14:21.186  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-05 14:14:21.186  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-05 14:14:21.186  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-05 14:14:21.186  7501  7570 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-05 14:14:21.186  7501  7570 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-05 14:14:21.186  7501  7570 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-05 14:14:21.186  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:21.186  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:21.186  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:21.186  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.186  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.186  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.186  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-05 14:14:21.186  7501  7570 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b not in the list
08-05 14:14:21.186  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.186  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.186  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.186  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.186  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.186  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.186  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.186  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:21.186  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:21.186  7501  7570 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:21.186  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:21.186  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.186  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.186  7501  7570 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-05 14:14:21.196  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:21.196  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:21.196  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:21.196  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.196  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.196  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.196  7501  7570 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b not in the list
08-05 14:14:21.196  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.196  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.196  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.196  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 14:14:21.196  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:21.196  7501  7588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1288)
08-05 14:14:21.196  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.196  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.196  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:21.196  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:21.196  7501  7570 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:21.196  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:21.196  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.196  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.196  7501  7570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-05 14:14:21.196  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:21.196  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:21.196  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:21.196  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.196  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.196  7501  7589 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1288
08-05 14:14:21.196  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.196  7501  7570 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b not in the list
08-05 14:14:21.196  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.196  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.196  7501  7588 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1288)
08-05 14:14:21.196  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.196  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.196  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.196  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.196  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:21.196  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:21.196  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:21.206  7501  7570 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:21.206  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:21.206  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.206  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
,08-05 14:14:21.206  7501  7570 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-05 14:14:21.206  7501  7570 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-05 14:14:21.206  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 14:14:21.206  7501  7570 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-05 14:14:21.206  7501  7570 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-05 14:14:21.206  7501  7570 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-05 14:14:21.206  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 14:14:21.206  7501  7570 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-05 14:14:21.206  7501  7570 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-05 14:14:21.206  7501  7570 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-05 14:14:21.206  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 14:14:21.206  7501  7570 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-05 14:14:21.206  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:21.206  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:21.206  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:21.206  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.206  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.206  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.206  7501  7570 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b not in the list
08-05 14:14:21.206  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.206  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.206  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.206  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.206  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.206  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.206  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.206  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:21.206  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:21.206  7501  7570 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:21.206  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:21.206  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.206  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.206  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.206  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.206  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.206  7501  7570 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b not in the list
08-05 14:14:21.206  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.206  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.206  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.206  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.206  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.206  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.206  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.206  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.206  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.206  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.206  7501  7570 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b not in the list
08-05 14:14:21.206  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:21.206  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:21.206  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:21.206  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.206  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.206  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.206  7501  7570 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b not in the list
08-05 14:14:21.206  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.206  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.206  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.206  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.216  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.216  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.216  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.216  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:21.216  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:21.216  7501  7570 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:21.216  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:21.216  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.216  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.216  7501  7570 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-05 14:14:21.216  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:21.216  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-05 14:14:21.216  7501  7570 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-05 14:14:21.216  7501  7570 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-05 14:14:21.216  7501  7501 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-05 14:14:21.216  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-05 14:14:21.216  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-05 14:14:21.216  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.216  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-05 14:14:21.216  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-05 14:14:21.216  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-05 14:14:21.216  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.216  7501  7570 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-05 14:14:21.216  7501  7501 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-05 14:14:21.216  7501  7570 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b not in the list
08-05 14:14:21.216  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.216  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-05 14:14:21.216  7501  7570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-05 14:14:21.216  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-05 14:14:21.216  7501  7590 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-05 14:14:21.216  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-05 14:14:21.216  7501  7590 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-05 14:14:21.216  7501  7570 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:21.216  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:21.216  7501  7570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-05 14:14:21.216  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.216  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.216  7501  7570 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 14:14:21.226  7501  7501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 14:14:21.226  7501  7501 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-05 14:14:21.226  7501  7501 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-05 14:14:21.226  7501  7501 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-05 14:14:21.226  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.226  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:21.226  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:21.226  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:21.226  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.226  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.226  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.226  7501  7570 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b not in the list
08-05 14:14:21.226  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.226  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.226  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.226  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.226  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.226  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.226  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.226  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:21.226  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:21.226  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.226  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.226  7501  7570 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-05 14:14:21.226  7501  7570 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-05 14:14:21.226  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-05 14:14:21.226  7501  7570 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-05 14:14:21.226  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:21.226  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:21.226  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:21.226  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.226  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.226  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.226  7501  7570 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b not in the list
08-05 14:14:21.226  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.226  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.226  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.226  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.226  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.226  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.226  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.236  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:21.236  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:21.236  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.236  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.236  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:21.236  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:21.236  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:21.236  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.236  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.236  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.236  7501  7570 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b not in the list
08-05 14:14:21.236  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.236  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.236  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.236  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.236  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.236  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.236  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.236  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:21.236  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:21.236  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.236  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.246  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:21.246  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:21.246  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:21.246  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:21.246  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.246  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.246  7501  7570 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@184bcf7b not in the list
08-05 14:14:21.246  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.246  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.246  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:21.246  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.246  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.246  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:21.246  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:21.246  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:21.246  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:21.246  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:21.246  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@25a10198 not in the list
08-05 14:14:21.246  7501  7570 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-05 14:14:21.246  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 14:14:21.246  7501  7570 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,08-05 14:14:21.246  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-05 14:14:21.246  7501  7570 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-05 14:14:21.246  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-05 14:14:21.246  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-05 14:14:21.246  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,08-05 14:14:21.246  7501  7570 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-05 14:14:21.246  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,08-05 14:14:21.246  7501  7570 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-05 14:14:21.246  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-05 14:14:21.256  7501  7570 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-05 14:14:21.256  7501  7570 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-05 14:14:21.256  7501  7570 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-05 14:14:21.256  7501  7570 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-05 14:14:21.256  7501  7570 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-05 14:14:21.256  7501  7570 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-05 14:14:21.256  7501  7570 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-05 14:14:21.256  7501  7570 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-05 14:14:21.256  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:21.256  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e0faa29 added. We now have 2 listener(s)
08-05 14:14:21.256  7501  7570 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:21.256  7501  7570 D BluetoothAdapter: enable()
08-05 14:14:21.256  7501  7570 D BluetoothAdapter: enable(): BT is already enabled..!
08-05 14:14:21.256  7501  7570 I WifiManager: packageName : com.test.thalitest
08-05 14:14:21.256   765  1452 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-05 14:14:21.256   765  1452 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-05 14:14:21.256   765  1452 D SecContentProvider2: mCursor = null
08-05 14:14:21.256   765  1452 D WifiService: setWifiEnabled: true pid=7501, uid=10079
08-05 14:14:21.256   765  1452 W ActivityManager: Permission Denial: getCurrentUser() from pid=7501, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-05 14:14:21.256   765  1452 W WifiService: Failed getting userId using ActivityManagerNative
08-05 14:14:21.256   765  1452 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7501, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-05 14:14:21.256   765  1452 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
08-05 14:14:21.256   765  1452 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
08-05 14:14:21.256   765  1452 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
08-05 14:14:21.256   765  1452 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-05 14:14:21.256   765  1452 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-05 14:14:21.256   765  1452 D SettingsProvider: name = wifi_on
08-05 14:14:21.256  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:21.256  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@373a21ae added. We now have 3 listener(s)
08-05 14:14:21.256  7501  7570 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 14:14:21.266  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-05 14:14:21.266  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@34978b4f added. We now have 4 listener(s)
08-05 14:14:21.266  7501  7570 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 14:14:21.266  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-05 14:14:21.266  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1f1292dc added. We now have 5 listener(s)
08-05 14:14:21.266  7501  7570 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 14:14:21.266  7501  7570 I WifiManager: packageName : com.test.thalitest
,08-05 14:14:21.266   765  1237 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-05 14:14:21.266   765  1237 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-05 14:14:21.266   765  1237 D SecContentProvider2: mCursor = null
,08-05 14:14:21.266   765  1237 D WifiService: setWifiEnabled: false pid=7501, uid=10079
,08-05 14:14:21.266   765  1237 D SettingsProvider: name = wifi_on
,08-05 14:14:21.266  7501  7570 D BluetoothAdapter: disable()
,08-05 14:14:21.266   765  1452 D SettingsProvider: name = bluetooth_on
,08-05 14:14:21.276  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 14:14:21.276   765  3349 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.276  3004  3068 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-05 14:14:21.276  3004  3068 D BluetoothAdapterProperties: Setting state to 13
08-05 14:14:21.276  3004  3068 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-05 14:14:21.276  3004  3068 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-05 14:14:21.276  3004  3068 D BluetoothAdapterService: updateAdapterState state is 13
,08-05 14:14:21.276   765  1467 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-05 14:14:21.276  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:21.276  7501  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:21.276  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:21.276  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:21.276  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:21.276  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 14:14:21.276  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:21.276  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 14:14:21.276  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 14:14:21.276  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:21.276  7501  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:21.276  7501  7570 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 14:14:21.276   765  1467 D ActivityManager: caller:android.app.ApplicationThreadProxy@35f41062, r.packageName :com.android.bluetooth
,08-05 14:14:21.276   765  1437 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:21.276  3004  3068 D BluetoothAdapterService: Autoconnection is available 
08-05 14:14:21.276  3004  3068 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-05 14:14:21.276  3004  3068 D BluetoothAdapterService: terminating service from this receiver
08-05 14:14:21.276  3004  3004 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-05 14:14:21.276  3004  3004 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@15336d52, channel: 19, state: LISTENING
,08-05 14:14:21.276  3004  3004 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@15336d52, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@21cab8fa, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@11a0b823mSocket: android.net.LocalSocket@79b4120 impl:android.net.LocalSocketImpl@9b2aad9 fd:FileDescriptor[72]
08-05 14:14:21.276  3004  3004 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@79b4120 impl:android.net.LocalSocketImpl@9b2aad9 fd:FileDescriptor[72]
,08-05 14:14:21.286  3004  3068 D BluetoothAdapterProperties: onBluetoothDisable()
,08-05 14:14:21.286   765  1322 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-05 14:14:21.286  3004  3068 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-05 14:14:21.286  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:21.286   765  1149 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-05 14:14:21.286   765   784 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.286  3004  3151 D bt_vendor: op for 7
,08-05 14:14:21.286  3004  3151 D bt_upio : proc btwrite assertion
,08-05 14:14:21.286  1739  1739 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-05 14:14:21.286  1316  1316 D BluetoothPbap: Proxy object disconnected
08-05 14:14:21.286  1316  1316 D PbapServerProfile: Bluetooth service disconnected
,08-05 14:14:21.296  1196  1196 D BluetoothTile:  onBluetoothStateChange:
,08-05 14:14:21.296  3004  3071 D BluetoothAdapterProperties: Scan Mode:20
,08-05 14:14:21.296  3004  3068 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-05 14:14:21.296  3004  3068 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-05 14:14:21.296  3004  3068 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-05 14:14:21.296  3004  3068 E bt-btif : BTM_SEC_CLR[17]: id 57
,08-05 14:14:21.296  3004  3151 D bt_vendor: op for 7
08-05 14:14:21.296  3004  3151 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:21.296  3004  3151 D bt_vendor: op for 7
08-05 14:14:21.296  3004  3151 D bt_upio : BT_WAKE is asserted already
08-05 14:14:21.296  3004  5613 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-05 14:14:21.296  3004  3149 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-05 14:14:21.296  3004  3149 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-05 14:14:21.296  3004  3149 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 14:14:21.296  3004  3149 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 14:14:21.296  3004  3149 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-05 14:14:21.296  3004  3151 D bt_vendor: op for 7
08-05 14:14:21.296  3004  3151 D bt_upio : BT_WAKE is asserted already
08-05 14:14:21.296  3004  3068 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-05 14:14:21.296  1303  1303 I wpa_supplicant: reset timer : RESET_TIMER 0
08-05 14:14:21.296  1303  1303 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-05 14:14:21.296  1303  1303 I wpa_supplicant: P2P: Current p2p state = IDLE
08-05 14:14:21.296  3004  3151 D bt_vendor: op for 7
08-05 14:14:21.296  3004  3151 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:21.306   765  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-05 14:14:21.306  3004  3151 D bt_vendor: op for 7
08-05 14:14:21.306  3004  3151 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:21.306  3004  3151 D bt_vendor: op for 7
08-05 14:14:21.306  3004  3151 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:21.306  1316  1316 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-05 14:14:21.306  3004  3151 D bt_vendor: op for 7
08-05 14:14:21.306  3004  3151 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:21.306  1196  1196 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-05 14:14:21.306  1196  1196 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-05 14:14:21.306  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:21.306  3004  3151 D bt_vendor: op for 7
08-05 14:14:21.306  3004  3151 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:21.306  3004  3151 D bt_vendor: op for 7
08-05 14:14:21.306  3004  3151 D bt_upio : BT_WAKE is asserted already
08-05 14:14:21.306  3004  3151 D bt_vendor: op for 7
08-05 14:14:21.306  3004  3151 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:21.316  1196  1597 D BluetoothTile:  handleUpdatestate:false name:null
,08-05 14:14:21.316  1303  1303 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-05 14:14:21.316  3004  3151 D bt_vendor: op for 7
08-05 14:14:21.316  3004  3151 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:21.316  3004  3151 D bt_vendor: op for 7
08-05 14:14:21.316  3004  3151 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:21.316  1196  1597 D BluetoothTile:  handleUpdatestate:false name:null
,08-05 14:14:21.316  3004  3151 D bt_vendor: op for 7
08-05 14:14:21.316  3004  3151 D bt_upio : BT_WAKE is asserted already
08-05 14:14:21.316   765  1647 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.316  3004  3151 D bt_vendor: op for 7
08-05 14:14:21.316  3004  3151 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:21.316  1196  1597 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-05 14:14:21.316  7501  7501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 14:14:21.316  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:21.316  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:21.316  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:21.316  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:21.316  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 14:14:21.316  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:21.316  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 14:14:21.316  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 14:14:21.316   765   765 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-05 14:14:21.316   765   765 I InputMethodManagerService: [BT Setting State] State =13
08-05 14:14:21.316   765  1677 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-05 14:14:21.316   765  1149 E native  : do suspend true
,08-05 14:14:21.316   765  1677 D ActivityManager: caller:android.app.ApplicationThreadProxy@23b505f3, r.packageName :com.google.android.gms
,08-05 14:14:21.326  7501  7501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:21.326  7501  7501 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 14:14:21.326   765  1706 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.326   765  1647 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,08-05 14:14:21.326   765  1144 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-05 14:14:21.326   765  1148 D WifiP2pService: InactiveState{ what=143375 }
,08-05 14:14:21.326   765  1148 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-05 14:14:21.326  1196  1196 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,08-05 14:14:21.336  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:21.336   765  1452 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:21.336   298  1056 D CommandListener: Clearing all IP addresses on wlan0
,08-05 14:14:21.336  1196  1196 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-05 14:14:21.336  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:21.336   765   784 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.336  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:21.336  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-05 14:14:21.366  3004  3004 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@183cb37f, channel: 5, state: LISTENING
,08-05 14:14:21.366  3004  3004 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@183cb37f, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@33091eab, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@23c34f4cmSocket: android.net.LocalSocket@1d1a1b95 impl:android.net.LocalSocketImpl@2c354aa fd:FileDescriptor[74]
,08-05 14:14:21.366  3004  3004 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1d1a1b95 impl:android.net.LocalSocketImpl@2c354aa fd:FileDescriptor[74]
,08-05 14:14:21.366  3004  3004 I BtOppRfcommListener: stopping Accept Thread
,08-05 14:14:21.366  3004  3004 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1673089b, channel: 12, state: LISTENING
,08-05 14:14:21.376  3004  3004 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1673089b, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b5e0ddd, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1e7c1438mSocket: android.net.LocalSocket@244ddc11 impl:android.net.LocalSocketImpl@345a1176 fd:FileDescriptor[78]
,08-05 14:14:21.376  3004  3004 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@244ddc11 impl:android.net.LocalSocketImpl@345a1176 fd:FileDescriptor[78]
,08-05 14:14:21.376  3004  5613 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-05 14:14:21.376  1903  5073 V NativeCrypto: Read error: ssl=0xaf33ee00: I/O error during system call, Connection timed out
,08-05 14:14:21.376   765  1151 E ConnectivityService: updateNetworkInfo()
08-05 14:14:21.376   765  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-05 14:14:21.376   765  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,08-05 14:14:21.386   765  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-05 14:14:21.386   765   765 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-05 14:14:21.386  1903  5073 V NativeCrypto: SSL shutdown failed: ssl=0xaf33ee00: I/O error during system call, Broken pipe
,08-05 14:14:21.386   765  1578 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.386  1196  1196 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-05 14:14:21.386  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-05 14:14:21.386  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,08-05 14:14:21.386  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:21.386  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,08-05 14:14:21.386  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:21.386  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:21.386  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:21.386  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:21.386  1196  1196 D StatusBar.NetworkController: applyOpen
,08-05 14:14:21.386   765  3410 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.396   765   765 D WifiScanningService: SCAN_AVAILABLE : 1
08-05 14:14:21.396   765   765 D RttService: SCAN_AVAILABLE : 1
,08-05 14:14:21.396   765  1167 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:21.396   765  1168 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:21.396  1903  5073 E GCM     : Wifi connection closed with errorCode 20
,08-05 14:14:21.396   765  1237 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.396   765   783 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
08-05 14:14:21.396   765  1148 D WifiP2pService: InactiveState{ what=131204 }
08-05 14:14:21.396   765  1148 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-05 14:14:21.396   765  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:21.396   765  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:21.396   765  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-05 14:14:21.396   765  1148 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-05 14:14:21.396   765  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:21.396   765  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,08-05 14:14:21.396   765  1059 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:21.396   765  1059 D WifiDisplayAdapter: onP2pDisconnected
08-05 14:14:21.396   765  1059 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-05 14:14:21.396   765  1059 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-05 14:14:21.396   765  1757 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-05 14:14:21.406   765  1148 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-05 14:14:21.406   765  1437 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.406   765   765 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-05 14:14:21.406   765  1059 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,08-05 14:14:21.406   765  1059 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-05 14:14:21.406   765  1059 D WifiDisplayController: disconnect
08-05 14:14:21.406   765  1059 D WifiDisplayController: updateConnection
08-05 14:14:21.406   765  1059 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-05 14:14:21.406   765  1059 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-05 14:14:21.406   765  1526 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:21.406   765  1148 D WifiP2pService: P2pDisablingState
,08-05 14:14:21.406   765  1148 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-05 14:14:21.406   765  1059 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-05 14:14:21.406   765  1059 D WifiDisplayAdapter: onP2pDisconnected
08-05 14:14:21.406   765  1059 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-05 14:14:21.406   765  1059 D IpRemoteDisplayController: WfdBridgeServer is already null
08-05 14:14:21.406   765  1706 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.406   765  1148 D WifiP2pService: p2p socket connection lost
,08-05 14:14:21.406   765  1148 D WifiP2pService: P2pDisabledState
,08-05 14:14:21.406  1196  1196 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-05 14:14:21.406   765   784 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-05 14:14:21.406  1196  1196 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-05 14:14:21.416   765  1149 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-05 14:14:21.416   765  1149 E native  : do suspend true
,08-05 14:14:21.416  1316  1316 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-05 14:14:21.416   765  3349 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-05 14:14:21.416   765  3349 D ActivityManager: caller:android.app.ApplicationThreadProxy@11100e4f, r.packageName :com.android.settings
,08-05 14:14:21.416   765  1148 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-05 14:14:21.426   765  1148 D WifiP2pService: DefaultState{ what=143375 }
,08-05 14:14:21.426  1196  1196 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-05 14:14:21.426  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-05 14:14:21.426   765  1322 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.436  1316  1316 D DockEventReceiver: finishStartingService: stopping service
,08-05 14:14:21.436  1316  1316 D BluetoothNotiBroadcastReceiver: onReceive
,08-05 14:14:21.446   765  1237 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-05 14:14:21.446   765  1237 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:21.446   765  1237 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:21.446   765  1237 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:21.446   765  1237 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:21.456   298  1056 D CommandListener: Clearing all IP addresses on wlan0
,08-05 14:14:21.456   765  1151 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-05 14:14:21.456   765  1151 D ConnectivityService: calling update connectivity
08-05 14:14:21.456   765  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-05 14:14:21.456   765  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-05 14:14:21.456   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:21.456   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-05 14:14:21.456   765  1151 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 14:14:21.456   765  1058 D EntConnectivity: Not allowed due to - mEnabled false
08-05 14:14:21.456   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 14:14:21.456   765  1151 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:21.456  1196  1593 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-05 14:14:21.456   765  1151 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
08-05 14:14:21.456   765  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:21.456   765  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:21.456   765  1757 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-05 14:14:21.456   765  1151 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 14:14:21.456   765  1151 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:21.456  4411  7336 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-05 14:14:21.456  1425  1425 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 14:14:21.456   765  1151 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-05 14:14:21.456   765  1151 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-05 14:14:21.456   765  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-05 14:14:21.486  7615  7615 E Zygote  : MountEmulatedStorage()
08-05 14:14:21.486  7615  7615 E Zygote  : v2
08-05 14:14:21.486  7615  7615 I libpersona: KNOX_SDCARD checking this for 10140
08-05 14:14:21.486  7615  7615 I libpersona: KNOX_SDCARD not a persona
,08-05 14:14:21.496   765  1237 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7615 uid=10140 gids={50140, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-05 14:14:21.496   765   765 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-05 14:14:21.496  7615  7615 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 14:14:21.496  1303  1303 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-05 14:14:21.496  7615  7615 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-05 14:14:21.496  7615  7615 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-05 14:14:21.496  1196  1196 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-05 14:14:21.496  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-05 14:14:21.496   765  1151 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 14:14:21.496   765  1151 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-05 14:14:21.496   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-05 14:14:21.496   765  1152 D Tethering: MasterInitialState.processMessage what=3
,08-05 14:14:21.496  3004  3149 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-05 14:14:21.496  3004  3151 D bt_vendor: op for 6
,08-05 14:14:21.496   765  1151 E ConnectivityService: updateNetworkInfo()
08-05 14:14:21.496   765  1151 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 14:14:21.496   765  1151 E ConnectivityService: updateNetworkInfo()
08-05 14:14:21.496   765  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
08-05 14:14:21.496  3004  3151 D bt_vendor: op for 7
08-05 14:14:21.496   765  1151 E ConnectivityService: EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-05 14:14:21.506  3004  3149 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 14:14:21.506  3004  3151 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:21.506  3004  3149 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 14:14:21.506   765  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
08-05 14:14:21.506  3004  3152 D bt_userial: RX termination
08-05 14:14:21.506  3004  3152 W bt_userial: select_read return size <=0:-1, exiting userial_read_thread
08-05 14:14:21.506  3004  3152 D bt_userial: Leaving userial_read_thread()
08-05 14:14:21.506   765  1153 D SmartBondingService: getSBEnabled() enabled =false
08-05 14:14:21.506  3004  3071 D bt_userial: userial_close_reader Joined userial reader thread: 0
08-05 14:14:21.506   765  1153 D SmartBondingService: getSBEnabled() enabled =false
08-05 14:14:21.506  3004  3151 D bt_vendor: op for 9
08-05 14:14:21.506   765  1153 D SmartBondingService: getSBEnabled() enabled =false
08-05 14:14:21.506  3004  3151 D bt_hwcfg: hw_epilog_process
08-05 14:14:21.506  3004  3071 D bt_vendor: op for 4
08-05 14:14:21.506  3004  3071 I bt_userial_vendor: device fd = 65 close
,08-05 14:14:21.506  3004  3149 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 14:14:21.506  3004  3149 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 14:14:21.506  3004  3149 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 14:14:21.506  3004  3149 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 14:14:21.506  3004  3149 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 14:14:21.506  3004  3149 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 14:14:21.506  3004  3149 W bt-btif : ag scb idx 1 not allocated
,08-05 14:14:21.506  3004  3149 W bt-btif : ag scb idx 2 not allocated
08-05 14:14:21.506  3004  3149 E bt-btif : BTA AG is already disabled, ignoring ...
08-05 14:14:21.506   765  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,08-05 14:14:21.506   765  1146 V NetworkStats: updateIfacesLocked()
08-05 14:14:21.506   765  1146 V NetworkStats: performPollLocked(flags=0x1)
,08-05 14:14:21.506  3004  3071 D bt_vendor: op for 0
08-05 14:14:21.506  3004  3071 D bt_upio : upio_set_bluetooth_power(on: 0)
08-05 14:14:21.506  3004  3071 D bt_upio : is_emulator_context : 0
08-05 14:14:21.506  3004  3071 D bt_upio : is_rfkill_disabled ? [0]
,08-05 14:14:21.506   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 14:14:21.506  3004  3071 D bt_vendor: cleanup
,08-05 14:14:21.506  3004  3149 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-05 14:14:21.506   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 14:14:21.506   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:21.506   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 14:14:21.506   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 14:14:21.506   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 14:14:21.506   765  1147 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-05 14:14:21.506   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-05 14:14:21.506   765  1149 D SecContentProvider2: mCursor = null
08-05 14:14:21.506  3004  3071 I GKI_LINUX: GKI_exit_task 0 done
08-05 14:14:21.506  3004  3071 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-05 14:14:21.506  3004  3068 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-05 14:14:21.506  1196  1196 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-05 14:14:21.506  1196  1196 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-05 14:14:21.506   765  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
08-05 14:14:21.506  1196  1196 D StatusBar.NetworkController: updateDataNetType()
08-05 14:14:21.506  1196  1196 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-05 14:14:21.506  1196  1196 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-05 14:14:21.506  3004  3068 D BtConfig.SecureMode: isSecureModeOn:false
08-05 14:14:21.506  3004  3068 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
,08-05 14:14:21.516  3004  3068 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-05 14:14:21.516  3004  3068 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-05 14:14:21.516   765  1146 D NetworkStatsFactory: UpdateStatsForKnox
,08-05 14:14:21.516   765  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.516  1316  1316 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-05 14:14:21.516  3004  3068 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-05 14:14:21.516   765  1467 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-05 14:14:21.516   765  1467 D ActivityManager: caller:android.app.ApplicationThreadProxy@280b7ae5, r.packageName :com.android.bluetooth
08-05 14:14:21.516  3004  3068 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-05 14:14:21.516  3004  3068 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-05 14:14:21.516  3004  3004 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-05 14:14:21.516  3004  3004 D BtGatt.GattService: Received stop request...Stopping profile...
08-05 14:14:21.516  3004  3004 D BtGatt.GattService: stop()
08-05 14:14:21.516  3004  3004 D BtGatt.AdvertiseManager: advertise clients cleared
,08-05 14:14:21.516  3004  3068 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-05 14:14:21.516   765  3349 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:21.516   765  3349 D ActivityManager: caller:android.app.ApplicationThreadProxy@3e7349ba, r.packageName :com.android.bluetooth
08-05 14:14:21.516  7501  7501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:21.516  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:21.516  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:21.516  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:21.516  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 14:14:21.516  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 14:14:21.516  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:21.516  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:21.516  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 14:14:21.516  1196  1196 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-05 14:14:21.516  1196  1196 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-05 14:14:21.516  3004  3068 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-05 14:14:21.516  3004  3068 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-05 14:14:21.526  1196  1196 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-05 14:14:21.526  3004  3004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eea3460
08-05 14:14:21.526  1196  1196 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-05 14:14:21.526  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-05 14:14:21.526  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:21.526  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:21.526  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:21.526  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:21.526  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:21.526  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:21.526  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:21.526  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:21.526  3004  3068 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-05 14:14:21.526  1196  1196 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-05 14:14:21.526  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-05 14:14:21.526  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:21.526  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:21.526  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:21.526  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:21.526  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:21.526  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:21.526  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:21.526  7501  7501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:21.526  1196  1196 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:21.526  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:21.526  7501  7501 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:21.526  1196  1196 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:21.526  1196  1196 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-05 14:14:21.526  1196  1597 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-05 14:14:21.526   765  1146 V NetworkStats: performPollLocked() took 17ms
08-05 14:14:21.526   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 14:14:21.526   765  1526 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:21.526   765  1526 D ActivityManager: caller:android.app.ApplicationThreadProxy@3769406b, r.packageName :com.android.bluetooth
08-05 14:14:21.526  3004  3068 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-05 14:14:21.526  3004  3068 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-05 14:14:21.526  3004  3004 D HeadsetService: Received stop request...Stopping profile...
08-05 14:14:21.526  3004  3004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eea3460
08-05 14:14:21.526   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 14:14:21.526   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 14:14:21.526  1316  1316 D HeadsetProfile: Bluetooth service disconnected
08-05 14:14:21.526  1196  1196 D HotspotTile: onReceive : 0, 0
08-05 14:14:21.526  3004  3068 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-05 14:14:21.526  7501  7501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:21.526  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:21.526  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:21.526  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:21.526  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 14:14:21.526  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 14:14:21.526  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:21.526  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:21.526  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 14:14:21.526   765  3410 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:21.526   765  3410 D ActivityManager: caller:android.app.ApplicationThreadProxy@273337c8, r.packageName :com.android.bluetooth
08-05 14:14:21.526   765   765 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-05 14:14:21.526  7501  7501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:21.526  7501  7501 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:21.526  3004  3068 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-05 14:14:21.526  3004  3068 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-05 14:14:21.526   765   784 I AudioService: getStreamVolume 3 index 0
08-05 14:14:21.536  3004  3068 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-05 14:14:21.536  7615  7615 D TimaKeyStoreProvider: TimaSignature is unavailable
08-05 14:14:21.536   765   783 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:21.536  7615  7615 D ActivityThread: Added TimaKeyStore provider
08-05 14:14:21.536   765   783 D ActivityManager: caller:android.app.ApplicationThreadProxy@387de061, r.packageName :com.android.bluetooth
08-05 14:14:21.536  3004  3068 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-05 14:14:21.536  3004  3068 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-05 14:14:21.536  3004  3068 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-05 14:14:21.536   765  1677 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:21.536   765  1677 D ActivityManager: caller:android.app.ApplicationThreadProxy@13fc4786, r.packageName :com.android.bluetooth
08-05 14:14:21.536  3004  3068 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-05 14:14:21.536  3004  3068 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-05 14:14:21.546  3004  3068 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-05 14:14:21.546   765  1437 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:21.546   765  1437 D ActivityManager: caller:android.app.ApplicationThreadProxy@37d97847, r.packageName :com.android.bluetooth
08-05 14:14:21.546  3004  3068 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-05 14:14:21.546  3004  3068 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-05 14:14:21.546  3004  3068 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-05 14:14:21.546  7615  7615 D ResourcesManager: creating new AssetManager and set to /system/app/Maps/Maps.apk
08-05 14:14:21.546   765  3349 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:21.546  1303  1303 I wpa_supplicant: Blacklist: Clear (all) 
08-05 14:14:21.546   765  3349 D ActivityManager: caller:android.app.ApplicationThreadProxy@18280874, r.packageName :com.android.bluetooth
08-05 14:14:21.546  3004  3068 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-05 14:14:21.546  3004  3068 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-05 14:14:21.556   765  3081 D SSRM:n  : SIOP:: AP = 370, PST = 321, CUR = 450
08-05 14:14:21.556  3004  3068 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-05 14:14:21.556  3004  3068 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-05 14:14:21.556  3004  3068 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-05 14:14:21.556  3004  3068 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-05 14:14:21.556  3004  3068 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-05 14:14:21.556  3004  3068 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-05 14:14:21.556  3004  3068 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-05 14:14:21.556  3004  3068 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-05 14:14:21.556  3004  3068 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-05 14:14:21.556  3004  3068 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-05 14:14:21.556  3004  3004 E BluetoothAdapterService(518665312): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-05 14:14:21.556  3004  3068 D BluetoothAdapterState: Stopping profile services that were post enabled
08-05 14:14:21.556  3004  3004 D A2dpService: Received stop request...Stopping profile...
08-05 14:14:21.556  3004  3004 V Avrcp   : doQuit
08-05 14:14:21.556  3004  3078 D A2dpStateMachine: Exit Disconnected: -1
,08-05 14:14:21.556  3004  3004 D Avrcp   : Unregistering previous receiver
08-05 14:14:21.556  3004  3004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eea3460
08-05 14:14:21.556   765   765 D BluetoothA2dp: Proxy object disconnected
08-05 14:14:21.556   765   765 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-05 14:14:21.556  3178  3178 D BluetoothA2dp: Proxy object disconnected
08-05 14:14:21.556  3004  3004 E BluetoothAdapterService(518665312): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-05 14:14:21.556  3004  3004 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-05 14:14:21.556  3004  3004 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-05 14:14:21.556  1316  1316 D BluetoothA2dp: Proxy object disconnected
08-05 14:14:21.556  1316  1316 D A2dpProfile: Bluetooth service disconnected
08-05 14:14:21.556  3004  3004 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-05 14:14:21.556  3004  3004 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 14:14:21.556  3004  3004 D HidService: Received stop request...Stopping profile...
08-05 14:14:21.556  3004  3004 D HidService: Stopping Bluetooth HidService
08-05 14:14:21.556  3004  3004 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-05 14:14:21.556  3004  3004 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-05 14:14:21.556  3004  3004 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-05 14:14:21.556  3004  3004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eea3460
08-05 14:14:21.556  3004  3004 D HealthService: Received stop request...Stopping profile...
08-05 14:14:21.556  3004  3004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eea3460
08-05 14:14:21.556  1316  1316 D BluetoothInputDevice: Proxy object disconnected
08-05 14:14:21.556  1316  1316 D HidProfile: Bluetooth service disconnected
08-05 14:14:21.566  3004  3004 D PanService: Received stop request...Stopping profile...
08-05 14:14:21.566  3004  3004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eea3460
08-05 14:14:21.566   765   765 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-05 14:14:21.566  3004  3004 D BluetoothMapService: Received stop request...Stopping profile...
08-05 14:14:21.566  1316  1316 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-05 14:14:21.566  1316  1316 D PanProfile: Bluetooth service disconnected
08-05 14:14:21.566  3004  3004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eea3460
08-05 14:14:21.566  1316  1316 D BluetoothMap: Proxy object disconnected
08-05 14:14:21.566  1316  1316 D MapProfile: Bluetooth service disconnected
08-05 14:14:21.566  3004  3004 D SapService: Received stop request...Stopping profile...
08-05 14:14:21.566  3004  3004 D SapService: Stopping Bluetooth SapService
08-05 14:14:21.566  3004  3004 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eea3460
08-05 14:14:21.566  3004  3004 E BluetoothAdapterService(518665312): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-05 14:14:21.566  3004  3004 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-05 14:14:21.566  3004  3004 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-05 14:14:21.566  3004  3004 D BluetoothA2dp: Proxy object disconnected
08-05 14:14:21.566  3004  3004 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-05 14:14:21.566  3004  3079 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-05 14:14:21.566  1316  1316 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-05 14:14:21.566  3004  3004 I GKI_LINUX: GKI_exit_task 2 done
08-05 14:14:21.566  3004  3004 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-05 14:14:21.566  3004  3004 V Avrcp   : cleanup
08-05 14:14:21.566  1316  1316 D SapProfile: Bluetooth service disconnected
08-05 14:14:21.566  3004  3004 E BluetoothAdapterService(518665312): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-05 14:14:21.566  3004  3004 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-05 14:14:21.566  3004  3004 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-05 14:14:21.566  3004  3004 E BluetoothAdapterService(518665312): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-05 14:14:21.566  3004  3004 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-05 14:14:21.566  3004  3004 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-05 14:14:21.566  3004  3004 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-05 14:14:21.566  3004  3004 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 14:14:21.566  3004  3004 E BluetoothAdapterService(518665312): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-05 14:14:21.566  3004  3004 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-05 14:14:21.566  3004  3004 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-05 14:14:21.566  3004  3004 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-05 14:14:21.566  3004  3004 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-05 14:14:21.576  3004  3004 E BluetoothAdapterService(518665312): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-05 14:14:21.576  3004  3004 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-05 14:14:21.576  3004  3004 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-05 14:14:21.576  3004  3004 E BluetoothAdapterService(518665312): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-05 14:14:21.576  3004  3004 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-05 14:14:21.576  3004  3068 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-05 14:14:21.576  3004  3004 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-05 14:14:21.576  3004  3068 D BluetoothAdapterProperties: Setting state to 10
08-05 14:14:21.576  3004  3068 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-05 14:14:21.576  3004  3068 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-05 14:14:21.576  3004  3068 D BluetoothAdapterService: updateAdapterState state is 10
08-05 14:14:21.576  1316  1332 D BluetoothPbap: onBluetoothStateChange: up=false
08-05 14:14:21.576  3004  3068 D BluetoothAdapterService: Autoconnection is available 
08-05 14:14:21.576  3004  3068 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-05 14:14:21.576  3004  3068 I BluetoothAdapterState: Entering OffState
08-05 14:14:21.576  1316  3348 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-05 14:14:21.576  1316  1329 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 14:14:21.576  3178  3187 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 14:14:21.576  1316  3348 D Bluetoothsap: onBluetoothStateChange: up=false
08-05 14:14:21.576  1316  3348 D Bluetoothsap: Unbinding service...
08-05 14:14:21.576   765  1058 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 14:14:21.576  1316  1332 D BluetoothMap: onBluetoothStateChange: up=false
08-05 14:14:21.576  3004  3019 D BluetoothA2dp: onBluetoothStateChange: up=false
08-05 14:14:21.586  1303  1303 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-05 14:14:21.586   765  1058 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 12 receivers.
08-05 14:14:21.586  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-05 14:14:21.586  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-05 14:14:21.586   765  1058 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-05 14:14:21.586  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-05 14:14:21.596   765   765 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:21.596   765   765 I InputMethodManagerService: [BT Setting State] State =10
08-05 14:14:21.596   765   765 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-05 14:14:21.596  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-05 14:14:21.596  1196  1196 D BluetoothAdapter: 972163852: getState() :  mService = null. Returning STATE_OFF
,08-05 14:14:21.596  1196  1196 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-05 14:14:21.596  1196  1196 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:21.596  1739  1739 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-05 14:14:21.596  1196  1597 D BluetoothAdapter: 972163852: getState() :  mService = null. Returning STATE_OFF
,08-05 14:14:21.596  1303  1303 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-05 14:14:21.596   765  1677 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-05 14:14:21.596   765  1677 D ActivityManager: caller:android.app.ApplicationThreadProxy@3957219d, r.packageName :com.google.android.gms
08-05 14:14:21.596  1303  1303 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-05 14:14:21.596  1303  1303 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=0 BSSID=F4.99.3E SSID=4E47373030
08-05 14:14:21.596  1303  1303 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-05 14:14:21.596  1196  1597 D BluetoothAdapter: 972163852: getState() :  mService = null. Returning STATE_OFF
08-05 14:14:21.596  1196  1196 D BluetoothAdapter: 972163852: getState() :  mService = null. Returning STATE_OFF
08-05 14:14:21.596  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:21.596  1196  1597 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-05 14:14:21.596  1196  1196 D BluetoothAdapter: 972163852: getState() :  mService = null. Returning STATE_OFF
08-05 14:14:21.596  1316  1316 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:21.596   765  1289 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,08-05 14:14:21.596   765  1706 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-05 14:14:21.596  1903  2407 D BluetoothAdapter: 349785975: getState() :  mService = null. Returning STATE_OFF
08-05 14:14:21.596  1903  2407 D BluetoothAdapter: 349785975: getState() :  mService = null. Returning STATE_OFF
,08-05 14:14:21.596  1196  1196 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
08-05 14:14:21.596  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:21.596  3004  3071 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-05 14:14:21.606  3004  3004 I GKI_LINUX: GKI_exit_task 1 done
08-05 14:14:21.606  3004  3004 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-05 14:14:21.606  3004  3004 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-05 14:14:21.606  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-05 14:14:21.606  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-05 14:14:21.606  3004  3004 I art     : System.exit called, status: 0
08-05 14:14:21.606  3004  3004 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-05 14:14:21.616  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-05 14:14:21.616  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-05 14:14:21.626  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-05 14:14:21.626  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-05 14:14:21.626  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-05 14:14:21.636  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-05 14:14:21.636  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-05 14:14:21.636  1425  1425 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-05 14:14:21.666   765  1322 I ActivityManager: Process com.android.bluetooth (pid 3004)(adj 0) has died(191,1576)
,08-05 14:14:21.686  1303  1303 I wpa_supplicant: Blacklist: Clear (all) 
,08-05 14:14:21.726  7501  7501 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-05 14:14:21.796   765  1452 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,08-05 14:14:21.796  1903  1903 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-05 14:14:21.796  1903  1903 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-05 14:14:21.816   765  1152 D Tethering: InitialState.processMessage what=4
08-05 14:14:21.816  1303  1303 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-05 14:14:21.816   765  1152 E Tethering: No numeric data
08-05 14:14:21.816   765  1152 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-05 14:14:21.816   765  1146 V NetworkStats: performPollLocked(flags=0x1)
08-05 14:14:21.816   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 14:14:21.816   765  1146 D NetworkStatsFactory: UpdateStatsForKnox
08-05 14:14:21.816  1196  1196 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-05 14:14:21.816  1196  1196 D HotspotTile: updateTetherState():false, false
,08-05 14:14:21.816   765  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:21.816   765  1146 V NetworkStats: performPollLocked() took 4ms
,08-05 14:14:21.816   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 14:14:21.826   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 14:14:21.826   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 14:14:21.826  7615  7615 D StrictMode: StrictMode policy violation; ~duration=186 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-05 14:14:21.826  7615  7615 D StrictMode: StrictMode policy violation; ~duration=175 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-05 14:14:21.826  7615  7615 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at java.io.File.exists(File.java:363)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1319)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.ActivityTh,read.main(ActivityThread.java:5938)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-05 14:14:21.826  7615  7615 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-05 14:14:21.826  7615  7615 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-05 14:14:21.836  7615  7615 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-05 14:14:21.836  7615  7615 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.r.e.b(PG:170)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-05 14:14:21.836  7615  7615 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.r.k.b(PG:14147)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.r.k.c(PG:583)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.r.e.b(PG:170)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-05 14:14:21.836  7615  7615 D StrictMode: StrictMode policy violation; ~duration=100 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at java.io.File.exists(File.java:363)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1485)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-05 14:14:21.836  7615  7615 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-05 14:14:21.836   765  1706 I ActivityManager: Killing 6692:com.sec.esdk.elm/u0a116 (adj 15): emptyCount ##41
08-05 14:14:21.836  1903  1903 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-05 14:14:21.836  1903  1903 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-05 14:14:21.836   765  1526 D ActivityManager: startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
08-05 14:14:21.846   765  1526 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:21.846   765  1526 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:21.846   765  1526 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:21.846   765  1526 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:21.876  7615  7654 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-05 14:14:21.886  7661  7661 E Zygote  : MountEmulatedStorage()
08-05 14:14:21.886  7661  7661 E Zygote  : v2
08-05 14:14:21.886  7661  7661 I libpersona: KNOX_SDCARD checking this for 10038
08-05 14:14:21.886  7661  7661 I libpersona: KNOX_SDCARD not a persona
08-05 14:14:21.896  7661  7661 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 14:14:21.896  7661  7661 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-05 14:14:21.896  7661  7661 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-05 14:14:21.896   765  1526 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7661 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-05 14:14:21.916  7661  7661 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:14:21.916  7661  7661 D ActivityThread: Added TimaKeyStore provider
,08-05 14:14:21.916   765  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-05 14:14:21.916   765  1149 D WifiNative-HAL: callSECApiBoolean - ID [21]
,08-05 14:14:21.916   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,08-05 14:14:21.926  1196  1196 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-05 14:14:21.926  1316  1316 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-05 14:14:21.926  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-05 14:14:21.926  1903  2407 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-05 14:14:21.926  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:21.926  1196  1196 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:21.926  1196  1196 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-05 14:14:21.926  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:21.926  1196  1196 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:21.926  1196  1597 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-05 14:14:21.926  1196  1196 D HotspotTile: onReceive : 1, 0
,08-05 14:14:21.996   765  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 14:14:21.996   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 14:14:21.996   765   765 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:22.006   765   765 I ApplicationPolicy: updateDataUsageMap
,08-05 14:14:22.006   765   988 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-05 14:14:22.006   765   988 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:22.006   765  1677 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:22.006  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:22.006  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:22.006  1480  1480 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-05 14:14:22.006   765  1677 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:22.016   765  1467 I art     : Explicit concurrent mark sweep GC freed 88756(5MB) AllocSpace objects, 89(1425KB) LOS objects, 29% free, 37MB/53MB, paused 1.379ms total 123.617ms
,08-05 14:14:22.016   765  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
08-05 14:14:22.016   765  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
08-05 14:14:22.016   765  1153 D SmartBondingService: getSBEnabled() enabled =false
08-05 14:14:22.016   765  1153 D SmartBondingService: getSBEnabled() enabled =false
08-05 14:14:22.016   765  1153 D SmartBondingService: getSBEnabled() enabled =false
,08-05 14:14:22.026   765  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,08-05 14:14:22.036  7661  7661 D ResourcesManager: creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,08-05 14:14:22.036  7661  7661 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,08-05 14:14:22.126   765  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-05 14:14:22.156  7661  7661 I VlingoApplication: VlingoApplication appVersion ='11.2.2.0.37791', ro.csc.sales_code=XEO
,08-05 14:14:22.226  7661  7661 D BluetoothAdapter: 451743810: getState() :  mService = null. Returning STATE_OFF
,08-05 14:14:22.226  7661  7661 D BluetoothAdapter: 451743810: getState() :  mService = null. Returning STATE_OFF
08-05 14:14:22.226  7661  7661 D BluetoothAdapter: 451743810: getState() :  mService = null. Returning STATE_OFF
,08-05 14:14:22.226  7661  7661 D BluetoothAdapter: 451743810: getState() :  mService = null. Returning STATE_OFF
08-05 14:14:22.226  7661  7661 D BluetoothAdapter: 451743810: getState() :  mService = null. Returning STATE_OFF
08-05 14:14:22.226  7661  7661 D BluetoothAdapter: 451743810: getState() :  mService = null. Returning STATE_OFF
,08-05 14:14:22.256  7661  7661 E BluetoothHeadset: BTStateChangeCB is registed
,08-05 14:14:22.256   765  1647 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-05 14:14:22.256  7661  7661 E BluetoothHeadset: BluetoothHeadset service is binded
,08-05 14:14:22.266   765  3410 I ActivityManager: Killing 5726:com.android.calendar/u0a172 (adj 15): emptyCount ##41
,08-05 14:14:22.266  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-05 14:14:22.266   765  1706 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:22.266  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-05 14:14:22.266  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-05 14:14:22.266   765  1467 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-05 14:14:22.266  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-05 14:14:22.266  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-05 14:14:22.266  1316  1316 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-05 14:14:22.266  1316  2693 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-05 14:14:22.276   765  1144 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:22.276  7037  7037 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-05 14:14:22.276   765  1322 D SettingsProvider: name = driving_mode_on
,08-05 14:14:22.276   765  1322 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:22.276   765  1322 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:22.276   765  1322 D SettingsProvider: selectionArgs: false
08-05 14:14:22.276   765  1322 D SettingsProvider: selectionArgs: 10038
08-05 14:14:22.276   765  1322 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:22.276   765  1322 D SettingsProvider: ret = -1
,08-05 14:14:22.286  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-05 14:14:22.286  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-05 14:14:22.286  7661  7661 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
08-05 14:14:22.286   765  1467 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:22.286  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-05 14:14:22.286   765  1526 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-05 14:14:22.286  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-05 14:14:22.286  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-05 14:14:22.286  1316  1316 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-05 14:14:22.286  1316  2693 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-05 14:14:22.286  7144  7144 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-05 14:14:22.296   765  1289 D ActivityManager: startProcessLocked calleePkgName: com.samsung.shareshot, hostingType: broadcast
,08-05 14:14:22.296   765  1289 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:22.296   765  1289 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:22.296   765  1289 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:22.296   765  1289 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:22.376  7686  7686 E Zygote  : MountEmulatedStorage()
08-05 14:14:22.376  7686  7686 E Zygote  : v2
08-05 14:14:22.376  7686  7686 I libpersona: KNOX_SDCARD checking this for 10192
08-05 14:14:22.376  7686  7686 I libpersona: KNOX_SDCARD not a persona
,08-05 14:14:22.386  7686  7686 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,08-05 14:14:22.386  7686  7686 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-05 14:14:22.386   765  1289 I ActivityManager: Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=7686 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-05 14:14:22.386  7686  7686 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-05 14:14:22.396   337   337 I art     : Explicit concurrent mark sweep GC freed 8756(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 305us total 13.095ms
,08-05 14:14:22.406   337   337 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 279us total 9.718ms
,08-05 14:14:22.416  7686  7686 D TimaKeyStoreProvider: TimaSignature is unavailable
08-05 14:14:22.416  7686  7686 D ActivityThread: Added TimaKeyStore provider
,08-05 14:14:22.416   337   337 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 278us total 9.702ms
,08-05 14:14:22.436  7686  7686 D ResourcesManager: creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,08-05 14:14:22.446  7686  7686 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-05 14:14:22.456  7686  7686 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,08-05 14:14:22.456  7686  7686 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,08-05 14:14:22.456  7686  7686 D WifiDirectBR: stopServiceTest : false
,08-05 14:14:22.456  7686  7686 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,08-05 14:14:22.456   765  3349 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-05 14:14:22.456   765  3349 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:22.456   765  3349 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:22.456   765  3349 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:22.456   765  3349 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:22.506  7702  7702 E Zygote  : MountEmulatedStorage()
08-05 14:14:22.506  7702  7702 E Zygote  : v2
08-05 14:14:22.506  7702  7702 I libpersona: KNOX_SDCARD checking this for 10131
08-05 14:14:22.506  7702  7702 I libpersona: KNOX_SDCARD not a persona
,08-05 14:14:22.506   765  3349 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7702 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-05 14:14:22.516   765  3349 I ActivityManager: Killing 6728:com.qualcomm.timeservice/1000 (adj 15): emptyCount ##41
,08-05 14:14:22.546  7702  7702 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1,
08-05 14:14:22.546  7702  7702 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-05 14:14:22.546  7702  7702 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-05 14:14:22.566  7702  7702 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:14:22.566  7702  7702 D ActivityThread: Added TimaKeyStore provider
,08-05 14:14:22.586  7702  7702 D ResourcesManager: creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,08-05 14:14:22.596  7702  7702 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-05 14:14:22.766  7702  7729 I Babel   : MmsConfig: mnc/mcc: 0/0
08-05 14:14:22.766  7702  7729 I Babel   : MmsConfig.loadMmsSettings
,08-05 14:14:22.766  7702  7729 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
08-05 14:14:22.766  7702  7729 I Babel   : MmsConfig.loadFromDatabase
,08-05 14:14:22.766  7702  7702 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,08-05 14:14:22.766  7702  7729 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,08-05 14:14:22.766  7702  7729 I Babel   : MmsConfig.loadFromResources
,08-05 14:14:22.776  7702  7729 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,08-05 14:14:22.776  7702  7729 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
,08-05 14:14:22.786   765  3410 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-05 14:14:22.786  7702  7702 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 14:14:22.826  7702  7702 I Babel_StickerModule: App launched.
,08-05 14:14:22.826  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-05 14:14:22.826  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-05 14:14:22.836   765  1578 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:22.836  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-05 14:14:22.846   765  1237 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-05 14:14:22.846  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-05 14:14:22.846  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-05 14:14:22.846  1316  1316 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-05 14:14:22.846  1316  2693 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-05 14:14:22.846   765  3349 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:22.846  7037  7037 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-05 14:14:22.856   313   696 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,08-05 14:14:22.856   313   696 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
08-05 14:14:22.856   313   696 W QCamera2Factory: getCameraInfo: X
,08-05 14:14:22.866  7037  7037 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-05 14:14:22.866   313  1159 W QCamera2Factory: getCameraInfo: E, camera_id = 1
08-05 14:14:22.866   313  1159 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
08-05 14:14:22.866   313  1159 W QCamera2HWI: __dbg: info->orientation : 270 rc = 0
08-05 14:14:22.866   313  1159 W QCamera2Factory: getCameraInfo: X
,08-05 14:14:22.866   765  1706 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:22.866  6711  6711 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-05 14:14:22.866  6711  6711 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-05 14:14:22.866  6711  6711 D SecurityLogAgent: StateMachine : Current State = 1
,08-05 14:14:22.866  6711  6711 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-05 14:14:22.876  1316  1316 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-05 14:14:22.876   765  1237 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-05 14:14:22.876   765  1237 D ActivityManager: caller:android.app.ApplicationThreadProxy@19366f96, r.packageName :com.android.settings
,08-05 14:14:22.876  7702  7702 W AudioCapabilities: Unsupported mime audio/evrc
,08-05 14:14:22.886  7702  7702 W AudioCapabilities: Unsupported mime audio/qcelp
,08-05 14:14:22.886  7702  7702 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-05 14:14:22.886  7702  7702 W AudioCapabilities: Unsupported mime audio/mpeg-L1
08-05 14:14:22.886  7702  7702 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-05 14:14:22.896  1316  1316 D DockEventReceiver: finishStartingService: stopping service
,08-05 14:14:22.896  1316  1316 D BluetoothNotiBroadcastReceiver: onReceive
,08-05 14:14:22.896   765  1677 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-05 14:14:22.896   765  1677 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:22.896   765  1677 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:22.896  7702  7702 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-05 14:14:22.896   765  1677 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:22.896   765  1677 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:22.896  7702  7702 W AudioCapabilities: Unsupported mime audio/x-ima
,08-05 14:14:22.896  7702  7702 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-05 14:14:22.896  7702  7702 W AudioCapabilities: Unsupported mime audio/qcelp
,08-05 14:14:22.896  7702  7702 W AudioCapabilities: Unsupported mime audio/evrc
,08-05 14:14:22.906  7702  7702 W VideoCapabilities: Unsupported mime video/wvc1
,08-05 14:14:22.906  7702  7702 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-05 14:14:22.926  7702  7702 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-05 14:14:22.926  7702  7702 W VideoCapabilities: Unsupported mime video/wvc1
,08-05 14:14:22.926  7702  7702 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-05 14:14:22.926  7702  7702 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-05 14:14:22.936  7741  7741 E Zygote  : MountEmulatedStorage()
08-05 14:14:22.936  7741  7741 E Zygote  : v2
08-05 14:14:22.936  7741  7741 I libpersona: KNOX_SDCARD checking this for 1002
08-05 14:14:22.936  7741  7741 I libpersona: KNOX_SDCARD not a persona
,08-05 14:14:22.936   765  1677 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7741 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-05 14:14:22.966  7741  7741 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 14:14:22.966  7702  7702 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-05 14:14:22.966  7741  7741 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-05 14:14:22.966  7741  7741 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-05 14:14:22.966  7702  7702 W VideoCapabilities: Unsupported mime video/mp43
,08-05 14:14:22.966  7702  7702 W VideoCapabilities: Unsupported mime video/sorenson
,08-05 14:14:22.976  7702  7702 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-05 14:14:22.986  7741  7741 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:14:22.986  7741  7741 D ActivityThread: Added TimaKeyStore provider
,08-05 14:14:22.996  7741  7741 D ResourcesManager: creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,08-05 14:14:22.996  7741  7741 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-05 14:14:23.006  7741  7741 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-05 14:14:23.006  7702  7702 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-05 14:14:23.026  7741  7741 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-05 14:14:23.026   765  1677 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,08-05 14:14:23.036   765  1706 I ActivityManager: Killing 6506:com.android.defcontainer/u0a7 (adj 15): emptyCount ##41
,08-05 14:14:23.056  7741  7741 D BtSettings.ProfileConfig: Adding GattService
,08-05 14:14:23.056  7741  7741 D BtSettings.ProfileConfig: Adding HeadsetService
08-05 14:14:23.056  7741  7741 D BtSettings.ProfileConfig: Adding A2dpService
08-05 14:14:23.056  7741  7741 D BtSettings.ProfileConfig: Adding HidService
,08-05 14:14:23.056  7741  7741 D BtSettings.ProfileConfig: Adding HealthService
08-05 14:14:23.056  7741  7741 D BtSettings.ProfileConfig: Adding PanService
08-05 14:14:23.056  7741  7741 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-05 14:14:23.056  7741  7741 D BtSettings.ProfileConfig: Adding SapService
08-05 14:14:23.056  7741  7741 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-05 14:14:23.056  7741  7741 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-05 14:14:23.056  7741  7741 D BtSettings.ProfileConfig: Adding SapClientService
08-05 14:14:23.056  7741  7741 D BtSettings.ProfileConfig: Adding HidDevService
,08-05 14:14:23.056  7741  7741 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-05 14:14:23.056   765  1467 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
08-05 14:14:23.056   765  1467 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:23.056   765  1467 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:23.056   765  1467 D SettingsProvider: selectionArgs: false
08-05 14:14:23.056   765  1467 D SettingsProvider: selectionArgs: 1002
08-05 14:14:23.056   765  1467 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:23.056   765  1467 D SettingsProvider: ret = -1
,08-05 14:14:23.056   765  1452 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-05 14:14:23.056   765  1452 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:23.056   765  1452 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:23.056   765  1452 D SettingsProvider: selectionArgs: false
08-05 14:14:23.056   765  1452 D SettingsProvider: selectionArgs: 1002
08-05 14:14:23.056   765  1452 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:23.056   765  1452 D SettingsProvider: ret = -1
,08-05 14:14:23.056   765  1237 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-05 14:14:23.056   765  1237 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:23.056   765  1237 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:23.056   765  1237 D SettingsProvider: selectionArgs: false
08-05 14:14:23.056   765  1237 D SettingsProvider: selectionArgs: 1002
08-05 14:14:23.056   765  1237 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:23.056   765  1237 D SettingsProvider: ret = -1
,08-05 14:14:23.066   765  1647 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-05 14:14:23.066   765  1647 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:23.066   765  1647 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:23.066   765  1647 D SettingsProvider: selectionArgs: false
08-05 14:14:23.066   765  1647 D SettingsProvider: selectionArgs: 1002
08-05 14:14:23.066   765  1647 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:23.066   765  1647 D SettingsProvider: ret = -1
,08-05 14:14:23.066   765  1289 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-05 14:14:23.066   765  1289 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:23.066   765  1289 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:23.066   765  1289 D SettingsProvider: selectionArgs: false
08-05 14:14:23.066   765  1289 D SettingsProvider: selectionArgs: 1002
08-05 14:14:23.066   765  1289 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:23.066   765  1289 D SettingsProvider: ret = -1
,08-05 14:14:23.066   765  3349 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-05 14:14:23.066   765  3349 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:23.066   765  3349 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:23.066   765  3349 D SettingsProvider: selectionArgs: false
08-05 14:14:23.066   765  3349 D SettingsProvider: selectionArgs: 1002
08-05 14:14:23.066   765  3349 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:23.066   765  3349 D SettingsProvider: ret = -1
,08-05 14:14:23.066   765  1526 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-05 14:14:23.066   765  1526 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:23.066   765  1526 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:23.066   765  1526 D SettingsProvider: selectionArgs: false
08-05 14:14:23.066   765  1526 D SettingsProvider: selectionArgs: 1002
08-05 14:14:23.066   765  1526 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-05 14:14:23.066   765  1526 D SettingsProvider: ret = -1
08-05 14:14:23.066   765   784 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-05 14:14:23.066   765   784 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:23.066   765   784 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:23.066   765   784 D SettingsProvider: selectionArgs: false
08-05 14:14:23.066   765   784 D SettingsProvider: selectionArgs: 1002
08-05 14:14:23.066   765   784 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:23.066   765   784 D SettingsProvider: ret = -1
,08-05 14:14:23.066   765   783 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-05 14:14:23.066   765   783 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:23.066   765   783 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:23.066   765   783 D SettingsProvider: selectionArgs: false
08-05 14:14:23.066   765   783 D SettingsProvider: selectionArgs: 1002
08-05 14:14:23.066   765   783 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:23.066   765   783 D SettingsProvider: ret = -1
,08-05 14:14:23.066   765  1322 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-05 14:14:23.066   765  1322 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:23.066   765  1322 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:23.066   765  1322 D SettingsProvider: selectionArgs: false
08-05 14:14:23.066   765  1322 D SettingsProvider: selectionArgs: 1002
08-05 14:14:23.066   765  1322 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:23.066   765  1322 D SettingsProvider: ret = -1
08-05 14:14:23.066   765  1677 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,08-05 14:14:23.066   765  1677 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:23.066   765  1677 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:23.066   765  1677 D SettingsProvider: selectionArgs: false
08-05 14:14:23.066   765  1677 D SettingsProvider: selectionArgs: 1002
08-05 14:14:23.066   765  1677 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:23.066   765  1677 D SettingsProvider: ret = -1
08-05 14:14:23.066   765  1578 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-05 14:14:23.066   765  1578 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-05 14:14:23.066   765  1578 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:23.066   765  1578 D SettingsProvider: selectionArgs: false
08-05 14:14:23.066   765  1578 D SettingsProvider: selectionArgs: 1002
08-05 14:14:23.066   765  1578 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:23.066   765  1578 D SettingsProvider: ret = -1
,08-05 14:14:23.076   765  1706 I ActivityManager: Killing 6750:com.google.android.partnersetup/u0a19 (adj 15): emptyCount ##41
,08-05 14:14:23.086  1903  1903 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-05 14:14:23.086   765  1526 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-05 14:14:23.086   765  1526 D ActivityManager: caller:android.app.ApplicationThreadProxy@15e1ef22, r.packageName :com.google.android.gms
,08-05 14:14:23.086  1903  7764 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-05 14:14:23.086  1903  1903 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-05 14:14:23.106  7037  7037 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-05 14:14:23.106   765   784 D ActivityManager: caller:android.app.ApplicationThreadProxy@2a24220f, r.packageName :com.google.android.gms
,08-05 14:14:23.116   765  3410 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:23.116  6711  6711 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-05 14:14:23.116  6711  6711 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-05 14:14:23.116  6711  6711 D SecurityLogAgent: StateMachine : Current State = 1
08-05 14:14:23.116  6711  6711 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-05 14:14:23.126  1903  7764 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-05 14:14:23.126  6803  6803 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-05 14:14:23.126  6803  6803 I PCWCLIENTTRACE_PushUtil: sales region : global
08-05 14:14:23.126  6803  6803 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-05 14:14:23.126  6803  6803 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-05 14:14:23.126  6803  6803 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-05 14:14:23.136   765  1452 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,08-05 14:14:23.136   765  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:23.136   765  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:23.136   765  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:23.136   765  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:23.156   305   305 E SMD     : DCD ON
,08-05 14:14:23.176  7766  7766 E Zygote  : MountEmulatedStorage()
,08-05 14:14:23.176  7766  7766 E Zygote  : v2
08-05 14:14:23.176  7766  7766 I libpersona: KNOX_SDCARD checking this for 10144
08-05 14:14:23.176  7766  7766 I libpersona: KNOX_SDCARD not a persona
,08-05 14:14:23.186   765  1452 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7766 uid=10144 gids={50144, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-05 14:14:23.196  7766  7766 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 14:14:23.196  7766  7766 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-05 14:14:23.196  7766  7766 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-05 14:14:23.216  7766  7766 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:14:23.216  7766  7766 D ActivityThread: Added TimaKeyStore provider
,08-05 14:14:23.226  7766  7766 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,08-05 14:14:23.316  7766  7766 I MusicStore: Database version: 108
,08-05 14:14:23.326   765  1452 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-05 14:14:23.376  7766  7766 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,08-05 14:14:23.376  7766  7766 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-05 14:14:23.376  7766  7766 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-05 14:14:23.416  7766  7766 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-05 14:14:23.456  7766  7766 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-05 14:14:23.456  7766  7766 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@a01fdb4: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-05 14:14:23.456  7766  7766 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,08-05 14:14:23.456  7766  7766 D AndroidMusic: GMSCore installation verified
,08-05 14:14:23.476   765  1237 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-05 14:14:23.486  7766  7766 I ConfigStore: Config Database version: 1
,08-05 14:14:23.536   265   557 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-05 14:14:23.536   265   557 W Vold    : Returning OperationFailed - no handler for errno 0
,08-05 14:14:23.536  7766  7766 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-05 14:14:23.546   265   557 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-05 14:14:23.546   265   557 W Vold    : Returning OperationFailed - no handler for errno 0
,08-05 14:14:23.546  7766  7766 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-05 14:14:23.546   265   557 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-05 14:14:23.546   265   557 W Vold    : Returning OperationFailed - no handler for errno 0
,08-05 14:14:23.546  7766  7766 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-05 14:14:23.556   765  1452 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-05 14:14:23.556   765  1452 D ActivityManager: caller:android.app.ApplicationThreadProxy@623fc1e, r.packageName :com.google.android.music
,08-05 14:14:23.566   765  1526 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-05 14:14:23.586   765   783 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-05 14:14:23.586   765  1647 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-05 14:14:23.596   765  1237 I AudioService: getStreamVolume 3 index 0
,08-05 14:14:23.596  7766  7766 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,08-05 14:14:23.596  7766  7766 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,08-05 14:14:23.626   765  1237 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-05 14:14:23.626   765  3349 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-05 14:14:23.636   765  1706 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-05 14:14:23.636   765   783 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-05 14:14:23.646   765  1289 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-05 14:14:23.646   765  1289 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:23.646   765  1289 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:23.646   765  1289 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:23.646   765  1289 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:23.686   765  1289 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7800 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-05 14:14:23.696  7800  7800 E Zygote  : MountEmulatedStorage()
08-05 14:14:23.696  7800  7800 I libpersona: KNOX_SDCARD checking this for 10004
08-05 14:14:23.696  7800  7800 E Zygote  : v2
08-05 14:14:23.696  7800  7800 I libpersona: KNOX_SDCARD not a persona
,08-05 14:14:23.706  7800  7800 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,08-05 14:14:23.706  7800  7800 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-05 14:14:23.716  7800  7800 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-05 14:14:23.716   765  1526 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,08-05 14:14:23.736  7766  7766 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,08-05 14:14:23.736   765  1706 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-05 14:14:23.746  7800  7800 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:14:23.746  7800  7800 D ActivityThread: Added TimaKeyStore provider
,08-05 14:14:23.766  7800  7800 D ResourcesManager: creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,08-05 14:14:23.806   765   783 I ActivityManager: Killing 6768:com.samsung.groupcast/u0a20 (adj 15): emptyCount ##41
,08-05 14:14:23.806   765  1322 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-05 14:14:23.806   765  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:23.806   765  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:23.806   765  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:23.806   765  1322 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:23.856  7823  7823 E Zygote  : MountEmulatedStorage()
08-05 14:14:23.856  7823  7823 E Zygote  : v2
08-05 14:14:23.856  7823  7823 I libpersona: KNOX_SDCARD checking this for 1000
08-05 14:14:23.856  7823  7823 I libpersona: KNOX_SDCARD not a persona
,08-05 14:14:23.866  7823  7823 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,08-05 14:14:23.866  7823  7823 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-05 14:14:23.866  7823  7823 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-05 14:14:23.866   765  1322 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7823 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-05 14:14:23.896  7823  7823 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:14:23.896  7823  7823 D ActivityThread: Added TimaKeyStore provider
,08-05 14:14:23.906  7823  7823 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,08-05 14:14:23.936  7823  7823 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,08-05 14:14:23.956  7823  7823 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,08-05 14:14:24.066  7823  7823 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,08-05 14:14:24.076  7823  7823 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,08-05 14:14:24.076  7823  7823 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-05 14:14:24.076  7823  7823 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-05 14:14:24.166   765  1237 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,08-05 14:14:24.166   765  1237 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:24.166   765  1237 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:24.166   765  1237 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:24.176   765  1237 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:24.236  7844  7844 E Zygote  : MountEmulatedStorage()
,08-05 14:14:24.236  7844  7844 E Zygote  : v2
08-05 14:14:24.236  7844  7844 I libpersona: KNOX_SDCARD checking this for 10014
08-05 14:14:24.236  7844  7844 I libpersona: KNOX_SDCARD not a persona
,08-05 14:14:24.236   765  1237 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7844 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-05 14:14:24.246  7844  7844 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,08-05 14:14:24.246  7844  7844 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-05 14:14:24.246  7844  7844 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-05 14:14:24.266  7844  7844 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:14:24.266  7844  7844 D ActivityThread: Added TimaKeyStore provider
,08-05 14:14:24.276  7844  7844 D ResourcesManager: creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,08-05 14:14:24.276  7501  7570 I WifiManager: packageName : com.test.thalitest
,08-05 14:14:24.276   765  3349 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-05 14:14:24.276   765  3349 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-05 14:14:24.276   765  3349 D SecContentProvider2: mCursor = null
,08-05 14:14:24.276   765  3349 D WifiService: setWifiEnabled: true pid=7501, uid=10079
,08-05 14:14:24.276   765  3349 W ActivityManager: Permission Denial: getCurrentUser() from pid=7501, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-05 14:14:24.276   765  3349 W WifiService: Failed getting userId using ActivityManagerNative
08-05 14:14:24.276   765  3349 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7501, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-05 14:14:24.276   765  3349 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
08-05 14:14:24.276   765  3349 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
08-05 14:14:24.276   765  3349 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
08-05 14:14:24.276   765  3349 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-05 14:14:24.276   765  3349 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-05 14:14:24.286   765  3349 D SettingsProvider: name = wifi_on
,08-05 14:14:24.286   765  1149 E WifiHW  : ##################### set firmware type 0 #####################
,08-05 14:14:24.286   298  1056 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
08-05 14:14:24.286   298  1056 I WifiHW  : module is semco
08-05 14:14:24.286   298  1056 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
08-05 14:14:24.286   298  1056 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
08-05 14:14:24.286   298  1056 E WifiHW  : TEMP_FAILURE_RETRY complete
08-05 14:14:24.286   298  1056 D SoftapController: Softap fwReload - Ok
,08-05 14:14:24.286   298  1056 D CommandListener: Setting iface cfg
08-05 14:14:24.286   298  1056 D CommandListener: Trying to bring down wlan0
,08-05 14:14:24.286   298  1056 D CommandListener: Clearing all IP addresses on wlan0
,08-05 14:14:24.296   765  1149 E WifiHW  : supplicant_name : p2p_supplicant
,08-05 14:14:24.296   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,08-05 14:14:24.296  1196  1196 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-05 14:14:24.296  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-05 14:14:24.306  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:24.306  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:24.306  1196  1196 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-05 14:14:24.306  1196  1196 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-05 14:14:24.306  1196  1196 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-05 14:14:24.306  1196  1597 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-05 14:14:24.306  1196  1196 D HotspotTile: onReceive : 2, 0
,08-05 14:14:24.306   765  1149 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-05 14:14:24.306  1316  1316 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-05 14:14:24.316   765  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,08-05 14:14:24.326  7860  7860 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-05 14:14:24.326  7860  7860 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-05 14:14:24.326  7860  7860 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-05 14:14:24.326  7860  7860 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-05 14:14:24.326   352   352 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7860
08-05 14:14:24.326   352   352 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-05 14:14:24.326  7860  7860 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-05 14:14:24.326  7860  7860 I wpa_supplicant: ssSupport state is = 1
,08-05 14:14:24.326  7860  7860 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,08-05 14:14:24.326  7860  7860 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-05 14:14:24.326   352   352 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7860
08-05 14:14:24.326   352   352 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,08-05 14:14:24.346   765   783 I ActivityManager: Killing 6786:com.sec.android.service.health/u0a21 (adj 15): emptyCount ##41
,08-05 14:14:24.356  7844  7844 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,08-05 14:14:24.366  7844  7844 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,08-05 14:14:24.376  7844  7844 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,08-05 14:14:24.386   765  1237 I ActivityManager: Killing 6825:com.sec.spp.push/u0a43 (adj 15): emptyCount ##41
,08-05 14:14:24.386  4023  4023 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-05 14:14:24.396  4023  4023 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1470399264406
,08-05 14:14:24.396  4023  4023 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,08-05 14:14:24.396   765  1647 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:24.396   765  1578 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:24.396  4023  4023 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,08-05 14:14:24.396  4023  4023 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,08-05 14:14:24.396   765   784 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.pinboard, hostingType: broadcast
,08-05 14:14:24.396   765   784 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:24.396   765   784 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:24.396   765   784 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:24.396   765   784 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:24.516  7873  7873 E Zygote  : MountEmulatedStorage()
,08-05 14:14:24.516  7873  7873 E Zygote  : v2
08-05 14:14:24.516  7873  7873 I libpersona: KNOX_SDCARD checking this for 10036
08-05 14:14:24.526  7873  7873 I libpersona: KNOX_SDCARD not a persona
,08-05 14:14:24.526   765   784 I ActivityManager: Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7873 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-05 14:14:24.566  7873  7873 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 14:14:24.566  7873  7873 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-05 14:14:24.566  7873  7873 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-05 14:14:24.586   765  1452 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-05 14:14:24.586   765  1452 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
08-05 14:14:24.586   765  1452 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
08-05 14:14:24.586   765   765 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-05 14:14:24.586   765  1452 D BatteryService: stay LED for fully charged
,08-05 14:14:24.586   765   765 I MotionRecognitionService: Plugged
08-05 14:14:24.586   765   765 I MotionRecognitionService: setPowerConnected  = true
08-05 14:14:24.586  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-05 14:14:24.586  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,08-05 14:14:24.586  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-05 14:14:24.586  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
08-05 14:14:24.586  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-05 14:14:24.586  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-05 14:14:24.596  7873  7873 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:14:24.596  7873  7873 D ActivityThread: Added TimaKeyStore provider
,08-05 14:14:24.596   352   352 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-05 14:14:24.606  7873  7873 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,08-05 14:14:24.606  7873  7873 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-05 14:14:24.606  7873  7873 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-05 14:14:24.626  7873  7873 E Minikin : addFont failed to create font /system/fonts/SamsungSans-light.ttf
,08-05 14:14:24.646   765  1322 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:24.646   765  1467 I ActivityManager: Killing 6843:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): emptyCount ##41
,08-05 14:14:24.646   765  1467 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-05 14:14:24.646   765  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:24.646   765  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:24.646   765  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:24.646   765  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:24.686  7888  7888 E Zygote  : MountEmulatedStorage()
08-05 14:14:24.686  7888  7888 E Zygote  : v2
08-05 14:14:24.686  7888  7888 I libpersona: KNOX_SDCARD checking this for 10042
08-05 14:14:24.686  7888  7888 I libpersona: KNOX_SDCARD not a persona
,08-05 14:14:24.696   765  1467 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7888 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,08-05 14:14:24.706  7888  7888 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 14:14:24.706  7888  7888 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-05 14:14:24.706  7888  7888 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-05 14:14:24.726  7888  7888 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:14:24.726  7888  7888 D ActivityThread: Added TimaKeyStore provider
,08-05 14:14:24.736  7888  7888 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,08-05 14:14:24.756  7888  7888 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,08-05 14:14:24.766   765  1467 I ActivityManager: Killing 6643:com.osp.app.signin/u0a50 (adj 15): emptyCount ##41
,08-05 14:14:24.766   765  1677 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-05 14:14:24.766   765  1677 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:24.766   765  1677 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:24.766   765  3349 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:24.766   765  1677 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:24.766   765  1677 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:24.776  3554  7907 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-05 14:14:24.776   765  1452 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:24.776  3554  7907 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-05 14:14:24.776  3554  7907 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-05 14:14:24.776  3554  7907 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-05 14:14:24.776  3554  7907 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-05 14:14:24.816  7908  7908 E Zygote  : MountEmulatedStorage()
,08-05 14:14:24.816  7908  7908 E Zygote  : v2
08-05 14:14:24.816  7908  7908 I libpersona: KNOX_SDCARD checking this for 10043
08-05 14:14:24.816  7908  7908 I libpersona: KNOX_SDCARD not a persona
,08-05 14:14:24.816   765  1677 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7908 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-05 14:14:24.826  7908  7908 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 14:14:24.826  7908  7908 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-05 14:14:24.826  7908  7908 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-05 14:14:24.846  7908  7908 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:14:24.846  7908  7908 D ActivityThread: Added TimaKeyStore provider
,08-05 14:14:24.846  7860  7860 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,08-05 14:14:24.856  7908  7908 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,08-05 14:14:24.886  7908  7908 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-05 14:14:24.886  7908  7908 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-05 14:14:24.896  7908  7908 D SPPClientService: PushLog.txt file is not deleted.
,08-05 14:14:24.896  7860  7860 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-05 14:14:24.896  7860  7860 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-05 14:14:24.896  7908  7908 D SPPClientService: PushLog.txt file is not deleted.
08-05 14:14:24.896   352   352 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7860
08-05 14:14:24.896   352   352 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-05 14:14:24.896  7860  7860 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-05 14:14:24.896  7860  7860 I wpa_supplicant: ssSupport state is = 1
08-05 14:14:24.896  7860  7860 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-05 14:14:24.896  7860  7860 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-05 14:14:24.896  7860  7860 E wpa_supplicant: SIM READ ERROR
08-05 14:14:24.896  7908  7908 D SPPClientService: ============PushLog. stop!
08-05 14:14:24.896  7860  7860 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-05 14:14:24.896  7860  7860 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-05 14:14:24.896  7860  7860 E wpa_supplicant: SIM READ ERROR
08-05 14:14:24.896  7860  7860 I wpa_supplicant: Blacklist: Clear (all) 
,08-05 14:14:24.896  7860  7860 I wpa_supplicant: wpa_default_ap_write_once
08-05 14:14:24.896  7860  7860 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-05 14:14:24.896  7860  7860 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-05 14:14:24.896  7860  7860 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-05 14:14:24.896  7860  7860 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-05 14:14:24.896  7860  7860 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-05 14:14:24.896  7860  7860 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-05 14:14:24.896  7908  7908 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-05 14:14:24.896   765   783 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-05 14:14:24.896   765   783 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:24.896   765   783 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:24.896   765   783 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:24.896   765   783 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:24.936  7924  7924 E Zygote  : MountEmulatedStorage()
,08-05 14:14:24.936  7924  7924 E Zygote  : v2
08-05 14:14:24.936  7924  7924 I libpersona: KNOX_SDCARD checking this for 10050
08-05 14:14:24.936  7924  7924 I libpersona: KNOX_SDCARD not a persona
,08-05 14:14:24.946   765   783 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7924 uid=10050 gids={50050, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-05 14:14:24.946   765   783 I ActivityManager: Killing 5602:com.android.mms/u0a55 (adj 15): emptyCount ##41
,08-05 14:14:24.946   765  1526 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,08-05 14:14:24.946   765  1526 D ActivityManager: caller:android.app.ApplicationThreadProxy@2363e17e, r.packageName :com.sec.spp.push
,08-05 14:14:24.956  7924  7924 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 14:14:24.956  7924  7924 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-05 14:14:24.956  7924  7924 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-05 14:14:24.966  7908  7931 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-05 14:14:24.976  7924  7924 D TimaKeyStoreProvider: TimaSignature is unavailable
08-05 14:14:24.976  7924  7924 D ActivityThread: Added TimaKeyStore provider
,08-05 14:14:24.996  7924  7924 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,08-05 14:14:25.016   765  1437 D CountryDetector: No listener is left
,08-05 14:14:25.026  7924  7924 I SA      : [SSP] onCreated
,08-05 14:14:25.036  7924  7924 I SA      : [TPM] There is no property file
,08-05 14:14:25.036  7924  7924 I SA      : [SCU] isHaveSA() - false
,08-05 14:14:25.036  7924  7924 I SA      : [TPM] getModelProperty : null
,08-05 14:14:25.046  7924  7924 I SA      : [TPM] getCSCProperty : null
,08-05 14:14:25.046  7924  7924 I SA      : [DM] init START
,08-05 14:14:25.046  7924  7924 I SA      : [DM] This device is not a Vodafone
,08-05 14:14:25.046  7924  7924 I SA      : checkReactivationActive for LOLLIPOP
,08-05 14:14:25.046  7924  7924 I SA      : checkReactivationActive for reactiveActive
08-05 14:14:25.046  7924  7924 I SA      : setSupportRL : true
,08-05 14:14:25.056  7924  7924 I SA      : [SCU] isHaveSA() - false
,08-05 14:14:25.056  7924  7924 I SA      : support phone number id : false
,08-05 14:14:25.056  7924  7924 I SA      : [DM] init END
,08-05 14:14:25.056  7924  7924 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,08-05 14:14:25.066  7924  7924 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,08-05 14:14:25.066  7924  7924 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-05 14:14:25.066  7924  7924 I SA      : [SLFUCHKMGR] constructor called
,08-05 14:14:25.066  7924  7924 I SA      : [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,08-05 14:14:25.076  7924  7924 I SA      : [OR] == isSIMCardReady false ==
,08-05 14:14:25.076  7924  7924 I SA      : [SCU] == networkStateCheck == false
08-05 14:14:25.076  7924  7924 I SA      : [OR] onReceive END
,08-05 14:14:25.076   765  1289 I ActivityManager: Killing 6871:com.sec.android.app.soundalive/u0a64 (adj 15): emptyCount ##41
,08-05 14:14:25.076   765  1289 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,08-05 14:14:25.076   765  1289 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:25.076   765  1289 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:25.076   765  1289 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:25.076   765  1289 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:25.116  7945  7945 E Zygote  : MountEmulatedStorage()
,08-05 14:14:25.116  7945  7945 E Zygote  : v2
08-05 14:14:25.116  7945  7945 I libpersona: KNOX_SDCARD checking this for 10074
08-05 14:14:25.116  7945  7945 I libpersona: KNOX_SDCARD not a persona
,08-05 14:14:25.126  7945  7945 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,08-05 14:14:25.126  7945  7945 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-05 14:14:25.126  7945  7945 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-05 14:14:25.126   765  1289 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7945 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-05 14:14:25.136   337   337 I art     : Explicit concurrent mark sweep GC freed 8742(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 312us total 13.289ms
,08-05 14:14:25.146  7945  7945 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:14:25.146  7945  7945 D ActivityThread: Added TimaKeyStore provider
,08-05 14:14:25.146   337   337 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 273us total 9.609ms
,08-05 14:14:25.156  7945  7945 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,08-05 14:14:25.156   337   337 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 276us total 9.615ms
,08-05 14:14:25.216  7945  7945 I sCloudBackupApp: sCloudBackupApp Version Info : 3.13.7.KK_APP
,08-05 14:14:25.216  7945  7945 I SCloudBackupReceiver: Other Intent
,08-05 14:14:25.216  7159  7159 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,08-05 14:14:25.216  7159  7159 I KnoxUsageLogPro: premStatus:2
,08-05 14:14:25.226  7159  7159 I KnoxUsageLogPro: isEulaShown : false
,08-05 14:14:25.226  7159  7159 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,08-05 14:14:25.226   765  1452 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-05 14:14:25.226   765  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:25.226   765  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:25.226   765  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:25.226   765  1452 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:25.266  7961  7961 E Zygote  : MountEmulatedStorage()
08-05 14:14:25.266  7961  7961 E Zygote  : v2
08-05 14:14:25.266  7961  7961 I libpersona: KNOX_SDCARD checking this for 10104
08-05 14:14:25.266  7961  7961 I libpersona: KNOX_SDCARD not a persona
,08-05 14:14:25.276   765  1452 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7961 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-05 14:14:25.276   765  1452 I ActivityManager: Killing 6891:com.samsung.android.app.assistantmenu/1000 (adj 15): emptyCount ##41
,08-05 14:14:25.286  7961  7961 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 14:14:25.286  7961  7961 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-05 14:14:25.286  7961  7961 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-05 14:14:25.316  7961  7961 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:14:25.316  7961  7961 D ActivityThread: Added TimaKeyStore provider
,08-05 14:14:25.326  7961  7961 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,08-05 14:14:25.406   765  1289 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-05 14:14:25.406   765  1289 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:25.406   765  1289 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:25.406   765  1289 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:25.406   765  1289 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:25.446  7977  7977 E Zygote  : MountEmulatedStorage()
,08-05 14:14:25.446  7977  7977 E Zygote  : v2
08-05 14:14:25.446  7977  7977 I libpersona: KNOX_SDCARD checking this for 10146
08-05 14:14:25.446  7977  7977 I libpersona: KNOX_SDCARD not a persona
,08-05 14:14:25.456   765  1289 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7977 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-05 14:14:25.456   765  1289 I ActivityManager: Killing 6929:com.google.android.apps.docs/u0a112 (adj 15): emptyCount ##41
,08-05 14:14:25.466  7977  7977 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 14:14:25.466  7977  7977 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-05 14:14:25.466  7977  7977 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-05 14:14:25.476   346   346 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 14:14:25.486  7977  7977 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:14:25.486  7977  7977 D ActivityThread: Added TimaKeyStore provider
,08-05 14:14:25.496  7977  7977 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,08-05 14:14:25.696   265   557 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-05 14:14:25.696   265   557 W Vold    : Returning OperationFailed - no handler for errno 0
,08-05 14:14:25.696  7977  7995 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-05 14:14:25.696   265   557 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-05 14:14:25.696   265   557 W Vold    : Returning OperationFailed - no handler for errno 0
08-05 14:14:25.696  7977  7995 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-05 14:14:25.706   265   557 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-05 14:14:25.706   265   557 W Vold    : Returning OperationFailed - no handler for errno 0
,08-05 14:14:25.706  7977  7998 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-05 14:14:25.706   265   557 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-05 14:14:25.706   265   557 W Vold    : Returning OperationFailed - no handler for errno 0
,08-05 14:14:25.706  7977  7998 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-05 14:14:25.716   765  1152 E Tethering: No numeric data
,08-05 14:14:25.716   765  1152 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-05 14:14:25.716   765  1146 V NetworkStats: performPollLocked(flags=0x1)
08-05 14:14:25.716   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 14:14:25.716  1196  1196 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-05 14:14:25.716  1196  1196 D HotspotTile: updateTetherState():false, false
08-05 14:14:25.716   765  1146 D NetworkStatsFactory: UpdateStatsForKnox
08-05 14:14:25.716   765  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:25.716   765  1146 V NetworkStats: performPollLocked() took 3ms
08-05 14:14:25.716   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 14:14:25.716   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 14:14:25.716   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 14:14:25.736  7860  7860 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-05 14:14:25.756  7860  7860 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-05 14:14:25.756  7860  7860 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-05 14:14:25.756  7860  7860 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-05 14:14:25.756   352   352 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7860
08-05 14:14:25.756   352   352 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-05 14:14:25.756  7860  7860 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-05 14:14:25.756  7860  7860 I wpa_supplicant: ssSupport state is = 1
,08-05 14:14:25.756  7860  7860 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-05 14:14:25.756  7860  7860 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-05 14:14:25.756   352   352 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7860
08-05 14:14:25.756   352   352 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-05 14:14:25.756  7860  7860 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-05 14:14:25.756  7860  7860 I wpa_supplicant: ssSupport state is = 1
08-05 14:14:25.756  7860  7860 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-05 14:14:25.756  7860  7860 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-05 14:14:25.756  7860  7860 E wpa_supplicant: SIM READ ERROR
08-05 14:14:25.756  7860  7860 I wpa_supplicant: wpa_default_ap_write_once
08-05 14:14:25.756  7860  7860 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-05 14:14:25.756  7860  7860 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-05 14:14:25.776  7860  7860 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-05 14:14:25.776  7860  7860 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-05 14:14:25.796  7860  7860 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-05 14:14:25.796  7860  7860 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-05 14:14:25.796   765  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-05 14:14:25.796   765  1149 D WifiNative-HAL: callSECApiBoolean - ID [21]
,08-05 14:14:25.796  7860  7860 I wpa_supplicant: HOTSPOT20_ENABLE called
08-05 14:14:25.796  7860  7860 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-05 14:14:25.796  7860  7860 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-05 14:14:25.796  7860  7860 E wpa_supplicant: SIM READ ERROR
08-05 14:14:25.796  7860  7860 I wpa_supplicant: Blacklist: Clear (all) 
,08-05 14:14:25.816  7860  7860 I wpa_supplicant: Skip scan - bUseNetwork false
,08-05 14:14:25.826   765  1149 D WifiNative-HAL: callSECApiInt - ID [210]
,08-05 14:14:25.826   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:25.826   765  1149 D WifiConfigStore: Loading config and enabling all networks 
,08-05 14:14:25.826  1196  1196 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-05 14:14:25.826  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-05 14:14:25.826  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:25.826  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:25.826  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:25.826  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:25.826  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:25.826  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:25.826  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:25.826  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:25.826  1196  1196 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:25.826  1196  1196 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:25.826  1196  1196 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-05 14:14:25.826  1196  1597 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-05 14:14:25.826  7501  7501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:25.826  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:25.826  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:25.826  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:25.826  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:25.826  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 14:14:25.826  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:25.826  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:25.826  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 14:14:25.826   765  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
08-05 14:14:25.826  7501  7501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:25.826  7501  7501 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-05 14:14:25.826  1316  1316 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:25.826  7501  7501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:25.826  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:25.826  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:25.826  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:25.826  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:25.826  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 14:14:25.826  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:25.826  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:25.826  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 14:14:25.826  7501  7501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:25.826  7501  7501 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:25.826  1196  1196 D HotspotTile: onReceive : 3, 0
,08-05 14:14:25.826   765  1149 E WifiConfigStore: Not a HS20
,08-05 14:14:25.846   765  1149 E WifiConfigStore: Not a HS20
,08-05 14:14:25.846   765  1149 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-05 14:14:25.846   765  1149 D WifiNative-HAL: callSECApiInt - ID [65]
,08-05 14:14:25.866   765  1149 D WifiNative-HAL: callSECApiBoolean - ID [13]
,08-05 14:14:25.866  7860  7860 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-05 14:14:25.866  7860  7860 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-05 14:14:25.866  7860  7860 I wpa_supplicant: reset timer : RESET_TIMER 0
08-05 14:14:25.866  7860  7860 I wpa_supplicant: P2P: Current p2p state = IDLE
08-05 14:14:25.866  7860  7860 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-05 14:14:25.866  7860  7860 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-05 14:14:25.866  7860  7860 I wpa_supplicant: First Scan Start
,08-05 14:14:25.866  7702  7702 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 14:14:25.876  7860  7860 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-05 14:14:25.876   765  1149 D WifiNative-HAL: Setting external_sim to 1
,08-05 14:14:25.876   765  1149 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 14:14:25.876   765  1149 I WifiNative-HAL: startHal
08-05 14:14:25.876   765  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9329886c
08-05 14:14:25.876   765  1149 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x301862
08-05 14:14:25.876   765  1149 I WifiNative-HAL: Could not start hal
,08-05 14:14:25.886  7977  7977 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,08-05 14:14:25.886  7977  7977 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,08-05 14:14:25.886   765  1149 E native  : do suspend true
,08-05 14:14:25.896   765  1148 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-05 14:14:25.896   298  1056 D CommandListener: Setting iface cfg
08-05 14:14:25.896   298  1056 D CommandListener: Trying to bring up p2p0
,08-05 14:14:25.896   765  1148 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-05 14:14:25.896   765  1148 D WifiP2pService: P2pEnablingState
,08-05 14:14:25.896   765  1148 D WifiP2pService: P2pEnablingState{ what=147457 }
08-05 14:14:25.896   765  1148 D WifiP2pService: P2p socket connection successful
08-05 14:14:25.896   765  1148 D WifiP2pService: P2pEnabledState
,08-05 14:14:25.896   765  1148 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-05 14:14:25.896   765   765 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-05 14:14:25.896   765  1059 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-05 14:14:25.896   765  1059 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-05 14:14:25.896   765  1059 D WifiDisplayController: disconnect
08-05 14:14:25.896   765  1059 D WifiDisplayController: updateConnection
08-05 14:14:25.896   765  1151 E ConnectivityService: updateNetworkInfo()
08-05 14:14:25.896   765  1059 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-05 14:14:25.896   765  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
08-05 14:14:25.896   765  1059 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-05 14:14:25.896  1196  1196 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-05 14:14:25.896   765   784 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-05 14:14:25.896   765  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-05 14:14:25.896   765  1059 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:25.896   765  1059 D WifiDisplayAdapter: onP2pDisconnected
08-05 14:14:25.896   765  1059 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-05 14:14:25.896   765  1059 D IpRemoteDisplayController: WfdBridgeServer is already null
08-05 14:14:25.896  1196  1196 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-05 14:14:25.896  7977  7977 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5084-5088)
08-05 14:14:25.896  7977  7977 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-05 14:14:25.896   765   765 D WifiScanningService: SCAN_AVAILABLE : 3
08-05 14:14:25.896   765   765 D RttService: SCAN_AVAILABLE : 3
08-05 14:14:25.896   765  1167 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:25.896   765  1167 I WifiNative-HAL: startHal
08-05 14:14:25.896   765  1168 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 14:14:25.906   765  1167 E wifi    : getStaticLongField sWifiHalHandle 0x9c3bb99c
08-05 14:14:25.906   765  1167 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x30185a
08-05 14:14:25.906   765  1167 I WifiNative-HAL: Could not start hal
08-05 14:14:25.906   765  1167 E WifiScanningService: could not start HAL
,08-05 14:14:25.906   765  1148 D WifiNative-HAL: p2pGetDeviceAddress
,08-05 14:14:25.906   765  1148 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:de:28:a3
,08-05 14:14:25.906   765  1148 D WifiP2pService: DeviceAddress: ea:28:a3
,08-05 14:14:25.906   765  1059 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
08-05 14:14:25.906   765  1059 D WifiDisplayController:  deviceAddress: ea:50:8b:de:28:a3
08-05 14:14:25.906   765  1059 D WifiDisplayController:  primary type: 10-0050F204-5
08-05 14:14:25.906   765  1059 D WifiDisplayController:  secondary type: null
08-05 14:14:25.906   765  1059 D WifiDisplayController:  wps: 0
08-05 14:14:25.906   765  1059 D WifiDisplayController:  grpcapab: 0
08-05 14:14:25.906   765  1059 D WifiDisplayController:  devcapab: 0
08-05 14:14:25.906   765  1059 D WifiDisplayController:  status: 3
08-05 14:14:25.906   765  1059 D WifiDisplayController:  wfdInfo: null
08-05 14:14:25.906   765  1059 D WifiDisplayController:  groupownerAddress: null
08-05 14:14:25.906   765  1059 D WifiDisplayController:  GOdeviceName: null
08-05 14:14:25.906   765  1059 D WifiDisplayController:  interfaceAddress: 
08-05 14:14:25.906   765  1059 D WifiDisplayController:  SConnectInfo : null
,08-05 14:14:25.906   765  1149 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-05 14:14:25.906   765  1149 D WifiNative-HAL: callSECStringApiVoid - ID [215]
08-05 14:14:25.906   765  1149 E WifiNative-HAL: invaild command id : 215
,08-05 14:14:25.906  7977  7977 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1d1a1b95}
,08-05 14:14:25.906  7977  7977 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-05 14:14:25.906  7977  7977 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-05 14:14:25.926   765  1148 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-05 14:14:25.926   765  1148 D WifiP2pService: InactiveState
08-05 14:14:25.926   765  1148 D WifiP2pService: InactiveState{ what=143376 }
08-05 14:14:25.926   765  1148 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-05 14:14:25.926  7977  7977 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-05 14:14:25.936  7977  7977 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-05 14:14:25.936  7977  7977 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-05 14:14:25.956  7860  7860 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-05 14:14:25.956  7860  7860 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-05 14:14:25.956   765  1148 D WifiP2pService: InactiveState{ what=143376 }
,08-05 14:14:25.956   765  1148 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-05 14:14:25.966  7977  7977 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-05 14:14:25.966  7977  7977 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
08-05 14:14:25.966  7977  7977 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,08-05 14:14:25.966  7977  7977 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
08-05 14:14:25.966  7977  7977 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
08-05 14:14:25.966  7977  7977 I Adreno-EGL: Build Date: 11/19/14 Wed
08-05 14:14:25.966  7977  7977 I Adreno-EGL: Local Branch: mybranch5813579
08-05 14:14:25.966  7977  7977 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
08-05 14:14:25.966  7977  7977 I Adreno-EGL: Local Patches: NONE
08-05 14:14:25.966  7977  7977 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,08-05 14:14:25.976  7860  7860 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,08-05 14:14:25.986   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-05 14:14:25.986   765  1149 D SecContentProvider2: mCursor = null
,08-05 14:14:25.986   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-05 14:14:25.986   765  1149 D SecContentProvider2: mCursor = null
,08-05 14:14:26.036  7977  8028 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-05 14:14:26.036  7977  7977 I NSApplication: Starting up...
,08-05 14:14:26.056   765   784 I ActivityManager: Killing 6966:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##41
,08-05 14:14:26.126   765  1578 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-05 14:14:26.136   765  1578 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:26.136   765  1578 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:26.136   765  1578 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:26.136   765  1578 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:26.156   305   305 E SMD     : DCD ON
,08-05 14:14:26.176  8035  8035 E Zygote  : MountEmulatedStorage()
,08-05 14:14:26.176  8035  8035 E Zygote  : v2
08-05 14:14:26.176  8035  8035 I libpersona: KNOX_SDCARD checking this for 10158
08-05 14:14:26.176  8035  8035 I libpersona: KNOX_SDCARD not a persona
,08-05 14:14:26.176   765  1578 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=8035 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-05 14:14:26.186  8035  8035 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 14:14:26.186  8035  8035 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-05 14:14:26.186  8035  8035 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-05 14:14:26.206  8035  8035 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:14:26.206  8035  8035 D ActivityThread: Added TimaKeyStore provider
,08-05 14:14:26.216  8035  8035 D ResourcesManager: creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,08-05 14:14:26.216  8035  8035 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 14:14:26.216  8035  8035 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-05 14:14:26.216  8035  8035 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-05 14:14:26.236  8035  8035 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-05 14:14:26.236  8035  8035 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-05 14:14:26.236  8035  8035 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-05 14:14:26.236   765  1437 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-05 14:14:26.236   765  1437 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:26.236   765  1437 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:26.236   765  1437 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:26.236   765  1437 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:26.276  8050  8050 E Zygote  : MountEmulatedStorage()
,08-05 14:14:26.276  8050  8050 E Zygote  : v2
08-05 14:14:26.276  8050  8050 I libpersona: KNOX_SDCARD checking this for 10186
08-05 14:14:26.276  8050  8050 I libpersona: KNOX_SDCARD not a persona
,08-05 14:14:26.286  8050  8050 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 14:14:26.286  8050  8050 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-05 14:14:26.286  8050  8050 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-05 14:14:26.296   765  1437 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=8050 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-05 14:14:26.296   765  1437 I ActivityManager: Killing 6983:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): emptyCount ##41
,08-05 14:14:26.316  8050  8050 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:14:26.316  8050  8050 D ActivityThread: Added TimaKeyStore provider
,08-05 14:14:26.336  8050  8050 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,08-05 14:14:26.336  8050  8050 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-05 14:14:26.336  8050  8050 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 14:14:26.336  8050  8050 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-05 14:14:26.336  8050  8050 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-05 14:14:26.336  8050  8050 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-05 14:14:26.426   765  1706 D RCPManagerService: exchangeData() failure , invalid userId
,08-05 14:14:26.446   765   783 D RCPManagerService: exchangeData() failure , invalid userId
,08-05 14:14:26.456   765  1452 D RCPManagerService: exchangeData() failure , invalid userId
,08-05 14:14:26.476   346   346 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 14:14:26.486   765  1144 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-05 14:14:26.486   765  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:26.486   765  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:26.486   765  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:26.486   765  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:26.496   765  1706 D RCPManagerService: exchangeData() failure , invalid userId
,08-05 14:14:26.526  8074  8074 E Zygote  : MountEmulatedStorage()
08-05 14:14:26.526  8074  8074 E Zygote  : v2
08-05 14:14:26.526  8074  8074 I libpersona: KNOX_SDCARD checking this for 10092
08-05 14:14:26.526  8074  8074 I libpersona: KNOX_SDCARD not a persona
,08-05 14:14:26.536  8074  8074 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,08-05 14:14:26.536  8074  8074 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-05 14:14:26.536  8074  8074 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-05 14:14:26.536   765  1144 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8074 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,08-05 14:14:26.546   765  1322 D RCPManagerService: exchangeData() failure , invalid userId
,08-05 14:14:26.556  8074  8074 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:14:26.556  8074  8074 D ActivityThread: Added TimaKeyStore provider
,08-05 14:14:26.566   765  1237 D RCPManagerService: exchangeData() failure , invalid userId
,08-05 14:14:26.566   765  3410 I ActivityManager: Killing 6999:com.samsung.helphub/1000 (adj 15): emptyCount ##41
,08-05 14:14:26.586   765  3349 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:26.586  6711  6711 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-05 14:14:26.586  6711  6711 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found ,
08-05 14:14:26.586  6711  6711 D SecurityLogAgent: StateMachine : Current State = 1
08-05 14:14:26.586  6711  6711 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-05 14:14:26.656   765   783 I art     : Explicit concurrent mark sweep GC freed 44518(2MB) AllocSpace objects, 3(48KB) LOS objects, 29% free, 37MB/53MB, paused 1.336ms total 89.313ms
,08-05 14:14:26.656   765  1322 I ActivityManager: Killing 7055:com.samsung.android.snote:provider/u0a168 (adj 15): emptyCount ##41
,08-05 14:14:26.656   765  1467 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,08-05 14:14:26.656   765  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:26.656   765  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:26.656   765  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:26.656   765  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:26.656   765  1237 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:26.656   765  1677 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:26.666  8074  8074 D ResourcesManager: creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,08-05 14:14:26.676  7860  7860 I wpa_supplicant: nl80211: Received scan results (33 BSSes)
08-05 14:14:26.676  7860  7860 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-05 14:14:26.676  7860  7860 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
08-05 14:14:26.676  7860  7860 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-05 14:14:26.676  7860  7860 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=5 BSSID=00.00.00 SSID=4E47373030
,08-05 14:14:26.676  8074  8074 D BadgeProvider: onCreate
,08-05 14:14:26.696  8074  8074 D BadgeProvider: DatabaseHelper
,08-05 14:14:26.696  8090  8090 E Zygote  : MountEmulatedStorage()
08-05 14:14:26.696  8090  8090 I libpersona: KNOX_SDCARD checking this for 10200
08-05 14:14:26.696  8090  8090 E Zygote  : v2
08-05 14:14:26.696  8090  8090 I libpersona: KNOX_SDCARD not a persona
,08-05 14:14:26.706   765  1467 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8090 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-05 14:14:26.706   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-05 14:14:26.706   765  1149 D SecContentProvider2: mCursor = null
,08-05 14:14:26.736  8090  8090 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 14:14:26.736  8090  8090 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-05 14:14:26.736  8090  8090 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-05 14:14:26.746  7860  7860 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-05 14:14:26.746  7860  7860 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=6 BSSID=00.00.00 SSID=4E47373030
08-05 14:14:26.746  7860  7860 I wpa_supplicant: Associated with F4.99.3E
08-05 14:14:26.746  7860  7860 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
,08-05 14:14:26.746  7860  7860 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-05 14:14:26.746  8074  8084 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-05 14:14:26.746   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-05 14:14:26.746   765  1149 D SecContentProvider2: mCursor = null
,08-05 14:14:26.746   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-05 14:14:26.746   765  1149 D SecContentProvider2: mCursor = null
,08-05 14:14:26.756  8074  8084 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
,08-05 14:14:26.756  8074  8084 D BadgeProvider: sendNotify, [notify] : null
08-05 14:14:26.756  8074  8084 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
08-05 14:14:26.756  8074  8084 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-05 14:14:26.756  8074  8084 D BadgeProvider: update, [UpdateCount] : 1
,08-05 14:14:26.756  1440  1440 D Launcher.Model: reloadBadges entered.
,08-05 14:14:26.756  7860  7860 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-05 14:14:26.766  7860  7860 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-05 14:14:26.766  7860  7860 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-05 14:14:26.766  7860  7860 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 14:14:26.766  7860  7860 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-05 14:14:26.766  7860  7860 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=1 id_str=]
,08-05 14:14:26.766  7860  7860 I wpa_supplicant: Blacklist: Clear (temp) 
08-05 14:14:26.766  7860  7860 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-05 14:14:26.766   765  1149 D WifiNative-HAL: callSECApiVoid - ID [50]
,08-05 14:14:26.776   765  1149 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-05 14:14:26.776   765  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 14:14:26.776   765  1151 D ConnectivityService: Got NetworkAgent Messenger
08-05 14:14:26.776   765  1151 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-05 14:14:26.776   765  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 14:14:26.776   765  1151 E ConnectivityService: updateNetworkInfo()
08-05 14:14:26.776   765  1151 D ConnectivityService: NetworkAgent connected
,08-05 14:14:26.776  1196  1196 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-05 14:14:26.776  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-05 14:14:26.776   765  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 14:14:26.776  8090  8090 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:14:26.776  8090  8090 D ActivityThread: Added TimaKeyStore provider
,08-05 14:14:26.786   298  1056 D CommandListener: Setting iface cfg
,08-05 14:14:26.786   765  1149 E WifiStateMachine: Start Dhcp Watchdog 2
,08-05 14:14:26.796   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-05 14:14:26.796   765  1149 D SecContentProvider2: mCursor = null
,08-05 14:14:26.796  1196  1196 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-05 14:14:26.796  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-05 14:14:26.796   765  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,08-05 14:14:26.806  8090  8090 D ResourcesManager: creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,08-05 14:14:26.826   765  1452 I ActivityManager: Killing 7074:com.sec.kidsplat.installer/u0a189 (adj 15): emptyCount ##41
,08-05 14:14:26.826   765  3349 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-05 14:14:26.826   765  1437 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-05 14:14:26.826   765  1437 D ActivityManager: caller:android.app.ApplicationThreadProxy@a42bfc0, r.packageName :com.google.android.gms
,08-05 14:14:26.836  4411  4411 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-05 14:14:26.836  4411  5388 I iu.UploadsManager: num queued entries: 0
,08-05 14:14:26.836  4411  5388 I iu.UploadsManager: num updated entries: 0
08-05 14:14:26.836  4411  5388 I iu.SyncManager: NEXT; no task
,08-05 14:14:26.846  7037  7037 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-05 14:14:26.856   765  1706 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:26.856  6711  6711 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-05 14:14:26.856  6711  6711 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-05 14:14:26.856  6711  6711 D SecurityLogAgent: StateMachine : Current State = 1
08-05 14:14:26.856  6711  6711 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-05 14:14:26.856  7037  7037 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-05 14:14:26.866   765  3349 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:26.866  6711  6711 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-05 14:14:26.866  6711  6711 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-05 14:14:26.866  6711  6711 D SecurityLogAgent: StateMachine : Current State = 1
08-05 14:14:26.866  6711  6711 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-05 14:14:26.876  7686  7686 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,08-05 14:14:26.876  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-05 14:14:26.876  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-05 14:14:26.876   765  1706 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:26.876  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-05 14:14:26.876   765  1677 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:26.876  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-05 14:14:26.876  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-05 14:14:26.876  1316  1316 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-05 14:14:26.876  1316  2693 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-05 14:14:26.886   765  1149 E native  : do suspend false
,08-05 14:14:26.886  7144  7144 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-05 14:14:26.886  7686  7686 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-05 14:14:26.886   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-05 14:14:26.886   765  1149 D SecContentProvider2: mCursor = null
08-05 14:14:26.886  7686  7686 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,08-05 14:14:26.886  7686  7686 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
08-05 14:14:26.886   765  1148 D WifiP2pService: InactiveState{ what=143375 }
08-05 14:14:26.886   765  1148 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-05 14:14:26.886  7686  7686 D WifiDirectBR: stopServiceTest : false
,08-05 14:14:26.896  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-05 14:14:26.896  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-05 14:14:26.896   765  1578 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:26.896  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-05 14:14:26.896   765  1706 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:26.906  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-05 14:14:26.906  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-05 14:14:26.906  1316  1316 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-05 14:14:26.906  1316  2693 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-05 14:14:26.906   765  1677 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:26.906  7037  7037 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-05 14:14:27.096  8115  8115 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-05 14:14:27.106  8115  8115 I dhcpcd  : version 5.5.6 starting
,08-05 14:14:27.106  8115  8115 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-05 14:14:27.176  8115  8115 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-05 14:14:27.176  8115  8115 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-05 14:14:27.176  8115  8115 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-05 14:14:27.176  8115  8115 I dhcpcd  : bssid match
08-05 14:14:27.176  8115  8115 I dhcpcd  : wlan0: rebinding lease of 192.168.1.122
,08-05 14:14:27.296  7501  7570 I WifiManager: packageName : com.test.thalitest
08-05 14:14:27.296   765  1578 D WifiService: setWifiEnabled: false pid=7501, uid=10079
08-05 14:14:27.296   765  1578 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-05 14:14:27.296   765  1578 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-05 14:14:27.296   765  1578 D SecContentProvider2: mCursor = null
08-05 14:14:27.296   765  1578 D SettingsProvider: name = wifi_on
,08-05 14:14:27.296   765  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-05 14:14:27.306   765  1149 E native  : do suspend true
,08-05 14:14:27.316   765  1148 D WifiP2pService: InactiveState{ what=143375 }
,08-05 14:14:27.316   765  1148 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-05 14:14:27.316   298  1056 D CommandListener: Clearing all IP addresses on wlan0
,08-05 14:14:27.326  1196  1196 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-05 14:14:27.326  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-05 14:14:27.336   765  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-05 14:14:27.336   765  1151 E ConnectivityService: updateNetworkInfo()
08-05 14:14:27.336   765  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 14:14:27.336   765  1151 E ConnectivityService: updateNetworkInfo()
08-05 14:14:27.336   765  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
08-05 14:14:27.336   765  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-05 14:14:27.336   298  1056 E Netd    : no such netId 503
,08-05 14:14:27.336   765   765 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-05 14:14:27.336   765  1151 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '77 network destroy 503' failed with '400 77 destroyNetwork() failed (Machine is not on the network)'
08-05 14:14:27.336   765  1151 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-05 14:14:27.336   765  1151 D ConnectivityService: calling update connectivity
08-05 14:14:27.336   765  1151 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=false
,08-05 14:14:27.336   765  8106 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:27.336   765  8106 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-05 14:14:27.336  1196  1196 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-05 14:14:27.336   765  1151 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-05 14:14:27.336  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-05 14:14:27.346   765  1149 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-05 14:14:27.346   765   765 D WifiScanningService: SCAN_AVAILABLE : 1
08-05 14:14:27.346   765   765 D RttService: SCAN_AVAILABLE : 1
08-05 14:14:27.346   765  1148 D WifiP2pService: InactiveState{ what=131204 }
,08-05 14:14:27.346   765  1148 D WifiP2pService: P2pEnabledState{ what=131204 }
08-05 14:14:27.346   765  1148 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-05 14:14:27.346   765  1167 D WifiScanningService: DefaultState got{ when=-2ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:27.346   765  1168 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 14:14:27.346   765  1059 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:27.346   765  1059 D WifiDisplayAdapter: onP2pDisconnected
08-05 14:14:27.346   765  1059 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-05 14:14:27.346   765  1059 D IpRemoteDisplayController: WfdBridgeServer is already null
08-05 14:14:27.346   765  1151 E ConnectivityService: updateNetworkInfo()
,08-05 14:14:27.346   765  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
08-05 14:14:27.356   765  1059 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,08-05 14:14:27.356   765  1059 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-05 14:14:27.356   765  1059 D WifiDisplayController: disconnect
08-05 14:14:27.356   765  1059 D WifiDisplayController: updateConnection
08-05 14:14:27.356   765  1059 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-05 14:14:27.356   765  1059 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-05 14:14:27.356   765   765 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-05 14:14:27.356   765  1148 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
08-05 14:14:27.356   765  1059 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-05 14:14:27.356   765  1059 D WifiDisplayAdapter: onP2pDisconnected
08-05 14:14:27.356   765  1059 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-05 14:14:27.356   765  1059 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-05 14:14:27.356  1196  1196 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-05 14:14:27.356   765  1151 E ConnectivityService: updateNetworkInfo()
08-05 14:14:27.356   765  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
08-05 14:14:27.356   765  1148 D WifiP2pService: P2pDisablingState
08-05 14:14:27.356   765  1148 D WifiP2pService: P2pDisablingState{ what=147458 }
08-05 14:14:27.356   765  1148 D WifiP2pService: p2p socket connection lost
08-05 14:14:27.356   765  1706 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-05 14:14:27.356  1196  1196 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-05 14:14:27.366   765  1148 D WifiP2pService: P2pDisabledState
08-05 14:14:27.366   765  1149 E native  : do suspend true
,08-05 14:14:27.366  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-05 14:14:27.366  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-05 14:14:27.366   765  1677 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:27.366  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-05 14:14:27.366   765  1237 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-05 14:14:27.366   765  1148 D WifiP2pService: P2pDisabledState{ what=143375 }
08-05 14:14:27.366  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-05 14:14:27.366   765  1148 D WifiP2pService: DefaultState{ what=143375 }
,08-05 14:14:27.366  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-05 14:14:27.366  1316  1316 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-05 14:14:27.366   298  1056 D CommandListener: Clearing all IP addresses on wlan0
,08-05 14:14:27.366  1316  2693 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-05 14:14:27.376  7860  7860 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-05 14:14:27.376   765   765 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-05 14:14:27.376  1196  1196 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-05 14:14:27.376  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-05 14:14:27.376  1196  1196 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-05 14:14:27.376  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-05 14:14:27.376   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,08-05 14:14:27.376  1196  1196 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-05 14:14:27.386  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-05 14:14:27.386  7501  7501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:27.386  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:27.386  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:27.386  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:27.386  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:27.386  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 14:14:27.386  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 14:14:27.386  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:27.386  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:27.386  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 14:14:27.386  7501  7501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:27.386  7501  7501 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 14:14:27.386  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:27.386  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:27.386  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:27.386  7501  7501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:27.386  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:27.386  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:27.386  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:27.386  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 14:14:27.386  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 14:14:27.386  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:27.386  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:27.386  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 14:14:27.386  7501  7501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:27.386  7501  7501 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 14:14:27.386  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:27.386   765  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
08-05 14:14:27.386  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:27.386  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:27.386  1196  1196 D StatusBar.NetworkController: applyOpen
,08-05 14:14:27.386  1196  1196 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:27.386  1196  1196 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-05 14:14:27.386  1196  1196 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:27.386   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-05 14:14:27.386  1196  1597 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-05 14:14:27.386   765  1149 D SecContentProvider2: mCursor = null
,08-05 14:14:27.386  1316  1316 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:27.386  1196  1196 D HotspotTile: onReceive : 0, 0
,08-05 14:14:27.386   765  1578 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:27.396  7037  7037 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-05 14:14:27.396  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-05 14:14:27.396  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-05 14:14:27.396   765  1706 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:27.396  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-05 14:14:27.396   765  1677 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-05 14:14:27.396  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-05 14:14:27.396  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-05 14:14:27.396  1316  1316 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-05 14:14:27.406  1316  2693 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-05 14:14:27.406  7144  7144 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-05 14:14:27.406  7686  7686 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-05 14:14:27.406  7686  7686 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
08-05 14:14:27.406  7686  7686 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,08-05 14:14:27.406  7686  7686 D WifiDirectBR: stopServiceTest : false
,08-05 14:14:27.416  7860  7860 I wpa_supplicant: Blacklist: Clear (all) 
,08-05 14:14:27.416  7686  7686 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,08-05 14:14:27.416  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-05 14:14:27.416  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-05 14:14:27.416   765  1289 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:27.416  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-05 14:14:27.416   765   784 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-05 14:14:27.416  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-05 14:14:27.416  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-05 14:14:27.416  1316  1316 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-05 14:14:27.416  1316  2693 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-05 14:14:27.426   765  1677 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:27.426  7037  7037 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-05 14:14:27.436  7860  7860 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-05 14:14:27.436  7860  7860 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-05 14:14:27.436  7860  7860 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-05 14:14:27.436  7860  7860 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=0 BSSID=F4.99.3E SSID=4E47373030
08-05 14:14:27.436  7860  7860 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-05 14:14:27.446  7037  7037 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-05 14:14:27.456   765  3349 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:27.456  6711  6711 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-05 14:14:27.456  6711  6711 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-05 14:14:27.456  6711  6711 D SecurityLogAgent: StateMachine : Current State = 1
08-05 14:14:27.456  6711  6711 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-05 14:14:27.476  7860  7860 I wpa_supplicant: Blacklist: Clear (all) 
,08-05 14:14:27.476   346   346 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 14:14:27.596   765  1152 D Tethering: InitialState.processMessage what=4
,08-05 14:14:27.596   765  1152 E Tethering: No numeric data
08-05 14:14:27.596  7860  7860 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-05 14:14:27.596   765  1152 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-05 14:14:27.596   765  1146 V NetworkStats: performPollLocked(flags=0x1)
,08-05 14:14:27.596  1196  1196 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-05 14:14:27.596  1196  1196 D HotspotTile: updateTetherState():false, false
,08-05 14:14:27.596   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 14:14:27.596   765  1146 D NetworkStatsFactory: UpdateStatsForKnox
,08-05 14:14:27.596   765  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:27.606   765  1146 V NetworkStats: performPollLocked() took 4ms
08-05 14:14:27.606   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 14:14:27.606   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 14:14:27.606   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 14:14:27.696   765  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,08-05 14:14:27.706   765  1149 D WifiNative-HAL: callSECApiBoolean - ID [21]
,08-05 14:14:27.706   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:27.706  1903  2407 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 14:14:27.706  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:27.706  1196  1196 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-05 14:14:27.706  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-05 14:14:27.706  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:27.706  1196  1196 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:27.706  1196  1196 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-05 14:14:27.706   765  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,08-05 14:14:27.706  1196  1597 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-05 14:14:27.706  1196  1196 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:27.706  1196  1196 D HotspotTile: onReceive : 1, 0
,08-05 14:14:27.706  1316  1316 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:27.706  7702  7702 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 14:14:27.706  7037  7037 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-05 14:14:27.716   765  1452 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:27.716  6711  6711 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-05 14:14:27.716  6711  6711 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-05 14:14:27.716  6711  6711 D SecurityLogAgent: StateMachine : Current State = 1
08-05 14:14:27.716  6711  6711 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-05 14:14:27.906   765  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-05 14:14:28.126   765   784 I ActivityManager: Killing 5817:com.android.providers.calendar/u0a51 (adj 15): emptyCount ##41
,08-05 14:14:28.356  8115  8115 E dhcpcd  : wlan0: send_raw_packet: Network is down
,08-05 14:14:28.476   346   346 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 14:14:28.496   765  8110 D NetUtils: dhcp_do_request failed : wlan0 (new)
08-05 14:14:28.496   765  8110 E DhcpStateMachine: DHCP failed on wlan0: DHCP result was failed
,08-05 14:14:28.596   765   783 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
08-05 14:14:28.596   765   783 D ActivityManager: caller:android.app.ApplicationThreadProxy@35854f9, r.packageName :com.google.android.music
,08-05 14:14:28.616   765   784 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-05 14:14:28.616   765  1706 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-05 14:14:28.616   765  3410 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-05 14:14:28.626   765  1647 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-05 14:14:28.626   765  1647 D ActivityManager: caller:android.app.ApplicationThreadProxy@1c8f5e97, r.packageName :com.google.android.music
,08-05 14:14:28.656  1903  1903 D WearableService: callingUid 10015, callindPid: 1903
,08-05 14:14:28.666   765  1578 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-05 14:14:28.696  7766  7766 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-05 14:14:28.696  7766  8177 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-05 14:14:28.726  7766  8172 I MusicLeanback: Conditions not met for autocaching.
,08-05 14:14:28.726  7766  8172 I MusicLeanback: Stop autocaching.
,08-05 14:14:29.166   305   305 E SMD     : DCD ON
,08-05 14:14:29.486   346   346 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 14:14:30.316  7501  7570 D BluetoothAdapter: enable()
,08-05 14:14:30.316   765  1467 W ActivityManager: Permission Denial: getCurrentUser() from pid=7501, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,08-05 14:14:30.316   765  1467 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-05 14:14:30.316   765  1467 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7501, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-05 14:14:30.316   765  1467 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
08-05 14:14:30.316   765  1467 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
08-05 14:14:30.316   765  1467 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
08-05 14:14:30.316   765  1467 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-05 14:14:30.316   765  1467 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-05 14:14:30.316   765  1467 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-05 14:14:30.316   765  1467 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2,
,08-05 14:14:30.326   765  1467 D SettingsProvider: name = bluetooth_on,
,08-05 14:14:30.326   765  1058 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-05 14:14:30.326   765  1058 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-05 14:14:30.326   765  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-05 14:14:30.356  7741  7741 D BluetoothAdapterState: make
,08-05 14:14:30.366  7741  7741 I bluedroid: init
,08-05 14:14:30.366  7741  8182 I BluetoothAdapterState: Entering OffState
,08-05 14:14:30.366  7741  7741 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-05 14:14:30.366  7741  7741 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-05 14:14:30.366  7741  7741 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-05 14:14:30.366  7741  7741 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-05 14:14:30.366  7741  7741 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-05 14:14:30.366  7741  7741 I bluedroid: get_profile_interface socket
08-05 14:14:30.366  7741  7741 I bluedroid: get_profile_interface map_client
,08-05 14:14:30.366  7741  7741 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-05 14:14:30.376  7741  8185 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-05 14:14:30.376  7741  8185 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
,08-05 14:14:30.376   765  1526 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-05 14:14:30.376  7741  7758 I bluedroid: config_hci_snoop_log
,08-05 14:14:30.376   765  1058 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 14 receivers.
,08-05 14:14:30.386   765  1058 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-05 14:14:30.386   765  1058 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-05 14:14:30.386   765  1058 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-05 14:14:30.386  7741  8182 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-05 14:14:30.386  7741  8185 E BluetoothServiceJni: populateRssiValuesNative
08-05 14:14:30.386  7741  8185 I bluedroid: getModelRssiValues
,08-05 14:14:30.386  7741  8185 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-05 14:14:30.386  7741  8185 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-05 14:14:30.386   765   765 D SettingsProvider: name = bluetooth_name
08-05 14:14:30.386  7741  8185 D BluetoothAdapterProperties: Name is: Note3-1
,08-05 14:14:30.386  7741  8182 D BluetoothAdapterProperties: Setting state to 11
08-05 14:14:30.386  7741  8182 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-05 14:14:30.386  7741  8182 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-05 14:14:30.386  7741  8182 D BluetoothAdapterService: updateAdapterState state is 11
,08-05 14:14:30.396   765   765 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-05 14:14:30.396   765   765 I InputMethodManagerService: [BT Setting State] State =11
,08-05 14:14:30.396  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:30.406  1196  1196 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-05 14:14:30.406  1196  1196 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-05 14:14:30.406  1196  1597 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-05 14:14:30.406  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:30.406   765  1677 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,08-05 14:14:30.406   765  3349 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-05 14:14:30.406  1196  1196 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,08-05 14:14:30.406   765  1467 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-05 14:14:30.406   765  1467 D ActivityManager: caller:android.app.ApplicationThreadProxy@3975f47f, r.packageName :com.google.android.gms
,08-05 14:14:30.416  1739  1739 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-05 14:14:30.416  1316  1316 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:30.416  7661  7661 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:30.416  7741  8182 D BluetoothAdapterService: Autoconnection is available 
08-05 14:14:30.416  7741  8182 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-05 14:14:30.416  1316  1316 D BluetoothNotiBroadcastReceiver: onReceive
,08-05 14:14:30.416  7741  8182 D BluetoothSecureManager: getInstant: null
,08-05 14:14:30.416  7741  8182 D BluetoothSecureManager: calling getMethod for getService
08-05 14:14:30.416  7741  8182 D BluetoothSecureManager: calling getService
08-05 14:14:30.416  7741  8182 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@103fd7b7
,08-05 14:14:30.416   765  1322 D BluetoothSecureManagerService: isSecureModeEnabled
08-05 14:14:30.416   765  1322 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-05 14:14:30.416  7741  8182 D BtConfig.SecureMode: isSecureModeOn:false
08-05 14:14:30.426  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-05 14:14:30.426  7741  8182 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-05 14:14:30.426  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-05 14:14:30.426  7741  8182 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,08-05 14:14:30.426  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-05 14:14:30.426  7741  8182 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-05 14:14:30.426  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-05 14:14:30.426  7741  8182 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,08-05 14:14:30.426  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-05 14:14:30.426  7741  8182 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-05 14:14:30.426  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-05 14:14:30.426  7741  8182 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-05 14:14:30.426  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-05 14:14:30.426  7741  8182 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-05 14:14:30.426  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-05 14:14:30.426  7741  8182 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-05 14:14:30.426  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-05 14:14:30.426  7741  8182 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,08-05 14:14:30.426  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-05 14:14:30.426  7741  8182 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-05 14:14:30.426  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-05 14:14:30.426  7741  8182 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-05 14:14:30.426  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-05 14:14:30.436  7741  8182 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-05 14:14:30.436  7741  8182 D BluetoothBondStateMachine: make
,08-05 14:14:30.446  1903  1903 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-05 14:14:30.446  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-05 14:14:30.446  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-05 14:14:30.446  7741  8182 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-05 14:14:30.446  7741  8197 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-05 14:14:30.446   765  3410 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-05 14:14:30.446   765  3410 D ActivityManager: caller:android.app.ApplicationThreadProxy@10afc495, r.packageName :com.android.bluetooth
,08-05 14:14:30.456  1903  1903 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-05 14:14:30.456  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-05 14:14:30.456  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-05 14:14:30.456  7741  8182 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-05 14:14:30.456  7741  7741 I BtGatt.JNI: classInitNative(L890): classInitNative: Success!
,08-05 14:14:30.456   765  1647 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-05 14:14:30.456   765  1647 D ActivityManager: caller:android.app.ApplicationThreadProxy@387f599b, r.packageName :com.android.bluetooth
08-05 14:14:30.456  7741  7741 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-05 14:14:30.466  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-05 14:14:30.466  7741  7741 D BtGatt.GattService: Received start request. Starting profile...
08-05 14:14:30.466  7741  7741 D BtGatt.GattService: start()
08-05 14:14:30.466  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-05 14:14:30.466  7741  8182 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-05 14:14:30.466  7741  7741 I bluedroid: get_profile_interface gatt
08-05 14:14:30.466   765  1467 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:30.466   765  1467 D ActivityManager: caller:android.app.ApplicationThreadProxy@6151511, r.packageName :com.android.bluetooth
08-05 14:14:30.466  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2d51de
08-05 14:14:30.466  7741  7741 D BtGatt.AdvertiseManager: advertise manager created
,08-05 14:14:30.466  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-05 14:14:30.466  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-05 14:14:30.466  7741  8182 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-05 14:14:30.466   765  3349 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-05 14:14:30.466   765  3349 D ActivityManager: caller:android.app.ApplicationThreadProxy@37eff477, r.packageName :com.android.bluetooth
,08-05 14:14:30.466  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-05 14:14:30.466  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-05 14:14:30.466  7741  8182 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-05 14:14:30.466   765  1144 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:30.466   765  1144 D ActivityManager: caller:android.app.ApplicationThreadProxy@3fa4f14d, r.packageName :com.android.bluetooth
,08-05 14:14:30.466  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-05 14:14:30.466  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-05 14:14:30.466  7741  8182 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-05 14:14:30.466   765  1289 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:30.466   765  1289 D ActivityManager: caller:android.app.ApplicationThreadProxy@34656113, r.packageName :com.android.bluetooth
,08-05 14:14:30.476  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-05 14:14:30.476  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-05 14:14:30.476  7741  8182 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-05 14:14:30.476   765   784 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:30.476   765   784 D ActivityManager: caller:android.app.ApplicationThreadProxy@21dc5549, r.packageName :com.android.bluetooth
,08-05 14:14:30.476  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-05 14:14:30.476  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-05 14:14:30.476  7741  8182 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-05 14:14:30.476   765  1706 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:30.476   765  1706 D ActivityManager: caller:android.app.ApplicationThreadProxy@3d10715a, r.packageName :com.android.bluetooth
,08-05 14:14:30.476  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-05 14:14:30.476  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-05 14:14:30.476  7741  8182 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-05 14:14:30.476  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-05 14:14:30.476  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2d51de
08-05 14:14:30.476  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-05 14:14:30.476  7741  8182 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-05 14:14:30.476  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-05 14:14:30.476  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-05 14:14:30.476  7741  8182 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-05 14:14:30.476  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-05 14:14:30.476  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-05 14:14:30.476  7741  8182 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-05 14:14:30.476  7741  8182 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-05 14:14:30.476   346   346 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
08-05 14:14:30.476  7741  7741 D HeadsetService: Received start request. Starting profile...
,08-05 14:14:30.486  7741  7741 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-05 14:14:30.486  7741  7741 D HeadsetStateMachine: make
,08-05 14:14:30.486  7741  7741 E HeadsetStateMachine: # of Max HF connection is 2
,08-05 14:14:30.496   765  1452 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-05 14:14:30.496   765  3349 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
,08-05 14:14:30.496  7741  7741 I bluedroid: get_profile_interface handsfree
,08-05 14:14:30.506  7741  7741 I DualScoManager: Instantiating Dual Sco Manager
08-05 14:14:30.506  7741  7741 I DualScoManager: Set HeadsetServiceHelper
,08-05 14:14:30.506  7741  7741 D BluetoothAtMessage: createCMTIContentObservers
,08-05 14:14:30.506   765  1437 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-05 14:14:30.506   765  1437 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:30.506   765  1437 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-05 14:14:30.506   765  1437 D SettingsProvider: selectionArgs: false
08-05 14:14:30.506   765  1437 D SettingsProvider: selectionArgs: 1002
08-05 14:14:30.506   765  1437 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:30.506   765  1437 D SettingsProvider: ret = -1
,08-05 14:14:30.506  7741  8208 D HeadsetStateMachine: Enter Disconnected: -2
08-05 14:14:30.506  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2d51de
,08-05 14:14:30.506  7741  7741 D A2dpService: Received start request. Starting profile...
,08-05 14:14:30.506  7741  8208 E HeadsetStateMachine: set to mRemoteBrsf = 0
,08-05 14:14:30.516  7741  8208 D HeadsetStateMachine: map size, before remove : 0
08-05 14:14:30.516  7741  7741 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-05 14:14:30.516  7741  7741 V Avrcp   : make
08-05 14:14:30.516  7741  8208 D HeadsetStateMachine: map size, after remove: 0
08-05 14:14:30.516  7741  8208 D HeadsetStateMachine: mNextConnectingDevice : null
08-05 14:14:30.516  7741  7741 V Avrcp   : Avrcp
,08-05 14:14:30.516  7741  7741 I bluedroid: get_profile_interface avrcp
,08-05 14:14:30.516  7741  7741 V Avrcp   : start
,08-05 14:14:30.516  7741  7741 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-05 14:14:30.516  7741  7741 V Avrcp   : ++registerMediaPlayers++
,08-05 14:14:30.526  7741  7741 I Avrcp   : No of Audio players :: 2
08-05 14:14:30.526  7741  7741 I Avrcp   : App Package name is com.google.android.music
,08-05 14:14:30.526  7741  7741 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,08-05 14:14:30.526  7741  7741 I Avrcp   : App pkg name is Google Play Music
,08-05 14:14:30.526  7741  7741 I Avrcp   : Name::Google Play Music
08-05 14:14:30.526  7741  7741 V Avrcp   : MediaPlayerInfo: mPlayerId=1
08-05 14:14:30.526  7741  7741 I Avrcp   : App Package name is com.sec.android.app.music
,08-05 14:14:30.526  7741  7741 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,08-05 14:14:30.526  7741  7741 I Avrcp   : App pkg name is Music
,08-05 14:14:30.526  7741  7741 I Avrcp   : Name::Music
08-05 14:14:30.526  7741  7741 V Avrcp   : MediaPlayerInfo: mPlayerId=2
08-05 14:14:30.526  7741  7741 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,08-05 14:14:30.536  7741  7741 I Avrcp   : No of Video players :: 1
08-05 14:14:30.536  7741  7741 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
,08-05 14:14:30.536  7741  7741 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,08-05 14:14:30.536  7741  7741 I Avrcp   : Video App pkg name is Video Player
08-05 14:14:30.536  7741  7741 I Avrcp   : Name::Video Player
08-05 14:14:30.536  7741  7741 V Avrcp   : MediaPlayerInfo: mPlayerId=3
,08-05 14:14:30.536  7741  7741 I Avrcp   : Add tempPlayer
08-05 14:14:30.536  7741  7741 V Avrcp   : MediaPlayerInfo: mPlayerId=4
08-05 14:14:30.536  7741  7741 I Avrcp   : Total no of players: 4
08-05 14:14:30.536  7741  7741 V Avrcp   : swapping the samsung player with 1st player
08-05 14:14:30.536  7741  7741 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-05 14:14:30.536  7741  8209 V Avrcp   : handleMessage, msg=207
08-05 14:14:30.536  7741  8209 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
08-05 14:14:30.536  7741  7741 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-05 14:14:30.536  7741  7741 D A2dpStateMachine: make
,08-05 14:14:30.536  7741  7741 I bluedroid: get_profile_interface a2dp
,08-05 14:14:30.536  7741  8211 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-05 14:14:30.536  7741  7741 E bt-btif : warning : media task started media_task_refcnt 1 
,08-05 14:14:30.536  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2d51de
,08-05 14:14:30.546  7741  8210 D A2dpStateMachine: Enter Disconnected: -2
08-05 14:14:30.546  7741  7741 I BluetoothHidServiceJni: classInitNative: succeeds
,08-05 14:14:30.546  7741  7741 D HidService: Received start request. Starting profile...
08-05 14:14:30.546  7741  7741 I bluedroid: get_profile_interface hidhost
,08-05 14:14:30.546  7741  7741 D HidService: setHidService(): set to: null
08-05 14:14:30.546  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2d51de
08-05 14:14:30.546  7741  7741 I BluetoothHealthServiceJni: classInitNative: succeeds
08-05 14:14:30.546  7741  8209 D BluetoothMediaBrowser: no now playing list
,08-05 14:14:30.546  7741  8209 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-05 14:14:30.546  7741  8209 D Avrcp   :  checkNowPlayingList start
08-05 14:14:30.546  7741  7741 D HealthService: Received start request. Starting profile...
,08-05 14:14:30.546  7741  7741 I bluedroid: get_profile_interface health
,08-05 14:14:30.546  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2d51de
08-05 14:14:30.546  7741  7741 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-05 14:14:30.546  7741  7741 D PanService: Received start request. Starting profile...
08-05 14:14:30.546  7741  7741 D BluetoothPanServiceJni: initializeNative(L110): pan
08-05 14:14:30.546  7741  7741 I bluedroid: get_profile_interface pan
,08-05 14:14:30.546  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2d51de
,08-05 14:14:30.556  7741  7741 D BluetoothMapService: Received start request. Starting profile...
,08-05 14:14:30.576  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2d51de
,08-05 14:14:30.576  7741  7741 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-05 14:14:30.576  7741  7741 D SapService: Received start request. Starting profile...
08-05 14:14:30.576  7741  7741 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-05 14:14:30.576  7741  7741 I bluedroid: get_profile_interface sap
08-05 14:14:30.576  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2d51de
,08-05 14:14:30.576  7741  7741 E BluetoothAdapterService(170742238): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
08-05 14:14:30.576  7741  7741 D HeadsetStateMachine: Try to query the phonestate on bind
,08-05 14:14:30.576  1395  1415 I Telecom : BluetoothPhoneService: queryPhoneState
08-05 14:14:30.576  1395  1395 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-05 14:14:30.576  7741  7741 D HeadsetStateMachine: Proxy object connected
,08-05 14:14:30.576  7741  7741 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-05 14:14:30.576  7741  7741 D HeadsetPhoneState: sendDeviceDataStateChanged
08-05 14:14:30.576  7741  7741 D HeadsetPhoneState: Signal level : previous=0 curr=0
,08-05 14:14:30.576  7741  7741 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-05 14:14:30.576  7741  7741 E BluetoothAdapterService(170742238): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-05 14:14:30.576  7741  8208 D HeadsetStateMachine: Disconnected process message: 11
08-05 14:14:30.576  7741  8208 D HeadsetStateMachine: Disconnected process message: 18
08-05 14:14:30.576  7741  8208 D HeadsetStateMachine: Disconnected process message: 10
08-05 14:14:30.576  7741  8208 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-05 14:14:30.576  7741  8208 D HeadsetStateMachine: Disconnected process message: 11
08-05 14:14:30.586  7741  7741 D BluetoothA2dp: Proxy object connected
08-05 14:14:30.586  7741  7741 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-05 14:14:30.586  7741  7741 E BluetoothAdapterService(170742238): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-05 14:14:30.586  7741  7741 E BluetoothAdapterService(170742238): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-05 14:14:30.586  7741  7741 E BluetoothAdapterService(170742238): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-05 14:14:30.586  7741  7741 E BluetoothAdapterService(170742238): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-05 14:14:30.586  7741  7741 E BluetoothAdapterService(170742238): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-05 14:14:30.586  7741  7741 E BluetoothAdapterService(170742238): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
08-05 14:14:30.586  7741  8182 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-05 14:14:30.586  7741  8182 I bluedroid: enable
08-05 14:14:30.586  7741  8215 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-05 14:14:30.586  7741  8182 I bt_hci_bdroid: init
,08-05 14:14:30.586  7741  8182 I bt_vendor: init
08-05 14:14:30.586  7741  8182 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-05 14:14:30.586  7741  8182 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
08-05 14:14:30.586  7741  8182 D bt_userial: userial_init
08-05 14:14:30.586  7741  8182 D bt_vendor: op for 5
,08-05 14:14:30.586  7741  8182 D bt_vendor: op for 0
08-05 14:14:30.586  7741  8182 D bt_upio : upio_set_bluetooth_power(on: 0)
08-05 14:14:30.586  7741  8182 D bt_upio : is_emulator_context : 0
08-05 14:14:30.586  7741  8182 D bt_upio : is_rfkill_disabled ? [0]
08-05 14:14:30.586  7741  8182 D bt_upio : is_rfkill_disabled ? [0]
,08-05 14:14:30.586  7741  8182 D bt_vendor: op for 0
08-05 14:14:30.586  7741  8182 D bt_upio : upio_set_bluetooth_power(on: 1)
08-05 14:14:30.586  7741  8182 D bt_upio : is_emulator_context : 0
08-05 14:14:30.586  7741  8182 D bt_upio : is_rfkill_disabled ? [0]
,08-05 14:14:30.586  7741  8217 D bt_vendor: op for 3
08-05 14:14:30.586  7741  8217 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-05 14:14:30.596  7741  8217 I bt_userial_vendor: userial_vendor_open():UART is setup
08-05 14:14:30.596  7741  8217 I bt_userial_vendor: device fd = 66 open
08-05 14:14:30.596  7741  8217 D bt_vendor: op for 1
08-05 14:14:30.596  7741  8217 E bt_hwcfg: Start CFG HW, HCI reset
08-05 14:14:30.596  7741  8218 D bt_userial: Entering userial_read_thread()
,08-05 14:14:30.676  7741  8217 E bt_hwcfg: Read Local Name after HCI reset
,08-05 14:14:30.696   765  1706 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,08-05 14:14:30.696  7741  8217 D bt_hwcfg: Chipset BCM4335C0
08-05 14:14:30.696  7741  8217 D bt_hwcfg: Target name = [BCM4335C0]
,08-05 14:14:30.696  7741  8217 I bt_hwcfg: module_type[semco].
08-05 14:14:30.696  7741  8217 I bt_hwcfg: not ZERO...
08-05 14:14:30.696  7741  8217 I bt_hwcfg: module_type[semco] is invalid.
08-05 14:14:30.696  7741  8217 E bt_hwcfg: patchram path ORG . BCM4335C0
08-05 14:14:30.696  7741  8217 E bt_hwcfg: patchram path ORG .. BCM4335C0
08-05 14:14:30.696  7741  8217 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
08-05 14:14:30.696  7741  8217 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
08-05 14:14:30.696  7741  8217 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
08-05 14:14:30.696  7741  8217 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
08-05 14:14:30.696  7741  8217 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335C0
08-05 14:14:30.696  7741  8217 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559_wisol.hcd BCM4335C0
08-05 14:14:30.696  7741  8217 E bt_hwcfg: fw ver (org)0.0
08-05 14:14:30.696  7741  8217 E bt_hwcfg: vendor lib preload failed to locate firmware patch file
08-05 14:14:30.696  7741  8217 E bt_hwcfg: Remove module rev, try again BCM4335
08-05 14:14:30.696  7741  8217 D bt_hwcfg: Target name = [BCM4335]
08-05 14:14:30.696  7741  8217 I bt_hwcfg: module_type[semco].
08-05 14:14:30.696  7741  8217 I bt_hwcfg: not ZERO...
08-05 14:14:30.696  7741  8217 I bt_hwcfg: module_type[semco] is invalid.
08-05 14:14:30.696  7741  8217 E bt_hwcfg: patchram path ORG . BCM4335
08-05 14:14:30.696  7741  8217 E bt_hwcfg: patchram path ORG .. BCM4335
08-05 14:14:30.696  7741  8217 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335
08-05 14:14:30.696  7741  8217 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
08-05 14:14:30.696  7741  8217 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335
08-05 14:14:30.696  7741  8217 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
08-05 14:14:30.696  7741  8217 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335
08-05 14:14:30.696  7741  8217 I bt_hwcfg: patch(org) : bcm4335_V0111.0559.hcd
08-05 14:14:30.696  7741  8217 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4335_V0111.0559.hcd
08-05 14:14:30.696  7741  8217 E bt_hwcfg: ORG patchram base 0111
08-05 14:14:30.696  7741  8217 E bt_hwcfg: ORG patchram minor 0559
08-05 14:14:30.696  7741  8217 E bt_hwcfg: fw ver (org)111.559
08-05 14:14:30.696  7741  8217 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4335_V0111.0559.hcd
,08-05 14:14:30.706  7977  7996 I GAV4    : Thread[GAThread,5,main]: No campaign data found.,
,08-05 14:14:30.706  7741  8217 I bt_hwcfg: Axi patch failure or not include AXI patching
,08-05 14:14:30.706  7741  8217 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-05 14:14:31.196  7741  8217 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-05 14:14:31.196  7741  8217 I bt_hwcfg: FW Download delta = 528917
,08-05 14:14:31.196  7741  8217 D bt_hwcfg: Settlement delay -- 100 ms
08-05 14:14:31.196  7741  8217 I bt_hwcfg: Setting fw settlement delay to 100 
,08-05 14:14:31.306  7741  8217 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-05 14:14:31.346  7741  8217 I bt_hwcfg: vendor lib fwcfg completed
,08-05 14:14:31.346  7741  8215 I         : BTE_InitTraceLevels -- TRC_HCI
,08-05 14:14:31.346  7741  8215 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-05 14:14:31.346  7741  8215 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-05 14:14:31.346  7741  8215 I         : BTE_InitTraceLevels -- TRC_AVDT
08-05 14:14:31.346  7741  8215 I         : BTE_InitTraceLevels -- TRC_AVRC
08-05 14:14:31.346  7741  8215 I         : BTE_InitTraceLevels -- TRC_A2D
,08-05 14:14:31.346  7741  8215 I         : BTE_InitTraceLevels -- TRC_BNEP
08-05 14:14:31.346  7741  8215 I         : BTE_InitTraceLevels -- TRC_BTM
08-05 14:14:31.346  7741  8215 I         : BTE_InitTraceLevels -- TRC_GAP
08-05 14:14:31.346  7741  8215 I         : BTE_InitTraceLevels -- TRC_PAN
08-05 14:14:31.346  7741  8215 I         : BTE_InitTraceLevels -- TRC_SAP
08-05 14:14:31.346  7741  8215 I         : BTE_InitTraceLevels -- TRC_SDP
08-05 14:14:31.346  7741  8215 I         : BTE_InitTraceLevels -- TRC_GATT
08-05 14:14:31.346  7741  8215 I         : BTE_InitTraceLevels -- TRC_SMP
08-05 14:14:31.346  7741  8215 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-05 14:14:31.346  7741  8215 I         : BTE_InitTraceLevels -- TRC_BTIF
08-05 14:14:31.346  7741  8215 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-05 14:14:31.566  7741  8215 W bt-l2cap: l2c_link_processs_ble_num_bufs 15
,08-05 14:14:31.566  7741  8215 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa1818b5d 
,08-05 14:14:31.566  7741  8215 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa1818b5d 
,08-05 14:14:31.606   765  3081 D SSRM:n  : SIOP:: AP = 360, PST = 326, CUR = 450
,08-05 14:14:31.786  7741  8185 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 1 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
,08-05 14:14:31.796  7741  8185 E bt-btif : Calling BTA_HhEnable
,08-05 14:14:31.796  7741  8185 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-05 14:14:31.796  7741  8185 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
08-05 14:14:31.796  7741  8185 E BluetoothServiceJni: populateRssiValuesNative
08-05 14:14:31.796  7741  8185 I bluedroid: getModelRssiValues
08-05 14:14:31.796  7741  8185 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-05 14:14:31.796  7741  8185 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-05 14:14:31.796   765   765 D SettingsProvider: name = bluetooth_name
,08-05 14:14:31.796  7741  8185 D BluetoothAdapterProperties: Name is: Note3-1
,08-05 14:14:31.796  7741  8185 D BluetoothAdapterProperties: Scan Mode:20
,08-05 14:14:31.796  7741  8185 D BluetoothAdapterProperties: Discoverable Timeout:120
08-05 14:14:31.796  7741  8185 D BluetoothAdapterProperties: LE Address is:E0:B7:20:3E:93:BC
,08-05 14:14:31.796  7741  8185 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-05 14:14:31.806  7741  8185 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-05 14:14:31.806  7741  8185 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-05 14:14:31.806  7741  8185 E bt-btif : btif_sock_init: !vhci_init
,08-05 14:14:31.806  7741  8185 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-05 14:14:31.806  7741  8185 D IOP_DB_BT: db_open: db_open : handle 3026157584l, read 14063 bytes onto local cache
08-05 14:14:31.806  7741  8185 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-05 14:14:31.806  7741  8185 D IOP_DB_BT: db_query: result 1
08-05 14:14:31.806  7741  8185 I         : iop_db_open: iop_db_open status 0
08-05 14:14:31.806  7741  8185 D bte_conf: Device ID record 1 : primary
,08-05 14:14:31.806  7741  8217 D bt_vendor: op for 2
08-05 14:14:31.806  7741  8185 D bte_conf:   vendorId            = 0075
08-05 14:14:31.806  7741  8217 D bt_vendor: op for 6
08-05 14:14:31.806  7741  8185 D bte_conf:   vendorIdSource      = 0001
,08-05 14:14:31.806  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.806  7741  8185 D bte_conf:   product             = 0100
08-05 14:14:31.806  7741  8185 D bte_conf:   version             = 0200
08-05 14:14:31.806  7741  8185 D bte_conf:   clientExecutableURL = 
,08-05 14:14:31.806  7741  8185 D bte_conf:   serviceDescription  = 
08-05 14:14:31.806  7741  8185 D bte_conf:   documentationURL    = 
08-05 14:14:31.806  7741  8185 D bte_conf: bte_load_did_conf no section named DID2.
,08-05 14:14:31.806  7741  8182 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-05 14:14:31.806  7741  8182 D BluetoothAdapterProperties: ScanMode =  20
08-05 14:14:31.806  7741  8182 D BluetoothAdapterProperties: State =  11
,08-05 14:14:31.806   765  1677 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-05 14:14:31.806  7741  8182 D BluetoothAdapterProperties: Setting state to 12
08-05 14:14:31.806  7741  8182 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-05 14:14:31.816   765  1467 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-05 14:14:31.816   765  1467 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:31.816   765  1467 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:31.816   765  1467 D SettingsProvider: selectionArgs: false
08-05 14:14:31.816   765  1467 D SettingsProvider: selectionArgs: 1002
,08-05 14:14:31.816   765  1467 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:31.816   765  1467 D SettingsProvider: ret = -1
08-05 14:14:31.816  7741  8182 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-05 14:14:31.816  7741  8182 D BluetoothAdapterService: updateAdapterState state is 12
,08-05 14:14:31.816  7741  8217 D bt_upio : proc btwrite assertion
,08-05 14:14:31.816  7741  8217 D bt_vendor: op for 7
,08-05 14:14:31.816  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.816  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.816  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.816   765  1437 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:31.816   765  1437 D ActivityManager: caller:android.app.ApplicationThreadProxy@1e7e6ff1, r.packageName :com.android.bluetooth
,08-05 14:14:31.826   765  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-05 14:14:31.826  7741  8182 D BluetoothAdapterService: Autoconnection is available 
08-05 14:14:31.826  7741  8182 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-05 14:14:31.826  7741  8182 D BluetoothAdapterService: starting service from this receiver
,08-05 14:14:31.836   765  1322 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-05 14:14:31.836   765  1322 D ActivityManager: caller:android.app.ApplicationThreadProxy@3f91a2d, r.packageName :com.android.bluetooth
,08-05 14:14:31.836   765  1058 E BluetoothHeadset: BluetoothHeadset service is binded
,08-05 14:14:31.836  7741  8182 I BluetoothAdapterState: Entering On State from state = 11
08-05 14:14:31.836  7741  8217 E bt_h4   : vendor lib postload completed
,08-05 14:14:31.836  7741  8185 D BluetoothAdapterProperties: Scan Mode:21
,08-05 14:14:31.836  7741  8185 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-05 14:14:31.846  7741  7741 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-05 14:14:31.846  7741  7741 I BluetoothPbapService: Handler(): got msg=1
,08-05 14:14:31.856   765  1322 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-05 14:14:31.856  1316  1332 D BluetoothPbap: onBluetoothStateChange: up=true
,08-05 14:14:31.856  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:31.856  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:31.856  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:31.856  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 14:14:31.856  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:31.856  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:31.856  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:31.856  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 14:14:31.856  7501  7501 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 14:14:31.856   765  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-05 14:14:31.856  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:31.856  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:31.856  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:31.856  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 14:14:31.856  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:31.856  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:31.856  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:31.856  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 14:14:31.866  7741  8217 D bt_vendor: op for 7
,08-05 14:14:31.866  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.866  7741  8185 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-05 14:14:31.866  7501  7501 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 14:14:31.866  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.866  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.866  7741  7755 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-05 14:14:31.866   765  1058 D BluetoothPan: Binding service...
,08-05 14:14:31.866  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.866  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.866  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:31.866  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.866  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.876  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.876  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.876   765  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-05 14:14:31.876   765   765 D BluetoothPan: BluetoothPAN Proxy object connected
,08-05 14:14:31.876  7741  8233 V BluetoothPbapService: PBAP Service initSocket try: 0
08-05 14:14:31.876  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.876  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.876  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:31.876   765  1058 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-05 14:14:31.876  1316  1316 D BluetoothPbap: Proxy object connected
,08-05 14:14:31.876  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.876  7741  8217 D bt_upio : BT_WAKE is asserted already
08-05 14:14:31.876  1316  1316 D PbapServerProfile: Bluetooth service connected
08-05 14:14:31.876  3178  7677 E BluetoothHeadset: BluetoothHeadset service is binded
,08-05 14:14:31.876  1316  1329 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-05 14:14:31.876  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.876  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.876   765  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-05 14:14:31.876  7741  8233 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-05 14:14:31.886  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.886  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.886  7741  8233 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[73]}
,08-05 14:14:31.886  7741  8233 D BluetoothSocket: bindListen(), new LocalSocket 
08-05 14:14:31.886  7741  8233 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-05 14:14:31.886  1316  1316 D BluetoothInputDevice: Proxy object connected
08-05 14:14:31.886  1316  1316 D HidProfile: Bluetooth service connected
08-05 14:14:31.886  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.886  7741  8217 D bt_upio : BT_WAKE is asserted already
08-05 14:14:31.886  7741  8233 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@33091eab
,08-05 14:14:31.886  7741  8233 D BluetoothSocket: channel: 19
08-05 14:14:31.886  7741  8233 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-05 14:14:31.886  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.886  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.886  7741  8217 D bt_vendor: op for 7
,08-05 14:14:31.886  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.886  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.886  7741  8217 D bt_upio : BT_WAKE is asserted already
08-05 14:14:31.886   765  1058 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-05 14:14:31.886  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.886  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.886  1395  1408 E BluetoothHeadset: BluetoothHeadset service is binded
08-05 14:14:31.886  1316  3348 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-05 14:14:31.886  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.886  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.886   765  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-05 14:14:31.896  1316  1316 D BluetoothA2dp: Proxy object connected
08-05 14:14:31.896  1316  1316 D A2dpProfile: Bluetooth service connected
,08-05 14:14:31.896  3178  3187 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-05 14:14:31.896  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.896  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.896   765  1058 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-05 14:14:31.896  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.896  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.896  3178  3178 D BluetoothA2dp: Proxy object connected
,08-05 14:14:31.896  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.896  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.896  7741  8217 D bt_vendor: op for 7
,08-05 14:14:31.896  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.896   765  1058 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-05 14:14:31.896  1395  1415 E BluetoothHeadset: BluetoothHeadset service is binded
,08-05 14:14:31.896  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.896  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.896   765  1058 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-05 14:14:31.906  1425  1675 E BluetoothHeadset: BluetoothHeadset service is binded
,08-05 14:14:31.906  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.906  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.906   765  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-05 14:14:31.906  1316  1332 E BluetoothHeadset: BluetoothHeadset service is binded
08-05 14:14:31.906  1316  1316 D HeadsetProfile: Bluetooth service connected
08-05 14:14:31.906  1316  1329 D Bluetoothsap: onBluetoothStateChange: up=true
08-05 14:14:31.906  1316  1329 D Bluetoothsap: Binding service...
,08-05 14:14:31.906  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.906  7741  8217 D bt_upio : BT_WAKE is asserted already
08-05 14:14:31.906  1316  1329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-05 14:14:31.906   765  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-05 14:14:31.906  1316  1329 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-05 14:14:31.906   765  1058 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-05 14:14:31.906   765  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-05 14:14:31.906   765   765 D BluetoothA2dp: Proxy object connected
,08-05 14:14:31.906  1316  1332 D BluetoothPan: Binding service...
08-05 14:14:31.906  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.906  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.906  1316  1316 D Bluetoothsap: BluetoothSAP Proxy object connected
08-05 14:14:31.906  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.906  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.906   765  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-05 14:14:31.906  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.906  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.906  1316  1316 D SapProfile: Bluetooth service connected
08-05 14:14:31.906  1316  1316 D Bluetoothsap: getConnectedDevices()
,08-05 14:14:31.906  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.906  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.906  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.906  7741  8217 D bt_upio : BT_WAKE is asserted already
08-05 14:14:31.906  1316  1316 D BluetoothPan: BluetoothPAN Proxy object connected
,08-05 14:14:31.906  1316  1316 D PanProfile: Bluetooth service connected
08-05 14:14:31.906   765  1058 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-05 14:14:31.916  1395  1408 E BluetoothHeadset: BluetoothHeadset service is binded
,08-05 14:14:31.916  1316  3348 D BluetoothMap: onBluetoothStateChange: up=true
,08-05 14:14:31.916   765  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-05 14:14:31.916   765  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-05 14:14:31.916  1316  1316 D BluetoothMap: Proxy object connected
,08-05 14:14:31.916  1316  1316 D MapProfile: Bluetooth service connected
08-05 14:14:31.916   765   765 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:31.916   765   765 I InputMethodManagerService: [BT Setting State] State =12
08-05 14:14:31.916   765   765 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-05 14:14:31.916  1395  1395 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@36dfeaec, true
,08-05 14:14:31.916  1395  1395 D BluetoothHeadset: registerMessageListener
,08-05 14:14:31.916  1196  1196 D BluetoothTile:  onBluetoothStateChange:
08-05 14:14:31.916  1739  1739 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-05 14:14:31.916  1196  1196 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-05 14:14:31.916  1196  1196 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-05 14:14:31.916  1316  1316 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-05 14:14:31.916  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:31.926  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:31.926   765   783 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
08-05 14:14:31.926   765  1677 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-05 14:14:31.926  7661  7661 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:31.926  1196  1196 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,08-05 14:14:31.926   765  1706 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-05 14:14:31.926  7741  7758 D HeadsetService: registerMessageListener
08-05 14:14:31.926   765  1058 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-05 14:14:31.926   765  1706 D ActivityManager: caller:android.app.ApplicationThreadProxy@100a8be6, r.packageName :com.google.android.gms
,08-05 14:14:31.926  7741  7758 D HeadsetService: registerMessageListener
08-05 14:14:31.926  7741  8208 D HeadsetStateMachine: Disconnected process message: 70
,08-05 14:14:31.926  1395  1395 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-05 14:14:31.926  7741  8208 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@257c5908
,08-05 14:14:31.926  1395  1395 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-05 14:14:31.926  1196  1597 D BluetoothTile:  handleUpdatestate:false name:null
08-05 14:14:31.926  1196  1597 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-05 14:14:31.926  1316  1316 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,08-05 14:14:31.936  7741  8208 D HeadsetStateMachine: Disconnected process message: 9
08-05 14:14:31.936  1316  1316 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-05 14:14:31.936  7741  8208 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-05 14:14:31.936  7741  8246 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-05 14:14:31.936  7741  8246 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-05 14:14:31.936   313  1159 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-05 14:14:31.936   313  1159 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-05 14:14:31.936   313  1159 V voice   : voice_set_parameters: exit with code(-2)
08-05 14:14:31.936   313  1159 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-05 14:14:31.936   313  1159 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-05 14:14:31.936   313  1159 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-05 14:14:31.936   313  1159 V audio_hw_primary: adev_set_parameters: exit
,08-05 14:14:31.946  7741  8208 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-05 14:14:31.946  7741  8246 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-05 14:14:31.946  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.946  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.946  7741  8246 D BluetoothSocket: bindListen(), new LocalSocket 
08-05 14:14:31.946  1316  1316 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-05 14:14:31.946   765  1237 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-05 14:14:31.946  7741  8246 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-05 14:14:31.946  7741  8246 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d4288a1
08-05 14:14:31.946  7741  8246 D BluetoothSocket: channel: 5
,08-05 14:14:31.946   765  1237 D ActivityManager: caller:android.app.ApplicationThreadProxy@c83f97d, r.packageName :com.android.settings
,08-05 14:14:31.956  1316  1316 D DockEventReceiver: finishStartingService: stopping service
,08-05 14:14:31.956  1316  1316 D BluetoothNotiBroadcastReceiver: onReceive
,08-05 14:14:31.966  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2d51de
,08-05 14:14:31.966  7741  7741 D BtConfig.SecureMode: isSecureModeOn:false
,08-05 14:14:31.966   765  1144 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-05 14:14:31.966   765  1144 D ActivityManager: caller:android.app.ApplicationThreadProxy@352c9cc3, r.packageName :com.android.bluetooth
,08-05 14:14:31.976  1903  1903 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-05 14:14:31.976   765  1289 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-05 14:14:31.976   765  1289 D ActivityManager: caller:android.app.ApplicationThreadProxy@32dbb079, r.packageName :com.google.android.gms
,08-05 14:14:31.976  1903  1903 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-05 14:14:31.976  1903  8252 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-05 14:14:31.986   765  1289 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-05 14:14:31.996  7741  8256 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-05 14:14:31.996   765  1322 D ActivityManager: caller:android.app.ApplicationThreadProxy@299df5b1, r.packageName :com.google.android.gms
,08-05 14:14:31.996  7741  8217 D bt_vendor: op for 7
08-05 14:14:31.996  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:31.996  7741  8256 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-05 14:14:31.996  7741  8256 D BluetoothSocket: bindListen(), new LocalSocket 
08-05 14:14:31.996  7741  8256 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-05 14:14:31.996  7741  8256 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b5e0ddd
08-05 14:14:31.996  7741  8256 D BluetoothSocket: channel: 12
08-05 14:14:31.996  7741  8256 I BtOppRfcommListener: Accept thread started.
,08-05 14:14:32.006  1903  8252 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-05 14:14:32.176   305   305 E SMD     : DCD ON
,08-05 14:14:33.346  7501  7570 D BluetoothAdapter: disable()
,08-05 14:14:33.346   765  1289 D SettingsProvider: name = bluetooth_on
,08-05 14:14:33.356  7741  8182 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-05 14:14:33.356  7741  8182 D BluetoothAdapterProperties: Setting state to 13
08-05 14:14:33.356  7741  8182 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-05 14:14:33.356  7741  8182 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-05 14:14:33.356  7741  8182 D BluetoothAdapterService: updateAdapterState state is 13
,08-05 14:14:33.356   765  3410 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:33.356   765  3410 D ActivityManager: caller:android.app.ApplicationThreadProxy@7745617, r.packageName :com.android.bluetooth
,08-05 14:14:33.366  7741  7741 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-05 14:14:33.366  7741  7741 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@15336d52, channel: 19, state: LISTENING
,08-05 14:14:33.366  7741  7741 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@15336d52, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@33091eab, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@11a0b823mSocket: android.net.LocalSocket@79b4120 impl:android.net.LocalSocketImpl@9b2aad9 fd:FileDescriptor[73]
08-05 14:14:33.366  7741  7741 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@79b4120 impl:android.net.LocalSocketImpl@9b2aad9 fd:FileDescriptor[73]
,08-05 14:14:33.366  7741  8182 D BluetoothAdapterService: Autoconnection is available 
,08-05 14:14:33.366  7741  8182 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-05 14:14:33.366  7741  8182 D BluetoothAdapterService: terminating service from this receiver
,08-05 14:14:33.366  7741  8182 D BluetoothAdapterProperties: onBluetoothDisable()
,08-05 14:14:33.366   765  1578 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-05 14:14:33.366  7741  8182 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-05 14:14:33.366  7741  8217 D bt_vendor: op for 7
08-05 14:14:33.366  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:33.366  7741  8217 D bt_vendor: op for 7
,08-05 14:14:33.366  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:33.376  7741  8217 D bt_vendor: op for 7
,08-05 14:14:33.376  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:33.376  7741  8185 D BluetoothAdapterProperties: Scan Mode:20
,08-05 14:14:33.376  7741  8182 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-05 14:14:33.376  7741  8182 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-05 14:14:33.376  7741  8182 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-05 14:14:33.376  7741  8182 E bt-btif : cmd socket is not created
,08-05 14:14:33.376  7741  8256 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-05 14:14:33.376  7741  8215 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-05 14:14:33.376  7741  8217 D bt_vendor: op for 7
08-05 14:14:33.376  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:33.386  7741  8215 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-05 14:14:33.386  7741  8215 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-05 14:14:33.386  7741  8215 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 14:14:33.386  7741  8215 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 14:14:33.386  7741  8182 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-05 14:14:33.386  7741  8217 D bt_vendor: op for 7
,08-05 14:14:33.386  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:33.386  7741  8217 D bt_vendor: op for 7
,08-05 14:14:33.386  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:33.386  7741  8217 D bt_vendor: op for 7
,08-05 14:14:33.386  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:33.386  7741  8217 D bt_vendor: op for 7
,08-05 14:14:33.386  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:33.396  7741  8217 D bt_vendor: op for 7
,08-05 14:14:33.396  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:33.396  7741  8217 D bt_vendor: op for 7
08-05 14:14:33.396  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:33.396  7741  8217 D bt_vendor: op for 7
,08-05 14:14:33.396  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:33.396  7741  8217 D bt_vendor: op for 7
,08-05 14:14:33.396  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:33.396  7741  8217 D bt_vendor: op for 7
08-05 14:14:33.396  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:33.396  7741  8217 D bt_vendor: op for 7
,08-05 14:14:33.396  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:33.396  7741  8217 D bt_vendor: op for 7
08-05 14:14:33.396  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:33.406   765   765 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-05 14:14:33.406  1196  1196 D BluetoothTile:  onBluetoothStateChange:
,08-05 14:14:33.406   765   765 I InputMethodManagerService: [BT Setting State] State =13
,08-05 14:14:33.416  7501  7501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 14:14:33.416  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:33.416  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:33.416  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:33.416  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 14:14:33.416  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 14:14:33.416  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:33.416  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:33.416  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 14:14:33.416  1196  1196 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-05 14:14:33.416  1196  1196 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-05 14:14:33.416  1196  1597 D BluetoothTile:  handleUpdatestate:false name:null
,08-05 14:14:33.416  7501  7501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-05 14:14:33.416  7501  7501 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 14:14:33.416  1196  1597 D BluetoothTile:  handleUpdatestate:false name:null
,08-05 14:14:33.416  1196  1597 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-05 14:14:33.416   765  1144 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,08-05 14:14:33.426   765  1578 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-05 14:14:33.426  7501  7501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 14:14:33.426  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:33.426  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:33.426  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:33.426  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 14:14:33.426  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-05 14:14:33.426  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:33.426  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:33.426  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 14:14:33.426  7501  7501 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-05 14:14:33.426  7501  7501 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:33.426  1196  1196 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,08-05 14:14:33.426   765  1706 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-05 14:14:33.426   765  1706 D ActivityManager: caller:android.app.ApplicationThreadProxy@b8dda04, r.packageName :com.google.android.gms
,08-05 14:14:33.436  7741  7741 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@183cb37f, channel: 5, state: LISTENING
,08-05 14:14:33.436  7741  7741 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@183cb37f, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3d4288a1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@23c34f4cmSocket: android.net.LocalSocket@1d1a1b95 impl:android.net.LocalSocketImpl@2c354aa fd:FileDescriptor[75]
08-05 14:14:33.436  7741  7741 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1d1a1b95 impl:android.net.LocalSocketImpl@2c354aa fd:FileDescriptor[75]
,08-05 14:14:33.436  7741  7741 I BtOppRfcommListener: stopping Accept Thread
08-05 14:14:33.436  7741  7741 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@1673089b, channel: 12, state: LISTENING
08-05 14:14:33.436  7741  7741 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@1673089b, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b5e0ddd, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1e7c1438mSocket: android.net.LocalSocket@244ddc11 impl:android.net.LocalSocketImpl@345a1176 fd:FileDescriptor[79]
,08-05 14:14:33.436  7741  7741 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@244ddc11 impl:android.net.LocalSocketImpl@345a1176 fd:FileDescriptor[79]
,08-05 14:14:33.436  7741  8256 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-05 14:14:33.436  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:33.436  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:33.446  7661  7661 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,08-05 14:14:33.446  1739  1739 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-05 14:14:33.446  1316  1316 D BluetoothPbap: Proxy object disconnected
,08-05 14:14:33.446  1316  1316 D PbapServerProfile: Bluetooth service disconnected
08-05 14:14:33.446  1316  1316 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-05 14:14:33.446  1316  1316 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-05 14:14:33.446   765  1467 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-05 14:14:33.446   765  1467 D ActivityManager: caller:android.app.ApplicationThreadProxy@24b8ea22, r.packageName :com.android.settings
,08-05 14:14:33.466  1316  1316 D DockEventReceiver: finishStartingService: stopping service
,08-05 14:14:33.466  1316  1316 D BluetoothNotiBroadcastReceiver: onReceive
,08-05 14:14:33.476  1903  1903 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-05 14:14:33.476  1903  1903 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-05 14:14:33.546  7741  8215 W bt-l2cap: btif_mce_execute_service enable:0
08-05 14:14:33.546  7741  8215 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 14:14:33.546  7741  8215 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 14:14:33.546  7741  8215 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 14:14:33.546  7741  8215 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 14:14:33.546  7741  8215 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 14:14:33.546  7741  8215 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-05 14:14:33.546  7741  8215 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-05 14:14:33.546  7741  8215 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-05 14:14:33.546  7741  8215 W bt-btif : ag scb idx 1 not allocated
08-05 14:14:33.546  7741  8215 W bt-btif : ag scb idx 2 not allocated
08-05 14:14:33.546  7741  8215 E bt-btif : BTA AG is already disabled, ignoring ...
08-05 14:14:33.546  7741  8217 D bt_vendor: op for 6
08-05 14:14:33.546  7741  8217 D bt_vendor: op for 7
08-05 14:14:33.546  7741  8217 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:33.546  7741  8218 D bt_userial: RX termination
08-05 14:14:33.546  7741  8218 W bt_userial: select_read return size <=0:-1, exiting userial_read_thread
08-05 14:14:33.546  7741  8218 D bt_userial: Leaving userial_read_thread()
08-05 14:14:33.546  7741  8185 D bt_userial: userial_close_reader Joined userial reader thread: 0
08-05 14:14:33.546  7741  8217 D bt_vendor: op for 9
08-05 14:14:33.546  7741  8217 D bt_hwcfg: hw_epilog_process
08-05 14:14:33.546  7741  8185 D bt_vendor: op for 4
08-05 14:14:33.546  7741  8185 I bt_userial_vendor: device fd = 66 close
,08-05 14:14:33.546  7741  8185 D bt_vendor: op for 0
,08-05 14:14:33.546  7741  8185 D bt_upio : upio_set_bluetooth_power(on: 0)
08-05 14:14:33.546  7741  8185 D bt_upio : is_emulator_context : 0
08-05 14:14:33.546  7741  8185 D bt_upio : is_rfkill_disabled ? [0]
,08-05 14:14:33.546  7741  8185 D bt_vendor: cleanup
,08-05 14:14:33.546  7741  8215 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-05 14:14:33.546  7741  8185 I GKI_LINUX: GKI_exit_task 0 done
08-05 14:14:33.546  7741  8185 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-05 14:14:33.546  7741  8182 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-05 14:14:33.546  7741  8182 D BtConfig.SecureMode: isSecureModeOn:false
08-05 14:14:33.546  7741  8182 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-05 14:14:33.546  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-05 14:14:33.546  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-05 14:14:33.546  7741  8182 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
08-05 14:14:33.546   765   784 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:33.546   765   784 D ActivityManager: caller:android.app.ApplicationThreadProxy@e109270, r.packageName :com.android.bluetooth
,08-05 14:14:33.556  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-05 14:14:33.556  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-05 14:14:33.556  7741  8182 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-05 14:14:33.556   765  1467 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:33.556   765  1467 D ActivityManager: caller:android.app.ApplicationThreadProxy@3c4ca9e9, r.packageName :com.android.bluetooth
08-05 14:14:33.556  7741  7741 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-05 14:14:33.556  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-05 14:14:33.556  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-05 14:14:33.556  7741  8182 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-05 14:14:33.556   765  3349 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:33.556  7741  7741 D BtGatt.GattService: Received stop request...Stopping profile...
08-05 14:14:33.556   765  3349 D ActivityManager: caller:android.app.ApplicationThreadProxy@1b9f866e, r.packageName :com.android.bluetooth
,08-05 14:14:33.556  7741  7741 D BtGatt.GattService: stop()
08-05 14:14:33.556  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-05 14:14:33.556  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-05 14:14:33.556  7741  8182 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-05 14:14:33.556  7741  7741 D BtGatt.AdvertiseManager: advertise clients cleared
08-05 14:14:33.556   765  1677 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:33.556   765  1677 D ActivityManager: caller:android.app.ApplicationThreadProxy@4f5f10f, r.packageName :com.android.bluetooth
,08-05 14:14:33.556  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2d51de
08-05 14:14:33.556  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-05 14:14:33.556  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-05 14:14:33.556  7741  8182 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-05 14:14:33.556   765  1437 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:33.556   765  1437 D ActivityManager: caller:android.app.ApplicationThreadProxy@cc4659c, r.packageName :com.android.bluetooth
08-05 14:14:33.556  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-05 14:14:33.556  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-05 14:14:33.556  7741  8182 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-05 14:14:33.556   765   783 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:33.556   765   783 D ActivityManager: caller:android.app.ApplicationThreadProxy@393cfba5, r.packageName :com.android.bluetooth
08-05 14:14:33.556  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-05 14:14:33.556  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-05 14:14:33.556  7741  8182 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-05 14:14:33.556   765  1144 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:33.556   765  1144 D ActivityManager: caller:android.app.ApplicationThreadProxy@3a419b7a, r.packageName :com.android.bluetooth
08-05 14:14:33.556  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-05 14:14:33.556  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-05 14:14:33.556  7741  8182 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-05 14:14:33.556   765  1706 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:33.556   765  1706 D ActivityManager: caller:android.app.ApplicationThreadProxy@5aa8f2b, r.packageName :com.android.bluetooth
08-05 14:14:33.556  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-05 14:14:33.556  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-05 14:14:33.556  7741  8182 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-05 14:14:33.556  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-05 14:14:33.556  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-05 14:14:33.556  7741  8182 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-05 14:14:33.556  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-05 14:14:33.556  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-05 14:14:33.556  7741  8182 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-05 14:14:33.556  7741  8182 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-05 14:14:33.556  7741  8182 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-05 14:14:33.556  7741  8182 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-05 14:14:33.556  7741  8182 D BluetoothAdapterState: Stopping profile services that were post enabled
,08-05 14:14:33.556  7741  7741 E BluetoothAdapterService(170742238): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-05 14:14:33.556  7741  7741 D HeadsetService: Received stop request...Stopping profile...
08-05 14:14:33.556  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2d51de
,08-05 14:14:33.556   765   765 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-05 14:14:33.556  1316  1316 D HeadsetProfile: Bluetooth service disconnected
,08-05 14:14:33.556  7661  7661 W BluetoothHeadset: Proxy not attached to service
,08-05 14:14:33.556  7741  7741 E BluetoothAdapterService(170742238): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-05 14:14:33.556  7741  7741 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-05 14:14:33.556  7741  7741 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-05 14:14:33.566  7741  7741 D A2dpService: Received stop request...Stopping profile...
08-05 14:14:33.566  7741  7741 V Avrcp   : doQuit
08-05 14:14:33.566  7741  8210 D A2dpStateMachine: Exit Disconnected: -1
,08-05 14:14:33.566  7741  7741 D Avrcp   : Unregistering previous receiver
,08-05 14:14:33.566  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2d51de
,08-05 14:14:33.566  3178  3178 D BluetoothA2dp: Proxy object disconnected
08-05 14:14:33.566   765   765 D BluetoothA2dp: Proxy object disconnected
08-05 14:14:33.566   765   765 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,08-05 14:14:33.566  1316  1316 D BluetoothA2dp: Proxy object disconnected
08-05 14:14:33.566  1316  1316 D A2dpProfile: Bluetooth service disconnected
08-05 14:14:33.566  7741  7741 D HidService: Received stop request...Stopping profile...
08-05 14:14:33.566  7741  7741 D HidService: Stopping Bluetooth HidService
08-05 14:14:33.566  7741  7741 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-05 14:14:33.566  7741  7741 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-05 14:14:33.566  7741  7741 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-05 14:14:33.566  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2d51de
,08-05 14:14:33.566  1316  1316 D BluetoothInputDevice: Proxy object disconnected
08-05 14:14:33.566  1316  1316 D HidProfile: Bluetooth service disconnected
,08-05 14:14:33.566  7741  7741 D HealthService: Received stop request...Stopping profile...
08-05 14:14:33.566  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2d51de
,08-05 14:14:33.566  7741  7741 D PanService: Received stop request...Stopping profile...
08-05 14:14:33.566  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2d51de
,08-05 14:14:33.566  1316  1316 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-05 14:14:33.566  1316  1316 D PanProfile: Bluetooth service disconnected
,08-05 14:14:33.566  7741  7741 D BluetoothMapService: Received stop request...Stopping profile...
,08-05 14:14:33.566   765   765 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-05 14:14:33.566  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2d51de
,08-05 14:14:33.566  1316  1316 D BluetoothMap: Proxy object disconnected
08-05 14:14:33.566  1316  1316 D MapProfile: Bluetooth service disconnected
,08-05 14:14:33.566  7741  7741 D SapService: Received stop request...Stopping profile...
08-05 14:14:33.566  7741  7741 D SapService: Stopping Bluetooth SapService
08-05 14:14:33.566  7741  7741 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@a2d51de
,08-05 14:14:33.566  1316  1316 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-05 14:14:33.566  1316  1316 D SapProfile: Bluetooth service disconnected
,08-05 14:14:33.576  7741  7741 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-05 14:14:33.576  7741  7741 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-05 14:14:33.576  7741  7741 E BluetoothAdapterService(170742238): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-05 14:14:33.576  7741  7741 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-05 14:14:33.576  7741  7741 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-05 14:14:33.576  7741  7741 D BluetoothA2dp: Proxy object disconnected
08-05 14:14:33.576  7741  7741 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-05 14:14:33.576  7741  8211 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-05 14:14:33.576  7741  7741 I GKI_LINUX: GKI_exit_task 2 done
08-05 14:14:33.576  7741  7741 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-05 14:14:33.576  7741  7741 V Avrcp   : cleanup
,08-05 14:14:33.576  7741  7741 E BluetoothAdapterService(170742238): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-05 14:14:33.576  7741  7741 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-05 14:14:33.576  7741  7741 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-05 14:14:33.576  7741  7741 E BluetoothAdapterService(170742238): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-05 14:14:33.576  7741  7741 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-05 14:14:33.576  7741  7741 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-05 14:14:33.576  7741  7741 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-05 14:14:33.576  7741  7741 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-05 14:14:33.576  7741  7741 E BluetoothAdapterService(170742238): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-05 14:14:33.576  7741  7741 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-05 14:14:33.576  7741  7741 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-05 14:14:33.576  7741  7741 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-05 14:14:33.576  7741  7741 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-05 14:14:33.576  7741  7741 E BluetoothAdapterService(170742238): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-05 14:14:33.576  7741  7741 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-05 14:14:33.576  7741  7741 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-05 14:14:33.576  7741  7741 E BluetoothAdapterService(170742238): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-05 14:14:33.576  7741  8182 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-05 14:14:33.576  7741  8182 D BluetoothAdapterProperties: Setting state to 10
08-05 14:14:33.576  7741  8182 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-05 14:14:33.576  7741  8182 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-05 14:14:33.576  7741  8182 D BluetoothAdapterService: updateAdapterState state is 10
,08-05 14:14:33.576  7741  7741 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-05 14:14:33.576  7741  7741 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-05 14:14:33.576  1316  1329 D BluetoothPbap: onBluetoothStateChange: up=false
08-05 14:14:33.576  7741  8182 D BluetoothAdapterService: Autoconnection is available 
08-05 14:14:33.576  7741  8182 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-05 14:14:33.576  7741  8182 I BluetoothAdapterState: Entering OffState
,08-05 14:14:33.576  7741  7758 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-05 14:14:33.576  1316  3348 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-05 14:14:33.576  1316  1332 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-05 14:14:33.576  3178  3187 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-05 14:14:33.586  1316  3348 D Bluetoothsap: onBluetoothStateChange: up=false
,08-05 14:14:33.586  1316  3348 D Bluetoothsap: Unbinding service...
08-05 14:14:33.586   765  1058 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-05 14:14:33.586  1316  1329 D BluetoothMap: onBluetoothStateChange: up=false
,08-05 14:14:33.586   765  1058 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 14 receivers.
,08-05 14:14:33.586   765  1058 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-05 14:14:33.586  1739  1739 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-05 14:14:33.586  1196  1196 D BluetoothAdapter: 972163852: getState() :  mService = null. Returning STATE_OFF
08-05 14:14:33.586  1196  1196 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-05 14:14:33.586  1196  1196 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:33.586  1196  1196 D BluetoothAdapter: 972163852: getState() :  mService = null. Returning STATE_OFF
08-05 14:14:33.586  1196  1196 D BluetoothAdapter: 972163852: getState() :  mService = null. Returning STATE_OFF
,08-05 14:14:33.586   765   765 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-05 14:14:33.596   765   765 I InputMethodManagerService: [BT Setting State] State =10
08-05 14:14:33.596   765   765 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-05 14:14:33.596   765  1578 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,08-05 14:14:33.596  1196  1597 D BluetoothAdapter: 972163852: getState() :  mService = null. Returning STATE_OFF
,08-05 14:14:33.596  1196  1597 D BluetoothAdapter: 972163852: getState() :  mService = null. Returning STATE_OFF
08-05 14:14:33.596  1196  1597 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-05 14:14:33.596  1903  2407 D BluetoothAdapter: 349785975: getState() :  mService = null. Returning STATE_OFF
08-05 14:14:33.596  1903  2407 D BluetoothAdapter: 349785975: getState() :  mService = null. Returning STATE_OFF
,08-05 14:14:33.596  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:33.596   765   783 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-05 14:14:33.596  7741  8185 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-05 14:14:33.596   765   783 D ActivityManager: caller:android.app.ApplicationThreadProxy@7803f88, r.packageName :com.google.android.gms
,08-05 14:14:33.596  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:33.596   765  3410 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-05 14:14:33.596  1196  1196 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
08-05 14:14:33.596  1196  1196 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,08-05 14:14:33.596  7741  7741 I GKI_LINUX: GKI_exit_task 1 done
08-05 14:14:33.596  7741  7741 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-05 14:14:33.596  7741  7741 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-05 14:14:33.596  7661  7661 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,08-05 14:14:33.596  1316  1316 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:33.596  7741  7741 I art     : System.exit called, status: 0
08-05 14:14:33.596  7741  7741 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-05 14:14:33.606  1316  1316 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-05 14:14:33.606   765  1677 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-05 14:14:33.606   765  1677 D ActivityManager: caller:android.app.ApplicationThreadProxy@11bdf546, r.packageName :com.android.settings
,08-05 14:14:33.606  1316  1316 D DockEventReceiver: finishStartingService: stopping service
,08-05 14:14:33.616  1316  1316 D BluetoothNotiBroadcastReceiver: onReceive
,08-05 14:14:33.646   765  1647 I ActivityManager: Process com.android.bluetooth (pid 7741)(adj 0) has died(183,1576)
,08-05 14:14:33.656  1903  1903 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-05 14:14:33.656   765  1467 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-05 14:14:33.656   765  1467 D ActivityManager: caller:android.app.ApplicationThreadProxy@14541fd2, r.packageName :com.google.android.gms
,08-05 14:14:33.656  1903  8288 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-05 14:14:33.656  1903  1903 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-05 14:14:33.666   765  1437 D ActivityManager: caller:android.app.ApplicationThreadProxy@c6577a0, r.packageName :com.google.android.gms
,08-05 14:14:33.666  1903  8288 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-05 14:14:34.646   765   784 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-05 14:14:34.656   765   784 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,08-05 14:14:34.656   765   784 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,08-05 14:14:34.656   765   765 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-05 14:14:34.656   765   765 I MotionRecognitionService: Plugged
,08-05 14:14:34.656   765   765 I MotionRecognitionService: setPowerConnected  = true
,08-05 14:14:34.656   765   784 D BatteryService: stay LED for fully charged
,08-05 14:14:34.666  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-05 14:14:34.666  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,08-05 14:14:34.666  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-05 14:14:34.666  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-05 14:14:34.666  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-05 14:14:34.666  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-05 14:14:35.176   305   305 E SMD     : DCD ON
,08-05 14:14:36.457  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
,08-05 14:14:36.457  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:37.297   765  3114 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-05 14:14:38.177   305   305 E SMD     : DCD ON
,08-05 14:14:39.466  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-05 14:14:39.466  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@260aaaba added. We now have 6 listener(s)
,08-05 14:14:39.466  7501  7570 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 14:14:39.466  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-05 14:14:39.476  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@386b8d6b added. We now have 7 listener(s)
,08-05 14:14:39.476  7501  7570 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 14:14:39.476  7501  7570 I System.out: IsBluetoothEnabled
,08-05 14:14:39.476  7501  7570 D BluetoothAdapter: disable()
08-05 14:14:39.476   765  1237 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-05 14:14:39.476  7501  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:39.476  7501  7570 D BluetoothAdapter: enable()
08-05 14:14:39.476   765  1452 W ActivityManager: Permission Denial: getCurrentUser() from pid=7501, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,08-05 14:14:39.486   765  1452 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-05 14:14:39.486   765  1452 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7501, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-05 14:14:39.486   765  1452 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
08-05 14:14:39.486   765  1452 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
08-05 14:14:39.486   765  1452 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
08-05 14:14:39.486   765  1452 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-05 14:14:39.486   765  1452 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-05 14:14:39.486   765  1452 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-05 14:14:39.486   765  1452 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-05 14:14:39.486   765  1452 D SettingsProvider: name = bluetooth_on
,08-05 14:14:39.486   765  1058 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-05 14:14:39.486   765  1058 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-05 14:14:39.486   765  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-05 14:14:39.486   765  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:39.486   765  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:39.486   765  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:14:39.486   765  1058 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:14:39.537  8298  8298 E Zygote  : MountEmulatedStorage()
,08-05 14:14:39.537  8298  8298 E Zygote  : v2
08-05 14:14:39.537  8298  8298 I libpersona: KNOX_SDCARD checking this for 1002
,08-05 14:14:39.537  8298  8298 I libpersona: KNOX_SDCARD not a persona
,08-05 14:14:39.547   765  1058 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=8298 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-05 14:14:39.547  8298  8298 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 14:14:39.547  8298  8298 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-05 14:14:39.557  8298  8298 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-05 14:14:39.576  8298  8298 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:14:39.576  8298  8298 D ActivityThread: Added TimaKeyStore provider
,08-05 14:14:39.586  8298  8298 D ResourcesManager: creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,08-05 14:14:39.596  8298  8298 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-05 14:14:39.596  8298  8298 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-05 14:14:39.617  8298  8298 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-05 14:14:39.636  8298  8298 D BtSettings.ProfileConfig: Adding GattService
,08-05 14:14:39.636  8298  8298 D BtSettings.ProfileConfig: Adding HeadsetService
08-05 14:14:39.636  8298  8298 D BtSettings.ProfileConfig: Adding A2dpService
08-05 14:14:39.636  8298  8298 D BtSettings.ProfileConfig: Adding HidService
,08-05 14:14:39.646  8298  8298 D BtSettings.ProfileConfig: Adding HealthService
08-05 14:14:39.646  8298  8298 D BtSettings.ProfileConfig: Adding PanService
08-05 14:14:39.646  8298  8298 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-05 14:14:39.646  8298  8298 D BtSettings.ProfileConfig: Adding SapService
08-05 14:14:39.646  8298  8298 D BtSettings.ProfileConfig: Adding HeadsetClientService
,08-05 14:14:39.646  8298  8298 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-05 14:14:39.646  8298  8298 D BtSettings.ProfileConfig: Adding SapClientService
08-05 14:14:39.646  8298  8298 D BtSettings.ProfileConfig: Adding HidDevService
08-05 14:14:39.646  8298  8298 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-05 14:14:39.646   765  1437 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-05 14:14:39.646   765  1437 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:39.646   765  1437 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:39.646   765  1437 D SettingsProvider: selectionArgs: false
08-05 14:14:39.646   765  1437 D SettingsProvider: selectionArgs: 1002
08-05 14:14:39.646   765  1437 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:39.646   765  1437 D SettingsProvider: ret = -1
,08-05 14:14:39.646   765   783 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-05 14:14:39.646   765   783 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:39.646   765   783 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:39.646   765   783 D SettingsProvider: selectionArgs: false
08-05 14:14:39.646   765   783 D SettingsProvider: selectionArgs: 1002
08-05 14:14:39.646   765   783 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:39.646   765   783 D SettingsProvider: ret = -1
,08-05 14:14:39.646   765  1647 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-05 14:14:39.646   765  1647 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:39.646   765  1647 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:39.646   765  1647 D SettingsProvider: selectionArgs: false
08-05 14:14:39.646   765  1647 D SettingsProvider: selectionArgs: 1002
08-05 14:14:39.646   765  1647 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:39.646   765  1647 D SettingsProvider: ret = -1
08-05 14:14:39.646   765  1526 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-05 14:14:39.646   765  1526 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:39.646   765  1526 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:39.646   765  1526 D SettingsProvider: selectionArgs: false
,08-05 14:14:39.646   765  1526 D SettingsProvider: selectionArgs: 1002
08-05 14:14:39.646   765  1526 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:39.646   765  1526 D SettingsProvider: ret = -1
08-05 14:14:39.646   765  1289 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-05 14:14:39.646   765  1289 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:39.646   765  1289 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:39.646   765  1289 D SettingsProvider: selectionArgs: false
,08-05 14:14:39.646   765  1289 D SettingsProvider: selectionArgs: 1002
08-05 14:14:39.656   765  1289 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:39.656   765  1289 D SettingsProvider: ret = -1
08-05 14:14:39.656   765  1578 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-05 14:14:39.656   765  1578 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:39.656   765  1578 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:39.656   765  1578 D SettingsProvider: selectionArgs: false
08-05 14:14:39.656   765  1578 D SettingsProvider: selectionArgs: 1002
08-05 14:14:39.656   765  1578 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:39.656   765  1578 D SettingsProvider: ret = -1
,08-05 14:14:39.656   765  1322 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-05 14:14:39.656   765  1322 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:39.656   765  1322 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:39.656   765  1322 D SettingsProvider: selectionArgs: false
08-05 14:14:39.656   765  1322 D SettingsProvider: selectionArgs: 1002
08-05 14:14:39.656   765  1322 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:39.656   765  1322 D SettingsProvider: ret = -1
,08-05 14:14:39.656   765  3410 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-05 14:14:39.656   765  3410 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:39.656   765  3410 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:39.656   765  3410 D SettingsProvider: selectionArgs: false
08-05 14:14:39.656   765  3410 D SettingsProvider: selectionArgs: 1002
08-05 14:14:39.656   765  3410 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-05 14:14:39.656   765  3410 D SettingsProvider: ret = -1
08-05 14:14:39.656   765  1677 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-05 14:14:39.656   765  1677 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:39.656   765  1677 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:39.656   765  1677 D SettingsProvider: selectionArgs: false
08-05 14:14:39.656   765  1677 D SettingsProvider: selectionArgs: 1002
08-05 14:14:39.656   765  1677 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:39.656   765  1677 D SettingsProvider: ret = -1
,08-05 14:14:39.656   765  1467 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-05 14:14:39.656   765  1467 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:39.656   765  1467 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:39.656   765  1467 D SettingsProvider: selectionArgs: false
08-05 14:14:39.656   765  1467 D SettingsProvider: selectionArgs: 1002
08-05 14:14:39.656   765  1467 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:39.656   765  1467 D SettingsProvider: ret = -1
,08-05 14:14:39.656   765  1706 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-05 14:14:39.656   765  1706 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:39.656   765  1706 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:39.656   765  1706 D SettingsProvider: selectionArgs: false
08-05 14:14:39.656   765  1706 D SettingsProvider: selectionArgs: 1002
08-05 14:14:39.656   765  1706 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-05 14:14:39.656   765  1706 D SettingsProvider: ret = -1
08-05 14:14:39.656   765  3349 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-05 14:14:39.656   765  3349 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:39.656   765  3349 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:39.656   765  3349 D SettingsProvider: selectionArgs: false
08-05 14:14:39.656   765  3349 D SettingsProvider: selectionArgs: 1002
08-05 14:14:39.656   765  3349 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-05 14:14:39.656   765  3349 D SettingsProvider: ret = -1
,08-05 14:14:39.676  8298  8298 D BluetoothAdapterState: make
,08-05 14:14:39.676  8298  8298 I bluedroid: init
,08-05 14:14:39.676  8298  8317 I BluetoothAdapterState: Entering OffState
08-05 14:14:39.676  8298  8298 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-05 14:14:39.676  8298  8298 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-05 14:14:39.676  8298  8298 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-05 14:14:39.676  8298  8298 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-05 14:14:39.676  8298  8298 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-05 14:14:39.676  8298  8298 I bluedroid: get_profile_interface socket
08-05 14:14:39.676  8298  8298 I bluedroid: get_profile_interface map_client
08-05 14:14:39.676  8298  8320 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-05 14:14:39.686  8298  8298 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
08-05 14:14:39.686  8298  8320 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
08-05 14:14:39.686  8298  8320 E BluetoothServiceJni: populateRssiValuesNative
08-05 14:14:39.686  8298  8320 I bluedroid: getModelRssiValues
08-05 14:14:39.686  8298  8320 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-05 14:14:39.686  8298  8320 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-05 14:14:39.686   765   765 D SettingsProvider: name = bluetooth_name
,08-05 14:14:39.686  8298  8320 D BluetoothAdapterProperties: Name is: Note3-1
,08-05 14:14:39.686   765  1578 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-05 14:14:39.686  8298  8306 I bluedroid: config_hci_snoop_log
,08-05 14:14:39.686   765  1058 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 14 receivers.
,08-05 14:14:39.696   765  1058 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-05 14:14:39.696   765  1058 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-05 14:14:39.696   765  1058 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-05 14:14:39.696  8298  8317 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-05 14:14:39.696  8298  8317 D BluetoothAdapterProperties: Setting state to 11
,08-05 14:14:39.696  8298  8317 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-05 14:14:39.696  8298  8317 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-05 14:14:39.696  8298  8317 D BluetoothAdapterService: updateAdapterState state is 11
,08-05 14:14:39.706   765   765 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-05 14:14:39.706  1316  1316 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:39.706  1196  1196 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-05 14:14:39.706  1196  1196 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-05 14:14:39.706  1739  1739 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-05 14:14:39.706  1196  1597 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-05 14:14:39.706   765   765 I InputMethodManagerService: [BT Setting State] State =11
,08-05 14:14:39.706   765  1526 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,08-05 14:14:39.706   765  1322 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-05 14:14:39.706  1196  1196 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,08-05 14:14:39.706  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:39.706  7661  7661 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,08-05 14:14:39.706   765  1677 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-05 14:14:39.706  8298  8317 D BluetoothAdapterService: Autoconnection is available 
08-05 14:14:39.706  8298  8317 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-05 14:14:39.706   765  1677 D ActivityManager: caller:android.app.ApplicationThreadProxy@10a122ef, r.packageName :com.google.android.gms
,08-05 14:14:39.716  1316  1316 D BluetoothNotiBroadcastReceiver: onReceive
,08-05 14:14:39.716  8298  8317 D BluetoothSecureManager: getInstant: null
08-05 14:14:39.716  8298  8317 D BluetoothSecureManager: calling getMethod for getService
08-05 14:14:39.716  8298  8317 D BluetoothSecureManager: calling getService
,08-05 14:14:39.726  8298  8317 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@10f651
,08-05 14:14:39.726   765   783 D BluetoothSecureManagerService: isSecureModeEnabled
,08-05 14:14:39.726   765   783 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-05 14:14:39.726  8298  8317 D BtConfig.SecureMode: isSecureModeOn:false
08-05 14:14:39.726  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-05 14:14:39.726  8298  8317 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-05 14:14:39.726  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-05 14:14:39.726  8298  8317 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-05 14:14:39.726  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-05 14:14:39.726  8298  8317 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-05 14:14:39.726  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-05 14:14:39.726  8298  8317 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-05 14:14:39.726  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-05 14:14:39.726  8298  8317 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-05 14:14:39.726  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-05 14:14:39.726  8298  8317 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-05 14:14:39.726  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-05 14:14:39.726  8298  8317 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-05 14:14:39.726  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-05 14:14:39.726  8298  8317 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-05 14:14:39.726  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-05 14:14:39.736  8298  8317 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-05 14:14:39.736  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-05 14:14:39.736  8298  8317 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,08-05 14:14:39.736  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-05 14:14:39.736  8298  8317 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-05 14:14:39.736  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-05 14:14:39.736  8298  8317 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-05 14:14:39.736  8298  8317 D BluetoothBondStateMachine: make
,08-05 14:14:39.736  1903  1903 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-05 14:14:39.746  1903  1903 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-05 14:14:39.746  8298  8317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-05 14:14:39.746  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-05 14:14:39.746  8298  8317 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-05 14:14:39.746   765  1578 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-05 14:14:39.746   765  1578 D ActivityManager: caller:android.app.ApplicationThreadProxy@e353085, r.packageName :com.android.bluetooth
,08-05 14:14:39.756  8298  8324 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-05 14:14:39.756  8298  8317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-05 14:14:39.756  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-05 14:14:39.756  8298  8317 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-05 14:14:39.756   765  1322 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:39.756   765  1322 D ActivityManager: caller:android.app.ApplicationThreadProxy@2506ff0b, r.packageName :com.android.bluetooth
08-05 14:14:39.756  8298  8298 I BtGatt.JNI: classInitNative(L890): classInitNative: Success!
,08-05 14:14:39.756  8298  8317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-05 14:14:39.756  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-05 14:14:39.756  8298  8317 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-05 14:14:39.756   765  3410 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:39.756   765  3410 D ActivityManager: caller:android.app.ApplicationThreadProxy@341d5001, r.packageName :com.android.bluetooth
,08-05 14:14:39.756  8298  8317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-05 14:14:39.756  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-05 14:14:39.756  8298  8317 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-05 14:14:39.756   765  1237 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:39.756   765  1237 D ActivityManager: caller:android.app.ApplicationThreadProxy@38a480e7, r.packageName :com.android.bluetooth
,08-05 14:14:39.756  8298  8317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-05 14:14:39.756  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-05 14:14:39.756  8298  8317 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-05 14:14:39.756   765  1677 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:39.756   765  1677 D ActivityManager: caller:android.app.ApplicationThreadProxy@250deb3d, r.packageName :com.android.bluetooth
,08-05 14:14:39.766  8298  8317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-05 14:14:39.766  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-05 14:14:39.766  8298  8317 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-05 14:14:39.766   765  1467 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:39.766   765  1467 D ActivityManager: caller:android.app.ApplicationThreadProxy@3cae4483, r.packageName :com.android.bluetooth
,08-05 14:14:39.766  8298  8317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-05 14:14:39.766  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-05 14:14:39.766  8298  8317 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-05 14:14:39.766   765   784 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:39.766   765   784 D ActivityManager: caller:android.app.ApplicationThreadProxy@2d72fe39, r.packageName :com.android.bluetooth
,08-05 14:14:39.766  8298  8317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-05 14:14:39.766  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-05 14:14:39.766  8298  8317 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-05 14:14:39.766   765   783 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:39.766   765   783 D ActivityManager: caller:android.app.ApplicationThreadProxy@3706a5df, r.packageName :com.android.bluetooth
,08-05 14:14:39.766  8298  8298 D BtGatt.DebugUtils: handleDebugAction() action=null
08-05 14:14:39.766  8298  8298 D BtGatt.GattService: Received start request. Starting profile...
,08-05 14:14:39.766  8298  8298 D BtGatt.GattService: start()
08-05 14:14:39.766  8298  8298 I bluedroid: get_profile_interface gatt
08-05 14:14:39.766  8298  8317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-05 14:14:39.766  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-05 14:14:39.766  8298  8317 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,08-05 14:14:39.766  8298  8298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eea3460
08-05 14:14:39.766  8298  8298 D BtGatt.AdvertiseManager: advertise manager created
08-05 14:14:39.766  8298  8317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-05 14:14:39.766  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-05 14:14:39.766  8298  8317 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,08-05 14:14:39.766  8298  8317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-05 14:14:39.766  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-05 14:14:39.766  8298  8317 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-05 14:14:39.766  8298  8317 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-05 14:14:39.766  8298  8317 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-05 14:14:39.766  8298  8317 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-05 14:14:39.766  8298  8317 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-05 14:14:39.776  8298  8298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eea3460
,08-05 14:14:39.786  8298  8298 D HeadsetService: Received start request. Starting profile...
,08-05 14:14:39.786  8298  8298 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-05 14:14:39.786  8298  8298 D HeadsetStateMachine: make
,08-05 14:14:39.786  8298  8298 E HeadsetStateMachine: # of Max HF connection is 2
,08-05 14:14:39.796   765  1578 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-05 14:14:39.796   765  3410 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
,08-05 14:14:39.796  8298  8298 I bluedroid: get_profile_interface handsfree
,08-05 14:14:39.806  8298  8298 I DualScoManager: Instantiating Dual Sco Manager
,08-05 14:14:39.806  8298  8298 I DualScoManager: Set HeadsetServiceHelper
,08-05 14:14:39.806  8298  8298 D BluetoothAtMessage: createCMTIContentObservers
,08-05 14:14:39.806   765  1677 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-05 14:14:39.806   765  1677 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:39.806   765  1677 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:39.806   765  1677 D SettingsProvider: selectionArgs: false
08-05 14:14:39.806   765  1677 D SettingsProvider: selectionArgs: 1002
,08-05 14:14:39.806   765  1677 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:39.806   765  1677 D SettingsProvider: ret = -1
,08-05 14:14:39.816  8298  8330 D HeadsetStateMachine: Enter Disconnected: -2
,08-05 14:14:39.816  8298  8298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eea3460
,08-05 14:14:39.816  8298  8330 E HeadsetStateMachine: set to mRemoteBrsf = 0
,08-05 14:14:39.816  8298  8298 D A2dpService: Received start request. Starting profile...
,08-05 14:14:39.816  8298  8330 D HeadsetStateMachine: map size, before remove : 0
08-05 14:14:39.816  8298  8330 D HeadsetStateMachine: map size, after remove: 0
08-05 14:14:39.816  8298  8330 D HeadsetStateMachine: mNextConnectingDevice : null
,08-05 14:14:39.816  8298  8298 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-05 14:14:39.816  8298  8298 V Avrcp   : make
,08-05 14:14:39.816  8298  8298 V Avrcp   : Avrcp
,08-05 14:14:39.816  8298  8298 I bluedroid: get_profile_interface avrcp
,08-05 14:14:39.826  8298  8298 V Avrcp   : start
,08-05 14:14:39.826  8298  8298 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-05 14:14:39.826  8298  8298 V Avrcp   : ++registerMediaPlayers++
,08-05 14:14:39.826  8298  8298 I Avrcp   : No of Audio players :: 2
,08-05 14:14:39.826  8298  8298 I Avrcp   : App Package name is com.google.android.music
,08-05 14:14:39.836  8298  8298 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,08-05 14:14:39.836  8298  8298 I Avrcp   : App pkg name is Google Play Music
,08-05 14:14:39.836  8298  8298 I Avrcp   : Name::Google Play Music
,08-05 14:14:39.836  8298  8298 V Avrcp   : MediaPlayerInfo: mPlayerId=1
08-05 14:14:39.836  8298  8298 I Avrcp   : App Package name is com.sec.android.app.music
,08-05 14:14:39.836  8298  8298 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,08-05 14:14:39.836  8298  8298 I Avrcp   : App pkg name is Music
,08-05 14:14:39.836  8298  8298 I Avrcp   : Name::Music
08-05 14:14:39.836  8298  8298 V Avrcp   : MediaPlayerInfo: mPlayerId=2
08-05 14:14:39.836  8298  8298 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,08-05 14:14:39.846  8298  8298 I Avrcp   : No of Video players :: 1
,08-05 14:14:39.846  8298  8298 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
,08-05 14:14:39.846  8298  8298 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,08-05 14:14:39.846  8298  8298 I Avrcp   : Video App pkg name is Video Player
,08-05 14:14:39.846  8298  8298 I Avrcp   : Name::Video Player
08-05 14:14:39.846  8298  8298 V Avrcp   : MediaPlayerInfo: mPlayerId=3
08-05 14:14:39.846  8298  8298 I Avrcp   : Add tempPlayer
,08-05 14:14:39.846  8298  8298 V Avrcp   : MediaPlayerInfo: mPlayerId=4
08-05 14:14:39.846  8298  8298 I Avrcp   : Total no of players: 4
08-05 14:14:39.846  8298  8298 V Avrcp   : swapping the samsung player with 1st player
08-05 14:14:39.846  8298  8298 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-05 14:14:39.846  8298  8298 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-05 14:14:39.846  8298  8298 D A2dpStateMachine: make
08-05 14:14:39.846  8298  8331 V Avrcp   : handleMessage, msg=207
,08-05 14:14:39.846  8298  8331 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-05 14:14:39.846  8298  8298 I bluedroid: get_profile_interface a2dp
,08-05 14:14:39.846  8298  8333 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-05 14:14:39.846  8298  8298 E bt-btif : warning : media task started media_task_refcnt 1 
,08-05 14:14:39.856  8298  8298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eea3460
,08-05 14:14:39.856  8298  8298 I BluetoothHidServiceJni: classInitNative: succeeds
08-05 14:14:39.856  8298  8332 D A2dpStateMachine: Enter Disconnected: -2
,08-05 14:14:39.856  8298  8298 D HidService: Received start request. Starting profile...
,08-05 14:14:39.856  8298  8298 I bluedroid: get_profile_interface hidhost
08-05 14:14:39.856  8298  8298 D HidService: setHidService(): set to: null
08-05 14:14:39.856  8298  8298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eea3460
,08-05 14:14:39.856  8298  8298 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-05 14:14:39.856  8298  8298 D HealthService: Received start request. Starting profile...
,08-05 14:14:39.866  8298  8331 D BluetoothMediaBrowser: no now playing list
,08-05 14:14:39.866  8298  8331 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-05 14:14:39.866  8298  8298 I bluedroid: get_profile_interface health
,08-05 14:14:39.866  8298  8298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eea3460
,08-05 14:14:39.866  8298  8298 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-05 14:14:39.866  8298  8298 D PanService: Received start request. Starting profile...
08-05 14:14:39.866  8298  8331 D Avrcp   :  checkNowPlayingList start
,08-05 14:14:39.866  8298  8298 D BluetoothPanServiceJni: initializeNative(L110): pan
08-05 14:14:39.866  8298  8298 I bluedroid: get_profile_interface pan
,08-05 14:14:39.866  8298  8298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eea3460
,08-05 14:14:39.866  8298  8298 D BluetoothMapService: Received start request. Starting profile...
,08-05 14:14:39.886  8298  8298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eea3460
,08-05 14:14:39.896  8298  8298 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-05 14:14:39.896  8298  8298 D SapService: Received start request. Starting profile...
,08-05 14:14:39.896  8298  8298 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-05 14:14:39.896  8298  8298 I bluedroid: get_profile_interface sap
08-05 14:14:39.896  8298  8298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eea3460
,08-05 14:14:39.896  8298  8298 E BluetoothAdapterService(518665312): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-05 14:14:39.896  8298  8298 D HeadsetStateMachine: Try to query the phonestate on bind
,08-05 14:14:39.896  1395  8281 I Telecom : BluetoothPhoneService: queryPhoneState
,08-05 14:14:39.896  1395  1395 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-05 14:14:39.896  8298  8298 D HeadsetStateMachine: Proxy object connected
,08-05 14:14:39.896  8298  8298 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-05 14:14:39.896  8298  8298 D HeadsetPhoneState: sendDeviceDataStateChanged
08-05 14:14:39.896  8298  8330 D HeadsetStateMachine: Disconnected process message: 11
,08-05 14:14:39.896  8298  8330 D HeadsetStateMachine: Disconnected process message: 18
08-05 14:14:39.906  8298  8298 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-05 14:14:39.906  8298  8298 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-05 14:14:39.906  8298  8298 E BluetoothAdapterService(518665312): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-05 14:14:39.906  8298  8298 D BluetoothA2dp: Proxy object connected
08-05 14:14:39.906  8298  8298 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-05 14:14:39.906  8298  8298 E BluetoothAdapterService(518665312): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-05 14:14:39.906  8298  8298 E BluetoothAdapterService(518665312): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-05 14:14:39.906  8298  8330 D HeadsetStateMachine: Disconnected process message: 10
,08-05 14:14:39.906  8298  8330 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-05 14:14:39.906  8298  8330 D HeadsetStateMachine: Disconnected process message: 11
,08-05 14:14:39.906  8298  8298 E BluetoothAdapterService(518665312): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-05 14:14:39.906  8298  8298 E BluetoothAdapterService(518665312): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-05 14:14:39.906  8298  8298 E BluetoothAdapterService(518665312): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-05 14:14:39.906  8298  8298 E BluetoothAdapterService(518665312): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-05 14:14:39.906  8298  8317 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-05 14:14:39.906  8298  8317 I bluedroid: enable
,08-05 14:14:39.906  8298  8317 I bt_hci_bdroid: init
08-05 14:14:39.906  8298  8337 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-05 14:14:39.906  8298  8317 I bt_vendor: init
,08-05 14:14:39.906  8298  8317 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-05 14:14:39.906  8298  8317 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
08-05 14:14:39.906  8298  8317 D bt_userial: userial_init
08-05 14:14:39.906  8298  8317 D bt_vendor: op for 5
,08-05 14:14:39.906  8298  8317 D bt_vendor: op for 0
08-05 14:14:39.906  8298  8317 D bt_upio : upio_set_bluetooth_power(on: 0)
08-05 14:14:39.906  8298  8317 D bt_upio : is_emulator_context : 0
08-05 14:14:39.906  8298  8317 D bt_upio : is_rfkill_disabled ? [0]
,08-05 14:14:39.906  8298  8317 D bt_upio : is_rfkill_disabled ? [0]
08-05 14:14:39.916  8298  8317 D bt_vendor: op for 0
,08-05 14:14:39.916  8298  8317 D bt_upio : upio_set_bluetooth_power(on: 1)
08-05 14:14:39.916  8298  8317 D bt_upio : is_emulator_context : 0
08-05 14:14:39.916  8298  8317 D bt_upio : is_rfkill_disabled ? [0]
,08-05 14:14:39.916  8298  8339 D bt_vendor: op for 3
08-05 14:14:39.916  8298  8339 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-05 14:14:39.916  8298  8339 I bt_userial_vendor: userial_vendor_open():UART is setup
08-05 14:14:39.916  8298  8339 I bt_userial_vendor: device fd = 65 open
,08-05 14:14:39.916  8298  8339 D bt_vendor: op for 1
08-05 14:14:39.916  8298  8339 E bt_hwcfg: Start CFG HW, HCI reset
08-05 14:14:39.916  8298  8340 D bt_userial: Entering userial_read_thread()
,08-05 14:14:39.996  8298  8339 E bt_hwcfg: Read Local Name after HCI reset
,08-05 14:14:40.016  8298  8339 D bt_hwcfg: Chipset BCM4335C0
08-05 14:14:40.016  8298  8339 D bt_hwcfg: Target name = [BCM4335C0]
08-05 14:14:40.016  8298  8339 I bt_hwcfg: module_type[semco].
08-05 14:14:40.016  8298  8339 I bt_hwcfg: not ZERO...
08-05 14:14:40.016  8298  8339 I bt_hwcfg: module_type[semco] is invalid.
08-05 14:14:40.016  8298  8339 E bt_hwcfg: patchram path ORG . BCM4335C0
08-05 14:14:40.016  8298  8339 E bt_hwcfg: patchram path ORG .. BCM4335C0
08-05 14:14:40.016  8298  8339 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
08-05 14:14:40.016  8298  8339 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
08-05 14:14:40.016  8298  8339 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
08-05 14:14:40.016  8298  8339 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
08-05 14:14:40.016  8298  8339 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335C0
08-05 14:14:40.016  8298  8339 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559_wisol.hcd BCM4335C0
08-05 14:14:40.016  8298  8339 E bt_hwcfg: fw ver (org)0.0
08-05 14:14:40.016  8298  8339 E bt_hwcfg: vendor lib preload failed to locate firmware patch file
08-05 14:14:40.016  8298  8339 E bt_hwcfg: Remove module rev, try again BCM4335
08-05 14:14:40.016  8298  8339 D bt_hwcfg: Target name = [BCM4335]
08-05 14:14:40.016  8298  8339 I bt_hwcfg: module_type[semco].
08-05 14:14:40.016  8298  8339 I bt_hwcfg: not ZERO...
08-05 14:14:40.016  8298  8339 I bt_hwcfg: module_type[semco] is invalid.
08-05 14:14:40.016  8298  8339 E bt_hwcfg: patchram path ORG . BCM4335
08-05 14:14:40.016  8298  8339 E bt_hwcfg: patchram path ORG .. BCM4335
08-05 14:14:40.016  8298  8339 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335
08-05 14:14:40.016  8298  8339 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
08-05 14:14:40.016  8298  8339 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335
08-05 14:14:40.016  8298  8339 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
08-05 14:14:40.016  8298  8339 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335
08-05 14:14:40.016  8298  8339 I bt_hwcfg: patch(org) : bcm4335_V0111.0559.hcd
08-05 14:14:40.016  8298  8339 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4335_V0111.0559.hcd
08-05 14:14:40.016  8298  8339 E bt_hwcfg: ORG patchram base 0111
08-05 14:14:40.016  8298  8339 E bt_hwcfg: ORG patchram minor 0559
08-05 14:14:40.016  8298  8339 E bt_hwcfg: fw ver (org)111.559
08-05 14:14:40.016  8298  8339 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4335_V0111.0559.hcd
,08-05 14:14:40.026  8298  8339 I bt_hwcfg: Axi patch failure or not include AXI patching
,08-05 14:14:40.026  8298  8339 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-05 14:14:40.506  8298  8339 I bt_hwcfg: bt vendor lib: set UART baud 115200,
,08-05 14:14:40.506  8298  8339 I bt_hwcfg: FW Download delta = 516697
,08-05 14:14:40.506  8298  8339 D bt_hwcfg: Settlement delay -- 100 ms
08-05 14:14:40.506  8298  8339 I bt_hwcfg: Setting fw settlement delay to 100 
,08-05 14:14:40.616  8298  8339 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-05 14:14:40.656  8298  8339 I bt_hwcfg: vendor lib fwcfg completed
,08-05 14:14:40.666  8298  8337 I         : BTE_InitTraceLevels -- TRC_HCI
,08-05 14:14:40.666  8298  8337 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-05 14:14:40.666  8298  8337 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-05 14:14:40.666  8298  8337 I         : BTE_InitTraceLevels -- TRC_AVDT
08-05 14:14:40.666  8298  8337 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-05 14:14:40.666  8298  8337 I         : BTE_InitTraceLevels -- TRC_A2D
08-05 14:14:40.666  8298  8337 I         : BTE_InitTraceLevels -- TRC_BNEP
08-05 14:14:40.666  8298  8337 I         : BTE_InitTraceLevels -- TRC_BTM
08-05 14:14:40.666  8298  8337 I         : BTE_InitTraceLevels -- TRC_GAP
08-05 14:14:40.666  8298  8337 I         : BTE_InitTraceLevels -- TRC_PAN
08-05 14:14:40.666  8298  8337 I         : BTE_InitTraceLevels -- TRC_SAP
,08-05 14:14:40.666  8298  8337 I         : BTE_InitTraceLevels -- TRC_SDP
08-05 14:14:40.666  8298  8337 I         : BTE_InitTraceLevels -- TRC_GATT
08-05 14:14:40.666  8298  8337 I         : BTE_InitTraceLevels -- TRC_SMP
,08-05 14:14:40.676  8298  8337 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-05 14:14:40.676  8298  8337 I         : BTE_InitTraceLevels -- TRC_BTIF
08-05 14:14:40.676  8298  8337 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-05 14:14:40.896  8298  8337 W bt-l2cap: l2c_link_processs_ble_num_bufs 15
,08-05 14:14:40.906  8298  8337 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xaf918b5d 
,08-05 14:14:40.906  8298  8337 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xaf918b5d 
,08-05 14:14:41.126  8298  8320 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 1 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
,08-05 14:14:41.126  8298  8320 E bt-btif : Calling BTA_HhEnable
,08-05 14:14:41.126  8298  8320 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-05 14:14:41.126  8298  8320 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
08-05 14:14:41.126  8298  8320 E BluetoothServiceJni: populateRssiValuesNative
08-05 14:14:41.126  8298  8320 I bluedroid: getModelRssiValues
,08-05 14:14:41.126  8298  8320 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-05 14:14:41.126  8298  8320 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-05 14:14:41.136   765   765 D SettingsProvider: name = bluetooth_name
,08-05 14:14:41.136  8298  8320 D BluetoothAdapterProperties: Name is: Note3-1
,08-05 14:14:41.136  8298  8320 D BluetoothAdapterProperties: Scan Mode:20
,08-05 14:14:41.136  8298  8320 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-05 14:14:41.136  8298  8320 D BluetoothAdapterProperties: LE Address is:E0:B7:20:3E:93:BC
08-05 14:14:41.136  8298  8320 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-05 14:14:41.136  8298  8339 D bt_vendor: op for 2
08-05 14:14:41.136  8298  8339 D bt_vendor: op for 6
,08-05 14:14:41.136  8298  8320 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-05 14:14:41.136  8298  8320 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-05 14:14:41.136  8298  8339 D bt_vendor: op for 7
08-05 14:14:41.136  8298  8320 E bt-btif : btif_sock_init: !vhci_init
,08-05 14:14:41.136  8298  8339 D bt_upio : proc btwrite assertion
08-05 14:14:41.136  8298  8320 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-05 14:14:41.136  8298  8320 D IOP_DB_BT: db_open: db_open : handle 3026165776l, read 14063 bytes onto local cache
,08-05 14:14:41.136  8298  8339 D bt_vendor: op for 7
08-05 14:14:41.136  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.146  8298  8339 D bt_vendor: op for 7
,08-05 14:14:41.146  8298  8339 D bt_upio : BT_WAKE is asserted already
08-05 14:14:41.146  8298  8320 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-05 14:14:41.146  8298  8320 D IOP_DB_BT: db_query: result 1
08-05 14:14:41.146  8298  8320 I         : iop_db_open: iop_db_open status 0
,08-05 14:14:41.146  8298  8320 D bte_conf: Device ID record 1 : primary
08-05 14:14:41.146  8298  8320 D bte_conf:   vendorId            = 0075
08-05 14:14:41.146  8298  8320 D bte_conf:   vendorIdSource      = 0001
,08-05 14:14:41.146  8298  8320 D bte_conf:   product             = 0100
08-05 14:14:41.146  8298  8320 D bte_conf:   version             = 0200
08-05 14:14:41.146  8298  8320 D bte_conf:   clientExecutableURL = 
08-05 14:14:41.146  8298  8320 D bte_conf:   serviceDescription  = 
08-05 14:14:41.146  8298  8320 D bte_conf:   documentationURL    = 
,08-05 14:14:41.146  8298  8320 D bte_conf: bte_load_did_conf no section named DID2.
,08-05 14:14:41.146  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:41.146  8298  8317 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-05 14:14:41.146  8298  8317 D BluetoothAdapterProperties: ScanMode =  20
08-05 14:14:41.146  8298  8317 D BluetoothAdapterProperties: State =  11
,08-05 14:14:41.146   765   783 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-05 14:14:41.146  8298  8317 D BluetoothAdapterProperties: Setting state to 12
,08-05 14:14:41.156  8298  8320 D BluetoothAdapterProperties: Scan Mode:21
,08-05 14:14:41.156  8298  8320 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-05 14:14:41.156  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:41.156  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:41.156  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:41.156  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 14:14:41.156  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:41.156  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:41.156  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:41.156  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 14:14:41.156  8298  8317 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-05 14:14:41.156   765  1467 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-05 14:14:41.156   765  1467 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-05 14:14:41.156   765  1467 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-05 14:14:41.156   765  1467 D SettingsProvider: selectionArgs: false
08-05 14:14:41.156   765  1467 D SettingsProvider: selectionArgs: 1002
,08-05 14:14:41.156   765  1467 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-05 14:14:41.156   765  1467 D SettingsProvider: ret = -1
,08-05 14:14:41.156  8298  8317 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-05 14:14:41.156  8298  8317 D BluetoothAdapterService: updateAdapterState state is 12
,08-05 14:14:41.156  8298  8339 E bt_h4   : vendor lib postload completed
,08-05 14:14:41.156   765  1144 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-05 14:14:41.166   765  1144 D ActivityManager: caller:android.app.ApplicationThreadProxy@383c523a, r.packageName :com.android.bluetooth
,08-05 14:14:41.166   305   305 E SMD     : DCD ON
,08-05 14:14:41.176  8298  8298 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-05 14:14:41.176  8298  8298 I BluetoothPbapService: Handler(): got msg=1
,08-05 14:14:41.176   765  1647 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-05 14:14:41.176   765  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-05 14:14:41.186   765  1058 E BluetoothHeadset: BluetoothHeadset service is binded
,08-05 14:14:41.186  1316  3348 D BluetoothPbap: onBluetoothStateChange: up=true
,08-05 14:14:41.186  8298  8317 D BluetoothAdapterService: Autoconnection is available 
,08-05 14:14:41.186  8298  8317 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-05 14:14:41.186  8298  8317 D BluetoothAdapterService: starting service from this receiver
,08-05 14:14:41.186  8298  8339 D bt_vendor: op for 7
,08-05 14:14:41.186  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.196  8298  8320 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-05 14:14:41.196  8298  8339 D bt_vendor: op for 7
,08-05 14:14:41.196  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.196  8298  8339 D bt_vendor: op for 7
,08-05 14:14:41.196  8298  8339 D bt_upio : BT_WAKE is asserted already
08-05 14:14:41.196  8298  8347 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-05 14:14:41.196  8298  8339 D bt_vendor: op for 7
,08-05 14:14:41.196  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.196  8298  8339 D bt_vendor: op for 7
,08-05 14:14:41.196  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.196  8298  8339 D bt_vendor: op for 7
,08-05 14:14:41.206  8298  8339 D bt_upio : BT_WAKE is asserted already
08-05 14:14:41.206  7501  7501 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 14:14:41.206  8298  8339 D bt_vendor: op for 7
08-05 14:14:41.206  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.206  8298  8339 D bt_vendor: op for 7
,08-05 14:14:41.206  8298  8339 D bt_upio : BT_WAKE is asserted already
08-05 14:14:41.206  8298  8347 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-05 14:14:41.206  8298  8347 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
,08-05 14:14:41.206  8298  8339 D bt_vendor: op for 7
08-05 14:14:41.206  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.206  8298  8347 D BluetoothSocket: bindListen(), new LocalSocket 
08-05 14:14:41.206  8298  8347 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-05 14:14:41.206  8298  8347 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@17885c33
,08-05 14:14:41.206  8298  8347 D BluetoothSocket: channel: 19
08-05 14:14:41.206  8298  8347 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-05 14:14:41.206  8298  8339 D bt_vendor: op for 7
,08-05 14:14:41.206  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.206  8298  8339 D bt_vendor: op for 7
,08-05 14:14:41.206  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.216  8298  8339 D bt_vendor: op for 7
,08-05 14:14:41.216  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.216  8298  8339 D bt_vendor: op for 7
,08-05 14:14:41.216  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.216  8298  8339 D bt_vendor: op for 7
,08-05 14:14:41.216  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.216  8298  8339 D bt_vendor: op for 7
,08-05 14:14:41.216  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.216  8298  8339 D bt_vendor: op for 7
,08-05 14:14:41.216  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.216  8298  8339 D bt_vendor: op for 7
,08-05 14:14:41.216  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.216  8298  8339 D bt_vendor: op for 7
08-05 14:14:41.216  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.226  8298  8339 D bt_vendor: op for 7
08-05 14:14:41.226  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.226  8298  8339 D bt_vendor: op for 7
,08-05 14:14:41.226  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.226  8298  8339 D bt_vendor: op for 7
,08-05 14:14:41.226  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.226  8298  8339 D bt_vendor: op for 7
,08-05 14:14:41.226  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.236  8298  8339 D bt_vendor: op for 7
,08-05 14:14:41.236  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.236  8298  8339 D bt_vendor: op for 7
08-05 14:14:41.236  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.236  8298  8339 D bt_vendor: op for 7
,08-05 14:14:41.236  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.236  8298  8339 D bt_vendor: op for 7
08-05 14:14:41.236  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.236  8298  8339 D bt_vendor: op for 7
,08-05 14:14:41.236  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.306   765  1058 I art     : Explicit concurrent mark sweep GC freed 50136(2MB) AllocSpace objects, 3(48KB) LOS objects, 29% free, 37MB/53MB, paused 1.189ms total 120.718ms
,08-05 14:14:41.306   765  3410 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:41.306   765  3410 D ActivityManager: caller:android.app.ApplicationThreadProxy@188d5806, r.packageName :com.android.bluetooth
,08-05 14:14:41.306   765  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-05 14:14:41.306  8298  8317 I BluetoothAdapterState: Entering On State from state = 11
,08-05 14:14:41.306   765  1058 D BluetoothPan: Binding service...
08-05 14:14:41.306   765  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-05 14:14:41.306   765  1058 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-05 14:14:41.316  3178  3187 E BluetoothHeadset: BluetoothHeadset service is binded
08-05 14:14:41.316  1316  3348 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-05 14:14:41.316   765  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-05 14:14:41.316   765  1058 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-05 14:14:41.316  1395  8281 E BluetoothHeadset: BluetoothHeadset service is binded
,08-05 14:14:41.316  1316  3348 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-05 14:14:41.316   765  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-05 14:14:41.316  1316  1316 D BluetoothA2dp: Proxy object connected
08-05 14:14:41.316  1316  1316 D A2dpProfile: Bluetooth service connected
,08-05 14:14:41.326  3178  3187 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-05 14:14:41.326   765   765 D BluetoothPan: BluetoothPAN Proxy object connected
,08-05 14:14:41.326   765  1058 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-05 14:14:41.326  3178  3178 D BluetoothA2dp: Proxy object connected
08-05 14:14:41.326  1316  1316 D BluetoothPbap: Proxy object connected
08-05 14:14:41.326  1316  1316 D PbapServerProfile: Bluetooth service connected
08-05 14:14:41.326  1316  1316 D BluetoothInputDevice: Proxy object connected
08-05 14:14:41.326  1316  1316 D HidProfile: Bluetooth service connected
,08-05 14:14:41.326   765  1058 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-05 14:14:41.326  7661  7670 E BluetoothHeadset: BluetoothHeadset service is binded
,08-05 14:14:41.326   765  1058 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-05 14:14:41.326  1395  1415 E BluetoothHeadset: BluetoothHeadset service is binded
,08-05 14:14:41.326   765  1058 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-05 14:14:41.326  1425  1745 E BluetoothHeadset: BluetoothHeadset service is binded
,08-05 14:14:41.336   765  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-05 14:14:41.336  1316  3348 E BluetoothHeadset: BluetoothHeadset service is binded
08-05 14:14:41.336  1316  3348 D Bluetoothsap: onBluetoothStateChange: up=true
08-05 14:14:41.336  1316  3348 D Bluetoothsap: Binding service...
,08-05 14:14:41.336  1316  1316 D HeadsetProfile: Bluetooth service connected
08-05 14:14:41.336  1316  3348 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-05 14:14:41.336   765  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-05 14:14:41.336  1316  3348 D Bluetoothsap: bindService called to Bluetooth SAP Service
08-05 14:14:41.336   765  1058 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-05 14:14:41.336   765  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-05 14:14:41.336   765   765 D BluetoothA2dp: Proxy object connected
,08-05 14:14:41.336  1316  1332 D BluetoothPan: Binding service...
08-05 14:14:41.336  1316  1316 D Bluetoothsap: BluetoothSAP Proxy object connected
,08-05 14:14:41.336  1316  1316 D SapProfile: Bluetooth service connected
08-05 14:14:41.336  1316  1316 D Bluetoothsap: getConnectedDevices()
08-05 14:14:41.336   765  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-05 14:14:41.336   765  1058 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-05 14:14:41.336  1395  8281 E BluetoothHeadset: BluetoothHeadset service is binded
08-05 14:14:41.336  1316  3348 D BluetoothMap: onBluetoothStateChange: up=true
,08-05 14:14:41.336  1316  1316 D BluetoothPan: BluetoothPAN Proxy object connected
08-05 14:14:41.336  1316  1316 D PanProfile: Bluetooth service connected
08-05 14:14:41.336   765  1058 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-05 14:14:41.336  8298  8306 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-05 14:14:41.336  1316  1316 D BluetoothMap: Proxy object connected
08-05 14:14:41.336  1316  1316 D MapProfile: Bluetooth service connected
08-05 14:14:41.336   765  1058 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-05 14:14:41.346   765   765 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-05 14:14:41.346  1395  1395 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@35731eb5, true
,08-05 14:14:41.346  1196  1196 D BluetoothTile:  onBluetoothStateChange:
,08-05 14:14:41.346   765   765 I InputMethodManagerService: [BT Setting State] State =12
,08-05 14:14:41.346  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:41.346   765   765 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-05 14:14:41.346  1395  1395 D BluetoothHeadset: registerMessageListener
,08-05 14:14:41.346  1316  1316 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:41.346  1196  1196 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-05 14:14:41.346  1196  1196 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-05 14:14:41.346  1739  1739 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-05 14:14:41.346  7661  7661 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,08-05 14:14:41.346   765  1058 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-05 14:14:41.346   765  1706 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-05 14:14:41.346   765  1706 D ActivityManager: caller:android.app.ApplicationThreadProxy@2b304131, r.packageName :com.google.android.gms
,08-05 14:14:41.356  8298  8322 D HeadsetService: registerMessageListener
08-05 14:14:41.356   765  1237 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
08-05 14:14:41.356  8298  8322 D HeadsetService: registerMessageListener
08-05 14:14:41.356   765  1677 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-05 14:14:41.356  1196  1196 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
08-05 14:14:41.356  8298  8330 D HeadsetStateMachine: Disconnected process message: 70
,08-05 14:14:41.356  1395  1395 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-05 14:14:41.356  8298  8330 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@21cab8fa
08-05 14:14:41.356  1395  1395 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-05 14:14:41.356  1196  1597 D BluetoothTile:  handleUpdatestate:false name:null
08-05 14:14:41.356  1196  1597 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-05 14:14:41.356  1316  1316 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,08-05 14:14:41.356  1316  1316 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-05 14:14:41.356  8298  8361 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-05 14:14:41.356  8298  8330 D HeadsetStateMachine: Disconnected process message: 9
,08-05 14:14:41.356  8298  8330 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-05 14:14:41.366  8298  8361 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-05 14:14:41.366  8298  8361 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-05 14:14:41.366  8298  8361 D BluetoothSocket: bindListen(), new LocalSocket 
08-05 14:14:41.366  8298  8361 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-05 14:14:41.366  8298  8361 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@33091eab
,08-05 14:14:41.366  8298  8339 D bt_vendor: op for 7
08-05 14:14:41.366  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.366  8298  8361 D BluetoothSocket: channel: 5
,08-05 14:14:41.366   313   779 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-05 14:14:41.366   313   779 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-05 14:14:41.366   313   779 V voice   : voice_set_parameters: exit with code(-2)
08-05 14:14:41.366   313   779 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-05 14:14:41.366   313   779 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-05 14:14:41.366   313   779 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-05 14:14:41.366   313   779 V audio_hw_primary: adev_set_parameters: exit
,08-05 14:14:41.366  8298  8330 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-05 14:14:41.366  1316  1316 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-05 14:14:41.366   765  1526 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-05 14:14:41.366   765  1526 D ActivityManager: caller:android.app.ApplicationThreadProxy@34ef3b84, r.packageName :com.android.settings
,08-05 14:14:41.376  1316  1316 D DockEventReceiver: finishStartingService: stopping service
,08-05 14:14:41.376  1316  1316 D BluetoothNotiBroadcastReceiver: onReceive
,08-05 14:14:41.386  8298  8298 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1eea3460
,08-05 14:14:41.386  8298  8298 D BtConfig.SecureMode: isSecureModeOn:false
,08-05 14:14:41.386   765   783 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-05 14:14:41.386   765   783 D ActivityManager: caller:android.app.ApplicationThreadProxy@2550e7a2, r.packageName :com.android.bluetooth
,08-05 14:14:41.396  1903  1903 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-05 14:14:41.396   765  1237 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-05 14:14:41.396   765  1237 D ActivityManager: caller:android.app.ApplicationThreadProxy@25e68bf0, r.packageName :com.google.android.gms
,08-05 14:14:41.396  1903  8367 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-05 14:14:41.396  1903  1903 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-05 14:14:41.416   765  3410 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-05 14:14:41.416   765  1647 D ActivityManager: caller:android.app.ApplicationThreadProxy@21ebe908, r.packageName :com.google.android.gms
,08-05 14:14:41.426  8298  8371 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-05 14:14:41.426  8298  8371 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
08-05 14:14:41.426  8298  8371 D BluetoothSocket: bindListen(), new LocalSocket 
08-05 14:14:41.426  8298  8371 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-05 14:14:41.426  8298  8371 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@b5e0ddd
08-05 14:14:41.426  8298  8339 D bt_vendor: op for 7
08-05 14:14:41.426  8298  8339 D bt_upio : BT_WAKE is asserted already
,08-05 14:14:41.426  8298  8371 D BluetoothSocket: channel: 12
08-05 14:14:41.426  8298  8371 I BtOppRfcommListener: Accept thread started.
,08-05 14:14:41.426  1903  8367 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-05 14:14:41.506  7501  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:41.506  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:41.506  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:41.506  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-05 14:14:41.506  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:41.506  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:41.506  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:41.506  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 14:14:41.506  7501  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-05 14:14:41.506  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:41.506  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@16a400c8 added. We now have 8 listener(s)
08-05 14:14:41.506  7501  7570 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 14:14:41.506  7501  7570 I WifiManager: packageName : com.test.thalitest
,08-05 14:14:41.506   765   783 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-05 14:14:41.506   765   783 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-05 14:14:41.506   765   783 D SecContentProvider2: mCursor = null
,08-05 14:14:41.516   765   783 D WifiService: setWifiEnabled: false pid=7501, uid=10079
,08-05 14:14:41.516   765   783 D SettingsProvider: name = wifi_on
,08-05 14:14:41.516  7501  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:41.516  7501  7570 I WifiManager: packageName : com.test.thalitest
08-05 14:14:41.516   765  1647 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-05 14:14:41.516   765  1647 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-05 14:14:41.516   765  1647 D SecContentProvider2: mCursor = null
08-05 14:14:41.516   765  1647 D WifiService: setWifiEnabled: true pid=7501, uid=10079
,08-05 14:14:41.516   765  1647 W ActivityManager: Permission Denial: getCurrentUser() from pid=7501, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-05 14:14:41.516   765  1647 W WifiService: Failed getting userId using ActivityManagerNative
08-05 14:14:41.516   765  1647 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7501, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-05 14:14:41.516   765  1647 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
08-05 14:14:41.516   765  1647 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
08-05 14:14:41.516   765  1647 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
08-05 14:14:41.516   765  1647 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-05 14:14:41.516   765  1647 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-05 14:14:41.516   765  1647 D SettingsProvider: name = wifi_on
,08-05 14:14:41.516   765  1149 E WifiHW  : ##################### set firmware type 0 #####################
,08-05 14:14:41.516   298  1056 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
08-05 14:14:41.516   298  1056 I WifiHW  : module is semco
08-05 14:14:41.516   298  1056 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
08-05 14:14:41.516   298  1056 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
08-05 14:14:41.516   298  1056 E WifiHW  : TEMP_FAILURE_RETRY complete
08-05 14:14:41.516   298  1056 D SoftapController: Softap fwReload - Ok
,08-05 14:14:41.526   298  1056 D CommandListener: Setting iface cfg
08-05 14:14:41.526   298  1056 D CommandListener: Trying to bring down wlan0
,08-05 14:14:41.526   298  1056 D CommandListener: Clearing all IP addresses on wlan0
,08-05 14:14:41.526   765  1149 E WifiHW  : supplicant_name : p2p_supplicant
,08-05 14:14:41.526   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,08-05 14:14:41.526  1316  1316 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-05 14:14:41.526  1196  1196 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-05 14:14:41.536  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-05 14:14:41.536  1196  1196 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:41.536  1196  1196 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-05 14:14:41.536  1196  1196 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:41.536  1196  1597 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-05 14:14:41.536  1196  1196 D HotspotTile: onReceive : 2, 0
,08-05 14:14:41.536   765  1149 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-05 14:14:41.536  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:41.536   765  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,08-05 14:14:41.536  7037  7037 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-05 14:14:41.536   765  3349 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:41.546  6711  6711 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-05 14:14:41.546  6711  6711 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-05 14:14:41.546  6711  6711 D SecurityLogAgent: StateMachine : Current State = 1
08-05 14:14:41.546  6711  6711 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-05 14:14:41.556  8375  8375 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-05 14:14:41.556  8375  8375 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-05 14:14:41.556  8375  8375 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-05 14:14:41.556  8375  8375 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-05 14:14:41.556   352   352 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8375
08-05 14:14:41.556   352   352 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-05 14:14:41.556  8375  8375 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-05 14:14:41.556  8375  8375 I wpa_supplicant: ssSupport state is = 1
,08-05 14:14:41.556  8375  8375 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,08-05 14:14:41.566  8375  8375 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-05 14:14:41.566   352   352 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8375
08-05 14:14:41.566   352   352 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,08-05 14:14:41.636   765  3081 D SSRM:n  : SIOP:: AP = 340, PST = 329, CUR = 450
,08-05 14:14:41.826   352   352 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,08-05 14:14:42.086  8375  8375 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,08-05 14:14:42.146  8375  8375 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-05 14:14:42.146  8375  8375 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-05 14:14:42.146   352   352 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8375
,08-05 14:14:42.146   352   352 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
08-05 14:14:42.146  8375  8375 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-05 14:14:42.146  8375  8375 I wpa_supplicant: ssSupport state is = 1
,08-05 14:14:42.146  8375  8375 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-05 14:14:42.146  8375  8375 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-05 14:14:42.146  8375  8375 E wpa_supplicant: SIM READ ERROR
,08-05 14:14:42.146  8375  8375 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-05 14:14:42.146  8375  8375 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-05 14:14:42.146  8375  8375 E wpa_supplicant: SIM READ ERROR
08-05 14:14:42.146  8375  8375 I wpa_supplicant: Blacklist: Clear (all) 
,08-05 14:14:42.146  8375  8375 I wpa_supplicant: wpa_default_ap_write_once
,08-05 14:14:42.146  8375  8375 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-05 14:14:42.146  8375  8375 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-05 14:14:42.146  8375  8375 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-05 14:14:42.146  8375  8375 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-05 14:14:42.156  8375  8375 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-05 14:14:42.156  8375  8375 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-05 14:14:42.806   765  1152 E Tethering: No numeric data
,08-05 14:14:42.806   765  1152 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-05 14:14:42.806   765  1146 V NetworkStats: performPollLocked(flags=0x1)
08-05 14:14:42.806   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 14:14:42.806   765  1146 D NetworkStatsFactory: UpdateStatsForKnox
,08-05 14:14:42.806   765  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:42.806  1196  1196 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-05 14:14:42.806  1196  1196 D HotspotTile: updateTetherState():false, false
,08-05 14:14:42.806   765  1146 V NetworkStats: performPollLocked() took 4ms
,08-05 14:14:42.806   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 14:14:42.806   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 14:14:42.806   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 14:14:42.816  8375  8375 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-05 14:14:42.826  8375  8375 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-05 14:14:42.826  8375  8375 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-05 14:14:42.826  8375  8375 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-05 14:14:42.826   352   352 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8375
08-05 14:14:42.826   352   352 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,08-05 14:14:42.826  8375  8375 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-05 14:14:42.826  8375  8375 I wpa_supplicant: ssSupport state is = 1
08-05 14:14:42.826  8375  8375 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-05 14:14:42.826  8375  8375 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-05 14:14:42.826   352   352 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8375
08-05 14:14:42.826   352   352 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
08-05 14:14:42.826  8375  8375 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-05 14:14:42.826  8375  8375 I wpa_supplicant: ssSupport state is = 1
08-05 14:14:42.826  8375  8375 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-05 14:14:42.826  8375  8375 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-05 14:14:42.826  8375  8375 E wpa_supplicant: SIM READ ERROR
08-05 14:14:42.826  8375  8375 I wpa_supplicant: wpa_default_ap_write_once
08-05 14:14:42.826  8375  8375 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-05 14:14:42.826  8375  8375 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-05 14:14:42.846  8375  8375 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-05 14:14:42.846  8375  8375 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-05 14:14:42.856  8375  8375 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-05 14:14:42.856  8375  8375 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-05 14:14:42.856   765  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-05 14:14:42.856   765  1149 D WifiNative-HAL: callSECApiBoolean - ID [21]
,08-05 14:14:42.856  8375  8375 I wpa_supplicant: HOTSPOT20_ENABLE called
08-05 14:14:42.856  8375  8375 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-05 14:14:42.856  8375  8375 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-05 14:14:42.856  8375  8375 E wpa_supplicant: SIM READ ERROR
08-05 14:14:42.856  8375  8375 I wpa_supplicant: Blacklist: Clear (all) 
,08-05 14:14:42.886  8375  8375 I wpa_supplicant: Skip scan - bUseNetwork false
,08-05 14:14:42.886   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,08-05 14:14:42.886  1196  1196 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-05 14:14:42.886  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-05 14:14:42.886  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:42.886  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:42.886  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:42.886  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:42.886  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:42.886  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:42.886  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:42.886  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:42.886  1196  1196 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:42.886  1196  1196 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-05 14:14:42.886  1196  1196 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-05 14:14:42.886  1196  1597 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-05 14:14:42.896   765  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,08-05 14:14:42.896  1316  1316 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-05 14:14:42.896  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:42.896  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:42.896  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:42.896  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:42.896  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:42.896  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:42.896  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:42.896  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 14:14:42.896  1196  1196 D HotspotTile: onReceive : 3, 0
,08-05 14:14:42.896   765  1149 D WifiNative-HAL: callSECApiInt - ID [210]
,08-05 14:14:42.896  7501  7501 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-05 14:14:42.896   765  1149 D WifiConfigStore: Loading config and enabling all networks 
,08-05 14:14:42.896  7037  7037 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-05 14:14:42.906   765  1149 E WifiConfigStore: Not a HS20
,08-05 14:14:42.906   765  3410 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:42.906  6711  6711 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-05 14:14:42.906  6711  6711 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-05 14:14:42.906  6711  6711 D SecurityLogAgent: StateMachine : Current State = 1
08-05 14:14:42.906  6711  6711 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-05 14:14:42.916   765  1149 E WifiConfigStore: Not a HS20
,08-05 14:14:42.916   765  1149 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-05 14:14:42.926   765  1149 D WifiNative-HAL: callSECApiInt - ID [65]
,08-05 14:14:42.926  8298  8339 D bt_vendor: op for 7
,08-05 14:14:42.926   765  1149 D WifiNative-HAL: callSECApiBoolean - ID [13]
,08-05 14:14:42.926  8375  8375 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-05 14:14:42.926  8375  8375 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-05 14:14:42.926  8375  8375 I wpa_supplicant: reset timer : RESET_TIMER 0
08-05 14:14:42.926  8375  8375 I wpa_supplicant: P2P: Current p2p state = IDLE
08-05 14:14:42.926  8375  8375 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-05 14:14:42.926  8375  8375 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-05 14:14:42.926  8375  8375 I wpa_supplicant: First Scan Start
,08-05 14:14:42.936  7702  7702 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-05 14:14:42.936  8375  8375 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-05 14:14:42.936   765  1149 D WifiNative-HAL: Setting external_sim to 1
,08-05 14:14:42.936   765  1149 D WifiStateMachine: Setting OUI to DA-A1-19
08-05 14:14:42.936   765  1149 I WifiNative-HAL: startHal
08-05 14:14:42.936   765  1149 E wifi    : getStaticLongField sWifiHalHandle 0x9329886c
08-05 14:14:42.936   765  1149 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x70180e
08-05 14:14:42.936   765  1149 I WifiNative-HAL: Could not start hal
,08-05 14:14:42.946   765  1149 E native  : do suspend true
,08-05 14:14:42.956   765  1148 D WifiP2pService: P2pDisabledState{ what=131203 }
08-05 14:14:42.956   765  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-05 14:14:42.956   765   765 D WifiScanningService: SCAN_AVAILABLE : 3
08-05 14:14:42.956   765   765 D RttService: SCAN_AVAILABLE : 3
08-05 14:14:42.956   765  1167 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:42.956   765  1167 I WifiNative-HAL: startHal
08-05 14:14:42.956   765  1167 E wifi    : getStaticLongField sWifiHalHandle 0x9c3bb99c
08-05 14:14:42.956   765  1167 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0xb0180a
08-05 14:14:42.956   765  1167 I WifiNative-HAL: Could not start hal
08-05 14:14:42.956   765  1167 E WifiScanningService: could not start HAL
08-05 14:14:42.956   765  1168 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-05 14:14:42.956   298  1056 D CommandListener: Setting iface cfg
08-05 14:14:42.956   298  1056 D CommandListener: Trying to bring up p2p0
,08-05 14:14:42.956   765  1148 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-05 14:14:42.956   765  1148 D WifiP2pService: P2pEnablingState
,08-05 14:14:42.956   765  1148 D WifiP2pService: P2pEnablingState{ what=147457 }
08-05 14:14:42.956   765  1148 D WifiP2pService: P2p socket connection successful
08-05 14:14:42.956   765  1148 D WifiP2pService: P2pEnabledState
,08-05 14:14:42.956   765   765 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-05 14:14:42.956   765  1059 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-05 14:14:42.956   765  1059 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-05 14:14:42.956   765  1059 D WifiDisplayController: disconnect
08-05 14:14:42.956   765  1059 D WifiDisplayController: updateConnection
08-05 14:14:42.956   765  1059 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-05 14:14:42.956   765  1059 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-05 14:14:42.966   765  1149 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-05 14:14:42.966   765  1149 D WifiNative-HAL: callSECStringApiVoid - ID [215]
08-05 14:14:42.966   765  1149 E WifiNative-HAL: invaild command id : 215
,08-05 14:14:42.966   765  1148 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-05 14:14:42.966   765  1059 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:42.966   765  1151 E ConnectivityService: updateNetworkInfo()
08-05 14:14:42.966   765  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,08-05 14:14:42.966   765  1059 D WifiDisplayAdapter: onP2pDisconnected
08-05 14:14:42.966   765  1059 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-05 14:14:42.966   765  1059 D IpRemoteDisplayController: WfdBridgeServer is already null
08-05 14:14:42.966  7686  7686 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,08-05 14:14:42.966  1196  1196 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-05 14:14:42.966   765  1148 D WifiNative-HAL: p2pGetDeviceAddress
08-05 14:14:42.966   765  1148 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:de:28:a3
08-05 14:14:42.966   765  1467 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-05 14:14:42.966  1196  1196 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-05 14:14:42.976  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-05 14:14:42.976  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-05 14:14:42.976   765  1059 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
08-05 14:14:42.976   765  1059 D WifiDisplayController:  deviceAddress: ea:50:8b:de:28:a3
08-05 14:14:42.976   765  1059 D WifiDisplayController:  primary type: 10-0050F204-5
08-05 14:14:42.976   765  1059 D WifiDisplayController:  secondary type: null
08-05 14:14:42.976   765  1059 D WifiDisplayController:  wps: 0
08-05 14:14:42.976   765  1059 D WifiDisplayController:  grpcapab: 0
08-05 14:14:42.976   765  1059 D WifiDisplayController:  devcapab: 0
08-05 14:14:42.976   765  1059 D WifiDisplayController:  status: 3
08-05 14:14:42.976   765  1059 D WifiDisplayController:  wfdInfo: null
08-05 14:14:42.976   765  1059 D WifiDisplayController:  groupownerAddress: null
08-05 14:14:42.976   765  1059 D WifiDisplayController:  GOdeviceName: null
08-05 14:14:42.976   765  1059 D WifiDisplayController:  interfaceAddress: 
08-05 14:14:42.976   765  1059 D WifiDisplayController:  SConnectInfo : null
,08-05 14:14:42.976   765  1148 D WifiP2pService: DeviceAddress: ea:28:a3
08-05 14:14:42.976   765  1237 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:42.976  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-05 14:14:42.976   765  1322 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:42.976  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-05 14:14:42.976  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-05 14:14:42.976  1316  1316 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-05 14:14:42.976  1316  2693 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-05 14:14:42.976  7144  7144 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-05 14:14:42.986  7686  7686 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-05 14:14:42.986  7686  7686 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
08-05 14:14:42.986  7686  7686 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,08-05 14:14:42.986  7686  7686 D WifiDirectBR: stopServiceTest : false
,08-05 14:14:42.996  8375  8375 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-05 14:14:43.016  8375  8375 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,08-05 14:14:43.036   765  1148 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-05 14:14:43.036   765  1148 D WifiP2pService: InactiveState
08-05 14:14:43.036   765  1148 D WifiP2pService: InactiveState{ what=143376 }
08-05 14:14:43.036   765  1148 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-05 14:14:43.036  8375  8375 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-05 14:14:43.036   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-05 14:14:43.036   765  1149 D SecContentProvider2: mCursor = null
,08-05 14:14:43.036   765  1148 D WifiP2pService: InactiveState{ what=143376 }
08-05 14:14:43.036   765  1148 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-05 14:14:43.036   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-05 14:14:43.036   765  1149 D SecContentProvider2: mCursor = null
,08-05 14:14:43.146  8298  8344 D bt_upio : ..proc_btwrite_timeout..
,08-05 14:14:43.536  7501  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:43.536  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:43.536  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:43.536  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:43.536  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:43.536  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:43.536  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:43.536  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 14:14:43.546  7501  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-05 14:14:43.546  7501  7570 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-05 14:14:43.546  7501  7570 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-05 14:14:43.556  7501  7570 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@8a37590 Bundle[{}]
,08-05 14:14:43.556  7501  7570 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-05 14:14:43.556  7501  7570 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-05 14:14:43.556  7501  7570 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-05 14:14:43.556  7501  7570 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-05 14:14:43.556  7501  7570 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-05 14:14:43.556  7501  7570 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-05 14:14:43.566  7501  7570 I System.out: Running OutgoingSocketThread
,08-05 14:14:43.566  7501  8417 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1318)
,08-05 14:14:43.566  7501  8417 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 55272
,08-05 14:14:43.566  7501  8417 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-05 14:14:43.746  8375  8375 I wpa_supplicant: nl80211: Received scan results (21 BSSes)
08-05 14:14:43.746  8375  8375 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-05 14:14:43.746  8375  8375 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
08-05 14:14:43.746  8375  8375 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-05 14:14:43.746  8375  8375 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=5 BSSID=00.00.00 SSID=4E47373030
,08-05 14:14:43.756   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-05 14:14:43.756   765  1149 D SecContentProvider2: mCursor = null
,08-05 14:14:43.816  8375  8375 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-05 14:14:43.816  8375  8375 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=6 BSSID=00.00.00 SSID=4E47373030
,08-05 14:14:43.816  8375  8375 I wpa_supplicant: Associated with F4.99.3E
08-05 14:14:43.816  8375  8375 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-05 14:14:43.816  8375  8375 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-05 14:14:43.816   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-05 14:14:43.816   765  1149 D SecContentProvider2: mCursor = null
,08-05 14:14:43.826   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-05 14:14:43.826   765  1149 D SecContentProvider2: mCursor = null
,08-05 14:14:43.826  8375  8375 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-05 14:14:43.836  8375  8375 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-05 14:14:43.836  8375  8375 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-05 14:14:43.836  8375  8375 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-05 14:14:43.836  8375  8375 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-05 14:14:43.836  8375  8375 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=1 id_str=]
08-05 14:14:43.836  8375  8375 I wpa_supplicant: Blacklist: Clear (temp) 
08-05 14:14:43.836  8375  8375 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-05 14:14:43.836   765  1149 D WifiNative-HAL: callSECApiVoid - ID [50]
,08-05 14:14:43.846  1196  1196 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-05 14:14:43.846  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-05 14:14:43.846   765  1149 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-05 14:14:43.846   765  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-05 14:14:43.846   765  1151 D ConnectivityService: Got NetworkAgent Messenger
08-05 14:14:43.846   765  1151 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,08-05 14:14:43.846   765  1151 E ConnectivityService: updateNetworkInfo()
08-05 14:14:43.846   765  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 14:14:43.846   765  1151 D ConnectivityService: NetworkAgent connected
,08-05 14:14:43.856  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-05 14:14:43.856  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-05 14:14:43.856   765  3410 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:43.856  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-05 14:14:43.856   765  1706 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:43.856  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,08-05 14:14:43.856  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-05 14:14:43.856  1316  1316 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-05 14:14:43.856  1316  2693 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-05 14:14:43.866   765  1452 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:43.866   765  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-05 14:14:43.866  7037  7037 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-05 14:14:43.876   298  1056 D CommandListener: Setting iface cfg
,08-05 14:14:43.876   765  1149 E WifiStateMachine: Start Dhcp Watchdog 3
,08-05 14:14:43.876   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-05 14:14:43.876   765  1149 D SecContentProvider2: mCursor = null
,08-05 14:14:43.886  1196  1196 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-05 14:14:43.886  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-05 14:14:43.886   765  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,08-05 14:14:43.896   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-05 14:14:43.896   765  1149 D SecContentProvider2: mCursor = null
,08-05 14:14:43.976   765  1149 E native  : do suspend false
,08-05 14:14:43.976   765  1148 D WifiP2pService: InactiveState{ what=143375 }
,08-05 14:14:43.976   765  1148 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-05 14:14:44.166   305   305 E SMD     : DCD ON
,08-05 14:14:44.196  8422  8422 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-05 14:14:44.196  8422  8422 I dhcpcd  : version 5.5.6 starting
,08-05 14:14:44.196  8422  8422 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-05 14:14:44.256  8422  8422 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-05 14:14:44.256  8422  8422 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-05 14:14:44.256  8422  8422 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-05 14:14:44.256  8422  8422 I dhcpcd  : bssid match
08-05 14:14:44.256  8422  8422 I dhcpcd  : wlan0: rebinding lease of 192.168.1.122
,08-05 14:14:44.276  8422  8422 I dhcpcd  : wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,08-05 14:14:44.276  8422  8422 I dhcpcd  : wlan0: leased 192.168.1.122 for 172800 seconds
,08-05 14:14:44.276   765  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,08-05 14:14:44.566  7501  7570 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1319)
08-05 14:14:44.566  7501  7570 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1319)
08-05 14:14:44.566  7501  7570 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1324)
08-05 14:14:44.566  7501  7570 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-05 14:14:44.566  7501  7570 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1325)
08-05 14:14:44.566  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 14:14:44.566  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ec17561 added. We now have 2 listener(s)
08-05 14:14:44.576  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
08-05 14:14:44.576  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 14:14:44.576  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 14:14:44.576  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:44.576  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1428b886 added. We now have 9 listener(s)
08-05 14:14:44.576  7501  7570 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:44.576  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 14:14:44.576  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,08-05 14:14:44.576  7501  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:44.576  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:44.576  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:44.576  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:44.576  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:44.576  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:44.576  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:44.576  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 14:14:44.576  7501  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:44.576  7501  7570 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 14:14:44.586  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:44.586  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:44.586  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 14:14:44.586  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@285c6174 added. We now have 3 listener(s)
,08-05 14:14:44.586  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,08-05 14:14:44.586  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 14:14:44.586  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 14:14:44.586  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:44.586  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28bf069d added. We now have 10 listener(s)
08-05 14:14:44.586  7501  7570 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:44.586  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 14:14:44.586  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:44.586  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:44.586   765  1149 E native  : do suspend true
,08-05 14:14:44.586  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:44.586  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:44.586  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:44.586  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-05 14:14:44.586  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ec17561 removed from the list
08-05 14:14:44.586  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:44.596  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1428b886 removed from the list
08-05 14:14:44.596  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
,08-05 14:14:44.596  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:44.596  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:44.596  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:44.596  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:44.596  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:44.596  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:44.596  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1428b886 not in the list
08-05 14:14:44.596  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 14:14:44.596  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:44.596  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:44.596  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:44.596  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-05 14:14:44.596  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28bf069d removed from the list
,08-05 14:14:44.596  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:44.596  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-05 14:14:44.596   765  1148 D WifiP2pService: InactiveState{ what=143375 }
,08-05 14:14:44.596   765  1148 D WifiP2pService: P2pEnabledState{ what=143375 }
08-05 14:14:44.596  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:44.606  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 14:14:44.606  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@285c6174 removed from the list
,08-05 14:14:44.606  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 14:14:44.606  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c7d712 added. We now have 2 listener(s)
,08-05 14:14:44.606   765  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,08-05 14:14:44.606  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
08-05 14:14:44.606  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 14:14:44.606  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-05 14:14:44.606  1196  1196 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-05 14:14:44.606  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-05 14:14:44.606  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-05 14:14:44.606  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d8a3ee3 added. We now have 9 listener(s)
08-05 14:14:44.606  7501  7570 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:44.606   765  1149 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-05 14:14:44.606   765  1149 E WifiStateMachine: VerifyingLinkState enter
08-05 14:14:44.606  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 14:14:44.616  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 14:14:44.616   765  1149 D WifiNative-HAL: callSECApiInt - ID [210]
,08-05 14:14:44.616   765  1151 E ConnectivityService: updateNetworkInfo()
,08-05 14:14:44.616   765  1151 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-05 14:14:44.616   765  1151 D ConnectivityService: Adding iface wlan0 to network 504
,08-05 14:14:44.616   765  1162 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-05 14:14:44.616  1196  1196 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-05 14:14:44.616   765  1162 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-05 14:14:44.616  7501  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:44.616  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:44.616  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:44.616  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:44.616  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:44.616  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:44.616  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:44.616  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 14:14:44.626   765  1162 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-05 14:14:44.626   765  1162 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-05 14:14:44.626   765  1162 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-05 14:14:44.626  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-05 14:14:44.626  7501  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:44.626  7501  7570 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 14:14:44.626  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 14:14:44.626  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a6f99 added. We now have 3 listener(s)
,08-05 14:14:44.626  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 14:14:44.626  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:44.636  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,08-05 14:14:44.636  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-05 14:14:44.636  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 14:14:44.636  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:44.636  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c8525e added. We now have 10 listener(s)
,08-05 14:14:44.636  7501  7570 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:44.636  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 14:14:44.636  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,08-05 14:14:44.636  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 14:14:44.636  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:44.636  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-05 14:14:44.636  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-05 14:14:44.646   765  1149 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-05 14:14:44.656  7501  7570 E BluetoothAdapter: bluetooth le advertising not supported
08-05 14:14:44.656   765   765 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-05 14:14:44.656  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 14:14:44.656  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-05 14:14:44.656  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-05 14:14:44.656  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-05 14:14:44.656  7501  7570 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-05 14:14:44.656  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:44.656  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-05 14:14:44.656  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-05 14:14:44.656  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:44.656  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:44.656  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-05 14:14:44.656  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:44.666  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:44.666  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-05 14:14:44.666  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7c7d712 removed from the list
08-05 14:14:44.666  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:44.666  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d8a3ee3 removed from the list
08-05 14:14:44.666  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:44.666  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:44.666  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:44.666  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:44.666  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-05 14:14:44.666  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:44.666  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:44.666  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d8a3ee3 not in the list
08-05 14:14:44.666  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:44.666  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:44.666  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-05 14:14:44.666  7501  7570 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:44.666  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:44.666  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:44.666  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:44.666  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c8525e removed from the list
,08-05 14:14:44.666  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:44.666  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:44.666  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:44.666  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 14:14:44.666  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2d0a6f99 removed from the list
,08-05 14:14:44.666  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-05 14:14:44.666  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-05 14:14:44.666  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d096c55 added. We now have 2 listener(s)
,08-05 14:14:44.666  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,08-05 14:14:44.676  1196  1196 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-05 14:14:44.676   765   765 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-05 14:14:44.676   765   765 I WifiTrafficPoller: mBoosterFLAG : 0
08-05 14:14:44.676   765   765 I WifiTrafficPoller: current booster mode : FullMode
08-05 14:14:44.676   765   765 D WifiNative-HAL: callSECApiVoid - ID [212]
,08-05 14:14:44.676  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-05 14:14:44.676  1196  1196 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-05 14:14:44.676  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-05 14:14:44.676   765  1149 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-05 14:14:44.676  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,08-05 14:14:44.676  1196  1196 D StatusBar.NetworkController: applyOpen
,08-05 14:14:44.676  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:44.676   765  1151 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
08-05 14:14:44.676  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:44.676  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,08-05 14:14:44.676  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:44.676   765  1151 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
08-05 14:14:44.676  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:44.676  1196  1196 D StatusBar.NetworkController: applyOpen
,08-05 14:14:44.676   765  1151 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 504
08-05 14:14:44.676  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 14:14:44.676  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 14:14:44.676  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:44.676  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ac3366a added. We now have 9 listener(s)
08-05 14:14:44.676  7501  7570 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:44.686   765  1151 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-05 14:14:44.686   765  1151 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
08-05 14:14:44.686   765  1151 D ConnectivityService: updateSourceRoutes : add src route for:192.168.1.122
08-05 14:14:44.686   298  1056 V         : QcRouteController
,08-05 14:14:44.686   765  3349 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-05 14:14:44.686   765  3349 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,08-05 14:14:44.686  1316  1316 I NearbySettings: MountReceiver.onReceive - Keep current state
08-05 14:14:44.686   765  3349 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
08-05 14:14:44.686  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-05 14:14:44.686   765  3349 D BatteryService: stay LED for fully charged
08-05 14:14:44.696   765   765 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-05 14:14:44.696  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-05 14:14:44.696  1196  1196 D KeyguardUpdateMonitor: handleBatteryUpdate
08-05 14:14:44.696   765   765 I MotionRecognitionService: Plugged
08-05 14:14:44.696   765   765 I MotionRecognitionService: setPowerConnected  = true
08-05 14:14:44.696  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 14:14:44.696  8298  8298 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-05 14:14:44.706  8298  8330 D HeadsetStateMachine: Disconnected process message: 10
08-05 14:14:44.706   298  1056 V         : QcRouteController
,08-05 14:14:44.706  7501  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:44.706  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:44.706  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:44.706  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:44.706  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:44.706  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:44.706  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:44.706  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-05 14:14:44.706  1196  1196 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
08-05 14:14:44.706  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-05 14:14:44.706  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-05 14:14:44.706  1196  1196 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-05 14:14:44.706  7501  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:44.706  7501  7570 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 14:14:44.706  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 14:14:44.706  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fbd2bf8 added. We now have 3 listener(s)
,08-05 14:14:44.706  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:44.706   765  1526 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:44.716   298  1056 V         : QcRouteController
08-05 14:14:44.716  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:44.716  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
08-05 14:14:44.716  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 14:14:44.716  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 14:14:44.716  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:44.716  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c178d1 added. We now have 10 listener(s)
08-05 14:14:44.716  7501  7570 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:44.716  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-05 14:14:44.716  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 14:14:44.716  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 14:14:44.716  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 14:14:44.716  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:44.716  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-05 14:14:44.726  7037  7037 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-05 14:14:44.726  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-05 14:14:44.726  7501  7570 E BluetoothAdapter: bluetooth le advertising not supported
08-05 14:14:44.726  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 14:14:44.726  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-05 14:14:44.736  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-05 14:14:44.736  1316  1316 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-05 14:14:44.736  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-05 14:14:44.736  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:44.736   765  1452 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:44.736  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-05 14:14:44.736  7501  7570 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-05 14:14:44.736  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:44.736  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:44.736   765  1467 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:44.736  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:44.736  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:44.736  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:44.736  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:44.736  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 14:14:44.736  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d096c55 removed from the list
08-05 14:14:44.736  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:44.736  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ac3366a removed from the list
08-05 14:14:44.736  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-05 14:14:44.736  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:44.736  1316  1316 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-05 14:14:44.736  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:44.736  1316  1316 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-05 14:14:44.736  1316  2693 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-05 14:14:44.736  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:44.736  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:44.736  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:44.736  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:44.736  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:44.736  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1ac3366a not in the list
08-05 14:14:44.736  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:44.736  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:44.736   298  1056 V         : QcRouteController
,08-05 14:14:44.736  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:44.736  7501  7570 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:44.736  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:44.736  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:44.736  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:44.736  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c178d1 removed from the list
,08-05 14:14:44.736  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:44.736  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:44.736  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:44.736  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 14:14:44.736  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3fbd2bf8 removed from the list
08-05 14:14:44.736  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 14:14:44.736  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2950fa4 added. We now have 2 listener(s)
,08-05 14:14:44.736  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
08-05 14:14:44.736  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 14:14:44.736  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 14:14:44.736  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:44.736  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@113d10d added. We now have 9 listener(s)
08-05 14:14:44.736  7501  7570 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 14:14:44.736  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 14:14:44.746  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 14:14:44.746  7501  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:44.746  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:44.746  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:44.746  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:44.746  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:44.746  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:44.746  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:44.746  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 14:14:44.746   765  1677 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:44.746  7037  7037 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-05 14:14:44.756  7501  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:44.756  7501  7570 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 14:14:44.756  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 14:14:44.756  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14f8a6d3 added. We now have 3 listener(s)
,08-05 14:14:44.756  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
08-05 14:14:44.756  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 14:14:44.756  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 14:14:44.756  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:44.756  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae58210 added. We now have 10 listener(s)
08-05 14:14:44.756  7501  7570 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-05 14:14:44.756  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 14:14:44.756  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-05 14:14:44.756  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-05 14:14:44.756  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-05 14:14:44.756  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-05 14:14:44.756  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:44.756  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:44.756   298  1056 V         : QcRouteController
08-05 14:14:44.756  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-05 14:14:44.766   765  1001 W ProcessCpuTracker: Skipping unknown process pid 8471
,08-05 14:14:44.766   765  1001 W ProcessCpuTracker: Skipping unknown process pid 8472
,08-05 14:14:44.766  7501  7570 E BluetoothAdapter: bluetooth le advertising not supported
08-05 14:14:44.766  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-05 14:14:44.766  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-05 14:14:44.766  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-05 14:14:44.766  1316  1316 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-05 14:14:44.766  1316  1316 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-05 14:14:44.766  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-05 14:14:44.766  7501  7570 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-05 14:14:44.776  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:44.776  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:44.776  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:44.776  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:44.776  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:44.776  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:44.776  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 14:14:44.776  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2950fa4 removed from the list
08-05 14:14:44.776  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:44.776  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@113d10d removed from the list
08-05 14:14:44.776  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:44.776  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:44.776  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:44.776  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:44.776   298  1056 V         : QcRouteController
08-05 14:14:44.776   765  1706 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
08-05 14:14:44.776  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:44.776  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:44.776  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:44.776  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@113d10d not in the list
08-05 14:14:44.776  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:44.776  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:44.776  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:44.776  7501  7570 D BluetoothLeScanner: could not find callback wrapper
08-05 14:14:44.776  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-05 14:14:44.776  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:44.776  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:44.776  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ae58210 removed from the list
08-05 14:14:44.776  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:44.776  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:44.776  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:44.776  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 14:14:44.776  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@14f8a6d3 removed from the list
,08-05 14:14:44.776  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 14:14:44.776  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@289cdd2f added. We now have 2 listener(s)
,08-05 14:14:44.776   298  1056 V         : QcRouteController
,08-05 14:14:44.776  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
08-05 14:14:44.776  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 14:14:44.776  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 14:14:44.776  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:44.776  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1788af3c added. We now have 9 listener(s)
08-05 14:14:44.776  7501  7570 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 14:14:44.786  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 14:14:44.786  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 14:14:44.786   765  1437 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:44.786  7501  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 14:14:44.786  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:44.786  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:44.786  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:44.786  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:44.786  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-05 14:14:44.786  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-05 14:14:44.786  7501  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-05 14:14:44.796  7501  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-05 14:14:44.796  7501  7570 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 14:14:44.796  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-05 14:14:44.796  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@104e0e1a added. We now have 3 listener(s)
,08-05 14:14:44.796   298  1056 V         : QcRouteController
08-05 14:14:44.796  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:44.796  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 14:14:44.796  7037  7037 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-05 14:14:44.796  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
08-05 14:14:44.796  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 14:14:44.796  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-05 14:14:44.796  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-05 14:14:44.796  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ba41d4b added. We now have 10 listener(s)
08-05 14:14:44.796  7501  7570 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 14:14:44.796  7501  7570 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-05 14:14:44.796  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-05 14:14:44.796  7501  7570 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-05 14:14:44.796  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:44.796  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:44.796  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-05 14:14:44.796  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 14:14:44.796  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@289cdd2f removed from the list
08-05 14:14:44.796  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:44.796  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1788af3c removed from the list
08-05 14:14:44.796  7501  7570 D io.jxcore.node.ConnectivityMonitor: stop
08-05 14:14:44.796  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:44.796  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:44.796  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:44.796  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:44.796  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:44.796  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:44.796  7501  7570 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1788af3c not in the list
08-05 14:14:44.796  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:44.796  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-05 14:14:44.796  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-05 14:14:44.796  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-05 14:14:44.796  7501  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 14:14:44.796  7501  7570 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ba41d4b removed from the list
08-05 14:14:44.796  7501  7570 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 14:14:44.796  7501  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 14:14:44.796  7501  7570 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 14:14:44.796  7501  7570 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 14:14:44.796  7501  7570 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@104e0e1a removed from the list
,08-05 14:14:44.806  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-05 14:14:44.806  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-05 14:14:44.806  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,08-05 14:14:44.806  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-05 14:14:44.806  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-05 14:14:44.806  7501  7570 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-05 14:14:44.806   266   266 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
,08-05 14:14:44.816  7501  8489 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1332, name: My test thread name)
,08-05 14:14:44.816  7501  8489 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1332, thread name: My test thread name)
08-05 14:14:44.816  7501  8489 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1332, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-05 14:14:44.816   765  1151 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
,08-05 14:14:44.816   765  1151 D ConnectivityService: LTETest block dns file not exists
,08-05 14:14:44.816   765  1151 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
08-05 14:14:44.816   765  1151 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-05 14:14:44.816   765  1151 D ConnectivityService: calling update connectivity
08-05 14:14:44.816   765  1151 E ConnectivityService: updateNetworkInfo()
08-05 14:14:44.816   765  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
08-05 14:14:44.816   765  1151 E ConnectivityService: updateNetworkInfo()
08-05 14:14:44.816   765  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
08-05 14:14:44.816   765  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 14:14:44.816   765  8418 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:44.816   765  1151 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-05 14:14:44.816   765  8418 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-05 14:14:44.816   765  1151 D ConnectivityService: calling update connectivity
08-05 14:14:44.816   765  8418 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-05 14:14:44.816   765  1151 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-05 14:14:44.816   765  8418 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-05 14:14:44.816   765  1151 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 14:14:44.816   765  1058 D EntConnectivity: Not allowed due to - mEnabled false
08-05 14:14:44.816   765  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 14:14:44.816   765  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:44.816   765  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 14:14:44.816   765  8418 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-05 14:14:44.826   765  1151 D ConnectivityService: currentScore = 0, newScore = 60
08-05 14:14:44.826   765  1151 D ConnectivityService:    accepting network in place of null
08-05 14:14:44.826   765  1151 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 14:14:44.826  1425  1425 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:44.826   765  1151 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-05 14:14:44.826   765  1151 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-05 14:14:44.826   765  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-05 14:14:44.826   765  1151 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
08-05 14:14:44.826   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-05 14:14:44.826   765  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
08-05 14:14:44.826  7501  8490 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1334, name: My test thread name)
08-05 14:14:44.826  7501  8490 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1334, thread name: My test thread name)
08-05 14:14:44.826   765  1153 D SmartBondingService: getSBEnabled() enabled =false
08-05 14:14:44.826  7501  8490 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1334, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-05 14:14:44.826   765  1153 D SmartBondingService: getSBEnabled() enabled =false
08-05 14:14:44.826   765  1153 D SmartBondingService: getSBEnabled() enabled =false
,08-05 14:14:44.826   765  1152 D Tethering: MasterInitialState.processMessage what=3
08-05 14:14:44.826   765  1146 V NetworkStats: updateIfacesLocked()
08-05 14:14:44.826   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 14:14:44.826   765  1146 V NetworkStats: performPollLocked(flags=0x1)
,08-05 14:14:44.826   765  1437 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=765
08-05 14:14:44.826  7501  7570 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-05 14:14:44.826  7501  7570 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-05 14:14:44.826   765  1146 D NetworkStatsFactory: UpdateStatsForKnox
08-05 14:14:44.826  7501  7570 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-05 14:14:44.826  7501  7570 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-05 14:14:44.826   765  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:44.826  7501  7570 D com.test.thalitest.ThaliTestRunner: Total duration: 23794 ms
,08-05 14:14:44.826   765  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
08-05 14:14:44.826   765  1151 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,08-05 14:14:44.826   765  1146 V NetworkStats: performPollLocked() took 3ms
08-05 14:14:44.826   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 14:14:44.836   765  1058 D EntConnectivity: Not allowed due to - mEnabled false
08-05 14:14:44.836   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 14:14:44.836   765  1151 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-05 14:14:44.836   765  1151 D ConnectivityService: calling update connectivity
08-05 14:14:44.836   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:44.836   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 14:14:44.836  7501  7570 I jxcore-log: Total number of executed tests:  80
08-05 14:14:44.836  7501  7570 I jxcore-log: 
08-05 14:14:44.836   765  1151 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 14:14:44.836   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 14:14:44.836   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 14:14:44.836  7501  7570 I jxcore-log: Number of passed tests:  80
08-05 14:14:44.836  7501  7570 I jxcore-log: 
08-05 14:14:44.836   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 14:14:44.836   765  1147 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-05 14:14:44.836   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 14:14:44.836  7501  7570 I jxcore-log: Number of failed tests:  0
08-05 14:14:44.836  7501  7570 I jxcore-log: 
08-05 14:14:44.836   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 14:14:44.836  7501  7570 I jxcore-log: Number of ignored tests:  0
08-05 14:14:44.836  7501  7570 I jxcore-log: 
,08-05 14:14:44.836   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:44.836  1196  1593 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-05 14:14:44.836   765  1151 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:44.836  7501  7570 I jxcore-log: Total duration:  23794
08-05 14:14:44.836  7501  7570 I jxcore-log: 
,08-05 14:14:44.836   765  1237 I AudioService: getStreamVolume 3 index 0
,08-05 14:14:44.836  4411  7336 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-05 14:14:44.836  7501  7570 I jxcore-log: Unit Test app is loaded
08-05 14:14:44.836  7501  7570 I jxcore-log: 
,08-05 14:14:44.846   765  1452 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:44.846  1196  1196 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-05 14:14:44.846  1196  1196 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-05 14:14:44.846  1196  1196 D StatusBar.NetworkController: updateDataNetType()
08-05 14:14:44.846  1196  1196 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-05 14:14:44.846  1196  1196 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-05 14:14:44.846  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 14:14:44.846  7501  7570 I jxcore-log: 
,08-05 14:14:44.846  7501  7501 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-05 14:14:44.846  1196  1196 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-05 14:14:44.846  1196  1196 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-05 14:14:44.846  1196  1196 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-05 14:14:44.846  1196  1196 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-05 14:14:44.846  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-05 14:14:44.846  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:44.846  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:44.846  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:44.846  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:44.846  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:44.846  1196  1196 D StatusBar.NetworkController: applyOpen
08-05 14:14:44.846  1196  1196 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-05 14:14:44.846  1196  1196 D StatusBar.NetworkController: applyOpen
,08-05 14:14:44.846  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 14:14:44.846  7501  7570 I jxcore-log: 
,08-05 14:14:44.856  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 14:14:44.856  7501  7570 I jxcore-log: 
,08-05 14:14:44.856  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 14:14:44.856  7501  7570 I jxcore-log: 
,08-05 14:14:44.856  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 14:14:44.856  7501  7570 I jxcore-log: 
,08-05 14:14:44.856  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 14:14:44.856  7501  7570 I jxcore-log: 
,08-05 14:14:44.856  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 14:14:44.856  7501  7570 I jxcore-log: 
,08-05 14:14:44.856  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 14:14:44.856  7501  7570 I jxcore-log: 
,08-05 14:14:44.856  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 14:14:44.856  7501  7570 I jxcore-log: 
,08-05 14:14:44.856  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-05 14:14:44.856  7501  7570 I jxcore-log: 
,08-05 14:14:44.856  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 14:14:44.856  7501  7570 I jxcore-log: 
,08-05 14:14:44.856  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-05 14:14:44.856  7501  7570 I jxcore-log: 
,08-05 14:14:44.856  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 14:14:44.856  7501  7570 I jxcore-log: 
,08-05 14:14:44.856  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 14:14:44.856  7501  7570 I jxcore-log: 
,08-05 14:14:44.856  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 14:14:44.856  7501  7570 I jxcore-log: 
,08-05 14:14:44.856  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 14:14:44.856  7501  7570 I jxcore-log: 
,08-05 14:14:44.866  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 14:14:44.866  7501  7570 I jxcore-log: 
,08-05 14:14:44.866  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-05 14:14:44.866  7501  7570 I jxcore-log: 
,08-05 14:14:44.866  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 14:14:44.866  7501  7570 I jxcore-log: 
,08-05 14:14:44.866  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-05 14:14:44.866  7501  7570 I jxcore-log: 
08-05 14:14:44.866  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 14:14:44.866  7501  7570 I jxcore-log: 
,08-05 14:14:44.866  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 14:14:44.866  7501  7570 I jxcore-log: 
,08-05 14:14:44.866  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 14:14:44.866  7501  7570 I jxcore-log: 
08-05 14:14:44.866  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 14:14:44.866  7501  7570 I jxcore-log: 
,08-05 14:14:44.866  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 14:14:44.866  7501  7570 I jxcore-log: 
08-05 14:14:44.866  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 14:14:44.866  7501  7570 I jxcore-log: 
,08-05 14:14:44.866  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-05 14:14:44.866  7501  7570 I jxcore-log: 
,08-05 14:14:44.876  7501  7570 I jxcore-log: My device name is: samsung-SM-N9005
08-05 14:14:44.876  7501  7570 I jxcore-log: 
,08-05 14:14:44.906   765  8418 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-05 14:14:45.006   765  8418 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Fri, 05 Aug 2016 12:14:45 GMT], X-Android-Received-Millis=[1470399285018], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470399284961]}
,08-05 14:14:45.006   765  8418 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-05 14:14:45.006   765  8418 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-05 14:14:45.006   765  1151 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-05 14:14:45.006   765  1151 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-05 14:14:45.006   765  1151 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-05 14:14:45.006   765  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,08-05 14:14:45.006   765  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:45.006   765  1151 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-05 14:14:45.006   765  1151 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-05 14:14:45.006   765  1151 D ConnectivityService: calling update connectivity
08-05 14:14:45.006   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:45.006   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 14:14:45.006   765  1151 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-05 14:14:45.006   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:45.006  1196  1593 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-05 14:14:45.006   765  1151 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 14:14:45.006   765  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-05 14:14:45.006  4411  7336 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-05 14:14:45.006   765  1647 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.006  1196  1196 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-05 14:14:45.006  1196  1196 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-05 14:14:45.006  1196  1196 D StatusBar.NetworkController: updateDataNetType()
08-05 14:14:45.006  1196  1196 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-05 14:14:45.006  1196  1196 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-05 14:14:45.006  1196  1196 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-05 14:14:45.006  1196  1196 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-05 14:14:45.006  1196  1196 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-05 14:14:45.006  1196  1196 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-05 14:14:45.006  1196  1196 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-05 14:14:45.326   765  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-05 14:14:45.336   765   765 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.336   765   988 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-05 14:14:45.336   765   765 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.336   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
08-05 14:14:45.336   765   765 D SmartBondingService: SmartBondingReceiver: wifi is connected
08-05 14:14:45.336   765   765 D SmartBondingService: SmartBondingReceiver: wifi ap is not changed
,08-05 14:14:45.336   765   765 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.336   765  1677 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.346   765  1437 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.346   765  1452 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:45.346   765  1706 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.346   765  1526 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.346   765  3410 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.346   765  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
,08-05 14:14:45.346   765  1153 D SmartBondingService: getSBEnabled() enabled =false
,08-05 14:14:45.346   765  1153 D SmartBondingService: getSBEnabled() enabled =false
,08-05 14:14:45.356   765  1153 D SmartBondingService: getSBEnabled() enabled =false
08-05 14:14:45.356   765   765 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.356   765  1578 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.356   765   765 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:45.356   765   765 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:45.356   765   765 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.356   765   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:45.356   765  1647 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.356  7766  7766 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-05 14:14:45.366   765   988 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.366   765   988 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.376   765  3410 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.376   765  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:45.376   765  1526 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.376   765  1578 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.376   765  1437 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.376   765  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,08-05 14:14:45.386  7501  7501 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-05 14:14:45.386  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 14:14:45.386  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 14:14:45.386  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 14:14:45.386  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 14:14:45.386  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 14:14:45.386  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 14:14:45.386  7501  7501 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 14:14:45.386  7501  7501 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 14:14:45.386  1480  1480 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-05 14:14:45.386   765  3349 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.396  6803  6803 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-05 14:14:45.396  6803  6803 I PCWCLIENTTRACE_PushUtil: sales region : global
08-05 14:14:45.396  6803  6803 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-05 14:14:45.396  6803  6803 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-05 14:14:45.406  7766  7766 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,08-05 14:14:45.416   765  1437 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-05 14:14:45.416   765  1437 D SecContentProvider2: mCursor = null
,08-05 14:14:45.426  7823  7823 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-05 14:14:45.426  7823  7823 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-05 14:14:45.496  7844  7844 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,08-05 14:14:45.496  7844  7844 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,08-05 14:14:45.496  7844  7844 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,08-05 14:14:45.506  4023  4023 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-05 14:14:45.506  4023  4023 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1470399285520
,08-05 14:14:45.506  4023  4023 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,08-05 14:14:45.506   765  3349 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:45.506   765   784 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.506  4023  4023 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,08-05 14:14:45.506  4023  4023 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().START
,08-05 14:14:45.506  4023  4023 I KLMS-2.4.511: : NetworkChangeOperations(): uploadRequestLog().START 
,08-05 14:14:45.516  4023  4023 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,08-05 14:14:45.516   765  1677 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.526   765  1452 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,08-05 14:14:45.536   765  1452 D ActivityManager: caller:android.app.ApplicationThreadProxy@36baa329, r.packageName :com.samsung.android.app.galaxyfinder
08-05 14:14:45.536  7888  7888 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,08-05 14:14:45.556   765  1437 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.556  3554  8514 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
08-05 14:14:45.556  3554  8514 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,08-05 14:14:45.556  3554  8514 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
08-05 14:14:45.556  7908  7908 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-05 14:14:45.566  7924  7924 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,08-05 14:14:45.566  7924  7924 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
08-05 14:14:45.566  7924  7924 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-05 14:14:45.566  7924  7924 I SA      : [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
08-05 14:14:45.566  7924  7924 I SA      : [OR] == isSIMCardReady false ==
,08-05 14:14:45.566   765   784 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:45.566  7924  7924 I SA      : [SCU] == networkStateCheck == true
,08-05 14:14:45.566  7924  7924 I SA      : [DM] getCountryCodeFromCSC : PL
08-05 14:14:45.566  7924  7924 I SA      : isChinaCountryCode : false
08-05 14:14:45.566  7924  7924 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-05 14:14:45.566  7924  7924 I SA      : [OR] == networkStateCheck true ==
,08-05 14:14:45.566  7924  7924 I SA      : [OR] GetMyCountryZoneTask
,08-05 14:14:45.566  7924  7924 I SA      : [OR] onReceive END
,08-05 14:14:45.576   765  1526 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.576   765  1144 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
08-05 14:14:45.576   765  1144 D ActivityManager: caller:android.app.ApplicationThreadProxy@1e81ac4f, r.packageName :com.android.providers.downloads
,08-05 14:14:45.576  7945  7945 I SCloudBackupReceiver: Other Intent
,08-05 14:14:45.576  7159  7159 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
08-05 14:14:45.576  7159  7159 I KnoxUsageLogPro: premStatus:2
,08-05 14:14:45.586  7159  7159 I KnoxUsageLogPro: isEulaShown : false
08-05 14:14:45.586  7159  7159 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,08-05 14:14:45.586  3554  8514 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-05 14:14:45.586  3554  8514 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,08-05 14:14:45.586  3554  8514 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,08-05 14:14:45.586  7924  8515 I SA      : [SRS] prepareGetMyCountryZone
,08-05 14:14:45.586  3554  8514 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,08-05 14:14:45.586  3554  8514 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,08-05 14:14:45.596  3554  8514 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,08-05 14:14:45.596  3554  8514 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,08-05 14:14:45.596  3554  8514 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-05 14:14:45.596   765  1452 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.606  7924  8515 I SA      : [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,08-05 14:14:45.606  7924  8515 I SA      : [SSP] query invoked
,08-05 14:14:45.606   765  1526 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.606   765  1677 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.606  7924  8515 I SA      : [TPMU] GetMccFromDB : null
,08-05 14:14:45.606  3554  8514 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-05 14:14:45.606  7924  8515 I SA      : [SCU] getMccFromPreferece mcc = 260
,08-05 14:14:45.606  7924  8515 I SA      : [TPM] isNoProxy(default) : true
,08-05 14:14:45.616  8035  8035 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-05 14:14:45.616  8035  8035 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
08-05 14:14:45.616  8035  8035 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-05 14:14:45.616   765  3349 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.626   765  1144 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.626   765   784 D RCPManagerService: exchangeData() failure , invalid userId
,08-05 14:14:45.626   765  1706 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:45.626   765  1437 D RCPManagerService: exchangeData() failure , invalid userId
,08-05 14:14:45.626  7924  8515 E File    : fail readDirectory() errno=2
,08-05 14:14:45.626  3554  8514 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-05 14:14:45.626   765  1526 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.626  6711  6711 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-05 14:14:45.626  6711  6711 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-05 14:14:45.626  6711  6711 D SecurityLogAgent: StateMachine : Current State = 1
,08-05 14:14:45.626   765  1677 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:45.626  6711  6711 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-05 14:14:45.636   765   783 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.636   765  3410 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.636   765  1144 D ActivityManager: startService callerProcessName:com.sec.android.app.SmartClipService, calleePkgName: com.sec.android.app.SmartClipService
,08-05 14:14:45.636   765  1144 D ActivityManager: caller:android.app.ApplicationThreadProxy@2db5ddc8, r.packageName :com.sec.android.app.SmartClipService
,08-05 14:14:45.646   765  1647 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-05 14:14:45.646   765  1647 D ActivityManager: caller:android.app.ApplicationThreadProxy@30b28e61, r.packageName :com.google.android.gms
,08-05 14:14:45.646   765  1677 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.646   765   783 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:45.646   765  3410 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:45.646   765  1467 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:45.646   765   784 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:45.646   765  1322 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:45.646  4411  4411 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
08-05 14:14:45.656  4411  5388 I iu.UploadsManager: num queued entries: 0
08-05 14:14:45.656  4411  5388 I iu.UploadsManager: num updated entries: 0
08-05 14:14:45.656  4411  5388 I iu.SyncManager: NEXT; no task
08-05 14:14:45.666   765  3349 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:45.666  7096  7096 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-05 14:14:45.796   765  1647 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,08-05 14:14:45.796   765  1647 D ActivityManager: caller:android.app.ApplicationThreadProxy@236e5d86, r.packageName :com.sec.android.app.samsungapps
,08-05 14:14:45.806  7096  7096 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,08-05 14:14:45.806  7096  7096 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,08-05 14:14:45.806  7096  7096 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,08-05 14:14:45.806  7096  7096 D InitializeManagerStateMachine: exit::IDLE
08-05 14:14:45.806  7096  7096 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,08-05 14:14:45.806   765  1144 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.816   765  1452 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.816  7096  7096 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
08-05 14:14:45.816  7096  7096 D InitializeManagerStateMachine: exit::NETWORK_CHECK
08-05 14:14:45.816  7096  7096 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
08-05 14:14:45.816  7096  7096 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
,08-05 14:14:45.816  7096  7096 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
08-05 14:14:45.816  7096  7096 D InitializeManagerStateMachine: entry::SUCCESS
08-05 14:14:45.816  7096  7096 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,08-05 14:14:45.816  7096  7096 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,08-05 14:14:45.816  7096  7096 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
08-05 14:14:45.816   765  1322 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.826  7096  7096 D InitializeManagerStateMachine: exit::SUCCESS
,08-05 14:14:45.826  7096  7096 D InitializeManagerStateMachine: entry::IDLE
,08-05 14:14:45.836   765  1151 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-05 14:14:45.916   765  1647 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.926  1903  8520 I qtaguid : Tagging socket 52 with tag 1000040700000000{268436487,0} uid -1, pid: 1903, getuid(): 10015
,08-05 14:14:45.926   765  3410 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.926   765  3349 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:45.926   765  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:46.096   765  1237 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:46.096   765  1437 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:46.096   765  1526 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:46.096   765  1578 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:46.106   765   784 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:46.106   765  1706 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:46.106   765  1437 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:46.106  7924  8515 I SA      : [RC New] Execute method=[GET] start
,08-05 14:14:46.136  7924  8515 I SA      : [RC New] Security=[true]
,08-05 14:14:46.146  7924  8515 I System.out: Thread-1270(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,08-05 14:14:46.146  7924  8515 I System.out: Thread-1270(ApacheHTTPLog):isShipBuild true
,08-05 14:14:46.146  7924  8515 I System.out: Thread-1270(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,08-05 14:14:46.716  7924  8515 I SA      : [RC New] [v2liruge] api execute + 574
,08-05 14:14:46.716  7924  8515 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
,08-05 14:14:46.716  7924  8515 I System.out: AsyncTask #1 calls detatch()
,08-05 14:14:46.726  7924  8515 I SA      : [TPMU] getNetworkMcc : 
,08-05 14:14:46.736  7924  8515 I SA      : [SCU] saveMccToPreferece Start
,08-05 14:14:46.736  7924  8515 I SA      : [SCU] RegionMCC : 260
08-05 14:14:46.736  7924  8515 I SA      : [SSP] query invoked
,08-05 14:14:46.736  7924  8515 I SA      : [TPMU] GetMccFromDB : null
,08-05 14:14:46.736  7924  8515 I SA      : [SCU] getMccFromPreferece mcc = 260
08-05 14:14:46.736  7924  8515 I SA      : [SCU] saveMccToPreferece End
,08-05 14:14:46.736  7924  8515 I SA      : [RC New] executeRequest [v2liruge] end. 631
08-05 14:14:46.736  7924  8515 I SA      : [RC New] Execute end
,08-05 14:14:46.746  7924  7924 I SA      : [OR] GetMyCountryZoneTask mcc = 260
08-05 14:14:46.746  7924  7924 I SA      : [OR] GetMyCountryZoneTask Success
,08-05 14:14:47.106   765  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=true
,08-05 14:14:47.106   765  1151 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-05 14:14:47.106   765  1151 D ConnectivityService: identical MTU - not setting
08-05 14:14:47.106   765  1151 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
08-05 14:14:47.106   765  1151 D ConnectivityService: updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
,08-05 14:14:47.106   298  1056 V         : QcRouteController
08-05 14:14:47.106   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,08-05 14:14:47.106   765   765 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:14:47.106   765  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
08-05 14:14:47.106   765  1153 D SmartBondingService: getSBEnabled() enabled =false
08-05 14:14:47.106   765  1153 D SmartBondingService: getSBEnabled() enabled =false
,08-05 14:14:47.106   765  1153 D SmartBondingService: getSBEnabled() enabled =false
,08-05 14:14:47.126   298  1056 V         : QcRouteController
,08-05 14:14:47.126   765  1151 W NetworkManagementService: route cmd failed: 
08-05 14:14:47.126   765  1151 W NetworkManagementService: com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '103 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 103 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
08-05 14:14:47.126   765  1151 W NetworkManagementService: '
08-05 14:14:47.126   765  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
08-05 14:14:47.126   765  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
08-05 14:14:47.126   765  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
08-05 14:14:47.126   765  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
08-05 14:14:47.126   765  1151 W NetworkManagementService: 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2844)
08-05 14:14:47.126   765  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5632)
08-05 14:14:47.126   765  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5444)
08-05 14:14:47.126   765  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService.access$2400(ConnectivityService.java:230)
08-05 14:14:47.126   765  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2387)
08-05 14:14:47.126   765  1151 W NetworkManagementService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 14:14:47.126   765  1151 W NetworkManagementService: 	at android.os.Looper.loop(Looper.java:145)
08-05 14:14:47.126   765  1151 W NetworkManagementService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-05 14:14:47.126   765  1151 V Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true
08-05 14:14:47.126   765  1151 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-05 14:14:47.126   765  1151 D ConnectivityService: calling update connectivity
,08-05 14:14:47.136   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 14:14:47.136   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 14:14:47.136   765  1151 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-05 14:14:47.136   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:47.136  1196  1593 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-05 14:14:47.136   765  1151 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 14:14:47.136  4411  7336 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-05 14:14:47.136   765  1151 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-05 14:14:47.136   765  1151 D ConnectivityService: calling update connectivity
08-05 14:14:47.136   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:47.136   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-05 14:14:47.136   765  1151 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-05 14:14:47.136   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-05 14:14:47.136  1196  1593 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-05 14:14:47.136   765  1151 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-05 14:14:47.136  4411  7336 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-05 14:14:47.146  8298  8318 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-05 14:14:47.166   305   305 E SMD     : DCD ON
,08-05 14:14:47.306  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-05 14:14:47.306  7501  7570 I jxcore-log: 
,08-05 14:14:47.876  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-05 14:14:47.876  7501  7570 I jxcore-log: 
,08-05 14:14:47.896  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-05 14:14:47.896  7501  7570 I jxcore-log: 
,08-05 14:14:48.086   765  1149 E WifiStateMachine: CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,08-05 14:14:48.296   266   400 I SurfaceFlinger: id=13 Removed Uoast (8/9)
,08-05 14:14:48.296   266   922 I SurfaceFlinger: id=13 Removed Uoast (-2/9)
,08-05 14:14:48.306   765   783 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 765) eventTime = 407497
,08-05 14:14:48.316   765   783 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=765 (0x0)
08-05 14:14:48.316   765   783 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=765, ws=WorkSource{10067}) (elapsedTime=3487)
,08-05 14:14:48.566   765  1467 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,08-05 14:14:48.566   765  1467 D ActivityManager: caller:android.app.ApplicationThreadProxy@3b2f0e74, r.packageName :com.sec.spp.push
,08-05 14:14:48.586   765  1452 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:48.596  8422  8422 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,08-05 14:14:49.256  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-05 14:14:49.256  7501  7570 I jxcore-log: 
,08-05 14:14:49.366   765  1237 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:49.486  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-05 14:14:49.486  7501  7570 I jxcore-log: 
,08-05 14:14:49.486  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-05 14:14:49.486  7501  7570 I jxcore-log: 
,08-05 14:14:49.506  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-05 14:14:49.506  7501  7570 I jxcore-log: 
,08-05 14:14:49.506  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-05 14:14:49.506  7501  7570 I jxcore-log: 
,08-05 14:14:49.716   765  1061 I PowerManagerService: [PWL] Off : 330s ago
,08-05 14:14:50.056   765  1346 E Watchdog: !@Sync 13
,08-05 14:14:50.166  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-05 14:14:50.166  7501  7570 I jxcore-log: 
,08-05 14:14:50.166   305   305 E SMD     : DCD ON
,08-05 14:14:50.176  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
,08-05 14:14:50.176  7501  7570 I jxcore-log: 
,08-05 14:14:50.186  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js,
08-05 14:14:50.186  7501  7570 I jxcore-log: 
,08-05 14:14:50.196  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js,
08-05 14:14:50.196  7501  7570 I jxcore-log: 
,08-05 14:14:50.246  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js,
08-05 14:14:50.246  7501  7570 I jxcore-log: 
,08-05 14:14:50.296  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js,
08-05 14:14:50.296  7501  7570 I jxcore-log: 
,08-05 14:14:50.306  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js,
08-05 14:14:50.306  7501  7570 I jxcore-log: 
,08-05 14:14:50.406  6803  6803 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
,08-05 14:14:50.426   765  1647 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:14:50.426  6803  8536 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,08-05 14:14:50.446  6803  8536 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,08-05 14:14:50.446  6803  8536 E art     : No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
08-05 14:14:50.446  6803  8536 W PCWCLIENTTRACE_SecurePreferencesJNI: GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,08-05 14:14:50.446  6803  8536 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
,08-05 14:14:50.446  6803  8536 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-05 14:14:50.446  6803  8536 I PCWCLIENTTRACE_PushUtil: sales region : global
08-05 14:14:50.446  6803  8536 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-05 14:14:50.446  6803  8536 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,08-05 14:14:50.466  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-05 14:14:50.466  7501  7570 I jxcore-log: 
,08-05 14:14:50.476   346   346 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 14:14:50.496  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-05 14:14:50.496  7501  7570 I jxcore-log: 
,08-05 14:14:50.496  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-05 14:14:50.496  7501  7570 I jxcore-log: 
,08-05 14:14:50.506  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-05 14:14:50.506  7501  7570 I jxcore-log: 
,08-05 14:14:50.526  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-05 14:14:50.526  7501  7570 I jxcore-log: 
,08-05 14:14:50.606  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-05 14:14:50.606  7501  7570 I jxcore-log: 
,08-05 14:14:50.616  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js,
08-05 14:14:50.616  7501  7570 I jxcore-log: 
,08-05 14:14:50.646  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js,
08-05 14:14:50.646  7501  7570 I jxcore-log: 
,08-05 14:14:50.656  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js,
08-05 14:14:50.656  7501  7570 I jxcore-log: 
,08-05 14:14:50.676  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js,
08-05 14:14:50.676  7501  7570 I jxcore-log: 
,08-05 14:14:50.706  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-05 14:14:50.706  7501  7570 I jxcore-log: 
,08-05 14:14:50.716  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-05 14:14:50.716  7501  7570 I jxcore-log: 
,08-05 14:14:50.866  7501  7570 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-05 14:14:50.866  7501  7570 I jxcore-log: 
,08-05 14:14:50.876  7501  7570 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,08-05 14:14:50.876  7501  7570 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-05 14:14:50.876  7501  7570 I jxcore-log: 
,08-05 14:14:50.926  7501  7570 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 14:14:50.926  7501  7570 I jxcore-log: 
,08-05 14:14:51.476   346   346 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 14:14:51.696   765  3081 D SSRM:n  : SIOP:: AP = 370, PST = 335, CUR = 450
,08-05 14:14:52.486   346   346 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 14:14:52.596  8422  8422 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,08-05 14:14:53.166   305   305 E SMD     : DCD ON
,08-05 14:14:53.486   346   346 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 14:14:54.486   346   346 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 14:14:55.486   346   346 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5,
,08-05 14:14:55.806   765  1452 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,08-05 14:14:55.806   765  1452 D ActivityManager: caller:android.app.ApplicationThreadProxy@3642cc12, r.packageName :com.sec.android.app.samsungapps
,08-05 14:14:55.836  7096  7096 D PreloadUpdateManagerStateMachine: execute::IDLE:EXECUTE
,08-05 14:14:55.836  7096  7096 D PreloadUpdateManagerStateMachine: exit::IDLE
,08-05 14:14:55.836  7096  7096 D PreloadUpdateManagerStateMachine: entry::CHECK_TIMEOUT_FOR_UPDATE
,08-05 14:14:55.836  7096  7096 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,08-05 14:14:55.836  7096  7096 D PreloadUpdateManagerStateMachine: execute::CHECK_TIMEOUT_FOR_UPDATE:NO_TIMED_OUT
,08-05 14:14:55.836  7096  7096 D PreloadUpdateManagerStateMachine: exit::CHECK_TIMEOUT_FOR_UPDATE
,08-05 14:14:55.836  7096  7096 D PreloadUpdateManagerStateMachine: entry::IDLE
,08-05 14:14:56.166   305   305 E SMD     : DCD ON
,08-05 14:14:56.606  8422  8422 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,08-05 14:14:56.606  8422  8422 I dhcpcd  : wlan0: no IPv6 Routers available
,08-05 14:14:57.296   765  3114 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-05 14:14:58.866   765  3349 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-05 14:14:58.866   765  3349 D ActivityManager: caller:android.app.ApplicationThreadProxy@224c473f, r.packageName :com.google.android.gms
,08-05 14:14:58.876   765  1706 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-05 14:14:58.876   765  1706 D ActivityManager: caller:android.app.ApplicationThreadProxy@1bdf3555, r.packageName :com.google.android.gms
,08-05 14:14:58.916  4411  8557 W IcingInternalCorpora: getNumBytesRead when not calculated.
,08-05 14:14:58.996  1903  2320 I art     : Explicit concurrent mark sweep GC freed 71233(3MB) AllocSpace objects, 75(3MB) LOS objects, 40% free, 23MB/39MB, paused 634us total 44.138ms
,08-05 14:14:59.006   765  1289 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-05 14:14:59.006   765  1289 D ActivityManager: caller:android.app.ApplicationThreadProxy@19b9ba0d, r.packageName :com.google.android.gms
,08-05 14:14:59.026   765  1437 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-05 14:14:59.026   765  1437 D ActivityManager: caller:android.app.ApplicationThreadProxy@312f37d3, r.packageName :com.google.android.gms
,08-05 14:14:59.026   765  1289 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-05 14:14:59.026   765  1289 D ActivityManager: caller:android.app.ApplicationThreadProxy@144f3f10, r.packageName :com.google.android.gms
,08-05 14:14:59.026   765   784 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-05 14:14:59.036   765   784 D ActivityManager: caller:android.app.ApplicationThreadProxy@2154ea09, r.packageName :com.google.android.gms
,08-05 14:14:59.166   305   305 E SMD     : DCD ON
,08-05 14:15:01.736   765  3081 D SSRM:n  : SIOP:: AP = 340, PST = 338, CUR = 450
,08-05 14:15:02.166   305   305 E SMD     : DCD ON
,08-05 14:15:02.926   765  1116 V AlarmManager: waitForAlarm result :4
,08-05 14:15:02.946   765  1116 D ActivityManager: caller:null, r.packageName :com.google.android.gms
,08-05 14:15:02.956   765  1706 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-05 14:15:02.976   765  1467 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-05 14:15:02.976  1196  1196 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-05 14:15:02.976  1196  1196 D KeyguardUpdateMonitor: handleTimeUpdate
,08-05 14:15:02.976  1196  1196 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,08-05 14:15:02.976  1196  1196 I KeyguardEffectViewController: *** don't update sliding image ***
,08-05 14:15:02.986  4411  8575 I MS_RegisterService: RegisterService intent:Intent { act=com.google.android.gms.matchstick.register_intent_action (has extras) } isPeriodic:false
,08-05 14:15:02.996   765  1647 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-05 14:15:03.006  4411  8575 I MS_RegisterService: Phone type: 1
,08-05 14:15:03.006   765  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:15:03.016  4411  8575 I MS_RegisterService: Doing full registration.
,08-05 14:15:03.016   765  1526 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-05 14:15:03.026   765  1437 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-05 14:15:03.026  1196  1196 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-05 14:15:03.036   765  3410 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
08-05 14:15:03.036  1196  1196 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-05 14:15:03.046   765  1677 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-05 14:15:03.056   765  1647 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-05 14:15:03.066   765  1526 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-05 14:15:03.066   765  1467 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-05 14:15:03.076   765  1526 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-05 14:15:03.076   765  1647 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-05 14:15:03.086   765   784 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-05 14:15:03.086   765  1452 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-05 14:15:03.086   765  1467 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-05 14:15:03.096   765  1677 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-05 14:15:03.106   765  1706 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-05 14:15:03.116   765  3349 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-05 14:15:03.116  4411  8575 I MS_RegisterService: Throttling registration.
,08-05 14:15:03.116  4411  8575 W MS_WakeLockHelper: Call to release wakelock: register_service_start_wakelock, but not held.
,08-05 14:15:03.116   765  1467 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-05 14:15:03.116   765  1467 D ActivityManager: caller:android.app.ApplicationThreadProxy@18a3adb8, r.packageName :com.google.android.gms
,08-05 14:15:05.176   305   305 E SMD     : DCD ON
,08-05 14:15:07.886  7501  7570 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-05 14:15:07.886  7501  7570 I jxcore-log: 
,08-05 14:15:08.166  8591  8591 D AndroidRuntime: 
08-05 14:15:08.166  8591  8591 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-05 14:15:08.166  8591  8591 D AndroidRuntime: CheckJNI is OFF
,08-05 14:15:08.166  8591  8591 D AndroidRuntime: readGMSProperty: start
08-05 14:15:08.166  8591  8591 D AndroidRuntime: readGMSProperty: already setted!!
,08-05 14:15:08.166  8591  8591 D AndroidRuntime: readGMSProperty: end
08-05 14:15:08.166  8591  8591 D AndroidRuntime: addProductProperty: start
,08-05 14:15:08.176   305   305 E SMD     : DCD ON
,08-05 14:15:08.296  8591  8591 E AffinityControl: AffinityControl: registerfunction enter
,08-05 14:15:08.316  8591  8591 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-05 14:15:08.326   765  1452 D PackageManager: START PACKAGE DELETE: observer{820983697}
08-05 14:15:08.326   765  1452 D PackageManager: pkg{<packageName>}
08-05 14:15:08.326   765  1452 D PackageManager: user{0}
08-05 14:15:08.326   765  1452 D PackageManager: caller{2000}
08-05 14:15:08.326   765  1452 D PackageManager: flags{2}
08-05 14:15:08.326   765  1452 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-05 14:15:08.326   765  1452 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-05 14:15:08.326   765  1452 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-05 14:15:08.326   765  1452 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-05 14:15:08.326   765  1452 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-05 14:15:08.326   765  1065 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-05 14:15:08.326   765  1065 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-05 14:15:08.326   765  1065 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-05 14:15:08.326   765  1065 D ApplicationPolicy: getApplicationUninstallationEnabled
08-05 14:15:08.326   765  1065 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-05 14:15:08.326   765  1065 D PackageManager: !@killApplicatoin: 10079, uninstall pkg
,08-05 14:15:08.336   765  1001 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
,08-05 14:15:08.336   765  1001 I ActivityManager: Killing 7501:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-05 14:15:08.336   765  1001 I ActivityManager:   Force finishing activity ActivityRecord{16c5f769 u0 com.test.thalitest/.MainActivity t99}
,08-05 14:15:08.336   765  1001 D FocusedStackFrame: Set to : 0
,08-05 14:15:08.346   765  1059 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-05 14:15:08.346   765  1059 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 14:15:08.346   765  1059 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-05 14:15:08.346   765  1059 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-05 14:15:08.346   266   922 I SurfaceFlinger: id=12 Removed NainActivit (6/8)
,08-05 14:15:08.346   266   402 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,08-05 14:15:08.406   765  1065 W PackageSettings: Skipping PackageSetting{3a8575f5 com.example.hello/10078} due to missing metadata
,08-05 14:15:08.426   765  3081 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:15:08.436   765  3081 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 14:15:08.436   765  1065 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=0: pkg removed
,08-05 14:15:08.486  1480  1480 I art     : Explicit concurrent mark sweep GC freed 1396(66KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 19MB/33MB, paused 13.112ms total 43.393ms
,08-05 14:15:08.486  3651  3651 I art     : Explicit concurrent mark sweep GC freed 6029(365KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 15MB/26MB, paused 385us total 18.867ms
,08-05 14:15:08.506  4411  4411 I art     : Explicit concurrent mark sweep GC freed 9085(488KB) AllocSpace objects, 5(80KB) LOS objects, 39% free, 24MB/40MB, paused 935us total 43.121ms
,08-05 14:15:08.536  5434  5434 I art     : Explicit concurrent mark sweep GC freed 638(36KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 296us total 21.960ms
,08-05 14:15:08.546   765  1059 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,08-05 14:15:08.556  1440  1440 D ResourcesManager: creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
08-05 14:15:08.556  1739  1739 E SamsungIME: mOCRHelper is null
,08-05 14:15:08.556  1440  1440 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-05 14:15:08.556  1440  1440 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-05 14:15:08.556  1440  1440 D ResourcesManager: creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
08-05 14:15:08.556  1903  2369 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-05 14:15:08.556   765   988 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,08-05 14:15:08.556  7037  7037 I art     : Explicit concurrent mark sweep GC freed 12627(693KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 16MB/21MB, paused 320us total 59.093ms
,08-05 14:15:08.556  1440  1440 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 14:15:08.556  1440  1440 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-05 14:15:08.556  1440  1440 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-05 14:15:08.566  1440  1440 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
08-05 14:15:08.566  1416  1416 D RegisteredServicesCache: empty dynamic service
,08-05 14:15:08.566  4023  4023 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-05 14:15:08.566  1440  1440 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-05 14:15:08.566  1440  1440 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
08-05 14:15:08.566   765  1122 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-05 14:15:08.566  4023  4023 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1470399308580
,08-05 14:15:08.566  4023  4023 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
,08-05 14:15:08.566  4023  4023 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,08-05 14:15:08.586   765  1146 V NetworkStats: removeUidsLocked() for UIDs [10079]
08-05 14:15:08.586   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 14:15:08.586   765  1146 V NetworkStats: performPollLocked(flags=0x3)
,08-05 14:15:08.586   765  1146 D NetworkStatsFactory: UpdateStatsForKnox
,08-05 14:15:08.586   765  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 14:15:08.586   765  3003 E libprocessgroup: failed to kill 1 processes for processgroup 7501
,08-05 14:15:08.596   765  1146 V NetworkStats: performPollLocked() took 11ms
,08-05 14:15:08.596   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 14:15:08.596   765   988 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,08-05 14:15:08.676   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 14:15:08.676   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 14:15:08.676   765   765 I art     : Explicit concurrent mark sweep GC freed 89039(6MB) AllocSpace objects, 21(336KB) LOS objects, 29% free, 37MB/53MB, paused 2.667ms total 141.724ms
,08-05 14:15:08.686   765  1065 I art     : WaitForGcToComplete blocked for 99.254ms for cause Explicit
08-05 14:15:08.686   765   765 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,08-05 14:15:08.716   765   765 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,08-05 14:15:08.716   765   765 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,08-05 14:15:08.726   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,08-05 14:15:08.726   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,08-05 14:15:08.736   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,08-05 14:15:08.756   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,08-05 14:15:08.756  4023  4023 I KLMS-2.4.511: : MainReciver(): Notification App List is Null. Remove Notification.
,08-05 14:15:08.756   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,08-05 14:15:08.756   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,08-05 14:15:08.756  4023  4023 I KLMS-2.4.511: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-05 14:15:08.766   765   765 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,08-05 14:15:08.766   765   765 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,08-05 14:15:08.766   765   765 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,08-05 14:15:08.776   765   765 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,08-05 14:15:08.786   765   765 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,08-05 14:15:08.786   765   765 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,08-05 14:15:08.786   765   765 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,08-05 14:15:08.786   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
,08-05 14:15:08.796   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,08-05 14:15:08.796   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,08-05 14:15:08.806   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,08-05 14:15:08.806   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,08-05 14:15:08.816   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,08-05 14:15:08.816   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,08-05 14:15:08.826   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,08-05 14:15:08.826   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,08-05 14:15:08.826   765   988 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,08-05 14:15:08.836   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,08-05 14:15:08.836   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
,08-05 14:15:08.856   765   765 D RCPManagerService: PackageReceiver onReceive()
08-05 14:15:08.856   765   765 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-05 14:15:08.856   765   765 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,08-05 14:15:08.856   765   988 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
,08-05 14:15:08.856   765   765 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-05 14:15:08.856   765   765 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-05 14:15:08.856   765   765 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-05 14:15:08.856   765   765 V EnterpriseBillingPolicy: uID is 10079
08-05 14:15:08.856   765   765 V EnterpriseBillingPolicy: Removed Packageuid is0
08-05 14:15:08.856   765   765 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-05 14:15:08.856   765   765 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
08-05 14:15:08.856   765   765 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-05 14:15:08.856   765   765 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-05 14:15:08.856   765   765 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-05 14:15:08.866   765   765 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-05 14:15:08.866   765  1179 D TaskPersister: removeObsoleteFile: deleting file=99_task.xml
,08-05 14:15:08.866   765   765 V AlarmManagerEXT: com.test.thalitest(10079) is removed.
,08-05 14:15:08.866   765  1065 I art     : Explicit concurrent mark sweep GC freed 12747(651KB) AllocSpace objects, 1(16KB) LOS objects, 29% free, 37MB/53MB, paused 2.204ms total 183.263ms
,08-05 14:15:08.866   765  3410 I art     : WaitForGcToComplete blocked for 203.599ms for cause Explicit
,08-05 14:15:08.936   765  3081 I SQLiteConnectionPool: exportDB...
,08-05 14:15:08.946   765  1065 D PackageManager: delete codoeFile: 
,08-05 14:15:08.956   765  1065 D AASAuninstall: userId = 0, info.removedAppID = 10079, info.uid = 10079, packageName = com.test.thalitest
,08-05 14:15:08.956   765  1065 I AASA_removePackage: UID=10079 Target=com.test.thalitest
08-05 14:15:08.956   765  1065 D PackageManager: result of delete: 1{820983697}
,08-05 14:15:08.966  8591  8591 D AndroidRuntime: Shutting down VM
,08-05 14:15:08.966   765  3410 I art     : Explicit concurrent mark sweep GC freed 8290(458KB) AllocSpace objects, 4(64KB) LOS objects, 29% free, 37MB/53MB, paused 2.487ms total 98.222ms
,08-05 14:15:08.966   765  1647 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
08-05 14:15:08.966   765  1647 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:15:08.966   765  1647 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:15:08.966   765  1647 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:15:08.966   765  1647 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:15:08.966   765  3410 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-05 14:15:08.966   765  3410 D SecContentProvider2: mCursor = null
08-05 14:15:08.966   765   988 D EnterpriseDeviceManagerService: Package has changed for user 0
08-05 14:15:08.966   765   988 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-05 14:15:08.976   765   988 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,08-05 14:15:08.986   765   988 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,08-05 14:15:08.986   765   988 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 14:15:08.986   765   988 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
,08-05 14:15:08.986   765   988 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,08-05 14:15:08.996   765   988 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,08-05 14:15:08.996   765   988 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 14:15:08.996   765   988 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,08-05 14:15:08.996   765   988 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,08-05 14:15:09.006   765   988 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 14:15:09.006   765   988 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,08-05 14:15:09.006   765   988 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-05 14:15:09.006   765   988 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,08-05 14:15:09.006   765   988 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 14:15:09.006   765   988 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 14:15:09.006  8618  8618 E Zygote  : MountEmulatedStorage()
08-05 14:15:09.006   765   988 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
08-05 14:15:09.006  8618  8618 E Zygote  : v2
08-05 14:15:09.006  8618  8618 I libpersona: KNOX_SDCARD checking this for 10116
08-05 14:15:09.006  8618  8618 I libpersona: KNOX_SDCARD not a persona
,08-05 14:15:09.016   765   988 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 14:15:09.016   765   988 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,08-05 14:15:09.016   765   988 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,08-05 14:15:09.016   765  1647 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8618 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,08-05 14:15:09.016   765   988 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,08-05 14:15:09.026   765   988 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,08-05 14:15:09.026   765   988 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 14:15:09.026   765   988 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,08-05 14:15:09.026   765   988 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,08-05 14:15:09.036  8618  8618 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 14:15:09.036  8618  8618 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-05 14:15:09.036  8618  8618 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-05 14:15:09.036   765   988 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,08-05 14:15:09.046   765   988 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 14:15:09.046   765   988 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 14:15:09.046   765   988 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,08-05 14:15:09.046   765   988 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-05 14:15:09.046   765   988 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 14:15:09.046   765   988 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-05 14:15:09.046   765   988 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 14:15:09.046   765   988 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,08-05 14:15:09.056   765   988 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,08-05 14:15:09.056  8618  8618 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:15:09.056  8618  8618 D ActivityThread: Added TimaKeyStore provider
,08-05 14:15:09.066   765   988 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,08-05 14:15:09.066   765  3081 I SQLiteConnectionPool: ...exportDB
,08-05 14:15:09.076   765  3081 D SSRM:aY : MSG_TYPE_APP_REMOVED::
,08-05 14:15:09.076   765   988 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,08-05 14:15:09.076  8618  8618 D ResourcesManager: creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,08-05 14:15:09.076   765   988 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 14:15:09.076   765   988 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,08-05 14:15:09.076   765   988 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 14:15:09.076   765   988 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,08-05 14:15:09.086  1440  1440 D SurfaceWidgetView: destroyHardwareResources():977897910
,08-05 14:15:09.086   765   988 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-05 14:15:09.086   765   988 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-05 14:15:09.086   765  1144 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-05 14:15:09.086   765  1144 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
08-05 14:15:09.086   765  1144 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-05 14:15:09.086   765  1144 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-05 14:15:09.086   765  1144 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,08-05 14:15:09.086   765   988 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,08-05 14:15:09.086  1440  1440 D Launcher: onRestart, Launcher: 237909644
,08-05 14:15:09.086  1440  1440 D Launcher: onStart, Launcher: 237909644
08-05 14:15:09.086  1440  1440 D Launcher.HomeView: onStart
,08-05 14:15:09.086  1440  1440 V ActivityThread: updateVisibility : ActivityRecord{30965ee3 token=android.os.BinderProxy@2c144af7 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-05 14:15:09.086  1767  1777 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
08-05 14:15:09.086  1767  2170 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
,08-05 14:15:09.086   765   988 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-05 14:15:09.086  1767  2170 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,08-05 14:15:09.086   765   988 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,08-05 14:15:09.086  8618  8618 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-05 14:15:09.086   765   988 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 14:15:09.096   765   988 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-05 14:15:09.096  8618  8618 D elm:14491: ELMEngine.ELMEngine( context ).
08-05 14:15:09.096   765   988 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,08-05 14:15:09.096  8618  8618 D elm:14491: MDMBridge.setEnterpriseBridge()
,08-05 14:15:09.096   765   783 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-05 14:15:09.096   765   783 D ActivityManager: caller:android.app.ApplicationThreadProxy@652579b, r.packageName :com.sec.esdk.elm
,08-05 14:15:09.096   765   988 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-05 14:15:09.096   765   988 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-05 14:15:09.096   765   988 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,08-05 14:15:09.096  8618  8618 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-05 14:15:09.096   765   988 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 14:15:09.106  3708  3708 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,08-05 14:15:09.106  3708  3708 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-05 14:15:09.106  3708  3708 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
08-05 14:15:09.106  3708  3708 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
08-05 14:15:09.106  3708  3708 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
08-05 14:15:09.106  3708  3708 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
08-05 14:15:09.106  3708  3708 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
08-05 14:15:09.106  3708  3708 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 14:15:09.106  3708  3708 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-05 14:15:09.106   266   266 I SurfaceFlinger: id=14 createSurf (1080x1920),1 flag=4, Mauncher
08-05 14:15:09.106  3708  3708 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-05 14:15:09.106  3708  3708 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 14:15:09.106  3708  3708 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 14:15:09.106  3708  3708 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-05 14:15:09.106  3708  3708 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,08-05 14:15:09.106   765   988 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-05 14:15:09.106   765  1057 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-05 14:15:09.106   765   988 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-05 14:15:09.106   765  1289 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.service.health, hostingType: broadcast
,08-05 14:15:09.106  8618  8618 D elm:14491: ElmAgentService : onCreate()
08-05 14:15:09.106   765  1057 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-05 14:15:09.106   765  1289 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:15:09.106   765  1289 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:15:09.106   765  1289 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:15:09.106   765  1289 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:15:09.106  8618  8635 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-05 14:15:09.106  8618  8635 D elm:14491: MainReceiver.listeningToPackageRemoved()
,08-05 14:15:09.106  8618  8635 D elm:14491: MDMBridge.getInstance()
08-05 14:15:09.106  8618  8635 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,08-05 14:15:09.106   765  1059 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-05 14:15:09.116   765  1059 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 14:15:09.116   765  1059 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
,08-05 14:15:09.116   765  1059 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-05 14:15:09.116  8618  8635 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,08-05 14:15:09.116   765  1677 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-05 14:15:09.116   765  1677 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 7501 uid 10079
,08-05 14:15:09.126   765  8639 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-05 14:15:09.146  8641  8641 E Zygote  : MountEmulatedStorage()
,08-05 14:15:09.146  8641  8641 E Zygote  : v2
08-05 14:15:09.146  8641  8641 I libpersona: KNOX_SDCARD checking this for 10021
08-05 14:15:09.146  8641  8641 I libpersona: KNOX_SDCARD not a persona
,08-05 14:15:09.156   765  1289 I ActivityManager: Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8641 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,08-05 14:15:09.166  8618  8618 D elm:14491: ElmAgentService : onDestroy().
08-05 14:15:09.166  8641  8641 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,08-05 14:15:09.166  8641  8641 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-05 14:15:09.166  8641  8641 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-05 14:15:09.186   765  1059 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{36e9d0fb u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t97} time:428375
,08-05 14:15:09.186  8641  8641 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:15:09.186  8641  8641 D ActivityThread: Added TimaKeyStore provider
,08-05 14:15:09.196   765  1065 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-05 14:15:09.196   765  1065 D PackageManager: userId{-1}
08-05 14:15:09.196   765  1065 D PackageManager: andCode{true}
,08-05 14:15:09.196   765  1065 D ActivityManager: caller:null, r.packageName :com.android.defcontainer
,08-05 14:15:09.196   765  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:15:09.196   765  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:15:09.196   765  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:15:09.196   765  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:15:09.206  8641  8641 D ResourcesManager: creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,08-05 14:15:09.236  8657  8657 E Zygote  : MountEmulatedStorage()
08-05 14:15:09.236  8657  8657 E Zygote  : v2
08-05 14:15:09.236  8657  8657 I libpersona: KNOX_SDCARD checking this for 10007
08-05 14:15:09.236  8657  8657 I libpersona: KNOX_SDCARD not a persona
,08-05 14:15:09.246   765  1065 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8657 uid=10007 gids={50007, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-05 14:15:09.246  8641  8641 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
08-05 14:15:09.246  8641  8641 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
08-05 14:15:09.246  8641  8641 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
,08-05 14:15:09.256  8657  8657 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 14:15:09.256  8657  8657 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-05 14:15:09.256  8657  8657 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-05 14:15:09.256  6803  6803 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-05 14:15:09.256  6803  6803 I PCWCLIENTTRACE_PushUtil: sales region : global
08-05 14:15:09.256  6803  6803 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-05 14:15:09.256  6803  6803 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-05 14:15:09.276   765   783 D ActivityManager: startService callerProcessName:com.sec.android.app.shealth, calleePkgName: com.sec.android.app.shealth
,08-05 14:15:09.276   765   783 D ActivityManager: caller:android.app.ApplicationThreadProxy@1e40ec76, r.packageName :com.sec.android.app.shealth
,08-05 14:15:09.276  8657  8657 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:15:09.276  8657  8657 D ActivityThread: Added TimaKeyStore provider
,08-05 14:15:09.286  7908  7908 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/registration_db" with flag (131138) and mode_t (0) due to error (30)
,08-05 14:15:09.286  7908  7908 E SQLiteDatabase: Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at com.sec.spp.push.h.a.a(Unknown Source)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at com.sec.spp.push.h.c.d(Unknown Source)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.onReceive(Unknown Source)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-05 14:15:09.286  7908  7908 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-05 14:15:09.286  7908  7908 E SPPClientService: [c] [getAppId()] SQLiteException with message =not an error (code 0): Could not open the database in read/write mode.
,08-05 14:15:09.286   765  1467 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-05 14:15:09.286   765  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:15:09.286   765  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:15:09.286   765  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:15:09.286   765  1467 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:15:09.296  8657  8657 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DefaultContainerService/DefaultContainerService.apk
,08-05 14:15:09.296  4465  8670 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,08-05 14:15:09.296  4465  8670 E SQLiteLog: (3850) statement aborts at 19: [delete  from app_registry where package_name= "com.test.thalitest" AND plugin_id= "1"] disk I/O error
,08-05 14:15:09.296  4465  8670 E SQLiteQuery: exception: disk I/O error (code 3850); query: delete  from app_registry where package_name= "com.test.thalitest" AND plugin_id= "1"
,08-05 14:15:09.306  4465  8670 E AndroidRuntime: FATAL EXCEPTION: IntentService[HandleAppDataService]
08-05 14:15:09.306  4465  8670 E AndroidRuntime: Process: com.sec.android.app.shealth, PID: 4465
08-05 14:15:09.306  4465  8670 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 14:15:09.306  4465  8670 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForCursorWindow(Native Method)
08-05 14:15:09.306  4465  8670 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForCursorWindow(SQLiteConnection.java:1015)
08-05 14:15:09.306  4465  8670 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForCursorWindow(SQLiteSession.java:836)
08-05 14:15:09.306  4465  8670 E AndroidRuntime: 	at android.database.sqlite.SQLiteQuery.fillWindow(SQLiteQuery.java:62)
08-05 14:15:09.306  4465  8670 E AndroidRuntime: 	at android.database.sqlite.SQLiteCursor.fillWindow(SQLiteCursor.java:147)
08-05 14:15:09.306  4465  8670 E AndroidRuntime: 	at android.database.sqlite.SQLiteCursor.getCount(SQLiteCursor.java:136)
08-05 14:15:09.306  4465  8670 E AndroidRuntime: 	at android.content.ContentResolver.query(ContentResolver.java:503)
08-05 14:15:09.306  4465  8670 E AndroidRuntime: 	at android.content.ContentResolver.query(ContentResolver.java:428)
08-05 14:15:09.306  4465  8670 E AndroidRuntime: 	at com.sec.android.app.shealth.framework.ui.data.AppRegistryDbManagerWithProvider.deleteAppRegistryData(Unknown Source)
08-05 14:15:09.306  4465  8670 E AndroidRuntime: 	at com.sec.android.app.shealth.service.HandleAppDataService.onHandleIntent(HandleAppDataService.java:66)
08-05 14:15:09.306  4465  8670 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-05 14:15:09.306  4465  8670 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 14:15:09.306  4465  8670 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-05 14:15:09.306  4465  8670 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-05 14:15:09.336  8676  8676 E Zygote  : MountEmulatedStorage()
08-05 14:15:09.336  8676  8676 E Zygote  : v2
08-05 14:15:09.336  8676  8676 I libpersona: KNOX_SDCARD checking this for 10043
08-05 14:15:09.336  8676  8676 I libpersona: KNOX_SDCARD not a persona
,08-05 14:15:09.336   765  1467 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8676 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-05 14:15:09.346   765  1237 D ActivityManager: bindService callerProcessName:com.sec.android.app.shealth, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,08-05 14:15:09.346   765  1706 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.shealth
,08-05 14:15:09.346  4465  8670 I Process : Sending signal. PID: 4465 SIG: 9
,08-05 14:15:09.356   765  8682 E DropBoxManagerService: Can't write: system_app_crash
08-05 14:15:09.356   765  8682 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop206.tmp: open failed: EROFS (Read-only file system)
08-05 14:15:09.356   765  8682 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-05 14:15:09.356   765  8682 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 14:15:09.356   765  8682 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 14:15:09.356   765  8682 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 14:15:09.356   765  8682 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-05 14:15:09.356   765  8682 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
08-05 14:15:09.356   765  8682 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 14:15:09.356   765  8682 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 14:15:09.356   765  8682 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 14:15:09.356   765  8682 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-05 14:15:09.356   765  8682 E DropBoxManagerService: 	... 5 more
,08-05 14:15:09.356   337   337 I art     : Explicit concurrent mark sweep GC freed 8732(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 320us total 13.361ms
,08-05 14:15:09.366   263   263 E lowmemorykiller: Error writing /proc/4465/oom_score_adj; errno=22
,08-05 14:15:09.366  8676  8676 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,08-05 14:15:09.366  8676  8676 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-05 14:15:09.366  8676  8676 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-05 14:15:09.366   337   337 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 407us total 11.198ms
,08-05 14:15:09.376   765  1122 I EventHub: Removing device '/dev/input/event6' due to inotify event
,08-05 14:15:09.376   337   337 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 277us total 10.357ms
,08-05 14:15:09.396  8676  8676 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:15:09.396  8676  8676 D ActivityThread: Added TimaKeyStore provider
,08-05 14:15:09.406  8676  8676 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,08-05 14:15:09.416   765  1122 I EventHub: Removing device '/dev/input/event7' due to inotify event
,08-05 14:15:09.416  8676  8676 W ContextImpl: Unable to create files subdir /data/data/com.sec.spp.push/cache
,08-05 14:15:09.416  8676  8676 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,08-05 14:15:09.426   765  1452 I ActivityManager: Process com.sec.android.app.shealth (pid 4465)(adj 5) has died(358,1501)
,08-05 14:15:09.426   765  1452 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/.service.HandleAppDataService in 1000ms
,08-05 14:15:09.426  5999  5999 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/pref_package.xml
,08-05 14:15:09.426   765  3349 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
08-05 14:15:09.426   765  3349 D ActivityManager: caller:android.app.ApplicationThreadProxy@dda1f13, r.packageName :com.samsung.android.app.galaxyfinder
,08-05 14:15:09.456  8676  8676 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-05 14:15:09.456   765  1122 I EventHub: Removing device '/dev/input/event8' due to inotify event
08-05 14:15:09.456  8676  8676 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-05 14:15:09.456  8676  8676 W ContextImpl: Unable to create files subdir /data/data/com.sec.spp.push/files
,08-05 14:15:09.456  8676  8676 D SPPClientService: PushLog.txt file is not deleted.
08-05 14:15:09.456  8676  8676 W ContextImpl: Unable to create files subdir /data/data/com.sec.spp.push/files
08-05 14:15:09.456  8676  8676 D SPPClientService: PushLog.txt file is not deleted.
08-05 14:15:09.456  8676  8676 D SPPClientService: ============PushLog. stop!
,08-05 14:15:09.466  8676  8676 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131138) and mode_t (0) due to error (30)
,08-05 14:15:09.466  8676  8676 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131072) and mode_t (0) due to error (2)
08-05 14:15:09.466  8676  8676 E SQLiteLog: (14) cannot open file at line 32509 of [b3bb660af9]
08-05 14:15:09.466  8676  8676 E SQLiteLog: (14) os_unix.c:32509: (2) open(/data/data/com.sec.spp.push/databases/push_noti_db) - 
,08-05 14:15:09.466  8676  8676 E SQLiteDatabase: Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.a.b.<init>(Unknown Source)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.a.b.a(Unknown Source)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.l.b(Unknown Source)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.l.a(Unknown Source)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.onReceive(Unknown Source)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-05 14:15:09.466  8676  8676 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,08-05 14:15:09.466  8676  8676 E LNoti   : [b] open fail. SQLException occured
,08-05 14:15:09.466   765  1578 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,08-05 14:15:09.466   765  1578 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:15:09.466   765  1578 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:15:09.466   765  1578 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:15:09.466   765  1578 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:15:09.506   765  1122 I EventHub: Removing device '/dev/input/event9' due to inotify event
,08-05 14:15:09.546   765  1122 I EventHub: Removing device '/dev/input/event10' due to inotify event
,08-05 14:15:09.546  8695  8695 E Zygote  : MountEmulatedStorage()
08-05 14:15:09.546  8695  8695 E Zygote  : v2
08-05 14:15:09.546  8695  8695 I libpersona: KNOX_SDCARD checking this for 10048
08-05 14:15:09.546  8695  8695 I libpersona: KNOX_SDCARD not a persona
,08-05 14:15:09.546   765  1578 I ActivityManager: Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8695 uid=10048 gids={50048, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,08-05 14:15:09.556   765  1578 I ActivityManager: Killing 5555:com.sec.android.gallery3d/u0a53 (adj 15): emptyCount ##41
,08-05 14:15:09.616   765  1122 I EventHub: Removing device '/dev/input/event11' due to inotify event
08-05 14:15:09.616  8695  8695 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,08-05 14:15:09.616  8695  8695 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-05 14:15:09.616  8695  8695 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-05 14:15:09.636  8695  8695 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:15:09.636  8695  8695 D ActivityThread: Added TimaKeyStore provider
,08-05 14:15:09.646  8695  8695 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLinkPlatform/SamsungLinkPlatform.apk
,08-05 14:15:09.646  8695  8695 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-05 14:15:09.656  8695  8695 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-05 14:15:09.656  8695  8695 W ContextImpl: Unable to create files subdir /data/data/com.samsung.android.sdk.samsunglink/cache
08-05 14:15:09.656  8695  8695 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,08-05 14:15:09.676   765  1122 I EventHub: Removing device '/dev/input/event12' due to inotify event
,08-05 14:15:09.726   765  1122 I EventHub: Removing device '/dev/input/event13' due to inotify event
,08-05 14:15:09.746  8695  8695 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db" with flag (131138) and mode_t (0) due to error (2)
08-05 14:15:09.746  8695  8695 E SQLiteLog: (28) failed to open "/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db" with flag (131072) and mode_t (0) due to error (2)
08-05 14:15:09.746  8695  8695 E SQLiteLog: (14) cannot open file at line 32509 of [b3bb660af9]
08-05 14:15:09.746  8695  8695 E SQLiteLog: (14) os_unix.c:32509: (2) open(/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db) - 
,08-05 14:15:09.746  8695  8695 E SQLiteDatabase: Failed to open database '/data/data/com.samsung.android.sdk.samsunglink/databases/asp.db'.
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:465)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1716)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1685)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5555)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5150)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5090)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-05 14:15:09.746  8695  8695 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-05 14:15:09.746  8695  8695 D AndroidRuntime: Shutting down VM
,08-05 14:15:09.746  8695  8695 E AndroidRuntime: FATAL EXCEPTION: main
08-05 14:15:09.746  8695  8695 E AndroidRuntime: Process: com.samsung.android.sdk.samsunglink, PID: 8695
08-05 14:15:09.746  8695  8695 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.mfluent.asp.datamodel.ASPMediaStoreProvider: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5558)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5150)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5090)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at com.mfluent.asp.datamodel.ASPMediaStoreProvider.onCreate(SourceFile:465)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1716)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1685)
08-05 14:15:09.,746  8695  8695 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5555)
08-05 14:15:09.746  8695  8695 E AndroidRuntime: 	... 11 more
08-05 14:15:09.746   765  1289 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sdk.samsunglink
,08-05 14:15:09.746   765  8711 E DropBoxManagerService: Can't write: system_app_crash
08-05 14:15:09.746   765  8711 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop207.tmp: open failed: EROFS (Read-only file system)
08-05 14:15:09.746   765  8711 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-05 14:15:09.746   765  8711 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 14:15:09.746   765  8711 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 14:15:09.746   765  8711 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 14:15:09.746   765  8711 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-05 14:15:09.746   765  8711 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
08-05 14:15:09.746   765  8711 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 14:15:09.746   765  8711 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 14:15:09.746   765  8711 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 14:15:09.746   765  8711 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-05 14:15:09.746   765  8711 E DropBoxManagerService: 	... 5 more
,08-05 14:15:09.746  7924  7924 I SA      : [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
08-05 14:15:09.746  7924  7924 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10079 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
08-05 14:15:09.746  8695  8695 I Process : Sending signal. PID: 8695 SIG: 9
,08-05 14:15:09.746   765   783 I ActivityManager: Killing 6080:com.sec.android.app.controlpanel/u0a134 (adj 15): emptyCount ##41
,08-05 14:15:09.776   765  1122 I EventHub: Removing device '/dev/input/event14' due to inotify event
,08-05 14:15:09.776   765  1677 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
,08-05 14:15:09.776   765  1677 D ActivityManager: caller:android.app.ApplicationThreadProxy@d55144e, r.packageName :com.android.providers.contacts
,08-05 14:15:09.776   765  1526 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.gallery3d, hostingType: broadcast
,08-05 14:15:09.776   765  1526 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:15:09.776   765  1526 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:15:09.776   765  1526 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 14:15:09.776   765  1526 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 14:15:09.816  8713  8713 E Zygote  : MountEmulatedStorage()
08-05 14:15:09.816  8713  8713 E Zygote  : v2
08-05 14:15:09.816  8713  8713 I libpersona: KNOX_SDCARD checking this for 10053
08-05 14:15:09.816  8713  8713 I libpersona: KNOX_SDCARD not a persona
,08-05 14:15:09.826   765  1526 I ActivityManager: Start proc com.sec.android.gallery3d for broadcast com.sec.android.gallery3d/.app.PackagesMonitor: pid=8713 uid=10053 gids={50053, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-05 14:15:09.826   263   263 E lowmemorykiller: Error writing /proc/8695/oom_score_adj; errno=22
,08-05 14:15:09.836   765  3349 I ActivityManager: Process com.samsung.android.sdk.samsunglink (pid 8695)(adj 11) has died(365,1501)
,08-05 14:15:09.856  8713  8713 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 14:15:09.856  8713  8713 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-05 14:15:09.856  8713  8713 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-05 14:15:09.876  8713  8713 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 14:15:09.886  8713  8713 D ActivityThread: Added TimaKeyStore provider
,08-05 14:15:09.896  8713  8713 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,08-05 14:15:09.896  8713  8713 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-05 14:15:09.896  8713  8713 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 14:15:09.896  8713  8713 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-05 14:15:09.896  8713  8713 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-05 14:15:09.896  8713  8713 W ResourcesManager: Asset path '/system/framework/svi.jar' does not exist or contains no resources.
,08-05 14:15:09.896  8713  8713 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-05 14:15:09.896  8713  8713 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-05 14:15:09.896  8713  8713 W ContextImpl: Unable to create files subdir /data/data/com.sec.android.gallery3d/cache
,08-05 14:15:09.896  8713  8713 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,08-05 14:15:09.976  8713  8713 E SQLiteLog: (28) failed to open "/data/data/com.sec.android.gallery3d/databases/picasa.db" with flag (131138) and mode_t (0) due to error (30)
,08-05 14:15:09.976  8713  8713 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0xa0ab6c89 in tid 8713 (droid.gallery3d)
,08-05 14:15:09.996   266   522 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
