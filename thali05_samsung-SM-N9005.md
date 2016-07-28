#### Test 77622416c9749bc_thali05_samsung-SM-N9005 Logs


```
--------- beginning of main
07-28 12:04:58.390   301   301 E SMD     : DCD ON
,07-28 12:04:59.889  7493  7493 D AndroidRuntime: 
07-28 12:04:59.889  7493  7493 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-28 12:04:59.889  7493  7493 D AndroidRuntime: CheckJNI is OFF
07-28 12:04:59.889  7493  7493 D AndroidRuntime: readGMSProperty: start
07-28 12:04:59.889  7493  7493 D AndroidRuntime: readGMSProperty: already setted!!
07-28 12:04:59.889  7493  7493 D AndroidRuntime: readGMSProperty: end
07-28 12:04:59.889  7493  7493 D AndroidRuntime: addProductProperty: start
--------- beginning of system
07-28 12:04:59.989   906  1112 V AlarmManager: waitForAlarm result :8
07-28 12:05:00.019   906  3135 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
07-28 12:05:00.059  7493  7493 E AffinityControl: AffinityControl: registerfunction enter
07-28 12:05:00.079  7493  7493 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-28 12:05:00.089   906   924 E PersonaManagerService: inState():  stateMachine is null !!
07-28 12:05:00.089   906   924 I PersonaManagerService: PersonaId don't exist
07-28 12:05:00.089   906   924 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-28 12:05:00.089   906   924 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-28 12:05:00.089   906   924 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-28 12:05:00.089   906   924 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-28 12:05:00.099   906   924 W ActivityManager: mDVFSHelper.acquire()
07-28 12:05:00.099   906   924 D FocusedStackFrame: Set to : 0
07-28 12:05:00.099   906   924 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:00.099   906   924 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:00.099   906   924 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:00.109   906   924 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:00.159   906   924 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7508 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-28 12:05:00.169   906  1031 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-28 12:05:00.169   906  1031 D PointerIcon: setMouseCustomIcon IconType is same.101
07-28 12:05:00.169   906  1031 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-28 12:05:00.169   906  1031 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-28 12:05:00.169  7508  7508 E Zygote  : MountEmulatedStorage()
07-28 12:05:00.169  7508  7508 E Zygote  : v2
07-28 12:05:00.169  7508  7508 I libpersona: KNOX_SDCARD checking this for 10079
07-28 12:05:00.169  7508  7508 I libpersona: KNOX_SDCARD not a persona
07-28 12:05:00.179  7493  7493 D AndroidRuntime: Shutting down VM
07-28 12:05:00.189  7508  7508 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:05:00.189  7508  7508 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:05:00.199  7508  7508 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-28 12:05:00.199   339   339 I art     : Explicit concurrent mark sweep GC freed 8768(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 4.188ms total 41.919ms
07-28 12:05:00.229   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 486us total 20.365ms
07-28 12:05:00.229  7508  7508 D TimaKeyStoreProvider: TimaSignature is unavailable
07-28 12:05:00.239  7508  7508 D ActivityThread: Added TimaKeyStore provider
07-28 12:05:00.239   906  1413 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-28 12:05:00.239   906  1413 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
07-28 12:05:00.239   906  1413 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-28 12:05:00.239   906  1413 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-28 12:05:00.239   906  1413 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
07-28 12:05:00.239  1444  1444 D SurfaceWidgetView: destroyHardwareResources():174590407
07-28 12:05:00.239   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 391us total 15.732ms
07-28 12:05:00.269   906  3093 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:00.279  7508  7508 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-28 12:05:00.289   906  3093 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:00.299   267  1450 I SurfaceFlinger: id=8 Removed Mauncher (6/8)
07-28 12:05:00.299   267   966 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
07-28 12:05:00.299  1771  1796 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
07-28 12:05:00.299  1444  1444 V ActivityThread: updateVisibility : ActivityRecord{26fd1629 token=android.os.BinderProxy@3df2fb34 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-28 12:05:00.309  1444  1444 D Launcher: onTrimMemory. Level: 20
07-28 12:05:00.389  7508  7508 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
07-28 12:05:00.389  7508  7508 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,07-28 12:05:00.409  7508  7508 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6209-6211)
,07-28 12:05:00.409  7508  7508 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-28 12:05:00.429  7508  7508 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c50e3a9}
,07-28 12:05:00.429  7508  7508 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-28 12:05:00.429  7508  7508 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-28 12:05:00.449  7508  7508 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-28 12:05:00.449  7508  7508 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-28 12:05:00.459  7508  7508 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-28 12:05:00.469  7508  7508 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-28 12:05:00.469  7508  7508 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
07-28 12:05:00.469  7508  7508 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-28 12:05:00.479  7508  7508 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-28 12:05:00.479  7508  7508 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-28 12:05:00.479  7508  7508 I Adreno-EGL: Build Date: 11/19/14 Wed
07-28 12:05:00.479  7508  7508 I Adreno-EGL: Local Branch: mybranch5813579
07-28 12:05:00.479  7508  7508 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-28 12:05:00.479  7508  7508 I Adreno-EGL: Local Patches: NONE
07-28 12:05:00.479  7508  7508 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-28 12:05:00.579  7508  7546 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-28 12:05:00.609  7508  7508 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-28 12:05:00.609  7508  7508 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-28 12:05:00.629  7508  7508 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-28 12:05:00.629  7508  7508 W art     : Attempt to remove local handle scope entry from IRT, ignoring
07-28 12:05:00.629  7508  7508 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-28 12:05:00.679  7508  7508 D Activity: performCreate Call secproduct feature valuefalse
07-28 12:05:00.679  7508  7508 D Activity: performCreate Call debug elastic valuetrue
,07-28 12:05:00.689  7508  7562 D OpenGLRenderer: Render dirty regions requested: true
,07-28 12:05:00.689   906  1361 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-28 12:05:00.689   906  1361 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-28 12:05:00.689   906  1361 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-28 12:05:00.689   906   906 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-28 12:05:00.689   906   906 D PersonaManagerService: getPersonasForUser(): returning null!
,07-28 12:05:00.709   267   267 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,07-28 12:05:00.709   906  1029 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-28 12:05:00.709   906  1029 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-28 12:05:00.719   906  1031 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-28 12:05:00.719   906  1031 D PointerIcon: setMouseCustomIcon IconType is same.101
07-28 12:05:00.719   906  1031 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-28 12:05:00.719   906  1031 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-28 12:05:00.719  7508  7562 I OpenGLRenderer: Initialized EGL, version 1.4
,07-28 12:05:00.729  7508  7562 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xb3de8dd0 ,&mEglDisplay = 1 , &mEglConfig = 8 
,07-28 12:05:00.729  7508  7562 D OpenGLRenderer: Enabling debug mode 0
,07-28 12:05:00.739  7508  7508 V ActivityThread: updateVisibility : ActivityRecord{1c2074db token=android.os.BinderProxy@81c1dd5 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-28 12:05:00.769   906  1413 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-28 12:05:00.779   906  7566 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-28 12:05:00.779  1724  1724 I SamsungIME: getCurrentCandidateView
,07-28 12:05:00.779  7508  7508 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-28 12:05:00.779  7508  7508 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@81c1dd5 time:156587
,07-28 12:05:00.789   906  1031 W ActivityManager: mDVFSHelper.release()
07-28 12:05:00.789   906  1031 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{12c79207 u0 com.test.thalitest/.MainActivity t99} time:156590
,07-28 12:05:00.829  7508  7508 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7508
,07-28 12:05:00.839  1724  1724 D SamsungIME: Dismiss ExpandCandiate
,07-28 12:05:00.899  7508  7508 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-28 12:05:00.919  1724  1724 I SamsungIME: getDebugLevel  : 0x4f4c
,07-28 12:05:00.949  1724  1724 I SamsungIME: getDebugLevel  : 0x4f4c
,07-28 12:05:00.969  1724  1724 I SamsungIME: KeybaordView init() : load resources
,07-28 12:05:00.989  1724  1724 I SamsungIME: getCurrentKeyboard
,07-28 12:05:00.989  1724  1724 I SamsungIME: getTextKeyboard
,07-28 12:05:00.999  1724  1724 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-28 12:05:00.999  7508  7569 D jxcore_app_log: JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1357920640
,07-28 12:05:01.009  7508  7569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-28 12:05:01.009  7508  7569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-28 12:05:01.009  7508  7569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-28 12:05:01.009  7508  7569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-28 12:05:01.009  7508  7569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-28 12:05:01.009  7508  7569 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3ce44acb added. We now have 1 listener(s)
07-28 12:05:01.019  7508  7569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:1F:C9:5E
,07-28 12:05:01.019  7508  7569 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-28 12:05:01.019  7508  7569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:05:01.019  7508  7569 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-28 12:05:01.019  7508  7569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-28 12:05:01.019  7508  7569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-28 12:05:01.019  7508  7569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-28 12:05:01.019  7508  7569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:1F:C9:5E
07-28 12:05:01.019  7508  7569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-28 12:05:01.019  7508  7569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-28 12:05:01.019  7508  7569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-28 12:05:01.019  7508  7569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-28 12:05:01.019  7508  7569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-28 12:05:01.019  7508  7569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-28 12:05:01.019  7508  7569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-28 12:05:01.019  7508  7569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-28 12:05:01.019  7508  7569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-28 12:05:01.019  7508  7569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-28 12:05:01.019  7508  7569 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20791d66 added. We now have 1 listener(s)
,07-28 12:05:01.019  7508  7569 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:05:01.029  7508  7569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:05:01.029  7508  7569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseMode: 1 -> 2
,07-28 12:05:01.029  7508  7569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseTxPowerLevel: 2 -> 3
07-28 12:05:01.029  7508  7569 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setScanMode: 1 -> 2
,07-28 12:05:01.039  7508  7569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:05:01.039  7508  7569 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:1F:C9:5E
,07-28 12:05:01.039   906  1541 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:01.039  7508  7569 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,07-28 12:05:01.049  7508  7569 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:01.049  7508  7569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:01.049  7508  7569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:01.049  7508  7569 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:01.049  7508  7569 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:01.049  7508  7569 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:01.049  7508  7569 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:05:01.049  7508  7569 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:05:01.049  7508  7569 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,07-28 12:05:01.049  7508  7569 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 12:05:01.049  7508  7569 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-28 12:05:01.049   906  1143 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:01.049  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:01.049   906  1435 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:01.049  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:01.069  7508  7508 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-28 12:05:01.319  1724  7571 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-28 12:05:01.379   301   301 E SMD     : DCD ON
,07-28 12:05:01.779  7508  7576 W jxcore-log: Initializing JXcore engine
,07-28 12:05:01.779  7508  7576 W jxcore-log: JXcore engine is ready
,07-28 12:05:01.829  1832  1832 E auditd  : In denial and Property audit_ondenial is set to 1 
,07-28 12:05:01.829  1832  1832 E audit   : type=1400 msg=audit(1469700301.819:203): avc:  denied  { ioctl } for  pid=7576 comm="Thread-1238" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
07-28 12:05:01.829  1832  1832 E audit   :  SEPF_SM-N9005_5.0-1_0032
07-28 12:05:01.829  1832  1832 E audit   : 
07-28 12:05:01.829  1832  1832 E audit   : type=1300 msg=audit(1469700301.819:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=995e08d8 items=0 ppid=339 ppcomm=main pid=7576 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1238" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
07-28 12:05:01.829  1832  1832 E audit   : type=1320 msg=audit(1469700301.819:203): 
,07-28 12:05:01.829   906  1019 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
07-28 12:05:01.829   906  1019 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,07-28 12:05:01.829   906  1019 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,07-28 12:05:01.829  6639  6639 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,07-28 12:05:01.839  6639  6639 D SecurityLogAgent:  SeDenialReceiver : File path = null
,07-28 12:05:01.839  7508  7576 W jxcore-log: Starting JXcore engine
,07-28 12:05:01.919  7508  7576 W jxcore-log: Platform android
07-28 12:05:01.919  7508  7576 W jxcore-log: 
,07-28 12:05:01.919  7508  7576 W jxcore-log: Process ARCH arm
07-28 12:05:01.919  7508  7576 W jxcore-log: 
,07-28 12:05:02.089  7508  7576 I jxcore-log: JXcore Cordova bridge is ready!
07-28 12:05:02.089  7508  7576 I jxcore-log: 
,07-28 12:05:02.089  7508  7576 W jxcore-log: JXcore engine is started
,07-28 12:05:02.089  7508  7569 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-28 12:05:02.089  7508  7508 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-28 12:05:03.069   906  3093 D SSRM:n  : SIOP:: AP = 360, PST = 358, CUR = 450
,07-28 12:05:04.379   301   301 E SMD     : DCD ON
,07-28 12:05:04.579   364   364 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:05:04.619   906   924 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-28 12:05:04.619   906   924 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-28 12:05:04.619   906   924 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-28 12:05:04.619   906   924 D BatteryService: stay LED for fully charged
,07-28 12:05:04.629   906   906 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-28 12:05:04.629  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-28 12:05:04.629  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-28 12:05:04.639  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-28 12:05:04.639  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:05:04.639  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:05:04.639  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:05:04.639   906   906 I MotionRecognitionService: Plugged
07-28 12:05:04.639   906   906 I MotionRecognitionService: setPowerConnected  = true
,07-28 12:05:04.639  2996  2996 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-28 12:05:04.639  2996  3092 D HeadsetStateMachine: Disconnected process message: 10
,07-28 12:05:05.579   364   364 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:05:06.579   364   364 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:05:07.379   301   301 E SMD     : DCD ON
,07-28 12:05:07.579   364   364 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:05:08.579   364   364 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:05:09.579   364   364 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,07-28 12:05:10.149   906  1051 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-28 12:05:10.379   301   301 E SMD     : DCD ON
,07-28 12:05:12.179  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-28 12:05:12.179  7508  7576 I jxcore-log: 
,07-28 12:05:12.179  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-28 12:05:12.179  7508  7576 I jxcore-log: 
,07-28 12:05:12.189   906  1243 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:12.189  7508  7576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:12.189  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:12.189  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:12.189  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:12.189  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:12.189  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:12.189  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:05:12.189  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:05:12.189  7508  7576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:05:12.199  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-28 12:05:12.199  7508  7576 I jxcore-log: 
,07-28 12:05:12.199  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-28 12:05:12.199  7508  7576 I jxcore-log: 
,07-28 12:05:12.549  7508  7576 D ExecuteNativeTests: Running unit tests
,07-28 12:05:12.649  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:05:12.649  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd added. We now have 2 listener(s)
,07-28 12:05:12.649  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-28 12:05:12.649  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:05:12.649  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:05:12.649  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:12.649  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 added. We now have 2 listener(s)
07-28 12:05:12.649  7508  7576 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:05:12.649  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:05:12.649  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:05:12.649   906  1663 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:12.659  7508  7576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:12.659  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:12.659  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:12.659  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:12.659  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:12.659  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:12.659  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:05:12.659  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:05:12.659  7508  7576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:12.659  7508  7576 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:05:12.659   906  1560 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:12.659  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:12.659   906  3355 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:12.659  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:12.659  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-28 12:05:12.669  7508  7576 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:05:12.669  7508  7576 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:05:12.669  7508  7576 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
07-28 12:05:12.669  7508  7576 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-28 12:05:12.669  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 12:05:12.669  7508  7576 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:05:12.669  7508  7576 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:05:12.669  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.669  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.669  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.669  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.669  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.669  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:12.669  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:05:12.669  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd removed from the list
07-28 12:05:12.669  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.669  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 removed from the list
07-28 12:05:12.669  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.669  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.669  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.669  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.679  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.679  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.679  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.679  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.679  7508  7576 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
07-28 12:05:12.679  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.679  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.679  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.679  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.679  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.679  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.679  7508  7576 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd not in the list
07-28 12:05:12.679  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.679  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.679  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.679  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.679  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.679  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.679  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.679  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.679  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.679  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.679  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-28 12:05:12.689  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.689  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.689  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.689  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.689  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.689  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.689  7508  7576 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd not in the list
07-28 12:05:12.689  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.689  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.689  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.689  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.689  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.689  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.689  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.689  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.689  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.689  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.689  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.689  7508  7576 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 12:05:12.699  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:12.699   906  1560 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:12.699  7508  7576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:12.699  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:12.699  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:12.699  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:12.699  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:12.699  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:12.699  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:05:12.699  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:05:12.699  7508  7576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:12.699  7508  7576 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:05:12.699   906  1361 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:12.699  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:05:12.699  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:12.699   906  1462 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:12.699  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:12.699  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:05:12.699  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:12.699  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:05:12.709  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 12:05:12.709  7508  7576 E BluetoothAdapter: bluetooth le advertising not supported
07-28 12:05:12.709  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:05:12.709  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
07-28 12:05:12.709  7508  7576 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
07-28 12:05:12.719  7508  7576 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
07-28 12:05:12.719  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:05:12.719  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:12.719  7508  7576 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:05:12.719  7508  7576 I io.jxcore.node.ConnectionHelper: start: OK
07-28 12:05:12.719  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.719  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.719  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.719  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.719  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.719  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:12.719  7508  7576 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd not in the list
,07-28 12:05:12.719  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.719  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.719  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.719  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.719  7508  7576 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 12:05:12.719  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:12.729   906  1243 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:12.729  7508  7576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:12.729  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:12.729  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:12.729  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:12.729  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:12.729  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:12.729  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:05:12.729  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:05:12.729  7508  7576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:12.729  7508  7576 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:05:12.729   906  3331 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:12.729  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:12.729   906   924 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:12.729  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:12.729  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:05:12.729  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:05:12.729  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:12.729  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:05:12.739  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:05:12.739  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:12.739  7508  7576 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:05:12.739  7508  7576 I io.jxcore.node.ConnectionHelper: start: OK
07-28 12:05:12.739  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.739  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.739  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.739  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.739  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.739  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:12.739  7508  7576 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd not in the list
07-28 12:05:12.739  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.739  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.739  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.739  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.739  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.739  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.739  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.739  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.739  7508  7576 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.739  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.739  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.739  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.739  7508  7576 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 12:05:12.739  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:12.739   906  1435 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:12.749  7508  7576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:12.749  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:12.749  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:12.749  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:12.749  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:12.749  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:12.749  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:05:12.749  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:05:12.749  7508  7576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:12.749  7508  7576 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:05:12.749   906  1243 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:12.749  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:12.749   906  1465 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:12.749  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:12.749  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:05:12.749  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:05:12.749  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:12.749  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:05:12.749  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:05:12.749  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:12.759  7508  7576 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:05:12.759  7508  7576 I io.jxcore.node.ConnectionHelper: start: OK
07-28 12:05:12.759  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.759  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.759  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.759  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.759  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.759  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.759  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.759  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.759  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:12.759  7508  7576 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd not in the list
07-28 12:05:12.759  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.759  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.759  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.759  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.759  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.759  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.759  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.759  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.759  7508  7576 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.759  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.759  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.759  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.759  7508  7576 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-28 12:05:12.759  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.759  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.759  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:05:12.759  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.759  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.759  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.759  7508  7576 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd not in the list
07-28 12:05:12.759  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.759  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.759  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.759  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.759  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.759  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.759  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.759  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.759  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.759  7508  7576 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.759  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.759  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.759  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.769  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-28 12:05:12.769  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.769  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.769  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.769  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.769  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.769  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.769  7508  7576 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd not in the list
07-28 12:05:12.769  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.769  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.769  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.769  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.769  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.769  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.769  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.769  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.769  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.769  7508  7576 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.769  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.769  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.769  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.769  7508  7576 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-28 12:05:12.769  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.769  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.769  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.769  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.769  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.769  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.769  7508  7576 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd not in the list
07-28 12:05:12.769  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.769  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.769  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.769  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.769  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.769  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.769  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.769  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.769  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.769  7508  7576 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.769  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.769  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.769  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.769  7508  7576 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-28 12:05:12.769  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.769  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.769  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.769  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.769  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.769  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.769  7508  7576 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd not in the list
07-28 12:05:12.769  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.769  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.769  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.769  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.769  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.769  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.769  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.779  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.779  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.779  7508  7576 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.779  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.779  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.779  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.779  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-28 12:05:12.779  7508  7576 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:05:12.779  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 12:05:12.779  7508  7576 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:05:12.779  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-28 12:05:12.779  7508  7576 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:05:12.779  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.779  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.779  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.779  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.779  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.779  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.779  7508  7576 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd not in the list
07-28 12:05:12.779  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.779  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.779  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.779  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.779  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.779  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.779  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.779  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.779  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.779  7508  7576 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.779  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.779  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.779  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.779  7508  7576 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:05:12.779  7508  7576 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-28 12:05:12.779  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-28 12:05:12.799  7508  7576 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:05:12.799  7508  7576 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-28 12:05:12.799  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-28 12:05:12.799  7508  7576 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-28 12:05:12.799  7508  7576 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:05:12.799  7508  7576 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-28 12:05:12.799  7508  7576 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:05:12.799  7508  7576 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:05:12.799  7508  7576 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-28 12:05:12.799  7508  7576 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:05:12.799  7508  7576 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:05:12.799  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,07-28 12:05:12.799  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-28 12:05:12.799  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-28 12:05:12.799  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-28 12:05:12.809  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-28 12:05:12.809  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-28 12:05:12.809  7508  7576 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-28 12:05:12.809  7508  7576 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:05:12.809  7508  7576 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-28 12:05:12.809  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.809  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.809  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.809  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.809  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.809  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.809  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-28 12:05:12.809  7508  7576 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd not in the list
07-28 12:05:12.809  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.809  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.809  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.809  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.809  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.809  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.809  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.809  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.809  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.809  7508  7576 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.809  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.809  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.809  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.819  7508  7576 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-28 12:05:12.819  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.819  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.819  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.819  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.819  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.819  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.819  7508  7576 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd not in the list
07-28 12:05:12.819  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.819  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.819  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.819  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.819  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.819  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.819  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.819  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.819  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.819  7508  7576 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.819  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.819  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.819  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.819  7508  7576 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-28 12:05:12.819  7508  7596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1302)
07-28 12:05:12.819  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.829  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.829  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.829  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.829  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.829  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.829  7508  7576 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd not in the list
07-28 12:05:12.829  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.829  7508  7596 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
07-28 12:05:12.829  7508  7596 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:05:12.829  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.829  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.829  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.829  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.829  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.829  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.829  7508  7597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1302
07-28 12:05:12.829  7508  7597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 1302)
07-28 12:05:12.829  7508  7597 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3c8d63bb, channel: -1, state: INIT
07-28 12:05:12.829  7508  7597 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3c8d63bb, channel: -1, mSocketIS: null, mSocketOS: nullmSocket: null
07-28 12:05:12.829  7508  7597 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 1302)
07-28 12:05:12.829  2996  3006 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:05:12.829  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.829  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.829  7508  7576 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.829  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.829  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.829  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.829  7508  7576 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-28 12:05:12.829  7508  7576 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-28 12:05:12.829  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:05:12.829  7508  7576 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-28 12:05:12.829  7508  7576 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-28 12:05:12.829  7508  7576 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-28 12:05:12.829  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:05:12.829  7508  7576 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-28 12:05:12.829  7508  7576 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-28 12:05:12.829  7508  7576 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-28 12:05:12.829  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:05:12.829  7508  7576 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
07-28 12:05:12.829  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.829  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.829  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.829  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.829  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.829  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.829  7508  7576 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd not in the list
07-28 12:05:12.829  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.829  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.829  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.829  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.829  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.829  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.829  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.829  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.829  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.829  7508  7576 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.829  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.829  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.829  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.829  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.829  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.829  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.829  7508  7576 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd not in the list
07-28 12:05:12.829  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.829  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.829  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.829  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.829  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.839  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.839  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.839  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.839  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.839  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.839  7508  7576 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd not in the list
07-28 12:05:12.839  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.839  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.839  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.839  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.839  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.839  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.839  7508  7576 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd not in the list
07-28 12:05:12.839  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.839  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.839  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.839  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.839  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.839  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.839  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.839  2996  3159 D bt_vendor: op for 7
07-28 12:05:12.839  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.839  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.839  7508  7576 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.839  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.839  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.839  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.839  7508  7576 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-28 12:05:12.839  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:12.839  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-28 12:05:12.839  2996  3159 D bt_upio : proc btwrite assertion
07-28 12:05:12.839  7508  7596 D BluetoothSocket: connect(), SocketState: CLOSED, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
,07-28 12:05:12.839  7508  7596 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3c8d63bb, channel: -1, state: CLOSED
07-28 12:05:12.839  7508  7576 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-28 12:05:12.839  7508  7596 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1302)
07-28 12:05:12.839  7508  7576 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-28 12:05:12.849  7508  7508 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-28 12:05:12.849  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-28 12:05:12.849  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-28 12:05:12.849  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.849  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-28 12:05:12.849  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-28 12:05:12.849  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-28 12:05:12.849  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.849  7508  7576 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-28 12:05:12.849  7508  7508 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-28 12:05:12.849  7508  7576 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd not in the list
07-28 12:05:12.849  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.849  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 12:05:12.849  7508  7576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-28 12:05:12.849  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 12:05:12.849  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-28 12:05:12.849  7508  7598 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:05:12.859  7508  7598 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
07-28 12:05:12.859  7508  7576 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:12.859  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:12.859  7508  7576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-28 12:05:12.859  7508  7598 D BluetoothSocket: bindListen(), new LocalSocket 
07-28 12:05:12.859  7508  7598 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-28 12:05:12.859  7508  7598 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3a38a0d8
07-28 12:05:12.859  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.859  7508  7598 D BluetoothSocket: channel: 6
07-28 12:05:12.859  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.859  7508  7598 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@a2e7c31, channel: 6, state: LISTENING
07-28 12:05:12.859  7508  7598 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@a2e7c31, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@3a38a0d8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3e87ff16mSocket: android.net.LocalSocket@30a48097 impl:android.net.LocalSocketImpl@2102f284 fd:FileDescriptor[112]
07-28 12:05:12.859  7508  7576 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:05:12.859  7508  7598 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@30a48097 impl:android.net.LocalSocketImpl@2102f284 fd:FileDescriptor[112]
07-28 12:05:12.859  7508  7598 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-28 12:05:12.859  7508  7598 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-28 12:05:12.859  7508  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:05:12.859  7508  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:05:12.859  7508  7508 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:05:12.859  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.859  7508  7598 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-28 12:05:12.859  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.859  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.859  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.859  7508  7508 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-28 12:05:12.859  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.859  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.859  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.859  7508  7576 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd not in the list
07-28 12:05:12.859  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.859  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.859  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.859  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.859  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.859  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.859  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.859  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.859  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.859  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.859  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.859  7508  7576 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
07-28 12:05:12.859  7508  7576 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-28 12:05:12.859  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 12:05:12.869  7508  7576 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:05:12.869  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.869  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.869  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.869  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.869  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.869  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.869  7508  7576 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd not in the list
07-28 12:05:12.869  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.869  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.869  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.869  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.869  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.869  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.869  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.869  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.869  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.869  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.869  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.869  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.869  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.869  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.869  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.869  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.869  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.869  7508  7576 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd not in the list
07-28 12:05:12.869  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.869  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.869  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.869  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.869  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.869  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.869  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.869  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.869  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.869  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.869  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.879  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:12.879  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:12.879  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:12.879  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:12.879  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.879  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.879  7508  7576 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1285c7fd not in the list
07-28 12:05:12.879  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.879  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.879  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:12.879  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.879  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.879  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:12.879  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:12.879  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:12.879  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:12.879  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:12.879  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@10936cf2 not in the list
07-28 12:05:12.879  7508  7576 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
07-28 12:05:12.879  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:05:12.879  7508  7576 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-28 12:05:12.879  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:05:12.879  7508  7576 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-28 12:05:12.879  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:05:12.879  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,07-28 12:05:12.879  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,07-28 12:05:12.879  7508  7576 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
07-28 12:05:12.879  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-28 12:05:12.879  7508  7576 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-28 12:05:12.879  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-28 12:05:12.879  7508  7576 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
07-28 12:05:12.879  7508  7576 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,07-28 12:05:12.889  7508  7576 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-28 12:05:12.889  7508  7576 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,07-28 12:05:12.889  7508  7576 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-28 12:05:12.889  7508  7576 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-28 12:05:12.889  7508  7576 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
07-28 12:05:12.889  7508  7576 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,07-28 12:05:12.889  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:12.889  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a3daa6d added. We now have 2 listener(s)
07-28 12:05:12.889  7508  7576 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:05:12.889  7508  7576 D BluetoothAdapter: enable()
07-28 12:05:12.889  7508  7576 D BluetoothAdapter: enable(): BT is already enabled..!
07-28 12:05:12.889  7508  7576 I WifiManager: packageName : com.test.thalitest
07-28 12:05:12.889   906  1709 D SecContentProvider: uri = 18 selection = isWifiEnabled
,07-28 12:05:12.889   906  1709 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-28 12:05:12.889   906  1709 D SecContentProvider2: mCursor = null
,07-28 12:05:12.889   906  1709 D WifiService: setWifiEnabled: true pid=7508, uid=10079
07-28 12:05:12.889   906  1709 W ActivityManager: Permission Denial: getCurrentUser() from pid=7508, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,07-28 12:05:12.889   906  1709 W WifiService: Failed getting userId using ActivityManagerNative
07-28 12:05:12.889   906  1709 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7508, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-28 12:05:12.889   906  1709 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-28 12:05:12.889   906  1709 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-28 12:05:12.889   906  1709 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-28 12:05:12.889   906  1709 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-28 12:05:12.889   906  1709 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
07-28 12:05:12.889   906  1709 D SettingsProvider: name = wifi_on
,07-28 12:05:12.889  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:12.889  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@237cf6a2 added. We now have 3 listener(s)
07-28 12:05:12.889  7508  7576 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:05:12.899  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:12.899  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@12a68f33 added. We now have 4 listener(s)
07-28 12:05:12.899  7508  7576 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:05:12.899  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:12.899  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@24feb2f0 added. We now have 5 listener(s)
07-28 12:05:12.899  7508  7576 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:05:12.899  7508  7576 I WifiManager: packageName : com.test.thalitest
,07-28 12:05:12.899   906  1541 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-28 12:05:12.899   906  1541 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-28 12:05:12.899   906  1541 D SecContentProvider2: mCursor = null
,07-28 12:05:12.899   906  1541 D WifiService: setWifiEnabled: false pid=7508, uid=10079
07-28 12:05:12.899   906  1541 D SettingsProvider: name = wifi_on
,07-28 12:05:12.909  7508  7576 D BluetoothAdapter: disable()
,07-28 12:05:12.909   906  1709 D SettingsProvider: name = bluetooth_on
,07-28 12:05:12.909   906  1148 E WifiStateMachine: WifiStateMachine: Leaving Connected state
07-28 12:05:12.909  1300  1300 I wpa_supplicant: reset timer : RESET_TIMER 0
07-28 12:05:12.909  1300  1300 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-28 12:05:12.909  1300  1300 I wpa_supplicant: P2P: Current p2p state = IDLE
07-28 12:05:12.909   906  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:05:12.919  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:05:12.919   906   924 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:12.919  2996  3081 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
07-28 12:05:12.919  2996  3081 D BluetoothAdapterProperties: Setting state to 13
07-28 12:05:12.919  2996  3081 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-28 12:05:12.919  2996  3081 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-28 12:05:12.919  2996  3081 D BluetoothAdapterService: updateAdapterState state is 13
07-28 12:05:12.919   906  1243 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:05:12.919   906  1243 D ActivityManager: caller:android.app.ApplicationThreadProxy@16de3748, r.packageName :com.android.bluetooth
,07-28 12:05:12.919  2996  3081 D BluetoothAdapterService: Autoconnection is available 
07-28 12:05:12.919  2996  3081 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
07-28 12:05:12.919  2996  3081 D BluetoothAdapterService: terminating service from this receiver
,07-28 12:05:12.919  2996  2996 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,07-28 12:05:12.919  2996  2996 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@fdc73a2, channel: 19, state: LISTENING
07-28 12:05:12.919  2996  2996 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@fdc73a2, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2017cbb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3d64c833mSocket: android.net.LocalSocket@235af7f0 impl:android.net.LocalSocketImpl@38e6e169 fd:FileDescriptor[74]
07-28 12:05:12.919  1300  1300 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-28 12:05:12.919  2996  2996 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@235af7f0 impl:android.net.LocalSocketImpl@38e6e169 fd:FileDescriptor[74]
,07-28 12:05:12.919  2996  3081 D BluetoothAdapterProperties: onBluetoothDisable()
,07-28 12:05:12.919   906   906 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:12.919   906   906 I InputMethodManagerService: [BT Setting State] State =13
07-28 12:05:12.919   906  3331 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
07-28 12:05:12.919  2996  3081 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,07-28 12:05:12.919  2996  3159 D bt_vendor: op for 7
07-28 12:05:12.919  2996  3159 D bt_upio : BT_WAKE is asserted already
07-28 12:05:12.929  2996  3159 D bt_vendor: op for 7
07-28 12:05:12.929  2996  3159 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:12.929  2996  3159 D bt_vendor: op for 7
07-28 12:05:12.929  2996  3159 D bt_upio : BT_WAKE is asserted already
07-28 12:05:12.929  1195  1195 D BluetoothTile:  onBluetoothStateChange:
,07-28 12:05:12.929  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-28 12:05:12.929  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:05:12.929  1195  1583 D BluetoothTile:  handleUpdatestate:false name:null
,07-28 12:05:12.929  1724  1724 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
07-28 12:05:12.929  1195  1583 D BluetoothTile:  handleUpdatestate:false name:null
,07-28 12:05:12.929  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:12.929  1195  1583 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
07-28 12:05:12.929  7508  7576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:12.929  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:12.929  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:12.929  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:12.929  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:05:12.929  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:12.929  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:05:12.929  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:05:12.929  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:12.929  7508  7576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:12.929  7508  7576 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:05:12.929   906  1148 E native  : do suspend true
,07-28 12:05:12.929   906  3355 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-28 12:05:12.929   906  1709 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:12.929  1306  1306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:05:12.929   906  1361 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
07-28 12:05:12.929  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-28 12:05:12.939  2996  3084 D BluetoothAdapterProperties: Scan Mode:20
,07-28 12:05:12.939  2996  3081 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-28 12:05:12.939  2996  3081 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
07-28 12:05:12.939   906  1462 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-28 12:05:12.939  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:12.939   906  1462 D ActivityManager: caller:android.app.ApplicationThreadProxy@3b25a9e1, r.packageName :com.google.android.gms
07-28 12:05:12.939  2996  3081 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
07-28 12:05:12.939   906  1709 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:12.939  2996  3081 E bt-btif : cmd socket is not created
,07-28 12:05:12.939  2996  5620 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:05:12.939  2996  3157 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
,07-28 12:05:12.939  2996  3159 D bt_vendor: op for 7
07-28 12:05:12.939  2996  3159 D bt_upio : BT_WAKE is asserted already
07-28 12:05:12.939  2996  3157 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-28 12:05:12.939  2996  3157 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:05:12.939  2996  3157 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:05:12.939   906  1147 D WifiP2pService: InactiveState{ what=143375 }
,07-28 12:05:12.939  2996  3157 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:05:12.939   906  1147 D WifiP2pService: P2pEnabledState{ what=143375 }
07-28 12:05:12.939  2996  3081 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
07-28 12:05:12.939  2996  3159 D bt_vendor: op for 7
07-28 12:05:12.939  2996  3159 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:12.939  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:12.939   906  1143 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:12.939  2996  3159 D bt_vendor: op for 7
07-28 12:05:12.939  2996  3159 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:12.949  2996  3159 D bt_vendor: op for 7
,07-28 12:05:12.949  2996  3159 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:12.949  2996  3159 D bt_vendor: op for 7
07-28 12:05:12.949  2996  3159 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:12.949  1306  1306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-28 12:05:12.949   906  1465 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-28 12:05:12.949   906  1465 D ActivityManager: caller:android.app.ApplicationThreadProxy@e21dc7, r.packageName :com.android.settings
,07-28 12:05:12.949  7508  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:12.949  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:12.949  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:12.949  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:12.949  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:12.949  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:05:12.949  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:12.949  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:05:12.949  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:05:12.949  2996  3159 D bt_vendor: op for 7
07-28 12:05:12.949  2996  3159 D bt_upio : BT_WAKE is asserted already
07-28 12:05:12.949  7508  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:12.949  7508  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:05:12.949  2996  3159 D bt_vendor: op for 7
07-28 12:05:12.949  2996  3159 D bt_upio : BT_WAKE is asserted already
07-28 12:05:12.949   906  1541 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:12.949  2996  3159 D bt_vendor: op for 7
07-28 12:05:12.949  2996  3159 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:12.949  2996  3159 D bt_vendor: op for 7
07-28 12:05:12.949  2996  3159 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:12.949  2996  2996 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@133227ee, channel: 5, state: LISTENING
07-28 12:05:12.949  2996  2996 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@133227ee, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@21b0854a, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@499b48fmSocket: android.net.LocalSocket@fa31c impl:android.net.LocalSocketImpl@e032b25 fd:FileDescriptor[72]
07-28 12:05:12.949  2996  2996 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@fa31c impl:android.net.LocalSocketImpl@e032b25 fd:FileDescriptor[72]
07-28 12:05:12.949  2996  2996 I BtOppRfcommListener: stopping Accept Thread
07-28 12:05:12.949  2996  2996 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@321cd4fa, channel: 12, state: LISTENING
07-28 12:05:12.949  2996  2996 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@321cd4fa, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@8a8fb6d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@12870aabmSocket: android.net.LocalSocket@3401d508 impl:android.net.LocalSocketImpl@3fe054a1 fd:FileDescriptor[77]
07-28 12:05:12.949  2996  2996 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3401d508 impl:android.net.LocalSocketImpl@3fe054a1 fd:FileDescriptor[77]
07-28 12:05:12.949  2996  5620 I BtOppRfcommListener: BluetoothSocket listen thread finished
,07-28 12:05:12.949  2996  3159 D bt_vendor: op for 7
07-28 12:05:12.949  2996  3159 D bt_upio : BT_WAKE is asserted already
07-28 12:05:12.949   294  1067 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:05:12.959  2996  3159 D bt_vendor: op for 7
07-28 12:05:12.959  2996  3159 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:12.959  2996  3159 D bt_vendor: op for 7
07-28 12:05:12.959  2996  3159 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:12.959  1195  1195 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:05:12.959  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-28 12:05:12.969   906  1413 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:12.969  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:12.969   906  1560 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:12.969  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:12.969   906   924 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:12.969  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:12.979  1922  5067 V NativeCrypto: Read error: ssl=0x9b7d3e00: I/O error during system call, Connection timed out
,07-28 12:05:12.979  1306  1306 D BluetoothPbap: Proxy object disconnected
,07-28 12:05:12.979  1306  1306 D PbapServerProfile: Bluetooth service disconnected
07-28 12:05:12.979  1922  5067 V NativeCrypto: SSL shutdown failed: ssl=0x9b7d3e00: I/O error during system call, Broken pipe
,07-28 12:05:12.979   906  1435 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:12.989   906  1150 E ConnectivityService: updateNetworkInfo()
07-28 12:05:12.989   906  1150 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:05:12.989   906  1150 E ConnectivityService: updateNetworkInfo()
07-28 12:05:12.989   906  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
,07-28 12:05:12.989   906  1150 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
,07-28 12:05:12.989   906  1341 E Watchdog: !@Sync 5
,07-28 12:05:12.989  1922  5067 E GCM     : Wifi connection closed with errorCode 20
,07-28 12:05:12.989   906  3355 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:13.009   906  1709 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
,07-28 12:05:13.009   906  1765 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:13.009   906  1765 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:13.009   906  1765 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,07-28 12:05:13.009   906  1765 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:13.009   906  1765 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,07-28 12:05:13.009   906  1765 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-28 12:05:13.009   906  1765 I qtaguid : Tagging socket 377 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 906, getuid(): 1000
,07-28 12:05:13.009   906  1765 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-28 12:05:13.009  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:05:13.009  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:05:13.009   906   906 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-28 12:05:13.009  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:13.009  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:13.009  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:13.009  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:13.009  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:13.009  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:13.009  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:13.009  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:13.009  1306  1306 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:05:13.009   906  1462 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:13.009   906  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:05:13.019   906  1560 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:13.019  1306  1306 D BluetoothNotiBroadcastReceiver: onReceive
,07-28 12:05:13.019   906  1435 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:13.019   906  1465 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,07-28 12:05:13.019   906  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:13.019   906  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:13.019   906  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:13.019   906  1465 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:13.059   906  1030 D EntConnectivity: Not allowed due to - mEnabled false
07-28 12:05:13.059   906  1150 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
07-28 12:05:13.059   906  1765 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
07-28 12:05:13.059   906  1150 D ConnectivityService: calling update connectivity
07-28 12:05:13.059   906  1765 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
07-28 12:05:13.059   906  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:13.059   906  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:05:13.059   906  1150 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:05:13.059  1195  1579 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-28 12:05:13.059   906  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:13.059   906  1150 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:13.059   906  1150 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
07-28 12:05:13.059   906  1150 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:13.059   906  1150 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-28 12:05:13.059  1428  1428 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:13.059   906  1150 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
07-28 12:05:13.059   906  1765 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:13.059   906  1150 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
07-28 12:05:13.059   906  1765 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:13.059   906  1150 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:05:13.059   906  1765 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,07-28 12:05:13.059  4431  7321 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,07-28 12:05:13.059  7619  7619 E Zygote  : MountEmulatedStorage()
07-28 12:05:13.069  7619  7619 E Zygote  : v2
07-28 12:05:13.069  7619  7619 I libpersona: KNOX_SDCARD checking this for 10140
07-28 12:05:13.069  7619  7619 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:13.069   906  1465 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7619 uid=10140 gids={50140, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,07-28 12:05:13.069   906  1150 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:13.069   906  1148 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
07-28 12:05:13.069   906  1147 D WifiP2pService: InactiveState{ what=131204 }
07-28 12:05:13.069   906  1147 D WifiP2pService: P2pEnabledState{ what=131204 }
,07-28 12:05:13.069   906  1150 E ConnectivityService: EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
07-28 12:05:13.069   906  1147 D WifiP2pService: sending p2p connection changed broadcast: FAILED
07-28 12:05:13.079   906  1150 E ConnectivityService: updateNetworkInfo()
,07-28 12:05:13.079   906  1150 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:05:13.079   906  1147 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
07-28 12:05:13.079   906  1150 E ConnectivityService: updateNetworkInfo()
,07-28 12:05:13.079   906  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
07-28 12:05:13.079   906  1147 D WifiP2pService: P2pDisablingState
07-28 12:05:13.079   906  1147 D WifiP2pService: P2pDisablingState{ what=147458 }
,07-28 12:05:13.079   906  1147 D WifiP2pService: p2p socket connection lost
07-28 12:05:13.079   906  1147 D WifiP2pService: P2pDisabledState
,07-28 12:05:13.079   906   906 D WifiScanningService: SCAN_AVAILABLE : 1
07-28 12:05:13.079   906   906 D RttService: SCAN_AVAILABLE : 1
07-28 12:05:13.079   906  1165 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:13.079   906  1166 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:13.079   906  1145 V NetworkStats: updateIfacesLocked()
07-28 12:05:13.079   906  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:05:13.079   906  1145 V NetworkStats: performPollLocked(flags=0x1)
07-28 12:05:13.079   906   906 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:05:13.079   906  1152 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-28 12:05:13.079   906  1151 D Tethering: MasterInitialState.processMessage what=3
07-28 12:05:13.079   906   906 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
07-28 12:05:13.079   906  1031 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-28 12:05:13.079   906  1031 D WifiDisplayAdapter: onP2pDisconnected
07-28 12:05:13.079   906  1031 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-28 12:05:13.079   906  1031 D IpRemoteDisplayController: WfdBridgeServer is already null
07-28 12:05:13.079   906  1031 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
07-28 12:05:13.079   906  1031 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-28 12:05:13.079   906  1031 D WifiDisplayController: disconnect
07-28 12:05:13.079   906  1031 D WifiDisplayController: updateConnection
07-28 12:05:13.079   906  1031 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-28 12:05:13.079   906  1031 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-28 12:05:13.079   906  1145 D NetworkStatsFactory: UpdateStatsForKnox
07-28 12:05:13.079   906  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:13.079   906  1152 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:05:13.079   906  1148 E native  : do suspend true
07-28 12:05:13.079   906  1152 D SmartBondingService: getSBEnabled() enabled =false
,07-28 12:05:13.079   906  1152 D SmartBondingService: getSBEnabled() enabled =false
,07-28 12:05:13.079   906  1145 V NetworkStats: performPollLocked() took 6ms
07-28 12:05:13.079   906  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:05:13.089   906  1147 D WifiP2pService: P2pDisabledState{ what=143375 }
07-28 12:05:13.089   906  1147 D WifiP2pService: DefaultState{ what=143375 }
,07-28 12:05:13.089   294  1067 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:05:13.089   906   906 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-28 12:05:13.089  1300  1300 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,07-28 12:05:13.099  7619  7619 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-28 12:05:13.099  7619  7619 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:05:13.099  1195  1195 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-28 12:05:13.099  1195  1195 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-28 12:05:13.099  1195  1195 D StatusBar.NetworkController: updateDataNetType()
07-28 12:05:13.099  1195  1195 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
07-28 12:05:13.099  1195  1195 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,07-28 12:05:13.099  7619  7619 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
07-28 12:05:13.099   906   906 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:05:13.099  1306  1306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:05:13.099   906  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-28 12:05:13.099   906  1148 D SecContentProvider2: mCursor = null
,07-28 12:05:13.099  7508  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:05:13.099  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:13.099  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:13.099  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:13.099  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:05:13.099  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:05:13.099  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:13.099  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:13.099  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:05:13.109   906  1152 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-28 12:05:13.109   906  1143 I AudioService: getStreamVolume 3 index 0
07-28 12:05:13.109  1195  1195 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-28 12:05:13.109  1195  1195 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
07-28 12:05:13.109  1195  1195 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
07-28 12:05:13.109  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:05:13.109  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:05:13.109  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:13.109  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:13.109  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:13.109   906  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-28 12:05:13.109  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:13.109  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:13.109  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:13.109  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:13.109  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:13.109  1195  1195 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,07-28 12:05:13.109  7508  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:13.109   906   924 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-28 12:05:13.109  7508  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:05:13.109   906  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:05:13.109   906  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:05:13.109   906  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:05:13.109   906  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:05:13.109   906  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:05:13.109   906  1146 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
07-28 12:05:13.109   906  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:05:13.109  7508  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:13.109  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:13.109  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:13.109  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:13.109  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:05:13.109  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:05:13.109  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:13.109  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:13.109  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:05:13.109  7508  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:13.109  7508  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:05:13.109  1195  1195 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-28 12:05:13.109  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:05:13.109  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:05:13.119  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:05:13.119  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:05:13.119  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:05:13.119  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-28 12:05:13.119  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:13.119  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:13.119  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:13.119  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:13.119  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:13.119  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:13.119  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:13.119  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:13.119  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:05:13.119  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
07-28 12:05:13.119  1195  1583 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-28 12:05:13.119  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:05:13.119  1195  1195 D HotspotTile: onReceive : 0, 0
07-28 12:05:13.119  7619  7619 D TimaKeyStoreProvider: TimaSignature is unavailable
07-28 12:05:13.129  7619  7619 D ActivityThread: Added TimaKeyStore provider
07-28 12:05:13.139   906  3093 D SSRM:n  : SIOP:: AP = 380, PST = 361, CUR = 450
07-28 12:05:13.139  1300  1300 I wpa_supplicant: Blacklist: Clear (all) 
07-28 12:05:13.139  2996  3157 W bt-l2cap: btif_mce_execute_service enable:0
07-28 12:05:13.139  2996  3157 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:05:13.139  2996  3157 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:05:13.139  2996  3157 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:05:13.139  2996  3157 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:05:13.139  2996  3157 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:05:13.139  2996  3157 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:05:13.139  2996  3157 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:05:13.139  2996  3157 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:05:13.139  2996  3157 W bt-btif : ag scb idx 1 not allocated
07-28 12:05:13.139  2996  3157 W bt-btif : ag scb idx 2 not allocated
07-28 12:05:13.139  2996  3157 E bt-btif : BTA AG is already disabled, ignoring ...
07-28 12:05:13.139  2996  3159 D bt_vendor: op for 6
07-28 12:05:13.139  2996  3159 D bt_vendor: op for 7
07-28 12:05:13.139  2996  3159 D bt_upio : BT_WAKE is asserted already
07-28 12:05:13.139  2996  3160 D bt_userial: RX termination
07-28 12:05:13.139  2996  3160 W bt_userial: select_read return size <=0:-1, exiting userial_read_thread
07-28 12:05:13.139  2996  3160 D bt_userial: Leaving userial_read_thread()
07-28 12:05:13.139  2996  3084 D bt_userial: userial_close_reader Joined userial reader thread: 0
07-28 12:05:13.139  2996  3159 D bt_vendor: op for 9
07-28 12:05:13.139  2996  3159 D bt_hwcfg: hw_epilog_process
07-28 12:05:13.139  2996  3084 D bt_vendor: op for 4
07-28 12:05:13.139  2996  3084 I bt_userial_vendor: device fd = 65 close
07-28 12:05:13.149  7619  7619 D ResourcesManager: creating new AssetManager and set to /system/app/Maps/Maps.apk
07-28 12:05:13.149  2996  3084 D bt_vendor: op for 0
07-28 12:05:13.149  2996  3084 D bt_upio : upio_set_bluetooth_power(on: 0)
07-28 12:05:13.149  2996  3084 D bt_upio : is_emulator_context : 0
07-28 12:05:13.149  2996  3084 D bt_upio : is_rfkill_disabled ? [0]
07-28 12:05:13.149  2996  3084 D bt_vendor: cleanup
07-28 12:05:13.149  2996  3157 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-28 12:05:13.149  2996  3084 I GKI_LINUX: GKI_exit_task 0 done
07-28 12:05:13.149  2996  3084 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
07-28 12:05:13.149  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-28 12:05:13.149  2996  3081 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-28 12:05:13.149  2996  3081 D BtConfig.SecureMode: isSecureModeOn:false
07-28 12:05:13.149  2996  3081 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
07-28 12:05:13.149  2996  3081 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
07-28 12:05:13.149  2996  3081 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-28 12:05:13.149  2996  3081 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
07-28 12:05:13.149   906  1243 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:05:13.149   906  1243 D ActivityManager: caller:android.app.ApplicationThreadProxy@312a760, r.packageName :com.android.bluetooth
07-28 12:05:13.149  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-28 12:05:13.149  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:05:13.149  2996  2996 D BtGatt.DebugUtils: handleDebugAction() action=null
07-28 12:05:13.149  2996  2996 D BtGatt.GattService: Received stop request...Stopping profile...
07-28 12:05:13.149  2996  2996 D BtGatt.GattService: stop()
07-28 12:05:13.149  2996  2996 D BtGatt.AdvertiseManager: advertise clients cleared
07-28 12:05:13.149  2996  3081 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
07-28 12:05:13.149  2996  3081 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-28 12:05:13.149  2996  2996 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c7e9b30
07-28 12:05:13.159  2996  3081 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
07-28 12:05:13.159   906   923 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:05:13.159  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-28 12:05:13.159   906   923 D ActivityManager: caller:android.app.ApplicationThreadProxy@1230b419, r.packageName :com.android.bluetooth
07-28 12:05:13.159  2996  3081 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
07-28 12:05:13.159  2996  3081 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-28 12:05:13.159  2996  3081 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
07-28 12:05:13.159   906   924 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:05:13.159   906   924 D ActivityManager: caller:android.app.ApplicationThreadProxy@39f27cde, r.packageName :com.android.bluetooth
07-28 12:05:13.159  2996  3081 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
07-28 12:05:13.159  2996  3081 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-28 12:05:13.159  2996  3081 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-28 12:05:13.159   906  1435 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:05:13.159   906  1435 D ActivityManager: caller:android.app.ApplicationThreadProxy@3ffefebf, r.packageName :com.android.bluetooth
07-28 12:05:13.159  2996  3081 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
07-28 12:05:13.159  2996  3081 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-28 12:05:13.159  2996  3081 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-28 12:05:13.159   906  1663 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:05:13.159   906  1663 D ActivityManager: caller:android.app.ApplicationThreadProxy@37ead98c, r.packageName :com.android.bluetooth
07-28 12:05:13.159  2996  3081 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
07-28 12:05:13.159  2996  3081 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-28 12:05:13.159  2996  3081 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-28 12:05:13.159  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-28 12:05:13.159   906  3355 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:05:13.159   906  3355 D ActivityManager: caller:android.app.ApplicationThreadProxy@2b8f78d5, r.packageName :com.android.bluetooth
07-28 12:05:13.159  2996  3081 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
07-28 12:05:13.159  2996  3081 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:05:13.159  2996  3081 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
07-28 12:05:13.159   906  1143 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:05:13.159   906  1143 D ActivityManager: caller:android.app.ApplicationThreadProxy@ca588ea, r.packageName :com.android.bluetooth
07-28 12:05:13.159  2996  3081 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
07-28 12:05:13.159  2996  3081 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-28 12:05:13.159  2996  3081 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-28 12:05:13.159   906  1243 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:05:13.159   906  1243 D ActivityManager: caller:android.app.ApplicationThreadProxy@212ec7db, r.packageName :com.android.bluetooth
07-28 12:05:13.159  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-28 12:05:13.159  2996  3081 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:05:13.159  2996  3081 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:05:13.159  2996  3081 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:05:13.159  2996  3081 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:05:13.159  2996  3081 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:05:13.169  2996  3081 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:05:13.169  2996  3081 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
07-28 12:05:13.169  2996  3081 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-28 12:05:13.169  2996  3081 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-28 12:05:13.169  2996  3081 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
07-28 12:05:13.169  2996  3081 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-28 12:05:13.169  2996  3081 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-28 12:05:13.169  1300  1300 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-28 12:05:13.169  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-28 12:05:13.169  2996  2996 E BluetoothAdapterService(1014930224): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
07-28 12:05:13.169  2996  2996 D HeadsetService: Received stop request...Stopping profile...
07-28 12:05:13.169  2996  3081 D BluetoothAdapterState: Stopping profile services that were post enabled
07-28 12:05:13.169  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-28 12:05:13.169  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-28 12:05:13.169  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-28 12:05:13.169  1300  1300 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
07-28 12:05:13.169  1300  1300 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
07-28 12:05:13.169  1300  1300 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=0 BSSID=F4.99.3E SSID=4E47373030
07-28 12:05:13.169  1300  1300 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
07-28 12:05:13.179  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-28 12:05:13.179  2996  2996 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c7e9b30
07-28 12:05:13.179   906   906 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-28 12:05:13.179  2996  2996 D A2dpService: Received stop request...Stopping profile...
07-28 12:05:13.179  2996  2996 V Avrcp   : doQuit
07-28 12:05:13.179  2996  3095 D A2dpStateMachine: Exit Disconnected: -1
07-28 12:05:13.179  1306  1306 D HeadsetProfile: Bluetooth service disconnected
07-28 12:05:13.179  2996  2996 D Avrcp   : Unregistering previous receiver
07-28 12:05:13.179  2996  2996 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c7e9b30
07-28 12:05:13.189  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-28 12:05:13.189   906   906 D BluetoothA2dp: Proxy object disconnected
07-28 12:05:13.189   906   906 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-28 12:05:13.189  1306  1306 D BluetoothA2dp: Proxy object disconnected
07-28 12:05:13.189  2996  2996 D HidService: Received stop request...Stopping profile...
07-28 12:05:13.189  2996  2996 D HidService: Stopping Bluetooth HidService
07-28 12:05:13.189  2996  2996 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-28 12:05:13.189  2996  2996 W bt-btif : cleanup: HH disabling or disabled already, status = 0
07-28 12:05:13.189  2996  2996 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-28 12:05:13.189  2996  2996 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c7e9b30
07-28 12:05:13.189  2996  2996 D HealthService: Received stop request...Stopping profile...
07-28 12:05:13.189  2996  2996 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c7e9b30
07-28 12:05:13.189  1306  1306 D A2dpProfile: Bluetooth service disconnected
07-28 12:05:13.189  3196  3196 D BluetoothA2dp: Proxy object disconnected
07-28 12:05:13.189  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-28 12:05:13.189  1306  1306 D BluetoothInputDevice: Proxy object disconnected
07-28 12:05:13.189  1306  1306 D HidProfile: Bluetooth service disconnected
07-28 12:05:13.189  2996  2996 D PanService: Received stop request...Stopping profile...
07-28 12:05:13.189  2996  2996 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c7e9b30
,07-28 12:05:13.189   906   906 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-28 12:05:13.189  2996  2996 D BluetoothMapService: Received stop request...Stopping profile...
07-28 12:05:13.189  2996  2996 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c7e9b30
07-28 12:05:13.199  1428  1428 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-28 12:05:13.199  2996  2996 D SapService: Received stop request...Stopping profile...
07-28 12:05:13.199  2996  2996 D SapService: Stopping Bluetooth SapService
07-28 12:05:13.199  2996  2996 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c7e9b30
07-28 12:05:13.199  2996  2996 E BluetoothAdapterService(1014930224): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
07-28 12:05:13.199  2996  2996 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-28 12:05:13.199  2996  2996 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
07-28 12:05:13.199  2996  2996 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-28 12:05:13.199  2996  2996 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
07-28 12:05:13.199  2996  2996 E BluetoothAdapterService(1014930224): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
07-28 12:05:13.199  2996  2996 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-28 12:05:13.199  2996  2996 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
07-28 12:05:13.199  2996  2996 D BluetoothA2dp: Proxy object disconnected
07-28 12:05:13.199  2996  2996 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
07-28 12:05:13.199  1306  1306 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-28 12:05:13.199  2996  3096 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-28 12:05:13.199  1306  1306 D PanProfile: Bluetooth service disconnected
07-28 12:05:13.199  1306  1306 D BluetoothMap: Proxy object disconnected
07-28 12:05:13.199  2996  2996 I GKI_LINUX: GKI_exit_task 2 done
07-28 12:05:13.199  2996  2996 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-28 12:05:13.199  2996  2996 V Avrcp   : cleanup
07-28 12:05:13.199  1306  1306 D MapProfile: Bluetooth service disconnected
07-28 12:05:13.199  2996  2996 E BluetoothAdapterService(1014930224): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
07-28 12:05:13.199  2996  2996 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:05:13.199  2996  2996 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-28 12:05:13.199  2996  2996 E BluetoothAdapterService(1014930224): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
07-28 12:05:13.199  2996  2996 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:05:13.199  2996  2996 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-28 12:05:13.199  2996  2996 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-28 12:05:13.199  2996  2996 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:05:13.199  2996  2996 E BluetoothAdapterService(1014930224): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
07-28 12:05:13.199  2996  2996 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:05:13.199  2996  2996 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-28 12:05:13.199  2996  2996 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-28 12:05:13.199  2996  2996 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-28 12:05:13.199  1306  1306 D Bluetoothsap: BluetoothSAP Proxy object disconnected
07-28 12:05:13.199  1306  1306 D SapProfile: Bluetooth service disconnected
07-28 12:05:13.199  2996  2996 E BluetoothAdapterService(1014930224): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
07-28 12:05:13.199  2996  2996 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-28 12:05:13.199  2996  2996 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
07-28 12:05:13.199  2996  2996 E BluetoothAdapterService(1014930224): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
07-28 12:05:13.199  2996  3081 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
07-28 12:05:13.199  2996  3081 D BluetoothAdapterProperties: Setting state to 10
07-28 12:05:13.199  2996  3081 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-28 12:05:13.199  2996  3081 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-28 12:05:13.199  2996  3081 D BluetoothAdapterService: updateAdapterState state is 10
07-28 12:05:13.199  2996  2996 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
07-28 12:05:13.199  2996  2996 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
07-28 12:05:13.199  2996  3081 D BluetoothAdapterService: Autoconnection is available 
07-28 12:05:13.199  2996  3081 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
07-28 12:05:13.199  2996  3081 I BluetoothAdapterState: Entering OffState
07-28 12:05:13.209  3196  3214 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:05:13.209  1306  1315 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:05:13.209  1306  1328 D BluetoothInputDevice: onBluetoothStateChange: up=false
07-28 12:05:13.209  1306  1318 D BluetoothMap: onBluetoothStateChange: up=false
07-28 12:05:13.209   906  1030 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:05:13.209  1306  1315 D Bluetoothsap: onBluetoothStateChange: up=false
07-28 12:05:13.209  1306  1315 D Bluetoothsap: Unbinding service...
07-28 12:05:13.209  2996  3009 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:05:13.209  1306  1328 D BluetoothPbap: onBluetoothStateChange: up=false
07-28 12:05:13.209   906  1030 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 12 receivers.
07-28 12:05:13.219  1300  1300 I wpa_supplicant: Blacklist: Clear (all) 
07-28 12:05:13.219   906  1030 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
07-28 12:05:13.219   906   906 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:13.219   906   906 I InputMethodManagerService: [BT Setting State] State =10
07-28 12:05:13.219   906   906 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
07-28 12:05:13.219  1195  1195 D BluetoothAdapter: 641724124: getState() :  mService = null. Returning STATE_OFF
07-28 12:05:13.219  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-28 12:05:13.219  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:13.219  1195  1583 D BluetoothAdapter: 641724124: getState() :  mService = null. Returning STATE_OFF
07-28 12:05:13.219  1306  1306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:13.219  1195  1195 D BluetoothAdapter: 641724124: getState() :  mService = null. Returning STATE_OFF
07-28 12:05:13.219  1724  1724 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
07-28 12:05:13.219  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:13.219  1195  1583 D BluetoothAdapter: 641724124: getState() :  mService = null. Returning STATE_OFF
07-28 12:05:13.219  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:13.219  1922  2408 D BluetoothAdapter: 136307705: getState() :  mService = null. Returning STATE_OFF
07-28 12:05:13.219  1922  2408 D BluetoothAdapter: 136307705: getState() :  mService = null. Returning STATE_OFF
07-28 12:05:13.219   906  1413 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-28 12:05:13.219  1195  1583 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
07-28 12:05:13.219   906  1413 D ActivityManager: caller:android.app.ApplicationThreadProxy@10320278, r.packageName :com.google.android.gms
07-28 12:05:13.219  1195  1195 D BluetoothAdapter: 641724124: getState() :  mService = null. Returning STATE_OFF
07-28 12:05:13.219   906   923 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-28 12:05:13.219   906   924 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
07-28 12:05:13.219  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
07-28 12:05:13.219  2996  3084 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
07-28 12:05:13.219  2996  2996 I GKI_LINUX: GKI_exit_task 1 done
07-28 12:05:13.219  2996  2996 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
07-28 12:05:13.229  2996  2996 I BluetoothServiceJni: cleanupNative: return from cleanup
07-28 12:05:13.229  2996  2996 I art     : System.exit called, status: 0
07-28 12:05:13.229  2996  2996 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-28 12:05:13.279   906   924 I ActivityManager: Process com.android.bluetooth (pid 2996)(adj 0) has died(171,1591)
,07-28 12:05:13.369   906   924 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,07-28 12:05:13.369  1922  1922 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-28 12:05:13.369  1922  1922 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-28 12:05:13.379  1300  1300 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-28 12:05:13.379   906  1145 V NetworkStats: performPollLocked(flags=0x1)
07-28 12:05:13.379   906  1151 D Tethering: InitialState.processMessage what=4
07-28 12:05:13.379  1195  1195 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-28 12:05:13.379   906  1151 E Tethering: No numeric data
07-28 12:05:13.379  1195  1195 D HotspotTile: updateTetherState():false, false
07-28 12:05:13.379   906  1151 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-28 12:05:13.379   906  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:05:13.379   301   301 E SMD     : DCD ON
,07-28 12:05:13.389   906  1145 D NetworkStatsFactory: UpdateStatsForKnox
07-28 12:05:13.389   906  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:13.389   906  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
,07-28 12:05:13.389   906  1148 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-28 12:05:13.389   906  1145 V NetworkStats: performPollLocked() took 10ms
,07-28 12:05:13.389  1306  1306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:05:13.399   906   906 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
07-28 12:05:13.399  1922  2408 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:05:13.399  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:05:13.399  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-28 12:05:13.399  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:05:13.399  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:13.399  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
07-28 12:05:13.399  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:05:13.399  1195  1583 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-28 12:05:13.399   906  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:05:13.399  1195  1195 D HotspotTile: onReceive : 1, 0
,07-28 12:05:13.399   906  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-28 12:05:13.399  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:13.399   906  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:05:13.399   906  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:05:13.419  7619  7619 D StrictMode: StrictMode policy violation; ~duration=191 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:05:13.419  7619  7619 D StrictMode: StrictMode policy violation; ~duration=181 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:05:13.419  7619  7619 D StrictMode: StrictMode policy violation; ~duration=139 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.io.File.doAccess(File.java:283)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.io.File.exists(File.java:363)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1319)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityTh,read.main(ActivityThread.java:5938)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:05:13.419  7619  7619 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:05:13.419  7619  7619 D StrictMode: StrictMode policy violation; ~duration=138 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:05:13.419  7619  7619 D StrictMode: StrictMode policy violation; ~duration=136 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.r.k.c(PG:1187)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.r.v.a(PG:1206)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.r.y.a(PG:2233)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.r.e.b(PG:170)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.r.e.b(PG:13188)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:05:13.419  7619  7619 D StrictMode: StrictMode policy violation; ~duration=134 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.r.k.c(PG:1187)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.r.k.b(PG:14147)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.r.k.c(PG:583)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.r.v.a(PG:1206)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.r.y.a(PG:2233)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.r.e.b(PG:170)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.r.e.b(PG:13188)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:05:13.419  7619  7619 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:05:13.429  7619  7619 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:05:13.429  7619  7619 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at java.io.File.doAccess(File.java:283)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at java.io.File.exists(File.java:363)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1485)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:05:13.429  7619  7619 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:05:13.429   906  1541 I ActivityManager: Killing 5763:com.android.calendar/u0a172 (adj 15): emptyCount ##41
07-28 12:05:13.429  1922  1922 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-28 12:05:13.439  1922  1922 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
07-28 12:05:13.439   906  3355 D ActivityManager: startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
07-28 12:05:13.439   906  3355 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:13.439   906  3355 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:13.439   906  3355 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:13.439   906  3355 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:13.469  7619  7658 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
07-28 12:05:13.479  7666  7666 E Zygote  : MountEmulatedStorage()
07-28 12:05:13.479  7666  7666 E Zygote  : v2
07-28 12:05:13.479  7666  7666 I libpersona: KNOX_SDCARD checking this for 10038
07-28 12:05:13.479  7666  7666 I libpersona: KNOX_SDCARD not a persona
07-28 12:05:13.489   906  3355 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7666 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
07-28 12:05:13.499  7666  7666 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:05:13.499  7666  7666 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:05:13.499  7666  7666 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-28 12:05:13.539  7666  7666 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:05:13.539  7666  7666 D ActivityThread: Added TimaKeyStore provider
,07-28 12:05:13.559  1922  2318 I art     : Explicit concurrent mark sweep GC freed 121728(6MB) AllocSpace objects, 61(2MB) LOS objects, 39% free, 23MB/39MB, paused 757us total 58.546ms
,07-28 12:05:13.569   906  1150 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:05:13.579   906   906 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:13.579   906   906 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:13.579   906   906 I ApplicationPolicy: updateDataUsageMap
,07-28 12:05:13.579   906  1152 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-28 12:05:13.579   906  1152 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:05:13.579   906  1152 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:05:13.579   906   981 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:13.579   906  1152 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:05:13.579   906   981 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:13.579  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:13.579  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:13.589  1586  1586 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-28 12:05:13.589   906   924 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:13.589   906   923 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:13.599   906  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,07-28 12:05:13.619   906  1243 I art     : Explicit concurrent mark sweep GC freed 59978(3MB) AllocSpace objects, 25(448KB) LOS objects, 29% free, 37MB/53MB, paused 1.491ms total 113.303ms
,07-28 12:05:13.619   906  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-28 12:05:13.629  7666  7666 D ResourcesManager: creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,07-28 12:05:13.639  7666  7666 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,07-28 12:05:13.749  7666  7666 I VlingoApplication: VlingoApplication appVersion ='11.2.2.0.37791', ro.csc.sales_code=XEO
,07-28 12:05:13.819  7666  7666 D BluetoothAdapter: 833714834: getState() :  mService = null. Returning STATE_OFF
,07-28 12:05:13.819  7666  7666 D BluetoothAdapter: 833714834: getState() :  mService = null. Returning STATE_OFF
07-28 12:05:13.819  7666  7666 D BluetoothAdapter: 833714834: getState() :  mService = null. Returning STATE_OFF
,07-28 12:05:13.819  7666  7666 D BluetoothAdapter: 833714834: getState() :  mService = null. Returning STATE_OFF
07-28 12:05:13.819  7666  7666 D BluetoothAdapter: 833714834: getState() :  mService = null. Returning STATE_OFF
07-28 12:05:13.819  7666  7666 D BluetoothAdapter: 833714834: getState() :  mService = null. Returning STATE_OFF
,07-28 12:05:13.849  7666  7666 E BluetoothHeadset: BTStateChangeCB is registed
,07-28 12:05:13.859   906  1541 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:05:13.859  7666  7666 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:05:13.859   906  1435 I ActivityManager: Killing 6658:com.qualcomm.timeservice/1000 (adj 15): emptyCount ##41
,07-28 12:05:13.859  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-28 12:05:13.859  1306  1306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-28 12:05:13.869   906  1462 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:13.869  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-28 12:05:13.869   906  1560 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-28 12:05:13.869  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:05:13.869  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:05:13.869  1306  1306 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:05:13.869  1306  2807 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:05:13.869   906  1361 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:13.879  7109  7109 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:05:13.879   906  1243 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,07-28 12:05:13.879   906  1243 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:13.879   906  1243 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:13.879   906  1243 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:13.879   906  1243 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:13.899   906  3331 D SettingsProvider: name = driving_mode_on
07-28 12:05:13.899   906  3331 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:13.899   906  3331 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:13.899   906  3331 D SettingsProvider: selectionArgs: false
07-28 12:05:13.899   906  3331 D SettingsProvider: selectionArgs: 10038
07-28 12:05:13.899   906  3331 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:13.899   906  3331 D SettingsProvider: ret = -1
,07-28 12:05:13.899  7666  7666 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,07-28 12:05:13.919  7692  7692 E Zygote  : MountEmulatedStorage()
07-28 12:05:13.919  7692  7692 E Zygote  : v2
07-28 12:05:13.919  7692  7692 I libpersona: KNOX_SDCARD checking this for 10131
07-28 12:05:13.919  7692  7692 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:13.929   906  1243 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7692 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-28 12:05:13.939  7692  7692 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:05:13.939  7692  7692 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:05:13.939  7692  7692 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-28 12:05:13.959  7692  7692 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:05:13.959  7692  7692 D ActivityThread: Added TimaKeyStore provider
,07-28 12:05:13.969  7692  7692 D ResourcesManager: creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,07-28 12:05:13.969  7692  7692 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-28 12:05:14.149  7692  7715 I Babel   : MmsConfig: mnc/mcc: 0/0
,07-28 12:05:14.149  7692  7715 I Babel   : MmsConfig.loadMmsSettings
07-28 12:05:14.149  7692  7715 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
,07-28 12:05:14.149  7692  7715 I Babel   : MmsConfig.loadFromDatabase
07-28 12:05:14.149  7692  7692 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,07-28 12:05:14.179  7692  7715 E Babel   : canonicalizeMccMnc: invalid mccmnc 
,07-28 12:05:14.179  7692  7715 I Babel   : MmsConfig.loadFromResources
,07-28 12:05:14.179  7692  7715 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,07-28 12:05:14.179  7692  7715 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
,07-28 12:05:14.189   906  1663 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,07-28 12:05:14.189  7692  7692 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:05:14.219  7692  7692 I Babel_StickerModule: App launched.
,07-28 12:05:14.229  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-28 12:05:14.229  1306  1306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-28 12:05:14.229   906  3064 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:14.229  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-28 12:05:14.229   906   924 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-28 12:05:14.229  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:05:14.229  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:05:14.229  1306  1306 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:05:14.229  1306  2807 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:05:14.239  7219  7219 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-28 12:05:14.239   906  1413 D ActivityManager: startProcessLocked calleePkgName: com.samsung.shareshot, hostingType: broadcast
,07-28 12:05:14.239   906  1413 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:14.239   906  1413 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:14.239   906  1413 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:14.239   906  1413 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:14.259   317   674 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,07-28 12:05:14.259   317   674 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
07-28 12:05:14.259   317   674 W QCamera2Factory: getCameraInfo: X
,07-28 12:05:14.259   317   317 W QCamera2Factory: getCameraInfo: E, camera_id = 1
07-28 12:05:14.259   317   317 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
07-28 12:05:14.259   317   317 W QCamera2HWI: __dbg: info->orientation : 270 rc = 0
07-28 12:05:14.259   317   317 W QCamera2Factory: getCameraInfo: X
,07-28 12:05:14.279  7692  7692 W AudioCapabilities: Unsupported mime audio/evrc
,07-28 12:05:14.279  7692  7692 W AudioCapabilities: Unsupported mime audio/qcelp
,07-28 12:05:14.279  7692  7692 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-28 12:05:14.289  7720  7720 E Zygote  : MountEmulatedStorage()
07-28 12:05:14.289  7720  7720 E Zygote  : v2
07-28 12:05:14.289  7720  7720 I libpersona: KNOX_SDCARD checking this for 10192
07-28 12:05:14.289  7720  7720 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:14.299   906  1413 I ActivityManager: Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=7720 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:05:14.309  7720  7720 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:05:14.309  7720  7720 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:05:14.309  7720  7720 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:05:14.309  7692  7692 W AudioCapabilities: Unsupported mime audio/mpeg-L1
,07-28 12:05:14.319  7692  7692 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,07-28 12:05:14.319  7692  7692 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,07-28 12:05:14.319  7692  7692 W AudioCapabilities: Unsupported mime audio/x-ima
,07-28 12:05:14.329  7692  7692 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,07-28 12:05:14.329  7692  7692 W AudioCapabilities: Unsupported mime audio/qcelp
07-28 12:05:14.329  7720  7720 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:05:14.339  7720  7720 D ActivityThread: Added TimaKeyStore provider
,07-28 12:05:14.339  7692  7692 W AudioCapabilities: Unsupported mime audio/evrc
,07-28 12:05:14.349  7720  7720 D ResourcesManager: creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,07-28 12:05:14.359  7692  7692 W VideoCapabilities: Unsupported mime video/wvc1
,07-28 12:05:14.359  7692  7692 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-28 12:05:14.369  7692  7692 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,07-28 12:05:14.369  7692  7692 W VideoCapabilities: Unsupported mime video/wvc1
,07-28 12:05:14.379  7692  7692 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-28 12:05:14.379  7720  7720 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-28 12:05:14.379  7692  7692 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,07-28 12:05:14.379  7720  7720 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
07-28 12:05:14.379  7692  7692 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,07-28 12:05:14.379  7720  7720 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-28 12:05:14.379  7720  7720 D WifiDirectBR: stopServiceTest : false
07-28 12:05:14.379  7692  7692 W VideoCapabilities: Unsupported mime video/mp43
,07-28 12:05:14.379  7720  7720 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-28 12:05:14.399   906  1541 I ActivityManager: Killing 5698:com.android.providers.calendar/u0a51 (adj 15): emptyCount ##41
,07-28 12:05:14.399  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-28 12:05:14.399  1306  1306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-28 12:05:14.399  7692  7692 W VideoCapabilities: Unsupported mime video/sorenson
,07-28 12:05:14.399   906  1243 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:14.399  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-28 12:05:14.399   906  3064 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-28 12:05:14.399  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:05:14.399  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
,07-28 12:05:14.399  1306  1306 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:05:14.399  1306  2807 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:05:14.419   906  1663 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:14.419  7692  7692 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-28 12:05:14.419  7109  7109 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:05:14.429  7109  7109 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-28 12:05:14.439   906  1709 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:14.439  6639  6639 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:05:14.439  6639  6639 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:05:14.439  6639  6639 D SecurityLogAgent: StateMachine : Current State = 1
,07-28 12:05:14.439  6639  6639 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:05:14.449  7692  7692 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-28 12:05:14.459  1306  1306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 12:05:14.459   906  3355 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-28 12:05:14.459   906  3355 D ActivityManager: caller:android.app.ApplicationThreadProxy@3aacc625, r.packageName :com.android.settings
,07-28 12:05:14.459  1306  1306 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:05:14.459  1306  1306 D BluetoothNotiBroadcastReceiver: onReceive
,07-28 12:05:14.459   906   923 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,07-28 12:05:14.459   906   923 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:14.459   906   923 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:14.459   906   923 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:14.459   906   923 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:14.499  7746  7746 E Zygote  : MountEmulatedStorage()
07-28 12:05:14.499  7746  7746 E Zygote  : v2
07-28 12:05:14.499  7746  7746 I libpersona: KNOX_SDCARD checking this for 1002
07-28 12:05:14.499  7746  7746 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:14.509   906   923 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7746 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,07-28 12:05:14.519   906  3064 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,07-28 12:05:14.529  7746  7746 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:05:14.529  7746  7746 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:05:14.529  7746  7746 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:05:14.529   906   924 I ActivityManager: Killing 6782:com.sec.enterprise.knox.cloudmdm.smdms/u0a201 (adj 15): emptyCount ##41
,07-28 12:05:14.559  7746  7746 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:05:14.559  7746  7746 D ActivityThread: Added TimaKeyStore provider
,07-28 12:05:14.569  7746  7746 D ResourcesManager: creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,07-28 12:05:14.569  7746  7746 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,07-28 12:05:14.569  7746  7746 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-28 12:05:14.589  7746  7746 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,07-28 12:05:14.619  7746  7746 D BtSettings.ProfileConfig: Adding GattService
,07-28 12:05:14.619  7746  7746 D BtSettings.ProfileConfig: Adding HeadsetService
07-28 12:05:14.619  7746  7746 D BtSettings.ProfileConfig: Adding A2dpService
07-28 12:05:14.619  7746  7746 D BtSettings.ProfileConfig: Adding HidService
07-28 12:05:14.619  7746  7746 D BtSettings.ProfileConfig: Adding HealthService
,07-28 12:05:14.619  7746  7746 D BtSettings.ProfileConfig: Adding PanService
07-28 12:05:14.619  7746  7746 D BtSettings.ProfileConfig: Adding BluetoothMapService
07-28 12:05:14.619  7746  7746 D BtSettings.ProfileConfig: Adding SapService
07-28 12:05:14.619  7746  7746 D BtSettings.ProfileConfig: Adding HeadsetClientService
,07-28 12:05:14.619  7746  7746 D BtSettings.ProfileConfig: Adding A2dpSinkService
07-28 12:05:14.619  7746  7746 D BtSettings.ProfileConfig: Adding SapClientService
07-28 12:05:14.619  7746  7746 D BtSettings.ProfileConfig: Adding HidDevService
07-28 12:05:14.619  7746  7746 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,07-28 12:05:14.619   906  1465 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
07-28 12:05:14.619   906  1465 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:14.619   906  1465 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:14.619   906  1465 D SettingsProvider: selectionArgs: false
07-28 12:05:14.619   906  1465 D SettingsProvider: selectionArgs: 1002
07-28 12:05:14.619   906  1465 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:14.619   906  1465 D SettingsProvider: ret = -1
,07-28 12:05:14.619   906  1541 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
07-28 12:05:14.619   906  1541 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:14.619   906  1541 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:14.619   906  1541 D SettingsProvider: selectionArgs: false
07-28 12:05:14.619   906  1541 D SettingsProvider: selectionArgs: 1002
,07-28 12:05:14.619   906  1541 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:14.619   906  1541 D SettingsProvider: ret = -1
07-28 12:05:14.619   906  1462 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
07-28 12:05:14.619   906  1462 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,07-28 12:05:14.619   906  1462 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:14.619   906  1462 D SettingsProvider: selectionArgs: false
07-28 12:05:14.619   906  1462 D SettingsProvider: selectionArgs: 1002
07-28 12:05:14.619   906  1462 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:14.619   906  1462 D SettingsProvider: ret = -1
,07-28 12:05:14.619   906  1413 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
07-28 12:05:14.619   906  1413 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:14.619   906  1413 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:14.619   906  1413 D SettingsProvider: selectionArgs: false
07-28 12:05:14.619   906  1413 D SettingsProvider: selectionArgs: 1002
07-28 12:05:14.619   906  1413 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:14.619   906  1413 D SettingsProvider: ret = -1
,07-28 12:05:14.619   906  1243 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
07-28 12:05:14.619   906  1243 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:14.619   906  1243 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:14.619   906  1243 D SettingsProvider: selectionArgs: false
07-28 12:05:14.619   906  1243 D SettingsProvider: selectionArgs: 1002
07-28 12:05:14.619   906  1243 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:14.619   906  1243 D SettingsProvider: ret = -1
07-28 12:05:14.619   906  1560 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
07-28 12:05:14.619   906  1560 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:14.619   906  1560 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:14.619   906  1560 D SettingsProvider: selectionArgs: false
07-28 12:05:14.619   906  1560 D SettingsProvider: selectionArgs: 1002
07-28 12:05:14.629   906  1560 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:14.629   906  1560 D SettingsProvider: ret = -1
,07-28 12:05:14.629   906  1143 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
07-28 12:05:14.629   906  1143 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:14.629   906  1143 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:14.629   906  1143 D SettingsProvider: selectionArgs: false
07-28 12:05:14.629   906  1143 D SettingsProvider: selectionArgs: 1002
07-28 12:05:14.629   906  1143 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:14.629   906  1143 D SettingsProvider: ret = -1
07-28 12:05:14.629   906  3064 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
07-28 12:05:14.629   906  3064 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:14.629   906  3064 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:14.629   906  3064 D SettingsProvider: selectionArgs: false
07-28 12:05:14.629   906  3064 D SettingsProvider: selectionArgs: 1002
07-28 12:05:14.629   906  3064 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:14.629   906  3064 D SettingsProvider: ret = -1
07-28 12:05:14.629   906   924 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:05:14.629   906   924 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:14.629   906   924 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:14.629   906   924 D SettingsProvider: selectionArgs: false
07-28 12:05:14.629   906   924 D SettingsProvider: selectionArgs: 1002
,07-28 12:05:14.629   906   924 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:14.629   906   924 D SettingsProvider: ret = -1
07-28 12:05:14.629   906   923 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:05:14.629   906   923 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:14.629   906   923 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:14.629   906   923 D SettingsProvider: selectionArgs: false
07-28 12:05:14.629   906   923 D SettingsProvider: selectionArgs: 1002
07-28 12:05:14.629   906   923 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:14.629   906   923 D SettingsProvider: ret = -1
07-28 12:05:14.629   906  3331 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,07-28 12:05:14.629   906  3331 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:14.629   906  3331 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:14.629   906  3331 D SettingsProvider: selectionArgs: false
07-28 12:05:14.629   906  3331 D SettingsProvider: selectionArgs: 1002
07-28 12:05:14.629   906  3331 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:14.629   906  3331 D SettingsProvider: ret = -1
07-28 12:05:14.629   906  1361 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
07-28 12:05:14.629   906  1361 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:14.629   906  1361 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,07-28 12:05:14.629   906  1361 D SettingsProvider: selectionArgs: false
07-28 12:05:14.629   906  1361 D SettingsProvider: selectionArgs: 1002
07-28 12:05:14.629   906  1361 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:14.629   906  1361 D SettingsProvider: ret = -1
,07-28 12:05:14.639   906  1663 I ActivityManager: Killing 6805:com.google.android.partnersetup/u0a19 (adj 15): emptyCount ##41
,07-28 12:05:14.639  1922  1922 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-28 12:05:14.639   906  1541 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-28 12:05:14.639   906  1541 D ActivityManager: caller:android.app.ApplicationThreadProxy@3d089fa1, r.packageName :com.google.android.gms
,07-28 12:05:14.649  1922  7763 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-28 12:05:14.649  1922  1922 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-28 12:05:14.659  7109  7109 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-28 12:05:14.669   906  1663 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:14.669  6639  6639 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:05:14.669  6639  6639 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,07-28 12:05:14.669  6639  6639 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:05:14.669  6639  6639 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:05:14.669   906  1462 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-28 12:05:14.669   906  1462 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4302, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-28 12:05:14.669   906  1462 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-28 12:05:14.669   906  1462 D BatteryService: stay LED for fully charged
07-28 12:05:14.669   906   906 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-28 12:05:14.669   906  1541 D ActivityManager: caller:android.app.ApplicationThreadProxy@34dee852, r.packageName :com.google.android.gms
,07-28 12:05:14.679  1922  7763 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-28 12:05:14.679   906   906 I MotionRecognitionService: Plugged
,07-28 12:05:14.679   906   906 I MotionRecognitionService: setPowerConnected  = true
07-28 12:05:14.679  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-28 12:05:14.679  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-28 12:05:14.679  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-28 12:05:14.679  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-28 12:05:14.679  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-28 12:05:14.679  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:05:14.689  6859  6859 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,07-28 12:05:14.689  6859  6859 I PCWCLIENTTRACE_PushUtil: sales region : global
07-28 12:05:14.689  6859  6859 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-28 12:05:14.689  6859  6859 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:05:14.689  6859  6859 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,07-28 12:05:14.699   906  1560 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,07-28 12:05:14.699   906  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:14.699   906  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:14.699   906  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:14.699   906  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:14.739  7766  7766 E Zygote  : MountEmulatedStorage()
07-28 12:05:14.739  7766  7766 E Zygote  : v2
07-28 12:05:14.739  7766  7766 I libpersona: KNOX_SDCARD checking this for 10144
07-28 12:05:14.739  7766  7766 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:14.739   906  1560 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7766 uid=10144 gids={50144, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:05:14.749  7766  7766 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-28 12:05:14.749  7766  7766 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:05:14.749  7766  7766 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-28 12:05:14.769  7766  7766 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:05:14.769  7766  7766 D ActivityThread: Added TimaKeyStore provider
,07-28 12:05:14.779  7766  7766 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-28 12:05:14.859  7766  7766 I MusicStore: Database version: 108
,07-28 12:05:14.879   906  1560 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:05:14.929  7766  7766 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,07-28 12:05:14.929  7766  7766 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-28 12:05:14.929  7766  7766 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-28 12:05:14.959  7766  7766 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-28 12:05:15.009  7766  7766 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-28 12:05:15.009  7766  7766 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@db4e784: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,07-28 12:05:15.009  7766  7766 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-28 12:05:15.009  7766  7766 D AndroidMusic: GMSCore installation verified
,07-28 12:05:15.019   906  1435 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:05:15.019  7766  7766 I ConfigStore: Config Database version: 1
,07-28 12:05:15.069   266   549 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-28 12:05:15.069   266   549 W Vold    : Returning OperationFailed - no handler for errno 0
,07-28 12:05:15.069  7766  7766 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-28 12:05:15.069   266   549 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-28 12:05:15.069   266   549 W Vold    : Returning OperationFailed - no handler for errno 0
07-28 12:05:15.069  7766  7766 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-28 12:05:15.069   266   549 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-28 12:05:15.069   266   549 W Vold    : Returning OperationFailed - no handler for errno 0
,07-28 12:05:15.069  7766  7766 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-28 12:05:15.079   906  1560 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-28 12:05:15.079   906  1560 D ActivityManager: caller:android.app.ApplicationThreadProxy@16636f4d, r.packageName :com.google.android.music
,07-28 12:05:15.089   906   924 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:05:15.109   906  1361 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-28 12:05:15.109   906  3064 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-28 12:05:15.109   906  3331 I AudioService: getStreamVolume 3 index 0
,07-28 12:05:15.119  7766  7766 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,07-28 12:05:15.119  7766  7766 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,07-28 12:05:15.149   906   924 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:05:15.149   906  3064 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:05:15.149   906  3355 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:05:15.159   906  1243 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-28 12:05:15.169   906  1560 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,07-28 12:05:15.169   906  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:15.169   906  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:15.169   906  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:15.169   906  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:15.209   906  1560 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7801 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:05:15.219  7801  7801 E Zygote  : MountEmulatedStorage()
07-28 12:05:15.219  7801  7801 I libpersona: KNOX_SDCARD checking this for 10004
07-28 12:05:15.219  7801  7801 E Zygote  : v2
07-28 12:05:15.219  7801  7801 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:15.229  7801  7801 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-28 12:05:15.229  7801  7801 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:05:15.229  7801  7801 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:05:15.239   906   924 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,07-28 12:05:15.259  7766  7766 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,07-28 12:05:15.259  7801  7801 D TimaKeyStoreProvider: TimaSignature is unavailable
07-28 12:05:15.259  7801  7801 D ActivityThread: Added TimaKeyStore provider
,07-28 12:05:15.269   906  3064 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:05:15.279  7801  7801 D ResourcesManager: creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,07-28 12:05:15.319   906  1541 I ActivityManager: Killing 6823:com.samsung.groupcast/u0a20 (adj 15): emptyCount ##41
,07-28 12:05:15.319   906  1663 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,07-28 12:05:15.319   906  1663 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:15.319   906  1663 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:15.319   906  1663 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:15.319   906  1663 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:15.359  7820  7820 E Zygote  : MountEmulatedStorage()
07-28 12:05:15.359  7820  7820 E Zygote  : v2
07-28 12:05:15.359  7820  7820 I libpersona: KNOX_SDCARD checking this for 1000
07-28 12:05:15.359  7820  7820 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:15.369   906  1663 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7820 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-28 12:05:15.379  7820  7820 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:05:15.379  7820  7820 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:05:15.379  7820  7820 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:05:15.399  7820  7820 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:05:15.399  7820  7820 D ActivityThread: Added TimaKeyStore provider
,07-28 12:05:15.419  7820  7820 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,07-28 12:05:15.439  7820  7820 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,07-28 12:05:15.459  7820  7820 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,07-28 12:05:15.569  7820  7820 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,07-28 12:05:15.569  7820  7820 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,07-28 12:05:15.579  7820  7820 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:05:15.579  7820  7820 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-28 12:05:15.639   906  1462 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,07-28 12:05:15.639   906  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:15.639   906  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:15.639   906  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:15.639   906  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:15.679   906  1462 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7836 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:05:15.679  7836  7836 E Zygote  : MountEmulatedStorage()
,07-28 12:05:15.679  7836  7836 E Zygote  : v2
07-28 12:05:15.679  7836  7836 I libpersona: KNOX_SDCARD checking this for 10014
07-28 12:05:15.679  7836  7836 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:15.699  7836  7836 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:05:15.699  7836  7836 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:05:15.699  7836  7836 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-28 12:05:15.719  7836  7836 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:05:15.719  7836  7836 D ActivityThread: Added TimaKeyStore provider
,07-28 12:05:15.729  7836  7836 D ResourcesManager: creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,07-28 12:05:15.779   906  1435 I ActivityManager: Killing 6842:com.sec.android.service.health/u0a21 (adj 15): emptyCount ##41
,07-28 12:05:15.789  7836  7836 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,07-28 12:05:15.789  7836  7836 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,07-28 12:05:15.809  7836  7836 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,07-28 12:05:15.809   906  1462 I ActivityManager: Killing 6715:com.android.defcontainer/u0a7 (adj 15): emptyCount ##41
,07-28 12:05:15.809  4019  4019 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-28 12:05:15.809  4019  4019 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1469700315822
,07-28 12:05:15.809  4019  4019 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,07-28 12:05:15.809   906  1361 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:15.809   906  3064 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:15.819  4019  4019 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,07-28 12:05:15.819  4019  4019 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
07-28 12:05:15.819   906  1143 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.pinboard, hostingType: broadcast
,07-28 12:05:15.819   906  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:15.819   906  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:15.819   906  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:15.819   906  1143 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:15.859  7851  7851 E Zygote  : MountEmulatedStorage()
,07-28 12:05:15.859  7851  7851 E Zygote  : v2
07-28 12:05:15.859  7851  7851 I libpersona: KNOX_SDCARD checking this for 10036
07-28 12:05:15.859  7851  7851 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:15.869  7851  7851 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-28 12:05:15.869  7851  7851 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:05:15.869   906  1143 I ActivityManager: Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7851 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-28 12:05:15.869  7851  7851 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:05:15.889  7851  7851 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:05:15.889  7851  7851 D ActivityThread: Added TimaKeyStore provider
,07-28 12:05:15.899  7851  7851 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,07-28 12:05:15.909  7851  7851 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-28 12:05:15.909  7851  7851 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-28 12:05:15.929  7851  7851 E Minikin : addFont failed to create font /system/fonts/SamsungSans-light.ttf
,07-28 12:05:15.929  7508  7576 I WifiManager: packageName : com.test.thalitest
,07-28 12:05:15.929   906  1663 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-28 12:05:15.929   906  1663 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-28 12:05:15.929   906  1663 D SecContentProvider2: mCursor = null
,07-28 12:05:15.929   906  1663 D WifiService: setWifiEnabled: true pid=7508, uid=10079
07-28 12:05:15.929   906  1663 W ActivityManager: Permission Denial: getCurrentUser() from pid=7508, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,07-28 12:05:15.929   906  1663 W WifiService: Failed getting userId using ActivityManagerNative
07-28 12:05:15.929   906  1663 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7508, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-28 12:05:15.929   906  1663 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-28 12:05:15.929   906  1663 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-28 12:05:15.929   906  1663 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-28 12:05:15.929   906  1663 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-28 12:05:15.929   906  1663 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
07-28 12:05:15.929   906  1663 D SettingsProvider: name = wifi_on
,07-28 12:05:15.939   906  1148 E WifiHW  : ##################### set firmware type 0 #####################
,07-28 12:05:15.939   294  1067 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
07-28 12:05:15.939   294  1067 I WifiHW  : module is semco
07-28 12:05:15.939   294  1067 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-28 12:05:15.939   294  1067 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-28 12:05:15.939   294  1067 E WifiHW  : TEMP_FAILURE_RETRY complete
07-28 12:05:15.939   294  1067 D SoftapController: Softap fwReload - Ok
,07-28 12:05:15.939   294  1067 D CommandListener: Setting iface cfg
07-28 12:05:15.939   294  1067 D CommandListener: Trying to bring down wlan0
,07-28 12:05:15.939   294  1067 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:05:15.949   906  1148 E WifiHW  : supplicant_name : p2p_supplicant
,07-28 12:05:15.949   906  1361 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:15.949   906   906 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:05:15.949  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:05:15.949  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,07-28 12:05:15.949  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:15.959  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:15.959   906  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-28 12:05:15.959  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:05:15.959  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
07-28 12:05:15.959  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:05:15.959   906  1148 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
07-28 12:05:15.959  1195  1583 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-28 12:05:15.959  1195  1195 D HotspotTile: onReceive : 2, 0
07-28 12:05:15.959  1306  1306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:05:15.959   906  1541 I ActivityManager: Killing 6900:com.sec.spp.push/u0a43 (adj 15): emptyCount ##41
,07-28 12:05:15.969   906  1462 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
,07-28 12:05:15.969   906  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:15.969   906  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:15.969   906  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:15.969   906  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:15.979  7868  7868 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-28 12:05:15.979  7868  7868 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-28 12:05:15.979  7868  7868 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,07-28 12:05:15.979  7868  7868 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-28 12:05:15.989   376   376 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7868
07-28 12:05:15.989   376   376 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
07-28 12:05:15.989  7868  7868 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-28 12:05:15.989  7868  7868 I wpa_supplicant: ssSupport state is = 1
,07-28 12:05:15.989  7868  7868 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,07-28 12:05:15.989  7868  7868 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-28 12:05:15.989   376   376 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7868
07-28 12:05:15.989   376   376 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,07-28 12:05:16.019  7869  7869 E Zygote  : MountEmulatedStorage()
07-28 12:05:16.019  7869  7869 I libpersona: KNOX_SDCARD checking this for 10042
07-28 12:05:16.019  7869  7869 E Zygote  : v2
07-28 12:05:16.019  7869  7869 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:16.029   906  1462 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7869 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,07-28 12:05:16.039   339   339 I art     : Explicit concurrent mark sweep GC freed 8726(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 8.143ms total 26.808ms
,07-28 12:05:16.059   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 278us total 9.983ms
,07-28 12:05:16.059  7869  7869 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:05:16.059  7869  7869 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:05:16.059  7869  7869 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:05:16.069   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 279us total 10.280ms
,07-28 12:05:16.079  7869  7869 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:05:16.079  7869  7869 D ActivityThread: Added TimaKeyStore provider
,07-28 12:05:16.099  7869  7869 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,07-28 12:05:16.119  7869  7869 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,07-28 12:05:16.119   906  1462 I ActivityManager: Killing 6916:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): emptyCount ##41
,07-28 12:05:16.129   906  1560 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,07-28 12:05:16.129   906  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:16.129   906  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:16.129   906  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:16.129   906  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:16.129  3586  7893 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
07-28 12:05:16.129   906  1435 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:16.129   906  1663 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:16.129  3586  7893 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,07-28 12:05:16.129  3586  7893 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,07-28 12:05:16.139  3586  7893 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,07-28 12:05:16.139  3586  7893 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,07-28 12:05:16.169  7894  7894 E Zygote  : MountEmulatedStorage()
07-28 12:05:16.169  7894  7894 E Zygote  : v2
07-28 12:05:16.169  7894  7894 I libpersona: KNOX_SDCARD checking this for 10043
07-28 12:05:16.169  7894  7894 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:16.169   906  1560 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7894 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:05:16.199  7894  7894 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-28 12:05:16.199  7894  7894 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:05:16.199  7894  7894 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,07-28 12:05:16.219  7894  7894 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:05:16.219  7894  7894 D ActivityThread: Added TimaKeyStore provider
,07-28 12:05:16.229  7894  7894 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,07-28 12:05:16.259  7894  7894 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,07-28 12:05:16.259  7894  7894 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,07-28 12:05:16.259  7894  7894 D SPPClientService: PushLog.txt file is not deleted.
,07-28 12:05:16.259  7894  7894 D SPPClientService: PushLog.txt file is not deleted.
07-28 12:05:16.269  7894  7894 D SPPClientService: ============PushLog. stop!
,07-28 12:05:16.269  7894  7894 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,07-28 12:05:16.269   376   376 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,07-28 12:05:16.269  6566  6566 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,07-28 12:05:16.269  6566  6566 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,07-28 12:05:16.269  6566  6566 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
07-28 12:05:16.269   906  1541 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
07-28 12:05:16.269   906  1541 D ActivityManager: caller:android.app.ApplicationThreadProxy@3fce982d, r.packageName :com.sec.spp.push
,07-28 12:05:16.279  6566  6566 I SA      : [SLFUCHKMGR] constructor called
,07-28 12:05:16.279  6566  6566 I SA      : [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
07-28 12:05:16.279  6566  6566 I SA      : [OR] == isSIMCardReady false ==
,07-28 12:05:16.279  6566  6566 I SA      : [SCU] == networkStateCheck == false
07-28 12:05:16.279  6566  6566 I SA      : [OR] onReceive END
,07-28 12:05:16.279  7894  7911 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,07-28 12:05:16.289   906   924 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,07-28 12:05:16.289   906   924 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:16.289   906   924 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:16.289   906   924 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:16.289   906   924 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:16.329  7913  7913 E Zygote  : MountEmulatedStorage()
07-28 12:05:16.329  7913  7913 E Zygote  : v2
07-28 12:05:16.329  7913  7913 I libpersona: KNOX_SDCARD checking this for 10074
07-28 12:05:16.329  7913  7913 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:16.339   906   924 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7913 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,07-28 12:05:16.339  7913  7913 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:05:16.339  7913  7913 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:05:16.339  7913  7913 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:05:16.339   906   924 I ActivityManager: Killing 5621:com.android.mms/u0a55 (adj 15): emptyCount ##41
,07-28 12:05:16.359  7913  7913 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:05:16.359  7913  7913 D ActivityThread: Added TimaKeyStore provider
,07-28 12:05:16.369  7913  7913 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,07-28 12:05:16.389   301   301 E SMD     : DCD ON
,07-28 12:05:16.389   906  1243 D CountryDetector: No listener is left
,07-28 12:05:16.419  7913  7913 I sCloudBackupApp: sCloudBackupApp Version Info : 3.13.7.KK_APP
,07-28 12:05:16.419  7913  7913 I SCloudBackupReceiver: Other Intent
,07-28 12:05:16.429  7234  7234 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,07-28 12:05:16.429  7234  7234 I KnoxUsageLogPro: premStatus:2
,07-28 12:05:16.439  7234  7234 I KnoxUsageLogPro: isEulaShown : false
,07-28 12:05:16.439  7234  7234 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-28 12:05:16.439   906  3355 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,07-28 12:05:16.439   906  3355 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:16.439   906  3355 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:16.439   906  3355 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:16.439   906  3355 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:16.479  7933  7933 E Zygote  : MountEmulatedStorage()
07-28 12:05:16.479  7933  7933 E Zygote  : v2
07-28 12:05:16.479  7933  7933 I libpersona: KNOX_SDCARD checking this for 10104
07-28 12:05:16.479  7933  7933 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:16.489   906  3355 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7933 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:05:16.489   906  3355 I ActivityManager: Killing 6944:com.sec.android.app.soundalive/u0a64 (adj 15): emptyCount ##41
,07-28 12:05:16.499  7933  7933 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:05:16.499  7933  7933 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:05:16.499  7933  7933 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,07-28 12:05:16.519  7868  7868 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,07-28 12:05:16.529  7933  7933 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:05:16.539  7933  7933 D ActivityThread: Added TimaKeyStore provider
,07-28 12:05:16.549  7933  7933 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,07-28 12:05:16.569  7868  7868 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-28 12:05:16.569  7868  7868 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-28 12:05:16.569   376   376 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7868
07-28 12:05:16.569   376   376 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-28 12:05:16.569  7868  7868 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-28 12:05:16.569  7868  7868 I wpa_supplicant: ssSupport state is = 1
,07-28 12:05:16.569  7868  7868 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:05:16.569  7868  7868 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-28 12:05:16.569  7868  7868 E wpa_supplicant: SIM READ ERROR
07-28 12:05:16.569  7868  7868 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:05:16.569  7868  7868 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-28 12:05:16.569  7868  7868 E wpa_supplicant: SIM READ ERROR
07-28 12:05:16.569  7868  7868 I wpa_supplicant: Blacklist: Clear (all) 
,07-28 12:05:16.569  7868  7868 I wpa_supplicant: wpa_default_ap_write_once
07-28 12:05:16.569  7868  7868 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-28 12:05:16.569  7868  7868 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:05:16.569  7868  7868 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
07-28 12:05:16.569  7868  7868 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:05:16.569  7868  7868 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-28 12:05:16.569  7868  7868 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-28 12:05:16.619   906  1435 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,07-28 12:05:16.619   906  1435 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:16.619   906  1435 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:16.619   906  1435 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:16.619   906  1435 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:16.659  7949  7949 E Zygote  : MountEmulatedStorage()
,07-28 12:05:16.659  7949  7949 E Zygote  : v2
07-28 12:05:16.659  7949  7949 I libpersona: KNOX_SDCARD checking this for 10146
07-28 12:05:16.659  7949  7949 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:16.669   906  1435 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7949 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:05:16.669   906  1435 I ActivityManager: Killing 6964:com.samsung.android.app.assistantmenu/1000 (adj 15): emptyCount ##41
,07-28 12:05:16.679  7949  7949 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:05:16.679  7949  7949 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:05:16.679  7949  7949 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-28 12:05:16.699  7949  7949 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:05:16.699  7949  7949 D ActivityThread: Added TimaKeyStore provider
,07-28 12:05:16.709  7949  7949 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,07-28 12:05:16.889   266   549 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
07-28 12:05:16.889   266   549 W Vold    : Returning OperationFailed - no handler for errno 0
,07-28 12:05:16.899  7949  7967 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
07-28 12:05:16.899   266   549 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
07-28 12:05:16.899   266   549 W Vold    : Returning OperationFailed - no handler for errno 0
07-28 12:05:16.899  7949  7967 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,07-28 12:05:16.929   266   549 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
07-28 12:05:16.929   266   549 W Vold    : Returning OperationFailed - no handler for errno 0
,07-28 12:05:16.929  7949  7970 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,07-28 12:05:16.929   266   549 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
07-28 12:05:16.929   266   549 W Vold    : Returning OperationFailed - no handler for errno 0
,07-28 12:05:16.929  7949  7970 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,07-28 12:05:17.069  7949  7949 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,07-28 12:05:17.069  7949  7949 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,07-28 12:05:17.089  7949  7949 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2889-2892)
,07-28 12:05:17.089  7949  7949 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-28 12:05:17.089  7949  7949 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e032b25}
,07-28 12:05:17.089  7949  7949 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-28 12:05:17.089  7949  7949 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-28 12:05:17.119  7949  7949 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-28 12:05:17.119  7949  7949 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-28 12:05:17.119  7949  7949 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-28 12:05:17.379   906  1151 E Tethering: No numeric data
,07-28 12:05:17.379   906  1151 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-28 12:05:17.379  1195  1195 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-28 12:05:17.379   906  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:05:17.379   906  1145 V NetworkStats: performPollLocked(flags=0x1)
07-28 12:05:17.379  1195  1195 D HotspotTile: updateTetherState():false, false
,07-28 12:05:17.379   906  1145 D NetworkStatsFactory: UpdateStatsForKnox
,07-28 12:05:17.379   906  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:17.389   906  1145 V NetworkStats: performPollLocked() took 3ms
07-28 12:05:17.389   906  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:05:17.389   906  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:05:17.389   906  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:05:17.389  7949  7949 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-28 12:05:17.399  7949  7949 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
,07-28 12:05:17.399  7949  7949 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,07-28 12:05:17.399  7949  7949 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-28 12:05:17.399  7949  7949 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-28 12:05:17.399  7949  7949 I Adreno-EGL: Build Date: 11/19/14 Wed
07-28 12:05:17.399  7949  7949 I Adreno-EGL: Local Branch: mybranch5813579
07-28 12:05:17.399  7949  7949 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-28 12:05:17.399  7949  7949 I Adreno-EGL: Local Patches: NONE
07-28 12:05:17.399  7949  7949 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-28 12:05:17.409  7868  7868 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,07-28 12:05:17.429  7868  7868 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-28 12:05:17.429  7868  7868 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-28 12:05:17.429  7868  7868 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-28 12:05:17.429   376   376 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7868
07-28 12:05:17.429   376   376 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-28 12:05:17.429  7868  7868 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-28 12:05:17.429  7868  7868 I wpa_supplicant: ssSupport state is = 1
07-28 12:05:17.429  7868  7868 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-28 12:05:17.429  7868  7868 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-28 12:05:17.429   376   376 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7868
07-28 12:05:17.429   376   376 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-28 12:05:17.429  7868  7868 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-28 12:05:17.429  7868  7868 I wpa_supplicant: ssSupport state is = 1
07-28 12:05:17.429  7868  7868 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:05:17.429  7868  7868 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-28 12:05:17.429  7868  7868 E wpa_supplicant: SIM READ ERROR
07-28 12:05:17.429  7868  7868 I wpa_supplicant: wpa_default_ap_write_once
07-28 12:05:17.429  7868  7868 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-28 12:05:17.429  7868  7868 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-28 12:05:17.449  7868  7868 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
07-28 12:05:17.449  7868  7868 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,07-28 12:05:17.469  7868  7868 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
07-28 12:05:17.469  7868  7868 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,07-28 12:05:17.469   906  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,07-28 12:05:17.469   906  1148 D WifiNative-HAL: callSECApiBoolean - ID [21]
07-28 12:05:17.469  7868  7868 I wpa_supplicant: HOTSPOT20_ENABLE called
07-28 12:05:17.469  7868  7868 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:05:17.469  7868  7868 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-28 12:05:17.469  7868  7868 E wpa_supplicant: SIM READ ERROR
07-28 12:05:17.469  7868  7868 I wpa_supplicant: Blacklist: Clear (all) 
,07-28 12:05:17.479  7949  8001 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-28 12:05:17.489  7949  7949 I NSApplication: Starting up...
,07-28 12:05:17.499  7868  7868 I wpa_supplicant: Skip scan - bUseNetwork false
,07-28 12:05:17.499   906  1148 D WifiNative-HAL: callSECApiInt - ID [210]
,07-28 12:05:17.499   906   906 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:05:17.499  7508  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:05:17.499   906  1152 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
07-28 12:05:17.499  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:17.499  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:17.499  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:17.499  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:17.499  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:05:17.499  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:17.499  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:17.499  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:05:17.499  7508  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:17.499  7508  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:05:17.499  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:05:17.499  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-28 12:05:17.499  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:17.499  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:17.509   906  1148 D WifiConfigStore: Loading config and enabling all networks 
,07-28 12:05:17.509  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:17.509  7508  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:05:17.509  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:17.509  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:17.509  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:17.509  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:17.509  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:17.509  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:17.509  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:17.509  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:17.509  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:17.509  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:05:17.509  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:17.509  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:17.509  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:05:17.509  7508  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:05:17.509  7508  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:05:17.509  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:05:17.509  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
07-28 12:05:17.509  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:05:17.509  1195  1583 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-28 12:05:17.509  1195  1195 D HotspotTile: onReceive : 3, 0
07-28 12:05:17.509  1306  1306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:05:17.509   906  3331 I ActivityManager: Killing 7001:com.google.android.apps.docs/u0a112 (adj 15): emptyCount ##41
07-28 12:05:17.509   906  1148 E WifiConfigStore: Not a HS20
,07-28 12:05:17.529   906  1148 E WifiConfigStore: Not a HS20
,07-28 12:05:17.539   906  1148 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-28 12:05:17.539   906  1148 D WifiNative-HAL: callSECApiInt - ID [65]
,07-28 12:05:17.549   906  1148 D WifiNative-HAL: callSECApiBoolean - ID [13]
,07-28 12:05:17.549  7868  7868 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-28 12:05:17.549  7868  7868 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,07-28 12:05:17.549  7868  7868 I wpa_supplicant: reset timer : RESET_TIMER 0
07-28 12:05:17.549  7868  7868 I wpa_supplicant: P2P: Current p2p state = IDLE
07-28 12:05:17.549  7868  7868 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
07-28 12:05:17.549  7868  7868 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
07-28 12:05:17.549  7868  7868 I wpa_supplicant: First Scan Start
,07-28 12:05:17.549  7868  7868 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
07-28 12:05:17.549   906  1148 D WifiNative-HAL: Setting external_sim to 1
07-28 12:05:17.549   906  1148 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 12:05:17.549   906  1148 I WifiNative-HAL: startHal
07-28 12:05:17.549   906  1148 E wifi    : getStaticLongField sWifiHalHandle 0x932e186c
07-28 12:05:17.549   906  1148 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x601a46
07-28 12:05:17.549   906  1148 I WifiNative-HAL: Could not start hal
,07-28 12:05:17.549  7692  7692 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:05:17.569   906  1148 E native  : do suspend true
,07-28 12:05:17.569   906  1147 D WifiP2pService: P2pDisabledState{ what=131203 }
,07-28 12:05:17.569   906  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,07-28 12:05:17.569   906   906 D WifiScanningService: SCAN_AVAILABLE : 3
07-28 12:05:17.569   906   906 D RttService: SCAN_AVAILABLE : 3
07-28 12:05:17.569   906  1165 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.569   906  1165 I WifiNative-HAL: startHal
07-28 12:05:17.569   906  1165 E wifi    : getStaticLongField sWifiHalHandle 0x9ca3299c
07-28 12:05:17.569   906  1165 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x301a0e
07-28 12:05:17.569   906  1165 I WifiNative-HAL: Could not start hal
07-28 12:05:17.569   906  1165 E WifiScanningService: could not start HAL
,07-28 12:05:17.569   906  1166 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:17.579   294  1067 D CommandListener: Setting iface cfg
07-28 12:05:17.579   294  1067 D CommandListener: Trying to bring up p2p0
07-28 12:05:17.579   906  1147 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-28 12:05:17.579   906  1147 D WifiP2pService: P2pEnablingState
07-28 12:05:17.579   906  1148 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
07-28 12:05:17.579   906  1148 D WifiNative-HAL: callSECStringApiVoid - ID [215]
07-28 12:05:17.579   906  1148 E WifiNative-HAL: invaild command id : 215
,07-28 12:05:17.579   906  1147 D WifiP2pService: P2pEnablingState{ what=147457 }
07-28 12:05:17.579   906  1147 D WifiP2pService: P2p socket connection successful
07-28 12:05:17.579   906  1147 D WifiP2pService: P2pEnabledState
,07-28 12:05:17.579   906   906 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
07-28 12:05:17.579   906  1031 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-28 12:05:17.579   906  1031 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-28 12:05:17.579   906  1031 D WifiDisplayController: disconnect
07-28 12:05:17.579   906  1031 D WifiDisplayController: updateConnection
07-28 12:05:17.579   906  1031 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-28 12:05:17.579   906  1031 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-28 12:05:17.579   906  1147 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-28 12:05:17.579  1195  1195 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
07-28 12:05:17.579   906  1361 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-28 12:05:17.579  1195  1195 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
07-28 12:05:17.579   906  1150 E ConnectivityService: updateNetworkInfo()
07-28 12:05:17.579   906  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,07-28 12:05:17.579   906  1031 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:17.579   906  1031 D WifiDisplayAdapter: onP2pDisconnected
07-28 12:05:17.579   906  1031 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-28 12:05:17.579   906  1031 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-28 12:05:17.599  7868  7868 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-28 12:05:17.609   906  1147 D WifiNative-HAL: p2pGetDeviceAddress
,07-28 12:05:17.609   906  1147 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:de:28:a3
07-28 12:05:17.609   906  1147 D WifiP2pService: DeviceAddress: ea:28:a3
,07-28 12:05:17.609   906  1031 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
07-28 12:05:17.609   906  1031 D WifiDisplayController:  deviceAddress: ea:50:8b:de:28:a3
07-28 12:05:17.609   906  1031 D WifiDisplayController:  primary type: 10-0050F204-5
07-28 12:05:17.609   906  1031 D WifiDisplayController:  secondary type: null
07-28 12:05:17.609   906  1031 D WifiDisplayController:  wps: 0
07-28 12:05:17.609   906  1031 D WifiDisplayController:  grpcapab: 0
07-28 12:05:17.609   906  1031 D WifiDisplayController:  devcapab: 0
07-28 12:05:17.609   906  1031 D WifiDisplayController:  status: 3
07-28 12:05:17.609   906  1031 D WifiDisplayController:  wfdInfo: null
07-28 12:05:17.609   906  1031 D WifiDisplayController:  groupownerAddress: null
07-28 12:05:17.609   906  1031 D WifiDisplayController:  GOdeviceName: null
07-28 12:05:17.609   906  1031 D WifiDisplayController:  interfaceAddress: 
07-28 12:05:17.609   906  1031 D WifiDisplayController:  SConnectInfo : null
,07-28 12:05:17.609   906  3331 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,07-28 12:05:17.609   906  3331 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:17.609   906  3331 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:17.609   906  3331 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:17.609   906  3331 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:17.629  7868  7868 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-28 12:05:17.649   906  1147 D WifiP2pService: sending p2p persistent groups changed broadcast
,07-28 12:05:17.649   906  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:05:17.649   906  1148 D SecContentProvider2: mCursor = null
,07-28 12:05:17.689  8021  8021 E Zygote  : MountEmulatedStorage()
,07-28 12:05:17.689  8021  8021 E Zygote  : v2
07-28 12:05:17.689  8021  8021 I libpersona: KNOX_SDCARD checking this for 10158
07-28 12:05:17.689  8021  8021 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:17.699   906  3331 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=8021 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,07-28 12:05:17.699   906  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:05:17.699   906  1148 D SecContentProvider2: mCursor = null
07-28 12:05:17.699   906  1147 D WifiP2pService: InactiveState
,07-28 12:05:17.699   906  1147 D WifiP2pService: InactiveState{ what=143376 }
07-28 12:05:17.699   906  1147 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-28 12:05:17.709  7868  7868 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-28 12:05:17.709  8021  8021 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:05:17.709  8021  8021 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:05:17.709   906  1147 D WifiP2pService: InactiveState{ what=143376 }
07-28 12:05:17.709  8021  8021 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:05:17.709   906  1147 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-28 12:05:17.729  8021  8021 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:05:17.729  8021  8021 D ActivityThread: Added TimaKeyStore provider
,07-28 12:05:17.739  8021  8021 D ResourcesManager: creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,07-28 12:05:17.739  8021  8021 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-28 12:05:17.739  8021  8021 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-28 12:05:17.739  8021  8021 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-28 12:05:17.749  8021  8021 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:05:17.759  8021  8021 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,07-28 12:05:17.759  8021  8021 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,07-28 12:05:17.759   906  1709 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
,07-28 12:05:17.759   906  1709 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:17.759   906  1709 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:17.759   906  1709 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:17.759   906  1709 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:17.799  8036  8036 E Zygote  : MountEmulatedStorage()
07-28 12:05:17.799  8036  8036 E Zygote  : v2
07-28 12:05:17.799  8036  8036 I libpersona: KNOX_SDCARD checking this for 10186
07-28 12:05:17.799  8036  8036 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:17.809   906  1709 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=8036 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,07-28 12:05:17.809   906  1709 I ActivityManager: Killing 7034:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##41
,07-28 12:05:17.819  8036  8036 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:05:17.819  8036  8036 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:05:17.819  8036  8036 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:05:17.839  8036  8036 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:05:17.839  8036  8036 D ActivityThread: Added TimaKeyStore provider
,07-28 12:05:17.849  8036  8036 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-28 12:05:17.859  8036  8036 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,07-28 12:05:17.859  8036  8036 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:05:17.859  8036  8036 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,07-28 12:05:17.859  8036  8036 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-28 12:05:17.859  8036  8036 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-28 12:05:17.889   906   985 W ProcessCpuTracker: Skipping unknown process pid 8016
,07-28 12:05:17.889   906   985 W ProcessCpuTracker: Skipping unknown process pid 8019
,07-28 12:05:17.939   906  1243 D RCPManagerService: exchangeData() failure , invalid userId
,07-28 12:05:17.969   906  1462 D RCPManagerService: exchangeData() failure , invalid userId
,07-28 12:05:17.979   906  3355 D RCPManagerService: exchangeData() failure , invalid userId
,07-28 12:05:17.999   906  1462 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,07-28 12:05:17.999   906  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:18.009   906  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:18.009   906  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:18.009   906  1462 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:18.019   906  1709 D RCPManagerService: exchangeData() failure , invalid userId
,07-28 12:05:18.029   906  3355 D RCPManagerService: exchangeData() failure , invalid userId
,07-28 12:05:18.039  8062  8062 E Zygote  : MountEmulatedStorage()
07-28 12:05:18.039  8062  8062 E Zygote  : v2
07-28 12:05:18.049  8062  8062 I libpersona: KNOX_SDCARD checking this for 10092
07-28 12:05:18.049  8062  8062 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:18.049   906  1462 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8062 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,07-28 12:05:18.069  8062  8062 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:05:18.069  8062  8062 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:05:18.069   906  1435 D RCPManagerService: exchangeData() failure , invalid userId
,07-28 12:05:18.069  8062  8062 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-28 12:05:18.069   906  3064 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:18.079  6639  6639 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:05:18.079  6639  6639 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:05:18.079  6639  6639 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:05:18.079  6639  6639 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:05:18.079   906  1243 I ActivityManager: Killing 7056:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): emptyCount ##41
,07-28 12:05:18.079   906  1560 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
07-28 12:05:18.079   906  3355 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:18.079   906  1663 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:18.079   906  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:18.079   906  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:18.079   906  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:18.079   906  1560 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:18.109  8062  8062 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:05:18.109  8062  8062 D ActivityThread: Added TimaKeyStore provider
,07-28 12:05:18.129  8081  8081 E Zygote  : MountEmulatedStorage()
07-28 12:05:18.129  8081  8081 E Zygote  : v2
07-28 12:05:18.129  8081  8081 I libpersona: KNOX_SDCARD checking this for 10200
07-28 12:05:18.129  8081  8081 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:18.139   906  1560 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8081 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:05:18.149  8081  8081 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:05:18.149  8081  8081 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:05:18.149  8081  8081 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-28 12:05:18.149   906   924 I ActivityManager: Killing 7071:com.samsung.helphub/1000 (adj 15): emptyCount ##41
,07-28 12:05:18.179  8081  8081 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:05:18.179  8081  8081 D ActivityThread: Added TimaKeyStore provider
,07-28 12:05:18.249   906  3064 I art     : Explicit concurrent mark sweep GC freed 40819(2MB) AllocSpace objects, 3(48KB) LOS objects, 30% free, 37MB/53MB, paused 1.331ms total 90.805ms
,07-28 12:05:18.259  8081  8081 D ResourcesManager: creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,07-28 12:05:18.259  8062  8062 D ResourcesManager: creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,07-28 12:05:18.279  8062  8062 D BadgeProvider: onCreate
,07-28 12:05:18.279  8062  8062 D BadgeProvider: DatabaseHelper
,07-28 12:05:18.279   906  1435 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,07-28 12:05:18.279   906   923 I ActivityManager: Killing 7127:com.samsung.android.snote:provider/u0a168 (adj 15): emptyCount ##41
,07-28 12:05:18.289   906  1663 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-28 12:05:18.289   906  1663 D ActivityManager: caller:android.app.ApplicationThreadProxy@15a86e1a, r.packageName :com.google.android.gms
,07-28 12:05:18.289  8062  8072 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
07-28 12:05:18.289  4431  4431 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-28 12:05:18.289  4431  5403 I iu.UploadsManager: num queued entries: 0
,07-28 12:05:18.299  4431  5403 I iu.UploadsManager: num updated entries: 0
,07-28 12:05:18.299  4431  5403 I iu.SyncManager: NEXT; no task
,07-28 12:05:18.309  8062  8072 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
07-28 12:05:18.309  8062  8072 D BadgeProvider: sendNotify, [notify] : null
,07-28 12:05:18.309  8062  8072 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
07-28 12:05:18.309  8062  8072 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-28 12:05:18.309  1444  1444 D Launcher.Model: reloadBadges entered.
07-28 12:05:18.309  8062  8072 D BadgeProvider: update, [UpdateCount] : 1
,07-28 12:05:18.319  7109  7109 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-28 12:05:18.319   906  1541 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:18.319  6639  6639 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:05:18.319  6639  6639 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:05:18.319  6639  6639 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:05:18.319  6639  6639 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:05:18.329  7868  7868 I wpa_supplicant: nl80211: Received scan results (26 BSSes)
07-28 12:05:18.329  7868  7868 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-28 12:05:18.329  7868  7868 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
07-28 12:05:18.329  7868  7868 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
07-28 12:05:18.329  7868  7868 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=5 BSSID=00.00.00 SSID=4E47373030
,07-28 12:05:18.339   906  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:05:18.339   906  1148 D SecContentProvider2: mCursor = null
,07-28 12:05:18.339  7109  7109 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-28 12:05:18.349   906  1465 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:18.349  6639  6639 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:05:18.349  6639  6639 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:05:18.349  6639  6639 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:05:18.349  6639  6639 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:05:18.349  7720  7720 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-28 12:05:18.359  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-28 12:05:18.359  1306  1306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-28 12:05:18.359   906  1361 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:18.359  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-28 12:05:18.359   906  3331 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:18.359  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:05:18.359  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:05:18.359  1306  1306 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:05:18.359  1306  2807 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:05:18.359  7219  7219 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-28 12:05:18.369  7720  7720 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-28 12:05:18.369  7720  7720 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
07-28 12:05:18.369  7720  7720 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
07-28 12:05:18.369  7720  7720 D WifiDirectBR: stopServiceTest : false
,07-28 12:05:18.399  7868  7868 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
07-28 12:05:18.399  7868  7868 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=6 BSSID=00.00.00 SSID=4E47373030
,07-28 12:05:18.399  7868  7868 I wpa_supplicant: Associated with F4.99.3E
07-28 12:05:18.399  7868  7868 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
07-28 12:05:18.399  7868  7868 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=7 BSSID=F4.99.3E SSID=4E47373030
,07-28 12:05:18.399   906  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:05:18.399   906  1148 D SecContentProvider2: mCursor = null
,07-28 12:05:18.409   906  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:05:18.409   906  1148 D SecContentProvider2: mCursor = null
,07-28 12:05:18.419  7868  7868 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,07-28 12:05:18.419  7868  7868 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
07-28 12:05:18.419  7868  7868 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=8 BSSID=F4.99.3E SSID=4E47373030
,07-28 12:05:18.419  7868  7868 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:05:18.419  7868  7868 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
07-28 12:05:18.419  7868  7868 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=1 id_str=]
07-28 12:05:18.419  7868  7868 I wpa_supplicant: Blacklist: Clear (temp) 
,07-28 12:05:18.419  7868  7868 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=9 BSSID=F4.99.3E SSID=4E47373030
,07-28 12:05:18.419   906  1148 D WifiNative-HAL: callSECApiVoid - ID [50]
,07-28 12:05:18.419  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:05:18.419  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:05:18.429   906  1148 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
07-28 12:05:18.429   906  1150 D ConnectivityService: Got NetworkAgent Messenger
07-28 12:05:18.429   906  1150 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
07-28 12:05:18.429   906  1150 E ConnectivityService: updateNetworkInfo()
07-28 12:05:18.429   906  1150 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:05:18.429   906  1150 D ConnectivityService: NetworkAgent connected
07-28 12:05:18.429   906  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:05:18.429  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-28 12:05:18.429  1306  1306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-28 12:05:18.429   906  1435 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:18.429  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-28 12:05:18.429   906  1361 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:18.429  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:05:18.429  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:05:18.429  1306  1306 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:05:18.429  1306  2807 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:05:18.439   906  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:05:18.439   906  1709 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:18.439  7109  7109 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:05:18.449   294  1067 D CommandListener: Setting iface cfg
,07-28 12:05:18.449   906  1148 E WifiStateMachine: Start Dhcp Watchdog 2
,07-28 12:05:18.449   906  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:05:18.449   906  1148 D SecContentProvider2: mCursor = null
,07-28 12:05:18.449  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:05:18.449  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:05:18.459   906  1150 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,07-28 12:05:18.539   906  1148 E native  : do suspend false
,07-28 12:05:18.539   906  1147 D WifiP2pService: InactiveState{ what=143375 }
,07-28 12:05:18.539   906  1147 D WifiP2pService: P2pEnabledState{ what=143375 }
07-28 12:05:18.539   906  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:05:18.539   906  1148 D SecContentProvider2: mCursor = null
,07-28 12:05:18.759  8110  8110 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-28 12:05:18.759  8110  8110 I dhcpcd  : version 5.5.6 starting
,07-28 12:05:18.759  8110  8110 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-28 12:05:18.819  8110  8110 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-28 12:05:18.819  8110  8110 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
07-28 12:05:18.819  8110  8110 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
07-28 12:05:18.819  8110  8110 I dhcpcd  : bssid match
07-28 12:05:18.829  8110  8110 I dhcpcd  : wlan0: rebinding lease of 192.168.1.122
,07-28 12:05:18.849  8110  8110 I dhcpcd  : wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,07-28 12:05:18.859  8110  8110 I dhcpcd  : wlan0: leased 192.168.1.122 for 172800 seconds
,07-28 12:05:18.859   906  1150 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,07-28 12:05:18.939  7508  7576 I WifiManager: packageName : com.test.thalitest
,07-28 12:05:18.939   906   924 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-28 12:05:18.939   906   924 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-28 12:05:18.939   906   924 D SecContentProvider2: mCursor = null
,07-28 12:05:18.939   906   924 D WifiService: setWifiEnabled: false pid=7508, uid=10079
,07-28 12:05:18.939   906   924 D SettingsProvider: name = wifi_on
,07-28 12:05:18.949   906  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:05:18.959   906  1148 E native  : do suspend true
,07-28 12:05:18.969   906  1147 D WifiP2pService: InactiveState{ what=143375 }
,07-28 12:05:18.969   906  1147 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-28 12:05:18.969  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:05:18.969  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:05:18.969   294  1067 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:05:19.029   906  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:05:19.029   906  1150 E ConnectivityService: updateNetworkInfo()
,07-28 12:05:19.029   906   906 I WifiTrafficPoller: evaluateTrafficStatsPolling
07-28 12:05:19.029   906  1150 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-28 12:05:19.029   906  1150 E ConnectivityService: updateNetworkInfo()
,07-28 12:05:19.029   906  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
,07-28 12:05:19.029   906  1150 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,07-28 12:05:19.029   294  1067 E Netd    : no such netId 503
,07-28 12:05:19.029  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:05:19.039  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:05:19.039   906  1150 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '77 network destroy 503' failed with '400 77 destroyNetwork() failed (Machine is not on the network)'
,07-28 12:05:19.039   906  1150 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
,07-28 12:05:19.039   906  1150 D ConnectivityService: calling update connectivity
07-28 12:05:19.039   906  1150 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
,07-28 12:05:19.039   906  1150 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,07-28 12:05:19.049   906  8099 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:19.049   906  8099 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,07-28 12:05:19.049   906  1148 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-28 12:05:19.049   906  1147 D WifiP2pService: InactiveState{ what=131204 }
,07-28 12:05:19.049   906  1147 D WifiP2pService: P2pEnabledState{ what=131204 }
07-28 12:05:19.049   906   906 D WifiScanningService: SCAN_AVAILABLE : 1
07-28 12:05:19.049   906   906 D RttService: SCAN_AVAILABLE : 1
07-28 12:05:19.049   906  1166 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:05:19.059   906  1165 D WifiScanningService: DefaultState got{ when=-4ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:05:19.059   906  1147 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,07-28 12:05:19.059  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-28 12:05:19.059  1306  1306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-28 12:05:19.059   906  3331 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:19.059  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-28 12:05:19.059   906  1031 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:19.059   906  1031 D WifiDisplayAdapter: onP2pDisconnected
07-28 12:05:19.059   906  1031 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-28 12:05:19.059   906  1031 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-28 12:05:19.059   906  3064 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:19.059  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:05:19.059  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:05:19.059  1306  1306 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-28 12:05:19.059  1306  2807 V NearbySettings: MountReceiver.mPrefHandler - 7002
07-28 12:05:19.059   906  1150 E ConnectivityService: updateNetworkInfo()
07-28 12:05:19.059   906  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,07-28 12:05:19.059   906  1031 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
07-28 12:05:19.059   906  1031 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-28 12:05:19.059   906  1031 D WifiDisplayController: disconnect
07-28 12:05:19.059   906  1031 D WifiDisplayController: updateConnection
07-28 12:05:19.059   906  1031 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-28 12:05:19.059   906  1031 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-28 12:05:19.059   906   906 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,07-28 12:05:19.069  1195  1195 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,07-28 12:05:19.069   906  1147 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
07-28 12:05:19.069   906   923 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-28 12:05:19.069  1195  1195 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-28 12:05:19.069   906  1150 E ConnectivityService: updateNetworkInfo()
07-28 12:05:19.069   906  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
07-28 12:05:19.069   906  1031 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-28 12:05:19.069   906  1031 D WifiDisplayAdapter: onP2pDisconnected
07-28 12:05:19.069   906  1031 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-28 12:05:19.069   906  1031 D IpRemoteDisplayController: WfdBridgeServer is already null
07-28 12:05:19.069   906  1147 D WifiP2pService: P2pDisablingState
07-28 12:05:19.069   906  1147 D WifiP2pService: P2pDisablingState{ what=147458 }
,07-28 12:05:19.069   906  1147 D WifiP2pService: p2p socket connection lost
07-28 12:05:19.069   906  1147 D WifiP2pService: P2pDisabledState
,07-28 12:05:19.069   906  3355 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:19.079   906  1148 E native  : do suspend true
,07-28 12:05:19.079  7109  7109 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:05:19.079  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-28 12:05:19.079  1306  1306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-28 12:05:19.089   906  1560 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:19.089  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-28 12:05:19.089   906  1435 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-28 12:05:19.089  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:05:19.089  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:05:19.089  1306  1306 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-28 12:05:19.089  1306  2807 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:05:19.089   906  1147 D WifiP2pService: P2pDisabledState{ what=143375 }
07-28 12:05:19.089   906  1147 D WifiP2pService: DefaultState{ what=143375 }
,07-28 12:05:19.089  7219  7219 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-28 12:05:19.089  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:05:19.089  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-28 12:05:19.089   294  1067 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:05:19.099   906   906 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-28 12:05:19.099  7868  7868 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
07-28 12:05:19.099  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:05:19.099  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:05:19.099   906   906 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:05:19.099  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:05:19.099  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-28 12:05:19.099  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:19.099  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:19.099  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:19.099  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:19.099  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:19.099  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:19.099  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:19.099  1195  1195 D StatusBar.NetworkController: applyOpen
,07-28 12:05:19.099  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:05:19.099  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
07-28 12:05:19.099   906  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-28 12:05:19.099  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:05:19.099  1195  1583 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-28 12:05:19.099  1195  1195 D HotspotTile: onReceive : 0, 0
07-28 12:05:19.099  7508  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:19.099  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:19.099  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:19.099  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:19.099  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:05:19.099  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:05:19.099  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:19.099  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:19.099  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:05:19.099  7508  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:19.099  7508  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:05:19.099  7720  7720 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-28 12:05:19.099  7508  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:19.099  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:19.099  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:19.099  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:19.099  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:05:19.099  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:05:19.099  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:19.099  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:19.099  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:05:19.099  7508  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:19.099  7508  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:05:19.099  1306  1306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
07-28 12:05:19.109   906  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:05:19.109   906  1148 D SecContentProvider2: mCursor = null
,07-28 12:05:19.109  7720  7720 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
07-28 12:05:19.109  7720  7720 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-28 12:05:19.109  7720  7720 D WifiDirectBR: stopServiceTest : false
,07-28 12:05:19.109  7720  7720 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-28 12:05:19.109  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-28 12:05:19.109  1306  1306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-28 12:05:19.109   906   924 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:19.109  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-28 12:05:19.119   906  3331 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-28 12:05:19.119  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:05:19.119  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:05:19.119  1306  1306 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:05:19.119  1306  2807 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:05:19.119   906  1541 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:19.119  7109  7109 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:05:19.129  7109  7109 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-28 12:05:19.139   906  1462 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:19.139  6639  6639 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:05:19.139  6639  6639 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:05:19.139  6639  6639 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:05:19.139  6639  6639 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:05:19.169  7868  7868 I wpa_supplicant: Blacklist: Clear (all) 
,07-28 12:05:19.179  7868  7868 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-28 12:05:19.179  7868  7868 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
07-28 12:05:19.179  7868  7868 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
07-28 12:05:19.179  7868  7868 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=0 BSSID=F4.99.3E SSID=4E47373030
07-28 12:05:19.179  7868  7868 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-28 12:05:19.219  7868  7868 I wpa_supplicant: Blacklist: Clear (all) 
,07-28 12:05:19.339   906  1151 D Tethering: InitialState.processMessage what=4
,07-28 12:05:19.339   906  1151 E Tethering: No numeric data
07-28 12:05:19.339  7868  7868 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-28 12:05:19.339   906  1151 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-28 12:05:19.339   906  1145 V NetworkStats: performPollLocked(flags=0x1)
07-28 12:05:19.339   906  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:05:19.339  1195  1195 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-28 12:05:19.339  1195  1195 D HotspotTile: updateTetherState():false, false
,07-28 12:05:19.339   906  1145 D NetworkStatsFactory: UpdateStatsForKnox
07-28 12:05:19.339   906  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:19.339   906  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:05:19.339   906  1145 V NetworkStats: performPollLocked() took 4ms
07-28 12:05:19.339   906  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:05:19.339   906  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:05:19.389   301   301 E SMD     : DCD ON
,07-28 12:05:19.439   906  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
07-28 12:05:19.439   906  1148 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-28 12:05:19.439   906   906 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:05:19.439  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:05:19.439  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-28 12:05:19.439  1306  1306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
07-28 12:05:19.439  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:05:19.439  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
07-28 12:05:19.439  7692  7692 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:19.439  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:05:19.439  1195  1195 D HotspotTile: onReceive : 1, 0
07-28 12:05:19.439  1195  1583 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-28 12:05:19.439  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:19.439   906  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-28 12:05:19.439  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:19.439  1922  2408 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:05:19.449  7109  7109 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-28 12:05:19.449   906   924 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:19.449  6639  6639 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:05:19.449  6639  6639 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:05:19.449  6639  6639 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:05:19.449  6639  6639 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:05:19.649   906  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,07-28 12:05:19.689   906  1413 I ActivityManager: Killing 7147:com.sec.kidsplat.installer/u0a189 (adj 15): emptyCount ##41
,07-28 12:05:20.029   906  3135 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-28 12:05:20.119   906  1361 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-28 12:05:20.119   906  1361 D ActivityManager: caller:android.app.ApplicationThreadProxy@3e189004, r.packageName :com.google.android.music
,07-28 12:05:20.139   906  3331 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:05:20.149   906  1435 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:05:20.149   906  1663 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:05:20.159   906  3355 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-28 12:05:20.159   906  3355 D ActivityManager: caller:android.app.ApplicationThreadProxy@1d51017a, r.packageName :com.google.android.music
,07-28 12:05:20.189  1922  1922 D WearableService: callingUid 10015, callindPid: 1922
,07-28 12:05:20.199   906   923 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:05:20.229  7766  7766 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,07-28 12:05:20.229  7766  8167 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,07-28 12:05:20.299  7766  8162 I MusicLeanback: Conditions not met for autocaching.
,07-28 12:05:20.299  7766  8162 I MusicLeanback: Stop autocaching.
,07-28 12:05:21.919   906  3355 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,07-28 12:05:21.929  7949  7968 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,07-28 12:05:21.949  7508  7576 D BluetoothAdapter: enable()
,07-28 12:05:21.949   906  1560 W ActivityManager: Permission Denial: getCurrentUser() from pid=7508, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,07-28 12:05:21.949   906  1560 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-28 12:05:21.949   906  1560 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7508, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-28 12:05:21.949   906  1560 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-28 12:05:21.949   906  1560 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
07-28 12:05:21.949   906  1560 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
07-28 12:05:21.949   906  1560 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-28 12:05:21.949   906  1560 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,07-28 12:05:21.949   906  1560 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-28 12:05:21.949   906  1560 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:05:21.949   906  1560 D SettingsProvider: name = bluetooth_on
,07-28 12:05:21.959   906  1030 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:05:21.959   906  1030 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:05:21.959   906  1030 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,07-28 12:05:21.989  7746  7746 D BluetoothAdapterState: make
,07-28 12:05:21.989  7746  7746 I bluedroid: init
,07-28 12:05:21.989  7746  7746 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-28 12:05:21.989  7746  7746 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-28 12:05:21.999  7746  7746 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,07-28 12:05:21.999  7746  7746 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,07-28 12:05:21.999  7746  7746 E bt-btif : btif_fetch_local_ble_random_bdaddr
07-28 12:05:21.999  7746  7746 I bluedroid: get_profile_interface socket
07-28 12:05:21.999  7746  7746 I bluedroid: get_profile_interface map_client
,07-28 12:05:21.999  7746  7746 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,07-28 12:05:21.999   906  1413 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-28 12:05:22.009  7746  7757 I bluedroid: config_hci_snoop_log
,07-28 12:05:22.009   906  1030 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 14 receivers.
,07-28 12:05:22.009   906  1030 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:05:22.009   906  1030 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:05:22.009   906  1030 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,07-28 12:05:22.009  7746  8183 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,07-28 12:05:22.019  7746  8183 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
,07-28 12:05:22.019  7746  8183 E BluetoothServiceJni: populateRssiValuesNative
07-28 12:05:22.019  7746  8183 I bluedroid: getModelRssiValues
07-28 12:05:22.019  7746  8183 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,07-28 12:05:22.019  7746  8183 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-28 12:05:22.019   906   906 D SettingsProvider: name = bluetooth_name
,07-28 12:05:22.019  7746  8183 D BluetoothAdapterProperties: Name is: Note3-1
,07-28 12:05:22.019  7746  8180 I BluetoothAdapterState: Entering OffState
07-28 12:05:22.019  7746  8180 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,07-28 12:05:22.019  7746  8180 D BluetoothAdapterProperties: Setting state to 11
07-28 12:05:22.019  7746  8180 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,07-28 12:05:22.019  7746  8180 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-28 12:05:22.019  7746  8180 D BluetoothAdapterService: updateAdapterState state is 11
,07-28 12:05:22.029   906   906 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:05:22.029  1724  1724 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-28 12:05:22.029   906   906 I InputMethodManagerService: [BT Setting State] State =11
,07-28 12:05:22.029  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-28 12:05:22.029  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:22.029  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:05:22.039  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:22.039   906  3064 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:05:22.039  1195  1583 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-28 12:05:22.039   906  1361 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-28 12:05:22.039  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-28 12:05:22.039  1306  1306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:05:22.039   906  3355 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-28 12:05:22.039   906  3355 D ActivityManager: caller:android.app.ApplicationThreadProxy@b591ed0, r.packageName :com.google.android.gms
,07-28 12:05:22.049  7666  7666 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:05:22.049  7746  8180 D BluetoothAdapterService: Autoconnection is available 
07-28 12:05:22.049  7746  8180 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,07-28 12:05:22.049  7746  8180 D BluetoothSecureManager: getInstant: null
,07-28 12:05:22.049  7746  8180 D BluetoothSecureManager: calling getMethod for getService
,07-28 12:05:22.049  7746  8180 D BluetoothSecureManager: calling getService
,07-28 12:05:22.049  7746  8180 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@19385ac7
,07-28 12:05:22.049   906  1709 D BluetoothSecureManagerService: isSecureModeEnabled
07-28 12:05:22.049   906  1709 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,07-28 12:05:22.059  7746  8180 D BtConfig.SecureMode: isSecureModeOn:false
,07-28 12:05:22.059  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-28 12:05:22.059  7746  8180 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
,07-28 12:05:22.059  1306  1306 D BluetoothNotiBroadcastReceiver: onReceive
07-28 12:05:22.059  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-28 12:05:22.059  7746  8180 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
07-28 12:05:22.059  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-28 12:05:22.069  7746  8180 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
07-28 12:05:22.069  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-28 12:05:22.069  7746  8180 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,07-28 12:05:22.069  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-28 12:05:22.069  7746  8180 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
07-28 12:05:22.069  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-28 12:05:22.069  7746  8180 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,07-28 12:05:22.069  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-28 12:05:22.069  7746  8180 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
07-28 12:05:22.069  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-28 12:05:22.069  7746  8180 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,07-28 12:05:22.069  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:05:22.069  7746  8180 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,07-28 12:05:22.069  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:05:22.069  7746  8180 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:05:22.069  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,07-28 12:05:22.069  7746  8180 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
07-28 12:05:22.069  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-28 12:05:22.069  7746  8180 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,07-28 12:05:22.079  7746  8180 D BluetoothBondStateMachine: make
,07-28 12:05:22.089  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,07-28 12:05:22.089  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-28 12:05:22.089  7746  8180 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
07-28 12:05:22.089  7746  8194 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-28 12:05:22.089   906  1413 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:05:22.099   906  1413 D ActivityManager: caller:android.app.ApplicationThreadProxy@3792d9ce, r.packageName :com.android.bluetooth
,07-28 12:05:22.099  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
07-28 12:05:22.099  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-28 12:05:22.099  7746  8180 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,07-28 12:05:22.099   906  3331 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:05:22.099  7746  7746 I BtGatt.JNI: classInitNative(L890): classInitNative: Success!
07-28 12:05:22.099   906  3331 D ActivityManager: caller:android.app.ApplicationThreadProxy@267957fc, r.packageName :com.android.bluetooth
,07-28 12:05:22.099  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,07-28 12:05:22.099  7746  7746 D BtGatt.DebugUtils: handleDebugAction() action=null
07-28 12:05:22.099  7746  7746 D BtGatt.GattService: Received start request. Starting profile...
07-28 12:05:22.099  7746  7746 D BtGatt.GattService: start()
07-28 12:05:22.099  7746  7746 I bluedroid: get_profile_interface gatt
,07-28 12:05:22.099  7746  7746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21849d2e
07-28 12:05:22.099  7746  7746 D BtGatt.AdvertiseManager: advertise manager created
,07-28 12:05:22.109  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-28 12:05:22.109  7746  8180 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,07-28 12:05:22.109   906  3064 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:05:22.109   906  3064 D ActivityManager: caller:android.app.ApplicationThreadProxy@6c4da, r.packageName :com.android.bluetooth
,07-28 12:05:22.109  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,07-28 12:05:22.109  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-28 12:05:22.109  7746  8180 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-28 12:05:22.109   906  1560 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:05:22.109   906  1560 D ActivityManager: caller:android.app.ApplicationThreadProxy@2f01f7e8, r.packageName :com.android.bluetooth
,07-28 12:05:22.109  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,07-28 12:05:22.109  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-28 12:05:22.109  7746  8180 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-28 12:05:22.109   906   924 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:05:22.109   906   924 D ActivityManager: caller:android.app.ApplicationThreadProxy@3b9c54a6, r.packageName :com.android.bluetooth
,07-28 12:05:22.119  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
07-28 12:05:22.119  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-28 12:05:22.119  7746  8180 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,07-28 12:05:22.119   906  1709 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:05:22.119   906  1709 D ActivityManager: caller:android.app.ApplicationThreadProxy@181f7283, r.packageName :com.android.bluetooth
,07-28 12:05:22.119  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
07-28 12:05:22.119  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:05:22.119  7746  8180 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,07-28 12:05:22.119   906  1663 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:05:22.119   906  1663 D ActivityManager: caller:android.app.ApplicationThreadProxy@208adc39, r.packageName :com.android.bluetooth
,07-28 12:05:22.119  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,07-28 12:05:22.119  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-28 12:05:22.119  7746  8180 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,07-28 12:05:22.119  7746  7746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21849d2e
,07-28 12:05:22.119   906  1435 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:05:22.119   906  1435 D ActivityManager: caller:android.app.ApplicationThreadProxy@35cb3df, r.packageName :com.android.bluetooth
,07-28 12:05:22.129  7746  7746 D HeadsetService: Received start request. Starting profile...
07-28 12:05:22.129  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,07-28 12:05:22.129  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-28 12:05:22.129  7746  8180 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,07-28 12:05:22.129  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:05:22.129  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:05:22.129  7746  8180 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:05:22.129  7746  7746 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-28 12:05:22.129  7746  7746 D HeadsetStateMachine: make
07-28 12:05:22.129  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
07-28 12:05:22.129  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-28 12:05:22.129  7746  8180 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,07-28 12:05:22.129  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
07-28 12:05:22.129  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-28 12:05:22.129  7746  8180 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,07-28 12:05:22.129  7746  8180 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,07-28 12:05:22.139  7746  7746 E HeadsetStateMachine: # of Max HF connection is 2
,07-28 12:05:22.139   906  1465 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,07-28 12:05:22.139   906  3064 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
,07-28 12:05:22.149  7746  7746 I bluedroid: get_profile_interface handsfree
,07-28 12:05:22.149  7746  7746 I DualScoManager: Instantiating Dual Sco Manager
07-28 12:05:22.149  7746  7746 I DualScoManager: Set HeadsetServiceHelper
,07-28 12:05:22.149  7746  7746 D BluetoothAtMessage: createCMTIContentObservers
,07-28 12:05:22.149   906  1709 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,07-28 12:05:22.159   906  1709 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:22.159   906  1709 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:22.159   906  1709 D SettingsProvider: selectionArgs: false
,07-28 12:05:22.159   906  1709 D SettingsProvider: selectionArgs: 1002
07-28 12:05:22.159   906  1709 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:22.159   906  1709 D SettingsProvider: ret = -1
,07-28 12:05:22.159  7746  7746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21849d2e
,07-28 12:05:22.159  7746  8198 D HeadsetStateMachine: Enter Disconnected: -2
,07-28 12:05:22.159  7746  8198 E HeadsetStateMachine: set to mRemoteBrsf = 0
,07-28 12:05:22.159  7746  7746 D A2dpService: Received start request. Starting profile...
,07-28 12:05:22.159  7746  7746 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-28 12:05:22.159  7746  7746 V Avrcp   : make
07-28 12:05:22.159  7746  7746 V Avrcp   : Avrcp
,07-28 12:05:22.159  7746  7746 I bluedroid: get_profile_interface avrcp
,07-28 12:05:22.169  7746  8198 D HeadsetStateMachine: map size, before remove : 0
07-28 12:05:22.169  7746  8198 D HeadsetStateMachine: map size, after remove: 0
07-28 12:05:22.169  7746  8198 D HeadsetStateMachine: mNextConnectingDevice : null
07-28 12:05:22.169  1922  1922 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-28 12:05:22.169  7746  7746 V Avrcp   : start
,07-28 12:05:22.169  7746  7746 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-28 12:05:22.179  7746  7746 V Avrcp   : ++registerMediaPlayers++
,07-28 12:05:22.179  7746  7746 I Avrcp   : No of Audio players :: 2
07-28 12:05:22.179  1922  1922 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
07-28 12:05:22.179  7746  7746 I Avrcp   : App Package name is com.google.android.music
,07-28 12:05:22.179  7746  7746 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-28 12:05:22.179  7746  7746 I Avrcp   : App pkg name is Google Play Music
,07-28 12:05:22.179  7746  7746 I Avrcp   : Name::Google Play Music
07-28 12:05:22.179  7746  7746 V Avrcp   : MediaPlayerInfo: mPlayerId=1
,07-28 12:05:22.179  7746  7746 I Avrcp   : App Package name is com.sec.android.app.music
07-28 12:05:22.179  7746  7746 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,07-28 12:05:22.189  7746  7746 I Avrcp   : App pkg name is Music
,07-28 12:05:22.189  7746  7746 I Avrcp   : Name::Music
07-28 12:05:22.189  7746  7746 V Avrcp   : MediaPlayerInfo: mPlayerId=2
,07-28 12:05:22.189  7746  7746 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,07-28 12:05:22.189  7746  7746 I Avrcp   : No of Video players :: 1
07-28 12:05:22.189  7746  7746 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
,07-28 12:05:22.189  7746  7746 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,07-28 12:05:22.189  7746  7746 I Avrcp   : Video App pkg name is Video Player
,07-28 12:05:22.189  7746  7746 I Avrcp   : Name::Video Player
07-28 12:05:22.189  7746  7746 V Avrcp   : MediaPlayerInfo: mPlayerId=3
07-28 12:05:22.189  7746  7746 I Avrcp   : Add tempPlayer
07-28 12:05:22.189  7746  7746 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-28 12:05:22.189  7746  7746 I Avrcp   : Total no of players: 4
,07-28 12:05:22.189  7746  7746 V Avrcp   : swapping the samsung player with 1st player
07-28 12:05:22.189  7746  7746 I Avrcp   :  Updating now playing list upon AVRCP Start
07-28 12:05:22.189  7746  8200 V Avrcp   : handleMessage, msg=207
,07-28 12:05:22.189  7746  8200 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,07-28 12:05:22.189  7746  7746 I BluetoothA2dpServiceJni: classInitNative: succeeds
,07-28 12:05:22.189  7746  7746 D A2dpStateMachine: make
,07-28 12:05:22.199  7746  7746 I bluedroid: get_profile_interface a2dp
,07-28 12:05:22.199  7746  8203 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-28 12:05:22.199  7746  7746 E bt-btif : warning : media task started media_task_refcnt 1 
,07-28 12:05:22.199  7746  8200 D BluetoothMediaBrowser: no now playing list
07-28 12:05:22.199  7746  8200 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,07-28 12:05:22.199  7746  8200 D Avrcp   :  checkNowPlayingList start
07-28 12:05:22.199  7746  7746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21849d2e
07-28 12:05:22.199  7746  8202 D A2dpStateMachine: Enter Disconnected: -2
,07-28 12:05:22.199  7746  7746 I BluetoothHidServiceJni: classInitNative: succeeds
,07-28 12:05:22.199  7746  7746 D HidService: Received start request. Starting profile...
,07-28 12:05:22.199  7746  7746 I bluedroid: get_profile_interface hidhost
07-28 12:05:22.199  7746  7746 D HidService: setHidService(): set to: null
07-28 12:05:22.199  7746  7746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21849d2e
,07-28 12:05:22.199  7746  7746 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-28 12:05:22.209  7746  7746 D HealthService: Received start request. Starting profile...
,07-28 12:05:22.209  7746  7746 I bluedroid: get_profile_interface health
,07-28 12:05:22.209  7746  7746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21849d2e
,07-28 12:05:22.209  7746  7746 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-28 12:05:22.209  7746  7746 D PanService: Received start request. Starting profile...
,07-28 12:05:22.209  7746  7746 D BluetoothPanServiceJni: initializeNative(L110): pan
07-28 12:05:22.209  7746  7746 I bluedroid: get_profile_interface pan
,07-28 12:05:22.209  7746  7746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21849d2e
,07-28 12:05:22.209  7746  7746 D BluetoothMapService: Received start request. Starting profile...
,07-28 12:05:22.239  7746  7746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21849d2e
,07-28 12:05:22.239  7746  7746 E BluetoothAdapterService(562339118): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,07-28 12:05:22.239  7746  7746 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,07-28 12:05:22.239  7746  7746 D SapService: Received start request. Starting profile...
,07-28 12:05:22.239  7746  7746 D BluetoothSAPServiceJni: initializeNative(L209): sap
07-28 12:05:22.239  7746  7746 I bluedroid: get_profile_interface sap
07-28 12:05:22.239  7746  7746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21849d2e
,07-28 12:05:22.239  7746  7746 D HeadsetStateMachine: Try to query the phonestate on bind
,07-28 12:05:22.239  1406  3090 I Telecom : BluetoothPhoneService: queryPhoneState
07-28 12:05:22.239  1406  1406 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,07-28 12:05:22.239  7746  7746 D HeadsetStateMachine: Proxy object connected
,07-28 12:05:22.239  7746  7746 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,07-28 12:05:22.239  7746  7746 D HeadsetPhoneState: sendDeviceDataStateChanged
07-28 12:05:22.239  7746  8198 D HeadsetStateMachine: Disconnected process message: 11
07-28 12:05:22.239  7746  8198 D HeadsetStateMachine: Disconnected process message: 18
07-28 12:05:22.239  7746  7746 D HeadsetPhoneState: Signal level : previous=0 curr=0
,07-28 12:05:22.239  7746  7746 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-28 12:05:22.239  7746  8198 D HeadsetStateMachine: Disconnected process message: 10
07-28 12:05:22.239  7746  7746 E BluetoothAdapterService(562339118): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
07-28 12:05:22.249  7746  8198 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-28 12:05:22.249  7746  8198 D HeadsetStateMachine: Disconnected process message: 11
,07-28 12:05:22.249  7746  7746 D BluetoothA2dp: Proxy object connected
07-28 12:05:22.249  7746  7746 D BluetoothAdapterService: Bluetooth A2dp source service connected
,07-28 12:05:22.249  7746  7746 E BluetoothAdapterService(562339118): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,07-28 12:05:22.249  7746  7746 E BluetoothAdapterService(562339118): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
07-28 12:05:22.249  7746  7746 E BluetoothAdapterService(562339118): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
07-28 12:05:22.249  7746  7746 E BluetoothAdapterService(562339118): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,07-28 12:05:22.249  7746  7746 E BluetoothAdapterService(562339118): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,07-28 12:05:22.249  7746  7746 E BluetoothAdapterService(562339118): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
07-28 12:05:22.249  7746  8180 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
07-28 12:05:22.249  7746  8180 I bluedroid: enable
,07-28 12:05:22.249  7746  8207 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-28 12:05:22.249  7746  8180 I bt_hci_bdroid: init
,07-28 12:05:22.249  7746  8180 I bt_vendor: init
07-28 12:05:22.249  7746  8180 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-28 12:05:22.249  7746  8180 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
07-28 12:05:22.249  7746  8180 D bt_userial: userial_init
07-28 12:05:22.249  7746  8180 D bt_vendor: op for 5
,07-28 12:05:22.249  7746  8180 D bt_vendor: op for 0
,07-28 12:05:22.259  7746  8180 D bt_upio : upio_set_bluetooth_power(on: 0)
07-28 12:05:22.259  7746  8180 D bt_upio : is_emulator_context : 0
07-28 12:05:22.259  7746  8180 D bt_upio : is_rfkill_disabled ? [0]
07-28 12:05:22.259  7746  8180 D bt_upio : is_rfkill_disabled ? [0]
,07-28 12:05:22.259  7746  8180 D bt_vendor: op for 0
07-28 12:05:22.259  7746  8180 D bt_upio : upio_set_bluetooth_power(on: 1)
07-28 12:05:22.259  7746  8180 D bt_upio : is_emulator_context : 0
07-28 12:05:22.259  7746  8180 D bt_upio : is_rfkill_disabled ? [0]
,07-28 12:05:22.259  7746  8209 D bt_vendor: op for 3
07-28 12:05:22.259  7746  8209 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-28 12:05:22.259  7746  8209 I bt_userial_vendor: userial_vendor_open():UART is setup
07-28 12:05:22.259  7746  8209 I bt_userial_vendor: device fd = 66 open
,07-28 12:05:22.269  7746  8209 D bt_vendor: op for 1
07-28 12:05:22.269  7746  8211 D bt_userial: Entering userial_read_thread()
07-28 12:05:22.269  7746  8209 E bt_hwcfg: Start CFG HW, HCI reset
,07-28 12:05:22.339  7746  8209 E bt_hwcfg: Read Local Name after HCI reset
,07-28 12:05:22.359  7746  8209 D bt_hwcfg: Chipset BCM4335C0
,07-28 12:05:22.359  7746  8209 D bt_hwcfg: Target name = [BCM4335C0]
,07-28 12:05:22.369  7746  8209 I bt_hwcfg: module_type[semco].
,07-28 12:05:22.369  7746  8209 I bt_hwcfg: not ZERO...
07-28 12:05:22.369  7746  8209 I bt_hwcfg: module_type[semco] is invalid.
07-28 12:05:22.369  7746  8209 E bt_hwcfg: patchram path ORG . BCM4335C0
07-28 12:05:22.369  7746  8209 E bt_hwcfg: patchram path ORG .. BCM4335C0
07-28 12:05:22.369  7746  8209 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
07-28 12:05:22.369  7746  8209 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
07-28 12:05:22.369  7746  8209 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
07-28 12:05:22.369  7746  8209 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
07-28 12:05:22.369  7746  8209 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335C0
07-28 12:05:22.369  7746  8209 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559_wisol.hcd BCM4335C0
07-28 12:05:22.369  7746  8209 E bt_hwcfg: fw ver (org)0.0
07-28 12:05:22.369  7746  8209 E bt_hwcfg: vendor lib preload failed to locate firmware patch file
07-28 12:05:22.369  7746  8209 E bt_hwcfg: Remove module rev, try again BCM4335
07-28 12:05:22.369  7746  8209 D bt_hwcfg: Target name = [BCM4335]
07-28 12:05:22.369  7746  8209 I bt_hwcfg: module_type[semco].
07-28 12:05:22.369  7746  8209 I bt_hwcfg: not ZERO...
07-28 12:05:22.369  7746  8209 I bt_hwcfg: module_type[semco] is invalid.
07-28 12:05:22.369  7746  8209 E bt_hwcfg: patchram path ORG . BCM4335
07-28 12:05:22.369  7746  8209 E bt_hwcfg: patchram path ORG .. BCM4335
07-28 12:05:22.369  7746  8209 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335
07-28 12:05:22.369  7746  8209 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
07-28 12:05:22.369  7746  8209 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335
07-28 12:05:22.369  7746  8209 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
07-28 12:05:22.369  7746  8209 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335
07-28 12:05:22.369  7746  8209 I bt_hwcfg: patch(org) : bcm4335_V0111.0559.hcd
07-28 12:05:22.369  7746  8209 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4335_V0111.0559.hcd
07-28 12:05:22.369  7746  8209 E bt_hwcfg: ORG patchram base 0111
07-28 12:05:22.369  7746  8209 E bt_hwcfg: ORG patchram minor 0559
07-28 12:05:22.369  7746  8209 E bt_hwcfg: fw ver (org)111.559
07-28 12:05:22.369  7746  8209 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4335_V0111.0559.hcd
,07-28 12:05:22.389  7746  8209 I bt_hwcfg: Axi patch failure or not include AXI patching
,07-28 12:05:22.389   301   301 E SMD     : DCD ON
,07-28 12:05:22.389  7746  8209 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-28 12:05:22.839  7746  8209 I bt_hwcfg: bt vendor lib: set UART baud 115200,
07-28 12:05:22.839  7746  8209 I bt_hwcfg: FW Download delta = 505335
07-28 12:05:22.839  7746  8209 D bt_hwcfg: Settlement delay -- 100 ms
07-28 12:05:22.839  7746  8209 I bt_hwcfg: Setting fw settlement delay to 100 
,07-28 12:05:22.949  7746  8209 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-28 12:05:22.979  7746  8209 I bt_hwcfg: vendor lib fwcfg completed
,07-28 12:05:22.989  7746  8207 I         : BTE_InitTraceLevels -- TRC_HCI
,07-28 12:05:22.989  7746  8207 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-28 12:05:22.989  7746  8207 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-28 12:05:22.989  7746  8207 I         : BTE_InitTraceLevels -- TRC_AVDT
07-28 12:05:22.989  7746  8207 I         : BTE_InitTraceLevels -- TRC_AVRC
07-28 12:05:22.989  7746  8207 I         : BTE_InitTraceLevels -- TRC_A2D
,07-28 12:05:22.989  7746  8207 I         : BTE_InitTraceLevels -- TRC_BNEP
07-28 12:05:22.989  7746  8207 I         : BTE_InitTraceLevels -- TRC_BTM
07-28 12:05:22.989  7746  8207 I         : BTE_InitTraceLevels -- TRC_GAP
07-28 12:05:22.989  7746  8207 I         : BTE_InitTraceLevels -- TRC_PAN
07-28 12:05:22.989  7746  8207 I         : BTE_InitTraceLevels -- TRC_SAP
,07-28 12:05:22.989  7746  8207 I         : BTE_InitTraceLevels -- TRC_SDP
07-28 12:05:22.989  7746  8207 I         : BTE_InitTraceLevels -- TRC_GATT
07-28 12:05:22.989  7746  8207 I         : BTE_InitTraceLevels -- TRC_SMP
07-28 12:05:22.989  7746  8207 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-28 12:05:22.989  7746  8207 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-28 12:05:22.989  7746  8207 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,07-28 12:05:23.189   906  3093 D SSRM:n  : SIOP:: AP = 370, PST = 363, CUR = 450
,07-28 12:05:23.209  7746  8207 W bt-l2cap: l2c_link_processs_ble_num_bufs 15
,07-28 12:05:23.209  7746  8207 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa1b18b5d 
,07-28 12:05:23.209  7746  8207 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa1b18b5d 
,07-28 12:05:23.429  7746  8183 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 1 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
,07-28 12:05:23.429  7746  8183 E bt-btif : Calling BTA_HhEnable
,07-28 12:05:23.429  7746  8183 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,07-28 12:05:23.439  7746  8183 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
,07-28 12:05:23.439  7746  8183 E BluetoothServiceJni: populateRssiValuesNative
07-28 12:05:23.439  7746  8183 I bluedroid: getModelRssiValues
07-28 12:05:23.439  7746  8183 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,07-28 12:05:23.439  7746  8183 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-28 12:05:23.439   906   906 D SettingsProvider: name = bluetooth_name
,07-28 12:05:23.439  7746  8183 D BluetoothAdapterProperties: Name is: Note3-1
,07-28 12:05:23.439  7746  8183 D BluetoothAdapterProperties: Scan Mode:20
,07-28 12:05:23.439  7746  8183 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-28 12:05:23.439  7746  8183 D BluetoothAdapterProperties: LE Address is:E0:B7:20:3E:93:BC
,07-28 12:05:23.439  7746  8209 D bt_vendor: op for 2
,07-28 12:05:23.439  7746  8209 D bt_vendor: op for 6
,07-28 12:05:23.449  7746  8209 D bt_vendor: op for 7
,07-28 12:05:23.449  7746  8209 D bt_upio : proc btwrite assertion
07-28 12:05:23.449  7746  8183 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,07-28 12:05:23.449  7746  8183 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
07-28 12:05:23.449  7746  8183 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,07-28 12:05:23.449  7746  8183 E bt-btif : btif_sock_init: !vhci_init
,07-28 12:05:23.449  7746  8209 D bt_vendor: op for 7
07-28 12:05:23.449  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:23.449  7746  8183 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,07-28 12:05:23.449  7746  8209 D bt_vendor: op for 7
07-28 12:05:23.449  7746  8209 D bt_upio : BT_WAKE is asserted already
07-28 12:05:23.449  7746  8183 D IOP_DB_BT: db_open: db_open : handle 3026251792l, read 14063 bytes onto local cache
,07-28 12:05:23.449  7746  8183 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
07-28 12:05:23.449  7746  8183 D IOP_DB_BT: db_query: result 1
07-28 12:05:23.449  7746  8183 I         : iop_db_open: iop_db_open status 0
,07-28 12:05:23.449  7746  8183 D bte_conf: Device ID record 1 : primary
,07-28 12:05:23.449  7746  8183 D bte_conf:   vendorId            = 0075
07-28 12:05:23.449  7746  8183 D bte_conf:   vendorIdSource      = 0001
07-28 12:05:23.449  7746  8183 D bte_conf:   product             = 0100
07-28 12:05:23.449  7746  8183 D bte_conf:   version             = 0200
,07-28 12:05:23.449  7746  8183 D bte_conf:   clientExecutableURL = 
07-28 12:05:23.449  7746  8183 D bte_conf:   serviceDescription  = 
07-28 12:05:23.449  7746  8183 D bte_conf:   documentationURL    = 
07-28 12:05:23.449  7746  8183 D bte_conf: bte_load_did_conf no section named DID2.
,07-28 12:05:23.449  7746  8180 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,07-28 12:05:23.449  7746  8180 D BluetoothAdapterProperties: ScanMode =  20
07-28 12:05:23.449  7746  8180 D BluetoothAdapterProperties: State =  11
,07-28 12:05:23.449  7746  8183 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-28 12:05:23.459   906  1361 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,07-28 12:05:23.459  7746  8180 D BluetoothAdapterProperties: Setting state to 12
07-28 12:05:23.459  7746  8180 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-28 12:05:23.459  7746  8183 D BluetoothAdapterProperties: Scan Mode:21
,07-28 12:05:23.459  7746  8183 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-28 12:05:23.459   906  3331 D SettingsProvider: name = bluetooth_a2dp_sink_mode
07-28 12:05:23.459   906  3331 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:23.459   906  3331 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,07-28 12:05:23.459   906  3331 D SettingsProvider: selectionArgs: false
07-28 12:05:23.459   906  3331 D SettingsProvider: selectionArgs: 1002
07-28 12:05:23.459   906  3331 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:23.459   906  3331 D SettingsProvider: ret = -1
,07-28 12:05:23.459  7746  8180 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-28 12:05:23.459  7746  8180 D BluetoothAdapterService: updateAdapterState state is 12
,07-28 12:05:23.459   906  1243 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:05:23.459   906  1243 D ActivityManager: caller:android.app.ApplicationThreadProxy@150052cf, r.packageName :com.android.bluetooth
,07-28 12:05:23.469  7746  8180 D BluetoothAdapterService: Autoconnection is available 
,07-28 12:05:23.469  7746  8180 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-28 12:05:23.469  7746  8180 D BluetoothAdapterService: starting service from this receiver
,07-28 12:05:23.469   906  1462 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:05:23.469   906  1462 D ActivityManager: caller:android.app.ApplicationThreadProxy@27cc9365, r.packageName :com.android.bluetooth
,07-28 12:05:23.469  7746  8209 E bt_h4   : vendor lib postload completed
,07-28 12:05:23.469  7746  8209 D bt_vendor: op for 7
07-28 12:05:23.469  7746  8209 D bt_upio : BT_WAKE is asserted already
07-28 12:05:23.469  7746  8180 I BluetoothAdapterState: Entering On State from state = 11
,07-28 12:05:23.479  7746  8209 D bt_vendor: op for 7
,07-28 12:05:23.479  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:23.479  7746  8209 D bt_vendor: op for 7
,07-28 12:05:23.479  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:23.479  7746  8209 D bt_vendor: op for 7
,07-28 12:05:23.479  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:23.479  7746  8209 D bt_vendor: op for 7
,07-28 12:05:23.479  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:23.479  7746  8209 D bt_vendor: op for 7
,07-28 12:05:23.479  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:23.479  7746  8209 D bt_vendor: op for 7
,07-28 12:05:23.479  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:23.479  7746  8209 D bt_vendor: op for 7
,07-28 12:05:23.479  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:23.489  7746  8209 D bt_vendor: op for 7
,07-28 12:05:23.489  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:23.489  7746  8209 D bt_vendor: op for 7
,07-28 12:05:23.489  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:23.489  7746  8209 D bt_vendor: op for 7
07-28 12:05:23.489  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:23.489  7746  8209 D bt_vendor: op for 7
,07-28 12:05:23.489  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:23.489  7746  8209 D bt_vendor: op for 7
,07-28 12:05:23.489  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:23.499  7746  8209 D bt_vendor: op for 7
,07-28 12:05:23.499  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:23.499  7746  8209 D bt_vendor: op for 7
,07-28 12:05:23.499  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:23.499  7746  7746 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,07-28 12:05:23.499  7746  8209 D bt_vendor: op for 7
07-28 12:05:23.499  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:23.499  7746  8209 D bt_vendor: op for 7
,07-28 12:05:23.499  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:23.499  7746  8209 D bt_vendor: op for 7
,07-28 12:05:23.499  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:23.499  7746  8209 D bt_vendor: op for 7
07-28 12:05:23.499  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:23.509  7746  8209 D bt_vendor: op for 7
,07-28 12:05:23.509  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:23.509  7746  7746 I BluetoothPbapService: Handler(): got msg=1
,07-28 12:05:23.509   906   924 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-28 12:05:23.519  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:23.519  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:23.519  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:23.519  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:05:23.519  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:23.519  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:23.519  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:23.519  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:05:23.519   906  1030 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:05:23.519  7508  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:05:23.519  1306  1315 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:05:23.519  3196  3208 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 12:05:23.519  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:23.519  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:23.519  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:23.519  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:05:23.519  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:23.519  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:23.519  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:23.519  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:05:23.519  7508  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:05:23.519   906  1030 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-28 12:05:23.529  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:23.529   906  1030 D BluetoothPan: Binding service...
,07-28 12:05:23.529   906  1030 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
07-28 12:05:23.529  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:23.529   906   906 D BluetoothPan: BluetoothPAN Proxy object connected
,07-28 12:05:23.529   906  1030 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:05:23.529  1428  1708 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:05:23.539  3196  3196 D BluetoothA2dp: Proxy object connected
,07-28 12:05:23.539  1306  1306 D HeadsetProfile: Bluetooth service connected
,07-28 12:05:23.539   906  1030 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:05:23.539  7746  8222 V BluetoothPbapService: PBAP Service initSocket try: 0
,07-28 12:05:23.539  3196  3214 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:05:23.539  1306  1328 D BluetoothPan: Binding service...
,07-28 12:05:23.539  7746  8222 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:05:23.539  7746  8209 D bt_vendor: op for 7
07-28 12:05:23.539  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:23.539  7746  8222 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[73]}
07-28 12:05:23.539  7746  8222 D BluetoothSocket: bindListen(), new LocalSocket 
07-28 12:05:23.539  7746  8222 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-28 12:05:23.539   906  1030 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
07-28 12:05:23.549  7746  8222 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2017cbb
07-28 12:05:23.549  7746  8222 D BluetoothSocket: channel: 19
,07-28 12:05:23.549  7746  8222 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,07-28 12:05:23.549  1306  1315 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 12:05:23.549   906  1030 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-28 12:05:23.549  1306  1306 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:05:23.549  1306  1306 D PanProfile: Bluetooth service connected
,07-28 12:05:23.549  1306  1306 D BluetoothA2dp: Proxy object connected
07-28 12:05:23.549  1306  1306 D A2dpProfile: Bluetooth service connected
,07-28 12:05:23.549  1306  1328 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-28 12:05:23.559   906  1030 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,07-28 12:05:23.559  1306  1318 D BluetoothMap: onBluetoothStateChange: up=true
,07-28 12:05:23.559   906  1030 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,07-28 12:05:23.559   906  1030 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:05:23.559   906  1030 E BluetoothHeadset: BluetoothHeadset service is binded
07-28 12:05:23.559  7746  7755 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 12:05:23.559   906  1030 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:05:23.559   906  1030 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-28 12:05:23.559  1306  1306 D BluetoothInputDevice: Proxy object connected
07-28 12:05:23.559  1306  1306 D HidProfile: Bluetooth service connected
07-28 12:05:23.559   906   906 D BluetoothA2dp: Proxy object connected
,07-28 12:05:23.559   906  1030 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:05:23.559  1406  1434 E BluetoothHeadset: BluetoothHeadset service is binded
07-28 12:05:23.559  1306  1306 D BluetoothMap: Proxy object connected
07-28 12:05:23.559  1306  1306 D MapProfile: Bluetooth service connected
,07-28 12:05:23.569   906  1030 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:05:23.569  1406  3091 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:05:23.569  1306  1315 D Bluetoothsap: onBluetoothStateChange: up=true
07-28 12:05:23.569  1306  1315 D Bluetoothsap: Binding service...
,07-28 12:05:23.569  1306  1315 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,07-28 12:05:23.569   906  1030 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,07-28 12:05:23.569  1306  1315 D Bluetoothsap: bindService called to Bluetooth SAP Service
,07-28 12:05:23.569  1306  1318 D BluetoothPbap: onBluetoothStateChange: up=true
,07-28 12:05:23.569  1306  1306 D Bluetoothsap: BluetoothSAP Proxy object connected
07-28 12:05:23.569  1306  1306 D SapProfile: Bluetooth service connected
07-28 12:05:23.569  1306  1306 D Bluetoothsap: getConnectedDevices()
,07-28 12:05:23.569   906  1030 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,07-28 12:05:23.569  1306  1306 D BluetoothPbap: Proxy object connected
07-28 12:05:23.569  1306  1306 D PbapServerProfile: Bluetooth service connected
,07-28 12:05:23.569   906  1030 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:05:23.569  1406  1416 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:05:23.569   906  1030 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,07-28 12:05:23.579   906  1030 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,07-28 12:05:23.579  1195  1195 D BluetoothTile:  onBluetoothStateChange:
,07-28 12:05:23.579  1406  1406 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@34a16bc, true
07-28 12:05:23.579  7666  7666 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:05:23.579   906   906 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:23.579   906   906 I InputMethodManagerService: [BT Setting State] State =12
07-28 12:05:23.579   906   906 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-28 12:05:23.579  1406  1406 D BluetoothHeadset: registerMessageListener
,07-28 12:05:23.579  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-28 12:05:23.579   906  3064 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-28 12:05:23.579   906  3064 D ActivityManager: caller:android.app.ApplicationThreadProxy@178070ec, r.packageName :com.google.android.gms
07-28 12:05:23.579  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:05:23.579  1306  1306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:05:23.579  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:23.579  7746  8097 D HeadsetService: registerMessageListener
,07-28 12:05:23.589  7746  8097 D HeadsetService: registerMessageListener
,07-28 12:05:23.589  7746  8198 D HeadsetStateMachine: Disconnected process message: 70
07-28 12:05:23.589  7746  8198 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@24545d8
07-28 12:05:23.589  1724  1724 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-28 12:05:23.589  1406  1406 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,07-28 12:05:23.589  1406  1406 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,07-28 12:05:23.589  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:23.589   906  3331 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:05:23.589  1195  1583 D BluetoothTile:  handleUpdatestate:false name:null
07-28 12:05:23.589  1195  1583 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-28 12:05:23.589   906  1560 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
07-28 12:05:23.589  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-28 12:05:23.589  7746  8198 D HeadsetStateMachine: Disconnected process message: 9
,07-28 12:05:23.589  7746  8198 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
07-28 12:05:23.589  1306  1306 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
07-28 12:05:23.589  1306  1306 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,07-28 12:05:23.599  1306  1306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 12:05:23.599   317   317 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
07-28 12:05:23.599   906  3355 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,07-28 12:05:23.599   906  3355 D ActivityManager: caller:android.app.ApplicationThreadProxy@3afd4ebb, r.packageName :com.android.settings
07-28 12:05:23.599   317   317 V voice   : voice_set_parameters: enter: A2dpSuspended=false
07-28 12:05:23.599   317   317 V voice   : voice_set_parameters: exit with code(-2)
07-28 12:05:23.599   317   317 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
07-28 12:05:23.599   317   317 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-28 12:05:23.599   317   317 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-28 12:05:23.599   317   317 V audio_hw_primary: adev_set_parameters: exit
07-28 12:05:23.599  7746  8236 D BluetoothMapMasInstance: set MAP SDP message type : 1
07-28 12:05:23.599  7746  8198 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,07-28 12:05:23.599  7746  8236 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:05:23.609  1306  1306 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:05:23.609  7746  8209 D bt_vendor: op for 7
07-28 12:05:23.609  7746  8209 D bt_upio : BT_WAKE is asserted already
07-28 12:05:23.609  7746  8236 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
07-28 12:05:23.609  1306  1306 D BluetoothNotiBroadcastReceiver: onReceive
07-28 12:05:23.609  7746  8236 D BluetoothSocket: bindListen(), new LocalSocket 
,07-28 12:05:23.609  7746  8236 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-28 12:05:23.609  7746  8236 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2fd6bd31
07-28 12:05:23.609  7746  8236 D BluetoothSocket: channel: 5
,07-28 12:05:23.609  7746  7746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21849d2e
,07-28 12:05:23.609  7746  7746 D BtConfig.SecureMode: isSecureModeOn:false
,07-28 12:05:23.609   906  1663 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:05:23.609   906  1663 D ActivityManager: caller:android.app.ApplicationThreadProxy@2f73df31, r.packageName :com.android.bluetooth
,07-28 12:05:23.629   906  1663 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-28 12:05:23.639  7746  8248 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:05:23.639  7746  8248 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[77]}
07-28 12:05:23.639  7746  8248 D BluetoothSocket: bindListen(), new LocalSocket 
07-28 12:05:23.639  7746  8248 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-28 12:05:23.639  7746  8248 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@8a8fb6d
,07-28 12:05:23.639  7746  8209 D bt_vendor: op for 7
07-28 12:05:23.639  7746  8209 D bt_upio : BT_WAKE is asserted already
07-28 12:05:23.639  7746  8248 D BluetoothSocket: channel: 12
07-28 12:05:23.639  7746  8248 I BtOppRfcommListener: Accept thread started.
,07-28 12:05:23.669  1922  1922 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-28 12:05:23.669   906  1413 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-28 12:05:23.669   906  1413 D ActivityManager: caller:android.app.ApplicationThreadProxy@bdd8da2, r.packageName :com.google.android.gms
,07-28 12:05:23.679  1922  8251 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-28 12:05:23.689  1922  1922 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-28 12:05:23.689   906  3355 D ActivityManager: caller:android.app.ApplicationThreadProxy@3a2ce68f, r.packageName :com.google.android.gms
,07-28 12:05:23.699  1922  8251 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-28 12:05:24.709   906  1541 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-28 12:05:24.709   906  1541 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-28 12:05:24.709   906  1541 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-28 12:05:24.709   906  1541 D BatteryService: stay LED for fully charged
,07-28 12:05:24.709   906   906 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-28 12:05:24.719  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-28 12:05:24.719  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
07-28 12:05:24.719   906   906 I MotionRecognitionService: Plugged
,07-28 12:05:24.719   906   906 I MotionRecognitionService: setPowerConnected  = true
,07-28 12:05:24.719  7746  7746 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-28 12:05:24.719  7746  8198 D HeadsetStateMachine: Disconnected process message: 10
,07-28 12:05:24.719  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-28 12:05:24.719  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-28 12:05:24.719  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:05:24.719  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:05:24.969  7508  7576 D BluetoothAdapter: disable()
,07-28 12:05:24.969   906  1243 D SettingsProvider: name = bluetooth_on
,07-28 12:05:24.969  7746  8180 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,07-28 12:05:24.969  7746  8180 D BluetoothAdapterProperties: Setting state to 13
07-28 12:05:24.969  7746  8180 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-28 12:05:24.969  7746  8180 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-28 12:05:24.969  7746  8180 D BluetoothAdapterService: updateAdapterState state is 13
,07-28 12:05:24.979   906  3331 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:05:24.979   906  3331 D ActivityManager: caller:android.app.ApplicationThreadProxy@3776ad25, r.packageName :com.android.bluetooth
,07-28 12:05:24.979  7746  7746 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,07-28 12:05:24.979  7746  8180 D BluetoothAdapterService: Autoconnection is available 
,07-28 12:05:24.979  7746  8180 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
07-28 12:05:24.979  7746  8180 D BluetoothAdapterService: terminating service from this receiver
,07-28 12:05:24.979  7746  7746 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@fdc73a2, channel: 19, state: LISTENING
,07-28 12:05:24.979  7746  7746 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@fdc73a2, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2017cbb, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3d64c833mSocket: android.net.LocalSocket@235af7f0 impl:android.net.LocalSocketImpl@38e6e169 fd:FileDescriptor[73]
07-28 12:05:24.979  7746  7746 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@235af7f0 impl:android.net.LocalSocketImpl@38e6e169 fd:FileDescriptor[73]
,07-28 12:05:24.979  7746  8180 D BluetoothAdapterProperties: onBluetoothDisable()
,07-28 12:05:24.979   906   923 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,07-28 12:05:24.979  7746  8180 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,07-28 12:05:24.979  7746  8209 D bt_vendor: op for 7
07-28 12:05:24.979  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:24.989  7746  8209 D bt_vendor: op for 7
,07-28 12:05:24.989  7746  8209 D bt_upio : BT_WAKE is asserted already
07-28 12:05:24.989  7746  8183 D BluetoothAdapterProperties: Scan Mode:20
07-28 12:05:24.989  7746  8180 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,07-28 12:05:24.989  7746  8209 D bt_vendor: op for 7
07-28 12:05:24.989  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:24.989  7746  8180 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,07-28 12:05:24.989  7746  8180 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,07-28 12:05:24.989  7746  8180 E bt-btif : cmd socket is not created
,07-28 12:05:24.989  7746  8248 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,07-28 12:05:24.989  7746  8207 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
,07-28 12:05:24.989  7746  8209 D bt_vendor: op for 7
07-28 12:05:24.989  7746  8209 D bt_upio : BT_WAKE is asserted already
07-28 12:05:24.989  7746  8207 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,07-28 12:05:24.989  7746  8207 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:05:24.989  7746  8207 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:05:24.989  7746  8207 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,07-28 12:05:24.989  7746  8180 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-28 12:05:24.989  7746  8209 D bt_vendor: op for 7
07-28 12:05:24.989  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:24.999  7746  8209 D bt_vendor: op for 7
,07-28 12:05:24.999  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:24.999  7746  8209 D bt_vendor: op for 7
,07-28 12:05:24.999  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:24.999  7746  8209 D bt_vendor: op for 7
,07-28 12:05:24.999  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:24.999  7746  8209 D bt_vendor: op for 7
,07-28 12:05:24.999  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:24.999  7746  8209 D bt_vendor: op for 7
,07-28 12:05:25.009  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:25.009  7746  8209 D bt_vendor: op for 7
,07-28 12:05:25.009  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:25.009  7746  8209 D bt_vendor: op for 7
,07-28 12:05:25.009  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:25.009  7746  8209 D bt_vendor: op for 7
,07-28 12:05:25.009  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:25.009  7746  8209 D bt_vendor: op for 7
,07-28 12:05:25.009  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:25.009  7746  8209 D bt_vendor: op for 7
07-28 12:05:25.009  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:25.019  7508  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:05:25.019  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:25.019  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:25.019  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:25.019  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:05:25.019  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:05:25.019  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:25.019  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:25.019  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:05:25.019  7508  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:05:25.019  7508  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:05:25.019   906   906 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:05:25.019   906   906 I InputMethodManagerService: [BT Setting State] State =13
,07-28 12:05:25.029  1724  1724 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
07-28 12:05:25.029  1195  1195 D BluetoothTile:  onBluetoothStateChange:
,07-28 12:05:25.029  7746  7746 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@499b48f, channel: 5, state: LISTENING
07-28 12:05:25.029  7746  7746 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@499b48f, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2fd6bd31, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@fa31cmSocket: android.net.LocalSocket@e032b25 impl:android.net.LocalSocketImpl@321cd4fa fd:FileDescriptor[75]
07-28 12:05:25.029  7746  7746 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@e032b25 impl:android.net.LocalSocketImpl@321cd4fa fd:FileDescriptor[75]
,07-28 12:05:25.029  7666  7666 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:25.029  7746  7746 I BtOppRfcommListener: stopping Accept Thread
07-28 12:05:25.029  7746  7746 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@12870aab, channel: 12, state: LISTENING
07-28 12:05:25.029  7746  7746 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@12870aab, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@8a8fb6d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3401d508mSocket: android.net.LocalSocket@3fe054a1 impl:android.net.LocalSocketImpl@21d346c6 fd:FileDescriptor[77]
07-28 12:05:25.029   906  3331 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-28 12:05:25.029  7746  7746 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3fe054a1 impl:android.net.LocalSocketImpl@21d346c6 fd:FileDescriptor[77]
07-28 12:05:25.029   906  3331 D ActivityManager: caller:android.app.ApplicationThreadProxy@15e72efa, r.packageName :com.google.android.gms
07-28 12:05:25.029  7746  8248 I BtOppRfcommListener: BluetoothSocket listen thread finished
07-28 12:05:25.029  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-28 12:05:25.029  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:05:25.039  7508  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:25.039  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:25.039  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:25.039  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:25.039  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:05:25.039  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:05:25.039  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:25.039  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:25.039  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:05:25.039   906  1361 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:05:25.039  1195  1583 D BluetoothTile:  handleUpdatestate:false name:null
07-28 12:05:25.039   906  1541 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-28 12:05:25.039  7508  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:05:25.039  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
07-28 12:05:25.039  7508  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:05:25.039  1195  1583 D BluetoothTile:  handleUpdatestate:false name:null
,07-28 12:05:25.039  1195  1583 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-28 12:05:25.039  1306  1306 D BluetoothPbap: Proxy object disconnected
07-28 12:05:25.039  1306  1306 D PbapServerProfile: Bluetooth service disconnected
07-28 12:05:25.039  1306  1306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:05:25.039  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:25.039  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:25.049  1306  1306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 12:05:25.049   906  3355 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-28 12:05:25.049   906  3355 D ActivityManager: caller:android.app.ApplicationThreadProxy@1024bf08, r.packageName :com.android.settings
,07-28 12:05:25.049  1306  1306 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:05:25.049  1306  1306 D BluetoothNotiBroadcastReceiver: onReceive
,07-28 12:05:25.099  1922  1922 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-28 12:05:25.109  1922  1922 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-28 12:05:25.189  7746  8209 D bt_vendor: op for 6
,07-28 12:05:25.189  7746  8211 D bt_userial: RX termination
07-28 12:05:25.189  7746  8211 W bt_userial: select_read return size <=0:-1, exiting userial_read_thread
07-28 12:05:25.189  7746  8211 D bt_userial: Leaving userial_read_thread()
07-28 12:05:25.189  7746  8207 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:05:25.189  7746  8207 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:05:25.189  7746  8183 D bt_userial: userial_close_reader Joined userial reader thread: 0
,07-28 12:05:25.189  7746  8207 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:05:25.189  7746  8207 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,07-28 12:05:25.189  7746  8209 D bt_vendor: op for 9
07-28 12:05:25.189  7746  8207 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:05:25.189  7746  8207 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:05:25.189  7746  8209 D bt_hwcfg: hw_epilog_process
07-28 12:05:25.189  7746  8207 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,07-28 12:05:25.189  7746  8209 D bt_vendor: op for 7
07-28 12:05:25.189  7746  8207 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:05:25.189  7746  8209 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:25.189  7746  8207 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:05:25.189  7746  8207 W bt-btif : ag scb idx 1 not allocated
07-28 12:05:25.189  7746  8207 W bt-btif : ag scb idx 2 not allocated
07-28 12:05:25.189  7746  8207 E bt-btif : BTA AG is already disabled, ignoring ...
,07-28 12:05:25.189  7746  8183 D bt_vendor: op for 4
07-28 12:05:25.189  7746  8183 I bt_userial_vendor: device fd = 66 close
,07-28 12:05:25.189  7746  8183 D bt_vendor: op for 0
,07-28 12:05:25.189  7746  8183 D bt_upio : upio_set_bluetooth_power(on: 0)
07-28 12:05:25.189  7746  8183 D bt_upio : is_emulator_context : 0
07-28 12:05:25.189  7746  8183 D bt_upio : is_rfkill_disabled ? [0]
,07-28 12:05:25.199  7746  8183 D bt_vendor: cleanup
,07-28 12:05:25.199  7746  8207 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,07-28 12:05:25.199  7746  8183 I GKI_LINUX: GKI_exit_task 0 done
07-28 12:05:25.199  7746  8183 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,07-28 12:05:25.199  7746  8180 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-28 12:05:25.199  7746  8180 D BtConfig.SecureMode: isSecureModeOn:false
07-28 12:05:25.199  7746  8180 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
07-28 12:05:25.199  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
07-28 12:05:25.199  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-28 12:05:25.199  7746  8180 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
07-28 12:05:25.199   906  1361 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:05:25.199   906  1361 D ActivityManager: caller:android.app.ApplicationThreadProxy@e940c6, r.packageName :com.android.bluetooth
,07-28 12:05:25.199  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
07-28 12:05:25.199  7746  7746 D BtGatt.DebugUtils: handleDebugAction() action=null
07-28 12:05:25.199  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-28 12:05:25.199  7746  8180 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,07-28 12:05:25.199  7746  7746 D BtGatt.GattService: Received stop request...Stopping profile...
,07-28 12:05:25.199  7746  7746 D BtGatt.GattService: stop()
07-28 12:05:25.199  7746  7746 D BtGatt.AdvertiseManager: advertise clients cleared
,07-28 12:05:25.199   906   923 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:05:25.199   906   923 D ActivityManager: caller:android.app.ApplicationThreadProxy@14311887, r.packageName :com.android.bluetooth
,07-28 12:05:25.199  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
07-28 12:05:25.199  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-28 12:05:25.199  7746  8180 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
07-28 12:05:25.199   906   923 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:05:25.199   906   923 D ActivityManager: caller:android.app.ApplicationThreadProxy@dcac3b4, r.packageName :com.android.bluetooth
07-28 12:05:25.199  7746  7746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21849d2e
,07-28 12:05:25.199  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
07-28 12:05:25.199  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-28 12:05:25.199  7746  8180 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-28 12:05:25.199   906  3331 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:05:25.199   906  3331 D ActivityManager: caller:android.app.ApplicationThreadProxy@382e5bdd, r.packageName :com.android.bluetooth
,07-28 12:05:25.209  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
07-28 12:05:25.209  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-28 12:05:25.209  7746  8180 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-28 12:05:25.209   906  3064 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:05:25.209  7746  7746 D HeadsetService: Received stop request...Stopping profile...
07-28 12:05:25.209   906  3064 D ActivityManager: caller:android.app.ApplicationThreadProxy@35a8a352, r.packageName :com.android.bluetooth
07-28 12:05:25.209  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
07-28 12:05:25.209  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-28 12:05:25.209  7746  8180 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-28 12:05:25.209   906  1361 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:05:25.209  7746  7746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21849d2e
,07-28 12:05:25.209   906  1361 D ActivityManager: caller:android.app.ApplicationThreadProxy@1dfcb623, r.packageName :com.android.bluetooth
07-28 12:05:25.209  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
07-28 12:05:25.209  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-28 12:05:25.209  7746  8180 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,07-28 12:05:25.209   906   906 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,07-28 12:05:25.209   906  1462 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:05:25.209  1306  1306 D HeadsetProfile: Bluetooth service disconnected
,07-28 12:05:25.209  7666  7666 W BluetoothHeadset: Proxy not attached to service
07-28 12:05:25.209   906  1462 D ActivityManager: caller:android.app.ApplicationThreadProxy@62a6720, r.packageName :com.android.bluetooth
,07-28 12:05:25.209  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
07-28 12:05:25.209  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-28 12:05:25.209  7746  8180 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,07-28 12:05:25.209   906  1435 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:05:25.209   906  1435 D ActivityManager: caller:android.app.ApplicationThreadProxy@2e39d8d9, r.packageName :com.android.bluetooth
07-28 12:05:25.209  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:05:25.209  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-28 12:05:25.209  7746  8180 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:05:25.209  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:05:25.209  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:05:25.209  7746  8180 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:05:25.209  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
,07-28 12:05:25.209  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-28 12:05:25.209  7746  8180 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-28 12:05:25.209  7746  8180 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
07-28 12:05:25.209  7746  8180 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-28 12:05:25.209  7746  8180 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,07-28 12:05:25.209  7746  8180 D BluetoothAdapterState: Stopping profile services that were post enabled
07-28 12:05:25.209  7746  7746 E BluetoothAdapterService(562339118): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
,07-28 12:05:25.219  7746  7746 D A2dpService: Received stop request...Stopping profile...
,07-28 12:05:25.219  7746  7746 V Avrcp   : doQuit
07-28 12:05:25.219  7746  8202 D A2dpStateMachine: Exit Disconnected: -1
,07-28 12:05:25.219  7746  7746 D Avrcp   : Unregistering previous receiver
,07-28 12:05:25.219  7746  7746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21849d2e
,07-28 12:05:25.219   906   906 D BluetoothA2dp: Proxy object disconnected
07-28 12:05:25.219   906   906 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,07-28 12:05:25.219  1306  1306 D BluetoothA2dp: Proxy object disconnected
07-28 12:05:25.219  3196  3196 D BluetoothA2dp: Proxy object disconnected
07-28 12:05:25.219  1306  1306 D A2dpProfile: Bluetooth service disconnected
,07-28 12:05:25.219  7746  7746 D HidService: Received stop request...Stopping profile...
,07-28 12:05:25.219  7746  7746 D HidService: Stopping Bluetooth HidService
07-28 12:05:25.219  7746  7746 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-28 12:05:25.219  7746  7746 W bt-btif : cleanup: HH disabling or disabled already, status = 0
07-28 12:05:25.219  7746  7746 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-28 12:05:25.219  7746  7746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21849d2e
,07-28 12:05:25.219  1306  1306 D BluetoothInputDevice: Proxy object disconnected
07-28 12:05:25.219  1306  1306 D HidProfile: Bluetooth service disconnected
,07-28 12:05:25.219  7746  7746 D HealthService: Received stop request...Stopping profile...
07-28 12:05:25.219  7746  7746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21849d2e
,07-28 12:05:25.229  7746  7746 E BluetoothAdapterService(562339118): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
07-28 12:05:25.229  7746  7746 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-28 12:05:25.229  7746  7746 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
07-28 12:05:25.229  7746  7746 D PanService: Received stop request...Stopping profile...
07-28 12:05:25.229  7746  7746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21849d2e
,07-28 12:05:25.229   906   906 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-28 12:05:25.229  1306  1306 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-28 12:05:25.229  1306  1306 D PanProfile: Bluetooth service disconnected
,07-28 12:05:25.229  7746  7746 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-28 12:05:25.229  7746  7746 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,07-28 12:05:25.229  7746  7746 D BluetoothMapService: Received stop request...Stopping profile...
,07-28 12:05:25.229  7746  7746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21849d2e
,07-28 12:05:25.229  1306  1306 D BluetoothMap: Proxy object disconnected
,07-28 12:05:25.229  1306  1306 D MapProfile: Bluetooth service disconnected
07-28 12:05:25.229  7746  7746 D SapService: Received stop request...Stopping profile...
,07-28 12:05:25.229  7746  7746 D SapService: Stopping Bluetooth SapService
07-28 12:05:25.229  7746  7746 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@21849d2e
,07-28 12:05:25.229  7746  7746 E BluetoothAdapterService(562339118): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
07-28 12:05:25.229  7746  7746 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-28 12:05:25.229  7746  7746 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
07-28 12:05:25.229  7746  7746 D BluetoothA2dp: Proxy object disconnected
07-28 12:05:25.229  7746  7746 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,07-28 12:05:25.229  1306  1306 D Bluetoothsap: BluetoothSAP Proxy object disconnected
07-28 12:05:25.229  1306  1306 D SapProfile: Bluetooth service disconnected
07-28 12:05:25.229  7746  8203 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-28 12:05:25.239  7746  7746 I GKI_LINUX: GKI_exit_task 2 done
07-28 12:05:25.239  7746  7746 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
,07-28 12:05:25.239  7746  7746 V Avrcp   : cleanup
07-28 12:05:25.239  7746  7746 E BluetoothAdapterService(562339118): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
07-28 12:05:25.239  7746  7746 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:05:25.239  7746  7746 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,07-28 12:05:25.239  7746  7746 E BluetoothAdapterService(562339118): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
07-28 12:05:25.239  7746  7746 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:05:25.239  7746  7746 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-28 12:05:25.239  7746  7746 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,07-28 12:05:25.239  7746  7746 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:05:25.239  7746  7746 E BluetoothAdapterService(562339118): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
07-28 12:05:25.239  7746  7746 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:05:25.239  7746  7746 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
,07-28 12:05:25.239  7746  7746 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-28 12:05:25.239  7746  7746 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-28 12:05:25.239  7746  7746 E BluetoothAdapterService(562339118): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
07-28 12:05:25.239  7746  7746 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,07-28 12:05:25.239  7746  7746 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
07-28 12:05:25.239  7746  7746 E BluetoothAdapterService(562339118): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,07-28 12:05:25.239  7746  8180 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
07-28 12:05:25.239  7746  7746 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
07-28 12:05:25.239  7746  7746 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
07-28 12:05:25.239  7746  8180 D BluetoothAdapterProperties: Setting state to 10
07-28 12:05:25.239  7746  8180 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-28 12:05:25.239  7746  8180 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-28 12:05:25.239  7746  8180 D BluetoothAdapterService: updateAdapterState state is 10
,07-28 12:05:25.239  7746  8180 D BluetoothAdapterService: Autoconnection is available 
,07-28 12:05:25.239  7746  8180 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
07-28 12:05:25.239  7746  8180 I BluetoothAdapterState: Entering OffState
07-28 12:05:25.239  3196  8223 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-28 12:05:25.239  1306  1315 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-28 12:05:25.239  1306  1328 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-28 12:05:25.239  1306  1318 D BluetoothMap: onBluetoothStateChange: up=false
,07-28 12:05:25.249  7746  7757 D BluetoothA2dp: onBluetoothStateChange: up=false
07-28 12:05:25.249   906  1030 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-28 12:05:25.249  1306  1315 D Bluetoothsap: onBluetoothStateChange: up=false
07-28 12:05:25.249  1306  1315 D Bluetoothsap: Unbinding service...
,07-28 12:05:25.249  1306  1328 D BluetoothPbap: onBluetoothStateChange: up=false
,07-28 12:05:25.249   906  1030 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 14 receivers.
,07-28 12:05:25.249   906  1030 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,07-28 12:05:25.249   906   906 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:25.249   906   906 I InputMethodManagerService: [BT Setting State] State =10
07-28 12:05:25.249   906   906 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-28 12:05:25.259  1195  1195 D BluetoothAdapter: 641724124: getState() :  mService = null. Returning STATE_OFF
,07-28 12:05:25.259  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-28 12:05:25.259  1724  1724 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
07-28 12:05:25.259  1306  1306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:25.259  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:25.259  1922  2408 D BluetoothAdapter: 136307705: getState() :  mService = null. Returning STATE_OFF
07-28 12:05:25.259  1195  1583 D BluetoothAdapter: 641724124: getState() :  mService = null. Returning STATE_OFF
07-28 12:05:25.259  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:25.259  1195  1195 D BluetoothAdapter: 641724124: getState() :  mService = null. Returning STATE_OFF
07-28 12:05:25.259  1195  1583 D BluetoothAdapter: 641724124: getState() :  mService = null. Returning STATE_OFF
07-28 12:05:25.259  1195  1583 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
07-28 12:05:25.259  1922  2408 D BluetoothAdapter: 136307705: getState() :  mService = null. Returning STATE_OFF
,07-28 12:05:25.259  1195  1195 D BluetoothAdapter: 641724124: getState() :  mService = null. Returning STATE_OFF
07-28 12:05:25.259  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:25.259   906  1462 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-28 12:05:25.259  7666  7666 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:25.259   906  1361 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-28 12:05:25.259  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-28 12:05:25.259   906  3331 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-28 12:05:25.259   906  3331 D ActivityManager: caller:android.app.ApplicationThreadProxy@1f89a29e, r.packageName :com.google.android.gms
,07-28 12:05:25.269  7746  8183 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,07-28 12:05:25.269  7746  7746 I GKI_LINUX: GKI_exit_task 1 done
07-28 12:05:25.269  7746  7746 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,07-28 12:05:25.269  1306  1306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-28 12:05:25.269  7746  7746 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-28 12:05:25.269   906  1435 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-28 12:05:25.269   906  1435 D ActivityManager: caller:android.app.ApplicationThreadProxy@331ed54c, r.packageName :com.android.settings
,07-28 12:05:25.269  7746  7746 I art     : System.exit called, status: 0
07-28 12:05:25.269  7746  7746 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-28 12:05:25.279  1306  1306 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:05:25.279  1306  1306 D BluetoothNotiBroadcastReceiver: onReceive
,07-28 12:05:25.319   906   923 I ActivityManager: Process com.android.bluetooth (pid 7746)(adj 0) has died(168,1591)
,07-28 12:05:25.329  1922  1922 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-28 12:05:25.329   906  3355 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-28 12:05:25.339   906  3355 D ActivityManager: caller:android.app.ApplicationThreadProxy@2f09fa38, r.packageName :com.google.android.gms
,07-28 12:05:25.349  1922  8285 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-28 12:05:25.349  1922  1922 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-28 12:05:25.349   906  1465 D ActivityManager: caller:android.app.ApplicationThreadProxy@26e96776, r.packageName :com.google.android.gms
,07-28 12:05:25.359  1922  8285 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-28 12:05:25.389   301   301 E SMD     : DCD ON
,07-28 12:05:27.649   906  1036 I PowerManagerService: [PWL] Off : 105s ago
,07-28 12:05:27.649   906  1036 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,07-28 12:05:27.649   906  1036 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,07-28 12:05:27.659   906  1036 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=906, ws=null) (elapsedTime=14584),
,07-28 12:05:28.039  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:05:28.039  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,07-28 12:05:28.390   301   301 E SMD     : DCD ON
,07-28 12:05:29.589   364   364 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:05:30.599   364   364 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:05:31.049  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:05:31.049  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13d7daee added. We now have 6 listener(s)
,07-28 12:05:31.049  7508  7576 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:05:31.059  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:05:31.059  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39b0eb8f added. We now have 7 listener(s)
07-28 12:05:31.059  7508  7576 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:05:31.059  7508  7576 I System.out: IsBluetoothEnabled
,07-28 12:05:31.059  7508  7576 D BluetoothAdapter: disable()
,07-28 12:05:31.059   906  1560 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,07-28 12:05:31.069  7508  7576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:31.069  7508  7576 D BluetoothAdapter: enable()
,07-28 12:05:31.069   906  1709 W ActivityManager: Permission Denial: getCurrentUser() from pid=7508, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,07-28 12:05:31.069   906  1709 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-28 12:05:31.069   906  1709 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7508, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-28 12:05:31.069   906  1709 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-28 12:05:31.069   906  1709 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
07-28 12:05:31.069   906  1709 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
07-28 12:05:31.069   906  1709 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-28 12:05:31.069   906  1709 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,07-28 12:05:31.069   906  1709 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-28 12:05:31.069   906  1709 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:05:31.069   906  1709 D SettingsProvider: name = bluetooth_on
,07-28 12:05:31.079   906  1030 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:05:31.079   906  1030 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:05:31.089   906  1030 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,07-28 12:05:31.089   906  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:31.089   906  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:31.089   906  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:31.089   906  1030 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:31.129  8295  8295 E Zygote  : MountEmulatedStorage()
,07-28 12:05:31.149   906  1030 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=8295 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,07-28 12:05:31.149  8295  8295 E Zygote  : v2
07-28 12:05:31.149  8295  8295 I libpersona: KNOX_SDCARD checking this for 1002
07-28 12:05:31.149  8295  8295 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:31.149  8295  8295 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-28 12:05:31.149  8295  8295 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:05:31.149  8295  8295 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:05:31.189  8295  8295 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:05:31.189  8295  8295 D ActivityThread: Added TimaKeyStore provider
,07-28 12:05:31.209  8295  8295 D ResourcesManager: creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,07-28 12:05:31.219  8295  8295 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,07-28 12:05:31.219  8295  8295 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-28 12:05:31.239  8295  8295 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,07-28 12:05:31.269  8295  8295 D BtSettings.ProfileConfig: Adding GattService
,07-28 12:05:31.269  8295  8295 D BtSettings.ProfileConfig: Adding HeadsetService
,07-28 12:05:31.269  8295  8295 D BtSettings.ProfileConfig: Adding A2dpService
,07-28 12:05:31.269  8295  8295 D BtSettings.ProfileConfig: Adding HidService
07-28 12:05:31.269  8295  8295 D BtSettings.ProfileConfig: Adding HealthService
,07-28 12:05:31.269  8295  8295 D BtSettings.ProfileConfig: Adding PanService
,07-28 12:05:31.269  8295  8295 D BtSettings.ProfileConfig: Adding BluetoothMapService
,07-28 12:05:31.279  8295  8295 D BtSettings.ProfileConfig: Adding SapService
,07-28 12:05:31.279  8295  8295 D BtSettings.ProfileConfig: Adding HeadsetClientService
,07-28 12:05:31.279  8295  8295 D BtSettings.ProfileConfig: Adding A2dpSinkService
,07-28 12:05:31.279  8295  8295 D BtSettings.ProfileConfig: Adding SapClientService
,07-28 12:05:31.279  8295  8295 D BtSettings.ProfileConfig: Adding HidDevService
,07-28 12:05:31.279  8295  8295 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,07-28 12:05:31.279   906  3355 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,07-28 12:05:31.279   906  3355 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:31.279   906  3355 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:31.279   906  3355 D SettingsProvider: selectionArgs: false
07-28 12:05:31.279   906  3355 D SettingsProvider: selectionArgs: 1002
,07-28 12:05:31.279   906  3355 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:31.279   906  3355 D SettingsProvider: ret = -1
,07-28 12:05:31.279   906  3331 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,07-28 12:05:31.289   906  3331 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:31.289   906  3331 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:31.289   906  3331 D SettingsProvider: selectionArgs: false
,07-28 12:05:31.289   906  3331 D SettingsProvider: selectionArgs: 1002
07-28 12:05:31.289   906  3331 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:31.289   906  3331 D SettingsProvider: ret = -1
,07-28 12:05:31.289   906  1462 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
,07-28 12:05:31.289   906  1462 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:31.289   906  1462 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:31.289   906  1462 D SettingsProvider: selectionArgs: false
,07-28 12:05:31.289   906  1462 D SettingsProvider: selectionArgs: 1002
07-28 12:05:31.289   906  1462 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:31.289   906  1462 D SettingsProvider: ret = -1
,07-28 12:05:31.289   906  3064 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
,07-28 12:05:31.289   906  3064 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:31.289   906  3064 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:31.289   906  3064 D SettingsProvider: selectionArgs: false
,07-28 12:05:31.289   906  3064 D SettingsProvider: selectionArgs: 1002
07-28 12:05:31.289   906  3064 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:31.289   906  3064 D SettingsProvider: ret = -1
,07-28 12:05:31.289   906  1361 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
,07-28 12:05:31.289   906  1361 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:31.289   906  1361 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:31.289   906  1361 D SettingsProvider: selectionArgs: false
07-28 12:05:31.289   906  1361 D SettingsProvider: selectionArgs: 1002
07-28 12:05:31.289   906  1361 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-28 12:05:31.289   906  1361 D SettingsProvider: ret = -1
07-28 12:05:31.289   906  1143 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
,07-28 12:05:31.289   906  1143 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:31.289   906  1143 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:31.289   906  1143 D SettingsProvider: selectionArgs: false
07-28 12:05:31.289   906  1143 D SettingsProvider: selectionArgs: 1002
,07-28 12:05:31.289   906  1143 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:31.289   906  1143 D SettingsProvider: ret = -1
,07-28 12:05:31.299   906   923 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
,07-28 12:05:31.299   906   923 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:31.299   906   923 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:31.299   906   923 D SettingsProvider: selectionArgs: false
07-28 12:05:31.299   906   923 D SettingsProvider: selectionArgs: 1002
,07-28 12:05:31.299   906   923 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:31.299   906   923 D SettingsProvider: ret = -1
,07-28 12:05:31.299   906   924 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
07-28 12:05:31.299   906   924 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,07-28 12:05:31.299   906   924 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:31.299   906   924 D SettingsProvider: selectionArgs: false
07-28 12:05:31.299   906   924 D SettingsProvider: selectionArgs: 1002
,07-28 12:05:31.299   906   924 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:31.299   906   924 D SettingsProvider: ret = -1
,07-28 12:05:31.299   906  1541 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
,07-28 12:05:31.299   906  1541 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:31.299   906  1541 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:31.299   906  1541 D SettingsProvider: selectionArgs: false
,07-28 12:05:31.299   906  1541 D SettingsProvider: selectionArgs: 1002
07-28 12:05:31.299   906  1541 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:31.299   906  1541 D SettingsProvider: ret = -1
,07-28 12:05:31.299   906  1465 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
,07-28 12:05:31.299   906  1465 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:31.299   906  1465 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:31.299   906  1465 D SettingsProvider: selectionArgs: false
07-28 12:05:31.299   906  1465 D SettingsProvider: selectionArgs: 1002
,07-28 12:05:31.299   906  1465 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:31.299   906  1465 D SettingsProvider: ret = -1
,07-28 12:05:31.299   906  1663 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,07-28 12:05:31.299   906  1663 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:31.299   906  1663 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:31.299   906  1663 D SettingsProvider: selectionArgs: false
,07-28 12:05:31.309   906  1663 D SettingsProvider: selectionArgs: 1002
,07-28 12:05:31.309   906  1663 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:31.309   906  1663 D SettingsProvider: ret = -1
,07-28 12:05:31.309   906  1435 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
07-28 12:05:31.309   906  1435 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,07-28 12:05:31.309   906  1435 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:31.309   906  1435 D SettingsProvider: selectionArgs: false
07-28 12:05:31.309   906  1435 D SettingsProvider: selectionArgs: 1002
07-28 12:05:31.309   906  1435 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-28 12:05:31.309   906  1435 D SettingsProvider: ret = -1
,07-28 12:05:31.339  8295  8295 D BluetoothAdapterState: make
,07-28 12:05:31.339  8295  8295 I bluedroid: init
,07-28 12:05:31.339  8295  8315 I BluetoothAdapterState: Entering OffState
,07-28 12:05:31.339  8295  8295 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-28 12:05:31.339  8295  8295 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-28 12:05:31.339  8295  8295 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,07-28 12:05:31.339  8295  8295 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,07-28 12:05:31.349  8295  8295 E bt-btif : btif_fetch_local_ble_random_bdaddr
07-28 12:05:31.349  8295  8295 I bluedroid: get_profile_interface socket
07-28 12:05:31.349  8295  8318 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
07-28 12:05:31.349  8295  8295 I bluedroid: get_profile_interface map_client
,07-28 12:05:31.349  8295  8318 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
,07-28 12:05:31.349  8295  8295 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
07-28 12:05:31.349  8295  8318 E BluetoothServiceJni: populateRssiValuesNative
07-28 12:05:31.349  8295  8318 I bluedroid: getModelRssiValues
07-28 12:05:31.349  8295  8318 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
07-28 12:05:31.349  8295  8318 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-28 12:05:31.349   906   906 D SettingsProvider: name = bluetooth_name
,07-28 12:05:31.349  8295  8318 D BluetoothAdapterProperties: Name is: Note3-1
,07-28 12:05:31.349   906  1143 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-28 12:05:31.359  8295  8303 I bluedroid: config_hci_snoop_log
,07-28 12:05:31.359   906  1030 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 14 receivers.
,07-28 12:05:31.359   906  1030 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:05:31.359   906  1030 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:05:31.359   906  1030 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,07-28 12:05:31.369  8295  8315 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,07-28 12:05:31.369  8295  8315 D BluetoothAdapterProperties: Setting state to 11
,07-28 12:05:31.369  8295  8315 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-28 12:05:31.369  8295  8315 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,07-28 12:05:31.369  8295  8315 D BluetoothAdapterService: updateAdapterState state is 11
,07-28 12:05:31.369  8295  8315 D BluetoothAdapterService: Autoconnection is available 
07-28 12:05:31.369  8295  8315 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,07-28 12:05:31.369   906   906 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:31.369   906   906 I InputMethodManagerService: [BT Setting State] State =11
,07-28 12:05:31.369  1724  1724 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-28 12:05:31.369  1306  1306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:05:31.369   906  1243 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-28 12:05:31.369  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:05:31.369  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-28 12:05:31.369  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:05:31.379   906  1243 D ActivityManager: caller:android.app.ApplicationThreadProxy@136b0cbd, r.packageName :com.google.android.gms
,07-28 12:05:31.379  7666  7666 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:05:31.379  1195  1583 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-28 12:05:31.379   906   924 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:05:31.379   906   923 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-28 12:05:31.379  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-28 12:05:31.379  1306  1306 D BluetoothNotiBroadcastReceiver: onReceive
,07-28 12:05:31.389  8295  8315 D BluetoothSecureManager: getInstant: null
,07-28 12:05:31.389  8295  8315 D BluetoothSecureManager: calling getMethod for getService
07-28 12:05:31.389  8295  8315 D BluetoothSecureManager: calling getService
,07-28 12:05:31.389   301   301 E SMD     : DCD ON
,07-28 12:05:31.389  8295  8315 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@9c05ee1
,07-28 12:05:31.389   906  1435 D BluetoothSecureManagerService: isSecureModeEnabled
07-28 12:05:31.389   906  1435 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
07-28 12:05:31.389  8295  8315 D BtConfig.SecureMode: isSecureModeOn:false
,07-28 12:05:31.389  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-28 12:05:31.389  8295  8315 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
07-28 12:05:31.389  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-28 12:05:31.389  8295  8315 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
07-28 12:05:31.389  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,07-28 12:05:31.389  8295  8315 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
07-28 12:05:31.389  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-28 12:05:31.389  8295  8315 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,07-28 12:05:31.389  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-28 12:05:31.389  8295  8315 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
07-28 12:05:31.389  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-28 12:05:31.389  8295  8315 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
07-28 12:05:31.389  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-28 12:05:31.389  8295  8315 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
07-28 12:05:31.389  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,07-28 12:05:31.389  8295  8315 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
07-28 12:05:31.399  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-28 12:05:31.399  8295  8315 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:05:31.399  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,07-28 12:05:31.399  8295  8315 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:05:31.399  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,07-28 12:05:31.399  8295  8315 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
07-28 12:05:31.399  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-28 12:05:31.399  8295  8315 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,07-28 12:05:31.399  8295  8315 D BluetoothBondStateMachine: make
,07-28 12:05:31.399  8295  8315 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,07-28 12:05:31.399  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-28 12:05:31.399  8295  8315 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,07-28 12:05:31.399   906  3331 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:05:31.399  8295  8322 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-28 12:05:31.399   906  3331 D ActivityManager: caller:android.app.ApplicationThreadProxy@3a080203, r.packageName :com.android.bluetooth
,07-28 12:05:31.409  8295  8295 I BtGatt.JNI: classInitNative(L890): classInitNative: Success!
,07-28 12:05:31.409  8295  8315 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,07-28 12:05:31.409  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,07-28 12:05:31.409  8295  8315 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,07-28 12:05:31.409   906  3355 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:05:31.409   906  3355 D ActivityManager: caller:android.app.ApplicationThreadProxy@3e40b7b9, r.packageName :com.android.bluetooth
,07-28 12:05:31.419  8295  8295 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 12:05:31.419  8295  8295 D BtGatt.GattService: Received start request. Starting profile...
07-28 12:05:31.419  8295  8295 D BtGatt.GattService: start()
07-28 12:05:31.419  8295  8295 I bluedroid: get_profile_interface gatt
,07-28 12:05:31.419  8295  8295 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c7e9b30
07-28 12:05:31.419  8295  8295 D BtGatt.AdvertiseManager: advertise manager created
,07-28 12:05:31.419  8295  8315 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
07-28 12:05:31.419  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-28 12:05:31.419  8295  8315 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,07-28 12:05:31.419   906  1361 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:05:31.419   906  1361 D ActivityManager: caller:android.app.ApplicationThreadProxy@3ffebb5f, r.packageName :com.android.bluetooth
,07-28 12:05:31.419  8295  8315 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,07-28 12:05:31.419  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-28 12:05:31.419  8295  8315 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,07-28 12:05:31.419   906  1143 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:05:31.419   906  1143 D ActivityManager: caller:android.app.ApplicationThreadProxy@3dcef498, r.packageName :com.android.bluetooth
,07-28 12:05:31.429  8295  8315 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,07-28 12:05:31.429  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-28 12:05:31.429  8295  8315 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-28 12:05:31.429  8295  8295 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c7e9b30
,07-28 12:05:31.429   906   923 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:05:31.429   906   923 D ActivityManager: caller:android.app.ApplicationThreadProxy@2511d8d6, r.packageName :com.android.bluetooth
,07-28 12:05:31.429  8295  8295 D HeadsetService: Received start request. Starting profile...
,07-28 12:05:31.429  8295  8315 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,07-28 12:05:31.429  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-28 12:05:31.429  8295  8315 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-28 12:05:31.429  8295  8295 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,07-28 12:05:31.429  8295  8295 D HeadsetStateMachine: make
07-28 12:05:31.429   906  1435 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:05:31.429   906  1435 D ActivityManager: caller:android.app.ApplicationThreadProxy@280ac244, r.packageName :com.android.bluetooth
,07-28 12:05:31.439  8295  8315 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,07-28 12:05:31.439  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:05:31.439  8295  8315 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,07-28 12:05:31.439   906  1560 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:05:31.439   906  1560 D ActivityManager: caller:android.app.ApplicationThreadProxy@302aac62, r.packageName :com.android.bluetooth
,07-28 12:05:31.439  8295  8295 E HeadsetStateMachine: # of Max HF connection is 2
,07-28 12:05:31.439  8295  8315 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
,07-28 12:05:31.439  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-28 12:05:31.439  8295  8315 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,07-28 12:05:31.439   906  3331 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:05:31.439   906  3331 D ActivityManager: caller:android.app.ApplicationThreadProxy@1b13beb0, r.packageName :com.android.bluetooth
,07-28 12:05:31.449   906  1709 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,07-28 12:05:31.449  8295  8315 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
,07-28 12:05:31.449  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-28 12:05:31.449  8295  8315 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:05:31.449  8295  8315 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:05:31.449  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:05:31.449  8295  8315 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:05:31.449  8295  8315 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
07-28 12:05:31.449  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-28 12:05:31.449  8295  8315 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-28 12:05:31.449  8295  8315 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
07-28 12:05:31.449  8295  8315 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-28 12:05:31.449  8295  8315 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-28 12:05:31.449  8295  8315 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,07-28 12:05:31.449   906  1143 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
,07-28 12:05:31.449  8295  8295 I bluedroid: get_profile_interface handsfree
,07-28 12:05:31.459  8295  8295 I DualScoManager: Instantiating Dual Sco Manager
,07-28 12:05:31.459  8295  8295 I DualScoManager: Set HeadsetServiceHelper
,07-28 12:05:31.459  8295  8295 D BluetoothAtMessage: createCMTIContentObservers
,07-28 12:05:31.459   906  1663 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,07-28 12:05:31.459   906  1663 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:31.459   906  1663 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:31.459   906  1663 D SettingsProvider: selectionArgs: false
07-28 12:05:31.459   906  1663 D SettingsProvider: selectionArgs: 1002
07-28 12:05:31.459   906  1663 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-28 12:05:31.459   906  1663 D SettingsProvider: ret = -1
,07-28 12:05:31.469  8295  8325 D HeadsetStateMachine: Enter Disconnected: -2
,07-28 12:05:31.469  8295  8295 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c7e9b30
,07-28 12:05:31.469  8295  8325 E HeadsetStateMachine: set to mRemoteBrsf = 0
,07-28 12:05:31.469  8295  8295 D A2dpService: Received start request. Starting profile...
,07-28 12:05:31.469  8295  8325 D HeadsetStateMachine: map size, before remove : 0
07-28 12:05:31.469  8295  8325 D HeadsetStateMachine: map size, after remove: 0
07-28 12:05:31.469  8295  8325 D HeadsetStateMachine: mNextConnectingDevice : null
,07-28 12:05:31.469  8295  8295 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-28 12:05:31.469  8295  8295 V Avrcp   : make
,07-28 12:05:31.469  8295  8295 V Avrcp   : Avrcp
,07-28 12:05:31.469  8295  8295 I bluedroid: get_profile_interface avrcp
,07-28 12:05:31.469  1922  1922 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-28 12:05:31.479  8295  8295 V Avrcp   : start
,07-28 12:05:31.479  1922  1922 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-28 12:05:31.479  8295  8295 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-28 12:05:31.479  8295  8295 V Avrcp   : ++registerMediaPlayers++
,07-28 12:05:31.479  8295  8295 I Avrcp   : No of Audio players :: 2
,07-28 12:05:31.479  8295  8295 I Avrcp   : App Package name is com.google.android.music
,07-28 12:05:31.489  8295  8295 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-28 12:05:31.489  8295  8295 I Avrcp   : App pkg name is Google Play Music
,07-28 12:05:31.489  8295  8295 I Avrcp   : Name::Google Play Music
,07-28 12:05:31.489  8295  8295 V Avrcp   : MediaPlayerInfo: mPlayerId=1
07-28 12:05:31.489  8295  8295 I Avrcp   : App Package name is com.sec.android.app.music
,07-28 12:05:31.489  8295  8295 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,07-28 12:05:31.489  8295  8295 I Avrcp   : App pkg name is Music
,07-28 12:05:31.489  8295  8295 I Avrcp   : Name::Music
07-28 12:05:31.489  8295  8295 V Avrcp   : MediaPlayerInfo: mPlayerId=2
07-28 12:05:31.499  8295  8295 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,07-28 12:05:31.499  8295  8295 I Avrcp   : No of Video players :: 1
,07-28 12:05:31.499  8295  8295 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
,07-28 12:05:31.499  8295  8295 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,07-28 12:05:31.499  8295  8295 I Avrcp   : Video App pkg name is Video Player
,07-28 12:05:31.499  8295  8295 I Avrcp   : Name::Video Player
07-28 12:05:31.499  8295  8295 V Avrcp   : MediaPlayerInfo: mPlayerId=3
07-28 12:05:31.499  8295  8295 I Avrcp   : Add tempPlayer
,07-28 12:05:31.499  8295  8295 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-28 12:05:31.499  8295  8295 I Avrcp   : Total no of players: 4
07-28 12:05:31.499  8295  8295 V Avrcp   : swapping the samsung player with 1st player
07-28 12:05:31.499  8295  8295 I Avrcp   :  Updating now playing list upon AVRCP Start
,07-28 12:05:31.499  8295  8337 V Avrcp   : handleMessage, msg=207
07-28 12:05:31.499  8295  8337 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,07-28 12:05:31.499  8295  8295 I BluetoothA2dpServiceJni: classInitNative: succeeds
,07-28 12:05:31.499  8295  8295 D A2dpStateMachine: make
,07-28 12:05:31.509  8295  8295 I bluedroid: get_profile_interface a2dp
,07-28 12:05:31.509  8295  8339 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-28 12:05:31.509  8295  8295 E bt-btif : warning : media task started media_task_refcnt 1 
,07-28 12:05:31.509  8295  8337 D BluetoothMediaBrowser: no now playing list
,07-28 12:05:31.509  8295  8337 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
07-28 12:05:31.509  8295  8337 D Avrcp   :  checkNowPlayingList start
,07-28 12:05:31.509  8295  8295 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c7e9b30
,07-28 12:05:31.509  8295  8295 I BluetoothHidServiceJni: classInitNative: succeeds
,07-28 12:05:31.509  8295  8338 D A2dpStateMachine: Enter Disconnected: -2
,07-28 12:05:31.509  8295  8295 D HidService: Received start request. Starting profile...
07-28 12:05:31.509  8295  8295 I bluedroid: get_profile_interface hidhost
07-28 12:05:31.509  8295  8295 D HidService: setHidService(): set to: null
07-28 12:05:31.509  8295  8295 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c7e9b30
07-28 12:05:31.509  8295  8295 E BluetoothAdapterService(1014930224): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,07-28 12:05:31.509  8295  8295 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-28 12:05:31.509  8295  8295 D HealthService: Received start request. Starting profile...
,07-28 12:05:31.509  8295  8295 I bluedroid: get_profile_interface health
,07-28 12:05:31.509  8295  8295 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c7e9b30
,07-28 12:05:31.509  8295  8295 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-28 12:05:31.519  8295  8295 D PanService: Received start request. Starting profile...
07-28 12:05:31.519  8295  8295 D BluetoothPanServiceJni: initializeNative(L110): pan
07-28 12:05:31.519  8295  8295 I bluedroid: get_profile_interface pan
,07-28 12:05:31.519  8295  8295 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c7e9b30
,07-28 12:05:31.519  8295  8295 D BluetoothMapService: Received start request. Starting profile...
,07-28 12:05:31.539  8295  8295 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c7e9b30
,07-28 12:05:31.539  8295  8295 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,07-28 12:05:31.539  8295  8295 D SapService: Received start request. Starting profile...
07-28 12:05:31.539  8295  8295 D BluetoothSAPServiceJni: initializeNative(L209): sap
07-28 12:05:31.539  8295  8295 I bluedroid: get_profile_interface sap
07-28 12:05:31.539  8295  8295 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c7e9b30
,07-28 12:05:31.539  8295  8295 D HeadsetStateMachine: Try to query the phonestate on bind
07-28 12:05:31.549  1406  1434 I Telecom : BluetoothPhoneService: queryPhoneState
,07-28 12:05:31.549  1406  1406 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
07-28 12:05:31.549  8295  8295 D HeadsetStateMachine: Proxy object connected
,07-28 12:05:31.549  8295  8295 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
07-28 12:05:31.549  8295  8295 D HeadsetPhoneState: sendDeviceDataStateChanged
07-28 12:05:31.549  8295  8325 D HeadsetStateMachine: Disconnected process message: 11
07-28 12:05:31.549  8295  8325 D HeadsetStateMachine: Disconnected process message: 18
07-28 12:05:31.549  8295  8295 D HeadsetPhoneState: Signal level : previous=0 curr=0
07-28 12:05:31.549  8295  8295 E BluetoothAdapterService(1014930224): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,07-28 12:05:31.549  8295  8295 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-28 12:05:31.549  8295  8325 D HeadsetStateMachine: Disconnected process message: 10
07-28 12:05:31.549  8295  8295 D BluetoothA2dp: Proxy object connected
07-28 12:05:31.549  8295  8295 D BluetoothAdapterService: Bluetooth A2dp source service connected
07-28 12:05:31.549  8295  8325 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
07-28 12:05:31.549  8295  8325 D HeadsetStateMachine: Disconnected process message: 11
,07-28 12:05:31.549  8295  8295 E BluetoothAdapterService(1014930224): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
07-28 12:05:31.549  8295  8295 E BluetoothAdapterService(1014930224): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
07-28 12:05:31.549  8295  8295 E BluetoothAdapterService(1014930224): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,07-28 12:05:31.549  8295  8295 E BluetoothAdapterService(1014930224): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,07-28 12:05:31.549  8295  8295 E BluetoothAdapterService(1014930224): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
07-28 12:05:31.549  8295  8295 E BluetoothAdapterService(1014930224): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,07-28 12:05:31.549  8295  8315 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
07-28 12:05:31.549  8295  8315 I bluedroid: enable
07-28 12:05:31.549  8295  8344 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,07-28 12:05:31.549  8295  8315 I bt_hci_bdroid: init
,07-28 12:05:31.549  8295  8315 I bt_vendor: init
07-28 12:05:31.549  8295  8315 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-28 12:05:31.549  8295  8315 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
07-28 12:05:31.549  8295  8315 D bt_userial: userial_init
07-28 12:05:31.549  8295  8315 D bt_vendor: op for 5
,07-28 12:05:31.559  8295  8315 D bt_vendor: op for 0
07-28 12:05:31.559  8295  8315 D bt_upio : upio_set_bluetooth_power(on: 0)
07-28 12:05:31.559  8295  8315 D bt_upio : is_emulator_context : 0
07-28 12:05:31.559  8295  8315 D bt_upio : is_rfkill_disabled ? [0]
07-28 12:05:31.559  8295  8315 D bt_upio : is_rfkill_disabled ? [0]
07-28 12:05:31.559  8295  8315 D bt_vendor: op for 0
07-28 12:05:31.559  8295  8315 D bt_upio : upio_set_bluetooth_power(on: 1)
07-28 12:05:31.559  8295  8315 D bt_upio : is_emulator_context : 0
07-28 12:05:31.559  8295  8315 D bt_upio : is_rfkill_disabled ? [0]
,07-28 12:05:31.559  8295  8346 D bt_vendor: op for 3
07-28 12:05:31.559  8295  8346 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-28 12:05:31.559  8295  8346 I bt_userial_vendor: userial_vendor_open():UART is setup
07-28 12:05:31.559  8295  8346 I bt_userial_vendor: device fd = 65 open
,07-28 12:05:31.559  8295  8346 D bt_vendor: op for 1
07-28 12:05:31.559  8295  8346 E bt_hwcfg: Start CFG HW, HCI reset
07-28 12:05:31.559  8295  8348 D bt_userial: Entering userial_read_thread()
,07-28 12:05:31.589   364   364 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:05:31.639  8295  8346 E bt_hwcfg: Read Local Name after HCI reset
,07-28 12:05:31.659  8295  8346 D bt_hwcfg: Chipset BCM4335C0
07-28 12:05:31.659  8295  8346 D bt_hwcfg: Target name = [BCM4335C0]
,07-28 12:05:31.659  8295  8346 I bt_hwcfg: module_type[semco].
07-28 12:05:31.659  8295  8346 I bt_hwcfg: not ZERO...
07-28 12:05:31.659  8295  8346 I bt_hwcfg: module_type[semco] is invalid.
07-28 12:05:31.659  8295  8346 E bt_hwcfg: patchram path ORG . BCM4335C0
07-28 12:05:31.659  8295  8346 E bt_hwcfg: patchram path ORG .. BCM4335C0
07-28 12:05:31.659  8295  8346 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
07-28 12:05:31.659  8295  8346 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
07-28 12:05:31.659  8295  8346 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
07-28 12:05:31.659  8295  8346 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
07-28 12:05:31.659  8295  8346 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335C0
07-28 12:05:31.659  8295  8346 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559_wisol.hcd BCM4335C0
07-28 12:05:31.659  8295  8346 E bt_hwcfg: fw ver (org)0.0
07-28 12:05:31.659  8295  8346 E bt_hwcfg: vendor lib preload failed to locate firmware patch file
07-28 12:05:31.659  8295  8346 E bt_hwcfg: Remove module rev, try again BCM4335
07-28 12:05:31.659  8295  8346 D bt_hwcfg: Target name = [BCM4335]
07-28 12:05:31.659  8295  8346 I bt_hwcfg: module_type[semco].
07-28 12:05:31.659  8295  8346 I bt_hwcfg: not ZERO...
07-28 12:05:31.659  8295  8346 I bt_hwcfg: module_type[semco] is invalid.
07-28 12:05:31.659  8295  8346 E bt_hwcfg: patchram path ORG . BCM4335
07-28 12:05:31.659  8295  8346 E bt_hwcfg: patchram path ORG .. BCM4335
07-28 12:05:31.659  8295  8346 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335
07-28 12:05:31.659  8295  8346 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
07-28 12:05:31.659  8295  8346 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335
07-28 12:05:31.659  8295  8346 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
07-28 12:05:31.659  8295  8346 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335
07-28 12:05:31.659  8295  8346 I bt_hwcfg: patch(org) : bcm4335_V0111.0559.hcd
07-28 12:05:31.659  8295  8346 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4335_V0111.0559.hcd
07-28 12:05:31.659  8295  8346 E bt_hwcfg: ORG patchram base 0111
07-28 12:05:31.659  8295  8346 E bt_hwcfg: ORG patchram minor 0559
07-28 12:05:31.659  8295  8346 E bt_hwcfg: fw ver (org)111.559
07-28 12:05:31.659  8295  8346 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4335_V0111.0559.hcd
,07-28 12:05:31.679  8295  8346 I bt_hwcfg: Axi patch failure or not include AXI patching
,07-28 12:05:31.679  8295  8346 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-28 12:05:32.179  8295  8346 I bt_hwcfg: bt vendor lib: set UART baud 115200,
,07-28 12:05:32.179  8295  8346 I bt_hwcfg: FW Download delta = 541821
,07-28 12:05:32.179  8295  8346 D bt_hwcfg: Settlement delay -- 100 ms
07-28 12:05:32.179  8295  8346 I bt_hwcfg: Setting fw settlement delay to 100 
,07-28 12:05:32.289  8295  8346 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-28 12:05:32.329  8295  8346 I bt_hwcfg: vendor lib fwcfg completed
,07-28 12:05:32.329  8295  8344 I         : BTE_InitTraceLevels -- TRC_HCI
,07-28 12:05:32.329  8295  8344 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-28 12:05:32.329  8295  8344 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-28 12:05:32.329  8295  8344 I         : BTE_InitTraceLevels -- TRC_AVDT
07-28 12:05:32.329  8295  8344 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-28 12:05:32.329  8295  8344 I         : BTE_InitTraceLevels -- TRC_A2D
07-28 12:05:32.329  8295  8344 I         : BTE_InitTraceLevels -- TRC_BNEP
07-28 12:05:32.329  8295  8344 I         : BTE_InitTraceLevels -- TRC_BTM
07-28 12:05:32.329  8295  8344 I         : BTE_InitTraceLevels -- TRC_GAP
07-28 12:05:32.329  8295  8344 I         : BTE_InitTraceLevels -- TRC_PAN
,07-28 12:05:32.329  8295  8344 I         : BTE_InitTraceLevels -- TRC_SAP
07-28 12:05:32.339  8295  8344 I         : BTE_InitTraceLevels -- TRC_SDP
,07-28 12:05:32.339  8295  8344 I         : BTE_InitTraceLevels -- TRC_GATT
07-28 12:05:32.339  8295  8344 I         : BTE_InitTraceLevels -- TRC_SMP
07-28 12:05:32.339  8295  8344 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-28 12:05:32.339  8295  8344 I         : BTE_InitTraceLevels -- TRC_BTIF
,07-28 12:05:32.339  8295  8344 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,07-28 12:05:32.559  8295  8344 W bt-l2cap: l2c_link_processs_ble_num_bufs 15
,07-28 12:05:32.569  8295  8344 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xaf818b5d 
,07-28 12:05:32.569  8295  8344 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xaf818b5d 
,07-28 12:05:32.589   364   364 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:05:32.779  8295  8318 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 1 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
,07-28 12:05:32.779  8295  8318 E bt-btif : Calling BTA_HhEnable
,07-28 12:05:32.779  8295  8318 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
07-28 12:05:32.779  8295  8318 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
,07-28 12:05:32.789  8295  8318 E BluetoothServiceJni: populateRssiValuesNative
07-28 12:05:32.789  8295  8318 I bluedroid: getModelRssiValues
07-28 12:05:32.789  8295  8318 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
07-28 12:05:32.789  8295  8318 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-28 12:05:32.789   906   906 D SettingsProvider: name = bluetooth_name
,07-28 12:05:32.789  8295  8318 D BluetoothAdapterProperties: Name is: Note3-1
,07-28 12:05:32.789  8295  8318 D BluetoothAdapterProperties: Scan Mode:20
,07-28 12:05:32.789  8295  8318 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-28 12:05:32.789  8295  8318 D BluetoothAdapterProperties: LE Address is:E0:B7:20:3E:93:BC
07-28 12:05:32.789  8295  8318 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
07-28 12:05:32.789  8295  8318 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,07-28 12:05:32.789  8295  8346 D bt_vendor: op for 2
,07-28 12:05:32.789  8295  8318 E bt-btif : btif_sock_init: !radio_req && !rfc_init
07-28 12:05:32.789  8295  8346 D bt_vendor: op for 6
,07-28 12:05:32.789  8295  8346 D bt_vendor: op for 7
07-28 12:05:32.789  8295  8318 E bt-btif : btif_sock_init: !vhci_init
,07-28 12:05:32.789  8295  8318 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
07-28 12:05:32.789  8295  8346 D bt_upio : proc btwrite assertion
,07-28 12:05:32.789  8295  8318 D IOP_DB_BT: db_open: db_open : handle 3026268176l, read 14063 bytes onto local cache
07-28 12:05:32.789  8295  8318 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,07-28 12:05:32.789  8295  8346 D bt_vendor: op for 7
,07-28 12:05:32.799  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.799  8295  8346 D bt_vendor: op for 7
07-28 12:05:32.799  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.799  8295  8318 D IOP_DB_BT: db_query: result 1
07-28 12:05:32.799  8295  8318 I         : iop_db_open: iop_db_open status 0
,07-28 12:05:32.799  8295  8318 D bte_conf: Device ID record 1 : primary
07-28 12:05:32.799  8295  8318 D bte_conf:   vendorId            = 0075
07-28 12:05:32.799  8295  8318 D bte_conf:   vendorIdSource      = 0001
07-28 12:05:32.799  8295  8318 D bte_conf:   product             = 0100
,07-28 12:05:32.799  8295  8318 D bte_conf:   version             = 0200
07-28 12:05:32.799  8295  8318 D bte_conf:   clientExecutableURL = 
07-28 12:05:32.799  8295  8318 D bte_conf:   serviceDescription  = 
07-28 12:05:32.799  8295  8318 D bte_conf:   documentationURL    = 
,07-28 12:05:32.799  8295  8318 D bte_conf: bte_load_did_conf no section named DID2.
,07-28 12:05:32.799  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:32.799  8295  8315 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-28 12:05:32.799  8295  8315 D BluetoothAdapterProperties: ScanMode =  20
,07-28 12:05:32.799  8295  8315 D BluetoothAdapterProperties: State =  11
,07-28 12:05:32.799   906  3355 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,07-28 12:05:32.809  8295  8318 D BluetoothAdapterProperties: Scan Mode:21
,07-28 12:05:32.809  8295  8318 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-28 12:05:32.809  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:32.809  8295  8315 D BluetoothAdapterProperties: Setting state to 12
07-28 12:05:32.809  8295  8315 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-28 12:05:32.809   906  1143 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,07-28 12:05:32.809   906  1143 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:05:32.809   906  1143 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:05:32.809   906  1143 D SettingsProvider: selectionArgs: false
07-28 12:05:32.809   906  1143 D SettingsProvider: selectionArgs: 1002
,07-28 12:05:32.809   906  1143 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:05:32.809   906  1143 D SettingsProvider: ret = -1
,07-28 12:05:32.809  8295  8315 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-28 12:05:32.809  8295  8315 D BluetoothAdapterService: updateAdapterState state is 12
,07-28 12:05:32.809   906  1663 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:05:32.809   906  1663 D ActivityManager: caller:android.app.ApplicationThreadProxy@3ac33e0, r.packageName :com.android.bluetooth
,07-28 12:05:32.819  8295  8346 E bt_h4   : vendor lib postload completed
,07-28 12:05:32.829  8295  8295 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,07-28 12:05:32.829  8295  8295 I BluetoothPbapService: Handler(): got msg=1
,07-28 12:05:32.829   906   923 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-28 12:05:32.839  8295  8315 D BluetoothAdapterService: Autoconnection is available 
,07-28 12:05:32.839  8295  8315 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,07-28 12:05:32.839  8295  8315 D BluetoothAdapterService: starting service from this receiver
,07-28 12:05:32.839  8295  8346 D bt_vendor: op for 7
07-28 12:05:32.839  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.839  8295  8318 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-28 12:05:32.839  8295  8346 D bt_vendor: op for 7
,07-28 12:05:32.839  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.849  8295  8346 D bt_vendor: op for 7
,07-28 12:05:32.849  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.849  8295  8346 D bt_vendor: op for 7
,07-28 12:05:32.849  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.849  8295  8361 V BluetoothPbapService: PBAP Service initSocket try: 0
,07-28 12:05:32.849  8295  8346 D bt_vendor: op for 7
07-28 12:05:32.849  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.849  8295  8346 D bt_vendor: op for 7
,07-28 12:05:32.849  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.849  8295  8346 D bt_vendor: op for 7
07-28 12:05:32.849  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.849  8295  8361 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:05:32.859  8295  8346 D bt_vendor: op for 7
,07-28 12:05:32.859  8295  8346 D bt_upio : BT_WAKE is asserted already
07-28 12:05:32.859  8295  8361 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
07-28 12:05:32.859  8295  8361 D BluetoothSocket: bindListen(), new LocalSocket 
07-28 12:05:32.859  8295  8361 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,07-28 12:05:32.859  8295  8361 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39f14843
07-28 12:05:32.859  8295  8361 D BluetoothSocket: channel: 19
07-28 12:05:32.859  8295  8361 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,07-28 12:05:32.859  8295  8346 D bt_vendor: op for 7
07-28 12:05:32.859  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.859  8295  8346 D bt_vendor: op for 7
,07-28 12:05:32.859  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.859  8295  8346 D bt_vendor: op for 7
07-28 12:05:32.859  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.859  8295  8346 D bt_vendor: op for 7
,07-28 12:05:32.859  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.859  8295  8346 D bt_vendor: op for 7
07-28 12:05:32.859  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.869  8295  8346 D bt_vendor: op for 7
07-28 12:05:32.869  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.869  8295  8346 D bt_vendor: op for 7
,07-28 12:05:32.869  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.869  8295  8346 D bt_vendor: op for 7
,07-28 12:05:32.869  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.869  8295  8346 D bt_vendor: op for 7
07-28 12:05:32.869  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.869  8295  8346 D bt_vendor: op for 7
07-28 12:05:32.869  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.889  8295  8346 D bt_vendor: op for 7
,07-28 12:05:32.889  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.889  8295  8346 D bt_vendor: op for 7
,07-28 12:05:32.889  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.889  8295  8346 D bt_vendor: op for 7
,07-28 12:05:32.889  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.889  8295  8346 D bt_vendor: op for 7
,07-28 12:05:32.889  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.889  8295  8346 D bt_vendor: op for 7
,07-28 12:05:32.889  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.899  8295  8346 D bt_vendor: op for 7
07-28 12:05:32.899  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.899  8295  8346 D bt_vendor: op for 7
,07-28 12:05:32.899  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.899  8295  8346 D bt_vendor: op for 7
07-28 12:05:32.899  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.899  8295  8346 D bt_vendor: op for 7
,07-28 12:05:32.899  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:32.949   906  1030 I art     : Explicit concurrent mark sweep GC freed 51793(2MB) AllocSpace objects, 3(48KB) LOS objects, 30% free, 37MB/53MB, paused 1.281ms total 110.329ms
,07-28 12:05:32.949   906  1030 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:05:32.949   906  1243 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:05:32.949   906  1243 D ActivityManager: caller:android.app.ApplicationThreadProxy@39d0ae0c, r.packageName :com.android.bluetooth
,07-28 12:05:32.949  1306  1318 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:05:32.949  3196  8223 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 12:05:32.949  1306  1306 D HeadsetProfile: Bluetooth service connected
,07-28 12:05:32.949   906  1030 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-28 12:05:32.949  3196  3196 D BluetoothA2dp: Proxy object connected
07-28 12:05:32.949  8295  8315 I BluetoothAdapterState: Entering On State from state = 11
,07-28 12:05:32.959  8295  8304 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 12:05:32.959   906  1030 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:05:32.959  7666  7680 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:05:32.959   906  1030 D BluetoothPan: Binding service...
07-28 12:05:32.959   906  1030 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,07-28 12:05:32.969   906  1030 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:05:32.969  1428  2438 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:05:32.969   906   906 D BluetoothPan: BluetoothPAN Proxy object connected
,07-28 12:05:32.969   906  1030 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:05:32.969  3196  3208 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:05:32.969  1306  1315 D BluetoothPan: Binding service...
,07-28 12:05:32.969   906  1030 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,07-28 12:05:32.969  1306  1306 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:05:32.969  1306  1306 D PanProfile: Bluetooth service connected
07-28 12:05:32.969  1306  1328 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 12:05:32.969   906  1030 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-28 12:05:32.969  1306  1315 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-28 12:05:32.969  1306  1306 D BluetoothA2dp: Proxy object connected
07-28 12:05:32.969   906  1030 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
07-28 12:05:32.969  1306  1306 D A2dpProfile: Bluetooth service connected
,07-28 12:05:32.969  1306  1318 D BluetoothMap: onBluetoothStateChange: up=true
,07-28 12:05:32.969   906  1030 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,07-28 12:05:32.979   906  1030 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:05:32.979  1306  1306 D BluetoothInputDevice: Proxy object connected
07-28 12:05:32.979  1306  1306 D HidProfile: Bluetooth service connected
07-28 12:05:32.979   906  1030 E BluetoothHeadset: BluetoothHeadset service is binded
07-28 12:05:32.979   906  1030 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:05:32.979   906  1030 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-28 12:05:32.979   906  1030 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:05:32.979   906   906 D BluetoothA2dp: Proxy object connected
,07-28 12:05:32.979  1406  1434 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:05:32.979  1306  1306 D BluetoothMap: Proxy object connected
07-28 12:05:32.979   906  1030 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
07-28 12:05:32.979  1306  1306 D MapProfile: Bluetooth service connected
,07-28 12:05:32.979  1406  3090 E BluetoothHeadset: BluetoothHeadset service is binded
07-28 12:05:32.979  1306  1318 D Bluetoothsap: onBluetoothStateChange: up=true
,07-28 12:05:32.979  1306  1318 D Bluetoothsap: Binding service...
,07-28 12:05:32.979  1306  1318 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,07-28 12:05:32.979   906  1030 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
07-28 12:05:32.979  1306  1318 D Bluetoothsap: bindService called to Bluetooth SAP Service
07-28 12:05:32.979  1306  1315 D BluetoothPbap: onBluetoothStateChange: up=true
,07-28 12:05:32.979  1306  1306 D Bluetoothsap: BluetoothSAP Proxy object connected
07-28 12:05:32.979  1306  1306 D SapProfile: Bluetooth service connected
07-28 12:05:32.979  1306  1306 D Bluetoothsap: getConnectedDevices()
,07-28 12:05:32.979   906  1030 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,07-28 12:05:32.989  1306  1306 D BluetoothPbap: Proxy object connected
07-28 12:05:32.989  1306  1306 D PbapServerProfile: Bluetooth service connected
,07-28 12:05:32.989   906  1030 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:05:32.989  1406  3091 E BluetoothHeadset: BluetoothHeadset service is binded
07-28 12:05:32.989   906  1030 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,07-28 12:05:32.989  1195  1195 D BluetoothTile:  onBluetoothStateChange:
,07-28 12:05:32.989  1724  1724 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-28 12:05:32.989  1195  1195 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-28 12:05:32.989   906   906 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:32.989   906   906 I InputMethodManagerService: [BT Setting State] State =12
07-28 12:05:32.989   906   906 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-28 12:05:32.989  1195  1195 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:05:32.989   906  1361 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-28 12:05:32.989   906  1361 D ActivityManager: caller:android.app.ApplicationThreadProxy@2e134e0f, r.packageName :com.google.android.gms
,07-28 12:05:32.999   906  1030 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,07-28 12:05:32.999  7666  7666 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:05:32.999  1306  1306 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:05:32.999  8295  8373 D BluetoothMapMasInstance: set MAP SDP message type : 1
,07-28 12:05:32.999  1406  1406 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@ae12645, true
,07-28 12:05:32.999  1406  1406 D BluetoothHeadset: registerMessageListener
,07-28 12:05:32.999  8295  8373 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:05:32.999  8295  8303 D HeadsetService: registerMessageListener
,07-28 12:05:32.999  8295  8303 D HeadsetService: registerMessageListener
,07-28 12:05:32.999  8295  8325 D HeadsetStateMachine: Disconnected process message: 70
07-28 12:05:32.999  1406  1406 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
07-28 12:05:32.999   906   924 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:05:32.999  1406  1406 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
07-28 12:05:32.999  8295  8325 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@21b0854a
07-28 12:05:32.999   906  1143 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
07-28 12:05:32.999  1195  1195 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:05:32.999  8295  8373 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
07-28 12:05:32.999  8295  8346 D bt_vendor: op for 7
07-28 12:05:32.999  8295  8373 D BluetoothSocket: bindListen(), new LocalSocket 
07-28 12:05:32.999  8295  8346 D bt_upio : BT_WAKE is asserted already
07-28 12:05:32.999  8295  8373 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
,07-28 12:05:32.999  8295  8373 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2017cbb
07-28 12:05:32.999  8295  8373 D BluetoothSocket: channel: 5
,07-28 12:05:33.009  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:33.009  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:33.009  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:33.009  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:05:33.009  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:33.009  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:33.009  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:33.009  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:05:33.009  1195  1583 D BluetoothTile:  handleUpdatestate:false name:null
07-28 12:05:33.009  1195  1583 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-28 12:05:33.009  7508  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:05:33.009  8295  8325 D HeadsetStateMachine: Disconnected process message: 9
,07-28 12:05:33.009  1306  1306 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
07-28 12:05:33.009  1306  1306 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,07-28 12:05:33.009  8295  8325 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,07-28 12:05:33.009   317   317 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
07-28 12:05:33.009  1306  1306 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
07-28 12:05:33.009   317   317 V voice   : voice_set_parameters: enter: A2dpSuspended=false
07-28 12:05:33.009   317   317 V voice   : voice_set_parameters: exit with code(-2)
07-28 12:05:33.009   317   317 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
07-28 12:05:33.009   317   317 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-28 12:05:33.009   906   923 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-28 12:05:33.009   317   317 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-28 12:05:33.009   317   317 V audio_hw_primary: adev_set_parameters: exit
07-28 12:05:33.009   906   923 D ActivityManager: caller:android.app.ApplicationThreadProxy@5505c7a, r.packageName :com.android.settings
,07-28 12:05:33.019  8295  8325 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,07-28 12:05:33.019  1306  1306 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:05:33.019  1306  1306 D BluetoothNotiBroadcastReceiver: onReceive
,07-28 12:05:33.019  8295  8295 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c7e9b30
07-28 12:05:33.019  8295  8295 D BtConfig.SecureMode: isSecureModeOn:false
,07-28 12:05:33.019   906  3331 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:05:33.019   906  3331 D ActivityManager: caller:android.app.ApplicationThreadProxy@12a76888, r.packageName :com.android.bluetooth
,07-28 12:05:33.049   906  1663 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-28 12:05:33.059  8295  8382 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:05:33.059  8295  8346 D bt_vendor: op for 7
07-28 12:05:33.059  8295  8346 D bt_upio : BT_WAKE is asserted already
,07-28 12:05:33.059  8295  8382 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
07-28 12:05:33.059  8295  8382 D BluetoothSocket: bindListen(), new LocalSocket 
,07-28 12:05:33.069  8295  8382 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-28 12:05:33.069  8295  8382 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@8a8fb6d
07-28 12:05:33.069  8295  8382 D BluetoothSocket: channel: 12
07-28 12:05:33.069  8295  8382 I BtOppRfcommListener: Accept thread started.
,07-28 12:05:33.089  1922  1922 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-28 12:05:33.099   906   923 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-28 12:05:33.099   906   923 D ActivityManager: caller:android.app.ApplicationThreadProxy@2a7cbf5d, r.packageName :com.google.android.gms
,07-28 12:05:33.099  7508  7576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:33.099  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:33.099  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:33.099  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:05:33.099  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:33.099  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:33.099  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:33.099  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:05:33.099  7508  7576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:05:33.099  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:33.099  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37b40e1c added. We now have 8 listener(s)
07-28 12:05:33.099  7508  7576 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:05:33.109  7508  7576 I WifiManager: packageName : com.test.thalitest
,07-28 12:05:33.109   906  3355 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-28 12:05:33.109   906  3355 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-28 12:05:33.109   906  3355 D SecContentProvider2: mCursor = null
,07-28 12:05:33.109  1922  8385 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-28 12:05:33.109   906  3355 D WifiService: setWifiEnabled: false pid=7508, uid=10079
07-28 12:05:33.109   906  3355 D SettingsProvider: name = wifi_on
,07-28 12:05:33.109  1922  1922 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-28 12:05:33.119  7508  7576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:33.119  7508  7576 I WifiManager: packageName : com.test.thalitest
07-28 12:05:33.119   906  1462 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-28 12:05:33.119   906  1462 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-28 12:05:33.119   906  1462 D SecContentProvider2: mCursor = null
,07-28 12:05:33.119   906  1462 D WifiService: setWifiEnabled: true pid=7508, uid=10079
07-28 12:05:33.119   906  1462 W ActivityManager: Permission Denial: getCurrentUser() from pid=7508, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-28 12:05:33.119   906  1462 W WifiService: Failed getting userId using ActivityManagerNative
07-28 12:05:33.119   906  1462 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7508, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-28 12:05:33.119   906  1462 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-28 12:05:33.119   906  1462 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-28 12:05:33.119   906  1462 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-28 12:05:33.119   906  1462 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-28 12:05:33.119   906  1462 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,07-28 12:05:33.119   906  1462 D SettingsProvider: name = wifi_on
,07-28 12:05:33.119   906  1148 E WifiHW  : ##################### set firmware type 0 #####################
,07-28 12:05:33.119   906  1709 D ActivityManager: caller:android.app.ApplicationThreadProxy@3bb3581e, r.packageName :com.google.android.gms
,07-28 12:05:33.119   294  1067 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
07-28 12:05:33.119   294  1067 I WifiHW  : module is semco
07-28 12:05:33.119   294  1067 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-28 12:05:33.119   294  1067 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-28 12:05:33.119   294  1067 E WifiHW  : TEMP_FAILURE_RETRY complete
07-28 12:05:33.119   294  1067 D SoftapController: Softap fwReload - Ok
,07-28 12:05:33.129   294  1067 D CommandListener: Setting iface cfg
07-28 12:05:33.129   294  1067 D CommandListener: Trying to bring down wlan0
,07-28 12:05:33.129   294  1067 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:05:33.129  1922  8385 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-28 12:05:33.129   906  1148 E WifiHW  : supplicant_name : p2p_supplicant
,07-28 12:05:33.159  8389  8389 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-28 12:05:33.159  8389  8389 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-28 12:05:33.159  8389  8389 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-28 12:05:33.159  8389  8389 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-28 12:05:33.159   376   376 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8389
07-28 12:05:33.159   376   376 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-28 12:05:33.159  8389  8389 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-28 12:05:33.159  8389  8389 I wpa_supplicant: ssSupport state is = 1
,07-28 12:05:33.159  8389  8389 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,07-28 12:05:33.159  8389  8389 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-28 12:05:33.159   376   376 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8389
07-28 12:05:33.159   376   376 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,07-28 12:05:33.229   906  1148 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-28 12:05:33.229   906   906 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:05:33.229  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:05:33.229  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,07-28 12:05:33.229  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:05:33.229  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
07-28 12:05:33.229  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:05:33.239  1195  1583 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-28 12:05:33.239   906  1152 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-28 12:05:33.239  1195  1195 D HotspotTile: onReceive : 2, 0
07-28 12:05:33.239  1306  1306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:05:33.239  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:33.239  7109  7109 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-28 12:05:33.239   906  1462 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:33.239  6639  6639 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:05:33.239  6639  6639 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:05:33.239  6639  6639 D SecurityLogAgent: StateMachine : Current State = 1
,07-28 12:05:33.239  6639  6639 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:05:33.249   906  3093 D SSRM:n  : SIOP:: AP = 350, PST = 362, CUR = 450
,07-28 12:05:33.429   376   376 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,07-28 12:05:33.589   364   364 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:05:33.689  8389  8389 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,07-28 12:05:33.739  8389  8389 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,07-28 12:05:33.739  8389  8389 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-28 12:05:33.739   376   376 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8389
07-28 12:05:33.739   376   376 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,07-28 12:05:33.739  8389  8389 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-28 12:05:33.739  8389  8389 I wpa_supplicant: ssSupport state is = 1
07-28 12:05:33.739  8389  8389 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,07-28 12:05:33.739  8389  8389 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-28 12:05:33.739  8389  8389 E wpa_supplicant: SIM READ ERROR
07-28 12:05:33.739  8389  8389 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:05:33.739  8389  8389 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-28 12:05:33.739  8389  8389 E wpa_supplicant: SIM READ ERROR
07-28 12:05:33.739  8389  8389 I wpa_supplicant: Blacklist: Clear (all) 
,07-28 12:05:33.749  8389  8389 I wpa_supplicant: wpa_default_ap_write_once
07-28 12:05:33.749  8389  8389 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
,07-28 12:05:33.749  8389  8389 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:05:33.749  8389  8389 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
07-28 12:05:33.749  8389  8389 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:05:33.749  8389  8389 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-28 12:05:33.749  8389  8389 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-28 12:05:34.389   301   301 E SMD     : DCD ON
,07-28 12:05:34.399   906  1151 E Tethering: No numeric data
,07-28 12:05:34.399   906  1151 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-28 12:05:34.409   906  1145 V NetworkStats: performPollLocked(flags=0x1)
07-28 12:05:34.409   906  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:05:34.409   906  1145 D NetworkStatsFactory: UpdateStatsForKnox
,07-28 12:05:34.409   906  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:34.409  1195  1195 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-28 12:05:34.409  1195  1195 D HotspotTile: updateTetherState():false, false
,07-28 12:05:34.409   906  1145 V NetworkStats: performPollLocked() took 3ms
07-28 12:05:34.409   906  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:05:34.409   906  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:05:34.409   906  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:05:34.419  8389  8389 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,07-28 12:05:34.419  8389  8389 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-28 12:05:34.419  8389  8389 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-28 12:05:34.419  8389  8389 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-28 12:05:34.419   376   376 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8389
07-28 12:05:34.419   376   376 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,07-28 12:05:34.419  8389  8389 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-28 12:05:34.419  8389  8389 I wpa_supplicant: ssSupport state is = 1
,07-28 12:05:34.419  8389  8389 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-28 12:05:34.419  8389  8389 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-28 12:05:34.419   376   376 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8389
07-28 12:05:34.419   376   376 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
07-28 12:05:34.419  8389  8389 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-28 12:05:34.429  8389  8389 I wpa_supplicant: ssSupport state is = 1
,07-28 12:05:34.429  8389  8389 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:05:34.429  8389  8389 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-28 12:05:34.429  8389  8389 E wpa_supplicant: SIM READ ERROR
07-28 12:05:34.429  8389  8389 I wpa_supplicant: wpa_default_ap_write_once
,07-28 12:05:34.429  8389  8389 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-28 12:05:34.429  8389  8389 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-28 12:05:34.439  8389  8389 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
,07-28 12:05:34.439  8389  8389 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,07-28 12:05:34.439  8389  8389 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
,07-28 12:05:34.439  8389  8389 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,07-28 12:05:34.439   906  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,07-28 12:05:34.439   906  1148 D WifiNative-HAL: callSECApiBoolean - ID [21]
07-28 12:05:34.439  8389  8389 I wpa_supplicant: HOTSPOT20_ENABLE called
07-28 12:05:34.439  8389  8389 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:05:34.439  8389  8389 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-28 12:05:34.439  8389  8389 E wpa_supplicant: SIM READ ERROR
07-28 12:05:34.439  8389  8389 I wpa_supplicant: Blacklist: Clear (all) 
,07-28 12:05:34.469  8389  8389 I wpa_supplicant: Skip scan - bUseNetwork false
,07-28 12:05:34.469   906   906 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:05:34.469  1306  1306 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:05:34.469   906  1148 D WifiNative-HAL: callSECApiInt - ID [210]
,07-28 12:05:34.479  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:05:34.479  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-28 12:05:34.479   906  1152 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
07-28 12:05:34.479  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:34.479  1195  1195 D StatusBar.NetworkController: applyOpen
,07-28 12:05:34.479  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-28 12:05:34.479   906  1148 D WifiConfigStore: Loading config and enabling all networks 
07-28 12:05:34.479  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:34.479  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:34.479  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:34.479  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:34.479  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:34.479  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:34.479  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:34.479  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:34.479  7508  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:05:34.479  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:34.479  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:34.479  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:34.479  1195  1195 D StatusBar.NetworkController: applyOpen
,07-28 12:05:34.479  1195  1195 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:05:34.479  1195  1195 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
07-28 12:05:34.479  1195  1195 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:05:34.479  1195  1583 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-28 12:05:34.479  1195  1195 D HotspotTile: onReceive : 3, 0
,07-28 12:05:34.479  7508  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:05:34.489  7109  7109 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-28 12:05:34.489   906  1148 E WifiConfigStore: Not a HS20
,07-28 12:05:34.489   906  1435 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:34.489  6639  6639 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:05:34.489  6639  6639 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:05:34.489  6639  6639 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:05:34.489  6639  6639 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:05:34.499   906  1148 E WifiConfigStore: Not a HS20
,07-28 12:05:34.509   906  1148 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-28 12:05:34.509   906  1148 D WifiNative-HAL: callSECApiInt - ID [65]
,07-28 12:05:34.519   906  1148 D WifiNative-HAL: callSECApiBoolean - ID [13]
07-28 12:05:34.519  8389  8389 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-28 12:05:34.519  8389  8389 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,07-28 12:05:34.519  8389  8389 I wpa_supplicant: reset timer : RESET_TIMER 0
07-28 12:05:34.519  8389  8389 I wpa_supplicant: P2P: Current p2p state = IDLE
07-28 12:05:34.519  8389  8389 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
07-28 12:05:34.519  8389  8389 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
07-28 12:05:34.519  8389  8389 I wpa_supplicant: First Scan Start
,07-28 12:05:34.519  8389  8389 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-28 12:05:34.519  7692  7692 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:05:34.519   906  1148 D WifiNative-HAL: Setting external_sim to 1
,07-28 12:05:34.519   906  1148 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 12:05:34.519   906  1148 I WifiNative-HAL: startHal
07-28 12:05:34.519   906  1148 E wifi    : getStaticLongField sWifiHalHandle 0x932e186c
07-28 12:05:34.519   906  1148 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0xd0189a
07-28 12:05:34.519   906  1148 I WifiNative-HAL: Could not start hal
,07-28 12:05:34.539   906  1148 E native  : do suspend true
,07-28 12:05:34.539   906  1147 D WifiP2pService: P2pDisabledState{ what=131203 }
,07-28 12:05:34.539   906   906 D WifiScanningService: SCAN_AVAILABLE : 3
07-28 12:05:34.539   906   906 D RttService: SCAN_AVAILABLE : 3
07-28 12:05:34.539   906  1165 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:34.539   906  1165 I WifiNative-HAL: startHal
07-28 12:05:34.539   906  1165 E wifi    : getStaticLongField sWifiHalHandle 0x9ca3299c
,07-28 12:05:34.539   906  1166 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:34.539   906  1165 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x90184e
07-28 12:05:34.539   906  1165 I WifiNative-HAL: Could not start hal
07-28 12:05:34.539   906  1165 E WifiScanningService: could not start HAL
07-28 12:05:34.539   906  1148 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,07-28 12:05:34.539   294  1067 D CommandListener: Setting iface cfg
07-28 12:05:34.539   294  1067 D CommandListener: Trying to bring up p2p0
07-28 12:05:34.539   906  1147 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-28 12:05:34.539   906  1147 D WifiP2pService: P2pEnablingState
07-28 12:05:34.539   906  1147 D WifiP2pService: P2pEnablingState{ what=147457 }
,07-28 12:05:34.539   906  1147 D WifiP2pService: P2p socket connection successful
07-28 12:05:34.539   906  1147 D WifiP2pService: P2pEnabledState
,07-28 12:05:34.539   906   906 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,07-28 12:05:34.539   906  1031 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-28 12:05:34.539   906  1031 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-28 12:05:34.539   906  1031 D WifiDisplayController: disconnect
07-28 12:05:34.539   906  1031 D WifiDisplayController: updateConnection
07-28 12:05:34.539   906  1031 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,07-28 12:05:34.549   906  1031 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-28 12:05:34.549   906  1147 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-28 12:05:34.549  1195  1195 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,07-28 12:05:34.549   906   923 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-28 12:05:34.549  1195  1195 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-28 12:05:34.549  7720  7720 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-28 12:05:34.549   906  1031 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:34.549   906  1031 D WifiDisplayAdapter: onP2pDisconnected
,07-28 12:05:34.549   906  1031 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-28 12:05:34.549   906  1031 D IpRemoteDisplayController: WfdBridgeServer is already null
07-28 12:05:34.549   906  1150 E ConnectivityService: updateNetworkInfo()
,07-28 12:05:34.549   906  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,07-28 12:05:34.549   906  1147 D WifiNative-HAL: p2pGetDeviceAddress
,07-28 12:05:34.549   906  1148 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
07-28 12:05:34.549   906  1148 D WifiNative-HAL: callSECStringApiVoid - ID [215]
07-28 12:05:34.549   906  1148 E WifiNative-HAL: invaild command id : 215
,07-28 12:05:34.559  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-28 12:05:34.559   906  1147 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:de:28:a3
,07-28 12:05:34.559   906  1147 D WifiP2pService: DeviceAddress: ea:28:a3
07-28 12:05:34.559   906  1031 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
07-28 12:05:34.559   906  1031 D WifiDisplayController:  deviceAddress: ea:50:8b:de:28:a3
07-28 12:05:34.559   906  1031 D WifiDisplayController:  primary type: 10-0050F204-5
07-28 12:05:34.559   906  1031 D WifiDisplayController:  secondary type: null
07-28 12:05:34.559   906  1031 D WifiDisplayController:  wps: 0
07-28 12:05:34.559   906  1031 D WifiDisplayController:  grpcapab: 0
07-28 12:05:34.559   906  1031 D WifiDisplayController:  devcapab: 0
07-28 12:05:34.559   906  1031 D WifiDisplayController:  status: 3
07-28 12:05:34.559   906  1031 D WifiDisplayController:  wfdInfo: null
07-28 12:05:34.559   906  1031 D WifiDisplayController:  groupownerAddress: null
07-28 12:05:34.559   906  1031 D WifiDisplayController:  GOdeviceName: null
07-28 12:05:34.559   906  1031 D WifiDisplayController:  interfaceAddress: 
07-28 12:05:34.559   906  1031 D WifiDisplayController:  SConnectInfo : null
,07-28 12:05:34.559  1306  1306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-28 12:05:34.559   906  1541 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:34.559  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-28 12:05:34.559   906  3355 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:34.559  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:05:34.559  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:05:34.559  1306  1306 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:05:34.559  1306  2807 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:05:34.559  7219  7219 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-28 12:05:34.569  8295  8346 D bt_vendor: op for 7
,07-28 12:05:34.569  7720  7720 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-28 12:05:34.569  7720  7720 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,07-28 12:05:34.569  7720  7720 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-28 12:05:34.569  7720  7720 D WifiDirectBR: stopServiceTest : false
,07-28 12:05:34.579   906  1147 D WifiP2pService: sending p2p persistent groups changed broadcast
,07-28 12:05:34.579   906  1147 D WifiP2pService: InactiveState
,07-28 12:05:34.579   906  1147 D WifiP2pService: InactiveState{ what=143376 }
07-28 12:05:34.579   906  1147 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-28 12:05:34.589   364   364 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-28 12:05:34.599  8389  8389 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-28 12:05:34.599  8389  8389 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-28 12:05:34.609   906  1147 D WifiP2pService: InactiveState{ what=143376 }
,07-28 12:05:34.609   906  1147 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-28 12:05:34.629  8389  8389 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-28 12:05:34.629   906  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:05:34.629   906  1148 D SecContentProvider2: mCursor = null
,07-28 12:05:34.629   906  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:05:34.629   906  1148 D SecContentProvider2: mCursor = null
,07-28 12:05:34.759   906  1413 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-28 12:05:34.759   906  1413 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4320, temperature: 283, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-28 12:05:34.759   906  1413 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-28 12:05:34.759   906  1413 D BatteryService: stay LED for fully charged
07-28 12:05:34.759   906   906 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-28 12:05:34.759   906   906 I MotionRecognitionService: Plugged
07-28 12:05:34.759   906   906 I MotionRecognitionService: setPowerConnected  = true
,07-28 12:05:34.759  1195  1195 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-28 12:05:34.759  1195  1195 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-28 12:05:34.759  1195  1195 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-28 12:05:34.759  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-28 12:05:34.759  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:05:34.759  1195  1195 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:05:34.759  8295  8295 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-28 12:05:34.759  8295  8325 D HeadsetStateMachine: Disconnected process message: 10
,07-28 12:05:34.789  8295  8359 D bt_upio : ..proc_btwrite_timeout..
,07-28 12:05:35.139  7508  7576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:05:35.139  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:35.139  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:35.139  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:35.139  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:35.139  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:35.139  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:35.139  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:05:35.149  7508  7576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:05:35.159  7508  7576 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-28 12:05:35.159  7508  7576 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-28 12:05:35.159  7508  7576 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@2dc73060 Bundle[{}]
,07-28 12:05:35.169  7508  7576 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-28 12:05:35.169  7508  7576 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-28 12:05:35.169  7508  7576 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-28 12:05:35.169  7508  7576 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-28 12:05:35.169  7508  7576 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-28 12:05:35.169  7508  7576 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-28 12:05:35.179  7508  7576 I System.out: Running OutgoingSocketThread
,07-28 12:05:35.179  7508  8408 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1332)
,07-28 12:05:35.179  7508  8408 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 44878
,07-28 12:05:35.179  7508  8408 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-28 12:05:35.329  8389  8389 I wpa_supplicant: nl80211: Received scan results (19 BSSes)
07-28 12:05:35.329  8389  8389 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-28 12:05:35.329  8389  8389 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
07-28 12:05:35.329  8389  8389 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
07-28 12:05:35.329  8389  8389 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=5 BSSID=00.00.00 SSID=4E47373030
,07-28 12:05:35.349   906  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-28 12:05:35.349   906  1148 D SecContentProvider2: mCursor = null
,07-28 12:05:35.399  8389  8389 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
07-28 12:05:35.399  8389  8389 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=6 BSSID=00.00.00 SSID=4E47373030
07-28 12:05:35.399  8389  8389 I wpa_supplicant: Associated with F4.99.3E
07-28 12:05:35.399  8389  8389 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
07-28 12:05:35.399  8389  8389 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=7 BSSID=F4.99.3E SSID=4E47373030
07-28 12:05:35.399   906  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:05:35.399   906  1148 D SecContentProvider2: mCursor = null
07-28 12:05:35.409   906  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:05:35.409   906  1148 D SecContentProvider2: mCursor = null
07-28 12:05:35.409  8389  8389 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
07-28 12:05:35.419  8389  8389 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
07-28 12:05:35.419  8389  8389 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=8 BSSID=F4.99.3E SSID=4E47373030
,07-28 12:05:35.419  8389  8389 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:05:35.419  8389  8389 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
07-28 12:05:35.419  8389  8389 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=1 id_str=]
07-28 12:05:35.419  8389  8389 I wpa_supplicant: Blacklist: Clear (temp) 
07-28 12:05:35.419  8389  8389 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=9 BSSID=F4.99.3E SSID=4E47373030
,07-28 12:05:35.419   906  1148 D WifiNative-HAL: callSECApiVoid - ID [50]
,07-28 12:05:35.429  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:05:35.429  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:05:35.429   906  1148 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,07-28 12:05:35.429   906  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:05:35.429   906  1150 D ConnectivityService: Got NetworkAgent Messenger
07-28 12:05:35.429   906  1150 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,07-28 12:05:35.439   906  1150 E ConnectivityService: updateNetworkInfo()
07-28 12:05:35.439   906  1150 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-28 12:05:35.439   906  1150 D ConnectivityService: NetworkAgent connected
,07-28 12:05:35.439  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-28 12:05:35.439  1306  1306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-28 12:05:35.439   906  3064 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:35.439  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-28 12:05:35.449   906  1361 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:35.449  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:05:35.449  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:05:35.449  1306  1306 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-28 12:05:35.449  1306  2807 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:05:35.449   906  3355 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:35.449   906  1148 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:05:35.459  7109  7109 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:05:35.459   294  1067 D CommandListener: Setting iface cfg
,07-28 12:05:35.469   906  1148 E WifiStateMachine: Start Dhcp Watchdog 3
,07-28 12:05:35.469   906  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-28 12:05:35.469   906  1148 D SecContentProvider2: mCursor = null
,07-28 12:05:35.469  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:05:35.479  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:05:35.479   906  1150 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,07-28 12:05:35.559   906  1148 E native  : do suspend false
,07-28 12:05:35.559   906  1147 D WifiP2pService: InactiveState{ what=143375 }
07-28 12:05:35.559   906  1147 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-28 12:05:35.559   906  1148 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:05:35.559   906  1148 D SecContentProvider2: mCursor = null
,07-28 12:05:35.779  8421  8421 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-28 12:05:35.779  8421  8421 I dhcpcd  : version 5.5.6 starting
,07-28 12:05:35.779  8421  8421 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-28 12:05:35.849  8421  8421 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-28 12:05:35.849  8421  8421 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
07-28 12:05:35.849  8421  8421 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
07-28 12:05:35.849  8421  8421 I dhcpcd  : bssid match
07-28 12:05:35.849  8421  8421 I dhcpcd  : wlan0: rebinding lease of 192.168.1.122
,07-28 12:05:35.849  8421  8421 I dhcpcd  : wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,07-28 12:05:35.849  8421  8421 I dhcpcd  : wlan0: leased 192.168.1.122 for 172800 seconds
,07-28 12:05:35.859   906  1150 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,07-28 12:05:36.169   906  1148 E native  : do suspend true
,07-28 12:05:36.179  7508  7576 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1333)
,07-28 12:05:36.179  7508  7576 D io.jxcore.node.OutgoingSocketThread: closeBluetoothSocketAndStreams: Closing... (thread ID: 1333)
,07-28 12:05:36.179  7508  7576 D io.jxcore.node.OutgoingSocketThread: closeLocalSocketAndStreams: Nothing to close (thread ID: 1333)
07-28 12:05:36.179   906  1147 D WifiP2pService: InactiveState{ what=143375 }
07-28 12:05:36.179   906  1147 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-28 12:05:36.179  7508  7576 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1333)
,07-28 12:05:36.179   906  1150 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,07-28 12:05:36.189  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:05:36.189  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:05:36.189   906  1148 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-28 12:05:36.189   906  1148 E WifiStateMachine: VerifyingLinkState enter
,07-28 12:05:36.189   906  1148 D WifiNative-HAL: callSECApiInt - ID [210]
,07-28 12:05:36.189   906  1150 E ConnectivityService: updateNetworkInfo()
,07-28 12:05:36.189   906  1150 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-28 12:05:36.189  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:05:36.189   906  1160 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,07-28 12:05:36.189   906  1160 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-28 12:05:36.189   906  1160 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-28 12:05:36.189   906  1150 D ConnectivityService: Adding iface wlan0 to network 504
,07-28 12:05:36.189   906  1160 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-28 12:05:36.199   906  1160 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-28 12:05:36.199  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:05:36.209   906  1148 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,07-28 12:05:36.219   906   906 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-28 12:05:36.219   906   906 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-28 12:05:36.219   906   906 I WifiTrafficPoller: mBoosterFLAG : 0
07-28 12:05:36.219   906   906 I WifiTrafficPoller: current booster mode : FullMode
07-28 12:05:36.219   906   906 D WifiNative-HAL: callSECApiVoid - ID [212]
,07-28 12:05:36.219   906  1150 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,07-28 12:05:36.219   906  1150 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,07-28 12:05:36.219   906  1150 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 504
,07-28 12:05:36.219   906  1150 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-28 12:05:36.219   906  1150 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
07-28 12:05:36.219   906  1150 D ConnectivityService: updateSourceRoutes : add src route for:192.168.1.122
,07-28 12:05:36.219   294  1067 V         : QcRouteController
,07-28 12:05:36.229  1195  1195 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:05:36.229  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:05:36.229  1195  1195 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020533/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020533/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014b/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:05:36.229  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-28 12:05:36.229  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-28 12:05:36.229  7508  7576 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 1338)
07-28 12:05:36.229  7508  7576 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Nothing to close (thread ID: 1338)
07-28 12:05:36.229  7508  7576 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1338)
,07-28 12:05:36.229   906  1148 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-28 12:05:36.229  1195  1195 D StatusBar.NetworkController: applyOpen
,07-28 12:05:36.239  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:36.239  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:36.239  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:36.239  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:36.239  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:36.239  1195  1195 D StatusBar.NetworkController: applyOpen
,07-28 12:05:36.239  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-28 12:05:36.239  1306  1306 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-28 12:05:36.239  7508  7576 D io.jxcore.node.SocketThreadBase: closeLocalSocketAndStreams: Closing... (thread ID: 1339)
,07-28 12:05:36.249  7508  7576 D io.jxcore.node.SocketThreadBase: closeBluetoothSocketAndStreams: Closing... (thread ID: 1341)
,07-28 12:05:36.249   294  1067 V         : QcRouteController
,07-28 12:05:36.259   906  1361 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:36.259  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:05:36.259  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@199eba25 added. We now have 2 listener(s)
,07-28 12:05:36.259  7109  7109 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:05:36.259  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-28 12:05:36.259  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:05:36.259  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:05:36.259  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:36.259  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22eab7fa added. We now have 9 listener(s)
07-28 12:05:36.259  7508  7576 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:05:36.259  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:05:36.269  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:05:36.269  7508  7576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:36.269  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:36.269  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:36.269  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:36.269  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:36.269  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:36.269  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:36.269  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:05:36.269  7508  7576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:05:36.269  7508  7576 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:05:36.269  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:05:36.269   294  1067 V         : QcRouteController
07-28 12:05:36.269  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3901f008 added. We now have 3 listener(s)
,07-28 12:05:36.269  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:36.269  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:36.279  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-28 12:05:36.279  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-28 12:05:36.279  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:05:36.279  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:05:36.279  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:36.279  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b25d3a1 added. We now have 10 listener(s)
,07-28 12:05:36.279  7508  7576 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:05:36.279  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:36.279  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:36.279  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:05:36.279  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:36.279  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:36.279  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:36.279  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:05:36.279  1306  1306 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-28 12:05:36.279  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@199eba25 removed from the list
,07-28 12:05:36.279  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:36.279   906  3064 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:36.279  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22eab7fa removed from the list
07-28 12:05:36.279  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-28 12:05:36.279  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:36.279  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:36.279   906  1361 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:36.279  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:05:36.279  1306  1306 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:05:36.279  1306  1306 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:05:36.279  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:36.279  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:05:36.279  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:36.279  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 12:05:36.279  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:36.279  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@22eab7fa not in the list
07-28 12:05:36.279  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:36.279  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:05:36.279  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 12:05:36.279  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:36.279  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:36.279  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b25d3a1 removed from the list
07-28 12:05:36.279  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:36.279  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:36.279  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:05:36.279  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:05:36.279  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3901f008 removed from the list
,07-28 12:05:36.289  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:05:36.289  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151c59c6 added. We now have 2 listener(s)
07-28 12:05:36.289  1306  2807 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:05:36.289   294  1067 V         : QcRouteController
,07-28 12:05:36.289  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-28 12:05:36.289  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-28 12:05:36.289   906  1560 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:36.289  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-28 12:05:36.289  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:36.289  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1590bd87 added. We now have 9 listener(s)
07-28 12:05:36.289  7508  7576 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:05:36.289  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:05:36.289  7109  7109 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:05:36.299  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:05:36.299  7508  7576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:36.299  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:36.299  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:36.299  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:36.299  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:36.299  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:36.299  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:36.299  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:05:36.299  7508  7576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:05:36.299  7508  7576 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:05:36.299  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-28 12:05:36.299  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bab08dd added. We now have 3 listener(s)
,07-28 12:05:36.299  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:36.299  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:36.299  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-28 12:05:36.299  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:05:36.299  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:05:36.299  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:36.299  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c744c52 added. We now have 10 listener(s)
07-28 12:05:36.299  7508  7576 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:05:36.299  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:05:36.299  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:05:36.299  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:36.299  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-28 12:05:36.309  1306  1306 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-28 12:05:36.309  1306  1306 I NearbySettings: MountReceiver.onReceive - Keep current state
07-28 12:05:36.309  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-28 12:05:36.309   294  1067 V         : QcRouteController
,07-28 12:05:36.309   906  1143 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,07-28 12:05:36.319  7508  7576 E BluetoothAdapter: bluetooth le advertising not supported
,07-28 12:05:36.319  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:05:36.319  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 12:05:36.319  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-28 12:05:36.319   906  1143 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:36.319  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:36.319   294  1067 V         : QcRouteController
,07-28 12:05:36.329   294  1067 V         : QcRouteController
,07-28 12:05:36.329  7109  7109 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:05:36.329  7508  7576 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:05:36.329  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:36.329  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:05:36.329  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:36.329  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:36.329  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:36.329  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:36.329  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:36.329  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:36.329  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:05:36.329  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@151c59c6 removed from the list
07-28 12:05:36.329  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:36.329  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1590bd87 removed from the list
07-28 12:05:36.329  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:36.329  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:36.329  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:36.329  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:05:36.329  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:36.329  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:36.329  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:36.329  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1590bd87 not in the list
07-28 12:05:36.329  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:36.329  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:05:36.329  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:36.329  7508  7576 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:36.329  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:36.329  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:36.329  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:36.329  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c744c52 removed from the list
07-28 12:05:36.329  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:36.329  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:36.329  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:36.329  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:05:36.329  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bab08dd removed from the list
,07-28 12:05:36.329  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:05:36.329  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115455d9 added. We now have 2 listener(s)
,07-28 12:05:36.329  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-28 12:05:36.329  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:05:36.329  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:05:36.329  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:36.329  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11e6db9e added. We now have 9 listener(s)
07-28 12:05:36.329  7508  7576 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:05:36.329  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:05:36.339  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:05:36.339  7508  7576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:36.339  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:36.339  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:36.339  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:36.339  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:36.339  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:36.339  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:36.339  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:05:36.339  7508  7576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:05:36.339  7508  7576 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:05:36.339  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:05:36.339  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5364c added. We now have 3 listener(s)
,07-28 12:05:36.339  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:36.339  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:36.339   267   267 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
,07-28 12:05:36.339   294  1067 V         : QcRouteController
07-28 12:05:36.339  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-28 12:05:36.339  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:05:36.339  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:05:36.339  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:36.339  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14ab7695 added. We now have 10 listener(s)
,07-28 12:05:36.349  7508  7576 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:05:36.349  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:05:36.349  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:05:36.349  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,07-28 12:05:36.349  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:36.349  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-28 12:05:36.349  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 12:05:36.349   906  1361 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=906
,07-28 12:05:36.349  7508  7576 E BluetoothAdapter: bluetooth le advertising not supported
07-28 12:05:36.349  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:05:36.349  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 12:05:36.349  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-28 12:05:36.349  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:05:36.359  7508  7576 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:05:36.359  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:36.359  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:36.359  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:36.359  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:36.359  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:36.359  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:36.359  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:05:36.359  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@115455d9 removed from the list
07-28 12:05:36.359  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:36.359  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11e6db9e removed from the list
07-28 12:05:36.359  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:36.359  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:36.359  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:36.359  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:05:36.359  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:36.359  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:36.359  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:36.359  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@11e6db9e not in the list
07-28 12:05:36.359  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:36.359  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:05:36.359  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:36.359  7508  7576 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:36.359  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:36.359  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:36.359  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:36.359  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@14ab7695 removed from the list
07-28 12:05:36.359  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:36.359  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:36.359  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:36.359  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:05:36.359  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a5364c removed from the list
,07-28 12:05:36.359  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:05:36.359  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16156b38 added. We now have 2 listener(s)
,07-28 12:05:36.359  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-28 12:05:36.359  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:05:36.359  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:05:36.359  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:36.359  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1319e711 added. We now have 9 listener(s)
07-28 12:05:36.359  7508  7576 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:05:36.359  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:05:36.359  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:05:36.369   906  1150 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
,07-28 12:05:36.369   906  1150 D ConnectivityService: LTETest block dns file not exists
07-28 12:05:36.369  7508  7576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:36.369  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:36.369  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:36.369  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:36.369  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:36.369  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:05:36.369  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:05:36.369  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:05:36.369   906  1150 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
07-28 12:05:36.369  7508  7576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:05:36.369  7508  7576 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:05:36.369  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-28 12:05:36.369  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:36.369  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193e1677 added. We now have 3 listener(s)
,07-28 12:05:36.369   906  1150 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
07-28 12:05:36.369   906  1150 D ConnectivityService: calling update connectivity
,07-28 12:05:36.369   906  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-28 12:05:36.369   906  1150 E ConnectivityService: updateNetworkInfo()
07-28 12:05:36.369   906  1150 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-28 12:05:36.369   906  1030 D EntConnectivity: Not allowed due to - mEnabled false
07-28 12:05:36.369   906  1150 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:05:36.369   906  1150 E ConnectivityService: updateNetworkInfo()
07-28 12:05:36.369   906  1150 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
07-28 12:05:36.369   906  8409 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:36.369   906  1150 D ConnectivityService: calling update connectivity
,07-28 12:05:36.369   906  8409 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
07-28 12:05:36.369   906  1150 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
07-28 12:05:36.369   906  8409 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:05:36.369   906  1150 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:05:36.369   906  8409 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-28 12:05:36.369   906  1150 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:05:36.369   906  1150 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:36.369   906  1150 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-28 12:05:36.369   906  8409 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-28 12:05:36.369  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-28 12:05:36.379  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:05:36.379  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-28 12:05:36.379  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:36.379  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15202e4 added. We now have 10 listener(s)
07-28 12:05:36.379  7508  7576 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:05:36.379  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-28 12:05:36.379  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:05:36.379  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:05:36.379  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:05:36.379  7508  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:05:36.379   906  1150 D ConnectivityService: currentScore = 0, newScore = 60
07-28 12:05:36.379   906  1150 D ConnectivityService:    accepting network in place of null
07-28 12:05:36.379   906  1150 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-28 12:05:36.379  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
07-28 12:05:36.379  1428  1428 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-28 12:05:36.379   906  1150 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
,07-28 12:05:36.379   906  1150 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
07-28 12:05:36.379   906  1150 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,07-28 12:05:36.379   906  1150 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:05:36.379   906  1150 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,07-28 12:05:36.379   906  1030 D EntConnectivity: Not allowed due to - mEnabled false
,07-28 12:05:36.379   906  1150 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
07-28 12:05:36.389   906  1150 D ConnectivityService: calling update connectivity
,07-28 12:05:36.389   906  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:36.389   906  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:05:36.389   906  1150 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-28 12:05:36.389  1195  1579 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,07-28 12:05:36.389   906  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:36.389   906  1150 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-28 12:05:36.389  4431  7321 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-28 12:05:36.389  7508  7576 E BluetoothAdapter: bluetooth le advertising not supported
07-28 12:05:36.389  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:05:36.389  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 12:05:36.389  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-28 12:05:36.389  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:05:36.389  7508  7576 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-28 12:05:36.389  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:36.389  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:05:36.389  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:36.389  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:36.389  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:36.389  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:05:36.389  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:05:36.389  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@16156b38 removed from the list
07-28 12:05:36.389  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:36.389  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1319e711 removed from the list
07-28 12:05:36.389  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:36.389  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:05:36.389  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:36.389  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:36.389  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:36.389  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:36.389  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:36.389  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1319e711 not in the list
07-28 12:05:36.389  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:36.389  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:05:36.389  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:36.389  7508  7576 D BluetoothLeScanner: could not find callback wrapper
07-28 12:05:36.389  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:05:36.389  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:36.389  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:36.389  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@15202e4 removed from the list
07-28 12:05:36.389  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:36.389  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:36.389  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:36.389  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:05:36.389  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@193e1677 removed from the list
,07-28 12:05:36.389  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:05:36.389  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3973a313 added. We now have 2 listener(s)
,07-28 12:05:36.399  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-28 12:05:36.399  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:05:36.399  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:05:36.399  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:36.399  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@259e6950 added. We now have 9 listener(s)
07-28 12:05:36.399  7508  7576 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:05:36.399  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:05:36.399  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:05:36.399   906  1560 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:36.409  7508  7576 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:05:36.409  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:05:36.409  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:05:36.409  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:05:36.409  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:05:36.409  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:05:36.409  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:05:36.409  7508  7576 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:05:36.409  7508  7576 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:05:36.409  7508  7576 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:05:36.409  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:05:36.409  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11cf684e added. We now have 3 listener(s)
,07-28 12:05:36.409  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-28 12:05:36.409  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:05:36.409  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:05:36.409  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:05:36.409  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b5d6f added. We now have 10 listener(s)
,07-28 12:05:36.409  7508  7576 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:05:36.409  7508  7576 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing all connections
07-28 12:05:36.409  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-28 12:05:36.409  7508  7576 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:05:36.409  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:36.409  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:36.409  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:05:36.409  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:05:36.409  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3973a313 removed from the list
07-28 12:05:36.409  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:36.409  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@259e6950 removed from the list
07-28 12:05:36.409  7508  7576 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:05:36.409  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:05:36.409  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:36.409  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:05:36.409  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:05:36.409  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:36.409  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:05:36.409  7508  7576 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@259e6950 not in the list
07-28 12:05:36.409  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:36.409  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:05:36.419  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:05:36.419  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:05:36.419  7508  7576 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:05:36.419  7508  7576 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b5d6f removed from the list
07-28 12:05:36.419  7508  7576 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:05:36.419  7508  7576 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:05:36.419  7508  7576 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:05:36.419  7508  7576 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-28 12:05:36.419  7508  7576 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11cf684e removed from the list
,07-28 12:05:36.419  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-28 12:05:36.419  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-28 12:05:36.419  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
,07-28 12:05:36.419  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-28 12:05:36.419  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
07-28 12:05:36.419  7508  7576 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-28 12:05:36.429   906   985 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{34357bc7 u-1 android.net.wifi.p2p.STATE_CHANGED} to ReceiverList{1074133a 7508 com.test.thalitest/10079/u0 remote:18d37a65}: filter unregistered
07-28 12:05:36.429   906   985 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{96685f4 u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{1074133a 7508 com.test.thalitest/10079/u0 remote:18d37a65}: filter unregistered
07-28 12:05:36.429   906  1145 V NetworkStats: updateIfacesLocked()
07-28 12:05:36.429   906  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:05:36.429   906  1145 V NetworkStats: performPollLocked(flags=0x1)
,07-28 12:05:36.429   906  1151 D Tethering: MasterInitialState.processMessage what=3
07-28 12:05:36.429   906   906 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:05:36.429   906  1152 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-28 12:05:36.429   906  1152 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:05:36.429   906  1152 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:05:36.429   906  1152 D SmartBondingService: getSBEnabled() enabled =false
,07-28 12:05:36.429   906  1145 D NetworkStatsFactory: UpdateStatsForKnox
07-28 12:05:36.429   906  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:36.429   906   985 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{c2f911d u-1 android.net.wifi.WIFI_STATE_CHANGED} to ReceiverList{2a8657e1 7508 com.test.thalitest/10079/u0 remote:5bcdd48}: filter unregistered
07-28 12:05:36.429   906   985 W BroadcastQueue: Skipping deliver [background] BroadcastRecord{7e5cf92 u-1 android.net.conn.CONNECTIVITY_CHANGE} to ReceiverList{2a8657e1 7508 com.test.thalitest/10079/u0 remote:5bcdd48}: filter unregistered
,07-28 12:05:36.429   906  1465 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:36.429  1195  1195 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-28 12:05:36.429   906  1152 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
07-28 12:05:36.429  1195  1195 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-28 12:05:36.429   906  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:05:36.429   906  1145 V NetworkStats: performPollLocked() took 3ms
,07-28 12:05:36.429  1195  1195 D StatusBar.NetworkController: updateDataNetType()
07-28 12:05:36.429  1195  1195 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
07-28 12:05:36.429  1195  1195 E StatusBar.NetworkController: updateLTEICONDataNetType:0
07-28 12:05:36.429   906  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:05:36.429   906  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:05:36.429   906  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:05:36.429   906  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:05:36.429   906  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:05:36.429   906  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:05:36.429   906  1146 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
,07-28 12:05:36.429  7508  8490 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1347, name: My test thread name)
,07-28 12:05:36.429  7508  8490 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1347, thread name: My test thread name)
07-28 12:05:36.429  7508  8490 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1347, name: My test thread name)
07-28 12:05:36.429  1195  1195 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-28 12:05:36.429  1195  1195 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,07-28 12:05:36.429  1195  1195 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,07-28 12:05:36.429  1195  1195 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020533/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020533/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014b/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:05:36.429   906  1143 I AudioService: getStreamVolume 3 index 0
07-28 12:05:36.429  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-28 12:05:36.429  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-28 12:05:36.429  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:36.429  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:36.439  1195  1195 D StatusBar.NetworkController: applyOpen
07-28 12:05:36.439  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:36.439  1195  1195 D StatusBar.NetworkController: applyOpen
,07-28 12:05:36.439  1195  1195 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:05:36.439  1195  1195 D StatusBar.NetworkController: applyOpen
,07-28 12:05:36.439  7508  8491 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1349, name: My test thread name)
07-28 12:05:36.439  7508  8491 E io.jxcore.node.StreamCopyingThread: Input stream got -1 on read (thread ID: 1349, thread name: My test thread name)
07-28 12:05:36.439  7508  8491 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1349, name: My test thread name)
,07-28 12:05:36.439  7508  7576 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
07-28 12:05:36.439  7508  7576 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
07-28 12:05:36.439  7508  7576 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-28 12:05:36.439  7508  7576 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,07-28 12:05:36.439  7508  7576 D com.test.thalitest.ThaliTestRunner: Total duration: 23794 ms
,07-28 12:05:36.439  7508  7576 I jxcore-log: Total number of executed tests:  80
07-28 12:05:36.439  7508  7576 I jxcore-log: 
07-28 12:05:36.439  7508  7576 I jxcore-log: Number of passed tests:  80
07-28 12:05:36.439  7508  7576 I jxcore-log: 
07-28 12:05:36.439  7508  7576 I jxcore-log: Number of failed tests:  0
07-28 12:05:36.439  7508  7576 I jxcore-log: 
07-28 12:05:36.439  7508  7576 I jxcore-log: Number of ignored tests:  0
07-28 12:05:36.439  7508  7576 I jxcore-log: 
07-28 12:05:36.439  7508  7576 I jxcore-log: Total duration:  23794
07-28 12:05:36.439  7508  7576 I jxcore-log: 
07-28 12:05:36.439  7508  7576 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
07-28 12:05:36.439  7508  7576 I jxcore-log: 
,07-28 12:05:36.439  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:05:36.439  7508  7576 I jxcore-log: 
07-28 12:05:36.439  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:05:36.439  7508  7576 I jxcore-log: 
07-28 12:05:36.439  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:05:36.439  7508  7576 I jxcore-log: 
07-28 12:05:36.439  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:05:36.439  7508  7576 I jxcore-log: 
07-28 12:05:36.439  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:05:36.439  7508  7576 I jxcore-log: 
07-28 12:05:36.449  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}
07-28 12:05:36.449  7508  7576 I jxcore-log: 
07-28 12:05:36.449  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-28 12:05:36.449  7508  7576 I jxcore-log: 
07-28 12:05:36.449  7508  7508 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
07-28 12:05:36.449  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:05:36.449  7508  7576 I jxcore-log: 
07-28 12:05:36.449  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:05:36.449  7508  7576 I jxcore-log: 
07-28 12:05:36.449  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:05:36.449  7508  7576 I jxcore-log: 
07-28 12:05:36.449  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:05:36.449  7508  7576 I jxcore-log: 
07-28 12:05:36.449  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:05:36.449  7508  7576 I jxcore-log: 
07-28 12:05:36.449   906  8409 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
07-28 12:05:36.449  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:05:36.449  7508  7576 I jxcore-log: 
,07-28 12:05:36.449  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:05:36.449  7508  7576 I jxcore-log: 
07-28 12:05:36.449  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:05:36.449  7508  7576 I jxcore-log: 
,07-28 12:05:36.449  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:05:36.449  7508  7576 I jxcore-log: 
07-28 12:05:36.449  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:05:36.449  7508  7576 I jxcore-log: 
07-28 12:05:36.449  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:05:36.449  7508  7576 I jxcore-log: 
07-28 12:05:36.449  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:05:36.449  7508  7576 I jxcore-log: 
07-28 12:05:36.459  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:05:36.459  7508  7576 I jxcore-log: 
07-28 12:05:36.459  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:05:36.459  7508  7576 I jxcore-log: 
07-28 12:05:36.459  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:05:36.459  7508  7576 I jxcore-log: 
07-28 12:05:36.459  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:05:36.459  7508  7576 I jxcore-log: 
07-28 12:05:36.459  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:05:36.459  7508  7576 I jxcore-log: 
07-28 12:05:36.459  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:05:36.459  7508  7576 I jxcore-log: 
07-28 12:05:36.459  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:05:36.459  7508  7576 I jxcore-log: 
07-28 12:05:36.459  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:05:36.459  7508  7576 I jxcore-log: 
07-28 12:05:36.459  7508  7576 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:05:36.459  7508  7576 I jxcore-log: 
,07-28 12:05:36.499   906  8409 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jul 2016 10:05:36 GMT], X-Android-Received-Millis=[1469700336509], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1469700336485]}
,07-28 12:05:36.499   906  8409 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-28 12:05:36.499   906  8409 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
07-28 12:05:36.499   906  1150 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
07-28 12:05:36.499   906  1150 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
,07-28 12:05:36.499   906  1150 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:05:36.499   906  1150 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:05:36.499   906  1150 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:36.499   906  1150 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
,07-28 12:05:36.499   906  1150 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
07-28 12:05:36.499   906  1150 D ConnectivityService: calling update connectivity
07-28 12:05:36.499   906  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:36.499   906  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-28 12:05:36.499   906  1150 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:05:36.499   906  1150 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:36.499  1195  1579 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,07-28 12:05:36.499   906  1150 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:05:36.499   906  1150 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
07-28 12:05:36.499  4431  7321 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,07-28 12:05:36.509   906  1435 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:36.509  1195  1195 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-28 12:05:36.509  1195  1195 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-28 12:05:36.509  1195  1195 D StatusBar.NetworkController: updateDataNetType()
07-28 12:05:36.509  1195  1195 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
,07-28 12:05:36.509  1195  1195 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,07-28 12:05:36.509  1195  1195 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,07-28 12:05:36.509  1195  1195 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
07-28 12:05:36.509  1195  1195 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,07-28 12:05:36.509  1195  1195 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020533/com.android.systemui:drawable/stat_sys_wifi_signal_3 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020533/com.android.systemui:drawable/stat_sys_wifi_signal_3 mQSWifiIconId=0x7f02014b/com.android.systemui:drawable/ic_qs_wifi_3 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:05:36.509  1195  1195 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-28 12:05:36.689  8492  8492 D AndroidRuntime: 
07-28 12:05:36.689  8492  8492 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-28 12:05:36.689  8492  8492 D AndroidRuntime: CheckJNI is OFF
,07-28 12:05:36.689  8492  8492 D AndroidRuntime: readGMSProperty: start
07-28 12:05:36.689  8492  8492 D AndroidRuntime: readGMSProperty: already setted!!
,07-28 12:05:36.689  8492  8492 D AndroidRuntime: readGMSProperty: end
07-28 12:05:36.689  8492  8492 D AndroidRuntime: addProductProperty: start
,07-28 12:05:36.839  8492  8492 E AffinityControl: AffinityControl: registerfunction enter
,07-28 12:05:36.859  8492  8492 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-28 12:05:36.869   906   923 D PackageManager: START PACKAGE DELETE: observer{1057230179}
07-28 12:05:36.869   906   923 D PackageManager: pkg{<packageName>}
07-28 12:05:36.869   906   923 D PackageManager: user{0}
07-28 12:05:36.869   906   923 D PackageManager: caller{2000}
07-28 12:05:36.869   906   923 D PackageManager: flags{2}
,07-28 12:05:36.869   906   923 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-28 12:05:36.869   906   923 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,07-28 12:05:36.869   906   923 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
07-28 12:05:36.869   906   923 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-28 12:05:36.879   906  1051 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-28 12:05:36.869   906   923 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,07-28 12:05:36.879   906  1051 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-28 12:05:36.879   906  1051 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1,
07-28 12:05:36.879   906  1051 D ApplicationPolicy: getApplicationUninstallationEnabled
,07-28 12:05:36.879   906  1051 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,07-28 12:05:36.879   906  1051 D PackageManager: !@killApplicatoin: 10079, uninstall pkg
,07-28 12:05:36.879   906   985 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
,07-28 12:05:36.879   906   985 I ActivityManager: Killing 7508:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest cause uninstall pkg
07-28 12:05:36.879   906  1150 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:05:36.879   906   985 I ActivityManager:   Force finishing activity ActivityRecord{12c79207 u0 com.test.thalitest/.MainActivity t99}
,07-28 12:05:36.889   906   985 D FocusedStackFrame: Set to : 0
,07-28 12:05:36.899   267   340 I SurfaceFlinger: id=12 Removed NainActivit (6/9)
,07-28 12:05:36.899   267   345 I SurfaceFlinger: id=12 Removed NainActivit (-2/9)
,07-28 12:05:36.909   906  1031 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,07-28 12:05:36.909   906  1031 D PointerIcon: setMouseCustomIcon IconType is same.101
07-28 12:05:36.909   906  1031 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-28 12:05:36.909   906  1031 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-28 12:05:36.909   906   906 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:36.909   906   906 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:36.919   906   906 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:36.919   906   906 D SmartBondingService: SmartBondingReceiver: wifi is connected
07-28 12:05:36.919   906   906 D SmartBondingService: SmartBondingReceiver: wifi ap is not changed
07-28 12:05:36.919   906   906 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:36.919   906  1152 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-28 12:05:36.919   906  1152 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:05:36.919   906  1152 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:05:36.919   906  1152 D SmartBondingService: getSBEnabled() enabled =false
,07-28 12:05:36.919   906  1152 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-28 12:05:36.919   906   906 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:36.919   906   906 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:36.919   906   906 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:36.929   906   906 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:36.929   906   981 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.009   906  1051 W PackageSettings: Skipping PackageSetting{b84ba82 com.example.hello/10078} due to missing metadata
,07-28 12:05:37.029   906  1541 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.029   906  1541 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:37.029   906  1560 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.029   906  1462 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:37.029   906  1435 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:37.029   906  3355 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.029   906  1143 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:37.029   906  3331 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:37.029   906  1465 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.029   906  1243 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:37.029   906  1560 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:37.029   906  3093 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.039   906  1663 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:37.039  7766  7766 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
07-28 12:05:37.039   906  3093 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:37.039  1586  1586 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
07-28 12:05:37.049   906  1413 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:37.059   906   924 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:37.059   906   981 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:37.059   906   981 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:37.059  6859  6859 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-28 12:05:37.059  6859  6859 I PCWCLIENTTRACE_PushUtil: sales region : global
07-28 12:05:37.059  6859  6859 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-28 12:05:37.059  6859  6859 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
07-28 12:05:37.059  7766  7766 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
07-28 12:05:37.069   906  1051 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=0: pkg removed
,07-28 12:05:37.099  3653  3653 I art     : Explicit concurrent mark sweep GC freed 5718(344KB) AllocSpace objects, 4(64KB) LOS objects, 40% free, 15MB/26MB, paused 344us total 18.212ms
07-28 12:05:37.099  1586  1586 I art     : Explicit concurrent mark sweep GC freed 1336(63KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 20MB/33MB, paused 547us total 29.923ms
07-28 12:05:37.099   906  1560 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-28 12:05:37.099   906  1560 D SecContentProvider2: mCursor = null
07-28 12:05:37.099  6346  6346 I art     : Explicit concurrent mark sweep GC freed 653(37KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 312us total 23.913ms
07-28 12:05:37.109   906   906 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
07-28 12:05:37.109   906   981 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,07-28 12:05:37.119   906   906 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,07-28 12:05:37.119   906   981 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,07-28 12:05:37.119   906   906 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,07-28 12:05:37.129   906  1031 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,07-28 12:05:37.129  1724  1724 E SamsungIME: mOCRHelper is null
,07-28 12:05:37.129  1444  1444 D ResourcesManager: creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
,07-28 12:05:37.129  1444  1444 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-28 12:05:37.129  1444  1444 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-28 12:05:37.129  1444  1444 D ResourcesManager: creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
,07-28 12:05:37.129   906  1145 V NetworkStats: removeUidsLocked() for UIDs [10079]
,07-28 12:05:37.129   906  1145 V NetworkStats: performPollLocked(flags=0x3)
07-28 12:05:37.129   906  1145 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:05:37.129  1444  1444 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:05:37.129  1444  1444 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-28 12:05:37.129  1444  1444 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-28 12:05:37.129  4431  4431 I art     : Explicit concurrent mark sweep GC freed 55167(3MB) AllocSpace objects, 18(407KB) LOS objects, 38% free, 25MB/41MB, paused 701us total 51.934ms
,07-28 12:05:37.129   906  1145 D NetworkStatsFactory: UpdateStatsForKnox
07-28 12:05:37.129   906  1145 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.129  1922  2354 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-28 12:05:37.139  1444  1444 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,07-28 12:05:37.139  1444  1444 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-28 12:05:37.139  1444  1444 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-28 12:05:37.139   906  1145 V NetworkStats: performPollLocked() took 10ms
07-28 12:05:37.139   906  1145 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:05:37.149   906  2995 E libprocessgroup: failed to kill 1 processes for processgroup 7508
,07-28 12:05:37.149   906  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:05:37.149   906  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:05:37.159   906  1121 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-28 12:05:37.159   906   906 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,07-28 12:05:37.169  1417  1417 D RegisteredServicesCache: empty dynamic service
,07-28 12:05:37.169   906   906 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,07-28 12:05:37.179  7820  7820 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:05:37.179  7820  7820 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-28 12:05:37.189   906   906 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,07-28 12:05:37.209   906   906 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,07-28 12:05:37.209   906   906 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-28 12:05:37.219   906   981 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
,07-28 12:05:37.229   906   906 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,07-28 12:05:37.239   906   906 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,07-28 12:05:37.249   906   906 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,07-28 12:05:37.249   906   906 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,07-28 12:05:37.279   906  3355 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-28 12:05:37.279   906  3355 D SecContentProvider2: mCursor = null
,07-28 12:05:37.289   906   906 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,07-28 12:05:37.289   906   906 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,07-28 12:05:37.289   906   906 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,07-28 12:05:37.299   906   906 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,07-28 12:05:37.299   906   981 D EnterpriseDeviceManagerService: Package has changed for user 0
07-28 12:05:37.299   906   981 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,07-28 12:05:37.299   906   906 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
,07-28 12:05:37.299   906   906 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,07-28 12:05:37.299   906   906 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,07-28 12:05:37.309   906   906 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,07-28 12:05:37.309   906   906 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,07-28 12:05:37.309   906   906 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-28 12:05:37.309   906   981 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,07-28 12:05:37.319  7836  7836 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,07-28 12:05:37.319   906   906 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,07-28 12:05:37.319   906   906 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,07-28 12:05:37.329   906   981 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:05:37.329   906   906 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,07-28 12:05:37.329  7836  7836 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,07-28 12:05:37.329  7836  7836 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,07-28 12:05:37.339  4019  4019 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-28 12:05:37.339   906   981 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-28 12:05:37.339   906   906 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-28 12:05:37.349   906   906 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
07-28 12:05:37.349  4019  4019 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1469700337351
,07-28 12:05:37.349  4019  4019 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,07-28 12:05:37.349   906  1709 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:37.349   906  1243 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.349  4019  4019 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,07-28 12:05:37.349  4019  4019 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().START
,07-28 12:05:37.349  4019  4019 I KLMS-2.4.511: : NetworkChangeOperations(): uploadRequestLog().START 
,07-28 12:05:37.349   906   906 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,07-28 12:05:37.349   906   981 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:05:37.349   906   981 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
07-28 12:05:37.349   906   906 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
,07-28 12:05:37.359   906   906 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,07-28 12:05:37.359   906   981 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,07-28 12:05:37.359  4019  4019 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,07-28 12:05:37.369   906   981 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:05:37.369   906   981 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,07-28 12:05:37.369   906  3064 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.369   906   906 D RCPManagerService: PackageReceiver onReceive()
,07-28 12:05:37.369   906   906 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-28 12:05:37.379   906   906 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,07-28 12:05:37.379   906   906 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-28 12:05:37.379   906   906 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-28 12:05:37.379   906   906 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-28 12:05:37.379   906   906 V EnterpriseBillingPolicy: uID is 10079
07-28 12:05:37.379   906   906 V EnterpriseBillingPolicy: Removed Packageuid is0
07-28 12:05:37.379   906   906 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,07-28 12:05:37.379   906   906 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
07-28 12:05:37.379   906   906 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-28 12:05:37.379   906   906 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-28 12:05:37.379   906   906 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-28 12:05:37.379   906  1051 I art     : Explicit concurrent mark sweep GC freed 77869(5MB) AllocSpace objects, 15(240KB) LOS objects, 29% free, 37MB/53MB, paused 2.484ms total 265.864ms
,07-28 12:05:37.379   906  1150 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,07-28 12:05:37.389   906   906 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-28 12:05:37.389   301   301 E SMD     : DCD ON
,07-28 12:05:37.399  7869  7869 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,07-28 12:05:37.399   906  1243 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
07-28 12:05:37.399   906  1243 D ActivityManager: caller:android.app.ApplicationThreadProxy@2c9653bd, r.packageName :com.samsung.android.app.galaxyfinder
,07-28 12:05:37.399   906  1177 D TaskPersister: removeObsoleteFile: deleting file=99_task.xml
,07-28 12:05:37.399   906   906 V AlarmManagerEXT: com.test.thalitest(10079) is removed.
,07-28 12:05:37.409   906   981 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:05:37.409   906   981 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,07-28 12:05:37.429  7894  7894 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,07-28 12:05:37.429   906  1541 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.429  3586  8524 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,07-28 12:05:37.429  3586  8524 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,07-28 12:05:37.439  3586  8524 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
07-28 12:05:37.439  6566  6566 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,07-28 12:05:37.439  6566  6566 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
07-28 12:05:37.439  6566  6566 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-28 12:05:37.439  6566  6566 I SA      : [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
07-28 12:05:37.439  6566  6566 I SA      : [OR] == isSIMCardReady false ==
,07-28 12:05:37.439   906  1465 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:37.439  6566  6566 I SA      : [SCU] == networkStateCheck == true
,07-28 12:05:37.439  6566  6566 I SA      : [DM] getCountryCodeFromCSC : PL
07-28 12:05:37.439  6566  6566 I SA      : isChinaCountryCode : false
07-28 12:05:37.439  6566  6566 I SA      : [SCU] is ChinestModel Data Restricted   : false
,07-28 12:05:37.439  6566  6566 I SA      : [OR] == networkStateCheck true ==
,07-28 12:05:37.439  6566  6566 I SA      : [OR] GetMyCountryZoneTask
,07-28 12:05:37.439  6566  6566 I SA      : [OR] onReceive END
,07-28 12:05:37.439   906   981 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:05:37.439   906   981 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:05:37.449   906   981 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,07-28 12:05:37.449   906  1709 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.449   906   923 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,07-28 12:05:37.449   906   923 D ActivityManager: caller:android.app.ApplicationThreadProxy@1c993d75, r.packageName :com.android.providers.downloads
,07-28 12:05:37.449  6566  8525 I SA      : [SRS] prepareGetMyCountryZone
,07-28 12:05:37.459  7913  7913 I SCloudBackupReceiver: Other Intent
,07-28 12:05:37.459  7234  7234 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
07-28 12:05:37.459  7234  7234 I KnoxUsageLogPro: premStatus:2
,07-28 12:05:37.459  7234  7234 I KnoxUsageLogPro: isEulaShown : false
07-28 12:05:37.459  7234  7234 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-28 12:05:37.469  3586  8524 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,07-28 12:05:37.479  3586  8524 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,07-28 12:05:37.479  3586  8524 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,07-28 12:05:37.479  3586  8524 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,07-28 12:05:37.479  3586  8524 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,07-28 12:05:37.479  3586  8524 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,07-28 12:05:37.479  3586  8524 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,07-28 12:05:37.479   906  3093 I SQLiteConnectionPool: exportDB...
,07-28 12:05:37.479   906   981 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:05:37.479   906   981 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,07-28 12:05:37.489  3586  8524 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,07-28 12:05:37.489   906   981 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,07-28 12:05:37.489   906  1051 D PackageManager: delete codoeFile: 
,07-28 12:05:37.489  6566  8525 I SA      : [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,07-28 12:05:37.499  6566  8525 I SA      : [SSP] query invoked
,07-28 12:05:37.499   906  1413 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.499  6566  8525 I SA      : [TPMU] GetMccFromDB : null
07-28 12:05:37.499  6566  8525 I SA      : [SCU] getMccFromPreferece mcc = 260
07-28 12:05:37.499  6566  8525 I SA      : [TPM] isNoProxy(default) : true
,07-28 12:05:37.499   906  1051 D AASAuninstall: userId = 0, info.removedAppID = 10079, info.uid = 10079, packageName = com.test.thalitest
07-28 12:05:37.499   906  1051 I AASA_removePackage: UID=10079 Target=com.test.thalitest
,07-28 12:05:37.499   906  1051 D PackageManager: result of delete: 1{1057230179}
,07-28 12:05:37.509  8492  8492 D AndroidRuntime: Shutting down VM
,07-28 12:05:37.509   906   981 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,07-28 12:05:37.509  6566  8525 E File    : fail readDirectory() errno=2
,07-28 12:05:37.519   906  1709 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.519   906  1663 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.519   906   981 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,07-28 12:05:37.519  3586  8524 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,07-28 12:05:37.529   906   981 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:05:37.529   906   981 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,07-28 12:05:37.529   906   981 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,07-28 12:05:37.539   906   924 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.539  3586  8524 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,07-28 12:05:37.539  8021  8021 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:05:37.539  8021  8021 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
07-28 12:05:37.539  8021  8021 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,07-28 12:05:37.539   906   981 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:05:37.539   906   981 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-28 12:05:37.539   906   981 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,07-28 12:05:37.549   906   981 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,07-28 12:05:37.549   906   981 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:05:37.549   906   981 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-28 12:05:37.549   906   923 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.549   906  1413 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:37.549   906   981 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:05:37.549   906   981 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,07-28 12:05:37.549   906  1243 D RCPManagerService: exchangeData() failure , invalid userId
,07-28 12:05:37.549   906  1560 D RCPManagerService: exchangeData() failure , invalid userId
,07-28 12:05:37.559   906  3331 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.559  6639  6639 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:05:37.559  6639  6639 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:05:37.559  6639  6639 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:05:37.559   906  1462 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.559   906   981 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
07-28 12:05:37.559  6639  6639 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:05:37.559   906   981 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,07-28 12:05:37.559   906  1465 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:37.559   906   924 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.569   906  1709 D ActivityManager: startService callerProcessName:com.sec.android.app.SmartClipService, calleePkgName: com.sec.android.app.SmartClipService
,07-28 12:05:37.569   906  1709 D ActivityManager: caller:android.app.ApplicationThreadProxy@56c749d, r.packageName :com.sec.android.app.SmartClipService
,07-28 12:05:37.569   906   981 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:05:37.569   906   981 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,07-28 12:05:37.579   906  1361 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-28 12:05:37.579   906  1361 D ActivityManager: caller:android.app.ApplicationThreadProxy@10d85ce3, r.packageName :com.google.android.gms
,07-28 12:05:37.579   906  1465 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:37.579   906   924 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.579   906  1435 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.579   906  3093 I SQLiteConnectionPool: ...exportDB
,07-28 12:05:37.579   906  1143 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.589   906  3093 D SSRM:aY : MSG_TYPE_APP_REMOVED::
,07-28 12:05:37.589   906   981 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-28 12:05:37.589   906   923 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:37.589   906   981 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,07-28 12:05:37.589   906  1243 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:37.589  4431  4431 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,07-28 12:05:37.589  4431  5403 I iu.UploadsManager: num queued entries: 0
,07-28 12:05:37.589  4431  5403 I iu.UploadsManager: num updated entries: 0
,07-28 12:05:37.589  4431  5403 I iu.SyncManager: NEXT; no task
,07-28 12:05:37.599   906  3064 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.599  7170  7170 D WaitQueueForNetworkActivate: notifyNetworkActivated
,07-28 12:05:37.599   906   981 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-28 12:05:37.599   906   981 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-28 12:05:37.599   906   981 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,07-28 12:05:37.609   906   981 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-28 12:05:37.609   906   981 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,07-28 12:05:37.609   906   981 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-28 12:05:37.609   906   981 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-28 12:05:37.609   906   981 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,07-28 12:05:37.609   906   981 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:05:37.609   906   981 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-28 12:05:37.609   906   981 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,07-28 12:05:37.609   906   981 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:05:37.619   906   981 D UsbSettingsManager: clearDefaults: com.test.thalitest
,07-28 12:05:37.619   906   981 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,07-28 12:05:37.709   906  1709 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.709  1922  8530 I qtaguid : Tagging socket 52 with tag 1000040700000000{268436487,0} uid -1, pid: 1922, getuid(): 10015
,07-28 12:05:37.709   906  1243 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.719   906  1465 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.719   906   924 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.739   906  1709 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,07-28 12:05:37.739   906  1709 D ActivityManager: caller:android.app.ApplicationThreadProxy@3a76b1f8, r.packageName :com.sec.android.app.samsungapps
,07-28 12:05:37.739  4019  4019 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-28 12:05:37.749  4019  4019 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1469700337754
,07-28 12:05:37.749  4019  4019 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
,07-28 12:05:37.749  4019  4019 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,07-28 12:05:37.749  7170  7170 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,07-28 12:05:37.749  7170  7170 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,07-28 12:05:37.749  7170  7170 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,07-28 12:05:37.759  7170  7170 D InitializeManagerStateMachine: exit::IDLE
07-28 12:05:37.759   906  1051 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-28 12:05:37.759   906  1051 D PackageManager: userId{-1}
07-28 12:05:37.759   906  1051 D PackageManager: andCode{true}
07-28 12:05:37.759  7170  7170 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,07-28 12:05:37.759   906  1051 D ActivityManager: caller:null, r.packageName :com.android.defcontainer
,07-28 12:05:37.759   906  1462 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:37.759   906  1051 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:37.759   906  1051 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:37.759   906  1051 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:37.759   906  1051 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:37.759   906  1560 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.759  7170  7170 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
07-28 12:05:37.759  7170  7170 D InitializeManagerStateMachine: exit::NETWORK_CHECK
07-28 12:05:37.759  7170  7170 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
07-28 12:05:37.759  7170  7170 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
07-28 12:05:37.759  7170  7170 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
07-28 12:05:37.759  7170  7170 D InitializeManagerStateMachine: entry::SUCCESS
07-28 12:05:37.759  7170  7170 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,07-28 12:05:37.799  8537  8537 E Zygote  : MountEmulatedStorage()
07-28 12:05:37.799  8537  8537 E Zygote  : v2
07-28 12:05:37.799  8537  8537 I libpersona: KNOX_SDCARD checking this for 10007
07-28 12:05:37.799  8537  8537 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:37.809   906  1051 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8537 uid=10007 gids={50007, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
07-28 12:05:37.809  7170  7170 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
07-28 12:05:37.809  7170  7170 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,07-28 12:05:37.819   906  1435 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.819  8537  8537 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:05:37.819  8537  8537 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:05:37.819  7170  7170 D InitializeManagerStateMachine: exit::SUCCESS
,07-28 12:05:37.819  8537  8537 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-28 12:05:37.819  4019  4019 I KLMS-2.4.511: : MainReciver(): Notification App List is Null. Remove Notification.
,07-28 12:05:37.819  7170  7170 D InitializeManagerStateMachine: entry::IDLE
,07-28 12:05:37.829  4019  4019 I KLMS-2.4.511: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,07-28 12:05:37.829   906  3331 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,07-28 12:05:37.829   906  3331 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:37.829   906  3331 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:37.829   906  3331 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:37.829   906  3331 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:37.839  8537  8537 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:05:37.839  8537  8537 D ActivityThread: Added TimaKeyStore provider
,07-28 12:05:37.869  8552  8552 E Zygote  : MountEmulatedStorage()
07-28 12:05:37.869   906   924 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:37.869  8552  8552 E Zygote  : v2
07-28 12:05:37.869   906   923 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:05:37.869  8552  8552 I libpersona: KNOX_SDCARD checking this for 10116
07-28 12:05:37.869  8552  8552 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:37.879   906  3331 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8552 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,07-28 12:05:37.899   339   339 I art     : Explicit concurrent mark sweep GC freed 8724(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 305us total 15.721ms
,07-28 12:05:37.909   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 270us total 9.467ms
,07-28 12:05:37.919   906  1541 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.919   906  1709 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.919  8552  8552 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:05:37.919  8552  8552 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:05:37.919  8552  8552 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-28 12:05:37.919   339   339 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 274us total 10.127ms
,07-28 12:05:37.939  8552  8552 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:05:37.939  8552  8552 D ActivityThread: Added TimaKeyStore provider
,07-28 12:05:37.939   906  1709 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.949   906  1560 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.949   906  1413 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:05:37.949  1444  1444 D SurfaceWidgetView: destroyHardwareResources():174590407
,07-28 12:05:37.959   906  3064 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
,07-28 12:05:37.959   906  3064 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
07-28 12:05:37.959   906  3064 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-28 12:05:37.959   906  3064 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-28 12:05:37.959   906  3064 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,07-28 12:05:37.959  8537  8537 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DefaultContainerService/DefaultContainerService.apk
,07-28 12:05:37.959  1444  1444 D Launcher: onRestart, Launcher: 753547868
,07-28 12:05:37.959  1444  1444 D Launcher: onStart, Launcher: 753547868
07-28 12:05:37.959  1444  1444 D Launcher.HomeView: onStart
,07-28 12:05:37.959  1444  1444 V ActivityThread: updateVisibility : ActivityRecord{26fd1629 token=android.os.BinderProxy@3df2fb34 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
07-28 12:05:37.959  1771  1796 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
,07-28 12:05:37.959  1771  2099 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
,07-28 12:05:37.959  1771  2099 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,07-28 12:05:37.969  8552  8552 D ResourcesManager: creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,07-28 12:05:37.969   906  1121 I EventHub: Removing device '/dev/input/event6' due to inotify event
,07-28 12:05:37.979  8552  8552 W ContextImpl: Unable to create files subdir /data/data/com.sec.esdk.elm/cache
,07-28 12:05:37.979  8552  8552 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,07-28 12:05:37.979   267   267 I SurfaceFlinger: id=14 createSurf (1080x1920),1 flag=4, Mauncher
,07-28 12:05:37.979   906  1029 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-28 12:05:37.979   906  1029 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-28 12:05:37.989   906  1031 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-28 12:05:37.989   906  1031 D PointerIcon: setMouseCustomIcon IconType is same.101
07-28 12:05:37.989   906  1031 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-28 12:05:37.989   906  1031 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-28 12:05:37.989   906  1361 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-28 12:05:37.999   906  1361 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 7508 uid 10079
,07-28 12:05:37.999   906  8572 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-28 12:05:37.999  8552  8552 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,07-28 12:05:37.999  8552  8552 D elm:14491: ELMEngine.ELMEngine( context ).
,07-28 12:05:37.999  8552  8552 D elm:14491: MDMBridge.setEnterpriseBridge()
,07-28 12:05:37.999   906   923 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,07-28 12:05:37.999   906   923 D ActivityManager: caller:android.app.ApplicationThreadProxy@dba1c37, r.packageName :com.sec.esdk.elm
,07-28 12:05:38.009  8552  8552 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,07-28 12:05:38.009  3717  3717 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,07-28 12:05:38.009  3717  3717 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,07-28 12:05:38.009  3717  3717 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
07-28 12:05:38.009  3717  3717 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-28 12:05:38.009  3717  3717 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
07-28 12:05:38.009  3717  3717 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-28 12:05:38.009  3717  3717 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-28 12:05:38.009  3717  3717 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:05:38.009  3717  3717 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:05:38.009  3717  3717 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:05:38.009  3717  3717 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:05:38.009  3717  3717 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:05:38.009  3717  3717 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:05:38.009   906  3355 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.service.health, hostingType: broadcast
07-28 12:05:38.009  3717  3717 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,07-28 12:05:38.009   906  3355 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:38.009   906  3355 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:38.009   906  3355 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:38.009   906  3355 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:38.019  8552  8552 D elm:14491: ElmAgentService : onCreate()
,07-28 12:05:38.019  8552  8574 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
07-28 12:05:38.019  8552  8574 D elm:14491: MainReceiver.listeningToPackageRemoved()
07-28 12:05:38.019  8552  8574 D elm:14491: MDMBridge.getInstance()
07-28 12:05:38.019  8552  8574 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,07-28 12:05:38.029   906  1121 I EventHub: Removing device '/dev/input/event7' due to inotify event
,07-28 12:05:38.029  8552  8574 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,07-28 12:05:38.059  8576  8576 E Zygote  : MountEmulatedStorage()
07-28 12:05:38.059  8576  8576 E Zygote  : v2
07-28 12:05:38.059  8576  8576 I libpersona: KNOX_SDCARD checking this for 10021
07-28 12:05:38.059  8576  8576 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:38.059   906  3355 I ActivityManager: Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8576 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,07-28 12:05:38.079   906  1121 I EventHub: Removing device '/dev/input/event8' due to inotify event
,07-28 12:05:38.089  8576  8576 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:05:38.089  8576  8576 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:05:38.089  8576  8576 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:05:38.089  8552  8552 D elm:14491: ElmAgentService : onDestroy().
,07-28 12:05:38.089   906  1031 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1266d4d0 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t97} time:193899
,07-28 12:05:38.119   906  1121 I EventHub: Removing device '/dev/input/event9' due to inotify event
,07-28 12:05:38.119  8576  8576 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:05:38.119  8576  8576 D ActivityThread: Added TimaKeyStore provider
,07-28 12:05:38.139   906  1465 I ActivityManager: Killing 5972:sstream.app/u0a25 (adj 15): emptyCount ##41
,07-28 12:05:38.139  8576  8576 D ResourcesManager: creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,07-28 12:05:38.149  8576  8576 W ContextImpl: Unable to create files subdir /data/data/com.sec.android.service.health/cache
07-28 12:05:38.149  8576  8576 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,07-28 12:05:38.159  8576  8576 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
07-28 12:05:38.159  8576  8576 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
07-28 12:05:38.159  8576  8576 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
,07-28 12:05:38.159   906  1709 I ActivityManager: Killing 6881:com.samsung.android.app.galaxyfinder/u0a39 (adj 15): emptyCount ##41
,07-28 12:05:38.169   906  1121 I EventHub: Removing device '/dev/input/event10' due to inotify event
,07-28 12:05:38.219  6859  6859 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-28 12:05:38.219  6859  6859 I PCWCLIENTTRACE_PushUtil: sales region : global
07-28 12:05:38.219  6859  6859 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-28 12:05:38.219  6859  6859 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,07-28 12:05:38.219   906  3064 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.galaxyfinder, hostingType: broadcast
07-28 12:05:38.219   906  3064 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:38.219   906  3064 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:38.219   906  3064 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:38.219   906  3064 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:38.229  6566  8525 I SA      : [RC New] Execute method=[GET] start
,07-28 12:05:38.249   906  1121 I EventHub: Removing device '/dev/input/event11' due to inotify event
,07-28 12:05:38.259  8591  8591 E Zygote  : MountEmulatedStorage()
07-28 12:05:38.259  8591  8591 E Zygote  : v2
07-28 12:05:38.259  8591  8591 I libpersona: KNOX_SDCARD checking this for 10039
07-28 12:05:38.259  8591  8591 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:38.269  6566  8525 I SA      : [RC New] Security=[true]
07-28 12:05:38.269   906  3064 I ActivityManager: Start proc com.samsung.android.app.galaxyfinder for broadcast com.samsung.android.app.galaxyfinder/.ApplicationStatusReceiver: pid=8591 uid=10039 gids={50039, 9997, 1028, 1015, 3003, 3002} abi=armeabi-v7a
,07-28 12:05:38.269  6566  8525 I System.out: Thread-1060(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,07-28 12:05:38.279   906  1121 I EventHub: Removing device '/dev/input/event12' due to inotify event
,07-28 12:05:38.279  6566  8525 I System.out: Thread-1060(ApacheHTTPLog):isShipBuild true
,07-28 12:05:38.329  8591  8591 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-28 12:05:38.329  8591  8591 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:05:38.329  8591  8591 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
07-28 12:05:38.329  6566  8525 I System.out: Thread-1060(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,07-28 12:05:38.349   906  1121 I EventHub: Removing device '/dev/input/event13' due to inotify event
,07-28 12:05:38.349  8591  8591 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:05:38.349  8591  8591 D ActivityThread: Added TimaKeyStore provider
,07-28 12:05:38.369  8591  8591 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,07-28 12:05:38.369  8591  8591 W ContextImpl: Unable to create files subdir /data/data/com.samsung.android.app.galaxyfinder/cache
07-28 12:05:38.369  8591  8591 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,07-28 12:05:38.379  8591  8591 I FeatureConfig: init() refresh[false], Select[false], DisplayOrder[false], HelpMenu[false]
,07-28 12:05:38.399  8591  8591 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,07-28 12:05:38.399  8591  8591 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-28 12:05:38.399  8591  8591 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-28 12:05:38.409  8591  8591 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,07-28 12:05:38.409  8591  8591 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,07-28 12:05:38.409  8591  8591 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:05:38.409  8591  8591 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
07-28 12:05:38.409  8591  8591 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-28 12:05:38.409  8591  8591 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
07-28 12:05:38.409  8591  8591 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,07-28 12:05:38.409  8591  8591 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecSettings/SecSettings.apk
,07-28 12:05:38.419  8591  8591 W ResourcesManager: Asset path '/system/framework/sec_platform_library.jar' does not exist or contains no resources.
,07-28 12:05:38.419  8591  8591 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
07-28 12:05:38.419  8591  8591 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-28 12:05:38.419  8591  8591 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-28 12:05:38.419  8591  8591 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-28 12:05:38.419  8591  8591 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-28 12:05:38.419  8591  8591 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,07-28 12:05:38.419  8591  8591 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-28 12:05:38.429   906  1121 I EventHub: Removing device '/dev/input/event14' due to inotify event
,07-28 12:05:38.429  8591  8591 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,07-28 12:05:38.429  8591  8591 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,07-28 12:05:38.429  8591  8591 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-28 12:05:38.429  8591  8591 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:05:38.429  8591  8591 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-28 12:05:38.439  8591  8591 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,07-28 12:05:38.439  8591  8591 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
07-28 12:05:38.439  8591  8591 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-28 12:05:38.439  8591  8591 W ResourcesManager: Asset path '/system/framework/imsmanager.jar' does not exist or contains no resources.
,07-28 12:05:38.439  8591  8591 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,07-28 12:05:38.439  8591  8591 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-28 12:05:38.439  8591  8591 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:05:38.439  8591  8591 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
07-28 12:05:38.439  8591  8591 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-28 12:05:38.439  8591  8591 W ResourcesManager: Asset path '/system/framework/svi.jar' does not exist or contains no resources.
07-28 12:05:38.439  8591  8591 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-28 12:05:38.439  8591  8591 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-28 12:05:38.449  8591  8591 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,07-28 12:05:38.449  8591  8591 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-28 12:05:38.449  8591  8591 W ResourcesManager: Asset path '/system/framework/sec_feature.jar' does not exist or contains no resources.
07-28 12:05:38.449  8591  8591 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-28 12:05:38.449  8591  8591 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-28 12:05:38.449  8591  8591 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,07-28 12:05:38.459  8591  8591 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,07-28 12:05:38.459  8591  8591 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-28 12:05:38.459  8591  8591 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
07-28 12:05:38.459  8591  8591 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-28 12:05:38.459  8591  8591 W ResourcesManager: Asset path '/system/framework/videowall.jar' does not exist or contains no resources.
,07-28 12:05:38.459  8591  8591 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,07-28 12:05:38.459  8591  8591 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,07-28 12:05:38.459  8591  8591 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,07-28 12:05:38.459  8591  8591 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-28 12:05:38.459  8591  8591 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-28 12:05:38.459  8591  8591 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,07-28 12:05:38.469  8591  8591 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-28 12:05:38.469  8591  8591 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-28 12:05:38.469  8591  8591 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,07-28 12:05:38.469  8591  8591 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:05:38.469  8591  8591 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
07-28 12:05:38.469  8591  8591 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-28 12:05:38.469  8591  8591 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-28 12:05:38.479  8591  8591 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,07-28 12:05:38.479  8591  8591 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,07-28 12:05:38.479  8591  8591 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-28 12:05:38.479  8591  8591 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,07-28 12:05:38.479  8591  8591 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,07-28 12:05:38.489  8591  8591 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,07-28 12:05:38.489  8591  8591 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,07-28 12:05:38.489  8591  8591 W ResourcesManager: Asset path '/system/framework/minimode.jar' does not exist or contains no resources.
,07-28 12:05:38.499  8591  8591 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,07-28 12:05:38.499  8591  8591 W ResourcesManager: Asset path '/system/framework/smatlib.jar' does not exist or contains no resources.
,07-28 12:05:38.499  8591  8591 W ResourcesManager: Asset path '/system/framework/secvisualeffect.jar' does not exist or contains no resources.
07-28 12:05:38.499  8591  8591 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-28 12:05:38.499  8591  8591 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
07-28 12:05:38.499  8591  8591 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-28 12:05:38.499  8591  8591 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
,07-28 12:05:38.499  8591  8591 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,07-28 12:05:38.499  8591  8591 W ResourcesManager: Asset path '/system/framework/secmediarecorder.jar' does not exist or contains no resources.
,07-28 12:05:38.499  8591  8591 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-28 12:05:38.509  8591  8591 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/pref_package.xml
,07-28 12:05:38.519  8591  8591 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/pref_package.xml
,07-28 12:05:38.529  8591  8591 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/com.samsung.android.app.galaxyfinder_preferences.xml
,07-28 12:05:38.579   906  1541 D ActivityManager: startService callerProcessName:com.sec.android.app.shealth, calleePkgName: com.sec.android.app.shealth
,07-28 12:05:38.579   906  1541 D ActivityManager: caller:android.app.ApplicationThreadProxy@1f0a44d3, r.packageName :com.sec.android.app.shealth
,07-28 12:05:38.589  4465  8609 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-28 12:05:38.589  4465  8609 E SQLiteLog: (3850) statement aborts at 19: [delete  from app_registry where package_name= "com.test.thalitest" AND plugin_id= "1"] disk I/O error
,07-28 12:05:38.589  4465  8609 E SQLiteQuery: exception: disk I/O error (code 3850); query: delete  from app_registry where package_name= "com.test.thalitest" AND plugin_id= "1"
,07-28 12:05:38.589  4465  8609 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9f4fdf8c in tid 8609 (IntentService[H)
,07-28 12:05:38.589  7894  7894 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/registration_db" with flag (131138) and mode_t (0) due to error (2)
,07-28 12:05:38.589  7894  7894 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/registration_db" with flag (131072) and mode_t (0) due to error (2)
07-28 12:05:38.589  7894  7894 E SQLiteLog: (14) cannot open file at line 32509 of [b3bb660af9]
07-28 12:05:38.589  7894  7894 E SQLiteLog: (14) os_unix.c:32509: (2) open(/data/data/com.sec.spp.push/databases/registration_db) - 
,07-28 12:05:38.589  7894  7894 E SQLiteDatabase: Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at com.sec.spp.push.h.a.a(Unknown Source)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at com.sec.spp.push.h.c.d(Unknown Source)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.onReceive(Unknown Source)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:05:38.589  7894  7894 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,07-28 12:05:38.589  7894  7894 E SPPClientService: [c] [getAppId()] SQLiteException with message =unknown error (code 14): Could not open database
07-28 12:05:38.589   906  3331 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
07-28 12:05:38.589   906  3331 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:38.589   906  3331 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:38.589   906  3331 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:05:38.589   906  3331 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:05:38.629  8610  8610 E Zygote  : MountEmulatedStorage()
,07-28 12:05:38.629  8610  8610 E Zygote  : v2
07-28 12:05:38.629  8610  8610 I libpersona: KNOX_SDCARD checking this for 10043
07-28 12:05:38.629  8610  8610 I libpersona: KNOX_SDCARD not a persona
,07-28 12:05:38.639   906  3331 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8610 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:05:38.649   267   523 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,07-28 12:05:38.679  8610  8610 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:05:38.679  8610  8610 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:05:38.679  8610  8610 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,07-28 12:05:38.689   295   295 I DEBUG   : failed to change ownership of /data/tombstones: Read-only file system
07-28 12:05:38.689   295   295 E         : ro.product_ship = true
07-28 12:05:38.689   295   295 E         : ro.debug_level = 0x4f4c
,07-28 12:05:38.689  1832  1832 E audit_log: File locking failed. error= Bad file number

```
