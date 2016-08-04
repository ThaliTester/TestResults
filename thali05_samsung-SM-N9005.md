#### Test 797510150d7f48d_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
08-04 11:57:25.696   303   303 E SMD     : DCD ON
,08-04 11:57:26.005  7220  7220 D AndroidRuntime: 
08-04 11:57:26.005  7220  7220 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-04 11:57:26.005  7220  7220 D AndroidRuntime: CheckJNI is OFF
08-04 11:57:26.005  7220  7220 D AndroidRuntime: readGMSProperty: start
08-04 11:57:26.005  7220  7220 D AndroidRuntime: readGMSProperty: already setted!!
08-04 11:57:26.005  7220  7220 D AndroidRuntime: readGMSProperty: end
08-04 11:57:26.005  7220  7220 D AndroidRuntime: addProductProperty: start
08-04 11:57:26.175  7220  7220 E AffinityControl: AffinityControl: registerfunction enter
08-04 11:57:26.195  7220  7220 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-04 11:57:26.205   765  1238 E PersonaManagerService: inState():  stateMachine is null !!
08-04 11:57:26.205   765  1238 I PersonaManagerService: PersonaId don't exist
08-04 11:57:26.205   765  1238 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-04 11:57:26.205   765  1238 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-04 11:57:26.205   765  1238 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-04 11:57:26.205   765  1238 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
08-04 11:57:26.215   765  1238 W ActivityManager: mDVFSHelper.acquire()
08-04 11:57:26.215   765  1238 D FocusedStackFrame: Set to : 0
08-04 11:57:26.215   765  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:26.215   765  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:26.215   765  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:26.215   765  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:26.275   765  1238 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7235 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-04 11:57:26.285   765  1060 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-04 11:57:26.285   765  1060 D PointerIcon: setMouseCustomIcon IconType is same.101
08-04 11:57:26.285   765  1060 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-04 11:57:26.285   765  1060 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-04 11:57:26.285  7235  7235 E Zygote  : MountEmulatedStorage()
08-04 11:57:26.285  7235  7235 E Zygote  : v2
08-04 11:57:26.285  7235  7235 I libpersona: KNOX_SDCARD checking this for 10079
08-04 11:57:26.285  7235  7235 I libpersona: KNOX_SDCARD not a persona
08-04 11:57:26.285  7220  7220 D AndroidRuntime: Shutting down VM
08-04 11:57:26.305   344   344 I art     : Explicit concurrent mark sweep GC freed 8776(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 953us total 32.281ms
08-04 11:57:26.305  7235  7235 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:26.305  7235  7235 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 11:57:26.315  7235  7235 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-04 11:57:26.325   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 270us total 11.770ms
08-04 11:57:26.335   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 273us total 9.381ms
08-04 11:57:26.345  7235  7235 D TimaKeyStoreProvider: TimaSignature is unavailable
08-04 11:57:26.345  7235  7235 D ActivityThread: Added TimaKeyStore provider
08-04 11:57:26.355   765  1263 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-04 11:57:26.355   765  1263 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
08-04 11:57:26.355   765  1263 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-04 11:57:26.355   765  1263 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-04 11:57:26.355   765  1263 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
08-04 11:57:26.375   765  3091 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:26.385  7235  7235 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
08-04 11:57:26.385  1439  1439 D SurfaceWidgetView: destroyHardwareResources():242199373
08-04 11:57:26.395   765  3091 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:26.425   267   382 I SurfaceFlinger: id=8 Removed Mauncher (6/8)
08-04 11:57:26.425   267   374 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
08-04 11:57:26.435  1782  1803 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
08-04 11:57:26.435  1439  1439 V ActivityThread: updateVisibility : ActivityRecord{3da5a5ff token=android.os.BinderProxy@15cbd742 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-04 11:57:26.435  1439  1439 D Launcher: onTrimMemory. Level: 20
08-04 11:57:26.475  7235  7235 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
08-04 11:57:26.475  7235  7235 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
08-04 11:57:26.485  7235  7235 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9125-9128)
08-04 11:57:26.485  7235  7235 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 11:57:26.525  7235  7235 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {25a13b4c}
08-04 11:57:26.525  7235  7235 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 11:57:26.525  7235  7235 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-04 11:57:26.545  7235  7235 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-04 11:57:26.545  7235  7235 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 11:57:26.555  7235  7235 E SysUtils: ApplicationContext is null in ApplicationStatus
08-04 11:57:26.565  7235  7235 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
08-04 11:57:26.565  7235  7235 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
08-04 11:57:26.565  7235  7235 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
08-04 11:57:26.575  7235  7235 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
08-04 11:57:26.575  7235  7235 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
08-04 11:57:26.575  7235  7235 I Adreno-EGL: Build Date: 11/19/14 Wed
08-04 11:57:26.575  7235  7235 I Adreno-EGL: Local Branch: mybranch5813579
08-04 11:57:26.575  7235  7235 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
08-04 11:57:26.575  7235  7235 I Adreno-EGL: Local Patches: NONE
08-04 11:57:26.575  7235  7235 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
08-04 11:57:26.665  7235  7266 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
08-04 11:57:26.695  7235  7235 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 11:57:26.705  7235  7235 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-04 11:57:26.715  7235  7235 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-04 11:57:26.725  7235  7235 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 11:57:26.725  7235  7235 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 11:57:26.765  7235  7235 D Activity: performCreate Call secproduct feature valuefalse
08-04 11:57:26.765  7235  7235 D Activity: performCreate Call debug elastic valuetrue
08-04 11:57:26.775  7235  7279 D OpenGLRenderer: Render dirty regions requested: true
08-04 11:57:26.785   765  1232 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-04 11:57:26.785   765  1232 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-04 11:57:26.785   765  1232 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-04 11:57:26.785   765   765 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-04 11:57:26.785   765   765 D PersonaManagerService: getPersonasForUser(): returning null!
08-04 11:57:26.795   267   267 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
08-04 11:57:26.795   765  1058 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-04 11:57:26.805   765  1058 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-04 11:57:26.815   765  1060 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-04 11:57:26.815   765  1060 D PointerIcon: setMouseCustomIcon IconType is same.101
08-04 11:57:26.815   765  1060 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-04 11:57:26.815   765  1060 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-04 11:57:26.815  7235  7279 I OpenGLRenderer: Initialized EGL, version 1.4
08-04 11:57:26.825  7235  7279 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xb3dd33d0 ,&mEglDisplay = 1 , &mEglConfig = 8 
08-04 11:57:26.825  7235  7279 D OpenGLRenderer: Enabling debug mode 0
08-04 11:57:26.845  7235  7235 V ActivityThread: updateVisibility : ActivityRecord{3115026 token=android.os.BinderProxy@318ca768 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-04 11:57:26.865   765  1232 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-04 11:57:26.865   765  7283 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-04 11:57:26.875  1750  1750 I SamsungIME: getCurrentCandidateView
08-04 11:57:26.875  7235  7235 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-04 11:57:26.885   765  1060 W ActivityManager: mDVFSHelper.release()
08-04 11:57:26.885   765  1060 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{339f74da u0 com.test.thalitest/.MainActivity t99} time:179524
08-04 11:57:26.885  7235  7235 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@318ca768 time:179525
08-04 11:57:26.925  7235  7235 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7235
08-04 11:57:26.925  1750  1750 D SamsungIME: Dismiss ExpandCandiate
08-04 11:57:26.995  7235  7235 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-04 11:57:27.005  1750  1750 I SamsungIME: getDebugLevel  : 0x4f4c
08-04 11:57:27.045  1750  1750 I SamsungIME: getDebugLevel  : 0x4f4c
08-04 11:57:27.055  1750  1750 I SamsungIME: KeybaordView init() : load resources
08-04 11:57:27.085  1750  1750 I SamsungIME: getCurrentKeyboard
08-04 11:57:27.085  1750  1750 I SamsungIME: getTextKeyboard
08-04 11:57:27.095  1750  1750 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
08-04 11:57:27.105  7235  7285 D jxcore_app_log: JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258382720
08-04 11:57:27.115  7235  7285 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-04 11:57:27.115  7235  7285 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-04 11:57:27.115  7235  7285 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-04 11:57:27.115  7235  7285 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-04 11:57:27.115  7235  7285 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-04 11:57:27.115  7235  7285 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22640ed6 added. We now have 1 listener(s)
08-04 11:57:27.125  7235  7285 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:1F:C9:5E
08-04 11:57:27.125  7235  7285 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
08-04 11:57:27.125  7235  7285 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 11:57:27.125  7235  7285 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:57:27.135  7235  7285 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-04 11:57:27.135  7235  7285 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-04 11:57:27.135  7235  7285 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-04 11:57:27.135  7235  7285 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:1F:C9:5E
08-04 11:57:27.135  7235  7285 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-04 11:57:27.135  7235  7285 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-04 11:57:27.135  7235  7285 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-04 11:57:27.135  7235  7285 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-04 11:57:27.135  7235  7285 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-04 11:57:27.135  7235  7285 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-04 11:57:27.135  7235  7285 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-04 11:57:27.135  7235  7285 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-04 11:57:27.135  7235  7285 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-04 11:57:27.135  7235  7285 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-04 11:57:27.135  7235  7285 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3125cd2d added. We now have 1 listener(s)
08-04 11:57:27.135  7235  7285 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:57:27.145  7235  7285 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 11:57:27.145  7235  7285 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-04 11:57:27.145  7235  7285 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-04 11:57:27.145  7235  7285 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-04 11:57:27.145  7235  7285 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-04 11:57:27.145  7235  7285 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:57:27.145  7235  7285 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:1F:C9:5E
08-04 11:57:27.145   765  1352 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:27.155  7235  7285 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-04 11:57:27.155  7235  7285 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:57:27.155  7235  7285 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:27.155  7235  7285 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:27.155  7235  7285 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:57:27.155  7235  7285 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:57:27.155  7235  7285 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:27.155  7235  7285 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:57:27.155  7235  7285 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:57:27.155  7235  7285 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-04 11:57:27.155  7235  7285 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 11:57:27.155   765  1232 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:27.155  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:27.155   765  3205 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:27.155  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:27.155  7235  7285 I io.jxcore.node.LifeCycleMonitor: start: OK
08-04 11:57:27.185  7235  7235 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-04 11:57:27.195   765  3091 D SSRM:n  : SIOP:: AP = 330, PST = 350, CUR = 450
08-04 11:57:27.465  1750  7289 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-04 11:57:27.965  7235  7294 W jxcore-log: Initializing JXcore engine
08-04 11:57:27.965  7235  7294 W jxcore-log: JXcore engine is ready
08-04 11:57:28.025  1848  1848 E auditd  : In denial and Property audit_ondenial is set to 1 
08-04 11:57:28.025  1848  1848 E audit   : type=1400 msg=audit(1470304648.025:203): avc:  denied  { ioctl } for  pid=7294 comm="Thread-1183" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-04 11:57:28.025  1848  1848 E audit   :  SEPF_SM-N9005_5.0-1_0032
08-04 11:57:28.025  1848  1848 E audit   : 
08-04 11:57:28.025   765  1056 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
08-04 11:57:28.025   765  1056 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
08-04 11:57:28.035   765  1015 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
08-04 11:57:28.035   765  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:28.035   765  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:28.035   765  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:28.035   765  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:28.035   765  1056 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
08-04 11:57:28.035  1848  1848 E audit   : type=1300 msg=audit(1470304648.025:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=989008d8 items=0 ppid=344 ppcomm=main pid=7294 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1183" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-04 11:57:28.035  1848  1848 E audit   : type=1320 msg=audit(1470304648.025:203): 
08-04 11:57:28.055  7235  7294 W jxcore-log: Starting JXcore engine
08-04 11:57:28.065   765  1015 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7299 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-04 11:57:28.075  7299  7299 E Zygote  : MountEmulatedStorage()
08-04 11:57:28.075  7299  7299 E Zygote  : v2
08-04 11:57:28.075  7299  7299 I libpersona: KNOX_SDCARD checking this for 1000
08-04 11:57:28.075  7299  7299 I libpersona: KNOX_SDCARD not a persona
08-04 11:57:28.095  7299  7299 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:28.095  7299  7299 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 11:57:28.095  7299  7299 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-04 11:57:28.115  7299  7299 D TimaKeyStoreProvider: TimaSignature is unavailable
08-04 11:57:28.115  7299  7299 D ActivityThread: Added TimaKeyStore provider
08-04 11:57:28.135  7299  7299 D ResourcesManager: creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
08-04 11:57:28.155  7299  7299 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
08-04 11:57:28.155  7299  7299 D SecurityLogAgent:  SeDenialReceiver : File path = null
08-04 11:57:28.155   765  1680 I ActivityManager: Killing 5080:com.google.android.music:main/u0a144 (adj 15): emptyCount ##41
08-04 11:57:28.175  7235  7294 W jxcore-log: Platform android
08-04 11:57:28.175  7235  7294 W jxcore-log: 
08-04 11:57:28.175  7235  7294 W jxcore-log: Process ARCH arm
08-04 11:57:28.175  7235  7294 W jxcore-log: 
,08-04 11:57:28.435  7235  7294 I jxcore-log: JXcore Cordova bridge is ready!
08-04 11:57:28.435  7235  7294 I jxcore-log: 
,08-04 11:57:28.435  7235  7294 W jxcore-log: JXcore engine is started
,08-04 11:57:28.435  7235  7285 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-04 11:57:28.435  7235  7235 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-04 11:57:28.695   303   303 E SMD     : DCD ON
,08-04 11:57:31.305   765  1062 I PowerManagerService: [PWL] Off : 105s ago
,08-04 11:57:31.695   303   303 E SMD     : DCD ON
,08-04 11:57:32.875   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,08-04 11:57:33.165   765  1117 V AlarmManager: waitForAlarm result :4
,08-04 11:57:33.175   765  1117 D ActivityManager: caller:null, r.packageName :com.google.android.gms
,08-04 11:57:33.185  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-04 11:57:33.185  1195  1195 D KeyguardUpdateMonitor: handleTimeUpdate
,08-04 11:57:33.195  1195  1195 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-04 11:57:33.195  1195  1195 I KeyguardEffectViewController: *** don't update sliding image ***
,08-04 11:57:33.195   765  1401 D NtpTrustedTime: forceRefresh() from cache miss
,08-04 11:57:33.215   765  1263 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-04 11:57:33.215   765  1263 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
08-04 11:57:33.215   765  1263 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
08-04 11:57:33.215   765  1263 D BatteryService: stay LED for fully charged
08-04 11:57:33.215   765   765 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-04 11:57:33.215  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-04 11:57:33.215  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
08-04 11:57:33.215   765   765 I MotionRecognitionService: Plugged
08-04 11:57:33.215   765   765 I MotionRecognitionService: setPowerConnected  = true
08-04 11:57:33.215  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
08-04 11:57:33.215  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-04 11:57:33.215  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-04 11:57:33.215  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-04 11:57:33.225  2992  2992 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-04 11:57:33.225  2992  3084 D HeadsetStateMachine: Disconnected process message: 10
,08-04 11:57:33.225   765  1444 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-04 11:57:33.225   765  1401 D NtpTrustedTime: requestTime Success from server:2.android.pool.ntp.org mCachedNtpTime : 1470304653229 mCachedNtpElapsedRealtime : 185860 mCachedNtpCertainty : 14
08-04 11:57:33.225   765  1401 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 11:57:33.235   765  1401 D AlarmManagerService: Setting time of day to sec=1470304653
08-04 11:57:33.235   765  1401 D AlarmManagerService: Trying to open a file
,08-04 11:57:33.235   765  1401 D AlarmManagerService: File Open Success
08-04 11:57:33.235   765  1401 D AlarmManagerService: File Close Success
08-04 11:57:33.235   765  1401 I AlarmManagerService: DRM_TIME_PATH CHMOD 666 for resetState done 
,08-04 11:57:33.230   765  1117 V AlarmManager: waitForAlarm result :65536
08-04 11:57:33.230   765  1401 W AlarmManagerService: Unable to set rtc to 1470304653: Invalid argument
,08-04 11:57:33.230  1195  1195 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-04 11:57:33.230  2540  7339 I MS_RegisterService: RegisterService intent:Intent { act=com.google.android.gms.matchstick.register_intent_action (has extras) } isPeriodic:false
,08-04 11:57:33.230  1195  1195 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-04 11:57:33.260   765   765 D WifiStateMachine: android.intent.action.TIME_SET - start updateConfiguredNetworkExpiration()
,08-04 11:57:33.260  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_SET
08-04 11:57:33.260  1195  1195 D KeyguardUpdateMonitor: handleTimeUpdate
,08-04 11:57:33.260  1195  1195 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_SET
,08-04 11:57:33.260   765   765 I DowntimeConditions: android.intent.action.TIME_SET ignored because schedule turned off.
,08-04 11:57:33.260  1195  1195 D StatusBar-DoNotDistrub: Received intent with android.intent.action.TIME_SET action
,08-04 11:57:33.260  1195  1195 D StatusBar-DoNotDistrub: Not data shared android.content.pm.PackageManager$NameNotFoundException: Application package com.sec.android.settings.praymodewidget not found
,08-04 11:57:33.270   765   765 W Settings: Setting auto_time has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 11:57:33.270   765  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.fotaclient, hostingType: broadcast
,08-04 11:57:33.270   765  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:33.270   765  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:33.270   765  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:33.270   765  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:33.270  1782  1782 D accuweather: [Accuweather J]>>> SWW:64 [0:0] =============== BR act = androidintentactionTIME_SET
,08-04 11:57:33.270  1782  1782 D accuweather: [Accuweather J]>>> SWW:645 [0:0] renderUpdateAllCondition : [0] = 1
,08-04 11:57:33.270  1782  1782 D accuweather: [Accuweather J]>>> WR:452 [0:0] =============== updateAllCondition = 1
08-04 11:57:33.270   765   765 I DrmEventService:  no response from SecureClock 
,08-04 11:57:33.310  7351  7351 E Zygote  : MountEmulatedStorage()
08-04 11:57:33.310  7351  7351 E Zygote  : v2
08-04 11:57:33.310  7351  7351 I libpersona: KNOX_SDCARD checking this for 10014
08-04 11:57:33.310  7351  7351 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:33.310   765  1015 I ActivityManager: Start proc com.sec.android.fotaclient for broadcast com.sec.android.fotaclient/.FotaRegisterReceiver: pid=7351 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-04 11:57:33.310   765  1703 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-04 11:57:33.320  1195  1195 D StatusBar-DoNotDistrub: sendBroadcast android.intent.action.DORMANT_MODE_OFF
,08-04 11:57:33.330  7351  7351 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:33.330  7351  7351 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 11:57:33.330   309   693 V AudioPolicyManager: getOutputsForDevice device 0002 -> 0002
08-04 11:57:33.330   765  1352 I AudioService: getStreamVolume 5 index 0
08-04 11:57:33.330  7351  7351 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
08-04 11:57:33.330  1195  1195 D StatusBar-DoNotDistrub: The STREAM NOTIFICATION volume is 0
08-04 11:57:33.330   765  1330 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=com.android.systemui
,08-04 11:57:33.340  1195  1195 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-04 11:57:33.340  2540  7339 I MS_RegisterService: Phone type: 1
,08-04 11:57:33.340  1195  1195 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-04 11:57:33.340   765  1703 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:33.340  2540  7339 I MS_RegisterService: Doing full registration.
,08-04 11:57:33.340   765   784 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-04 11:57:33.350  7351  7351 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:33.350  7351  7351 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:33.360   765  1263 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-04 11:57:33.370   765  1493 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-04 11:57:33.370  7351  7351 D ResourcesManager: creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,08-04 11:57:33.370   765  1573 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-04 11:57:33.380   765  1449 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-04 11:57:33.380   765  1352 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-04 11:57:33.390   765   784 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-04 11:57:33.390   765  1652 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-04 11:57:33.400   765  3205 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-04 11:57:33.400   765  1449 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-04 11:57:33.410   765  1680 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-04 11:57:33.420   765  1573 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-04 11:57:33.420  7351  7351 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,08-04 11:57:33.430   765  1680 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-04 11:57:33.430  7351  7351 I FOTA_Client: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,08-04 11:57:33.440  4014  4014 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-04 11:57:33.440  4014  4014 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.TIME_SET , timestamp: 1470304653443
,08-04 11:57:33.440  4014  4014 I KLMS-2.4.511: : MainReciver(): TIME_CHANGED
,08-04 11:57:33.440  4014  4014 I KLMS-2.4.511: : StateImplV2(): dateTimeChanged().START : Thu Aug 04 11:57:33 GMT+02:00 2016
,08-04 11:57:33.450  4014  4014 I KLMS-2.4.511: : StateImplV2(): dateTimeChanged().END
,08-04 11:57:33.540   765  1263 I art     : Explicit concurrent mark sweep GC freed 39699(2MB) AllocSpace objects, 27(432KB) LOS objects, 29% free, 37MB/53MB, paused 1.344ms total 92.904ms
,08-04 11:57:33.540   765  1263 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-04 11:57:33.550  6648  6648 W System.err: android.provider.Settings$SettingNotFoundException: TIME_DIFFERENCE
,08-04 11:57:33.550  6648  6648 W System.err: 	at android.provider.Settings$System.getLongForUser(Settings.java:1679)
08-04 11:57:33.550  6648  6648 W System.err: 	at android.provider.Settings$System.getLong(Settings.java:1669)
08-04 11:57:33.550  6648  6648 W System.err: 	at com.sec.android.sCloudSync.g.d.b(SourceFile:83)
08-04 11:57:33.550  6648  6648 W System.err: 	at com.sec.android.sCloudSync.Receivers.TimeChangedReceiver.onReceive(SourceFile:64)
08-04 11:57:33.550  6648  6648 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
08-04 11:57:33.550  6648  6648 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
08-04 11:57:33.550  6648  6648 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
08-04 11:57:33.550  6648  6648 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:57:33.550  6648  6648 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-04 11:57:33.550  6648  6648 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 11:57:33.550  6648  6648 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:57:33.550  6648  6648 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:57:33.550  6648  6648 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 11:57:33.550  6648  6648 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,08-04 11:57:33.560   765  1573 D ActivityManager: bindService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms, action: null
,08-04 11:57:33.560   765  1703 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,08-04 11:57:33.560   765  1703 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:33.560   765  1703 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:33.560   765  1703 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:33.560   765  1703 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:33.600  7370  7370 E Zygote  : MountEmulatedStorage()
,08-04 11:57:33.600  7370  7370 E Zygote  : v2
08-04 11:57:33.600  7370  7370 I libpersona: KNOX_SDCARD checking this for 10042
08-04 11:57:33.600  7370  7370 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:33.610   765  1703 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/com.sec.android.fota.osp.time.ServerTimeReceiver: pid=7370 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,08-04 11:57:33.660  7370  7370 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:33.660  7370  7370 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 11:57:33.660  7370  7370 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 11:57:33.660  2540  7339 I MS_RegisterService: Throttling registration.
,08-04 11:57:33.660  2540  7339 W MS_WakeLockHelper: Call to release wakelock: register_service_start_wakelock, but not held.
,08-04 11:57:33.660   765  1476 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-04 11:57:33.660   765  1476 D ActivityManager: caller:android.app.ApplicationThreadProxy@376091ee, r.packageName :com.google.android.gms
,08-04 11:57:33.680  7370  7370 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:33.680  7370  7370 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:33.690  7370  7370 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,08-04 11:57:33.720  7370  7370 I SO_AGENT: [com.sec.android.fota.osp.time.ServerTimeReceiver(47/onReceive)] No action is available before server time settings
,08-04 11:57:33.720  6697  6697 I SA      : [SBR] StdBroadcastReceiver received Intent of  action.TIME_SET.
,08-04 11:57:33.740   765  1263 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.sync, hostingType: broadcast
,08-04 11:57:33.740   765  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:33.740   765  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:33.740   765  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:33.740   765  1263 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:33.780  7386  7386 E Zygote  : MountEmulatedStorage()
08-04 11:57:33.780  7386  7386 E Zygote  : v2
08-04 11:57:33.780  7386  7386 I libpersona: KNOX_SDCARD checking this for 10076
08-04 11:57:33.780  7386  7386 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:33.790   765  1263 I ActivityManager: Start proc com.samsung.android.scloud.sync for broadcast com.samsung.android.scloud.sync/com.sec.android.sCloudSync.Receivers.TimeChangedReceiver: pid=7386 uid=10076 gids={50076, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-04 11:57:33.850  7386  7386 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:33.850  7386  7386 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 11:57:33.850  7386  7386 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 11:57:33.850   765  1263 I ActivityManager: Killing 6341:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 15): emptyCount ##41
,08-04 11:57:33.870   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,08-04 11:57:33.870  7386  7386 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:33.870  7386  7386 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:33.890  7386  7386 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudDataSync/sCloudDataSync.apk
,08-04 11:57:33.930   765  1680 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.clockpackage, hostingType: broadcast
,08-04 11:57:33.930   765  1680 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:33.930   765  1680 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:33.930   765  1680 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:33.930   765  1680 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:34.010  7403  7403 E Zygote  : MountEmulatedStorage()
08-04 11:57:34.010  7403  7403 E Zygote  : v2
08-04 11:57:34.010  7403  7403 I libpersona: KNOX_SDCARD checking this for 10106
08-04 11:57:34.010  7403  7403 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:34.020   765  1680 I ActivityManager: Start proc com.sec.android.app.clockpackage for broadcast com.sec.android.app.clockpackage/.alarm.AlarmReceiver: pid=7403 uid=10106 gids={50106, 9997, 3003, 1028, 1015, 1023} abi=armeabi-v7a
,08-04 11:57:34.090  7403  7403 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:34.090  7403  7403 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 11:57:34.090  7403  7403 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 11:57:34.090   765  1680 I ActivityManager: Killing 6390:com.google.android.gms:car/u0a15 (adj 15): emptyCount ##41
,08-04 11:57:34.090  7386  7401 I  Time Manager : Time Difference not stored. TIME_DIFFERENCE
,08-04 11:57:34.110  7403  7403 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:34.110  7403  7403 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:34.130  7403  7403 D ResourcesManager: creating new AssetManager and set to /system/app/ClockPackage_Osup/ClockPackage_Osup.apk
,08-04 11:57:34.130  7403  7403 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-04 11:57:34.130  7403  7403 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 11:57:34.130  7403  7403 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-04 11:57:34.180   765   785 D SettingsProvider: name = next_alarm_formatted
08-04 11:57:34.180   765   785 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:57:34.180   765   785 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:57:34.180   765   785 D SettingsProvider: selectionArgs: false
08-04 11:57:34.180   765   785 D SettingsProvider: selectionArgs: 10106
08-04 11:57:34.180   765   785 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:57:34.180   765   785 D SettingsProvider: ret = -1
,08-04 11:57:34.310   765  1680 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-04 11:57:34.310   765  1680 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:34.310   765  1680 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:34.310   765  1680 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:34.310   765  1680 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:34.340  7419  7419 E Zygote  : MountEmulatedStorage()
08-04 11:57:34.340  7419  7419 E Zygote  : v2
08-04 11:57:34.340  7419  7419 I libpersona: KNOX_SDCARD checking this for 10116
08-04 11:57:34.340  7419  7419 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:34.350   765  1680 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7419 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,08-04 11:57:34.400  7419  7419 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:34.400  7419  7419 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 11:57:34.400   765  1680 I ActivityManager: Killing 6538:com.sec.enterprise.knox.cloudmdm.smdms/u0a201 (adj 15): emptyCount ##41
08-04 11:57:34.400  7419  7419 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 11:57:34.430  7419  7419 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:34.430  7419  7419 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:34.440  7419  7419 D ResourcesManager: creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,08-04 11:57:34.450  7419  7419 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver }
,08-04 11:57:34.460  7419  7419 D elm:14491: ELMEngine.ELMEngine( context ).
,08-04 11:57:34.460  7419  7419 D elm:14491: MDMBridge.setEnterpriseBridge()
,08-04 11:57:34.460   765  1352 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-04 11:57:34.460   765  1352 D ActivityManager: caller:android.app.ApplicationThreadProxy@ca8d68f, r.packageName :com.sec.esdk.elm
,08-04 11:57:34.460  7419  7419 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.service.ElmAgentService } END.
,08-04 11:57:34.470   765  1573 D ActivityManager: startProcessLocked calleePkgName: com.android.calendar, hostingType: broadcast
,08-04 11:57:34.470   765  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:34.470   765  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:34.470   765  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:34.470   765  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:34.470  7419  7419 D elm:14491: ElmAgentService : onCreate()
08-04 11:57:34.470  7419  7437 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.TIME_SET flg=0x34000010 cmp=com.sec.esdk.elm/.service.ElmAgentService }
,08-04 11:57:34.480  7419  7437 D elm:14491: ELMAgentService.listeningToTimeDateChanges( context, intent ).
,08-04 11:57:34.480  7419  7419 D elm:14491: ELMEngine.ServiceHandler.handleMessage( ALARM_MODIFY ). 
,08-04 11:57:34.480  7419  7419 D elm:14491: ModuleBase.ModifySetAlarm()
08-04 11:57:34.480  7419  7419 D elm:14491: MDMBridge.getInstance()
08-04 11:57:34.480  7419  7419 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,08-04 11:57:34.550   765  1573 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.alerts.AlertReceiver: pid=7440 uid=10172 gids={50172, 9997, 3003, 1028, 1015, 1023, 3002} abi=armeabi-v7a
,08-04 11:57:34.550  7440  7440 E Zygote  : MountEmulatedStorage()
08-04 11:57:34.550  7440  7440 E Zygote  : v2
08-04 11:57:34.550  7440  7440 I libpersona: KNOX_SDCARD checking this for 10172
08-04 11:57:34.550  7440  7440 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:34.580  7440  7440 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:34.580  7419  7419 D elm:14491: ElmAgentService : onDestroy().
08-04 11:57:34.580  7440  7440 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 11:57:34.580  7440  7440 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 11:57:34.580   765  1263 I ActivityManager: Killing 6494:com.android.defcontainer/u0a7 (adj 15): emptyCount ##41
,08-04 11:57:34.600  7440  7440 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:34.600  7440  7440 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:34.620  7440  7440 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,08-04 11:57:34.620  7440  7440 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-04 11:57:34.620  7440  7440 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 11:57:34.620  7440  7440 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-04 11:57:34.660   765  1232 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-04 11:57:34.660   765  1232 D ActivityManager: caller:android.app.ApplicationThreadProxy@3aac1d25, r.packageName :com.android.calendar
,08-04 11:57:34.680   303   303 E SMD     : DCD ON
,08-04 11:57:34.680   765  1573 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-04 11:57:34.680   765  1573 D ActivityManager: caller:android.app.ApplicationThreadProxy@29664cab, r.packageName :com.android.calendar
,08-04 11:57:34.680   765  1703 D ActivityManager: getContentProviderImpl callerProcessName:com.android.calendar, calleePkgName: com.android.providers.calendar
,08-04 11:57:34.680   765  1703 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:34.680   765  1703 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:34.680   765  1703 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:34.680   765  1703 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:34.720  7461  7461 E Zygote  : MountEmulatedStorage()
,08-04 11:57:34.720  7461  7461 E Zygote  : v2
08-04 11:57:34.720  7461  7461 I libpersona: KNOX_SDCARD checking this for 10051
08-04 11:57:34.720  7461  7461 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:34.730   765  1703 I ActivityManager: Start proc com.android.providers.calendar for content provider com.android.providers.calendar/.CalendarProvider2: pid=7461 uid=10051 gids={50051, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-04 11:57:34.760  7461  7461 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:34.760  7461  7461 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 11:57:34.760  7461  7461 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-04 11:57:34.760  7299  7299 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-04 11:57:34.760  7299  7299 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-04 11:57:34.760  7299  7299 D SecurityLogAgent: StateMachine : Current State = 1
08-04 11:57:34.770   765  1652 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:34.770   765  1232 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:34.770   765  1476 D ActivityManager: startProcessLocked calleePkgName: com.qualcomm.timeservice, hostingType: broadcast
,08-04 11:57:34.770   765  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:34.770   765  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:34.770   765  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:34.770   765  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:34.780  7461  7461 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:34.780  7461  7461 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:34.810   765  1476 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7477 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-04 11:57:34.810  7477  7477 E Zygote  : MountEmulatedStorage()
08-04 11:57:34.810  7477  7477 E Zygote  : v2
08-04 11:57:34.810  7477  7477 I libpersona: KNOX_SDCARD checking this for 1000
08-04 11:57:34.810  7477  7477 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:34.830  7477  7477 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:34.830  7477  7477 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 11:57:34.830  7477  7477 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 11:57:34.840  7461  7461 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecCalendarProvider/SecCalendarProvider.apk
,08-04 11:57:34.840  7461  7461 W ResourcesManager: Asset path '/system/framework/android.test.runner.jar' does not exist or contains no resources.
,08-04 11:57:34.850  7477  7477 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:34.850  7477  7477 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:34.860  7477  7477 D ResourcesManager: creating new AssetManager and set to /system/app/TimeService/TimeService.apk
,08-04 11:57:34.870   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,08-04 11:57:34.880  7477  7477 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1470304654884
08-04 11:57:34.880  7477  7477 D         : TimeServiceNative: User Time to be set is 1470304654885
08-04 11:57:34.880  7477  7477 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-04 11:57:34.880  7477  7477 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-04 11:57:34.880  7477  7477 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1470304654885
,08-04 11:57:34.880   365   738 D QC-time-services: Daemon: Connection accepted:time_genoff
,08-04 11:57:34.880  7477  7477 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-04 11:57:34.880   365  7496 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1470304654885
08-04 11:57:34.880   365  7496 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1470304654885, operation = 0
,08-04 11:57:34.880   365  7496 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS11/12/70 16:46:38
08-04 11:57:34.880   365  7496 D QC-time-services: Daemon:Value read from RTC seconds = 29868398000
08-04 11:57:34.880   365  7496 D QC-time-services: Daemon:new time 1470304654885 
08-04 11:57:34.880   365  7496 D QC-time-services: Daemon: delta 1440436256885 genoff 1440436256885 
08-04 11:57:34.880   365  7496 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440436256885 to memory
08-04 11:57:34.880   365  7496 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-04 11:57:34.880   365  7496 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-04 11:57:34.890   365  7496 D QC-time-services: Updating the TOD offset
08-04 11:57:34.890   365  7496 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1440436256885 to memory
08-04 11:57:34.890   365  7496 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-04 11:57:34.890   365  7496 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
,08-04 11:57:34.890   365  7496 E QC-time-services: Daemon:Update to modem bit set
08-04 11:57:34.890   365  7496 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-04 11:57:34.890   365  7496 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1124471456885
,08-04 11:57:34.890  7477  7477 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
,08-04 11:57:34.890   765  1330 I ActivityManager: Killing 6580:com.google.android.partnersetup/u0a19 (adj 15): emptyCount ##41
,08-04 11:57:34.900  4156  4156 D comdaemonstockapp: [Daemon_Stock]>>> Stockclock_DaemonService.java:63 [0:0] onReceive: androidintentactionTIME_SET
08-04 11:57:34.900  4156  4156 D comdaemonstockapp: [Daemon_Stock]>>> Stockclock_DaemonService.java:64 [0:0] appServiceStatus: 0
,08-04 11:57:34.900  4156  4156 D comdaemonstockapp: [Daemon_Stock]>>> Stockclock_DaemonService.java:65 [0:0] [AR]: 0
,08-04 11:57:34.900  4156  4156 D comdaemonstockapp: [Daemon_Stock]>>> Stockclock_DaemonService.java:66 [0:0] [AR]: Next time = 0
08-04 11:57:34.900   365   738 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
,08-04 11:57:34.900  4156  4156 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:70 [0:0] Act : androidintentactionTIME_SET, run:true
,08-04 11:57:34.900  4156  4156 D comsamsunglog: [MSC_Accu_Daemon]>>> ====================================================================================================================
08-04 11:57:34.900  4156  4156 D comsamsunglog: [MSC_Accu_Daemon]>>> daemonapp [Version : 150820735400 ] [ 1 ] 
08-04 11:57:34.900  4156  4156 D comsamsunglog: [MSC_Accu_Daemon]>>> Header set to : ===> "daemonapp" <===
08-04 11:57:34.900  4156  4156 D comsamsunglog: [MSC_Accu_Daemon]>>> ====================================================================================================================
,08-04 11:57:34.900  4156  4156 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-04 11:57:34.900  4156  4156 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,08-04 11:57:34.910  4156  4156 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,08-04 11:57:34.910  4156  4156 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,08-04 11:57:34.910  4156  4156 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/current_weatherinfo
,08-04 11:57:34.910  4156  4156 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/settings
,08-04 11:57:34.910  4156  4156 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:113 [0:0] SerStus:true,TmpS:1,AtRfr:3, checkCurrent: 0
,08-04 11:57:34.920  4156  4156 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-04 11:57:34.920  4156  4156 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,08-04 11:57:34.920  4156  4156 D daemonapp: [MSC_Accu_Daemon]>>> ACP:435 [0:0] Provider query : content://apaccuweatherprovider/packagename
,08-04 11:57:34.920  7461  7461 I CalendarProvider2: CalendarProvider2.onCreate() called
,08-04 11:57:34.920  4156  4156 D daemonapp: [MSC_Accu_Daemon]>>> AWDS:1099 [0:0] PakNme size = 1
,08-04 11:57:34.960   765  1232 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-04 11:57:34.960   765  1232 D ActivityManager: caller:android.app.ApplicationThreadProxy@2125f3b4, r.packageName :com.google.android.gms
,08-04 11:57:35.000   365   736 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,08-04 11:57:35.000   294   294 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x5 conn_h=0xb6b01090
08-04 11:57:35.000   294   294 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-04 11:57:35.000   294   294 I rmt_storage: wakelock acquired: 1, error no: 42
08-04 11:57:35.000   294   662 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1229455232)
,08-04 11:57:35.050   765  1449 D ActivityManager: startService callerProcessName:com.android.providers.calendar, calleePkgName: com.android.providers.calendar
08-04 11:57:35.050   294   662 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
08-04 11:57:35.050   294   662 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-04 11:57:35.050   294   662 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1229455232) wakelock released: 1, error no: 0
08-04 11:57:35.050   294   662 I rmt_storage: 
08-04 11:57:35.050   765  1449 D ActivityManager: caller:android.app.ApplicationThreadProxy@207448d9, r.packageName :com.android.providers.calendar
,08-04 11:57:35.050   294   294 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x5 conn_h=0x0xb6b01090
,08-04 11:57:35.080   765  1232 I ActivityManager: Killing 6598:com.samsung.groupcast/u0a20 (adj 15): emptyCount ##41
,08-04 11:57:35.870   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,08-04 11:57:36.050  7461  7461 I CalendarProvider2: Sending notification intent: Intent { act=android.intent.action.PROVIDER_CHANGED dat=content://com.android.calendar }
,08-04 11:57:36.050   765  1015 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.widgetapp.SPlannerAppWidget, hostingType: broadcast
,08-04 11:57:36.050   765  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:36.050   765  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:36.050   765  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:36.050   765  1015 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:36.100   765  1015 I ActivityManager: Start proc com.sec.android.widgetapp.SPlannerAppWidget for broadcast com.sec.android.widgetapp.SPlannerAppWidget/.EasyWidget.EasyCalendarAppWidgetProvider: pid=7509 uid=10171 gids={50171, 9997} abi=armeabi-v7a
,08-04 11:57:36.100  7509  7509 E Zygote  : MountEmulatedStorage()
08-04 11:57:36.100  7509  7509 E Zygote  : v2
08-04 11:57:36.100  7509  7509 I libpersona: KNOX_SDCARD checking this for 10171
08-04 11:57:36.100  7509  7509 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:36.140  7509  7509 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:36.140   765  1493 I ActivityManager: Killing 6614:com.sec.android.service.health/u0a21 (adj 15): emptyCount ##41
08-04 11:57:36.140  7509  7509 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 11:57:36.140  7509  7509 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-04 11:57:36.160  7509  7509 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:36.160  7509  7509 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:36.190  7509  7509 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,08-04 11:57:36.200  7509  7509 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-04 11:57:36.200  7509  7509 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-04 11:57:36.230   765  1352 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-04 11:57:36.230   765  1352 D ActivityManager: caller:android.app.ApplicationThreadProxy@22b2817f, r.packageName :com.android.calendar
,08-04 11:57:36.230   765  1263 D ActivityManager: startService callerProcessName:com.android.calendar, calleePkgName: com.android.calendar
,08-04 11:57:36.230   765  1263 D ActivityManager: caller:android.app.ApplicationThreadProxy@21579995, r.packageName :com.android.calendar
,08-04 11:57:36.240   765  3205 I ActivityManager: Killing 6633:com.sec.pcw.device/1000 (adj 15): emptyCount ##41
,08-04 11:57:36.250   765  1066 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-04 11:57:36.870   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,08-04 11:57:37.230   765  3091 D SSRM:n  : SIOP:: AP = 380, PST = 353, CUR = 450
,08-04 11:57:37.680   303   303 E SMD     : DCD ON
,08-04 11:57:37.870   362   362 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,08-04 11:57:40.679   303   303 E SMD     : DCD ON
,08-04 11:57:40.689   765   785 I ActivityManager: Killing 4873:com.sec.spp.push/u0a43 (adj 15): emptyCount ##41
,08-04 11:57:43.269   765  1573 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-04 11:57:43.269   765  1573 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
08-04 11:57:43.269   765  1573 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
08-04 11:57:43.269   765  1573 D BatteryService: stay LED for fully charged
08-04 11:57:43.269   765   765 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-04 11:57:43.279   765   765 I MotionRecognitionService: Plugged
08-04 11:57:43.279   765   765 I MotionRecognitionService: setPowerConnected  = true
,08-04 11:57:43.289  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-04 11:57:43.289  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-04 11:57:43.289  2992  2992 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-04 11:57:43.289  2992  3084 D HeadsetStateMachine: Disconnected process message: 10
,08-04 11:57:43.299  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,08-04 11:57:43.299  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-04 11:57:43.299  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-04 11:57:43.299  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-04 11:57:43.679   303   303 E SMD     : DCD ON
,08-04 11:57:43.749   765  3128 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-04 11:57:44.279  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-04 11:57:44.279  7235  7294 I jxcore-log: 
,08-04 11:57:44.279  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-04 11:57:44.279  7235  7294 I jxcore-log: 
,08-04 11:57:44.279   765  1680 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:44.289  7235  7294 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:57:44.289  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:44.289  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:44.289  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:57:44.289  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:57:44.289  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:44.289  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:57:44.289  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 11:57:44.289  7235  7294 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 11:57:44.289  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-04 11:57:44.289  7235  7294 I jxcore-log: 
,08-04 11:57:44.289  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-04 11:57:44.289  7235  7294 I jxcore-log: 
,08-04 11:57:44.629  7235  7294 D ExecuteNativeTests: Running unit tests
,08-04 11:57:44.729  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 11:57:44.729  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 added. We now have 2 listener(s)
,08-04 11:57:44.729  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,08-04 11:57:44.729  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 11:57:44.729  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:57:44.729  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:57:44.729  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 added. We now have 2 listener(s)
08-04 11:57:44.729  7235  7294 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 11:57:44.729  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 11:57:44.739  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 11:57:44.739   765  1330 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:44.739  7235  7294 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:57:44.739  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:44.739  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:44.739  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:57:44.739  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:57:44.739  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:44.739  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:57:44.739  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 11:57:44.749  7235  7294 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 11:57:44.749  7235  7294 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 11:57:44.749   765   784 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:44.749  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:44.749   765  1232 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:44.749  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-04 11:57:44.749  7235  7294 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 11:57:44.749  7235  7294 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-04 11:57:44.749  7235  7294 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-04 11:57:44.749  7235  7294 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-04 11:57:44.749  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 11:57:44.749  7235  7294 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 11:57:44.749  7235  7294 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 11:57:44.749  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 11:57:44.759  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:44.759  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:44.759  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:44.759  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 11:57:44.759  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:57:44.759  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:57:44.759  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 removed from the list
08-04 11:57:44.759  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.759  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 removed from the list
,08-04 11:57:44.759  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:44.759  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:44.759  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 11:57:44.759  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.759  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 11:57:44.759  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:44.759  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:44.759  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 11:57:44.759  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
,08-04 11:57:44.759  7235  7294 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-04 11:57:44.759  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:44.759  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:44.759  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:44.759  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 11:57:44.759  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.759  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.769  7235  7294 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 not in the list
08-04 11:57:44.769  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.769  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:44.769  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 11:57:44.769  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.769  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.769  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.769  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:44.769  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:44.769  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.769  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
,08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
,08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-04 11:57:44.769  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-04 11:57:44.779  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-04 11:57:44.779  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,08-04 11:57:44.779  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-04 11:57:44.779  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-04 11:57:44.779  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:44.779  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:44.779  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:44.779  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:44.779  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.779  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.779  7235  7294 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 not in the list
08-04 11:57:44.779  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.779  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.779  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:44.779  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.779  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.779  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.779  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.779  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:44.779  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:44.779  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.779  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.779  7235  7294 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-04 11:57:44.779  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:57:44.779   765   784 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:44.779  7235  7294 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:57:44.779  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:44.779  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:44.779  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:57:44.779  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:57:44.779  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:44.779  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:57:44.779  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:57:44.779  7235  7294 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:44.789  7235  7294 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 11:57:44.789   765  1493 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:44.789  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:44.789   765  1703 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:44.789  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:44.789  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 11:57:44.789  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 11:57:44.789  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 11:57:44.789  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:57:44.789  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 11:57:44.789  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 11:57:44.799  7235  7294 E BluetoothAdapter: bluetooth le advertising not supported
08-04 11:57:44.799  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 11:57:44.799  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-04 11:57:44.799  7235  7294 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-04 11:57:44.799  7235  7294 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-04 11:57:44.799  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 11:57:44.799  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:57:44.799  7235  7294 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-04 11:57:44.799  7235  7294 I io.jxcore.node.ConnectionHelper: start: OK
08-04 11:57:44.809  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:44.809  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:44.809  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:44.809  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:44.809  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.809  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:57:44.809  7235  7294 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 not in the list
08-04 11:57:44.809  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.809  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.809  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:44.809  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.809  7235  7294 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-04 11:57:44.809  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:57:44.809   765  1680 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:44.809  7235  7294 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:57:44.809  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:44.809  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:44.809  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:57:44.809  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:57:44.809  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:44.809  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:57:44.809  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:57:44.819  7235  7294 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:44.819  7235  7294 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 11:57:44.819   765  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:44.819  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 11:57:44.819  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 11:57:44.819  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 11:57:44.819  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:57:44.819  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 11:57:44.819  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:44.819   765  1330 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:44.819  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:44.819  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 11:57:44.819  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:57:44.829  7235  7294 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-04 11:57:44.829  7235  7294 I io.jxcore.node.ConnectionHelper: start: OK
08-04 11:57:44.829  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:44.829  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:44.829  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:44.829  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:44.829  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.829  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:57:44.829  7235  7294 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 not in the list
08-04 11:57:44.829  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.829  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.829  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:44.829  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.829  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.829  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.829  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:44.829  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:44.829  7235  7294 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:44.829  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:44.829  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.829  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.829  7235  7294 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-04 11:57:44.829  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:57:44.829   765  1703 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:44.839  7235  7294 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:57:44.839  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:44.839  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:44.839  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:57:44.839  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:57:44.839  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:44.839  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:57:44.839  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:57:44.839  7235  7294 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:44.839  7235  7294 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 11:57:44.839  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 11:57:44.839  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 11:57:44.839  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 11:57:44.839  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:57:44.839  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-04 11:57:44.839   765  1232 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:44.839  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:44.839   765  1703 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:44.839  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:44.839  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 11:57:44.839  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:57:44.849  7235  7294 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-04 11:57:44.849  7235  7294 I io.jxcore.node.ConnectionHelper: start: OK
08-04 11:57:44.849  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:44.849  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:44.849  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:44.849  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:44.849  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:44.849  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:44.849  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:44.849  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.849  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:57:44.849  7235  7294 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 not in the list
08-04 11:57:44.849  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.849  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.849  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:44.849  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.849  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.849  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.849  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:44.849  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:44.849  7235  7294 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:44.849  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:44.849  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.849  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
,08-04 11:57:44.849  7235  7294 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-04 11:57:44.849  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:44.849  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:44.849  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:44.849  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:44.849  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.849  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.849  7235  7294 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 not in the list
08-04 11:57:44.849  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.849  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.849  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:44.849  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.849  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.849  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.849  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.849  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:44.849  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:44.849  7235  7294 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:44.849  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:44.849  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.849  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.859  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-04 11:57:44.859  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:44.859  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:44.859  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:44.859  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:44.859  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.859  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.859  7235  7294 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 not in the list
08-04 11:57:44.859  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.859  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.859  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:44.859  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.859  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.859  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.859  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.859  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:44.859  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:44.859  7235  7294 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:44.859  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:44.859  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.859  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.859  7235  7294 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-04 11:57:44.859  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:44.859  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:44.859  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:44.859  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:44.859  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.859  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.859  7235  7294 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 not in the list
08-04 11:57:44.859  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.859  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.859  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:44.859  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.859  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.859  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.859  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.859  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:44.859  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:44.859  7235  7294 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:44.859  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:44.859  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.859  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.859  7235  7294 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-04 11:57:44.859  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:44.859  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:44.859  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:44.859  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:44.859  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.859  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.859  7235  7294 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 not in the list
08-04 11:57:44.859  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.859  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.859  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:44.859  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.859  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.859  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.859  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.869  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:44.869  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:44.869  7235  7294 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:44.869  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:44.869  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.869  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.869  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-04 11:57:44.869  7235  7294 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 11:57:44.869  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 11:57:44.869  7235  7294 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 11:57:44.869  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-04 11:57:44.869  7235  7294 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 11:57:44.869  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:44.869  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:44.869  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:44.869  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:44.869  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.869  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.869  7235  7294 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 not in the list
08-04 11:57:44.869  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.869  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.869  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:44.869  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.869  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.869  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.869  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.869  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:44.869  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:44.869  7235  7294 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:44.869  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:44.869  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.869  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.869  7235  7294 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 11:57:44.869  7235  7294 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-04 11:57:44.869  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-04 11:57:44.869  7235  7294 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 11:57:44.879  7235  7294 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-04 11:57:44.879  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-04 11:57:44.879  7235  7294 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-04 11:57:44.879  7235  7294 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 11:57:44.879  7235  7294 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-04 11:57:44.879  7235  7294 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 11:57:44.879  7235  7294 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 11:57:44.879  7235  7294 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-04 11:57:44.879  7235  7294 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 11:57:44.879  7235  7294 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 11:57:44.879  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-04 11:57:44.879  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-04 11:57:44.879  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-04 11:57:44.879  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-04 11:57:44.889  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-04 11:57:44.889  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-04 11:57:44.889  7235  7294 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-04 11:57:44.889  7235  7294 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 11:57:44.889  7235  7294 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-04 11:57:44.889  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:44.889  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:44.889  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:44.889  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:44.889  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.889  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.889  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
,08-04 11:57:44.889  7235  7294 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 not in the list
08-04 11:57:44.889  7235  7547 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1247)
08-04 11:57:44.889  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.889  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.889  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:44.889  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.889  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.889  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.889  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.899  7235  7548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1247
08-04 11:57:44.899  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:44.899  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:44.899  7235  7294 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:44.899  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:44.899  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.899  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.899  7235  7294 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-04 11:57:44.899  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:44.899  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:44.899  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:44.899  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:44.899  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.899  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.899  7235  7294 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 not in the list
08-04 11:57:44.899  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.899  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.899  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:44.899  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.899  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.899  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.899  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.899  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:44.899  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:44.899  7235  7294 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:44.899  7235  7547 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-04 11:57:44.899  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:44.899  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.899  7235  7547 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 11:57:44.899  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.899  7235  7294 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-04 11:57:44.899  7235  7548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 1247)
08-04 11:57:44.899  7235  7548 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@c97679c, channel: -1, state: INIT
08-04 11:57:44.899  7235  7548 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@c97679c, channel: -1, mSocketIS: null, mSocketOS: nullmSocket: null
08-04 11:57:44.899  7235  7548 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 1247)
08-04 11:57:44.899  2992  3404 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 11:57:44.899  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:44.899  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:44.899  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:44.909  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:44.909  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.909  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.909  7235  7294 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 not in the list
08-04 11:57:44.909  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.909  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.909  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:44.909  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.909  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.909  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.909  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.909  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:44.909  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:44.909  7235  7294 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:44.909  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:44.909  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.909  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.909  7235  7294 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-04 11:57:44.909  2992  3169 D bt_vendor: op for 7
08-04 11:57:44.909  7235  7294 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-04 11:57:44.909  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 11:57:44.909  7235  7294 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-04 11:57:44.909  7235  7294 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-04 11:57:44.909  7235  7294 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-04 11:57:44.909  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 11:57:44.909  7235  7294 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-04 11:57:44.909  7235  7294 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-04 11:57:44.909  7235  7294 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-04 11:57:44.909  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 11:57:44.909  7235  7294 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-04 11:57:44.909  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:44.909  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:44.909  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:44.909  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:44.909  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.909  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.909  7235  7294 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 not in the list
08-04 11:57:44.909  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.909  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.909  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:44.909  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.909  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.909  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.909  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.909  2992  3169 D bt_upio : proc btwrite assertion
08-04 11:57:44.909  7235  7547 D BluetoothSocket: connect(), SocketState: CLOSED, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
08-04 11:57:44.909  7235  7547 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@c97679c, channel: -1, state: CLOSED
08-04 11:57:44.909  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:44.909  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:44.909  7235  7294 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:44.909  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:44.909  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.909  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.909  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:44.919  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.919  7235  7547 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1247)
08-04 11:57:44.919  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.919  7235  7294 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 not in the list
08-04 11:57:44.919  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.919  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.919  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:44.919  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.919  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.919  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.919  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.919  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:44.919  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.919  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.919  7235  7294 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 not in the list
08-04 11:57:44.919  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:44.919  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:44.919  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:44.919  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:44.919  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.919  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.919  7235  7294 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 not in the list
08-04 11:57:44.919  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.919  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.919  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:44.919  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.919  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.919  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.919  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.919  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:44.919  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:44.919  7235  7294 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:44.919  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:44.919  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.919  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.919  7235  7294 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-04 11:57:44.919  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:57:44.919  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-04 11:57:44.919  7235  7294 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-04 11:57:44.919  7235  7294 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-04 11:57:44.919  7235  7235 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-04 11:57:44.919  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-04 11:57:44.919  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-04 11:57:44.919  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:44.919  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-04 11:57:44.919  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-04 11:57:44.919  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-04 11:57:44.919  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.929  7235  7294 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-04 11:57:44.929  7235  7235 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-04 11:57:44.929  7235  7294 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 not in the list
08-04 11:57:44.929  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.929  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 11:57:44.929  7235  7294 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 11:57:44.929  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 11:57:44.929  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 11:57:44.929  7235  7549 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-04 11:57:44.929  7235  7549 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-04 11:57:44.929  7235  7294 D BluetoothLeScanner: could not find callback wrapper
08-04 11:57:44.929  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:57:44.929  7235  7294 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 11:57:44.929  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.929  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.929  7235  7294 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 11:57:44.929  7235  7235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 11:57:44.929  7235  7235 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 11:57:44.929  7235  7235 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-04 11:57:44.929  7235  7235 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 11:57:44.929  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.929  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:44.929  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:44.929  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:44.929  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 11:57:44.929  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.929  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.929  7235  7294 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 not in the list
08-04 11:57:44.929  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.929  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.929  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:44.929  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.929  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.929  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.929  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.929  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:44.929  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:44.929  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.929  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.929  7235  7294 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-04 11:57:44.929  7235  7294 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-04 11:57:44.929  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 11:57:44.939  7235  7294 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 11:57:44.939  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:44.939  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:44.939  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:44.939  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:44.939  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.939  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.939  7235  7294 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 not in the list
08-04 11:57:44.939  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.939  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.939  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:44.939  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.939  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.939  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.939  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.939  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:44.939  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:44.939  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.939  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.939  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:44.939  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:44.939  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:44.939  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:44.939  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.939  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.939  7235  7294 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 not in the list
08-04 11:57:44.939  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.939  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.939  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:44.939  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.939  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.939  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.939  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.939  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:44.939  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:44.939  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.939  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.939  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:57:44.939  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:57:44.939  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:57:44.939  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:57:44.939  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.939  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.939  7235  7294 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e2c96 not in the list
08-04 11:57:44.939  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.939  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.939  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:57:44.939  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.939  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.939  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:57:44.939  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:57:44.949  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:57:44.949  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:57:44.949  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:57:44.949  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2c82e017 not in the list
08-04 11:57:44.949  7235  7294 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-04 11:57:44.949  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 11:57:44.949  7235  7294 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-04 11:57:44.949  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 11:57:44.949  7235  7294 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-04 11:57:44.949  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 11:57:44.949  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-04 11:57:44.949  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-04 11:57:44.949  7235  7294 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-04 11:57:44.949  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-04 11:57:44.949  7235  7294 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-04 11:57:44.949  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-04 11:57:44.949  7235  7294 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-04 11:57:44.949  7235  7294 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-04 11:57:44.949  7235  7294 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-04 11:57:44.949  7235  7294 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-04 11:57:44.949  7235  7294 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-04 11:57:44.949  7235  7294 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-04 11:57:44.949  7235  7294 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-04 11:57:44.949  7235  7294 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-04 11:57:44.949  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:57:44.949  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3cb0d5a5 added. We now have 2 listener(s)
08-04 11:57:44.949  7235  7294 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:57:44.959  7235  7294 D BluetoothAdapter: enable()
08-04 11:57:44.959  7235  7294 D BluetoothAdapter: enable(): BT is already enabled..!
08-04 11:57:44.959  7235  7294 I WifiManager: packageName : com.test.thalitest
08-04 11:57:44.959   765   784 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-04 11:57:44.959   765   784 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-04 11:57:44.959   765   784 D SecContentProvider2: mCursor = null
08-04 11:57:44.959   765   784 D WifiService: setWifiEnabled: true pid=7235, uid=10079
08-04 11:57:44.959   765   784 W ActivityManager: Permission Denial: getCurrentUser() from pid=7235, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-04 11:57:44.959   765   784 W WifiService: Failed getting userId using ActivityManagerNative
08-04 11:57:44.959   765   784 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7235, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-04 11:57:44.959   765   784 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
08-04 11:57:44.959   765   784 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
08-04 11:57:44.959   765   784 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
08-04 11:57:44.959   765   784 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-04 11:57:44.959   765   784 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-04 11:57:44.959   765   784 D SettingsProvider: name = wifi_on
08-04 11:57:44.959  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:57:44.959  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1b016d7a added. We now have 3 listener(s)
08-04 11:57:44.959  7235  7294 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:57:44.959  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:57:44.959  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1552f92b added. We now have 4 listener(s)
08-04 11:57:44.959  7235  7294 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:57:44.969  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:57:44.969  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e816188 added. We now have 5 listener(s)
08-04 11:57:44.969  7235  7294 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:57:44.969  7235  7294 I WifiManager: packageName : com.test.thalitest
08-04 11:57:44.969   765  1444 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-04 11:57:44.969   765  1444 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-04 11:57:44.969   765  1444 D SecContentProvider2: mCursor = null
08-04 11:57:44.969   765  1444 D WifiService: setWifiEnabled: false pid=7235, uid=10079
08-04 11:57:44.969   765  1444 D SettingsProvider: name = wifi_on
,08-04 11:57:44.969  7235  7294 D BluetoothAdapter: disable()
08-04 11:57:44.969   765   784 D SettingsProvider: name = bluetooth_on
08-04 11:57:44.969   765  1149 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-04 11:57:44.979  1281  1281 I wpa_supplicant: reset timer : RESET_TIMER 0
08-04 11:57:44.979  1281  1281 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-04 11:57:44.979   765  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 11:57:44.979  1281  1281 I wpa_supplicant: P2P: Current p2p state = IDLE
08-04 11:57:44.979   765  1476 D ActivityManager: caller:android.app.ApplicationThreadProxy@15ad5c14, r.packageName :com.android.bluetooth
08-04 11:57:44.979  2992  3063 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-04 11:57:44.979  2992  3063 D BluetoothAdapterProperties: Setting state to 13
08-04 11:57:44.979  2992  3063 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-04 11:57:44.979  2992  3063 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-04 11:57:44.979  2992  3063 D BluetoothAdapterService: updateAdapterState state is 13
08-04 11:57:44.979  2992  2992 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-04 11:57:44.979  2992  3063 D BluetoothAdapterService: Autoconnection is available 
08-04 11:57:44.979  2992  3063 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-04 11:57:44.979  2992  3063 D BluetoothAdapterService: terminating service from this receiver
08-04 11:57:44.979  2992  2992 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2fdd1499, channel: 19, state: LISTENING
08-04 11:57:44.979  2992  2992 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2fdd1499, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25cff9c8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@4be935emSocket: android.net.LocalSocket@2ebf933f impl:android.net.LocalSocketImpl@2829140c fd:FileDescriptor[72]
08-04 11:57:44.979  2992  2992 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2ebf933f impl:android.net.LocalSocketImpl@2829140c fd:FileDescriptor[72]
08-04 11:57:44.979   765  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 11:57:44.979  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:57:44.979   765  1493 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:44.979  1321  1321 D BluetoothPbap: Proxy object disconnected
08-04 11:57:44.979  1321  1321 D PbapServerProfile: Bluetooth service disconnected
08-04 11:57:44.979   765   765 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-04 11:57:44.979   765   765 I InputMethodManagerService: [BT Setting State] State =13
08-04 11:57:44.979  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:44.979  7235  7294 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:57:44.979  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:44.979  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:44.979  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:57:44.979  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:44.979  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:44.979  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:57:44.979  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 11:57:44.989  2992  2992 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@a5c876a, channel: 5, state: LISTENING
08-04 11:57:44.989  2992  2992 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@a5c876a, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12fbd986, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@a4245bmSocket: android.net.LocalSocket@25964f8 impl:android.net.LocalSocketImpl@ca3bdd1 fd:FileDescriptor[74]
08-04 11:57:44.989  2992  2992 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@25964f8 impl:android.net.LocalSocketImpl@ca3bdd1 fd:FileDescriptor[74]
08-04 11:57:44.989  1195  1195 D BluetoothTile:  onBluetoothStateChange:
08-04 11:57:44.989  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:44.989  7235  7294 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 11:57:44.989  7235  7294 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 11:57:44.989  2992  2992 I BtOppRfcommListener: stopping Accept Thread
08-04 11:57:44.989  2992  2992 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2633b036, channel: 12, state: LISTENING
08-04 11:57:44.989  2992  2992 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2633b036, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@312a39e0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@376ab37mSocket: android.net.LocalSocket@53bd8a4 impl:android.net.LocalSocketImpl@2955660d fd:FileDescriptor[77]
08-04 11:57:44.989  2992  2992 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@53bd8a4 impl:android.net.LocalSocketImpl@2955660d fd:FileDescriptor[77]
08-04 11:57:44.989  1321  1321 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:44.989   765  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:44.989  1281  1281 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
08-04 11:57:44.989  2992  5630 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-04 11:57:44.989  2992  5630 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-04 11:57:44.989  1750  1750 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-04 11:57:44.989  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-04 11:57:44.989  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:44.989  1195  1604 D BluetoothTile:  handleUpdatestate:false name:null
08-04 11:57:44.989  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:44.989   765  1449 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:44.989   765  1703 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,08-04 11:57:44.989  2992  3063 D BluetoothAdapterProperties: onBluetoothDisable()
08-04 11:57:44.989  1195  1604 D BluetoothTile:  handleUpdatestate:false name:null
,08-04 11:57:44.999  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:44.999   765   785 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-04 11:57:44.999   765  1238 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:44.999   765  1232 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-04 11:57:44.999   765   785 D ActivityManager: caller:android.app.ApplicationThreadProxy@80e2580, r.packageName :com.google.android.gms
08-04 11:57:44.999  2992  3063 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-04 11:57:44.999  2992  3169 D bt_vendor: op for 7
08-04 11:57:44.999  2992  3169 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:44.999   765  1449 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-04 11:57:44.999  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
08-04 11:57:44.999  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
08-04 11:57:44.999  2992  3169 D bt_vendor: op for 7
,08-04 11:57:44.999  2992  3169 D bt_upio : BT_WAKE is asserted already
08-04 11:57:44.999  7235  7235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:44.999  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:44.999  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:44.999  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:44.999  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:57:44.999  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:44.999  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:44.999  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:57:44.999  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 11:57:44.999  7235  7235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:44.999  7235  7235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 11:57:44.999  2992  3169 D bt_vendor: op for 7
08-04 11:57:44.999  2992  3169 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:44.999   765  1232 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:44.999  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:44.999  1321  1321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 11:57:44.999   765  1149 E native  : do suspend true
08-04 11:57:44.999  1195  1604 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-04 11:57:45.009   765  1148 D WifiP2pService: InactiveState{ what=143375 }
08-04 11:57:45.009   765  1148 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-04 11:57:45.009   765  1444 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-04 11:57:45.009   765  1444 D ActivityManager: caller:android.app.ApplicationThreadProxy@1f3877fe, r.packageName :com.android.settings
08-04 11:57:45.009  2992  3074 D BluetoothAdapterProperties: Scan Mode:20
,08-04 11:57:45.009  2992  3063 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-04 11:57:45.009  2992  3063 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
08-04 11:57:45.009  2992  3063 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
08-04 11:57:45.009  2992  3063 E bt-btif : cmd socket is not created
,08-04 11:57:45.009  2992  3167 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-04 11:57:45.009  2992  3167 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-04 11:57:45.009  2992  3169 D bt_vendor: op for 7
08-04 11:57:45.009  2992  3169 D bt_upio : BT_WAKE is asserted already
08-04 11:57:45.009  2992  3167 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 11:57:45.009  2992  3167 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 11:57:45.009  2992  3167 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-04 11:57:45.009  2992  3063 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-04 11:57:45.009   298  1055 D CommandListener: Clearing all IP addresses on wlan0
,08-04 11:57:45.009  2992  3169 D bt_vendor: op for 7
08-04 11:57:45.009  2992  3169 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:45.019  2992  3169 D bt_vendor: op for 7
08-04 11:57:45.019  2992  3169 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:45.019  2992  3169 D bt_vendor: op for 7
08-04 11:57:45.019  2992  3169 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:45.019  2992  3169 D bt_vendor: op for 7
08-04 11:57:45.019  2992  3169 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:45.019  2992  3169 D bt_vendor: op for 7
08-04 11:57:45.019  2992  3169 D bt_upio : BT_WAKE is asserted already
08-04 11:57:45.019  2992  3169 D bt_vendor: op for 7
08-04 11:57:45.019  2992  3169 D bt_upio : BT_WAKE is asserted already
08-04 11:57:45.019  2992  3169 D bt_vendor: op for 7
08-04 11:57:45.019  2992  3169 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:45.019  2992  3169 D bt_vendor: op for 7
08-04 11:57:45.019  2992  3169 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:45.029  2992  3169 D bt_vendor: op for 7
08-04 11:57:45.029  2992  3169 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:45.029  1864  5038 V NativeCrypto: Read error: ssl=0x9b669e00: I/O error during system call, Connection timed out
08-04 11:57:45.029  2992  3169 D bt_vendor: op for 7
08-04 11:57:45.029  2992  3169 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:45.029  2992  3169 D bt_vendor: op for 7
,08-04 11:57:45.029  2992  3169 D bt_upio : BT_WAKE is asserted already
08-04 11:57:45.029   765  1330 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:45.029  1864  5038 V NativeCrypto: SSL shutdown failed: ssl=0x9b669e00: I/O error during system call, Broken pipe
,08-04 11:57:45.029  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:45.029   765  1238 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:45.029   765  1703 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:45.039  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:45.039  1195  1195 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-04 11:57:45.039  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-04 11:57:45.039  1864  5038 E GCM     : Wifi connection closed with errorCode 20
,08-04 11:57:45.039   765  1232 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:45.039   765  3205 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
,08-04 11:57:45.039   765  1767 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:45.039   765  1767 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:45.039   765  1767 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-04 11:57:45.039   765  1767 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:45.039   765  1767 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,08-04 11:57:45.039   765  1767 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-04 11:57:45.039   765  1767 I qtaguid : Tagging socket 397 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 765, getuid(): 1000
,08-04 11:57:45.039   765  1330 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:45.039   765  1151 E ConnectivityService: updateNetworkInfo()
08-04 11:57:45.039   765  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-04 11:57:45.039   765  1151 E ConnectivityService: updateNetworkInfo()
08-04 11:57:45.049   765  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
,08-04 11:57:45.049   765  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,08-04 11:57:45.049   765  1767 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-04 11:57:45.049   765  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:45.049   765  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 11:57:45.049   765   765 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-04 11:57:45.049   765  1330 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:45.049   765  1232 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:45.049  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 11:57:45.049  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-04 11:57:45.049  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,08-04 11:57:45.049  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:57:45.049  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:57:45.049  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:57:45.049  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,08-04 11:57:45.049  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:57:45.049  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:57:45.049  1195  1195 D StatusBar.NetworkController: applyOpen
,08-04 11:57:45.059   765  1148 D WifiP2pService: InactiveState{ what=131204 }
,08-04 11:57:45.059   765  1148 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-04 11:57:45.059   765  1148 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-04 11:57:45.059   765   765 D WifiScanningService: SCAN_AVAILABLE : 1
,08-04 11:57:45.059   765   765 D RttService: SCAN_AVAILABLE : 1
08-04 11:57:45.059   765  1166 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:45.059   765  1149 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-04 11:57:45.059   765  1167 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-04 11:57:45.059   765  1148 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-04 11:57:45.059   765   765 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-04 11:57:45.069   765  1060 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:45.069   765  1060 D WifiDisplayAdapter: onP2pDisconnected
08-04 11:57:45.069   765  1060 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-04 11:57:45.069   765  1060 D IpRemoteDisplayController: WfdBridgeServer is already null
08-04 11:57:45.069   765  1060 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-04 11:57:45.069   765  1060 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-04 11:57:45.069   765  1060 D WifiDisplayController: disconnect
08-04 11:57:45.069   765  1060 D WifiDisplayController: updateConnection
08-04 11:57:45.069   765  1060 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-04 11:57:45.069   765  1060 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-04 11:57:45.069   765  1060 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-04 11:57:45.069   765  1060 D WifiDisplayAdapter: onP2pDisconnected
08-04 11:57:45.069   765  1060 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-04 11:57:45.069   765  1060 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-04 11:57:45.069   765  1148 D WifiP2pService: P2pDisablingState
08-04 11:57:45.069   765  1148 D WifiP2pService: P2pDisablingState{ what=147458 }
08-04 11:57:45.069   765  1148 D WifiP2pService: p2p socket connection lost
08-04 11:57:45.069   765  1148 D WifiP2pService: P2pDisabledState
,08-04 11:57:45.069  1195  1195 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-04 11:57:45.069   765  1449 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-04 11:57:45.069  1195  1195 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-04 11:57:45.079   765  1149 E native  : do suspend true
,08-04 11:57:45.079  1321  1321 D DockEventReceiver: finishStartingService: stopping service
,08-04 11:57:45.089   765  1148 D WifiP2pService: P2pDisabledState{ what=143375 }
08-04 11:57:45.089  1321  1321 D BluetoothNotiBroadcastReceiver: onReceive
,08-04 11:57:45.089   765  1148 D WifiP2pService: DefaultState{ what=143375 }
,08-04 11:57:45.089  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-04 11:57:45.089  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 11:57:45.089   765  1352 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,08-04 11:57:45.089   765  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:45.089   765  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:45.089   765  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:45.089   765  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:45.099   765  1573 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:45.129   298  1055 D CommandListener: Clearing all IP addresses on wlan0
08-04 11:57:45.129   765  1151 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-04 11:57:45.129   765  1767 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-04 11:57:45.129   765  1151 D ConnectivityService: calling update connectivity
08-04 11:57:45.129   765  1059 D EntConnectivity: Not allowed due to - mEnabled false
08-04 11:57:45.129   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:45.129   765  1767 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-04 11:57:45.129   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:57:45.129  1195  1599 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-04 11:57:45.129   765  1151 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:57:45.129   765  1767 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:45.129   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:45.129   765  1767 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:45.129   765  1151 D ConnectivityService: sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:45.129   765  1767 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-04 11:57:45.129   765  1151 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
08-04 11:57:45.129  1428  1428 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:45.129   765  1151 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:45.129   765  1151 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:57:45.129   765  1151 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-04 11:57:45.129   765  1151 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-04 11:57:45.129   765  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-04 11:57:45.129  2540  3150 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,08-04 11:57:45.139  7573  7573 E Zygote  : MountEmulatedStorage()
,08-04 11:57:45.139  7573  7573 E Zygote  : v2
08-04 11:57:45.139  7573  7573 I libpersona: KNOX_SDCARD checking this for 10140
08-04 11:57:45.139  7573  7573 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:45.139   765  1352 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7573 uid=10140 gids={50140, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-04 11:57:45.149  7573  7573 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:45.149  7573  7573 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 11:57:45.149  1281  1281 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-04 11:57:45.149   765  1151 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:45.149   765  1151 E ConnectivityService: updateNetworkInfo()
08-04 11:57:45.149   765  1151 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 11:57:45.149   765  1151 E ConnectivityService: updateNetworkInfo()
08-04 11:57:45.149   765  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
08-04 11:57:45.149   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:57:45.149   765  1146 V NetworkStats: updateIfacesLocked()
08-04 11:57:45.149   765   765 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-04 11:57:45.149   765  1146 V NetworkStats: performPollLocked(flags=0x1)
08-04 11:57:45.149  7573  7573 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
08-04 11:57:45.149   765  1151 E ConnectivityService: EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-04 11:57:45.149   765  1146 D NetworkStatsFactory: UpdateStatsForKnox
08-04 11:57:45.149   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-04 11:57:45.149   765  1152 D Tethering: MasterInitialState.processMessage what=3
08-04 11:57:45.149   765  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:45.149   765  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
08-04 11:57:45.149   765  1153 D SmartBondingService: getSBEnabled() enabled =false
08-04 11:57:45.149   765  1153 D SmartBondingService: getSBEnabled() enabled =false
08-04 11:57:45.149   765  1153 D SmartBondingService: getSBEnabled() enabled =false
,08-04 11:57:45.149  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 11:57:45.149  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 11:57:45.149  1195  1195 D StatusBar.NetworkController: getUpdateDataNetType(): 0
,08-04 11:57:45.149   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:57:45.149   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-04 11:57:45.149   765  1149 D SecContentProvider2: mCursor = null
,08-04 11:57:45.159   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 11:57:45.159  7235  7235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:45.159  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:45.159  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:45.159  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:45.159  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 11:57:45.159  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:45.159  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:45.159  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:45.159  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 11:57:45.159  7235  7235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 11:57:45.159  7235  7235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 11:57:45.159   765  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,08-04 11:57:45.159   765  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,08-04 11:57:45.159   765  1146 V NetworkStats: performPollLocked() took 11ms
08-04 11:57:45.159  1195  1195 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-04 11:57:45.159  1195  1195 D StatusBar.NetworkController: updateDataNetType()
08-04 11:57:45.159  1195  1195 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-04 11:57:45.159  1195  1195 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-04 11:57:45.159   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:57:45.159   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:57:45.159   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:57:45.159   765  1147 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-04 11:57:45.159   344   344 I art     : Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 321us total 15.446ms
,08-04 11:57:45.159  7235  7235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:45.159  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:45.159  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:45.159  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:45.159  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 11:57:45.159  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:45.159  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:45.159  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:45.159  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 11:57:45.159  1195  1195 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-04 11:57:45.159  7235  7235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:45.159  1195  1195 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-04 11:57:45.159  7235  7235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 11:57:45.159  1195  1195 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-04 11:57:45.159  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-04 11:57:45.159  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-04 11:57:45.159   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:57:45.159  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:57:45.159  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:57:45.159  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:57:45.159  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:57:45.159  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:57:45.159  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:57:45.159  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:57:45.159  1195  1195 D StatusBar.NetworkController: applyOpen
,08-04 11:57:45.159  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 11:57:45.159  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-04 11:57:45.159  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:57:45.159  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:57:45.159  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,08-04 11:57:45.169  1321  1321 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:57:45.169  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:57:45.169  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:57:45.169  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:57:45.169  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:57:45.169  1195  1195 D StatusBar.NetworkController: applyOpen
,08-04 11:57:45.169  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 11:57:45.169  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-04 11:57:45.169  1195  1604 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-04 11:57:45.169  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:57:45.169  1195  1195 D HotspotTile: onReceive : 0, 0
,08-04 11:57:45.169   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 280us total 9.746ms
,08-04 11:57:45.169   765  1476 I AudioService: getStreamVolume 3 index 0
08-04 11:57:45.169   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:57:45.169   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 11:57:45.179   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 281us total 10.414ms
,08-04 11:57:45.189  7573  7573 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:45.189  7573  7573 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:45.209  1281  1281 I wpa_supplicant: Blacklist: Clear (all) 
,08-04 11:57:45.209  2992  3169 D bt_vendor: op for 6
,08-04 11:57:45.209  2992  3169 D bt_vendor: op for 7
08-04 11:57:45.209  2992  3169 D bt_upio : BT_WAKE is asserted already
08-04 11:57:45.209  2992  3170 D bt_userial: RX termination
08-04 11:57:45.209  2992  3170 W bt_userial: select_read return size <=0:-1, exiting userial_read_thread
08-04 11:57:45.209  2992  3170 D bt_userial: Leaving userial_read_thread()
08-04 11:57:45.209  2992  3074 D bt_userial: userial_close_reader Joined userial reader thread: 0
08-04 11:57:45.209  2992  3167 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 11:57:45.209  2992  3167 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 11:57:45.209  2992  3167 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 11:57:45.209  2992  3167 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 11:57:45.209  2992  3167 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 11:57:45.209  2992  3167 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 11:57:45.209  2992  3167 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 11:57:45.209  2992  3167 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 11:57:45.209  2992  3167 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 11:57:45.209  2992  3167 W bt-btif : ag scb idx 1 not allocated
08-04 11:57:45.209  2992  3167 W bt-btif : ag scb idx 2 not allocated
08-04 11:57:45.209  2992  3167 E bt-btif : BTA AG is already disabled, ignoring ...
08-04 11:57:45.209  2992  3169 D bt_vendor: op for 9
08-04 11:57:45.209  2992  3169 D bt_hwcfg: hw_epilog_process
08-04 11:57:45.209  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-04 11:57:45.209  2992  3074 D bt_vendor: op for 4
08-04 11:57:45.209  2992  3074 I bt_userial_vendor: device fd = 65 close
,08-04 11:57:45.209  7573  7573 D ResourcesManager: creating new AssetManager and set to /system/app/Maps/Maps.apk
,08-04 11:57:45.209  2992  3074 D bt_vendor: op for 0
08-04 11:57:45.209  2992  3074 D bt_upio : upio_set_bluetooth_power(on: 0)
08-04 11:57:45.209  2992  3074 D bt_upio : is_emulator_context : 0
08-04 11:57:45.209  2992  3074 D bt_upio : is_rfkill_disabled ? [0]
,08-04 11:57:45.219  2992  3074 D bt_vendor: cleanup
,08-04 11:57:45.219  2992  3167 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-04 11:57:45.219  1281  1281 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-04 11:57:45.219  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-04 11:57:45.219  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-04 11:57:45.219  2992  3074 I GKI_LINUX: GKI_exit_task 0 done
08-04 11:57:45.219  2992  3074 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-04 11:57:45.219  2992  3063 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-04 11:57:45.219  2992  3063 D BtConfig.SecureMode: isSecureModeOn:false
08-04 11:57:45.219  2992  3063 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-04 11:57:45.219  2992  3063 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-04 11:57:45.219  2992  3063 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-04 11:57:45.219  2992  3063 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-04 11:57:45.219   765  1652 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 11:57:45.219   765  1652 D ActivityManager: caller:android.app.ApplicationThreadProxy@9c9e7b, r.packageName :com.android.bluetooth
08-04 11:57:45.219  2992  3063 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-04 11:57:45.219  2992  3063 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-04 11:57:45.219  2992  2992 D BtGatt.DebugUtils: handleDebugAction() action=null
08-04 11:57:45.219  2992  2992 D BtGatt.GattService: Received stop request...Stopping profile...
08-04 11:57:45.219  2992  2992 D BtGatt.GattService: stop()
08-04 11:57:45.219  2992  2992 D BtGatt.AdvertiseManager: advertise clients cleared
,08-04 11:57:45.229  2992  3063 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-04 11:57:45.229  2992  2992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@186ecf7f
08-04 11:57:45.229  1281  1281 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-04 11:57:45.229  1281  1281 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-04 11:57:45.229   765  1330 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 11:57:45.229  1281  1281 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=0 BSSID=F4.99.3E SSID=4E47373030
08-04 11:57:45.229  1281  1281 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
08-04 11:57:45.229   765  1330 D ActivityManager: caller:android.app.ApplicationThreadProxy@91b2498, r.packageName :com.android.bluetooth
,08-04 11:57:45.229  2992  3063 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-04 11:57:45.229  2992  3063 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-04 11:57:45.229  2992  3063 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-04 11:57:45.229   765  1449 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 11:57:45.229   765  1449 D ActivityManager: caller:android.app.ApplicationThreadProxy@b4514f1, r.packageName :com.android.bluetooth
,08-04 11:57:45.229  2992  3063 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-04 11:57:45.229  2992  3063 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-04 11:57:45.229  2992  3063 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-04 11:57:45.229  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-04 11:57:45.229   765  1263 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 11:57:45.229   765  1263 D ActivityManager: caller:android.app.ApplicationThreadProxy@3c3188d6, r.packageName :com.android.bluetooth
,08-04 11:57:45.229  2992  3063 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-04 11:57:45.229  2992  3063 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-04 11:57:45.229  2992  3063 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-04 11:57:45.229   765   785 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 11:57:45.229   765   785 D ActivityManager: caller:android.app.ApplicationThreadProxy@244ca757, r.packageName :com.android.bluetooth
,08-04 11:57:45.229  2992  3063 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-04 11:57:45.229  2992  3063 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-04 11:57:45.229  2992  3063 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-04 11:57:45.229   765  1703 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 11:57:45.229  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-04 11:57:45.229   765  1703 D ActivityManager: caller:android.app.ApplicationThreadProxy@13e9f244, r.packageName :com.android.bluetooth
,08-04 11:57:45.229  2992  3063 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-04 11:57:45.239  2992  3063 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-04 11:57:45.239  2992  3063 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-04 11:57:45.239   765  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 11:57:45.239   765  1476 D ActivityManager: caller:android.app.ApplicationThreadProxy@27050f2d, r.packageName :com.android.bluetooth
,08-04 11:57:45.239  2992  3063 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-04 11:57:45.239  2992  3063 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-04 11:57:45.239  2992  3063 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-04 11:57:45.239   765  1680 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 11:57:45.239   765  1680 D ActivityManager: caller:android.app.ApplicationThreadProxy@11955c62, r.packageName :com.android.bluetooth
08-04 11:57:45.239  2992  3063 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-04 11:57:45.239  2992  3063 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-04 11:57:45.239  2992  3063 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-04 11:57:45.239  2992  3063 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-04 11:57:45.239  2992  3063 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-04 11:57:45.239  2992  3063 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-04 11:57:45.239  2992  3063 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-04 11:57:45.239  2992  3063 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-04 11:57:45.239  2992  3063 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-04 11:57:45.239  2992  3063 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-04 11:57:45.239  2992  3063 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-04 11:57:45.239  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-04 11:57:45.239  2992  3063 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-04 11:57:45.239  2992  3063 D BluetoothAdapterState: Stopping profile services that were post enabled
08-04 11:57:45.239  2992  2992 E BluetoothAdapterService(409915263): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,08-04 11:57:45.239  2992  2992 D HeadsetService: Received stop request...Stopping profile...
08-04 11:57:45.239  2992  2992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@186ecf7f
,08-04 11:57:45.239  1321  1321 D HeadsetProfile: Bluetooth service disconnected
,08-04 11:57:45.239   765   765 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-04 11:57:45.239  2992  2992 D A2dpService: Received stop request...Stopping profile...
08-04 11:57:45.239  2992  3088 D A2dpStateMachine: Exit Disconnected: -1
08-04 11:57:45.239  2992  2992 V Avrcp   : doQuit
,08-04 11:57:45.239  2992  2992 D Avrcp   : Unregistering previous receiver
,08-04 11:57:45.239  2992  2992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@186ecf7f
,08-04 11:57:45.239   765   765 D BluetoothA2dp: Proxy object disconnected
08-04 11:57:45.239   765   765 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-04 11:57:45.249  2992  2992 D HidService: Received stop request...Stopping profile...
08-04 11:57:45.249  3222  3222 D BluetoothA2dp: Proxy object disconnected
,08-04 11:57:45.249  2992  2992 D HidService: Stopping Bluetooth HidService
08-04 11:57:45.249  2992  2992 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-04 11:57:45.249  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-04 11:57:45.249  2992  2992 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-04 11:57:45.249  2992  2992 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,08-04 11:57:45.249  2992  2992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@186ecf7f
08-04 11:57:45.249  1321  1321 D BluetoothA2dp: Proxy object disconnected
08-04 11:57:45.249  1321  1321 D A2dpProfile: Bluetooth service disconnected
,08-04 11:57:45.249  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-04 11:57:45.249  2992  2992 D HealthService: Received stop request...Stopping profile...
08-04 11:57:45.249  2992  2992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@186ecf7f
,08-04 11:57:45.249  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-04 11:57:45.249  1321  1321 D BluetoothInputDevice: Proxy object disconnected
08-04 11:57:45.249  2992  2992 D PanService: Received stop request...Stopping profile...
08-04 11:57:45.249  2992  2992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@186ecf7f
08-04 11:57:45.249  1321  1321 D HidProfile: Bluetooth service disconnected
08-04 11:57:45.249  1321  1321 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-04 11:57:45.249  1321  1321 D PanProfile: Bluetooth service disconnected
08-04 11:57:45.249   765   765 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-04 11:57:45.249  2992  2992 D BluetoothMapService: Received stop request...Stopping profile...
,08-04 11:57:45.249  2992  2992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@186ecf7f
,08-04 11:57:45.249  2992  2992 D SapService: Received stop request...Stopping profile...
08-04 11:57:45.249  2992  2992 D SapService: Stopping Bluetooth SapService
08-04 11:57:45.249  2992  2992 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@186ecf7f
,08-04 11:57:45.249  2992  2992 E BluetoothAdapterService(409915263): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-04 11:57:45.249  2992  2992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-04 11:57:45.249  2992  2992 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-04 11:57:45.249  1321  1321 D BluetoothMap: Proxy object disconnected
08-04 11:57:45.259  1321  1321 D MapProfile: Bluetooth service disconnected
,08-04 11:57:45.259  2992  2992 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-04 11:57:45.259  2992  2992 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 11:57:45.259  2992  2992 E BluetoothAdapterService(409915263): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-04 11:57:45.259  2992  2992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-04 11:57:45.259  2992  2992 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-04 11:57:45.259  2992  2992 D BluetoothA2dp: Proxy object disconnected
08-04 11:57:45.259  2992  2992 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-04 11:57:45.259  2992  3089 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-04 11:57:45.259  1321  1321 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-04 11:57:45.259  1321  1321 D SapProfile: Bluetooth service disconnected
08-04 11:57:45.259  2992  2992 I GKI_LINUX: GKI_exit_task 2 done
08-04 11:57:45.259  2992  2992 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-04 11:57:45.259  2992  2992 V Avrcp   : cleanup
,08-04 11:57:45.259  2992  2992 E BluetoothAdapterService(409915263): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-04 11:57:45.259  2992  2992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-04 11:57:45.259  2992  2992 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-04 11:57:45.259  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-04 11:57:45.259  2992  2992 E BluetoothAdapterService(409915263): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-04 11:57:45.259  2992  2992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-04 11:57:45.259  2992  2992 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-04 11:57:45.259  2992  2992 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-04 11:57:45.259  2992  2992 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-04 11:57:45.259  2992  2992 E BluetoothAdapterService(409915263): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-04 11:57:45.259  2992  2992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-04 11:57:45.259  2992  2992 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-04 11:57:45.259  2992  2992 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-04 11:57:45.259  2992  2992 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-04 11:57:45.259  2992  2992 E BluetoothAdapterService(409915263): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-04 11:57:45.259  2992  2992 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-04 11:57:45.259  2992  2992 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-04 11:57:45.259  2992  2992 E BluetoothAdapterService(409915263): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-04 11:57:45.259  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-04 11:57:45.259  2992  3063 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-04 11:57:45.259  2992  3063 D BluetoothAdapterProperties: Setting state to 10
08-04 11:57:45.259  2992  3063 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-04 11:57:45.259  2992  3063 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-04 11:57:45.259  2992  3063 D BluetoothAdapterService: updateAdapterState state is 10
08-04 11:57:45.259  2992  2992 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-04 11:57:45.259  2992  2992 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,08-04 11:57:45.259  2992  3063 D BluetoothAdapterService: Autoconnection is available 
08-04 11:57:45.259  2992  3063 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-04 11:57:45.259  2992  3063 I BluetoothAdapterState: Entering OffState
,08-04 11:57:45.259  2992  3404 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-04 11:57:45.259  1321  1373 D BluetoothMap: onBluetoothStateChange: up=false
08-04 11:57:45.259  1321  1337 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-04 11:57:45.259  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-04 11:57:45.259  3222  3239 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 11:57:45.259   765  1059 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 11:57:45.259  1321  1361 D BluetoothPbap: onBluetoothStateChange: up=false
,08-04 11:57:45.259  1321  1373 D Bluetoothsap: onBluetoothStateChange: up=false
08-04 11:57:45.259  1321  1373 D Bluetoothsap: Unbinding service...
,08-04 11:57:45.259  1321  1361 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-04 11:57:45.269   765  1059 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 12 receivers.
,08-04 11:57:45.269   765  1059 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-04 11:57:45.269  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-04 11:57:45.269  2992  3074 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-04 11:57:45.269  1195  1195 D BluetoothAdapter: 297313051: getState() :  mService = null. Returning STATE_OFF
08-04 11:57:45.269   765   765 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:45.269   765   765 I InputMethodManagerService: [BT Setting State] State =10
08-04 11:57:45.269   765   765 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-04 11:57:45.269  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-04 11:57:45.279  1864  2360 D BluetoothAdapter: 1072597014: getState() :  mService = null. Returning STATE_OFF
08-04 11:57:45.279  1864  2360 D BluetoothAdapter: 1072597014: getState() :  mService = null. Returning STATE_OFF
08-04 11:57:45.279  1195  1604 D BluetoothAdapter: 297313051: getState() :  mService = null. Returning STATE_OFF
,08-04 11:57:45.279   765  1330 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-04 11:57:45.279  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:45.279  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:45.279   765  1330 D ActivityManager: caller:android.app.ApplicationThreadProxy@148a61f3, r.packageName :com.google.android.gms
08-04 11:57:45.279  1195  1195 D BluetoothAdapter: 297313051: getState() :  mService = null. Returning STATE_OFF
,08-04 11:57:45.279  1195  1604 D BluetoothAdapter: 297313051: getState() :  mService = null. Returning STATE_OFF
08-04 11:57:45.279  1195  1604 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-04 11:57:45.279  1195  1195 D BluetoothAdapter: 297313051: getState() :  mService = null. Returning STATE_OFF
08-04 11:57:45.279  1321  1321 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:45.279   765  1238 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
08-04 11:57:45.279  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:45.279   765  1263 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-04 11:57:45.279  1750  1750 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-04 11:57:45.279  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,08-04 11:57:45.279  2992  2992 I GKI_LINUX: GKI_exit_task 1 done
08-04 11:57:45.279  2992  2992 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-04 11:57:45.279  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-04 11:57:45.279  2992  2992 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-04 11:57:45.289  2992  2992 I art     : System.exit called, status: 0
,08-04 11:57:45.289  2992  2992 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-04 11:57:45.299  1281  1281 I wpa_supplicant: Blacklist: Clear (all) 
,08-04 11:57:45.329   765  1330 I ActivityManager: Process com.android.bluetooth (pid 2992)(adj 0) has died(181,1574)
,08-04 11:57:45.429  7235  7235 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-04 11:57:45.429   765  1680 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,08-04 11:57:45.429  1864  1864 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-04 11:57:45.439  1864  1864 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-04 11:57:45.449  1281  1281 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-04 11:57:45.449   765  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-04 11:57:45.449   765  1149 D WifiNative-HAL: callSECApiBoolean - ID [21]
08-04 11:57:45.459   765  1152 D Tethering: InitialState.processMessage what=4
,08-04 11:57:45.459   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:57:45.459  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 11:57:45.459  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-04 11:57:45.459  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:57:45.459   765  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
08-04 11:57:45.459   765  1152 E Tethering: No numeric data
,08-04 11:57:45.459  1864  2360 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 11:57:45.459  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-04 11:57:45.459  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:57:45.459  1195  1604 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-04 11:57:45.459   765  1152 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-04 11:57:45.459  1195  1195 D HotspotTile: onReceive : 1, 0
,08-04 11:57:45.459  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:45.459  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:45.459   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:57:45.459   765  1146 V NetworkStats: performPollLocked(flags=0x1)
,08-04 11:57:45.459   765  1146 D NetworkStatsFactory: UpdateStatsForKnox
08-04 11:57:45.459  1195  1195 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-04 11:57:45.459   765  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:45.469  1195  1195 D HotspotTile: updateTetherState():false, false
08-04 11:57:45.469  1321  1321 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:57:45.469   765  1146 V NetworkStats: performPollLocked() took 4ms
08-04 11:57:45.469   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 11:57:45.469   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:57:45.469   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 11:57:45.479  7573  7573 D StrictMode: StrictMode policy violation; ~duration=183 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-04 11:57:45.479  7573  7573 D StrictMode: StrictMode policy violation; ~duration=174 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-04 11:57:45.479  7573  7573 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.io.File.exists(File.java:363)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1319)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityTh,read.main(ActivityThread.java:5938)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-04 11:57:45.479  7573  7573 D StrictMode: StrictMode policy violation; ~duration=132 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-04 11:57:45.479  7573  7573 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-04 11:57:45.479  7573  7573 D StrictMode: StrictMode policy violation; ~duration=130 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.r.e.b(PG:170)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-04 11:57:45.479  7573  7573 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.r.k.b(PG:14147)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.r.k.c(PG:583)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.r.e.b(PG:170)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-04 11:57:45.479  7573  7573 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.io.File.exists(File.java:363)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1485)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 11:57:45.479  7573  7573 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-04 11:57:45.489   765  1263 I ActivityManager: Killing 6672:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): emptyCount ##41
08-04 11:57:45.489  1864  1864 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-04 11:57:45.489  1864  1864 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-04 11:57:45.489   765  1238 D ActivityManager: startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
08-04 11:57:45.489   765  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:45.489   765  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:45.489   765  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:45.489   765  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:45.529  7573  7614 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-04 11:57:45.529  7620  7620 E Zygote  : MountEmulatedStorage()
08-04 11:57:45.529  7620  7620 E Zygote  : v2
08-04 11:57:45.529  7620  7620 I libpersona: KNOX_SDCARD checking this for 10038
08-04 11:57:45.529  7620  7620 I libpersona: KNOX_SDCARD not a persona
08-04 11:57:45.539   765  1238 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7620 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-04 11:57:45.549  7620  7620 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:45.549  7620  7620 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 11:57:45.549  7620  7620 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-04 11:57:45.569  7620  7620 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:45.569  7620  7620 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:45.589  7620  7620 D ResourcesManager: creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,08-04 11:57:45.589  7620  7620 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,08-04 11:57:45.609  1864  2847 I art     : Explicit concurrent mark sweep GC freed 61754(3MB) AllocSpace objects, 57(2MB) LOS objects, 40% free, 23MB/38MB, paused 656us total 49.400ms
,08-04 11:57:45.649   765  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:57:45.649   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:45.649   765   765 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:45.649   765  1003 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-04 11:57:45.649   765   765 I ApplicationPolicy: updateDataUsageMap
08-04 11:57:45.649   765  1003 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:45.649   765  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
08-04 11:57:45.649   765  1153 D SmartBondingService: getSBEnabled() enabled =false
08-04 11:57:45.649   765  1153 D SmartBondingService: getSBEnabled() enabled =false
08-04 11:57:45.649   765  1153 D SmartBondingService: getSBEnabled() enabled =false
,08-04 11:57:45.649   765  1493 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:45.649   765  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
08-04 11:57:45.649  1498  1498 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,08-04 11:57:45.659   765  1703 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:45.659  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:45.659  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:45.669   765  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-04 11:57:45.719  7620  7620 I VlingoApplication: VlingoApplication appVersion ='11.2.2.0.37791', ro.csc.sales_code=XEO
,08-04 11:57:45.789  7620  7620 D BluetoothAdapter: 926136393: getState() :  mService = null. Returning STATE_OFF
,08-04 11:57:45.789  7620  7620 D BluetoothAdapter: 926136393: getState() :  mService = null. Returning STATE_OFF
08-04 11:57:45.789  7620  7620 D BluetoothAdapter: 926136393: getState() :  mService = null. Returning STATE_OFF
,08-04 11:57:45.789  7620  7620 D BluetoothAdapter: 926136393: getState() :  mService = null. Returning STATE_OFF
08-04 11:57:45.789  7620  7620 D BluetoothAdapter: 926136393: getState() :  mService = null. Returning STATE_OFF
08-04 11:57:45.789  7620  7620 D BluetoothAdapter: 926136393: getState() :  mService = null. Returning STATE_OFF
,08-04 11:57:45.839  7620  7620 E BluetoothHeadset: BTStateChangeCB is registed
,08-04 11:57:45.839   765  1449 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 11:57:45.839  7620  7620 E BluetoothHeadset: BluetoothHeadset service is binded
,08-04 11:57:45.849   765  1680 I ActivityManager: Killing 6742:com.sec.android.provider.badge/u0a92 (adj 15): emptyCount ##41
,08-04 11:57:45.849  1321  1321 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-04 11:57:45.849  1321  1321 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-04 11:57:45.849   765  1352 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:45.849  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-04 11:57:45.849   765  1476 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-04 11:57:45.849  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-04 11:57:45.849  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-04 11:57:45.849  1321  1321 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-04 11:57:45.849  1321  2802 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-04 11:57:45.859   765   785 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:45.859  6901  6901 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-04 11:57:45.869   765  1330 D SettingsProvider: name = driving_mode_on
08-04 11:57:45.869   765  1330 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:57:45.869   765  1330 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:57:45.869   765  1330 D SettingsProvider: selectionArgs: false
08-04 11:57:45.869   765  1330 D SettingsProvider: selectionArgs: 10038
08-04 11:57:45.869   765  1330 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:57:45.869   765  1330 D SettingsProvider: ret = -1
,08-04 11:57:45.869   765  1330 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-04 11:57:45.869   765  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:45.869   765  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:45.869   765  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:45.869   765  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:45.869  7620  7620 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,08-04 11:57:45.909  7647  7647 E Zygote  : MountEmulatedStorage()
08-04 11:57:45.909  7647  7647 I libpersona: KNOX_SDCARD checking this for 10131
08-04 11:57:45.909  7647  7647 E Zygote  : v2
08-04 11:57:45.909  7647  7647 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:45.919  7647  7647 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:45.919  7647  7647 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 11:57:45.919  7647  7647 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-04 11:57:45.919   765  1330 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7647 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-04 11:57:45.939  7647  7647 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:45.939  7647  7647 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:45.949  7647  7647 D ResourcesManager: creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,08-04 11:57:45.959  7647  7647 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-04 11:57:46.129  7647  7647 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,08-04 11:57:46.129  7647  7670 I Babel   : MmsConfig: mnc/mcc: 0/0
08-04 11:57:46.129  7647  7670 I Babel   : MmsConfig.loadMmsSettings
,08-04 11:57:46.129  7647  7670 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
08-04 11:57:46.129  7647  7670 I Babel   : MmsConfig.loadFromDatabase
,08-04 11:57:46.139  7647  7670 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-04 11:57:46.139  7647  7670 I Babel   : MmsConfig.loadFromResources
,08-04 11:57:46.149  7647  7670 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,08-04 11:57:46.149   765   785 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-04 11:57:46.149  7647  7670 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
,08-04 11:57:46.149  7647  7647 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 11:57:46.179  7647  7647 I Babel_StickerModule: App launched.
,08-04 11:57:46.179  1321  1321 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-04 11:57:46.179  1321  1321 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-04 11:57:46.179   765  1232 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:46.179  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-04 11:57:46.179   765   784 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-04 11:57:46.179  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-04 11:57:46.179  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-04 11:57:46.179  1321  1321 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-04 11:57:46.179  1321  2802 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-04 11:57:46.189  6992  6992 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-04 11:57:46.189   765  1493 D ActivityManager: startProcessLocked calleePkgName: com.samsung.shareshot, hostingType: broadcast
,08-04 11:57:46.199   765  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:46.199   765  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:46.199   765  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:46.199   765  1493 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:46.199   309  1530 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,08-04 11:57:46.199   309  1530 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
08-04 11:57:46.199   309  1530 W QCamera2Factory: getCameraInfo: X
,08-04 11:57:46.199   309   781 W QCamera2Factory: getCameraInfo: E, camera_id = 1
08-04 11:57:46.199   309   781 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
,08-04 11:57:46.199   309   781 W QCamera2HWI: __dbg: info->orientation : 270 rc = 0
08-04 11:57:46.199   309   781 W QCamera2Factory: getCameraInfo: X
,08-04 11:57:46.219  7647  7647 W AudioCapabilities: Unsupported mime audio/evrc
,08-04 11:57:46.219  7647  7647 W AudioCapabilities: Unsupported mime audio/qcelp
,08-04 11:57:46.219  7647  7647 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-04 11:57:46.229   765  1493 I ActivityManager: Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=7675 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-04 11:57:46.239  7675  7675 E Zygote  : MountEmulatedStorage()
,08-04 11:57:46.239  7675  7675 E Zygote  : v2
08-04 11:57:46.239  7675  7675 I libpersona: KNOX_SDCARD checking this for 10192
08-04 11:57:46.239  7675  7675 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:46.269  7675  7675 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:46.269  7675  7675 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 11:57:46.269  7675  7675 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 11:57:46.269  7647  7647 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,08-04 11:57:46.269  7647  7647 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,08-04 11:57:46.269  7647  7647 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-04 11:57:46.269  7647  7647 W AudioCapabilities: Unsupported mime audio/x-ima
,08-04 11:57:46.279  7647  7647 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-04 11:57:46.279  7647  7647 W AudioCapabilities: Unsupported mime audio/qcelp
,08-04 11:57:46.279  7647  7647 W AudioCapabilities: Unsupported mime audio/evrc
,08-04 11:57:46.289  7675  7675 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:46.289  7675  7675 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:46.299  7647  7647 W VideoCapabilities: Unsupported mime video/wvc1
,08-04 11:57:46.299  7647  7647 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-04 11:57:46.309  7675  7675 D ResourcesManager: creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,08-04 11:57:46.309  7647  7647 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-04 11:57:46.309  7647  7647 W VideoCapabilities: Unsupported mime video/wvc1
,08-04 11:57:46.309  7647  7647 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-04 11:57:46.309  7647  7647 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-04 11:57:46.319  7647  7647 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-04 11:57:46.319  7647  7647 W VideoCapabilities: Unsupported mime video/mp43
,08-04 11:57:46.319  7647  7647 W VideoCapabilities: Unsupported mime video/sorenson
,08-04 11:57:46.319  7647  7647 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-04 11:57:46.329  7675  7675 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-04 11:57:46.339  7675  7675 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,08-04 11:57:46.339  7675  7675 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,08-04 11:57:46.339  7675  7675 D WifiDirectBR: stopServiceTest : false
,08-04 11:57:46.339  7647  7647 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-04 11:57:46.349  7675  7675 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,08-04 11:57:46.349   765  1703 I ActivityManager: Killing 6758:com.sec.android.app.soundalive/u0a64 (adj 15): emptyCount ##41
,08-04 11:57:46.359  1321  1321 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-04 11:57:46.359  1321  1321 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-04 11:57:46.359   765  1476 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:46.359  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-04 11:57:46.359   765  1232 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-04 11:57:46.359  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-04 11:57:46.359  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-04 11:57:46.359  1321  1321 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-04 11:57:46.359  1321  2802 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-04 11:57:46.359   765   784 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:46.359  6901  6901 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-04 11:57:46.379  6901  6901 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-04 11:57:46.379   765  1238 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:46.379  7299  7299 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-04 11:57:46.379  7299  7299 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-04 11:57:46.379  7299  7299 D SecurityLogAgent: StateMachine : Current State = 1
,08-04 11:57:46.379  7299  7299 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-04 11:57:46.389  1321  1321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 11:57:46.389   765  1680 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-04 11:57:46.389   765  1680 D ActivityManager: caller:android.app.ApplicationThreadProxy@1a73cd4, r.packageName :com.android.settings
,08-04 11:57:46.399   765  1263 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,08-04 11:57:46.399  1321  1321 D DockEventReceiver: finishStartingService: stopping service
,08-04 11:57:46.399  1321  1321 D BluetoothNotiBroadcastReceiver: onReceive
,08-04 11:57:46.399   765  1352 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,08-04 11:57:46.399   765  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:46.399   765  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:46.399   765  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:46.399   765  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:46.459   765  1329 E Watchdog: !@Sync 6
,08-04 11:57:46.489  7704  7704 E Zygote  : MountEmulatedStorage()
,08-04 11:57:46.489  7704  7704 E Zygote  : v2
08-04 11:57:46.489  7704  7704 I libpersona: KNOX_SDCARD checking this for 1002
08-04 11:57:46.489  7704  7704 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:46.489   765  1352 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7704 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-04 11:57:46.499  7704  7704 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:46.499   765   785 I ActivityManager: Killing 6785:com.wsomacp/u0a29 (adj 15): emptyCount ##41
08-04 11:57:46.499  7704  7704 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 11:57:46.499  7704  7704 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 11:57:46.519  7704  7704 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:46.519  7704  7704 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:46.539  7704  7704 D ResourcesManager: creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,08-04 11:57:46.539  7704  7704 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-04 11:57:46.539  7704  7704 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-04 11:57:46.559  7704  7704 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-04 11:57:46.579  7704  7704 D BtSettings.ProfileConfig: Adding GattService
,08-04 11:57:46.579  7704  7704 D BtSettings.ProfileConfig: Adding HeadsetService
08-04 11:57:46.579  7704  7704 D BtSettings.ProfileConfig: Adding A2dpService
08-04 11:57:46.579  7704  7704 D BtSettings.ProfileConfig: Adding HidService
,08-04 11:57:46.579  7704  7704 D BtSettings.ProfileConfig: Adding HealthService
08-04 11:57:46.589  7704  7704 D BtSettings.ProfileConfig: Adding PanService
08-04 11:57:46.589  7704  7704 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-04 11:57:46.589  7704  7704 D BtSettings.ProfileConfig: Adding SapService
08-04 11:57:46.589  7704  7704 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-04 11:57:46.589  7704  7704 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-04 11:57:46.589  7704  7704 D BtSettings.ProfileConfig: Adding SapClientService
,08-04 11:57:46.589  7704  7704 D BtSettings.ProfileConfig: Adding HidDevService
08-04 11:57:46.589  7704  7704 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-04 11:57:46.589   765  1680 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-04 11:57:46.589   765  1680 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:57:46.589   765  1680 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:57:46.589   765  1680 D SettingsProvider: selectionArgs: false
08-04 11:57:46.589   765  1680 D SettingsProvider: selectionArgs: 1002
08-04 11:57:46.589   765  1680 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-04 11:57:46.589   765  1680 D SettingsProvider: ret = -1
08-04 11:57:46.589   765  1263 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-04 11:57:46.589   765  1263 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:57:46.589   765  1263 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:57:46.589   765  1263 D SettingsProvider: selectionArgs: false
08-04 11:57:46.589   765  1263 D SettingsProvider: selectionArgs: 1002
08-04 11:57:46.589   765  1263 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:57:46.589   765  1263 D SettingsProvider: ret = -1
,08-04 11:57:46.589   765  1238 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-04 11:57:46.589   765  1238 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:57:46.589   765  1238 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:57:46.589   765  1238 D SettingsProvider: selectionArgs: false
08-04 11:57:46.589   765  1238 D SettingsProvider: selectionArgs: 1002
08-04 11:57:46.589   765  1238 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:57:46.589   765  1238 D SettingsProvider: ret = -1
,08-04 11:57:46.589   765  1493 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-04 11:57:46.589   765  1493 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:57:46.589   765  1493 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:57:46.589   765  1493 D SettingsProvider: selectionArgs: false
08-04 11:57:46.589   765  1493 D SettingsProvider: selectionArgs: 1002
08-04 11:57:46.589   765  1493 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:57:46.589   765  1493 D SettingsProvider: ret = -1
,08-04 11:57:46.589   765  1573 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-04 11:57:46.589   765  1573 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:57:46.589   765  1573 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:57:46.589   765  1573 D SettingsProvider: selectionArgs: false
08-04 11:57:46.589   765  1573 D SettingsProvider: selectionArgs: 1002
08-04 11:57:46.589   765  1573 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:57:46.589   765  1573 D SettingsProvider: ret = -1
08-04 11:57:46.589   765  1449 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-04 11:57:46.589   765  1449 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:57:46.589   765  1449 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:57:46.589   765  1449 D SettingsProvider: selectionArgs: false
08-04 11:57:46.589   765  1449 D SettingsProvider: selectionArgs: 1002
08-04 11:57:46.589   765  1449 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:57:46.589   765  1449 D SettingsProvider: ret = -1
08-04 11:57:46.589   765  1652 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-04 11:57:46.589   765  1652 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:57:46.589   765  1652 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:57:46.589   765  1652 D SettingsProvider: selectionArgs: false
08-04 11:57:46.589   765  1652 D SettingsProvider: selectionArgs: 1002
08-04 11:57:46.589   765  1652 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:57:46.589   765  1652 D SettingsProvider: ret = -1
,08-04 11:57:46.589   765  3205 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-04 11:57:46.589   765  3205 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:57:46.589   765  3205 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:57:46.589   765  3205 D SettingsProvider: selectionArgs: false
08-04 11:57:46.589   765  3205 D SettingsProvider: selectionArgs: 1002
08-04 11:57:46.589   765  3205 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:57:46.589   765  3205 D SettingsProvider: ret = -1
,08-04 11:57:46.589   765  1352 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-04 11:57:46.589   765  1352 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:57:46.589   765  1352 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:57:46.589   765  1352 D SettingsProvider: selectionArgs: false
08-04 11:57:46.589   765  1352 D SettingsProvider: selectionArgs: 1002
08-04 11:57:46.589   765  1352 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:57:46.589   765  1352 D SettingsProvider: ret = -1
08-04 11:57:46.589   765  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,08-04 11:57:46.589   765  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:57:46.589   765  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:57:46.589   765  1476 D SettingsProvider: selectionArgs: false
08-04 11:57:46.589   765  1476 D SettingsProvider: selectionArgs: 1002
08-04 11:57:46.589   765  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:57:46.589   765  1476 D SettingsProvider: ret = -1
08-04 11:57:46.589   765   784 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-04 11:57:46.589   765   784 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-04 11:57:46.589   765   784 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:57:46.589   765   784 D SettingsProvider: selectionArgs: false
08-04 11:57:46.589   765   784 D SettingsProvider: selectionArgs: 1002
08-04 11:57:46.589   765   784 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:57:46.589   765   784 D SettingsProvider: ret = -1
08-04 11:57:46.589   765  1703 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-04 11:57:46.589   765  1703 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:57:46.589   765  1703 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-04 11:57:46.589   765  1703 D SettingsProvider: selectionArgs: false
08-04 11:57:46.589   765  1703 D SettingsProvider: selectionArgs: 1002
08-04 11:57:46.589   765  1703 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:57:46.589   765  1703 D SettingsProvider: ret = -1
,08-04 11:57:46.599   765   785 I ActivityManager: Killing 6778:com.samsung.android.app.assistantmenu/1000 (adj 15): emptyCount ##41
,08-04 11:57:46.609  1864  1864 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-04 11:57:46.609   765  1263 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-04 11:57:46.609   765  1263 D ActivityManager: caller:android.app.ApplicationThreadProxy@2ea55240, r.packageName :com.google.android.gms
,08-04 11:57:46.609  1864  7721 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-04 11:57:46.609  1864  1864 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-04 11:57:46.679   303   303 E SMD     : DCD ON
,08-04 11:57:46.699   765  1330 I art     : Explicit concurrent mark sweep GC freed 45495(2MB) AllocSpace objects, 6(144KB) LOS objects, 30% free, 37MB/53MB, paused 1.241ms total 88.590ms
,08-04 11:57:46.709  6901  6901 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-04 11:57:46.709   765  1652 D ActivityManager: caller:android.app.ApplicationThreadProxy@24713035, r.packageName :com.google.android.gms
,08-04 11:57:46.719  1864  7721 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-04 11:57:46.719   765  1352 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:46.719  7299  7299 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-04 11:57:46.719  7299  7299 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-04 11:57:46.719  7299  7299 D SecurityLogAgent: StateMachine : Current State = 1
08-04 11:57:46.719  7299  7299 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-04 11:57:46.729   765  1476 D ActivityManager: startProcessLocked calleePkgName: com.sec.pcw.device, hostingType: broadcast
,08-04 11:57:46.729   765  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:46.729   765  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:46.729   765  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:46.729   765  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:46.769  7722  7722 E Zygote  : MountEmulatedStorage()
08-04 11:57:46.769  7722  7722 E Zygote  : v2
08-04 11:57:46.769  7722  7722 I libpersona: KNOX_SDCARD checking this for 1000
08-04 11:57:46.769  7722  7722 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:46.779  7722  7722 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,08-04 11:57:46.779  7722  7722 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 11:57:46.779  7722  7722 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 11:57:46.779   765  1476 I ActivityManager: Start proc com.sec.pcw.device for broadcast com.sec.pcw.device/.receiver.SYSTEMReceiver: pid=7722 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-04 11:57:46.799  7722  7722 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:46.799  7722  7722 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:46.809  7722  7722 D ResourcesManager: creating new AssetManager and set to /system/priv-app/PCWClientS18/PCWClientS18.apk
,08-04 11:57:46.819  7722  7722 I PCWCLIENTTRACE_LOG: DEFAULT_LOGON : true
08-04 11:57:46.819  7722  7722 I PCWCLIENTTRACE_LOG: DEFAULT_LOGLEVEL : 3
08-04 11:57:46.819  7722  7722 I PCWCLIENTTRACE_DMDBOpenHelper: new DMDBOpenHelper instance
,08-04 11:57:46.829  7722  7722 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-04 11:57:46.829  7722  7722 I PCWCLIENTTRACE_PushUtil: sales region : global
08-04 11:57:46.829  7722  7722 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
,08-04 11:57:46.829  7722  7722 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:57:46.829  7722  7722 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-04 11:57:46.839   765  1476 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,08-04 11:57:46.839   765  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:46.839   765  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:46.839   765  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:46.839   765  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:46.879  7738  7738 E Zygote  : MountEmulatedStorage()
,08-04 11:57:46.879  7738  7738 E Zygote  : v2
08-04 11:57:46.879  7738  7738 I libpersona: KNOX_SDCARD checking this for 10144
08-04 11:57:46.879  7738  7738 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:46.889  7738  7738 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:46.889  7738  7738 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 11:57:46.889  7738  7738 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-04 11:57:46.889   765  1476 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7738 uid=10144 gids={50144, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-04 11:57:46.899  7738  7738 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:46.909  7738  7738 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:46.919  7738  7738 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,08-04 11:57:47.009  7738  7738 I MusicStore: Database version: 108
,08-04 11:57:47.019   765  1476 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-04 11:57:47.089  7738  7738 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,08-04 11:57:47.089  7738  7738 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-04 11:57:47.089  7738  7738 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-04 11:57:47.129  7738  7738 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-04 11:57:47.179  7738  7738 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-04 11:57:47.179  7738  7738 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@38211be3: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
08-04 11:57:47.179  7738  7738 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-04 11:57:47.179  7738  7738 D AndroidMusic: GMSCore installation verified
,08-04 11:57:47.199   765  1263 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-04 11:57:47.209  7738  7738 I ConfigStore: Config Database version: 1
,08-04 11:57:47.249   266   547 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-04 11:57:47.249   266   547 W Vold    : Returning OperationFailed - no handler for errno 0
,08-04 11:57:47.249  7738  7738 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-04 11:57:47.259   266   547 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-04 11:57:47.259   266   547 W Vold    : Returning OperationFailed - no handler for errno 0
,08-04 11:57:47.259  7738  7738 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-04 11:57:47.259   266   547 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-04 11:57:47.259   266   547 W Vold    : Returning OperationFailed - no handler for errno 0
,08-04 11:57:47.259  7738  7738 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-04 11:57:47.259   765   784 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-04 11:57:47.259   765   784 D ActivityManager: caller:android.app.ApplicationThreadProxy@21e02e9c, r.packageName :com.google.android.music
,08-04 11:57:47.269   765  3091 D SSRM:n  : SIOP:: AP = 390, PST = 352, CUR = 450
,08-04 11:57:47.279   765  1263 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-04 11:57:47.289   765  1330 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-04 11:57:47.299   765  1444 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-04 11:57:47.299   765  1449 I AudioService: getStreamVolume 3 index 0
,08-04 11:57:47.299  7738  7738 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,08-04 11:57:47.309  7738  7738 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,08-04 11:57:47.329   765  1232 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-04 11:57:47.329   765  1449 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-04 11:57:47.329   765  1238 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-04 11:57:47.339   765  1476 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-04 11:57:47.339   765   784 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-04 11:57:47.339   765   784 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:47.339   765   784 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:47.339   765   784 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:47.339   765   784 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:47.379  7772  7772 E Zygote  : MountEmulatedStorage()
08-04 11:57:47.379  7772  7772 E Zygote  : v2
08-04 11:57:47.389  7772  7772 I libpersona: KNOX_SDCARD checking this for 10004
08-04 11:57:47.389  7772  7772 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:47.389   765   784 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7772 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-04 11:57:47.399  7772  7772 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:47.399  7772  7772 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 11:57:47.399  7772  7772 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 11:57:47.419   765  1352 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,08-04 11:57:47.429  7738  7738 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,08-04 11:57:47.429   765   784 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-04 11:57:47.429  7772  7772 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:47.429  7772  7772 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:47.439  7772  7772 D ResourcesManager: creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,08-04 11:57:47.459   765  1493 I ActivityManager: Killing 6812:com.google.android.apps.docs/u0a112 (adj 15): emptyCount ##41
,08-04 11:57:47.489   765  1680 I ActivityManager: Killing 6846:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##41
,08-04 11:57:47.489   765  1680 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-04 11:57:47.489   765  1680 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:47.489   765  1680 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:47.489   765  1680 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:47.489   765  1680 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:47.609  7797  7797 E Zygote  : MountEmulatedStorage()
08-04 11:57:47.609  7797  7797 E Zygote  : v2
08-04 11:57:47.609  7797  7797 I libpersona: KNOX_SDCARD checking this for 1000
08-04 11:57:47.609  7797  7797 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:47.619  7797  7797 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,08-04 11:57:47.619  7797  7797 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 11:57:47.619  7797  7797 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 11:57:47.619   765  1680 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7797 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-04 11:57:47.639  7797  7797 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:47.639  7797  7797 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:47.649  7797  7797 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,08-04 11:57:47.679  7797  7797 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,08-04 11:57:47.689  7797  7797 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,08-04 11:57:47.799  7797  7797 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,08-04 11:57:47.809  7797  7797 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,08-04 11:57:47.809  7797  7797 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:57:47.809  7797  7797 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-04 11:57:47.879  7351  7351 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,08-04 11:57:47.889  7351  7351 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,08-04 11:57:47.899  7351  7351 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,08-04 11:57:47.909   765  1573 I ActivityManager: Killing 6868:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): emptyCount ##41
,08-04 11:57:47.909  4014  4014 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-04 11:57:47.909  4014  4014 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1470304667918
,08-04 11:57:47.909  4014  4014 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,08-04 11:57:47.909   765  3205 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:47.909   765  1680 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:47.919  4014  4014 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,08-04 11:57:47.919  4014  4014 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,08-04 11:57:47.919   765  1476 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.pinboard, hostingType: broadcast
,08-04 11:57:47.919   765  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:47.919   765  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:47.919   765  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:47.919   765  1476 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:47.959  7816  7816 E Zygote  : MountEmulatedStorage()
08-04 11:57:47.959  7816  7816 E Zygote  : v2
,08-04 11:57:47.959  7816  7816 I libpersona: KNOX_SDCARD checking this for 10036
08-04 11:57:47.959  7816  7816 I libpersona: KNOX_SDCARD not a persona
08-04 11:57:47.959   765  1476 I ActivityManager: Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7816 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-04 11:57:47.979  7816  7816 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:47.979  7816  7816 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 11:57:47.979  7816  7816 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 11:57:47.989  7235  7294 I WifiManager: packageName : com.test.thalitest
,08-04 11:57:47.989   765  1263 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-04 11:57:47.989   765  1263 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-04 11:57:47.989   765  1263 D SecContentProvider2: mCursor = null
,08-04 11:57:47.989   765  1263 D WifiService: setWifiEnabled: true pid=7235, uid=10079
,08-04 11:57:47.989   765  1263 W ActivityManager: Permission Denial: getCurrentUser() from pid=7235, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-04 11:57:47.989   765  1263 W WifiService: Failed getting userId using ActivityManagerNative
08-04 11:57:47.989   765  1263 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7235, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-04 11:57:47.989   765  1263 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
08-04 11:57:47.989   765  1263 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
08-04 11:57:47.989   765  1263 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
08-04 11:57:47.989   765  1263 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-04 11:57:47.989   765  1263 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-04 11:57:47.989   765  1263 D SettingsProvider: name = wifi_on
,08-04 11:57:47.999   765  1149 E WifiHW  : ##################### set firmware type 0 #####################
,08-04 11:57:47.999   298  1055 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
08-04 11:57:47.999   298  1055 I WifiHW  : module is semco
08-04 11:57:47.999   298  1055 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
08-04 11:57:47.999   298  1055 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
08-04 11:57:47.999   298  1055 E WifiHW  : TEMP_FAILURE_RETRY complete
08-04 11:57:47.999   298  1055 D SoftapController: Softap fwReload - Ok
,08-04 11:57:48.009   298  1055 D CommandListener: Setting iface cfg
08-04 11:57:48.009   298  1055 D CommandListener: Trying to bring down wlan0
,08-04 11:57:48.009   298  1055 D CommandListener: Clearing all IP addresses on wlan0
,08-04 11:57:48.009  7816  7816 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:48.009  7816  7816 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:48.009   765  1149 E WifiHW  : supplicant_name : p2p_supplicant
,08-04 11:57:48.019   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:57:48.019  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-04 11:57:48.019  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-04 11:57:48.019  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 11:57:48.019   765  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,08-04 11:57:48.019  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-04 11:57:48.019  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:48.019  1195  1604 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-04 11:57:48.019  1321  1321 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-04 11:57:48.019  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 11:57:48.019  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:48.019  1195  1195 D HotspotTile: onReceive : 2, 0
08-04 11:57:48.019   765  1149 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-04 11:57:48.029  7816  7816 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,08-04 11:57:48.029  7816  7816 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-04 11:57:48.029  7816  7816 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-04 11:57:48.049  7831  7831 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-04 11:57:48.049  7831  7831 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-04 11:57:48.049  7831  7831 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-04 11:57:48.049  7831  7831 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-04 11:57:48.049   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7831
08-04 11:57:48.049   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-04 11:57:48.049  7831  7831 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-04 11:57:48.049  7831  7831 I wpa_supplicant: ssSupport state is = 1
08-04 11:57:48.049  7831  7831 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,08-04 11:57:48.049  7831  7831 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-04 11:57:48.059   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7831
08-04 11:57:48.059   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,08-04 11:57:48.059  7816  7816 E Minikin : addFont failed to create font /system/fonts/SamsungSans-light.ttf
,08-04 11:57:48.069   765  1444 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:48.069   765  1352 I ActivityManager: Killing 6883:com.samsung.helphub/1000 (adj 15): emptyCount ##41
,08-04 11:57:48.089  7370  7370 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,08-04 11:57:48.089   765  1330 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-04 11:57:48.089   765  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:48.089   765  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:48.089   765  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:48.089   765  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:48.099   765  1703 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:48.099  3600  7843 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-04 11:57:48.109   765   785 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:48.109  3600  7843 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-04 11:57:48.109  3600  7843 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-04 11:57:48.109  3600  7843 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-04 11:57:48.109  3600  7843 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-04 11:57:48.129  7844  7844 E Zygote  : MountEmulatedStorage()
08-04 11:57:48.129  7844  7844 E Zygote  : v2
08-04 11:57:48.129  7844  7844 I libpersona: KNOX_SDCARD checking this for 10043
08-04 11:57:48.129  7844  7844 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:48.139   765  1330 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7844 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-04 11:57:48.169  7844  7844 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:48.169  7844  7844 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 11:57:48.169  7844  7844 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-04 11:57:48.179  7844  7844 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:48.189  7844  7844 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:48.199  7844  7844 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,08-04 11:57:48.229  7844  7844 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-04 11:57:48.229  7844  7844 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-04 11:57:48.229  7844  7844 D SPPClientService: PushLog.txt file is not deleted.
,08-04 11:57:48.229  7844  7844 D SPPClientService: PushLog.txt file is not deleted.
08-04 11:57:48.229  7844  7844 D SPPClientService: ============PushLog. stop!
,08-04 11:57:48.239  7844  7844 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-04 11:57:48.239  6697  6697 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,08-04 11:57:48.239  6697  6697 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,08-04 11:57:48.239   765  1232 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
08-04 11:57:48.239  6697  6697 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
08-04 11:57:48.239   765  1232 D ActivityManager: caller:android.app.ApplicationThreadProxy@dcf2afc, r.packageName :com.sec.spp.push
,08-04 11:57:48.239  6697  6697 I SA      : [SLFUCHKMGR] constructor called
,08-04 11:57:48.249  6697  6697 I SA      : [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
08-04 11:57:48.249  6697  6697 I SA      : [OR] == isSIMCardReady false ==
,08-04 11:57:48.249  6697  6697 I SA      : [SCU] == networkStateCheck == false
,08-04 11:57:48.249  6697  6697 I SA      : [OR] onReceive END
,08-04 11:57:48.249  7844  7861 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-04 11:57:48.249   765  3205 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,08-04 11:57:48.249   765  3205 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:48.249   765  3205 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:48.249   765  3205 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:48.249   765  3205 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:48.289  7863  7863 E Zygote  : MountEmulatedStorage()
08-04 11:57:48.289  7863  7863 E Zygote  : v2
08-04 11:57:48.289  7863  7863 I libpersona: KNOX_SDCARD checking this for 10074
08-04 11:57:48.289  7863  7863 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:48.299   765  3205 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7863 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-04 11:57:48.319   344   344 I art     : Explicit concurrent mark sweep GC freed 8738(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 306us total 12.600ms
,08-04 11:57:48.329   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 311us total 9.621ms
,08-04 11:57:48.329   372   372 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-04 11:57:48.339  7863  7863 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:48.339  7863  7863 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 11:57:48.339  7863  7863 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 11:57:48.339   765   784 I ActivityManager: Killing 6919:com.samsung.android.snote:provider/u0a168 (adj 15): emptyCount ##41
08-04 11:57:48.339   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 270us total 11.980ms
,08-04 11:57:48.359  7863  7863 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:48.359  7863  7863 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:48.369  7863  7863 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,08-04 11:57:48.419  7863  7863 I sCloudBackupApp: sCloudBackupApp Version Info : 3.13.7.KK_APP
,08-04 11:57:48.419  7863  7863 I SCloudBackupReceiver: Other Intent
,08-04 11:57:48.429  7009  7009 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,08-04 11:57:48.429  7009  7009 I KnoxUsageLogPro: premStatus:2
,08-04 11:57:48.429  7009  7009 I KnoxUsageLogPro: isEulaShown : false
08-04 11:57:48.429  7009  7009 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,08-04 11:57:48.439   765  1573 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-04 11:57:48.439   765  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:48.439   765  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:48.439   765  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:48.439   765  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:48.479  7879  7879 E Zygote  : MountEmulatedStorage()
08-04 11:57:48.479  7879  7879 E Zygote  : v2
08-04 11:57:48.479  7879  7879 I libpersona: KNOX_SDCARD checking this for 10104
08-04 11:57:48.479  7879  7879 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:48.489  7879  7879 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,08-04 11:57:48.489  7879  7879 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 11:57:48.489  7879  7879 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-04 11:57:48.489   765  1573 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7879 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-04 11:57:48.489   765  1573 I ActivityManager: Killing 6939:com.sec.kidsplat.installer/u0a189 (adj 15): emptyCount ##41
,08-04 11:57:48.509  7879  7879 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:48.509  7879  7879 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:48.519  7879  7879 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,08-04 11:57:48.579  7831  7831 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,08-04 11:57:48.589   765  1680 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-04 11:57:48.589   765  1680 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:48.589   765  1680 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:48.589   765  1680 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:48.589   765  1680 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:48.629  7831  7831 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-04 11:57:48.629  7831  7831 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-04 11:57:48.629   372   372 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7831
08-04 11:57:48.629   372   372 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-04 11:57:48.629  7831  7831 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-04 11:57:48.629  7831  7831 I wpa_supplicant: ssSupport state is = 1
08-04 11:57:48.629  7831  7831 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-04 11:57:48.629  7831  7831 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-04 11:57:48.629  7831  7831 E wpa_supplicant: SIM READ ERROR
08-04 11:57:48.629  7831  7831 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-04 11:57:48.629  7831  7831 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-04 11:57:48.629  7831  7831 E wpa_supplicant: SIM READ ERROR
08-04 11:57:48.629   765  1680 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7898 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-04 11:57:48.629  7831  7831 I wpa_supplicant: Blacklist: Clear (all) 
08-04 11:57:48.629  7831  7831 I wpa_supplicant: wpa_default_ap_write_once
08-04 11:57:48.629  7831  7831 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-04 11:57:48.629  7831  7831 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-04 11:57:48.629  7831  7831 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-04 11:57:48.629  7831  7831 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-04 11:57:48.629  7831  7831 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-04 11:57:48.629  7831  7831 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-04 11:57:48.629   765  1680 I ActivityManager: Killing 5372:com.sec.android.app.samsungapps/u0a45 (adj 15): emptyCount ##41
,08-04 11:57:48.629  7898  7898 E Zygote  : MountEmulatedStorage()
,08-04 11:57:48.629  7898  7898 E Zygote  : v2
08-04 11:57:48.639  7898  7898 I libpersona: KNOX_SDCARD checking this for 10146
08-04 11:57:48.639  7898  7898 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:48.669  7898  7898 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:48.669  7898  7898 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 11:57:48.669  7898  7898 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-04 11:57:48.689  7898  7898 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:48.689  7898  7898 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:48.709  7898  7898 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,08-04 11:57:48.899   266   547 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-04 11:57:48.899   266   547 W Vold    : Returning OperationFailed - no handler for errno 0
,08-04 11:57:48.899  7898  7916 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-04 11:57:48.899   266   547 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-04 11:57:48.899   266   547 W Vold    : Returning OperationFailed - no handler for errno 0
,08-04 11:57:48.899  7898  7916 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-04 11:57:48.909   266   547 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-04 11:57:48.909   266   547 W Vold    : Returning OperationFailed - no handler for errno 0
,08-04 11:57:48.909  7898  7919 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-04 11:57:48.909   266   547 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-04 11:57:48.909   266   547 W Vold    : Returning OperationFailed - no handler for errno 0
,08-04 11:57:48.909  7898  7919 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-04 11:57:49.069  7898  7898 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,08-04 11:57:49.069  7898  7898 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,08-04 11:57:49.099  7898  7898 I LibraryLoader: Time to load native libraries: 12 ms (timestamps 1738-1750)
,08-04 11:57:49.099  7898  7898 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-04 11:57:49.099  7898  7898 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {25964f8}
,08-04 11:57:49.099  7898  7898 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-04 11:57:49.109  7898  7898 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-04 11:57:49.119  7898  7898 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-04 11:57:49.119  7898  7898 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-04 11:57:49.129  7898  7898 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-04 11:57:49.439   765  1152 E Tethering: No numeric data
,08-04 11:57:49.449   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:57:49.449   765  1146 V NetworkStats: performPollLocked(flags=0x1)
,08-04 11:57:49.449   765  1146 D NetworkStatsFactory: UpdateStatsForKnox
08-04 11:57:49.449   765  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:49.449  1195  1195 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-04 11:57:49.449  1195  1195 D HotspotTile: updateTetherState():false, false
,08-04 11:57:49.449   765  1152 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-04 11:57:49.449   765  1146 V NetworkStats: performPollLocked() took 4ms
08-04 11:57:49.449   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 11:57:49.449  7898  7898 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-04 11:57:49.449   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:57:49.449   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 11:57:49.459  7898  7898 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
08-04 11:57:49.459  7898  7898 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,08-04 11:57:49.459  7898  7898 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
08-04 11:57:49.459  7898  7898 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
08-04 11:57:49.459  7898  7898 I Adreno-EGL: Build Date: 11/19/14 Wed
08-04 11:57:49.459  7898  7898 I Adreno-EGL: Local Branch: mybranch5813579
08-04 11:57:49.459  7898  7898 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
08-04 11:57:49.459  7898  7898 I Adreno-EGL: Local Patches: NONE
08-04 11:57:49.459  7898  7898 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,08-04 11:57:49.469  7831  7831 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-04 11:57:49.499  7831  7831 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-04 11:57:49.499  7831  7831 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-04 11:57:49.499  7831  7831 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-04 11:57:49.499   372   372 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7831
08-04 11:57:49.499   372   372 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-04 11:57:49.499  7831  7831 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-04 11:57:49.499  7831  7831 I wpa_supplicant: ssSupport state is = 1
,08-04 11:57:49.499  7831  7831 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-04 11:57:49.499  7831  7831 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-04 11:57:49.499   372   372 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7831
08-04 11:57:49.499   372   372 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
,08-04 11:57:49.499  7831  7831 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-04 11:57:49.499  7831  7831 I wpa_supplicant: ssSupport state is = 1
08-04 11:57:49.499  7831  7831 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-04 11:57:49.499  7831  7831 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-04 11:57:49.499  7831  7831 E wpa_supplicant: SIM READ ERROR
08-04 11:57:49.499  7831  7831 I wpa_supplicant: wpa_default_ap_write_once
08-04 11:57:49.499  7831  7831 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-04 11:57:49.499  7831  7831 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-04 11:57:49.519  7831  7831 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-04 11:57:49.519  7831  7831 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-04 11:57:49.529  7898  7949 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-04 11:57:49.539  7831  7831 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-04 11:57:49.539  7831  7831 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-04 11:57:49.539   765  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-04 11:57:49.539   765  1149 D WifiNative-HAL: callSECApiBoolean - ID [21]
,08-04 11:57:49.539  7831  7831 I wpa_supplicant: HOTSPOT20_ENABLE called
08-04 11:57:49.539  7831  7831 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-04 11:57:49.539  7831  7831 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-04 11:57:49.539  7831  7831 E wpa_supplicant: SIM READ ERROR
08-04 11:57:49.539  7831  7831 I wpa_supplicant: Blacklist: Clear (all) 
,08-04 11:57:49.549  7898  7898 I NSApplication: Starting up...
,08-04 11:57:49.569  7831  7831 I wpa_supplicant: Skip scan - bUseNetwork false
,08-04 11:57:49.569   765  1330 I ActivityManager: Killing 5935:sstream.app/u0a25 (adj 15): emptyCount ##41
,08-04 11:57:49.569   765  1149 D WifiNative-HAL: callSECApiInt - ID [210]
,08-04 11:57:49.569   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:57:49.569  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 11:57:49.569   765  1149 D WifiConfigStore: Loading config and enabling all networks 
,08-04 11:57:49.569  7235  7235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 11:57:49.569   765  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
08-04 11:57:49.569  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:49.569  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:49.569  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:49.569  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:57:49.569  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:49.569  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:49.569  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:49.569  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 11:57:49.579  7235  7235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:49.579  7235  7235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 11:57:49.579  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-04 11:57:49.579  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:57:49.579  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:57:49.579  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,08-04 11:57:49.579  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:57:49.579  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:57:49.579  1195  1195 D StatusBar.NetworkController: applyOpen
,08-04 11:57:49.579  7235  7235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:49.579  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:57:49.579  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:57:49.579  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:49.579  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:49.579  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:49.579  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:57:49.579  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:49.579  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:49.579  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:49.579  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 11:57:49.579  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 11:57:49.579  7235  7235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:49.579  7235  7235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 11:57:49.579  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-04 11:57:49.579  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 11:57:49.579  1195  1604 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-04 11:57:49.579  1195  1195 D HotspotTile: onReceive : 3, 0
,08-04 11:57:49.579   765  1149 E WifiConfigStore: Not a HS20
,08-04 11:57:49.589  1321  1321 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:57:49.599   765  1149 E WifiConfigStore: Not a HS20
,08-04 11:57:49.599   765  1149 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-04 11:57:49.609   765  1149 D WifiNative-HAL: callSECApiInt - ID [65]
,08-04 11:57:49.609   765  1149 D WifiNative-HAL: callSECApiBoolean - ID [13]
08-04 11:57:49.609  7831  7831 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-04 11:57:49.609  7831  7831 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-04 11:57:49.619  7831  7831 I wpa_supplicant: reset timer : RESET_TIMER 0
08-04 11:57:49.619  7831  7831 I wpa_supplicant: P2P: Current p2p state = IDLE
08-04 11:57:49.619  7831  7831 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-04 11:57:49.619  7831  7831 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-04 11:57:49.619  7831  7831 I wpa_supplicant: First Scan Start
,08-04 11:57:49.619  7831  7831 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-04 11:57:49.619   765  1149 D WifiNative-HAL: Setting external_sim to 1
,08-04 11:57:49.619   765  1149 D WifiStateMachine: Setting OUI to DA-A1-19
08-04 11:57:49.619   765  1149 I WifiNative-HAL: startHal
08-04 11:57:49.619   765  1149 E wifi    : getStaticLongField sWifiHalHandle 0x935db86c
08-04 11:57:49.619   765  1149 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0xc0189e
08-04 11:57:49.619   765  1149 I WifiNative-HAL: Could not start hal
,08-04 11:57:49.619  7647  7647 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 11:57:49.639   765  1149 E native  : do suspend true
,08-04 11:57:49.639   765  1148 D WifiP2pService: P2pDisabledState{ what=131203 }
08-04 11:57:49.639   765  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-04 11:57:49.639   765   765 D WifiScanningService: SCAN_AVAILABLE : 3
08-04 11:57:49.639   765   765 D RttService: SCAN_AVAILABLE : 3
08-04 11:57:49.639   765  1166 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:49.639   765  1166 I WifiNative-HAL: startHal
08-04 11:57:49.639   765  1166 E wifi    : getStaticLongField sWifiHalHandle 0x9b2cd99c
08-04 11:57:49.639   765  1166 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0xa01892
08-04 11:57:49.639   765  1166 I WifiNative-HAL: Could not start hal
08-04 11:57:49.639   765  1166 E WifiScanningService: could not start HAL
,08-04 11:57:49.639   765  1167 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-04 11:57:49.639   298  1055 D CommandListener: Setting iface cfg
08-04 11:57:49.639   298  1055 D CommandListener: Trying to bring up p2p0
,08-04 11:57:49.639   765  1148 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-04 11:57:49.649   765  1148 D WifiP2pService: P2pEnablingState
08-04 11:57:49.649   765  1148 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-04 11:57:49.649   765  1149 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-04 11:57:49.649   765  1149 D WifiNative-HAL: callSECStringApiVoid - ID [215]
08-04 11:57:49.649   765  1149 E WifiNative-HAL: invaild command id : 215
,08-04 11:57:49.649   765  1148 D WifiP2pService: P2p socket connection successful
08-04 11:57:49.649   765  1148 D WifiP2pService: P2pEnabledState
,08-04 11:57:49.649   765  1148 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-04 11:57:49.649   765   765 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-04 11:57:49.649   765  1060 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-04 11:57:49.649   765  1060 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,08-04 11:57:49.649   765  1060 D WifiDisplayController: disconnect
08-04 11:57:49.649   765  1060 D WifiDisplayController: updateConnection
08-04 11:57:49.649   765  1060 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-04 11:57:49.649   765  1060 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-04 11:57:49.649  1195  1195 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-04 11:57:49.649   765  1493 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-04 11:57:49.649  1195  1195 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-04 11:57:49.659   765  1151 E ConnectivityService: updateNetworkInfo()
08-04 11:57:49.659   765  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,08-04 11:57:49.659   765  1060 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:49.659   765  1060 D WifiDisplayAdapter: onP2pDisconnected
08-04 11:57:49.659   765  1060 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-04 11:57:49.659   765  1060 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-04 11:57:49.669  7831  7831 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-04 11:57:49.679   303   303 E SMD     : DCD ON
,08-04 11:57:49.699   765  1449 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-04 11:57:49.699   765  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:49.699   765  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:49.699   765  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:49.699   765  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:49.699  7831  7831 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,08-04 11:57:49.699   765  1148 D WifiNative-HAL: p2pGetDeviceAddress
,08-04 11:57:49.699   765  1148 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:de:28:a3
08-04 11:57:49.699   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-04 11:57:49.699   765  1149 D SecContentProvider2: mCursor = null
,08-04 11:57:49.739  7968  7968 E Zygote  : MountEmulatedStorage()
08-04 11:57:49.739  7968  7968 E Zygote  : v2
08-04 11:57:49.739  7968  7968 I libpersona: KNOX_SDCARD checking this for 10158
08-04 11:57:49.739  7968  7968 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:49.749  7968  7968 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,08-04 11:57:49.749  7968  7968 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 11:57:49.749  7968  7968 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 11:57:49.749   765  1449 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7968 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-04 11:57:49.749   765  1148 D WifiP2pService: DeviceAddress: ea:28:a3
08-04 11:57:49.749   765  1060 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
08-04 11:57:49.749   765  1060 D WifiDisplayController:  deviceAddress: ea:50:8b:de:28:a3
08-04 11:57:49.749   765  1060 D WifiDisplayController:  primary type: 10-0050F204-5
08-04 11:57:49.749   765  1060 D WifiDisplayController:  secondary type: null
08-04 11:57:49.749   765  1060 D WifiDisplayController:  wps: 0
08-04 11:57:49.749   765  1060 D WifiDisplayController:  grpcapab: 0
08-04 11:57:49.749   765  1060 D WifiDisplayController:  devcapab: 0
08-04 11:57:49.749   765  1060 D WifiDisplayController:  status: 3
08-04 11:57:49.749   765  1060 D WifiDisplayController:  wfdInfo: null
08-04 11:57:49.749   765  1060 D WifiDisplayController:  groupownerAddress: null
08-04 11:57:49.749   765  1060 D WifiDisplayController:  GOdeviceName: null
08-04 11:57:49.749   765  1060 D WifiDisplayController:  interfaceAddress: 
08-04 11:57:49.749   765  1060 D WifiDisplayController:  SConnectInfo : null
,08-04 11:57:49.749   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-04 11:57:49.749   765  1149 D SecContentProvider2: mCursor = null
,08-04 11:57:49.769   765  1148 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-04 11:57:49.769   765  1148 D WifiP2pService: InactiveState
08-04 11:57:49.769   765  1148 D WifiP2pService: InactiveState{ what=143376 }
08-04 11:57:49.769   765  1148 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-04 11:57:49.769  7968  7968 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:49.769  7968  7968 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:49.769  7831  7831 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-04 11:57:49.769   765  1148 D WifiP2pService: InactiveState{ what=143376 }
08-04 11:57:49.769   765  1148 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-04 11:57:49.779  7968  7968 D ResourcesManager: creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,08-04 11:57:49.779  7968  7968 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-04 11:57:49.779  7968  7968 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-04 11:57:49.779  7968  7968 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-04 11:57:49.799  7968  7968 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:57:49.799  7968  7968 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-04 11:57:49.799  7968  7968 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-04 11:57:49.799   765   784 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,08-04 11:57:49.799   765   784 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:49.799   765   784 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:49.799   765   784 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:49.799   765   784 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:49.839  7983  7983 E Zygote  : MountEmulatedStorage()
,08-04 11:57:49.839  7983  7983 E Zygote  : v2
08-04 11:57:49.839  7983  7983 I libpersona: KNOX_SDCARD checking this for 10186
08-04 11:57:49.839  7983  7983 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:49.849   765   784 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7983 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,08-04 11:57:49.849   765   784 I ActivityManager: Killing 5968:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): emptyCount ##41
,08-04 11:57:49.859  7983  7983 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:49.859  7983  7983 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 11:57:49.859  7983  7983 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 11:57:49.879  7983  7983 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:49.879  7983  7983 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:49.889  7983  7983 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,08-04 11:57:49.889  7983  7983 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-04 11:57:49.889  7983  7983 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 11:57:49.889  7983  7983 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,08-04 11:57:49.889  7983  7983 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-04 11:57:49.889  7983  7983 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-04 11:57:49.979   765  1352 D RCPManagerService: exchangeData() failure , invalid userId
,08-04 11:57:50.009   765  1238 D RCPManagerService: exchangeData() failure , invalid userId
,08-04 11:57:50.009   765  1330 D RCPManagerService: exchangeData() failure , invalid userId
,08-04 11:57:50.039   765  1449 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-04 11:57:50.049   765  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:50.049   765  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:50.049   765  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:50.049   765  1449 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:50.059   765  1652 D RCPManagerService: exchangeData() failure , invalid userId
,08-04 11:57:50.079  8009  8009 E Zygote  : MountEmulatedStorage()
08-04 11:57:50.079  8009  8009 E Zygote  : v2
08-04 11:57:50.079  8009  8009 I libpersona: KNOX_SDCARD checking this for 10092
08-04 11:57:50.079  8009  8009 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:50.089   765  1449 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8009 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,08-04 11:57:50.099  8009  8009 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:50.099  8009  8009 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 11:57:50.099  8009  8009 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-04 11:57:50.099   765  1238 D RCPManagerService: exchangeData() failure , invalid userId
,08-04 11:57:50.109   765  1703 D RCPManagerService: exchangeData() failure , invalid userId
,08-04 11:57:50.109   765  1263 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:50.109  7299  7299 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-04 11:57:50.109  7299  7299 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-04 11:57:50.109  7299  7299 D SecurityLogAgent: StateMachine : Current State = 1
08-04 11:57:50.109  7299  7299 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-04 11:57:50.109   765  1352 I ActivityManager: Killing 5536:com.sec.android.gallery3d/u0a53 (adj 15): emptyCount ##41
,08-04 11:57:50.119   765  1238 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:50.119   765  1330 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,08-04 11:57:50.119   765  1476 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:50.119   765  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:50.119   765  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:50.119   765  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:50.119   765  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:50.129  8009  8009 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:50.129  8009  8009 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:50.159  8025  8025 E Zygote  : MountEmulatedStorage()
08-04 11:57:50.159  8025  8025 I libpersona: KNOX_SDCARD checking this for 10200
08-04 11:57:50.159  8025  8025 E Zygote  : v2
08-04 11:57:50.159  8025  8025 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:50.169   765  1330 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8025 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-04 11:57:50.209  8025  8025 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:50.209  8025  8025 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 11:57:50.209  8025  8025 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-04 11:57:50.209   765  1680 I ActivityManager: Killing 7040:com.sec.knox.knoxsetupwizardclient/1000 (adj 15): emptyCount ##41
,08-04 11:57:50.229  8009  8009 D ResourcesManager: creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,08-04 11:57:50.239  8025  8025 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:50.239  8025  8025 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:50.249  8009  8009 D BadgeProvider: onCreate
,08-04 11:57:50.249  8009  8009 D BadgeProvider: DatabaseHelper
,08-04 11:57:50.259  8025  8025 D ResourcesManager: creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,08-04 11:57:50.269  8009  8017 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-04 11:57:50.279  1439  1439 D Launcher.Model: reloadBadges entered.
,08-04 11:57:50.279  8009  8017 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-04 11:57:50.279  8009  8017 D BadgeProvider: sendNotify, [notify] : null
08-04 11:57:50.279  8009  8017 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
,08-04 11:57:50.279  8009  8017 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-04 11:57:50.279  8009  8017 D BadgeProvider: update, [UpdateCount] : 1
,08-04 11:57:50.279   765  1573 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-04 11:57:50.279   765  1573 D ActivityManager: caller:android.app.ApplicationThreadProxy@d73011d, r.packageName :com.google.android.gms
,08-04 11:57:50.289  2540  2540 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*,
,08-04 11:57:50.299   765  1493 I ActivityManager: Killing 6106:com.android.vending/u0a33 (adj 15): emptyCount ##41
,08-04 11:57:50.299  2540  5371 I iu.UploadsManager: num queued entries: 0
,08-04 11:57:50.299  2540  5371 I iu.UploadsManager: num updated entries: 0
,08-04 11:57:50.299   765  1238 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.samsungapps, hostingType: broadcast
08-04 11:57:50.299  2540  5371 I iu.SyncManager: NEXT; no task
,08-04 11:57:50.299   765  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:50.299   765  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:50.299   765  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:57:50.299   765  1238 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:57:50.339  8042  8042 E Zygote  : MountEmulatedStorage()
08-04 11:57:50.339  8042  8042 E Zygote  : v2
,08-04 11:57:50.339  8042  8042 I libpersona: KNOX_SDCARD checking this for 10045
08-04 11:57:50.339  8042  8042 I libpersona: KNOX_SDCARD not a persona
,08-04 11:57:50.349   765  1238 I ActivityManager: Start proc com.sec.android.app.samsungapps for broadcast com.sec.android.app.samsungapps/.networkstatereceiver.NetworkStateReceiver: pid=8042 uid=10045 gids={50045, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-04 11:57:50.349   765  1680 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-04 11:57:50.369  8042  8042 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:57:50.369  8042  8042 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 11:57:50.369  8042  8042 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-04 11:57:50.389  8042  8042 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:57:50.389  8042  8042 D ActivityThread: Added TimaKeyStore provider
,08-04 11:57:50.399  7831  7831 I wpa_supplicant: nl80211: Received scan results (36 BSSes)
,08-04 11:57:50.399  8042  8042 D ResourcesManager: creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
,08-04 11:57:50.399  7831  7831 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-04 11:57:50.399  7831  7831 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
08-04 11:57:50.399  7831  7831 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-04 11:57:50.399  7831  7831 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=5 BSSID=00.00.00 SSID=4E47373030
,08-04 11:57:50.409   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-04 11:57:50.409   765  1149 D SecContentProvider2: mCursor = null
,08-04 11:57:50.449   765  1238 I ActivityManager: Killing 7123:com.google.android.gms.unstable/u0a15 (adj 15): emptyCount ##41
,08-04 11:57:50.459  6901  6901 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-04 11:57:50.459   765  1444 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:50.459  7299  7299 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-04 11:57:50.459  7299  7299 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-04 11:57:50.459  7299  7299 D SecurityLogAgent: StateMachine : Current State = 1
08-04 11:57:50.459  7299  7299 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-04 11:57:50.469  6901  6901 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-04 11:57:50.469  7831  7831 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-04 11:57:50.469  7831  7831 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=6 BSSID=00.00.00 SSID=4E47373030
,08-04 11:57:50.469  7831  7831 I wpa_supplicant: Associated with F4.99.3E
08-04 11:57:50.469  7831  7831 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-04 11:57:50.469  7831  7831 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-04 11:57:50.479   765  1476 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:50.479  7299  7299 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-04 11:57:50.479  7299  7299 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-04 11:57:50.479  7299  7299 D SecurityLogAgent: StateMachine : Current State = 1
08-04 11:57:50.479  7299  7299 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-04 11:57:50.479   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-04 11:57:50.479   765  1149 D SecContentProvider2: mCursor = null
,08-04 11:57:50.479  7675  7675 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,08-04 11:57:50.479   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-04 11:57:50.479   765  1149 D SecContentProvider2: mCursor = null
,08-04 11:57:50.489  1321  1321 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-04 11:57:50.489  1321  1321 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-04 11:57:50.489   765  1238 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:50.489  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-04 11:57:50.489  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-04 11:57:50.489   765  1680 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:50.489  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-04 11:57:50.489  1321  1321 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-04 11:57:50.489  1321  2802 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-04 11:57:50.489  7831  7831 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-04 11:57:50.489  7831  7831 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-04 11:57:50.489  7831  7831 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-04 11:57:50.489  7831  7831 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-04 11:57:50.489  7831  7831 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-04 11:57:50.489  7831  7831 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=1 id_str=]
,08-04 11:57:50.489  7831  7831 I wpa_supplicant: Blacklist: Clear (temp) 
08-04 11:57:50.489  7831  7831 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-04 11:57:50.489  6992  6992 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-04 11:57:50.499   765  1149 D WifiNative-HAL: callSECApiVoid - ID [50]
,08-04 11:57:50.499  7675  7675 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-04 11:57:50.499  7675  7675 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
08-04 11:57:50.499  7675  7675 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,08-04 11:57:50.499  7675  7675 D WifiDirectBR: stopServiceTest : false
,08-04 11:57:50.499  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 11:57:50.499  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 11:57:50.499   765  1149 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-04 11:57:50.499   765  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 11:57:50.499   765  1151 D ConnectivityService: Got NetworkAgent Messenger
08-04 11:57:50.499   765  1151 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-04 11:57:50.499   765  1151 E ConnectivityService: updateNetworkInfo()
08-04 11:57:50.499   765  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 11:57:50.499   765  1151 D ConnectivityService: NetworkAgent connected
,08-04 11:57:50.509  1321  1321 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-04 11:57:50.509  1321  1321 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-04 11:57:50.509   765  1652 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:50.509  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-04 11:57:50.509   765  1238 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:50.509  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-04 11:57:50.509  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-04 11:57:50.509  1321  1321 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-04 11:57:50.509  1321  2802 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-04 11:57:50.519   765  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 11:57:50.519   765  1493 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:50.529  6901  6901 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-04 11:57:50.539   298  1055 D CommandListener: Setting iface cfg
,08-04 11:57:50.539   765  1149 E WifiStateMachine: Start Dhcp Watchdog 2
,08-04 11:57:50.539   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-04 11:57:50.539   765  1149 D SecContentProvider2: mCursor = null
,08-04 11:57:50.539  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-04 11:57:50.539  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 11:57:50.549   765  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,08-04 11:57:50.629   765  1149 E native  : do suspend false
,08-04 11:57:50.629   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-04 11:57:50.629   765  1149 D SecContentProvider2: mCursor = null
08-04 11:57:50.629   765  1148 D WifiP2pService: InactiveState{ what=143375 }
08-04 11:57:50.629   765  1148 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-04 11:57:50.869  8072  8072 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-04 11:57:50.869  8072  8072 I dhcpcd  : version 5.5.6 starting
,08-04 11:57:50.869  8072  8072 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-04 11:57:50.959  8072  8072 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-04 11:57:50.959  8072  8072 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
,08-04 11:57:50.959  8072  8072 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
,08-04 11:57:50.959  8072  8072 I dhcpcd  : bssid match
08-04 11:57:50.959  8072  8072 I dhcpcd  : wlan0: rebinding lease of 192.168.1.122
,08-04 11:57:50.989  8072  8072 I dhcpcd  : wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,08-04 11:57:50.999  7235  7294 I WifiManager: packageName : com.test.thalitest
,08-04 11:57:50.999   765  1232 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-04 11:57:50.999   765  1232 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
,08-04 11:57:50.999   765  1232 D SecContentProvider2: mCursor = null
,08-04 11:57:51.009   765  1232 D WifiService: setWifiEnabled: false pid=7235, uid=10079
,08-04 11:57:51.009   765  1232 D SettingsProvider: name = wifi_on
,08-04 11:57:51.019   765  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 11:57:51.019  8072  8072 I dhcpcd  : wlan0: leased 192.168.1.122 for 172800 seconds
,08-04 11:57:51.029   765  1149 E native  : do suspend true
,08-04 11:57:51.029   765  1148 D WifiP2pService: InactiveState{ what=143375 }
08-04 11:57:51.029   765  1148 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-04 11:57:51.039  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-04 11:57:51.039  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 11:57:51.039   298  1055 D CommandListener: Clearing all IP addresses on wlan0
,08-04 11:57:51.089   765  1151 E ConnectivityService: updateNetworkInfo()
08-04 11:57:51.089   765  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 11:57:51.089   765  1151 E ConnectivityService: updateNetworkInfo()
08-04 11:57:51.089   765  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
08-04 11:57:51.089   765  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 11:57:51.089   765  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-04 11:57:51.089   298  1055 E Netd    : no such netId 503
08-04 11:57:51.089   765  1151 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '77 network destroy 503' failed with '400 77 destroyNetwork() failed (Machine is not on the network)'
08-04 11:57:51.089   765  1151 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-04 11:57:51.089   765  1151 D ConnectivityService: calling update connectivity
,08-04 11:57:51.089   765  1151 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=false
08-04 11:57:51.089   765  1151 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-04 11:57:51.089   765  8063 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:51.089   765  8063 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,08-04 11:57:51.089   765   765 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-04 11:57:51.089  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 11:57:51.089  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 11:57:51.099   765  1149 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-04 11:57:51.109   765  1148 D WifiP2pService: InactiveState{ what=131204 }
,08-04 11:57:51.109   765   765 D WifiScanningService: SCAN_AVAILABLE : 1
,08-04 11:57:51.109   765   765 D RttService: SCAN_AVAILABLE : 1
08-04 11:57:51.109   765  1166 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,08-04 11:57:51.109   765  1167 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:57:51.109   765  1148 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-04 11:57:51.109   765  1148 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-04 11:57:51.109   765  1060 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:51.109   765  1060 D WifiDisplayAdapter: onP2pDisconnected
08-04 11:57:51.109   765  1060 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-04 11:57:51.109   765  1060 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-04 11:57:51.109   765  1151 E ConnectivityService: updateNetworkInfo()
,08-04 11:57:51.119   765  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,08-04 11:57:51.119  1321  1321 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-04 11:57:51.119  1321  1321 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-04 11:57:51.119   765  1652 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:51.119  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-04 11:57:51.119   765  1148 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-04 11:57:51.129   765  1060 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
,08-04 11:57:51.129   765   765 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-04 11:57:51.129   765  1151 E ConnectivityService: updateNetworkInfo()
08-04 11:57:51.129   765  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
08-04 11:57:51.129   765  1703 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-04 11:57:51.129   765  1060 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-04 11:57:51.129  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-04 11:57:51.129  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-04 11:57:51.129  1321  1321 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-04 11:57:51.129  1321  2802 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-04 11:57:51.129   765  1060 D WifiDisplayController: disconnect
08-04 11:57:51.129   765  1060 D WifiDisplayController: updateConnection
08-04 11:57:51.129   765  1060 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-04 11:57:51.129   765  1060 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-04 11:57:51.129   765  1060 D WifiDisplayAdapter: onP2pDisconnected
08-04 11:57:51.129   765  1060 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-04 11:57:51.129   765  1060 D IpRemoteDisplayController: WfdBridgeServer is already null
08-04 11:57:51.129   765  1060 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-04 11:57:51.129  1195  1195 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-04 11:57:51.129   765  1148 D WifiP2pService: P2pDisablingState
08-04 11:57:51.129   765  1148 D WifiP2pService: P2pDisablingState{ what=147458 }
,08-04 11:57:51.129   765  1148 D WifiP2pService: p2p socket connection lost
08-04 11:57:51.129   765  1148 D WifiP2pService: P2pDisabledState
,08-04 11:57:51.129   765  1352 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-04 11:57:51.129   765  1149 E native  : do suspend true
08-04 11:57:51.129  1195  1195 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-04 11:57:51.139   765  1148 D WifiP2pService: P2pDisabledState{ what=143375 }
08-04 11:57:51.139   765  1148 D WifiP2pService: DefaultState{ what=143375 }
,08-04 11:57:51.139   298  1055 D CommandListener: Clearing all IP addresses on wlan0
,08-04 11:57:51.139  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 11:57:51.139   765  1330 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:51.139  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 11:57:51.139  7831  7831 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-04 11:57:51.139   765   765 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-04 11:57:51.139  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-04 11:57:51.139  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 11:57:51.149   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-04 11:57:51.149   765  1149 D SecContentProvider2: mCursor = null
,08-04 11:57:51.149   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:57:51.149  1321  1321 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-04 11:57:51.149   765  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,08-04 11:57:51.149  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 11:57:51.149  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-04 11:57:51.149  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:57:51.149  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:57:51.149  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:57:51.149  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:57:51.149  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:57:51.149  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:57:51.149  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:57:51.149  1195  1195 D StatusBar.NetworkController: applyOpen
,08-04 11:57:51.149  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 11:57:51.149  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-04 11:57:51.149  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 11:57:51.149  7235  7235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:51.149  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:51.149  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:51.149  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:51.149  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 11:57:51.149  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:51.149  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:51.149  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:51.149  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 11:57:51.149  7235  7235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:51.149  7235  7235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 11:57:51.149  1195  1604 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-04 11:57:51.149  1195  1195 D HotspotTile: onReceive : 0, 0
08-04 11:57:51.149  7235  7235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 11:57:51.149  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:51.149  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:51.149  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:51.149  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 11:57:51.149  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:51.149  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:51.149  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:51.149  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 11:57:51.149  7235  7235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:51.149  7235  7235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 11:57:51.149  6901  6901 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-04 11:57:51.159  1321  1321 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-04 11:57:51.159  1321  1321 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-04 11:57:51.159   765  1573 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:51.159  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-04 11:57:51.159   765  1352 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-04 11:57:51.159  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-04 11:57:51.159  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-04 11:57:51.159  1321  1321 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-04 11:57:51.159  1321  2802 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-04 11:57:51.169  6992  6992 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-04 11:57:51.169  7675  7675 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-04 11:57:51.169  7675  7675 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
08-04 11:57:51.169  7675  7675 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,08-04 11:57:51.169  7831  7831 I wpa_supplicant: Blacklist: Clear (all) 
08-04 11:57:51.169  7675  7675 D WifiDirectBR: stopServiceTest : false
08-04 11:57:51.169  7675  7675 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,08-04 11:57:51.179  1321  1321 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-04 11:57:51.179  1321  1321 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-04 11:57:51.179   765  1232 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:57:51.179  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-04 11:57:51.179   765   785 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-04 11:57:51.179  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-04 11:57:51.179  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-04 11:57:51.179  1321  1321 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-04 11:57:51.179  1321  2802 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-04 11:57:51.189   765  1703 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:51.189  6901  6901 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-04 11:57:51.199  7831  7831 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-04 11:57:51.199  7831  7831 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-04 11:57:51.199  7831  7831 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
,08-04 11:57:51.199  7831  7831 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=0 BSSID=F4.99.3E SSID=4E47373030
08-04 11:57:51.199  7831  7831 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-04 11:57:51.209  6901  6901 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-04 11:57:51.209   765   784 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:51.209  7299  7299 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-04 11:57:51.209  7299  7299 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-04 11:57:51.209  7299  7299 D SecurityLogAgent: StateMachine : Current State = 1
08-04 11:57:51.209  7299  7299 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-04 11:57:51.249  7831  7831 I wpa_supplicant: Blacklist: Clear (all) 
,08-04 11:57:51.389  7831  7831 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-04 11:57:51.389   765  1152 D Tethering: InitialState.processMessage what=4
08-04 11:57:51.389   765  1152 E Tethering: No numeric data
08-04 11:57:51.389   765  1152 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-04 11:57:51.389   765  1146 V NetworkStats: performPollLocked(flags=0x1)
,08-04 11:57:51.389  1195  1195 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-04 11:57:51.389  1195  1195 D HotspotTile: updateTetherState():false, false
08-04 11:57:51.389   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 11:57:51.389   765  1146 D NetworkStatsFactory: UpdateStatsForKnox
,08-04 11:57:51.389   765  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:51.389   765  1146 V NetworkStats: performPollLocked() took 5ms
08-04 11:57:51.389   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 11:57:51.399   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:57:51.399   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 11:57:51.489   765  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-04 11:57:51.489   765  1149 D WifiNative-HAL: callSECApiBoolean - ID [21]
,08-04 11:57:51.489   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:57:51.489  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-04 11:57:51.489  1864  2360 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 11:57:51.489  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-04 11:57:51.499   765  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,08-04 11:57:51.499  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:57:51.499  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-04 11:57:51.499  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:57:51.499  1195  1604 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-04 11:57:51.499  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:51.499  7647  7647 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 11:57:51.499  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:51.499  1321  1321 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:57:51.499  1195  1195 D HotspotTile: onReceive : 1, 0
,08-04 11:57:51.499  6901  6901 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-04 11:57:51.499   765  1476 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:57:51.509  7299  7299 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-04 11:57:51.509  7299  7299 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-04 11:57:51.509  7299  7299 D SecurityLogAgent: StateMachine : Current State = 1
,08-04 11:57:51.509  7299  7299 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-04 11:57:51.689   765  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-04 11:57:51.729   765  1703 I ActivityManager: Killing 4489:com.sec.android.app.shealth/u0a40 (adj 15): emptyCount ##41
,08-04 11:57:52.319   765  1238 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-04 11:57:52.319   765  1238 D ActivityManager: caller:android.app.ApplicationThreadProxy@3d63a3af, r.packageName :com.google.android.music
,08-04 11:57:52.339   765   785 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-04 11:57:52.339   765  1652 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-04 11:57:52.349   765  1703 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-04 11:57:52.349   765  1352 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-04 11:57:52.349   765  1352 D ActivityManager: caller:android.app.ApplicationThreadProxy@196b51fd, r.packageName :com.google.android.music
,08-04 11:57:52.379  1864  1864 D WearableService: callingUid 10015, callindPid: 1864
,08-04 11:57:52.389   765  1232 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-04 11:57:52.419  7738  7738 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-04 11:57:52.419  7738  8141 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-04 11:57:52.449  7738  8136 I MusicLeanback: Conditions not met for autocaching.
,08-04 11:57:52.449  7738  8136 I MusicLeanback: Stop autocaching.
,08-04 11:57:52.679   303   303 E SMD     : DCD ON
,08-04 11:57:53.399   765  1476 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-04 11:57:53.399   765  1476 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 288, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
08-04 11:57:53.399   765  1476 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,08-04 11:57:53.399   765  1476 D BatteryService: stay LED for fully charged
08-04 11:57:53.399   765   765 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-04 11:57:53.399   765   765 I MotionRecognitionService: Plugged
,08-04 11:57:53.399   765   765 I MotionRecognitionService: setPowerConnected  = true
,08-04 11:57:53.399  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-04 11:57:53.409  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,08-04 11:57:53.409  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-04 11:57:53.409  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-04 11:57:53.409  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-04 11:57:53.409  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-04 11:57:54.019  7235  7294 D BluetoothAdapter: enable()
,08-04 11:57:54.019   765  1493 W ActivityManager: Permission Denial: getCurrentUser() from pid=7235, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,08-04 11:57:54.019   765  1493 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-04 11:57:54.019   765  1493 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7235, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-04 11:57:54.019   765  1493 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
08-04 11:57:54.019   765  1493 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
08-04 11:57:54.019   765  1493 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
08-04 11:57:54.019   765  1493 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-04 11:57:54.019   765  1493 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-04 11:57:54.019   765  1493 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-04 11:57:54.019   765  1493 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-04 11:57:54.019   765  1493 D SettingsProvider: name = bluetooth_on
,08-04 11:57:54.019   765  1059 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-04 11:57:54.029   765  1059 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-04 11:57:54.029   765  1059 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-04 11:57:54.049   765  1238 I art     : Explicit concurrent mark sweep GC freed 64783(3MB) AllocSpace objects, 5(80KB) LOS objects, 29% free, 37MB/53MB, paused 1.491ms total 114.973ms
,08-04 11:57:54.049   765  1238 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,08-04 11:57:54.069  7704  7704 D BluetoothAdapterState: make
,08-04 11:57:54.069  7898  7917 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-04 11:57:54.079  7704  7704 I bluedroid: init
,08-04 11:57:54.079  7704  8157 I BluetoothAdapterState: Entering OffState
,08-04 11:57:54.079  7704  7704 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-04 11:57:54.079  7704  7704 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-04 11:57:54.079  7704  7704 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-04 11:57:54.079  7704  7704 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-04 11:57:54.079  7704  7704 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-04 11:57:54.079  7704  7704 I bluedroid: get_profile_interface socket
08-04 11:57:54.079  7704  7704 I bluedroid: get_profile_interface map_client
08-04 11:57:54.079  7704  8160 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-04 11:57:54.079  7704  7704 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-04 11:57:54.089  7704  8160 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
,08-04 11:57:54.089  7704  8160 E BluetoothServiceJni: populateRssiValuesNative
08-04 11:57:54.089  7704  8160 I bluedroid: getModelRssiValues
08-04 11:57:54.089  7704  8160 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-04 11:57:54.089   765  1263 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-04 11:57:54.089  7704  8160 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-04 11:57:54.089   765   765 D SettingsProvider: name = bluetooth_name
,08-04 11:57:54.089  7704  7714 I bluedroid: config_hci_snoop_log
,08-04 11:57:54.089   765  1059 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 13 receivers.
,08-04 11:57:54.089  7704  8160 D BluetoothAdapterProperties: Name is: Note3-1
,08-04 11:57:54.089   765  1059 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-04 11:57:54.089   765  1059 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-04 11:57:54.099   765  1059 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-04 11:57:54.099  7704  8157 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-04 11:57:54.099  7704  8157 D BluetoothAdapterProperties: Setting state to 11
08-04 11:57:54.099  7704  8157 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-04 11:57:54.099  7704  8157 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-04 11:57:54.099  7704  8157 D BluetoothAdapterService: updateAdapterState state is 11
,08-04 11:57:54.099  7704  8157 D BluetoothAdapterService: Autoconnection is available 
,08-04 11:57:54.099  7704  8157 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
08-04 11:57:54.099   765   765 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:54.099   765   765 I InputMethodManagerService: [BT Setting State] State =11
,08-04 11:57:54.099  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:54.099  1750  1750 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-04 11:57:54.109  7620  7620 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,08-04 11:57:54.109  1321  1321 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-04 11:57:54.109  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:54.109   765  1680 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-04 11:57:54.109   765  1680 D ActivityManager: caller:android.app.ApplicationThreadProxy@77d4208, r.packageName :com.google.android.gms
08-04 11:57:54.109  7704  8157 D BluetoothSecureManager: getInstant: null
,08-04 11:57:54.109  7704  8157 D BluetoothSecureManager: calling getMethod for getService
08-04 11:57:54.109  7704  8157 D BluetoothSecureManager: calling getService
,08-04 11:57:54.109  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-04 11:57:54.109  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:54.109  7704  8157 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@28391b02
,08-04 11:57:54.109   765  1493 D BluetoothSecureManagerService: isSecureModeEnabled
08-04 11:57:54.109   765  1493 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-04 11:57:54.109   765  1449 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
08-04 11:57:54.109   765  1652 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-04 11:57:54.109  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,08-04 11:57:54.109  1195  1604 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-04 11:57:54.109  7704  8157 D BtConfig.SecureMode: isSecureModeOn:false
08-04 11:57:54.109  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-04 11:57:54.119  7704  8157 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
,08-04 11:57:54.119  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-04 11:57:54.119  1321  1321 D BluetoothNotiBroadcastReceiver: onReceive
,08-04 11:57:54.119  7704  8157 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-04 11:57:54.119  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-04 11:57:54.119  7704  8157 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-04 11:57:54.119  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-04 11:57:54.119  7704  8157 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-04 11:57:54.119  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-04 11:57:54.119  7704  8157 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-04 11:57:54.119  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-04 11:57:54.119  7704  8157 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-04 11:57:54.119  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-04 11:57:54.119  7704  8157 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-04 11:57:54.119  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-04 11:57:54.119  7704  8157 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,08-04 11:57:54.119  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-04 11:57:54.119  7704  8157 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-04 11:57:54.119  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-04 11:57:54.119  7704  8157 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-04 11:57:54.119  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-04 11:57:54.119  7704  8157 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-04 11:57:54.119  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-04 11:57:54.119  7704  8157 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-04 11:57:54.129  7704  8157 D BluetoothBondStateMachine: make
,08-04 11:57:54.129  1864  1864 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-04 11:57:54.139  7704  8169 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-04 11:57:54.139  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-04 11:57:54.139  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-04 11:57:54.139  7704  8157 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-04 11:57:54.139   765  1352 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 11:57:54.139   765  1352 D ActivityManager: caller:android.app.ApplicationThreadProxy@1904fbc6, r.packageName :com.android.bluetooth
,08-04 11:57:54.139  1864  1864 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-04 11:57:54.149  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-04 11:57:54.149  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-04 11:57:54.149  7704  8157 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-04 11:57:54.149  7704  7704 I BtGatt.JNI: classInitNative(L890): classInitNative: Success!
,08-04 11:57:54.149   765  3205 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 11:57:54.149   765  3205 D ActivityManager: caller:android.app.ApplicationThreadProxy@35a876b4, r.packageName :com.android.bluetooth
,08-04 11:57:54.149  7704  7704 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 11:57:54.149  7704  7704 D BtGatt.GattService: Received start request. Starting profile...
08-04 11:57:54.149  7704  7704 D BtGatt.GattService: start()
08-04 11:57:54.149  7704  7704 I bluedroid: get_profile_interface gatt
,08-04 11:57:54.149  7704  7704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7f9795
08-04 11:57:54.149  7704  7704 D BtGatt.AdvertiseManager: advertise manager created
,08-04 11:57:54.149  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-04 11:57:54.149  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-04 11:57:54.149  7704  8157 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,08-04 11:57:54.159   765  1703 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 11:57:54.159   765  1703 D ActivityManager: caller:android.app.ApplicationThreadProxy@33450e52, r.packageName :com.android.bluetooth
,08-04 11:57:54.159  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-04 11:57:54.159  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-04 11:57:54.159  7704  8157 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-04 11:57:54.159   765  1652 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 11:57:54.159   765  1652 D ActivityManager: caller:android.app.ApplicationThreadProxy@38b8107f, r.packageName :com.android.bluetooth
,08-04 11:57:54.159  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-04 11:57:54.159  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-04 11:57:54.159  7704  8157 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-04 11:57:54.159   765  1444 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 11:57:54.159   765  1444 D ActivityManager: caller:android.app.ApplicationThreadProxy@3fa54095, r.packageName :com.android.bluetooth
,08-04 11:57:54.159  7704  7704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7f9795
,08-04 11:57:54.169  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-04 11:57:54.169  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-04 11:57:54.169  7704  8157 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-04 11:57:54.169  7704  7704 D HeadsetService: Received start request. Starting profile...
,08-04 11:57:54.169  7704  7704 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-04 11:57:54.169  7704  7704 D HeadsetStateMachine: make
08-04 11:57:54.169   765  1352 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 11:57:54.169   765  1352 D ActivityManager: caller:android.app.ApplicationThreadProxy@1fc7359b, r.packageName :com.android.bluetooth
,08-04 11:57:54.169  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-04 11:57:54.169  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-04 11:57:54.169  7704  8157 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-04 11:57:54.169   765  1493 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 11:57:54.169   765  1493 D ActivityManager: caller:android.app.ApplicationThreadProxy@14e65111, r.packageName :com.android.bluetooth
,08-04 11:57:54.169  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-04 11:57:54.169  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-04 11:57:54.169  7704  8157 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-04 11:57:54.179   765  1238 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 11:57:54.179   765  1238 D ActivityManager: caller:android.app.ApplicationThreadProxy@21d99077, r.packageName :com.android.bluetooth
,08-04 11:57:54.179  7704  7704 E HeadsetStateMachine: # of Max HF connection is 2
,08-04 11:57:54.179  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-04 11:57:54.179  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-04 11:57:54.179  7704  8157 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-04 11:57:54.179  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-04 11:57:54.179  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-04 11:57:54.179  7704  8157 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-04 11:57:54.179  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-04 11:57:54.179  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-04 11:57:54.179  7704  8157 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-04 11:57:54.179  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-04 11:57:54.179  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-04 11:57:54.179  7704  8157 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-04 11:57:54.179  7704  8157 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-04 11:57:54.179   765  3205 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-04 11:57:54.189   765  1573 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
,08-04 11:57:54.189  7704  7704 I bluedroid: get_profile_interface handsfree
,08-04 11:57:54.189  7704  7704 I DualScoManager: Instantiating Dual Sco Manager
,08-04 11:57:54.189  7704  7704 I DualScoManager: Set HeadsetServiceHelper
,08-04 11:57:54.199  7704  7704 D BluetoothAtMessage: createCMTIContentObservers
,08-04 11:57:54.199   765  1652 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-04 11:57:54.199   765  1652 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:57:54.199   765  1652 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:57:54.199   765  1652 D SettingsProvider: selectionArgs: false
08-04 11:57:54.199   765  1652 D SettingsProvider: selectionArgs: 1002
08-04 11:57:54.199   765  1652 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:57:54.199   765  1652 D SettingsProvider: ret = -1
,08-04 11:57:54.199  7704  8175 D HeadsetStateMachine: Enter Disconnected: -2
,08-04 11:57:54.199  7704  7704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7f9795
,08-04 11:57:54.199  7704  7704 D A2dpService: Received start request. Starting profile...
,08-04 11:57:54.199  7704  8175 E HeadsetStateMachine: set to mRemoteBrsf = 0
,08-04 11:57:54.199  7704  8175 D HeadsetStateMachine: map size, before remove : 0
,08-04 11:57:54.199  7704  8175 D HeadsetStateMachine: map size, after remove: 0
08-04 11:57:54.199  7704  8175 D HeadsetStateMachine: mNextConnectingDevice : null
,08-04 11:57:54.199  7704  7704 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-04 11:57:54.199  7704  7704 V Avrcp   : make
,08-04 11:57:54.199  7704  7704 V Avrcp   : Avrcp
,08-04 11:57:54.209  7704  7704 I bluedroid: get_profile_interface avrcp
,08-04 11:57:54.209  7704  7704 V Avrcp   : start
,08-04 11:57:54.209  7704  7704 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-04 11:57:54.209  7704  7704 V Avrcp   : ++registerMediaPlayers++
,08-04 11:57:54.209  7704  7704 I Avrcp   : No of Audio players :: 2
,08-04 11:57:54.209  7704  7704 I Avrcp   : App Package name is com.google.android.music
,08-04 11:57:54.219  7704  7704 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,08-04 11:57:54.219  7704  7704 I Avrcp   : App pkg name is Google Play Music
,08-04 11:57:54.219  7704  7704 I Avrcp   : Name::Google Play Music
,08-04 11:57:54.219  7704  7704 V Avrcp   : MediaPlayerInfo: mPlayerId=1
08-04 11:57:54.219  7704  7704 I Avrcp   : App Package name is com.sec.android.app.music
,08-04 11:57:54.219  7704  7704 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,08-04 11:57:54.219  7704  7704 I Avrcp   : App pkg name is Music
,08-04 11:57:54.219  7704  7704 I Avrcp   : Name::Music
08-04 11:57:54.219  7704  7704 V Avrcp   : MediaPlayerInfo: mPlayerId=2
,08-04 11:57:54.229  7704  7704 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,08-04 11:57:54.229  7704  7704 I Avrcp   : No of Video players :: 1
,08-04 11:57:54.229  7704  7704 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
,08-04 11:57:54.229  7704  7704 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,08-04 11:57:54.229  7704  7704 I Avrcp   : Video App pkg name is Video Player
,08-04 11:57:54.229  7704  7704 I Avrcp   : Name::Video Player
08-04 11:57:54.229  7704  7704 V Avrcp   : MediaPlayerInfo: mPlayerId=3
08-04 11:57:54.229  7704  7704 I Avrcp   : Add tempPlayer
,08-04 11:57:54.229  7704  7704 V Avrcp   : MediaPlayerInfo: mPlayerId=4
08-04 11:57:54.229  7704  7704 I Avrcp   : Total no of players: 4
08-04 11:57:54.229  7704  7704 V Avrcp   : swapping the samsung player with 1st player
08-04 11:57:54.229  7704  7704 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-04 11:57:54.229  7704  8176 V Avrcp   : handleMessage, msg=207
,08-04 11:57:54.229  7704  8176 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-04 11:57:54.229  7704  7704 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-04 11:57:54.229  7704  7704 D A2dpStateMachine: make
,08-04 11:57:54.239  7704  7704 I bluedroid: get_profile_interface a2dp
,08-04 11:57:54.239  7704  8178 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-04 11:57:54.239  7704  7704 E bt-btif : warning : media task started media_task_refcnt 1 
,08-04 11:57:54.239  7704  7704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7f9795
,08-04 11:57:54.239  7704  8177 D A2dpStateMachine: Enter Disconnected: -2
,08-04 11:57:54.239  7704  7704 I BluetoothHidServiceJni: classInitNative: succeeds
08-04 11:57:54.239  7704  8176 D BluetoothMediaBrowser: no now playing list
08-04 11:57:54.239  7704  8176 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,08-04 11:57:54.239  7704  8176 D Avrcp   :  checkNowPlayingList start
,08-04 11:57:54.239  7704  7704 D HidService: Received start request. Starting profile...
,08-04 11:57:54.239  7704  7704 I bluedroid: get_profile_interface hidhost
08-04 11:57:54.239  7704  7704 D HidService: setHidService(): set to: null
08-04 11:57:54.239  7704  7704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7f9795
,08-04 11:57:54.239  7704  7704 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-04 11:57:54.239  7704  7704 E BluetoothAdapterService(243242901): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-04 11:57:54.239  7704  7704 D HealthService: Received start request. Starting profile...
,08-04 11:57:54.249  7704  7704 I bluedroid: get_profile_interface health
,08-04 11:57:54.249  7704  7704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7f9795
,08-04 11:57:54.249  7704  7704 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-04 11:57:54.249  7704  7704 D PanService: Received start request. Starting profile...
,08-04 11:57:54.249  7704  7704 D BluetoothPanServiceJni: initializeNative(L110): pan
08-04 11:57:54.249  7704  7704 I bluedroid: get_profile_interface pan
,08-04 11:57:54.249  7704  7704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7f9795
,08-04 11:57:54.249  7704  7704 D BluetoothMapService: Received start request. Starting profile...
,08-04 11:57:54.269  7704  7704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7f9795
,08-04 11:57:54.279  7704  7704 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-04 11:57:54.279  7704  7704 D SapService: Received start request. Starting profile...
08-04 11:57:54.279  7704  7704 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-04 11:57:54.279  7704  7704 I bluedroid: get_profile_interface sap
08-04 11:57:54.279  7704  7704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7f9795
,08-04 11:57:54.279  7704  7704 D HeadsetStateMachine: Try to query the phonestate on bind
,08-04 11:57:54.279  1403  1416 I Telecom : BluetoothPhoneService: queryPhoneState
,08-04 11:57:54.279  1403  1403 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-04 11:57:54.279  7704  7704 D HeadsetStateMachine: Proxy object connected
,08-04 11:57:54.279  7704  7704 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-04 11:57:54.279  7704  7704 D HeadsetPhoneState: sendDeviceDataStateChanged
08-04 11:57:54.279  7704  8175 D HeadsetStateMachine: Disconnected process message: 11
08-04 11:57:54.279  7704  7704 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-04 11:57:54.279  7704  7704 E BluetoothAdapterService(243242901): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-04 11:57:54.279  7704  8175 D HeadsetStateMachine: Disconnected process message: 18
08-04 11:57:54.279  7704  7704 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-04 11:57:54.279  7704  7704 D BluetoothA2dp: Proxy object connected
08-04 11:57:54.279  7704  7704 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-04 11:57:54.279  7704  7704 E BluetoothAdapterService(243242901): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-04 11:57:54.279  7704  8175 D HeadsetStateMachine: Disconnected process message: 10
,08-04 11:57:54.279  7704  8175 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-04 11:57:54.279  7704  8175 D HeadsetStateMachine: Disconnected process message: 11
,08-04 11:57:54.289  7704  7704 E BluetoothAdapterService(243242901): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-04 11:57:54.289  7704  7704 E BluetoothAdapterService(243242901): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-04 11:57:54.289  7704  7704 E BluetoothAdapterService(243242901): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-04 11:57:54.289  7704  7704 E BluetoothAdapterService(243242901): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-04 11:57:54.289  7704  7704 E BluetoothAdapterService(243242901): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-04 11:57:54.289  7704  8157 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,08-04 11:57:54.289  7704  8157 I bluedroid: enable
,08-04 11:57:54.289  7704  8182 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-04 11:57:54.289  7704  8157 I bt_hci_bdroid: init
,08-04 11:57:54.289  7704  8157 I bt_vendor: init
,08-04 11:57:54.289  7704  8157 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-04 11:57:54.289  7704  8157 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
08-04 11:57:54.289  7704  8157 D bt_userial: userial_init
08-04 11:57:54.289  7704  8157 D bt_vendor: op for 5
,08-04 11:57:54.289  7704  8157 D bt_vendor: op for 0
,08-04 11:57:54.289  7704  8157 D bt_upio : upio_set_bluetooth_power(on: 0)
08-04 11:57:54.289  7704  8157 D bt_upio : is_emulator_context : 0
08-04 11:57:54.289  7704  8157 D bt_upio : is_rfkill_disabled ? [0]
08-04 11:57:54.289  7704  8157 D bt_upio : is_rfkill_disabled ? [0]
,08-04 11:57:54.289  7704  8157 D bt_vendor: op for 0
,08-04 11:57:54.289  7704  8157 D bt_upio : upio_set_bluetooth_power(on: 1)
08-04 11:57:54.289  7704  8157 D bt_upio : is_emulator_context : 0
08-04 11:57:54.289  7704  8157 D bt_upio : is_rfkill_disabled ? [0]
,08-04 11:57:54.299  7704  8184 D bt_vendor: op for 3
08-04 11:57:54.299  7704  8184 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-04 11:57:54.299  7704  8184 I bt_userial_vendor: userial_vendor_open():UART is setup
,08-04 11:57:54.299  7704  8184 I bt_userial_vendor: device fd = 66 open
08-04 11:57:54.299  7704  8184 D bt_vendor: op for 1
08-04 11:57:54.299  7704  8185 D bt_userial: Entering userial_read_thread()
,08-04 11:57:54.299  7704  8184 E bt_hwcfg: Start CFG HW, HCI reset
,08-04 11:57:54.379  7704  8184 E bt_hwcfg: Read Local Name after HCI reset
,08-04 11:57:54.399  7704  8184 D bt_hwcfg: Chipset BCM4335C0
,08-04 11:57:54.399  7704  8184 D bt_hwcfg: Target name = [BCM4335C0]
08-04 11:57:54.399  7704  8184 I bt_hwcfg: module_type[semco].
08-04 11:57:54.399  7704  8184 I bt_hwcfg: not ZERO...
,08-04 11:57:54.399  7704  8184 I bt_hwcfg: module_type[semco] is invalid.
08-04 11:57:54.399  7704  8184 E bt_hwcfg: patchram path ORG . BCM4335C0
08-04 11:57:54.399  7704  8184 E bt_hwcfg: patchram path ORG .. BCM4335C0
08-04 11:57:54.399  7704  8184 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
08-04 11:57:54.399  7704  8184 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
,08-04 11:57:54.399  7704  8184 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
08-04 11:57:54.399  7704  8184 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
08-04 11:57:54.399  7704  8184 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335C0
08-04 11:57:54.399  7704  8184 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559_wisol.hcd BCM4335C0
08-04 11:57:54.399  7704  8184 E bt_hwcfg: fw ver (org)0.0
08-04 11:57:54.399  7704  8184 E bt_hwcfg: vendor lib preload failed to locate firmware patch file
,08-04 11:57:54.399  7704  8184 E bt_hwcfg: Remove module rev, try again BCM4335
08-04 11:57:54.399  7704  8184 D bt_hwcfg: Target name = [BCM4335]
08-04 11:57:54.399  7704  8184 I bt_hwcfg: module_type[semco].
08-04 11:57:54.399  7704  8184 I bt_hwcfg: not ZERO...
08-04 11:57:54.399  7704  8184 I bt_hwcfg: module_type[semco] is invalid.
08-04 11:57:54.399  7704  8184 E bt_hwcfg: patchram path ORG . BCM4335
,08-04 11:57:54.399  7704  8184 E bt_hwcfg: patchram path ORG .. BCM4335
08-04 11:57:54.399  7704  8184 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335
08-04 11:57:54.399  7704  8184 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
08-04 11:57:54.399  7704  8184 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335
08-04 11:57:54.399  7704  8184 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
08-04 11:57:54.399  7704  8184 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335
,08-04 11:57:54.399  7704  8184 I bt_hwcfg: patch(org) : bcm4335_V0111.0559.hcd
08-04 11:57:54.399  7704  8184 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4335_V0111.0559.hcd
08-04 11:57:54.399  7704  8184 E bt_hwcfg: ORG patchram base 0111
08-04 11:57:54.399  7704  8184 E bt_hwcfg: ORG patchram minor 0559
08-04 11:57:54.399  7704  8184 E bt_hwcfg: fw ver (org)111.559
08-04 11:57:54.399  7704  8184 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4335_V0111.0559.hcd
,08-04 11:57:54.409  7704  8184 I bt_hwcfg: Axi patch failure or not include AXI patching
,08-04 11:57:54.419  7704  8184 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 11:57:54.869  7704  8184 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-04 11:57:54.869  7704  8184 I bt_hwcfg: FW Download delta = 491090
,08-04 11:57:54.869  7704  8184 D bt_hwcfg: Settlement delay -- 100 ms
08-04 11:57:54.869  7704  8184 I bt_hwcfg: Setting fw settlement delay to 100 
,08-04 11:57:54.969  7704  8184 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 11:57:54.999  7704  8184 I bt_hwcfg: vendor lib fwcfg completed
,08-04 11:57:55.029  7704  8182 I         : BTE_InitTraceLevels -- TRC_HCI
,08-04 11:57:55.029  7704  8182 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-04 11:57:55.029  7704  8182 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,08-04 11:57:55.029  7704  8182 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-04 11:57:55.029  7704  8182 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-04 11:57:55.039  7704  8182 I         : BTE_InitTraceLevels -- TRC_A2D
08-04 11:57:55.039  7704  8182 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-04 11:57:55.039  7704  8182 I         : BTE_InitTraceLevels -- TRC_BTM
,08-04 11:57:55.039  7704  8182 I         : BTE_InitTraceLevels -- TRC_GAP
08-04 11:57:55.039  7704  8182 I         : BTE_InitTraceLevels -- TRC_PAN
,08-04 11:57:55.039  7704  8182 I         : BTE_InitTraceLevels -- TRC_SAP
08-04 11:57:55.039  7704  8182 I         : BTE_InitTraceLevels -- TRC_SDP
08-04 11:57:55.039  7704  8182 I         : BTE_InitTraceLevels -- TRC_GATT
,08-04 11:57:55.039  7704  8182 I         : BTE_InitTraceLevels -- TRC_SMP
08-04 11:57:55.039  7704  8182 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-04 11:57:55.039  7704  8182 I         : BTE_InitTraceLevels -- TRC_BTIF
08-04 11:57:55.039  7704  8182 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-04 11:57:55.249  7704  8182 W bt-l2cap: l2c_link_processs_ble_num_bufs 15
,08-04 11:57:55.249  7704  8182 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa1b64b5d 
,08-04 11:57:55.259  7704  8182 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa1b64b5d 
,08-04 11:57:55.479  7704  8160 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 1 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
,08-04 11:57:55.479  7704  8160 E bt-btif : Calling BTA_HhEnable
,08-04 11:57:55.479  7704  8160 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-04 11:57:55.479  7704  8160 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
,08-04 11:57:55.479  7704  8160 E BluetoothServiceJni: populateRssiValuesNative
08-04 11:57:55.479  7704  8160 I bluedroid: getModelRssiValues
08-04 11:57:55.479  7704  8160 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-04 11:57:55.479  7704  8160 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-04 11:57:55.479   765   765 D SettingsProvider: name = bluetooth_name
,08-04 11:57:55.489  7704  8160 D BluetoothAdapterProperties: Name is: Note3-1
,08-04 11:57:55.489  7704  8160 D BluetoothAdapterProperties: Scan Mode:20
,08-04 11:57:55.489  7704  8160 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-04 11:57:55.489  7704  8160 D BluetoothAdapterProperties: LE Address is:E0:B7:20:3E:93:BC
08-04 11:57:55.489  7704  8160 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-04 11:57:55.489  7704  8160 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-04 11:57:55.489  7704  8160 E bt-btif : btif_sock_init: !radio_req && !rfc_init
08-04 11:57:55.489  7704  8160 E bt-btif : btif_sock_init: !vhci_init
,08-04 11:57:55.489  7704  8160 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
08-04 11:57:55.489  7704  8160 D IOP_DB_BT: db_open: db_open : handle 3026681872l, read 14063 bytes onto local cache
,08-04 11:57:55.489  7704  8160 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-04 11:57:55.489  7704  8160 D IOP_DB_BT: db_query: result 1
,08-04 11:57:55.489  7704  8160 I         : iop_db_open: iop_db_open status 0
08-04 11:57:55.489  7704  8160 D bte_conf: Device ID record 1 : primary
08-04 11:57:55.489  7704  8160 D bte_conf:   vendorId            = 0075
,08-04 11:57:55.489  7704  8160 D bte_conf:   vendorIdSource      = 0001
08-04 11:57:55.489  7704  8160 D bte_conf:   product             = 0100
08-04 11:57:55.489  7704  8160 D bte_conf:   version             = 0200
08-04 11:57:55.489  7704  8160 D bte_conf:   clientExecutableURL = 
,08-04 11:57:55.489  7704  8160 D bte_conf:   serviceDescription  = 
,08-04 11:57:55.489  7704  8160 D bte_conf:   documentationURL    = 
,08-04 11:57:55.499  7704  8160 D bte_conf: bte_load_did_conf no section named DID2.
,08-04 11:57:55.499  7704  8184 D bt_vendor: op for 2
,08-04 11:57:55.499  7704  8184 D bt_vendor: op for 6
,08-04 11:57:55.499  7704  8184 D bt_vendor: op for 7
,08-04 11:57:55.499  7704  8184 D bt_upio : proc btwrite assertion
,08-04 11:57:55.499  7704  8160 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-04 11:57:55.499  7704  8184 D bt_vendor: op for 7
08-04 11:57:55.499  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.499  7704  8184 D bt_vendor: op for 7
,08-04 11:57:55.499  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.499  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:55.499  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:55.499  7704  8157 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-04 11:57:55.499  7704  8157 D BluetoothAdapterProperties: ScanMode =  20
08-04 11:57:55.499  7704  8157 D BluetoothAdapterProperties: State =  11
,08-04 11:57:55.509   765  1238 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-04 11:57:55.509  7704  8160 D BluetoothAdapterProperties: Scan Mode:21
,08-04 11:57:55.509  7704  8160 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-04 11:57:55.509  7704  8157 D BluetoothAdapterProperties: Setting state to 12
,08-04 11:57:55.509  7704  8157 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-04 11:57:55.509   765  1703 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-04 11:57:55.509   765  1703 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:57:55.509   765  1703 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:57:55.509   765  1703 D SettingsProvider: selectionArgs: false
,08-04 11:57:55.509   765  1703 D SettingsProvider: selectionArgs: 1002
08-04 11:57:55.509   765  1703 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:57:55.509   765  1703 D SettingsProvider: ret = -1
,08-04 11:57:55.509  7704  8157 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-04 11:57:55.509  7704  8157 D BluetoothAdapterService: updateAdapterState state is 12
,08-04 11:57:55.509   765  1330 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 11:57:55.519   765  1330 D ActivityManager: caller:android.app.ApplicationThreadProxy@17998567, r.packageName :com.android.bluetooth
,08-04 11:57:55.519  7704  8184 D bt_vendor: op for 7
,08-04 11:57:55.519  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.519  7704  8184 E bt_h4   : vendor lib postload completed
,08-04 11:57:55.519  7704  8184 D bt_vendor: op for 7
08-04 11:57:55.519  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.519   765  1059 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 11:57:55.519  7704  8184 D bt_vendor: op for 7
,08-04 11:57:55.519  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.519  1321  1373 E BluetoothHeadset: BluetoothHeadset service is binded
,08-04 11:57:55.519  7704  8157 D BluetoothAdapterService: Autoconnection is available 
08-04 11:57:55.519  7704  8157 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,08-04 11:57:55.519  7704  8184 D bt_vendor: op for 7
08-04 11:57:55.519  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.529  7704  8157 D BluetoothAdapterService: starting service from this receiver
,08-04 11:57:55.529   765   785 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 11:57:55.529   765   785 D ActivityManager: caller:android.app.ApplicationThreadProxy@332f1103, r.packageName :com.android.bluetooth
,08-04 11:57:55.529  7704  8184 D bt_vendor: op for 7
,08-04 11:57:55.529  7704  8184 D bt_upio : BT_WAKE is asserted already
08-04 11:57:55.529  7704  8157 I BluetoothAdapterState: Entering On State from state = 11
,08-04 11:57:55.529  7704  8184 D bt_vendor: op for 7
,08-04 11:57:55.529  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.529  1321  1361 D BluetoothMap: onBluetoothStateChange: up=true
,08-04 11:57:55.529  7704  8184 D bt_vendor: op for 7
,08-04 11:57:55.529  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.529  7704  8184 D bt_vendor: op for 7
,08-04 11:57:55.529  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.539   765  1059 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-04 11:57:55.539  7704  8184 D bt_vendor: op for 7
08-04 11:57:55.539  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.539  7704  8184 D bt_vendor: op for 7
,08-04 11:57:55.539  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.539  7704  8184 D bt_vendor: op for 7
,08-04 11:57:55.539  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.539  7704  8184 D bt_vendor: op for 7
,08-04 11:57:55.539  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.539  7704  8184 D bt_vendor: op for 7
,08-04 11:57:55.539  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.539  7704  8184 D bt_vendor: op for 7
,08-04 11:57:55.539  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.549  7704  8184 D bt_vendor: op for 7
,08-04 11:57:55.549  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.549  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:55.549  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:55.549  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:55.549  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 11:57:55.549  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:57:55.549  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:55.549  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:55.549  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 11:57:55.559  7704  8166 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 11:57:55.559  1321  1321 D HeadsetProfile: Bluetooth service connected
,08-04 11:57:55.559   765  1059 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 11:57:55.559  7704  8184 D bt_vendor: op for 7
08-04 11:57:55.559  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.559  7704  8184 D bt_vendor: op for 7
08-04 11:57:55.559  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.559  7704  8184 D bt_vendor: op for 7
08-04 11:57:55.559  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.559   765  1059 E BluetoothHeadset: BluetoothHeadset service is binded
,08-04 11:57:55.559   765  1059 D BluetoothPan: Binding service...
08-04 11:57:55.559  7704  8184 D bt_vendor: op for 7
08-04 11:57:55.559  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.569  7704  8184 D bt_vendor: op for 7
08-04 11:57:55.569   765  1059 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-04 11:57:55.569  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.569  7704  8184 D bt_vendor: op for 7
08-04 11:57:55.569  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.569  7235  7235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 11:57:55.569  7704  8184 D bt_vendor: op for 7
08-04 11:57:55.569  7704  8184 D bt_upio : BT_WAKE is asserted already
08-04 11:57:55.569  7704  7704 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-04 11:57:55.569  7704  8184 D bt_vendor: op for 7
08-04 11:57:55.569  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.569  1321  1337 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-04 11:57:55.569  7704  8184 D bt_vendor: op for 7
08-04 11:57:55.569  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.569  7704  8184 D bt_vendor: op for 7
08-04 11:57:55.569  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.579  7704  8184 D bt_vendor: op for 7,
08-04 11:57:55.579  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:55.579  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:55.579  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:55.579  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:55.579  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 11:57:55.579  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:57:55.579  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:55.579  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:55.579  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 11:57:55.579  7235  7235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 11:57:55.579   765  1059 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-04 11:57:55.589  7704  7704 I BluetoothPbapService: Handler(): got msg=1
,08-04 11:57:55.589   765  1449 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-04 11:57:55.589   765  1059 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 11:57:55.589  3222  3239 E BluetoothHeadset: BluetoothHeadset service is binded
,08-04 11:57:55.589  1321  1321 D BluetoothMap: Proxy object connected
08-04 11:57:55.589  1321  1321 D MapProfile: Bluetooth service connected
,08-04 11:57:55.589   765  1059 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 11:57:55.589  1403  7598 E BluetoothHeadset: BluetoothHeadset service is binded
08-04 11:57:55.589  3222  3239 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 11:57:55.589   765  1059 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-04 11:57:55.589  3222  3222 D BluetoothA2dp: Proxy object connected
,08-04 11:57:55.589   765   765 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 11:57:55.589   765  1059 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 11:57:55.599   765  1059 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-04 11:57:55.599  7704  8211 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-04 11:57:55.599   765   765 D BluetoothA2dp: Proxy object connected
,08-04 11:57:55.599  1321  1337 D BluetoothPbap: onBluetoothStateChange: up=true
,08-04 11:57:55.599   765  1059 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-04 11:57:55.599  7704  8211 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 11:57:55.599  1321  1337 D Bluetoothsap: onBluetoothStateChange: up=true
,08-04 11:57:55.599  1321  1337 D Bluetoothsap: Binding service...
08-04 11:57:55.599  7704  8211 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[73]}
08-04 11:57:55.599  7704  8211 D BluetoothSocket: bindListen(), new LocalSocket 
08-04 11:57:55.599  7704  8211 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-04 11:57:55.599  7704  8184 D bt_vendor: op for 7
08-04 11:57:55.599  7704  8184 D bt_upio : BT_WAKE is asserted already
08-04 11:57:55.599  7704  8211 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12fbd986
08-04 11:57:55.599  7704  8211 D BluetoothSocket: channel: 19
08-04 11:57:55.599  7704  8211 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-04 11:57:55.599  1321  1321 D BluetoothInputDevice: Proxy object connected
08-04 11:57:55.599  1321  1321 D HidProfile: Bluetooth service connected
,08-04 11:57:55.599  1321  1337 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-04 11:57:55.599   765  1059 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
08-04 11:57:55.599  1321  1337 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-04 11:57:55.599  1321  1361 D BluetoothPan: Binding service...
,08-04 11:57:55.599  1321  1321 D BluetoothPbap: Proxy object connected
08-04 11:57:55.599  1321  1321 D PbapServerProfile: Bluetooth service connected
08-04 11:57:55.599  1321  1321 D Bluetoothsap: BluetoothSAP Proxy object connected
08-04 11:57:55.599  1321  1321 D SapProfile: Bluetooth service connected
08-04 11:57:55.599  1321  1321 D Bluetoothsap: getConnectedDevices()
,08-04 11:57:55.609   765  1059 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-04 11:57:55.609  1321  1321 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 11:57:55.609  1321  1321 D PanProfile: Bluetooth service connected
,08-04 11:57:55.609   765  1059 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 11:57:55.609  1428  3561 E BluetoothHeadset: BluetoothHeadset service is binded
,08-04 11:57:55.609   765  1059 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 11:57:55.609  1403  1416 E BluetoothHeadset: BluetoothHeadset service is binded
,08-04 11:57:55.609  1321  1337 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 11:57:55.609   765  1059 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-04 11:57:55.609  1321  1321 D BluetoothA2dp: Proxy object connected
08-04 11:57:55.609  1321  1321 D A2dpProfile: Bluetooth service connected
,08-04 11:57:55.609   765  1059 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 11:57:55.609  1403  7598 E BluetoothHeadset: BluetoothHeadset service is binded
08-04 11:57:55.609   765  1059 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-04 11:57:55.609   765   765 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:55.609   765   765 I InputMethodManagerService: [BT Setting State] State =12
08-04 11:57:55.609   765   765 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-04 11:57:55.619  1403  1403 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2dfecc7b, true
,08-04 11:57:55.619  1195  1195 D BluetoothTile:  onBluetoothStateChange:
,08-04 11:57:55.619  1403  1403 D BluetoothHeadset: registerMessageListener
,08-04 11:57:55.619  1321  1321 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-04 11:57:55.619  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:55.619  7620  7620 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:55.619  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-04 11:57:55.619  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:55.619  1750  1750 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
08-04 11:57:55.619  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:55.619   765  1476 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,08-04 11:57:55.619   765  1059 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-04 11:57:55.619  7704  7717 D HeadsetService: registerMessageListener
,08-04 11:57:55.619  7704  7717 D HeadsetService: registerMessageListener
08-04 11:57:55.619  7704  8175 D HeadsetStateMachine: Disconnected process message: 70
08-04 11:57:55.619  1403  1403 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-04 11:57:55.619   765  1330 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-04 11:57:55.619  7704  8175 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1526a247
08-04 11:57:55.619  1403  1403 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
08-04 11:57:55.619  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,08-04 11:57:55.629   765  3205 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-04 11:57:55.629   765  3205 D ActivityManager: caller:android.app.ApplicationThreadProxy@2c5825a4, r.packageName :com.google.android.gms
,08-04 11:57:55.629  1195  1604 D BluetoothTile:  handleUpdatestate:false name:null
08-04 11:57:55.629  1195  1604 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-04 11:57:55.629  7704  8218 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-04 11:57:55.629  1321  1321 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,08-04 11:57:55.629  1321  1321 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-04 11:57:55.629  7704  8175 D HeadsetStateMachine: Disconnected process message: 9
,08-04 11:57:55.629  7704  8175 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-04 11:57:55.629  7704  8218 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 11:57:55.629  7704  8184 D bt_vendor: op for 7
08-04 11:57:55.629  7704  8184 D bt_upio : BT_WAKE is asserted already
08-04 11:57:55.629  7704  8218 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
08-04 11:57:55.629  7704  8218 D BluetoothSocket: bindListen(), new LocalSocket 
08-04 11:57:55.629  7704  8218 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-04 11:57:55.629  7704  8218 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10ceea74
08-04 11:57:55.629  7704  8218 D BluetoothSocket: channel: 5
,08-04 11:57:55.639   309   693 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-04 11:57:55.639   309   693 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-04 11:57:55.639   309   693 V voice   : voice_set_parameters: exit with code(-2)
08-04 11:57:55.639   309   693 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-04 11:57:55.639   309   693 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-04 11:57:55.639   309   693 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-04 11:57:55.639   309   693 V audio_hw_primary: adev_set_parameters: exit
,08-04 11:57:55.639  7704  8175 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
08-04 11:57:55.639  1321  1321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-04 11:57:55.639   765  1703 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-04 11:57:55.639   765  1703 D ActivityManager: caller:android.app.ApplicationThreadProxy@1e0f34d3, r.packageName :com.android.settings
08-04 11:57:55.639  1321  1321 D DockEventReceiver: finishStartingService: stopping service
08-04 11:57:55.649  1321  1321 D BluetoothNotiBroadcastReceiver: onReceive
08-04 11:57:55.649  7704  7704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7f9795
08-04 11:57:55.649  7704  7704 D BtConfig.SecureMode: isSecureModeOn:false
08-04 11:57:55.649   765  1652 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 11:57:55.649   765  1652 D ActivityManager: caller:android.app.ApplicationThreadProxy@2165af09, r.packageName :com.android.bluetooth
08-04 11:57:55.659  1864  1864 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-04 11:57:55.659   765  1330 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-04 11:57:55.659   765  1330 D ActivityManager: caller:android.app.ApplicationThreadProxy@78e4b2f, r.packageName :com.google.android.gms
08-04 11:57:55.669  1864  8224 D EasyUnlockInitService: Handling intent for initializer IntentService.
08-04 11:57:55.669   765  1573 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
08-04 11:57:55.669  1864  1864 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-04 11:57:55.679   303   303 E SMD     : DCD ON
08-04 11:57:55.689  7704  8228 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 11:57:55.689   765  1263 D ActivityManager: caller:android.app.ApplicationThreadProxy@22867127, r.packageName :com.google.android.gms
08-04 11:57:55.689  7704  8184 D bt_vendor: op for 7
08-04 11:57:55.689  7704  8184 D bt_upio : BT_WAKE is asserted already
08-04 11:57:55.689  7704  8228 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-04 11:57:55.689  7704  8228 D BluetoothSocket: bindListen(), new LocalSocket 
08-04 11:57:55.689  7704  8228 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-04 11:57:55.689  7704  8228 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@312a39e0
08-04 11:57:55.689  7704  8228 D BluetoothSocket: channel: 12
08-04 11:57:55.689  7704  8228 I BtOppRfcommListener: Accept thread started.
08-04 11:57:55.699  1864  8224 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-04 11:57:57.029  7235  7294 D BluetoothAdapter: disable()
,08-04 11:57:57.029   765  1330 D SettingsProvider: name = bluetooth_on
,08-04 11:57:57.049  7704  8157 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-04 11:57:57.059  7704  8157 D BluetoothAdapterProperties: Setting state to 13
,08-04 11:57:57.059  7704  8157 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-04 11:57:57.059  7704  8157 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-04 11:57:57.059  7704  8157 D BluetoothAdapterService: updateAdapterState state is 13
,08-04 11:57:57.059   765  1238 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 11:57:57.059   765  1238 D ActivityManager: caller:android.app.ApplicationThreadProxy@5bff57d, r.packageName :com.android.bluetooth
,08-04 11:57:57.059  7704  8157 D BluetoothAdapterService: Autoconnection is available 
,08-04 11:57:57.059  7704  8157 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-04 11:57:57.059  7704  8157 D BluetoothAdapterService: terminating service from this receiver
,08-04 11:57:57.059  7704  8157 D BluetoothAdapterProperties: onBluetoothDisable()
,08-04 11:57:57.059   765   784 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-04 11:57:57.069  7704  8157 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-04 11:57:57.069  7704  8184 D bt_vendor: op for 7
,08-04 11:57:57.069  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:57.069  7704  8184 D bt_vendor: op for 7
,08-04 11:57:57.069  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:57.069  7704  8184 D bt_vendor: op for 7
,08-04 11:57:57.069  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:57.069  7704  8160 D BluetoothAdapterProperties: Scan Mode:20
,08-04 11:57:57.069  7704  8157 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-04 11:57:57.069  7704  8157 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-04 11:57:57.069  7704  8157 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-04 11:57:57.069  7704  8157 E bt-btif : cmd socket is not created
,08-04 11:57:57.079  7704  8228 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-04 11:57:57.079  7704  8182 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
,08-04 11:57:57.079  7704  8184 D bt_vendor: op for 7
08-04 11:57:57.079  7704  8184 D bt_upio : BT_WAKE is asserted already
08-04 11:57:57.079  7704  8182 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-04 11:57:57.079  7704  8182 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 11:57:57.079  7704  8182 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 11:57:57.079  7704  8182 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-04 11:57:57.079  7704  8157 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-04 11:57:57.079  7704  8184 D bt_vendor: op for 7
08-04 11:57:57.079  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:57.079  7704  8184 D bt_vendor: op for 7
,08-04 11:57:57.079  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:57.079  7704  8184 D bt_vendor: op for 7
,08-04 11:57:57.079  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:57.089  7704  8184 D bt_vendor: op for 7
,08-04 11:57:57.089  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:57.089  7704  7704 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-04 11:57:57.089  7704  8184 D bt_vendor: op for 7
,08-04 11:57:57.089  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:57.089  7704  8184 D bt_vendor: op for 7
,08-04 11:57:57.089  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:57.089  7704  8184 D bt_vendor: op for 7
,08-04 11:57:57.089  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:57.089  7704  8184 D bt_vendor: op for 7
,08-04 11:57:57.089  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:57.089  7704  8184 D bt_vendor: op for 7
,08-04 11:57:57.089  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:57.099  7704  8184 D bt_vendor: op for 7
08-04 11:57:57.099  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:57.099  7704  7704 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2fdd1499, channel: 19, state: LISTENING
08-04 11:57:57.099  7704  7704 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2fdd1499, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12fbd986, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@4be935emSocket: android.net.LocalSocket@2ebf933f impl:android.net.LocalSocketImpl@2829140c fd:FileDescriptor[73]
,08-04 11:57:57.099  7704  7704 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2ebf933f impl:android.net.LocalSocketImpl@2829140c fd:FileDescriptor[73]
,08-04 11:57:57.099  7704  8184 D bt_vendor: op for 7
,08-04 11:57:57.099  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:57.099  7235  7235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 11:57:57.099  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:57.099  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:57.099  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:57.099  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 11:57:57.099  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:57.099  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:57.099  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:57.099  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 11:57:57.099  7235  7235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 11:57:57.109  7235  7235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 11:57:57.109  7235  7235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 11:57:57.109  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:57:57.109  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:57:57.109  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:57:57.109  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 11:57:57.109  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 11:57:57.109  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:57:57.109  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:57:57.109  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 11:57:57.109  7235  7235 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 11:57:57.109  7235  7235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 11:57:57.109   765   765 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-04 11:57:57.119  1195  1195 D BluetoothTile:  onBluetoothStateChange:
,08-04 11:57:57.119   765   765 I InputMethodManagerService: [BT Setting State] State =13
,08-04 11:57:57.119  7704  7704 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@a5c876a, channel: 5, state: LISTENING
,08-04 11:57:57.119  7704  7704 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@a5c876a, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@10ceea74, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@a4245bmSocket: android.net.LocalSocket@25964f8 impl:android.net.LocalSocketImpl@ca3bdd1 fd:FileDescriptor[75]
08-04 11:57:57.119  7704  7704 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@25964f8 impl:android.net.LocalSocketImpl@ca3bdd1 fd:FileDescriptor[75]
,08-04 11:57:57.119  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-04 11:57:57.119  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-04 11:57:57.119  1195  1604 D BluetoothTile:  handleUpdatestate:false name:null
,08-04 11:57:57.119  1195  1604 D BluetoothTile:  handleUpdatestate:false name:null
,08-04 11:57:57.119   765  1476 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,08-04 11:57:57.119   765  1652 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-04 11:57:57.119  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,08-04 11:57:57.129  7620  7620 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,08-04 11:57:57.129  1750  1750 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-04 11:57:57.129  1195  1604 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-04 11:57:57.129  7704  7704 I BtOppRfcommListener: stopping Accept Thread
08-04 11:57:57.129  7704  7704 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2633b036, channel: 12, state: LISTENING
,08-04 11:57:57.129  7704  7704 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2633b036, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@312a39e0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@376ab37mSocket: android.net.LocalSocket@53bd8a4 impl:android.net.LocalSocketImpl@2955660d fd:FileDescriptor[77]
08-04 11:57:57.129  7704  7704 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@53bd8a4 impl:android.net.LocalSocketImpl@2955660d fd:FileDescriptor[77]
,08-04 11:57:57.129  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:57.129  7704  8228 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-04 11:57:57.129  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:57.129  1321  1321 D BluetoothPbap: Proxy object disconnected
,08-04 11:57:57.129  1321  1321 D PbapServerProfile: Bluetooth service disconnected
08-04 11:57:57.129  1321  1321 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-04 11:57:57.129   765   784 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-04 11:57:57.139   765   784 D ActivityManager: caller:android.app.ApplicationThreadProxy@b35cc72, r.packageName :com.google.android.gms
,08-04 11:57:57.139  1321  1321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 11:57:57.139   765  1476 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-04 11:57:57.139   765  1476 D ActivityManager: caller:android.app.ApplicationThreadProxy@e0d8540, r.packageName :com.android.settings
,08-04 11:57:57.149  1321  1321 D DockEventReceiver: finishStartingService: stopping service
,08-04 11:57:57.149  1321  1321 D BluetoothNotiBroadcastReceiver: onReceive
,08-04 11:57:57.159  1864  1864 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-04 11:57:57.169  1864  1864 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-04 11:57:57.229  7704  8184 D bt_vendor: op for 6
,08-04 11:57:57.229  7704  8185 D bt_userial: RX termination
08-04 11:57:57.229  7704  8182 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 11:57:57.229  7704  8182 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 11:57:57.229  7704  8182 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 11:57:57.229  7704  8182 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 11:57:57.229  7704  8182 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 11:57:57.229  7704  8182 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 11:57:57.229  7704  8182 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 11:57:57.229  7704  8182 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 11:57:57.229  7704  8182 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 11:57:57.229  7704  8182 W bt-btif : ag scb idx 1 not allocated
08-04 11:57:57.229  7704  8182 W bt-btif : ag scb idx 2 not allocated
08-04 11:57:57.229  7704  8182 E bt-btif : BTA AG is already disabled, ignoring ...
08-04 11:57:57.229  7704  8184 D bt_vendor: op for 7
08-04 11:57:57.229  7704  8184 D bt_upio : BT_WAKE is asserted already
,08-04 11:57:57.229  7704  8185 W bt_userial: select_read return size <=0:-1, exiting userial_read_thread
08-04 11:57:57.229  7704  8185 D bt_userial: Leaving userial_read_thread()
08-04 11:57:57.229  7704  8160 D bt_userial: userial_close_reader Joined userial reader thread: 0
08-04 11:57:57.229  7704  8184 D bt_vendor: op for 9
08-04 11:57:57.229  7704  8184 D bt_hwcfg: hw_epilog_process
08-04 11:57:57.229  7704  8160 D bt_vendor: op for 4
08-04 11:57:57.229  7704  8160 I bt_userial_vendor: device fd = 66 close
,08-04 11:57:57.229  7704  8160 D bt_vendor: op for 0
,08-04 11:57:57.229  7704  8160 D bt_upio : upio_set_bluetooth_power(on: 0)
08-04 11:57:57.229  7704  8160 D bt_upio : is_emulator_context : 0
08-04 11:57:57.229  7704  8160 D bt_upio : is_rfkill_disabled ? [0]
,08-04 11:57:57.239  7704  8160 D bt_vendor: cleanup
,08-04 11:57:57.239  7704  8182 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-04 11:57:57.239  7704  8160 I GKI_LINUX: GKI_exit_task 0 done
08-04 11:57:57.239  7704  8160 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-04 11:57:57.239  7704  8157 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-04 11:57:57.239  7704  8157 D BtConfig.SecureMode: isSecureModeOn:false
08-04 11:57:57.239  7704  8157 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-04 11:57:57.239  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-04 11:57:57.239   765  1444 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 11:57:57.239   765  1444 D ActivityManager: caller:android.app.ApplicationThreadProxy@c103dbe, r.packageName :com.android.bluetooth
08-04 11:57:57.239  7704  7704 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-04 11:57:57.239  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-04 11:57:57.239   765  1263 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 11:57:57.239   765  1263 D ActivityManager: caller:android.app.ApplicationThreadProxy@14ae5e1f, r.packageName :com.android.bluetooth
,08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-04 11:57:57.239  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-04 11:57:57.239   765  1449 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 11:57:57.239   765  1449 D ActivityManager: caller:android.app.ApplicationThreadProxy@19e5b56c, r.packageName :com.android.bluetooth
,08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-04 11:57:57.239  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-04 11:57:57.239   765  1330 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 11:57:57.239   765  1330 D ActivityManager: caller:android.app.ApplicationThreadProxy@19d5735, r.packageName :com.android.bluetooth
,08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-04 11:57:57.239  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-04 11:57:57.239   765   784 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 11:57:57.239   765   784 D ActivityManager: caller:android.app.ApplicationThreadProxy@88e77ca, r.packageName :com.android.bluetooth
,08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-04 11:57:57.239  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-04 11:57:57.239   765  1652 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 11:57:57.239   765  1652 D ActivityManager: caller:android.app.ApplicationThreadProxy@3d64bd3b, r.packageName :com.android.bluetooth
,08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-04 11:57:57.239  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-04 11:57:57.239   765  1703 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 11:57:57.239   765  1703 D ActivityManager: caller:android.app.ApplicationThreadProxy@2c2ebc58, r.packageName :com.android.bluetooth
08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-04 11:57:57.239  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-04 11:57:57.239   765  3205 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 11:57:57.239   765  3205 D ActivityManager: caller:android.app.ApplicationThreadProxy@115931b1, r.packageName :com.android.bluetooth
08-04 11:57:57.239  7704  7704 D BtGatt.GattService: Received stop request...Stopping profile...
08-04 11:57:57.239  7704  7704 D BtGatt.GattService: stop()
08-04 11:57:57.239  7704  7704 D BtGatt.AdvertiseManager: advertise clients cleared
08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-04 11:57:57.239  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-04 11:57:57.239  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-04 11:57:57.239  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-04 11:57:57.239  7704  8157 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-04 11:57:57.239  7704  8157 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,08-04 11:57:57.239  7704  8157 D BluetoothAdapterState: Stopping profile services that were post enabled
08-04 11:57:57.239  7704  7704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7f9795
08-04 11:57:57.239  7704  7704 D HeadsetService: Received stop request...Stopping profile...
,08-04 11:57:57.249  7704  7704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7f9795
,08-04 11:57:57.249  1321  1321 D HeadsetProfile: Bluetooth service disconnected
,08-04 11:57:57.249  7620  7620 W BluetoothHeadset: Proxy not attached to service
,08-04 11:57:57.249   765   765 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-04 11:57:57.249  7704  7704 D A2dpService: Received stop request...Stopping profile...
,08-04 11:57:57.249  7704  8177 D A2dpStateMachine: Exit Disconnected: -1
08-04 11:57:57.249  7704  7704 V Avrcp   : doQuit
,08-04 11:57:57.249  7704  7704 D Avrcp   : Unregistering previous receiver
,08-04 11:57:57.249  7704  7704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7f9795
,08-04 11:57:57.249  3222  3222 D BluetoothA2dp: Proxy object disconnected
,08-04 11:57:57.249  1321  1321 D BluetoothA2dp: Proxy object disconnected
08-04 11:57:57.249  1321  1321 D A2dpProfile: Bluetooth service disconnected
08-04 11:57:57.249   765   765 D BluetoothA2dp: Proxy object disconnected
08-04 11:57:57.249   765   765 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-04 11:57:57.249  7704  7704 D HidService: Received stop request...Stopping profile...
,08-04 11:57:57.249  7704  7704 D HidService: Stopping Bluetooth HidService
08-04 11:57:57.249  7704  7704 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-04 11:57:57.249  7704  7704 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-04 11:57:57.249  7704  7704 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-04 11:57:57.249  7704  7704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7f9795
,08-04 11:57:57.249  1321  1321 D BluetoothInputDevice: Proxy object disconnected
08-04 11:57:57.249  7704  7704 D HealthService: Received stop request...Stopping profile...
08-04 11:57:57.249  7704  7704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7f9795
,08-04 11:57:57.249  1321  1321 D HidProfile: Bluetooth service disconnected
,08-04 11:57:57.249  7704  7704 D PanService: Received stop request...Stopping profile...
08-04 11:57:57.249  7704  7704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7f9795
,08-04 11:57:57.249  1321  1321 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-04 11:57:57.259   765   765 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-04 11:57:57.259  1321  1321 D PanProfile: Bluetooth service disconnected
,08-04 11:57:57.259  7704  7704 D BluetoothMapService: Received stop request...Stopping profile...
,08-04 11:57:57.259  7704  7704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7f9795
,08-04 11:57:57.259  1321  1321 D BluetoothMap: Proxy object disconnected
08-04 11:57:57.259  1321  1321 D MapProfile: Bluetooth service disconnected
,08-04 11:57:57.259  7704  7704 D SapService: Received stop request...Stopping profile...
08-04 11:57:57.259  7704  7704 D SapService: Stopping Bluetooth SapService
08-04 11:57:57.259  7704  7704 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e7f9795
,08-04 11:57:57.259  1321  1321 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-04 11:57:57.259  1321  1321 D SapProfile: Bluetooth service disconnected
08-04 11:57:57.259  7704  7704 E BluetoothAdapterService(243242901): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-04 11:57:57.259  7704  7704 E BluetoothAdapterService(243242901): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-04 11:57:57.259  7704  7704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-04 11:57:57.259  7704  7704 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-04 11:57:57.259  7704  7704 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-04 11:57:57.259  7704  7704 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 11:57:57.259  7704  7704 E BluetoothAdapterService(243242901): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-04 11:57:57.259  7704  7704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-04 11:57:57.259  7704  7704 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-04 11:57:57.259  7704  7704 D BluetoothA2dp: Proxy object disconnected
08-04 11:57:57.259  7704  7704 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-04 11:57:57.259  7704  8178 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,08-04 11:57:57.259  7704  7704 I GKI_LINUX: GKI_exit_task 2 done
08-04 11:57:57.259  7704  7704 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-04 11:57:57.259  7704  7704 V Avrcp   : cleanup
08-04 11:57:57.259  7704  7704 E BluetoothAdapterService(243242901): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-04 11:57:57.259  7704  7704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-04 11:57:57.259  7704  7704 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,08-04 11:57:57.259  7704  7704 E BluetoothAdapterService(243242901): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-04 11:57:57.259  7704  7704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-04 11:57:57.259  7704  7704 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-04 11:57:57.259  7704  7704 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-04 11:57:57.259  7704  7704 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 11:57:57.259  7704  7704 E BluetoothAdapterService(243242901): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-04 11:57:57.259  7704  7704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-04 11:57:57.259  7704  7704 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-04 11:57:57.259  7704  7704 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-04 11:57:57.259  7704  7704 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-04 11:57:57.259  7704  7704 E BluetoothAdapterService(243242901): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-04 11:57:57.259  7704  7704 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-04 11:57:57.259  7704  7704 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-04 11:57:57.259  7704  7704 E BluetoothAdapterService(243242901): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-04 11:57:57.259  7704  7704 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-04 11:57:57.259  7704  7704 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-04 11:57:57.259  7704  8157 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-04 11:57:57.259  7704  8157 D BluetoothAdapterProperties: Setting state to 10
08-04 11:57:57.259  7704  8157 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-04 11:57:57.259  7704  8157 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-04 11:57:57.259  7704  8157 D BluetoothAdapterService: updateAdapterState state is 10
08-04 11:57:57.259  7704  8157 D BluetoothAdapterService: Autoconnection is available 
08-04 11:57:57.259  7704  8157 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-04 11:57:57.259  7704  8157 I BluetoothAdapterState: Entering OffState
08-04 11:57:57.269  1321  1373 D BluetoothMap: onBluetoothStateChange: up=false
08-04 11:57:57.269  7704  8166 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 11:57:57.269  1321  1361 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-04 11:57:57.269  3222  3239 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 11:57:57.269   765  1059 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 11:57:57.269  1321  1337 D BluetoothPbap: onBluetoothStateChange: up=false
08-04 11:57:57.269  1321  1373 D Bluetoothsap: onBluetoothStateChange: up=false
08-04 11:57:57.269  1321  1373 D Bluetoothsap: Unbinding service...
,08-04 11:57:57.269  1321  1337 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-04 11:57:57.269   765  1059 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 13 receivers.
,08-04 11:57:57.269   765  1059 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-04 11:57:57.279   765   765 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:57.279   765   765 I InputMethodManagerService: [BT Setting State] State =10
08-04 11:57:57.279   765   765 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-04 11:57:57.279  1195  1195 D BluetoothAdapter: 297313051: getState() :  mService = null. Returning STATE_OFF
08-04 11:57:57.279  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-04 11:57:57.279  1195  1604 D BluetoothAdapter: 297313051: getState() :  mService = null. Returning STATE_OFF
08-04 11:57:57.279  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:57.279  1195  1195 D BluetoothAdapter: 297313051: getState() :  mService = null. Returning STATE_OFF
08-04 11:57:57.279  7704  8160 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-04 11:57:57.279  1195  1604 D BluetoothAdapter: 297313051: getState() :  mService = null. Returning STATE_OFF
08-04 11:57:57.279  1195  1604 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-04 11:57:57.279  1195  1195 D BluetoothAdapter: 297313051: getState() :  mService = null. Returning STATE_OFF
,08-04 11:57:57.279   765  1232 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
08-04 11:57:57.279   765  3205 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-04 11:57:57.279  7704  7704 I GKI_LINUX: GKI_exit_task 1 done
08-04 11:57:57.279  7704  7704 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-04 11:57:57.279  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,08-04 11:57:57.279  7704  7704 I BluetoothServiceJni: cleanupNative: return from cleanup
08-04 11:57:57.279  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,08-04 11:57:57.279   765  1330 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-04 11:57:57.279  1864  2360 D BluetoothAdapter: 1072597014: getState() :  mService = null. Returning STATE_OFF
08-04 11:57:57.279  1864  2360 D BluetoothAdapter: 1072597014: getState() :  mService = null. Returning STATE_OFF
08-04 11:57:57.279   765  1330 D ActivityManager: caller:android.app.ApplicationThreadProxy@30044696, r.packageName :com.google.android.gms
,08-04 11:57:57.279  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:57:57.279  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:57:57.279  1750  1750 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-04 11:57:57.279  7620  7620 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:57:57.279  1321  1321 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-04 11:57:57.279  1321  1321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 11:57:57.279   765   785 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-04 11:57:57.279   765   785 D ActivityManager: caller:android.app.ApplicationThreadProxy@2eff4604, r.packageName :com.android.settings
,08-04 11:57:57.289  7704  7704 I art     : System.exit called, status: 0
08-04 11:57:57.289  7704  7704 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-04 11:57:57.289  1321  1321 D DockEventReceiver: finishStartingService: stopping service
,08-04 11:57:57.289  1321  1321 D BluetoothNotiBroadcastReceiver: onReceive
,08-04 11:57:57.319   765  3091 D SSRM:n  : SIOP:: AP = 370, PST = 349, CUR = 450
,08-04 11:57:57.329   765  1573 I ActivityManager: Process com.android.bluetooth (pid 7704)(adj 0) has died(213,1572)
,08-04 11:57:57.339  1864  1864 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-04 11:57:57.339   765  1449 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-04 11:57:57.339   765  1449 D ActivityManager: caller:android.app.ApplicationThreadProxy@352cbe70, r.packageName :com.google.android.gms
,08-04 11:57:57.339  1864  8262 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-04 11:57:57.349  1864  1864 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-04 11:57:57.349   765  3205 D ActivityManager: caller:android.app.ApplicationThreadProxy@30a5926e, r.packageName :com.google.android.gms
,08-04 11:57:57.359  1864  8262 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-04 11:57:58.679   303   303 E SMD     : DCD ON
,08-04 11:58:00.000   765  1117 V AlarmManager: waitForAlarm result :8
,08-04 11:58:00.129  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 11:58:00.129  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 11:58:01.680   303   303 E SMD     : DCD ON
,08-04 11:58:02.869   362   362 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
08-04 11:58:02.869   362   362 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,08-04 11:58:03.140  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 11:58:03.140  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13a8e746 added. We now have 6 listener(s)
,08-04 11:58:03.140  7235  7294 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 11:58:03.150  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 11:58:03.150  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3b85fd07 added. We now have 7 listener(s)
08-04 11:58:03.150  7235  7294 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 11:58:03.150  7235  7294 I System.out: IsBluetoothEnabled
,08-04 11:58:03.150  7235  7294 D BluetoothAdapter: disable()
,08-04 11:58:03.150   765  1449 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-04 11:58:03.160  7235  7294 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:58:03.160  7235  7294 D BluetoothAdapter: enable()
,08-04 11:58:03.160   765  1238 W ActivityManager: Permission Denial: getCurrentUser() from pid=7235, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,08-04 11:58:03.160   765  1238 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-04 11:58:03.160   765  1238 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7235, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-04 11:58:03.160   765  1238 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
08-04 11:58:03.160   765  1238 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
08-04 11:58:03.160   765  1238 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
08-04 11:58:03.160   765  1238 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-04 11:58:03.160   765  1238 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-04 11:58:03.160   765  1238 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-04 11:58:03.160   765  1238 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-04 11:58:03.160   765  1238 D SettingsProvider: name = bluetooth_on
,08-04 11:58:03.170   765  1059 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-04 11:58:03.170   765  1059 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-04 11:58:03.170   765  1059 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-04 11:58:03.170   765  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:58:03.170   765  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:58:03.170   765  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:58:03.170   765  1059 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:58:03.220  8273  8273 E Zygote  : MountEmulatedStorage()
,08-04 11:58:03.220  8273  8273 E Zygote  : v2
08-04 11:58:03.220  8273  8273 I libpersona: KNOX_SDCARD checking this for 1002
08-04 11:58:03.220  8273  8273 I libpersona: KNOX_SDCARD not a persona
,08-04 11:58:03.220   765  1059 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=8273 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-04 11:58:03.230  8273  8273 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:58:03.230  8273  8273 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 11:58:03.230  8273  8273 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 11:58:03.269  8273  8273 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:58:03.269  8273  8273 D ActivityThread: Added TimaKeyStore provider
,08-04 11:58:03.289  8273  8273 D ResourcesManager: creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,08-04 11:58:03.289  8273  8273 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-04 11:58:03.289  8273  8273 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-04 11:58:03.319  8273  8273 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-04 11:58:03.339  8273  8273 D BtSettings.ProfileConfig: Adding GattService
,08-04 11:58:03.349  8273  8273 D BtSettings.ProfileConfig: Adding HeadsetService
,08-04 11:58:03.349  8273  8273 D BtSettings.ProfileConfig: Adding A2dpService
,08-04 11:58:03.349  8273  8273 D BtSettings.ProfileConfig: Adding HidService
,08-04 11:58:03.349  8273  8273 D BtSettings.ProfileConfig: Adding HealthService
08-04 11:58:03.349  8273  8273 D BtSettings.ProfileConfig: Adding PanService
,08-04 11:58:03.349  8273  8273 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-04 11:58:03.349  8273  8273 D BtSettings.ProfileConfig: Adding SapService
,08-04 11:58:03.349  8273  8273 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-04 11:58:03.349  8273  8273 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-04 11:58:03.349  8273  8273 D BtSettings.ProfileConfig: Adding SapClientService
,08-04 11:58:03.349  8273  8273 D BtSettings.ProfileConfig: Adding HidDevService
,08-04 11:58:03.349  8273  8273 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-04 11:58:03.349   765  1652 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-04 11:58:03.349   765  1652 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:58:03.349   765  1652 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:58:03.349   765  1652 D SettingsProvider: selectionArgs: false
08-04 11:58:03.349   765  1652 D SettingsProvider: selectionArgs: 1002
08-04 11:58:03.359   765  1652 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-04 11:58:03.359   765  1652 D SettingsProvider: ret = -1
,08-04 11:58:03.359   765  1263 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-04 11:58:03.359   765  1263 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:58:03.359   765  1263 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:58:03.359   765  1263 D SettingsProvider: selectionArgs: false
,08-04 11:58:03.359   765  1263 D SettingsProvider: selectionArgs: 1002
,08-04 11:58:03.359   765  1263 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-04 11:58:03.359   765  1263 D SettingsProvider: ret = -1
,08-04 11:58:03.359   765  1703 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-04 11:58:03.359   765  1703 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:58:03.359   765  1703 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:58:03.359   765  1703 D SettingsProvider: selectionArgs: false
08-04 11:58:03.359   765  1703 D SettingsProvider: selectionArgs: 1002
08-04 11:58:03.359   765  1703 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:58:03.359   765  1703 D SettingsProvider: ret = -1
08-04 11:58:03.359   765  1680 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-04 11:58:03.359   765  1680 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:58:03.359   765  1680 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:58:03.359   765  1680 D SettingsProvider: selectionArgs: false
08-04 11:58:03.359   765  1680 D SettingsProvider: selectionArgs: 1002
08-04 11:58:03.359   765  1680 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:58:03.359   765  1680 D SettingsProvider: ret = -1
08-04 11:58:03.359   765   785 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-04 11:58:03.359   765   785 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:58:03.359   765   785 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:58:03.359   765   785 D SettingsProvider: selectionArgs: false
08-04 11:58:03.359   765   785 D SettingsProvider: selectionArgs: 1002
08-04 11:58:03.359   765   785 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:58:03.359   765   785 D SettingsProvider: ret = -1
,08-04 11:58:03.359   765  3205 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-04 11:58:03.359   765  3205 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:58:03.359   765  3205 D SettingsProvider: projectionArgs: isSettingsChangesAllowed,
08-04 11:58:03.359   765  3205 D SettingsProvider: selectionArgs: false
08-04 11:58:03.359   765  3205 D SettingsProvider: selectionArgs: 1002
,08-04 11:58:03.359   765  3205 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:58:03.359   765  3205 D SettingsProvider: ret = -1
,08-04 11:58:03.359   765  1352 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-04 11:58:03.359   765  1352 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3,
08-04 11:58:03.359   765  1352 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-04 11:58:03.359   765  1352 D SettingsProvider: selectionArgs: false
08-04 11:58:03.359   765  1352 D SettingsProvider: selectionArgs: 1002
,08-04 11:58:03.359   765  1352 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:58:03.359   765  1352 D SettingsProvider: ret = -1
,08-04 11:58:03.359   765  1573 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
,08-04 11:58:03.359   765  1573 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:58:03.359   765  1573 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-04 11:58:03.359   765  1573 D SettingsProvider: selectionArgs: false
08-04 11:58:03.359   765  1573 D SettingsProvider: selectionArgs: 1002
,08-04 11:58:03.359   765  1573 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:58:03.359   765  1573 D SettingsProvider: ret = -1,
08-04 11:58:03.359   765  1232 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,08-04 11:58:03.359   765  1232 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:58:03.359   765  1232 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-04 11:58:03.359   765  1232 D SettingsProvider: selectionArgs: false
08-04 11:58:03.359   765  1232 D SettingsProvider: selectionArgs: 1002
,08-04 11:58:03.359   765  1232 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:58:03.359   765  1232 D SettingsProvider: ret = -1
08-04 11:58:03.359   765  1493 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-04 11:58:03.359   765  1493 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:58:03.359   765  1493 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:58:03.359   765  1493 D SettingsProvider: selectionArgs: false
,08-04 11:58:03.359   765  1493 D SettingsProvider: selectionArgs: 1002
08-04 11:58:03.359   765  1493 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:58:03.359   765  1493 D SettingsProvider: ret = -1
08-04 11:58:03.359   765  1330 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-04 11:58:03.359   765  1330 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:58:03.359   765  1330 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:58:03.359   765  1330 D SettingsProvider: selectionArgs: false
,08-04 11:58:03.359   765  1330 D SettingsProvider: selectionArgs: 1002
08-04 11:58:03.359   765  1330 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:58:03.359   765  1330 D SettingsProvider: ret = -1
08-04 11:58:03.359   765  1444 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-04 11:58:03.359   765  1444 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:58:03.359   765  1444 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-04 11:58:03.359   765  1444 D SettingsProvider: selectionArgs: false
08-04 11:58:03.359   765  1444 D SettingsProvider: selectionArgs: 1002
08-04 11:58:03.359   765  1444 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:58:03.359   765  1444 D SettingsProvider: ret = -1
,08-04 11:58:03.379  8273  8273 D BluetoothAdapterState: make
,08-04 11:58:03.389  8273  8273 I bluedroid: init
,08-04 11:58:03.389  8273  8294 I BluetoothAdapterState: Entering OffState
,08-04 11:58:03.389  8273  8273 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-04 11:58:03.389  8273  8273 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-04 11:58:03.389  8273  8273 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-04 11:58:03.389  8273  8273 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-04 11:58:03.389  8273  8273 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-04 11:58:03.389  8273  8273 I bluedroid: get_profile_interface socket
08-04 11:58:03.389  8273  8273 I bluedroid: get_profile_interface map_client
08-04 11:58:03.389  8273  8297 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-04 11:58:03.389  8273  8273 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-04 11:58:03.399  8273  8297 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
,08-04 11:58:03.399  8273  8297 E BluetoothServiceJni: populateRssiValuesNative
08-04 11:58:03.399  8273  8297 I bluedroid: getModelRssiValues
08-04 11:58:03.399  8273  8297 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-04 11:58:03.399  8273  8297 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-04 11:58:03.399   765   765 D SettingsProvider: name = bluetooth_name
,08-04 11:58:03.399  8273  8297 D BluetoothAdapterProperties: Name is: Note3-1
,08-04 11:58:03.399   765  1352 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-04 11:58:03.399  8273  8281 I bluedroid: config_hci_snoop_log
,08-04 11:58:03.399   765  1059 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 13 receivers.
,08-04 11:58:03.409   765  1059 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-04 11:58:03.409   765  1059 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-04 11:58:03.409   765  1059 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-04 11:58:03.409  8273  8294 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,08-04 11:58:03.409  8273  8294 D BluetoothAdapterProperties: Setting state to 11
08-04 11:58:03.409  8273  8294 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-04 11:58:03.409  8273  8294 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-04 11:58:03.409  8273  8294 D BluetoothAdapterService: updateAdapterState state is 11
,08-04 11:58:03.409  8273  8294 D BluetoothAdapterService: Autoconnection is available 
08-04 11:58:03.409  8273  8294 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-04 11:58:03.409   765   765 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-04 11:58:03.409   765   765 I InputMethodManagerService: [BT Setting State] State =11
,08-04 11:58:03.419  1750  1750 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-04 11:58:03.419  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-04 11:58:03.419  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-04 11:58:03.419  1195  1604 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-04 11:58:03.419   765  1444 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-04 11:58:03.419   765  1444 D ActivityManager: caller:android.app.ApplicationThreadProxy@31ca9415, r.packageName :com.google.android.gms
,08-04 11:58:03.419  8273  8294 D BluetoothSecureManager: getInstant: null
,08-04 11:58:03.419  8273  8294 D BluetoothSecureManager: calling getMethod for getService
,08-04 11:58:03.419  8273  8294 D BluetoothSecureManager: calling getService
,08-04 11:58:03.429  1321  1321 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-04 11:58:03.429   765  1493 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,08-04 11:58:03.429   765  1330 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-04 11:58:03.429  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,08-04 11:58:03.429  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:58:03.429  8273  8294 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@3e29a7e4
,08-04 11:58:03.429   765   784 D BluetoothSecureManagerService: isSecureModeEnabled
08-04 11:58:03.429   765   784 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-04 11:58:03.429  8273  8294 D BtConfig.SecureMode: isSecureModeOn:false
08-04 11:58:03.429  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-04 11:58:03.429  8273  8294 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-04 11:58:03.429  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-04 11:58:03.429  8273  8294 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-04 11:58:03.429  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-04 11:58:03.429  8273  8294 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-04 11:58:03.429  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-04 11:58:03.429  8273  8294 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-04 11:58:03.429  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-04 11:58:03.429  8273  8294 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,08-04 11:58:03.429  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-04 11:58:03.429  8273  8294 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-04 11:58:03.429  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-04 11:58:03.429  8273  8294 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-04 11:58:03.429  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-04 11:58:03.429  8273  8294 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-04 11:58:03.429  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-04 11:58:03.429  8273  8294 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-04 11:58:03.429  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-04 11:58:03.429  7620  7620 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,08-04 11:58:03.439  8273  8294 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-04 11:58:03.439  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-04 11:58:03.439  8273  8294 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-04 11:58:03.439  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-04 11:58:03.439  8273  8294 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-04 11:58:03.439  8273  8294 D BluetoothBondStateMachine: make
,08-04 11:58:03.439  8273  8294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-04 11:58:03.439  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-04 11:58:03.439  8273  8294 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-04 11:58:03.439  8273  8300 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-04 11:58:03.439   765  1449 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 11:58:03.449   765  1449 D ActivityManager: caller:android.app.ApplicationThreadProxy@3c51751b, r.packageName :com.android.bluetooth
,08-04 11:58:03.449  1321  1321 D BluetoothNotiBroadcastReceiver: onReceive
,08-04 11:58:03.449  8273  8273 I BtGatt.JNI: classInitNative(L890): classInitNative: Success!
,08-04 11:58:03.459  8273  8294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-04 11:58:03.459  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-04 11:58:03.459  8273  8294 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-04 11:58:03.459   765  1493 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 11:58:03.459   765  1493 D ActivityManager: caller:android.app.ApplicationThreadProxy@22cd5c91, r.packageName :com.android.bluetooth
08-04 11:58:03.459  8273  8273 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 11:58:03.459  8273  8273 D BtGatt.GattService: Received start request. Starting profile...
08-04 11:58:03.459  8273  8273 D BtGatt.GattService: start()
08-04 11:58:03.459  8273  8273 I bluedroid: get_profile_interface gatt
,08-04 11:58:03.459  8273  8273 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@186ecf7f
08-04 11:58:03.459  8273  8273 D BtGatt.AdvertiseManager: advertise manager created
,08-04 11:58:03.459  8273  8294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-04 11:58:03.459  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-04 11:58:03.459  8273  8294 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-04 11:58:03.459   765   784 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 11:58:03.459   765   784 D ActivityManager: caller:android.app.ApplicationThreadProxy@198847f7, r.packageName :com.android.bluetooth
,08-04 11:58:03.469  8273  8294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-04 11:58:03.469  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-04 11:58:03.469  8273  8294 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-04 11:58:03.469   765  1238 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 11:58:03.469   765  1238 D ActivityManager: caller:android.app.ApplicationThreadProxy@5a30cd, r.packageName :com.android.bluetooth
,08-04 11:58:03.469  8273  8294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-04 11:58:03.469  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-04 11:58:03.469  8273  8294 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,08-04 11:58:03.469   765  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 11:58:03.469   765  1476 D ActivityManager: caller:android.app.ApplicationThreadProxy@35ef6c93, r.packageName :com.android.bluetooth
,08-04 11:58:03.469  8273  8294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-04 11:58:03.479  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-04 11:58:03.479  8273  8294 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-04 11:58:03.479   765   785 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 11:58:03.479   765   785 D ActivityManager: caller:android.app.ApplicationThreadProxy@37b3cdfc, r.packageName :com.android.bluetooth
,08-04 11:58:03.479  8273  8273 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@186ecf7f
,08-04 11:58:03.479  8273  8273 D HeadsetService: Received start request. Starting profile...
,08-04 11:58:03.479  8273  8273 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-04 11:58:03.479  8273  8273 D HeadsetStateMachine: make
,08-04 11:58:03.489  8273  8294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-04 11:58:03.489  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-04 11:58:03.489  8273  8294 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-04 11:58:03.489  8273  8273 E HeadsetStateMachine: # of Max HF connection is 2
,08-04 11:58:03.489   765  1232 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 11:58:03.489   765  1232 D ActivityManager: caller:android.app.ApplicationThreadProxy@27fd2ada, r.packageName :com.android.bluetooth
,08-04 11:58:03.489  8273  8294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-04 11:58:03.489  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-04 11:58:03.489  8273  8294 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-04 11:58:03.499   765  1703 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 11:58:03.499   765  1703 D ActivityManager: caller:android.app.ApplicationThreadProxy@186dcde8, r.packageName :com.android.bluetooth
,08-04 11:58:03.499   765  1444 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-04 11:58:03.499  8273  8294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-04 11:58:03.499  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-04 11:58:03.499  8273  8294 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-04 11:58:03.499  8273  8294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-04 11:58:03.499  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-04 11:58:03.499  8273  8294 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-04 11:58:03.499  8273  8294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-04 11:58:03.499  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-04 11:58:03.499  8273  8294 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-04 11:58:03.499  8273  8294 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-04 11:58:03.499  8273  8294 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-04 11:58:03.499  8273  8294 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-04 11:58:03.499  8273  8294 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-04 11:58:03.499   765  1449 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
,08-04 11:58:03.499  1864  1864 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-04 11:58:03.499  8273  8273 I bluedroid: get_profile_interface handsfree
,08-04 11:58:03.509  1864  1864 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-04 11:58:03.519  8273  8273 I DualScoManager: Instantiating Dual Sco Manager
,08-04 11:58:03.519  8273  8273 I DualScoManager: Set HeadsetServiceHelper
,08-04 11:58:03.519  8273  8273 D BluetoothAtMessage: createCMTIContentObservers
,08-04 11:58:03.519   765  1232 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-04 11:58:03.519   765  1232 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:58:03.519   765  1232 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:58:03.519   765  1232 D SettingsProvider: selectionArgs: false
08-04 11:58:03.519   765  1232 D SettingsProvider: selectionArgs: 1002
08-04 11:58:03.519   765  1232 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:58:03.519   765  1232 D SettingsProvider: ret = -1
,08-04 11:58:03.519  8273  8305 D HeadsetStateMachine: Enter Disconnected: -2
,08-04 11:58:03.519  8273  8273 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@186ecf7f
,08-04 11:58:03.519  8273  8305 E HeadsetStateMachine: set to mRemoteBrsf = 0
,08-04 11:58:03.519  8273  8273 D A2dpService: Received start request. Starting profile...
,08-04 11:58:03.519  8273  8305 D HeadsetStateMachine: map size, before remove : 0
,08-04 11:58:03.519  8273  8305 D HeadsetStateMachine: map size, after remove: 0
,08-04 11:58:03.519  8273  8305 D HeadsetStateMachine: mNextConnectingDevice : null
,08-04 11:58:03.529  8273  8273 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-04 11:58:03.529  8273  8273 V Avrcp   : make
,08-04 11:58:03.529  8273  8273 V Avrcp   : Avrcp
,08-04 11:58:03.529  8273  8273 I bluedroid: get_profile_interface avrcp
,08-04 11:58:03.529  8273  8273 V Avrcp   : start
,08-04 11:58:03.529  8273  8273 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-04 11:58:03.529  8273  8273 V Avrcp   : ++registerMediaPlayers++
,08-04 11:58:03.539  8273  8273 I Avrcp   : No of Audio players :: 2
,08-04 11:58:03.539  8273  8273 I Avrcp   : App Package name is com.google.android.music
,08-04 11:58:03.539  8273  8273 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,08-04 11:58:03.539  8273  8273 I Avrcp   : App pkg name is Google Play Music
,08-04 11:58:03.539  8273  8273 I Avrcp   : Name::Google Play Music
,08-04 11:58:03.539  8273  8273 V Avrcp   : MediaPlayerInfo: mPlayerId=1
08-04 11:58:03.539  8273  8273 I Avrcp   : App Package name is com.sec.android.app.music
,08-04 11:58:03.539  8273  8273 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,08-04 11:58:03.539  8273  8273 I Avrcp   : App pkg name is Music
,08-04 11:58:03.549  8273  8273 I Avrcp   : Name::Music
08-04 11:58:03.549  8273  8273 V Avrcp   : MediaPlayerInfo: mPlayerId=2
08-04 11:58:03.549  8273  8273 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,08-04 11:58:03.549  8273  8273 I Avrcp   : No of Video players :: 1
,08-04 11:58:03.549  8273  8273 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
,08-04 11:58:03.549  8273  8273 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,08-04 11:58:03.549  8273  8273 I Avrcp   : Video App pkg name is Video Player
,08-04 11:58:03.549  8273  8273 I Avrcp   : Name::Video Player
08-04 11:58:03.549  8273  8273 V Avrcp   : MediaPlayerInfo: mPlayerId=3
08-04 11:58:03.549  8273  8273 I Avrcp   : Add tempPlayer
,08-04 11:58:03.549  8273  8273 V Avrcp   : MediaPlayerInfo: mPlayerId=4
08-04 11:58:03.549  8273  8273 I Avrcp   : Total no of players: 4
08-04 11:58:03.549  8273  8273 V Avrcp   : swapping the samsung player with 1st player
08-04 11:58:03.549  8273  8273 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-04 11:58:03.549  8273  8316 V Avrcp   : handleMessage, msg=207
,08-04 11:58:03.549  8273  8316 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,08-04 11:58:03.549  8273  8273 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-04 11:58:03.549  8273  8273 D A2dpStateMachine: make
,08-04 11:58:03.559  8273  8273 I bluedroid: get_profile_interface a2dp
,08-04 11:58:03.559  8273  8318 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-04 11:58:03.559  8273  8273 E bt-btif : warning : media task started media_task_refcnt 1 
,08-04 11:58:03.559  8273  8316 D BluetoothMediaBrowser: no now playing list
,08-04 11:58:03.559  8273  8316 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-04 11:58:03.559  8273  8273 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@186ecf7f
08-04 11:58:03.559  8273  8316 D Avrcp   :  checkNowPlayingList start
08-04 11:58:03.559  8273  8317 D A2dpStateMachine: Enter Disconnected: -2
,08-04 11:58:03.559  8273  8273 I BluetoothHidServiceJni: classInitNative: succeeds
,08-04 11:58:03.559  8273  8273 D HidService: Received start request. Starting profile...
08-04 11:58:03.559  8273  8273 I bluedroid: get_profile_interface hidhost
,08-04 11:58:03.559  8273  8273 D HidService: setHidService(): set to: null
08-04 11:58:03.559  8273  8273 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@186ecf7f
08-04 11:58:03.559  8273  8273 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-04 11:58:03.559  8273  8273 D HealthService: Received start request. Starting profile...
,08-04 11:58:03.559  8273  8273 I bluedroid: get_profile_interface health
,08-04 11:58:03.569  8273  8273 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@186ecf7f
08-04 11:58:03.569  8273  8273 E BluetoothAdapterService(409915263): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-04 11:58:03.569  8273  8273 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-04 11:58:03.569  8273  8273 D PanService: Received start request. Starting profile...
08-04 11:58:03.569  8273  8273 D BluetoothPanServiceJni: initializeNative(L110): pan
08-04 11:58:03.569  8273  8273 I bluedroid: get_profile_interface pan
,08-04 11:58:03.569  8273  8273 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@186ecf7f
,08-04 11:58:03.569  8273  8273 D BluetoothMapService: Received start request. Starting profile...
,08-04 11:58:03.589  8273  8273 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@186ecf7f
,08-04 11:58:03.589  8273  8273 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-04 11:58:03.589  8273  8273 D SapService: Received start request. Starting profile...
08-04 11:58:03.589  8273  8273 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-04 11:58:03.589  8273  8273 I bluedroid: get_profile_interface sap
08-04 11:58:03.589  8273  8273 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@186ecf7f
,08-04 11:58:03.589  8273  8273 D HeadsetStateMachine: Try to query the phonestate on bind
08-04 11:58:03.589  1403  1416 I Telecom : BluetoothPhoneService: queryPhoneState
,08-04 11:58:03.599  1403  1403 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-04 11:58:03.599  8273  8273 D HeadsetStateMachine: Proxy object connected
,08-04 11:58:03.599  8273  8273 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,08-04 11:58:03.599  8273  8273 D HeadsetPhoneState: sendDeviceDataStateChanged
08-04 11:58:03.599  8273  8273 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-04 11:58:03.599  8273  8273 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-04 11:58:03.599  8273  8273 E BluetoothAdapterService(409915263): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
08-04 11:58:03.599  8273  8273 D BluetoothA2dp: Proxy object connected
08-04 11:58:03.599  8273  8273 D BluetoothAdapterService: Bluetooth A2dp source service connected
,08-04 11:58:03.599  8273  8305 D HeadsetStateMachine: Disconnected process message: 11
08-04 11:58:03.599  8273  8305 D HeadsetStateMachine: Disconnected process message: 18
08-04 11:58:03.599  8273  8305 D HeadsetStateMachine: Disconnected process message: 10
,08-04 11:58:03.599  8273  8305 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-04 11:58:03.599  8273  8305 D HeadsetStateMachine: Disconnected process message: 11
,08-04 11:58:03.599  8273  8273 E BluetoothAdapterService(409915263): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,08-04 11:58:03.599  8273  8273 E BluetoothAdapterService(409915263): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-04 11:58:03.599  8273  8273 E BluetoothAdapterService(409915263): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-04 11:58:03.599  8273  8273 E BluetoothAdapterService(409915263): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-04 11:58:03.599  8273  8273 E BluetoothAdapterService(409915263): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-04 11:58:03.599  8273  8273 E BluetoothAdapterService(409915263): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
08-04 11:58:03.599  8273  8294 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-04 11:58:03.599  8273  8294 I bluedroid: enable
,08-04 11:58:03.599  8273  8323 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,08-04 11:58:03.609  8273  8294 I bt_hci_bdroid: init
,08-04 11:58:03.609  8273  8294 I bt_vendor: init
08-04 11:58:03.609  8273  8294 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-04 11:58:03.609  8273  8294 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
08-04 11:58:03.609  8273  8294 D bt_userial: userial_init
08-04 11:58:03.609  8273  8294 D bt_vendor: op for 5
08-04 11:58:03.609  8273  8294 D bt_vendor: op for 0
08-04 11:58:03.609  8273  8294 D bt_upio : upio_set_bluetooth_power(on: 0)
08-04 11:58:03.609  8273  8294 D bt_upio : is_emulator_context : 0
08-04 11:58:03.609  8273  8294 D bt_upio : is_rfkill_disabled ? [0]
08-04 11:58:03.609  8273  8294 D bt_upio : is_rfkill_disabled ? [0]
,08-04 11:58:03.609  8273  8294 D bt_vendor: op for 0
08-04 11:58:03.609  8273  8294 D bt_upio : upio_set_bluetooth_power(on: 1)
08-04 11:58:03.609  8273  8294 D bt_upio : is_emulator_context : 0
08-04 11:58:03.609  8273  8294 D bt_upio : is_rfkill_disabled ? [0]
,08-04 11:58:03.609  8273  8325 D bt_vendor: op for 3
08-04 11:58:03.609  8273  8325 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-04 11:58:03.609  8273  8325 I bt_userial_vendor: userial_vendor_open():UART is setup
08-04 11:58:03.609  8273  8325 I bt_userial_vendor: device fd = 65 open
,08-04 11:58:03.609  8273  8325 D bt_vendor: op for 1
08-04 11:58:03.609  8273  8325 E bt_hwcfg: Start CFG HW, HCI reset
08-04 11:58:03.609  8273  8326 D bt_userial: Entering userial_read_thread()
,08-04 11:58:03.689  8273  8325 E bt_hwcfg: Read Local Name after HCI reset
,08-04 11:58:03.709  8273  8325 D bt_hwcfg: Chipset BCM4335C0
08-04 11:58:03.709  8273  8325 D bt_hwcfg: Target name = [BCM4335C0]
,08-04 11:58:03.709  8273  8325 I bt_hwcfg: module_type[semco].
08-04 11:58:03.709  8273  8325 I bt_hwcfg: not ZERO...
08-04 11:58:03.709  8273  8325 I bt_hwcfg: module_type[semco] is invalid.
08-04 11:58:03.709  8273  8325 E bt_hwcfg: patchram path ORG . BCM4335C0
08-04 11:58:03.709  8273  8325 E bt_hwcfg: patchram path ORG .. BCM4335C0
08-04 11:58:03.709  8273  8325 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
08-04 11:58:03.709  8273  8325 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
08-04 11:58:03.709  8273  8325 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
08-04 11:58:03.709  8273  8325 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
08-04 11:58:03.709  8273  8325 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335C0
08-04 11:58:03.709  8273  8325 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559_wisol.hcd BCM4335C0
08-04 11:58:03.709  8273  8325 E bt_hwcfg: fw ver (org)0.0
08-04 11:58:03.709  8273  8325 E bt_hwcfg: vendor lib preload failed to locate firmware patch file
08-04 11:58:03.709  8273  8325 E bt_hwcfg: Remove module rev, try again BCM4335
08-04 11:58:03.709  8273  8325 D bt_hwcfg: Target name = [BCM4335]
08-04 11:58:03.709  8273  8325 I bt_hwcfg: module_type[semco].
08-04 11:58:03.709  8273  8325 I bt_hwcfg: not ZERO...
08-04 11:58:03.709  8273  8325 I bt_hwcfg: module_type[semco] is invalid.
08-04 11:58:03.709  8273  8325 E bt_hwcfg: patchram path ORG . BCM4335
08-04 11:58:03.709  8273  8325 E bt_hwcfg: patchram path ORG .. BCM4335
08-04 11:58:03.709  8273  8325 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335
08-04 11:58:03.709  8273  8325 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
08-04 11:58:03.709  8273  8325 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335
08-04 11:58:03.709  8273  8325 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
08-04 11:58:03.709  8273  8325 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335
08-04 11:58:03.709  8273  8325 I bt_hwcfg: patch(org) : bcm4335_V0111.0559.hcd
08-04 11:58:03.709  8273  8325 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4335_V0111.0559.hcd
08-04 11:58:03.709  8273  8325 E bt_hwcfg: ORG patchram base 0111
08-04 11:58:03.709  8273  8325 E bt_hwcfg: ORG patchram minor 0559
08-04 11:58:03.709  8273  8325 E bt_hwcfg: fw ver (org)111.559
08-04 11:58:03.709  8273  8325 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4335_V0111.0559.hcd
,08-04 11:58:03.719  8273  8325 I bt_hwcfg: Axi patch failure or not include AXI patching
08-04 11:58:03.719  8273  8325 I bt_hwcfg: bt vendor lib: set UART baud 3000000
08-04 11:58:03.749   765  3128 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-04 11:58:04.249  8273  8325 I bt_hwcfg: bt vendor lib: set UART baud 115200,
,08-04 11:58:04.249  8273  8325 I bt_hwcfg: FW Download delta = 567340
,08-04 11:58:04.259  8273  8325 D bt_hwcfg: Settlement delay -- 100 ms
,08-04 11:58:04.259  8273  8325 I bt_hwcfg: Setting fw settlement delay to 100 
,08-04 11:58:04.359  8273  8325 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 11:58:04.399  8273  8325 I bt_hwcfg: vendor lib fwcfg completed
,08-04 11:58:04.409  8273  8323 I         : BTE_InitTraceLevels -- TRC_HCI
,08-04 11:58:04.409  8273  8323 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-04 11:58:04.409  8273  8323 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-04 11:58:04.409  8273  8323 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-04 11:58:04.409  8273  8323 I         : BTE_InitTraceLevels -- TRC_AVRC
08-04 11:58:04.409  8273  8323 I         : BTE_InitTraceLevels -- TRC_A2D
08-04 11:58:04.409  8273  8323 I         : BTE_InitTraceLevels -- TRC_BNEP
08-04 11:58:04.409  8273  8323 I         : BTE_InitTraceLevels -- TRC_BTM
,08-04 11:58:04.409  8273  8323 I         : BTE_InitTraceLevels -- TRC_GAP
08-04 11:58:04.409  8273  8323 I         : BTE_InitTraceLevels -- TRC_PAN
08-04 11:58:04.409  8273  8323 I         : BTE_InitTraceLevels -- TRC_SAP
08-04 11:58:04.409  8273  8323 I         : BTE_InitTraceLevels -- TRC_SDP
,08-04 11:58:04.409  8273  8323 I         : BTE_InitTraceLevels -- TRC_GATT
08-04 11:58:04.409  8273  8323 I         : BTE_InitTraceLevels -- TRC_SMP
08-04 11:58:04.409  8273  8323 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-04 11:58:04.409  8273  8323 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-04 11:58:04.409  8273  8323 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-04 11:58:04.639  8273  8323 W bt-l2cap: l2c_link_processs_ble_num_bufs 15
,08-04 11:58:04.649  8273  8323 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xb3b18b5d 
,08-04 11:58:04.649  8273  8323 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xb3b18b5d 
,08-04 11:58:04.689   303   303 E SMD     : DCD ON
,08-04 11:58:04.869  8273  8297 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 1 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
,08-04 11:58:04.869  8273  8297 E bt-btif : Calling BTA_HhEnable
,08-04 11:58:04.869  8273  8297 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
08-04 11:58:04.869  8273  8297 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
,08-04 11:58:04.869  8273  8297 E BluetoothServiceJni: populateRssiValuesNative
08-04 11:58:04.869  8273  8297 I bluedroid: getModelRssiValues
08-04 11:58:04.869  8273  8297 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-04 11:58:04.869  8273  8297 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-04 11:58:04.879   765   765 D SettingsProvider: name = bluetooth_name
,08-04 11:58:04.879  8273  8297 D BluetoothAdapterProperties: Name is: Note3-1
,08-04 11:58:04.879  8273  8297 D BluetoothAdapterProperties: Scan Mode:20
,08-04 11:58:04.879  8273  8297 D BluetoothAdapterProperties: Discoverable Timeout:120
08-04 11:58:04.879  8273  8297 D BluetoothAdapterProperties: LE Address is:E0:B7:20:3E:93:BC
,08-04 11:58:04.879  8273  8297 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-04 11:58:04.879  8273  8297 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,08-04 11:58:04.879  8273  8325 D bt_vendor: op for 2
08-04 11:58:04.879  8273  8325 D bt_vendor: op for 6
,08-04 11:58:04.879  8273  8297 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-04 11:58:04.879  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.879  8273  8297 E bt-btif : btif_sock_init: !vhci_init
08-04 11:58:04.879  8273  8325 D bt_upio : proc btwrite assertion
,08-04 11:58:04.879  8273  8297 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-04 11:58:04.879  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.879  8273  8325 D bt_upio : BT_WAKE is asserted already
08-04 11:58:04.879  8273  8297 D IOP_DB_BT: db_open: db_open : handle 3026710544l, read 14063 bytes onto local cache
,08-04 11:58:04.879  8273  8297 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
08-04 11:58:04.879  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.879  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.879  8273  8297 D IOP_DB_BT: db_query: result 1
,08-04 11:58:04.889  8273  8297 I         : iop_db_open: iop_db_open status 0
08-04 11:58:04.889  8273  8297 D bte_conf: Device ID record 1 : primary
,08-04 11:58:04.889  8273  8297 D bte_conf:   vendorId            = 0075
08-04 11:58:04.889  8273  8297 D bte_conf:   vendorIdSource      = 0001
08-04 11:58:04.889  8273  8297 D bte_conf:   product             = 0100
08-04 11:58:04.889  8273  8297 D bte_conf:   version             = 0200
,08-04 11:58:04.889  8273  8297 D bte_conf:   clientExecutableURL = 
08-04 11:58:04.889  8273  8297 D bte_conf:   serviceDescription  = 
08-04 11:58:04.889  8273  8297 D bte_conf:   documentationURL    = 
08-04 11:58:04.889  8273  8297 D bte_conf: bte_load_did_conf no section named DID2.
,08-04 11:58:04.889  8273  8294 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-04 11:58:04.889  8273  8294 D BluetoothAdapterProperties: ScanMode =  20
,08-04 11:58:04.889  8273  8294 D BluetoothAdapterProperties: State =  11
08-04 11:58:04.889   765  1680 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
08-04 11:58:04.889  8273  8294 D BluetoothAdapterProperties: Setting state to 12
,08-04 11:58:04.889  8273  8294 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-04 11:58:04.889   765  1703 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-04 11:58:04.889   765  1703 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 11:58:04.889   765  1703 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 11:58:04.889   765  1703 D SettingsProvider: selectionArgs: false
08-04 11:58:04.889   765  1703 D SettingsProvider: selectionArgs: 1002
,08-04 11:58:04.889   765  1703 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 11:58:04.889   765  1703 D SettingsProvider: ret = -1
08-04 11:58:04.889  8273  8294 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-04 11:58:04.889  8273  8294 D BluetoothAdapterService: updateAdapterState state is 12
,08-04 11:58:04.899   765  1444 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 11:58:04.899   765  1444 D ActivityManager: caller:android.app.ApplicationThreadProxy@a48118, r.packageName :com.android.bluetooth
,08-04 11:58:04.899  8273  8294 D BluetoothAdapterService: Autoconnection is available 
,08-04 11:58:04.899  8273  8294 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-04 11:58:04.899  8273  8294 D BluetoothAdapterService: starting service from this receiver
,08-04 11:58:04.899   765   784 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 11:58:04.899   765   784 D ActivityManager: caller:android.app.ApplicationThreadProxy@2e2d7956, r.packageName :com.android.bluetooth
,08-04 11:58:04.909  8273  8294 I BluetoothAdapterState: Entering On State from state = 11
,08-04 11:58:04.909  8273  8325 E bt_h4   : vendor lib postload completed
,08-04 11:58:04.919  8273  8297 D BluetoothAdapterProperties: Scan Mode:21
,08-04 11:58:04.919  8273  8297 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-04 11:58:04.919  8273  8273 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-04 11:58:04.929   765  1059 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 11:58:04.929  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:58:04.929  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:58:04.929  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:58:04.929  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 11:58:04.929  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:58:04.929  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:58:04.929  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:58:04.929  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 11:58:04.929  8273  8273 I BluetoothPbapService: Handler(): got msg=1
,08-04 11:58:04.929   765  1493 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-04 11:58:04.929  7235  7235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 11:58:04.939  1321  1337 E BluetoothHeadset: BluetoothHeadset service is binded
,08-04 11:58:04.939  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:58:04.949  1321  1321 D HeadsetProfile: Bluetooth service connected
,08-04 11:58:04.949  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.949  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.949  8273  8297 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-04 11:58:04.949  8273  8325 D bt_vendor: op for 7
,08-04 11:58:04.949  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.949  8273  8325 D bt_vendor: op for 7
,08-04 11:58:04.949  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.949  8273  8325 D bt_vendor: op for 7
,08-04 11:58:04.949  8273  8325 D bt_upio : BT_WAKE is asserted already
08-04 11:58:04.949  8273  8339 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-04 11:58:04.949  8273  8325 D bt_vendor: op for 7
,08-04 11:58:04.949  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.959  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.959  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.959  8273  8339 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 11:58:04.959  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.959  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.959  8273  8339 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
08-04 11:58:04.959  8273  8339 D BluetoothSocket: bindListen(), new LocalSocket 
08-04 11:58:04.959  8273  8339 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-04 11:58:04.959  8273  8339 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25cff9c8
,08-04 11:58:04.959  8273  8339 D BluetoothSocket: channel: 19
,08-04 11:58:04.959  8273  8339 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-04 11:58:04.959  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.959  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.969  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.969  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.969  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.969  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.969  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.969  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.969  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.969  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.979  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.979  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.979  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.979  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.979  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.979  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.979  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.979  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.979  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.979  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.979  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.979  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.989  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.989  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.989  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.989  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.989  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.989  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.989  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.989  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.999  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.999  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.999  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.999  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.999  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.999  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.999  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.999  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:04.999  8273  8325 D bt_vendor: op for 7
08-04 11:58:04.999  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:05.049   765  1059 I art     : Explicit concurrent mark sweep GC freed 21833(1401KB) AllocSpace objects, 3(48KB) LOS objects, 30% free, 37MB/53MB, paused 1.249ms total 108.616ms
08-04 11:58:05.049   765  1059 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 11:58:05.049  7620  7635 E BluetoothHeadset: BluetoothHeadset service is binded
,08-04 11:58:05.059  8273  8281 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 11:58:05.059  1321  1373 D BluetoothMap: onBluetoothStateChange: up=true
,08-04 11:58:05.059   765  1059 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-04 11:58:05.059  1321  1321 D BluetoothMap: Proxy object connected
08-04 11:58:05.059  1321  1321 D MapProfile: Bluetooth service connected
,08-04 11:58:05.059   765  1059 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-04 11:58:05.059   765  1059 E BluetoothHeadset: BluetoothHeadset service is binded
08-04 11:58:05.059   765  1059 D BluetoothPan: Binding service...
,08-04 11:58:05.059   765  1059 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-04 11:58:05.059   765   765 D BluetoothPan: BluetoothPAN Proxy object connected
,08-04 11:58:05.059  1321  1361 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-04 11:58:05.059   765  1059 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-04 11:58:05.059  1321  1321 D BluetoothInputDevice: Proxy object connected
08-04 11:58:05.059  1321  1321 D HidProfile: Bluetooth service connected
,08-04 11:58:05.059   765  1059 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 11:58:05.069  3222  3233 E BluetoothHeadset: BluetoothHeadset service is binded
,08-04 11:58:05.069   765  1059 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 11:58:05.069  1403  1411 E BluetoothHeadset: BluetoothHeadset service is binded
,08-04 11:58:05.069  3222  3239 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 11:58:05.069   765  1059 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-04 11:58:05.069  3222  3222 D BluetoothA2dp: Proxy object connected
,08-04 11:58:05.069   765  1059 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 11:58:05.069   765  1059 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-04 11:58:05.069   765   765 D BluetoothA2dp: Proxy object connected
,08-04 11:58:05.069  1321  1373 D BluetoothPbap: onBluetoothStateChange: up=true
,08-04 11:58:05.069   765  1059 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-04 11:58:05.079  1321  1361 D Bluetoothsap: onBluetoothStateChange: up=true
08-04 11:58:05.079  1321  1361 D Bluetoothsap: Binding service...
,08-04 11:58:05.079  1321  1321 D BluetoothPbap: Proxy object connected
08-04 11:58:05.079  1321  1321 D PbapServerProfile: Bluetooth service connected
,08-04 11:58:05.079  1321  1361 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-04 11:58:05.079   765  1059 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-04 11:58:05.079  1321  1361 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-04 11:58:05.079  1321  1373 D BluetoothPan: Binding service...
,08-04 11:58:05.079  1321  1321 D Bluetoothsap: BluetoothSAP Proxy object connected
08-04 11:58:05.079  1321  1321 D SapProfile: Bluetooth service connected
08-04 11:58:05.079  1321  1321 D Bluetoothsap: getConnectedDevices()
,08-04 11:58:05.079   765  1059 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-04 11:58:05.079  1321  1321 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 11:58:05.079  1321  1321 D PanProfile: Bluetooth service connected
,08-04 11:58:05.079   765  1059 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 11:58:05.079  1428  2432 E BluetoothHeadset: BluetoothHeadset service is binded
,08-04 11:58:05.089   765  1059 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 11:58:05.089  1403  1416 E BluetoothHeadset: BluetoothHeadset service is binded
,08-04 11:58:05.089  1321  1337 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 11:58:05.089   765  1059 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-04 11:58:05.089  1321  1321 D BluetoothA2dp: Proxy object connected
08-04 11:58:05.089  1321  1321 D A2dpProfile: Bluetooth service connected
,08-04 11:58:05.089   765  1059 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 11:58:05.099  1403  7598 E BluetoothHeadset: BluetoothHeadset service is binded
,08-04 11:58:05.099   765  1059 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-04 11:58:05.099   765   765 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-04 11:58:05.099   765   765 I InputMethodManagerService: [BT Setting State] State =12
08-04 11:58:05.099   765   765 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-04 11:58:05.099  1195  1195 D BluetoothTile:  onBluetoothStateChange:
,08-04 11:58:05.099  1403  1403 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@19ecba98, true
,08-04 11:58:05.099  1750  1750 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
08-04 11:58:05.099  7620  7620 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,08-04 11:58:05.099  1321  1321 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-04 11:58:05.099  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:58:05.099   765  3205 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-04 11:58:05.099   765  1059 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-04 11:58:05.099  1403  1403 D BluetoothHeadset: registerMessageListener
,08-04 11:58:05.099   765  3205 D ActivityManager: caller:android.app.ApplicationThreadProxy@263588a7, r.packageName :com.google.android.gms
,08-04 11:58:05.109  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-04 11:58:05.109  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-04 11:58:05.109  8273  8298 D HeadsetService: registerMessageListener
,08-04 11:58:05.109  8273  8298 D HeadsetService: registerMessageListener
,08-04 11:58:05.109  1403  1403 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
08-04 11:58:05.109  1195  1604 D BluetoothTile:  handleUpdatestate:false name:null
08-04 11:58:05.109  1195  1604 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-04 11:58:05.109  1403  1403 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-04 11:58:05.109   765  1476 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,08-04 11:58:05.109  8273  8305 D HeadsetStateMachine: Disconnected process message: 70
08-04 11:58:05.109   765   784 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-04 11:58:05.109  8273  8305 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@30587a61
08-04 11:58:05.109  8273  8305 D HeadsetStateMachine: Disconnected process message: 9
,08-04 11:58:05.109  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,08-04 11:58:05.109  8273  8305 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-04 11:58:05.119  1321  1321 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-04 11:58:05.119  1321  1321 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-04 11:58:05.119  8273  8353 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-04 11:58:05.119   309   693 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-04 11:58:05.119   309   693 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-04 11:58:05.119   309   693 V voice   : voice_set_parameters: exit with code(-2)
08-04 11:58:05.119   309   693 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-04 11:58:05.119   309   693 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-04 11:58:05.119   309   693 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-04 11:58:05.119   309   693 V audio_hw_primary: adev_set_parameters: exit
,08-04 11:58:05.119  8273  8305 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-04 11:58:05.119  1321  1321 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 11:58:05.129   765   785 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-04 11:58:05.129  8273  8353 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 11:58:05.129   765   785 D ActivityManager: caller:android.app.ApplicationThreadProxy@34c369f2, r.packageName :com.android.settings
,08-04 11:58:05.129  8273  8325 D bt_vendor: op for 7
08-04 11:58:05.129  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:05.129  8273  8353 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-04 11:58:05.129  8273  8353 D BluetoothSocket: bindListen(), new LocalSocket 
08-04 11:58:05.129  8273  8353 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-04 11:58:05.129  8273  8353 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12fbd986
08-04 11:58:05.129  8273  8353 D BluetoothSocket: channel: 5
,08-04 11:58:05.139  1321  1321 D DockEventReceiver: finishStartingService: stopping service
,08-04 11:58:05.139  1321  1321 D BluetoothNotiBroadcastReceiver: onReceive
,08-04 11:58:05.139  8273  8273 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@186ecf7f
,08-04 11:58:05.139  8273  8273 D BtConfig.SecureMode: isSecureModeOn:false
,08-04 11:58:05.139   765   785 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 11:58:05.139   765   785 D ActivityManager: caller:android.app.ApplicationThreadProxy@34e21ec0, r.packageName :com.android.bluetooth
,08-04 11:58:05.149  1864  1864 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-04 11:58:05.149   765  1493 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-04 11:58:05.149   765  1493 D ActivityManager: caller:android.app.ApplicationThreadProxy@9a333e, r.packageName :com.google.android.gms
,08-04 11:58:05.159  1864  1864 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-04 11:58:05.159  1864  8359 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-04 11:58:05.169   765  1652 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-04 11:58:05.169   765   785 D ActivityManager: caller:android.app.ApplicationThreadProxy@12276c16, r.packageName :com.google.android.gms
,08-04 11:58:05.179  1864  8359 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-04 11:58:05.179  8273  8363 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 11:58:05.179  8273  8325 D bt_vendor: op for 7
08-04 11:58:05.179  8273  8325 D bt_upio : BT_WAKE is asserted already
,08-04 11:58:05.179  8273  8363 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
08-04 11:58:05.179  8273  8363 D BluetoothSocket: bindListen(), new LocalSocket 
08-04 11:58:05.179  8273  8363 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-04 11:58:05.179  8273  8363 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@312a39e0
08-04 11:58:05.179  8273  8363 D BluetoothSocket: channel: 12
08-04 11:58:05.179  8273  8363 I BtOppRfcommListener: Accept thread started.
,08-04 11:58:05.189  7235  7294 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:58:05.189  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:58:05.189  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:58:05.189  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 11:58:05.189  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:58:05.189  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:58:05.189  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:58:05.189  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 11:58:05.189  7235  7294 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 11:58:05.189  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:58:05.189  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@258f0e34 added. We now have 8 listener(s)
08-04 11:58:05.189  7235  7294 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 11:58:05.189  7235  7294 I WifiManager: packageName : com.test.thalitest
,08-04 11:58:05.189   765  1573 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-04 11:58:05.199   765  1573 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-04 11:58:05.199   765  1573 D SecContentProvider2: mCursor = null
,08-04 11:58:05.199   765  1573 D WifiService: setWifiEnabled: false pid=7235, uid=10079
,08-04 11:58:05.199   765  1573 D SettingsProvider: name = wifi_on
,08-04 11:58:05.199  7235  7294 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:58:05.199  7235  7294 I WifiManager: packageName : com.test.thalitest
08-04 11:58:05.199   765  1476 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-04 11:58:05.199   765  1476 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-04 11:58:05.199   765  1476 D SecContentProvider2: mCursor = null
,08-04 11:58:05.199   765  1476 D WifiService: setWifiEnabled: true pid=7235, uid=10079
08-04 11:58:05.199   765  1476 W ActivityManager: Permission Denial: getCurrentUser() from pid=7235, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-04 11:58:05.199   765  1476 W WifiService: Failed getting userId using ActivityManagerNative
08-04 11:58:05.199   765  1476 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7235, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-04 11:58:05.199   765  1476 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
08-04 11:58:05.199   765  1476 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
08-04 11:58:05.199   765  1476 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
08-04 11:58:05.199   765  1476 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-04 11:58:05.199   765  1476 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-04 11:58:05.199   765  1476 D SettingsProvider: name = wifi_on
,08-04 11:58:05.209   765  1149 E WifiHW  : ##################### set firmware type 0 #####################
,08-04 11:58:05.209   298  1055 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,08-04 11:58:05.209   298  1055 I WifiHW  : module is semco
08-04 11:58:05.209   298  1055 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
08-04 11:58:05.209   298  1055 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
08-04 11:58:05.209   298  1055 E WifiHW  : TEMP_FAILURE_RETRY complete
08-04 11:58:05.209   298  1055 D SoftapController: Softap fwReload - Ok
,08-04 11:58:05.209   298  1055 D CommandListener: Setting iface cfg
08-04 11:58:05.209   298  1055 D CommandListener: Trying to bring down wlan0
,08-04 11:58:05.209   298  1055 D CommandListener: Clearing all IP addresses on wlan0
,08-04 11:58:05.209   765  1149 E WifiHW  : supplicant_name : p2p_supplicant
,08-04 11:58:05.249  8371  8371 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,08-04 11:58:05.249  8371  8371 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-04 11:58:05.249  8371  8371 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-04 11:58:05.249  8371  8371 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-04 11:58:05.249   372   372 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8371
08-04 11:58:05.249   372   372 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
,08-04 11:58:05.249  8371  8371 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-04 11:58:05.249  8371  8371 I wpa_supplicant: ssSupport state is = 1
08-04 11:58:05.249  8371  8371 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,08-04 11:58:05.249  8371  8371 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-04 11:58:05.249   372   372 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8371
08-04 11:58:05.249   372   372 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,08-04 11:58:05.319   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:58:05.319  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 11:58:05.319  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-04 11:58:05.319  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 11:58:05.319  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-04 11:58:05.319  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 11:58:05.319  1195  1604 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-04 11:58:05.319   765  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,08-04 11:58:05.319  1195  1195 D HotspotTile: onReceive : 2, 0
,08-04 11:58:05.319   765  1149 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-04 11:58:05.319  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:58:05.319  1321  1321 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:58:05.319  6901  6901 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-04 11:58:05.329   765  1573 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:05.329  7299  7299 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-04 11:58:05.329  7299  7299 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-04 11:58:05.329  7299  7299 D SecurityLogAgent: StateMachine : Current State = 1
08-04 11:58:05.329  7299  7299 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-04 11:58:05.509   372   372 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,08-04 11:58:05.779  8371  8371 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,08-04 11:58:05.829  8371  8371 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-04 11:58:05.829  8371  8371 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-04 11:58:05.829   372   372 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8371
08-04 11:58:05.829   372   372 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,08-04 11:58:05.829  8371  8371 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-04 11:58:05.829  8371  8371 I wpa_supplicant: ssSupport state is = 1
08-04 11:58:05.829  8371  8371 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-04 11:58:05.829  8371  8371 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-04 11:58:05.829  8371  8371 E wpa_supplicant: SIM READ ERROR
08-04 11:58:05.829  8371  8371 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-04 11:58:05.829  8371  8371 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-04 11:58:05.829  8371  8371 E wpa_supplicant: SIM READ ERROR
08-04 11:58:05.829  8371  8371 I wpa_supplicant: Blacklist: Clear (all) 
,08-04 11:58:05.839  8371  8371 I wpa_supplicant: wpa_default_ap_write_once
08-04 11:58:05.839  8371  8371 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,08-04 11:58:05.839  8371  8371 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-04 11:58:05.839  8371  8371 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-04 11:58:05.839  8371  8371 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-04 11:58:05.839  8371  8371 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-04 11:58:05.839  8371  8371 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-04 11:58:06.289   765  1062 I PowerManagerService: [PWL] Off : 140s ago
08-04 11:58:06.289   765  1062 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-04 11:58:06.289   765  1062 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-04 11:58:06.289   765  1062 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=765, ws=null) (elapsedTime=21144)
08-04 11:58:06.289   765  1062 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=8273, ws=null) (elapsedTime=1882)
08-04 11:58:06.289   765  1062 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=1171)
,08-04 11:58:06.499   765  1152 E Tethering: No numeric data
,08-04 11:58:06.499   765  1152 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-04 11:58:06.499   765  1146 V NetworkStats: performPollLocked(flags=0x1)
08-04 11:58:06.499   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 11:58:06.499   765  1146 D NetworkStatsFactory: UpdateStatsForKnox
,08-04 11:58:06.499   765  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:06.499  1195  1195 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,08-04 11:58:06.499  1195  1195 D HotspotTile: updateTetherState():false, false
,08-04 11:58:06.499   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:58:06.499   765  1146 V NetworkStats: performPollLocked() took 4ms
,08-04 11:58:06.499   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 11:58:06.499   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 11:58:06.509  8371  8371 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-04 11:58:06.519  8371  8371 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-04 11:58:06.519  8371  8371 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-04 11:58:06.519  8371  8371 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-04 11:58:06.519   372   372 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8371
08-04 11:58:06.519   372   372 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,08-04 11:58:06.519  8371  8371 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-04 11:58:06.519  8371  8371 I wpa_supplicant: ssSupport state is = 1
,08-04 11:58:06.519  8371  8371 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-04 11:58:06.519  8371  8371 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-04 11:58:06.519   372   372 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8371
08-04 11:58:06.519   372   372 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,08-04 11:58:06.519  8371  8371 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-04 11:58:06.519  8371  8371 I wpa_supplicant: ssSupport state is = 1
08-04 11:58:06.519  8371  8371 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-04 11:58:06.519  8371  8371 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-04 11:58:06.519  8371  8371 E wpa_supplicant: SIM READ ERROR
08-04 11:58:06.519  8371  8371 I wpa_supplicant: wpa_default_ap_write_once
08-04 11:58:06.519  8371  8371 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-04 11:58:06.519  8371  8371 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-04 11:58:06.539  8371  8371 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
,08-04 11:58:06.539  8371  8371 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-04 11:58:06.539  8371  8371 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,08-04 11:58:06.539  8371  8371 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-04 11:58:06.539   765  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-04 11:58:06.539   765  1149 D WifiNative-HAL: callSECApiBoolean - ID [21]
,08-04 11:58:06.539  8371  8371 I wpa_supplicant: HOTSPOT20_ENABLE called
08-04 11:58:06.539  8371  8371 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-04 11:58:06.539  8371  8371 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-04 11:58:06.539  8371  8371 E wpa_supplicant: SIM READ ERROR
08-04 11:58:06.539  8371  8371 I wpa_supplicant: Blacklist: Clear (all) 
,08-04 11:58:06.589  8371  8371 I wpa_supplicant: Skip scan - bUseNetwork false
,08-04 11:58:06.589   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:58:06.589   765  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,08-04 11:58:06.589  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 11:58:06.589  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-04 11:58:06.589  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:58:06.589  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:58:06.589  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:58:06.589  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:58:06.589  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:58:06.589  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:58:06.589  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:58:06.589  1195  1195 D StatusBar.NetworkController: applyOpen
,08-04 11:58:06.589  1321  1321 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:58:06.599  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 11:58:06.599  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-04 11:58:06.599  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-04 11:58:06.599  1195  1604 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-04 11:58:06.599  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:58:06.599  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:58:06.599  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:58:06.599  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:58:06.599  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:58:06.599  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:58:06.599  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:58:06.599  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 11:58:06.599   765  1149 D WifiNative-HAL: callSECApiInt - ID [210]
,08-04 11:58:06.599  1195  1195 D HotspotTile: onReceive : 3, 0
,08-04 11:58:06.599  7235  7235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 11:58:06.599   765  1149 D WifiConfigStore: Loading config and enabling all networks 
,08-04 11:58:06.599  6901  6901 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-04 11:58:06.609   765  1652 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:06.609   765  1149 E WifiConfigStore: Not a HS20
,08-04 11:58:06.619  7299  7299 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-04 11:58:06.619  7299  7299 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-04 11:58:06.619  7299  7299 D SecurityLogAgent: StateMachine : Current State = 1
08-04 11:58:06.619  7299  7299 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-04 11:58:06.619   765  1149 E WifiConfigStore: Not a HS20
,08-04 11:58:06.629   765  1149 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-04 11:58:06.629   765  1149 D WifiNative-HAL: callSECApiInt - ID [65]
,08-04 11:58:06.639   765  1149 D WifiNative-HAL: callSECApiBoolean - ID [13]
08-04 11:58:06.639  8371  8371 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-04 11:58:06.639  8371  8371 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-04 11:58:06.639  8371  8371 I wpa_supplicant: reset timer : RESET_TIMER 0
08-04 11:58:06.639  8371  8371 I wpa_supplicant: P2P: Current p2p state = IDLE
08-04 11:58:06.639  8371  8371 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-04 11:58:06.639  8371  8371 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-04 11:58:06.639  8371  8371 I wpa_supplicant: First Scan Start
,08-04 11:58:06.639  8371  8371 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-04 11:58:06.639  7647  7647 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 11:58:06.639   765  1149 D WifiNative-HAL: Setting external_sim to 1
08-04 11:58:06.639   765  1149 D WifiStateMachine: Setting OUI to DA-A1-19
08-04 11:58:06.639   765  1149 I WifiNative-HAL: startHal
08-04 11:58:06.639   765  1149 E wifi    : getStaticLongField sWifiHalHandle 0x935db86c
08-04 11:58:06.639   765  1149 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0xb0178e
08-04 11:58:06.639   765  1149 I WifiNative-HAL: Could not start hal
,08-04 11:58:06.659   765  1149 E native  : do suspend true
,08-04 11:58:06.659   765  1148 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-04 11:58:06.659   298  1055 D CommandListener: Setting iface cfg
08-04 11:58:06.659   298  1055 D CommandListener: Trying to bring up p2p0
,08-04 11:58:06.659   765   765 D WifiScanningService: SCAN_AVAILABLE : 3
08-04 11:58:06.659   765   765 D RttService: SCAN_AVAILABLE : 3
08-04 11:58:06.659   765  1166 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:06.659   765  1166 I WifiNative-HAL: startHal
08-04 11:58:06.659   765  1166 E wifi    : getStaticLongField sWifiHalHandle 0x9b2cd99c
08-04 11:58:06.659   765  1166 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0xb0177a
08-04 11:58:06.659   765  1166 I WifiNative-HAL: Could not start hal
08-04 11:58:06.659   765  1166 E WifiScanningService: could not start HAL
08-04 11:58:06.659   765  1148 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-04 11:58:06.659   765  1167 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:06.659   765  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
08-04 11:58:06.659   765  1148 D WifiP2pService: P2pEnablingState
,08-04 11:58:06.659   765  1148 D WifiP2pService: P2pEnablingState{ what=147457 }
08-04 11:58:06.659   765  1148 D WifiP2pService: P2p socket connection successful
08-04 11:58:06.669   765  1148 D WifiP2pService: P2pEnabledState
,08-04 11:58:06.669   765  1060 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-04 11:58:06.669   765  1060 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-04 11:58:06.669   765  1060 D WifiDisplayController: disconnect
08-04 11:58:06.669   765  1060 D WifiDisplayController: updateConnection
08-04 11:58:06.669   765  1060 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-04 11:58:06.669   765   765 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-04 11:58:06.669   765  1060 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-04 11:58:06.669   765  1149 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-04 11:58:06.669   765  1149 D WifiNative-HAL: callSECStringApiVoid - ID [215]
08-04 11:58:06.669   765  1149 E WifiNative-HAL: invaild command id : 215
,08-04 11:58:06.669   765  1148 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-04 11:58:06.669  1195  1195 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-04 11:58:06.669   765  1476 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-04 11:58:06.669  1195  1195 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
08-04 11:58:06.669   765  1060 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:06.669   765  1060 D WifiDisplayAdapter: onP2pDisconnected
08-04 11:58:06.669   765  1060 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-04 11:58:06.669   765  1060 D IpRemoteDisplayController: WfdBridgeServer is already null
08-04 11:58:06.669   765  1151 E ConnectivityService: updateNetworkInfo()
08-04 11:58:06.669   765  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,08-04 11:58:06.669  7675  7675 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,08-04 11:58:06.679   765  1148 D WifiNative-HAL: p2pGetDeviceAddress
,08-04 11:58:06.679   765  1148 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:de:28:a3
,08-04 11:58:06.679  1321  1321 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-04 11:58:06.679  1321  1321 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-04 11:58:06.679   765  1703 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:06.679  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-04 11:58:06.679   765   784 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:06.679  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-04 11:58:06.679  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-04 11:58:06.679  1321  1321 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-04 11:58:06.679   765  1060 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
08-04 11:58:06.679   765  1060 D WifiDisplayController:  deviceAddress: ea:50:8b:de:28:a3
08-04 11:58:06.679   765  1060 D WifiDisplayController:  primary type: 10-0050F204-5
08-04 11:58:06.679   765  1060 D WifiDisplayController:  secondary type: null
08-04 11:58:06.679   765  1060 D WifiDisplayController:  wps: 0
08-04 11:58:06.679   765  1060 D WifiDisplayController:  grpcapab: 0
08-04 11:58:06.679   765  1060 D WifiDisplayController:  devcapab: 0
08-04 11:58:06.679   765  1060 D WifiDisplayController:  status: 3
08-04 11:58:06.679   765  1060 D WifiDisplayController:  wfdInfo: null
08-04 11:58:06.679   765  1060 D WifiDisplayController:  groupownerAddress: null
08-04 11:58:06.679   765  1060 D WifiDisplayController:  GOdeviceName: null
08-04 11:58:06.679   765  1060 D WifiDisplayController:  interfaceAddress: 
08-04 11:58:06.679   765  1060 D WifiDisplayController:  SConnectInfo : null
08-04 11:58:06.679  1321  2802 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-04 11:58:06.679   765  1148 D WifiP2pService: DeviceAddress: ea:28:a3
,08-04 11:58:06.679  6992  6992 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-04 11:58:06.689  8273  8325 D bt_vendor: op for 7
,08-04 11:58:06.689  7675  7675 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-04 11:58:06.689  7675  7675 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,08-04 11:58:06.689  7675  7675 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,08-04 11:58:06.689  7675  7675 D WifiDirectBR: stopServiceTest : false
,08-04 11:58:06.709  8371  8371 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-04 11:58:06.719  8371  8371 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,08-04 11:58:06.729   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-04 11:58:06.729   765  1149 D SecContentProvider2: mCursor = null
,08-04 11:58:06.729   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-04 11:58:06.729   765  1149 D SecContentProvider2: mCursor = null
,08-04 11:58:06.739   765  1148 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-04 11:58:06.739   765  1148 D WifiP2pService: InactiveState
08-04 11:58:06.739   765  1148 D WifiP2pService: InactiveState{ what=143376 }
,08-04 11:58:06.739   765  1148 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-04 11:58:06.739  8371  8371 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-04 11:58:06.739   765  1148 D WifiP2pService: InactiveState{ what=143376 }
,08-04 11:58:06.739   765  1148 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-04 11:58:06.879  8273  8337 D bt_upio : ..proc_btwrite_timeout..
,08-04 11:58:07.229  7235  7294 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:58:07.229  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:58:07.229  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:58:07.229  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:58:07.229  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:58:07.229  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:58:07.229  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:58:07.229  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 11:58:07.239  7235  7294 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 11:58:07.249  7235  7294 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-04 11:58:07.249  7235  7294 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-04 11:58:07.249  7235  7294 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@520966f Bundle[{}]
,08-04 11:58:07.249  7235  7294 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-04 11:58:07.249  7235  7294 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-04 11:58:07.259  7235  7294 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,08-04 11:58:07.259  7235  7294 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-04 11:58:07.259  7235  7294 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-04 11:58:07.259  7235  7294 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-04 11:58:07.259  7235  7294 I System.out: Running OutgoingSocketThread
,08-04 11:58:07.269  7235  8402 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1277)
,08-04 11:58:07.269  7235  8402 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 54282
,08-04 11:58:07.269  7235  8402 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-04 11:58:07.359   765  3091 D SSRM:n  : SIOP:: AP = 360, PST = 350, CUR = 450
,08-04 11:58:07.439  8371  8371 I wpa_supplicant: nl80211: Received scan results (31 BSSes)
08-04 11:58:07.439  8371  8371 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-04 11:58:07.439  8371  8371 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
08-04 11:58:07.439  8371  8371 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-04 11:58:07.439  8371  8371 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=5 BSSID=00.00.00 SSID=4E47373030
,08-04 11:58:07.459   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-04 11:58:07.459   765  1149 D SecContentProvider2: mCursor = null
,08-04 11:58:07.499  8371  8371 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-04 11:58:07.499  8371  8371 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=6 BSSID=00.00.00 SSID=4E47373030
,08-04 11:58:07.509  8371  8371 I wpa_supplicant: Associated with F4.99.3E
08-04 11:58:07.509  8371  8371 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-04 11:58:07.509  8371  8371 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-04 11:58:07.509   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-04 11:58:07.509   765  1149 D SecContentProvider2: mCursor = null
,08-04 11:58:07.519   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-04 11:58:07.519   765  1149 D SecContentProvider2: mCursor = null
,08-04 11:58:07.519  8371  8371 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-04 11:58:07.519  8371  8371 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-04 11:58:07.519  8371  8371 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-04 11:58:07.529  8371  8371 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-04 11:58:07.529  8371  8371 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-04 11:58:07.529  8371  8371 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=1 id_str=]
08-04 11:58:07.529  8371  8371 I wpa_supplicant: Blacklist: Clear (temp) 
08-04 11:58:07.529  8371  8371 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-04 11:58:07.529   765  1149 D WifiNative-HAL: callSECApiVoid - ID [50]
,08-04 11:58:07.529  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-04 11:58:07.529  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 11:58:07.539   765  1149 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-04 11:58:07.539   765  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 11:58:07.539   765  1151 D ConnectivityService: Got NetworkAgent Messenger
08-04 11:58:07.539   765  1151 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,08-04 11:58:07.539   765  1151 E ConnectivityService: updateNetworkInfo()
08-04 11:58:07.539   765  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 11:58:07.539   765  1151 D ConnectivityService: NetworkAgent connected
,08-04 11:58:07.549  1321  1321 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-04 11:58:07.549  1321  1321 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-04 11:58:07.549   765  1352 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:07.549   765  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 11:58:07.549  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-04 11:58:07.549   765  1263 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:07.549  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-04 11:58:07.549  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,08-04 11:58:07.549  1321  1321 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-04 11:58:07.549  1321  2802 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-04 11:58:07.559   298  1055 D CommandListener: Setting iface cfg
,08-04 11:58:07.559   765  1149 E WifiStateMachine: Start Dhcp Watchdog 3
,08-04 11:58:07.569   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-04 11:58:07.569   765  1149 D SecContentProvider2: mCursor = null
,08-04 11:58:07.569   765  1330 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:07.569  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-04 11:58:07.579  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 11:58:07.579   765  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,08-04 11:58:07.579   765  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-04 11:58:07.579   765  1149 D SecContentProvider2: mCursor = null
,08-04 11:58:07.589  6901  6901 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-04 11:58:07.659   765  1149 E native  : do suspend false
,08-04 11:58:07.659   765  1148 D WifiP2pService: InactiveState{ what=143375 }
,08-04 11:58:07.659   765  1148 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-04 11:58:07.679   303   303 E SMD     : DCD ON
,08-04 11:58:07.879  8407  8407 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-04 11:58:07.879  8407  8407 I dhcpcd  : version 5.5.6 starting
,08-04 11:58:07.879  8407  8407 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-04 11:58:07.939  8407  8407 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-04 11:58:07.939  8407  8407 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-04 11:58:07.939  8407  8407 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-04 11:58:07.939  8407  8407 I dhcpcd  : bssid match
08-04 11:58:07.939  8407  8407 I dhcpcd  : wlan0: rebinding lease of 192.168.1.122
,08-04 11:58:07.959  8407  8407 I dhcpcd  : wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,08-04 11:58:07.959  8407  8407 I dhcpcd  : wlan0: leased 192.168.1.122 for 172800 seconds
,08-04 11:58:07.959   765  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,08-04 11:58:08.269  7235  7294 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1278)
08-04 11:58:08.269  7235  7294 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1278)
,08-04 11:58:08.269   765  1149 E native  : do suspend true
,08-04 11:58:08.269  7235  7294 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1283)
,08-04 11:58:08.269  7235  7294 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-04 11:58:08.269  7235  7294 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1284)
,08-04 11:58:08.279   765  1148 D WifiP2pService: InactiveState{ what=143375 }
,08-04 11:58:08.279   765  1148 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-04 11:58:08.279   765  1149 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-04 11:58:08.289   765  1149 E WifiStateMachine: VerifyingLinkState enter
08-04 11:58:08.289   765  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,08-04 11:58:08.289  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-04 11:58:08.289  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-04 11:58:08.289  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 11:58:08.289  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@475145d added. We now have 2 listener(s)
,08-04 11:58:08.289   765  1149 D WifiNative-HAL: callSECApiInt - ID [210]
,08-04 11:58:08.289   765  1151 E ConnectivityService: updateNetworkInfo()
,08-04 11:58:08.289   765  1151 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-04 11:58:08.289   765  1151 D ConnectivityService: Adding iface wlan0 to network 504
,08-04 11:58:08.289  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,08-04 11:58:08.289  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 11:58:08.289  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:58:08.289  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 11:58:08.289  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2efc31d2 added. We now have 9 listener(s)
08-04 11:58:08.289  7235  7294 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 11:58:08.289  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 11:58:08.289   765  1161 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
08-04 11:58:08.289   765  1161 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-04 11:58:08.289   765  1161 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-04 11:58:08.299   765  1161 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-04 11:58:08.299   765  1161 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-04 11:58:08.299  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-04 11:58:08.299  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 11:58:08.309  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 11:58:08.309  7235  7294 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:58:08.309  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:58:08.309  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:58:08.309  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:58:08.309  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:58:08.309  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:58:08.309  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:58:08.309  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 11:58:08.309  7235  7294 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 11:58:08.309  7235  7294 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 11:58:08.309  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:58:08.309  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 11:58:08.309  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a28d9a0 added. We now have 3 listener(s)
,08-04 11:58:08.309  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:58:08.319  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,08-04 11:58:08.319  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 11:58:08.319  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:58:08.319  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 11:58:08.319  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27739959 added. We now have 10 listener(s)
08-04 11:58:08.319  7235  7294 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:58:08.319  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:58:08.319  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 11:58:08.319   765  1149 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
08-04 11:58:08.319  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:58:08.319  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 11:58:08.319  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 11:58:08.319   765   765 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-04 11:58:08.319  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 11:58:08.319  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-04 11:58:08.319  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@475145d removed from the list
08-04 11:58:08.319  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:08.319  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2efc31d2 removed from the list
08-04 11:58:08.319   765  1149 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-04 11:58:08.319  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 11:58:08.329  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 11:58:08.329   765   765 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-04 11:58:08.329   765   765 I WifiTrafficPoller: mBoosterFLAG : 0
08-04 11:58:08.329   765   765 I WifiTrafficPoller: current booster mode : FullMode
08-04 11:58:08.329   765   765 D WifiNative-HAL: callSECApiVoid - ID [212]
,08-04 11:58:08.339  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-04 11:58:08.339   765  1151 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-04 11:58:08.339  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:08.339  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 11:58:08.339   765  1151 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-04 11:58:08.339  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:58:08.339  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:58:08.339  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 11:58:08.339  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2efc31d2 not in the list
08-04 11:58:08.339  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:08.339  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 11:58:08.339   765  1151 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 504
08-04 11:58:08.339  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:58:08.339  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:58:08.339  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:08.339  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27739959 removed from the list
08-04 11:58:08.339  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:58:08.339  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:08.339  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:08.339  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:58:08.339  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3a28d9a0 removed from the list
,08-04 11:58:08.339  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 11:58:08.339   765  1151 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-04 11:58:08.339   765  1151 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
08-04 11:58:08.339   765  1151 D ConnectivityService: updateSourceRoutes : add src route for:192.168.1.122
,08-04 11:58:08.339   298  1055 V         : QcRouteController
,08-04 11:58:08.349  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 11:58:08.349  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38c7991e added. We now have 2 listener(s)
,08-04 11:58:08.349  1195  1195 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-04 11:58:08.349  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
08-04 11:58:08.349  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-04 11:58:08.349  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:58:08.349  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 11:58:08.349  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:58:08.349  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:58:08.349  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d785ff added. We now have 9 listener(s)
08-04 11:58:08.349  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:58:08.349  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:58:08.349  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:58:08.349  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:58:08.349  1195  1195 D StatusBar.NetworkController: applyOpen
,08-04 11:58:08.349  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:58:08.349  7235  7294 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:58:08.349  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:58:08.349  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 11:58:08.349  1321  1321 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-04 11:58:08.349  1321  1321 I NearbySettings: MountReceiver.onReceive - Keep current state
08-04 11:58:08.359  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 11:58:08.359  7235  7294 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:58:08.359  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:58:08.359  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:58:08.359  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:58:08.359  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:58:08.359  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:58:08.359  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:58:08.359  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 11:58:08.359  7235  7294 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 11:58:08.359  7235  7294 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 11:58:08.359  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 11:58:08.359  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@243b7215 added. We now have 3 listener(s)
,08-04 11:58:08.359  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:58:08.359  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:58:08.359  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
08-04 11:58:08.359  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 11:58:08.359  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:58:08.359  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:58:08.359  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b50292a added. We now have 10 listener(s)
08-04 11:58:08.359  7235  7294 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:58:08.359  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 11:58:08.359  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 11:58:08.359  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 11:58:08.359  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:58:08.359  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-04 11:58:08.359  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-04 11:58:08.359   298  1055 V         : QcRouteController
,08-04 11:58:08.369  7235  7294 E BluetoothAdapter: bluetooth le advertising not supported
08-04 11:58:08.369  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 11:58:08.369  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 11:58:08.369  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-04 11:58:08.369  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 11:58:08.369   765  1652 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:08.369  7235  7294 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-04 11:58:08.369  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:58:08.369  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 11:58:08.379  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 11:58:08.379  6901  6901 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
08-04 11:58:08.379  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:58:08.379  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:58:08.379  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:58:08.379  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:08.379  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:58:08.379  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:58:08.379  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38c7991e removed from the list
08-04 11:58:08.379  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:08.379  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d785ff removed from the list
08-04 11:58:08.379  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:58:08.379  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:08.379  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:08.379  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 11:58:08.379  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:58:08.379  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:58:08.379  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:08.379  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8d785ff not in the list
08-04 11:58:08.379  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:08.379  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 11:58:08.379  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:58:08.379  7235  7294 D BluetoothLeScanner: could not find callback wrapper
08-04 11:58:08.379  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:58:08.379  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:58:08.379  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:08.379  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b50292a removed from the list
08-04 11:58:08.379  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:58:08.379  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:08.379  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:08.379  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:58:08.379  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@243b7215 removed from the list
08-04 11:58:08.379  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 11:58:08.379  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e6e1a91 added. We now have 2 listener(s)
,08-04 11:58:08.379  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,08-04 11:58:08.379  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 11:58:08.379  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:58:08.379  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:58:08.379   298  1055 V         : QcRouteController
08-04 11:58:08.379  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e1fadf6 added. We now have 9 listener(s)
,08-04 11:58:08.389  1321  1321 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-04 11:58:08.389  7235  7294 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:58:08.389  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 11:58:08.389  1321  1321 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-04 11:58:08.389   765  3205 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:08.389  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 11:58:08.389  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-04 11:58:08.389   765  1263 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:08.389  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-04 11:58:08.389  1321  1321 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-04 11:58:08.389  7235  7294 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:58:08.389  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:58:08.389  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:58:08.389  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:58:08.389  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:58:08.389  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:58:08.389  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:58:08.389  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 11:58:08.389  1321  1321 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-04 11:58:08.389  1321  2802 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-04 11:58:08.389  7235  7294 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 11:58:08.389  7235  7294 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 11:58:08.389  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 11:58:08.389  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2c6c64 added. We now have 3 listener(s)
,08-04 11:58:08.389  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:58:08.399  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,08-04 11:58:08.399  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 11:58:08.399  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 11:58:08.399  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 11:58:08.399  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:58:08.399  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848cecd added. We now have 10 listener(s)
08-04 11:58:08.399  7235  7294 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:58:08.399  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-04 11:58:08.399   765  1444 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:08.399  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-04 11:58:08.399   298  1055 V         : QcRouteController
,08-04 11:58:08.399  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 11:58:08.399  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 11:58:08.399  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:58:08.399  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-04 11:58:08.399  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-04 11:58:08.399  7235  7294 E BluetoothAdapter: bluetooth le advertising not supported
,08-04 11:58:08.399  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 11:58:08.399  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 11:58:08.409  6901  6901 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
08-04 11:58:08.409  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 11:58:08.409  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:58:08.409  7235  7294 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-04 11:58:08.409  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:58:08.409  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:58:08.409  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 11:58:08.409  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:58:08.409  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:08.409  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:58:08.409  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:58:08.409  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e6e1a91 removed from the list
08-04 11:58:08.409  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:08.409  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e1fadf6 removed from the list
08-04 11:58:08.409  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:58:08.409  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:08.409  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:08.409  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 11:58:08.409  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:58:08.409  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:58:08.409  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:08.409  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e1fadf6 not in the list
08-04 11:58:08.409  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:08.409  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 11:58:08.409  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:58:08.409  7235  7294 D BluetoothLeScanner: could not find callback wrapper
08-04 11:58:08.409  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:58:08.409  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:58:08.409  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:08.409  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3848cecd removed from the list
08-04 11:58:08.409  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:58:08.409  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:08.409  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:08.409  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:58:08.409  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f2c6c64 removed from the list
,08-04 11:58:08.409  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 11:58:08.409  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2475ead0 added. We now have 2 listener(s)
,08-04 11:58:08.419  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
08-04 11:58:08.419  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 11:58:08.419  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:58:08.419   298  1055 V         : QcRouteController
08-04 11:58:08.419  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:58:08.419  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20a08ac9 added. We now have 9 listener(s)
08-04 11:58:08.419  7235  7294 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 11:58:08.419  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 11:58:08.419  1321  1321 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-04 11:58:08.419  1321  1321 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-04 11:58:08.419  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 11:58:08.419  7235  7294 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:58:08.419  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:58:08.419  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:58:08.419  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:58:08.419  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:58:08.419  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:58:08.419  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:58:08.419  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 11:58:08.419  7235  7294 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 11:58:08.419  7235  7294 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 11:58:08.419  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 11:58:08.429  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e63ecef added. We now have 3 listener(s)
,08-04 11:58:08.429  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:58:08.429  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:58:08.429  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,08-04 11:58:08.429   765  1330 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-04 11:58:08.429  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 11:58:08.429  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:58:08.429  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:58:08.429  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2296e3fc added. We now have 10 listener(s)
08-04 11:58:08.429  7235  7294 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 11:58:08.429  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 11:58:08.429  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 11:58:08.429  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 11:58:08.429  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:58:08.429  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-04 11:58:08.429   298  1055 V         : QcRouteController
,08-04 11:58:08.439   298  1055 V         : QcRouteController
,08-04 11:58:08.439  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-04 11:58:08.439   765  1573 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:08.439  7235  7294 E BluetoothAdapter: bluetooth le advertising not supported
08-04 11:58:08.439  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-04 11:58:08.439  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 11:58:08.449  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-04 11:58:08.449  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 11:58:08.449  6901  6901 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-04 11:58:08.449  7235  7294 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-04 11:58:08.449  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:58:08.449  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:58:08.449  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:58:08.449  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:58:08.449  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:08.449  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:58:08.449  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:58:08.449  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2475ead0 removed from the list
08-04 11:58:08.449  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:08.449  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20a08ac9 removed from the list
08-04 11:58:08.449  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:58:08.449  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:08.449  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:08.449  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 11:58:08.449  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:58:08.449  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:58:08.449  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:08.449  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20a08ac9 not in the list
08-04 11:58:08.449  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:08.449  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 11:58:08.449  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:58:08.449  7235  7294 D BluetoothLeScanner: could not find callback wrapper
08-04 11:58:08.449  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 11:58:08.449  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:58:08.449  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:08.449  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2296e3fc removed from the list
08-04 11:58:08.449  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:58:08.449  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:08.449  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:08.449  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:58:08.449  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e63ecef removed from the list
08-04 11:58:08.449  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 11:58:08.449  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d2c690b added. We now have 2 listener(s)
,08-04 11:58:08.459  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
08-04 11:58:08.459  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 11:58:08.459  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:58:08.459  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:58:08.459  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d6c43e8 added. We now have 9 listener(s)
08-04 11:58:08.459  7235  7294 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 11:58:08.459  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 11:58:08.459  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 11:58:08.459  7235  7294 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:58:08.459  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:58:08.459  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:58:08.459  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:58:08.459  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:58:08.459  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 11:58:08.459  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 11:58:08.459  7235  7294 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 11:58:08.459   765  1015 W ProcessCpuTracker: Skipping unknown process pid 8467
,08-04 11:58:08.459  7235  7294 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 11:58:08.459  7235  7294 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 11:58:08.459  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 11:58:08.459  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eed80a6 added. We now have 3 listener(s)
,08-04 11:58:08.469  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:58:08.469  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:58:08.469   298  1055 V         : QcRouteController
,08-04 11:58:08.469  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
08-04 11:58:08.469  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 11:58:08.469  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 11:58:08.469  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 11:58:08.469  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb68ae7 added. We now have 10 listener(s)
08-04 11:58:08.469  7235  7294 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 11:58:08.469   267   267 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
,08-04 11:58:08.469  7235  7294 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 11:58:08.469  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 11:58:08.469  7235  7294 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 11:58:08.469  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:58:08.469  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:08.469  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 11:58:08.469  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:58:08.469  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d2c690b removed from the list
08-04 11:58:08.469  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:08.469  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d6c43e8 removed from the list
08-04 11:58:08.469  7235  7294 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:58:08.469  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 11:58:08.469  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:08.469  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 11:58:08.469  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:58:08.469  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:58:08.469  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:08.469  7235  7294 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d6c43e8 not in the list
08-04 11:58:08.469  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:08.469  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 11:58:08.469  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 11:58:08.469  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 11:58:08.469  7235  7294 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:58:08.469  7235  7294 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1eb68ae7 removed from the list
08-04 11:58:08.469  7235  7294 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 11:58:08.469  7235  7294 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:58:08.469  7235  7294 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:58:08.469  7235  7294 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:58:08.469  7235  7294 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@eed80a6 removed from the list
,08-04 11:58:08.469  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-04 11:58:08.469  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-04 11:58:08.469  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-04 11:58:08.469  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-04 11:58:08.469  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-04 11:58:08.469  7235  7294 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,08-04 11:58:08.479  7235  8474 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1291, name: My test thread name)
,08-04 11:58:08.479  7235  8474 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1291, thread name: My test thread name)
08-04 11:58:08.479  7235  8474 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1291, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-04 11:58:08.489   765  1573 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=765
,08-04 11:58:08.489  7235  8475 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1293, name: My test thread name)
,08-04 11:58:08.489  7235  8475 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1293, thread name: My test thread name)
08-04 11:58:08.489  7235  8475 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1293, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-04 11:58:08.489  7235  7294 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,08-04 11:58:08.489  7235  7294 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-04 11:58:08.489  7235  7294 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-04 11:58:08.489  7235  7294 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-04 11:58:08.489  7235  7294 D com.test.thalitest.ThaliTestRunner: Total duration: 23763 ms
,08-04 11:58:08.489   765  1151 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
,08-04 11:58:08.489   765  1151 D ConnectivityService: LTETest block dns file not exists
,08-04 11:58:08.489   765  1151 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
08-04 11:58:08.489   765  1151 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,08-04 11:58:08.499   765  1151 D ConnectivityService: calling update connectivity
,08-04 11:58:08.499   765  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
08-04 11:58:08.499   765  1059 D EntConnectivity: Not allowed due to - mEnabled false
08-04 11:58:08.499   765  1151 E ConnectivityService: updateNetworkInfo()
,08-04 11:58:08.499   765  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
08-04 11:58:08.499   765  1151 E ConnectivityService: updateNetworkInfo()
08-04 11:58:08.499   765  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 11:58:08.499   765  1151 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-04 11:58:08.499   765  1151 D ConnectivityService: calling update connectivity
,08-04 11:58:08.499   765  1151 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-04 11:58:08.499   765  8403 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-04 11:58:08.499   765  8403 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-04 11:58:08.499   765  8403 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-04 11:58:08.499   765  8403 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,08-04 11:58:08.499   765  8403 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-04 11:58:08.499   765  1151 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 11:58:08.499   765  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:58:08.499   765  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:58:08.499   765  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:58:08.499  7235  7294 I jxcore-log: Total number of executed tests:  80
08-04 11:58:08.499  7235  7294 I jxcore-log: 
,08-04 11:58:08.499  7235  7294 I jxcore-log: Number of passed tests:  80
08-04 11:58:08.499  7235  7294 I jxcore-log: 
08-04 11:58:08.499  7235  7294 I jxcore-log: Number of failed tests:  0
08-04 11:58:08.499  7235  7294 I jxcore-log: 
08-04 11:58:08.499  7235  7294 I jxcore-log: Number of ignored tests:  0
08-04 11:58:08.499  7235  7294 I jxcore-log: 
08-04 11:58:08.499  7235  7294 I jxcore-log: Total duration:  23763
08-04 11:58:08.499  7235  7294 I jxcore-log: 
,08-04 11:58:08.509  7235  7294 I jxcore-log: Unit Test app is loaded
08-04 11:58:08.509  7235  7294 I jxcore-log: 
,08-04 11:58:08.509   765  1151 D ConnectivityService: currentScore = 0, newScore = 60
,08-04 11:58:08.509   765  1151 D ConnectivityService:    accepting network in place of null
08-04 11:58:08.509   765  1151 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-04 11:58:08.509  1428  1428 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-04 11:58:08.509   765  1151 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-04 11:58:08.509   765  1151 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-04 11:58:08.509   765  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-04 11:58:08.509   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-04 11:58:08.509   765  1152 D Tethering: MasterInitialState.processMessage what=3
08-04 11:58:08.509   765  1146 V NetworkStats: updateIfacesLocked()
08-04 11:58:08.509   765  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
08-04 11:58:08.509   765  1153 D SmartBondingService: getSBEnabled() enabled =false
08-04 11:58:08.509   765  1151 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
08-04 11:58:08.509   765  1153 D SmartBondingService: getSBEnabled() enabled =false
08-04 11:58:08.509   765  1153 D SmartBondingService: getSBEnabled() enabled =false
08-04 11:58:08.509   765  1151 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-04 11:58:08.509   765  1146 V NetworkStats: performPollLocked(flags=0x1)
,08-04 11:58:08.509   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:58:08.509   765  1151 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-04 11:58:08.509   765  1151 D ConnectivityService: calling update connectivity
08-04 11:58:08.509   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:58:08.509   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:58:08.509   765  1151 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-04 11:58:08.509  7235  7235 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-04 11:58:08.509   765  1059 D EntConnectivity: Not allowed due to - mEnabled false
08-04 11:58:08.509   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:58:08.509   765  1151 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-04 11:58:08.519   765  1146 D NetworkStatsFactory: UpdateStatsForKnox
08-04 11:58:08.519  1195  1599 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-04 11:58:08.519   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:58:08.519   765  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:08.519   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:58:08.519   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:58:08.519   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:58:08.519   765  1147 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,08-04 11:58:08.519  2540  3150 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-04 11:58:08.519   765  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,08-04 11:58:08.519  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 11:58:08.519  7235  7294 I jxcore-log: 
08-04 11:58:08.519   765  1476 I AudioService: getStreamVolume 3 index 0
,08-04 11:58:08.519   765  1146 V NetworkStats: performPollLocked() took 6ms
08-04 11:58:08.519   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 11:58:08.519  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 11:58:08.519  7235  7294 I jxcore-log: 
,08-04 11:58:08.519  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 11:58:08.519  7235  7294 I jxcore-log: 
,08-04 11:58:08.519  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 11:58:08.519  7235  7294 I jxcore-log: 
,08-04 11:58:08.519   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:58:08.519   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 11:58:08.519  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 11:58:08.519  7235  7294 I jxcore-log: 
,08-04 11:58:08.519  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 11:58:08.519  7235  7294 I jxcore-log: 
,08-04 11:58:08.529   765  1680 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:08.529  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 11:58:08.529  7235  7294 I jxcore-log: 
,08-04 11:58:08.529  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 11:58:08.529  7235  7294 I jxcore-log: 
,08-04 11:58:08.529  1195  1195 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-04 11:58:08.529  1195  1195 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-04 11:58:08.529  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 11:58:08.529  7235  7294 I jxcore-log: 
08-04 11:58:08.529  1195  1195 D StatusBar.NetworkController: updateDataNetType()
08-04 11:58:08.529  1195  1195 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
,08-04 11:58:08.529  1195  1195 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-04 11:58:08.529  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 11:58:08.529  7235  7294 I jxcore-log: 
,08-04 11:58:08.529  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 11:58:08.529  7235  7294 I jxcore-log: 
08-04 11:58:08.529  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 11:58:08.529  7235  7294 I jxcore-log: 
,08-04 11:58:08.529  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 11:58:08.529  7235  7294 I jxcore-log: 
08-04 11:58:08.529  1195  1195 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-04 11:58:08.529  1195  1195 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-04 11:58:08.529  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 11:58:08.529  7235  7294 I jxcore-log: 
08-04 11:58:08.529  1195  1195 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-04 11:58:08.529  1195  1195 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 11:58:08.529  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-04 11:58:08.529  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:58:08.529  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:58:08.529  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 11:58:08.529  7235  7294 I jxcore-log: 
08-04 11:58:08.529  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:58:08.529  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:58:08.529  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:58:08.529  1195  1195 D StatusBar.NetworkController: applyOpen
08-04 11:58:08.529  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 11:58:08.529  1195  1195 D StatusBar.NetworkController: applyOpen
,08-04 11:58:08.529  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 11:58:08.529  7235  7294 I jxcore-log: 
08-04 11:58:08.529  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 11:58:08.529  7235  7294 I jxcore-log: 
08-04 11:58:08.529  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 11:58:08.529  7235  7294 I jxcore-log: 
08-04 11:58:08.529  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 11:58:08.529  7235  7294 I jxcore-log: 
08-04 11:58:08.529  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 11:58:08.529  7235  7294 I jxcore-log: 
08-04 11:58:08.529  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 11:58:08.529  7235  7294 I jxcore-log: 
08-04 11:58:08.529  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 11:58:08.529  7235  7294 I jxcore-log: 
08-04 11:58:08.539  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 11:58:08.539  7235  7294 I jxcore-log: 
08-04 11:58:08.539  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 11:58:08.539  7235  7294 I jxcore-log: 
08-04 11:58:08.539  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 11:58:08.539  7235  7294 I jxcore-log: 
08-04 11:58:08.539  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 11:58:08.539  7235  7294 I jxcore-log: 
08-04 11:58:08.539  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 11:58:08.539  7235  7294 I jxcore-log: 
08-04 11:58:08.539  7235  7294 I jxcore-log: My device name is: samsung-SM-N9005
08-04 11:58:08.539  7235  7294 I jxcore-log: 
,08-04 11:58:08.589   765  8403 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-04 11:58:08.669   765  8403 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Aug 2016 09:58:08 GMT], X-Android-Received-Millis=[1470304688679], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470304688637]}
08-04 11:58:08.669   765  8403 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-04 11:58:08.669   765  8403 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-04 11:58:08.669   765  1151 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-04 11:58:08.669   765  1151 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-04 11:58:08.669   765  1151 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 11:58:08.669   765  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:58:08.669   765  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:58:08.669   765  1151 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-04 11:58:08.669   765  1151 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-04 11:58:08.669   765  1151 D ConnectivityService: calling update connectivity
08-04 11:58:08.669   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:58:08.669   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 11:58:08.679   765  1151 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-04 11:58:08.679   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:58:08.679   765  1151 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:58:08.679   765  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-04 11:58:08.679  1195  1599 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-04 11:58:08.679  2540  3150 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-04 11:58:08.679   765  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:08.679  1195  1195 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-04 11:58:08.679  1195  1195 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-04 11:58:08.679  1195  1195 D StatusBar.NetworkController: updateDataNetType()
08-04 11:58:08.679  1195  1195 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-04 11:58:08.679  1195  1195 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-04 11:58:08.679  1195  1195 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-04 11:58:08.679  1195  1195 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-04 11:58:08.679  1195  1195 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-04 11:58:08.679  1195  1195 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 11:58:08.679  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-04 11:58:09.009   765  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:58:09.019   765  1003 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:58:09.019   765  1003 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.019   765   765 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.019   765  1352 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.019   765   785 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.019   765  1232 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.019   765  1238 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.019   765   765 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.029   765  1330 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.029   765   784 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.029   765  1352 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.029   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
08-04 11:58:09.039   765   765 D SmartBondingService: SmartBondingReceiver: wifi is connected
08-04 11:58:09.039   765   765 D SmartBondingService: SmartBondingReceiver: wifi ap is not changed
08-04 11:58:09.039   765   765 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.039   765  1493 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.039   765  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
08-04 11:58:09.039   765  1153 D SmartBondingService: getSBEnabled() enabled =false
08-04 11:58:09.039   765   765 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.039   765  1153 D SmartBondingService: getSBEnabled() enabled =false
08-04 11:58:09.039   765  1153 D SmartBondingService: getSBEnabled() enabled =false
08-04 11:58:09.039   765   765 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.039   765  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
08-04 11:58:09.039   765   765 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.039   765  1232 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.039  7235  7235 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 11:58:09.039  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:58:09.039  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 11:58:09.039  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:58:09.039  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:58:09.039  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:58:09.039  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:58:09.039  7235  7235 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 11:58:09.039  7235  7235 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 11:58:09.039   765   765 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.039   765  1573 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.049   765  1330 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.049  7738  7738 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
08-04 11:58:09.059   765  1232 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.079  1498  1498 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
08-04 11:58:09.089   765  1652 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-04 11:58:09.089   765  1652 D SecContentProvider2: mCursor = null
,08-04 11:58:09.089   765  1493 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.089  7722  7722 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-04 11:58:09.089  7722  7722 I PCWCLIENTTRACE_PushUtil: sales region : global
08-04 11:58:09.089  7722  7722 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-04 11:58:09.089  7722  7722 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:58:09.099  7738  7738 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,08-04 11:58:09.099   765  1003 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.119  7797  7797 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:58:09.119  7797  7797 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-04 11:58:09.219  7351  7351 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,08-04 11:58:09.219  7351  7351 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,08-04 11:58:09.229  7351  7351 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,08-04 11:58:09.229  4014  4014 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-04 11:58:09.229  4014  4014 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1470304689236
,08-04 11:58:09.229  4014  4014 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,08-04 11:58:09.229   765  1680 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.229   765  1476 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.229  4014  4014 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,08-04 11:58:09.239  4014  4014 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().START
,08-04 11:58:09.239  4014  4014 I KLMS-2.4.511: : NetworkChangeOperations(): uploadRequestLog().START 
,08-04 11:58:09.239  4014  4014 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,08-04 11:58:09.249   765  1232 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.259  7370  7370 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,08-04 11:58:09.269   765   785 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,08-04 11:58:09.269   765   785 D ActivityManager: caller:android.app.ApplicationThreadProxy@169cc95f, r.packageName :com.samsung.android.app.galaxyfinder
,08-04 11:58:09.289  7844  7844 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-04 11:58:09.289   765  1352 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.289  3600  8498 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-04 11:58:09.289  3600  8498 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,08-04 11:58:09.289  3600  8498 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-04 11:58:09.289  6697  6697 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,08-04 11:58:09.289  6697  6697 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
08-04 11:58:09.289  6697  6697 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-04 11:58:09.299  6697  6697 I SA      : [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
08-04 11:58:09.299  6697  6697 I SA      : [OR] == isSIMCardReady false ==
,08-04 11:58:09.299   765  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.299  6697  6697 I SA      : [SCU] == networkStateCheck == true
,08-04 11:58:09.299  6697  6697 I SA      : [DM] getCountryCodeFromCSC : PL
08-04 11:58:09.299  6697  6697 I SA      : isChinaCountryCode : false
08-04 11:58:09.299  6697  6697 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-04 11:58:09.299  6697  6697 I SA      : [OR] == networkStateCheck true ==
,08-04 11:58:09.299  6697  6697 I SA      : [OR] GetMyCountryZoneTask
,08-04 11:58:09.299  6697  6697 I SA      : [OR] onReceive END
,08-04 11:58:09.309   765  1238 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.309   765  1263 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,08-04 11:58:09.309   765  1263 D ActivityManager: caller:android.app.ApplicationThreadProxy@176bd475, r.packageName :com.android.providers.downloads
,08-04 11:58:09.309  7863  7863 I SCloudBackupReceiver: Other Intent
,08-04 11:58:09.319  7009  7009 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,08-04 11:58:09.319  7009  7009 I KnoxUsageLogPro: premStatus:2
,08-04 11:58:09.319  7009  7009 I KnoxUsageLogPro: isEulaShown : false
,08-04 11:58:09.319  7009  7009 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,08-04 11:58:09.319  6697  8500 I SA      : [SRS] prepareGetMyCountryZone
,08-04 11:58:09.329  6697  8500 I SA      : [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,08-04 11:58:09.329  6697  8500 I SA      : [SSP] query invoked
,08-04 11:58:09.329  3600  8498 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-04 11:58:09.329  3600  8498 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,08-04 11:58:09.339   765  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.339  3600  8498 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,08-04 11:58:09.339  3600  8498 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,08-04 11:58:09.339  3600  8498 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,08-04 11:58:09.339  3600  8498 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,08-04 11:58:09.339  3600  8498 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,08-04 11:58:09.339  3600  8498 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-04 11:58:09.349  6697  8500 I SA      : [TPMU] GetMccFromDB : null
,08-04 11:58:09.349  6697  8500 I SA      : [SCU] getMccFromPreferece mcc = 260
08-04 11:58:09.349  6697  8500 I SA      : [TPM] isNoProxy(default) : true
,08-04 11:58:09.349   765  1238 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.349  3600  8498 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
08-04 11:58:09.349   765  1444 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.359  6697  8500 E File    : fail readDirectory() errno=2
,08-04 11:58:09.359  7968  7968 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-04 11:58:09.359   765  1680 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.359  7968  7968 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
08-04 11:58:09.359  7968  7968 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
08-04 11:58:09.359  3600  8498 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-04 11:58:09.369   765  1449 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.369   765   785 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.369   765  1476 D RCPManagerService: exchangeData() failure , invalid userId
,08-04 11:58:09.369   765  1352 D RCPManagerService: exchangeData() failure , invalid userId
,08-04 11:58:09.379   765  1330 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.379  7299  7299 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-04 11:58:09.379  7299  7299 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-04 11:58:09.379  7299  7299 D SecurityLogAgent: StateMachine : Current State = 1
08-04 11:58:09.379   765  1238 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.379  7299  7299 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-04 11:58:09.379   765  3205 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.379   765  1573 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.389   765  1263 D ActivityManager: startService callerProcessName:com.sec.android.app.SmartClipService, calleePkgName: com.sec.android.app.SmartClipService
,08-04 11:58:09.389   765  1263 D ActivityManager: caller:android.app.ApplicationThreadProxy@3ab21ed6, r.packageName :com.sec.android.app.SmartClipService
,08-04 11:58:09.399   765  1232 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-04 11:58:09.399   765  1232 D ActivityManager: caller:android.app.ApplicationThreadProxy@32c08557, r.packageName :com.google.android.gms
,08-04 11:58:09.399   765  1680 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.399   765  1652 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.399   765  1703 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.399   765  1493 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.399   765  1573 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.399   765  3205 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.399  2540  2540 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-04 11:58:09.409  2540  5371 I iu.UploadsManager: num queued entries: 0
,08-04 11:58:09.409  2540  5371 I iu.UploadsManager: num updated entries: 0
08-04 11:58:09.409  2540  5371 I iu.SyncManager: NEXT; no task
,08-04 11:58:09.419   765  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.419  8042  8042 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-04 11:58:09.509   765  1151 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-04 11:58:09.539   765  1449 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,08-04 11:58:09.539   765  1449 D ActivityManager: caller:android.app.ApplicationThreadProxy@3ce37844, r.packageName :com.sec.android.app.samsungapps
,08-04 11:58:09.549  8042  8042 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,08-04 11:58:09.549  8042  8042 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,08-04 11:58:09.549  8042  8042 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,08-04 11:58:09.549  8042  8042 D InitializeManagerStateMachine: exit::IDLE
08-04 11:58:09.549  8042  8042 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,08-04 11:58:09.549   765  1238 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.549   765  1352 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 11:58:09.549  8042  8042 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
08-04 11:58:09.549  8042  8042 D InitializeManagerStateMachine: exit::NETWORK_CHECK
08-04 11:58:09.559  8042  8042 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
08-04 11:58:09.559  8042  8042 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
08-04 11:58:09.559  8042  8042 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
08-04 11:58:09.559  8042  8042 D InitializeManagerStateMachine: entry::SUCCESS
08-04 11:58:09.559  8042  8042 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,08-04 11:58:09.559  8042  8042 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
08-04 11:58:09.559  8042  8042 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,08-04 11:58:09.559   765  1573 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.559  8042  8042 D InitializeManagerStateMachine: exit::SUCCESS
08-04 11:58:09.559  8042  8042 D InitializeManagerStateMachine: entry::IDLE
,08-04 11:58:09.579   765  1703 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.579  1864  8506 I qtaguid : Tagging socket 52 with tag 1000040700000000{268436487,0} uid -1, pid: 1864, getuid(): 10015
,08-04 11:58:09.579   765  1680 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.589   765  1330 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.589   765  1238 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.749   765  1449 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.749   765  1232 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.759   765  1263 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.759   765  1493 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.759   765  1573 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.759   765  1449 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.759   765  1703 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:09.849  6697  8500 I SA      : [RC New] Execute method=[GET] start
,08-04 11:58:09.879  6697  8500 I SA      : [RC New] Security=[true]
,08-04 11:58:09.889  6697  8500 I System.out: Thread-1075(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,08-04 11:58:09.889  6697  8500 I System.out: Thread-1075(ApacheHTTPLog):isShipBuild true
,08-04 11:58:09.889  6697  8500 I System.out: Thread-1075(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,08-04 11:58:10.459   765  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=true
,08-04 11:58:10.459   765  1151 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-04 11:58:10.459   765  1151 D ConnectivityService: identical MTU - not setting
08-04 11:58:10.459   765  1151 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
08-04 11:58:10.459   765  1151 D ConnectivityService: updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
,08-04 11:58:10.459   298  1055 V         : QcRouteController
,08-04 11:58:10.459   765   765 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
,08-04 11:58:10.459   765   765 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:10.459   765  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
08-04 11:58:10.459   765  1153 D SmartBondingService: getSBEnabled() enabled =false
08-04 11:58:10.459   765  1153 D SmartBondingService: getSBEnabled() enabled =false
08-04 11:58:10.459   765  1153 D SmartBondingService: getSBEnabled() enabled =false
,08-04 11:58:10.479  6697  8500 I SA      : [RC New] [v2liruge] api execute + 591
,08-04 11:58:10.479  6697  8500 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
08-04 11:58:10.479  6697  8500 I System.out: AsyncTask #1 calls detatch()
,08-04 11:58:10.479  6697  8500 I SA      : [TPMU] getNetworkMcc : 
,08-04 11:58:10.489   298  1055 V         : QcRouteController
,08-04 11:58:10.499   765  1151 W NetworkManagementService: route cmd failed: 
08-04 11:58:10.499   765  1151 W NetworkManagementService: com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '103 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 103 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
08-04 11:58:10.499   765  1151 W NetworkManagementService: '
08-04 11:58:10.499   765  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
08-04 11:58:10.499   765  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
08-04 11:58:10.499   765  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
08-04 11:58:10.499   765  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
08-04 11:58:10.499   765  1151 W NetworkManagementService: 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2844)
08-04 11:58:10.499   765  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5632)
08-04 11:58:10.499   765  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5444)
08-04 11:58:10.499   765  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService.access$2400(ConnectivityService.java:230)
08-04 11:58:10.499   765  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2387)
08-04 11:58:10.499   765  1151 W NetworkManagementService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:58:10.499   765  1151 W NetworkManagementService: 	at android.os.Looper.loop(Looper.java:145)
08-04 11:58:10.499   765  1151 W NetworkManagementService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 11:58:10.499  6697  8500 I SA      : [SCU] saveMccToPreferece Start
08-04 11:58:10.499   765  1151 V Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true
08-04 11:58:10.499  6697  8500 I SA      : [SCU] RegionMCC : 260
08-04 11:58:10.499   765  1151 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-04 11:58:10.499  6697  8500 I SA      : [SSP] query invoked
08-04 11:58:10.499   765  1151 D ConnectivityService: calling update connectivity
,08-04 11:58:10.499   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:58:10.499   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-04 11:58:10.499   765  1151 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-04 11:58:10.499   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:58:10.499  1195  1599 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-04 11:58:10.499  6697  8500 I SA      : [TPMU] GetMccFromDB : null
08-04 11:58:10.499  6697  8500 I SA      : [SCU] getMccFromPreferece mcc = 260
08-04 11:58:10.499  6697  8500 I SA      : [SCU] saveMccToPreferece End
,08-04 11:58:10.499  6697  8500 I SA      : [RC New] executeRequest [v2liruge] end. 653
08-04 11:58:10.499   765  1151 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:58:10.499  6697  8500 I SA      : [RC New] Execute end
,08-04 11:58:10.499   765  1151 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-04 11:58:10.499   765  1151 D ConnectivityService: calling update connectivity
08-04 11:58:10.499   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 11:58:10.499   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-04 11:58:10.499  2540  3150 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-04 11:58:10.499  6697  6697 I SA      : [OR] GetMyCountryZoneTask mcc = 260
08-04 11:58:10.499   765  1151 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-04 11:58:10.509  1195  1599 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-04 11:58:10.509   765  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-04 11:58:10.509  6697  6697 I SA      : [OR] GetMyCountryZoneTask Success
,08-04 11:58:10.509   765  1151 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-04 11:58:10.509  2540  3150 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-04 11:58:10.689   303   303 E SMD     : DCD ON
,08-04 11:58:10.909  8273  8295 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-04 11:58:11.029  7235  7294 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-04 11:58:11.029  7235  7294 I jxcore-log: 
,08-04 11:58:11.609  7235  7294 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-04 11:58:11.609  7235  7294 I jxcore-log: 
,08-04 11:58:11.629  7235  7294 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-04 11:58:11.629  7235  7294 I jxcore-log: 
,08-04 11:58:11.859   765  1149 E WifiStateMachine: CAPTIVE_PORTAL_EVENT_AUTHENTICATED
,08-04 11:58:11.949   267   374 I SurfaceFlinger: id=13 Removed Uoast (8/9)
,08-04 11:58:11.949   267   374 I SurfaceFlinger: id=13 Removed Uoast (-2/9)
,08-04 11:58:11.959   765  1680 D PowerManagerService: [api] [s] userActivity : event: 0 flags: 0 (uid: 1000 pid: 765) eventTime = 224614
,08-04 11:58:11.959   765  1680 D PowerManagerService: [api] release WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=765 (0x0)
08-04 11:58:11.959   765  1680 D PowerManagerService: [api] applyWakeLockFlagsOnReleaseLocked : userActivityNoUpdateLocked is called : SCREEN_BRIGHT_WAKE_LOCK        'WindowManager' ON_AFTER_RELEASE (uid=1000, pid=765, ws=WorkSource{10067}) (elapsedTime=3474)
,08-04 11:58:12.019   765  1117 V AlarmManager: waitForAlarm result :4
,08-04 11:58:12.019  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,08-04 11:58:12.019  1195  1195 D KeyguardUpdateMonitor: handleTimeUpdate
,08-04 11:58:12.019  1195  1195 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
08-04 11:58:12.019  1195  1195 I KeyguardEffectViewController: *** don't update sliding image ***
,08-04 11:58:12.059  1195  1195 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
08-04 11:58:12.059   765  1444 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-04 11:58:12.059  1195  1195 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,08-04 11:58:12.199  8407  8407 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
,08-04 11:58:12.289   765  1680 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,08-04 11:58:12.289   765  1680 D ActivityManager: caller:android.app.ApplicationThreadProxy@3c1d4b0, r.packageName :com.sec.spp.push
,08-04 11:58:12.309   765  1352 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:12.869   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,08-04 11:58:12.989  7235  7294 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-04 11:58:12.989  7235  7294 I jxcore-log: 
,08-04 11:58:13.049   765  1444 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:13.209  7235  7294 I jxcore-log: ERROR runTests: 
08-04 11:58:13.209  7235  7294 I jxcore-log: 
,08-04 11:58:13.209  7235  7294 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thaliLogger'
08-04 11:58:13.209  7235  7294 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"39","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-04 11:58:13.219  7235  7294 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-04 11:58:13.219  7235  7294 I jxcore-log:     _functionName: 'loadFile',
08-04 11:58:13.219  7235  7294 I jxcore-log:     _lineNumber: '26',
08-04 11:58:13.219  7235  7294 I jxcore-log:     _columnNumber: '11',
08-04 11:58:13.219  7235  7294 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-04 11:58:13.219  7235  7294 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-04 11:58:13.219  7235  7294 I jxcore-log:     _functionName: '',
08-04 11:58:13.219  7235  7294 I jxcore-log:     _lineNumber: '39',
08-04 11:58:13.219  7235  7294 I jxcore-log:     _columnNumber: '7',
08-04 11:58:13.219  7235  7294 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:39:7' },
08-04 11:58:13.219  7235  7294 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-04 11:58:13.219  7235  7294 I jxcore-log:     _functionName: '',
08-04 11:58:13.219  7235  7294 I jxcore-log:     _lineNumber: '35',
08-04 11:58:13.219  7235  7294 I jxcore-log:     _columnNumber: '3',
08-04 11:58:13.219  7235  7294 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-04 11:58:13.219  7235  7294 I jxcore-log:   { _fileName: 'module.js',
08-04 11:58:13.219  7235  7294 I jxcore-log:     _functionName: '$w.prototype._compile',
08-04 11:58:13.219  7235  7294 I jxcore-log:     _lineNumber: '621',
08-04 11:58:13.219  7235  7294 I jxcore-log:     _columnNumber: '8',
08-04 11:58:13.219  7235  7294 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-04 11:58:13.219  7235  7294 I jxcore-log:   { _fileName: 'module.js',
08-04 11:58:13.219  7235  7294 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-04 11:58:13.219  7235  7294 I jxcore-log:     _lineNumber: '651',
08-04 11:58:13.219  7235  7294 I jxcore-log:     _columnNumber: '1',
08-04 11:58:13.219  7235  7294 I jxcore-log:    
,08-04 11:58:13.219  7235  7294 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-04 11:58:13.219  7235  7294 I jxcore-log: 
08-04 11:58:13.219  7235  7294 E jxcore-log: Error: 
08-04 11:58:13.219  7235  7294 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thaliLogger'
08-04 11:58:13.219  7235  7294 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-04 11:58:13.219  7235  7294 E jxcore-log: 
,08-04 11:58:13.219  7235  7294 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 11:58:13.219  7235  7294 I jxcore-log: 
,08-04 11:58:13.539  8530  8530 D AndroidRuntime: 
08-04 11:58:13.539  8530  8530 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-04 11:58:13.549  8530  8530 D AndroidRuntime: CheckJNI is OFF
,08-04 11:58:13.549  8530  8530 D AndroidRuntime: readGMSProperty: start
08-04 11:58:13.549  8530  8530 D AndroidRuntime: readGMSProperty: already setted!!
,08-04 11:58:13.549  8530  8530 D AndroidRuntime: readGMSProperty: end
08-04 11:58:13.549  8530  8530 D AndroidRuntime: addProductProperty: start
,08-04 11:58:13.689   303   303 E SMD     : DCD ON
,08-04 11:58:13.729  8530  8530 E AffinityControl: AffinityControl: registerfunction enter
,08-04 11:58:13.749  8530  8530 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-04 11:58:13.759   765  1263 D PackageManager: START PACKAGE DELETE: observer{799945390}
08-04 11:58:13.759   765  1263 D PackageManager: pkg{<packageName>}
08-04 11:58:13.759   765  1263 D PackageManager: user{0}
08-04 11:58:13.759   765  1263 D PackageManager: caller{2000}
08-04 11:58:13.759   765  1263 D PackageManager: flags{2}
,08-04 11:58:13.759   765  1263 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-04 11:58:13.759   765  1263 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-04 11:58:13.759   765  1263 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-04 11:58:13.759   765  1263 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-04 11:58:13.759   765  1263 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-04 11:58:13.759   765  1066 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-04 11:58:13.759   765  1066 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
08-04 11:58:13.759   765  1066 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-04 11:58:13.759   765  1066 D ApplicationPolicy: getApplicationUninstallationEnabled
08-04 11:58:13.759   765  1066 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-04 11:58:13.759   765  1066 D PackageManager: !@killApplicatoin: 10079, uninstall pkg
,08-04 11:58:13.759   765  1015 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
08-04 11:58:13.769   765  1015 I ActivityManager: Killing 7235:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-04 11:58:13.769   765  1015 I ActivityManager:   Force finishing activity ActivityRecord{339f74da u0 com.test.thalitest/.MainActivity t99}
08-04 11:58:13.769   765  1015 D FocusedStackFrame: Set to : 0
,08-04 11:58:13.769   765  1060 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-04 11:58:13.769   765  1060 D PointerIcon: setMouseCustomIcon IconType is same.101
08-04 11:58:13.769   765  1060 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-04 11:58:13.769   765  1060 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-04 11:58:13.779   267  1709 I SurfaceFlinger: id=12 Removed NainActivit (6/8)
,08-04 11:58:13.779   267  1709 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,08-04 11:58:13.869   765  1066 W PackageSettings: Skipping PackageSetting{5920143 com.example.hello/10078} due to missing metadata
,08-04 11:58:13.869   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,08-04 11:58:13.889   765  3091 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:13.899   765  3091 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:13.909   765  1066 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=0: pkg removed
,08-04 11:58:13.939   765  1060 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,08-04 11:58:13.939  3673  3673 I art     : Explicit concurrent mark sweep GC freed 6031(365KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 15MB/26MB, paused 380us total 20.230ms
,08-04 11:58:13.939  1750  1750 E SamsungIME: mOCRHelper is null
,08-04 11:58:13.939   765  1123 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-04 11:58:13.949  1864  2296 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-04 11:58:13.949  1419  1419 D RegisteredServicesCache: empty dynamic service
,08-04 11:58:13.949  1439  1439 D ResourcesManager: creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
,08-04 11:58:13.949  1439  1439 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-04 11:58:13.949  1439  1439 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-04 11:58:13.959  1439  1439 D ResourcesManager: creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
,08-04 11:58:13.959  1439  1439 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 11:58:13.959  1439  1439 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-04 11:58:13.959  4014  4014 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-04 11:58:13.959  1439  1439 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-04 11:58:13.969  1439  1439 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,08-04 11:58:13.969  1439  1439 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-04 11:58:13.969  1439  1439 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-04 11:58:13.979  1498  1498 I art     : Explicit concurrent mark sweep GC freed 1210(59KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 20MB/33MB, paused 921us total 38.526ms
,08-04 11:58:13.999   765  3375 E libprocessgroup: failed to kill 1 processes for processgroup 7235
,08-04 11:58:13.999  4014  4014 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1470304694005
,08-04 11:58:13.999  4014  4014 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
,08-04 11:58:14.009  4014  4014 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,08-04 11:58:14.009   765  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,08-04 11:58:14.009   765  1476 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-04 11:58:14.009   765  1476 D SecContentProvider2: mCursor = null
,08-04 11:58:14.009   765  1146 V NetworkStats: removeUidsLocked() for UIDs [10079]
,08-04 11:58:14.009   765  1146 V NetworkStats: performPollLocked(flags=0x3)
08-04 11:58:14.009   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 11:58:14.009   765  1146 D NetworkStatsFactory: UpdateStatsForKnox
08-04 11:58:14.019   765  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:14.019   765  1146 V NetworkStats: performPollLocked() took 4ms
,08-04 11:58:14.019   765  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 11:58:14.049  5416  5416 I art     : Explicit concurrent mark sweep GC freed 725(41KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 291us total 132.311ms
,08-04 11:58:14.059   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 11:58:14.059   765  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 11:58:14.069  6901  6901 I art     : Explicit concurrent mark sweep GC freed 7126(460KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 16MB/21MB, paused 331us total 143.016ms
,08-04 11:58:14.079   765   765 I art     : Explicit concurrent mark sweep GC freed 77836(5MB) AllocSpace objects, 15(240KB) LOS objects, 29% free, 37MB/53MB, paused 2.357ms total 154.699ms
,08-04 11:58:14.079   765  1066 I art     : WaitForGcToComplete blocked for 67.536ms for cause Explicit
,08-04 11:58:14.079   765   765 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,08-04 11:58:14.089  2540  2540 I art     : Explicit concurrent mark sweep GC freed 9579(528KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 24MB/32MB, paused 574us total 169.286ms
,08-04 11:58:14.089  7722  7722 I PCWCLIENTTRACE_SYSTEMReceiver: mConnectivityHandler : connected
,08-04 11:58:14.099   765  1444 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 11:58:14.099   765   765 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,08-04 11:58:14.099   765  1003 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,08-04 11:58:14.099  7722  8547 W PCWCLIENTTRACE_AccountUtil: [hasSamungAccount] - No Samsung Account
,08-04 11:58:14.109   765   765 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,08-04 11:58:14.119   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,08-04 11:58:14.119   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,08-04 11:58:14.129   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,08-04 11:58:14.129   765  1003 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
,08-04 11:58:14.139  4014  4014 I KLMS-2.4.511: : MainReciver(): Notification App List is Null. Remove Notification.
,08-04 11:58:14.139   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,08-04 11:58:14.139  7722  8547 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-S]
,08-04 11:58:14.139  7722  8547 E art     : No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
08-04 11:58:14.139   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
08-04 11:58:14.139  7722  8547 W PCWCLIENTTRACE_SecurePreferencesJNI: GetString : secure API is not supported!! No implementation found for java.lang.String com.sec.pcw.device.util.SecurePreferencesJNI.getString() (tried Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString and Java_com_sec_pcw_device_util_SecurePreferencesJNI_getString__)
,08-04 11:58:14.139  7722  8547 I PCWCLIENTTRACE_SecurePreferencesJNI: [GetString-E]
08-04 11:58:14.139  7722  8547 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-04 11:58:14.139  7722  8547 I PCWCLIENTTRACE_PushUtil: sales region : global
08-04 11:58:14.139  7722  8547 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-04 11:58:14.139  7722  8547 E PCWCLIENTTRACE_PCWHandler: [ensureRegistration] - No Samsung account
,08-04 11:58:14.149  4014  4014 I KLMS-2.4.511: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-04 11:58:14.149   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,08-04 11:58:14.149  7419  7419 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-04 11:58:14.149   765  1449 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
08-04 11:58:14.149   765  1449 D ActivityManager: caller:android.app.ApplicationThreadProxy@1293a40c, r.packageName :com.sec.esdk.elm
,08-04 11:58:14.149  7419  7419 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-04 11:58:14.149  3716  3716 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,08-04 11:58:14.159   765   765 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,08-04 11:58:14.159   765  1003 D EnterpriseDeviceManagerService: Package has changed for user 0
08-04 11:58:14.159   765  1003 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-04 11:58:14.159  3716  3716 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-04 11:58:14.159  3716  3716 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
08-04 11:58:14.159  3716  3716 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
08-04 11:58:14.159  3716  3716 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
08-04 11:58:14.159  3716  3716 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
08-04 11:58:14.159  3716  3716 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
08-04 11:58:14.159  3716  3716 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:58:14.159  3716  3716 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-04 11:58:14.159  3716  3716 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 11:58:14.159  3716  3716 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:58:14.159  3716  3716 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:58:14.159  3716  3716 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 11:58:14.159  3716  3716 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,08-04 11:58:14.159  7419  7419 D elm:14491: ElmAgentService : onCreate()
,08-04 11:58:14.159  7419  8548 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
08-04 11:58:14.159  7419  8548 D elm:14491: MainReceiver.listeningToPackageRemoved()
08-04 11:58:14.159  7419  8548 D elm:14491: MDMBridge.getInstance()
08-04 11:58:14.159  7419  8548 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,08-04 11:58:14.159   765   765 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,08-04 11:58:14.159   765  1573 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.service.health, hostingType: broadcast
,08-04 11:58:14.159   765  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:58:14.159   765  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:58:14.159   765  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:58:14.159   765  1573 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:58:14.169   765   765 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,08-04 11:58:14.169  7419  8548 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,08-04 11:58:14.179   765  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,08-04 11:58:14.189   765   765 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,08-04 11:58:14.189   765   765 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,08-04 11:58:14.189   765   765 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,08-04 11:58:14.199   765   765 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,08-04 11:58:14.199   765  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-04 11:58:14.199   765  1003 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
,08-04 11:58:14.199   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
,08-04 11:58:14.209  8549  8549 E Zygote  : MountEmulatedStorage()
08-04 11:58:14.209  8549  8549 E Zygote  : v2
08-04 11:58:14.209  8549  8549 I libpersona: KNOX_SDCARD checking this for 10021
08-04 11:58:14.209  8549  8549 I libpersona: KNOX_SDCARD not a persona
,08-04 11:58:14.209   765  1003 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,08-04 11:58:14.209   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,08-04 11:58:14.219   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,08-04 11:58:14.219   765  1573 I ActivityManager: Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8549 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,08-04 11:58:14.229  8549  8549 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:58:14.229  7419  7419 D elm:14491: ElmAgentService : onDestroy().
08-04 11:58:14.229  8549  8549 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 11:58:14.229  8549  8549 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 11:58:14.229   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,08-04 11:58:14.239   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,08-04 11:58:14.239   765  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-04 11:58:14.239   765  1003 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,08-04 11:58:14.239   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,08-04 11:58:14.239   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,08-04 11:58:14.249   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,08-04 11:58:14.259  8549  8549 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:58:14.259  8549  8549 D ActivityThread: Added TimaKeyStore provider
,08-04 11:58:14.269   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,08-04 11:58:14.269   765   765 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
,08-04 11:58:14.269   765  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 11:58:14.269   765  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,08-04 11:58:14.289   765  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 11:58:14.289   765  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,08-04 11:58:14.289  8549  8549 D ResourcesManager: creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,08-04 11:58:14.289  1439  1439 D SurfaceWidgetView: destroyHardwareResources():242199373
,08-04 11:58:14.289   765  1493 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-04 11:58:14.289   765  1493 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
08-04 11:58:14.289   765  1493 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
,08-04 11:58:14.289   765  1493 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-04 11:58:14.289   765  1493 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,08-04 11:58:14.299   765   765 D RCPManagerService: PackageReceiver onReceive()
,08-04 11:58:14.299   765   765 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-04 11:58:14.299  1439  1439 D Launcher: onRestart, Launcher: 497738907
,08-04 11:58:14.299  1439  1439 D Launcher: onStart, Launcher: 497738907
08-04 11:58:14.299  1439  1439 D Launcher.HomeView: onStart
,08-04 11:58:14.299   765   765 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
08-04 11:58:14.299  1439  1439 V ActivityThread: updateVisibility : ActivityRecord{3da5a5ff token=android.os.BinderProxy@15cbd742 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-04 11:58:14.299  1782  1803 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
08-04 11:58:14.299  1782  2092 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
08-04 11:58:14.299  1782  2092 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,08-04 11:58:14.299   765   765 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-04 11:58:14.299   765   765 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-04 11:58:14.299   765   765 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-04 11:58:14.299   765   765 V EnterpriseBillingPolicy: uID is 10079
08-04 11:58:14.299   765   765 V EnterpriseBillingPolicy: Removed Packageuid is0
08-04 11:58:14.299   765   765 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-04 11:58:14.299   765   765 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
,08-04 11:58:14.299   765   765 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-04 11:58:14.299   765   765 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-04 11:58:14.299   765   765 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-04 11:58:14.309   765   765 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-04 11:58:14.309   765  1178 D TaskPersister: removeObsoleteFile: deleting file=99_task.xml
,08-04 11:58:14.309   765  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 11:58:14.319   765  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-04 11:58:14.319   267   267 I SurfaceFlinger: id=14 createSurf (1080x1920),1 flag=4, Mauncher
,08-04 11:58:14.319   765   765 V AlarmManagerEXT: com.test.thalitest(10079) is removed.
,08-04 11:58:14.319   765  1058 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-04 11:58:14.319   765  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 11:58:14.319   765  1058 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-04 11:58:14.319   765  1060 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-04 11:58:14.319   765  1060 D PointerIcon: setMouseCustomIcon IconType is same.101
08-04 11:58:14.319   765  1060 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-04 11:58:14.319   765  1060 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-04 11:58:14.319   765  1003 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,08-04 11:58:14.329   765  3205 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-04 11:58:14.339   765  8566 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-04 11:58:14.339   765  3205 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 7235 uid 10079
,08-04 11:58:14.339   765  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 11:58:14.339   765  1003 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,08-04 11:58:14.339   765  1003 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,08-04 11:58:14.339  8549  8549 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
,08-04 11:58:14.339  8549  8549 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
08-04 11:58:14.339  8549  8549 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
,08-04 11:58:14.339   765  1352 D ActivityManager: startProcessLocked calleePkgName: sstream.app, hostingType: broadcast
,08-04 11:58:14.349   765  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:58:14.349   765  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:58:14.349   765  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:58:14.349   765  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:58:14.349   765  1003 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,08-04 11:58:14.349   765  1066 I art     : Explicit concurrent mark sweep GC freed 20658(1241KB) AllocSpace objects, 2(32KB) LOS objects, 29% free, 37MB/53MB, paused 3.986ms total 271.094ms
,08-04 11:58:14.359   765  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 11:58:14.369   765  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 11:58:14.379   765  1003 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,08-04 11:58:14.389   765  3091 I SQLiteConnectionPool: exportDB...
,08-04 11:58:14.389  8568  8568 E Zygote  : MountEmulatedStorage()
08-04 11:58:14.389  8568  8568 E Zygote  : v2
08-04 11:58:14.389  8568  8568 I libpersona: KNOX_SDCARD checking this for 10025
08-04 11:58:14.389  8568  8568 I libpersona: KNOX_SDCARD not a persona
,08-04 11:58:14.399   765  1003 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-04 11:58:14.399   765  1003 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 11:58:14.399   765  1003 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-04 11:58:14.399   765  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 11:58:14.399   765  1003 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,08-04 11:58:14.399   765  1003 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,08-04 11:58:14.409   765  1003 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,08-04 11:58:14.409   765  1352 I ActivityManager: Start proc sstream.app for broadcast sstream.app/.receiver.ApplicationCompatibleReceiver: pid=8568 uid=10025 gids={50025, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-04 11:58:14.409   765  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,08-04 11:58:14.419   765  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,08-04 11:58:14.419   765  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 11:58:14.419   765  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,08-04 11:58:14.419   765  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 11:58:14.419   765  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,08-04 11:58:14.419   765  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 11:58:14.419   765  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-04 11:58:14.419   765  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,08-04 11:58:14.429  8568  8568 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:58:14.429  8568  8568 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 11:58:14.429  8568  8568 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 11:58:14.429   765  1060 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3ae436ec u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t97} time:227084
,08-04 11:58:14.429   765  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 11:58:14.429   765  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,08-04 11:58:14.429   765  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 11:58:14.429   765  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-04 11:58:14.429   765  1003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,08-04 11:58:14.439   765  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-04 11:58:14.439   765  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-04 11:58:14.439   765  1003 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,08-04 11:58:14.439   765  1003 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 11:58:14.439   765  1003 D UsbSettingsManager: clearDefaults: com.test.thalitest
08-04 11:58:14.439   765  1003 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-04 11:58:14.449   765  1066 D PackageManager: delete codoeFile: 
,08-04 11:58:14.449  8568  8568 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:58:14.459  8568  8568 D ActivityThread: Added TimaKeyStore provider
,08-04 11:58:14.459   765  1066 D AASAuninstall: userId = 0, info.removedAppID = 10079, info.uid = 10079, packageName = com.test.thalitest
,08-04 11:58:14.459   765  1066 I AASA_removePackage: UID=10079 Target=com.test.thalitest
,08-04 11:58:14.459   765  1066 D PackageManager: result of delete: 1{799945390}
,08-04 11:58:14.469  8530  8530 D AndroidRuntime: Shutting down VM
,08-04 11:58:14.469  8568  8568 D ResourcesManager: creating new AssetManager and set to /system/priv-app/MagazineHome/MagazineHome.apk
,08-04 11:58:14.469   765  1066 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-04 11:58:14.469   765  1066 D PackageManager: userId{-1}
08-04 11:58:14.469   765  1066 D PackageManager: andCode{true}
,08-04 11:58:14.469   765  1066 D ActivityManager: caller:null, r.packageName :com.android.defcontainer
,08-04 11:58:14.469  8568  8568 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-04 11:58:14.469   765  1066 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:58:14.469   765  1066 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:58:14.469   765  1066 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:58:14.469   765  1066 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:58:14.489  8568  8568 W linker  : libdmcAlwaysFD.so has text relocations. This is wasting memory and prevents security hardening. Please fix.
,08-04 11:58:14.489  8568  8568 D MVFD_interface: <<<  caMVFace_FaceInit
,08-04 11:58:14.499   765  3091 I SQLiteConnectionPool: ...exportDB
,08-04 11:58:14.509   765  3091 D SSRM:aY : MSG_TYPE_APP_REMOVED::
,08-04 11:58:14.519  8584  8584 E Zygote  : MountEmulatedStorage()
08-04 11:58:14.519  8584  8584 E Zygote  : v2
08-04 11:58:14.519  8584  8584 I libpersona: KNOX_SDCARD checking this for 10007
08-04 11:58:14.519  8584  8584 I libpersona: KNOX_SDCARD not a persona
,08-04 11:58:14.529  8584  8584 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:58:14.529  8584  8584 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 11:58:14.529  8584  8584 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 11:58:14.529   765  1066 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8584 uid=10007 gids={50007, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-04 11:58:14.539   344   344 I art     : Explicit concurrent mark sweep GC freed 8716(370KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 316us total 13.384ms
,08-04 11:58:14.549  8584  8584 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:58:14.549  8584  8584 D ActivityThread: Added TimaKeyStore provider
,08-04 11:58:14.549   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 279us total 9.633ms
,08-04 11:58:14.559   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 275us total 9.781ms
,08-04 11:58:14.559  8584  8584 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DefaultContainerService/DefaultContainerService.apk
,08-04 11:58:14.569   266   547 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
08-04 11:58:14.569   266   547 W Vold    : Returning OperationFailed - no handler for errno 0
,08-04 11:58:14.569  8568  8568 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
,08-04 11:58:14.569   266   547 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/sstream.app/cache/
08-04 11:58:14.569   266   547 W Vold    : Returning OperationFailed - no handler for errno 0
,08-04 11:58:14.569  8568  8568 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/sstream.app/cache
,08-04 11:58:14.579   765  1703 I ActivityManager: Killing 6718:com.android.mms/u0a55 (adj 15): emptyCount ##41
,08-04 11:58:14.629   765   784 D CountryDetector: No listener is left
,08-04 11:58:14.649  8568  8568 D HockeyApp: Current handler class = sstream.app.util.Log$1
,08-04 11:58:14.739  8568  8613 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,08-04 11:58:14.749  8568  8613 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-04 11:58:14.749  8568  8568 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-04 11:58:14.749  8568  8568 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM config WHERE config_id=?] disk I/O error
,08-04 11:58:14.759  8568  8568 D AndroidRuntime: Shutting down VM
,08-04 11:58:14.759  7722  7722 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-04 11:58:14.759  7722  7722 I PCWCLIENTTRACE_PushUtil: sales region : global
08-04 11:58:14.759  7722  7722 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-04 11:58:14.759  7722  7722 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-04 11:58:14.759   765  1352 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
,08-04 11:58:14.759   765  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:58:14.759   765  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:58:14.759   765  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:58:14.759   765  1352 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:58:14.759  8568  8613 D ApplicationCompatibleReceiver: com.sec.chaton Already existed in setting table , SKIP!!!
,08-04 11:58:14.759  8568  8613 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
08-04 11:58:14.769  8568  8568 D HockeyApp: Writing unhandled exception to: /data/data/sstream.app/files/62bd6e95-f346-4f58-a0c3-f5f5f61ffdb6.stacktrace
08-04 11:58:14.769  8568  8613 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-04 11:58:14.769  8568  8613 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-04 11:58:14.769  8568  8613 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-04 11:58:14.769  8568  8613 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-04 11:58:14.769  8568  8613 W ResourcesManager: Asset path '/system/framework/videowall.jar' does not exist or contains no resources.
08-04 11:58:14.769  8568  8613 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-04 11:58:14.769  8568  8568 E HockeyApp: Error saving exception stacktrace!
08-04 11:58:14.769  8568  8568 E HockeyApp: 
08-04 11:58:14.769  8568  8568 E HockeyApp: java.io.FileNotFoundException: /data/data/sstream.app/files/62bd6e95-f346-4f58-a0c3-f5f5f61ffdb6.stacktrace: open failed: EROFS (Read-only file system)
08-04 11:58:14.769  8568  8568 E HockeyApp: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-04 11:58:14.769  8568  8568 E HockeyApp: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 11:58:14.769  8568  8568 E HockeyApp: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 11:58:14.769  8568  8568 E HockeyApp: 	at java.io.FileWriter.<init>(FileWriter.java:80)
08-04 11:58:14.769  8568  8568 E HockeyApp: 	at net.hockeyapp.android.internal.ExceptionHandler.saveException(ExceptionHandler.java:83)
08-04 11:58:14.769  8568  8568 E HockeyApp: 	at net.hockeyapp.android.internal.ExceptionHandler.uncaughtException(ExceptionHandler.java:108)
08-04 11:58:14.769  8568  8568 E HockeyApp: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
08-04 11:58:14.769  8568  8568 E HockeyApp: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
08-04 11:58:14.769  8568  8568 E HockeyApp: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 11:58:14.769  8568  8568 E HockeyApp: 	at libcore.io.Posix.open(Native Method)
08-04 11:58:14.769  8568  8568 E HockeyApp: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 11:58:14.769  8568  8568 E HockeyApp: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-04 11:58:14.769  8568  8568 E HockeyApp: 	... 7 more
,08-04 11:58:14.779  8568  8613 D ApplicationCompatibleReceiver: com.sec.android.app.videoplayer Already existed in setting table , SKIP!!!
08-04 11:58:14.779  8568  8613 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
08-04 11:58:14.779  8568  8613 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-04 11:58:14.779  8568  8613 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-04 11:58:14.779  8568  8613 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-04 11:58:14.779  8568  8613 D ApplicationCompatibleReceiver: com.sec.pcw Already existed in setting table , SKIP!!!
08-04 11:58:14.779  8568  8613 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
08-04 11:58:14.789  8568  8613 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-04 11:58:14.789  8568  8613 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-04 11:58:14.789  8568  8613 D ApplicationCompatibleReceiver: com.samsung.android.app.pinboard Already existed in setting table , SKIP!!!
08-04 11:58:14.789  8568  8613 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
08-04 11:58:14.789  8568  8613 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-04 11:58:14.789  8568  8613 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 11:58:14.789  8568  8613 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-04 11:58:14.789  8568  8613 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-04 11:58:14.789  8568  8613 E SQLiteLog: (3850) statement aborts at 30: [INSERT INTO config(selected,category,native_package_names,image_unselected,image_selected,login,application_name,visible,native_app_required,config_id,stream_id,source_icon) VALUES (?,
08-04 11:58:14.789  8568  8613 E SQLiteDatabase: Error inserting selected=1 category=com.android.calendar native_package_names=null image_unselected=2130903040 image_selected=2130903040 login=0 application_name=2131625003 visible=1 native_app_required=0 config_id=com.android.calendar stream_id=null source_icon=0
08-04 11:58:14.789  8568  8613 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 11:58:14.789  8568  8613 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-04 11:58:14.789  8568  8613 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:952)
08-04 11:58:14.789  8568  8613 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:788)
08-04 11:58:14.789  8568  8613 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-04 11:58:14.789  8568  8613 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1595)
08-04 11:58:14.789  8568  8613 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1465)
08-04 11:58:14.789  8568  8613 E SQLiteDatabase: 	at sstream.app.provider.StoryProvider.insertOne(StoryProvider.java:352)
08-04 11:58:14.789  8568  8613 E SQLiteDatabase: 	at sstream.app.provider.StoryProvider.insert(StoryProvider.java:263)
08-04 11:58:14.789  8568  8613 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-04 11:58:14.789  8568  8613 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1217)
08-04 11:58:14.789  8568  8613 E SQLiteDatabase: 	at sstream.app.provider.DatabaseUtil.storeConfigSetting(DatabaseUtil.java:784)
08-04 11:58:14.789  8568  8613 E SQLiteDatabase: 	at sstream.app.receiver.ApplicationCompatibleReceiver.addCompatibleAppsToDB(ApplicationCompatibleReceiver.java:420)
08-04 11:58:14.789  8568  8613 E SQLiteDatabase: 	at sstream.app.receiver.ApplicationCompatibleReceiver.getCompatibleApps(ApplicationCompatibleReceiver.java:155)
08-04 11:58:14.789  8568  8613 E SQLiteDatabase: 	at sstream.app.StreamManager$1.run(StreamManager.java:177)
08-04 11:58:14.799  8568  8613 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
08-04 11:58:14.799  8568  8613 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-04 11:58:14.799  8568  8613 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 11:58:14.799  8568  8613 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-04 11:58:14.799  8568  8613 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-04 11:58:14.799  8568  8613 W ResourcesManager: Asset path '/system/framework/svi.jar' does not exist or contains no resources.
08-04 11:58:14.799  8568  8613 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-04 11:58:14.799  8568  8613 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-04 11:58:14.799  8618  8618 E Zygote  : MountEmulatedStorage()
08-04 11:58:14.799  8618  8618 E Zygote  : v2
08-04 11:58:14.799  8618  8618 I libpersona: KNOX_SDCARD checking this for 10039
08-04 11:58:14.799  8618  8618 I libpersona: KNOX_SDCARD not a persona
08-04 11:58:14.799  8568  8613 D ApplicationCompatibleReceiver: com.sec.android.gallery3d Already existed in setting table , SKIP!!!
08-04 11:58:14.809   765  1352 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8618 uid=10039 gids={50039, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
08-04 11:58:14.809   765  1352 I ActivityManager: Killing 7386:com.samsung.android.scloud.sync/u0a76 (adj 15): emptyCount ##41
,08-04 11:58:14.839  8568  8613 D ResourcesManager: creating new AssetManager and set to /data/app/com.sec.android.app.samsungapps-2/base.apk
08-04 11:58:14.839  8618  8618 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:58:14.839  8618  8618 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 11:58:14.839  8618  8618 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-04 11:58:14.839  8568  8613 D ApplicationCompatibleReceiver: com.sec.android.app.samsungapps Already existed in setting table , SKIP!!!
08-04 11:58:14.849  8568  8613 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
08-04 11:58:14.849   765  1123 I EventHub: Removing device '/dev/input/event6' due to inotify event
,08-04 11:58:14.859  8568  8613 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,08-04 11:58:14.859  8568  8613 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,08-04 11:58:14.859  8568  8613 D ApplicationCompatibleReceiver: com.samsung.android.snote Already existed in setting table , SKIP!!!
,08-04 11:58:14.859  8618  8618 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:58:14.859  8618  8618 D ActivityThread: Added TimaKeyStore provider
,08-04 11:58:14.869  8618  8618 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,08-04 11:58:14.869   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,08-04 11:58:14.879  8618  8618 W ContextImpl: Unable to create files subdir /data/data/com.samsung.android.app.galaxyfinder/cache
08-04 11:58:14.879  8618  8618 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,08-04 11:58:14.889  8618  8618 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,08-04 11:58:14.899   765  1123 I EventHub: Removing device '/dev/input/event7' due to inotify event
,08-04 11:58:14.919  8618  8618 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,08-04 11:58:14.919  8568  8604 D Volley  : [1326] DiskBasedCache.get: /data/data/sstream.app/cache/volley/852217856-371018006: java.io.FileNotFoundException: /data/data/sstream.app/cache/volley/852217856-371018006: open failed: ENOENT (No such file or directory)
08-04 11:58:14.919  8568  8604 D Volley  : [1326] DiskBasedCache.remove: Could not delete cache entry for key=https://sstream.flipboard.com/v1/static/sstreamConfig.json?userid=0&udid=41c5433a3107c9acc8fa3a75862cd57fff02f588&tuuid=187d8917-cf9e-4bfa-a94b-f73be745548b&ver=2.0.5_s3.0.0.71d&device=aphone-samsung-SM-N9005-21&lang=en&locale=en_US&screensize=5.6&variant=sstream, filename=852217856-371018006
,08-04 11:58:14.919  8568  8604 D Volley  : [1326] DiskBasedCache.get: /data/data/sstream.app/cache/volley/-2107138505379496909: java.io.FileNotFoundException: /data/data/sstream.app/cache/volley/-2107138505379496909: open failed: ENOENT (No such file or directory)
,08-04 11:58:14.919  8618  8618 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-04 11:58:14.919  8618  8618 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-04 11:58:14.919  8618  8618 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
08-04 11:58:14.919  8568  8604 D Volley  : [1326] DiskBasedCache.remove: Could not delete cache entry for key=https://sstream.flipboard.com/v1/static/sstreamCategories.json?userid=0&udid=41c5433a3107c9acc8fa3a75862cd57fff02f588&tuuid=187d8917-cf9e-4bfa-a94b-f73be745548b&ver=2.0.5_s3.0.0.71d&device=aphone-samsung-SM-N9005-21&lang=en&locale=en_US&screensize=5.6&variant=sstream, filename=-2107138505379496909
,08-04 11:58:14.919  8618  8618 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,08-04 11:58:14.919  8618  8618 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 11:58:14.919  8618  8618 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-04 11:58:14.919  8618  8618 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-04 11:58:14.919  8618  8618 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
08-04 11:58:14.919  8618  8618 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-04 11:58:14.919  8568  8604 D Volley  : [1326] DiskBasedCache.get: /data/data/sstream.app/cache/volley/769804234985904208: java.io.FileNotFoundException: /data/data/sstream.app/cache/volley/769804234985904208: open failed: ENOENT (No such file or directory)
,08-04 11:58:14.919  8568  8604 D Volley  : [1326] DiskBasedCache.remove: Could not delete cache entry for key=https://sstream.flipboard.com/v1/static/sstreamServices.json?userid=0&udid=41c5433a3107c9acc8fa3a75862cd57fff02f588&tuuid=187d8917-cf9e-4bfa-a94b-f73be745548b&ver=2.0.5_s3.0.0.71d&device=aphone-samsung-SM-N9005-21&lang=en&locale=en_US&screensize=5.6&variant=sstream, filename=769804234985904208
,08-04 11:58:14.929  8618  8618 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,08-04 11:58:14.929  8618  8618 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,08-04 11:58:14.929  8618  8618 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-04 11:58:14.929  8618  8618 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-04 11:58:14.929  8618  8618 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 11:58:14.929  8618  8618 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-04 11:58:14.929  8618  8618 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-04 11:58:14.929  8618  8618 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,08-04 11:58:14.929  8568  8605 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-04 11:58:14.929  8568  8605 I System.out: (HTTPLog)-Static: isShipBuild true
,08-04 11:58:14.929  8568  8605 I System.out: (HTTPLog)-Thread-1327-674831106: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-04 11:58:14.929  8568  8605 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-04 11:58:14.929  8618  8618 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 11:58:14.929  8568  8606 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-04 11:58:14.929  8568  8606 I System.out: (HTTPLog)-Static: isShipBuild true
,08-04 11:58:14.929  8568  8606 I System.out: (HTTPLog)-Thread-1328-739724307: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
,08-04 11:58:14.939  8568  8606 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-04 11:58:14.939  8568  8607 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-04 11:58:14.939  8618  8618 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
08-04 11:58:14.939  8568  8607 I System.out: (HTTPLog)-Static: isShipBuild true
08-04 11:58:14.939  8568  8607 I System.out: (HTTPLog)-Thread-1329-147545680: SmartBonding Enabling is false, SHIP_BUILD is true, log to file is false, DBG is false
08-04 11:58:14.939  8568  8607 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,08-04 11:58:14.939  8618  8618 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,08-04 11:58:14.949  8618  8618 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-04 11:58:14.949  8618  8618 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 11:58:14.949  8618  8618 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-04 11:58:14.949  8618  8618 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,08-04 11:58:14.949  8618  8618 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
08-04 11:58:14.949  8618  8618 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-04 11:58:14.949  8618  8618 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,08-04 11:58:14.949  8618  8618 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,08-04 11:58:14.959  8618  8618 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-04 11:58:14.959  8618  8618 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 11:58:14.959   765  1123 I EventHub: Removing device '/dev/input/event8' due to inotify event
08-04 11:58:14.959  8618  8618 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-04 11:58:14.959  8618  8618 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-04 11:58:14.959  8618  8618 W ResourcesManager: Asset path '/system/framework/svi.jar' does not exist or contains no resources.
08-04 11:58:14.959  8618  8618 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-04 11:58:14.959  8618  8618 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-04 11:58:14.959  8618  8618 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,08-04 11:58:14.959  8618  8618 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-04 11:58:14.959  8618  8618 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
08-04 11:58:14.959  8618  8618 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-04 11:58:14.959  8618  8618 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-04 11:58:14.969  8618  8618 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,08-04 11:58:14.969  8618  8618 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,08-04 11:58:14.969  8618  8618 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-04 11:58:14.969  8618  8618 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-04 11:58:14.969  8618  8618 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-04 11:58:14.969  8618  8618 W ResourcesManager: Asset path '/system/framework/videowall.jar' does not exist or contains no resources.
08-04 11:58:14.969  8618  8618 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-04 11:58:14.969  8618  8618 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,08-04 11:58:14.969  8618  8618 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-04 11:58:14.969  8618  8618 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-04 11:58:14.969  8618  8618 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-04 11:58:14.979  8618  8618 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,08-04 11:58:14.979  8618  8618 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-04 11:58:14.979  8568  8605 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-04 11:58:14.989  8568  8606 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-04 11:58:14.989  8568  8607 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-04 11:58:14.989  8568  8606 I qtaguid : Tagging socket 50 with tag 6d6b53b100000000{1835750321,0} uid -1, pid: 8568, getuid(): 10025
08-04 11:58:14.989  8568  8607 I qtaguid : Tagging socket 52 with tag 6d6b53b100000000{1835750321,0} uid -1, pid: 8568, getuid(): 10025
,08-04 11:58:14.989  8568  8605 I qtaguid : Tagging socket 54 with tag 6d6b53b100000000{1835750321,0} uid -1, pid: 8568, getuid(): 10025
,08-04 11:58:14.989  8618  8618 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,08-04 11:58:14.989  8618  8618 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-04 11:58:14.989  8618  8618 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 11:58:14.989  8618  8618 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-04 11:58:14.989  8618  8618 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-04 11:58:14.989  8618  8618 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-04 11:58:14.999  8618  8618 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,08-04 11:58:14.999  8618  8618 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,08-04 11:58:14.999  8618  8618 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-04 11:58:14.999  8618  8618 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,08-04 11:58:14.999  8618  8618 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
08-04 11:58:15.009  8618  8618 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
08-04 11:58:15.009  8618  8618 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
08-04 11:58:15.009  8618  8618 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
08-04 11:58:15.019  8618  8618 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
08-04 11:58:15.019  8618  8618 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,08-04 11:58:15.019  8618  8618 W ResourcesManager: Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
08-04 11:58:15.019  8618  8618 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-04 11:58:15.019  8618  8618 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-04 11:58:15.019  8618  8618 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-04 11:58:15.019  8618  8618 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-04 11:58:15.019  8618  8618 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,08-04 11:58:15.019  8618  8618 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,08-04 11:58:15.019  8618  8618 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-04 11:58:15.029  8618  8618 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/pref_package.xml
,08-04 11:58:15.039   765  1123 I EventHub: Removing device '/dev/input/event9' due to inotify event
,08-04 11:58:15.039  8618  8618 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/pref_package.xml
,08-04 11:58:15.049  8618  8618 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/com.samsung.android.app.galaxyfinder_preferences.xml
,08-04 11:58:15.079   765  1330 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.shealth, hostingType: broadcast
,08-04 11:58:15.089   765  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:58:15.089   765  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:58:15.089   765  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 11:58:15.089   765  1330 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 11:58:15.099   765  1123 I EventHub: Removing device '/dev/input/event10' due to inotify event
,08-04 11:58:15.119  8639  8639 E Zygote  : MountEmulatedStorage()
08-04 11:58:15.119  8639  8639 E Zygote  : v2
08-04 11:58:15.119  8639  8639 I libpersona: KNOX_SDCARD checking this for 10040
08-04 11:58:15.119  8639  8639 I libpersona: KNOX_SDCARD not a persona
,08-04 11:58:15.129   765  1330 I ActivityManager: Start proc com.sec.android.app.shealth for broadcast com.sec.android.app.shealth/.receiver.InstalledReceiver: pid=8639 uid=10040 gids={50040, 9997, 3003, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-04 11:58:15.129   765  1330 I ActivityManager: Killing 5416:com.samsung.android.sm/1000 (adj 15): emptyCount ##41
,08-04 11:58:15.139   765  1123 I EventHub: Removing device '/dev/input/event11' due to inotify event
,08-04 11:58:15.199  8639  8639 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 11:58:15.199  8639  8639 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 11:58:15.199  8639  8639 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-04 11:58:15.209   765  1123 I EventHub: Removing device '/dev/input/event12' due to inotify event
,08-04 11:58:15.219  8639  8639 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 11:58:15.219  8639  8639 D ActivityThread: Added TimaKeyStore provider
,08-04 11:58:15.239  8639  8639 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,08-04 11:58:15.249  8639  8639 W ContextImpl: Unable to create files subdir /data/data/com.sec.android.app.shealth/cache
08-04 11:58:15.249  8639  8639 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,08-04 11:58:15.269  8639  8639 W         : Zip: inflate read failed (15885 vs 32768)
,08-04 11:58:15.279  8639  8639 D AndroidRuntime: Shutting down VM
,08-04 11:58:15.279  8639  8639 E AndroidRuntime: FATAL EXCEPTION: main
08-04 11:58:15.279  8639  8639 E AndroidRuntime: Process: com.sec.android.app.shealth, PID: 8639
08-04 11:58:15.279  8639  8639 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate application com.sec.android.app.shealth.SHealthApplication: java.lang.ClassNotFoundException: Didn't find class "com.sec.android.app.shealth.SHealthApplication" on path: DexPathList[[zip file "/system/priv-app/SHealth3_5/SHealth3_5.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:625)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5082)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: Caused by: java.lang.ClassNotFoundException: Didn't find class "com.sec.android.app.shealth.SHealthApplication" on path: DexPathList[[zip file "/system/priv-app/SHealth3_5/SHealth3_5.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	at android.app.Instrumentation.newApplication(Instrumentation.java:988)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	at android.app.LoadedApk.makeApplication(LoadedApk.java:620)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	... 10 more
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	Suppressed: java.io.IOException: Failed to extract 'classes.dex' from '/system/priv-app/SHealth3_5/SHealth3_5.apk': I/O Error
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFileNative(Native Method)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:80)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:59)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		a,t java.lang.reflect.Method.invoke(Native Method)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		... 10 more
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open file '/data/dalvik-cache/arm/system@priv-app@SHealth3_5@SHealth3_5.apk@classes.dex': Read-only file system
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		... 27 more
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/priv-app/SHealth3_5/SHealth3_5.apk'
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		... 27 more
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from /system/priv-app/SHealth3_5/arm/SHealth3_5.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		... 27 more
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	Caused by: java.io.IOException: 
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		... 27 more
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	Suppressed: java.lang.ClassNotFoundException: com.sec.android.app.shealth.SHealthApplication
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		at java.lang.Class.classForName(Native Method)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 		... 13 more
08-04 11:58:15.279  8639  8639 E AndroidRuntime: 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
,08-04 11:58:15.279   765  1232 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.app.shealth
,08-04 11:58:15.289   765  1123 I EventHub: Removing device '/dev/input/event13' due to inotify event
,08-04 11:58:15.289   765  8654 E AndroidRuntime: *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
08-04 11:58:15.289   765  8654 E AndroidRuntime: java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
08-04 11:58:15.289   765  8654 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:46)
08-04 11:58:15.289   765  8654 E AndroidRuntime: 	at android.os.StatFs.restat(StatFs.java:56)
08-04 11:58:15.289   765  8654 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
08-04 11:58:15.289   765  8654 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
08-04 11:58:15.289   765  8654 E AndroidRuntime: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-04 11:58:15.289   765  8654 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
08-04 11:58:15.289   765  8654 E AndroidRuntime: Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
08-04 11:58:15.289   765  8654 E AndroidRuntime: 	at libcore.io.Posix.statvfs(Native Method)
08-04 11:58:15.289   765  8654 E AndroidRuntime: 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
08-04 11:58:15.289   765  8654 E AndroidRuntime: 	at android.system.Os.statvfs(Os.java:473)
08-04 11:58:15.289   765  8654 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:44)
08-04 11:58:15.289   765  8654 E AndroidRuntime: 	... 5 more
,08-04 11:58:15.299  7844  7844 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/registration_db" with flag (131138) and mode_t (0) due to error (2)
08-04 11:58:15.299  7844  7844 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/registration_db" with flag (131072) and mode_t (0) due to error (2)
08-04 11:58:15.299  7844  7844 E SQLiteLog: (14) cannot open file at line 32509 of [b3bb660af9]
08-04 11:58:15.299  7844  7844 E SQLiteLog: (14) os_unix.c:32509: (2) open(/data/data/com.sec.spp.push/databases/registration_db) - 
,08-04 11:58:15.299  8639  8639 I Process : Sending signal. PID: 8639 SIG: 9
,08-04 11:58:15.299   765  8654 E android.os.Debug: ro.product_ship = true
08-04 11:58:15.299   765  8654 E android.os.Debug: ro.debug_level = 0x4f4c
,08-04 11:58:15.299  7844  7844 E SQLiteDatabase: Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at com.sec.spp.push.h.a.a(Unknown Source)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at com.sec.spp.push.h.c.d(Unknown Source)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.onReceive(Unknown Source)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 11:58:15.299  7844  7844 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,08-04 11:58:15.309   765  8654 E AndroidRuntime: Error reporting crash
08-04 11:58:15.309   765  8654 E AndroidRuntime: java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
08-04 11:58:15.309   765  8654 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:46)
08-04 11:58:15.309   765  8654 E AndroidRuntime: 	at android.os.StatFs.restat(StatFs.java:56)
08-04 11:58:15.309   765  8654 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
08-04 11:58:15.309   765  8654 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
08-04 11:58:15.309   765  8654 E AndroidRuntime: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-04 11:58:15.309   765  8654 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
08-04 11:58:15.309   765  8654 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:15161)
08-04 11:58:15.309   765  8654 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:14749)
08-04 11:58:15.309   765  8654 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:14733)
08-04 11:58:15.309   765  8654 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
08-04 11:58:15.309   765  8654 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
08-04 11:58:15.309   765  8654 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
08-04 11:58:15.309   765  8654 E AndroidRuntime: Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
08-04 11:58:15.309   765  8654 E AndroidRuntime: 	at libcore.io.Posix.statvfs(Native Method)
08-04 11:58:15.309   765  8654 E AndroidRuntime: 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
08-04 11:58:15.309   765  8654 E AndroidRuntime: 	at android.system.Os.statvfs(Os.java:473)
08-04 11:58:15.309   765  8654 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:44)
08-04 11:58:15.309   765  8654 E AndroidRuntime: 	... 11 more
08-04 11:58:15.309   765  8654 I Process : Sending signal. PID: 765 SIG: 9
,08-04 11:58:15.309  7844  7844 E SPPClientService: [c] [getAppId()] SQLiteException with message =unknown error (code 14): Could not open database
,08-04 11:58:15.439   265   265 I ServiceManager: service 'wifip2p' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'ABTPersistenceService' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'textservices' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'network_score' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'netstats' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'netpolicy' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'wifi' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'msapwifi' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'wifiscanner' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'rttmanager' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'mum_container_policy' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'enterprise_billing_policy' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'knox_timakeystore_policy' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'enterprise_policy' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'statusbar' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'clipboard' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'clipboardEx' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'network_management' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'audio' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'DockObserver' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'usb' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'serial' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'uimode' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'jobscheduler' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'sec_analytics' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'connectivity' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'sb_service' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'servicediscovery' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'updatelock' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'notification' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'devicestoragemonitor' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'location' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'country_detector' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'search' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'dropbox' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'wallpaper' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'backup' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'appwidget' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'voiceinteraction' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'SecExternalDisplayService' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'diskstats' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'mDNIe' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'spengestureservice' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'quickconnect' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'samplingprofiler' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'commontime_management' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'dreams' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'print' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'restrictions' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'media_session' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'media_router' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'trust' died
08-04 11:58:15.439   265   265 I ServiceManager: servic,e 'fingerprint' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'launcherapps' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'voip' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'edmnativehelper' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'input_method' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'accessibility' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'motion_recognition' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'media_projection' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'lpnet' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'imms' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'cover' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'mount' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'lock_settings' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'device_policy' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'harmony_eas_service' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'sdp' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'log_manager_service' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'permission' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'hardware' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'context_aware' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'scontext' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'barbeam' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'multiwindow_facade' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'window' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'input' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'tactileassist' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'bluetooth_manager' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'rcp' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'mdm.remotedesktop' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'sensorservice' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'power' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'display' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'persona_policy' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'CustomFrequencyManagerService' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'samsung.smartfaceservice' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'consumer_ir' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'enterprise_license_policy' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'application_policy' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'wifi_policy' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'phone_restriction_policy' died
,08-04 11:58:15.439   265   265 I ServiceManager: service 'remoteinjection' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'alarm' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'sedenial' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'vibrator' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'tima' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'cepproxyks' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'batterystats' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'appops' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'battery' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'usagestats' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'webviewupdate' died
,08-04 11:58:15.439   265   265 I ServiceManager: service 'scheduling_policy' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'telephony.registry' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'entropy' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'SEAMService' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'persona' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'account' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'content' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'DirEncryptService' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'ReactiveService' died
,08-04 11:58:15.439   265   265 I ServiceManager: service 'procstats' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'gfxinfo' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'dbinfo' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'activity' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'package' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'cpuinfo' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'user' died
08-04 11:58:15.439   265   265 I ServiceManager: service 'meminfo' died
08-04 11:58:15.439  8618  8618 D AndroidRuntime: Shutting down VM
,08-04 11:58:15.449  1428  1771 E WifiManager: Channel connection lost
08-04 11:58:15.449  1195  1594 E WifiManager: Channel connection lost
,08-04 11:58:15.449  1403  1416 W Sensors : sensorservice died [0xaf0dd900]
,08-04 11:58:15.449   309  1526 W AudioFlinger: power manager service died !!!
08-04 11:58:15.449  1195  4917 W Sensors : sensorservice died [0xaf0ec240]
08-04 11:58:15.449   267   626 I SurfaceFlinger: restart the boot-animation @ binderDied
08-04 11:58:15.449   267   267 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6962000
08-04 11:58:15.449   267   267 D qdhwcomposer: hwc_blank: Unblanking display: 0
,08-04 11:58:15.449   309  1526 W AudioCache: clearPowerManager -mWakeLockCount is 0, failed to releaseWakeLock function
,08-04 11:58:15.459  1321  2803 E WifiManager: Channel connection lost
,08-04 11:58:15.459  1428  1466 W Sensors : sensorservice died [0xafa20180]
,08-04 11:58:15.459  1864  2293 E WifiManager: Channel connection lost
,08-04 11:58:15.459  1864  2847 W Sensors : sensorservice died [0xb3b55380]
,08-04 11:58:15.459  1439  1456 W Sensors : sensorservice died [0xaf0f2280]
,08-04 11:58:15.459  1487  2246 E WifiManager: Channel connection lost
,08-04 11:58:15.459  1782  1798 W Sensors : sensorservice died [0xaf072300]
,08-04 11:58:15.459  1892  1941 W Sensors : sensorservice died [0xaf0dda00]
,08-04 11:58:15.469  7620  7645 E WifiManager: Channel connection lost
,08-04 11:58:15.469  1498  3809 E WifiManager: Channel connection lost
,08-04 11:58:15.469   267   374 I SurfaceFlinger: id=2 Removed GocusedStac (5/8)
,08-04 11:58:15.469   267   374 I SurfaceFlinger: id=3 Removed EimLayer (0/7)
08-04 11:58:15.469   267   374 I SurfaceFlinger: id=4 Removed EimLayer (0/6)
08-04 11:58:15.469   267   374 I SurfaceFlinger: id=5 Removed EimLayer (0/5)
08-04 11:58:15.469   267   374 I SurfaceFlinger: id=6 Removed EimLayer (0/4)
08-04 11:58:15.469   267   374 I SurfaceFlinger: id=2 Removed GocusedStac (-2/4)
08-04 11:58:15.469   267   374 I SurfaceFlinger: id=3 Removed EimLayer (-2/4)
,08-04 11:58:15.469   267   374 I SurfaceFlinger: id=4 Removed EimLayer (-2/4)
08-04 11:58:15.469   267   374 I SurfaceFlinger: id=7 Removed JmageWallpa (0/3)
08-04 11:58:15.469   267   374 I SurfaceFlinger: id=7 Removed JmageWallpa (-2/3)
08-04 11:58:15.469   267   374 I SurfaceFlinger: id=9 Removed TtatusBar (1/2)
08-04 11:58:15.469   267   374 I SurfaceFlinger: id=14 Removed Mauncher (0/1)
08-04 11:58:15.469   267   374 I SurfaceFlinger: id=9 Removed TtatusBar (-2/1)
08-04 11:58:15.469   267   374 I SurfaceFlinger: id=14 Removed Mauncher (-2/1)
08-04 11:58:15.479   267   374 I SurfaceFlinger: id=11 Removed DolorFade (0/0)
08-04 11:58:15.479   267   374 I SurfaceFlinger: id=11 Removed DolorFade (-2/0)
,08-04 11:58:15.479   267  1709 I SurfaceFlinger: id=5 Removed EimLayer (-2/0)
,08-04 11:58:15.479   267  1709 I SurfaceFlinger: id=6 Removed EimLayer (-2/0)
,08-04 11:58:15.479  8618  8618 E AndroidRuntime: FATAL EXCEPTION: main
08-04 11:58:15.479  8618  8618 E AndroidRuntime: Process: com.samsung.android.app.galaxyfinder, PID: 8618
08-04 11:58:15.479  8618  8618 E AndroidRuntime: java.lang.RuntimeException: Package manager has died
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:301)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at android.app.ApplicationPackageManager.getResourcesForApplication(ApplicationPackageManager.java:1299)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at com.samsung.android.app.galaxyfinder.SearchableAppManager.getApplicationLabel(SearchableAppManager.java:436)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at com.samsung.android.app.galaxyfinder.SearchableAppManager$1.compare(SearchableAppManager.java:412)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at com.samsung.android.app.galaxyfinder.SearchableAppManager$1.compare(SearchableAppManager.java:409)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at java.util.TimSort.binarySort(TimSort.java:261)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at java.util.TimSort.sort(TimSort.java:186)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at java.util.TimSort.sort(TimSort.java:169)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at java.util.Arrays.sort(Arrays.java:2010)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at java.util.Collections.sort(Collections.java:1883)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at com.samsung.android.app.galaxyfinder.SearchableAppManager.updateSearchableList(SearchableAppManager.java:401)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at com.samsung.android.app.galaxyfinder.SearchableAppManager.getSearchableList(SearchableAppManager.java:87)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.updateSearchableList(CategoryPreferences.java:57)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at com.samsung.android.app.galaxyfinder.util.CategoryPreferences.refreshSearchCategory(CategoryPreferences.java:113)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at com.samsung.android.app.galaxyfinder.ApplicationStatusReceiver$1.handleMessage(ApplicationStatusReceiver.java:66)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: Caused by: android.os.DeadObjectException
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at android.os.BinderProxy.transactNative(Native Method)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at android.os.BinderProxy.transact(Binder.java:496)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at android.content.pm.IPackageManager$Stub$Proxy.getApplicationInfo(IPackageManager.java:2309)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:292)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	... 21 more
,08-04 11:58:15.479  8618  8618 E AndroidRuntime: Error reporting crash
08-04 11:58:15.479  8618  8618 E AndroidRuntime: android.os.DeadObjectException
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at android.os.BinderProxy.transactNative(Native Method)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at android.os.BinderProxy.transact(Binder.java:496)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4706)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
08-04 11:58:15.479  8618  8618 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
08-04 11:58:15.479  8618  8618 I Process : Sending signal. PID: 8618 SIG: 9
,08-04 11:58:15.609  8568  8606 I qtaguid : Untagging socket 50
,08-04 11:58:15.619  8568  8606 E Volley  : [1328] NetworkDispatcher.run: Unhandled exception java.lang.NullPointerException: Attempt to read from field 'byte[] com.android.volley.Cache$Entry.data' on a null object reference
08-04 11:58:15.619  8568  8606 E Volley  : java.lang.NullPointerException: Attempt to read from field 'byte[] com.android.volley.Cache$Entry.data' on a null object reference
08-04 11:58:15.619  8568  8606 E Volley  : 	at com.android.volley.toolbox.BasicNetwork.performRequest(BasicNetwork.java:100)
08-04 11:58:15.619  8568  8606 E Volley  : 	at com.android.volley.NetworkDispatcher.run(NetworkDispatcher.java:105)
,08-04 11:58:15.689   267   535 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,08-04 11:58:15.689   267   267 E qdexternal: writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
08-04 11:58:15.689   267   267 D qdhwcomposer: hwc_blank: Done unblanking display: 0
08-04 11:58:15.689   267   557 E qdhwcomposer: hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Operation not permitted
08-04 11:58:15.689   267   557 E SurfaceFlinger: eventControl(0, 1) failed Operation not permitted
,08-04 11:58:15.719   315   315 E installd: eof
08-04 11:58:15.719   315   315 E installd: failed to read size
08-04 11:58:15.719   315   315 I installd: closing connection
,08-04 11:58:15.779  8568  8568 E AndroidRuntime: FATAL EXCEPTION: main
08-04 11:58:15.779  8568  8568 E AndroidRuntime: Process: sstream.app, PID: 8568
08-04 11:58:15.779  8568  8568 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver sstream.app.receiver.ApplicationCompatibleReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2996)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1623)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at sstream.app.provider.StoryProvider.delete(StoryProvider.java:140)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:314)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1309)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at sstream.app.provider.DatabaseUtil.deleteConfigSettingForApp(DatabaseUtil.java:985)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at sstream.app.receiver.ApplicationCompatibleReceiver.onReceive(ApplicationCompatibleReceiver.java:216)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	... 9 more
,08-04 11:58:15.779  8568  8568 E AndroidRuntime: Error reporting crash
08-04 11:58:15.779  8568  8568 E AndroidRuntime: android.os.DeadObjectException
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at android.os.BinderProxy.transactNative(Native Method)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at android.os.BinderProxy.transact(Binder.java:496)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4706)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at sstream.app.util.Log$1.uncaughtException(Log.java:39)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at net.hockeyapp.android.internal.ExceptionHandler.uncaughtException(ExceptionHandler.java:111)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
08-04 11:58:15.779  8568  8568 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
08-04 11:58:15.779  8568  8568 I Process : Sending signal. PID: 8568 SIG: 9
,08-04 11:58:15.849   267   535 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-04 11:58:15.879   362   362 I ServiceManager: Waiting for service AtCmdFwd...

```
