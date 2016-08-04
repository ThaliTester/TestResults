#### Test 79426650eeb77ae_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
08-05 01:29:18.604   303   303 E SMD     : DCD ON
,08-05 01:29:18.894  7631  7631 D AndroidRuntime: 
08-05 01:29:18.894  7631  7631 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-05 01:29:18.904  7631  7631 D AndroidRuntime: CheckJNI is OFF
08-05 01:29:18.904  7631  7631 D AndroidRuntime: readGMSProperty: start
08-05 01:29:18.904  7631  7631 D AndroidRuntime: readGMSProperty: already setted!!
08-05 01:29:18.904  7631  7631 D AndroidRuntime: readGMSProperty: end
08-05 01:29:18.904  7631  7631 D AndroidRuntime: addProductProperty: start
08-05 01:29:19.074  7631  7631 E AffinityControl: AffinityControl: registerfunction enter
08-05 01:29:19.094  7631  7631 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-05 01:29:19.104   760   775 E PersonaManagerService: inState():  stateMachine is null !!
08-05 01:29:19.104   760   775 I PersonaManagerService: PersonaId don't exist
08-05 01:29:19.104   760   775 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-05 01:29:19.104   760   775 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
--------- beginning of system
08-05 01:29:19.104   760   775 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-05 01:29:19.104   760   775 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
08-05 01:29:19.114   760   775 W ActivityManager: mDVFSHelper.acquire()
08-05 01:29:19.114   760   775 D FocusedStackFrame: Set to : 0
08-05 01:29:19.114   760   775 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 01:29:19.114   760   775 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 01:29:19.114   760   775 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 01:29:19.114   760   775 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 01:29:19.174   760   775 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7646 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-05 01:29:19.174  7631  7631 D AndroidRuntime: Shutting down VM
08-05 01:29:19.184  7646  7646 E Zygote  : MountEmulatedStorage()
08-05 01:29:19.184  7646  7646 E Zygote  : v2
08-05 01:29:19.184  7646  7646 I libpersona: KNOX_SDCARD checking this for 10079
08-05 01:29:19.184  7646  7646 I libpersona: KNOX_SDCARD not a persona
08-05 01:29:19.204   346   346 I art     : Explicit concurrent mark sweep GC freed 8781(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 3.593ms total 29.097ms
08-05 01:29:19.204  7646  7646 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 01:29:19.204  7646  7646 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-05 01:29:19.204   760  1038 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-05 01:29:19.204   760  1038 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 01:29:19.204   760  1038 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-05 01:29:19.204   760  1038 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-05 01:29:19.204  7646  7646 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-05 01:29:19.214   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 280us total 9.577ms
08-05 01:29:19.234   346   346 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 504us total 15.665ms
08-05 01:29:19.244  7646  7646 D TimaKeyStoreProvider: TimaSignature is unavailable
08-05 01:29:19.244  7646  7646 D ActivityThread: Added TimaKeyStore provider
08-05 01:29:19.244   760  1326 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-05 01:29:19.244   760  1326 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
08-05 01:29:19.244   760  1326 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-05 01:29:19.244   760  1326 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-05 01:29:19.244   760  1326 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
08-05 01:29:19.274  1430  1430 D SurfaceWidgetView: destroyHardwareResources():1002998330
08-05 01:29:19.274   760  3300 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 01:29:19.284  7646  7646 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
08-05 01:29:19.314   266  1429 I SurfaceFlinger: id=8 Removed Mauncher (6/8)
08-05 01:29:19.314   266   365 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
08-05 01:29:19.324  1757  1777 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
08-05 01:29:19.324  1430  1430 V ActivityThread: updateVisibility : ActivityRecord{265a8444 token=android.os.BinderProxy@32d5d37a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-05 01:29:19.324  1430  1430 D Launcher: onTrimMemory. Level: 20
,08-05 01:29:19.414  7646  7646 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,08-05 01:29:19.414  7646  7646 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,08-05 01:29:19.424  7646  7646 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 5085-5087)
,08-05 01:29:19.424  7646  7646 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-05 01:29:19.444  7646  7646 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3d2b2ead}
,08-05 01:29:19.454  7646  7646 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-05 01:29:19.454  7646  7646 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-05 01:29:19.484  7646  7646 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-05 01:29:19.484  7646  7646 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-05 01:29:19.484  7646  7646 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-05 01:29:19.504  7646  7646 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
08-05 01:29:19.504  7646  7646 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
08-05 01:29:19.504  7646  7646 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
08-05 01:29:19.514  7646  7646 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
08-05 01:29:19.514  7646  7646 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
08-05 01:29:19.514  7646  7646 I Adreno-EGL: Build Date: 11/19/14 Wed
08-05 01:29:19.514  7646  7646 I Adreno-EGL: Local Branch: mybranch5813579
08-05 01:29:19.514  7646  7646 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
08-05 01:29:19.514  7646  7646 I Adreno-EGL: Local Patches: NONE
08-05 01:29:19.514  7646  7646 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,08-05 01:29:19.604   760  1044 I PowerManagerService: [PWL] Off : 75s ago
,08-05 01:29:19.714  7646  7679 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,08-05 01:29:19.764   760   941 W ActivityManager: Activity pause timeout for ActivityRecord{221d07cd u0 com.test.thalitest/.MainActivity t99},
,08-05 01:29:19.774  7646  7646 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-05 01:29:19.784  7646  7646 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-05 01:29:19.804  7646  7646 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-05 01:29:19.814  7646  7646 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-05 01:29:19.814  7646  7646 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-05 01:29:19.884  7646  7646 D Activity: performCreate Call secproduct feature valuefalse
,08-05 01:29:19.884  7646  7646 D Activity: performCreate Call debug elastic valuetrue
,08-05 01:29:19.894  7646  7699 D OpenGLRenderer: Render dirty regions requested: true
,08-05 01:29:19.904   760  3207 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-05 01:29:19.904   760  3207 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-05 01:29:19.904   760  3207 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
,08-05 01:29:19.904   760   760 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-05 01:29:19.904   760   760 D PersonaManagerService: getPersonasForUser(): returning null!
,08-05 01:29:19.924  7646  7646 V ActivityThread: updateVisibility : ActivityRecord{3b1e48bf token=android.os.BinderProxy@1dc86e19 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-05 01:29:19.944   266   266 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,08-05 01:29:19.944   760  1033 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-05 01:29:19.944   760  1033 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-05 01:29:19.954   760  1038 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-05 01:29:19.954   760  1038 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 01:29:19.954   760  1038 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-05 01:29:19.954   760  1038 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-05 01:29:19.954  7646  7699 I OpenGLRenderer: Initialized EGL, version 1.4
,08-05 01:29:19.964  7646  7699 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xb3cc4218 ,&mEglDisplay = 1 , &mEglConfig = 8 
,08-05 01:29:19.974  7646  7699 D OpenGLRenderer: Enabling debug mode 0
,08-05 01:29:20.004   760  1659 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-05 01:29:20.014   760  7706 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-05 01:29:20.024  1727  1727 I SamsungIME: getCurrentCandidateView
,08-05 01:29:20.024   760  1038 W ActivityManager: mDVFSHelper.release()
08-05 01:29:20.024   760  1038 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{221d07cd u0 com.test.thalitest/.MainActivity t99} time:155686
,08-05 01:29:20.034  7646  7646 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-05 01:29:20.034  7646  7646 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1dc86e19 time:155694
,08-05 01:29:20.094  7646  7646 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7646
,08-05 01:29:20.114  1727  1727 D SamsungIME: Dismiss ExpandCandiate
,08-05 01:29:20.184  7646  7646 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-05 01:29:20.224  1727  1727 I SamsungIME: getDebugLevel  : 0x4f4c
,08-05 01:29:20.254  1727  1727 I SamsungIME: getDebugLevel  : 0x4f4c
,08-05 01:29:20.264  1727  1727 I SamsungIME: KeybaordView init() : load resources
,08-05 01:29:20.294  1727  1727 I SamsungIME: getCurrentKeyboard
,08-05 01:29:20.294  1727  1727 I SamsungIME: getTextKeyboard
,08-05 01:29:20.304  1727  1727 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-05 01:29:20.304  7646  7708 D jxcore_app_log: JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1357162624
,08-05 01:29:20.314  7646  7708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-05 01:29:20.314  7646  7708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-05 01:29:20.314  7646  7708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-05 01:29:20.314  7646  7708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-05 01:29:20.314  7646  7708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-05 01:29:20.314  7646  7708 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2040dfaf added. We now have 1 listener(s)
,08-05 01:29:20.324  7646  7708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:1F:C9:5E
,08-05 01:29:20.324  7646  7708 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,08-05 01:29:20.324  7646  7708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-05 01:29:20.324  7646  7708 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-05 01:29:20.324  7646  7708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-05 01:29:20.324  7646  7708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-05 01:29:20.324  7646  7708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-05 01:29:20.324  7646  7708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:1F:C9:5E
08-05 01:29:20.324  7646  7708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-05 01:29:20.324  7646  7708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-05 01:29:20.324  7646  7708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-05 01:29:20.324  7646  7708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-05 01:29:20.324  7646  7708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-05 01:29:20.324  7646  7708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-05 01:29:20.324  7646  7708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-05 01:29:20.324  7646  7708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-05 01:29:20.324  7646  7708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-05 01:29:20.324  7646  7708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-05 01:29:20.324  7646  7708 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1199d29a added. We now have 1 listener(s)
08-05 01:29:20.324  7646  7708 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 01:29:20.334  7646  7708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 01:29:20.334  7646  7708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-05 01:29:20.334  7646  7708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-05 01:29:20.334  7646  7708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-05 01:29:20.334  7646  7708 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-05 01:29:20.344  7646  7708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 01:29:20.344  7646  7708 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:1F:C9:5E
,08-05 01:29:20.344   760  1536 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 01:29:20.354  7646  7708 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-05 01:29:20.354  7646  7708 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 01:29:20.354  7646  7708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 01:29:20.354  7646  7708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 01:29:20.354  7646  7708 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 01:29:20.354  7646  7708 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 01:29:20.354  7646  7708 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 01:29:20.354  7646  7708 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 01:29:20.354  7646  7708 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 01:29:20.354  7646  7708 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-05 01:29:20.354  7646  7708 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-05 01:29:20.354   760  1357 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 01:29:20.354  7646  7708 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-05 01:29:20.354  7646  7646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 01:29:20.354   760   774 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 01:29:20.354  7646  7646 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 01:29:20.384  7646  7646 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-05 01:29:20.684  1727  7711 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-05 01:29:21.334  7646  7721 W jxcore-log: Initializing JXcore engine
08-05 01:29:21.334  7646  7721 W jxcore-log: JXcore engine is ready
,08-05 01:29:21.384  1805  1805 E auditd  : In denial and Property audit_ondenial is set to 1 
08-05 01:29:21.384  1805  1805 E audit   : type=1400 msg=audit(1470353361.384:203): avc:  denied  { ioctl } for  pid=7721 comm="Thread-1238" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-05 01:29:21.384  1805  1805 E audit   :  SEPF_SM-N9005_5.0-1_0032
08-05 01:29:21.384  1805  1805 E audit   : 
08-05 01:29:21.384   760  1024 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
08-05 01:29:21.384   760  1024 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
08-05 01:29:21.384   760   941 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-05 01:29:21.384   760   941 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 01:29:21.384   760   941 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 01:29:21.384   760   941 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 01:29:21.384   760   941 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 01:29:21.384   760  1024 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,08-05 01:29:21.384  1805  1805 E audit   : type=1300 msg=audit(1470353361.384:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=99cfb8d8 items=0 ppid=346 ppcomm=main pid=7721 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1238" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
,08-05 01:29:21.384  1805  1805 E audit   : type=1320 msg=audit(1470353361.384:203): 
,08-05 01:29:21.404  7646  7721 W jxcore-log: Starting JXcore engine
,08-05 01:29:21.444   760   941 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7734 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-05 01:29:21.444  7734  7734 E Zygote  : MountEmulatedStorage()
,08-05 01:29:21.444  7734  7734 E Zygote  : v2
08-05 01:29:21.444  7734  7734 I libpersona: KNOX_SDCARD checking this for 1000
08-05 01:29:21.444  7734  7734 I libpersona: KNOX_SDCARD not a persona
,08-05 01:29:21.474  7734  7734 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 01:29:21.474  7734  7734 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-05 01:29:21.474  7734  7734 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-05 01:29:21.494  7734  7734 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 01:29:21.494  7734  7734 D ActivityThread: Added TimaKeyStore provider
,08-05 01:29:21.504  7646  7721 W jxcore-log: Platform android
08-05 01:29:21.504  7646  7721 W jxcore-log: 
,08-05 01:29:21.504  7646  7721 W jxcore-log: Process ARCH arm
08-05 01:29:21.504  7646  7721 W jxcore-log: 
,08-05 01:29:21.514  7734  7734 D ResourcesManager: creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,08-05 01:29:21.524  7734  7734 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,08-05 01:29:21.524  7734  7734 D SecurityLogAgent:  SeDenialReceiver : File path = null
,08-05 01:29:21.524   760  1244 I ActivityManager: Killing 5325:com.google.android.music:main/u0a144 (adj 15): emptyCount ##41
,08-05 01:29:21.604   303   303 E SMD     : DCD ON
,08-05 01:29:21.654   760  3332 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-05 01:29:21.754  7646  7721 I jxcore-log: JXcore Cordova bridge is ready!
08-05 01:29:21.754  7646  7721 I jxcore-log: 
,08-05 01:29:21.754  7646  7721 W jxcore-log: JXcore engine is started
,08-05 01:29:21.764  7646  7708 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-05 01:29:21.764  7646  7646 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-05 01:29:24.604   303   303 E SMD     : DCD ON
,08-05 01:29:24.824   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 01:29:25.144   760  3300 D SSRM:n  : SIOP:: AP = 360, PST = 353, CUR = 450
,08-05 01:29:25.184   760   775 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-05 01:29:25.184   760   775 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4332, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
08-05 01:29:25.184   760   775 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
08-05 01:29:25.184   760   775 D BatteryService: stay LED for fully charged
08-05 01:29:25.184   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-05 01:29:25.184   760   760 I MotionRecognitionService: Plugged
08-05 01:29:25.184   760   760 I MotionRecognitionService: setPowerConnected  = true
,08-05 01:29:25.184  3219  3219 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,08-05 01:29:25.184  3219  3292 D HeadsetStateMachine: Disconnected process message: 10
,08-05 01:29:25.184  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-05 01:29:25.184  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,08-05 01:29:25.184  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-05 01:29:25.184  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-05 01:29:25.184  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-05 01:29:25.184  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-05 01:29:25.824   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 01:29:26.824   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 01:29:27.604   303   303 E SMD     : DCD ON
,08-05 01:29:27.824   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 01:29:28.824   357   357 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 01:29:29.164   760  1063 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-05 01:29:29.824   357   357 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-05 01:29:30.604   303   303 E SMD     : DCD ON
,08-05 01:29:33.304   760  1332 E Watchdog: !@Sync 5
,08-05 01:29:33.604   303   303 E SMD     : DCD ON
,08-05 01:29:34.874  7646  7721 E jxcore  : Error!: Cannot find module '../thalilogger'
08-05 01:29:34.874  7646  7721 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w._oldRes","_lineNumber":"802","_columnNumber":"9","_msg":"    at $w._oldRes@module.js:802:9"},{"_fileName":"module.js","_functionName":"$w._resolveFilename","_lineNumber":"1771","_columnNumber":"1","_msg":"    at $w._resolveFilename@module.js:1771:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"362","_columnNumber":"4","_msg":"    at $w._load@module.js:362:4"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js","_functionName":"","_lineNumber":"5","_columnNumber":"14","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js:5:14"}]
,08-05 01:29:34.884  7646  7646 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "Cannot find module '../thalilogger'\nError: Cannot find module '../thalilogger'\n    at $w._oldRes@module.js:802:9\n    at $w._resolveFilename@module.js:1771:1\n    at $w._load@module.js:362:4\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at @/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js:5:14"", source: file:///android_asset/www/js/thali_main.js (57)
,08-05 01:29:34.884  7646  7646 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,08-05 01:29:34.894   760   774 I ActivityManager: Killing 6720:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 15): emptyCount ##41
08-05 01:29:34.894  7646  7646 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-05 01:29:34.894  7646  7646 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-05 01:29:34.904  7646  7646 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-05 01:29:34.904  7646  7646 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-05 01:29:34.904  7646  7646 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-05 01:29:34.904  7646  7646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-05 01:29:34.904  7646  7646 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2040dfaf removed from the list
08-05 01:29:34.904  7646  7646 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-05 01:29:34.904  7646  7646 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1199d29a removed from the list
08-05 01:29:34.904  7646  7646 D io.jxcore.node.ConnectivityMonitor: stop
08-05 01:29:34.904  7646  7646 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-05 01:29:34.904   760  3300 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 01:29:34.904  7646  7646 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-05 01:29:34.944   266  1429 I SurfaceFlinger: id=12 Removed NainActivit (6/8)
,08-05 01:29:34.944   266  1448 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,08-05 01:29:34.944   760  1038 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-05 01:29:34.944   760  1038 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 01:29:34.944   760  1038 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-05 01:29:34.944   760  1038 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-05 01:29:34.954  7646  7646 E ViewRootImpl: sendUserActionEvent() mView == null
,08-05 01:29:35.134  7782  7782 D AndroidRuntime: 
08-05 01:29:35.134  7782  7782 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-05 01:29:35.134  7782  7782 D AndroidRuntime: CheckJNI is OFF
,08-05 01:29:35.134  7782  7782 D AndroidRuntime: readGMSProperty: start
08-05 01:29:35.134  7782  7782 D AndroidRuntime: readGMSProperty: already setted!!
08-05 01:29:35.134  7782  7782 D AndroidRuntime: readGMSProperty: end
08-05 01:29:35.134  7782  7782 D AndroidRuntime: addProductProperty: start
,08-05 01:29:35.184   760  3300 D SSRM:n  : SIOP:: AP = 380, PST = 356, CUR = 450
,08-05 01:29:35.234   760  1709 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-05 01:29:35.234   760  1709 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4326, temperature: 285, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
08-05 01:29:35.234   760  1709 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
08-05 01:29:35.234   760  1709 D BatteryService: stay LED for fully charged
08-05 01:29:35.234   760   760 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-05 01:29:35.244  3219  3219 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-05 01:29:35.244  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-05 01:29:35.244  3219  3292 D HeadsetStateMachine: Disconnected process message: 10
08-05 01:29:35.244  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
08-05 01:29:35.244  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
08-05 01:29:35.244  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-05 01:29:35.244  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-05 01:29:35.244  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-05 01:29:35.244   760   760 I MotionRecognitionService: Plugged
08-05 01:29:35.244   760   760 I MotionRecognitionService: setPowerConnected  = true
,08-05 01:29:35.354  7782  7782 E AffinityControl: AffinityControl: registerfunction enter
,08-05 01:29:35.374  7782  7782 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm,
,08-05 01:29:35.384   760   775 D PackageManager: START PACKAGE DELETE: observer{722016302}
08-05 01:29:35.384   760   775 D PackageManager: pkg{<packageName>}
08-05 01:29:35.384   760   775 D PackageManager: user{0}
08-05 01:29:35.384   760   775 D PackageManager: caller{2000}
08-05 01:29:35.384   760   775 D PackageManager: flags{2}
08-05 01:29:35.384   760   775 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-05 01:29:35.384   760   775 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-05 01:29:35.384   760   775 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-05 01:29:35.384   760   775 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-05 01:29:35.394   760   775 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-05 01:29:35.394   760  1063 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,08-05 01:29:35.394   760  1063 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-05 01:29:35.394   760  1063 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-05 01:29:35.394   760  1063 D ApplicationPolicy: getApplicationUninstallationEnabled
,08-05 01:29:35.394   760  1063 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-05 01:29:35.394   760  1063 D PackageManager: !@killApplicatoin: 10079, uninstall pkg
,08-05 01:29:35.404   760   941 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
,08-05 01:29:35.404   760   941 I ActivityManager: Killing 7646:com.test.thalitest/u0a79 (adj 9): stop com.test.thalitest cause uninstall pkg
,08-05 01:29:35.414   760   941 D FocusedStackFrame: Set to : 0
,08-05 01:29:35.534   760  1063 W PackageSettings: Skipping PackageSetting{3d5db291 com.example.hello/10078} due to missing metadata
,08-05 01:29:35.564  1888  3179 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-05 01:29:35.564   760  1063 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=0: pkg removed
,08-05 01:29:35.624   760  3117 E libprocessgroup: failed to kill 1 processes for processgroup 7646
,08-05 01:29:35.624  3865  3865 I art     : Explicit concurrent mark sweep GC freed 5386(298KB) AllocSpace objects, 1(16KB) LOS objects, 39% free, 15MB/26MB, paused 484us total 26.101ms
,08-05 01:29:35.634  1585  1585 I art     : Explicit concurrent mark sweep GC freed 1848(80KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 20MB/33MB, paused 807us total 65.001ms
,08-05 01:29:35.644  6742  6742 I art     : Explicit concurrent mark sweep GC freed 635(36KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 358us total 58.542ms
,08-05 01:29:35.644  7217  7217 I art     : Explicit concurrent mark sweep GC freed 9312(432KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 351us total 54.862ms
,08-05 01:29:35.654  4685  4685 I art     : Explicit concurrent mark sweep GC freed 1953(75KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 24MB/32MB, paused 866us total 71.116ms
,08-05 01:29:35.654   760  1038 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,08-05 01:29:35.654   760   927 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,08-05 01:29:35.664  1727  1727 E SamsungIME: mOCRHelper is null
,08-05 01:29:35.664   760  1120 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-05 01:29:35.664  1430  1430 D ResourcesManager: creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
,08-05 01:29:35.664  1888  2323 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-05 01:29:35.664  1430  1430 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-05 01:29:35.664  1430  1430 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-05 01:29:35.664   760   927 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,08-05 01:29:35.664  1430  1430 D ResourcesManager: creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
,08-05 01:29:35.664  1413  1413 D RegisteredServicesCache: empty dynamic service
,08-05 01:29:35.674   760  1144 V NetworkStats: removeUidsLocked() for UIDs [10079]
08-05 01:29:35.674   760  1144 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 01:29:35.674   760  1144 V NetworkStats: performPollLocked(flags=0x3)
,08-05 01:29:35.674   760  1144 D NetworkStatsFactory: UpdateStatsForKnox
,08-05 01:29:35.674   760  1144 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 01:29:35.674  2504  2504 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-05 01:29:35.674   760  1144 V NetworkStats: performPollLocked() took 5ms
,08-05 01:29:35.674   760  1144 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 01:29:35.674  2504  2504 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1470353375685
,08-05 01:29:35.674   760  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 01:29:35.674   760  1145 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 01:29:35.674  2504  2504 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
,08-05 01:29:35.674  1430  1430 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-05 01:29:35.684  1430  1430 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-05 01:29:35.684  1430  1430 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-05 01:29:35.684  1430  1430 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,08-05 01:29:35.684  1430  1430 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-05 01:29:35.684  1430  1430 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-05 01:29:35.694  2504  2504 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,08-05 01:29:35.714   760   927 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,08-05 01:29:35.724   760   760 I art     : Explicit concurrent mark sweep GC freed 53192(3MB) AllocSpace objects, 29(464KB) LOS objects, 29% free, 38MB/54MB, paused 2.547ms total 150.056ms
,08-05 01:29:35.724   760   760 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
08-05 01:29:35.724   760  1063 I art     : WaitForGcToComplete blocked for 48.240ms for cause Explicit
,08-05 01:29:35.764   760   760 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,08-05 01:29:35.784   760   760 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,08-05 01:29:35.794   760   760 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,08-05 01:29:35.794   760  1445 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
08-05 01:29:35.794   760  1445 D SecContentProvider2: mCursor = null
,08-05 01:29:35.794   760   760 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,08-05 01:29:35.804   760   760 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,08-05 01:29:35.814   760   760 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,08-05 01:29:35.814   760   760 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,08-05 01:29:35.814   760   760 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
08-05 01:29:35.814   760   927 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
,08-05 01:29:35.824   760   760 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,08-05 01:29:35.824  2504  2504 I KLMS-2.4.511: : MainReciver(): Notification App List is Null. Remove Notification.
,08-05 01:29:35.834   760   760 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,08-05 01:29:35.834   760   760 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,08-05 01:29:35.834   760   927 D EnterpriseDeviceManagerService: Package has changed for user 0
,08-05 01:29:35.834   760   927 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-05 01:29:35.834  2504  2504 I KLMS-2.4.511: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-05 01:29:35.844   760   760 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,08-05 01:29:35.854   760  1142 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-05 01:29:35.854   760   760 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,08-05 01:29:35.854   760  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 01:29:35.854   760  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 01:29:35.854   760  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 01:29:35.854   760  1142 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 01:29:35.854   760   760 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,08-05 01:29:35.854   760   760 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,08-05 01:29:35.854   760   927 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,08-05 01:29:35.854   760   760 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
,08-05 01:29:35.864   760   760 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,08-05 01:29:35.874   760   927 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 01:29:35.874   760   760 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,08-05 01:29:35.884   760   760 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
08-05 01:29:35.894  7805  7805 I libpersona: KNOX_SDCARD checking this for 10116
08-05 01:29:35.894  7805  7805 E Zygote  : MountEmulatedStorage()
08-05 01:29:35.894  7805  7805 I libpersona: KNOX_SDCARD not a persona
08-05 01:29:35.894  7805  7805 E Zygote  : v2
,08-05 01:29:35.894   760   927 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,08-05 01:29:35.894   760   760 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,08-05 01:29:35.904  7805  7805 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,08-05 01:29:35.904  7805  7805 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-05 01:29:35.904   760  1142 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7805 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,08-05 01:29:35.904  7805  7805 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-05 01:29:35.904   760   760 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,08-05 01:29:35.904   760   760 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,08-05 01:29:35.914   760   760 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,08-05 01:29:35.924   760   760 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,08-05 01:29:35.924  7805  7805 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 01:29:35.934   760   927 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 01:29:35.934   760   927 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,08-05 01:29:35.934   760   760 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
08-05 01:29:35.934  7805  7805 D ActivityThread: Added TimaKeyStore provider
08-05 01:29:35.934   760   760 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
,08-05 01:29:35.944   760   760 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,08-05 01:29:35.954   760   927 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,08-05 01:29:35.954  7805  7805 D ResourcesManager: creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,08-05 01:29:35.954  1430  1430 D SurfaceWidgetView: destroyHardwareResources():1002998330
,08-05 01:29:35.954   760  1536 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-05 01:29:35.954   760  1536 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
08-05 01:29:35.954   760  1536 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-05 01:29:35.954   760  1536 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-05 01:29:35.954   760  1536 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,08-05 01:29:35.964  1430  1430 D Launcher: onRestart, Launcher: 659305520
,08-05 01:29:35.964  1430  1430 D Launcher: onStart, Launcher: 659305520
08-05 01:29:35.964  1430  1430 D Launcher.HomeView: onStart
08-05 01:29:35.964  1430  1430 V ActivityThread: updateVisibility : ActivityRecord{265a8444 token=android.os.BinderProxy@32d5d37a {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,08-05 01:29:35.964  1757  1777 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
08-05 01:29:35.964   760   927 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-05 01:29:35.964  1757  2048 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
,08-05 01:29:35.964   760   927 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
08-05 01:29:35.964  1757  2048 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,08-05 01:29:35.964   760   760 D RCPManagerService: PackageReceiver onReceive()
,08-05 01:29:35.964   760   760 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-05 01:29:35.964   760   760 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,08-05 01:29:35.964   760   927 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 01:29:35.964   760   927 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
08-05 01:29:35.974   760   760 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-05 01:29:35.974   760   760 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-05 01:29:35.974   760   760 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-05 01:29:35.974   760   760 V EnterpriseBillingPolicy: uID is 10079
08-05 01:29:35.974   760   760 V EnterpriseBillingPolicy: Removed Packageuid is0
08-05 01:29:35.974   760   760 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-05 01:29:35.974   760   760 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
,08-05 01:29:35.974   760   760 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-05 01:29:35.974   760   760 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-05 01:29:35.974   760   760 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-05 01:29:35.974   760   760 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-05 01:29:35.974   760  3300 D SSRM:aY : MSG_TYPE_APP_REMOVED::
08-05 01:29:35.974   760  1176 D TaskPersister: removeObsoleteFile: deleting file=99_task.xml
,08-05 01:29:35.974   266   266 I SurfaceFlinger: id=13 createSurf (1080x1920),1 flag=4, Mauncher
,08-05 01:29:35.974   760   760 V AlarmManagerEXT: com.test.thalitest(10079) is removed.
,08-05 01:29:35.984   760  1033 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-05 01:29:35.984   760  1033 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-05 01:29:35.984   760  1063 I art     : Explicit concurrent mark sweep GC freed 19833(1632KB) AllocSpace objects, 0(0B) LOS objects, 29% free, 37MB/53MB, paused 3.204ms total 254.878ms
08-05 01:29:35.984  7805  7805 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-05 01:29:35.984   760  1038 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-05 01:29:35.984   760  1038 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 01:29:35.984   760  1038 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-05 01:29:35.984   760  1038 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-05 01:29:35.984  7805  7805 D elm:14491: ELMEngine.ELMEngine( context ).
,08-05 01:29:35.994  7805  7805 D elm:14491: MDMBridge.setEnterpriseBridge()
,08-05 01:29:35.994   760  3654 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-05 01:29:35.994   760  3654 D ActivityManager: caller:android.app.ApplicationThreadProxy@e594f49, r.packageName :com.sec.esdk.elm
,08-05 01:29:35.994   760  1536 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-05 01:29:35.994   760  1536 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 7646 uid 10079
,08-05 01:29:35.994  7805  7805 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-05 01:29:36.004  3808  3808 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,08-05 01:29:36.004  3808  3808 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-05 01:29:36.004  3808  3808 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
08-05 01:29:36.004  3808  3808 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
08-05 01:29:36.004  3808  3808 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
08-05 01:29:36.004  3808  3808 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
08-05 01:29:36.004  3808  3808 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
08-05 01:29:36.004  3808  3808 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 01:29:36.004  3808  3808 W System.err: 	at android.os.Looper.loop(Looper.java:145)
,08-05 01:29:36.004  3808  3808 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-05 01:29:36.004  3808  3808 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 01:29:36.004  3808  3808 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 01:29:36.004  3808  3808 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-05 01:29:36.004  3808  3808 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,08-05 01:29:36.004   760  7822 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-05 01:29:36.004  7805  7805 D elm:14491: ElmAgentService : onCreate()
,08-05 01:29:36.014  7805  7824 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-05 01:29:36.014  7805  7824 D elm:14491: MainReceiver.listeningToPackageRemoved()
08-05 01:29:36.014  7805  7824 D elm:14491: MDMBridge.getInstance()
,08-05 01:29:36.014  7805  7824 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,08-05 01:29:36.014  7805  7824 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,08-05 01:29:36.024  6098  6098 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
,08-05 01:29:36.024  6098  6098 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
08-05 01:29:36.024  6098  6098 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
,08-05 01:29:36.024   760   927 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 01:29:36.024   760   927 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 01:29:36.024   760   927 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,08-05 01:29:36.034  7805  7805 D elm:14491: ElmAgentService : onDestroy().
,08-05 01:29:36.034  6974  6974 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-05 01:29:36.034  6974  6974 I PCWCLIENTTRACE_PushUtil: sales region : global
08-05 01:29:36.034  6974  6974 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-05 01:29:36.034  6974  6974 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-05 01:29:36.054   760   774 D ActivityManager: startService callerProcessName:com.sec.android.app.shealth, calleePkgName: com.sec.android.app.shealth
,08-05 01:29:36.054   760   774 D ActivityManager: caller:android.app.ApplicationThreadProxy@19d2fb26, r.packageName :com.sec.android.app.shealth
,08-05 01:29:36.054   760  1038 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1d198191 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t97} time:171715
,08-05 01:29:36.054   760   927 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 01:29:36.054   760   927 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,08-05 01:29:36.064   760   927 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,08-05 01:29:36.064   760  3207 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-05 01:29:36.064   760  3207 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 01:29:36.064   760  3207 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 01:29:36.074   760  3207 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 01:29:36.074   760  3207 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 01:29:36.074   760   927 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,08-05 01:29:36.084   760   927 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,08-05 01:29:36.084   760   927 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 01:29:36.084   760   927 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,08-05 01:29:36.084   760   927 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,08-05 01:29:36.094   760   927 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,08-05 01:29:36.094   760   927 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 01:29:36.094   760   927 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 01:29:36.094   760   927 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,08-05 01:29:36.094   760   927 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-05 01:29:36.094   760   927 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 01:29:36.104   760   927 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-05 01:29:36.104   760   927 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 01:29:36.104   760   927 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,08-05 01:29:36.104   760  1063 D PackageManager: delete codoeFile: 
,08-05 01:29:36.104   760  1063 D AASAuninstall: userId = 0, info.removedAppID = 10079, info.uid = 10079, packageName = com.test.thalitest
,08-05 01:29:36.104   760  1063 I AASA_removePackage: UID=10079 Target=com.test.thalitest
,08-05 01:29:36.104   760  1063 D PackageManager: result of delete: 1{722016302}
,08-05 01:29:36.114   760   927 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
08-05 01:29:36.114  7827  7827 E Zygote  : MountEmulatedStorage()
08-05 01:29:36.114  7827  7827 I libpersona: KNOX_SDCARD checking this for 10043
08-05 01:29:36.114  7827  7827 E Zygote  : v2
08-05 01:29:36.114  7827  7827 I libpersona: KNOX_SDCARD not a persona
,08-05 01:29:36.114   760   927 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,08-05 01:29:36.114  7782  7782 D AndroidRuntime: Shutting down VM
,08-05 01:29:36.114   760   927 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 01:29:36.114   760   927 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,08-05 01:29:36.114   760  3207 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7827 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-05 01:29:36.124   760   927 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-05 01:29:36.124   760   927 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,08-05 01:29:36.124   760   927 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 01:29:36.124   760   927 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-05 01:29:36.124   760   927 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,08-05 01:29:36.124   760   927 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 01:29:36.124   760   927 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,08-05 01:29:36.134   760   927 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 01:29:36.134   760   927 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-05 01:29:36.134   760   927 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,08-05 01:29:36.134   760   927 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 01:29:36.134   760   927 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-05 01:29:36.134   760   927 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,08-05 01:29:36.134   760   927 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 01:29:36.134   760   927 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-05 01:29:36.134   760   927 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-05 01:29:36.144  7827  7827 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 01:29:36.144  7827  7827 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-05 01:29:36.144  7827  7827 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-05 01:29:36.144   760  1063 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-05 01:29:36.144   760  1063 D PackageManager: userId{-1}
08-05 01:29:36.144   760  1063 D PackageManager: andCode{true}
,08-05 01:29:36.144   760  1063 D ActivityManager: caller:null, r.packageName :com.android.defcontainer
,08-05 01:29:36.164  7827  7827 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 01:29:36.164  7827  7827 D ActivityThread: Added TimaKeyStore provider
,08-05 01:29:36.184  7827  7827 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,08-05 01:29:36.204  7827  7827 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-05 01:29:36.204  7827  7827 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-05 01:29:36.214  7827  7827 D SPPClientService: PushLog.txt file is not deleted.
08-05 01:29:36.214  7827  7827 D SPPClientService: PushLog.txt file is not deleted.
08-05 01:29:36.214  7827  7827 D SPPClientService: ============PushLog. stop!
,08-05 01:29:36.214   760  1377 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,08-05 01:29:36.214   760  1377 D ActivityManager: caller:android.app.ApplicationThreadProxy@3b7c2629, r.packageName :com.samsung.android.app.galaxyfinder
,08-05 01:29:36.234  7060  7060 I SA      : [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,08-05 01:29:36.244  7060  7060 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10079 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,08-05 01:29:36.244   760  1536 I ActivityManager: Killing 6787:com.google.android.gms:car/u0a15 (adj 15): emptyCount ##41
,08-05 01:29:36.244   760   775 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
,08-05 01:29:36.244   760   775 D ActivityManager: caller:android.app.ApplicationThreadProxy@1432edae, r.packageName :com.android.providers.contacts
,08-05 01:29:36.344  7083  7083 D Mms/FreeMessageReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,08-05 01:29:36.344   760  1536 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
,08-05 01:29:36.344   760  1536 D ActivityManager: caller:android.app.ApplicationThreadProxy@3d63edc, r.packageName :com.android.mms
,08-05 01:29:36.354   760  1659 I TactileAssist: enable value -1
08-05 01:29:36.354   760  1659 I TactileAssist: internal enable value -1
08-05 01:29:36.354   760  1659 I TactileAssist: intensity value -1
08-05 01:29:36.354   760  1659 I TactileAssist: saveAppList value true
,08-05 01:29:36.354  7083  7845 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
,08-05 01:29:36.354  7083  7845 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
08-05 01:29:36.354   760  1659 I TactileAssist: List of disabled apps :
,08-05 01:29:36.354   760  1709 D SettingsProvider: name = reading_mode_app_list
,08-05 01:29:36.364  7123  7123 D Compatibility: onReceive() it will make start service
,08-05 01:29:36.364   760   775 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
,08-05 01:29:36.364   760   775 D ActivityManager: caller:android.app.ApplicationThreadProxy@7c436ba, r.packageName :com.sec.android.app.soundalive
,08-05 01:29:36.364   760  1326 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
,08-05 01:29:36.374   760  1326 D ActivityManager: caller:android.app.ApplicationThreadProxy@21f66cc8, r.packageName :com.google.android.googlequicksearchbox
,08-05 01:29:36.374  7123  7846 D Compatibility: onHandleIntent()
,08-05 01:29:36.374  7123  7846 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10079, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
08-05 01:29:36.374  7123  7846 D Compatibility: found: 2
08-05 01:29:36.374  7123  7846 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
08-05 01:29:36.374  7123  7846 D Compatibility: skipping ResolveInfo{8204d73 com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-05 01:29:36.374  7123  7846 D Compatibility: considering ResolveInfo{274c3430 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-05 01:29:36.374  7123  7846 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-05 01:29:36.374  7123  7846 D Compatibility: enabling receiver ResolveInfo{7908a9 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-05 01:29:36.374  1585  7847 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-05 01:29:36.384  7123  7846 D Compatibility: enabling receiver ResolveInfo{2fe25e2e com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-05 01:29:36.384  7123  7846 D Compatibility: enabling receiver ResolveInfo{21a84dcf com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-05 01:29:36.384  7123  7846 D Compatibility: enabling receiver ResolveInfo{1978635c com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-05 01:29:36.394  7123  7846 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,08-05 01:29:36.404  6742  6742 I art     : Explicit concurrent mark sweep GC freed 122(6KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 336us total 11.905ms
,08-05 01:29:36.424  5879  5879 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.assistantmenu.AssistantMenuReceiver.onReceive:159 android.app.ActivityThread.handleReceiver:2989 
,08-05 01:29:36.424   760  1709 D ActivityManager: startService callerProcessName:com.samsung.android.app.assistantmenu, calleePkgName: com.samsung.android.app.assistantmenu
08-05 01:29:36.424   760  1709 D ActivityManager: caller:android.app.ApplicationThreadProxy@25ef0486, r.packageName :com.samsung.android.app.assistantmenu
,08-05 01:29:36.434  7430  7430 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
08-05 01:29:36.434   760   775 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-05 01:29:36.434   760   775 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-05 01:29:36.454   760   775 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-05 01:29:36.454   760   775 D ActivityManager: caller:android.app.ApplicationThreadProxy@2b2a5ae3, r.packageName :com.google.android.gms
,08-05 01:29:36.464  6742  7848 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-05 01:29:36.464   760  1142 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-05 01:29:36.464   760  1142 D ActivityManager: caller:android.app.ApplicationThreadProxy@c8deb99, r.packageName :com.google.android.gms
,08-05 01:29:36.464  7217  7217 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2989 
,08-05 01:29:36.474   760  1377 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
,08-05 01:29:36.474   760  1377 D ActivityManager: caller:android.app.ApplicationThreadProxy@229dc23f, r.packageName :com.samsung.android.app.filterinstaller
,08-05 01:29:36.474   760  1473 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-05 01:29:36.474   760  1473 D ActivityManager: caller:android.app.ApplicationThreadProxy@1748a855, r.packageName :com.google.android.gms
,08-05 01:29:36.494   760   775 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.provider.filterprovider
,08-05 01:29:36.494   760   775 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 01:29:36.494   760   775 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 01:29:36.494   760   775 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 01:29:36.494   760   775 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 01:29:36.494  1585  7847 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,08-05 01:29:36.494  1585  7847 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-05 01:29:36.494  7107  7117 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-05 01:29:36.494  7107  7117 E SQLiteLog: (3850) statement aborts at 28: [UPDATE apps SET badgecount=? WHERE package=? AND class=?] disk I/O error
,08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: Exception thrown from onTableChanged
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: java.lang.RuntimeException: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:343)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:261)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.w.j(InternalIcingCorporaProvider.java:661)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.w.a(InternalIcingCorporaProvider.java:652)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.w.g(InternalIcingCorporaProvider.java:590)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:290)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:330)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at android.content.ContentResolver.update(ContentResolver.java:1343)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.z.amO(UpdateIcingCorporaService.java:358)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.ab.amQ(UpdateIcingCorporaService.java:297)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.aF(UpdateIcingCorporaService.java:194)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at android.os.Looper.loop(Looper.java:145)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:661)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.b.amO(AppDataSearchDbOpenHelperBase.java:246)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	at com.google.android.gms.appdatasearch.a.b.call(AppDataSearchDbOpenHelperBase.java:227)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelp,er: 	at com.google.android.gms.appdatasearch.a.a.a(AppDataSearchDbOpenHelperBase.java:341)
08-05 01:29:36.494  1585  7847 E AppDataSearchHelper: 	... 16 more
08-05 01:29:36.494  1585  7847 W AppDataSearchHelper: Table change notification failed for com.google.android.gms.appdatasearch.a.k@be7fd6a1
08-05 01:29:36.494  7107  7117 E DatabaseUtils: Writing exception to parcel
08-05 01:29:36.494  7107  7117 E DatabaseUtils: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 01:29:36.494  7107  7117 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-05 01:29:36.494  7107  7117 E DatabaseUtils: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:904)
08-05 01:29:36.494  7107  7117 E DatabaseUtils: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-05 01:29:36.494  7107  7117 E DatabaseUtils: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-05 01:29:36.494  7107  7117 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.updateWithOnConflict(SQLiteDatabase.java:1700)
08-05 01:29:36.494  7107  7117 E DatabaseUtils: 	at android.database.sqlite.SQLiteDatabase.update(SQLiteDatabase.java:1646)
08-05 01:29:36.494  7107  7117 E DatabaseUtils: 	at com.sec.android.provider.badge.BadgeProvider.update(BadgeProvider.java:152)
08-05 01:29:36.494  7107  7117 E DatabaseUtils: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:330)
08-05 01:29:36.494  7107  7117 E DatabaseUtils: 	at android.content.ContentProviderNative.onTransact(ContentProviderNative.java:222)
08-05 01:29:36.494  7107  7117 E DatabaseUtils: 	at android.os.Binder.execTransact(Binder.java:446)
08-05 01:29:36.494  1585  7847 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 120 ms] updated apps [took 120 ms] 
08-05 01:29:36.534  7854  7854 E Zygote  : MountEmulatedStorage()
08-05 01:29:36.534  7854  7854 E Zygote  : v2
08-05 01:29:36.534  7854  7854 I libpersona: KNOX_SDCARD checking this for 10121
08-05 01:29:36.534  7854  7854 I libpersona: KNOX_SDCARD not a persona
,08-05 01:29:36.534   760   775 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=7854 uid=10121 gids={50121, 9997, 1023} abi=armeabi-v7a
,08-05 01:29:36.544  7854  7854 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 01:29:36.544  7854  7854 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-05 01:29:36.544  7854  7854 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-05 01:29:36.564   760  1120 I EventHub: Removing device '/dev/input/event6' due to inotify event
,08-05 01:29:36.574  4685  7853 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,08-05 01:29:36.574  4685  7853 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-05 01:29:36.584  4685  5316 W FileUtils: Failed to chmod(/data/data/com.google.android.gms/files): android.system.ErrnoException: chmod failed: EROFS (Read-only file system)
,08-05 01:29:36.584  4685  5316 E GAv4-SVC: Error creating clientId file: java.io.FileNotFoundException: /data/data/com.google.android.gms/files/gaClientId: open failed: EROFS (Read-only file system)
,08-05 01:29:36.584   760  1641 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,08-05 01:29:36.584  4685  5140 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml
,08-05 01:29:36.584  4685  5316 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
,08-05 01:29:36.584  4685  5316 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-05 01:29:36.584  4685  5316 E GAv4-SVC: Failed to update Analytics property: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 01:29:36.584  7854  7854 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 01:29:36.584  7854  7854 D ActivityThread: Added TimaKeyStore provider
,08-05 01:29:36.594  4685  5140 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml
,08-05 01:29:36.594   760  1641 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 01:29:36.594   760  1641 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 01:29:36.594   760  1641 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 01:29:36.594   760  1641 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 01:29:36.594  4685  5316 E GAv4-SVC: Job execution failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
,08-05 01:29:36.594  4685  5140 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml
,08-05 01:29:36.604   760  1120 I EventHub: Removing device '/dev/input/event7' due to inotify event
,08-05 01:29:36.604   303   303 E SMD     : DCD ON
,08-05 01:29:36.624  7869  7869 E Zygote  : MountEmulatedStorage()
,08-05 01:29:36.634  7869  7869 E Zygote  : v2
08-05 01:29:36.634  7869  7869 I libpersona: KNOX_SDCARD checking this for 1000
08-05 01:29:36.634  7869  7869 I libpersona: KNOX_SDCARD not a persona
,08-05 01:29:36.634   760  1120 I EventHub: Removing device '/dev/input/event8' due to inotify event
,08-05 01:29:36.644   760  1641 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7869 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-05 01:29:36.654   760  1659 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-05 01:29:36.654   760  1659 D ActivityManager: caller:android.app.ApplicationThreadProxy@2dc79b36, r.packageName :com.google.android.gms
,08-05 01:29:36.654   760  1564 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-05 01:29:36.654   760  1564 D ActivityManager: caller:android.app.ApplicationThreadProxy@8d7c2d3, r.packageName :com.google.android.gms
,08-05 01:29:36.674  7869  7869 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 01:29:36.674  7869  7869 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-05 01:29:36.674  7869  7869 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-05 01:29:36.674   760  3654 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 01:29:36.694  7854  7854 D ResourcesManager: creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
,08-05 01:29:36.694  7854  7854 W ContextImpl: Unable to create files subdir /data/user/0/com.samsung.android.provider.filterprovider/cache
,08-05 01:29:36.704   760  1120 I EventHub: Removing device '/dev/input/event9' due to inotify event
,08-05 01:29:36.704  7854  7854 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,08-05 01:29:36.704  7869  7869 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 01:29:36.714  7869  7869 D ActivityThread: Added TimaKeyStore provider
,08-05 01:29:36.724  7854  7854 D AndroidRuntime: Shutting down VM
,08-05 01:29:36.724  7869  7869 D ResourcesManager: creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
,08-05 01:29:36.734  7854  7854 E AndroidRuntime: FATAL EXCEPTION: main
08-05 01:29:36.734  7854  7854 E AndroidRuntime: Process: com.samsung.android.provider.filterprovider, PID: 7854
08-05 01:29:36.734  7854  7854 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.filterprovider.FilterProvider: java.lang.ClassNotFoundException: Didn't find class "com.samsung.android.provider.filterprovider.FilterProvider" on path: DexPathList[[zip file "/system/app/FilterProvider/FilterProvider.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5558)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5150)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5090)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: Caused by: java.lang.ClassNotFoundException: Didn't find class "com.samsung.android.provider.filterprovider.FilterProvider" on path: DexPathList[[zip file "/system/app/FilterProvider/FilterProvider.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5543)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 	... 11 more
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 	Suppressed: java.io.IOException: Zip archive '/system/app/FilterProvider/FilterProvider.apk' doesn't contain classes.dex (error msg: Entry not found)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFileNative(Native Method)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:80)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:59)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		at dalvik.system.PathC,lassLoader.openArtFile(PathClassLoader.java:76)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Native Method)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Method.java:372)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5082)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		... 9 more
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/app/FilterProvider/FilterProvider.apk'
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		... 27 more
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from /system/app/FilterProvider/arm/FilterProvider.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		... 27 more
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 	Caused by: java.io.IOException: 
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		... 27 more
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 	Suppressed: java.lang.ClassNotFoundException: com.samsung.android.provider.filterprovider.FilterProvider
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		at java.lang.Class.classForName(Native Method)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 		... 13 more
08-05 01:29:36.734  7854  7854 E AndroidRuntime: 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
08-05 01:29:36.734  7869  7869 W ContextImpl: Unable to create files subdir /data/data/com.android.keychain/cache
08-05 01:29:36.734  7869  7869 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
08-05 01:29:36.734   760   774 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.provider.filterprovider
08-05 01:29:36.734   760  7885 E AndroidRuntime: *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
08-05 01:29:36.734   760  7885 E AndroidRuntime: java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
08-05 01:29:36.734   760  7885 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:46)
08-05 01:29:36.734   760  7885 E AndroidRuntime: 	at android.os.StatFs.restat(StatFs.java:56)
08-05 01:29:36.734   760  7885 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
08-05 01:29:36.734   760  7885 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
08-05 01:29:36.734   760  7885 E AndroidRuntime: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-05 01:29:36.734   760  7885 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
08-05 01:29:36.734   760  7885 E AndroidRuntime: Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
08-05 01:29:36.734   760  7885 E AndroidRuntime: 	at libcore.io.Posix.statvfs(Native Method)
08-05 01:29:36.734   760  7885 E AndroidRuntime: 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
08-05 01:29:36.734   760  7885 E AndroidRuntime: 	at android.system.Os.statvfs(Os.java:473)
08-05 01:29:36.734   760  7885 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:44)
08-05 01:29:36.734   760  7885 E AndroidRuntime: 	... 5 more
08-05 01:29:36.734  7854  7854 I Process : Sending signal. PID: 7854 SIG: 9
08-05 01:29:36.764   760  7885 E android.os.Debug: ro.product_ship = true
08-05 01:29:36.764   760  7885 E android.os.Debug: ro.debug_level = 0x4f4c
,08-05 01:29:36.764   760  7885 E AndroidRuntime: Error reporting crash
08-05 01:29:36.764   760  7885 E AndroidRuntime: java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
08-05 01:29:36.764   760  7885 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:46)
08-05 01:29:36.764   760  7885 E AndroidRuntime: 	at android.os.StatFs.restat(StatFs.java:56)
08-05 01:29:36.764   760  7885 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
08-05 01:29:36.764   760  7885 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
08-05 01:29:36.764   760  7885 E AndroidRuntime: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-05 01:29:36.764   760  7885 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
08-05 01:29:36.764   760  7885 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:15161)
08-05 01:29:36.764   760  7885 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:14749)
08-05 01:29:36.764   760  7885 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:14733)
08-05 01:29:36.764   760  7885 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
08-05 01:29:36.764   760  7885 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
08-05 01:29:36.764   760  7885 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
08-05 01:29:36.764   760  7885 E AndroidRuntime: Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
08-05 01:29:36.764   760  7885 E AndroidRuntime: 	at libcore.io.Posix.statvfs(Native Method)
08-05 01:29:36.764   760  7885 E AndroidRuntime: 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
08-05 01:29:36.764   760  7885 E AndroidRuntime: 	at android.system.Os.statvfs(Os.java:473)
08-05 01:29:36.764   760  7885 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:44)
08-05 01:29:36.764   760  7885 E AndroidRuntime: 	... 11 more
08-05 01:29:36.764   760  7885 I Process : Sending signal. PID: 760 SIG: 9
08-05 01:29:36.764  4685  5316 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-05 01:29:36.764  4685  5316 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-05 01:29:36.764  4685  5316 E GAv4-SVC: Sync local dispatch failed: java.lang.IllegalStateException: Cannot perform this operation because there is no current transaction.
08-05 01:29:36.764  4685  5140 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.gms/shared_prefs/com.google.android.gms.analytics.prefs.xml
08-05 01:29:36.764  7869  7869 D AndroidRuntime: Shutting down VM
08-05 01:29:36.774  7869  7869 E AndroidRuntime: FATAL EXCEPTION: main
08-05 01:29:36.774  7869  7869 E AndroidRuntime: Process: com.android.keychain, PID: 7869
08-05 01:29:36.774  7869  7869 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate receiver com.android.keychain.KeyChainBroadcastReceiver: java.lang.ClassNotFoundException: Didn't find class "com.android.keychain.KeyChainBroadcastReceiver" on path: DexPathList[[zip file "/system/app/KeyChain/KeyChain.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2970)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: Caused by: java.lang.ClassNotFoundException: Didn't find class "com.android.keychain.KeyChainBroadcastReceiver" on path: DexPathList[[zip file "/system/app/KeyChain/KeyChain.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2965)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	... 9 more
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	Suppressed: java.io.IOException: Zip archive '/system/app/KeyChain/KeyChain.apk' doesn't contain classes.dex (error msg: Entry not found)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFileNative(Native Method)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:80)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:59)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Native Method)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Method.java:372)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5082)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		... 7 more
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/app/KeyChain/KeyChain.apk'
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		... 27 more
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from /system/app/KeyChain/arm/KeyChain.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		... 27 more
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	Caused by: java.io.IOException: 
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		... 27 more
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	Suppressed: java.lang.ClassNotFoundException: com.android.keychain.KeyChainBroadcastReceiver
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at java.lang.Class.classForName(Native Method)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 		... 11 more
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
08-05 01:29:36.774  7869  7869 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-05 01:29:36.774  7869  7869 E AndroidRuntime: Error reporting crash
08-05 01:29:36.774  7869  7869 E AndroidRuntime: android.os.TransactionTooLargeException
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4706)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
08-05 01:29:36.774  7869  7869 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
08-05 01:29:36.774  7869  7869 I Process : Sending signal. PID: 7869 SIG: 9
,08-05 01:29:36.904   264   264 I ServiceManager: service 'audio' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'DockObserver' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'usb' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'serial' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'uimode' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'jobscheduler' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'network_management' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'ABTPersistenceService' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'textservices' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'network_score' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'netstats' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'netpolicy' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'sec_analytics' died
08-05 01:29:36.904   310  1507 W AudioFlinger: power manager service died !!!
08-05 01:29:36.904   264   264 I ServiceManager: service 'wifip2p' died
08-05 01:29:36.904   310  1507 W AudioCache: clearPowerManager -mWakeLockCount is 0, failed to releaseWakeLock function
08-05 01:29:36.904   264   264 I ServiceManager: service 'connectivity' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'sb_service' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'servicediscovery' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'updatelock' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'notification' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'devicestoragemonitor' died
08-05 01:29:36.904  1757  1772 W Sensors : sensorservice died [0xaf1b6300]
08-05 01:29:36.904   264   264 I ServiceManager: service 'location' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'country_detector' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'search' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'dropbox' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'wallpaper' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'wifi' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'msapwifi' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'wifiscanner' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'rttmanager' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'spengestureservice' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'quickconnect' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'samplingprofiler' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'commontime_management' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'dreams' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'print' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'restrictions' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'media_session' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'media_router' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'trust' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'fingerprint' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'launcherapps' died
08-05 01:29:36.904  1422  1458 W Sensors : sensorservice died [0xaf915180]
08-05 01:29:36.904   264   264 I ServiceManager: service 'voip' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'media_projection' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'lpnet' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'imms' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'entropy' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'context_aware' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'scontext' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'barbeam' died,
08-05 01:29:36.904   264   264 I ServiceManager: service 'multiwindow_facade' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'window' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'input' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'bluetooth_manager' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'tactileassist' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'rcp' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'input_method' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'accessibility' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'motion_recognition' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'mum_container_policy' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'enterprise_billing_policy' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'knox_timakeystore_policy' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'enterprise_policy' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'statusbar' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'clipboard' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'clipboardEx' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'cover' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'mount' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'lock_settings' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'device_policy' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'harmony_eas_service' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'sdp' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'log_manager_service' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'persona_policy' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'SEAMService' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'persona' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'account' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'content' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'DirEncryptService' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'ReactiveService' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'alarm' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'sedenial' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'vibrator' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'tima' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'cepproxyks' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'CustomFrequencyManagerService' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'samsung.smartfaceservice' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'consumer_ir' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'enterprise_license_policy' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'application_policy' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'wifi_policy' died,
08-05 01:29:36.904   264   264 I ServiceManager: service 'phone_restriction_policy' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'remoteinjection' died
,08-05 01:29:36.904   264   264 I ServiceManager: service 'backup' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'appwidget' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'voiceinteraction' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'SecExternalDisplayService' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'diskstats' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'mDNIe' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'telephony.registry' died
,08-05 01:29:36.904  1395  3291 W Sensors : sensorservice died [0xaf152900]
08-05 01:29:36.904   264   264 I ServiceManager: service 'package' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'user' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'cpuinfo' died
08-05 01:29:36.904  1430  1455 W Sensors : sensorservice died [0xafc1e200]
08-05 01:29:36.904   264   264 I ServiceManager: service 'usagestats' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'scheduling_policy' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'dbinfo' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'activity' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'meminfo' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'hardware' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'procstats' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'gfxinfo' died,
,08-05 01:29:36.904   264   264 I ServiceManager: service 'edmnativehelper' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'permission' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'battery' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'webviewupdate' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'mdm.remotedesktop' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'sensorservice' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'batterystats' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'appops' died
08-05 01:29:36.904   264   264 I ServiceManager: service 'power' died
,08-05 01:29:36.914  4685  7853 E ActivityThread: Failed to find provider info for com.google.android.gsf.gservices
08-05 01:29:36.904   264   264 I ServiceManager: service 'display' died
08-05 01:29:36.904  1191  1219 W Sensors : sensorservice died [0xb3a0e240]
08-05 01:29:36.904  1422  1781 E WifiManager: Channel connection lost
08-05 01:29:36.904   266   341 I SurfaceFlinger: restart the boot-animation @ binderDied
08-05 01:29:36.904  1191  1570 E WifiManager: Channel connection lost
08-05 01:29:36.904  1901  1966 W Sensors : sensorservice died [0xaf152a00]
,08-05 01:29:36.904  1888  4997 W Sensors : sensorservice died [0xb3a53380]
08-05 01:29:36.914   266   365 I SurfaceFlinger: id=2 Removed GocusedStac (5/8)
08-05 01:29:36.914   266   365 I SurfaceFlinger: id=3 Removed EimLayer (0/7)
08-05 01:29:36.914   266   365 I SurfaceFlinger: id=4 Removed EimLayer (0/6)
08-05 01:29:36.914   266   365 I SurfaceFlinger: id=5 Removed EimLayer (0/5)
08-05 01:29:36.914   266   365 I SurfaceFlinger: id=6 Removed EimLayer (0/4)
08-05 01:29:36.914   266   365 I SurfaceFlinger: id=2 Removed GocusedStac (-2/4)
,08-05 01:29:36.914   266   365 I SurfaceFlinger: id=3 Removed EimLayer (-2/4)
08-05 01:29:36.914   266   365 I SurfaceFlinger: id=4 Removed EimLayer (-2/4)
08-05 01:29:36.914   266   365 I SurfaceFlinger: id=5 Removed EimLayer (-2/4)
08-05 01:29:36.914   266   365 I SurfaceFlinger: id=6 Removed EimLayer (-2/4)
08-05 01:29:36.914   266   365 I SurfaceFlinger: id=9 Removed TtatusBar (2/3)
08-05 01:29:36.914   266   365 I SurfaceFlinger: id=7 Removed JmageWallpa (0/2)
08-05 01:29:36.914   266   365 I SurfaceFlinger: id=7 Removed JmageWallpa (-2/2)
,08-05 01:29:36.914   266   365 I SurfaceFlinger: id=13 Removed Mauncher (0/1)
08-05 01:29:36.914   266   365 I SurfaceFlinger: id=9 Removed TtatusBar (-2/1)
08-05 01:29:36.914   266   365 I SurfaceFlinger: id=13 Removed Mauncher (-2/1)
08-05 01:29:36.914   266   365 I SurfaceFlinger: id=11 Removed DolorFade (0/0)
08-05 01:29:36.914   266   365 I SurfaceFlinger: id=11 Removed DolorFade (-2/0)
08-05 01:29:36.914   266   266 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6962000
08-05 01:29:36.914   266   266 D qdhwcomposer: hwc_blank: Unblanking display: 0
08-05 01:29:36.914  1888  2322 E WifiManager: Channel connection lost
,08-05 01:29:36.914  4685  7853 I GCore-Chimera-Crash: Cg0KB3ZJbmZyYTQQstg5Gl8KHWNvbS5nb29nbGUuYW5kcm9pZC
08-05 01:29:36.914  4685  7853 I GCore-Chimera-Crash: 5wbGF5LmdhbWVzEhQzLjcuMjQgKDMwNTE3NzQtMDM4KRjm-eAR
08-05 01:29:36.914  4685  7853 I GCore-Chimera-Crash: IiMKHGNvbS5nb29nbGUuYW5kcm9pZC5nbXMuZ2FtZXMQwPngEQ
08-05 01:29:36.914  4685  7853 I GCore-Chimera-Crash: ==
08-05 01:29:36.914  4685  7853 I GCore-Chimera-Crash: GCore-Chimera-Crash
08-05 01:29:36.914  4685  7853 I DeviceDoctorDatabaseHelper: Cleaning stale data from database!
08-05 01:29:36.914  4685  7853 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db" with flag (131138) and mode_t (0) due to error (30)
08-05 01:29:36.914  4685  7853 E SQLiteLog: (28) failed to open "/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db" with flag (131072) and mode_t (0) due to error (2)
08-05 01:29:36.914  4685  7853 E SQLiteLog: (14) cannot open file at line 32509 of [b3bb660af9]
08-05 01:29:36.914  4685  7853 E SQLiteLog: (14) os_unix.c:32509: (2) open(/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db) - 
,08-05 01:29:36.914  4685  7853 E SQLiteDatabase: Failed to open database '/data/data/com.google.android.gms/databases/com.google.android.gms.devicedoctor.db'.
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1496)
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:276)
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: 	at ivm.g(:com.google.android.gms:204)
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: 	at ivm.e(:com.google.android.gms:176)
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: 	at ivh.a(:com.google.android.gms:22519)
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: 	,at iiq.c(:com.google.android.gms:207)
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: 	at ifm.uncaughtException(:com.google.android.gms:2111)
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: 	at ifs.uncaughtException(:com.google.android.gms:54)
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: 	at ifl.uncaughtException(:com.google.android.gms:62)
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: 	at cir.uncaughtException(:com.google.android.gms:112)
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
08-05 01:29:36.914  4685  7853 E SQLiteDatabase: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
08-05 01:29:36.914  4685  7853 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-05 01:29:36.914  4685  7853 E AndroidRuntime: Process: com.google.android.gms, PID: 4685
08-05 01:29:36.914  4685  7853 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 01:29:36.914  4685  7853 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-05 01:29:36.914  4685  7853 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
08-05 01:29:36.914  4685  7853 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-05 01:29:36.914  4685  7853 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-05 01:29:36.914  4685  7853 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
08-05 01:29:36.914  4685  7853 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
08-05 01:29:36.914  4685  7853 E AndroidRuntime: 	at pgd.a(:com.google.android.gms:290)
08-05 01:29:36.914  4685  7853 E AndroidRuntime: 	at pgd.b(:com.google.android.gms:138)
08-05 01:29:36.914  4685  7853 E AndroidRuntime: 	at phk.a(:com.google.android.gms:382)
08-05 01:29:36.914  4685  7853 E AndroidRuntime: 	at com.google.android.gms.icing.proxy.InternalIcingCorporaChimeraProvider.update(:com.google.android.gms:247)
08-05 01:29:36.914  4685  7853 E AndroidRuntime: 	at com.google.android.chimera.container.ContentProviderProxy.update(:com.google.android.gms:462)
08-05 01:29:36.914  4685  7853 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:330)
08-05 01:29:36.914  4685  7853 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1343)
,08-05 01:29:36.914  4685  7853 E AndroidRuntime: 	at pih.call(:com.google.android.gms:1333)
08-05 01:29:36.914  4685  7853 E AndroidRuntime: 	at pii.call(:com.google.android.gms:1266)
08-05 01:29:36.914  4685  7853 E AndroidRuntime: 	at com.google.android.gms.icing.proxy.UpdateIcingCorporaChimeraService.a(:com.google.android.gms:244)
08-05 01:29:36.914  4685  7853 E AndroidRuntime: 	at com.google.android.gms.icing.proxy.UpdateIcingCorporaChimeraService.onHandleIntent(:com.google.android.gms:2177)
08-05 01:29:36.914  4685  7853 E AndroidRuntime: 	at bhe.handleMessage(:com.google.android.gms:65)
08-05 01:29:36.914  4685  7853 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 01:29:36.914  4685  7853 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-05 01:29:36.914  4685  7853 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 01:29:36.924  4685  7853 E AndroidRuntime: Error reporting crash
08-05 01:29:36.924  4685  7853 E AndroidRuntime: android.os.DeadObjectException
08-05 01:29:36.924  4685  7853 E AndroidRuntime: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 01:29:36.924  4685  7853 E AndroidRuntime: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 01:29:36.924  4685  7853 E AndroidRuntime: 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4706)
08-05 01:29:36.924  4685  7853 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
08-05 01:29:36.924  4685  7853 E AndroidRuntime: 	at ifm.uncaughtException(:com.google.android.gms:42)
08-05 01:29:36.924  4685  7853 E AndroidRuntime: 	at ifs.uncaughtException(:com.google.android.gms:54)
08-05 01:29:36.924  4685  7853 E AndroidRuntime: 	at ifl.uncaughtException(:com.google.android.gms:62)
08-05 01:29:36.924  4685  7853 E AndroidRuntime: 	at cir.uncaughtException(:com.google.android.gms:112)
08-05 01:29:36.924  4685  7853 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
08-05 01:29:36.924  4685  7853 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
,08-05 01:29:36.924  7217  7852 E ActivityThread: Failed to find provider info for com.samsung.android.provider.filterprovider
08-05 01:29:36.924  4685  7853 I Process : Sending signal. PID: 4685 SIG: 9
08-05 01:29:36.924  7217  7852 E ActivityThread: Failed to find provider info for com.samsung.android.provider.filterprovider
08-05 01:29:36.924  1317  2981 E WifiManager: Channel connection lost
08-05 01:29:36.924  5125  5187 E WifiManager: Channel connection lost
08-05 01:29:36.924  1585  4037 E WifiManager: Channel connection lost
08-05 01:29:36.924  7217  7852 E AndroidRuntime: FATAL EXCEPTION: FilterPackageServiceHandler
08-05 01:29:36.924  7217  7852 E AndroidRuntime: Process: com.samsung.android.app.filterinstaller, PID: 7217
08-05 01:29:36.924  7217  7852 E AndroidRuntime: java.lang.IllegalArgumentException: Unknown URL content://com.samsung.android.provider.filterprovider/packages/com.test.thalitest
08-05 01:29:36.924  7217  7852 E AndroidRuntime: 	,at android.content.ContentResolver.delete(ContentResolver.java:1305)
08-05 01:29:36.924  7217  7852 E AndroidRuntime: 	at com.samsung.android.app.filterinstaller.FilterUninstaller.removeFromDB(FilterUninstaller.java:52)
08-05 01:29:36.924  7217  7852 E AndroidRuntime: 	at com.samsung.android.app.filterinstaller.FilterUninstaller.uninstallFilters(FilterUninstaller.java:43)
08-05 01:29:36.924  7217  7852 E AndroidRuntime: 	at com.samsung.android.app.filterinstaller.FilterPackageService$ServiceHandler.handleMessage(FilterPackageService.java:149)
08-05 01:29:36.924  7217  7852 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 01:29:36.924  7217  7852 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-05 01:29:36.924  7217  7852 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 01:29:36.924  7217  7852 E AndroidRuntime: Error reporting crash
08-05 01:29:36.924  7217  7852 E AndroidRuntime: android.os.DeadObjectException
08-05 01:29:36.924  7217  7852 E AndroidRuntime: 	at android.os.BinderProxy.transactNative(Native Method)
08-05 01:29:36.924  7217  7852 E AndroidRuntime: 	at android.os.BinderProxy.transact(Binder.java:496)
08-05 01:29:36.924  7217  7852 E AndroidRuntime: 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4706)
08-05 01:29:36.924  7217  7852 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
08-05 01:29:36.924  7217  7852 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
08-05 01:29:36.924  7217  7852 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
,08-05 01:29:36.924  7217  7852 I Process : Sending signal. PID: 7217 SIG: 9
,08-05 01:29:36.934  6742  6742 E SQLiteLog: (284) automatic index on crash_info_summary(package_name_touched)
,08-05 01:29:36.944   313   313 E installd: eof
,08-05 01:29:36.944   313   313 E installd: failed to read size
08-05 01:29:36.944   313   313 I installd: closing connection
,08-05 01:29:36.944  6742  6742 E ActivityThread: Failed to find provider info for com.sec.badge
,08-05 01:29:37.154   266   529 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
08-05 01:29:37.154   266   266 E qdexternal: writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
08-05 01:29:37.154   266   266 D qdhwcomposer: hwc_blank: Done unblanking display: 0
,08-05 01:29:37.154   266   561 E qdhwcomposer: hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Operation not permitted
08-05 01:29:37.154   266   561 E SurfaceFlinger: eventControl(0, 1) failed Operation not permitted
,08-05 01:29:37.324   266   529 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
