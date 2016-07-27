#### Test 77622416ad9274d_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
07-27 11:50:57.604   771  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response_id = 3
07-27 11:50:57.604   771  1100 I TLC_TIMA_PKM_measure_kernel: TIMA: response ret = 0, result_ondemand = MSG=Kernel Verification Success;
--------- beginning of system
07-27 11:50:57.614   771  1100 D TimaService: TIMA MEASUREMENT Result: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-27 11:50:57.614   771  1100 D TimaService: TIMA MEASUREMENT success status: TIMA_STATUS=0;MSG=Kernel Verification Success;
07-27 11:50:57.744   771  1338 E Watchdog: !@Sync 10
07-27 11:50:57.964   304   304 E SMD     : DCD ON
,07-27 11:50:58.734  7555  7555 D AndroidRuntime: 
07-27 11:50:58.734  7555  7555 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-27 11:50:58.744  7555  7555 D AndroidRuntime: CheckJNI is OFF
07-27 11:50:58.744  7555  7555 D AndroidRuntime: readGMSProperty: start
07-27 11:50:58.744  7555  7555 D AndroidRuntime: readGMSProperty: already setted!!
07-27 11:50:58.744  7555  7555 D AndroidRuntime: readGMSProperty: end
07-27 11:50:58.744  7555  7555 D AndroidRuntime: addProductProperty: start
07-27 11:50:58.914  7555  7555 E AffinityControl: AffinityControl: registerfunction enter
07-27 11:50:58.934  7555  7555 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-27 11:50:58.944   771  1702 E PersonaManagerService: inState():  stateMachine is null !!
07-27 11:50:58.944   771  1702 I PersonaManagerService: PersonaId don't exist
07-27 11:50:58.944   771  1702 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-27 11:50:58.944   771  1702 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-27 11:50:58.944   771  1702 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-27 11:50:58.944   771  1702 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-27 11:50:58.954   771  1702 W ActivityManager: mDVFSHelper.acquire()
07-27 11:50:58.954   771  1702 D FocusedStackFrame: Set to : 0
07-27 11:50:58.954   771  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:50:58.954   771  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:50:58.954   771  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:50:58.954   771  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:50:59.014   771  1702 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7570 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-27 11:50:59.014   771  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-27 11:50:59.014   771  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 11:50:59.014   771  1047 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-27 11:50:59.014   771  1047 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-27 11:50:59.024  7570  7570 E Zygote  : MountEmulatedStorage()
07-27 11:50:59.024  7570  7570 I libpersona: KNOX_SDCARD checking this for 10079
07-27 11:50:59.024  7570  7570 E Zygote  : v2
07-27 11:50:59.024  7570  7570 I libpersona: KNOX_SDCARD not a persona
07-27 11:50:59.034  7555  7555 D AndroidRuntime: Shutting down VM
07-27 11:50:59.034  7570  7570 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 11:50:59.034  7570  7570 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 11:50:59.034  7570  7570 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-27 11:50:59.064  7570  7570 D TimaKeyStoreProvider: TimaSignature is unavailable
07-27 11:50:59.064  7570  7570 D ActivityThread: Added TimaKeyStore provider
07-27 11:50:59.064   771  1360 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-27 11:50:59.064   771  1360 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
07-27 11:50:59.064   771  1360 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-27 11:50:59.064   771  1360 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-27 11:50:59.064   771  1360 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
07-27 11:50:59.094  1443  1443 D SurfaceWidgetView: destroyHardwareResources():328834930
07-27 11:50:59.094   771  3104 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:50:59.104  7570  7570 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-27 11:50:59.114   771  3104 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:50:59.154   266  1337 I SurfaceFlinger: id=9 Removed Mauncher (6/8)
07-27 11:50:59.154   266   349 I SurfaceFlinger: id=9 Removed Mauncher (-2/8)
07-27 11:50:59.174  1826  1842 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
07-27 11:50:59.174  1443  1443 V ActivityThread: updateVisibility : ActivityRecord{2d8f79af token=android.os.BinderProxy@11aaf0b2 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-27 11:50:59.174  1443  1443 D Launcher: onTrimMemory. Level: 20
07-27 11:50:59.194  7570  7570 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-27 11:50:59.194  7570  7570 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
07-27 11:50:59.214  7570  7570 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 518-521)
07-27 11:50:59.214  7570  7570 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 11:50:59.234  7570  7570 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {273b5d3c}
07-27 11:50:59.234  7570  7570 I LibraryLoader: Expected native library version number "",actual native library version number ""
07-27 11:50:59.234  7570  7570 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-27 11:50:59.264  7570  7570 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-27 11:50:59.264  7570  7570 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-27 11:50:59.264  7570  7570 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-27 11:50:59.284  7570  7570 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-27 11:50:59.284  7570  7570 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
07-27 11:50:59.284  7570  7570 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-27 11:50:59.284  7570  7570 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-27 11:50:59.284  7570  7570 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-27 11:50:59.284  7570  7570 I Adreno-EGL: Build Date: 11/19/14 Wed
07-27 11:50:59.284  7570  7570 I Adreno-EGL: Local Branch: mybranch5813579
07-27 11:50:59.284  7570  7570 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-27 11:50:59.284  7570  7570 I Adreno-EGL: Local Patches: NONE
07-27 11:50:59.284  7570  7570 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-27 11:50:59.384  7570  7602 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-27 11:50:59.414  7570  7570 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-27 11:50:59.424  7570  7570 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-27 11:50:59.434  7570  7570 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-27 11:50:59.444  7570  7570 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-27 11:50:59.444  7570  7570 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-27 11:50:59.494  7570  7570 D Activity: performCreate Call secproduct feature valuefalse
07-27 11:50:59.494  7570  7570 D Activity: performCreate Call debug elastic valuetrue
,07-27 11:50:59.494  7570  7615 D OpenGLRenderer: Render dirty regions requested: true
,07-27 11:50:59.504   771  3075 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-27 11:50:59.504   771  3075 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-27 11:50:59.504   771  3075 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-27 11:50:59.504   771   771 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-27 11:50:59.504   771   771 D PersonaManagerService: getPersonasForUser(): returning null!
,07-27 11:50:59.524   266   266 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,07-27 11:50:59.524   771  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-27 11:50:59.524   771  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-27 11:50:59.534   771  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,07-27 11:50:59.534   771  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 11:50:59.534   771  1047 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-27 11:50:59.534   771  1047 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-27 11:50:59.534  7570  7615 I OpenGLRenderer: Initialized EGL, version 1.4
,07-27 11:50:59.544  7570  7615 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xb3df3218 ,&mEglDisplay = 1 , &mEglConfig = 8 
,07-27 11:50:59.544  7570  7615 D OpenGLRenderer: Enabling debug mode 0
,07-27 11:50:59.564  7570  7570 V ActivityThread: updateVisibility : ActivityRecord{35c65e96 token=android.os.BinderProxy@25ad1458 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-27 11:50:59.584   771  1567 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-27 11:50:59.584   771  7620 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 11:50:59.594  1748  1748 I SamsungIME: getCurrentCandidateView
,07-27 11:50:59.594  7570  7570 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-27 11:50:59.604   771  1047 W ActivityManager: mDVFSHelper.release()
,07-27 11:50:59.604   771  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{253265c2 u0 com.test.thalitest/.MainActivity t99} time:320916
,07-27 11:50:59.604  7570  7570 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@25ad1458 time:320917
,07-27 11:50:59.644  7570  7570 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7570
,07-27 11:50:59.654  1748  1748 D SamsungIME: Dismiss ExpandCandiate
,07-27 11:50:59.704   771  3104 D SSRM:n  : SIOP:: AP = 320, PST = 316, CUR = 450
,07-27 11:50:59.724  7570  7570 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-27 11:50:59.734  1748  1748 I SamsungIME: getDebugLevel  : 0x4f4c
,07-27 11:50:59.764  1748  1748 I SamsungIME: getDebugLevel  : 0x4f4c
,07-27 11:50:59.774  1748  1748 I SamsungIME: KeybaordView init() : load resources
,07-27 11:50:59.804  1748  1748 I SamsungIME: getCurrentKeyboard
07-27 11:50:59.804  1748  1748 I SamsungIME: getTextKeyboard
,07-27 11:50:59.814  1748  1748 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-27 11:50:59.814  7570  7623 D jxcore_app_log: JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1258385920
,07-27 11:50:59.824  7570  7623 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-27 11:50:59.824  7570  7623 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-27 11:50:59.824  7570  7623 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-27 11:50:59.824  7570  7623 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-27 11:50:59.824  7570  7623 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-27 11:50:59.824  7570  7623 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e719946 added. We now have 1 listener(s)
,07-27 11:50:59.834  7570  7623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:1F:C9:5E
,07-27 11:50:59.834  7570  7623 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-27 11:50:59.834  7570  7623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-27 11:50:59.834  7570  7623 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-27 11:50:59.854  7570  7623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-27 11:50:59.854  7570  7623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-27 11:50:59.854  7570  7623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-27 11:50:59.854  7570  7623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:1F:C9:5E
07-27 11:50:59.854  7570  7623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-27 11:50:59.854  7570  7623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-27 11:50:59.854  7570  7623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-27 11:50:59.854  7570  7623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-27 11:50:59.854  7570  7623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-27 11:50:59.854  7570  7623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-27 11:50:59.854  7570  7623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-27 11:50:59.854  7570  7623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-27 11:50:59.854  7570  7623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-27 11:50:59.854  7570  7623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,07-27 11:50:59.854  7570  7623 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2112ee5d added. We now have 1 listener(s)
07-27 11:50:59.854  7570  7623 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 11:50:59.864  7570  7623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 11:50:59.864  7570  7623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,07-27 11:50:59.864  7570  7623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
,07-27 11:50:59.864  7570  7623 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-27 11:50:59.864  7570  7623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 11:50:59.864  7570  7623 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:1F:C9:5E
07-27 11:50:59.864   771  1143 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:50:59.874  7570  7623 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,07-27 11:50:59.874  7570  7623 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:50:59.874  7570  7623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:50:59.874  7570  7623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:50:59.874  7570  7623 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:50:59.874  7570  7623 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:50:59.874  7570  7623 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:50:59.874  7570  7623 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:50:59.874  7570  7623 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:50:59.874  7570  7623 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-27 11:50:59.874  7570  7623 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:50:59.874   771   794 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:50:59.874  7570  7623 I io.jxcore.node.LifeCycleMonitor: start: OK
07-27 11:50:59.874  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:50:59.874   771  3266 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:50:59.874  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:50:59.914  7570  7570 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-27 11:51:00.154  1748  7626 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-27 11:51:00.544  7570  7631 W jxcore-log: Initializing JXcore engine
,07-27 11:51:00.544  7570  7631 W jxcore-log: JXcore engine is ready
,07-27 11:51:00.594  1874  1874 E auditd  : In denial and Property audit_ondenial is set to 1 
,07-27 11:51:00.604   771  1036 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
,07-27 11:51:00.604   771  1036 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
07-27 11:51:00.604  1874  1874 E audit   : type=1400 msg=audit(1469613060.594:203): avc:  denied  { ioctl } for  pid=7631 comm="Thread-1228" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,07-27 11:51:00.604  1874  1874 E audit   :  SEPF_SM-N9005_5.0-1_0032
07-27 11:51:00.604  1874  1874 E audit   : 
,07-27 11:51:00.604  1874  1874 E audit   : type=1300 msg=audit(1469613060.594:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=1 a3=988e08d8 items=0 ppid=332 ppcomm=main pid=7631 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1228" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
,07-27 11:51:00.604   771  1036 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
07-27 11:51:00.604  1874  1874 E audit   : type=1320 msg=audit(1469613060.594:203): 
,07-27 11:51:00.604  6793  6793 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,07-27 11:51:00.604  6793  6793 D SecurityLogAgent:  SeDenialReceiver : File path = null
,07-27 11:51:00.614  7570  7631 W jxcore-log: Starting JXcore engine
,07-27 11:51:00.694  7570  7631 W jxcore-log: Platform android
07-27 11:51:00.694  7570  7631 W jxcore-log: 
,07-27 11:51:00.694  7570  7631 W jxcore-log: Process ARCH arm
07-27 11:51:00.694  7570  7631 W jxcore-log: 
,07-27 11:51:00.734   771  1310 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 11:51:00.884  7570  7631 I jxcore-log: JXcore Cordova bridge is ready!
07-27 11:51:00.884  7570  7631 I jxcore-log: 
,07-27 11:51:00.884  7570  7631 W jxcore-log: JXcore engine is started
,07-27 11:51:00.884  7570  7623 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-27 11:51:00.894  7570  7570 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-27 11:51:00.954   304   304 E SMD     : DCD ON
,07-27 11:51:03.954   304   304 E SMD     : DCD ON
,07-27 11:51:04.234   361   361 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,07-27 11:51:04.234   361   361 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,07-27 11:51:06.954   304   304 E SMD     : DCD ON
,07-27 11:51:09.004   771  1063 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-27 11:51:09.754   771  3104 D SSRM:n  : SIOP:: AP = 360, PST = 320, CUR = 450
,07-27 11:51:09.954   304   304 E SMD     : DCD ON
,07-27 11:51:10.934  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-27 11:51:10.934  7570  7631 I jxcore-log: 
,07-27 11:51:10.934  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-27 11:51:10.934  7570  7631 I jxcore-log: 
,07-27 11:51:10.934   771   796 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:10.944  7570  7631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:51:10.944  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:10.944  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:10.944  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:10.944  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:10.944  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:10.944  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:51:10.944  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 11:51:10.944  7570  7631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 11:51:10.944  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-27 11:51:10.944  7570  7631 I jxcore-log: 
,07-27 11:51:10.944  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-27 11:51:10.944  7570  7631 I jxcore-log: 
,07-27 11:51:11.284  7570  7631 D ExecuteNativeTests: Running unit tests
,07-27 11:51:11.384  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:51:11.384  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 added. We now have 2 listener(s)
,07-27 11:51:11.384  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-27 11:51:11.384  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:51:11.384  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:51:11.384  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:11.384  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 added. We now have 2 listener(s)
07-27 11:51:11.384  7570  7631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:11.384  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 11:51:11.394  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 11:51:11.394   771  3075 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:11.394  7570  7631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:51:11.394  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:11.394  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:11.394  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:11.394  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:11.394  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:11.394  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:51:11.394  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 11:51:11.394  7570  7631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 11:51:11.394  7570  7631 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:51:11.394   771   794 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:11.394  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:11.394   771  1318 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:11.394  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:11.394  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-27 11:51:11.404  7570  7631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-27 11:51:11.404  7570  7631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-27 11:51:11.404  7570  7631 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,07-27 11:51:11.404  7570  7631 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-27 11:51:11.404  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-27 11:51:11.404  7570  7631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-27 11:51:11.404  7570  7631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-27 11:51:11.404  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.404  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-27 11:51:11.404  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.404  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.404  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.404  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:11.404  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-27 11:51:11.404  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 removed from the list
07-27 11:51:11.404  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.404  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 removed from the list
07-27 11:51:11.404  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.404  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:51:11.414  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 11:51:11.414  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:51:11.414  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.414  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-27 11:51:11.414  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.414  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
,07-27 11:51:11.414  7570  7631 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,07-27 11:51:11.414  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.414  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.414  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-27 11:51:11.414  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.414  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.414  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.414  7570  7631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 not in the list
07-27 11:51:11.414  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 11:51:11.414  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.414  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.414  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.414  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.414  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.414  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:51:11.414  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.414  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-27 11:51:11.414  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.414  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
,07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
,07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,07-27 11:51:11.424  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.424  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.424  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.424  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.424  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.424  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.424  7570  7631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 not in the list
07-27 11:51:11.424  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.424  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.424  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.424  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.424  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.424  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.424  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.424  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.424  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.424  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.424  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.424  7570  7631 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-27 11:51:11.434  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:11.434   771   794 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:11.434  7570  7631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:51:11.434  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:11.434  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:11.434  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:11.434  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:11.434  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:11.434  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:51:11.434  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:51:11.434  7570  7631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:11.434  7570  7631 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:51:11.434   771  1458 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:11.434  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:51:11.434  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:11.434  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 11:51:11.434  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:11.434  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 11:51:11.434   771  1702 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:11.434  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:11.434  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-27 11:51:11.444  7570  7631 E BluetoothAdapter: bluetooth le advertising not supported
07-27 11:51:11.444  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-27 11:51:11.444  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-27 11:51:11.444  7570  7631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
07-27 11:51:11.454  7570  7631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
07-27 11:51:11.454  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 11:51:11.454  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:11.454  7570  7631 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 11:51:11.454  7570  7631 I io.jxcore.node.ConnectionHelper: start: OK
07-27 11:51:11.454  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.454  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.454  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.454  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.454  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.454  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:11.454  7570  7631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 not in the list
07-27 11:51:11.454  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.454  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.454  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.454  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.454  7570  7631 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-27 11:51:11.454  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:11.454   771  1143 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:11.464  7570  7631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:51:11.464  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:11.464  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:11.464  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:11.464  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:11.464  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:11.464  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:51:11.464  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:51:11.464  7570  7631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-27 11:51:11.464  7570  7631 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:51:11.464   771  3266 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:11.464  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:51:11.464  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 11:51:11.464  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:11.464   771   796 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:11.464  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:11.464  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 11:51:11.464  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:11.464  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 11:51:11.464  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:11.464  7570  7631 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 11:51:11.464  7570  7631 I io.jxcore.node.ConnectionHelper: start: OK
07-27 11:51:11.474  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.474  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.474  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.474  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.474  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.474  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:11.474  7570  7631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 not in the list
07-27 11:51:11.474  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.474  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.474  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.474  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.474  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.474  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.474  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.474  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.474  7570  7631 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.474  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.474  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.474  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.474  7570  7631 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-27 11:51:11.474  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:11.474   771  1428 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:11.474  7570  7631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:51:11.474  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:11.474  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:11.474  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:11.474  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:11.474  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:11.474  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:51:11.474  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:51:11.474  7570  7631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:11.474  7570  7631 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:51:11.484   771  1143 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:11.484  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:51:11.484  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 11:51:11.484  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:11.484  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 11:51:11.484  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:11.484   771  1702 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:11.484  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:11.484  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 11:51:11.484  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:11.484  7570  7631 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 11:51:11.484  7570  7631 I io.jxcore.node.ConnectionHelper: start: OK
07-27 11:51:11.484  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.484  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.484  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.484  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.484  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.484  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.484  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.484  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.484  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:11.484  7570  7631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 not in the list
07-27 11:51:11.484  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.484  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.484  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.484  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.484  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.484  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.494  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.494  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.494  7570  7631 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.494  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.494  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.494  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.494  7570  7631 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-27 11:51:11.494  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.494  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.494  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.494  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.494  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.494  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.494  7570  7631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 not in the list
07-27 11:51:11.494  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.494  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.494  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.494  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.494  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.494  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.494  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.494  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.494  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.494  7570  7631 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.494  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.494  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.494  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.494  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-27 11:51:11.494  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.494  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.494  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.494  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.494  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.494  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.494  7570  7631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 not in the list
07-27 11:51:11.494  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.494  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.494  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.494  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.494  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.494  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.494  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.494  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.494  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.494  7570  7631 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.494  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.494  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.494  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.494  7570  7631 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-27 11:51:11.494  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.504  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.504  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.504  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.504  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.504  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.504  7570  7631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 not in the list
07-27 11:51:11.504  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.504  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.504  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.504  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.504  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.504  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.504  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.504  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.504  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.504  7570  7631 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.504  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.504  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.504  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
,07-27 11:51:11.504  7570  7631 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-27 11:51:11.504  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.504  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.504  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.504  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.504  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.504  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.504  7570  7631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 not in the list
07-27 11:51:11.504  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.504  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.504  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.504  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.504  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.504  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.504  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.504  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.504  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.504  7570  7631 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.504  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.504  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.504  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.504  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-27 11:51:11.504  7570  7631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-27 11:51:11.504  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-27 11:51:11.504  7570  7631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-27 11:51:11.504  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-27 11:51:11.504  7570  7631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-27 11:51:11.504  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.504  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.504  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.504  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.504  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.504  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.504  7570  7631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 not in the list
07-27 11:51:11.504  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.504  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.504  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.504  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.504  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.504  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.504  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.504  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.504  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.504  7570  7631 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.504  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.504  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.504  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.514  7570  7631 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 11:51:11.514  7570  7631 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-27 11:51:11.514  7570  7631 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 11:51:11.514  7570  7631 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-27 11:51:11.514  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-27 11:51:11.514  7570  7631 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-27 11:51:11.514  7570  7631 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-27 11:51:11.514  7570  7631 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-27 11:51:11.514  7570  7631 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 11:51:11.514  7570  7631 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-27 11:51:11.514  7570  7631 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-27 11:51:11.514  7570  7631 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 11:51:11.514  7570  7631 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-27 11:51:11.514  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-27 11:51:11.514  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-27 11:51:11.514  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-27 11:51:11.514  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-27 11:51:11.514  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-27 11:51:11.524  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-27 11:51:11.524  7570  7631 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-27 11:51:11.524  7570  7631 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-27 11:51:11.524  7570  7631 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-27 11:51:11.524  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.524  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.524  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.524  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.524  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.524  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.524  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-27 11:51:11.524  7570  7631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 not in the list
07-27 11:51:11.524  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.524  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.524  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.524  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.524  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.524  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.524  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.524  7570  7651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1292)
07-27 11:51:11.524  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.524  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.524  7570  7631 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.524  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.524  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.524  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.524  7570  7631 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-27 11:51:11.524  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.524  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.524  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.524  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.524  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.524  7570  7651 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
07-27 11:51:11.524  7570  7651 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 11:51:11.524  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.524  7570  7631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 not in the list
07-27 11:51:11.524  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.534  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.534  3011  3024 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:51:11.534  7570  7651 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
07-27 11:51:11.534  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.534  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.534  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.534  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.534  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.534  3011  3185 D bt_vendor: op for 7
07-27 11:51:11.534  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.534  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.534  7570  7631 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.534  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.534  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.534  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.534  7570  7631 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-27 11:51:11.534  3011  3185 D bt_upio : proc btwrite assertion
07-27 11:51:11.534  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.534  7570  7652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1292
07-27 11:51:11.534  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.534  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.534  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.534  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.534  7570  7652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 1292)
07-27 11:51:11.534  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.534  7570  7631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 not in the list
07-27 11:51:11.534  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.534  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.534  7570  7652 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@36321771, channel: -1, state: INIT
07-27 11:51:11.534  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.534  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.534  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.534  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.544  7570  7652 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@36321771, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@28de9956, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2803add7mSocket: android.net.LocalSocket@33d2b6c4 impl:android.net.LocalSocketImpl@23ffb9ad fd:FileDescriptor[112]
07-27 11:51:11.544  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.544  7570  7652 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@33d2b6c4 impl:android.net.LocalSocketImpl@23ffb9ad fd:FileDescriptor[112]
07-27 11:51:11.544  7570  7651 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@36321771, channel: -1, state: CLOSED
07-27 11:51:11.544  7570  7651 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1292)
07-27 11:51:11.544  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.544  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.544  7570  7631 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.544  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.544  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.544  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.544  3011  3361 E bt-btif : SOCK_THREAD_FD_RD signaled when rfc is not connected,                                       slot id:4, channel:-1
,07-27 11:51:11.544  7570  7631 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-27 11:51:11.544  7570  7652 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 1292)
07-27 11:51:11.544  7570  7631 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-27 11:51:11.544  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-27 11:51:11.544  7570  7631 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-27 11:51:11.544  7570  7631 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-27 11:51:11.544  7570  7631 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-27 11:51:11.544  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-27 11:51:11.544  7570  7631 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-27 11:51:11.544  7570  7631 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-27 11:51:11.544  7570  7631 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-27 11:51:11.544  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-27 11:51:11.544  7570  7631 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-27 11:51:11.544  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.544  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.544  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.544  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.544  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.544  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.544  7570  7631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 not in the list
07-27 11:51:11.544  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.544  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.544  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.544  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.544  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.544  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.544  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.544  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.544  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.544  7570  7631 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.544  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.544  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.544  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.544  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.544  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.544  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.544  7570  7631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 not in the list
07-27 11:51:11.554  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.554  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.554  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.554  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.554  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.554  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.554  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.554  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.554  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.554  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.554  7570  7631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 not in the list
07-27 11:51:11.554  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.554  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.554  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.554  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.554  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.554  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.554  7570  7631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 not in the list
07-27 11:51:11.554  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.554  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.554  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.554  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.554  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.554  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.554  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.554  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.554  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.554  7570  7631 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.554  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.554  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.554  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.554  7570  7631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-27 11:51:11.554  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:11.554  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-27 11:51:11.554  7570  7631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-27 11:51:11.554  7570  7631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-27 11:51:11.554  7570  7570 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-27 11:51:11.554  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-27 11:51:11.554  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-27 11:51:11.554  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.554  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-27 11:51:11.554  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-27 11:51:11.554  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-27 11:51:11.554  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.554  7570  7631 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-27 11:51:11.554  7570  7570 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-27 11:51:11.554  7570  7631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 not in the list
07-27 11:51:11.554  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.554  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-27 11:51:11.554  7570  7631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-27 11:51:11.554  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-27 11:51:11.554  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-27 11:51:11.554  7570  7631 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:11.554  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:11.554  7570  7631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-27 11:51:11.554  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.554  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.564  7570  7631 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 11:51:11.564  7570  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 11:51:11.564  7570  7570 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-27 11:51:11.564  7570  7570 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-27 11:51:11.564  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.564  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.564  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.564  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.564  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.564  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.564  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.564  7570  7631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 not in the list
07-27 11:51:11.564  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.564  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.564  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.564  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.564  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.564  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.564  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.564  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.564  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.564  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.564  7570  7653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-27 11:51:11.564  7570  7653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-27 11:51:11.564  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.564  7570  7570 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-27 11:51:11.564  7570  7631 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-27 11:51:11.564  7570  7631 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-27 11:51:11.564  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-27 11:51:11.564  7570  7631 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-27 11:51:11.564  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.564  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.564  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.564  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.564  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.564  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.564  7570  7631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 not in the list
07-27 11:51:11.564  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.564  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.564  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.564  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.564  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.564  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.564  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.574  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.574  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.574  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.574  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.574  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.574  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.574  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.574  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.574  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.574  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.574  7570  7631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 not in the list
07-27 11:51:11.574  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.574  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.574  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.574  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.574  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.574  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.574  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.574  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.574  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.574  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.574  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.574  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:11.574  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:11.574  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:11.574  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:11.574  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.574  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.574  7570  7631 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c694083 not in the list
07-27 11:51:11.574  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.574  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.574  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:11.574  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.574  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.574  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:11.574  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:11.574  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:11.574  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:11.574  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:11.574  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32ca9200 not in the list
07-27 11:51:11.584  7570  7631 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-27 11:51:11.584  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-27 11:51:11.584  7570  7631 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-27 11:51:11.584  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-27 11:51:11.584  7570  7631 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-27 11:51:11.584  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,07-27 11:51:11.584  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-27 11:51:11.584  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
07-27 11:51:11.584  7570  7631 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-27 11:51:11.584  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-27 11:51:11.584  7570  7631 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-27 11:51:11.584  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-27 11:51:11.584  7570  7631 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-27 11:51:11.584  7570  7631 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
07-27 11:51:11.584  7570  7631 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-27 11:51:11.584  7570  7631 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
07-27 11:51:11.584  7570  7631 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-27 11:51:11.584  7570  7631 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-27 11:51:11.584  7570  7631 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-27 11:51:11.584  7570  7631 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-27 11:51:11.584  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:11.584  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@742f4e2 added. We now have 2 listener(s)
07-27 11:51:11.584  7570  7631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:11.594  7570  7631 D BluetoothAdapter: enable()
07-27 11:51:11.594  7570  7631 D BluetoothAdapter: enable(): BT is already enabled..!
07-27 11:51:11.594  7570  7631 I WifiManager: packageName : com.test.thalitest
07-27 11:51:11.594   771  1506 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-27 11:51:11.594   771  1506 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-27 11:51:11.594   771  1506 D SecContentProvider2: mCursor = null
07-27 11:51:11.594   771  1506 D WifiService: setWifiEnabled: true pid=7570, uid=10079
07-27 11:51:11.594   771  1506 W ActivityManager: Permission Denial: getCurrentUser() from pid=7570, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-27 11:51:11.594   771  1506 W WifiService: Failed getting userId using ActivityManagerNative
07-27 11:51:11.594   771  1506 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7570, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-27 11:51:11.594   771  1506 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-27 11:51:11.594   771  1506 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-27 11:51:11.594   771  1506 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-27 11:51:11.594   771  1506 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-27 11:51:11.594   771  1506 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
07-27 11:51:11.594   771  1506 D SettingsProvider: name = wifi_on
07-27 11:51:11.594  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:11.594  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6eb5073 added. We now have 3 listener(s)
07-27 11:51:11.594  7570  7631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:11.594  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:11.594  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@10a67b30 added. We now have 4 listener(s)
07-27 11:51:11.594  7570  7631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:11.594  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:11.594  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@78b43a9 added. We now have 5 listener(s)
07-27 11:51:11.594  7570  7631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:11.604  7570  7631 I WifiManager: packageName : com.test.thalitest
07-27 11:51:11.604   771   794 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-27 11:51:11.604   771   794 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-27 11:51:11.604   771   794 D SecContentProvider2: mCursor = null
07-27 11:51:11.604   771   794 D WifiService: setWifiEnabled: false pid=7570, uid=10079
07-27 11:51:11.604   771   794 D SettingsProvider: name = wifi_on
07-27 11:51:11.604   771  1148 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-27 11:51:11.604  7570  7631 D BluetoothAdapter: disable()
07-27 11:51:11.604  1279  1279 I wpa_supplicant: reset timer : RESET_TIMER 0
07-27 11:51:11.604  1279  1279 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-27 11:51:11.604   771  1506 D SettingsProvider: name = bluetooth_on
07-27 11:51:11.604  1279  1279 I wpa_supplicant: P2P: Current p2p state = IDLE
07-27 11:51:11.614   771  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 11:51:11.614  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:11.614   771  1525 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:11.614  3011  3093 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
07-27 11:51:11.614  3011  3093 D BluetoothAdapterProperties: Setting state to 13
07-27 11:51:11.614  3011  3093 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-27 11:51:11.614  3011  3093 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 11:51:11.614  3011  3093 D BluetoothAdapterService: updateAdapterState state is 13
07-27 11:51:11.614   771  1318 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 11:51:11.614   771  1318 D ActivityManager: caller:android.app.ApplicationThreadProxy@3cbe02f7, r.packageName :com.android.bluetooth
07-27 11:51:11.614  3011  3011 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
07-27 11:51:11.614  3011  3093 D BluetoothAdapterService: Autoconnection is available 
07-27 11:51:11.614  3011  3093 D BluetoothAdapterServ,ice: updateAdapterState prevState = 12newState = 13
07-27 11:51:11.614  3011  3093 D BluetoothAdapterService: terminating service from this receiver
07-27 11:51:11.614  3011  3011 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@229484c9, channel: 19, state: LISTENING
07-27 11:51:11.614  3011  3011 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@229484c9, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d78dff6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3627f7cemSocket: android.net.LocalSocket@33d976ef impl:android.net.LocalSocketImpl@1aea5fc fd:FileDescriptor[74]
07-27 11:51:11.614  3011  3011 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@33d976ef impl:android.net.LocalSocketImpl@1aea5fc fd:FileDescriptor[74]
07-27 11:51:11.614  1279  1279 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-27 11:51:11.624   771   771 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:11.624   771   771 I InputMethodManagerService: [BT Setting State] State =13
,07-27 11:51:11.624  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:11.624  3011  3093 D BluetoothAdapterProperties: onBluetoothDisable()
,07-27 11:51:11.624  7570  7631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:51:11.624  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:11.624  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:11.624  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:11.624  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:51:11.624  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:11.624  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:51:11.624  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-27 11:51:11.624   771  3075 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,07-27 11:51:11.624  1312  1312 D BluetoothPbap: Proxy object disconnected
07-27 11:51:11.624  3011  3093 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-27 11:51:11.624  3011  3185 D bt_vendor: op for 7
07-27 11:51:11.624  3011  3185 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:11.624  3011  3185 D bt_vendor: op for 7
07-27 11:51:11.624  3011  3185 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:11.624  1312  1312 D PbapServerProfile: Bluetooth service disconnected
07-27 11:51:11.624  1188  1188 D BluetoothTile:  onBluetoothStateChange:
07-27 11:51:11.624  3011  3185 D bt_vendor: op for 7
07-27 11:51:11.624  3011  3185 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:11.634  1748  1748 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-27 11:51:11.634   771  1148 E native  : do suspend true
,07-27 11:51:11.634  1188  1188 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-27 11:51:11.634  1188  1188 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:51:11.634  1188  1601 D BluetoothTile:  handleUpdatestate:false name:null
07-27 11:51:11.634  1188  1601 D BluetoothTile:  handleUpdatestate:false name:null
07-27 11:51:11.634  1188  1601 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-27 11:51:11.634   771  1360 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-27 11:51:11.634   771  1702 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-27 11:51:11.634  1188  1188 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
07-27 11:51:11.634  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:11.634  7570  7631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:11.634  7570  7631 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-27 11:51:11.634   771  1147 D WifiP2pService: InactiveState{ what=143375 }
07-27 11:51:11.634   771  1147 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-27 11:51:11.634   771  1458 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:11.634   771  3266 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-27 11:51:11.644  3011  3097 D BluetoothAdapterProperties: Scan Mode:20
,07-27 11:51:11.644   771  3266 D ActivityManager: caller:android.app.ApplicationThreadProxy@3d8b564, r.packageName :com.google.android.gms
07-27 11:51:11.644  3011  3093 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-27 11:51:11.644  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:11.644  3011  3093 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
07-27 11:51:11.644   771  3075 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:11.644  3011  3093 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,07-27 11:51:11.644  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:11.644  3011  3093 E bt-btif : cmd socket is not created
07-27 11:51:11.644   771  1702 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:11.644  3011  5666 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,07-27 11:51:11.644  3011  3181 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
,07-27 11:51:11.644  3011  3185 D bt_vendor: op for 7
07-27 11:51:11.644  3011  3185 D bt_upio : BT_WAKE is asserted already
07-27 11:51:11.644  7570  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:11.644  3011  3181 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-27 11:51:11.644  3011  3181 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:51:11.644  3011  3181 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:51:11.644  3011  3181 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,07-27 11:51:11.644  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:11.644  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:11.644  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:11.644  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:11.644  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:51:11.644  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:11.644  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-27 11:51:11.644  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-27 11:51:11.644  3011  3093 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-27 11:51:11.644  3011  3185 D bt_vendor: op for 7
07-27 11:51:11.644  3011  3185 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:11.644   297  1060 D CommandListener: Clearing all IP addresses on wlan0
,07-27 11:51:11.644  3011  3185 D bt_vendor: op for 7
07-27 11:51:11.644  3011  3185 D bt_upio : BT_WAKE is asserted already
07-27 11:51:11.644  7570  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:11.644  7570  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-27 11:51:11.644   771  1458 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:11.644  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:11.644   771  1525 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:11.654  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:11.654   771  1360 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:11.654  3011  3011 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@15cfc2da, channel: 5, state: LISTENING
,07-27 11:51:11.654  3011  3011 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@15cfc2da, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f84d491, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2570930bmSocket: android.net.LocalSocket@33e25e8 impl:android.net.LocalSocketImpl@a730401 fd:FileDescriptor[72]
07-27 11:51:11.654  3011  3011 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@33e25e8 impl:android.net.LocalSocketImpl@a730401 fd:FileDescriptor[72]
,07-27 11:51:11.654  3011  3011 I BtOppRfcommListener: stopping Accept Thread
07-27 11:51:11.654  3011  3011 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@17f732a6, channel: 12, state: LISTENING
,07-27 11:51:11.654  3011  3011 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@17f732a6, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a358cd0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@181354e7mSocket: android.net.LocalSocket@35c3b894 impl:android.net.LocalSocketImpl@1d0adf3d fd:FileDescriptor[77]
07-27 11:51:11.654  3011  3011 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@35c3b894 impl:android.net.LocalSocketImpl@1d0adf3d fd:FileDescriptor[77]
,07-27 11:51:11.654  3011  5666 I BtOppRfcommListener: BluetoothSocket listen thread finished
,07-27 11:51:11.664  3011  3185 D bt_vendor: op for 7
07-27 11:51:11.664  3011  3185 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:11.664  1188  1188 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 11:51:11.664  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:11.664  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 11:51:11.664   771  1673 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:11.664  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:51:11.674  1892  5066 V NativeCrypto: Read error: ssl=0xaf55fe00: I/O error during system call, Connection timed out
07-27 11:51:11.674  3011  3185 D bt_vendor: op for 7
07-27 11:51:11.674  3011  3185 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:11.674  1892  5066 V NativeCrypto: SSL shutdown failed: ssl=0xaf55fe00: I/O error during system call, Broken pipe
,07-27 11:51:11.674   771  1702 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:11.674  3011  3185 D bt_vendor: op for 7
07-27 11:51:11.674  3011  3185 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:11.674  3011  3185 D bt_vendor: op for 7
07-27 11:51:11.674  3011  3185 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:11.674  1312  1312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-27 11:51:11.674   771  3075 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-27 11:51:11.674   771  1150 E ConnectivityService: updateNetworkInfo()
07-27 11:51:11.674   771  1150 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-27 11:51:11.674   771  3075 D ActivityManager: caller:android.app.ApplicationThreadProxy@1624a482, r.packageName :com.android.settings
07-27 11:51:11.674   771  1150 E ConnectivityService: updateNetworkInfo()
07-27 11:51:11.674   771  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
07-27 11:51:11.674  3011  3185 D bt_vendor: op for 7
07-27 11:51:11.674  3011  3185 D bt_upio : BT_WAKE is asserted already
07-27 11:51:11.674   771  1150 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,07-27 11:51:11.684  3011  3185 D bt_vendor: op for 7
07-27 11:51:11.684  3011  3185 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:11.684  3011  3185 D bt_vendor: op for 7
07-27 11:51:11.684  3011  3185 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:11.684  3011  3185 D bt_vendor: op for 7
07-27 11:51:11.684  3011  3185 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:11.694  1892  5066 E GCM     : Wifi connection closed with errorCode 20
,07-27 11:51:11.694  3011  3185 D bt_vendor: op for 7
07-27 11:51:11.694  3011  3185 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:11.694   771  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 11:51:11.694   771   796 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:11.694   771   771 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-27 11:51:11.694  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 11:51:11.704  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-27 11:51:11.704  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 11:51:11.704   771  1360 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
,07-27 11:51:11.704   771  1756 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:11.704   771  1756 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
,07-27 11:51:11.704   771  1756 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
07-27 11:51:11.704   771  1756 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,07-27 11:51:11.704   771  1702 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:11.704   771  1756 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,07-27 11:51:11.704   771  1756 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-27 11:51:11.704   771  3266 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:11.704   771  1469 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:11.704  1188  1188 D StatusBar.NetworkController: applyOpen
,07-27 11:51:11.704  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 11:51:11.704   771   771 D WifiScanningService: SCAN_AVAILABLE : 1
,07-27 11:51:11.704   771   771 D RttService: SCAN_AVAILABLE : 1
07-27 11:51:11.704   771  1165 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:11.704  1188  1188 D StatusBar.NetworkController: applyOpen
,07-27 11:51:11.704   771  1166 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:11.714   771  1147 D WifiP2pService: InactiveState{ what=131204 }
07-27 11:51:11.714   771  1147 D WifiP2pService: P2pEnabledState{ what=131204 }
07-27 11:51:11.714  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:11.714  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:11.714  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:11.714  1188  1188 D StatusBar.NetworkController: applyOpen
,07-27 11:51:11.714   771  1147 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,07-27 11:51:11.714   771  1148 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-27 11:51:11.714   771  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:11.714   771  1047 D WifiDisplayAdapter: onP2pDisconnected
,07-27 11:51:11.714   771  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-27 11:51:11.714   771  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-27 11:51:11.714   771  1147 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
07-27 11:51:11.714   771   771 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,07-27 11:51:11.714   771  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
07-27 11:51:11.714   771  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-27 11:51:11.714   771  1047 D WifiDisplayController: disconnect
07-27 11:51:11.714   771  1047 D WifiDisplayController: updateConnection
07-27 11:51:11.714   771  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-27 11:51:11.714   771  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-27 11:51:11.724   771  1147 D WifiP2pService: P2pDisablingState
,07-27 11:51:11.724   771  1147 D WifiP2pService: P2pDisablingState{ what=147458 }
,07-27 11:51:11.724   771  1147 D WifiP2pService: p2p socket connection lost
07-27 11:51:11.724   771  1147 D WifiP2pService: P2pDisabledState
07-27 11:51:11.724   771  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-27 11:51:11.724  1188  1188 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,07-27 11:51:11.724   771  1047 D WifiDisplayAdapter: onP2pDisconnected
07-27 11:51:11.724   771  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-27 11:51:11.724   771  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-27 11:51:11.724   771  1148 E native  : do suspend true
07-27 11:51:11.724   771  1506 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-27 11:51:11.724  1188  1188 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-27 11:51:11.724  1312  1312 D DockEventReceiver: finishStartingService: stopping service
,07-27 11:51:11.734   771  1147 D WifiP2pService: P2pDisabledState{ what=143375 }
,07-27 11:51:11.734   771  1147 D WifiP2pService: DefaultState{ what=143375 }
,07-27 11:51:11.734  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
07-27 11:51:11.734  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 11:51:11.734  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-27 11:51:11.734   771  1458 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:11.734   771  1673 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
07-27 11:51:11.734   771  1673 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:11.734   771  1673 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:11.734   771  1673 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:11.734   771  1673 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:11.764   297  1060 D CommandListener: Clearing all IP addresses on wlan0
07-27 11:51:11.764   771  1150 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
07-27 11:51:11.764   771  1045 D EntConnectivity: Not allowed due to - mEnabled false
07-27 11:51:11.764   771  1150 D ConnectivityService: calling update connectivity
07-27 11:51:11.764   771  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:11.764   771  1756 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
07-27 11:51:11.764   771  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:11.764   771  1756 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
07-27 11:51:11.764   771  1150 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:11.764   771  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 11:51:11.764   771  1756 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:11.764   771  1150 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:11.764   771  1756 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:11.764   771  1150 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
07-27 11:51:11.764   771  1756 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-27 11:51:11.764   771  1150 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:11.764  1188  1597 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-27 11:51:11.764   771  1150 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:11.764  1427  1427 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:11.764  4499  7406 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,07-27 11:51:11.764   771  1150 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
07-27 11:51:11.764   771  1150 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
07-27 11:51:11.764   771  1150 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,07-27 11:51:11.784  7678  7678 E Zygote  : MountEmulatedStorage()
07-27 11:51:11.784  7678  7678 E Zygote  : v2
07-27 11:51:11.784  7678  7678 I libpersona: KNOX_SDCARD checking this for 10140
07-27 11:51:11.784  7678  7678 I libpersona: KNOX_SDCARD not a persona
,07-27 11:51:11.794   771  1673 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7678 uid=10140 gids={50140, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,07-27 11:51:11.794  7678  7678 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 11:51:11.794   771  1150 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:51:11.794  7678  7678 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 11:51:11.794   771   771 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 11:51:11.794   771  1151 D Tethering: MasterInitialState.processMessage what=3
07-27 11:51:11.794   771  1150 E ConnectivityService: updateNetworkInfo()
07-27 11:51:11.794  7678  7678 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
07-27 11:51:11.794   771  1150 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:51:11.794   771  1150 E ConnectivityService: updateNetworkInfo()
07-27 11:51:11.794   771  1145 V NetworkStats: updateIfacesLocked()
07-27 11:51:11.794   771  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 11:51:11.794   771  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
07-27 11:51:11.794   771  1145 V NetworkStats: performPollLocked(flags=0x1)
07-27 11:51:11.794   771  1150 E ConnectivityService: EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
07-27 11:51:11.794   771  1152 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-27 11:51:11.794   771  1152 D SmartBondingService: getSBEnabled() enabled =false
07-27 11:51:11.794   771  1152 D SmartBondingService: getSBEnabled() enabled =false
07-27 11:51:11.794  1188  1188 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-27 11:51:11.794  1188  1188 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-27 11:51:11.794  1188  1188 D StatusBar.NetworkController: updateDataNetType()
07-27 11:51:11.794  1188  1188 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
07-27 11:51:11.794  1188  1188 E StatusBar.NetworkController: updateLTEICONDataNetType:0
07-27 11:51:11.794   771  1152 D SmartBondingService: getSBEnabled() enabled =false
07-27 11:51:11.794  1279  1279 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
07-27 11:51:11.794   771  1145 D NetworkStatsFactory: UpdateStatsForKnox
07-27 11:51:11.794   771  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:11.794   771  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 11:51:11.794   771  1148 D SecContentProvider2: mCursor = null
,07-27 11:51:11.794   771  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 11:51:11.804   771  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 11:51:11.804   771  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 11:51:11.804   771  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 11:51:11.804   771  1146 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
07-27 11:51:11.804   771   771 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-27 11:51:11.804   771  1152 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-27 11:51:11.804   771   771 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:51:11.804  1188  1188 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-27 11:51:11.804  1188  1188 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,07-27 11:51:11.804   771  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-27 11:51:11.804  1188  1188 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,07-27 11:51:11.804  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 11:51:11.804  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-27 11:51:11.804  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:11.804  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:11.804  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:11.804  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:11.804  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:11.804  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:11.804  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:11.804  1188  1188 D StatusBar.NetworkController: applyOpen
,07-27 11:51:11.804  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 11:51:11.804  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 11:51:11.804  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 11:51:11.804  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-27 11:51:11.804   771  1145 V NetworkStats: performPollLocked() took 15ms
07-27 11:51:11.804  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:11.804  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:11.804  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:11.804  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:11.804  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:11.804  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:11.804  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:11.804  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:11.804   771  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 11:51:11.804  1188  1188 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 11:51:11.804  1188  1188 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,07-27 11:51:11.814  1188  1601 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-27 11:51:11.814  1188  1188 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:51:11.814  1188  1188 D HotspotTile: onReceive : 0, 0
,07-27 11:51:11.814   771   796 I AudioService: getStreamVolume 3 index 0
,07-27 11:51:11.814  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:51:11.814  7570  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:11.814  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:11.814  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:11.814  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:11.814  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:51:11.814  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:51:11.814  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:11.814  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:11.814  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:51:11.814  7570  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:11.814  7570  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:51:11.814   771  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 11:51:11.814   771  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 11:51:11.814  7570  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:11.814  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:11.814  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:11.814  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:11.814  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:51:11.814  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:51:11.814  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:11.814  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:11.814  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:51:11.814  7570  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 11:51:11.814  7570  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:51:11.834  7678  7678 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:11.834  7678  7678 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:11.844  1279  1279 I wpa_supplicant: Blacklist: Clear (all) 
,07-27 11:51:11.844  3011  3181 W bt-l2cap: btif_in_execute_service_request : 25 disabled
07-27 11:51:11.844  3011  3181 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:51:11.844  3011  3181 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 11:51:11.844  3011  3181 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:51:11.844  3011  3181 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:51:11.844  3011  3181 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 11:51:11.844  3011  3181 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:51:11.844  3011  3181 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:51:11.844  3011  3181 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 11:51:11.844  3011  3181 W bt-btif : ag scb idx 1 not allocated
07-27 11:51:11.844  3011  3181 W bt-btif : ag scb idx 2 not allocated
07-27 11:51:11.844  3011  3181 E bt-btif : BTA AG is already disabled, ignoring ...
,07-27 11:51:11.844  3011  3185 D bt_vendor: op for 6
,07-27 11:51:11.844  3011  3185 D bt_vendor: op for 7
07-27 11:51:11.844  3011  3185 D bt_upio : BT_WAKE is asserted already
07-27 11:51:11.844  3011  3189 D bt_userial: RX termination
07-27 11:51:11.844  3011  3189 W bt_userial: select_read return size <=0:-1, exiting userial_read_thread
07-27 11:51:11.844  3011  3189 D bt_userial: Leaving userial_read_thread()
07-27 11:51:11.844  3011  3097 D bt_userial: userial_close_reader Joined userial reader thread: 0
,07-27 11:51:11.844  3011  3185 D bt_vendor: op for 9
07-27 11:51:11.844  3011  3185 D bt_hwcfg: hw_epilog_process
07-27 11:51:11.844  3011  3097 D bt_vendor: op for 4
07-27 11:51:11.844  3011  3097 I bt_userial_vendor: device fd = 65 close
,07-27 11:51:11.844  3011  3097 D bt_vendor: op for 0
07-27 11:51:11.844  3011  3097 D bt_upio : upio_set_bluetooth_power(on: 0)
07-27 11:51:11.844  3011  3097 D bt_upio : is_emulator_context : 0
07-27 11:51:11.844  3011  3097 D bt_upio : is_rfkill_disabled ? [0]
,07-27 11:51:11.854  3011  3097 D bt_vendor: cleanup
,07-27 11:51:11.854  3011  3181 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,07-27 11:51:11.854  3011  3097 I GKI_LINUX: GKI_exit_task 0 done
07-27 11:51:11.854  3011  3097 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,07-27 11:51:11.854  3011  3093 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-27 11:51:11.854  3011  3093 D BtConfig.SecureMode: isSecureModeOn:false
07-27 11:51:11.854  7678  7678 D ResourcesManager: creating new AssetManager and set to /system/app/Maps/Maps.apk
,07-27 11:51:11.854  3011  3093 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
07-27 11:51:11.854  3011  3093 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
07-27 11:51:11.854  3011  3093 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-27 11:51:11.854  1279  1279 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-27 11:51:11.854  3011  3093 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,07-27 11:51:11.854  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-27 11:51:11.854  1279  1279 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
07-27 11:51:11.854  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-27 11:51:11.864  1279  1279 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
,07-27 11:51:11.864  1279  1279 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=0 BSSID=F4.99.3E SSID=4E47373030
07-27 11:51:11.864  1279  1279 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-27 11:51:11.864   771  1469 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 11:51:11.864   771  1469 D ActivityManager: caller:android.app.ApplicationThreadProxy@337c86ce, r.packageName :com.android.bluetooth
,07-27 11:51:11.864  3011  3093 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
07-27 11:51:11.864  3011  3093 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-27 11:51:11.864  3011  3011 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-27 11:51:11.864  3011  3093 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
07-27 11:51:11.864  3011  3011 D BtGatt.GattService: Received stop request...Stopping profile...
07-27 11:51:11.864  3011  3011 D BtGatt.GattService: stop()
07-27 11:51:11.864  3011  3011 D BtGatt.AdvertiseManager: advertise clients cleared
,07-27 11:51:11.864   771   794 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 11:51:11.864   771   794 D ActivityManager: caller:android.app.ApplicationThreadProxy@2e6c59ef, r.packageName :com.android.bluetooth
,07-27 11:51:11.864  3011  3093 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
07-27 11:51:11.864  3011  3093 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-27 11:51:11.864  3011  3093 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
07-27 11:51:11.864  3011  3011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd5832f
,07-27 11:51:11.864   771  1360 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 11:51:11.864  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-27 11:51:11.864   771  1360 D ActivityManager: caller:android.app.ApplicationThreadProxy@5634cfc, r.packageName :com.android.bluetooth
,07-27 11:51:11.864  3011  3093 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
07-27 11:51:11.864  3011  3093 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-27 11:51:11.864  3011  3011 D HeadsetService: Received stop request...Stopping profile...
,07-27 11:51:11.864  3011  3011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd5832f
,07-27 11:51:11.874   771   771 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,07-27 11:51:11.874  3011  3093 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-27 11:51:11.874  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-27 11:51:11.874   771  1360 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 11:51:11.874   771  1360 D ActivityManager: caller:android.app.ApplicationThreadProxy@13a4bf85, r.packageName :com.android.bluetooth
,07-27 11:51:11.874  1312  1312 D HeadsetProfile: Bluetooth service disconnected
07-27 11:51:11.874  3011  3093 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
07-27 11:51:11.874  3011  3093 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-27 11:51:11.874  3011  3093 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-27 11:51:11.874   771  1506 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 11:51:11.874   771  1506 D ActivityManager: caller:android.app.ApplicationThreadProxy@355e41da, r.packageName :com.android.bluetooth
07-27 11:51:11.874  3011  3093 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
07-27 11:51:11.874  3011  3093 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-27 11:51:11.874  3011  3093 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-27 11:51:11.874  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-27 11:51:11.874   771  1318 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 11:51:11.874   771  1318 D ActivityManager: caller:android.app.ApplicationThreadProxy@39cea60b, r.packageName :com.android.bluetooth
07-27 11:51:11.874  3011  3093 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
07-27 11:51:11.874  3011  3093 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-27 11:51:11.874  3011  3093 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
07-27 11:51:11.874   771  1567 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 11:51:11.874  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-27 11:51:11.874   771  1567 D ActivityManager: caller:android.app.ApplicationThreadProxy@b163ce8, r.packageName :com.android.bluetooth
,07-27 11:51:11.874  3011  3093 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
07-27 11:51:11.874  3011  3093 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,07-27 11:51:11.874  3011  3093 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-27 11:51:11.874   771  1143 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 11:51:11.874   771  1143 D ActivityManager: caller:android.app.ApplicationThreadProxy@276cf01, r.packageName :com.android.bluetooth
,07-27 11:51:11.874  3011  3093 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-27 11:51:11.874  3011  3093 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-27 11:51:11.884  3011  3093 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-27 11:51:11.884  3011  3093 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-27 11:51:11.884  3011  3093 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,07-27 11:51:11.884  3011  3093 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-27 11:51:11.884  3011  3093 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
07-27 11:51:11.884  3011  3093 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,07-27 11:51:11.884  3011  3093 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-27 11:51:11.884  3011  3093 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
07-27 11:51:11.884  3011  3093 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-27 11:51:11.884  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-27 11:51:11.884  3011  3093 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,07-27 11:51:11.884  3011  3093 D BluetoothAdapterState: Stopping profile services that were post enabled
07-27 11:51:11.884  3011  3011 E BluetoothAdapterService(500532015): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
07-27 11:51:11.884  3011  3011 D A2dpService: Received stop request...Stopping profile...
07-27 11:51:11.884  3011  3011 V Avrcp   : doQuit
07-27 11:51:11.884  3011  3105 D A2dpStateMachine: Exit Disconnected: -1
07-27 11:51:11.884  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-27 11:51:11.894  3011  3011 D Avrcp   : Unregistering previous receiver
07-27 11:51:11.894  3011  3011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd5832f
07-27 11:51:11.894   771   771 D BluetoothA2dp: Proxy object disconnected
07-27 11:51:11.894   771   771 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-27 11:51:11.894  3011  3011 E BluetoothAdapterService(500532015): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
07-27 11:51:11.894  3011  3011 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-27 11:51:11.894  3011  3011 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
07-27 11:51:11.894  1312  1312 D BluetoothA2dp: Proxy object disconnected
07-27 11:51:11.894  1312  1312 D A2dpProfile: Bluetooth service disconnected
07-27 11:51:11.894  3206  3206 D BluetoothA2dp: Proxy object disconnected
07-27 11:51:11.894  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-27 11:51:11.894  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-27 11:51:11.894  3011  3011 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-27 11:51:11.894  3011  3011 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,07-27 11:51:11.894  3011  3011 D HidService: Received stop request...Stopping profile...
07-27 11:51:11.894  3011  3011 D HidService: Stopping Bluetooth HidService
07-27 11:51:11.894  3011  3011 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-27 11:51:11.894  3011  3011 W bt-btif : cleanup: HH disabling or disabled already, status = 0
07-27 11:51:11.894  3011  3011 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-27 11:51:11.894  3011  3011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd5832f
,07-27 11:51:11.894  1312  1312 D BluetoothInputDevice: Proxy object disconnected
07-27 11:51:11.894  1312  1312 D HidProfile: Bluetooth service disconnected
07-27 11:51:11.894  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-27 11:51:11.894  3011  3011 D HealthService: Received stop request...Stopping profile...
07-27 11:51:11.894  3011  3011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd5832f
,07-27 11:51:11.894  3011  3011 D PanService: Received stop request...Stopping profile...
07-27 11:51:11.894  3011  3011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd5832f
,07-27 11:51:11.894  3011  3011 D BluetoothMapService: Received stop request...Stopping profile...
07-27 11:51:11.894   771   771 D BluetoothPan: BluetoothPAN Proxy object disconnected
,07-27 11:51:11.904  1312  1312 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-27 11:51:11.904  1312  1312 D PanProfile: Bluetooth service disconnected
,07-27 11:51:11.904  3011  3011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd5832f
,07-27 11:51:11.904  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-27 11:51:11.904  3011  3011 D SapService: Received stop request...Stopping profile...
,07-27 11:51:11.904  3011  3011 D SapService: Stopping Bluetooth SapService
07-27 11:51:11.904  3011  3011 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd5832f
,07-27 11:51:11.904  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-27 11:51:11.904  1312  1312 D BluetoothMap: Proxy object disconnected
07-27 11:51:11.904  1312  1312 D MapProfile: Bluetooth service disconnected
,07-27 11:51:11.904  1312  1312 D Bluetoothsap: BluetoothSAP Proxy object disconnected
07-27 11:51:11.904  3011  3011 E BluetoothAdapterService(500532015): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
07-27 11:51:11.904  1312  1312 D SapProfile: Bluetooth service disconnected
07-27 11:51:11.904  3011  3011 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-27 11:51:11.904  3011  3011 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
07-27 11:51:11.904  3011  3011 D BluetoothA2dp: Proxy object disconnected
07-27 11:51:11.904  3011  3011 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,07-27 11:51:11.904  3011  3106 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-27 11:51:11.904  3011  3011 I GKI_LINUX: GKI_exit_task 2 done
07-27 11:51:11.904  3011  3011 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-27 11:51:11.904  1427  1427 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-27 11:51:11.904  3011  3011 V Avrcp   : cleanup
,07-27 11:51:11.904  3011  3011 E BluetoothAdapterService(500532015): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
07-27 11:51:11.904  3011  3011 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 11:51:11.904  3011  3011 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-27 11:51:11.904  3011  3011 E BluetoothAdapterService(500532015): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
07-27 11:51:11.904  3011  3011 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 11:51:11.904  3011  3011 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-27 11:51:11.904  3011  3011 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-27 11:51:11.904  3011  3011 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,07-27 11:51:11.904  3011  3011 E BluetoothAdapterService(500532015): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
07-27 11:51:11.904  3011  3011 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 11:51:11.904  3011  3011 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-27 11:51:11.904  3011  3011 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-27 11:51:11.904  3011  3011 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-27 11:51:11.904  3011  3011 E BluetoothAdapterService(500532015): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
07-27 11:51:11.904  3011  3011 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-27 11:51:11.904  3011  3011 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
07-27 11:51:11.904  3011  3011 E BluetoothAdapterService(500532015): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
07-27 11:51:11.904  3011  3093 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
07-27 11:51:11.904  3011  3093 D BluetoothAdapterProperties: Setting state to 10
07-27 11:51:11.904  3011  3093 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-27 11:51:11.904  3011  3093 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 11:51:11.904  3011  3093 D BluetoothAdapterService: updateAdapterState state is 10
07-27 11:51:11.904  3011  3011 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
07-27 11:51:11.904  3011  3011 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,07-27 11:51:11.914  3011  3093 D BluetoothAdapterService: Autoconnection is available 
07-27 11:51:11.914  3011  3093 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
07-27 11:51:11.914  3011  3093 I BluetoothAdapterState: Entering OffState
,07-27 11:51:11.914  1312  1340 D BluetoothMap: onBluetoothStateChange: up=false
,07-27 11:51:11.914   771  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-27 11:51:11.914  1312  1326 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-27 11:51:11.914  3206  3217 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-27 11:51:11.914  1312  1339 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-27 11:51:11.924  1312  1340 D BluetoothPbap: onBluetoothStateChange: up=false
,07-27 11:51:11.924  1312  1326 D Bluetoothsap: onBluetoothStateChange: up=false
07-27 11:51:11.924  1312  1326 D Bluetoothsap: Unbinding service...
,07-27 11:51:11.924  3011  3366 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-27 11:51:11.924   771  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 12 receivers.
,07-27 11:51:11.924   771  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,07-27 11:51:11.924   771   771 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:11.924   771   771 I InputMethodManagerService: [BT Setting State] State =10
07-27 11:51:11.924   771   771 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-27 11:51:11.924  3011  3097 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,07-27 11:51:11.934  1279  1279 I wpa_supplicant: Blacklist: Clear (all) 
,07-27 11:51:11.934  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:11.934  3011  3011 I GKI_LINUX: GKI_exit_task 1 done
07-27 11:51:11.934  3011  3011 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,07-27 11:51:11.934  1188  1188 D BluetoothAdapter: 375652811: getState() :  mService = null. Returning STATE_OFF
07-27 11:51:11.934   771  3075 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-27 11:51:11.934  1188  1188 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:11.934   771  3075 D ActivityManager: caller:android.app.ApplicationThreadProxy@1b6ea1a6, r.packageName :com.google.android.gms
07-27 11:51:11.934  1188  1188 D BluetoothAdapter: 375652811: getState() :  mService = null. Returning STATE_OFF
07-27 11:51:11.934  1188  1188 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-27 11:51:11.934  1188  1188 D BluetoothAdapter: 375652811: getState() :  mService = null. Returning STATE_OFF
07-27 11:51:11.934   771  1360 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-27 11:51:11.934  1188  1601 D BluetoothAdapter: 375652811: getState() :  mService = null. Returning STATE_OFF
07-27 11:51:11.934  1188  1601 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
07-27 11:51:11.934  1188  1601 D BluetoothAdapter: 375652811: getState() :  mService = null. Returning STATE_OFF
,07-27 11:51:11.934  1892  2393 D BluetoothAdapter: 34077501: getState() :  mService = null. Returning STATE_OFF
07-27 11:51:11.934  1892  2393 D BluetoothAdapter: 34077501: getState() :  mService = null. Returning STATE_OFF
07-27 11:51:11.934  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:11.934  3011  3011 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-27 11:51:11.934   771  1567 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
07-27 11:51:11.934  1748  1748 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
07-27 11:51:11.934  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:11.934  1188  1188 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-27 11:51:11.934  3011  3011 I art     : System.exit called, status: 0
07-27 11:51:11.934  3011  3011 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-27 11:51:11.974   771  1318 I ActivityManager: Process com.android.bluetooth (pid 3011)(adj 0) has died(192,1568)
,07-27 11:51:12.084   771  1702 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,07-27 11:51:12.084  1892  1892 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 11:51:12.084  1892  1892 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-27 11:51:12.104   771  1151 D Tethering: InitialState.processMessage what=4
07-27 11:51:12.104  1279  1279 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-27 11:51:12.104   771  1151 E Tethering: No numeric data
07-27 11:51:12.104   771  1151 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-27 11:51:12.104   771  1145 V NetworkStats: performPollLocked(flags=0x1)
07-27 11:51:12.104  1188  1188 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-27 11:51:12.104  1188  1188 D HotspotTile: updateTetherState():false, false
07-27 11:51:12.104   771  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 11:51:12.104   771  1145 D NetworkStatsFactory: UpdateStatsForKnox
07-27 11:51:12.104   771  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:12.104   771  1145 V NetworkStats: performPollLocked() took 4ms
,07-27 11:51:12.104   771  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 11:51:12.114   771  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 11:51:12.114   771  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 11:51:12.114   771  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,07-27 11:51:12.114   771  1148 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-27 11:51:12.114   771   771 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:51:12.114   771  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-27 11:51:12.114  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:51:12.114  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 11:51:12.114  1892  2393 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:12.114  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:12.114  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-27 11:51:12.114  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:12.114  1188  1188 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:51:12.114  1188  1188 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
07-27 11:51:12.114  1188  1188 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 11:51:12.114  1188  1601 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-27 11:51:12.114  1188  1188 D HotspotTile: onReceive : 1, 0
,07-27 11:51:12.134  7678  7678 D StrictMode: StrictMode policy violation; ~duration=189 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 11:51:12.134  7678  7678 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 11:51:12.134  7678  7678 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-27 11:51:12.134  7678  7678 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
07-27 11:51:12.134  7678  7678 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
07-27 11:51:12.134  7678  7678 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
07-27 11:51:12.134  7678  7678 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
07-27 11:51:12.134  7678  7678 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
07-27 11:51:12.134  7678  7678 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
07-27 11:51:12.134  7678  7678 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
07-27 11:51:12.134  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
07-27 11:51:12.134  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 11:51:12.134  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 11:51:12.134  7678  7678 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 11:51:12.134  7678  7678 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 11:51:12.134  7678  7678 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 11:51:12.134  7678  7678 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 11:51:12.134  7678  7678 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:51:12.134  7678  7678 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 11:51:12.134  7678  7678 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 11:51:12.134  7678  7678 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:51:12.134  7678  7678 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 11:51:12.134  7678  7678 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 11:51:12.134  7678  7678 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 11:51:12.144  7678  7678 D StrictMode: StrictMode policy violation; ~duration=178 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 11:51:12.144  7678  7678 D StrictMode: StrictMode policy violation; ~duration=131 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.io.File.doAccess(File.java:283)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.io.File.exists(File.java:363)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1319)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityTh,read.main(ActivityThread.java:5938)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 11:51:12.144  7678  7678 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 11:51:12.144  7678  7678 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 11:51:12.144  7678  7678 D StrictMode: StrictMode policy violation; ~duration=126 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.r.k.c(PG:1187)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.r.v.a(PG:1206)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.r.y.a(PG:2233)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.r.e.b(PG:170)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.r.e.b(PG:13188)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 11:51:12.144  7678  7678 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.r.k.c(PG:1187)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.r.k.b(PG:14147)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.r.k.c(PG:583)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.r.v.a(PG:1206)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.r.y.a(PG:2233)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.r.e.b(PG:170)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.r.e.b(PG:13188)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 11:51:12.144  7678  7678 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.io.File.doAccess(File.java:283)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.io.File.exists(File.java:363)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1485)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 11:51:12.144  7678  7678 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 11:51:12.144   771  1673 I ActivityManager: Killing 6742:com.sec.esdk.elm/u0a116 (adj 15): emptyCount ##41
07-27 11:51:12.144  1892  1892 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-27 11:51:12.144  1892  1892 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
07-27 11:51:12.144   771  1114 V AlarmManager: waitForAlarm result :4
07-27 11:51:12.144   771  1458 D ActivityManager: startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
07-27 11:51:12.154   771  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:12.154   771  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:12.154   771  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:12.154   771  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:12.194   771  1143 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-27 11:51:12.194   771  1143 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4315, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-27 11:51:12.194   771  1143 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 11:51:12.194   771  1143 D BatteryService: stay LED for fully charged
07-27 11:51:12.194   771   771 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 11:51:12.194  7722  7722 E Zygote  : MountEmulatedStorage()
07-27 11:51:12.194  7722  7722 E Zygote  : v2
07-27 11:51:12.194  7722  7722 I libpersona: KNOX_SDCARD checking this for 10038
07-27 11:51:12.194  7722  7722 I libpersona: KNOX_SDCARD not a persona
07-27 11:51:12.194  7678  7719 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
07-27 11:51:12.204   771  1458 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7722 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,07-27 11:51:12.214   771   771 I MotionRecognitionService: Plugged
07-27 11:51:12.214   771   771 I MotionRecognitionService: setPowerConnected  = true
,07-27 11:51:12.214   332   332 I art     : Explicit concurrent mark sweep GC freed 8781(373KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 581us total 13.398ms
,07-27 11:51:12.224  7722  7722 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 11:51:12.224  7722  7722 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 11:51:12.224  1188  1188 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-27 11:51:12.224  7722  7722 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
07-27 11:51:12.224  1188  1188 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-27 11:51:12.224  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 11:51:12.224  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 11:51:12.224  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 11:51:12.224  1188  1188 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
07-27 11:51:12.224  1188  1188 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 11:51:12.224  1188  1188 D KeyguardUpdateMonitor: handleTimeUpdate
,07-27 11:51:12.224  1188  1188 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
07-27 11:51:12.224  1188  1188 I KeyguardEffectViewController: *** don't update sliding image ***
,07-27 11:51:12.224   332   332 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 272us total 11.125ms
,07-27 11:51:12.234   332   332 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 272us total 9.840ms
,07-27 11:51:12.244  7722  7722 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:12.244  7722  7722 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:12.264  1188  1188 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-27 11:51:12.264  1188  1188 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-27 11:51:12.264  7722  7722 D ResourcesManager: creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,07-27 11:51:12.274  7722  7722 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,07-27 11:51:12.294   771  1150 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:51:12.294   771   978 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:51:12.294   771   978 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:12.294   771   771 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:51:12.294   771   771 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:12.294  1487  1487 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-27 11:51:12.294   771   771 I ApplicationPolicy: updateDataUsageMap
,07-27 11:51:12.294   771  1469 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:12.294   771  1152 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-27 11:51:12.294   771  1152 D SmartBondingService: getSBEnabled() enabled =false
07-27 11:51:12.294   771  1152 D SmartBondingService: getSBEnabled() enabled =false
07-27 11:51:12.294   771  1152 D SmartBondingService: getSBEnabled() enabled =false
,07-27 11:51:12.304   771   796 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:12.304   771  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-27 11:51:12.304  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:12.314  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:12.314   771  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,07-27 11:51:12.324  1892  2510 I art     : Explicit concurrent mark sweep GC freed 82537(4MB) AllocSpace objects, 80(3MB) LOS objects, 40% free, 23MB/39MB, paused 704us total 54.798ms
,07-27 11:51:12.404  7722  7722 I VlingoApplication: VlingoApplication appVersion ='11.2.2.0.37791', ro.csc.sales_code=XEO
,07-27 11:51:12.464  7722  7722 D BluetoothAdapter: 643818617: getState() :  mService = null. Returning STATE_OFF
,07-27 11:51:12.474  7722  7722 D BluetoothAdapter: 643818617: getState() :  mService = null. Returning STATE_OFF
07-27 11:51:12.474  7722  7722 D BluetoothAdapter: 643818617: getState() :  mService = null. Returning STATE_OFF
,07-27 11:51:12.474  7722  7722 D BluetoothAdapter: 643818617: getState() :  mService = null. Returning STATE_OFF
07-27 11:51:12.474  7722  7722 D BluetoothAdapter: 643818617: getState() :  mService = null. Returning STATE_OFF
07-27 11:51:12.474  7722  7722 D BluetoothAdapter: 643818617: getState() :  mService = null. Returning STATE_OFF
,07-27 11:51:12.514  7722  7722 E BluetoothHeadset: BTStateChangeCB is registed
,07-27 11:51:12.514   771  1469 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 11:51:12.514  7722  7722 E BluetoothHeadset: BluetoothHeadset service is binded
,07-27 11:51:12.514   771  1360 I ActivityManager: Killing 5773:com.android.calendar/u0a172 (adj 15): emptyCount ##41
,07-27 11:51:12.514  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-27 11:51:12.514   771  1702 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:12.514  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-27 11:51:12.514  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-27 11:51:12.514   771   794 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-27 11:51:12.514  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-27 11:51:12.514  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 11:51:12.514  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-27 11:51:12.514  1312  2825 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 11:51:12.524   771  3266 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:12.524  7193  7193 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-27 11:51:12.534   771  1360 D SettingsProvider: name = driving_mode_on
07-27 11:51:12.534   771  1360 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:12.534   771  1469 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
07-27 11:51:12.534   771  1360 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:12.534   771  1360 D SettingsProvider: selectionArgs: false
07-27 11:51:12.534   771  1360 D SettingsProvider: selectionArgs: 10038
07-27 11:51:12.534   771  1360 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:12.534   771  1360 D SettingsProvider: ret = -1
,07-27 11:51:12.534   771  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:12.534   771  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:12.534   771  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:12.534   771  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:12.534  7722  7722 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,07-27 11:51:12.624  7750  7750 E Zygote  : MountEmulatedStorage()
07-27 11:51:12.624  7750  7750 E Zygote  : v2
07-27 11:51:12.624  7750  7750 I libpersona: KNOX_SDCARD checking this for 10131
07-27 11:51:12.624  7750  7750 I libpersona: KNOX_SDCARD not a persona
,07-27 11:51:12.624   771  1469 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7750 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-27 11:51:12.634  7750  7750 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 11:51:12.634  7750  7750 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 11:51:12.634  7750  7750 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-27 11:51:12.654  7750  7750 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:12.654  7750  7750 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:12.664  7750  7750 D ResourcesManager: creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,07-27 11:51:12.664  7750  7750 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-27 11:51:12.854  7750  7750 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,07-27 11:51:12.864  7750  7776 I Babel   : MmsConfig: mnc/mcc: 0/0
,07-27 11:51:12.864  7750  7776 I Babel   : MmsConfig.loadMmsSettings
,07-27 11:51:12.864  7750  7776 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
07-27 11:51:12.864  7750  7776 I Babel   : MmsConfig.loadFromDatabase
,07-27 11:51:12.874  7750  7776 E Babel   : canonicalizeMccMnc: invalid mccmnc 
07-27 11:51:12.874  7750  7776 I Babel   : MmsConfig.loadFromResources
,07-27 11:51:12.884  7750  7776 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,07-27 11:51:12.884  7750  7776 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
,07-27 11:51:12.894   771  1360 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,07-27 11:51:12.894  7750  7750 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 11:51:12.924  7750  7750 I Babel_StickerModule: App launched.
,07-27 11:51:12.924  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-27 11:51:12.934  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-27 11:51:12.934   771  1567 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:12.934  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-27 11:51:12.934   771   794 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-27 11:51:12.934  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-27 11:51:12.934  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 11:51:12.934  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-27 11:51:12.934  1312  2825 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 11:51:12.934  7323  7323 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-27 11:51:12.934   771  3075 D ActivityManager: startProcessLocked calleePkgName: com.samsung.shareshot, hostingType: broadcast
,07-27 11:51:12.944   771  3075 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:12.944   771  3075 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:12.944   771  3075 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:12.944   771  3075 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:12.944   309  1502 W QCamera2Factory: getCameraInfo: E, camera_id = 0
07-27 11:51:12.944   309  1502 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
07-27 11:51:12.944   309  1502 W QCamera2Factory: getCameraInfo: X
,07-27 11:51:12.944   309  1361 W QCamera2Factory: getCameraInfo: E, camera_id = 1
07-27 11:51:12.944   309  1361 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
07-27 11:51:12.944   309  1361 W QCamera2HWI: __dbg: info->orientation : 270 rc = 0
07-27 11:51:12.944   309  1361 W QCamera2Factory: getCameraInfo: X
,07-27 11:51:12.954  7750  7750 W AudioCapabilities: Unsupported mime audio/evrc
,07-27 11:51:12.954  7750  7750 W AudioCapabilities: Unsupported mime audio/qcelp
,07-27 11:51:12.954  7750  7750 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-27 11:51:12.954   304   304 E SMD     : DCD ON
,07-27 11:51:12.964  7750  7750 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,07-27 11:51:12.964  7750  7750 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,07-27 11:51:12.964  7750  7750 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,07-27 11:51:12.964  7750  7750 W AudioCapabilities: Unsupported mime audio/x-ima
,07-27 11:51:12.964  7750  7750 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,07-27 11:51:12.964  7750  7750 W AudioCapabilities: Unsupported mime audio/qcelp
,07-27 11:51:12.964  7750  7750 W AudioCapabilities: Unsupported mime audio/evrc
,07-27 11:51:12.974  7750  7750 W VideoCapabilities: Unsupported mime video/wvc1
,07-27 11:51:12.974  7750  7750 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-27 11:51:12.974  7782  7782 E Zygote  : MountEmulatedStorage()
07-27 11:51:12.974  7782  7782 I libpersona: KNOX_SDCARD checking this for 10192
07-27 11:51:12.974  7782  7782 E Zygote  : v2
07-27 11:51:12.974  7782  7782 I libpersona: KNOX_SDCARD not a persona
,07-27 11:51:12.984   771  3075 I ActivityManager: Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=7782 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 11:51:13.024  7782  7782 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 11:51:13.024  7782  7782 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 11:51:13.024  7750  7750 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,07-27 11:51:13.024  7782  7782 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 11:51:13.024  7750  7750 W VideoCapabilities: Unsupported mime video/wvc1
,07-27 11:51:13.024  7750  7750 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-27 11:51:13.024  7750  7750 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,07-27 11:51:13.034  7750  7750 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,07-27 11:51:13.034  7750  7750 W VideoCapabilities: Unsupported mime video/mp43
,07-27 11:51:13.044  7750  7750 W VideoCapabilities: Unsupported mime video/sorenson
,07-27 11:51:13.044  7750  7750 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-27 11:51:13.054  7782  7782 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:13.054  7782  7782 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:13.064  7750  7750 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-27 11:51:13.064  7782  7782 D ResourcesManager: creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,07-27 11:51:13.084  7782  7782 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-27 11:51:13.084  7782  7782 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,07-27 11:51:13.084  7782  7782 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-27 11:51:13.084   771  1702 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,07-27 11:51:13.084  7782  7782 D WifiDirectBR: stopServiceTest : false
,07-27 11:51:13.084  7782  7782 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-27 11:51:13.094   771  1673 I ActivityManager: Killing 6814:com.qualcomm.timeservice/1000 (adj 15): emptyCount ##41
,07-27 11:51:13.094  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-27 11:51:13.094  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-27 11:51:13.094   771  1143 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:13.094  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-27 11:51:13.094   771  1458 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-27 11:51:13.094  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-27 11:51:13.094  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 11:51:13.094  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-27 11:51:13.094  1312  2825 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 11:51:13.104   771  1673 I ActivityManager: Killing 6336:com.android.providers.calendar/u0a51 (adj 15): emptyCount ##41
,07-27 11:51:13.104   771  3075 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:13.114  7193  7193 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-27 11:51:13.124  7193  7193 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-27 11:51:13.134   771  1567 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:13.134  6793  6793 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 11:51:13.134  6793  6793 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 11:51:13.134  6793  6793 D SecurityLogAgent: StateMachine : Current State = 1
,07-27 11:51:13.134  6793  6793 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 11:51:13.144  1312  1312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-27 11:51:13.144   771  1310 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-27 11:51:13.144   771  1310 D ActivityManager: caller:android.app.ApplicationThreadProxy@1f2afeb7, r.packageName :com.android.settings
,07-27 11:51:13.154  1312  1312 D DockEventReceiver: finishStartingService: stopping service
,07-27 11:51:13.154  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
,07-27 11:51:13.154   771  1310 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,07-27 11:51:13.154   771  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:13.154   771  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:13.154   771  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:13.154   771  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:13.234  7803  7803 E Zygote  : MountEmulatedStorage()
,07-27 11:51:13.234  7803  7803 E Zygote  : v2
07-27 11:51:13.234  7803  7803 I libpersona: KNOX_SDCARD checking this for 1002
07-27 11:51:13.234  7803  7803 I libpersona: KNOX_SDCARD not a persona
,07-27 11:51:13.244  7803  7803 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 11:51:13.244   771  1310 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7803 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
07-27 11:51:13.244  7803  7803 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 11:51:13.244  7803  7803 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 11:51:13.264  7803  7803 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:13.264  7803  7803 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:13.274  7803  7803 D ResourcesManager: creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,07-27 11:51:13.284  7803  7803 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,07-27 11:51:13.284  7803  7803 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-27 11:51:13.304  7803  7803 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,07-27 11:51:13.324  7803  7803 D BtSettings.ProfileConfig: Adding GattService
,07-27 11:51:13.324  7803  7803 D BtSettings.ProfileConfig: Adding HeadsetService
,07-27 11:51:13.324  7803  7803 D BtSettings.ProfileConfig: Adding A2dpService
07-27 11:51:13.324  7803  7803 D BtSettings.ProfileConfig: Adding HidService
,07-27 11:51:13.324  7803  7803 D BtSettings.ProfileConfig: Adding HealthService
,07-27 11:51:13.324  7803  7803 D BtSettings.ProfileConfig: Adding PanService
07-27 11:51:13.324  7803  7803 D BtSettings.ProfileConfig: Adding BluetoothMapService
,07-27 11:51:13.334  7803  7803 D BtSettings.ProfileConfig: Adding SapService
07-27 11:51:13.334  7803  7803 D BtSettings.ProfileConfig: Adding HeadsetClientService
,07-27 11:51:13.334  7803  7803 D BtSettings.ProfileConfig: Adding A2dpSinkService
07-27 11:51:13.334  7803  7803 D BtSettings.ProfileConfig: Adding SapClientService
,07-27 11:51:13.334  7803  7803 D BtSettings.ProfileConfig: Adding HidDevService
07-27 11:51:13.334  7803  7803 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,07-27 11:51:13.334   771   794 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
07-27 11:51:13.334   771   794 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:13.334   771   794 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:13.334   771   794 D SettingsProvider: selectionArgs: false
07-27 11:51:13.334   771   794 D SettingsProvider: selectionArgs: 1002
07-27 11:51:13.334   771   794 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:13.334   771   794 D SettingsProvider: ret = -1
,07-27 11:51:13.334   771  1360 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
07-27 11:51:13.334   771  1360 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:13.334   771  1360 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:13.334   771  1360 D SettingsProvider: selectionArgs: false
07-27 11:51:13.334   771  1360 D SettingsProvider: selectionArgs: 1002
07-27 11:51:13.334   771  1360 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:13.334   771  1360 D SettingsProvider: ret = -1
07-27 11:51:13.334   771  1458 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
07-27 11:51:13.334   771  1458 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:13.334   771  1458 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:13.334   771  1458 D SettingsProvider: selectionArgs: false
07-27 11:51:13.334   771  1458 D SettingsProvider: selectionArgs: 1002
07-27 11:51:13.334   771  1458 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:13.334   771  1458 D SettingsProvider: ret = -1
,07-27 11:51:13.334   771  1143 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
07-27 11:51:13.334   771  1143 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:13.334   771  1143 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:13.334   771  1143 D SettingsProvider: selectionArgs: false
07-27 11:51:13.334   771  1143 D SettingsProvider: selectionArgs: 1002
07-27 11:51:13.334   771  1143 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:13.334   771  1143 D SettingsProvider: ret = -1
,07-27 11:51:13.334   771  1567 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
07-27 11:51:13.334   771  1567 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:13.334   771  1567 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:13.334   771  1567 D SettingsProvider: selectionArgs: false
,07-27 11:51:13.334   771  1567 D SettingsProvider: selectionArgs: 1002
07-27 11:51:13.334   771  1567 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:13.334   771  1567 D SettingsProvider: ret = -1
,07-27 11:51:13.334   771  1428 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
07-27 11:51:13.334   771  1428 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:13.334   771  1428 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:13.334   771  1428 D SettingsProvider: selectionArgs: false
07-27 11:51:13.334   771  1428 D SettingsProvider: selectionArgs: 1002
07-27 11:51:13.334   771  1428 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-27 11:51:13.334   771  1428 D SettingsProvider: ret = -1
07-27 11:51:13.334   771  1469 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
07-27 11:51:13.334   771  1469 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,07-27 11:51:13.334   771  1469 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:13.334   771  1469 D SettingsProvider: selectionArgs: false
07-27 11:51:13.334   771  1469 D SettingsProvider: selectionArgs: 1002
07-27 11:51:13.334   771  1469 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:13.334   771  1469 D SettingsProvider: ret = -1
,07-27 11:51:13.344   771  3266 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
07-27 11:51:13.344   771  3266 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:13.344   771  3266 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:13.344   771  3266 D SettingsProvider: selectionArgs: false
07-27 11:51:13.344   771  3266 D SettingsProvider: selectionArgs: 1002
07-27 11:51:13.344   771  3266 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:13.344   771  3266 D SettingsProvider: ret = -1
,07-27 11:51:13.344   771  1318 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
07-27 11:51:13.344   771  1318 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:13.344   771  1318 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:13.344   771  1318 D SettingsProvider: selectionArgs: false
07-27 11:51:13.344   771  1318 D SettingsProvider: selectionArgs: 1002
07-27 11:51:13.344   771  1318 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:13.344   771  1318 D SettingsProvider: ret = -1
07-27 11:51:13.344   771  1525 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
07-27 11:51:13.344   771  1525 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:13.344   771  1525 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,07-27 11:51:13.344   771  1525 D SettingsProvider: selectionArgs: false
07-27 11:51:13.344   771  1525 D SettingsProvider: selectionArgs: 1002
07-27 11:51:13.344   771  1525 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:13.344   771  1525 D SettingsProvider: ret = -1
07-27 11:51:13.344   771  1673 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
07-27 11:51:13.344   771  1673 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:13.344   771  1673 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:13.344   771  1673 D SettingsProvider: selectionArgs: false
07-27 11:51:13.344   771  1673 D SettingsProvider: selectionArgs: 1002
,07-27 11:51:13.344   771  1673 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:13.344   771  1673 D SettingsProvider: ret = -1
07-27 11:51:13.344   771  3075 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
07-27 11:51:13.344   771  3075 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:13.344   771  3075 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:13.344   771  3075 D SettingsProvider: selectionArgs: false
07-27 11:51:13.344   771  3075 D SettingsProvider: selectionArgs: 1002
07-27 11:51:13.344   771  3075 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:13.344   771  3075 D SettingsProvider: ret = -1
,07-27 11:51:13.354   771  1702 I ActivityManager: Killing 6904:com.google.android.partnersetup/u0a19 (adj 15): emptyCount ##41
,07-27 11:51:13.354  1892  1892 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-27 11:51:13.364   771  1360 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-27 11:51:13.364   771  1360 D ActivityManager: caller:android.app.ApplicationThreadProxy@1786a58d, r.packageName :com.google.android.gms
,07-27 11:51:13.364  1892  7819 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-27 11:51:13.364  1892  1892 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-27 11:51:13.384  7193  7193 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-27 11:51:13.384   771  1318 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:13.384  6793  6793 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 11:51:13.384  6793  6793 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 11:51:13.384  6793  6793 D SecurityLogAgent: StateMachine : Current State = 1
07-27 11:51:13.384  6793  6793 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 11:51:13.394   771  1567 D ActivityManager: caller:android.app.ApplicationThreadProxy@13fcb18e, r.packageName :com.google.android.gms
,07-27 11:51:13.394  1892  7819 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-27 11:51:13.394   771  1143 D ActivityManager: startProcessLocked calleePkgName: com.blurb.checkout, hostingType: broadcast
,07-27 11:51:13.394   771  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:13.394   771  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:13.394   771  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:13.394   771  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:13.474  7821  7821 E Zygote  : MountEmulatedStorage()
07-27 11:51:13.474  7821  7821 E Zygote  : v2
07-27 11:51:13.474  7821  7821 I libpersona: KNOX_SDCARD checking this for 10096
07-27 11:51:13.474  7821  7821 I libpersona: KNOX_SDCARD not a persona
,07-27 11:51:13.484   771  1143 I ActivityManager: Start proc com.blurb.checkout for broadcast com.blurb.checkout/.RebootReceiver: pid=7821 uid=10096 gids={50096, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 11:51:13.494  7821  7821 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 11:51:13.494  7821  7821 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 11:51:13.494  7821  7821 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,07-27 11:51:13.504  7821  7821 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:13.514  7821  7821 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:13.524  7821  7821 D ResourcesManager: creating new AssetManager and set to /system/app/Blurb/Blurb.apk
,07-27 11:51:13.534   771  1360 D ActivityManager: startService callerProcessName:com.blurb.checkout, calleePkgName: com.blurb.checkout
,07-27 11:51:13.534   771  1360 D ActivityManager: caller:android.app.ApplicationThreadProxy@12c55bc, r.packageName :com.blurb.checkout
,07-27 11:51:13.534  6957  6957 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,07-27 11:51:13.534  6957  6957 I PCWCLIENTTRACE_PushUtil: sales region : global
07-27 11:51:13.534  6957  6957 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-27 11:51:13.534  6957  6957 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:13.534  6957  6957 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,07-27 11:51:13.544   771  1525 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,07-27 11:51:13.544   771  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:13.544   771  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:13.544   771  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:13.544   771  1525 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:13.584  7839  7839 E Zygote  : MountEmulatedStorage()
,07-27 11:51:13.584  7839  7839 E Zygote  : v2
07-27 11:51:13.584  7839  7839 I libpersona: KNOX_SDCARD checking this for 10144
07-27 11:51:13.584  7839  7839 I libpersona: KNOX_SDCARD not a persona
,07-27 11:51:13.594   771  1525 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7839 uid=10144 gids={50144, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 11:51:13.604  7839  7839 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 11:51:13.604  7839  7839 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 11:51:13.604  7839  7839 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-27 11:51:13.614  7839  7839 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:13.624  7839  7839 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:13.634  7839  7839 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-27 11:51:13.724  7839  7839 I MusicStore: Database version: 108
,07-27 11:51:13.734   771  3266 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-27 11:51:13.784  7839  7839 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,07-27 11:51:13.794  7839  7839 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-27 11:51:13.794  7839  7839 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-27 11:51:13.824  7839  7839 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-27 11:51:13.864  7839  7839 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-27 11:51:13.864  7839  7839 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@e2b2493: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,07-27 11:51:13.864  7839  7839 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
07-27 11:51:13.864  7839  7839 D AndroidMusic: GMSCore installation verified
,07-27 11:51:13.874   771  1360 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-27 11:51:13.884  7839  7839 I ConfigStore: Config Database version: 1
,07-27 11:51:13.924   265   544 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-27 11:51:13.924   265   544 W Vold    : Returning OperationFailed - no handler for errno 0
,07-27 11:51:13.924  7839  7839 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-27 11:51:13.924   265   544 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-27 11:51:13.924   265   544 W Vold    : Returning OperationFailed - no handler for errno 0
,07-27 11:51:13.924  7839  7839 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-27 11:51:13.924   265   544 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-27 11:51:13.924   265   544 W Vold    : Returning OperationFailed - no handler for errno 0
,07-27 11:51:13.924  7839  7839 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-27 11:51:13.934   771  1506 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-27 11:51:13.934   771  1506 D ActivityManager: caller:android.app.ApplicationThreadProxy@1e1ac09f, r.packageName :com.google.android.music
,07-27 11:51:13.944   771  1360 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-27 11:51:13.954   771  1673 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-27 11:51:13.954   771   794 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-27 11:51:13.964   771   796 I AudioService: getStreamVolume 3 index 0
,07-27 11:51:13.964  7839  7839 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,07-27 11:51:13.974  7839  7839 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,07-27 11:51:13.984   771  1360 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-27 11:51:13.984   771   794 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-27 11:51:13.994   771  1143 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-27 11:51:13.994   771  3266 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-27 11:51:14.004   771  1702 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,07-27 11:51:14.004   771  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:14.004   771  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:14.004   771  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:14.004   771  1702 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:14.034   771  1702 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7869 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 11:51:14.044  7869  7869 E Zygote  : MountEmulatedStorage()
,07-27 11:51:14.044  7869  7869 E Zygote  : v2
07-27 11:51:14.044  7869  7869 I libpersona: KNOX_SDCARD checking this for 10004
07-27 11:51:14.044  7869  7869 I libpersona: KNOX_SDCARD not a persona
,07-27 11:51:14.054  7869  7869 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 11:51:14.054  7869  7869 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 11:51:14.054  7869  7869 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 11:51:14.074  7869  7869 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:14.074  7869  7869 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:14.084   771  1673 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,07-27 11:51:14.084  7869  7869 D ResourcesManager: creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,07-27 11:51:14.094  7839  7839 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,07-27 11:51:14.094   771  1525 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-27 11:51:14.124   771  1458 I ActivityManager: Killing 6922:com.samsung.groupcast/u0a20 (adj 15): emptyCount ##41
,07-27 11:51:14.134   771  1143 I ActivityManager: Killing 6940:com.sec.android.service.health/u0a21 (adj 15): emptyCount ##41
,07-27 11:51:14.144   771  1310 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,07-27 11:51:14.144   771  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:14.144   771  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:14.144   771  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:14.144   771  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:14.184  7892  7892 E Zygote  : MountEmulatedStorage()
07-27 11:51:14.184  7892  7892 E Zygote  : v2
07-27 11:51:14.184  7892  7892 I libpersona: KNOX_SDCARD checking this for 1000
07-27 11:51:14.184  7892  7892 I libpersona: KNOX_SDCARD not a persona
,07-27 11:51:14.194   771  1310 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7892 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-27 11:51:14.204  7892  7892 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 11:51:14.204  7892  7892 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 11:51:14.204  7892  7892 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 11:51:14.224  7892  7892 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:14.224  7892  7892 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:14.234  7892  7892 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,07-27 11:51:14.264  7892  7892 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,07-27 11:51:14.274  7892  7892 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,07-27 11:51:14.384  7892  7892 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,07-27 11:51:14.394  7892  7892 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,07-27 11:51:14.394  7892  7892 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:51:14.394  7892  7892 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-27 11:51:14.454   771  1360 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,07-27 11:51:14.454   771  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:14.454   771  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:14.454   771  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:14.454   771  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:14.494  7911  7911 E Zygote  : MountEmulatedStorage()
,07-27 11:51:14.494  7911  7911 E Zygote  : v2
07-27 11:51:14.494  7911  7911 I libpersona: KNOX_SDCARD checking this for 10014
07-27 11:51:14.494  7911  7911 I libpersona: KNOX_SDCARD not a persona
,07-27 11:51:14.494   771  1360 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7911 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 11:51:14.494  7911  7911 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-27 11:51:14.494  7911  7911 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 11:51:14.494  7911  7911 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-27 11:51:14.514  7911  7911 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:14.514  7911  7911 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:14.534  7911  7911 D ResourcesManager: creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,07-27 11:51:14.584   771  1428 I ActivityManager: Killing 6768:com.android.defcontainer/u0a7 (adj 15): emptyCount ##41
,07-27 11:51:14.594  7911  7911 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,07-27 11:51:14.594  7911  7911 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,07-27 11:51:14.614  7911  7911 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,07-27 11:51:14.614   771  1360 I ActivityManager: Killing 6979:com.sec.spp.push/u0a43 (adj 15): emptyCount ##41
,07-27 11:51:14.614  4017  4017 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-27 11:51:14.624  4017  4017 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1469613074630
,07-27 11:51:14.624  4017  4017 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
07-27 11:51:14.624   771  1310 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:14.624   771  1318 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:14.624  4017  4017 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,07-27 11:51:14.634  4017  4017 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,07-27 11:51:14.634   771  1428 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.pinboard, hostingType: broadcast
,07-27 11:51:14.634   771  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:14.634   771  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:14.634   771  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:14.634   771  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:14.634  7570  7631 I WifiManager: packageName : com.test.thalitest
,07-27 11:51:14.634   771  1458 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-27 11:51:14.634   771  1458 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-27 11:51:14.634   771  1458 D SecContentProvider2: mCursor = null
,07-27 11:51:14.644   771  1458 D WifiService: setWifiEnabled: true pid=7570, uid=10079
,07-27 11:51:14.644   771  1458 W ActivityManager: Permission Denial: getCurrentUser() from pid=7570, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-27 11:51:14.644   771  1458 W WifiService: Failed getting userId using ActivityManagerNative
07-27 11:51:14.644   771  1458 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7570, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-27 11:51:14.644   771  1458 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-27 11:51:14.644   771  1458 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-27 11:51:14.644   771  1458 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-27 11:51:14.644   771  1458 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-27 11:51:14.644   771  1458 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
07-27 11:51:14.644   771  1458 D SettingsProvider: name = wifi_on
,07-27 11:51:14.654   771  1148 E WifiHW  : ##################### set firmware type 0 #####################
,07-27 11:51:14.654   297  1060 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
07-27 11:51:14.654   297  1060 I WifiHW  : module is semco
07-27 11:51:14.654   297  1060 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-27 11:51:14.654   297  1060 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-27 11:51:14.654   297  1060 E WifiHW  : TEMP_FAILURE_RETRY complete
07-27 11:51:14.654   297  1060 D SoftapController: Softap fwReload - Ok
,07-27 11:51:14.654   297  1060 D CommandListener: Setting iface cfg
07-27 11:51:14.654   297  1060 D CommandListener: Trying to bring down wlan0
,07-27 11:51:14.654   297  1060 D CommandListener: Clearing all IP addresses on wlan0
,07-27 11:51:14.654   771  1148 E WifiHW  : supplicant_name : p2p_supplicant
,07-27 11:51:14.694  7927  7927 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
,07-27 11:51:14.694  7927  7927 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-27 11:51:14.694  7927  7927 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,07-27 11:51:14.694  7927  7927 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-27 11:51:14.694  7928  7928 E Zygote  : MountEmulatedStorage()
07-27 11:51:14.694  7928  7928 E Zygote  : v2
07-27 11:51:14.694   377   377 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7927
07-27 11:51:14.694   377   377 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
,07-27 11:51:14.694  7928  7928 I libpersona: KNOX_SDCARD checking this for 10036
07-27 11:51:14.694  7927  7927 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-27 11:51:14.694  7928  7928 I libpersona: KNOX_SDCARD not a persona
07-27 11:51:14.694  7927  7927 I wpa_supplicant: ssSupport state is = 1
,07-27 11:51:14.694  7927  7927 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,07-27 11:51:14.694  7927  7927 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-27 11:51:14.694   377   377 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7927
07-27 11:51:14.694   377   377 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,07-27 11:51:14.704   771  1428 I ActivityManager: Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7928 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-27 11:51:14.704   771  1148 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-27 11:51:14.704   771   771 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:51:14.714  7928  7928 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 11:51:14.714  7928  7928 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 11:51:14.714  7928  7928 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 11:51:14.724  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:51:14.724  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 11:51:14.724  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:14.724  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,07-27 11:51:14.724   771  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-27 11:51:14.724  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:14.724  1188  1188 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 11:51:14.724  1188  1188 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,07-27 11:51:14.724  1188  1188 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 11:51:14.724  1188  1601 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-27 11:51:14.724  1188  1188 D HotspotTile: onReceive : 2, 0
,07-27 11:51:14.744  7928  7928 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:14.744  7928  7928 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:14.764  7928  7928 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,07-27 11:51:14.764  7928  7928 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-27 11:51:14.764  7928  7928 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-27 11:51:14.784  7928  7928 E Minikin : addFont failed to create font /system/fonts/SamsungSans-light.ttf
,07-27 11:51:14.804   771  1143 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:14.804   771  1310 I ActivityManager: Killing 6998:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): emptyCount ##41
,07-27 11:51:14.804   771  1310 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,07-27 11:51:14.804   771  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:14.804   771  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:14.804   771  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:14.804   771  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:14.844  7952  7952 E Zygote  : MountEmulatedStorage()
07-27 11:51:14.844  7952  7952 E Zygote  : v2
07-27 11:51:14.844  7952  7952 I libpersona: KNOX_SDCARD checking this for 10042
07-27 11:51:14.844  7952  7952 I libpersona: KNOX_SDCARD not a persona
,07-27 11:51:14.854   771  1310 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7952 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,07-27 11:51:14.894  7952  7952 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 11:51:14.894  7952  7952 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 11:51:14.894  7952  7952 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 11:51:14.904   771  3150 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 11:51:14.914  7952  7952 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:14.914  7952  7952 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:14.924  7952  7952 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,07-27 11:51:14.944  7952  7952 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,07-27 11:51:14.944   771  1567 I ActivityManager: Killing 6677:com.osp.app.signin/u0a50 (adj 15): emptyCount ##41
,07-27 11:51:14.954   771  1673 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,07-27 11:51:14.954   771  1673 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:14.954   771  1673 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:14.954   771  1673 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:14.954   771  1673 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:14.954   771  1702 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:14.964  3577  7968 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,07-27 11:51:14.964   771  1428 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:14.964  3577  7968 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,07-27 11:51:14.964  3577  7968 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,07-27 11:51:14.964  3577  7968 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,07-27 11:51:14.964  3577  7968 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,07-27 11:51:14.984   377   377 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,07-27 11:51:14.994  7969  7969 E Zygote  : MountEmulatedStorage()
07-27 11:51:14.994  7969  7969 E Zygote  : v2
07-27 11:51:14.994  7969  7969 I libpersona: KNOX_SDCARD checking this for 10043
07-27 11:51:14.994  7969  7969 I libpersona: KNOX_SDCARD not a persona
,07-27 11:51:15.004  7969  7969 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-27 11:51:15.004  7969  7969 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 11:51:15.004  7969  7969 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
07-27 11:51:15.004   771  1673 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7969 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 11:51:15.014   332   332 I art     : Explicit concurrent mark sweep GC freed 8735(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 311us total 14.079ms
,07-27 11:51:15.024   332   332 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 277us total 9.603ms
,07-27 11:51:15.034  7969  7969 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:15.034  7969  7969 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:15.044   332   332 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 280us total 10.586ms
,07-27 11:51:15.044  7969  7969 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,07-27 11:51:15.074  7969  7969 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,07-27 11:51:15.074  7969  7969 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,07-27 11:51:15.074  7969  7969 D SPPClientService: PushLog.txt file is not deleted.
,07-27 11:51:15.074  7969  7969 D SPPClientService: PushLog.txt file is not deleted.
07-27 11:51:15.074  7969  7969 D SPPClientService: ============PushLog. stop!
,07-27 11:51:15.084  7969  7969 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,07-27 11:51:15.084   771   796 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,07-27 11:51:15.084   771   796 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:15.084   771   796 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:15.084   771   796 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:15.084   771   796 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:15.124  7988  7988 E Zygote  : MountEmulatedStorage()
07-27 11:51:15.124  7988  7988 E Zygote  : v2
07-27 11:51:15.124  7988  7988 I libpersona: KNOX_SDCARD checking this for 10050
07-27 11:51:15.124  7988  7988 I libpersona: KNOX_SDCARD not a persona
,07-27 11:51:15.124   771   796 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7988 uid=10050 gids={50050, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 11:51:15.134   771   796 I ActivityManager: Killing 5649:com.android.mms/u0a55 (adj 15): emptyCount ##41
,07-27 11:51:15.134   771  1469 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,07-27 11:51:15.134   771  1469 D ActivityManager: caller:android.app.ApplicationThreadProxy@1844fa7f, r.packageName :com.sec.spp.push
,07-27 11:51:15.144  7988  7988 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 11:51:15.144  7988  7988 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 11:51:15.144  7988  7988 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,07-27 11:51:15.154  7969  7994 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,07-27 11:51:15.174  7988  7988 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:15.174  7988  7988 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:15.194  7988  7988 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,07-27 11:51:15.194   771  1673 D CountryDetector: No listener is left
,07-27 11:51:15.224  7988  7988 I SA      : [SSP] onCreated
,07-27 11:51:15.234  7927  7927 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,07-27 11:51:15.244  7988  7988 I SA      : [TPM] There is no property file
,07-27 11:51:15.244  7988  7988 I SA      : [SCU] isHaveSA() - false
,07-27 11:51:15.244  7988  7988 I SA      : [TPM] getModelProperty : null
,07-27 11:51:15.244  7988  7988 I SA      : [TPM] getCSCProperty : null
,07-27 11:51:15.254  7988  7988 I SA      : [DM] init START
,07-27 11:51:15.254  7988  7988 I SA      : [DM] This device is not a Vodafone
,07-27 11:51:15.254  7988  7988 I SA      : checkReactivationActive for LOLLIPOP
,07-27 11:51:15.254  7988  7988 I SA      : checkReactivationActive for reactiveActive
07-27 11:51:15.254  7988  7988 I SA      : setSupportRL : true
,07-27 11:51:15.264  7988  7988 I SA      : [SCU] isHaveSA() - false
,07-27 11:51:15.264  7988  7988 I SA      : support phone number id : false
,07-27 11:51:15.264  7988  7988 I SA      : [DM] init END
,07-27 11:51:15.264  7988  7988 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,07-27 11:51:15.274  7927  7927 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-27 11:51:15.274  7927  7927 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-27 11:51:15.274   377   377 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7927
07-27 11:51:15.274   377   377 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-27 11:51:15.274  7927  7927 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-27 11:51:15.274  7927  7927 I wpa_supplicant: ssSupport state is = 1
07-27 11:51:15.274  7927  7927 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 11:51:15.274  7927  7927 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 11:51:15.274  7927  7927 E wpa_supplicant: SIM READ ERROR
07-27 11:51:15.274  7927  7927 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 11:51:15.274  7927  7927 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 11:51:15.274  7927  7927 E wpa_supplicant: SIM READ ERROR
07-27 11:51:15.274  7927  7927 I wpa_supplicant: Blacklist: Clear (all) 
,07-27 11:51:15.274  7927  7927 I wpa_supplicant: wpa_default_ap_write_once
07-27 11:51:15.274  7927  7927 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-27 11:51:15.274  7927  7927 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 11:51:15.274  7927  7927 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
07-27 11:51:15.274  7927  7927 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 11:51:15.274  7927  7927 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-27 11:51:15.274  7927  7927 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 11:51:15.274  7988  7988 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,07-27 11:51:15.274  7988  7988 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-27 11:51:15.274  7988  7988 I SA      : [SLFUCHKMGR] constructor called
,07-27 11:51:15.284  7988  7988 I SA      : [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,07-27 11:51:15.284  7988  7988 I SA      : [OR] == isSIMCardReady false ==
,07-27 11:51:15.284  7988  7988 I SA      : [SCU] == networkStateCheck == false
07-27 11:51:15.284  7988  7988 I SA      : [OR] onReceive END
,07-27 11:51:15.284   771  3266 I ActivityManager: Killing 7026:com.sec.android.app.soundalive/u0a64 (adj 15): emptyCount ##41
,07-27 11:51:15.284   771  3266 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,07-27 11:51:15.284   771  3266 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:15.284   771  3266 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:15.284   771  3266 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:15.284   771  3266 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:15.324  8009  8009 E Zygote  : MountEmulatedStorage()
07-27 11:51:15.324  8009  8009 E Zygote  : v2
07-27 11:51:15.324  8009  8009 I libpersona: KNOX_SDCARD checking this for 10074
07-27 11:51:15.324  8009  8009 I libpersona: KNOX_SDCARD not a persona
,07-27 11:51:15.334  8009  8009 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-27 11:51:15.334  8009  8009 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 11:51:15.334  8009  8009 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 11:51:15.334   771  3266 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=8009 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,07-27 11:51:15.354  8009  8009 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:15.354  8009  8009 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:15.364  8009  8009 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,07-27 11:51:15.424  8009  8009 I sCloudBackupApp: sCloudBackupApp Version Info : 3.13.7.KK_APP
,07-27 11:51:15.424  8009  8009 I SCloudBackupReceiver: Other Intent
,07-27 11:51:15.424  7338  7338 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,07-27 11:51:15.434  7338  7338 I KnoxUsageLogPro: premStatus:2
,07-27 11:51:15.434  7338  7338 I KnoxUsageLogPro: isEulaShown : false
07-27 11:51:15.434  7338  7338 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-27 11:51:15.434   771  1310 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,07-27 11:51:15.434   771  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:15.434   771  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:15.434   771  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:15.434   771  1310 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:15.474  8025  8025 E Zygote  : MountEmulatedStorage()
07-27 11:51:15.474  8025  8025 E Zygote  : v2
07-27 11:51:15.474  8025  8025 I libpersona: KNOX_SDCARD checking this for 10104
07-27 11:51:15.474  8025  8025 I libpersona: KNOX_SDCARD not a persona
,07-27 11:51:15.484   771  1310 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8025 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 11:51:15.484   771  1310 I ActivityManager: Killing 7046:com.samsung.android.app.assistantmenu/1000 (adj 15): emptyCount ##41
,07-27 11:51:15.494  8025  8025 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 11:51:15.494  8025  8025 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 11:51:15.494  8025  8025 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,07-27 11:51:15.514  8025  8025 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:15.514  8025  8025 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:15.524  8025  8025 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,07-27 11:51:15.594   771  3266 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,07-27 11:51:15.594   771  3266 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:15.594   771  3266 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:15.594   771  3266 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:15.594   771  3266 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:15.634  8041  8041 E Zygote  : MountEmulatedStorage()
07-27 11:51:15.634  8041  8041 E Zygote  : v2
07-27 11:51:15.634  8041  8041 I libpersona: KNOX_SDCARD checking this for 10146
07-27 11:51:15.634  8041  8041 I libpersona: KNOX_SDCARD not a persona
,07-27 11:51:15.644   771  3266 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8041 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-27 11:51:15.644   771  3266 I ActivityManager: Killing 7083:com.google.android.apps.docs/u0a112 (adj 15): emptyCount ##41
,07-27 11:51:15.654  8041  8041 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 11:51:15.654  8041  8041 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 11:51:15.654  8041  8041 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-27 11:51:15.674  8041  8041 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:15.684  8041  8041 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:15.704  8041  8041 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,07-27 11:51:15.894   265   544 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
07-27 11:51:15.894   265   544 W Vold    : Returning OperationFailed - no handler for errno 0
,07-27 11:51:15.894  8041  8059 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,07-27 11:51:15.904   265   544 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
07-27 11:51:15.904   265   544 W Vold    : Returning OperationFailed - no handler for errno 0
,07-27 11:51:15.904  8041  8059 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,07-27 11:51:15.914   265   544 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
07-27 11:51:15.914   265   544 W Vold    : Returning OperationFailed - no handler for errno 0
,07-27 11:51:15.914  8041  8061 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,07-27 11:51:15.914   265   544 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
07-27 11:51:15.914   265   544 W Vold    : Returning OperationFailed - no handler for errno 0
,07-27 11:51:15.914  8041  8061 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,07-27 11:51:15.954   304   304 E SMD     : DCD ON
,07-27 11:51:16.074  8041  8041 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,07-27 11:51:16.074  8041  8041 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,07-27 11:51:16.084   771  1151 E Tethering: No numeric data
07-27 11:51:16.084   771  1151 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
07-27 11:51:16.084   771  1145 V NetworkStats: performPollLocked(flags=0x1)
07-27 11:51:16.084   771  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 11:51:16.084   771  1145 D NetworkStatsFactory: UpdateStatsForKnox
07-27 11:51:16.084   771  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:16.084  1188  1188 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-27 11:51:16.084  1188  1188 D HotspotTile: updateTetherState():false, false
,07-27 11:51:16.084   771  1145 V NetworkStats: performPollLocked() took 3ms
07-27 11:51:16.084   771  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 11:51:16.084   771  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 11:51:16.084   771  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 11:51:16.104  8041  8041 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 7408-7410)
,07-27 11:51:16.104  8041  8041 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-27 11:51:16.104  8041  8041 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {33e25e8}
,07-27 11:51:16.104  8041  8041 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-27 11:51:16.104  8041  8041 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-27 11:51:16.114  7927  7927 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,07-27 11:51:16.124  8041  8041 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-27 11:51:16.124  8041  8041 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-27 11:51:16.124  8041  8041 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-27 11:51:16.144  7927  7927 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
07-27 11:51:16.144  7927  7927 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-27 11:51:16.144  7927  7927 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-27 11:51:16.144   377   377 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7927
07-27 11:51:16.144   377   377 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-27 11:51:16.144  7927  7927 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-27 11:51:16.144  7927  7927 I wpa_supplicant: ssSupport state is = 1
07-27 11:51:16.144  7927  7927 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-27 11:51:16.144  7927  7927 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-27 11:51:16.144   377   377 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7927
07-27 11:51:16.144   377   377 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-27 11:51:16.144  7927  7927 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-27 11:51:16.144  7927  7927 I wpa_supplicant: ssSupport state is = 1
07-27 11:51:16.144  7927  7927 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 11:51:16.144  7927  7927 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 11:51:16.144  7927  7927 E wpa_supplicant: SIM READ ERROR
07-27 11:51:16.144  7927  7927 I wpa_supplicant: wpa_default_ap_write_once
07-27 11:51:16.144  7927  7927 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-27 11:51:16.144  7927  7927 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 11:51:16.154  8041  8041 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-27 11:51:16.154  8041  8041 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
07-27 11:51:16.154  8041  8041 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,07-27 11:51:16.154  8041  8041 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-27 11:51:16.154  8041  8041 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-27 11:51:16.154  8041  8041 I Adreno-EGL: Build Date: 11/19/14 Wed
07-27 11:51:16.154  8041  8041 I Adreno-EGL: Local Branch: mybranch5813579
07-27 11:51:16.154  8041  8041 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-27 11:51:16.154  8041  8041 I Adreno-EGL: Local Patches: NONE
07-27 11:51:16.154  8041  8041 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-27 11:51:16.164  7927  7927 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
07-27 11:51:16.164  7927  7927 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,07-27 11:51:16.194  7927  7927 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
07-27 11:51:16.194  7927  7927 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,07-27 11:51:16.194   771  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,07-27 11:51:16.194   771  1148 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-27 11:51:16.194  7927  7927 I wpa_supplicant: HOTSPOT20_ENABLE called
07-27 11:51:16.194  7927  7927 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 11:51:16.194  7927  7927 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 11:51:16.194  7927  7927 E wpa_supplicant: SIM READ ERROR
07-27 11:51:16.194  7927  7927 I wpa_supplicant: Blacklist: Clear (all) 
,07-27 11:51:16.224  7927  7927 I wpa_supplicant: Skip scan - bUseNetwork false
,07-27 11:51:16.224   771  1148 D WifiNative-HAL: callSECApiInt - ID [210]
,07-27 11:51:16.224   771  1148 D WifiConfigStore: Loading config and enabling all networks 
,07-27 11:51:16.224   771   771 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
07-27 11:51:16.224  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 11:51:16.224  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-27 11:51:16.224  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:16.224  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:16.224  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:16.224  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:16.224  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:16.224  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:16.224  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:16.224  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:16.224  1188  1188 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 11:51:16.224  1188  1188 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,07-27 11:51:16.224  1188  1601 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-27 11:51:16.224  1188  1188 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:51:16.224  1188  1188 D HotspotTile: onReceive : 3, 0
,07-27 11:51:16.224   771  1152 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-27 11:51:16.224  7570  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:16.224  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:16.224  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:16.224  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:16.224  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:16.224  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:51:16.224  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:16.224  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:16.224  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:51:16.224  7570  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:16.224  7570  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:51:16.224  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
07-27 11:51:16.224  7570  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:16.224  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:16.224  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:16.224  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:16.224  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:16.224  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:51:16.224  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:16.224  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:16.224  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:51:16.224  7570  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:16.224  7570  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:51:16.234   771  1148 E WifiConfigStore: Not a HS20
,07-27 11:51:16.234  8041  8090 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-27 11:51:16.244   771  1148 E WifiConfigStore: Not a HS20
,07-27 11:51:16.244  8041  8041 I NSApplication: Starting up...
,07-27 11:51:16.254   771  1148 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-27 11:51:16.254   771  1148 D WifiNative-HAL: callSECApiInt - ID [65]
,07-27 11:51:16.264   771  1148 D WifiNative-HAL: callSECApiBoolean - ID [13]
07-27 11:51:16.264  7927  7927 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-27 11:51:16.264  7927  7927 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,07-27 11:51:16.264  7927  7927 I wpa_supplicant: reset timer : RESET_TIMER 0
07-27 11:51:16.264  7927  7927 I wpa_supplicant: P2P: Current p2p state = IDLE
07-27 11:51:16.264  7927  7927 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
07-27 11:51:16.264  7927  7927 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
07-27 11:51:16.264  7927  7927 I wpa_supplicant: First Scan Start
,07-27 11:51:16.264  7927  7927 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-27 11:51:16.264   771  1525 I ActivityManager: Killing 7120:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##41
,07-27 11:51:16.274   771  1148 D WifiNative-HAL: Setting external_sim to 1
07-27 11:51:16.274  7750  7750 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-27 11:51:16.274   771  1148 D WifiStateMachine: Setting OUI to DA-A1-19
07-27 11:51:16.274   771  1148 I WifiNative-HAL: startHal
07-27 11:51:16.274   771  1148 E wifi    : getStaticLongField sWifiHalHandle 0x934b986c
07-27 11:51:16.274   771  1148 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x901176
07-27 11:51:16.274   771  1148 I WifiNative-HAL: Could not start hal
,07-27 11:51:16.294   771  1148 E native  : do suspend true
,07-27 11:51:16.304   771  1147 D WifiP2pService: P2pDisabledState{ what=131203 }
,07-27 11:51:16.304   297  1060 D CommandListener: Setting iface cfg
07-27 11:51:16.304   297  1060 D CommandListener: Trying to bring up p2p0
,07-27 11:51:16.304   771  1147 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
07-27 11:51:16.304   771  1147 D WifiP2pService: P2pEnablingState
,07-27 11:51:16.304   771  1147 D WifiP2pService: P2pEnablingState{ what=147457 }
07-27 11:51:16.304   771  1147 D WifiP2pService: P2p socket connection successful
07-27 11:51:16.304   771  1147 D WifiP2pService: P2pEnabledState
,07-27 11:51:16.304   771  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,07-27 11:51:16.304   771   771 D WifiScanningService: SCAN_AVAILABLE : 3
07-27 11:51:16.304   771   771 D RttService: SCAN_AVAILABLE : 3
,07-27 11:51:16.304   771  1165 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:16.304   771  1165 I WifiNative-HAL: startHal
07-27 11:51:16.304   771  1165 E wifi    : getStaticLongField sWifiHalHandle 0x9adb399c
07-27 11:51:16.304   771  1165 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0xe0176e
07-27 11:51:16.304   771  1165 I WifiNative-HAL: Could not start hal
07-27 11:51:16.304   771  1165 E WifiScanningService: could not start HAL
07-27 11:51:16.304   771  1166 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:16.304   771   771 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,07-27 11:51:16.304   771  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-27 11:51:16.304   771  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-27 11:51:16.304   771  1047 D WifiDisplayController: disconnect
07-27 11:51:16.304   771  1047 D WifiDisplayController: updateConnection
07-27 11:51:16.304   771  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,07-27 11:51:16.304   771  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-27 11:51:16.304   771  1148 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
07-27 11:51:16.304   771  1148 D WifiNative-HAL: callSECStringApiVoid - ID [215]
07-27 11:51:16.304   771  1148 E WifiNative-HAL: invaild command id : 215
,07-27 11:51:16.314   771  1147 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-27 11:51:16.314  1188  1188 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-27 11:51:16.314   771  1150 E ConnectivityService: updateNetworkInfo()
07-27 11:51:16.314   771  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
07-27 11:51:16.314   771  3266 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-27 11:51:16.314  1188  1188 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-27 11:51:16.314   771  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:16.314   771  1047 D WifiDisplayAdapter: onP2pDisconnected
07-27 11:51:16.314   771  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-27 11:51:16.314   771  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-27 11:51:16.314   771  1147 D WifiNative-HAL: p2pGetDeviceAddress
,07-27 11:51:16.314   771  1147 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:de:28:a3
07-27 11:51:16.314   771  1147 D WifiP2pService: DeviceAddress: ea:28:a3
07-27 11:51:16.314   771  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
07-27 11:51:16.314   771  1047 D WifiDisplayController:  deviceAddress: ea:50:8b:de:28:a3
07-27 11:51:16.314   771  1047 D WifiDisplayController:  primary type: 10-0050F204-5
07-27 11:51:16.314   771  1047 D WifiDisplayController:  secondary type: null
07-27 11:51:16.314   771  1047 D WifiDisplayController:  wps: 0
07-27 11:51:16.314   771  1047 D WifiDisplayController:  grpcapab: 0
07-27 11:51:16.314   771  1047 D WifiDisplayController:  devcapab: 0
07-27 11:51:16.314   771  1047 D WifiDisplayController:  status: 3
07-27 11:51:16.314   771  1047 D WifiDisplayController:  wfdInfo: null
07-27 11:51:16.314   771  1047 D WifiDisplayController:  groupownerAddress: null
07-27 11:51:16.314   771  1047 D WifiDisplayController:  GOdeviceName: null
07-27 11:51:16.314   771  1047 D WifiDisplayController:  interfaceAddress: 
07-27 11:51:16.314   771  1047 D WifiDisplayController:  SConnectInfo : null
,07-27 11:51:16.324   771  1147 D WifiP2pService: sending p2p persistent groups changed broadcast
,07-27 11:51:16.324   771  1147 D WifiP2pService: InactiveState
,07-27 11:51:16.334   771  1147 D WifiP2pService: InactiveState{ what=143376 }
07-27 11:51:16.334   771  1147 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-27 11:51:16.344  7927  7927 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-27 11:51:16.354  7927  7927 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-27 11:51:16.354   771  1147 D WifiP2pService: InactiveState{ what=143376 }
,07-27 11:51:16.354   771  1147 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-27 11:51:16.364   771  1506 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,07-27 11:51:16.364   771  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:16.364   771  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:16.364   771  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:16.364   771  1506 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:16.374  7927  7927 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
07-27 11:51:16.374   771  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 11:51:16.374   771  1148 D SecContentProvider2: mCursor = null
,07-27 11:51:16.404  8105  8105 E Zygote  : MountEmulatedStorage()
07-27 11:51:16.404  8105  8105 E Zygote  : v2
07-27 11:51:16.404  8105  8105 I libpersona: KNOX_SDCARD checking this for 10158
07-27 11:51:16.404  8105  8105 I libpersona: KNOX_SDCARD not a persona
,07-27 11:51:16.414  8105  8105 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-27 11:51:16.414  8105  8105 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 11:51:16.414  8105  8105 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 11:51:16.414   771  1506 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=8105 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,07-27 11:51:16.414   771  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 11:51:16.414   771  1148 D SecContentProvider2: mCursor = null
,07-27 11:51:16.434  8105  8105 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:16.434  8105  8105 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:16.444  8105  8105 D ResourcesManager: creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,07-27 11:51:16.444  8105  8105 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 11:51:16.444  8105  8105 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-27 11:51:16.444  8105  8105 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-27 11:51:16.464  8105  8105 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:51:16.464  8105  8105 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,07-27 11:51:16.464  8105  8105 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,07-27 11:51:16.464   771   796 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,07-27 11:51:16.464   771   796 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:16.464   771   796 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:16.464   771   796 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:16.464   771   796 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:16.504  8121  8121 E Zygote  : MountEmulatedStorage()
07-27 11:51:16.504  8121  8121 E Zygote  : v2
07-27 11:51:16.504  8121  8121 I libpersona: KNOX_SDCARD checking this for 10186
07-27 11:51:16.504  8121  8121 I libpersona: KNOX_SDCARD not a persona
,07-27 11:51:16.514   771   796 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=8121 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,07-27 11:51:16.514   771   796 I ActivityManager: Killing 7137:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): emptyCount ##41
,07-27 11:51:16.534  8121  8121 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 11:51:16.534  8121  8121 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 11:51:16.534  8121  8121 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 11:51:16.554  8121  8121 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:16.554  8121  8121 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:16.564  8121  8121 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-27 11:51:16.574  8121  8121 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,07-27 11:51:16.574  8121  8121 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-27 11:51:16.574  8121  8121 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
07-27 11:51:16.574  8121  8121 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-27 11:51:16.574  8121  8121 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-27 11:51:16.584   771   987 W ProcessCpuTracker: Skipping unknown process pid 8098
,07-27 11:51:16.584   771   987 W ProcessCpuTracker: Skipping unknown process pid 8101
,07-27 11:51:16.664   771  1143 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 11:51:16.694   771  3266 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 11:51:16.694   771  1673 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 11:51:16.724   771  1360 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,07-27 11:51:16.724   771  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:16.724   771  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:16.724   771  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:16.724   771  1360 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:16.744   771   796 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 11:51:16.764   771  1702 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 11:51:16.764  8147  8147 E Zygote  : MountEmulatedStorage()
07-27 11:51:16.764  8147  8147 I libpersona: KNOX_SDCARD checking this for 10092
07-27 11:51:16.764  8147  8147 E Zygote  : v2
07-27 11:51:16.764  8147  8147 I libpersona: KNOX_SDCARD not a persona
,07-27 11:51:16.774   771  1360 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8147 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,07-27 11:51:16.794  8147  8147 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 11:51:16.794  8147  8147 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 11:51:16.794  8147  8147 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-27 11:51:16.794   771  1143 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 11:51:16.794   771  3266 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:16.794  6793  6793 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 11:51:16.794  6793  6793 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 11:51:16.794  6793  6793 D SecurityLogAgent: StateMachine : Current State = 1
,07-27 11:51:16.804  6793  6793 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 11:51:16.814  8147  8147 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:16.814   771  1318 I ActivityManager: Killing 7153:com.samsung.helphub/1000 (adj 15): emptyCount ##41
07-27 11:51:16.814  8147  8147 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:16.814   771  1567 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:16.824   771  1428 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:16.824   771  1702 I ActivityManager: Killing 7212:com.samsung.android.snote:provider/u0a168 (adj 15): emptyCount ##41
,07-27 11:51:16.824   771  1318 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,07-27 11:51:16.824   771  1318 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:16.824   771  1318 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:16.824   771  1318 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:16.824   771  1318 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:16.864  8162  8162 E Zygote  : MountEmulatedStorage()
07-27 11:51:16.864   771  1318 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8162 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
07-27 11:51:16.864  8162  8162 E Zygote  : v2
07-27 11:51:16.864  8162  8162 I libpersona: KNOX_SDCARD checking this for 10200
07-27 11:51:16.864  8162  8162 I libpersona: KNOX_SDCARD not a persona
,07-27 11:51:16.904  8162  8162 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-27 11:51:16.904  8162  8162 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 11:51:16.904  8162  8162 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-27 11:51:16.924  8162  8162 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:16.924  8162  8162 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:16.964   771  3075 I art     : Explicit concurrent mark sweep GC freed 97100(6MB) AllocSpace objects, 70(1120KB) LOS objects, 29% free, 37MB/53MB, paused 1.340ms total 106.747ms
,07-27 11:51:16.974  8162  8162 D ResourcesManager: creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
07-27 11:51:16.974  8147  8147 D ResourcesManager: creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,07-27 11:51:16.984  8147  8147 D BadgeProvider: onCreate
,07-27 11:51:16.984  8147  8147 D BadgeProvider: DatabaseHelper
,07-27 11:51:16.984   771  1673 I ActivityManager: Killing 7232:com.sec.kidsplat.installer/u0a189 (adj 15): emptyCount ##41
,07-27 11:51:16.994   771  3075 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-27 11:51:16.994   771  3075 D ActivityManager: caller:android.app.ApplicationThreadProxy@3e79744, r.packageName :com.google.android.gms
07-27 11:51:16.994   771  3266 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,07-27 11:51:16.994  4499  4499 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-27 11:51:16.994  4499  5434 I iu.UploadsManager: num queued entries: 0
,07-27 11:51:17.004  4499  5434 I iu.UploadsManager: num updated entries: 0
,07-27 11:51:17.004  4499  5434 I iu.SyncManager: NEXT; no task
,07-27 11:51:17.014  8147  8156 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,07-27 11:51:17.014  7193  7193 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-27 11:51:17.014   771  1428 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:17.014  6793  6793 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 11:51:17.014  6793  6793 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,07-27 11:51:17.014  6793  6793 D SecurityLogAgent: StateMachine : Current State = 1
07-27 11:51:17.014  6793  6793 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 11:51:17.024  7193  7193 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-27 11:51:17.034   771  1458 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:17.034  6793  6793 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 11:51:17.034  6793  6793 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 11:51:17.034  6793  6793 D SecurityLogAgent: StateMachine : Current State = 1
07-27 11:51:17.034  6793  6793 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 11:51:17.034  1443  1443 D Launcher.Model: reloadBadges entered.
07-27 11:51:17.034  8147  8156 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
07-27 11:51:17.034  8147  8156 D BadgeProvider: sendNotify, [notify] : null
07-27 11:51:17.034  8147  8156 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
07-27 11:51:17.034  8147  8156 D BadgeProvider: update, [BadgeCount] : badgecount=0
,07-27 11:51:17.034  8147  8156 D BadgeProvider: update, [UpdateCount] : 1
,07-27 11:51:17.044  7927  7927 I wpa_supplicant: nl80211: Received scan results (30 BSSes)
,07-27 11:51:17.044  7927  7927 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,07-27 11:51:17.044  7927  7927 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
07-27 11:51:17.044  7927  7927 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
07-27 11:51:17.044  7927  7927 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=5 BSSID=00.00.00 SSID=4E47373030
,07-27 11:51:17.054  7782  7782 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-27 11:51:17.054  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-27 11:51:17.054  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-27 11:51:17.054   771   796 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:17.054  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-27 11:51:17.054   771  1525 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:17.054  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-27 11:51:17.054  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 11:51:17.054  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-27 11:51:17.054  1312  2825 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 11:51:17.064   771  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-27 11:51:17.064   771  1148 D SecContentProvider2: mCursor = null
,07-27 11:51:17.064  7323  7323 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-27 11:51:17.074  7782  7782 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-27 11:51:17.074  7782  7782 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,07-27 11:51:17.074  7782  7782 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-27 11:51:17.074  7782  7782 D WifiDirectBR: stopServiceTest : false
,07-27 11:51:17.114  7927  7927 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
07-27 11:51:17.114  7927  7927 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=6 BSSID=00.00.00 SSID=4E47373030
,07-27 11:51:17.114  7927  7927 I wpa_supplicant: Associated with F4.99.3E
07-27 11:51:17.114  7927  7927 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
07-27 11:51:17.114  7927  7927 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=7 BSSID=F4.99.3E SSID=4E47373030
,07-27 11:51:17.114   771  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 11:51:17.114   771  1148 D SecContentProvider2: mCursor = null
,07-27 11:51:17.114   771  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 11:51:17.114   771  1148 D SecContentProvider2: mCursor = null
,07-27 11:51:17.124  7927  7927 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,07-27 11:51:17.124  7927  7927 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
07-27 11:51:17.124  7927  7927 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=8 BSSID=F4.99.3E SSID=4E47373030
,07-27 11:51:17.124  7927  7927 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 11:51:17.124  7927  7927 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
07-27 11:51:17.124  7927  7927 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=1 id_str=]
,07-27 11:51:17.134  7927  7927 I wpa_supplicant: Blacklist: Clear (temp) 
07-27 11:51:17.134  7927  7927 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=9 BSSID=F4.99.3E SSID=4E47373030
,07-27 11:51:17.134   771  1148 D WifiNative-HAL: callSECApiVoid - ID [50]
,07-27 11:51:17.134  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 11:51:17.134  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 11:51:17.134   771  1148 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,07-27 11:51:17.134   771  1150 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
07-27 11:51:17.134   771  1150 D ConnectivityService: Got NetworkAgent Messenger
07-27 11:51:17.134   771  1150 E ConnectivityService: updateNetworkInfo()
07-27 11:51:17.134   771  1150 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:51:17.134   771  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 11:51:17.134   771  1150 D ConnectivityService: NetworkAgent connected
,07-27 11:51:17.144  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-27 11:51:17.144  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-27 11:51:17.144   771  1310 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:17.144  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-27 11:51:17.144   771  3075 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:17.144  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,07-27 11:51:17.144  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 11:51:17.144  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-27 11:51:17.144  1312  2825 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 11:51:17.144   771  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 11:51:17.144   771  1428 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:17.144  7193  7193 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-27 11:51:17.154   297  1060 D CommandListener: Setting iface cfg
,07-27 11:51:17.154   771  1148 E WifiStateMachine: Start Dhcp Watchdog 2
,07-27 11:51:17.164   771  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 11:51:17.164   771  1148 D SecContentProvider2: mCursor = null
,07-27 11:51:17.164  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 11:51:17.164  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 11:51:17.164   771  1150 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,07-27 11:51:17.244   771  1148 E native  : do suspend false
,07-27 11:51:17.254   771  1147 D WifiP2pService: InactiveState{ what=143375 }
,07-27 11:51:17.254   771  1147 D WifiP2pService: P2pEnabledState{ what=143375 }
07-27 11:51:17.254   771  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 11:51:17.254   771  1148 D SecContentProvider2: mCursor = null
,07-27 11:51:17.464  8197  8197 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-27 11:51:17.464  8197  8197 I dhcpcd  : version 5.5.6 starting
,07-27 11:51:17.464  8197  8197 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-27 11:51:17.554  8197  8197 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-27 11:51:17.554  8197  8197 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
07-27 11:51:17.554  8197  8197 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
07-27 11:51:17.554  8197  8197 I dhcpcd  : bssid match
07-27 11:51:17.554  8197  8197 I dhcpcd  : wlan0: rebinding lease of 192.168.1.122
,07-27 11:51:17.564  8197  8197 I dhcpcd  : wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,07-27 11:51:17.564  8197  8197 I dhcpcd  : wlan0: leased 192.168.1.122 for 172800 seconds
,07-27 11:51:17.574   771  1150 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,07-27 11:51:17.644  7570  7631 I WifiManager: packageName : com.test.thalitest
,07-27 11:51:17.644   771  1318 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-27 11:51:17.644   771  1318 D WifiService: setWifiEnabled: false pid=7570, uid=10079
07-27 11:51:17.644   771  1318 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-27 11:51:17.644   771  1318 D SecContentProvider2: mCursor = null
07-27 11:51:17.644   771  1318 D SettingsProvider: name = wifi_on
,07-27 11:51:17.654   771  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 11:51:17.664   771  1148 E native  : do suspend true
,07-27 11:51:17.674   771  1147 D WifiP2pService: InactiveState{ what=143375 },
,07-27 11:51:17.674   297  1060 D CommandListener: Clearing all IP addresses on wlan0
,07-27 11:51:17.684  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 11:51:17.684  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 11:51:17.684   771  1147 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-27 11:51:17.724   771  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 11:51:17.734   771  1150 E ConnectivityService: updateNetworkInfo()
07-27 11:51:17.734   771   771 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-27 11:51:17.734   771  1150 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:51:17.734   771  1150 E ConnectivityService: updateNetworkInfo()
07-27 11:51:17.734   771  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
,07-27 11:51:17.744   771  1150 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,07-27 11:51:17.744   297  1060 E Netd    : no such netId 503
07-27 11:51:17.744   771  1150 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '77 network destroy 503' failed with '400 77 destroyNetwork() failed (Machine is not on the network)'
07-27 11:51:17.744   771  1150 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
07-27 11:51:17.744   771  1150 D ConnectivityService: calling update connectivity
07-27 11:51:17.744   771  1150 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
07-27 11:51:17.744   771  1150 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,07-27 11:51:17.744   771  8184 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
,07-27 11:51:17.744   771  8184 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,07-27 11:51:17.744  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 11:51:17.744  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 11:51:17.754   771  1147 D WifiP2pService: InactiveState{ what=131204 }
,07-27 11:51:17.754   771  1147 D WifiP2pService: P2pEnabledState{ what=131204 }
,07-27 11:51:17.754   771  1147 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,07-27 11:51:17.754   771  1150 E ConnectivityService: updateNetworkInfo()
,07-27 11:51:17.754   771  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
07-27 11:51:17.754   771  1147 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-27 11:51:17.754   771   771 D WifiScanningService: SCAN_AVAILABLE : 1
07-27 11:51:17.764   771  1165 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,07-27 11:51:17.764   771   771 D RttService: SCAN_AVAILABLE : 1
07-27 11:51:17.764   771  1166 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-27 11:51:17.764   771  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:17.764   771  1047 D WifiDisplayAdapter: onP2pDisconnected
07-27 11:51:17.764   771  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-27 11:51:17.764   771  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-27 11:51:17.764   771   771 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,07-27 11:51:17.764   771  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
07-27 11:51:17.764   771  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,07-27 11:51:17.764   771  1047 D WifiDisplayController: disconnect
07-27 11:51:17.764   771  1047 D WifiDisplayController: updateConnection
07-27 11:51:17.764   771  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,07-27 11:51:17.764   771  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-27 11:51:17.764   771  1147 D WifiP2pService: P2pDisablingState
,07-27 11:51:17.764   771  1150 E ConnectivityService: updateNetworkInfo()
,07-27 11:51:17.764   771  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,07-27 11:51:17.764   771  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-27 11:51:17.774   771  1047 D WifiDisplayAdapter: onP2pDisconnected
07-27 11:51:17.774   771  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
,07-27 11:51:17.774   771  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-27 11:51:17.774  1188  1188 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,07-27 11:51:17.774   771  1458 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-27 11:51:17.774   771  1147 D WifiP2pService: P2pDisablingState{ what=147458 }
07-27 11:51:17.774   771  1147 D WifiP2pService: p2p socket connection lost
,07-27 11:51:17.774  1188  1188 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
07-27 11:51:17.774   771  1148 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-27 11:51:17.774  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-27 11:51:17.774  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-27 11:51:17.774   771  3266 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:17.774   771  1147 D WifiP2pService: P2pDisabledState
07-27 11:51:17.774  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-27 11:51:17.774   771  1143 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-27 11:51:17.774  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-27 11:51:17.774  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 11:51:17.774  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-27 11:51:17.774  1312  2825 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 11:51:17.774   771  1148 E native  : do suspend true
,07-27 11:51:17.784   771  1567 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:17.784  7193  7193 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-27 11:51:17.784   771  1147 D WifiP2pService: P2pDisabledState{ what=143375 }
,07-27 11:51:17.794   771  1147 D WifiP2pService: DefaultState{ what=143375 }
,07-27 11:51:17.794   297  1060 D CommandListener: Clearing all IP addresses on wlan0
,07-27 11:51:17.794  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 11:51:17.794  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-27 11:51:17.794  7927  7927 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,07-27 11:51:17.794   771   771 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-27 11:51:17.794  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 11:51:17.794   771   771 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:51:17.794   771  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 11:51:17.794   771  1148 D SecContentProvider2: mCursor = null
07-27 11:51:17.794  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 11:51:17.794  7570  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:17.794  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:17.794  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:17.794  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:17.794  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:51:17.794  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:51:17.794  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:17.794  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:17.794  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:51:17.794  7570  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:17.794  7570  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:51:17.794   771  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-27 11:51:17.804  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 11:51:17.804  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-27 11:51:17.804  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:17.804  7570  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:17.804  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:17.804  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:17.804  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:17.804  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:51:17.804  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:51:17.804  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:17.804  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:17.804  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:51:17.804  7570  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:17.804  7570  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:51:17.804  1188  1188 D StatusBar.NetworkController: applyOpen
,07-27 11:51:17.804  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:17.804  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:17.804  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:17.804  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:17.804  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:17.804  1188  1188 D StatusBar.NetworkController: applyOpen
,07-27 11:51:17.804  1188  1188 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 11:51:17.804  1188  1188 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,07-27 11:51:17.804  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
07-27 11:51:17.804  1188  1601 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-27 11:51:17.804  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-27 11:51:17.804  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-27 11:51:17.804  1188  1188 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 11:51:17.804   771  3266 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:17.804  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-27 11:51:17.804   771  1428 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-27 11:51:17.804  1188  1188 D HotspotTile: onReceive : 0, 0
,07-27 11:51:17.804  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-27 11:51:17.804  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 11:51:17.804  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-27 11:51:17.804  1312  2825 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 11:51:17.804  7323  7323 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-27 11:51:17.814  7782  7782 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-27 11:51:17.814  7782  7782 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
07-27 11:51:17.814  7782  7782 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-27 11:51:17.814  7782  7782 D WifiDirectBR: stopServiceTest : false
,07-27 11:51:17.814  7782  7782 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-27 11:51:17.824  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-27 11:51:17.824  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-27 11:51:17.824   771  1360 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:17.824  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-27 11:51:17.824   771  3266 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-27 11:51:17.824  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-27 11:51:17.824  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 11:51:17.824  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-27 11:51:17.824  1312  2825 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 11:51:17.824   771  1143 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:17.834  7193  7193 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-27 11:51:17.834  7927  7927 I wpa_supplicant: Blacklist: Clear (all) 
,07-27 11:51:17.844  7193  7193 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-27 11:51:17.844   771  1506 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:17.844  6793  6793 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 11:51:17.844  6793  6793 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 11:51:17.844  6793  6793 D SecurityLogAgent: StateMachine : Current State = 1
07-27 11:51:17.844  6793  6793 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 11:51:17.864  7927  7927 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-27 11:51:17.864  7927  7927 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,07-27 11:51:17.864  7927  7927 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
,07-27 11:51:17.864  7927  7927 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=0 BSSID=F4.99.3E SSID=4E47373030
07-27 11:51:17.864  7927  7927 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-27 11:51:17.914  7927  7927 I wpa_supplicant: Blacklist: Clear (all) 
,07-27 11:51:18.024   771  1151 D Tethering: InitialState.processMessage what=4
,07-27 11:51:18.024   771  1151 E Tethering: No numeric data
,07-27 11:51:18.024   771  1151 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-27 11:51:18.024   771  1145 V NetworkStats: performPollLocked(flags=0x1)
07-27 11:51:18.024   771  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 11:51:18.024  1188  1188 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-27 11:51:18.024  1188  1188 D HotspotTile: updateTetherState():false, false
,07-27 11:51:18.024   771  1145 D NetworkStatsFactory: UpdateStatsForKnox
,07-27 11:51:18.024   771  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:18.024   771  1145 V NetworkStats: performPollLocked() took 2ms
07-27 11:51:18.024   771  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 11:51:18.024   771  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 11:51:18.024   771  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 11:51:18.024  7927  7927 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-27 11:51:18.124   771  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
07-27 11:51:18.124   771  1148 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-27 11:51:18.124  7750  7750 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 11:51:18.134   771   771 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:51:18.134  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 11:51:18.134  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,07-27 11:51:18.134  1892  2393 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 11:51:18.134  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:18.134   771  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-27 11:51:18.134  1188  1188 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 11:51:18.134  1188  1188 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
07-27 11:51:18.134  1188  1188 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:51:18.134  1188  1601 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-27 11:51:18.134  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:18.134  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
07-27 11:51:18.134  1188  1188 D HotspotTile: onReceive : 1, 0
,07-27 11:51:18.144  7193  7193 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-27 11:51:18.144   771  1673 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:18.144  6793  6793 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 11:51:18.144  6793  6793 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 11:51:18.144  6793  6793 D SecurityLogAgent: StateMachine : Current State = 1
07-27 11:51:18.144  6793  6793 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 11:51:18.334   771  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,07-27 11:51:18.404   771   794 I ActivityManager: Killing 7271:com.sec.enterprise.knox.cloudmdm.smdms/u0a201 (adj 15): emptyCount ##41
,07-27 11:51:18.964   304   304 E SMD     : DCD ON
,07-27 11:51:18.984   771  1506 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-27 11:51:18.984   771  1506 D ActivityManager: caller:android.app.ApplicationThreadProxy@15058a5e, r.packageName :com.google.android.music
,07-27 11:51:19.004   771  1702 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-27 11:51:19.004   771  1673 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-27 11:51:19.004   771  1310 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-27 11:51:19.014   771  1567 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-27 11:51:19.014   771  1567 D ActivityManager: caller:android.app.ApplicationThreadProxy@de807a4, r.packageName :com.google.android.music
,07-27 11:51:19.054   771  1673 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-27 11:51:19.064  1892  1892 D WearableService: callingUid 10015, callindPid: 1892
,07-27 11:51:19.094  7839  7839 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,07-27 11:51:19.094  7839  8267 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,07-27 11:51:19.144  7839  8262 I MusicLeanback: Conditions not met for autocaching.
,07-27 11:51:19.144  7839  8262 I MusicLeanback: Stop autocaching.
,07-27 11:51:19.234   361   361 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 11:51:19.794   771  3104 D SSRM:n  : SIOP:: AP = 370, PST = 325, CUR = 450
,07-27 11:51:20.234   361   361 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 11:51:20.664  7570  7631 D BluetoothAdapter: enable()
,07-27 11:51:20.664   771  1702 W ActivityManager: Permission Denial: getCurrentUser() from pid=7570, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,07-27 11:51:20.664   771  1702 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-27 11:51:20.664   771  1702 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7570, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-27 11:51:20.664   771  1702 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-27 11:51:20.664   771  1702 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
07-27 11:51:20.664   771  1702 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
07-27 11:51:20.664   771  1702 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-27 11:51:20.664   771  1702 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,07-27 11:51:20.664   771  1702 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-27 11:51:20.664   771  1702 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 11:51:20.664   771  1702 D SettingsProvider: name = bluetooth_on
,07-27 11:51:20.674   771  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 11:51:20.674   771  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-27 11:51:20.674   771  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,07-27 11:51:20.704  7803  7803 D BluetoothAdapterState: make
,07-27 11:51:20.704  7803  7803 I bluedroid: init
,07-27 11:51:20.704  7803  7803 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-27 11:51:20.704  7803  7803 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-27 11:51:20.704  7803  7803 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-27 11:51:20.704  7803  7803 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,07-27 11:51:20.714  7803  7803 E bt-btif : btif_fetch_local_ble_random_bdaddr
07-27 11:51:20.714  7803  7803 I bluedroid: get_profile_interface socket
07-27 11:51:20.714  7803  7803 I bluedroid: get_profile_interface map_client
,07-27 11:51:20.714  7803  7803 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,07-27 11:51:20.714   771  1428 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-27 11:51:20.714  7803  7811 I bluedroid: config_hci_snoop_log
,07-27 11:51:20.714   771  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 14 receivers.
,07-27 11:51:20.724   771  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 11:51:20.724   771  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 11:51:20.724   771  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,07-27 11:51:20.724  7803  8278 I BluetoothAdapterState: Entering OffState
07-27 11:51:20.724  7803  8281 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,07-27 11:51:20.734  7803  8281 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
,07-27 11:51:20.734  7803  8281 E BluetoothServiceJni: populateRssiValuesNative
07-27 11:51:20.734  7803  8281 I bluedroid: getModelRssiValues
07-27 11:51:20.734  7803  8281 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
07-27 11:51:20.734  7803  8281 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-27 11:51:20.734   771   771 D SettingsProvider: name = bluetooth_name
,07-27 11:51:20.734  7803  8281 D BluetoothAdapterProperties: Name is: Note3-1
07-27 11:51:20.734  7803  8278 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
07-27 11:51:20.734  7803  8278 D BluetoothAdapterProperties: Setting state to 11
,07-27 11:51:20.734  7803  8278 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-27 11:51:20.734  7803  8278 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 11:51:20.734  7803  8278 D BluetoothAdapterService: updateAdapterState state is 11
,07-27 11:51:20.734   771   771 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:51:20.734   771   771 I InputMethodManagerService: [BT Setting State] State =11
,07-27 11:51:20.744  1748  1748 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-27 11:51:20.744  1188  1188 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-27 11:51:20.744  1188  1188 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:51:20.744  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:20.744  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:20.744   771  3266 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-27 11:51:20.754  1188  1601 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-27 11:51:20.754   771  1143 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-27 11:51:20.754  1188  1188 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-27 11:51:20.754  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:51:20.754   771  1310 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-27 11:51:20.754   771  1310 D ActivityManager: caller:android.app.ApplicationThreadProxy@51c576c, r.packageName :com.google.android.gms
,07-27 11:51:20.754  7722  7722 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:51:20.754  7803  8278 D BluetoothAdapterService: Autoconnection is available 
07-27 11:51:20.754  7803  8278 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,07-27 11:51:20.764  7803  8278 D BluetoothSecureManager: getInstant: null
,07-27 11:51:20.764  7803  8278 D BluetoothSecureManager: calling getMethod for getService
,07-27 11:51:20.764  7803  8278 D BluetoothSecureManager: calling getService
07-27 11:51:20.764  7803  8278 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@226b6472
,07-27 11:51:20.764   771  1525 D BluetoothSecureManagerService: isSecureModeEnabled
07-27 11:51:20.764   771  1525 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,07-27 11:51:20.764  7803  8278 D BtConfig.SecureMode: isSecureModeOn:false
,07-27 11:51:20.764  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-27 11:51:20.774  7803  8278 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
,07-27 11:51:20.774  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-27 11:51:20.774  7803  8278 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
07-27 11:51:20.774  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-27 11:51:20.774  7803  8278 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,07-27 11:51:20.774  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-27 11:51:20.774  7803  8278 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,07-27 11:51:20.774  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-27 11:51:20.774  7803  8278 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,07-27 11:51:20.774  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-27 11:51:20.774  7803  8278 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,07-27 11:51:20.774  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-27 11:51:20.784  7803  8278 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,07-27 11:51:20.784  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-27 11:51:20.784  7803  8278 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
07-27 11:51:20.784  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-27 11:51:20.784  7803  8278 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,07-27 11:51:20.784  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,07-27 11:51:20.784  7803  8278 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
07-27 11:51:20.784  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-27 11:51:20.784  7803  8278 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
07-27 11:51:20.784  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-27 11:51:20.784  7803  8278 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,07-27 11:51:20.794  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
,07-27 11:51:20.794  7803  8278 D BluetoothBondStateMachine: make
,07-27 11:51:20.814  7803  8297 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-27 11:51:20.814  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
07-27 11:51:20.814  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-27 11:51:20.814  7803  8278 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,07-27 11:51:20.814   771  1458 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 11:51:20.814   771  1458 D ActivityManager: caller:android.app.ApplicationThreadProxy@236ae9ca, r.packageName :com.android.bluetooth
,07-27 11:51:20.814  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
07-27 11:51:20.814  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-27 11:51:20.814  7803  8278 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,07-27 11:51:20.814   771  1318 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 11:51:20.814   771  1318 D ActivityManager: caller:android.app.ApplicationThreadProxy@312d7e58, r.packageName :com.android.bluetooth
07-27 11:51:20.814  7803  7803 I BtGatt.JNI: classInitNative(L890): classInitNative: Success!
,07-27 11:51:20.824  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
07-27 11:51:20.824  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-27 11:51:20.824  7803  8278 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,07-27 11:51:20.824   771  1360 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 11:51:20.824   771  1360 D ActivityManager: caller:android.app.ApplicationThreadProxy@135d896, r.packageName :com.android.bluetooth
,07-27 11:51:20.824  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
07-27 11:51:20.824  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-27 11:51:20.824  7803  8278 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,07-27 11:51:20.824  7803  7803 D BtGatt.DebugUtils: handleDebugAction() action=null
07-27 11:51:20.824  7803  7803 D BtGatt.GattService: Received start request. Starting profile...
07-27 11:51:20.824   771  3075 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 11:51:20.824  7803  7803 D BtGatt.GattService: start()
07-27 11:51:20.824  7803  7803 I bluedroid: get_profile_interface gatt
,07-27 11:51:20.824   771  3075 D ActivityManager: caller:android.app.ApplicationThreadProxy@32282804, r.packageName :com.android.bluetooth
07-27 11:51:20.824  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23172ac5
07-27 11:51:20.824  7803  7803 D BtGatt.AdvertiseManager: advertise manager created
,07-27 11:51:20.824  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
07-27 11:51:20.824  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-27 11:51:20.824  7803  8278 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-27 11:51:20.824   771  3266 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 11:51:20.824   771  3266 D ActivityManager: caller:android.app.ApplicationThreadProxy@28eee822, r.packageName :com.android.bluetooth
,07-27 11:51:20.834  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,07-27 11:51:20.834  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-27 11:51:20.834  7803  8278 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,07-27 11:51:20.834   771  1143 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 11:51:20.834   771  1143 D ActivityManager: caller:android.app.ApplicationThreadProxy@3f01c070, r.packageName :com.android.bluetooth
,07-27 11:51:20.834  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,07-27 11:51:20.834  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 11:51:20.834  7803  8278 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
07-27 11:51:20.834   771  1506 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 11:51:20.834   771  1506 D ActivityManager: caller:android.app.ApplicationThreadProxy@2037646e, r.packageName :com.android.bluetooth
,07-27 11:51:20.844  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,07-27 11:51:20.844  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-27 11:51:20.844  7803  8278 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-27 11:51:20.844   771  1318 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 11:51:20.844   771  1318 D ActivityManager: caller:android.app.ApplicationThreadProxy@324a752b, r.packageName :com.android.bluetooth
,07-27 11:51:20.844  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23172ac5
,07-27 11:51:20.844  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-27 11:51:20.844  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-27 11:51:20.844  7803  8278 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-27 11:51:20.844  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-27 11:51:20.844  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-27 11:51:20.844  7803  8278 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-27 11:51:20.844  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
07-27 11:51:20.844  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-27 11:51:20.844  7803  8278 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,07-27 11:51:20.844  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
07-27 11:51:20.844  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-27 11:51:20.844  7803  8278 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-27 11:51:20.844  7803  7803 D HeadsetService: Received start request. Starting profile...
07-27 11:51:20.844  1892  1892 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-27 11:51:20.844  7803  8278 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,07-27 11:51:20.854  7803  7803 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-27 11:51:20.854  7803  7803 D HeadsetStateMachine: make
,07-27 11:51:20.854  7803  7803 E HeadsetStateMachine: # of Max HF connection is 2
,07-27 11:51:20.864  1892  1892 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-27 11:51:20.864   771  3266 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,07-27 11:51:20.864   771  1310 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
,07-27 11:51:20.864  7803  7803 I bluedroid: get_profile_interface handsfree
,07-27 11:51:20.874  7803  7803 I DualScoManager: Instantiating Dual Sco Manager
07-27 11:51:20.874  7803  7803 I DualScoManager: Set HeadsetServiceHelper
,07-27 11:51:20.874  7803  7803 D BluetoothAtMessage: createCMTIContentObservers
,07-27 11:51:20.874   771   796 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
07-27 11:51:20.874   771   796 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:20.874   771   796 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:20.874   771   796 D SettingsProvider: selectionArgs: false
07-27 11:51:20.874   771   796 D SettingsProvider: selectionArgs: 1002
07-27 11:51:20.874   771   796 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:20.874   771   796 D SettingsProvider: ret = -1
07-27 11:51:20.874  7803  8304 D HeadsetStateMachine: Enter Disconnected: -2
,07-27 11:51:20.874  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23172ac5
07-27 11:51:20.874  7803  8304 E HeadsetStateMachine: set to mRemoteBrsf = 0
,07-27 11:51:20.874  7803  7803 D A2dpService: Received start request. Starting profile...
,07-27 11:51:20.884  7803  8304 D HeadsetStateMachine: map size, before remove : 0
07-27 11:51:20.884  7803  8304 D HeadsetStateMachine: map size, after remove: 0
07-27 11:51:20.884  7803  8304 D HeadsetStateMachine: mNextConnectingDevice : null
,07-27 11:51:20.884  7803  7803 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-27 11:51:20.884  7803  7803 V Avrcp   : make
,07-27 11:51:20.884  7803  7803 V Avrcp   : Avrcp
07-27 11:51:20.884  7803  7803 I bluedroid: get_profile_interface avrcp
,07-27 11:51:20.884  7803  7803 V Avrcp   : start
,07-27 11:51:20.894  7803  7803 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-27 11:51:20.894  7803  7803 V Avrcp   : ++registerMediaPlayers++
,07-27 11:51:20.894  7803  7803 I Avrcp   : No of Audio players :: 2
07-27 11:51:20.894  7803  7803 I Avrcp   : App Package name is com.google.android.music
,07-27 11:51:20.894  7803  7803 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-27 11:51:20.894  7803  7803 I Avrcp   : App pkg name is Google Play Music
,07-27 11:51:20.894  7803  7803 I Avrcp   : Name::Google Play Music
07-27 11:51:20.894  7803  7803 V Avrcp   : MediaPlayerInfo: mPlayerId=1
07-27 11:51:20.894  7803  7803 I Avrcp   : App Package name is com.sec.android.app.music
,07-27 11:51:20.894  7803  7803 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,07-27 11:51:20.904  7803  7803 I Avrcp   : App pkg name is Music
,07-27 11:51:20.904  7803  7803 I Avrcp   : Name::Music
07-27 11:51:20.904  7803  7803 V Avrcp   : MediaPlayerInfo: mPlayerId=2
07-27 11:51:20.904  7803  7803 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,07-27 11:51:20.904  7803  7803 I Avrcp   : No of Video players :: 1
07-27 11:51:20.904  7803  7803 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
,07-27 11:51:20.904  7803  7803 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,07-27 11:51:20.904  7803  7803 I Avrcp   : Video App pkg name is Video Player
,07-27 11:51:20.904  7803  7803 I Avrcp   : Name::Video Player
07-27 11:51:20.904  7803  7803 V Avrcp   : MediaPlayerInfo: mPlayerId=3
07-27 11:51:20.904  7803  7803 I Avrcp   : Add tempPlayer
07-27 11:51:20.904  7803  7803 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-27 11:51:20.904  7803  7803 I Avrcp   : Total no of players: 4
07-27 11:51:20.904  7803  7803 V Avrcp   : swapping the samsung player with 1st player
07-27 11:51:20.904  7803  7803 I Avrcp   :  Updating now playing list upon AVRCP Start
07-27 11:51:20.904  7803  8306 V Avrcp   : handleMessage, msg=207
,07-27 11:51:20.904  7803  8306 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,07-27 11:51:20.904  7803  7803 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-27 11:51:20.904  7803  7803 D A2dpStateMachine: make
,07-27 11:51:20.914  7803  7803 I bluedroid: get_profile_interface a2dp
07-27 11:51:20.914  7803  8308 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-27 11:51:20.914  7803  7803 E bt-btif : warning : media task started media_task_refcnt 1 
,07-27 11:51:20.914  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23172ac5
07-27 11:51:20.914  7803  8307 D A2dpStateMachine: Enter Disconnected: -2
,07-27 11:51:20.914   771  1458 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,07-27 11:51:20.914  7803  7803 I BluetoothHidServiceJni: classInitNative: succeeds
,07-27 11:51:20.914  7803  7803 D HidService: Received start request. Starting profile...
07-27 11:51:20.914  7803  7803 I bluedroid: get_profile_interface hidhost
07-27 11:51:20.914  7803  7803 D HidService: setHidService(): set to: null
07-27 11:51:20.914  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23172ac5
,07-27 11:51:20.914  7803  7803 I BluetoothHealthServiceJni: classInitNative: succeeds
07-27 11:51:20.914  7803  8306 D BluetoothMediaBrowser: no now playing list
,07-27 11:51:20.924  7803  8306 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
07-27 11:51:20.924  7803  7803 D HealthService: Received start request. Starting profile...
07-27 11:51:20.924  7803  8306 D Avrcp   :  checkNowPlayingList start
,07-27 11:51:20.924  7803  7803 I bluedroid: get_profile_interface health
07-27 11:51:20.924  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23172ac5
,07-27 11:51:20.924  7803  7803 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-27 11:51:20.924  7803  7803 D PanService: Received start request. Starting profile...
07-27 11:51:20.924  7803  7803 D BluetoothPanServiceJni: initializeNative(L110): pan
07-27 11:51:20.924  7803  7803 I bluedroid: get_profile_interface pan
,07-27 11:51:20.924  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23172ac5
,07-27 11:51:20.924  7803  7803 D BluetoothMapService: Received start request. Starting profile...
,07-27 11:51:20.934  8041  8060 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,07-27 11:51:20.954  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23172ac5
,07-27 11:51:20.954  7803  7803 E BluetoothAdapterService(588720837): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,07-27 11:51:20.954  7803  7803 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,07-27 11:51:20.954  7803  7803 D SapService: Received start request. Starting profile...
07-27 11:51:20.954  7803  7803 D BluetoothSAPServiceJni: initializeNative(L209): sap
07-27 11:51:20.954  7803  7803 I bluedroid: get_profile_interface sap
07-27 11:51:20.954  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23172ac5
,07-27 11:51:20.954  7803  7803 D HeadsetStateMachine: Try to query the phonestate on bind
,07-27 11:51:20.954  1405  1414 I Telecom : BluetoothPhoneService: queryPhoneState
07-27 11:51:20.954  1405  1405 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,07-27 11:51:20.954  7803  7803 D HeadsetStateMachine: Proxy object connected
07-27 11:51:20.954  7803  7803 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,07-27 11:51:20.954  7803  7803 D HeadsetPhoneState: sendDeviceDataStateChanged
07-27 11:51:20.954  7803  8304 D HeadsetStateMachine: Disconnected process message: 11
07-27 11:51:20.954  7803  8304 D HeadsetStateMachine: Disconnected process message: 18
07-27 11:51:20.954  7803  7803 D HeadsetPhoneState: Signal level : previous=0 curr=0
07-27 11:51:20.954  7803  7803 E BluetoothAdapterService(588720837): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
07-27 11:51:20.954  7803  7803 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 11:51:20.954  7803  7803 D BluetoothA2dp: Proxy object connected
07-27 11:51:20.954  7803  7803 D BluetoothAdapterService: Bluetooth A2dp source service connected
07-27 11:51:20.954  7803  7803 E BluetoothAdapterService(588720837): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
07-27 11:51:20.954  7803  7803 E BluetoothAdapterService(588720837): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
07-27 11:51:20.954  7803  8304 D HeadsetStateMachine: Disconnected process message: 10
07-27 11:51:20.954  7803  8304 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-27 11:51:20.954  7803  8304 D HeadsetStateMachine: Disconnected process message: 11
,07-27 11:51:20.964  7803  7803 E BluetoothAdapterService(588720837): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
07-27 11:51:20.964  7803  7803 E BluetoothAdapterService(588720837): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,07-27 11:51:20.964  7803  7803 E BluetoothAdapterService(588720837): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,07-27 11:51:20.964  7803  7803 E BluetoothAdapterService(588720837): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
07-27 11:51:20.964  7803  8278 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
07-27 11:51:20.964  7803  8278 I bluedroid: enable
07-27 11:51:20.964  7803  8314 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-27 11:51:20.964  7803  8278 I bt_hci_bdroid: init
,07-27 11:51:20.964  7803  8278 I bt_vendor: init
07-27 11:51:20.964  7803  8278 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-27 11:51:20.964  7803  8278 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
07-27 11:51:20.964  7803  8278 D bt_userial: userial_init
07-27 11:51:20.964  7803  8278 D bt_vendor: op for 5
07-27 11:51:20.964  7803  8278 D bt_vendor: op for 0
,07-27 11:51:20.964  7803  8278 D bt_upio : upio_set_bluetooth_power(on: 0)
07-27 11:51:20.964  7803  8278 D bt_upio : is_emulator_context : 0
07-27 11:51:20.964  7803  8278 D bt_upio : is_rfkill_disabled ? [0]
07-27 11:51:20.964  7803  8278 D bt_upio : is_rfkill_disabled ? [0]
,07-27 11:51:20.964  7803  8278 D bt_vendor: op for 0
07-27 11:51:20.964  7803  8278 D bt_upio : upio_set_bluetooth_power(on: 1)
07-27 11:51:20.964  7803  8278 D bt_upio : is_emulator_context : 0
07-27 11:51:20.964  7803  8278 D bt_upio : is_rfkill_disabled ? [0]
,07-27 11:51:20.964  7803  8316 D bt_vendor: op for 3
07-27 11:51:20.964  7803  8316 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-27 11:51:20.974  7803  8316 I bt_userial_vendor: userial_vendor_open():UART is setup
07-27 11:51:20.974  7803  8316 I bt_userial_vendor: device fd = 66 open
07-27 11:51:20.974  7803  8316 D bt_vendor: op for 1
07-27 11:51:20.974  7803  8316 E bt_hwcfg: Start CFG HW, HCI reset
07-27 11:51:20.974  7803  8317 D bt_userial: Entering userial_read_thread()
,07-27 11:51:21.044  7803  8316 E bt_hwcfg: Read Local Name after HCI reset
,07-27 11:51:21.074  7803  8316 D bt_hwcfg: Chipset BCM4335C0,
07-27 11:51:21.074  7803  8316 D bt_hwcfg: Target name = [BCM4335C0]
07-27 11:51:21.074  7803  8316 I bt_hwcfg: module_type[semco].,
07-27 11:51:21.074  7803  8316 I bt_hwcfg: not ZERO...
07-27 11:51:21.074  7803  8316 I bt_hwcfg: module_type[semco] is invalid.
,07-27 11:51:21.074  7803  8316 E bt_hwcfg: patchram path ORG . BCM4335C0
07-27 11:51:21.074  7803  8316 E bt_hwcfg: patchram path ORG .. BCM4335C0
,07-27 11:51:21.074  7803  8316 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
07-27 11:51:21.074  7803  8316 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
07-27 11:51:21.074  7803  8316 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0,
07-27 11:51:21.074  7803  8316 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
07-27 11:51:21.074  7803  8316 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335C0
,07-27 11:51:21.074  7803  8316 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559_wisol.hcd BCM4335C0
07-27 11:51:21.074  7803  8316 E bt_hwcfg: fw ver (org)0.0
,07-27 11:51:21.074  7803  8316 E bt_hwcfg: vendor lib preload failed to locate firmware patch file
07-27 11:51:21.074  7803  8316 E bt_hwcfg: Remove module rev, try again BCM4335
,07-27 11:51:21.074  7803  8316 D bt_hwcfg: Target name = [BCM4335]
07-27 11:51:21.074  7803  8316 I bt_hwcfg: module_type[semco].
,07-27 11:51:21.074  7803  8316 I bt_hwcfg: not ZERO...
07-27 11:51:21.074  7803  8316 I bt_hwcfg: module_type[semco] is invalid.
,07-27 11:51:21.074  7803  8316 E bt_hwcfg: patchram path ORG . BCM4335
07-27 11:51:21.074  7803  8316 E bt_hwcfg: patchram path ORG .. BCM4335
,07-27 11:51:21.074  7803  8316 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335
07-27 11:51:21.074  7803  8316 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
,07-27 11:51:21.074  7803  8316 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335
07-27 11:51:21.074  7803  8316 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
,07-27 11:51:21.074  7803  8316 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335
07-27 11:51:21.074  7803  8316 I bt_hwcfg: patch(org) : bcm4335_V0111.0559.hcd
,07-27 11:51:21.074  7803  8316 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4335_V0111.0559.hcd
07-27 11:51:21.074  7803  8316 E bt_hwcfg: ORG patchram base 0111
,07-27 11:51:21.074  7803  8316 E bt_hwcfg: ORG patchram minor 0559
07-27 11:51:21.074  7803  8316 E bt_hwcfg: fw ver (org)111.559,
07-27 11:51:21.074  7803  8316 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4335_V0111.0559.hcd
,07-27 11:51:21.084  7803  8316 I bt_hwcfg: Axi patch failure or not include AXI patching
,07-27 11:51:21.094  7803  8316 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-27 11:51:21.234   361   361 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 11:51:21.504  7803  8316 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-27 11:51:21.504  7803  8316 I bt_hwcfg: FW Download delta = 457622
07-27 11:51:21.504  7803  8316 D bt_hwcfg: Settlement delay -- 100 ms
,07-27 11:51:21.504  7803  8316 I bt_hwcfg: Setting fw settlement delay to 100 
,07-27 11:51:21.614  7803  8316 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-27 11:51:21.644  7803  8316 I bt_hwcfg: vendor lib fwcfg completed
,07-27 11:51:21.644  7803  8314 I         : BTE_InitTraceLevels -- TRC_HCI
,07-27 11:51:21.644  7803  8314 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-27 11:51:21.644  7803  8314 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-27 11:51:21.644  7803  8314 I         : BTE_InitTraceLevels -- TRC_AVDT
07-27 11:51:21.644  7803  8314 I         : BTE_InitTraceLevels -- TRC_AVRC
07-27 11:51:21.644  7803  8314 I         : BTE_InitTraceLevels -- TRC_A2D
07-27 11:51:21.644  7803  8314 I         : BTE_InitTraceLevels -- TRC_BNEP
,07-27 11:51:21.644  7803  8314 I         : BTE_InitTraceLevels -- TRC_BTM
07-27 11:51:21.644  7803  8314 I         : BTE_InitTraceLevels -- TRC_GAP
07-27 11:51:21.644  7803  8314 I         : BTE_InitTraceLevels -- TRC_PAN
07-27 11:51:21.644  7803  8314 I         : BTE_InitTraceLevels -- TRC_SAP
07-27 11:51:21.644  7803  8314 I         : BTE_InitTraceLevels -- TRC_SDP
07-27 11:51:21.644  7803  8314 I         : BTE_InitTraceLevels -- TRC_GATT
,07-27 11:51:21.644  7803  8314 I         : BTE_InitTraceLevels -- TRC_SMP
07-27 11:51:21.644  7803  8314 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-27 11:51:21.644  7803  8314 I         : BTE_InitTraceLevels -- TRC_BTIF
07-27 11:51:21.654  7803  8314 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,07-27 11:51:21.864  7803  8314 W bt-l2cap: l2c_link_processs_ble_num_bufs 15
,07-27 11:51:21.864  7803  8314 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa1929b5d 
,07-27 11:51:21.874  7803  8314 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa1929b5d 
,07-27 11:51:21.964   304   304 E SMD     : DCD ON
,07-27 11:51:22.084  7803  8281 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 1 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
,07-27 11:51:22.084  7803  8281 E bt-btif : Calling BTA_HhEnable
,07-27 11:51:22.084  7803  8281 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,07-27 11:51:22.094  7803  8281 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
,07-27 11:51:22.094  7803  8281 E BluetoothServiceJni: populateRssiValuesNative
07-27 11:51:22.094  7803  8281 I bluedroid: getModelRssiValues
07-27 11:51:22.094  7803  8281 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
07-27 11:51:22.094  7803  8281 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-27 11:51:22.094   771   771 D SettingsProvider: name = bluetooth_name
,07-27 11:51:22.094  7803  8281 D BluetoothAdapterProperties: Name is: Note3-1
,07-27 11:51:22.094  7803  8281 D BluetoothAdapterProperties: Scan Mode:20
,07-27 11:51:22.094  7803  8281 D BluetoothAdapterProperties: Discoverable Timeout:120
07-27 11:51:22.094  7803  8281 D BluetoothAdapterProperties: LE Address is:E0:B7:20:3E:93:BC
,07-27 11:51:22.094  7803  8316 D bt_vendor: op for 2
,07-27 11:51:22.094  7803  8316 D bt_vendor: op for 6
,07-27 11:51:22.094  7803  8316 D bt_vendor: op for 7
,07-27 11:51:22.094  7803  8316 D bt_upio : proc btwrite assertion
07-27 11:51:22.094  7803  8281 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,07-27 11:51:22.104  7803  8316 D bt_vendor: op for 7
,07-27 11:51:22.104  7803  8316 D bt_upio : BT_WAKE is asserted already
07-27 11:51:22.104  7803  8281 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,07-27 11:51:22.104  7803  8281 E bt-btif : btif_sock_init: !radio_req && !rfc_init
07-27 11:51:22.104  7803  8316 D bt_vendor: op for 7
07-27 11:51:22.104  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:22.104  7803  8281 E bt-btif : btif_sock_init: !vhci_init
07-27 11:51:22.104  7803  8281 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,07-27 11:51:22.104  7803  8281 D IOP_DB_BT: db_open: db_open : handle 3026141200l, read 14063 bytes onto local cache
07-27 11:51:22.104  7803  8281 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,07-27 11:51:22.104  7803  8281 D IOP_DB_BT: db_query: result 1
07-27 11:51:22.104  7803  8281 I         : iop_db_open: iop_db_open status 0
,07-27 11:51:22.104  7803  8281 D bte_conf: Device ID record 1 : primary
07-27 11:51:22.104  7803  8281 D bte_conf:   vendorId            = 0075
07-27 11:51:22.104  7803  8281 D bte_conf:   vendorIdSource      = 0001
,07-27 11:51:22.104  7803  8281 D bte_conf:   product             = 0100
07-27 11:51:22.104  7803  8281 D bte_conf:   version             = 0200
07-27 11:51:22.104  7803  8281 D bte_conf:   clientExecutableURL = 
07-27 11:51:22.104  7803  8281 D bte_conf:   serviceDescription  = 
07-27 11:51:22.104  7803  8281 D bte_conf:   documentationURL    = 
,07-27 11:51:22.104  7803  8281 D bte_conf: bte_load_did_conf no section named DID2.
,07-27 11:51:22.104  7803  8278 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-27 11:51:22.104  7803  8278 D BluetoothAdapterProperties: ScanMode =  20
07-27 11:51:22.104  7803  8278 D BluetoothAdapterProperties: State =  11
,07-27 11:51:22.104  7803  8281 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-27 11:51:22.104   771  3075 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,07-27 11:51:22.114  7803  8278 D BluetoothAdapterProperties: Setting state to 12
07-27 11:51:22.114  7803  8278 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-27 11:51:22.114   771  1702 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,07-27 11:51:22.114   771  1702 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:22.114   771  1702 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:22.114   771  1702 D SettingsProvider: selectionArgs: false
07-27 11:51:22.114   771  1702 D SettingsProvider: selectionArgs: 1002
,07-27 11:51:22.114   771  1702 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:22.114   771  1702 D SettingsProvider: ret = -1
07-27 11:51:22.114  7803  8278 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,07-27 11:51:22.114  7803  8278 D BluetoothAdapterService: updateAdapterState state is 12
,07-27 11:51:22.114   771  1360 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 11:51:22.114   771  1360 D ActivityManager: caller:android.app.ApplicationThreadProxy@b6f691, r.packageName :com.android.bluetooth
,07-27 11:51:22.124  7803  8278 D BluetoothAdapterService: Autoconnection is available 
,07-27 11:51:22.124  7803  8278 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-27 11:51:22.124  7803  8278 D BluetoothAdapterService: starting service from this receiver
,07-27 11:51:22.124   771  1310 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 11:51:22.124   771  1310 D ActivityManager: caller:android.app.ApplicationThreadProxy@18fc71f7, r.packageName :com.android.bluetooth
,07-27 11:51:22.124  7803  8316 E bt_h4   : vendor lib postload completed
,07-27 11:51:22.124  7803  8316 D bt_vendor: op for 7
07-27 11:51:22.124  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:22.124  7803  8278 I BluetoothAdapterState: Entering On State from state = 11
,07-27 11:51:22.124  7803  8316 D bt_vendor: op for 7
07-27 11:51:22.124  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:22.124  7803  8316 D bt_vendor: op for 7
,07-27 11:51:22.124  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:22.134  7803  8316 D bt_vendor: op for 7
,07-27 11:51:22.134  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:22.134  7803  8316 D bt_vendor: op for 7
,07-27 11:51:22.134  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:22.134  7803  8316 D bt_vendor: op for 7
07-27 11:51:22.134  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:22.134  7803  8316 D bt_vendor: op for 7
,07-27 11:51:22.134  7803  8316 D bt_upio : BT_WAKE is asserted already
07-27 11:51:22.134  7803  8281 D BluetoothAdapterProperties: Scan Mode:21
07-27 11:51:22.134  7803  8281 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-27 11:51:22.134  7803  8316 D bt_vendor: op for 7
07-27 11:51:22.134  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:22.134  7803  8316 D bt_vendor: op for 7
,07-27 11:51:22.134  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:22.144  7803  7803 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,07-27 11:51:22.154  7803  8316 D bt_vendor: op for 7
,07-27 11:51:22.154  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:22.154  7803  8316 D bt_vendor: op for 7
,07-27 11:51:22.154  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:22.154  7803  8316 D bt_vendor: op for 7
07-27 11:51:22.154  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:22.154  7803  8316 D bt_vendor: op for 7
,07-27 11:51:22.154  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:22.154  7803  8316 D bt_vendor: op for 7
,07-27 11:51:22.154  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:22.164  7803  8316 D bt_vendor: op for 7
,07-27 11:51:22.164  7803  8316 D bt_upio : BT_WAKE is asserted already
07-27 11:51:22.164  7803  7803 I BluetoothPbapService: Handler(): got msg=1
,07-27 11:51:22.164  7803  8316 D bt_vendor: op for 7
,07-27 11:51:22.164  7803  8316 D bt_upio : BT_WAKE is asserted already
07-27 11:51:22.164   771  1428 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-27 11:51:22.164  7803  8316 D bt_vendor: op for 7
,07-27 11:51:22.164  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:22.164  7803  8316 D bt_vendor: op for 7
,07-27 11:51:22.164  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:22.164  7803  8316 D bt_vendor: op for 7
07-27 11:51:22.164  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:22.164  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:22.164  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:22.164  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:22.164  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:51:22.164  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:22.164  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:22.164  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:22.164  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:51:22.174  7803  8316 D bt_vendor: op for 7
07-27 11:51:22.174  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:22.174   771  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 11:51:22.174  1312  1339 E BluetoothHeadset: BluetoothHeadset service is binded
07-27 11:51:22.174  7803  8316 D bt_vendor: op for 7
07-27 11:51:22.174  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:22.174  1312  1312 D HeadsetProfile: Bluetooth service connected
07-27 11:51:22.174  1312  1326 D BluetoothMap: onBluetoothStateChange: up=true
,07-27 11:51:22.174   771  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,07-27 11:51:22.174   771  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-27 11:51:22.174   771  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
07-27 11:51:22.174  7570  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:51:22.174   771   771 D BluetoothA2dp: Proxy object connected
,07-27 11:51:22.184  1312  1312 D BluetoothMap: Proxy object connected
07-27 11:51:22.184  1312  1312 D MapProfile: Bluetooth service connected
,07-27 11:51:22.184   771  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 11:51:22.184  1427  1755 E BluetoothHeadset: BluetoothHeadset service is binded
,07-27 11:51:22.184  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:22.184  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:22.184  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:22.184  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:51:22.184  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:22.184  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:22.184  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:22.184  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:51:22.184  1312  1340 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-27 11:51:22.184  7570  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:51:22.184   771  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
07-27 11:51:22.184  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:22.184  7803  8340 V BluetoothPbapService: PBAP Service initSocket try: 0
07-27 11:51:22.184  1312  1312 D BluetoothA2dp: Proxy object connected
07-27 11:51:22.184  3206  3221 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-27 11:51:22.184  1312  1312 D A2dpProfile: Bluetooth service connected
07-27 11:51:22.184  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:22.184   771  1045 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-27 11:51:22.184  3206  3206 D BluetoothA2dp: Proxy object connected
07-27 11:51:22.184  1312  1339 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-27 11:51:22.194   771  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,07-27 11:51:22.194  1312  1312 D BluetoothInputDevice: Proxy object connected
,07-27 11:51:22.194  1312  1312 D HidProfile: Bluetooth service connected
07-27 11:51:22.194  7803  8340 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 11:51:22.194  7803  8316 D bt_vendor: op for 7
07-27 11:51:22.194  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:22.194  7803  8340 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[73]}
07-27 11:51:22.194  7803  8340 D BluetoothSocket: bindListen(), new LocalSocket 
07-27 11:51:22.194  7803  8340 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-27 11:51:22.194  7803  8340 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d78dff6
07-27 11:51:22.194  7803  8340 D BluetoothSocket: channel: 19
07-27 11:51:22.194   771  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
07-27 11:51:22.194  7803  8340 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,07-27 11:51:22.204  1405  3101 E BluetoothHeadset: BluetoothHeadset service is binded
,07-27 11:51:22.204   771  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 11:51:22.204  1405  1414 E BluetoothHeadset: BluetoothHeadset service is binded
,07-27 11:51:22.204  7803  7813 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 11:51:22.204  1312  1340 D BluetoothPbap: onBluetoothStateChange: up=true
,07-27 11:51:22.204   771  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,07-27 11:51:22.204   771  1045 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 11:51:22.204  1312  1312 D BluetoothPbap: Proxy object connected
07-27 11:51:22.204  1312  1312 D PbapServerProfile: Bluetooth service connected
07-27 11:51:22.204  3206  3221 E BluetoothHeadset: BluetoothHeadset service is binded
,07-27 11:51:22.204   771  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 11:51:22.204   771  1045 E BluetoothHeadset: BluetoothHeadset service is binded
07-27 11:51:22.204  1312  1326 D Bluetoothsap: onBluetoothStateChange: up=true
07-27 11:51:22.204  1312  1326 D Bluetoothsap: Binding service...
,07-27 11:51:22.204  1312  1326 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,07-27 11:51:22.204   771  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,07-27 11:51:22.214  1312  1326 D Bluetoothsap: bindService called to Bluetooth SAP Service
07-27 11:51:22.214  1312  1340 D BluetoothPan: Binding service...
,07-27 11:51:22.214  1312  1312 D Bluetoothsap: BluetoothSAP Proxy object connected
07-27 11:51:22.214  1312  1312 D SapProfile: Bluetooth service connected
07-27 11:51:22.214  1312  1312 D Bluetoothsap: getConnectedDevices()
,07-27 11:51:22.214   771  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,07-27 11:51:22.214   771  1045 D BluetoothPan: Binding service...
,07-27 11:51:22.214  1312  1312 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 11:51:22.214   771  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
07-27 11:51:22.214  1312  1312 D PanProfile: Bluetooth service connected
07-27 11:51:22.214   771   771 D BluetoothPan: BluetoothPAN Proxy object connected
,07-27 11:51:22.214   771  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 11:51:22.214  1405  3101 E BluetoothHeadset: BluetoothHeadset service is binded
07-27 11:51:22.214   771  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,07-27 11:51:22.214   771  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,07-27 11:51:22.214   771   771 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:22.214   771   771 I InputMethodManagerService: [BT Setting State] State =12
07-27 11:51:22.214   771   771 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-27 11:51:22.214  1188  1188 D BluetoothTile:  onBluetoothStateChange:
,07-27 11:51:22.214  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:51:22.214  1748  1748 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
07-27 11:51:22.214  1405  1405 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2eba232b, true
,07-27 11:51:22.214  7722  7722 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:51:22.224  1405  1405 D BluetoothHeadset: registerMessageListener
,07-27 11:51:22.224  1188  1188 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-27 11:51:22.224  1188  1188 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:51:22.224  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:22.224   771  1428 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-27 11:51:22.224   771  1428 D ActivityManager: caller:android.app.ApplicationThreadProxy@1e50f606, r.packageName :com.google.android.gms
,07-27 11:51:22.224  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:22.224  7803  8349 D BluetoothMapMasInstance: set MAP SDP message type : 1
,07-27 11:51:22.234  1312  1312 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,07-27 11:51:22.234  7803  8346 D HeadsetService: registerMessageListener
07-27 11:51:22.234  1312  1312 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
07-27 11:51:22.234  7803  8346 D HeadsetService: registerMessageListener
,07-27 11:51:22.234  1405  1405 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
07-27 11:51:22.234  7803  8304 D HeadsetStateMachine: Disconnected process message: 70
07-27 11:51:22.234  1405  1405 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
07-27 11:51:22.234  7803  8304 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@1ef87ff7
,07-27 11:51:22.234  1188  1601 D BluetoothTile:  handleUpdatestate:false name:null
07-27 11:51:22.234  1188  1601 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-27 11:51:22.234   771  1506 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-27 11:51:22.234   771  1458 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 11:51:22.234   771  1458 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-27 11:51:22.234   771  1458 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-27 11:51:22.234   771  1458 D BatteryService: stay LED for fully charged
07-27 11:51:22.234   771   771 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 11:51:22.234   771   796 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,07-27 11:51:22.234   361   361 I ServiceManager: Waiting for service AtCmdFwd...
07-27 11:51:22.234  7803  8349 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-27 11:51:22.234  1188  1188 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-27 11:51:22.234   771   771 I MotionRecognitionService: Plugged
07-27 11:51:22.234   771   771 I MotionRecognitionService: setPowerConnected  = true
,07-27 11:51:22.234  7803  8304 D HeadsetStateMachine: Disconnected process message: 9
,07-27 11:51:22.244  7803  8304 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,07-27 11:51:22.244  1312  1312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-27 11:51:22.244  7803  7803 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 11:51:22.244   771  1143 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-27 11:51:22.244   771  1143 D ActivityManager: caller:android.app.ApplicationThreadProxy@2bdc821d, r.packageName :com.android.settings
07-27 11:51:22.244  7803  8316 D bt_vendor: op for 7
,07-27 11:51:22.244  7803  8316 D bt_upio : BT_WAKE is asserted already
07-27 11:51:22.244  7803  8349 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
07-27 11:51:22.244  7803  8349 D BluetoothSocket: bindListen(), new LocalSocket 
07-27 11:51:22.244  7803  8349 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-27 11:51:22.244  7803  8349 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16d5ee64
,07-27 11:51:22.244  7803  8349 D BluetoothSocket: channel: 5
,07-27 11:51:22.244   309  1361 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
07-27 11:51:22.244   309  1361 V voice   : voice_set_parameters: enter: A2dpSuspended=false
07-27 11:51:22.244   309  1361 V voice   : voice_set_parameters: exit with code(-2)
07-27 11:51:22.244   309  1361 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
07-27 11:51:22.244   309  1361 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-27 11:51:22.244   309  1361 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-27 11:51:22.244   309  1361 V audio_hw_primary: adev_set_parameters: exit
07-27 11:51:22.244  7803  8304 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
07-27 11:51:22.244  7803  8304 D HeadsetStateMachine: Disconnected process message: 10
,07-27 11:51:22.254  1312  1312 D DockEventReceiver: finishStartingService: stopping service
,07-27 11:51:22.254  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
,07-27 11:51:22.254  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23172ac5
07-27 11:51:22.254  7803  7803 D BtConfig.SecureMode: isSecureModeOn:false
,07-27 11:51:22.254   771  1525 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 11:51:22.254  1188  1188 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 11:51:22.254   771  1525 D ActivityManager: caller:android.app.ApplicationThreadProxy@7ece663, r.packageName :com.android.bluetooth
07-27 11:51:22.254  1188  1188 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-27 11:51:22.254  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 11:51:22.254  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 11:51:22.254  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 11:51:22.254  1188  1188 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 11:51:22.284   771  1469 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-27 11:51:22.294  7803  8357 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 11:51:22.294  7803  8316 D bt_vendor: op for 7
07-27 11:51:22.294  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:22.294  7803  8357 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
07-27 11:51:22.294  7803  8357 D BluetoothSocket: bindListen(), new LocalSocket 
07-27 11:51:22.294  7803  8357 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-27 11:51:22.294  7803  8357 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a358cd0
07-27 11:51:22.294  7803  8357 D BluetoothSocket: channel: 12
,07-27 11:51:22.294  7803  8357 I BtOppRfcommListener: Accept thread started.
,07-27 11:51:22.354  1892  1892 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-27 11:51:22.354   771  1428 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-27 11:51:22.354   771  1428 D ActivityManager: caller:android.app.ApplicationThreadProxy@172c548c, r.packageName :com.google.android.gms
,07-27 11:51:22.374  1892  8361 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-27 11:51:22.374  1892  1892 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-27 11:51:22.384   771  3075 D ActivityManager: caller:android.app.ApplicationThreadProxy@3b0e1c51, r.packageName :com.google.android.gms
,07-27 11:51:22.394  1892  8361 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-27 11:51:23.234   361   361 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 11:51:23.684  7570  7631 D BluetoothAdapter: disable()
,07-27 11:51:23.694   771   796 D SettingsProvider: name = bluetooth_on
,07-27 11:51:23.714  7803  8278 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,07-27 11:51:23.714  7803  8278 D BluetoothAdapterProperties: Setting state to 13
07-27 11:51:23.714  7803  8278 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-27 11:51:23.714  7803  8278 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 11:51:23.714  7803  8278 D BluetoothAdapterService: updateAdapterState state is 13
,07-27 11:51:23.714   771  3266 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 11:51:23.714   771  3266 D ActivityManager: caller:android.app.ApplicationThreadProxy@16f06db7, r.packageName :com.android.bluetooth
,07-27 11:51:23.714  7803  7803 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,07-27 11:51:23.724  7803  8278 D BluetoothAdapterService: Autoconnection is available 
,07-27 11:51:23.724  7803  8278 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
07-27 11:51:23.724  7803  8278 D BluetoothAdapterService: terminating service from this receiver
,07-27 11:51:23.724  7803  7803 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@229484c9, channel: 19, state: LISTENING
,07-27 11:51:23.724  7803  7803 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@229484c9, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d78dff6, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3627f7cemSocket: android.net.LocalSocket@33d976ef impl:android.net.LocalSocketImpl@1aea5fc fd:FileDescriptor[73]
,07-27 11:51:23.724  7803  7803 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@33d976ef impl:android.net.LocalSocketImpl@1aea5fc fd:FileDescriptor[73]
,07-27 11:51:23.734  7803  8278 D BluetoothAdapterProperties: onBluetoothDisable()
,07-27 11:51:23.734   771  1458 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,07-27 11:51:23.734  7803  8278 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,07-27 11:51:23.734  7803  8316 D bt_vendor: op for 7
07-27 11:51:23.734  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:23.734  7803  8316 D bt_vendor: op for 7
,07-27 11:51:23.734  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:23.734  7803  8316 D bt_vendor: op for 7
07-27 11:51:23.734  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:23.734  7803  8281 D BluetoothAdapterProperties: Scan Mode:20
,07-27 11:51:23.734  7803  8278 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-27 11:51:23.734  7803  8278 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,07-27 11:51:23.744  7803  8278 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,07-27 11:51:23.744  7803  8278 E bt-btif : cmd socket is not created
,07-27 11:51:23.744  7803  8278 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-27 11:51:23.744  7803  8316 D bt_vendor: op for 7
,07-27 11:51:23.744  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:23.744  7803  8314 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
,07-27 11:51:23.744  7803  8314 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-27 11:51:23.744  7803  8314 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:51:23.744  7803  8314 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,07-27 11:51:23.744  7803  8314 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 11:51:23.744  7803  8316 D bt_vendor: op for 7
07-27 11:51:23.744  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:23.744  7803  8357 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,07-27 11:51:23.744  7803  8316 D bt_vendor: op for 7
07-27 11:51:23.744  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:23.744  7803  8316 D bt_vendor: op for 7
,07-27 11:51:23.744  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:23.754  7803  8316 D bt_vendor: op for 7
,07-27 11:51:23.754  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:23.754  7803  8316 D bt_vendor: op for 7
,07-27 11:51:23.754  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:23.754  7803  8316 D bt_vendor: op for 7
07-27 11:51:23.754  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:23.754  7570  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-27 11:51:23.754  7803  8316 D bt_vendor: op for 7
07-27 11:51:23.754  7803  8316 D bt_upio : BT_WAKE is asserted already
07-27 11:51:23.754  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:23.754  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:23.754  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:23.754  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:51:23.754  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:51:23.754  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:23.754  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:23.754  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:51:23.754  7803  8316 D bt_vendor: op for 7
07-27 11:51:23.754  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:23.754  7570  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:23.754  7803  8316 D bt_vendor: op for 7
07-27 11:51:23.754  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:23.754  7570  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:51:23.764  7803  8316 D bt_vendor: op for 7
07-27 11:51:23.764  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:23.764  7803  8316 D bt_vendor: op for 7
,07-27 11:51:23.764  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:23.764   771   771 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:51:23.764  1188  1188 D BluetoothTile:  onBluetoothStateChange:
,07-27 11:51:23.764   771   771 I InputMethodManagerService: [BT Setting State] State =13
,07-27 11:51:23.774  1188  1188 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-27 11:51:23.774  1188  1601 D BluetoothTile:  handleUpdatestate:false name:null
,07-27 11:51:23.774  1188  1188 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:51:23.774  1188  1601 D BluetoothTile:  handleUpdatestate:false name:null
,07-27 11:51:23.774  7803  7803 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@15cfc2da, channel: 5, state: LISTENING
,07-27 11:51:23.774  7803  7803 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@15cfc2da, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@16d5ee64, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2570930bmSocket: android.net.LocalSocket@33e25e8 impl:android.net.LocalSocketImpl@a730401 fd:FileDescriptor[75]
07-27 11:51:23.774  7803  7803 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@33e25e8 impl:android.net.LocalSocketImpl@a730401 fd:FileDescriptor[75]
,07-27 11:51:23.774  7803  7803 I BtOppRfcommListener: stopping Accept Thread
07-27 11:51:23.774  7803  7803 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@17f732a6, channel: 12, state: LISTENING
,07-27 11:51:23.774  7803  7803 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@17f732a6, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a358cd0, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@181354e7mSocket: android.net.LocalSocket@35c3b894 impl:android.net.LocalSocketImpl@1d0adf3d fd:FileDescriptor[77]
,07-27 11:51:23.784  7803  7803 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@35c3b894 impl:android.net.LocalSocketImpl@1d0adf3d fd:FileDescriptor[77]
,07-27 11:51:23.784  7803  8357 I BtOppRfcommListener: BluetoothSocket listen thread finished
,07-27 11:51:23.784  7722  7722 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:51:23.784  7570  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:23.784  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:23.784  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:23.784  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:23.784  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:51:23.784  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-27 11:51:23.784  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:23.784  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:23.784  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:51:23.784  1188  1601 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
07-27 11:51:23.784   771  1702 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-27 11:51:23.784   771  1469 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
07-27 11:51:23.784  1188  1188 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
07-27 11:51:23.784  7570  7570 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-27 11:51:23.784  7570  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:51:23.784   771   794 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-27 11:51:23.784   771   794 D ActivityManager: caller:android.app.ApplicationThreadProxy@1856a924, r.packageName :com.google.android.gms
07-27 11:51:23.784  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:23.794  1748  1748 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-27 11:51:23.794  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:23.794  1312  1312 D BluetoothPbap: Proxy object disconnected
07-27 11:51:23.794  1312  1312 D PbapServerProfile: Bluetooth service disconnected
07-27 11:51:23.794  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:51:23.804  1312  1312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-27 11:51:23.804   771  1458 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-27 11:51:23.804   771  1458 D ActivityManager: caller:android.app.ApplicationThreadProxy@1ef1e42, r.packageName :com.android.settings
,07-27 11:51:23.814  1312  1312 D DockEventReceiver: finishStartingService: stopping service
,07-27 11:51:23.814  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
,07-27 11:51:23.844  7803  8314 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:51:23.844  7803  8314 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:51:23.844  7803  8314 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 11:51:23.844  7803  8314 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:51:23.844  7803  8314 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:51:23.844  7803  8314 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 11:51:23.844  7803  8314 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-27 11:51:23.844  7803  8314 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-27 11:51:23.844  7803  8314 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-27 11:51:23.844  7803  8314 W bt-btif : ag scb idx 1 not allocated
07-27 11:51:23.844  7803  8314 W bt-btif : ag scb idx 2 not allocated
07-27 11:51:23.844  7803  8314 E bt-btif : BTA AG is already disabled, ignoring ...
07-27 11:51:23.844  7803  8316 D bt_vendor: op for 6
07-27 11:51:23.844  7803  8316 D bt_vendor: op for 7
07-27 11:51:23.844  7803  8316 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:23.844  7803  8317 D bt_userial: RX termination
07-27 11:51:23.844  7803  8317 W bt_userial: select_read return size <=0:-1, exiting userial_read_thread
07-27 11:51:23.844  7803  8317 D bt_userial: Leaving userial_read_thread()
07-27 11:51:23.844  7803  8281 D bt_userial: userial_close_reader Joined userial reader thread: 0
07-27 11:51:23.844  7803  8316 D bt_vendor: op for 9
07-27 11:51:23.844  7803  8316 D bt_hwcfg: hw_epilog_process
07-27 11:51:23.844  7803  8281 D bt_vendor: op for 4
07-27 11:51:23.844  7803  8281 I bt_userial_vendor: device fd = 66 close
,07-27 11:51:23.854  7803  8281 D bt_vendor: op for 0
,07-27 11:51:23.854  7803  8281 D bt_upio : upio_set_bluetooth_power(on: 0)
07-27 11:51:23.854  7803  8281 D bt_upio : is_emulator_context : 0
07-27 11:51:23.854  7803  8281 D bt_upio : is_rfkill_disabled ? [0]
07-27 11:51:23.854  7803  8281 D bt_vendor: cleanup,
,07-27 11:51:23.854  7803  8314 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-27 11:51:23.854  7803  8281 I GKI_LINUX: GKI_exit_task 0 done
07-27 11:51:23.854  7803  8281 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,07-27 11:51:23.854  7803  8278 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-27 11:51:23.854  7803  8278 D BtConfig.SecureMode: isSecureModeOn:false
07-27 11:51:23.854  7803  8278 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
07-27 11:51:23.854  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
07-27 11:51:23.854  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-27 11:51:23.854  7803  8278 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,07-27 11:51:23.854   771  1458 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 11:51:23.854   771  1458 D ActivityManager: caller:android.app.ApplicationThreadProxy@20e73390, r.packageName :com.android.bluetooth
07-27 11:51:23.854  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
07-27 11:51:23.854  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-27 11:51:23.854  7803  8278 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,07-27 11:51:23.854   771  3266 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 11:51:23.854   771  3266 D ActivityManager: caller:android.app.ApplicationThreadProxy@25870489, r.packageName :com.android.bluetooth
,07-27 11:51:23.854  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
07-27 11:51:23.854  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-27 11:51:23.854  7803  8278 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
07-27 11:51:23.854   771  1310 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 11:51:23.864   771  1310 D ActivityManager: caller:android.app.ApplicationThreadProxy@28d4dc8e, r.packageName :com.android.bluetooth
07-27 11:51:23.864  7803  7803 D BtGatt.DebugUtils: handleDebugAction() action=null
07-27 11:51:23.864  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
07-27 11:51:23.864  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-27 11:51:23.864  7803  7803 D BtGatt.GattService: Received stop request...Stopping profile...
07-27 11:51:23.864  7803  8278 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-27 11:51:23.864  7803  7803 D BtGatt.GattService: stop()
07-27 11:51:23.864  7803  7803 D BtGatt.AdvertiseManager: advertise clients cleared
07-27 11:51:23.864   771  1143 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 11:51:23.864   771  1143 D ActivityManager: caller:android.app.ApplicationThreadProxy@21a95caf, r.packageName :com.android.bluetooth
,07-27 11:51:23.864  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23172ac5
07-27 11:51:23.864  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
07-27 11:51:23.864  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-27 11:51:23.864  7803  8278 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,07-27 11:51:23.864   771  1428 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 11:51:23.864   771  1428 D ActivityManager: caller:android.app.ApplicationThreadProxy@db3f8bc, r.packageName :com.android.bluetooth
,07-27 11:51:23.864  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
07-27 11:51:23.864  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-27 11:51:23.864  7803  8278 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,07-27 11:51:23.864   771  1458 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 11:51:23.864   771  1458 D ActivityManager: caller:android.app.ApplicationThreadProxy@8d26045, r.packageName :com.android.bluetooth
,07-27 11:51:23.864  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
07-27 11:51:23.864  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 11:51:23.864  7803  8278 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,07-27 11:51:23.864   771   794 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 11:51:23.864   771   794 D ActivityManager: caller:android.app.ApplicationThreadProxy@1546339a, r.packageName :com.android.bluetooth
,07-27 11:51:23.864  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
07-27 11:51:23.864  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-27 11:51:23.864  7803  8278 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,07-27 11:51:23.864   771  3266 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 11:51:23.864   771  3266 D ActivityManager: caller:android.app.ApplicationThreadProxy@35b914cb, r.packageName :com.android.bluetooth
07-27 11:51:23.864  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-27 11:51:23.864  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-27 11:51:23.864  7803  8278 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-27 11:51:23.864  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-27 11:51:23.864  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-27 11:51:23.864  7803  8278 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-27 11:51:23.864  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
07-27 11:51:23.864  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-27 11:51:23.864  7803  8278 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-27 11:51:23.864  7803  8278 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
07-27 11:51:23.864  7803  8278 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-27 11:51:23.864  7803  8278 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-27 11:51:23.864  7803  8278 D BluetoothAdapterState: Stopping profile services that were post enabled
07-27 11:51:23.864  7803  7803 E BluetoothAdapterService(588720837): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,07-27 11:51:23.864  7803  7803 D HeadsetService: Received stop request...Stopping profile...
07-27 11:51:23.864  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23172ac5
,07-27 11:51:23.864   771   771 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,07-27 11:51:23.874  7803  7803 D A2dpService: Received stop request...Stopping profile...
,07-27 11:51:23.874  7803  7803 V Avrcp   : doQuit
07-27 11:51:23.874  7722  7722 W BluetoothHeadset: Proxy not attached to service
07-27 11:51:23.874  7803  8307 D A2dpStateMachine: Exit Disconnected: -1
07-27 11:51:23.874  7803  7803 D Avrcp   : Unregistering previous receiver
07-27 11:51:23.874  1312  1312 D HeadsetProfile: Bluetooth service disconnected
,07-27 11:51:23.874  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23172ac5
,07-27 11:51:23.874  3206  3206 D BluetoothA2dp: Proxy object disconnected
,07-27 11:51:23.874  1892  1892 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-27 11:51:23.874  1312  1312 D BluetoothA2dp: Proxy object disconnected
07-27 11:51:23.874   771   771 D BluetoothA2dp: Proxy object disconnected
,07-27 11:51:23.874   771   771 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-27 11:51:23.874  1312  1312 D A2dpProfile: Bluetooth service disconnected
07-27 11:51:23.874  7803  7803 D HidService: Received stop request...Stopping profile...
07-27 11:51:23.874  7803  7803 D HidService: Stopping Bluetooth HidService
07-27 11:51:23.874  7803  7803 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-27 11:51:23.874  7803  7803 W bt-btif : cleanup: HH disabling or disabled already, status = 0
07-27 11:51:23.874  7803  7803 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-27 11:51:23.874  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23172ac5
,07-27 11:51:23.884  1892  1892 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-27 11:51:23.884  7803  7803 D HealthService: Received stop request...Stopping profile...
07-27 11:51:23.884  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23172ac5
,07-27 11:51:23.884  1312  1312 D BluetoothInputDevice: Proxy object disconnected
07-27 11:51:23.884  1312  1312 D HidProfile: Bluetooth service disconnected
,07-27 11:51:23.894  7803  7803 D PanService: Received stop request...Stopping profile...
07-27 11:51:23.894  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23172ac5
,07-27 11:51:23.894   771   771 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-27 11:51:23.894  1312  1312 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-27 11:51:23.894  1312  1312 D PanProfile: Bluetooth service disconnected
,07-27 11:51:23.894  7803  7803 D BluetoothMapService: Received stop request...Stopping profile...
,07-27 11:51:23.894  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23172ac5
,07-27 11:51:23.894  1312  1312 D BluetoothMap: Proxy object disconnected
07-27 11:51:23.894  1312  1312 D MapProfile: Bluetooth service disconnected
07-27 11:51:23.894  7803  7803 D SapService: Received stop request...Stopping profile...
07-27 11:51:23.894  7803  7803 D SapService: Stopping Bluetooth SapService
07-27 11:51:23.894  7803  7803 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@23172ac5
,07-27 11:51:23.894  7803  7803 E BluetoothAdapterService(588720837): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,07-27 11:51:23.894  1312  1312 D Bluetoothsap: BluetoothSAP Proxy object disconnected
07-27 11:51:23.894  7803  7803 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-27 11:51:23.894  7803  7803 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
07-27 11:51:23.894  1312  1312 D SapProfile: Bluetooth service disconnected
,07-27 11:51:23.894  7803  7803 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-27 11:51:23.894  7803  7803 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-27 11:51:23.894  7803  7803 E BluetoothAdapterService(588720837): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
07-27 11:51:23.894  7803  7803 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-27 11:51:23.894  7803  7803 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,07-27 11:51:23.894  7803  7803 D BluetoothA2dp: Proxy object disconnected
07-27 11:51:23.894  7803  7803 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
07-27 11:51:23.894  7803  8308 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
,07-27 11:51:23.894  7803  7803 I GKI_LINUX: GKI_exit_task 2 done
07-27 11:51:23.894  7803  7803 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-27 11:51:23.894  7803  7803 V Avrcp   : cleanup
07-27 11:51:23.894  7803  7803 E BluetoothAdapterService(588720837): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
07-27 11:51:23.894  7803  7803 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 11:51:23.894  7803  7803 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,07-27 11:51:23.894  7803  7803 E BluetoothAdapterService(588720837): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
07-27 11:51:23.894  7803  7803 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 11:51:23.894  7803  7803 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-27 11:51:23.894  7803  7803 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,07-27 11:51:23.894  7803  7803 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-27 11:51:23.894  7803  7803 E BluetoothAdapterService(588720837): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
07-27 11:51:23.894  7803  7803 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 11:51:23.894  7803  7803 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-27 11:51:23.894  7803  7803 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-27 11:51:23.894  7803  7803 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-27 11:51:23.894  7803  7803 E BluetoothAdapterService(588720837): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
07-27 11:51:23.894  7803  7803 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-27 11:51:23.894  7803  7803 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
07-27 11:51:23.894  7803  7803 E BluetoothAdapterService(588720837): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,07-27 11:51:23.894  7803  7803 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
07-27 11:51:23.894  7803  7803 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
07-27 11:51:23.894  7803  8278 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
07-27 11:51:23.894  7803  8278 D BluetoothAdapterProperties: Setting state to 10
07-27 11:51:23.894  7803  8278 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-27 11:51:23.894  7803  8278 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 11:51:23.894  7803  8278 D BluetoothAdapterService: updateAdapterState state is 10
07-27 11:51:23.904  7803  8278 D BluetoothAdapterService: Autoconnection is available 
07-27 11:51:23.904  7803  8278 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
07-27 11:51:23.904  7803  8278 I BluetoothAdapterState: Entering OffState
,07-27 11:51:23.904  1312  1339 D BluetoothMap: onBluetoothStateChange: up=false
07-27 11:51:23.904   771  1045 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-27 11:51:23.904  1312  1340 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-27 11:51:23.904  3206  8347 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-27 11:51:23.904  1312  1326 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-27 11:51:23.904  7803  8346 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-27 11:51:23.904  1312  1339 D BluetoothPbap: onBluetoothStateChange: up=false
07-27 11:51:23.904  1312  1340 D Bluetoothsap: onBluetoothStateChange: up=false
,07-27 11:51:23.904  1312  1340 D Bluetoothsap: Unbinding service...
,07-27 11:51:23.904   771  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 14 receivers.
,07-27 11:51:23.904   771  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,07-27 11:51:23.914   771   771 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:51:23.914   771   771 I InputMethodManagerService: [BT Setting State] State =10
07-27 11:51:23.914   771   771 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
07-27 11:51:23.914  1188  1188 D BluetoothAdapter: 375652811: getState() :  mService = null. Returning STATE_OFF
,07-27 11:51:23.914  1188  1188 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-27 11:51:23.914  1188  1188 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:23.914  1188  1601 D BluetoothAdapter: 375652811: getState() :  mService = null. Returning STATE_OFF
07-27 11:51:23.914  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:23.914  1188  1188 D BluetoothAdapter: 375652811: getState() :  mService = null. Returning STATE_OFF
07-27 11:51:23.914  1188  1601 D BluetoothAdapter: 375652811: getState() :  mService = null. Returning STATE_OFF
,07-27 11:51:23.914  1188  1601 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-27 11:51:23.914  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:23.914   771  1469 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-27 11:51:23.914  1892  2393 D BluetoothAdapter: 34077501: getState() :  mService = null. Returning STATE_OFF
07-27 11:51:23.914  1892  2393 D BluetoothAdapter: 34077501: getState() :  mService = null. Returning STATE_OFF
07-27 11:51:23.914  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:23.914   771  1469 D ActivityManager: caller:android.app.ApplicationThreadProxy@2425e4a8, r.packageName :com.google.android.gms
07-27 11:51:23.914  1188  1188 D BluetoothAdapter: 375652811: getState() :  mService = null. Returning STATE_OFF
07-27 11:51:23.914  7722  7722 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:23.914  1748  1748 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
07-27 11:51:23.914  1312  1312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-27 11:51:23.914   771  1506 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-27 11:51:23.914   771  1525 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-27 11:51:23.914  1188  1188 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-27 11:51:23.914   771   796 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-27 11:51:23.914   771   796 D ActivityManager: caller:android.app.ApplicationThreadProxy@3543ef66, r.packageName :com.android.settings
,07-27 11:51:23.924  7803  8281 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,07-27 11:51:23.924  7803  7803 I GKI_LINUX: GKI_exit_task 1 done
,07-27 11:51:23.924  7803  7803 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,07-27 11:51:23.924  7803  7803 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-27 11:51:23.924  1312  1312 D DockEventReceiver: finishStartingService: stopping service
,07-27 11:51:23.924  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
,07-27 11:51:23.924  7803  7803 I art     : System.exit called, status: 0
07-27 11:51:23.924  7803  7803 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-27 11:51:23.974   771  1428 I ActivityManager: Process com.android.bluetooth (pid 7803)(adj 0) has died(185,1568)
,07-27 11:51:23.984  1892  1892 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-27 11:51:23.984   771  1458 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-27 11:51:23.984   771  1458 D ActivityManager: caller:android.app.ApplicationThreadProxy@40f9bf2, r.packageName :com.google.android.gms
,07-27 11:51:23.994  1892  8398 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-27 11:51:23.994  1892  1892 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-27 11:51:23.994   771  1458 D ActivityManager: caller:android.app.ApplicationThreadProxy@3536a0c0, r.packageName :com.google.android.gms
,07-27 11:51:24.004  1892  8398 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-27 11:51:24.234   361   361 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,07-27 11:51:24.974   304   304 E SMD     : DCD ON
,07-27 11:51:26.794  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
,07-27 11:51:26.794  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:51:27.745   771  1338 E Watchdog: !@Sync 11
,07-27 11:51:27.974   304   304 E SMD     : DCD ON
,07-27 11:51:29.244   361   361 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 11:51:29.804  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 11:51:29.804  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@15a080cf added. We now have 6 listener(s)
,07-27 11:51:29.804  7570  7631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 11:51:29.814  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 11:51:29.814  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bb01a5c added. We now have 7 listener(s)
07-27 11:51:29.814  7570  7631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 11:51:29.814  7570  7631 I System.out: IsBluetoothEnabled
,07-27 11:51:29.814  7570  7631 D BluetoothAdapter: disable()
07-27 11:51:29.814   771  1525 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,07-27 11:51:29.834  7570  7631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:29.834  7570  7631 D BluetoothAdapter: enable()
,07-27 11:51:29.834   771  1310 W ActivityManager: Permission Denial: getCurrentUser() from pid=7570, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-27 11:51:29.834   771  1310 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-27 11:51:29.834   771  1310 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7570, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-27 11:51:29.834   771  1310 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-27 11:51:29.834   771  1310 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
07-27 11:51:29.834   771  1310 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
07-27 11:51:29.834   771  1310 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-27 11:51:29.834   771  1310 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,07-27 11:51:29.834   771  1310 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-27 11:51:29.834   771  1310 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 11:51:29.834   771  1310 D SettingsProvider: name = bluetooth_on
,07-27 11:51:29.845   771  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 11:51:29.845   771  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 11:51:29.845   771  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,07-27 11:51:29.845   771  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:29.845   771  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:29.845   771  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:29.845   771  1045 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:29.894  8411  8411 E Zygote  : MountEmulatedStorage()
,07-27 11:51:29.894   771  1045 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=8411 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,07-27 11:51:29.904  8411  8411 E Zygote  : v2
,07-27 11:51:29.904  8411  8411 I libpersona: KNOX_SDCARD checking this for 1002
07-27 11:51:29.904  8411  8411 I libpersona: KNOX_SDCARD not a persona
,07-27 11:51:29.914  8411  8411 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-27 11:51:29.914  8411  8411 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 11:51:29.914  8411  8411 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 11:51:29.924   771  3104 D SSRM:n  : SIOP:: AP = 340, PST = 327, CUR = 450
,07-27 11:51:29.954  8411  8411 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:29.954  8411  8411 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:29.974  8411  8411 D ResourcesManager: creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,07-27 11:51:29.974  8411  8411 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,07-27 11:51:29.974  8411  8411 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-27 11:51:29.994  8411  8411 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,07-27 11:51:30.024  8411  8411 D BtSettings.ProfileConfig: Adding GattService
,07-27 11:51:30.024  8411  8411 D BtSettings.ProfileConfig: Adding HeadsetService
,07-27 11:51:30.024  8411  8411 D BtSettings.ProfileConfig: Adding A2dpService
07-27 11:51:30.024  8411  8411 D BtSettings.ProfileConfig: Adding HidService
,07-27 11:51:30.024  8411  8411 D BtSettings.ProfileConfig: Adding HealthService
07-27 11:51:30.024  8411  8411 D BtSettings.ProfileConfig: Adding PanService
,07-27 11:51:30.024  8411  8411 D BtSettings.ProfileConfig: Adding BluetoothMapService
07-27 11:51:30.024  8411  8411 D BtSettings.ProfileConfig: Adding SapService
,07-27 11:51:30.024  8411  8411 D BtSettings.ProfileConfig: Adding HeadsetClientService
07-27 11:51:30.024  8411  8411 D BtSettings.ProfileConfig: Adding A2dpSinkService
,07-27 11:51:30.024  8411  8411 D BtSettings.ProfileConfig: Adding SapClientService
07-27 11:51:30.024  8411  8411 D BtSettings.ProfileConfig: Adding HidDevService
,07-27 11:51:30.034  8411  8411 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,07-27 11:51:30.034   771  1567 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
07-27 11:51:30.034   771  1567 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:30.034   771  1567 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:30.034   771  1567 D SettingsProvider: selectionArgs: false
07-27 11:51:30.034   771  1567 D SettingsProvider: selectionArgs: 1002
07-27 11:51:30.034   771  1567 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:30.034   771  1567 D SettingsProvider: ret = -1
,07-27 11:51:30.034   771  1673 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
07-27 11:51:30.034   771  1673 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:30.034   771  1673 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:30.034   771  1673 D SettingsProvider: selectionArgs: false
07-27 11:51:30.034   771  1673 D SettingsProvider: selectionArgs: 1002
07-27 11:51:30.034   771  1673 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:30.034   771  1673 D SettingsProvider: ret = -1
07-27 11:51:30.034   771   794 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
07-27 11:51:30.034   771   794 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:30.034   771   794 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:30.034   771   794 D SettingsProvider: selectionArgs: false
07-27 11:51:30.034   771   794 D SettingsProvider: selectionArgs: 1002
07-27 11:51:30.034   771   794 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:30.034   771   794 D SettingsProvider: ret = -1
,07-27 11:51:30.034   771  1428 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
07-27 11:51:30.034   771  1428 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:30.034   771  1428 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:30.034   771  1428 D SettingsProvider: selectionArgs: false
07-27 11:51:30.034   771  1428 D SettingsProvider: selectionArgs: 1002
07-27 11:51:30.034   771  1428 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-27 11:51:30.034   771  1428 D SettingsProvider: ret = -1
07-27 11:51:30.034   771  1702 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
07-27 11:51:30.034   771  1702 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:30.034   771  1702 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:30.034   771  1702 D SettingsProvider: selectionArgs: false
07-27 11:51:30.034   771  1702 D SettingsProvider: selectionArgs: 1002
07-27 11:51:30.034   771  1702 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:30.034   771  1702 D SettingsProvider: ret = -1
,07-27 11:51:30.034   771  1458 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
07-27 11:51:30.034   771  1458 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:30.034   771  1458 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:30.034   771  1458 D SettingsProvider: selectionArgs: false
07-27 11:51:30.034   771  1458 D SettingsProvider: selectionArgs: 1002
07-27 11:51:30.034   771  1458 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:30.034   771  1458 D SettingsProvider: ret = -1
,07-27 11:51:30.034   771  1469 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
07-27 11:51:30.034   771  1469 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:30.034   771  1469 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:30.034   771  1469 D SettingsProvider: selectionArgs: false
07-27 11:51:30.034   771  1469 D SettingsProvider: selectionArgs: 1002
07-27 11:51:30.034   771  1469 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-27 11:51:30.034   771  1469 D SettingsProvider: ret = -1
07-27 11:51:30.034   771  1318 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
07-27 11:51:30.034   771  1318 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:30.034   771  1318 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:30.034   771  1318 D SettingsProvider: selectionArgs: false
07-27 11:51:30.034   771  1318 D SettingsProvider: selectionArgs: 1002
07-27 11:51:30.034   771  1318 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:30.034   771  1318 D SettingsProvider: ret = -1
,07-27 11:51:30.034   771  3075 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
07-27 11:51:30.034   771  3075 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:30.034   771  3075 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:30.034   771  3075 D SettingsProvider: selectionArgs: false
07-27 11:51:30.034   771  3075 D SettingsProvider: selectionArgs: 1002
07-27 11:51:30.034   771  3075 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:30.034   771  3075 D SettingsProvider: ret = -1
07-27 11:51:30.034   771  1506 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,07-27 11:51:30.034   771  1506 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:30.034   771  1506 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:30.034   771  1506 D SettingsProvider: selectionArgs: false
07-27 11:51:30.034   771  1506 D SettingsProvider: selectionArgs: 1002
07-27 11:51:30.034   771  1506 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:30.034   771  1506 D SettingsProvider: ret = -1
07-27 11:51:30.034   771   796 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
07-27 11:51:30.034   771   796 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,07-27 11:51:30.034   771   796 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:30.034   771   796 D SettingsProvider: selectionArgs: false
07-27 11:51:30.034   771   796 D SettingsProvider: selectionArgs: 1002
07-27 11:51:30.034   771   796 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:30.034   771   796 D SettingsProvider: ret = -1
,07-27 11:51:30.044   771  1360 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
07-27 11:51:30.044   771  1360 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:30.044   771  1360 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:30.044   771  1360 D SettingsProvider: selectionArgs: false
,07-27 11:51:30.044   771  1360 D SettingsProvider: selectionArgs: 1002
07-27 11:51:30.044   771  1360 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:30.044   771  1360 D SettingsProvider: ret = -1
,07-27 11:51:30.054  8411  8411 D BluetoothAdapterState: make
,07-27 11:51:30.064  8411  8411 I bluedroid: init
,07-27 11:51:30.064  8411  8436 I BluetoothAdapterState: Entering OffState
,07-27 11:51:30.064  8411  8411 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-27 11:51:30.064  8411  8411 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-27 11:51:30.064  8411  8411 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-27 11:51:30.064  8411  8411 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
07-27 11:51:30.064  8411  8411 E bt-btif : btif_fetch_local_ble_random_bdaddr
07-27 11:51:30.064  8411  8411 I bluedroid: get_profile_interface socket
07-27 11:51:30.064  8411  8439 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-27 11:51:30.064  8411  8411 I bluedroid: get_profile_interface map_client
,07-27 11:51:30.064  8411  8411 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,07-27 11:51:30.064  8411  8439 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
,07-27 11:51:30.064  8411  8439 E BluetoothServiceJni: populateRssiValuesNative
07-27 11:51:30.064  8411  8439 I bluedroid: getModelRssiValues
07-27 11:51:30.064  8411  8439 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
07-27 11:51:30.064  8411  8439 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-27 11:51:30.064   771   771 D SettingsProvider: name = bluetooth_name
07-27 11:51:30.064  8411  8439 D BluetoothAdapterProperties: Name is: Note3-1
,07-27 11:51:30.074   771  1469 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-27 11:51:30.074  8411  8419 I bluedroid: config_hci_snoop_log
,07-27 11:51:30.074   771  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 14 receivers.
,07-27 11:51:30.074   771  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-27 11:51:30.074   771  1045 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-27 11:51:30.084   771  1045 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,07-27 11:51:30.084  8411  8436 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
07-27 11:51:30.084  8411  8436 D BluetoothAdapterProperties: Setting state to 11
07-27 11:51:30.084  8411  8436 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-27 11:51:30.084  8411  8436 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,07-27 11:51:30.084  8411  8436 D BluetoothAdapterService: updateAdapterState state is 11
07-27 11:51:30.084  8411  8436 D BluetoothAdapterService: Autoconnection is available 
07-27 11:51:30.084  8411  8436 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,07-27 11:51:30.084   771   771 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:30.084   771   771 I InputMethodManagerService: [BT Setting State] State =11
,07-27 11:51:30.084  1748  1748 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-27 11:51:30.084  7722  7722 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:51:30.084  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:51:30.084   771   796 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-27 11:51:30.084  1188  1188 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-27 11:51:30.084  1188  1188 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:30.084   771   796 D ActivityManager: caller:android.app.ApplicationThreadProxy@232de8f, r.packageName :com.google.android.gms
,07-27 11:51:30.084  8411  8436 D BluetoothSecureManager: getInstant: null
,07-27 11:51:30.094  8411  8436 D BluetoothSecureManager: calling getMethod for getService
07-27 11:51:30.094   771  1469 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-27 11:51:30.094  8411  8436 D BluetoothSecureManager: calling getService
,07-27 11:51:30.094   771  1310 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
07-27 11:51:30.094  1188  1188 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-27 11:51:30.094  8411  8436 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@12c817d4
07-27 11:51:30.094   771  1143 D BluetoothSecureManagerService: isSecureModeEnabled
07-27 11:51:30.094   771  1143 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,07-27 11:51:30.094  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:30.094  8411  8436 D BtConfig.SecureMode: isSecureModeOn:false
07-27 11:51:30.094  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-27 11:51:30.094  1188  1601 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-27 11:51:30.094  8411  8436 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
07-27 11:51:30.094  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-27 11:51:30.094  8411  8436 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
07-27 11:51:30.094  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-27 11:51:30.094  8411  8436 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
07-27 11:51:30.094  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
,07-27 11:51:30.094  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-27 11:51:30.094  8411  8436 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
07-27 11:51:30.094  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-27 11:51:30.094  8411  8436 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
07-27 11:51:30.094  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-27 11:51:30.094  8411  8436 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
07-27 11:51:30.094  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-27 11:51:30.094  8411  8436 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
07-27 11:51:30.104  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,07-27 11:51:30.104  8411  8436 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
07-27 11:51:30.104  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-27 11:51:30.104  8411  8436 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-27 11:51:30.104  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,07-27 11:51:30.104  8411  8436 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
07-27 11:51:30.104  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,07-27 11:51:30.104  8411  8436 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
07-27 11:51:30.104  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-27 11:51:30.104  8411  8436 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,07-27 11:51:30.104  8411  8436 D BluetoothBondStateMachine: make
,07-27 11:51:30.104  8411  8436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,07-27 11:51:30.104  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-27 11:51:30.104  8411  8436 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,07-27 11:51:30.114  8411  8443 I BluetoothBondStateMachine: StableState(): Entering Off State
07-27 11:51:30.114   771  1702 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 11:51:30.114   771  1702 D ActivityManager: caller:android.app.ApplicationThreadProxy@9196525, r.packageName :com.android.bluetooth
,07-27 11:51:30.114  8411  8411 I BtGatt.JNI: classInitNative(L890): classInitNative: Success!
,07-27 11:51:30.114  8411  8436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,07-27 11:51:30.114  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-27 11:51:30.114  8411  8436 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
07-27 11:51:30.114   771  1525 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 11:51:30.124   771  1525 D ActivityManager: caller:android.app.ApplicationThreadProxy@2188d4ab, r.packageName :com.android.bluetooth
,07-27 11:51:30.124  8411  8436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
07-27 11:51:30.124  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-27 11:51:30.124  8411  8436 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,07-27 11:51:30.124   771  1469 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 11:51:30.124   771  1469 D ActivityManager: caller:android.app.ApplicationThreadProxy@f202ea1, r.packageName :com.android.bluetooth
07-27 11:51:30.124  8411  8411 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-27 11:51:30.124  8411  8411 D BtGatt.GattService: Received start request. Starting profile...
07-27 11:51:30.124  8411  8411 D BtGatt.GattService: start()
07-27 11:51:30.124  8411  8411 I bluedroid: get_profile_interface gatt
,07-27 11:51:30.124  8411  8411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd5832f
07-27 11:51:30.124  8411  8411 D BtGatt.AdvertiseManager: advertise manager created
,07-27 11:51:30.124  8411  8436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
07-27 11:51:30.124  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-27 11:51:30.124  8411  8436 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,07-27 11:51:30.124   771  1310 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 11:51:30.124   771  1310 D ActivityManager: caller:android.app.ApplicationThreadProxy@27fe1087, r.packageName :com.android.bluetooth
,07-27 11:51:30.124  8411  8436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,07-27 11:51:30.124  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-27 11:51:30.124  8411  8436 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-27 11:51:30.124   771  3075 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 11:51:30.124   771  3075 D ActivityManager: caller:android.app.ApplicationThreadProxy@147013dd, r.packageName :com.android.bluetooth
,07-27 11:51:30.134  8411  8436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,07-27 11:51:30.134  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-27 11:51:30.134  8411  8436 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-27 11:51:30.134   771  1673 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 11:51:30.134   771  1673 D ActivityManager: caller:android.app.ApplicationThreadProxy@ef27a9e, r.packageName :com.android.bluetooth
,07-27 11:51:30.134  8411  8436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
07-27 11:51:30.134  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-27 11:51:30.134  8411  8436 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,07-27 11:51:30.134   771   794 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-27 11:51:30.134   771   794 D ActivityManager: caller:android.app.ApplicationThreadProxy@270f6d4c, r.packageName :com.android.bluetooth
,07-27 11:51:30.134  8411  8411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd5832f
,07-27 11:51:30.134  8411  8436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,07-27 11:51:30.134  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-27 11:51:30.134  8411  8436 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-27 11:51:30.134   771  1428 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 11:51:30.134   771  1428 D ActivityManager: caller:android.app.ApplicationThreadProxy@2307a2aa, r.packageName :com.android.bluetooth
07-27 11:51:30.134  8411  8411 D HeadsetService: Received start request. Starting profile...
,07-27 11:51:30.144  8411  8411 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-27 11:51:30.144  8411  8411 D HeadsetStateMachine: make
07-27 11:51:30.144  8411  8436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,07-27 11:51:30.144  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-27 11:51:30.144  8411  8436 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-27 11:51:30.144  8411  8436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-27 11:51:30.144  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-27 11:51:30.144  8411  8436 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-27 11:51:30.144  8411  8436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,07-27 11:51:30.144  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-27 11:51:30.144  8411  8436 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-27 11:51:30.144  8411  8436 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
07-27 11:51:30.144  8411  8436 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-27 11:51:30.144  8411  8436 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,07-27 11:51:30.144  8411  8436 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,07-27 11:51:30.144  8411  8411 E HeadsetStateMachine: # of Max HF connection is 2
,07-27 11:51:30.154   771  1360 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,07-27 11:51:30.154   771  1310 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
,07-27 11:51:30.154  8411  8411 I bluedroid: get_profile_interface handsfree
,07-27 11:51:30.164  8411  8411 I DualScoManager: Instantiating Dual Sco Manager
07-27 11:51:30.164  8411  8411 I DualScoManager: Set HeadsetServiceHelper
,07-27 11:51:30.164  8411  8411 D BluetoothAtMessage: createCMTIContentObservers
,07-27 11:51:30.164   771   794 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
07-27 11:51:30.164   771   794 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:30.164   771   794 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,07-27 11:51:30.164   771   794 D SettingsProvider: selectionArgs: false
07-27 11:51:30.164   771   794 D SettingsProvider: selectionArgs: 1002
07-27 11:51:30.164   771   794 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:30.164   771   794 D SettingsProvider: ret = -1
,07-27 11:51:30.164  8411  8446 D HeadsetStateMachine: Enter Disconnected: -2
07-27 11:51:30.174  8411  8446 E HeadsetStateMachine: set to mRemoteBrsf = 0
,07-27 11:51:30.174  8411  8411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd5832f
,07-27 11:51:30.174  1892  1892 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-27 11:51:30.174  8411  8411 D A2dpService: Received start request. Starting profile...
,07-27 11:51:30.174  8411  8446 D HeadsetStateMachine: map size, before remove : 0
07-27 11:51:30.174  8411  8446 D HeadsetStateMachine: map size, after remove: 0
07-27 11:51:30.174  8411  8446 D HeadsetStateMachine: mNextConnectingDevice : null
,07-27 11:51:30.174  1892  1892 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-27 11:51:30.174  8411  8411 I BluetoothAvrcpServiceJni: classInitNative: succeeds
07-27 11:51:30.174  8411  8411 V Avrcp   : make
,07-27 11:51:30.174  8411  8411 V Avrcp   : Avrcp
,07-27 11:51:30.184  8411  8411 I bluedroid: get_profile_interface avrcp
,07-27 11:51:30.184  8411  8411 V Avrcp   : start
,07-27 11:51:30.184  8411  8411 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-27 11:51:30.184  8411  8411 V Avrcp   : ++registerMediaPlayers++
,07-27 11:51:30.184  8411  8411 I Avrcp   : No of Audio players :: 2
,07-27 11:51:30.184  8411  8411 I Avrcp   : App Package name is com.google.android.music
,07-27 11:51:30.194  8411  8411 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-27 11:51:30.194  8411  8411 I Avrcp   : App pkg name is Google Play Music
,07-27 11:51:30.194  8411  8411 I Avrcp   : Name::Google Play Music
07-27 11:51:30.194  8411  8411 V Avrcp   : MediaPlayerInfo: mPlayerId=1
07-27 11:51:30.194  8411  8411 I Avrcp   : App Package name is com.sec.android.app.music
,07-27 11:51:30.194  8411  8411 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,07-27 11:51:30.194  8411  8411 I Avrcp   : App pkg name is Music
,07-27 11:51:30.194  8411  8411 I Avrcp   : Name::Music
07-27 11:51:30.194  8411  8411 V Avrcp   : MediaPlayerInfo: mPlayerId=2
07-27 11:51:30.204  8411  8411 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,07-27 11:51:30.204  8411  8411 I Avrcp   : No of Video players :: 1
,07-27 11:51:30.204  8411  8411 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
07-27 11:51:30.204  8411  8411 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
07-27 11:51:30.204  8411  8411 I Avrcp   : Video App pkg name is Video Player
07-27 11:51:30.204  8411  8411 I Avrcp   : Name::Video Player
07-27 11:51:30.204  8411  8411 V Avrcp   : MediaPlayerInfo: mPlayerId=3
07-27 11:51:30.204  8411  8411 I Avrcp   : Add tempPlayer
07-27 11:51:30.204  8411  8411 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-27 11:51:30.204  8411  8411 I Avrcp   : Total no of players: 4
07-27 11:51:30.204  8411  8411 V Avrcp   : swapping the samsung player with 1st player
,07-27 11:51:30.204  8411  8411 I Avrcp   :  Updating now playing list upon AVRCP Start
07-27 11:51:30.204  8411  8449 V Avrcp   : handleMessage, msg=207
,07-27 11:51:30.204  8411  8449 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,07-27 11:51:30.204  8411  8411 I BluetoothA2dpServiceJni: classInitNative: succeeds
,07-27 11:51:30.214  8411  8411 D A2dpStateMachine: make
,07-27 11:51:30.214  8411  8411 I bluedroid: get_profile_interface a2dp
,07-27 11:51:30.214  8411  8451 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-27 11:51:30.214  8411  8411 E bt-btif : warning : media task started media_task_refcnt 1 
,07-27 11:51:30.214  8411  8449 D BluetoothMediaBrowser: no now playing list
07-27 11:51:30.214  8411  8449 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,07-27 11:51:30.214  8411  8449 D Avrcp   :  checkNowPlayingList start
,07-27 11:51:30.214  8411  8411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd5832f
07-27 11:51:30.214  8411  8450 D A2dpStateMachine: Enter Disconnected: -2
,07-27 11:51:30.214  8411  8411 I BluetoothHidServiceJni: classInitNative: succeeds
,07-27 11:51:30.214  8411  8411 D HidService: Received start request. Starting profile...
07-27 11:51:30.214  8411  8411 I bluedroid: get_profile_interface hidhost
,07-27 11:51:30.214  8411  8411 D HidService: setHidService(): set to: null
07-27 11:51:30.214  8411  8411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd5832f
07-27 11:51:30.214  8411  8411 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-27 11:51:30.224  8411  8411 D HealthService: Received start request. Starting profile...
,07-27 11:51:30.224  8411  8411 I bluedroid: get_profile_interface health
,07-27 11:51:30.224  8411  8411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd5832f
,07-27 11:51:30.224  8411  8411 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-27 11:51:30.224  8411  8411 D PanService: Received start request. Starting profile...
,07-27 11:51:30.224  8411  8411 D BluetoothPanServiceJni: initializeNative(L110): pan
07-27 11:51:30.224  8411  8411 I bluedroid: get_profile_interface pan
,07-27 11:51:30.224  8411  8411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd5832f
,07-27 11:51:30.224  8411  8411 E BluetoothAdapterService(500532015): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,07-27 11:51:30.234  8411  8411 D BluetoothMapService: Received start request. Starting profile...
,07-27 11:51:30.244   361   361 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 11:51:30.254  8411  8411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd5832f
,07-27 11:51:30.254  8411  8411 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,07-27 11:51:30.254  8411  8411 D SapService: Received start request. Starting profile...
07-27 11:51:30.254  8411  8411 D BluetoothSAPServiceJni: initializeNative(L209): sap
07-27 11:51:30.254  8411  8411 I bluedroid: get_profile_interface sap
07-27 11:51:30.254  8411  8411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd5832f
,07-27 11:51:30.254  8411  8411 D HeadsetStateMachine: Try to query the phonestate on bind
,07-27 11:51:30.254  1405  1414 I Telecom : BluetoothPhoneService: queryPhoneState
,07-27 11:51:30.254  1405  1405 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
07-27 11:51:30.254  8411  8411 D HeadsetStateMachine: Proxy object connected
,07-27 11:51:30.254  8411  8411 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
07-27 11:51:30.254  8411  8411 D HeadsetPhoneState: sendDeviceDataStateChanged
07-27 11:51:30.254  8411  8446 D HeadsetStateMachine: Disconnected process message: 11
,07-27 11:51:30.254  8411  8446 D HeadsetStateMachine: Disconnected process message: 18
07-27 11:51:30.254  8411  8411 D HeadsetPhoneState: Signal level : previous=0 curr=0
07-27 11:51:30.254  8411  8411 E BluetoothAdapterService(500532015): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
07-27 11:51:30.254  8411  8411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 11:51:30.254  8411  8446 D HeadsetStateMachine: Disconnected process message: 10
07-27 11:51:30.254  8411  8411 D BluetoothA2dp: Proxy object connected
07-27 11:51:30.254  8411  8446 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-27 11:51:30.254  8411  8446 D HeadsetStateMachine: Disconnected process message: 11
07-27 11:51:30.254  8411  8411 D BluetoothAdapterService: Bluetooth A2dp source service connected
,07-27 11:51:30.264  8411  8411 E BluetoothAdapterService(500532015): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,07-27 11:51:30.264  8411  8411 E BluetoothAdapterService(500532015): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
07-27 11:51:30.264  8411  8411 E BluetoothAdapterService(500532015): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
07-27 11:51:30.264  8411  8411 E BluetoothAdapterService(500532015): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,07-27 11:51:30.264  8411  8411 E BluetoothAdapterService(500532015): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,07-27 11:51:30.264  8411  8411 E BluetoothAdapterService(500532015): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
07-27 11:51:30.264  8411  8436 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
07-27 11:51:30.264  8411  8436 I bluedroid: enable
,07-27 11:51:30.264  8411  8436 I bt_hci_bdroid: init
,07-27 11:51:30.264  8411  8436 I bt_vendor: init
07-27 11:51:30.264  8411  8436 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-27 11:51:30.264  8411  8436 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
07-27 11:51:30.264  8411  8436 D bt_userial: userial_init
07-27 11:51:30.264  8411  8436 D bt_vendor: op for 5
07-27 11:51:30.264  8411  8455 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-27 11:51:30.264  8411  8436 D bt_vendor: op for 0
,07-27 11:51:30.264  8411  8436 D bt_upio : upio_set_bluetooth_power(on: 0)
07-27 11:51:30.264  8411  8436 D bt_upio : is_emulator_context : 0
07-27 11:51:30.264  8411  8436 D bt_upio : is_rfkill_disabled ? [0]
07-27 11:51:30.264  8411  8436 D bt_upio : is_rfkill_disabled ? [0]
07-27 11:51:30.264  8411  8436 D bt_vendor: op for 0
07-27 11:51:30.264  8411  8436 D bt_upio : upio_set_bluetooth_power(on: 1)
07-27 11:51:30.264  8411  8436 D bt_upio : is_emulator_context : 0
07-27 11:51:30.264  8411  8436 D bt_upio : is_rfkill_disabled ? [0]
,07-27 11:51:30.264  8411  8457 D bt_vendor: op for 3
07-27 11:51:30.264  8411  8457 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-27 11:51:30.274  8411  8457 I bt_userial_vendor: userial_vendor_open():UART is setup
07-27 11:51:30.274  8411  8457 I bt_userial_vendor: device fd = 65 open
,07-27 11:51:30.274  8411  8457 D bt_vendor: op for 1
07-27 11:51:30.274  8411  8457 E bt_hwcfg: Start CFG HW, HCI reset
07-27 11:51:30.274  8411  8458 D bt_userial: Entering userial_read_thread()
,07-27 11:51:30.354  8411  8457 E bt_hwcfg: Read Local Name after HCI reset
,07-27 11:51:30.374  8411  8457 D bt_hwcfg: Chipset BCM4335C0
07-27 11:51:30.374  8411  8457 D bt_hwcfg: Target name = [BCM4335C0]
,07-27 11:51:30.374  8411  8457 I bt_hwcfg: module_type[semco].
07-27 11:51:30.374  8411  8457 I bt_hwcfg: not ZERO...
07-27 11:51:30.374  8411  8457 I bt_hwcfg: module_type[semco] is invalid.
07-27 11:51:30.374  8411  8457 E bt_hwcfg: patchram path ORG . BCM4335C0
07-27 11:51:30.374  8411  8457 E bt_hwcfg: patchram path ORG .. BCM4335C0
07-27 11:51:30.374  8411  8457 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
07-27 11:51:30.374  8411  8457 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
07-27 11:51:30.374  8411  8457 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
07-27 11:51:30.374  8411  8457 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
07-27 11:51:30.374  8411  8457 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335C0
07-27 11:51:30.374  8411  8457 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559_wisol.hcd BCM4335C0
07-27 11:51:30.374  8411  8457 E bt_hwcfg: fw ver (org)0.0
07-27 11:51:30.374  8411  8457 E bt_hwcfg: vendor lib preload failed to locate firmware patch file
07-27 11:51:30.374  8411  8457 E bt_hwcfg: Remove module rev, try again BCM4335
07-27 11:51:30.374  8411  8457 D bt_hwcfg: Target name = [BCM4335]
07-27 11:51:30.374  8411  8457 I bt_hwcfg: module_type[semco].
07-27 11:51:30.374  8411  8457 I bt_hwcfg: not ZERO...
07-27 11:51:30.374  8411  8457 I bt_hwcfg: module_type[semco] is invalid.
07-27 11:51:30.374  8411  8457 E bt_hwcfg: patchram path ORG . BCM4335
07-27 11:51:30.374  8411  8457 E bt_hwcfg: patchram path ORG .. BCM4335
07-27 11:51:30.374  8411  8457 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335
07-27 11:51:30.374  8411  8457 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
07-27 11:51:30.374  8411  8457 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335
07-27 11:51:30.374  8411  8457 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
07-27 11:51:30.374  8411  8457 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335
07-27 11:51:30.374  8411  8457 I bt_hwcfg: patch(org) : bcm4335_V0111.0559.hcd
07-27 11:51:30.374  8411  8457 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4335_V0111.0559.hcd
07-27 11:51:30.374  8411  8457 E bt_hwcfg: ORG patchram base 0111
07-27 11:51:30.374  8411  8457 E bt_hwcfg: ORG patchram minor 0559
07-27 11:51:30.374  8411  8457 E bt_hwcfg: fw ver (org)111.559
07-27 11:51:30.374  8411  8457 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4335_V0111.0559.hcd
,07-27 11:51:30.384  8411  8457 I bt_hwcfg: Axi patch failure or not include AXI patching
,07-27 11:51:30.394  8411  8457 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-27 11:51:30.884  8411  8457 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-27 11:51:30.884  8411  8457 I bt_hwcfg: FW Download delta = 538189
,07-27 11:51:30.884  8411  8457 D bt_hwcfg: Settlement delay -- 100 ms
07-27 11:51:30.884  8411  8457 I bt_hwcfg: Setting fw settlement delay to 100 
,07-27 11:51:30.974   304   304 E SMD     : DCD ON
,07-27 11:51:30.994  8411  8457 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-27 11:51:31.034  8411  8457 I bt_hwcfg: vendor lib fwcfg completed
,07-27 11:51:31.044  8411  8455 I         : BTE_InitTraceLevels -- TRC_HCI
,07-27 11:51:31.044  8411  8455 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-27 11:51:31.044  8411  8455 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-27 11:51:31.044  8411  8455 I         : BTE_InitTraceLevels -- TRC_AVDT
07-27 11:51:31.044  8411  8455 I         : BTE_InitTraceLevels -- TRC_AVRC
07-27 11:51:31.044  8411  8455 I         : BTE_InitTraceLevels -- TRC_A2D
07-27 11:51:31.044  8411  8455 I         : BTE_InitTraceLevels -- TRC_BNEP
07-27 11:51:31.044  8411  8455 I         : BTE_InitTraceLevels -- TRC_BTM
,07-27 11:51:31.044  8411  8455 I         : BTE_InitTraceLevels -- TRC_GAP
07-27 11:51:31.044  8411  8455 I         : BTE_InitTraceLevels -- TRC_PAN
07-27 11:51:31.044  8411  8455 I         : BTE_InitTraceLevels -- TRC_SAP
07-27 11:51:31.044  8411  8455 I         : BTE_InitTraceLevels -- TRC_SDP
07-27 11:51:31.044  8411  8455 I         : BTE_InitTraceLevels -- TRC_GATT
07-27 11:51:31.044  8411  8455 I         : BTE_InitTraceLevels -- TRC_SMP
07-27 11:51:31.044  8411  8455 I         : BTE_InitTraceLevels -- TRC_BTAPP
,07-27 11:51:31.044  8411  8455 I         : BTE_InitTraceLevels -- TRC_BTIF
07-27 11:51:31.044  8411  8455 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,07-27 11:51:31.244   361   361 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 11:51:31.274  8411  8455 W bt-l2cap: l2c_link_processs_ble_num_bufs 15
,07-27 11:51:31.284  8411  8455 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xafb06b5d 
,07-27 11:51:31.284  8411  8455 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xafb06b5d 
,07-27 11:51:31.504  8411  8439 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 1 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
,07-27 11:51:31.504  8411  8439 E bt-btif : Calling BTA_HhEnable
,07-27 11:51:31.504  8411  8439 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
07-27 11:51:31.504  8411  8439 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
,07-27 11:51:31.504  8411  8439 E BluetoothServiceJni: populateRssiValuesNative
07-27 11:51:31.504  8411  8439 I bluedroid: getModelRssiValues
07-27 11:51:31.504  8411  8439 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,07-27 11:51:31.504  8411  8439 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-27 11:51:31.504  8411  8439 D BluetoothAdapterProperties: Name is: Note3-1
,07-27 11:51:31.514   771   771 D SettingsProvider: name = bluetooth_name
,07-27 11:51:31.514  8411  8439 D BluetoothAdapterProperties: Scan Mode:20
,07-27 11:51:31.514  8411  8439 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-27 11:51:31.514  8411  8439 D BluetoothAdapterProperties: LE Address is:E0:B7:20:3E:93:BC
07-27 11:51:31.514  8411  8439 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,07-27 11:51:31.514  8411  8457 D bt_vendor: op for 2
07-27 11:51:31.514  8411  8457 D bt_vendor: op for 6
,07-27 11:51:31.514  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.514  8411  8439 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
07-27 11:51:31.514  8411  8457 D bt_upio : proc btwrite assertion
,07-27 11:51:31.514  8411  8439 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,07-27 11:51:31.514  8411  8457 D bt_vendor: op for 7
07-27 11:51:31.514  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.514  8411  8439 E bt-btif : btif_sock_init: !vhci_init
07-27 11:51:31.514  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.514  8411  8457 D bt_upio : BT_WAKE is asserted already
07-27 11:51:31.514  8411  8439 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,07-27 11:51:31.514  8411  8439 D IOP_DB_BT: db_open: db_open : handle 3013562384l, read 14063 bytes onto local cache
07-27 11:51:31.514  8411  8439 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,07-27 11:51:31.514  8411  8439 D IOP_DB_BT: db_query: result 1
,07-27 11:51:31.514  8411  8439 I         : iop_db_open: iop_db_open status 0
07-27 11:51:31.524  8411  8439 D bte_conf: Device ID record 1 : primary
,07-27 11:51:31.524  8411  8439 D bte_conf:   vendorId            = 0075
07-27 11:51:31.524  8411  8439 D bte_conf:   vendorIdSource      = 0001
07-27 11:51:31.524  8411  8439 D bte_conf:   product             = 0100
07-27 11:51:31.524  8411  8439 D bte_conf:   version             = 0200
,07-27 11:51:31.524  8411  8439 D bte_conf:   clientExecutableURL = 
07-27 11:51:31.524  8411  8439 D bte_conf:   serviceDescription  = 
07-27 11:51:31.524  8411  8439 D bte_conf:   documentationURL    = 
07-27 11:51:31.524  8411  8439 D bte_conf: bte_load_did_conf no section named DID2.
,07-27 11:51:31.524  8411  8436 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,07-27 11:51:31.524  8411  8436 D BluetoothAdapterProperties: ScanMode =  20
07-27 11:51:31.524  8411  8436 D BluetoothAdapterProperties: State =  11
,07-27 11:51:31.524   771  1143 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,07-27 11:51:31.524  8411  8436 D BluetoothAdapterProperties: Setting state to 12
07-27 11:51:31.524  8411  8436 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-27 11:51:31.524   771  1673 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,07-27 11:51:31.524   771  1673 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-27 11:51:31.524   771  1673 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-27 11:51:31.524   771  1673 D SettingsProvider: selectionArgs: false
07-27 11:51:31.524   771  1673 D SettingsProvider: selectionArgs: 1002
,07-27 11:51:31.524   771  1673 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-27 11:51:31.524   771  1673 D SettingsProvider: ret = -1
,07-27 11:51:31.524  8411  8436 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-27 11:51:31.524  8411  8436 D BluetoothAdapterService: updateAdapterState state is 12
,07-27 11:51:31.534   771  1458 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 11:51:31.534   771  1458 D ActivityManager: caller:android.app.ApplicationThreadProxy@35a60a5a, r.packageName :com.android.bluetooth
,07-27 11:51:31.534  8411  8436 D BluetoothAdapterService: Autoconnection is available 
,07-27 11:51:31.534  8411  8436 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-27 11:51:31.534  8411  8436 D BluetoothAdapterService: starting service from this receiver
,07-27 11:51:31.534   771  1567 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 11:51:31.534   771  1567 D ActivityManager: caller:android.app.ApplicationThreadProxy@38247968, r.packageName :com.android.bluetooth
,07-27 11:51:31.544  8411  8436 I BluetoothAdapterState: Entering On State from state = 11
,07-27 11:51:31.544  8411  8457 E bt_h4   : vendor lib postload completed
,07-27 11:51:31.544  8411  8439 D BluetoothAdapterProperties: Scan Mode:21
,07-27 11:51:31.544  8411  8439 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-27 11:51:31.554  8411  8411 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,07-27 11:51:31.564  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:31.564  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:31.564  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:31.564  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:51:31.564  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:31.564  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:31.564  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:31.564  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:51:31.564  7570  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:51:31.564  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:31.564  8411  8457 D bt_vendor: op for 7
07-27 11:51:31.564  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.564  8411  8439 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-27 11:51:31.574  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.574  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.574  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.574  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.574  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.574  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.574  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.574  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.574  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.574  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.584  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.584  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.584  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.584  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.584  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.584  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.584  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.584  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.584  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.584  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.584  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.584  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.594  8411  8457 D bt_vendor: op for 7
07-27 11:51:31.594  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.594  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.594  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.594  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.594  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.594  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.594  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.594  8411  8457 D bt_vendor: op for 7
07-27 11:51:31.594  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.594  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.604  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.604  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.604  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.604  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.604  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.604  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.604  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.604  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.604  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.604  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.614  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.614  8411  8457 D bt_vendor: op for 7
07-27 11:51:31.614  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.614  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.614  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.614  8411  8457 D bt_vendor: op for 7
07-27 11:51:31.614  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.674   771  1045 I art     : Explicit concurrent mark sweep GC freed 56070(3MB) AllocSpace objects, 5(80KB) LOS objects, 30% free, 36MB/52MB, paused 1.245ms total 113.035ms
07-27 11:51:31.674   771  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 11:51:31.674  1312  1326 E BluetoothHeadset: BluetoothHeadset service is binded
,07-27 11:51:31.674  1312  1339 D BluetoothMap: onBluetoothStateChange: up=true
,07-27 11:51:31.674   771  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,07-27 11:51:31.674   771  1045 D BluetoothA2dp: onBluetoothStateChange: up=true
07-27 11:51:31.674   771  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
07-27 11:51:31.674   771   771 D BluetoothA2dp: Proxy object connected
,07-27 11:51:31.674  8411  8411 I BluetoothPbapService: Handler(): got msg=1
,07-27 11:51:31.674   771  1525 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-27 11:51:31.684  1312  1312 D HeadsetProfile: Bluetooth service connected
,07-27 11:51:31.684   771  1045 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 11:51:31.684  8411  8479 V BluetoothPbapService: PBAP Service initSocket try: 0
07-27 11:51:31.684  1427  1728 E BluetoothHeadset: BluetoothHeadset service is binded
,07-27 11:51:31.684  1312  1339 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-27 11:51:31.684   771  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-27 11:51:31.684  3206  8347 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-27 11:51:31.684   771  1045 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-27 11:51:31.684  3206  3206 D BluetoothA2dp: Proxy object connected
07-27 11:51:31.684  1312  1339 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-27 11:51:31.684  8411  8479 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 11:51:31.694   771  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,07-27 11:51:31.694  8411  8457 D bt_vendor: op for 7
07-27 11:51:31.694  8411  8457 D bt_upio : BT_WAKE is asserted already
,07-27 11:51:31.694  8411  8479 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
07-27 11:51:31.694  8411  8479 D BluetoothSocket: bindListen(), new LocalSocket 
07-27 11:51:31.694  8411  8479 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-27 11:51:31.694  8411  8479 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@15c99eb8
07-27 11:51:31.694  8411  8479 D BluetoothSocket: channel: 19
07-27 11:51:31.694  8411  8479 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,07-27 11:51:31.694   771  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 11:51:31.694  1312  1312 D BluetoothMap: Proxy object connected
07-27 11:51:31.694  1312  1312 D MapProfile: Bluetooth service connected
07-27 11:51:31.694  1312  1312 D BluetoothA2dp: Proxy object connected
07-27 11:51:31.694  1312  1312 D A2dpProfile: Bluetooth service connected
07-27 11:51:31.694  1405  1415 E BluetoothHeadset: BluetoothHeadset service is binded
,07-27 11:51:31.694   771  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 11:51:31.694  1405  1414 E BluetoothHeadset: BluetoothHeadset service is binded
07-27 11:51:31.694  1312  1312 D BluetoothInputDevice: Proxy object connected
,07-27 11:51:31.694  1312  1312 D HidProfile: Bluetooth service connected
,07-27 11:51:31.694   771  1045 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 11:51:31.694  7722  7733 E BluetoothHeadset: BluetoothHeadset service is binded
07-27 11:51:31.694  1312  1340 D BluetoothPbap: onBluetoothStateChange: up=true
,07-27 11:51:31.694   771  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,07-27 11:51:31.694   771  1045 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 11:51:31.694  1312  1312 D BluetoothPbap: Proxy object connected
07-27 11:51:31.694  1312  1312 D PbapServerProfile: Bluetooth service connected
07-27 11:51:31.694  3206  3217 E BluetoothHeadset: BluetoothHeadset service is binded
,07-27 11:51:31.704   771  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 11:51:31.704   771  1045 E BluetoothHeadset: BluetoothHeadset service is binded
07-27 11:51:31.704  1312  1339 D Bluetoothsap: onBluetoothStateChange: up=true
07-27 11:51:31.704  1312  1339 D Bluetoothsap: Binding service...
,07-27 11:51:31.704  1312  1339 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,07-27 11:51:31.704   771  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
07-27 11:51:31.704  1312  1339 D Bluetoothsap: bindService called to Bluetooth SAP Service
,07-27 11:51:31.704  1312  1340 D BluetoothPan: Binding service...
,07-27 11:51:31.704  1312  1312 D Bluetoothsap: BluetoothSAP Proxy object connected
07-27 11:51:31.704  1312  1312 D SapProfile: Bluetooth service connected
07-27 11:51:31.704  1312  1312 D Bluetoothsap: getConnectedDevices()
,07-27 11:51:31.704   771  1045 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,07-27 11:51:31.704   771  1045 D BluetoothPan: Binding service...
,07-27 11:51:31.704   771  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
07-27 11:51:31.704  8411  8420 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-27 11:51:31.704   771   771 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 11:51:31.704  1312  1312 D BluetoothPan: BluetoothPAN Proxy object connected
07-27 11:51:31.704  1312  1312 D PanProfile: Bluetooth service connected
,07-27 11:51:31.704   771  1045 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-27 11:51:31.704  1405  1415 E BluetoothHeadset: BluetoothHeadset service is binded
07-27 11:51:31.704   771  1045 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,07-27 11:51:31.704   771   771 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:31.704   771   771 I InputMethodManagerService: [BT Setting State] State =12
07-27 11:51:31.704   771   771 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-27 11:51:31.714  1405  1405 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@3a3a4388, true
,07-27 11:51:31.714  1188  1188 D BluetoothTile:  onBluetoothStateChange:
,07-27 11:51:31.714  1405  1405 D BluetoothHeadset: registerMessageListener
,07-27 11:51:31.714  1748  1748 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-27 11:51:31.714  1188  1188 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-27 11:51:31.714  1188  1188 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:51:31.714  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:31.714   771  1525 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-27 11:51:31.714   771  1702 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,07-27 11:51:31.714  1188  1188 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-27 11:51:31.714   771  1045 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
07-27 11:51:31.714   771  1360 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-27 11:51:31.724   771  1360 D ActivityManager: caller:android.app.ApplicationThreadProxy@2cefa7d1, r.packageName :com.google.android.gms
,07-27 11:51:31.724  1312  1312 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-27 11:51:31.724  1188  1601 D BluetoothTile:  handleUpdatestate:false name:null
07-27 11:51:31.724  1188  1601 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-27 11:51:31.724  8411  8441 D HeadsetService: registerMessageListener
07-27 11:51:31.724  8411  8441 D HeadsetService: registerMessageListener
,07-27 11:51:31.724  8411  8446 D HeadsetStateMachine: Disconnected process message: 70
07-27 11:51:31.724  8411  8446 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2f84d491
07-27 11:51:31.724  1405  1405 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,07-27 11:51:31.724  7722  7722 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
07-27 11:51:31.724  1405  1405 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,07-27 11:51:31.724  8411  8446 D HeadsetStateMachine: Disconnected process message: 9
,07-27 11:51:31.724  1312  1312 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
07-27 11:51:31.724  1312  1312 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
07-27 11:51:31.724  8411  8446 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,07-27 11:51:31.724  8411  8485 D BluetoothMapMasInstance: set MAP SDP message type : 1
,07-27 11:51:31.734   309   309 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,07-27 11:51:31.734   309   309 V voice   : voice_set_parameters: enter: A2dpSuspended=false
07-27 11:51:31.734   309   309 V voice   : voice_set_parameters: exit with code(-2)
07-27 11:51:31.734   309   309 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
07-27 11:51:31.734   309   309 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-27 11:51:31.734   309   309 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-27 11:51:31.734   309   309 V audio_hw_primary: adev_set_parameters: exit
,07-27 11:51:31.734  8411  8446 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
07-27 11:51:31.734  1312  1312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-27 11:51:31.734  8411  8485 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 11:51:31.734   771  1506 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-27 11:51:31.734  8411  8457 D bt_vendor: op for 7
07-27 11:51:31.734  8411  8457 D bt_upio : BT_WAKE is asserted already
07-27 11:51:31.734  8411  8485 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
,07-27 11:51:31.734  8411  8485 D BluetoothSocket: bindListen(), new LocalSocket 
07-27 11:51:31.734  8411  8485 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-27 11:51:31.734   771  1506 D ActivityManager: caller:android.app.ApplicationThreadProxy@1cc04aa4, r.packageName :com.android.settings
07-27 11:51:31.734  8411  8485 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2d78dff6
07-27 11:51:31.734  8411  8485 D BluetoothSocket: channel: 5
,07-27 11:51:31.744  1312  1312 D DockEventReceiver: finishStartingService: stopping service
,07-27 11:51:31.744  1312  1312 D BluetoothNotiBroadcastReceiver: onReceive
,07-27 11:51:31.744  8411  8411 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1dd5832f
,07-27 11:51:31.744  8411  8411 D BtConfig.SecureMode: isSecureModeOn:false
,07-27 11:51:31.744   771  1143 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-27 11:51:31.744   771  1143 D ActivityManager: caller:android.app.ApplicationThreadProxy@f695bc2, r.packageName :com.android.bluetooth
,07-27 11:51:31.774   771   794 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-27 11:51:31.794  8411  8492 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-27 11:51:31.794  8411  8492 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
07-27 11:51:31.794  8411  8492 D BluetoothSocket: bindListen(), new LocalSocket 
07-27 11:51:31.794  8411  8492 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-27 11:51:31.794  8411  8492 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@a358cd0
07-27 11:51:31.794  8411  8457 D bt_vendor: op for 7
,07-27 11:51:31.794  8411  8457 D bt_upio : BT_WAKE is asserted already
07-27 11:51:31.794  8411  8492 D BluetoothSocket: channel: 12
07-27 11:51:31.794  8411  8492 I BtOppRfcommListener: Accept thread started.
,07-27 11:51:31.814  1892  1892 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-27 11:51:31.814   771  1525 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-27 11:51:31.814   771  1525 D ActivityManager: caller:android.app.ApplicationThreadProxy@2696042f, r.packageName :com.google.android.gms
,07-27 11:51:31.824  1892  8496 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-27 11:51:31.824  1892  1892 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-27 11:51:31.834   771  1525 D ActivityManager: caller:android.app.ApplicationThreadProxy@3725ce28, r.packageName :com.google.android.gms
,07-27 11:51:31.834  1892  8496 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-27 11:51:31.874  7570  7631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:31.874  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:31.874  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:31.874  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-27 11:51:31.874  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:31.874  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:31.874  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:31.874  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:51:31.874  7570  7631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:51:31.874  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:31.874  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@212b7165 added. We now have 8 listener(s)
07-27 11:51:31.874  7570  7631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 11:51:31.874  7570  7631 I WifiManager: packageName : com.test.thalitest
,07-27 11:51:31.874   771  1673 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-27 11:51:31.874   771  1673 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-27 11:51:31.874   771  1673 D SecContentProvider2: mCursor = null
,07-27 11:51:31.874   771  1673 D WifiService: setWifiEnabled: false pid=7570, uid=10079
07-27 11:51:31.874   771  1673 D SettingsProvider: name = wifi_on
,07-27 11:51:31.884  7570  7631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:31.884  7570  7631 I WifiManager: packageName : com.test.thalitest
07-27 11:51:31.884   771  1428 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-27 11:51:31.884   771  1428 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-27 11:51:31.884   771  1428 D SecContentProvider2: mCursor = null
,07-27 11:51:31.884   771  1428 D WifiService: setWifiEnabled: true pid=7570, uid=10079
07-27 11:51:31.884   771  1428 W ActivityManager: Permission Denial: getCurrentUser() from pid=7570, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-27 11:51:31.884   771  1428 W WifiService: Failed getting userId using ActivityManagerNative
07-27 11:51:31.884   771  1428 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7570, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-27 11:51:31.884   771  1428 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-27 11:51:31.884   771  1428 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-27 11:51:31.884   771  1428 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-27 11:51:31.884   771  1428 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-27 11:51:31.884   771  1428 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
07-27 11:51:31.884   771  1428 D SettingsProvider: name = wifi_on
,07-27 11:51:31.884   771  1148 E WifiHW  : ##################### set firmware type 0 #####################
,07-27 11:51:31.884   297  1060 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
07-27 11:51:31.884   297  1060 I WifiHW  : module is semco
07-27 11:51:31.884   297  1060 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-27 11:51:31.884   297  1060 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-27 11:51:31.884   297  1060 E WifiHW  : TEMP_FAILURE_RETRY complete
07-27 11:51:31.884   297  1060 D SoftapController: Softap fwReload - Ok
,07-27 11:51:31.884   297  1060 D CommandListener: Setting iface cfg
07-27 11:51:31.884   297  1060 D CommandListener: Trying to bring down wlan0
,07-27 11:51:31.894   297  1060 D CommandListener: Clearing all IP addresses on wlan0
,07-27 11:51:31.894   771  1148 E WifiHW  : supplicant_name : p2p_supplicant
,07-27 11:51:31.924  8500  8500 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-27 11:51:31.924  8500  8500 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-27 11:51:31.924  8500  8500 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-27 11:51:31.924  8500  8500 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-27 11:51:31.924   377   377 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8500
07-27 11:51:31.924   377   377 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-27 11:51:31.924  8500  8500 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-27 11:51:31.924  8500  8500 I wpa_supplicant: ssSupport state is = 1
,07-27 11:51:31.924  8500  8500 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,07-27 11:51:31.924  8500  8500 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-27 11:51:31.924   377   377 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8500
07-27 11:51:31.924   377   377 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,07-27 11:51:31.994   771   771 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:51:31.994   771  1148 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-27 11:51:31.994  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 11:51:31.994   771  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-27 11:51:31.994  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,07-27 11:51:31.994  1188  1188 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 11:51:31.994  1188  1188 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
07-27 11:51:31.994  1188  1188 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 11:51:31.994  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:31.994  1188  1601 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-27 11:51:31.994  1188  1188 D HotspotTile: onReceive : 2, 0
,07-27 11:51:31.994  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:51:32.004  7193  7193 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-27 11:51:32.004   771  1525 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:32.004  6793  6793 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 11:51:32.004  6793  6793 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 11:51:32.004  6793  6793 D SecurityLogAgent: StateMachine : Current State = 1
07-27 11:51:32.004  6793  6793 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 11:51:32.194   377   377 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,07-27 11:51:32.244   361   361 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 11:51:32.284   771  1318 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-27 11:51:32.284   771  1318 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4327, temperature: 290, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-27 11:51:32.284   771  1318 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-27 11:51:32.284   771   771 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-27 11:51:32.284   771  1318 D BatteryService: stay LED for fully charged
,07-27 11:51:32.284  1188  1188 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-27 11:51:32.284  1188  1188 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-27 11:51:32.284   771   771 I MotionRecognitionService: Plugged
07-27 11:51:32.284   771   771 I MotionRecognitionService: setPowerConnected  = true
,07-27 11:51:32.284  8411  8411 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-27 11:51:32.284  1188  1188 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-27 11:51:32.284  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 11:51:32.284  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-27 11:51:32.284  1188  1188 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-27 11:51:32.284  8411  8446 D HeadsetStateMachine: Disconnected process message: 10
,07-27 11:51:32.444  8500  8500 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,07-27 11:51:32.484  8500  8500 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,07-27 11:51:32.484  8500  8500 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-27 11:51:32.484   377   377 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8500
07-27 11:51:32.484   377   377 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,07-27 11:51:32.484  8500  8500 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-27 11:51:32.484  8500  8500 I wpa_supplicant: ssSupport state is = 1
07-27 11:51:32.484  8500  8500 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 11:51:32.484  8500  8500 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-27 11:51:32.484  8500  8500 E wpa_supplicant: SIM READ ERROR
07-27 11:51:32.484  8500  8500 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 11:51:32.484  8500  8500 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 11:51:32.484  8500  8500 E wpa_supplicant: SIM READ ERROR
07-27 11:51:32.484  8500  8500 I wpa_supplicant: Blacklist: Clear (all) 
,07-27 11:51:32.484  8500  8500 I wpa_supplicant: wpa_default_ap_write_once
07-27 11:51:32.484  8500  8500 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-27 11:51:32.484  8500  8500 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 11:51:32.484  8500  8500 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
,07-27 11:51:32.484  8500  8500 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 11:51:32.484  8500  8500 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-27 11:51:32.494  8500  8500 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 11:51:32.814   771  1050 I PowerManagerService: [PWL] Off : 275s ago
,07-27 11:51:32.814   771  1050 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
07-27 11:51:32.814   771  1050 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
07-27 11:51:32.814   771  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=771, ws=null) (elapsedTime=21023)
,07-27 11:51:32.814   771  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=8411, ws=null) (elapsedTime=1772)
07-27 11:51:32.814   771  1050 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'AudioMix' (uid=1013, pid=0, ws=null) (elapsedTime=1084)
,07-27 11:51:33.144   771  1151 E Tethering: No numeric data
,07-27 11:51:33.144   771  1151 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-27 11:51:33.144  1188  1188 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
,07-27 11:51:33.144  1188  1188 D HotspotTile: updateTetherState():false, false
07-27 11:51:33.144   771  1145 V NetworkStats: performPollLocked(flags=0x1)
,07-27 11:51:33.144   771  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 11:51:33.144   771  1145 D NetworkStatsFactory: UpdateStatsForKnox
,07-27 11:51:33.144   771  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:33.154   771  1145 V NetworkStats: performPollLocked() took 5ms
,07-27 11:51:33.154   771  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 11:51:33.154   771  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 11:51:33.154   771  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 11:51:33.154  8500  8500 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,07-27 11:51:33.164  8500  8500 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-27 11:51:33.164  8500  8500 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-27 11:51:33.164  8500  8500 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-27 11:51:33.164   377   377 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8500
07-27 11:51:33.164   377   377 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,07-27 11:51:33.164  8500  8500 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-27 11:51:33.164  8500  8500 I wpa_supplicant: ssSupport state is = 1
,07-27 11:51:33.164  8500  8500 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-27 11:51:33.164  8500  8500 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-27 11:51:33.164   377   377 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8500
07-27 11:51:33.164   377   377 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
07-27 11:51:33.164  8500  8500 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-27 11:51:33.164  8500  8500 I wpa_supplicant: ssSupport state is = 1
,07-27 11:51:33.164  8500  8500 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 11:51:33.164  8500  8500 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 11:51:33.164  8500  8500 E wpa_supplicant: SIM READ ERROR
07-27 11:51:33.164  8500  8500 I wpa_supplicant: wpa_default_ap_write_once
07-27 11:51:33.164  8500  8500 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,07-27 11:51:33.164  8500  8500 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-27 11:51:33.174  8500  8500 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
,07-27 11:51:33.174  8500  8500 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,07-27 11:51:33.184  8500  8500 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,07-27 11:51:33.184  8500  8500 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,07-27 11:51:33.184   771  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,07-27 11:51:33.184   771  1148 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-27 11:51:33.184  8500  8500 I wpa_supplicant: HOTSPOT20_ENABLE called
,07-27 11:51:33.184  8500  8500 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-27 11:51:33.184  8500  8500 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-27 11:51:33.184  8500  8500 E wpa_supplicant: SIM READ ERROR
07-27 11:51:33.184  8500  8500 I wpa_supplicant: Blacklist: Clear (all) 
,07-27 11:51:33.214  8500  8500 I wpa_supplicant: Skip scan - bUseNetwork false
,07-27 11:51:33.214   771  1148 D WifiNative-HAL: callSECApiInt - ID [210]
,07-27 11:51:33.214   771   771 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:51:33.214  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 11:51:33.214  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 11:51:33.214  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 11:51:33.224  1312  1312 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:51:33.224   771  1152 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-27 11:51:33.224  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:33.224  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:33.224  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:33.224  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 11:51:33.224  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:33.224  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 11:51:33.224  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:33.224  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:33.224  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:33.224  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:33.224  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:33.224  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:33.224  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:33.224  7570  7570 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:51:33.224  7570  7570 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:51:33.224  1188  1188 D StatusBar.NetworkController: applyOpen
,07-27 11:51:33.224  1188  1188 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-27 11:51:33.234  1188  1188 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,07-27 11:51:33.234  1188  1188 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-27 11:51:33.234  1188  1601 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-27 11:51:33.234   771  1148 D WifiConfigStore: Loading config and enabling all networks 
,07-27 11:51:33.234  1188  1188 D HotspotTile: onReceive : 3, 0
,07-27 11:51:33.234  7193  7193 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-27 11:51:33.244   771  1458 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:33.244  6793  6793 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 11:51:33.244  6793  6793 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 11:51:33.244  6793  6793 D SecurityLogAgent: StateMachine : Current State = 1
,07-27 11:51:33.244   771  1148 E WifiConfigStore: Not a HS20
07-27 11:51:33.244  6793  6793 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 11:51:33.244   361   361 I ServiceManager: Waiting for service AtCmdFwd...
,07-27 11:51:33.254   771  1148 E WifiConfigStore: Not a HS20
,07-27 11:51:33.254   771  1148 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-27 11:51:33.264   771  1148 D WifiNative-HAL: callSECApiInt - ID [65]
,07-27 11:51:33.264   771  1148 D WifiNative-HAL: callSECApiBoolean - ID [13]
,07-27 11:51:33.264  8500  8500 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-27 11:51:33.264  8500  8500 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,07-27 11:51:33.264  8500  8500 I wpa_supplicant: reset timer : RESET_TIMER 0
07-27 11:51:33.264  8500  8500 I wpa_supplicant: P2P: Current p2p state = IDLE
07-27 11:51:33.264  8500  8500 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
07-27 11:51:33.264  8500  8500 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
07-27 11:51:33.264  8500  8500 I wpa_supplicant: First Scan Start
,07-27 11:51:33.274  8500  8500 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-27 11:51:33.274  7750  7750 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-27 11:51:33.274   771  1148 D WifiNative-HAL: Setting external_sim to 1
,07-27 11:51:33.274   771  1148 D WifiStateMachine: Setting OUI to DA-A1-19
07-27 11:51:33.274   771  1148 I WifiNative-HAL: startHal
,07-27 11:51:33.274   771  1148 E wifi    : getStaticLongField sWifiHalHandle 0x934b986c
07-27 11:51:33.274   771  1148 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x501c32
07-27 11:51:33.274   771  1148 I WifiNative-HAL: Could not start hal
,07-27 11:51:33.294   771  1148 E native  : do suspend true
,07-27 11:51:33.294  8411  8457 D bt_vendor: op for 7
,07-27 11:51:33.294   771  1147 D WifiP2pService: P2pDisabledState{ what=131203 }
,07-27 11:51:33.294   297  1060 D CommandListener: Setting iface cfg
07-27 11:51:33.294   297  1060 D CommandListener: Trying to bring up p2p0
,07-27 11:51:33.294   771  1147 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-27 11:51:33.294   771  1147 D WifiP2pService: P2pEnablingState
07-27 11:51:33.294   771  1147 D WifiP2pService: P2pEnablingState{ what=147457 }
07-27 11:51:33.294   771  1147 D WifiP2pService: P2p socket connection successful
,07-27 11:51:33.294   771  1147 D WifiP2pService: P2pEnabledState
,07-27 11:51:33.294   771   771 D WifiScanningService: SCAN_AVAILABLE : 3
,07-27 11:51:33.294   771   771 D RttService: SCAN_AVAILABLE : 3
07-27 11:51:33.294   771  1165 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:33.304   771  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
07-27 11:51:33.304   771  1165 I WifiNative-HAL: startHal
,07-27 11:51:33.304   771  1166 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:33.304   771  1165 E wifi    : getStaticLongField sWifiHalHandle 0x9adb399c
07-27 11:51:33.304   771  1165 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x301c2a
07-27 11:51:33.304   771  1165 I WifiNative-HAL: Could not start hal
,07-27 11:51:33.304   771  1165 E WifiScanningService: could not start HAL
07-27 11:51:33.304   771  1148 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
07-27 11:51:33.304   771  1148 D WifiNative-HAL: callSECStringApiVoid - ID [215]
07-27 11:51:33.304   771  1148 E WifiNative-HAL: invaild command id : 215
,07-27 11:51:33.304   771   771 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
07-27 11:51:33.304   771  1047 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-27 11:51:33.304   771  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-27 11:51:33.304   771  1047 D WifiDisplayController: disconnect
07-27 11:51:33.304   771  1047 D WifiDisplayController: updateConnection
07-27 11:51:33.304   771  1047 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-27 11:51:33.304   771  1047 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-27 11:51:33.304   771  1147 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-27 11:51:33.304   771  1150 E ConnectivityService: updateNetworkInfo()
07-27 11:51:33.304   771  1047 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:33.304   771  1047 D WifiDisplayAdapter: onP2pDisconnected
07-27 11:51:33.304  7782  7782 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
07-27 11:51:33.304   771  1047 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-27 11:51:33.304   771  1047 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-27 11:51:33.304   771  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
07-27 11:51:33.304  1188  1188 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-27 11:51:33.304   771  1567 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-27 11:51:33.304  1188  1188 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-27 11:51:33.314   771  1147 D WifiNative-HAL: p2pGetDeviceAddress
07-27 11:51:33.314  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-27 11:51:33.314  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-27 11:51:33.314   771  3266 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:33.314   771  1147 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:de:28:a3
07-27 11:51:33.314  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-27 11:51:33.314   771  1360 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:33.314   771  1147 D WifiP2pService: DeviceAddress: ea:28:a3
07-27 11:51:33.314   771  1047 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
07-27 11:51:33.314   771  1047 D WifiDisplayController:  deviceAddress: ea:50:8b:de:28:a3
07-27 11:51:33.314   771  1047 D WifiDisplayController:  primary type: 10-0050F204-5
07-27 11:51:33.314   771  1047 D WifiDisplayController:  secondary type: null
07-27 11:51:33.314   771  1047 D WifiDisplayController:  wps: 0
07-27 11:51:33.314   771  1047 D WifiDisplayController:  grpcapab: 0
07-27 11:51:33.314   771  1047 D WifiDisplayController:  devcapab: 0
07-27 11:51:33.314   771  1047 D WifiDisplayController:  status: 3
07-27 11:51:33.314   771  1047 D WifiDisplayController:  wfdInfo: null
07-27 11:51:33.314   771  1047 D WifiDisplayController:  groupownerAddress: null
07-27 11:51:33.314   771  1047 D WifiDisplayController:  GOdeviceName: null
07-27 11:51:33.314   771  1047 D WifiDisplayController:  interfaceAddress: 
07-27 11:51:33.314   771  1047 D WifiDisplayController:  SConnectInfo : null
,07-27 11:51:33.314  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-27 11:51:33.314  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 11:51:33.314  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-27 11:51:33.314  1312  2825 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 11:51:33.314  7323  7323 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-27 11:51:33.324  7782  7782 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-27 11:51:33.324  7782  7782 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
07-27 11:51:33.324  7782  7782 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-27 11:51:33.324  7782  7782 D WifiDirectBR: stopServiceTest : false
,07-27 11:51:33.344  8500  8500 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-27 11:51:33.364  8500  8500 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-27 11:51:33.364   771  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 11:51:33.364   771  1148 D SecContentProvider2: mCursor = null
,07-27 11:51:33.374   771  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 11:51:33.374   771  1148 D SecContentProvider2: mCursor = null
,07-27 11:51:33.404   771  1147 D WifiP2pService: sending p2p persistent groups changed broadcast
,07-27 11:51:33.404   771  1147 D WifiP2pService: InactiveState
07-27 11:51:33.404   771  1147 D WifiP2pService: InactiveState{ what=143376 }
07-27 11:51:33.404   771  1147 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-27 11:51:33.414  8500  8500 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-27 11:51:33.414   771  1147 D WifiP2pService: InactiveState{ what=143376 }
07-27 11:51:33.414   771  1147 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-27 11:51:33.514  8411  8466 D bt_upio : ..proc_btwrite_timeout..
,07-27 11:51:33.904  7570  7631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-27 11:51:33.904  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:33.904  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:33.904  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:33.904  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:33.904  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:33.904  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:33.904  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:51:33.914  7570  7631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:51:33.924  7570  7631 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-27 11:51:33.924  7570  7631 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-27 11:51:33.924  7570  7631 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@733961f Bundle[{}]
,07-27 11:51:33.924  7570  7631 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-27 11:51:33.934  7570  7631 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-27 11:51:33.934  7570  7631 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
07-27 11:51:33.934  7570  7631 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-27 11:51:33.934  7570  7631 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-27 11:51:33.934  7570  7631 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-27 11:51:33.944  7570  7631 I System.out: Running OutgoingSocketThread
,07-27 11:51:33.944  7570  8535 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1322)
,07-27 11:51:33.944  7570  8535 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 56590
,07-27 11:51:33.944  7570  8535 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-27 11:51:33.964   304   304 E SMD     : DCD ON
,07-27 11:51:34.084  8500  8500 I wpa_supplicant: nl80211: Received scan results (21 BSSes)
,07-27 11:51:34.094  8500  8500 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,07-27 11:51:34.094  8500  8500 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
,07-27 11:51:34.094  8500  8500 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
,07-27 11:51:34.094  8500  8500 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=5 BSSID=00.00.00 SSID=4E47373030
,07-27 11:51:34.124   771  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-27 11:51:34.124   771  1148 D SecContentProvider2: mCursor = null
,07-27 11:51:34.154  8500  8500 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
07-27 11:51:34.154  8500  8500 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=6 BSSID=00.00.00 SSID=4E47373030
,07-27 11:51:34.154  8500  8500 I wpa_supplicant: Associated with F4.99.3E
07-27 11:51:34.154  8500  8500 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
07-27 11:51:34.154  8500  8500 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=7 BSSID=F4.99.3E SSID=4E47373030
,07-27 11:51:34.164   771  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-27 11:51:34.164   771  1148 D SecContentProvider2: mCursor = null
,07-27 11:51:34.164   771  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-27 11:51:34.164   771  1148 D SecContentProvider2: mCursor = null
,07-27 11:51:34.174  8500  8500 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,07-27 11:51:34.174  8500  8500 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
07-27 11:51:34.174  8500  8500 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=8 BSSID=F4.99.3E SSID=4E47373030
,07-27 11:51:34.174  8500  8500 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-27 11:51:34.174  8500  8500 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
07-27 11:51:34.174  8500  8500 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=1 id_str=]
07-27 11:51:34.174  8500  8500 I wpa_supplicant: Blacklist: Clear (temp) 
07-27 11:51:34.174  8500  8500 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=9 BSSID=F4.99.3E SSID=4E47373030
,07-27 11:51:34.174   771  1148 D WifiNative-HAL: callSECApiVoid - ID [50]
,07-27 11:51:34.184  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 11:51:34.184  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 11:51:34.184   771  1148 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,07-27 11:51:34.184   771  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-27 11:51:34.184   771  1150 D ConnectivityService: Got NetworkAgent Messenger
07-27 11:51:34.184   771  1150 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
07-27 11:51:34.184   771  1150 E ConnectivityService: updateNetworkInfo()
,07-27 11:51:34.194   771  1150 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:51:34.194   771  1150 D ConnectivityService: NetworkAgent connected
,07-27 11:51:34.194  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-27 11:51:34.194  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-27 11:51:34.194   771  1458 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:34.194  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-27 11:51:34.194   771  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-27 11:51:34.204   771  1428 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:34.204  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-27 11:51:34.204  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,07-27 11:51:34.204  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-27 11:51:34.204  1312  2825 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 11:51:34.204   297  1060 D CommandListener: Setting iface cfg
,07-27 11:51:34.214   771  1148 E WifiStateMachine: Start Dhcp Watchdog 3
,07-27 11:51:34.214   771  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-27 11:51:34.214   771  1148 D SecContentProvider2: mCursor = null
,07-27 11:51:34.224  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 11:51:34.224   771  1702 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:34.224  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 11:51:34.224   771  1150 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,07-27 11:51:34.224   771  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-27 11:51:34.224   771  1148 D SecContentProvider2: mCursor = null
,07-27 11:51:34.234  7193  7193 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-27 11:51:34.244   361   361 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,07-27 11:51:34.304   771  1148 E native  : do suspend false
,07-27 11:51:34.314   771  1147 D WifiP2pService: InactiveState{ what=143375 }
,07-27 11:51:34.314   771  1147 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-27 11:51:34.524  8540  8540 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-27 11:51:34.534  8540  8540 I dhcpcd  : version 5.5.6 starting
,07-27 11:51:34.534  8540  8540 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-27 11:51:34.594  8540  8540 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-27 11:51:34.594  8540  8540 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
07-27 11:51:34.594  8540  8540 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
07-27 11:51:34.594  8540  8540 I dhcpcd  : bssid match
07-27 11:51:34.594  8540  8540 I dhcpcd  : wlan0: rebinding lease of 192.168.1.122
,07-27 11:51:34.604  8540  8540 I dhcpcd  : wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,07-27 11:51:34.604  8540  8540 I dhcpcd  : wlan0: leased 192.168.1.122 for 172800 seconds
,07-27 11:51:34.614   771  1150 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,07-27 11:51:34.904   771  3150 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 11:51:34.924   771  1148 E native  : do suspend true
,07-27 11:51:34.934   771  1147 D WifiP2pService: InactiveState{ what=143375 }
,07-27 11:51:34.934   771  1147 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-27 11:51:34.934   771  1150 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,07-27 11:51:34.934  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 11:51:34.934  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 11:51:34.934   771  1148 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,07-27 11:51:34.934   771  1148 E WifiStateMachine: VerifyingLinkState enter
,07-27 11:51:34.944   771  1148 D WifiNative-HAL: callSECApiInt - ID [210]
,07-27 11:51:34.944   771  1150 E ConnectivityService: updateNetworkInfo()
,07-27 11:51:34.944   771  1150 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-27 11:51:34.944   771  1150 D ConnectivityService: Adding iface wlan0 to network 504
07-27 11:51:34.944  7570  7631 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1323)
,07-27 11:51:34.944  7570  7631 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1323)
,07-27 11:51:34.944  7570  7631 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 1323)
,07-27 11:51:34.944  7570  7631 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1323)
,07-27 11:51:34.954   771  1160 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,07-27 11:51:34.954  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 11:51:34.954  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 11:51:34.954  7570  7631 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 1328)
07-27 11:51:34.954  7570  7631 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 1328)
07-27 11:51:34.954  7570  7631 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1328)
,07-27 11:51:34.954  7570  7631 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 1329)
,07-27 11:51:34.954   771  1160 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-27 11:51:34.954   771  1160 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-27 11:51:34.954  7570  7631 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 1331)
,07-27 11:51:34.964   771  1160 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-27 11:51:34.964   771  1160 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-27 11:51:34.964  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-27 11:51:34.964  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@352a3e3a added. We now have 2 listener(s)
,07-27 11:51:34.964  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-27 11:51:34.974  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:51:34.974  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-27 11:51:34.974  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:34.974  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce5aeb added. We now have 9 listener(s)
,07-27 11:51:34.974  7570  7631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 11:51:34.974  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 11:51:34.974  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 11:51:34.974   771  1148 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,07-27 11:51:34.984   771   771 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-27 11:51:34.984   771   771 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-27 11:51:34.984   771   771 I WifiTrafficPoller: mBoosterFLAG : 0
,07-27 11:51:34.984   771   771 I WifiTrafficPoller: current booster mode : FullMode
07-27 11:51:34.984   771   771 D WifiNative-HAL: callSECApiVoid - ID [212]
,07-27 11:51:34.984  1188  1188 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-27 11:51:34.984   771  1148 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-27 11:51:34.984  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-27 11:51:34.994  1188  1188 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020533/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020533/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014b/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 11:51:34.994  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-27 11:51:34.994  7570  7631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:51:34.994  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:34.994  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:34.994  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:34.994  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:34.994  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:34.994  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:34.994  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:51:34.994  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-27 11:51:34.994  7570  7631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:51:34.994  7570  7631 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-27 11:51:34.994  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:34.994  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:34.994  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:51:34.994  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25e6bee1 added. We now have 3 listener(s)
,07-27 11:51:34.994  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-27 11:51:34.994  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-27 11:51:34.994  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:51:34.994  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:51:34.994  1188  1188 D StatusBar.NetworkController: applyOpen
,07-27 11:51:34.994  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:34.994  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@346e0406 added. We now have 10 listener(s)
07-27 11:51:34.994  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:34.994  7570  7631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:34.994  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
,07-27 11:51:34.994  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:34.994  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:35.004  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:35.004  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-27 11:51:35.004  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:35.004  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:35.004  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:35.004  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:35.004  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-27 11:51:35.004  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:35.004  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:51:35.004  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@352a3e3a removed from the list
07-27 11:51:35.004  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 11:51:35.004  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce5aeb removed from the list
07-27 11:51:35.004  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:35.004  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:51:35.004  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:35.004  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:51:35.004  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:35.004  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:35.004  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:35.004  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1cce5aeb not in the list
07-27 11:51:35.004  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-27 11:51:35.004  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:35.004  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-27 11:51:35.004  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:35.004  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:35.004  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@346e0406 removed from the list
07-27 11:51:35.004  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:35.004  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:35.004  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:35.004  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:51:35.004  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25e6bee1 removed from the list
07-27 11:51:35.004  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:51:35.004  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab5bac7 added. We now have 2 listener(s)
07-27 11:51:35.004  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-27 11:51:35.004  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:51:35.004  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:51:35.004  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:35.004  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b3358f4 added. We now have 9 listener(s)
07-27 11:51:35.004  7570  7631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:35.004  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 11:51:35.014  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 11:51:35.014   771  1150 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,07-27 11:51:35.014  7570  7631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:51:35.014  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:35.014  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:35.014  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:35.014  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:35.014  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:35.014  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:35.014  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-27 11:51:35.014   771  1150 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,07-27 11:51:35.014  7570  7631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-27 11:51:35.014  7570  7631 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:51:35.014   771  1150 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 504
,07-27 11:51:35.014   771  1150 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-27 11:51:35.014   771  1150 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
07-27 11:51:35.014   771  1150 D ConnectivityService: updateSourceRoutes : add src route for:192.168.1.122
07-27 11:51:35.014  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:35.014   297  1060 V         : QcRouteController
,07-27 11:51:35.014  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-27 11:51:35.014  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:51:35.024  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11d65a92 added. We now have 3 listener(s)
,07-27 11:51:35.024  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-27 11:51:35.024  1312  1312 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-27 11:51:35.024  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-27 11:51:35.024  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:51:35.024  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:35.024  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c93c63 added. We now have 10 listener(s)
07-27 11:51:35.024  7570  7631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 11:51:35.024  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:51:35.034  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-27 11:51:35.034  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 11:51:35.034  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-27 11:51:35.034   771  1428 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:35.034  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-27 11:51:35.044  7570  7631 E BluetoothAdapter: bluetooth le advertising not supported
,07-27 11:51:35.044  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-27 11:51:35.044  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-27 11:51:35.044  7193  7193 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-27 11:51:35.044   297  1060 V         : QcRouteController
,07-27 11:51:35.044  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-27 11:51:35.044  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-27 11:51:35.044  7570  7631 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-27 11:51:35.044  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-27 11:51:35.044  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-27 11:51:35.054  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:35.054  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:35.054  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:35.054  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:35.054  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:35.054  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:35.054  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:51:35.054  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ab5bac7 removed from the list
07-27 11:51:35.054  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:35.054  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b3358f4 removed from the list
,07-27 11:51:35.054  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:35.054  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:35.054  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:35.054  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:51:35.054  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:35.054  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:35.054  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:35.054  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b3358f4 not in the list
07-27 11:51:35.054  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:35.054  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:35.054  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:35.054  7570  7631 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:35.054  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:35.054  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:35.054  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:35.054  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6c93c63 removed from the list
07-27 11:51:35.054  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:35.054  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:35.054  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:35.054  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:51:35.054  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11d65a92 removed from the list
07-27 11:51:35.054  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-27 11:51:35.054  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37fb8dde added. We now have 2 listener(s)
,07-27 11:51:35.054  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-27 11:51:35.054  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:51:35.054  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:51:35.054  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-27 11:51:35.054  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13093bbf added. We now have 9 listener(s)
07-27 11:51:35.054  7570  7631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:35.054  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-27 11:51:35.064  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-27 11:51:35.064  7570  7631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:51:35.064  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:35.064  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:35.064  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:35.064  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:35.064  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:35.064  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:35.064  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:51:35.064  7570  7631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:51:35.064  7570  7631 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:51:35.064  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:51:35.064  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d747dd5 added. We now have 3 listener(s)
07-27 11:51:35.064  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:35.064  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:35.064  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-27 11:51:35.064  1312  1312 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-27 11:51:35.064   771  1525 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:35.064  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-27 11:51:35.064   771  1673 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:35.074  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-27 11:51:35.074  1312  1312 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-27 11:51:35.074  1312  1312 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-27 11:51:35.074  1312  2825 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-27 11:51:35.074  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-27 11:51:35.074  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:51:35.074  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:51:35.074  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:35.074  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10aea9ea added. We now have 10 listener(s)
07-27 11:51:35.074  7570  7631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:35.074  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:51:35.074   297  1060 V         : QcRouteController
,07-27 11:51:35.074  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:51:35.074  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 11:51:35.074  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:35.074  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-27 11:51:35.074  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-27 11:51:35.074   771  3266 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:35.084  7570  7631 E BluetoothAdapter: bluetooth le advertising not supported
07-27 11:51:35.084  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-27 11:51:35.084  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-27 11:51:35.084  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 11:51:35.084  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:35.084  7193  7193 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
07-27 11:51:35.084  7570  7631 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 11:51:35.084  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:35.084  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:35.084  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:35.084  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:35.084  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:35.084  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:35.084  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:51:35.084  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37fb8dde removed from the list
07-27 11:51:35.084  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:35.084  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13093bbf removed from the list
07-27 11:51:35.084  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:35.084  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:35.084  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:35.084  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:35.084  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:35.084  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:35.084  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:35.084  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13093bbf not in the list
07-27 11:51:35.084  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:35.084  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:35.084  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:35.084  7570  7631 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:35.084  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:35.084  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:35.084  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:35.084  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10aea9ea removed from the list
07-27 11:51:35.084  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:35.084  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:35.084  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:35.084  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:51:35.084  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d747dd5 removed from the list
07-27 11:51:35.084  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:51:35.084  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e8c2251 added. We now have 2 listener(s)
07-27 11:51:35.094   297  1060 V         : QcRouteController
07-27 11:51:35.094  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-27 11:51:35.094  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:51:35.094  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:51:35.094  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:35.094  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fc57ab6 added. We now have 9 listener(s)
07-27 11:51:35.094  7570  7631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:35.094  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 11:51:35.094  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:35.094  1312  1312 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-27 11:51:35.094  1312  1312 I NearbySettings: MountReceiver.onReceive - Keep current state
07-27 11:51:35.104  7570  7631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:51:35.104  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:35.104  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:35.104  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:35.104  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:35.104  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:35.104  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:35.104  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:51:35.104  7570  7631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:51:35.104  7570  7631 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:51:35.104   771  1567 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
07-27 11:51:35.104  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:51:35.104  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad8e724 added. We now have 3 listener(s)
07-27 11:51:35.104  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:35.104  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:35.114  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-27 11:51:35.114  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:51:35.114  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:51:35.114  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:35.114  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e9f928d added. We now have 10 listener(s)
07-27 11:51:35.114  7570  7631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:35.114  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-27 11:51:35.114  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-27 11:51:35.114  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:35.114  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-27 11:51:35.114   771  1506 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:35.114   297  1060 V         : QcRouteController
07-27 11:51:35.114  7193  7193 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
07-27 11:51:35.114  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-27 11:51:35.124  7570  7631 E BluetoothAdapter: bluetooth le advertising not supported
07-27 11:51:35.124  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-27 11:51:35.124  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-27 11:51:35.124  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-27 11:51:35.124  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:35.124  7570  7631 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-27 11:51:35.124  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:35.124  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:35.124  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:35.124  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:35.124  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:35.124  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:35.124  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:51:35.124  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e8c2251 removed from the list
07-27 11:51:35.124  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:35.124  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fc57ab6 removed from the list
07-27 11:51:35.124  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:35.124  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:35.124  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:35.124  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:35.124  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:35.124  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:35.124  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:35.124  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1fc57ab6 not in the list
07-27 11:51:35.124  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:35.124  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:35.124  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:35.124  7570  7631 D BluetoothLeScanner: could not find callback wrapper
07-27 11:51:35.124  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-27 11:51:35.124  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:35.124  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:35.124  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e9f928d removed from the list
07-27 11:51:35.124  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:35.124  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:35.124  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:35.124  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:51:35.124  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ad8e724 removed from the list
07-27 11:51:35.124  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:51:35.124  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c4f5190 added. We now have 2 listener(s)
07-27 11:51:35.124  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-27 11:51:35.124  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:51:35.124  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:51:35.124  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:35.124  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dffca89 added. We now have 9 listener(s)
07-27 11:51:35.124  7570  7631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-27 11:51:35.134  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-27 11:51:35.134  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-27 11:51:35.134   297  1060 V         : QcRouteController
07-27 11:51:35.134   266   266 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
07-27 11:51:35.134   297  1060 V         : QcRouteController
07-27 11:51:35.134  7570  7631 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-27 11:51:35.134  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-27 11:51:35.134  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-27 11:51:35.134  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-27 11:51:35.134  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-27 11:51:35.134  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-27 11:51:35.134  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-27 11:51:35.134  7570  7631 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-27 11:51:35.134  7570  7631 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-27 11:51:35.134  7570  7631 D io.jxcore.node.ConnectivityMonitor: start: OK
07-27 11:51:35.134  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-27 11:51:35.134  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:35.134  7570  7570 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-27 11:51:35.134  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e4e92af added. We now have 3 listener(s)
07-27 11:51:35.144  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-27 11:51:35.144  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-27 11:51:35.144  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-27 11:51:35.144  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-27 11:51:35.144  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a7ff6bc added. We now have 10 listener(s)
07-27 11:51:35.144  7570  7631 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-27 11:51:35.144  7570  7631 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-27 11:51:35.144  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-27 11:51:35.144  7570  7631 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-27 11:51:35.144  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:35.144  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:35.144  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-27 11:51:35.144  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:51:35.144  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c4f5190 removed from the list
07-27 11:51:35.144  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-27 11:51:35.144  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dffca89 removed from the list
07-27 11:51:35.144  7570  7631 D io.jxcore.node.ConnectivityMonitor: stop
07-27 11:51:35.144  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:35.144  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:35.144  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:35.144  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-27 11:51:35.144  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:35.144  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:35.144  7570  7631 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3dffca89 not in the list
07-27 11:51:35.144  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:35.144  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-27 11:51:35.144  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-27 11:51:35.144   771   987 W ProcessCpuTracker: Skipping unknown process pid 8593
07-27 11:51:35.144  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-27 11:51:35.144  7570  7631 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-27 11:51:35.144   771   987 W ProcessCpuTracker: Skipping unknown process pid 8594
,07-27 11:51:35.144  7570  7631 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3a7ff6bc removed from the list
07-27 11:51:35.144  7570  7631 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-27 11:51:35.144  7570  7631 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-27 11:51:35.144  7570  7631 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-27 11:51:35.144  7570  7631 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-27 11:51:35.144  7570  7631 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e4e92af removed from the list
,07-27 11:51:35.144  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,07-27 11:51:35.144  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-27 11:51:35.144  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-27 11:51:35.144  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,07-27 11:51:35.144  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-27 11:51:35.144  7570  7631 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-27 11:51:35.154   771  1469 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=771
,07-27 11:51:35.154   297  1060 V         : QcRouteController
,07-27 11:51:35.154  7570  8604 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1337, name: My test thread name)
,07-27 11:51:35.154  7570  8604 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1337, thread name: My test thread name)
07-27 11:51:35.154  7570  8604 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1337, name: My test thread name)
,07-27 11:51:35.164  7570  8607 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1339, name: My test thread name)
07-27 11:51:35.164  7570  8607 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1339, thread name: My test thread name)
07-27 11:51:35.164  7570  8607 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1339, name: My test thread name)
,07-27 11:51:35.164  7570  7631 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 84
07-27 11:51:35.164  7570  7631 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 84
07-27 11:51:35.164  7570  7631 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-27 11:51:35.164  7570  7631 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,07-27 11:51:35.164  7570  7631 D com.test.thalitest.ThaliTestRunner: Total duration: 23785 ms
,07-27 11:51:35.164  7570  7631 I jxcore-log: Total number of executed tests:  84
07-27 11:51:35.164  7570  7631 I jxcore-log: 
,07-27 11:51:35.174  7570  7631 I jxcore-log: Number of passed tests:  84
07-27 11:51:35.174  7570  7631 I jxcore-log: 
07-27 11:51:35.174  7570  7631 I jxcore-log: Number of failed tests:  0
07-27 11:51:35.174  7570  7631 I jxcore-log: 
07-27 11:51:35.174  7570  7631 I jxcore-log: Number of ignored tests:  0
07-27 11:51:35.174  7570  7631 I jxcore-log: 
07-27 11:51:35.174  7570  7631 I jxcore-log: Total duration:  23785
07-27 11:51:35.174  7570  7631 I jxcore-log: 
,07-27 11:51:35.174  7570  7631 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
07-27 11:51:35.174  7570  7631 I jxcore-log: 
,07-27 11:51:35.174  7570  7631 I jxcore-log: Unit Test app is loaded
07-27 11:51:35.174  7570  7631 I jxcore-log: 
07-27 11:51:35.174  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:51:35.174  7570  7631 I jxcore-log: 
07-27 11:51:35.174   771  1150 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
07-27 11:51:35.174   771  1150 D ConnectivityService: LTETest block dns file not exists
07-27 11:51:35.184   771  1150 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
07-27 11:51:35.184   771  1150 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
07-27 11:51:35.184   771  1150 E ConnectivityService: updateNetworkInfo()
07-27 11:51:35.184   771  1150 D ConnectivityService: calling update connectivity
07-27 11:51:35.184   771  1045 D EntConnectivity: Not allowed due to - mEnabled false
07-27 11:51:35.184   771  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-27 11:51:35.184   771  1150 E ConnectivityService: updateNetworkInfo()
07-27 11:51:35.184   771  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-27 11:51:35.184   771  1150 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:51:35.184   771  1150 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
07-27 11:51:35.184   771  1150 D ConnectivityService: calling update connectivity
07-27 11:51:35.184   771  1150 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
07-27 11:51:35.184   771  1150 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:51:35.184   771  8536 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:35.184   771  1150 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:35.184   771  8536 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
07-27 11:51:35.184   771  1150 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:35.184   771  8536 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-27 11:51:35.184   771  1150 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:35.184   771  8536 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-27 11:51:35.184   771  8536 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-27 11:51:35.184  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:51:35.184  7570  7631 I jxcore-log: 
07-27 11:51:35.184   771  1150 D ConnectivityService: currentScore = 0, newScore = 60
07-27 11:51:35.184   771  1150 D ConnectivityService:    accepting network in place of null
07-27 11:51:35.184   771  1150 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:35.184  1427  1427 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:35.184  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:51:35.184  7570  7631 I jxcore-log: 
07-27 11:51:35.184   771  1150 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-27 11:51:35.184   771  1150 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
07-27 11:51:35.184   771  1150 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 11:51:35.184   771  1150 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:35.184   771  1150 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
07-27 11:51:35.194   771  1151 D Tethering: MasterInitialState.processMessage what=3
07-27 11:51:35.194   771   771 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-27 11:51:35.194   771  1152 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-27 11:51:35.194   771  1152 D SmartBondingService: getSBEnabled() enabled =false
07-27 11:51:35.194   771  1152 D SmartBondingService: getSBEnabled() enabled =false
07-27 11:51:35.194   771  1152 D SmartBondingService: getSBEnabled() enabled =false
,07-27 11:51:35.194   771  1145 V NetworkStats: updateIfacesLocked()
07-27 11:51:35.194   771  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 11:51:35.194   771  1145 V NetworkStats: performPollLocked(flags=0x1)
07-27 11:51:35.194   771  1318 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:35.194   771  1152 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
07-27 11:51:35.194  1188  1188 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-27 11:51:35.194  1188  1188 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-27 11:51:35.194  1188  1188 D StatusBar.NetworkController: updateDataNetType()
07-27 11:51:35.194  1188  1188 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
07-27 11:51:35.194  1188  1188 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,07-27 11:51:35.194  1188  1188 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-27 11:51:35.194  1188  1188 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
07-27 11:51:35.194  1188  1188 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
07-27 11:51:35.194   771  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 11:51:35.194  1188  1188 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020533/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020533/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014b/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 11:51:35.194  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 11:51:35.194  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:35.194  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:35.194  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:35.194  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:35.194  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:35.194  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:35.194  1188  1188 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-27 11:51:35.194  7570  7570 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
07-27 11:51:35.194  1188  1188 D StatusBar.NetworkController: applyOpen
07-27 11:51:35.194  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:51:35.194  7570  7631 I jxcore-log: 
,07-27 11:51:35.194  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:51:35.194  7570  7631 I jxcore-log: 
07-27 11:51:35.194   771  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 11:51:35.194   771  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 11:51:35.194   771  1146 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
07-27 11:51:35.194   771  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 11:51:35.194   771  1702 I AudioService: getStreamVolume 3 index 0
07-27 11:51:35.194  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-27 11:51:35.194  7570  7631 I jxcore-log: 
07-27 11:51:35.194   771  1145 D NetworkStatsFactory: UpdateStatsForKnox
07-27 11:51:35.204   771  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:35.204   771  1045 D EntConnectivity: Not allowed due to - mEnabled false
07-27 11:51:35.204  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-27 11:51:35.204  7570  7631 I jxcore-log: 
07-27 11:51:35.204  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:51:35.204  7570  7631 I jxcore-log: 
07-27 11:51:35.204   771  1145 V NetworkStats: performPollLocked() took 10ms
07-27 11:51:35.204   771  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 11:51:35.204  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-27 11:51:35.204  7570  7631 I jxcore-log: 
07-27 11:51:35.204   771  1150 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
07-27 11:51:35.204   771  1150 D ConnectivityService: calling update connectivity
07-27 11:51:35.204   771  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:35.204   771  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:35.204   771  1150 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:35.204  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:51:35.204  7570  7631 I jxcore-log: 
07-27 11:51:35.204   771  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:35.204  1188  1597 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-27 11:51:35.204   771  1150 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 11:51:35.204  4499  7406 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-27 11:51:35.204  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:51:35.204  7570  7631 I jxcore-log: 
07-27 11:51:35.204  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 11:51:35.204  7570  7631 I jxcore-log: 
,07-27 11:51:35.204  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-27 11:51:35.204  7570  7631 I jxcore-log: 
,07-27 11:51:35.204  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:51:35.204  7570  7631 I jxcore-log: 
,07-27 11:51:35.204  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:51:35.204  7570  7631 I jxcore-log: 
07-27 11:51:35.204   771  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 11:51:35.204   771  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 11:51:35.204  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 11:51:35.204  7570  7631 I jxcore-log: 
07-27 11:51:35.204  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 11:51:35.204  7570  7631 I jxcore-log: 
,07-27 11:51:35.204  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:51:35.204  7570  7631 I jxcore-log: 
,07-27 11:51:35.214  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-27 11:51:35.214  7570  7631 I jxcore-log: 
,07-27 11:51:35.214  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 11:51:35.214  7570  7631 I jxcore-log: 
,07-27 11:51:35.214  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-27 11:51:35.214  7570  7631 I jxcore-log: 
,07-27 11:51:35.214  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 11:51:35.214  7570  7631 I jxcore-log: 
,07-27 11:51:35.214  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 11:51:35.214  7570  7631 I jxcore-log: 
07-27 11:51:35.214  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 11:51:35.214  7570  7631 I jxcore-log: 
,07-27 11:51:35.214  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 11:51:35.214  7570  7631 I jxcore-log: 
,07-27 11:51:35.214  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 11:51:35.214  7570  7631 I jxcore-log: 
,07-27 11:51:35.214  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 11:51:35.214  7570  7631 I jxcore-log: 
07-27 11:51:35.214  7570  7631 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-27 11:51:35.214  7570  7631 I jxcore-log: 
,07-27 11:51:35.214  7570  7631 I jxcore-log: My device name is: samsung-SM-N9005
07-27 11:51:35.214  7570  7631 I jxcore-log: 
,07-27 11:51:35.224  7570  7631 I jxcore-log: WARN testUtils: myNameCallback not set!
07-27 11:51:35.224  7570  7631 I jxcore-log: 
,07-27 11:51:35.264   771  8536 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,07-27 11:51:35.294   771  1150 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=true
,07-27 11:51:35.294   771  1150 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-27 11:51:35.294   771  1150 D ConnectivityService: identical MTU - not setting
07-27 11:51:35.294   771  1150 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
07-27 11:51:35.294   771  1150 D ConnectivityService: updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
07-27 11:51:35.294   771   771 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
07-27 11:51:35.294   771   771 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:35.294   297  1060 V         : QcRouteController
,07-27 11:51:35.294   771  1152 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-27 11:51:35.294   771  1152 D SmartBondingService: getSBEnabled() enabled =false
07-27 11:51:35.294   771  1152 D SmartBondingService: getSBEnabled() enabled =false
,07-27 11:51:35.294   771  1152 D SmartBondingService: getSBEnabled() enabled =false
,07-27 11:51:35.314   771  8536 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 27 Jul 2016 09:51:35 GMT], X-Android-Received-Millis=[1469613095327], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1469613095304]}
07-27 11:51:35.314   771  8536 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-27 11:51:35.314   771  8536 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,07-27 11:51:35.314   297  1060 V         : QcRouteController
,07-27 11:51:35.324   771  1150 W NetworkManagementService: route cmd failed: 
07-27 11:51:35.324   771  1150 W NetworkManagementService: com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '103 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 103 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
07-27 11:51:35.324   771  1150 W NetworkManagementService: '
07-27 11:51:35.324   771  1150 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
07-27 11:51:35.324   771  1150 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
07-27 11:51:35.324   771  1150 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
07-27 11:51:35.324   771  1150 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
07-27 11:51:35.324   771  1150 W NetworkManagementService: 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2844)
07-27 11:51:35.324   771  1150 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5632)
07-27 11:51:35.324   771  1150 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5444)
07-27 11:51:35.324   771  1150 W NetworkManagementService: 	at com.android.server.ConnectivityService.access$2400(ConnectivityService.java:230)
07-27 11:51:35.324   771  1150 W NetworkManagementService: 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2387)
07-27 11:51:35.324   771  1150 W NetworkManagementService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:51:35.324   771  1150 W NetworkManagementService: 	at android.os.Looper.loop(Looper.java:145)
07-27 11:51:35.324   771  1150 W NetworkManagementService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
07-27 11:51:35.324   771  1150 V Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true
07-27 11:51:35.324   771  1150 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
07-27 11:51:35.324   771  1150 D ConnectivityService: calling update connectivity
07-27 11:51:35.324   771  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:35.324   771  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-27 11:51:35.324   771  1150 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:35.324  1188  1597 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
07-27 11:51:35.324   771  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 11:51:35.324   771  1150 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 11:51:35.324  4499  7406 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,07-27 11:51:35.324   771  1150 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
,07-27 11:51:35.324   771  1150 D ConnectivityService: calling update connectivity
07-27 11:51:35.324   771  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:35.324   771  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-27 11:51:35.324   771  1150 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:35.324   771  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:35.324  1188  1597 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,07-27 11:51:35.324   771  1150 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:35.324   771  1150 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
07-27 11:51:35.324  4499  7406 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,07-27 11:51:35.324   771  1150 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
07-27 11:51:35.324   771  1150 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-27 11:51:35.324   771  1150 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:35.324   771  1150 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:35.324   771  1150 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
07-27 11:51:35.324   771  1150 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
,07-27 11:51:35.324   771  1150 D ConnectivityService: calling update connectivity
07-27 11:51:35.324   771  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:35.324   771  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-27 11:51:35.324   771  1150 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-27 11:51:35.324  1188  1597 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-27 11:51:35.324   771  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-27 11:51:35.324   771  1150 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-27 11:51:35.324  4499  7406 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-27 11:51:35.334   771  1150 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-27 11:51:35.334   771  3266 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:35.334  1188  1188 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-27 11:51:35.334  1188  1188 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-27 11:51:35.334  1188  1188 D StatusBar.NetworkController: updateDataNetType()
07-27 11:51:35.334  1188  1188 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
07-27 11:51:35.334  1188  1188 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,07-27 11:51:35.334  1188  1188 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-27 11:51:35.334  1188  1188 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
07-27 11:51:35.334  1188  1188 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,07-27 11:51:35.334  1188  1188 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020533/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020533/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014b/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-27 11:51:35.334  1188  1188 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-27 11:51:35.424  8612  8612 D AndroidRuntime: 
07-27 11:51:35.424  8612  8612 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-27 11:51:35.424  8612  8612 D AndroidRuntime: CheckJNI is OFF
,07-27 11:51:35.424  8612  8612 D AndroidRuntime: readGMSProperty: start
07-27 11:51:35.424  8612  8612 D AndroidRuntime: readGMSProperty: already setted!!
,07-27 11:51:35.424  8612  8612 D AndroidRuntime: readGMSProperty: end
07-27 11:51:35.424  8612  8612 D AndroidRuntime: addProductProperty: start
,07-27 11:51:35.554  8612  8612 E AffinityControl: AffinityControl: registerfunction enter
,07-27 11:51:35.574  8612  8612 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-27 11:51:35.584   771  1318 D PackageManager: START PACKAGE DELETE: observer{995614153}
07-27 11:51:35.584   771  1318 D PackageManager: pkg{<packageName>}
07-27 11:51:35.584   771  1318 D PackageManager: user{0}
07-27 11:51:35.584   771  1318 D PackageManager: caller{2000}
07-27 11:51:35.584   771  1318 D PackageManager: flags{2}
,07-27 11:51:35.584   771  1318 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-27 11:51:35.584   771  1318 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-27 11:51:35.584   771  1318 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-27 11:51:35.584   771  1318 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,07-27 11:51:35.584   771  1318 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,07-27 11:51:35.584   771  1063 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-27 11:51:35.584   771  1063 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-27 11:51:35.584   771  1063 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-27 11:51:35.584   771  1063 D ApplicationPolicy: getApplicationUninstallationEnabled
07-27 11:51:35.584   771  1063 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,07-27 11:51:35.594   771  1063 D PackageManager: !@killApplicatoin: 10079, uninstall pkg
,07-27 11:51:35.594   771   987 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
,07-27 11:51:35.594   771   987 I ActivityManager: Killing 7570:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest cause uninstall pkg
,07-27 11:51:35.604   771   987 I ActivityManager:   Force finishing activity ActivityRecord{253265c2 u0 com.test.thalitest/.MainActivity t99}
,07-27 11:51:35.604   771   987 D FocusedStackFrame: Set to : 0
,07-27 11:51:35.604   266  1337 I SurfaceFlinger: id=12 Removed NainActivit (6/9)
,07-27 11:51:35.604   266   343 I SurfaceFlinger: id=12 Removed NainActivit (-2/9)
,07-27 11:51:35.624   771  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-27 11:51:35.624   771  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 11:51:35.624   771  1047 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-27 11:51:35.624   771  1047 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-27 11:51:35.674   771  1063 W PackageSettings: Skipping PackageSetting{3c661129 com.example.hello/10078} due to missing metadata
,07-27 11:51:35.684   771  1150 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:51:35.704   771  3104 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:35.704   771   771 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:35.704   771   771 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:35.714   771  3266 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:35.714   771   771 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:35.714   771   771 D SmartBondingService: SmartBondingReceiver: wifi is connected
07-27 11:51:35.714   771   771 D SmartBondingService: SmartBondingReceiver: wifi ap is not changed
,07-27 11:51:35.714   771   771 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:35.714   771  1360 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:35.714   771  3266 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:35.714   771  1152 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-27 11:51:35.714   771  1152 D SmartBondingService: getSBEnabled() enabled =false
07-27 11:51:35.714   771  1152 D SmartBondingService: getSBEnabled() enabled =false
,07-27 11:51:35.714   771  1310 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:35.714   771  1152 D SmartBondingService: getSBEnabled() enabled =false
,07-27 11:51:35.714  7839  7839 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
07-27 11:51:35.714   771  1673 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:35.714   771  1702 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:35.714   771   796 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:35.714   771  1152 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-27 11:51:35.714   771  1469 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:35.714   771   771 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:35.714   771   771 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:35.714   771  1469 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:35.724   771   771 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:35.724   771   771 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:35.724  1487  1487 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
07-27 11:51:35.724   771   978 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-27 11:51:35.724   771   978 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:35.724   771   978 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:35.724   771  1063 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=0: pkg removed
07-27 11:51:35.734   771  3075 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:35.734   771  1702 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:35.734   771  1525 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:35.734   771  1143 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:35.734   771  3104 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:35.734   771  1702 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:35.734  6957  6957 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-27 11:51:35.734  6957  6957 I PCWCLIENTTRACE_PushUtil: sales region : global
07-27 11:51:35.734  6957  6957 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-27 11:51:35.734  6957  6957 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:51:35.774  7193  7193 I art     : Explicit concurrent mark sweep GC freed 13444(728KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 16MB/21MB, paused 320us total 35.929ms
07-27 11:51:35.784   771  1143 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-27 11:51:35.784   771  1143 D SecContentProvider2: mCursor = null
,07-27 11:51:35.804  4499  4499 I art     : Explicit concurrent mark sweep GC freed 32690(1877KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 24MB/40MB, paused 632us total 53.912ms
,07-27 11:51:35.814  3705  3705 I art     : Explicit concurrent mark sweep GC freed 5482(303KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 15MB/26MB, paused 352us total 27.799ms
,07-27 11:51:35.814   771   771 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
07-27 11:51:35.814   771   978 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,07-27 11:51:35.824   771  1047 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,07-27 11:51:35.824  1443  1443 D ResourcesManager: creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
07-27 11:51:35.824   771   771 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,07-27 11:51:35.824  1443  1443 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-27 11:51:35.824  1748  1748 E SamsungIME: mOCRHelper is null
07-27 11:51:35.824  1443  1443 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-27 11:51:35.824  1892  2381 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-27 11:51:35.824   771  1120 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-27 11:51:35.834   771   771 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,07-27 11:51:35.834   771  3010 E libprocessgroup: failed to kill 1 processes for processgroup 7570
,07-27 11:51:35.834  1443  1443 D ResourcesManager: creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
,07-27 11:51:35.834  5476  5476 I art     : Explicit concurrent mark sweep GC freed 650(36KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 301us total 31.054ms
,07-27 11:51:35.834  1443  1443 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 11:51:35.834  7839  7839 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
07-27 11:51:35.834  1443  1443 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-27 11:51:35.834  1416  1416 D RegisteredServicesCache: empty dynamic service
07-27 11:51:35.834  1443  1443 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-27 11:51:35.844  1443  1443 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
07-27 11:51:35.844  1443  1443 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-27 11:51:35.844  1443  1443 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
07-27 11:51:35.844  1487  1487 I art     : Explicit concurrent mark sweep GC freed 1551(72KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 20MB/33MB, paused 1.230ms total 49.611ms
07-27 11:51:35.854   771   771 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,07-27 11:51:35.854   771   771 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,07-27 11:51:35.864   771   978 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,07-27 11:51:35.864   771   771 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,07-27 11:51:35.864  7892  7892 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:51:35.864  7892  7892 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-27 11:51:35.874   771  1145 V NetworkStats: removeUidsLocked() for UIDs [10079]
07-27 11:51:35.874   771  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 11:51:35.874   771  1145 V NetworkStats: performPollLocked(flags=0x3)
,07-27 11:51:35.884   771   771 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,07-27 11:51:35.884   771  1145 D NetworkStatsFactory: UpdateStatsForKnox
07-27 11:51:35.884   771  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:35.884   771  1145 V NetworkStats: performPollLocked() took 15ms
07-27 11:51:35.884   771  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 11:51:35.884   771   771 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-27 11:51:35.904   771   771 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,07-27 11:51:35.924   771   771 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,07-27 11:51:35.924   771   978 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
,07-27 11:51:35.954   771   771 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,07-27 11:51:35.954   771  1318 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-27 11:51:35.954   771  1318 D SecContentProvider2: mCursor = null
,07-27 11:51:35.954   771   771 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,07-27 11:51:35.974   771   771 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,07-27 11:51:35.974   771   771 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,07-27 11:51:35.974   771  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-27 11:51:35.974   771  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-27 11:51:35.974   771   771 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,07-27 11:51:35.974   771   771 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,07-27 11:51:35.974   771   771 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
,07-27 11:51:35.984   771   771 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,07-27 11:51:35.984   771   771 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,07-27 11:51:36.004   771   771 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,07-27 11:51:36.004   771   771 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,07-27 11:51:36.004   771   771 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-27 11:51:36.014   771   771 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,07-27 11:51:36.014   771   771 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,07-27 11:51:36.014   771   978 D EnterpriseDeviceManagerService: Package has changed for user 0
07-27 11:51:36.014   771   978 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,07-27 11:51:36.024   771   771 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,07-27 11:51:36.024  7911  7911 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,07-27 11:51:36.034  7911  7911 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,07-27 11:51:36.034   771   771 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,07-27 11:51:36.034  7911  7911 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,07-27 11:51:36.034   771   771 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
,07-27 11:51:36.044   771   771 D RCPManagerService: PackageReceiver onReceive()
,07-27 11:51:36.044   771   771 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-27 11:51:36.044   771   771 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,07-27 11:51:36.044   771   978 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,07-27 11:51:36.054  4017  4017 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-27 11:51:36.054   771   771 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-27 11:51:36.054   771   771 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
07-27 11:51:36.054   771   771 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-27 11:51:36.054   771   771 V EnterpriseBillingPolicy: uID is 10079
07-27 11:51:36.054   771   771 V EnterpriseBillingPolicy: Removed Packageuid is0
07-27 11:51:36.054  4017  4017 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1469613096064
07-27 11:51:36.054   771   771 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-27 11:51:36.054   771   771 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
07-27 11:51:36.054   771   771 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-27 11:51:36.054   771   771 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-27 11:51:36.054   771   771 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
07-27 11:51:36.054   771   771 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-27 11:51:36.054  4017  4017 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,07-27 11:51:36.054   771  1143 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:36.054   771  1177 D TaskPersister: removeObsoleteFile: deleting file=99_task.xml
,07-27 11:51:36.054   771  1525 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.054  4017  4017 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,07-27 11:51:36.054  4017  4017 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().START
,07-27 11:51:36.054   771   771 V AlarmManagerEXT: com.test.thalitest(10079) is removed.
,07-27 11:51:36.064  4017  4017 I KLMS-2.4.511: : NetworkChangeOperations(): uploadRequestLog().START 
,07-27 11:51:36.064   771   978 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 11:51:36.064   771   978 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-27 11:51:36.064   771   978 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,07-27 11:51:36.074   771   978 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 11:51:36.074   771   978 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,07-27 11:51:36.074  4017  4017 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,07-27 11:51:36.084   771   978 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 11:51:36.084   771   978 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,07-27 11:51:36.094   771   794 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.094   771   978 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 11:51:36.094   771   978 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 11:51:36.094   771   978 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,07-27 11:51:36.094   771   978 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 11:51:36.094   771   978 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,07-27 11:51:36.104  7952  7952 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,07-27 11:51:36.104   771  1567 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,07-27 11:51:36.104   771  1567 D ActivityManager: caller:android.app.ApplicationThreadProxy@2844e1fa, r.packageName :com.samsung.android.app.galaxyfinder
,07-27 11:51:36.114   771   978 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,07-27 11:51:36.114   771   978 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,07-27 11:51:36.114   771   978 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,07-27 11:51:36.124   771   978 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 11:51:36.124   771   978 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,07-27 11:51:36.124   771   978 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,07-27 11:51:36.134   771  3104 I SQLiteConnectionPool: exportDB...
,07-27 11:51:36.134   771   978 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,07-27 11:51:36.134   771  1318 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.144  3577  8637 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,07-27 11:51:36.144   771   978 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-27 11:51:36.144  7969  7969 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,07-27 11:51:36.144  3577  8637 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
07-27 11:51:36.144   771  1063 I art     : Explicit concurrent mark sweep GC freed 84612(5MB) AllocSpace objects, 14(224KB) LOS objects, 29% free, 37MB/53MB, paused 2.831ms total 272.650ms
,07-27 11:51:36.144   771   978 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-27 11:51:36.144   771   978 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,07-27 11:51:36.144  7988  7988 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,07-27 11:51:36.144  7988  7988 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
07-27 11:51:36.154  7988  7988 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-27 11:51:36.154  3577  8637 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,07-27 11:51:36.154  7988  7988 I SA      : [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,07-27 11:51:36.154  7988  7988 I SA      : [OR] == isSIMCardReady false ==
07-27 11:51:36.154   771  1310 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.154  7988  7988 I SA      : [SCU] == networkStateCheck == true
,07-27 11:51:36.154  7988  7988 I SA      : [DM] getCountryCodeFromCSC : PL
07-27 11:51:36.154  7988  7988 I SA      : isChinaCountryCode : false
07-27 11:51:36.154  7988  7988 I SA      : [SCU] is ChinestModel Data Restricted   : false
,07-27 11:51:36.154  7988  7988 I SA      : [OR] == networkStateCheck true ==
,07-27 11:51:36.164  7988  7988 I SA      : [OR] GetMyCountryZoneTask
,07-27 11:51:36.164  7988  7988 I SA      : [OR] onReceive END
,07-27 11:51:36.164  7988  8638 I SA      : [SRS] prepareGetMyCountryZone
,07-27 11:51:36.174  7988  8638 I SA      : [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,07-27 11:51:36.174  7988  8638 I SA      : [SSP] query invoked
,07-27 11:51:36.174  3577  8637 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,07-27 11:51:36.174  3577  8637 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,07-27 11:51:36.184  3577  8637 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,07-27 11:51:36.184  3577  8637 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,07-27 11:51:36.184  3577  8637 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,07-27 11:51:36.184  3577  8637 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,07-27 11:51:36.184   771   978 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,07-27 11:51:36.184  7988  8638 I SA      : [TPMU] GetMccFromDB : null
07-27 11:51:36.184   771   978 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-27 11:51:36.184   771   978 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-27 11:51:36.184  7988  8638 I SA      : [SCU] getMccFromPreferece mcc = 260
,07-27 11:51:36.184  3577  8637 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,07-27 11:51:36.194  7988  8638 I SA      : [TPM] isNoProxy(default) : true
07-27 11:51:36.194   771  3075 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.194   771  1428 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,07-27 11:51:36.194   771  1428 D ActivityManager: caller:android.app.ApplicationThreadProxy@499bdaa, r.packageName :com.android.providers.downloads
,07-27 11:51:36.194  3577  8637 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,07-27 11:51:36.204   771  1063 D PackageManager: delete codoeFile: 
,07-27 11:51:36.204  3577  8637 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,07-27 11:51:36.204  7988  8638 E File    : fail readDirectory() errno=2
,07-27 11:51:36.204   771  1150 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,07-27 11:51:36.214   771  1063 D AASAuninstall: userId = 0, info.removedAppID = 10079, info.uid = 10079, packageName = com.test.thalitest
,07-27 11:51:36.214   771  1063 I AASA_removePackage: UID=10079 Target=com.test.thalitest
,07-27 11:51:36.214   771  1525 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.214  3577  8637 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,07-27 11:51:36.224   771  1063 D PackageManager: result of delete: 1{995614153}
,07-27 11:51:36.224   771  3104 I SQLiteConnectionPool: ...exportDB
,07-27 11:51:36.224  8009  8009 I SCloudBackupReceiver: Other Intent
,07-27 11:51:36.234  8612  8612 D AndroidRuntime: Shutting down VM
,07-27 11:51:36.234   771  3104 D SSRM:aY : MSG_TYPE_APP_REMOVED::
,07-27 11:51:36.234   771   978 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 11:51:36.234   771   978 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,07-27 11:51:36.234  7338  7338 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
07-27 11:51:36.234  7338  7338 I KnoxUsageLogPro: premStatus:2
,07-27 11:51:36.244  7338  7338 I KnoxUsageLogPro: isEulaShown : false
07-27 11:51:36.244  7338  7338 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-27 11:51:36.244   771  1063 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-27 11:51:36.244   771  1063 D PackageManager: userId{-1}
07-27 11:51:36.244   771  1063 D PackageManager: andCode{true}
,07-27 11:51:36.254   771   978 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,07-27 11:51:36.264   771   978 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,07-27 11:51:36.264   771  1063 D ActivityManager: caller:null, r.packageName :com.android.defcontainer
,07-27 11:51:36.264   771  1063 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:36.264   771  1063 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:36.264   771  1063 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:36.264   771  1063 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:36.264   771   978 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,07-27 11:51:36.274   771   978 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,07-27 11:51:36.274   771   978 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 11:51:36.274   771   978 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,07-27 11:51:36.274   771   978 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 11:51:36.274   771   978 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,07-27 11:51:36.284   771   978 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-27 11:51:36.284   771   978 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-27 11:51:36.284   771   978 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,07-27 11:51:36.284   771   978 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 11:51:36.284   771   978 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,07-27 11:51:36.284   771   978 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-27 11:51:36.284   771   978 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-27 11:51:36.284   771   978 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,07-27 11:51:36.294   771   978 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-27 11:51:36.294   771   978 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-27 11:51:36.294   771   978 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,07-27 11:51:36.304   771   978 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-27 11:51:36.304  8642  8642 E Zygote  : MountEmulatedStorage()
07-27 11:51:36.304  8642  8642 E Zygote  : v2
07-27 11:51:36.304  8642  8642 I libpersona: KNOX_SDCARD checking this for 10007
07-27 11:51:36.304  8642  8642 I libpersona: KNOX_SDCARD not a persona
,07-27 11:51:36.314   771  1063 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8642 uid=10007 gids={50007, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,07-27 11:51:36.314   771   978 D UsbSettingsManager: clearDefaults: com.test.thalitest
,07-27 11:51:36.314   771   978 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,07-27 11:51:36.334  8642  8642 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-27 11:51:36.334  8642  8642 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-27 11:51:36.334   771  1506 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.334  8642  8642 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 11:51:36.344   771  1673 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.354   771   796 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.354  8642  8642 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:36.354  8642  8642 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:36.374  8105  8105 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,07-27 11:51:36.374  8105  8105 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,07-27 11:51:36.374  8105  8105 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,07-27 11:51:36.374  8642  8642 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DefaultContainerService/DefaultContainerService.apk
,07-27 11:51:36.374   771  3266 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.374   771   794 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.374   771  1567 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 11:51:36.374   771  3075 D RCPManagerService: exchangeData() failure , invalid userId
,07-27 11:51:36.384  1443  1443 D SurfaceWidgetView: destroyHardwareResources():328834930
,07-27 11:51:36.384   771  1469 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:36.384   771  1360 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-27 11:51:36.384   771  1360 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-27 11:51:36.384   771  1360 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
07-27 11:51:36.384   771  1360 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-27 11:51:36.384   771  1360 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
07-27 11:51:36.384  6793  6793 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-27 11:51:36.384  6793  6793 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-27 11:51:36.384  6793  6793 D SecurityLogAgent: StateMachine : Current State = 1
07-27 11:51:36.384   771  1310 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.384  6793  6793 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-27 11:51:36.384  1443  1443 D Launcher: onRestart, Launcher: 46211915
,07-27 11:51:36.384  1443  1443 D Launcher: onStart, Launcher: 46211915
,07-27 11:51:36.384  1443  1443 D Launcher.HomeView: onStart
,07-27 11:51:36.394  1443  1443 V ActivityThread: updateVisibility : ActivityRecord{2d8f79af token=android.os.BinderProxy@11aaf0b2 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
07-27 11:51:36.394  1826  1842 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
07-27 11:51:36.394  1826  2123 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
,07-27 11:51:36.394  1826  2123 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,07-27 11:51:36.394   771  3266 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.394   771  1428 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.394   771   794 D ActivityManager: startService callerProcessName:com.sec.android.app.SmartClipService, calleePkgName: com.sec.android.app.SmartClipService
,07-27 11:51:36.394   771   794 D ActivityManager: caller:android.app.ApplicationThreadProxy@c0a6881, r.packageName :com.sec.android.app.SmartClipService
,07-27 11:51:36.404   266   266 I SurfaceFlinger: id=14 createSurf (1080x1920),1 flag=4, Mauncher
,07-27 11:51:36.404   771  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-27 11:51:36.404   771  1043 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-27 11:51:36.414   771  1047 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,07-27 11:51:36.414   771  1047 D PointerIcon: setMouseCustomIcon IconType is same.101
07-27 11:51:36.414   771  1047 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-27 11:51:36.414   771  1047 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-27 11:51:36.414   771  1567 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-27 11:51:36.414   771  1567 D ActivityManager: caller:android.app.ApplicationThreadProxy@210bfd26, r.packageName :com.google.android.gms
,07-27 11:51:36.414   771  1143 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.414   771   794 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:36.414   771  3075 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.424   771  1428 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-27 11:51:36.424   771  1506 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.424   771  1360 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:36.424   771  1428 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 7570 uid 10079
,07-27 11:51:36.424   771  1567 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:36.424  4499  4499 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
07-27 11:51:36.424   771  8662 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-27 11:51:36.434  4499  5434 I iu.UploadsManager: num queued entries: 0
,07-27 11:51:36.434  4499  5434 I iu.UploadsManager: num updated entries: 0
,07-27 11:51:36.434  4499  5434 I iu.SyncManager: NEXT; no task
,07-27 11:51:36.434   771  1506 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.434  7255  7255 D WaitQueueForNetworkActivate: notifyNetworkActivated
,07-27 11:51:36.474   771  1047 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{44468ba u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t97} time:357786
,07-27 11:51:36.554   771   794 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.554  1892  8663 I qtaguid : Tagging socket 52 with tag 1000040700000000{268436487,0} uid -1, pid: 1892, getuid(): 10015
,07-27 11:51:36.564   771   796 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.564   771  1469 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.564   771  1702 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.584   771   794 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,07-27 11:51:36.584   771   794 D ActivityManager: caller:android.app.ApplicationThreadProxy@2aa08d67, r.packageName :com.sec.android.app.samsungapps
,07-27 11:51:36.594  4017  4017 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-27 11:51:36.594  4017  4017 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1469613096603
,07-27 11:51:36.594  4017  4017 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
,07-27 11:51:36.594  4017  4017 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,07-27 11:51:36.604  7255  7255 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,07-27 11:51:36.604  7255  7255 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,07-27 11:51:36.604  7255  7255 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,07-27 11:51:36.604  7255  7255 D InitializeManagerStateMachine: exit::IDLE
07-27 11:51:36.604  7255  7255 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,07-27 11:51:36.604   771  1525 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.604   771  1318 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-27 11:51:36.604  7255  7255 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
07-27 11:51:36.604  7255  7255 D InitializeManagerStateMachine: exit::NETWORK_CHECK
07-27 11:51:36.604  7255  7255 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
07-27 11:51:36.604  7255  7255 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
07-27 11:51:36.604  7255  7255 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
07-27 11:51:36.604  7255  7255 D InitializeManagerStateMachine: entry::SUCCESS
07-27 11:51:36.604  7255  7255 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,07-27 11:51:36.604  7255  7255 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
07-27 11:51:36.604  7255  7255 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,07-27 11:51:36.604   771  1310 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.604  7255  7255 D InitializeManagerStateMachine: exit::SUCCESS
07-27 11:51:36.604  7255  7255 D InitializeManagerStateMachine: entry::IDLE
,07-27 11:51:36.634   771  1120 I EventHub: Removing device '/dev/input/event6' due to inotify event
,07-27 11:51:36.644  4017  4017 I KLMS-2.4.511: : MainReciver(): Notification App List is Null. Remove Notification.
,07-27 11:51:36.644  4017  4017 I KLMS-2.4.511: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,07-27 11:51:36.644   771  1428 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,07-27 11:51:36.654   771  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:36.654   771  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:36.654   771  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:36.654   771  1428 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:36.664   771  1120 I EventHub: Removing device '/dev/input/event7' due to inotify event
,07-27 11:51:36.684  8672  8672 E Zygote  : MountEmulatedStorage()
07-27 11:51:36.684  8672  8672 E Zygote  : v2
07-27 11:51:36.684  8672  8672 I libpersona: KNOX_SDCARD checking this for 10116
07-27 11:51:36.684  8672  8672 I libpersona: KNOX_SDCARD not a persona
,07-27 11:51:36.704   771  1428 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8672 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,07-27 11:51:36.704   332   332 I art     : Explicit concurrent mark sweep GC freed 8728(371KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 1.629ms total 14.234ms
,07-27 11:51:36.714   771  1120 I EventHub: Removing device '/dev/input/event8' due to inotify event
,07-27 11:51:36.724   332   332 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 276us total 10.051ms
,07-27 11:51:36.734   332   332 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 40% free, 15MB/25MB, paused 276us total 9.446ms
,07-27 11:51:36.744  8672  8672 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 11:51:36.744  8672  8672 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-27 11:51:36.744   771  1525 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.744   771  1318 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.744   771  1702 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.744   771  1458 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.754   771   796 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.754   771  1428 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.754   771  1318 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-27 11:51:36.764   771  1120 I EventHub: Removing device '/dev/input/event9' due to inotify event
,07-27 11:51:36.794  8672  8672 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-27 11:51:36.794  8672  8672 D ActivityThread: Added TimaKeyStore provider
,07-27 11:51:36.794  7988  8638 I SA      : [RC New] Execute method=[GET] start
,07-27 11:51:36.804   771  1120 I EventHub: Removing device '/dev/input/event10' due to inotify event
07-27 11:51:36.804  8672  8672 D ResourcesManager: creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,07-27 11:51:36.804  8672  8672 W ContextImpl: Unable to create files subdir /data/data/com.sec.esdk.elm/cache
,07-27 11:51:36.804  8672  8672 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,07-27 11:51:36.814  3658  3658 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,07-27 11:51:36.814  3658  3658 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,07-27 11:51:36.814  3658  3658 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
07-27 11:51:36.814  3658  3658 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-27 11:51:36.814  3658  3658 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
07-27 11:51:36.814  3658  3658 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-27 11:51:36.814  3658  3658 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
,07-27 11:51:36.814  3658  3658 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:51:36.824  3658  3658 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-27 11:51:36.824  3658  3658 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 11:51:36.824  3658  3658 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:51:36.824  3658  3658 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 11:51:36.824  3658  3658 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
,07-27 11:51:36.824  3658  3658 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,07-27 11:51:36.824   771  1458 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.service.health, hostingType: broadcast
07-27 11:51:36.824   771  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:36.824   771  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:36.824   771  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-27 11:51:36.824   771  1458 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-27 11:51:36.834  8672  8672 D AndroidRuntime: Shutting down VM
,07-27 11:51:36.854   771  1120 I EventHub: Removing device '/dev/input/event11' due to inotify event
,07-27 11:51:36.854  8672  8672 E AndroidRuntime: FATAL EXCEPTION: main
07-27 11:51:36.854  8672  8672 E AndroidRuntime: Process: com.sec.esdk.elm, PID: 8672
07-27 11:51:36.854  8672  8672 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate receiver com.sec.esdk.elm.receiver.MainReceiver: java.lang.ClassNotFoundException: Didn't find class "com.sec.esdk.elm.receiver.MainReceiver" on path: DexPathList[[zip file "/system/app/ELMAgent/ELMAgent.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2970)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: Caused by: java.lang.ClassNotFoundException: Didn't find class "com.sec.esdk.elm.receiver.MainReceiver" on path: DexPathList[[zip file "/system/app/ELMAgent/ELMAgent.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2965)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 	... 9 more
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 	Suppressed: java.io.IOException: Zip archive '/system/app/ELMAgent/ELMAgent.apk' doesn't contain classes.dex (error msg: Entry not found)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFileNative(Native Method)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:80)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:59)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Native Method)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Method.java:372)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62,)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5082)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		... 7 more
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/app/ELMAgent/ELMAgent.apk'
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		... 27 more
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from /system/app/ELMAgent/arm/ELMAgent.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		... 27 more
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 	Caused by: java.io.IOException: 
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		... 27 more
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 	Suppressed: java.lang.ClassNotFoundException: com.sec.esdk.elm.receiver.MainReceiver
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at java.lang.Class.classForName(Native Method)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 		... 11 more
07-27 11:51:36.854  8672  8672 E AndroidRuntime: 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
07-27 11:51:36.864  8687  8687 E Zygote  : MountEmulatedStorage()
07-27 11:51:36.864  8687  8687 E Zygote  : v2
07-27 11:51:36.864  8687  8687 I libpersona: KNOX_SDCARD checking this for 10021
07-27 11:51:36.864  8687  8687 I libpersona: KNOX_SDCARD not a persona
07-27 11:51:36.864  7988  8638 I SA      : [RC New] Security=[true]
07-27 11:51:36.874   771  1458 I ActivityManager: Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8687 uid=10021 gids={50021, 9997} abi=armeabi-v7a
07-27 11:51:36.874  7988  8638 I System.out: Thread-1280(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
07-27 11:51:36.874   771  1143 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.esdk.elm
07-27 11:51:36.874  7988  8638 I System.out: Thread-1280(ApacheHTTPLog):isShipBuild true
,07-27 11:51:36.904   771  1120 I EventHub: Removing device '/dev/input/event12' due to inotify event
,07-27 11:51:36.914  8687  8687 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-27 11:51:36.914  8687  8687 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-27 11:51:36.914   771  3075 I ActivityManager: Killing 6101:sstream.app/u0a25 (adj 15): emptyCount ##41
,07-27 11:51:36.924   771  8694 E AndroidRuntime: *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
07-27 11:51:36.924   771  8694 E AndroidRuntime: java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
07-27 11:51:36.924   771  8694 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:46)
07-27 11:51:36.924   771  8694 E AndroidRuntime: 	at android.os.StatFs.restat(StatFs.java:56)
07-27 11:51:36.924   771  8694 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
07-27 11:51:36.924   771  8694 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
07-27 11:51:36.924   771  8694 E AndroidRuntime: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-27 11:51:36.924   771  8694 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
07-27 11:51:36.924   771  8694 E AndroidRuntime: Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
07-27 11:51:36.924   771  8694 E AndroidRuntime: 	at libcore.io.Posix.statvfs(Native Method)
07-27 11:51:36.924   771  8694 E AndroidRuntime: 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
07-27 11:51:36.924   771  8694 E AndroidRuntime: 	at android.system.Os.statvfs(Os.java:473)
07-27 11:51:36.924   771  8694 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:44)
07-27 11:51:36.924   771  8694 E AndroidRuntime: 	... 5 more
,07-27 11:51:36.934   771  8694 E android.os.Debug: ro.product_ship = true
07-27 11:51:36.934   771  8694 E android.os.Debug: ro.debug_level = 0x4f4c
,07-27 11:51:36.934   771  8694 E AndroidRuntime: Error reporting crash
07-27 11:51:36.934   771  8694 E AndroidRuntime: java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
07-27 11:51:36.934   771  8694 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:46)
07-27 11:51:36.934   771  8694 E AndroidRuntime: 	at android.os.StatFs.restat(StatFs.java:56)
07-27 11:51:36.934   771  8694 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
07-27 11:51:36.934   771  8694 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
07-27 11:51:36.934   771  8694 E AndroidRuntime: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
07-27 11:51:36.934   771  8694 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
07-27 11:51:36.934   771  8694 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:15161)
07-27 11:51:36.934   771  8694 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:14749)
07-27 11:51:36.934   771  8694 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:14733)
07-27 11:51:36.934   771  8694 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
07-27 11:51:36.934   771  8694 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
07-27 11:51:36.934   771  8694 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
07-27 11:51:36.934   771  8694 E AndroidRuntime: Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
07-27 11:51:36.934   771  8694 E AndroidRuntime: 	at libcore.io.Posix.statvfs(Native Method)
07-27 11:51:36.934   771  8694 E AndroidRuntime: 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
07-27 11:51:36.934   771  8694 E AndroidRuntime: 	at android.system.Os.statvfs(Os.java:473)
07-27 11:51:36.934   771  8694 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:44)
07-27 11:51:36.934   771  8694 E AndroidRuntime: 	... 11 more
07-27 11:51:36.934   771  8694 I Process : Sending signal. PID: 771 SIG: 9
,07-27 11:51:36.944  8672  8672 I Process : Sending signal. PID: 8672 SIG: 9
,07-27 11:51:36.944  7988  8638 I System.out: Thread-1280(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,07-27 11:51:36.964   304   304 E SMD     : DCD ON
,07-27 11:51:37.094   264   264 I ServiceManager: service 'wifip2p' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'quickconnect' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'samplingprofiler' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'commontime_management' died
07-27 11:51:37.094   266  1337 I SurfaceFlinger: restart the boot-animation @ binderDied
07-27 11:51:37.094   264   264 I ServiceManager: service 'dreams' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'print' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'restrictions' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'media_session' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'media_router' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'trust' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'fingerprint' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'launcherapps' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'voip' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'media_projection' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'lpnet' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'imms' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'connectivity' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'sb_service' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'servicediscovery' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'updatelock' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'notification' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'devicestoragemonitor' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'location' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'country_detector' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'search' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'dropbox' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'wallpaper' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'audio' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'sec_analytics' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'cover' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'mount' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'lock_settings' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'device_policy' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'harmony_eas_service' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'sdp' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'log_manager_service' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'enterprise_license_policy' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'mum_container_policy' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'enterprise_billing_policy' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'knox_timakeystore_policy' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'enterprise_policy' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'statusbar' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'clipboard' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'clipboardEx' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'network_management' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'DockObserver' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'usb' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'serial' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'uimode' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'jobscheduler' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'ABTPersistenceService' died
07-27 11:51:37.094   264   264 I Service,Manager: service 'textservices' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'network_score' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'netstats' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'netpolicy' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'wifi' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'msapwifi' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'wifiscanner' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'rttmanager' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'edmnativehelper' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'user' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'dbinfo' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'hardware' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'procstats' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'telephony.registry' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'CustomFrequencyManagerService' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'samsung.smartfaceservice' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'consumer_ir' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'application_policy' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'wifi_policy' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'phone_restriction_policy' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'remoteinjection' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'alarm' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'input_method' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'accessibility' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'motion_recognition' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'backup' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'appwidget' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'voiceinteraction' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'SecExternalDisplayService' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'diskstats' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'mDNIe' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'spengestureservice' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'context_aware' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'scontext' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'barbeam' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'multiwindow_facade' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'window' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'input' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'tactileassist' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'bluetooth_manager' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'bluetooth_secure_mode_manager' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'rcp' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'entropy' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'SEAMService' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'persona' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'account' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'content' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'DirEncryptService' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'ReactiveService' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'batterystats' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'appops' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'sedenial' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'vibrator' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'tima' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'cepproxyks' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'scheduling_policy' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'activity' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'usagestats' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'webviewupdate' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'package' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'battery' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'meminfo' died
07-27 11:51:37.094  1892  5534 W Sensors : sensorservice died [0xb3b4b340]
07-27 11:51:37.094   264   264 I ServiceManager: service 'cpuinfo' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'gfxinfo' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'permission' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'power' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'display' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'persona_policy' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'mdm.remotedesktop' died
07-27 11:51:37.094   264   264 I ServiceManager: service 'sensorservice' died
07-27 11:51:37.094  1188  1221 W Sensors : sensorservice died [0xaf07f240]
07-27 11:51:37.094   309   681 W AudioFlinger: power manager service died !!!
07-27 11:51:37.094   309   681 W AudioCache: clearPowerManager -mWakeLockCount is 0, failed to releaseWakeLock function
07-27 11:51:37.094  1826  2793 W Sensors : sensorservice died [0xafb012c0]
07-27 11:51:37.094  1916  1978 W Sensors : sensorservice died [0xaf0bd9c0]
07-27 11:51:37.104  1405  1415 W Sensors : sensorservice died [0xaf0bd900]
07-27 11:51:37.104   266   266 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6962000
07-27 11:51:37.104   266   266 D qdhwcomposer: hwc_blank: Unblanking display: 0
07-27 11:51:37.104  1487  3931 E WifiManager: Channel connection lost
07-27 11:51:37.104  1188  1596 E WifiManager: Channel connection lost
07-27 11:51:37.104  1892  2380 E WifiManager: Channel connection lost
07-27 11:51:37.104  8687  8687 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x74a3d726 in tid 8687 (.service.health)
07-27 11:51:37.104   266   343 I SurfaceFlinger: id=2 Removed GocusedStac (5/9)
07-27 11:51:37.104   266   343 I SurfaceFlinger: id=3 Removed EimLayer (0/8)
07-27 11:51:37.104   266   343 I SurfaceFlinger: id=4 Removed EimLayer (0/7)
07-27 11:51:37.104   266   343 I SurfaceFlinger: id=5 Removed EimLayer (0/6)
07-27 11:51:37.104   266   343 I SurfaceFlinger: id=6 Removed EimLayer (0/5)
07-27 11:51:37.104   266   343 I SurfaceFlinger: id=2 Removed GocusedStac (-2/5)
07-27 11:51:37.104   266   343 I SurfaceFlinger: id=3 Removed EimLayer (-2/5)
07-27 11:51:37.104   266   343 I SurfaceFlinger: id=4 Removed EimLayer (-2/5)
07-27 11:51:37.104   266   343 I SurfaceFlinger: id=5 Removed EimLayer (-2/5)
07-27 11:51:37.104   266   343 I SurfaceFlinger: id=6 Removed EimLayer (-2/5)
07-27 11:51:37.104   266   343 I SurfaceFlinger: id=7 Removed JmageWallpa (0/4)
07-27 11:51:37.104   266   343 I SurfaceFlinger: id=7 Removed JmageWallpa (-2/4)
07-27 11:51:37.104   266   343 I SurfaceFlinger: id=8 Removed TtatusBar (1/3)
07-27 11:51:37.104   266   343 I SurfaceFlinger: id=13 Removed Uoast (1/2)
07-27 11:51:37.104   266   343 I SurfaceFlinger: id=14 Removed Mauncher (0/1)
07-27 11:51:37.104   266   343 I SurfaceFlinger: id=8 Removed TtatusBar (-2/1)
07-27 11:51:37.104   266   343 I SurfaceFlinger: id=14 Removed Mauncher (-2/1)
07-27 11:51:37.104   266   343 I SurfaceFlinger: id=13 Removed Uoast (-2/1)
07-27 11:51:37.104   266   343 I SurfaceFlinger: id=11 Removed DolorFade (0/0)
07-27 11:51:37.104   266   343 I SurfaceFlinger: id=11 Removed DolorFade (-2/0)
07-27 11:51:37.114  1427  1766 E WifiManager: Channel connection lost
07-27 11:51:37.114  7722  7744 E WifiManager: Channel connection lost
07-27 11:51:37.114  1312  2826 E WifiManager: Channel connection lost
07-27 11:51:37.114  1517  2187 E WifiManager: Channel connection lost
07-27 11:51:37.114  1427  1461 W Sensors : sensorservice died [0xa0a01140]
07-27 11:51:37.114  1443  1463 W Sensors : sensorservice died [0xaf0f1200]
,07-27 11:51:37.174   314   314 E installd: eof
07-27 11:51:37.174   314   314 E installd: failed to read size
07-27 11:51:37.174   314   314 I installd: closing connection
,07-27 11:51:37.214   298   298 I DEBUG   : failed to create /data/tombstones: Read-only file system
07-27 11:51:37.214   298   298 I DEBUG   : failed to open /data/tombstones: No such file or directory
07-27 11:51:37.214   298   298 E         : ro.product_ship = true
07-27 11:51:37.214   298   298 E         : ro.debug_level = 0x4f4c
,07-27 11:51:37.214  1874  1874 E audit_log: File locking failed. error= Bad file number
,07-27 11:51:37.284   332   332 I Zygote  : Process 8687 exited due to signal (7)
,07-27 11:51:37.344   266   514 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,07-27 11:51:37.344   266   266 E qdexternal: writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
07-27 11:51:37.344   266   266 D qdhwcomposer: hwc_blank: Done unblanking display: 0
07-27 11:51:37.344   266   529 E qdhwcomposer: hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Operation not permitted
07-27 11:51:37.344   266   529 E SurfaceFlinger: eventControl(0, 1) failed Operation not permitted
,07-27 11:51:37.504   266   514 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,07-27 11:51:37.524  7988  8638 I SA      : [RC New] [v2liruge] api execute + 664
07-27 11:51:37.524  7988  8638 I SA      : [RC New] executeRequest [v2liruge] httpResponse : HTTP/1.1 200 OK
07-27 11:51:37.524  7988  8638 I System.out: AsyncTask #1 calls detatch()
,07-27 11:51:37.534  7988  8638 I SA      : [TPMU] getNetworkMcc : 
,07-27 11:51:37.544  7988  8638 I SA      : [SCU] saveMccToPreferece Start
07-27 11:51:37.544  7988  8638 I SA      : [SCU] RegionMCC : 260
07-27 11:51:37.544  7988  8638 I SA      : [SSP] query invoked
,07-27 11:51:37.544  7988  8638 I SA      : [TPMU] GetMccFromDB : null
,07-27 11:51:37.544  7988  8638 I SA      : [SCU] getMccFromPreferece mcc = 260
,07-27 11:51:37.544  7988  8638 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.osp.app.signin/shared_prefs/SERVICE_DISTRICT.xml
,07-27 11:51:37.544  7988  8638 I SA      : [SCU] saveMccToPreferece End
,07-27 11:51:37.544  7988  8638 I SA      : [RC New] executeRequest [v2liruge] end. 745
,07-27 11:51:37.544  7988  8638 I SA      : [RC New] Execute end
07-27 11:51:37.544  7988  7988 I SA      : [OR] GetMyCountryZoneTask mcc = 260
,07-27 11:51:37.544  7988  7988 I SA      : [OR] GetMyCountryZoneTask Success
,07-27 11:51:37.554  8411  8437 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new

```
