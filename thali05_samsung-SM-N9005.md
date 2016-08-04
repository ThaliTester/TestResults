#### Test 800380637c16410_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
08-04 10:45:58.217   746  1366 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-04 10:45:58.217   746  1366 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 281, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
08-04 10:45:58.217   746  1366 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
08-04 10:45:58.217   746  1366 D BatteryService: stay LED for fully charged
08-04 10:45:58.217   746   746 D BatteryService: Sending ACTION_BATTERY_CHANGED.
--------- beginning of main
08-04 10:45:58.237  1190  1190 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-04 10:45:58.237  1190  1190 D KeyguardUpdateMonitor: handleBatteryUpdate
08-04 10:45:58.237  3212  3212 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-04 10:45:58.237  3212  3303 D HeadsetStateMachine: Disconnected process message: 10
08-04 10:45:58.237   746   746 I MotionRecognitionService: Plugged
08-04 10:45:58.237   746   746 I MotionRecognitionService: setPowerConnected  = true
08-04 10:45:58.237  1190  1190 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
08-04 10:45:58.237  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-04 10:45:58.237  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-04 10:45:58.237  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-04 10:45:58.258   310   310 E SMD     : DCD ON
,08-04 10:45:58.727  7538  7538 D AndroidRuntime: 
08-04 10:45:58.727  7538  7538 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-04 10:45:58.737  7538  7538 D AndroidRuntime: CheckJNI is OFF
08-04 10:45:58.737  7538  7538 D AndroidRuntime: readGMSProperty: start
08-04 10:45:58.737  7538  7538 D AndroidRuntime: readGMSProperty: already setted!!
08-04 10:45:58.737  7538  7538 D AndroidRuntime: readGMSProperty: end
08-04 10:45:58.737  7538  7538 D AndroidRuntime: addProductProperty: start
08-04 10:45:58.897  7538  7538 E AffinityControl: AffinityControl: registerfunction enter
08-04 10:45:58.927  7538  7538 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-04 10:45:58.927   746   764 E PersonaManagerService: inState():  stateMachine is null !!
08-04 10:45:58.927   746   764 I PersonaManagerService: PersonaId don't exist
08-04 10:45:58.927   746   764 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-04 10:45:58.937   746   764 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-04 10:45:58.937   746   764 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-04 10:45:58.937   746   764 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
08-04 10:45:58.937   746   764 W ActivityManager: mDVFSHelper.acquire()
08-04 10:45:58.947   746   764 D FocusedStackFrame: Set to : 0
08-04 10:45:58.947   746   764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:45:58.947   746   764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:45:58.947   746   764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:45:58.947   746   764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:45:58.997   746   764 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7553 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-04 10:45:59.017  7553  7553 E Zygote  : MountEmulatedStorage()
08-04 10:45:59.017  7553  7553 E Zygote  : v2
08-04 10:45:59.017  7553  7553 I libpersona: KNOX_SDCARD checking this for 10079
08-04 10:45:59.017  7553  7553 I libpersona: KNOX_SDCARD not a persona
08-04 10:45:59.017   746  1030 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-04 10:45:59.017   746  1030 D PointerIcon: setMouseCustomIcon IconType is same.101
08-04 10:45:59.017   746  1030 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-04 10:45:59.017   746  1030 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-04 10:45:59.017  7538  7538 D AndroidRuntime: Shutting down VM
08-04 10:45:59.047   361   361 I art     : Explicit concurrent mark sweep GC freed 8769(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 530us total 39.211ms
08-04 10:45:59.047  7553  7553 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 10:45:59.047  7553  7553 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 10:45:59.047  7553  7553 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-04 10:45:59.057   361   361 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 393us total 16.853ms
08-04 10:45:59.067   361   361 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 275us total 9.464ms
08-04 10:45:59.077  7553  7553 D TimaKeyStoreProvider: TimaSignature is unavailable
08-04 10:45:59.077  7553  7553 D ActivityThread: Added TimaKeyStore provider
08-04 10:45:59.077   746  1696 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-04 10:45:59.077   746  1696 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
08-04 10:45:59.077   746  1696 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-04 10:45:59.077   746  1696 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-04 10:45:59.077   746  1696 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
08-04 10:45:59.097  1419  1419 D SurfaceWidgetView: destroyHardwareResources():1033425470
08-04 10:45:59.127   746  3312 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:45:59.127   267   323 I SurfaceFlinger: id=7 Removed Mauncher (6/8)
08-04 10:45:59.137   267  1353 I SurfaceFlinger: id=7 Removed Mauncher (-2/8)
08-04 10:45:59.137  1419  1419 D Launcher: onTrimMemory. Level: 20
08-04 10:45:59.137  1419  1419 V ActivityThread: updateVisibility : ActivityRecord{24c5f327 token=android.os.BinderProxy@1bab3900 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-04 10:45:59.147  7553  7553 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
08-04 10:45:59.157  1760  1773 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
08-04 10:45:59.157   746  3312 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:45:59.247  7553  7553 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
08-04 10:45:59.247  7553  7553 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
08-04 10:45:59.267  7553  7553 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2302-2305)
08-04 10:45:59.267  7553  7553 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 10:45:59.287  7553  7553 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {36eb6a8}
08-04 10:45:59.287  7553  7553 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 10:45:59.287  7553  7553 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
08-04 10:45:59.317  7553  7553 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-04 10:45:59.327  7553  7553 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 10:45:59.327  7553  7553 E SysUtils: ApplicationContext is null in ApplicationStatus
08-04 10:45:59.347  7553  7553 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
08-04 10:45:59.347  7553  7553 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
08-04 10:45:59.347  7553  7553 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
08-04 10:45:59.347  7553  7553 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
08-04 10:45:59.347  7553  7553 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
08-04 10:45:59.347  7553  7553 I Adreno-EGL: Build Date: 11/19/14 Wed
08-04 10:45:59.347  7553  7553 I Adreno-EGL: Local Branch: mybranch5813579
08-04 10:45:59.347  7553  7553 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
08-04 10:45:59.347  7553  7553 I Adreno-EGL: Local Patches: NONE
08-04 10:45:59.347  7553  7553 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
08-04 10:45:59.467  7553  7590 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
08-04 10:45:59.497  7553  7553 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 10:45:59.497  7553  7553 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-04 10:45:59.517  7553  7553 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
08-04 10:45:59.517  7553  7553 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 10:45:59.517  7553  7553 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-04 10:45:59.567  7553  7553 D Activity: performCreate Call secproduct feature valuefalse
08-04 10:45:59.567  7553  7553 D Activity: performCreate Call debug elastic valuetrue
08-04 10:45:59.577  7553  7606 D OpenGLRenderer: Render dirty regions requested: true
08-04 10:45:59.587   746  1471 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
08-04 10:45:59.587   746  1471 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-04 10:45:59.587   746  1471 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-04 10:45:59.587   746   746 D KnoxTimeoutHandler: handleActiveUserChange for user 0
08-04 10:45:59.587   746   746 D PersonaManagerService: getPersonasForUser(): returning null!
08-04 10:45:59.597   267   267 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
08-04 10:45:59.607   746  1026 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-04 10:45:59.607   746  1026 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-04 10:45:59.627   746  1030 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-04 10:45:59.627   746  1030 D PointerIcon: setMouseCustomIcon IconType is same.101
08-04 10:45:59.627   746  1030 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-04 10:45:59.627   746  1030 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-04 10:45:59.627  7553  7606 I OpenGLRenderer: Initialized EGL, version 1.4
08-04 10:45:59.637  7553  7606 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xb3decec0 ,&mEglDisplay = 1 , &mEglConfig = 8 
08-04 10:45:59.637  7553  7606 D OpenGLRenderer: Enabling debug mode 0
08-04 10:45:59.657  7553  7553 V ActivityThread: updateVisibility : ActivityRecord{3129a7a2 token=android.os.BinderProxy@2769fb84 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
08-04 10:45:59.677   746  1444 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
08-04 10:45:59.677   746  7610 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
08-04 10:45:59.687  1688  1688 I SamsungIME: getCurrentCandidateView
08-04 10:45:59.687  7553  7553 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-04 10:45:59.697   746  1030 W ActivityManager: mDVFSHelper.release()
08-04 10:45:59.697   746  1030 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3510508c u0 com.test.thalitest/.MainActivity t99} time:152731
08-04 10:45:59.697  7553  7553 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2769fb84 time:152732
08-04 10:45:59.727  7553  7553 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7553
08-04 10:45:59.737  1688  1688 D SamsungIME: Dismiss ExpandCandiate
08-04 10:45:59.807  7553  7553 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-04 10:45:59.817  1688  1688 I SamsungIME: getDebugLevel  : 0x4f4c
08-04 10:45:59.847  1688  1688 I SamsungIME: getDebugLevel  : 0x4f4c
08-04 10:45:59.857  1688  1688 I SamsungIME: KeybaordView init() : load resources
08-04 10:45:59.877  1688  1688 I SamsungIME: getCurrentKeyboard
08-04 10:45:59.877  1688  1688 I SamsungIME: getTextKeyboard
08-04 10:45:59.887  1688  1688 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
08-04 10:45:59.907  7553  7612 D jxcore_app_log: JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1357928832
08-04 10:45:59.917  7553  7612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-04 10:45:59.917  7553  7612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-04 10:45:59.917  7553  7612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-04 10:45:59.917  7553  7612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-04 10:45:59.917  7553  7612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-04 10:45:59.917  7553  7612 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1b2f3d52 added. We now have 1 listener(s)
08-04 10:45:59.917  7553  7612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:1F:C9:5E
08-04 10:45:59.917  7553  7612 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
08-04 10:45:59.927  7553  7612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:45:59.927  7553  7612 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:45:59.927  7553  7612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-04 10:45:59.927  7553  7612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-04 10:45:59.927  7553  7612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-04 10:45:59.927  7553  7612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:1F:C9:5E
08-04 10:45:59.927  7553  7612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-04 10:45:59.927  7553  7612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-04 10:45:59.927  7553  7612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-04 10:45:59.927  7553  7612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-04 10:45:59.927  7553  7612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-04 10:45:59.927  7553  7612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-04 10:45:59.927  7553  7612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-04 10:45:59.927  7553  7612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-04 10:45:59.927  7553  7612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-04 10:45:59.927  7553  7612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-04 10:45:59.927  7553  7612 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17cbad9 added. We now have 1 listener(s)
08-04 10:45:59.927  7553  7612 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:45:59.937  7553  7612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 10:45:59.937  7553  7612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-04 10:45:59.937  7553  7612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-04 10:45:59.937  7553  7612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-04 10:45:59.937  7553  7612 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-04 10:45:59.947  7553  7612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:45:59.947  7553  7612 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:1F:C9:5E
08-04 10:45:59.947   746  1461 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:45:59.957  7553  7612 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-04 10:45:59.957  7553  7612 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:45:59.957  7553  7612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:45:59.957  7553  7612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:45:59.957  7553  7612 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:45:59.957  7553  7612 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:45:59.957  7553  7612 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:45:59.957  7553  7612 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:45:59.957  7553  7612 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 10:45:59.957  7553  7612 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-04 10:45:59.957  7553  7612 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:45:59.957  7553  7612 I io.jxcore.node.LifeCycleMonitor: start: OK
08-04 10:45:59.957   746   764 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:45:59.957  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:45:59.957   746   762 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:45:59.957  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:45:59.977  7553  7553 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
08-04 10:45:59.987   746  1117 V AlarmManager: waitForAlarm result :8
,08-04 10:46:00.237  1688  7616 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
08-04 10:46:00.637  7553  7621 W jxcore-log: Initializing JXcore engine
08-04 10:46:00.637  7553  7621 W jxcore-log: JXcore engine is ready
08-04 10:46:00.687  1895  1895 E auditd  : In denial and Property audit_ondenial is set to 1 
08-04 10:46:00.687   746  1018 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
08-04 10:46:00.687  1895  1895 E audit   : type=1400 msg=audit(1470300360.677:203): avc:  denied  { ioctl } for  pid=7621 comm="Thread-1239" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-04 10:46:00.687   746  1018 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
08-04 10:46:00.687   746   915 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
08-04 10:46:00.687  1895  1895 E audit   :  SEPF_SM-N9005_5.0-1_0032
08-04 10:46:00.687  1895  1895 E audit   : 
08-04 10:46:00.687   746   915 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:00.687  1895  1895 E audit   : type=1300 msg=audit(1470300360.677:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=98ae08d8 items=0 ppid=361 ppcomm=main pid=7621 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1239" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
08-04 10:46:00.687   746   915 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:00.687   746   915 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:00.687   746   915 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:00.687  1895  1895 E audit   : type=1320 msg=audit(1470300360.677:203): 
08-04 10:46:00.687   746  1018 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
08-04 10:46:00.697  7553  7621 W jxcore-log: Starting JXcore engine
08-04 10:46:00.737   746   915 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7624 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
08-04 10:46:00.737  7624  7624 E Zygote  : MountEmulatedStorage()
08-04 10:46:00.737  7624  7624 E Zygote  : v2
08-04 10:46:00.737  7624  7624 I libpersona: KNOX_SDCARD checking this for 1000
08-04 10:46:00.737  7624  7624 I libpersona: KNOX_SDCARD not a persona
08-04 10:46:00.767  7624  7624 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 10:46:00.767  7624  7624 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 10:46:00.767  7624  7624 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-04 10:46:00.787  7553  7621 W jxcore-log: Platform android
08-04 10:46:00.787  7553  7621 W jxcore-log: 
08-04 10:46:00.787  7553  7621 W jxcore-log: Process ARCH arm
08-04 10:46:00.787  7553  7621 W jxcore-log: 
08-04 10:46:00.797  7624  7624 D TimaKeyStoreProvider: TimaSignature is unavailable
08-04 10:46:00.797  7624  7624 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:00.817  7624  7624 D ResourcesManager: creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,08-04 10:46:00.827  7624  7624 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,08-04 10:46:00.827  7624  7624 D SecurityLogAgent:  SeDenialReceiver : File path = null
,08-04 10:46:00.837   746  1461 I ActivityManager: Killing 5234:com.google.android.music:main/u0a144 (adj 15): emptyCount ##41
,08-04 10:46:00.987   746  1036 I PowerManagerService: [PWL] Off : 75s ago
,08-04 10:46:00.997  7553  7621 I jxcore-log: JXcore Cordova bridge is ready!
08-04 10:46:00.997  7553  7621 I jxcore-log: 
,08-04 10:46:00.997  7553  7621 W jxcore-log: JXcore engine is started
,08-04 10:46:00.997  7553  7612 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-04 10:46:01.007  7553  7553 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-04 10:46:01.257   310   310 E SMD     : DCD ON
,08-04 10:46:04.247   746  3345 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-04 10:46:04.257   310   310 E SMD     : DCD ON
,08-04 10:46:06.547   746  3312 D SSRM:n  : SIOP:: AP = 370, PST = 357, CUR = 450
,08-04 10:46:07.257   310   310 E SMD     : DCD ON
,08-04 10:46:07.567   369   369 I ServiceManager: Waiting for service AtCmdFwd...
,08-04 10:46:08.297   746  1696 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-04 10:46:08.297   746  1696 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,08-04 10:46:08.297   746  1696 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,08-04 10:46:08.297   746   746 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-04 10:46:08.297  1190  1190 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-04 10:46:08.297  1190  1190 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-04 10:46:08.307   746   746 I MotionRecognitionService: Plugged
08-04 10:46:08.307   746   746 I MotionRecognitionService: setPowerConnected  = true
,08-04 10:46:08.307   746  1696 D BatteryService: stay LED for fully charged
,08-04 10:46:08.317  1190  1190 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
08-04 10:46:08.317  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-04 10:46:08.317  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-04 10:46:08.317  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-04 10:46:08.317  3212  3212 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-04 10:46:08.317  3212  3303 D HeadsetStateMachine: Disconnected process message: 10
,08-04 10:46:08.567   369   369 I ServiceManager: Waiting for service AtCmdFwd...
,08-04 10:46:08.987   746  1052 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-04 10:46:09.567   369   369 I ServiceManager: Waiting for service AtCmdFwd...
,08-04 10:46:10.257   310   310 E SMD     : DCD ON
,08-04 10:46:10.567   369   369 I ServiceManager: Waiting for service AtCmdFwd...
,08-04 10:46:10.777  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-04 10:46:10.777  7553  7621 I jxcore-log: 
,08-04 10:46:10.777  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-04 10:46:10.777  7553  7621 I jxcore-log: 
,08-04 10:46:10.777   746   762 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false],
,08-04 10:46:10.777  7553  7621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:46:10.777  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:10.777  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:10.777  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:10.777  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:10.777  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:10.777  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:46:10.777  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 10:46:10.777  7553  7621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 10:46:10.787  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-04 10:46:10.787  7553  7621 I jxcore-log: 
,08-04 10:46:10.787  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-04 10:46:10.787  7553  7621 I jxcore-log: 
,08-04 10:46:11.117  7553  7621 D ExecuteNativeTests: Running unit tests
,08-04 10:46:11.217  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:46:11.217  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 added. We now have 2 listener(s)
,08-04 10:46:11.217  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,08-04 10:46:11.217  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:46:11.217  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:46:11.217  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:11.217  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 added. We now have 2 listener(s)
08-04 10:46:11.217  7553  7621 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:46:11.217  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 10:46:11.217  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 10:46:11.217   746  1461 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:11.227  7553  7621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:46:11.227  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:11.227  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:11.227  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:11.227  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:11.227  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:11.227  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:46:11.227  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 10:46:11.227  7553  7621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 10:46:11.227  7553  7621 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:46:11.227   746  1459 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:11.227  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:11.227   746  1426 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:11.227  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:11.227  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-04 10:46:11.227  7553  7621 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 10:46:11.227  7553  7621 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-04 10:46:11.227  7553  7621 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-04 10:46:11.227  7553  7621 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-04 10:46:11.227  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 10:46:11.227  7553  7621 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 10:46:11.237  7553  7621 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-04 10:46:11.237  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 10:46:11.237  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 10:46:11.237  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 10:46:11.247  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 10:46:11.247  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.247  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:46:11.247  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-04 10:46:11.247  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 removed from the list
08-04 10:46:11.247  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.247  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 removed from the list
08-04 10:46:11.247  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:11.247  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:11.247  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.247  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:11.247  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:11.247  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:11.247  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.247  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
,08-04 10:46:11.247  7553  7621 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,08-04 10:46:11.247  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:11.247  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:11.247  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:11.247  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:11.247  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 10:46:11.247  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.247  7553  7621 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 not in the list
08-04 10:46:11.247  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.247  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.247  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:11.247  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.247  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.247  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 10:46:11.247  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.247  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:11.247  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 10:46:11.247  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.247  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
,08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-04 10:46:11.257  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:11.257  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:11.257  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 10:46:11.257  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:11.257  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.257  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.257  7553  7621 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 not in the list
08-04 10:46:11.257  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.257  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.257  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 10:46:11.257  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.257  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.257  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.257  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:11.257  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:11.257  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:11.257  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.257  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
,08-04 10:46:11.267  7553  7621 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-04 10:46:11.267  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 10:46:11.267   746  1459 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:11.267  7553  7621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:46:11.267  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:11.267  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:11.267  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:11.267  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:11.267  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:11.267  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:46:11.267  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 10:46:11.267  7553  7621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 10:46:11.267  7553  7621 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:46:11.267   746  1298 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:11.267  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:11.267   746  1401 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:11.267  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:11.267  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-04 10:46:11.267  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 10:46:11.267  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 10:46:11.267  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:11.267  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-04 10:46:11.277  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-04 10:46:11.277  7553  7621 E BluetoothAdapter: bluetooth le advertising not supported
,08-04 10:46:11.277  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-04 10:46:11.277  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 10:46:11.277  7553  7621 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,08-04 10:46:11.287  7553  7621 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
,08-04 10:46:11.287  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-04 10:46:11.287  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 10:46:11.287  7553  7621 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-04 10:46:11.287  7553  7621 I io.jxcore.node.ConnectionHelper: start: OK
,08-04 10:46:11.287  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 10:46:11.287  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:11.287  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:11.287  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:11.287  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.287  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:46:11.287  7553  7621 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 not in the list
,08-04 10:46:11.287  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.287  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.287  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:11.287  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:11.287  7553  7621 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-04 10:46:11.287  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 10:46:11.287   746  1455 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:11.297  7553  7621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:46:11.297  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:11.297  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:11.297  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:11.297  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:11.297  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:11.297  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:46:11.297  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 10:46:11.297  7553  7621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 10:46:11.297  7553  7621 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:46:11.297  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 10:46:11.297  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 10:46:11.297  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 10:46:11.297  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:11.297   746  1696 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:11.297  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-04 10:46:11.297  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:11.297   746  1298 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:11.297  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:11.297  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-04 10:46:11.297  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 10:46:11.307  7553  7621 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-04 10:46:11.307  7553  7621 I io.jxcore.node.ConnectionHelper: start: OK
,08-04 10:46:11.307  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:11.307  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 10:46:11.307  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:11.307  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:11.307  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.307  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:46:11.307  7553  7621 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 not in the list
,08-04 10:46:11.307  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.307  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.307  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:11.307  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:11.307  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.307  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:11.307  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:11.307  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:11.307  7553  7621 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:11.307  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:11.307  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.307  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
,08-04 10:46:11.307  7553  7621 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-04 10:46:11.307  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 10:46:11.307   746  1297 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:11.307  7553  7621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:46:11.307  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:11.307  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:11.307  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:11.307  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:11.307  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:11.307  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:46:11.307  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 10:46:11.317  7553  7621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-04 10:46:11.317  7553  7621 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:46:11.317   746  1298 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:11.317  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:11.317   746  1401 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:11.317  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:11.317  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 10:46:11.317  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 10:46:11.317  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 10:46:11.317  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:11.317  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-04 10:46:11.317  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-04 10:46:11.317  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 10:46:11.317  7553  7621 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-04 10:46:11.317  7553  7621 I io.jxcore.node.ConnectionHelper: start: OK
,08-04 10:46:11.317  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:11.317  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:11.317  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 10:46:11.317  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:11.327  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:11.327  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:11.327  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:11.327  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.327  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 10:46:11.327  7553  7621 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 not in the list
08-04 10:46:11.327  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.327  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.327  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:11.327  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:11.327  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.327  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:11.327  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:11.327  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:11.327  7553  7621 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:11.327  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:11.327  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.327  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
,08-04 10:46:11.327  7553  7621 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,08-04 10:46:11.327  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:11.327  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:11.327  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:11.327  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:11.327  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.327  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:11.327  7553  7621 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 not in the list
08-04 10:46:11.327  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.327  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.327  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:11.327  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.327  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.327  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 10:46:11.327  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.327  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:11.327  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 10:46:11.327  7553  7621 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:11.327  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:11.327  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.327  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
,08-04 10:46:11.327  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-04 10:46:11.327  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:11.327  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:11.327  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:11.327  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:11.327  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.327  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:11.327  7553  7621 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 not in the list
08-04 10:46:11.327  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.327  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.327  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:11.327  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.327  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.327  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-04 10:46:11.327  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.327  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-04 10:46:11.337  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:11.337  7553  7621 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:11.337  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:11.337  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.337  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
,08-04 10:46:11.337  7553  7621 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-04 10:46:11.337  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 10:46:11.337  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:11.337  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:11.337  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:11.337  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.337  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.337  7553  7621 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 not in the list
,08-04 10:46:11.337  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.337  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.337  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:11.337  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.337  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.337  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.337  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:11.337  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:11.337  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-04 10:46:11.337  7553  7621 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:11.337  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:11.337  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.337  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
,08-04 10:46:11.337  7553  7621 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-04 10:46:11.337  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:11.337  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 10:46:11.337  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:11.337  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:11.337  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.337  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.337  7553  7621 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 not in the list
08-04 10:46:11.337  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.337  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
,08-04 10:46:11.337  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:11.337  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.337  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.337  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.337  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:11.337  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:11.337  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:11.337  7553  7621 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:11.337  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-04 10:46:11.337  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.337  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.337  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-04 10:46:11.337  7553  7621 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-04 10:46:11.337  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-04 10:46:11.347  7553  7621 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 10:46:11.347  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-04 10:46:11.347  7553  7621 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-04 10:46:11.347  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:11.347  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:11.347  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:11.347  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 10:46:11.347  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.347  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.347  7553  7621 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 not in the list
08-04 10:46:11.347  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.347  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.347  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:11.347  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.347  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:11.347  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.347  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:11.347  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:11.347  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:11.347  7553  7621 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:11.347  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:11.347  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.347  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
,08-04 10:46:11.347  7553  7621 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-04 10:46:11.347  7553  7621 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-04 10:46:11.347  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,08-04 10:46:11.357  7553  7621 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-04 10:46:11.357  7553  7621 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-04 10:46:11.357  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-04 10:46:11.357  7553  7621 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-04 10:46:11.357  7553  7621 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 10:46:11.357  7553  7621 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-04 10:46:11.357  7553  7621 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 10:46:11.357  7553  7621 W i,o.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 10:46:11.357  7553  7621 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-04 10:46:11.357  7553  7621 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 10:46:11.357  7553  7621 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-04 10:46:11.357  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-04 10:46:11.357  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-04 10:46:11.367  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-04 10:46:11.367  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-04 10:46:11.367  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-04 10:46:11.367  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-04 10:46:11.367  7553  7621 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-04 10:46:11.367  7553  7621 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-04 10:46:11.367  7553  7621 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-04 10:46:11.367  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:11.367  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:11.367  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:11.367  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:11.367  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.367  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.367  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-04 10:46:11.367  7553  7621 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 not in the list
08-04 10:46:11.367  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.367  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.367  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:11.367  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.367  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.367  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.367  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.367  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:11.367  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:11.367  7553  7621 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:11.367  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:11.367  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.367  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.377  7553  7656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1303)
08-04 10:46:11.377  7553  7621 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-04 10:46:11.377  7553  7657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1303
08-04 10:46:11.377  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:11.377  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:11.377  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:11.377  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:11.377  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.377  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.377  7553  7621 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 not in the list
08-04 10:46:11.387  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.387  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.387  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:11.387  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.387  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.387  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.387  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.387  7553  7656 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
08-04 10:46:11.387  7553  7656 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 10:46:11.387  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:11.387  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:11.387  7553  7621 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:11.387  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:11.387  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.387  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.387  3212  6568 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:46:11.387  7553  7621 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
,08-04 10:46:11.387  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:11.387  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:11.387  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:11.387  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:11.387  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.387  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.387  7553  7621 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 not in the list
08-04 10:46:11.387  3212  3407 D bt_vendor: op for 7
08-04 10:46:11.387  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.387  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.387  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:11.387  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.387  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.387  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.387  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.387  7553  7656 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[111]}
08-04 10:46:11.387  3212  3407 D bt_upio : proc btwrite assertion
08-04 10:46:11.387  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:11.387  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:11.387  7553  7621 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:11.387  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:11.387  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.397  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.397  7553  7621 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-04 10:46:11.397  7553  7621 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-04 10:46:11.397  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 10:46:11.397  7553  7621 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-04 10:46:11.397  7553  7621 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-04 10:46:11.397  7553  7621 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-04 10:46:11.397  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 10:46:11.397  7553  7621 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-04 10:46:11.397  7553  7621 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-04 10:46:11.397  7553  7621 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-04 10:46:11.397  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 10:46:11.397  7553  7621 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-04 10:46:11.397  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:11.397  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:11.397  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:11.397  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:11.397  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.397  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.397  7553  7621 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 not in the list
08-04 10:46:11.397  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.397  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.397  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:11.397  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.397  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.397  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.397  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.407  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:11.407  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:11.407  7553  7621 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:11.407  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:11.407  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.407  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.407  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:11.407  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.407  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.407  7553  7621 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 not in the list
08-04 10:46:11.407  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.407  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.407  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:11.407  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.407  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.407  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.407  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.407  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:11.407  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.407  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.407  7553  7621 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 not in the list
08-04 10:46:11.407  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:11.407  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:11.407  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:11.407  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:11.407  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.407  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.407  7553  7621 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 not in the list
08-04 10:46:11.407  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.407  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.407  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:11.407  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.407  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.407  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.407  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.407  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:11.407  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:11.407  7553  7621 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:11.407  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:11.407  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.407  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.407  7553  7621 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-04 10:46:11.407  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:11.417  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-04 10:46:11.417  7553  7621 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-04 10:46:11.417  7553  7621 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-04 10:46:11.417  7553  7553 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-04 10:46:11.417  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-04 10:46:11.417  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-04 10:46:11.417  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:11.417  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-04 10:46:11.417  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-04 10:46:11.417  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-04 10:46:11.417  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.417  7553  7621 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-04 10:46:11.417  7553  7621 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 not in the list
08-04 10:46:11.417  7553  7553 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-04 10:46:11.417  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.417  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-04 10:46:11.417  7553  7621 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-04 10:46:11.417  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-04 10:46:11.417  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-04 10:46:11.417  7553  7621 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:11.417  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:11.417  7553  7658 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-04 10:46:11.417  7553  7621 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-04 10:46:11.417  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.417  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.427  7553  7658 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[112]}
08-04 10:46:11.427  7553  7658 D BluetoothSocket: bindListen(), new LocalSocket 
08-04 10:46:11.427  7553  7658 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-04 10:46:11.427  7553  7658 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@47017a1
08-04 10:46:11.427  7553  7658 D BluetoothSocket: channel: 6
08-04 10:46:11.427  7553  7658 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@32734dc6, channel: 6, state: LISTENING
08-04 10:46:11.427  7553  7658 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@32734dc6, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@47017a1, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@9eea187mSocket: android.net.LocalSocket@253c18b4 impl:android.net.LocalSocketImpl@39558cdd fd:FileDescriptor[112]
08-04 10:46:11.427  7553  7658 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@253c18b4 impl:android.net.LocalSocketImpl@39558cdd fd:FileDescriptor[112]
08-04 10:46:11.427  7553  7658 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-04 10:46:11.427  7553  7658 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-04 10:46:11.427  7553  7621 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 10:46:11.427  7553  7553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 10:46:11.427  7553  7553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-04 10:46:11.427  7553  7553 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-04 10:46:11.427  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.427  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:11.427  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:11.427  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:11.427  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:11.427  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.427  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.427  7553  7621 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 not in the list
08-04 10:46:11.427  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.427  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.427  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:11.427  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.427  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.427  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.427  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.427  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:11.427  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:11.427  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.427  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.427  7553  7658 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-04 10:46:11.427  7553  7553 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-04 10:46:11.427  7553  7621 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-04 10:46:11.427  7553  7621 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-04 10:46:11.427  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-04 10:46:11.427  7553  7621 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-04 10:46:11.427  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:11.427  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:11.427  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:11.427  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:11.427  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.437  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.437  7553  7621 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 not in the list
08-04 10:46:11.437  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.437  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.437  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:11.437  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.437  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.437  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.437  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.437  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:11.437  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:11.437  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.437  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.437  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:11.437  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:11.437  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:11.437  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:11.437  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.437  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.437  7553  7621 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 not in the list
08-04 10:46:11.437  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.437  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.437  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:11.437  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.437  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.437  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.437  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.437  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:11.437  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:11.437  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.437  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.437  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:11.437  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:11.437  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:11.437  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:11.437  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.437  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.437  7553  7621 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@36edb333 not in the list
08-04 10:46:11.437  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.437  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.437  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:11.437  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.437  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.437  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:11.437  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:11.447  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:11.447  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:11.447  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:11.447  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c4106f0 not in the list
08-04 10:46:11.447  7553  7621 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-04 10:46:11.447  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 10:46:11.447  7553  7621 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-04 10:46:11.447  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-04 10:46:11.447  7553  7621 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-04 10:46:11.447  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-04 10:46:11.447  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-04 10:46:11.447  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-04 10:46:11.447  7553  7621 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-04 10:46:11.447  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-04 10:46:11.447  7553  7621 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-04 10:46:11.447  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-04 10:46:11.447  7553  7621 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-04 10:46:11.447  7553  7621 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-04 10:46:11.447  7553  7621 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-04 10:46:11.447  7553  7621 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-04 10:46:11.447  7553  7621 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-04 10:46:11.447  7553  7621 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-04 10:46:11.447  7553  7621 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-04 10:46:11.447  7553  7621 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-04 10:46:11.457  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:11.457  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a468052 added. We now have 2 listener(s)
08-04 10:46:11.457  7553  7621 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:46:11.457  7553  7621 D BluetoothAdapter: enable()
08-04 10:46:11.457  7553  7621 D BluetoothAdapter: enable(): BT is already enabled..!
08-04 10:46:11.457  7553  7621 I WifiManager: packageName : com.test.thalitest
08-04 10:46:11.457   746   762 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-04 10:46:11.457   746   762 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-04 10:46:11.457   746   762 D SecContentProvider2: mCursor = null
08-04 10:46:11.457   746   762 D WifiService: setWifiEnabled: true pid=7553, uid=10079
08-04 10:46:11.457   746   762 W ActivityManager: Permission Denial: getCurrentUser() from pid=7553, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-04 10:46:11.457   746   762 W WifiService: Failed getting userId using ActivityManagerNative
08-04 10:46:11.457   746   762 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7553, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-04 10:46:11.457   746   762 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
08-04 10:46:11.457   746   762 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
08-04 10:46:11.457   746   762 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
08-04 10:46:11.457   746   762 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-04 10:46:11.457   746   762 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-04 10:46:11.457   746   762 D SettingsProvider: name = wifi_on
08-04 10:46:11.457  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:11.457  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c89cf23 added. We now have 3 listener(s)
08-04 10:46:11.457  7553  7621 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:46:11.457  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:11.457  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@bdc0c20 added. We now have 4 listener(s)
08-04 10:46:11.467  7553  7621 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:46:11.467  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:11.467  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@192319d9 added. We now have 5 listener(s)
08-04 10:46:11.467  7553  7621 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:46:11.467  7553  7621 I WifiManager: packageName : com.test.thalitest
08-04 10:46:11.467   746  1366 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-04 10:46:11.467   746  1366 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-04 10:46:11.467   746  1366 D SecContentProvider2: mCursor = null
08-04 10:46:11.467   746  1366 D WifiService: setWifiEnabled: false pid=7553, uid=10079
,08-04 10:46:11.467   746  1366 D SettingsProvider: name = wifi_on
,08-04 10:46:11.467   746  1150 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,08-04 10:46:11.477  1294  1294 I wpa_supplicant: reset timer : RESET_TIMER 0
08-04 10:46:11.477  1294  1294 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
08-04 10:46:11.477  7553  7621 D BluetoothAdapter: disable()
08-04 10:46:11.477  1294  1294 I wpa_supplicant: P2P: Current p2p state = IDLE
08-04 10:46:11.477   746   762 D SettingsProvider: name = bluetooth_on
,08-04 10:46:11.477   746  1150 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 10:46:11.477  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 10:46:11.477  3212  3280 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
08-04 10:46:11.477  3212  3280 D BluetoothAdapterProperties: Setting state to 13
08-04 10:46:11.477  3212  3280 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-04 10:46:11.477  3212  3280 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-04 10:46:11.477  3212  3280 D BluetoothAdapterService: updateAdapterState state is 13
08-04 10:46:11.477   746  1145 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:11.477   746  1145 D ActivityManager: caller:android.app.ApplicationThreadProxy@74f694c, r.packageName :com.android.bluetooth
08-04 10:46:11.477   746  1444 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:11.477  3212  3212 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
08-04 10:46:11.477  3212  3280 D BluetoothAdapterService: Autoconnection is available 
08-04 10:46:11.477  3212  3280 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-04 10:46:11.477  3212  3280 D BluetoothAdapterService: terminating service from this receiver
,08-04 10:46:11.477  3212  3212 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3c792405, channel: 19, state: LISTENING
08-04 10:46:11.487  3212  3212 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3c792405, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2949ec11, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@96c0c5amSocket: android.net.LocalSocket@1660de8b impl:android.net.LocalSocketImpl@358f4b68 fd:FileDescriptor[72]
,08-04 10:46:11.487  3212  3212 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1660de8b impl:android.net.LocalSocketImpl@358f4b68 fd:FileDescriptor[72]
08-04 10:46:11.487  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:11.487  7553  7621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:46:11.487  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:11.487  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:11.487  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:11.487  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:46:11.487  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:11.487  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:46:11.487  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 10:46:11.487  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:11.487  7553  7621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:11.487  7553  7621 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:46:11.487  1294  1294 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-04 10:46:11.487   746  1455 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:11.487  3212  3280 D BluetoothAdapterProperties: onBluetoothDisable()
,08-04 10:46:11.487   746  1444 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-04 10:46:11.487  3212  3280 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-04 10:46:11.487   746   746 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:11.487   746   746 I InputMethodManagerService: [BT Setting State] State =13
,08-04 10:46:11.487  1190  1190 D BluetoothTile:  onBluetoothStateChange:
08-04 10:46:11.487  3212  3407 D bt_vendor: op for 7
08-04 10:46:11.487  3212  3407 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:11.487  3212  3407 D bt_vendor: op for 7
08-04 10:46:11.487  3212  3407 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:11.487  3212  3407 D bt_vendor: op for 7
,08-04 10:46:11.487  3212  3407 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:11.487  1190  1190 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-04 10:46:11.487  1190  1190 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-04 10:46:11.497  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:11.497   746  1444 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:11.497  1190  1602 D BluetoothTile:  handleUpdatestate:false name:null
08-04 10:46:11.497  1190  1602 D BluetoothTile:  handleUpdatestate:false name:null
08-04 10:46:11.497   746  1455 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,08-04 10:46:11.497  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:11.497   746  1471 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:11.497  1190  1602 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-04 10:46:11.497   746   762 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-04 10:46:11.497  1190  1190 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,08-04 10:46:11.497  7553  7553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:11.497  1688  1688 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
08-04 10:46:11.497  1320  1320 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:11.497  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:11.497  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:11.497  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:11.497  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:11.497  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:46:11.497  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:11.497  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:46:11.497  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 10:46:11.497  1320  1320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 10:46:11.497   746   764 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-04 10:46:11.497   746   764 D ActivityManager: caller:android.app.ApplicationThreadProxy@bad2d95, r.packageName :com.google.android.gms
08-04 10:46:11.497  7553  7553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 10:46:11.497  7553  7553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:11.497  3212  3287 D BluetoothAdapterProperties: Scan Mode:20
08-04 10:46:11.497  3212  3280 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-04 10:46:11.497  3212  3280 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-04 10:46:11.507   746  1459 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:11.507  3212  3280 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-04 10:46:11.507  3212  3280 E bt-btif : cmd socket is not created
08-04 10:46:11.507  3212  5836 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-04 10:46:11.507  7553  7656 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@e203a7f, channel: -1, state: INIT
08-04 10:46:11.507  7553  7656 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@e203a7f, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@12c5ca4c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@4a27a95mSocket: android.net.LocalSocket@1ec5c7aa impl:android.net.LocalSocketImpl@3487ff9b fd:FileDescriptor[111]
08-04 10:46:11.507  7553  7656 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1ec5c7aa impl:android.net.LocalSocketImpl@3487ff9b fd:FileDescriptor[111]
08-04 10:46:11.507  7553  7656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1303)
08-04 10:46:11.507  3212  3405 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-04 10:46:11.507  3212  3405 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-04 10:46:11.507  3212  3405 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 10:46:11.507  3212  3405 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 10:46:11.507  3212  3405 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 10:46:11.507  3212  3407 D bt_vendor: op for 7
08-04 10:46:11.507  3212  3407 D bt_upio : BT_WAKE is asserted already
08-04 10:46:11.507  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:11.507   746  1718 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:11.507  3212  3407 D bt_vendor: op for 7
08-04 10:46:11.507  3212  3407 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:11.507  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:11.507   746  1696 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:11.507  3212  3407 D bt_vendor: op for 7
08-04 10:46:11.507  3212  3407 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:11.507   746  1366 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-04 10:46:11.507   746  1366 D ActivityManager: caller:android.app.ApplicationThreadProxy@d996a9b, r.packageName :com.android.settings
,08-04 10:46:11.507  3212  3407 D bt_vendor: op for 7
08-04 10:46:11.507  3212  3407 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:11.517  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:11.517  3212  3407 D bt_vendor: op for 7
08-04 10:46:11.517  3212  3407 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:11.517  3212  3407 D bt_vendor: op for 7
08-04 10:46:11.517  3212  3407 D bt_upio : BT_WAKE is asserted already
08-04 10:46:11.517  3212  3407 D bt_vendor: op for 7
08-04 10:46:11.517  3212  3407 D bt_upio : BT_WAKE is asserted already
08-04 10:46:11.517  3212  3407 D bt_vendor: op for 7
08-04 10:46:11.517  3212  3407 D bt_upio : BT_WAKE is asserted already
08-04 10:46:11.517  3212  3280 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-04 10:46:11.517   746  1150 E native  : do suspend true
08-04 10:46:11.517  3212  3407 D bt_vendor: op for 7
08-04 10:46:11.517  3212  3407 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:11.517  3212  3407 D bt_vendor: op for 7
08-04 10:46:11.517  3212  3407 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:11.517  3212  3212 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@316cfb81, channel: 5, state: LISTENING
08-04 10:46:11.517  3212  3212 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@316cfb81, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@5d9f02, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@6ce9426mSocket: android.net.LocalSocket@127cd867 impl:android.net.LocalSocketImpl@2fc1b614 fd:FileDescriptor[74]
08-04 10:46:11.517  3212  3212 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@127cd867 impl:android.net.LocalSocketImpl@2fc1b614 fd:FileDescriptor[74]
08-04 10:46:11.517  3212  3212 I BtOppRfcommListener: stopping Accept Thread
08-04 10:46:11.517  3212  3212 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@26ccebd, channel: 12, state: LISTENING
08-04 10:46:11.517  3212  3212 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@26ccebd, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39f0737c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@127fccb2mSocket: android.net.LocalSocket@14749403 impl:android.net.LocalSocketImpl@380e1f80 fd:FileDescriptor[77]
08-04 10:46:11.517  3212  3212 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@14749403 impl:android.net.LocalSocketImpl@380e1f80 fd:FileDescriptor[77]
08-04 10:46:11.517  3212  3407 D bt_vendor: op for 7
08-04 10:46:11.517  3212  3407 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:11.517  3212  5836 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-04 10:46:11.517  3212  3407 D bt_vendor: op for 7
08-04 10:46:11.517  3212  3407 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:11.517  1320  1320 D BluetoothPbap: Proxy object disconnected
,08-04 10:46:11.517  1320  1320 D PbapServerProfile: Bluetooth service disconnected
,08-04 10:46:11.527   746  1149 D WifiP2pService: InactiveState{ what=143375 }
,08-04 10:46:11.527   746  1149 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-04 10:46:11.527   305  1066 D CommandListener: Clearing all IP addresses on wlan0
08-04 10:46:11.527  1190  1190 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 10:46:11.527  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-04 10:46:11.567  1942  5289 V NativeCrypto: Read error: ssl=0x9b2cce00: I/O error during system call, Connection timed out
,08-04 10:46:11.567  1942  5289 V NativeCrypto: SSL shutdown failed: ssl=0x9b2cce00: I/O error during system call, Broken pipe
,08-04 10:46:11.567   369   369 I ServiceManager: Waiting for service AtCmdFwd...
,08-04 10:46:11.567   746  1297 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:11.567   746  1152 E ConnectivityService: updateNetworkInfo()
08-04 10:46:11.567   746  1152 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-04 10:46:11.567   746  1152 E ConnectivityService: updateNetworkInfo()
08-04 10:46:11.567   746  1152 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
08-04 10:46:11.567   746  1152 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
08-04 10:46:11.577   746  1150 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 10:46:11.577   746   746 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-04 10:46:11.587  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 10:46:11.587  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-04 10:46:11.587  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,08-04 10:46:11.587  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:11.587  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:11.587  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:11.587  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:11.587  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:11.587  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:11.587  1190  1190 D StatusBar.NetworkController: applyOpen
,08-04 10:46:11.587   746  1150 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-04 10:46:11.587  1320  1320 D DockEventReceiver: finishStartingService: stopping service
,08-04 10:46:11.587   746  1149 D WifiP2pService: InactiveState{ what=131204 }
08-04 10:46:11.587   746  1149 D WifiP2pService: P2pEnabledState{ what=131204 }
,08-04 10:46:11.587   746  1444 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:11.587  1942  5289 E GCM     : Wifi connection closed with errorCode 20
,08-04 10:46:11.587   746  1366 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:11.587   746  1149 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,08-04 10:46:11.587   746  1459 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
08-04 10:46:11.587   746  1770 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:11.587   746  1770 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:11.587   746  1770 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
,08-04 10:46:11.587   746  1770 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:11.587   746  1770 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
,08-04 10:46:11.597  1320  1320 D BluetoothNotiBroadcastReceiver: onReceive
08-04 10:46:11.597   746  1149 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-04 10:46:11.597   746  1030 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-04 10:46:11.597   746  1149 D WifiP2pService: P2pDisablingState
08-04 10:46:11.597   746  1030 D WifiDisplayAdapter: onP2pDisconnected
08-04 10:46:11.597   746  1030 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-04 10:46:11.597   746  1149 D WifiP2pService: P2pDisablingState{ what=147458 }
08-04 10:46:11.597   746  1030 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-04 10:46:11.597   746  1030 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-04 10:46:11.597   746  1030 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-04 10:46:11.597   746  1030 D WifiDisplayController: disconnect
08-04 10:46:11.597   746  1030 D WifiDisplayController: updateConnection
08-04 10:46:11.597   746  1149 D WifiP2pService: p2p socket connection lost
08-04 10:46:11.597   746  1030 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-04 10:46:11.597   746  1030 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-04 10:46:11.597   746  1149 D WifiP2pService: P2pDisabledState
08-04 10:46:11.597   746  1298 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:11.597   746  1770 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-04 10:46:11.597   746  1770 I qtaguid : Tagging socket 406 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 746, getuid(): 1000
08-04 10:46:11.597   746   746 D WifiScanningService: SCAN_AVAILABLE : 1
08-04 10:46:11.597   746   746 D RttService: SCAN_AVAILABLE : 1
08-04 10:46:11.597   746  1167 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:11.597   746   746 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-04 10:46:11.597   746  1770 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-04 10:46:11.597   746  1168 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:11.597   746  1435 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:11.597   746  1150 E native  : do suspend true
08-04 10:46:11.607   746  1426 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:11.607   746   764 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
08-04 10:46:11.607   746  1149 D WifiP2pService: P2pDisabledState{ what=143375 }
,08-04 10:46:11.607  1190  1190 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-04 10:46:11.607   746   764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:11.607   746   764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:11.607   746   764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:11.607   746   764 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:11.607   746  1459 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-04 10:46:11.607  1190  1190 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-04 10:46:11.607   746  1149 D WifiP2pService: DefaultState{ what=143375 }
,08-04 10:46:11.637   746  1152 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
08-04 10:46:11.637   746  1152 D ConnectivityService: calling update connectivity
08-04 10:46:11.637   746  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:11.637   746  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 10:46:11.637   746  1152 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-04 10:46:11.637   746  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-04 10:46:11.637   746  1028 D EntConnectivity: Not allowed due to - mEnabled false
08-04 10:46:11.637   746  1152 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:11.637   746  1770 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-04 10:46:11.637   746  1152 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
08-04 10:46:11.637   746  1770 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
08-04 10:46:11.637   746  1770 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:11.637   746  1770 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:11.637   746  1770 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-04 10:46:11.637  1190  1594 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-04 10:46:11.637  4674  7399 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-04 10:46:11.637   746  1152 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:11.637   746  1152 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-04 10:46:11.637   746  1152 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-04 10:46:11.637  1402  1402 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:11.637   746  1152 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
08-04 10:46:11.637   746  1152 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,08-04 10:46:11.647  7680  7680 E Zygote  : MountEmulatedStorage()
08-04 10:46:11.647  7680  7680 E Zygote  : v2
08-04 10:46:11.647  7680  7680 I libpersona: KNOX_SDCARD checking this for 10140
08-04 10:46:11.647  7680  7680 I libpersona: KNOX_SDCARD not a persona
,08-04 10:46:11.657   746   764 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7680 uid=10140 gids={50140, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,08-04 10:46:11.657   305  1066 D CommandListener: Clearing all IP addresses on wlan0
,08-04 10:46:11.657   746  1152 E ConnectivityService: updateNetworkInfo()
08-04 10:46:11.657   746  1152 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
08-04 10:46:11.657   746  1152 E ConnectivityService: updateNetworkInfo()
08-04 10:46:11.657   746  1152 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 10:46:11.657   746  1152 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,08-04 10:46:11.657   746  1152 E ConnectivityService: EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
08-04 10:46:11.657   746  1153 D Tethering: MasterInitialState.processMessage what=3
08-04 10:46:11.657   746   746 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-04 10:46:11.667   746  1154 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
08-04 10:46:11.667  7680  7680 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 10:46:11.667   746  1154 D SmartBondingService: getSBEnabled() enabled =false
08-04 10:46:11.667  7680  7680 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 10:46:11.667   746  1154 D SmartBondingService: getSBEnabled() enabled =false
08-04 10:46:11.667   746  1154 D SmartBondingService: getSBEnabled() enabled =false
08-04 10:46:11.667  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 10:46:11.667  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 10:46:11.667  7680  7680 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-04 10:46:11.667  1190  1190 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-04 10:46:11.667  1190  1190 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-04 10:46:11.667  1190  1190 D StatusBar.NetworkController: updateDataNetType()
08-04 10:46:11.667  1190  1190 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-04 10:46:11.667  1190  1190 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-04 10:46:11.667   746  1147 V NetworkStats: updateIfacesLocked()
08-04 10:46:11.667   746  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:11.667   746  1147 V NetworkStats: performPollLocked(flags=0x1)
08-04 10:46:11.667   746  1148 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:11.667   746  1154 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,08-04 10:46:11.667   746  1148 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:11.667   746  1148 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:11.667   746  1148 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-04 10:46:11.667   746  1148 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:11.667   746  1147 D NetworkStatsFactory: UpdateStatsForKnox
,08-04 10:46:11.667   746  1147 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:11.667  1190  1190 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-04 10:46:11.667  1190  1190 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,08-04 10:46:11.667  1190  1190 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-04 10:46:11.667  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 10:46:11.667  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-04 10:46:11.667  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:11.667  1294  1294 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-04 10:46:11.667  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:11.667  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:11.667  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:11.667  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:11.667  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:11.667  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:11.667  1190  1190 D StatusBar.NetworkController: applyOpen
,08-04 10:46:11.667   746   746 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-04 10:46:11.677  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-04 10:46:11.677   746  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-04 10:46:11.677   746  1150 D SecContentProvider2: mCursor = null
08-04 10:46:11.677   746   746 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,08-04 10:46:11.677  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 10:46:11.677  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-04 10:46:11.677  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-04 10:46:11.677  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:11.677  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:11.677  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:11.677  1190  1190 D StatusBar.NetworkController: applyOpen
,08-04 10:46:11.677  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:11.677  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:11.677  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:11.677   746  1147 V NetworkStats: performPollLocked() took 12ms
08-04 10:46:11.677   746  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:11.677  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:11.677  1190  1190 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,08-04 10:46:11.677  1190  1190 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
08-04 10:46:11.677  1190  1190 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 10:46:11.677  1190  1602 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-04 10:46:11.677  1190  1190 D HotspotTile: onReceive : 0, 0
,08-04 10:46:11.677   746  1154 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
08-04 10:46:11.677  1320  1320 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-04 10:46:11.687  7553  7553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:11.687  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:11.687  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:11.687  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:11.687  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:46:11.687  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:46:11.687  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:11.687  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:11.687  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:46:11.687   746  1718 I AudioService: getStreamVolume 3 index 0
,08-04 10:46:11.687   746  1148 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:11.687   746  1148 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:11.687  7553  7553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:11.687  7553  7553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:46:11.687  7553  7553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:11.687  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:11.687  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:11.687  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:11.687  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:46:11.687  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:46:11.687  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:11.687  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:11.687  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:46:11.687  7553  7553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:11.687  7553  7553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:46:11.697  7680  7680 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:11.697  7680  7680 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:11.707  3212  3407 D bt_vendor: op for 6
,08-04 10:46:11.707  3212  3407 D bt_vendor: op for 7
08-04 10:46:11.707  3212  3407 D bt_upio : BT_WAKE is asserted already
08-04 10:46:11.707  3212  3405 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 10:46:11.707  3212  3405 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 10:46:11.707  3212  3405 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 10:46:11.707  3212  3405 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 10:46:11.707  3212  3405 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 10:46:11.707  3212  3405 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 10:46:11.707  3212  3405 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 10:46:11.707  3212  3405 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 10:46:11.707  3212  3405 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 10:46:11.707  3212  3405 W bt-btif : ag scb idx 1 not allocated
08-04 10:46:11.707  3212  3405 W bt-btif : ag scb idx 2 not allocated
08-04 10:46:11.707  3212  3405 E bt-btif : BTA AG is already disabled, ignoring ...
08-04 10:46:11.707  3212  3408 D bt_userial: RX termination
08-04 10:46:11.707  3212  3408 W bt_userial: select_read return size <=0:-1, exiting userial_read_thread
08-04 10:46:11.707  3212  3408 D bt_userial: Leaving userial_read_thread()
08-04 10:46:11.707  3212  3287 D bt_userial: userial_close_reader Joined userial reader thread: 0
,08-04 10:46:11.707  3212  3407 D bt_vendor: op for 9
08-04 10:46:11.707  3212  3407 D bt_hwcfg: hw_epilog_process
,08-04 10:46:11.707  3212  3287 D bt_vendor: op for 4
08-04 10:46:11.707  3212  3287 I bt_userial_vendor: device fd = 65 close
,08-04 10:46:11.717  1294  1294 I wpa_supplicant: Blacklist: Clear (all) 
,08-04 10:46:11.717  3212  3287 D bt_vendor: op for 0
08-04 10:46:11.717  3212  3287 D bt_upio : upio_set_bluetooth_power(on: 0)
08-04 10:46:11.717  3212  3287 D bt_upio : is_emulator_context : 0
08-04 10:46:11.717  3212  3287 D bt_upio : is_rfkill_disabled ? [0]
,08-04 10:46:11.717  3212  3287 D bt_vendor: cleanup
,08-04 10:46:11.717  3212  3405 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-04 10:46:11.717  3212  3287 I GKI_LINUX: GKI_exit_task 0 done
08-04 10:46:11.717  3212  3287 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-04 10:46:11.717  3212  3280 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-04 10:46:11.717  3212  3280 D BtConfig.SecureMode: isSecureModeOn:false
08-04 10:46:11.717  3212  3280 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-04 10:46:11.717  3212  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-04 10:46:11.717  3212  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-04 10:46:11.717  3212  3280 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-04 10:46:11.717   746  1145 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 10:46:11.717   746  1145 D ActivityManager: caller:android.app.ApplicationThreadProxy@5af95e4, r.packageName :com.android.bluetooth
,08-04 10:46:11.717  3212  3212 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 10:46:11.717  1402  1402 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-04 10:46:11.717  3212  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-04 10:46:11.717  3212  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-04 10:46:11.717  3212  3212 D BtGatt.GattService: Received stop request...Stopping profile...
08-04 10:46:11.717  3212  3212 D BtGatt.GattService: stop()
08-04 10:46:11.717  3212  3212 D BtGatt.AdvertiseManager: advertise clients cleared
08-04 10:46:11.717  3212  3280 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-04 10:46:11.717   746  1435 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 10:46:11.717  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2839eecb
08-04 10:46:11.717   746  1435 D ActivityManager: caller:android.app.ApplicationThreadProxy@3dc67a4d, r.packageName :com.android.bluetooth
08-04 10:46:11.717  3212  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-04 10:46:11.717  3212  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-04 10:46:11.717  1402  1402 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-04 10:46:11.717  3212  3280 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-04 10:46:11.717   746  1459 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 10:46:11.717   746  1459 D ActivityManager: caller:android.app.ApplicationThreadProxy@2b53b902, r.packageName :com.android.bluetooth
08-04 10:46:11.717  3212  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-04 10:46:11.717  3212  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-04 10:46:11.717  3212  3280 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-04 10:46:11.717   746   764 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 10:46:11.717   746   764 D ActivityManager: caller:android.app.ApplicationThreadProxy@e909213, r.packageName :com.android.bluetooth
,08-04 10:46:11.727  3212  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
08-04 10:46:11.727  3212  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-04 10:46:11.727  3212  3280 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-04 10:46:11.727  1402  1402 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-04 10:46:11.727  1402  1402 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-04 10:46:11.727  7680  7680 D ResourcesManager: creating new AssetManager and set to /system/app/Maps/Maps.apk
,08-04 10:46:11.727   746   762 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:11.727   746   762 D ActivityManager: caller:android.app.ApplicationThreadProxy@dc22c50, r.packageName :com.android.bluetooth
08-04 10:46:11.727  1402  1402 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-04 10:46:11.727  3212  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-04 10:46:11.727  3212  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-04 10:46:11.727  3212  3280 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-04 10:46:11.737  1294  1294 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-04 10:46:11.737   746  1366 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:11.737   746  1366 D ActivityManager: caller:android.app.ApplicationThreadProxy@1b0d6e49, r.packageName :com.android.bluetooth
,08-04 10:46:11.737  3212  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-04 10:46:11.737  3212  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-04 10:46:11.737  3212  3280 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-04 10:46:11.737   746   764 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 10:46:11.737   746   764 D ActivityManager: caller:android.app.ApplicationThreadProxy@31c8634e, r.packageName :com.android.bluetooth
,08-04 10:46:11.737  3212  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-04 10:46:11.737  3212  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-04 10:46:11.737  3212  3280 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,08-04 10:46:11.737   746  1426 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 10:46:11.737   746  1426 D ActivityManager: caller:android.app.ApplicationThreadProxy@1ce83c6f, r.packageName :com.android.bluetooth
08-04 10:46:11.737  3212  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-04 10:46:11.737  3212  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-04 10:46:11.737  3212  3280 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-04 10:46:11.737  3212  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-04 10:46:11.737  3212  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-04 10:46:11.737  3212  3280 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-04 10:46:11.737  3212  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-04 10:46:11.737  3212  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-04 10:46:11.737  3212  3280 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-04 10:46:11.737  3212  3280 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-04 10:46:11.737  3212  3280 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-04 10:46:11.737  3212  3280 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-04 10:46:11.737  3212  3280 D BluetoothAdapterState: Stopping profile services that were post enabled
08-04 10:46:11.737  3212  3212 E BluetoothAdapterService(674885323): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-04 10:46:11.737  3212  3212 D HeadsetService: Received stop request...Stopping profile...
,08-04 10:46:11.747  1402  1402 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-04 10:46:11.747  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2839eecb
,08-04 10:46:11.747   746   746 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,08-04 10:46:11.747  1294  1294 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
08-04 10:46:11.747  1320  1320 D HeadsetProfile: Bluetooth service disconnected
08-04 10:46:11.747  1294  1294 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
,08-04 10:46:11.747  1294  1294 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=0 BSSID=F4.99.3E SSID=4E47373030
08-04 10:46:11.747  1294  1294 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-04 10:46:11.747  3212  3212 D A2dpService: Received stop request...Stopping profile...
08-04 10:46:11.747  3212  3305 D A2dpStateMachine: Exit Disconnected: -1
08-04 10:46:11.747  3212  3212 V Avrcp   : doQuit
,08-04 10:46:11.747  3212  3212 D Avrcp   : Unregistering previous receiver
08-04 10:46:11.747  1402  1402 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-04 10:46:11.747  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2839eecb
,08-04 10:46:11.747  3420  3420 D BluetoothA2dp: Proxy object disconnected
,08-04 10:46:11.747  3212  3212 D HidService: Received stop request...Stopping profile...
08-04 10:46:11.747   746   746 D BluetoothA2dp: Proxy object disconnected
08-04 10:46:11.747   746   746 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-04 10:46:11.747  3212  3212 D HidService: Stopping Bluetooth HidService
,08-04 10:46:11.747  3212  3212 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-04 10:46:11.747  3212  3212 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-04 10:46:11.747  3212  3212 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-04 10:46:11.747  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2839eecb
08-04 10:46:11.747  1320  1320 D BluetoothA2dp: Proxy object disconnected
08-04 10:46:11.747  1320  1320 D A2dpProfile: Bluetooth service disconnected
08-04 10:46:11.747  3212  3212 D HealthService: Received stop request...Stopping profile...
08-04 10:46:11.747  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2839eecb
,08-04 10:46:11.757  1320  1320 D BluetoothInputDevice: Proxy object disconnected
08-04 10:46:11.757  1320  1320 D HidProfile: Bluetooth service disconnected
,08-04 10:46:11.757  1402  1402 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-04 10:46:11.757  3212  3212 D PanService: Received stop request...Stopping profile...
08-04 10:46:11.757  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2839eecb
,08-04 10:46:11.757  1320  1320 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-04 10:46:11.757  1320  1320 D PanProfile: Bluetooth service disconnected
08-04 10:46:11.757   746   746 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-04 10:46:11.757  3212  3212 D BluetoothMapService: Received stop request...Stopping profile...
,08-04 10:46:11.757  1402  1402 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-04 10:46:11.757  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2839eecb
,08-04 10:46:11.757  1402  1402 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-04 10:46:11.767  1320  1320 D BluetoothMap: Proxy object disconnected
08-04 10:46:11.767  1320  1320 D MapProfile: Bluetooth service disconnected
08-04 10:46:11.767  3212  3212 D SapService: Received stop request...Stopping profile...
08-04 10:46:11.767  1402  1402 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-04 10:46:11.767  3212  3212 D SapService: Stopping Bluetooth SapService
08-04 10:46:11.767  3212  3212 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2839eecb
,08-04 10:46:11.767  3212  3212 E BluetoothAdapterService(674885323): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-04 10:46:11.767  3212  3212 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-04 10:46:11.767  3212  3212 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,08-04 10:46:11.767  1320  1320 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-04 10:46:11.767  1320  1320 D SapProfile: Bluetooth service disconnected
,08-04 10:46:11.767  3212  3212 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-04 10:46:11.767  3212  3212 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-04 10:46:11.767  3212  3212 E BluetoothAdapterService(674885323): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-04 10:46:11.767  3212  3212 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-04 10:46:11.767  3212  3212 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-04 10:46:11.767  3212  3212 D BluetoothA2dp: Proxy object disconnected
08-04 10:46:11.767  3212  3212 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,08-04 10:46:11.767  3212  3306 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-04 10:46:11.767  3212  3212 I GKI_LINUX: GKI_exit_task 2 done
08-04 10:46:11.767  3212  3212 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-04 10:46:11.767  3212  3212 V Avrcp   : cleanup
08-04 10:46:11.767  3212  3212 E BluetoothAdapterService(674885323): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
,08-04 10:46:11.767  3212  3212 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-04 10:46:11.767  3212  3212 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-04 10:46:11.767  3212  3212 E BluetoothAdapterService(674885323): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-04 10:46:11.767  3212  3212 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-04 10:46:11.767  3212  3212 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-04 10:46:11.767  3212  3212 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-04 10:46:11.767  3212  3212 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,08-04 10:46:11.767  3212  3212 E BluetoothAdapterService(674885323): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-04 10:46:11.767  3212  3212 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-04 10:46:11.767  3212  3212 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-04 10:46:11.767  3212  3212 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-04 10:46:11.767  3212  3212 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-04 10:46:11.767  3212  3212 E BluetoothAdapterService(674885323): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
,08-04 10:46:11.767  3212  3212 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-04 10:46:11.767  3212  3212 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
08-04 10:46:11.767  3212  3212 E BluetoothAdapterService(674885323): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,08-04 10:46:11.767  3212  3280 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-04 10:46:11.767  3212  3280 D BluetoothAdapterProperties: Setting state to 10
08-04 10:46:11.767  1402  1402 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
08-04 10:46:11.767  3212  3280 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-04 10:46:11.777  3212  3212 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-04 10:46:11.777  3212  3212 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-04 10:46:11.777  3212  3280 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-04 10:46:11.777  3212  3280 D BluetoothAdapterService: updateAdapterState state is 10
,08-04 10:46:11.777   746  1028 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-04 10:46:11.777  3212  3280 D BluetoothAdapterService: Autoconnection is available 
08-04 10:46:11.777  1320  1365 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 10:46:11.777  3212  3280 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-04 10:46:11.777  3212  3280 I BluetoothAdapterState: Entering OffState
,08-04 10:46:11.777  1402  1402 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-04 10:46:11.777  1320  1386 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-04 10:46:11.777  3212  3221 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-04 10:46:11.777  1320  1365 D Bluetoothsap: onBluetoothStateChange: up=false
08-04 10:46:11.777  1320  1365 D Bluetoothsap: Unbinding service...
,08-04 10:46:11.777  1402  1402 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,08-04 10:46:11.777  1320  1386 D BluetoothMap: onBluetoothStateChange: up=false
,08-04 10:46:11.777  1320  1365 D BluetoothPbap: onBluetoothStateChange: up=false
,08-04 10:46:11.777  3420  3429 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-04 10:46:11.787   746  1028 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 12 receivers.
,08-04 10:46:11.787   746  1028 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-04 10:46:11.787  1190  1190 D BluetoothAdapter: 616952615: getState() :  mService = null. Returning STATE_OFF
08-04 10:46:11.787  1190  1190 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-04 10:46:11.787  1190  1190 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-04 10:46:11.787  1190  1190 D BluetoothAdapter: 616952615: getState() :  mService = null. Returning STATE_OFF
08-04 10:46:11.787  1190  1190 D BluetoothAdapter: 616952615: getState() :  mService = null. Returning STATE_OFF
08-04 10:46:11.797  1190  1602 D BluetoothAdapter: 616952615: getState() :  mService = null. Returning STATE_OFF
08-04 10:46:11.797  1190  1602 D BluetoothAdapter: 616952615: getState() :  mService = null. Returning STATE_OFF
08-04 10:46:11.797  1190  1602 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-04 10:46:11.797   746   746 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:11.797   746   746 I InputMethodManagerService: [BT Setting State] State =10
08-04 10:46:11.797   746   746 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
08-04 10:46:11.797  1942  2393 D BluetoothAdapter: 955132242: getState() :  mService = null. Returning STATE_OFF
08-04 10:46:11.797  1942  2393 D BluetoothAdapter: 955132242: getState() :  mService = null. Returning STATE_OFF
08-04 10:46:11.797  1688  1688 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-04 10:46:11.797  1320  1320 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:11.797   746  1444 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
08-04 10:46:11.797   746   762 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-04 10:46:11.797   746   762 D ActivityManager: caller:android.app.ApplicationThreadProxy@3e25bd7c, r.packageName :com.google.android.gms
08-04 10:46:11.797   746  1297 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-04 10:46:11.797  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:11.797  1190  1190 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,08-04 10:46:11.797  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:11.797  3212  3287 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-04 10:46:11.797  3212  3212 I GKI_LINUX: GKI_exit_task 1 done
08-04 10:46:11.797  3212  3212 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,08-04 10:46:11.797  3212  3212 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-04 10:46:11.797  3212  3212 I art     : System.exit called, status: 0
08-04 10:46:11.797  3212  3212 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-04 10:46:11.827  1294  1294 I wpa_supplicant: Blacklist: Clear (all) 
,08-04 10:46:11.847   746   764 I ActivityManager: Process com.android.bluetooth (pid 3212)(adj 0) has died(153,1601)
,08-04 10:46:11.927  7553  7553 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-04 10:46:11.947   746  1471 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,08-04 10:46:11.947  1942  1942 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-04 10:46:11.957  1942  1942 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-04 10:46:11.977  1294  1294 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-04 10:46:11.977   746  1153 D Tethering: InitialState.processMessage what=4
,08-04 10:46:11.977   746  1153 E Tethering: No numeric data
,08-04 10:46:11.977   746  1153 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-04 10:46:11.977   746  1147 V NetworkStats: performPollLocked(flags=0x1)
,08-04 10:46:11.977  1190  1190 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-04 10:46:11.977  1190  1190 D HotspotTile: updateTetherState():false, false
08-04 10:46:11.977   746  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 10:46:11.977   746  1147 D NetworkStatsFactory: UpdateStatsForKnox
,08-04 10:46:11.977   746  1147 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:11.977   746  1147 V NetworkStats: performPollLocked() took 4ms
08-04 10:46:11.977   746  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 10:46:11.987   746  1148 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:11.987   746  1148 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 10:46:11.987  7680  7680 D StrictMode: StrictMode policy violation; ~duration=176 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-04 10:46:11.987  7680  7680 D StrictMode: StrictMode policy violation; ~duration=166 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.g,mm.base.app.a.a(PG:1211)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-04 10:46:11.987  7680  7680 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.io.File.exists(File.java:363)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1319)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityTh,read.main(ActivityThread.java:5938)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-04 10:46:11.987  7680  7680 D StrictMode: StrictMode policy violation; ~duration=123 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-04 10:46:11.987  7680  7680 D StrictMode: StrictMode policy violation; ~duration=122 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-04 10:46:11.987  7680  7680 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.r.e.b(PG:170)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-04 10:46:11.987  7680  7680 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.r.k.c(PG:1187)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.r.k.b(PG:14147)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.r.k.c(PG:583)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.r.v.a(PG:1206)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.r.y.a(PG:2233)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.r.e.b(PG:170)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.r.e.b(PG:13188)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-04 10:46:11.987  7680  7680 D StrictMode: StrictMode policy violation; ~duration=93 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.io.File.doAccess(File.java:283)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.io.File.exists(File.java:363)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1485)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 10:46:11.987  7680  7680 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-04 10:46:11.997   746  1471 I ActivityManager: Killing 6685:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 15): emptyCount ##41
08-04 10:46:11.997  1942  1942 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
08-04 10:46:12.007  1942  1942 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
08-04 10:46:12.007   746  1718 D ActivityManager: startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
08-04 10:46:12.007   746  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:12.007   746  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:12.007   746  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:12.007   746  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:12.047  7680  7719 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
08-04 10:46:12.047  7727  7727 E Zygote  : MountEmulatedStorage()
08-04 10:46:12.047  7727  7727 E Zygote  : v2
08-04 10:46:12.047  7727  7727 I libpersona: KNOX_SDCARD checking this for 10038
08-04 10:46:12.047  7727  7727 I libpersona: KNOX_SDCARD not a persona
08-04 10:46:12.047   746  1718 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7727 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
08-04 10:46:12.067  7727  7727 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 10:46:12.067  7727  7727 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 10:46:12.067  7727  7727 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-04 10:46:12.077   746  1150 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-04 10:46:12.077   746  1150 D WifiNative-HAL: callSECApiBoolean - ID [21]
,08-04 10:46:12.077   746   746 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,08-04 10:46:12.087  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 10:46:12.087  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-04 10:46:12.087  1190  1190 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 10:46:12.087  1190  1190 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-04 10:46:12.087  1190  1190 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 10:46:12.087  1942  2393 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 10:46:12.087  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:12.087  1190  1602 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
08-04 10:46:12.087  1190  1190 D HotspotTile: onReceive : 1, 0
,08-04 10:46:12.087  1320  1320 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-04 10:46:12.087  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:12.087  7727  7727 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:12.087  7727  7727 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:12.157   746  1152 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:46:12.167   746   902 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:46:12.167   746   902 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:12.167  1574  1574 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
08-04 10:46:12.167   746  1696 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:12.167  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:12.167   746  1298 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:12.167   746   746 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
08-04 10:46:12.167   746   746 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:12.167   746   746 I ApplicationPolicy: updateDataUsageMap
,08-04 10:46:12.177  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:12.187   746  1366 I art     : Explicit concurrent mark sweep GC freed 60708(3MB) AllocSpace objects, 23(416KB) LOS objects, 29% free, 37MB/53MB, paused 1.280ms total 107.670ms
,08-04 10:46:12.187   746  1154 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,08-04 10:46:12.187   746  1154 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
08-04 10:46:12.187   746  1154 D SmartBondingService: getSBEnabled() enabled =false
08-04 10:46:12.187   746  1154 D SmartBondingService: getSBEnabled() enabled =false
08-04 10:46:12.187   746  1154 D SmartBondingService: getSBEnabled() enabled =false
,08-04 10:46:12.187   746  1154 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,08-04 10:46:12.207  7727  7727 D ResourcesManager: creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,08-04 10:46:12.207  7727  7727 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,08-04 10:46:12.247  1942  2006 I art     : Explicit concurrent mark sweep GC freed 101583(5MB) AllocSpace objects, 58(2MB) LOS objects, 39% free, 23MB/39MB, paused 653us total 48.773ms
,08-04 10:46:12.287   746  1150 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-04 10:46:12.327  7727  7727 I VlingoApplication: VlingoApplication appVersion ='11.2.2.0.37791', ro.csc.sales_code=XEO
,08-04 10:46:12.397  7727  7727 D BluetoothAdapter: 554053301: getState() :  mService = null. Returning STATE_OFF
,08-04 10:46:12.397  7727  7727 D BluetoothAdapter: 554053301: getState() :  mService = null. Returning STATE_OFF
08-04 10:46:12.397  7727  7727 D BluetoothAdapter: 554053301: getState() :  mService = null. Returning STATE_OFF
,08-04 10:46:12.397  7727  7727 D BluetoothAdapter: 554053301: getState() :  mService = null. Returning STATE_OFF
08-04 10:46:12.397  7727  7727 D BluetoothAdapter: 554053301: getState() :  mService = null. Returning STATE_OFF
08-04 10:46:12.397  7727  7727 D BluetoothAdapter: 554053301: getState() :  mService = null. Returning STATE_OFF
,08-04 10:46:12.437  7727  7727 E BluetoothHeadset: BTStateChangeCB is registed
,08-04 10:46:12.437   746  1435 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-04 10:46:12.437  7727  7727 E BluetoothHeadset: BluetoothHeadset service is binded
,08-04 10:46:12.437   746  1461 I ActivityManager: Killing 6736:com.google.android.gms:car/u0a15 (adj 15): emptyCount ##41
,08-04 10:46:12.447  1320  1320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-04 10:46:12.447  1320  1320 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-04 10:46:12.447   746  1461 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:12.447  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-04 10:46:12.447   746  1718 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-04 10:46:12.447  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-04 10:46:12.447  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-04 10:46:12.447  1320  1320 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-04 10:46:12.447  1320  3147 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-04 10:46:12.457   746   762 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:12.457  7187  7187 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-04 10:46:12.457   746  1435 D SettingsProvider: name = driving_mode_on
08-04 10:46:12.457   746  1435 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:12.457   746  1435 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:12.457   746  1435 D SettingsProvider: selectionArgs: false
08-04 10:46:12.457   746  1435 D SettingsProvider: selectionArgs: 10038
08-04 10:46:12.457   746  1435 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:12.457   746  1435 D SettingsProvider: ret = -1
,08-04 10:46:12.457  7727  7727 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,08-04 10:46:12.467  1320  1320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-04 10:46:12.467  1320  1320 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-04 10:46:12.467   746  1145 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:12.467  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-04 10:46:12.467   746  1718 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-04 10:46:12.467  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-04 10:46:12.467  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-04 10:46:12.467  1320  1320 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-04 10:46:12.467  1320  3147 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-04 10:46:12.477  7318  7318 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-04 10:46:12.487   746   762 D ActivityManager: startProcessLocked calleePkgName: com.samsung.shareshot, hostingType: broadcast
,08-04 10:46:12.487   746   762 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:12.487   746   762 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:12.487   746   762 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:12.487   746   762 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:12.527  7754  7754 E Zygote  : MountEmulatedStorage()
08-04 10:46:12.527  7754  7754 E Zygote  : v2
08-04 10:46:12.527  7754  7754 I libpersona: KNOX_SDCARD checking this for 10192
08-04 10:46:12.527  7754  7754 I libpersona: KNOX_SDCARD not a persona
,08-04 10:46:12.527   746   762 I ActivityManager: Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=7754 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-04 10:46:12.537  7754  7754 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 10:46:12.537  7754  7754 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 10:46:12.537  7754  7754 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 10:46:12.557  7754  7754 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:12.557  7754  7754 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:12.567  7754  7754 D ResourcesManager: creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,08-04 10:46:12.567   369   369 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-04 10:46:12.587  7754  7754 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-04 10:46:12.587  7754  7754 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,08-04 10:46:12.587  7754  7754 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,08-04 10:46:12.597  7754  7754 D WifiDirectBR: stopServiceTest : false
,08-04 10:46:12.597  7754  7754 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,08-04 10:46:12.597   746  1298 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,08-04 10:46:12.597   746  1298 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:12.597   746  1298 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:12.597   746  1298 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:12.597   746  1298 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:12.637  7770  7770 E Zygote  : MountEmulatedStorage()
,08-04 10:46:12.637  7770  7770 E Zygote  : v2
08-04 10:46:12.637  7770  7770 I libpersona: KNOX_SDCARD checking this for 10131
08-04 10:46:12.637  7770  7770 I libpersona: KNOX_SDCARD not a persona
,08-04 10:46:12.637   746  1298 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7770 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-04 10:46:12.647   746  1298 I ActivityManager: Killing 6896:com.google.android.partnersetup/u0a19 (adj 15): emptyCount ##41
,08-04 10:46:12.647  7770  7770 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 10:46:12.647  7770  7770 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 10:46:12.647  7770  7770 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-04 10:46:12.677  7770  7770 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:12.677  7770  7770 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:12.687  7770  7770 D ResourcesManager: creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,08-04 10:46:12.687  7770  7770 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-04 10:46:12.847  7770  7793 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-04 10:46:12.847  7770  7793 I Babel   : MmsConfig.loadMmsSettings
08-04 10:46:12.857  7770  7793 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
08-04 10:46:12.857  7770  7793 I Babel   : MmsConfig.loadFromDatabase
,08-04 10:46:12.857  7770  7770 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,08-04 10:46:12.867  7770  7793 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-04 10:46:12.867  7770  7793 I Babel   : MmsConfig.loadFromResources
,08-04 10:46:12.867  7770  7793 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,08-04 10:46:12.867  7770  7793 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
,08-04 10:46:12.877   746  1459 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,08-04 10:46:12.877  7770  7770 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 10:46:12.907  7770  7770 I Babel_StickerModule: App launched.
,08-04 10:46:12.907  1320  1320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-04 10:46:12.907  1320  1320 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-04 10:46:12.917   746   764 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:12.917  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-04 10:46:12.917   746  1461 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-04 10:46:12.917  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-04 10:46:12.917  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-04 10:46:12.917  1320  1320 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-04 10:46:12.917  1320  3147 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-04 10:46:12.917   746  1297 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:12.917  7187  7187 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-04 10:46:12.927   325   669 W QCamera2Factory: getCameraInfo: E, camera_id = 0
,08-04 10:46:12.927   325   669 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
08-04 10:46:12.927   325   669 W QCamera2Factory: getCameraInfo: X
,08-04 10:46:12.927  7187  7187 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-04 10:46:12.927   325   747 W QCamera2Factory: getCameraInfo: E, camera_id = 1
08-04 10:46:12.927   325   747 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
08-04 10:46:12.927   325   747 W QCamera2HWI: __dbg: info->orientation : 270 rc = 0
08-04 10:46:12.927   325   747 W QCamera2Factory: getCameraInfo: X
,08-04 10:46:12.937   746  1459 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:12.937  7624  7624 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-04 10:46:12.937  7624  7624 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,08-04 10:46:12.937  7624  7624 D SecurityLogAgent: StateMachine : Current State = 1
,08-04 10:46:12.947  7770  7770 W AudioCapabilities: Unsupported mime audio/evrc
,08-04 10:46:12.947  7624  7624 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-04 10:46:12.947  7770  7770 W AudioCapabilities: Unsupported mime audio/qcelp
,08-04 10:46:12.947  7770  7770 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-04 10:46:12.957  1320  1320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 10:46:12.957   746  1145 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-04 10:46:12.957   746  1145 D ActivityManager: caller:android.app.ApplicationThreadProxy@1e634a99, r.packageName :com.android.settings
,08-04 10:46:12.957  1320  1320 D DockEventReceiver: finishStartingService: stopping service
,08-04 10:46:12.957  7770  7770 W AudioCapabilities: Unsupported mime audio/mpeg-L1
08-04 10:46:12.957  1320  1320 D BluetoothNotiBroadcastReceiver: onReceive
,08-04 10:46:12.957  7770  7770 W AudioCapabilities: Unsupported mime audio/mpeg-L2
08-04 10:46:12.957   746  1471 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
08-04 10:46:12.957   746  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:12.957   746  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:12.957   746  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:12.957   746  1471 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:12.967  7770  7770 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,08-04 10:46:12.967  7770  7770 W AudioCapabilities: Unsupported mime audio/x-ima
,08-04 10:46:12.967  7770  7770 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-04 10:46:12.967  7770  7770 W AudioCapabilities: Unsupported mime audio/qcelp
,08-04 10:46:12.967  7770  7770 W AudioCapabilities: Unsupported mime audio/evrc
,08-04 10:46:12.967  7770  7770 W VideoCapabilities: Unsupported mime video/wvc1
,08-04 10:46:12.977  7770  7770 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-04 10:46:12.977  7770  7770 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,08-04 10:46:12.977  7770  7770 W VideoCapabilities: Unsupported mime video/wvc1
,08-04 10:46:12.977  7770  7770 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-04 10:46:12.987  7770  7770 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,08-04 10:46:12.997  7770  7770 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,08-04 10:46:12.997  7770  7770 W VideoCapabilities: Unsupported mime video/mp43
,08-04 10:46:12.997  7799  7799 E Zygote  : MountEmulatedStorage()
,08-04 10:46:12.997  7799  7799 E Zygote  : v2
08-04 10:46:12.997  7799  7799 I libpersona: KNOX_SDCARD checking this for 1002
08-04 10:46:12.997  7799  7799 I libpersona: KNOX_SDCARD not a persona
,08-04 10:46:13.007   746  1471 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7799 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-04 10:46:13.037  7799  7799 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 10:46:13.037  7799  7799 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 10:46:13.037  7770  7770 W VideoCapabilities: Unsupported mime video/sorenson
,08-04 10:46:13.037  7799  7799 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 10:46:13.037  7770  7770 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-04 10:46:13.057  7799  7799 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:13.057  7799  7799 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:13.077  7770  7770 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-04 10:46:13.077  7799  7799 D ResourcesManager: creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,08-04 10:46:13.077  7799  7799 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-04 10:46:13.077  7799  7799 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-04 10:46:13.097   746  1298 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,08-04 10:46:13.097  7799  7799 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-04 10:46:13.107   746  1459 I ActivityManager: Killing 6914:com.samsung.groupcast/u0a20 (adj 15): emptyCount ##41
,08-04 10:46:13.127  7799  7799 D BtSettings.ProfileConfig: Adding GattService
,08-04 10:46:13.127  7799  7799 D BtSettings.ProfileConfig: Adding HeadsetService
08-04 10:46:13.127  7799  7799 D BtSettings.ProfileConfig: Adding A2dpService
,08-04 10:46:13.127  7799  7799 D BtSettings.ProfileConfig: Adding HidService
08-04 10:46:13.127  7799  7799 D BtSettings.ProfileConfig: Adding HealthService
08-04 10:46:13.127  7799  7799 D BtSettings.ProfileConfig: Adding PanService
08-04 10:46:13.127  7799  7799 D BtSettings.ProfileConfig: Adding BluetoothMapService
,08-04 10:46:13.127  7799  7799 D BtSettings.ProfileConfig: Adding SapService
08-04 10:46:13.127  7799  7799 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-04 10:46:13.127  7799  7799 D BtSettings.ProfileConfig: Adding A2dpSinkService
,08-04 10:46:13.137  7799  7799 D BtSettings.ProfileConfig: Adding SapClientService
08-04 10:46:13.137  7799  7799 D BtSettings.ProfileConfig: Adding HidDevService
,08-04 10:46:13.137  7799  7799 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-04 10:46:13.137   746  1718 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
08-04 10:46:13.137   746  1718 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:13.137   746  1718 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:13.137   746  1718 D SettingsProvider: selectionArgs: false
08-04 10:46:13.137   746  1718 D SettingsProvider: selectionArgs: 1002
08-04 10:46:13.137   746  1718 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:13.137   746  1718 D SettingsProvider: ret = -1
,08-04 10:46:13.137   746  1444 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-04 10:46:13.137   746  1444 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:13.137   746  1444 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:13.137   746  1444 D SettingsProvider: selectionArgs: false
,08-04 10:46:13.137   746  1444 D SettingsProvider: selectionArgs: 1002
08-04 10:46:13.137   746  1444 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:13.137   746  1444 D SettingsProvider: ret = -1
,08-04 10:46:13.147   746  1455 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-04 10:46:13.147   746  1455 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:13.147   746  1455 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:13.147   746  1455 D SettingsProvider: selectionArgs: false
08-04 10:46:13.147   746  1455 D SettingsProvider: selectionArgs: 1002
08-04 10:46:13.147   746  1455 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:13.147   746  1455 D SettingsProvider: ret = -1
,08-04 10:46:13.147   746   762 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-04 10:46:13.147   746   762 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:13.147   746   762 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:13.147   746   762 D SettingsProvider: selectionArgs: false
08-04 10:46:13.147   746   762 D SettingsProvider: selectionArgs: 1002
08-04 10:46:13.147   746   762 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:13.147   746   762 D SettingsProvider: ret = -1
,08-04 10:46:13.147   746  1471 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-04 10:46:13.147   746  1471 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:13.147   746  1471 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:13.147   746  1471 D SettingsProvider: selectionArgs: false
08-04 10:46:13.147   746  1471 D SettingsProvider: selectionArgs: 1002
08-04 10:46:13.147   746  1471 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:13.147   746  1471 D SettingsProvider: ret = -1
08-04 10:46:13.147   746  1401 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-04 10:46:13.147   746  1401 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,08-04 10:46:13.147   746  1401 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:13.147   746  1401 D SettingsProvider: selectionArgs: false
08-04 10:46:13.147   746  1401 D SettingsProvider: selectionArgs: 1002
08-04 10:46:13.147   746  1401 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:13.147   746  1401 D SettingsProvider: ret = -1
,08-04 10:46:13.147   746  1298 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-04 10:46:13.147   746  1298 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:13.147   746  1298 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:13.147   746  1298 D SettingsProvider: selectionArgs: false
,08-04 10:46:13.147   746  1298 D SettingsProvider: selectionArgs: 1002
08-04 10:46:13.147   746  1298 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:13.147   746  1298 D SettingsProvider: ret = -1
,08-04 10:46:13.147   746   764 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-04 10:46:13.147   746   764 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:13.147   746   764 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:13.147   746   764 D SettingsProvider: selectionArgs: false
08-04 10:46:13.147   746   764 D SettingsProvider: selectionArgs: 1002
08-04 10:46:13.147   746   764 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:13.147   746   764 D SettingsProvider: ret = -1
,08-04 10:46:13.147   746  1459 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-04 10:46:13.147   746  1459 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:13.147   746  1459 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:13.147   746  1459 D SettingsProvider: selectionArgs: false
08-04 10:46:13.147   746  1459 D SettingsProvider: selectionArgs: 1002
08-04 10:46:13.147   746  1459 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:13.147   746  1459 D SettingsProvider: ret = -1
08-04 10:46:13.147   746  1435 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-04 10:46:13.147   746  1435 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:13.147   746  1435 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:13.147   746  1435 D SettingsProvider: selectionArgs: false
08-04 10:46:13.147   746  1435 D SettingsProvider: selectionArgs: 1002
08-04 10:46:13.147   746  1435 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:13.147   746  1435 D SettingsProvider: ret = -1
,08-04 10:46:13.147   746  1696 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-04 10:46:13.147   746  1696 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:13.147   746  1696 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:13.147   746  1696 D SettingsProvider: selectionArgs: false
08-04 10:46:13.147   746  1696 D SettingsProvider: selectionArgs: 1002
08-04 10:46:13.147   746  1696 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:13.147   746  1696 D SettingsProvider: ret = -1
,08-04 10:46:13.147   746  1426 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-04 10:46:13.147   746  1426 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:13.147   746  1426 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:13.147   746  1426 D SettingsProvider: selectionArgs: false
08-04 10:46:13.147   746  1426 D SettingsProvider: selectionArgs: 1002
08-04 10:46:13.147   746  1426 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:13.147   746  1426 D SettingsProvider: ret = -1
,08-04 10:46:13.157   746  1145 I ActivityManager: Killing 6071:com.sec.android.service.health/u0a21 (adj 15): emptyCount ##41
,08-04 10:46:13.157  1942  1942 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-04 10:46:13.157   746  1455 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-04 10:46:13.157   746  1455 D ActivityManager: caller:android.app.ApplicationThreadProxy@1a94f755, r.packageName :com.google.android.gms
,08-04 10:46:13.167  1942  7816 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-04 10:46:13.167  1942  1942 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-04 10:46:13.187  7187  7187 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-04 10:46:13.187   746  1471 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:13.187  7624  7624 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-04 10:46:13.187  7624  7624 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-04 10:46:13.187  7624  7624 D SecurityLogAgent: StateMachine : Current State = 1
08-04 10:46:13.187  7624  7624 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-04 10:46:13.187   746   762 D ActivityManager: caller:android.app.ApplicationThreadProxy@1c2e6e36, r.packageName :com.google.android.gms
,08-04 10:46:13.197  6932  6932 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-04 10:46:13.197  6932  6932 I PCWCLIENTTRACE_PushUtil: sales region : global
08-04 10:46:13.197  6932  6932 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-04 10:46:13.197  6932  6932 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:46:13.197  1942  7816 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
08-04 10:46:13.197  6932  6932 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,08-04 10:46:13.207   746  1461 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,08-04 10:46:13.207   746  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:13.207   746  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:13.207   746  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:13.207   746  1461 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:13.257   310   310 E SMD     : DCD ON
,08-04 10:46:13.297  7823  7823 E Zygote  : MountEmulatedStorage()
08-04 10:46:13.297  7823  7823 E Zygote  : v2
08-04 10:46:13.297  7823  7823 I libpersona: KNOX_SDCARD checking this for 10144
08-04 10:46:13.297  7823  7823 I libpersona: KNOX_SDCARD not a persona
,08-04 10:46:13.297   746  1461 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7823 uid=10144 gids={50144, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-04 10:46:13.307  7823  7823 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 10:46:13.307  7823  7823 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 10:46:13.307  7823  7823 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-04 10:46:13.327  7823  7823 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:13.327  7823  7823 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:13.337  7823  7823 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,08-04 10:46:13.427  7823  7823 I MusicStore: Database version: 108
,08-04 10:46:13.437   746  1461 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-04 10:46:13.487  7823  7823 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,08-04 10:46:13.497  7823  7823 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-04 10:46:13.497  7823  7823 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-04 10:46:13.527  7823  7823 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,08-04 10:46:13.567  7823  7823 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-04 10:46:13.567  7823  7823 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@ef40a6f: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,08-04 10:46:13.567  7823  7823 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
08-04 10:46:13.567  7823  7823 D AndroidMusic: GMSCore installation verified
,08-04 10:46:13.577   746  1696 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-04 10:46:13.587  7823  7823 I ConfigStore: Config Database version: 1
,08-04 10:46:13.627   266   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-04 10:46:13.627   266   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-04 10:46:13.627  7823  7823 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-04 10:46:13.627   266   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-04 10:46:13.627   266   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-04 10:46:13.627  7823  7823 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-04 10:46:13.627   266   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
08-04 10:46:13.627   266   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-04 10:46:13.627  7823  7823 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,08-04 10:46:13.637   746  1435 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-04 10:46:13.637   746  1435 D ActivityManager: caller:android.app.ApplicationThreadProxy@fbf3341, r.packageName :com.google.android.music
,08-04 10:46:13.647   746  1455 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-04 10:46:13.657   746  1297 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-04 10:46:13.657   746   764 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-04 10:46:13.667   746  1718 I AudioService: getStreamVolume 3 index 0
,08-04 10:46:13.667  7823  7823 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,08-04 10:46:13.677  7823  7823 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,08-04 10:46:13.687   746  1455 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-04 10:46:13.697   746   764 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-04 10:46:13.697   746  1459 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-04 10:46:13.697   746  1298 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-04 10:46:13.707   746   762 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,08-04 10:46:13.707   746   762 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:13.707   746   762 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:13.707   746   762 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:13.707   746   762 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:13.747  7857  7857 E Zygote  : MountEmulatedStorage()
,08-04 10:46:13.747  7857  7857 E Zygote  : v2
,08-04 10:46:13.747  7857  7857 I libpersona: KNOX_SDCARD checking this for 10004
08-04 10:46:13.747  7857  7857 I libpersona: KNOX_SDCARD not a persona
,08-04 10:46:13.747   746   762 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7857 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-04 10:46:13.757  7857  7857 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 10:46:13.757  7857  7857 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 10:46:13.757  7857  7857 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 10:46:13.787  7857  7857 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:13.787  7857  7857 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:13.787   746  1401 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,08-04 10:46:13.797  7823  7823 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,08-04 10:46:13.807   746  1455 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-04 10:46:13.807  7857  7857 D ResourcesManager: creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,08-04 10:46:13.847   746  1435 I ActivityManager: Killing 5060:com.sec.spp.push/u0a43 (adj 15): emptyCount ##41
,08-04 10:46:13.847   746  1444 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,08-04 10:46:13.847   746  1444 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:13.847   746  1444 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:13.857   746  1444 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:13.857   746  1444 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:13.887  7884  7884 E Zygote  : MountEmulatedStorage()
,08-04 10:46:13.887  7884  7884 E Zygote  : v2
08-04 10:46:13.887  7884  7884 I libpersona: KNOX_SDCARD checking this for 1000
08-04 10:46:13.897  7884  7884 I libpersona: KNOX_SDCARD not a persona
,08-04 10:46:13.897   746  1444 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7884 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-04 10:46:13.907  7884  7884 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 10:46:13.907  7884  7884 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 10:46:13.907  7884  7884 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 10:46:13.927  7884  7884 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:13.927  7884  7884 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:13.937  7884  7884 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,08-04 10:46:13.967  7884  7884 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,08-04 10:46:13.977  7884  7884 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,08-04 10:46:14.087  7884  7884 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,08-04 10:46:14.097  7884  7884 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,08-04 10:46:14.097  7884  7884 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:46:14.097  7884  7884 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,08-04 10:46:14.157   746  1718 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,08-04 10:46:14.157   746  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:14.157   746  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:14.157   746  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:14.157   746  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:14.197  7906  7906 E Zygote  : MountEmulatedStorage()
08-04 10:46:14.197  7906  7906 E Zygote  : v2
08-04 10:46:14.197  7906  7906 I libpersona: KNOX_SDCARD checking this for 10014
08-04 10:46:14.197  7906  7906 I libpersona: KNOX_SDCARD not a persona
,08-04 10:46:14.207   746  1718 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7906 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-04 10:46:14.207  7906  7906 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,08-04 10:46:14.207  7906  7906 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 10:46:14.207  7906  7906 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-04 10:46:14.227  7906  7906 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:14.227  7906  7906 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:14.237  7906  7906 D ResourcesManager: creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,08-04 10:46:14.287   746  1401 I ActivityManager: Killing 6824:com.android.defcontainer/u0a7 (adj 15): emptyCount ##41
,08-04 10:46:14.297  7906  7906 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,08-04 10:46:14.297  7906  7906 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,08-04 10:46:14.317  7906  7906 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,08-04 10:46:14.327   746  1366 I ActivityManager: Killing 6971:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): emptyCount ##41
,08-04 10:46:14.327  2494  2494 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-04 10:46:14.327  2494  2494 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1470300374345
,08-04 10:46:14.337  2494  2494 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,08-04 10:46:14.337   746  1459 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:14.337   746   764 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:14.337  2494  2494 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,08-04 10:46:14.337  2494  2494 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,08-04 10:46:14.337   746  1366 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.pinboard, hostingType: broadcast
,08-04 10:46:14.337   746  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:14.337   746  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:14.337   746  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:14.337   746  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:14.387  7921  7921 E Zygote  : MountEmulatedStorage()
08-04 10:46:14.387  7921  7921 I libpersona: KNOX_SDCARD checking this for 10036
08-04 10:46:14.387  7921  7921 E Zygote  : v2
08-04 10:46:14.387  7921  7921 I libpersona: KNOX_SDCARD not a persona
,08-04 10:46:14.387   746  1366 I ActivityManager: Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7921 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-04 10:46:14.407   361   361 I art     : Explicit concurrent mark sweep GC freed 8732(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 330us total 14.983ms
,08-04 10:46:14.407  7921  7921 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 10:46:14.407  7921  7921 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 10:46:14.407  7921  7921 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 10:46:14.417   361   361 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 271us total 10.174ms
,08-04 10:46:14.427  7921  7921 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:14.427  7921  7921 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:14.437   361   361 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 274us total 10.921ms
,08-04 10:46:14.447  7921  7921 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,08-04 10:46:14.457  7921  7921 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-04 10:46:14.457  7921  7921 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-04 10:46:14.477  7921  7921 E Minikin : addFont failed to create font /system/fonts/SamsungSans-light.ttf
,08-04 10:46:14.487  7553  7621 I WifiManager: packageName : com.test.thalitest
,08-04 10:46:14.487   746  1455 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-04 10:46:14.487   746  1455 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-04 10:46:14.487   746  1455 D SecContentProvider2: mCursor = null
,08-04 10:46:14.487   746  1455 D WifiService: setWifiEnabled: true pid=7553, uid=10079
,08-04 10:46:14.487   746  1455 W ActivityManager: Permission Denial: getCurrentUser() from pid=7553, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-04 10:46:14.487   746  1455 W WifiService: Failed getting userId using ActivityManagerNative
08-04 10:46:14.487   746  1455 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7553, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-04 10:46:14.487   746  1455 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
08-04 10:46:14.487   746  1455 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
08-04 10:46:14.487   746  1455 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
08-04 10:46:14.487   746  1455 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-04 10:46:14.487   746  1455 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,08-04 10:46:14.487   746  1455 D SettingsProvider: name = wifi_on
,08-04 10:46:14.497   746  1150 E WifiHW  : ##################### set firmware type 0 #####################
,08-04 10:46:14.497   305  1066 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,08-04 10:46:14.497   305  1066 I WifiHW  : module is semco
08-04 10:46:14.497   305  1066 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
08-04 10:46:14.497   305  1066 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
08-04 10:46:14.497   305  1066 E WifiHW  : TEMP_FAILURE_RETRY complete
08-04 10:46:14.497   305  1066 D SoftapController: Softap fwReload - Ok
,08-04 10:46:14.497   305  1066 D CommandListener: Setting iface cfg
08-04 10:46:14.497   305  1066 D CommandListener: Trying to bring down wlan0
,08-04 10:46:14.497   305  1066 D CommandListener: Clearing all IP addresses on wlan0
,08-04 10:46:14.497   746  1150 E WifiHW  : supplicant_name : p2p_supplicant
,08-04 10:46:14.507   746  1471 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:14.517   746  1150 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-04 10:46:14.517   746   746 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,08-04 10:46:14.517  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-04 10:46:14.527  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:14.527  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-04 10:46:14.527  1190  1190 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 10:46:14.527   746  1154 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,08-04 10:46:14.527  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:14.527  1190  1190 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
,08-04 10:46:14.527  1190  1190 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 10:46:14.527  1190  1602 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-04 10:46:14.527  1190  1190 D HotspotTile: onReceive : 2, 0
,08-04 10:46:14.527  1320  1320 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-04 10:46:14.527   746  1696 I ActivityManager: Killing 6998:com.osp.app.signin/u0a50 (adj 15): emptyCount ##41
,08-04 10:46:14.537  7938  7938 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-04 10:46:14.537  7938  7938 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-04 10:46:14.537  7938  7938 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-04 10:46:14.537  7938  7938 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-04 10:46:14.537   746  1426 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
08-04 10:46:14.537   385   385 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7938
08-04 10:46:14.537   385   385 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
08-04 10:46:14.537  7938  7938 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-04 10:46:14.537  7938  7938 I wpa_supplicant: ssSupport state is = 1
08-04 10:46:14.537  7938  7938 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,08-04 10:46:14.537   746  1426 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:14.537   746  1426 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:14.537   746  1426 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:14.537   746  1426 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:14.537  7938  7938 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-04 10:46:14.537   385   385 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7938
08-04 10:46:14.537   385   385 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,08-04 10:46:14.587   746  1426 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7947 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,08-04 10:46:14.597  7947  7947 E Zygote  : MountEmulatedStorage()
08-04 10:46:14.597  7947  7947 E Zygote  : v2
08-04 10:46:14.597  7947  7947 I libpersona: KNOX_SDCARD checking this for 10042
08-04 10:46:14.597  7947  7947 I libpersona: KNOX_SDCARD not a persona
,08-04 10:46:14.617  7947  7947 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 10:46:14.617  7947  7947 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 10:46:14.617  7947  7947 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 10:46:14.637  7947  7947 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:14.637  7947  7947 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:14.647  7947  7947 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,08-04 10:46:14.667  7947  7947 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,08-04 10:46:14.667   746  1145 I ActivityManager: Killing 7019:com.android.mms/u0a55 (adj 15): emptyCount ##41
,08-04 10:46:14.677   746  1455 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-04 10:46:14.677   746  1455 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:14.677   746  1455 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:14.677   746  1455 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:14.677   746  1455 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:14.677   746  1471 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:14.677  3737  7963 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,08-04 10:46:14.687   746   764 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:14.687  3737  7963 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,08-04 10:46:14.687  3737  7963 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,08-04 10:46:14.687  3737  7963 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,08-04 10:46:14.687  3737  7963 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,08-04 10:46:14.717  7965  7965 E Zygote  : MountEmulatedStorage()
,08-04 10:46:14.717  7965  7965 E Zygote  : v2
08-04 10:46:14.717  7965  7965 I libpersona: KNOX_SDCARD checking this for 10043
08-04 10:46:14.717  7965  7965 I libpersona: KNOX_SDCARD not a persona
,08-04 10:46:14.727   746  1455 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7965 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-04 10:46:14.767  7965  7965 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 10:46:14.767   746  1297 D CountryDetector: No listener is left
08-04 10:46:14.767  7965  7965 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 10:46:14.767  7965  7965 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-04 10:46:14.787  7965  7965 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:14.787  7965  7965 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:14.797  7965  7965 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,08-04 10:46:14.827   385   385 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,08-04 10:46:14.827  7965  7965 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-04 10:46:14.827  7965  7965 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-04 10:46:14.827  7965  7965 D SPPClientService: PushLog.txt file is not deleted.
,08-04 10:46:14.827  7965  7965 D SPPClientService: PushLog.txt file is not deleted.
08-04 10:46:14.827  7965  7965 D SPPClientService: ============PushLog. stop!
,08-04 10:46:14.837  7965  7965 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,08-04 10:46:14.837   746  1366 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,08-04 10:46:14.837   746  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:14.837   746  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:14.837   746  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:14.837   746  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:14.877  7981  7981 E Zygote  : MountEmulatedStorage()
08-04 10:46:14.877  7981  7981 E Zygote  : v2
08-04 10:46:14.877  7981  7981 I libpersona: KNOX_SDCARD checking this for 10050
08-04 10:46:14.877  7981  7981 I libpersona: KNOX_SDCARD not a persona
,08-04 10:46:14.887  7981  7981 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,08-04 10:46:14.887  7981  7981 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 10:46:14.887  7981  7981 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,08-04 10:46:14.887   746  1366 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7981 uid=10050 gids={50050, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-04 10:46:14.887   746  1366 I ActivityManager: Killing 7043:com.sec.android.provider.badge/u0a92 (adj 15): emptyCount ##41
,08-04 10:46:14.887   746   762 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,08-04 10:46:14.887   746   762 D ActivityManager: caller:android.app.ApplicationThreadProxy@4336621, r.packageName :com.sec.spp.push
,08-04 10:46:14.907  7965  7989 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,08-04 10:46:14.907  7981  7981 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:14.907  7981  7981 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:14.917  7981  7981 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,08-04 10:46:14.957  7981  7981 I SA      : [SSP] onCreated
,08-04 10:46:14.967  7981  7981 I SA      : [TPM] There is no property file
,08-04 10:46:14.967  7981  7981 I SA      : [SCU] isHaveSA() - false
,08-04 10:46:14.967  7981  7981 I SA      : [TPM] getModelProperty : null
,08-04 10:46:14.967  7981  7981 I SA      : [TPM] getCSCProperty : null
,08-04 10:46:14.977  7981  7981 I SA      : [DM] init START
,08-04 10:46:14.977  7981  7981 I SA      : [DM] This device is not a Vodafone
,08-04 10:46:14.977  7981  7981 I SA      : checkReactivationActive for LOLLIPOP
,08-04 10:46:14.977  7981  7981 I SA      : checkReactivationActive for reactiveActive
08-04 10:46:14.977  7981  7981 I SA      : setSupportRL : true
,08-04 10:46:14.977  7981  7981 I SA      : [SCU] isHaveSA() - false
,08-04 10:46:14.977  7981  7981 I SA      : support phone number id : false
,08-04 10:46:14.987  7981  7981 I SA      : [DM] init END
,08-04 10:46:14.987  7981  7981 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,08-04 10:46:14.997  7981  7981 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,08-04 10:46:14.997  7981  7981 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,08-04 10:46:14.997  7981  7981 I SA      : [SLFUCHKMGR] constructor called
,08-04 10:46:14.997  7981  7981 I SA      : [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,08-04 10:46:14.997  7981  7981 I SA      : [OR] == isSIMCardReady false ==
08-04 10:46:14.997  7981  7981 I SA      : [SCU] == networkStateCheck == false
,08-04 10:46:14.997  7981  7981 I SA      : [OR] onReceive END
,08-04 10:46:15.007   746  1426 I ActivityManager: Killing 7059:com.sec.android.app.soundalive/u0a64 (adj 15): emptyCount ##41
,08-04 10:46:15.007   746  1444 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,08-04 10:46:15.007   746  1444 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:15.007   746  1444 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:15.007   746  1444 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:15.007   746  1444 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:15.047  8003  8003 E Zygote  : MountEmulatedStorage()
08-04 10:46:15.047  8003  8003 E Zygote  : v2
08-04 10:46:15.047  8003  8003 I libpersona: KNOX_SDCARD checking this for 10074
08-04 10:46:15.047  8003  8003 I libpersona: KNOX_SDCARD not a persona
,08-04 10:46:15.057   746  1444 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=8003 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,08-04 10:46:15.067  8003  8003 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 10:46:15.067  8003  8003 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 10:46:15.067  8003  8003 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 10:46:15.077  7938  7938 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,08-04 10:46:15.087  8003  8003 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:15.087  8003  8003 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:15.097  8003  8003 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,08-04 10:46:15.127  7938  7938 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-04 10:46:15.127  7938  7938 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-04 10:46:15.127   385   385 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7938
08-04 10:46:15.127   385   385 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-04 10:46:15.127  7938  7938 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-04 10:46:15.127  7938  7938 I wpa_supplicant: ssSupport state is = 1
08-04 10:46:15.127  7938  7938 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-04 10:46:15.127  7938  7938 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-04 10:46:15.127  7938  7938 E wpa_supplicant: SIM READ ERROR
08-04 10:46:15.127  7938  7938 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-04 10:46:15.127  7938  7938 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-04 10:46:15.127  7938  7938 E wpa_supplicant: SIM READ ERROR
08-04 10:46:15.127  7938  7938 I wpa_supplicant: Blacklist: Clear (all) 
,08-04 10:46:15.127  7938  7938 I wpa_supplicant: wpa_default_ap_write_once
08-04 10:46:15.127  7938  7938 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-04 10:46:15.127  7938  7938 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-04 10:46:15.127  7938  7938 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-04 10:46:15.127  7938  7938 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-04 10:46:15.127  7938  7938 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-04 10:46:15.127  7938  7938 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-04 10:46:15.147  8003  8003 I sCloudBackupApp: sCloudBackupApp Version Info : 3.13.7.KK_APP
,08-04 10:46:15.147  8003  8003 I SCloudBackupReceiver: Other Intent
,08-04 10:46:15.147  7333  7333 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,08-04 10:46:15.157  7333  7333 I KnoxUsageLogPro: premStatus:2
,08-04 10:46:15.157  7333  7333 I KnoxUsageLogPro: isEulaShown : false
08-04 10:46:15.157  7333  7333 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,08-04 10:46:15.157   746   762 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,08-04 10:46:15.157   746   762 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:15.157   746   762 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:15.157   746   762 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:15.157   746   762 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:15.197  8022  8022 E Zygote  : MountEmulatedStorage()
08-04 10:46:15.197  8022  8022 E Zygote  : v2
08-04 10:46:15.197  8022  8022 I libpersona: KNOX_SDCARD checking this for 10104
08-04 10:46:15.197  8022  8022 I libpersona: KNOX_SDCARD not a persona
,08-04 10:46:15.207   746   762 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=8022 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-04 10:46:15.217   746   762 I ActivityManager: Killing 5837:com.samsung.android.app.assistantmenu/1000 (adj 15): emptyCount ##41
,08-04 10:46:15.227  8022  8022 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 10:46:15.227  8022  8022 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 10:46:15.227  8022  8022 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,08-04 10:46:15.247  8022  8022 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:15.247  8022  8022 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:15.257  8022  8022 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,08-04 10:46:15.327   746  1459 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,08-04 10:46:15.327   746  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:15.327   746  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:15.327   746  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:15.327   746  1459 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:15.367  8038  8038 E Zygote  : MountEmulatedStorage()
,08-04 10:46:15.367  8038  8038 E Zygote  : v2
08-04 10:46:15.367  8038  8038 I libpersona: KNOX_SDCARD checking this for 10146
08-04 10:46:15.367  8038  8038 I libpersona: KNOX_SDCARD not a persona
,08-04 10:46:15.377  8038  8038 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 10:46:15.377  8038  8038 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 10:46:15.377  8038  8038 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,08-04 10:46:15.377   746  1459 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8038 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-04 10:46:15.377   746  1459 I ActivityManager: Killing 7080:com.wsomacp/u0a29 (adj 15): emptyCount ##41
,08-04 10:46:15.407  8038  8038 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:15.407  8038  8038 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:15.417  8038  8038 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,08-04 10:46:15.637   266   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-04 10:46:15.637   266   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-04 10:46:15.637  8038  8059 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-04 10:46:15.647   266   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-04 10:46:15.647   266   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-04 10:46:15.647  8038  8059 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-04 10:46:15.687   266   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
08-04 10:46:15.687   266   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-04 10:46:15.687  8038  8063 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,08-04 10:46:15.687   266   530 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
08-04 10:46:15.687   266   530 W Vold    : Returning OperationFailed - no handler for errno 0
,08-04 10:46:15.687  8038  8063 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,08-04 10:46:15.797  8038  8038 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,08-04 10:46:15.797  8038  8038 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,08-04 10:46:15.807  8038  8038 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 8842-8846)
,08-04 10:46:15.807  8038  8038 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-04 10:46:15.817  8038  8038 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2fc1b614}
,08-04 10:46:15.817  8038  8038 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-04 10:46:15.817  8038  8038 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-04 10:46:15.837  8038  8038 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-04 10:46:15.837  8038  8038 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-04 10:46:15.837  8038  8038 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-04 10:46:15.847   746  1328 E Watchdog: !@Sync 5
,08-04 10:46:15.937   746  1153 E Tethering: No numeric data
,08-04 10:46:15.937   746  1153 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-04 10:46:15.937   746  1147 V NetworkStats: performPollLocked(flags=0x1)
,08-04 10:46:15.937   746  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:15.937  1190  1190 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-04 10:46:15.937  1190  1190 D HotspotTile: updateTetherState():false, false
,08-04 10:46:15.937   746  1147 D NetworkStatsFactory: UpdateStatsForKnox
,08-04 10:46:15.937   746  1147 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:15.947   746  1147 V NetworkStats: performPollLocked() took 4ms
,08-04 10:46:15.947   746  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 10:46:15.947   746  1148 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:15.947   746  1148 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 10:46:15.947  8038  8038 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-04 10:46:15.947  8038  8038 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
08-04 10:46:15.947  8038  8038 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,08-04 10:46:15.957  7938  7938 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-04 10:46:15.957  8038  8038 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
08-04 10:46:15.957  8038  8038 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
08-04 10:46:15.957  8038  8038 I Adreno-EGL: Build Date: 11/19/14 Wed
08-04 10:46:15.957  8038  8038 I Adreno-EGL: Local Branch: mybranch5813579
08-04 10:46:15.957  8038  8038 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
08-04 10:46:15.957  8038  8038 I Adreno-EGL: Local Patches: NONE
08-04 10:46:15.957  8038  8038 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,08-04 10:46:15.987  7938  7938 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-04 10:46:15.987  7938  7938 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-04 10:46:15.987  7938  7938 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-04 10:46:15.987   385   385 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7938
08-04 10:46:15.987   385   385 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
,08-04 10:46:15.987  7938  7938 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-04 10:46:15.987  7938  7938 I wpa_supplicant: ssSupport state is = 1
08-04 10:46:15.987  7938  7938 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-04 10:46:15.987  7938  7938 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-04 10:46:15.987   385   385 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7938
08-04 10:46:15.987   385   385 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-04 10:46:15.987  7938  7938 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-04 10:46:15.987  7938  7938 I wpa_supplicant: ssSupport state is = 1
08-04 10:46:15.987  7938  7938 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-04 10:46:15.987  7938  7938 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-04 10:46:15.987  7938  7938 E wpa_supplicant: SIM READ ERROR
08-04 10:46:15.987  7938  7938 I wpa_supplicant: wpa_default_ap_write_once
,08-04 10:46:15.987  7938  7938 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-04 10:46:15.987  7938  7938 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-04 10:46:16.007  7938  7938 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-04 10:46:16.007  7938  7938 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-04 10:46:16.017  7938  7938 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-04 10:46:16.017  7938  7938 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-04 10:46:16.017   746  1150 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-04 10:46:16.017   746  1150 D WifiNative-HAL: callSECApiBoolean - ID [21]
,08-04 10:46:16.017  7938  7938 I wpa_supplicant: HOTSPOT20_ENABLE called
08-04 10:46:16.017  7938  7938 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-04 10:46:16.017  7938  7938 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-04 10:46:16.017  7938  7938 E wpa_supplicant: SIM READ ERROR
08-04 10:46:16.017  7938  7938 I wpa_supplicant: Blacklist: Clear (all) 
,08-04 10:46:16.027  8038  8094 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-04 10:46:16.037  8038  8038 I NSApplication: Starting up...
,08-04 10:46:16.047  7938  7938 I wpa_supplicant: Skip scan - bUseNetwork false
,08-04 10:46:16.047   746  1455 I ActivityManager: Killing 7096:com.google.android.apps.docs/u0a112 (adj 15): emptyCount ##41
,08-04 10:46:16.047   746  1150 D WifiNative-HAL: callSECApiInt - ID [210]
,08-04 10:46:16.047   746   746 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,08-04 10:46:16.057  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 10:46:16.057  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-04 10:46:16.057  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:16.057  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:16.057  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:16.057  1190  1190 D StatusBar.NetworkController: applyOpen
,08-04 10:46:16.057   746  1154 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,08-04 10:46:16.057  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:16.057  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:16.057  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:16.057  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:16.057  1190  1190 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 10:46:16.057  1190  1190 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
08-04 10:46:16.057  1190  1190 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 10:46:16.057   746  1150 D WifiConfigStore: Loading config and enabling all networks 
,08-04 10:46:16.057  1190  1602 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-04 10:46:16.057  1190  1190 D HotspotTile: onReceive : 3, 0
08-04 10:46:16.057  7553  7553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:16.057  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:16.057  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:16.057  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:16.057  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:16.057  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:46:16.057  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:16.057  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:16.057  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:46:16.057  7553  7553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:16.057  7553  7553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:46:16.057  7553  7553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:16.057  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:16.057  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:16.057  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:16.057  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:16.057  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:46:16.057  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:16.057  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:16.057  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:46:16.057  7553  7553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:16.057  7553  7553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:46:16.057  1320  1320 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-04 10:46:16.057   746  1150 E WifiConfigStore: Not a HS20
,08-04 10:46:16.077   746  1150 E WifiConfigStore: Not a HS20
,08-04 10:46:16.077   746  1150 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-04 10:46:16.077   746  1150 D WifiNative-HAL: callSECApiInt - ID [65]
,08-04 10:46:16.087   746  1150 D WifiNative-HAL: callSECApiBoolean - ID [13]
08-04 10:46:16.087  7938  7938 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-04 10:46:16.087  7938  7938 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-04 10:46:16.087  7938  7938 I wpa_supplicant: reset timer : RESET_TIMER 0
08-04 10:46:16.087  7938  7938 I wpa_supplicant: P2P: Current p2p state = IDLE
08-04 10:46:16.087  7938  7938 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-04 10:46:16.087  7938  7938 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-04 10:46:16.087  7938  7938 I wpa_supplicant: First Scan Start
,08-04 10:46:16.097  7938  7938 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-04 10:46:16.097   746  1150 D WifiNative-HAL: Setting external_sim to 1
,08-04 10:46:16.097   746  1150 D WifiStateMachine: Setting OUI to DA-A1-19
08-04 10:46:16.097   746  1150 I WifiNative-HAL: startHal
08-04 10:46:16.097   746  1150 E wifi    : getStaticLongField sWifiHalHandle 0x933b986c
08-04 10:46:16.097   746  1150 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x501ca6
08-04 10:46:16.097   746  1150 I WifiNative-HAL: Could not start hal
,08-04 10:46:16.097  7770  7770 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 10:46:16.107   746  1150 E native  : do suspend true
,08-04 10:46:16.117   746  1149 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-04 10:46:16.117   746  1150 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-04 10:46:16.117   746   746 D WifiScanningService: SCAN_AVAILABLE : 3
08-04 10:46:16.117   746   746 D RttService: SCAN_AVAILABLE : 3
08-04 10:46:16.117   746  1167 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:16.117   746  1167 I WifiNative-HAL: startHal
08-04 10:46:16.117   746  1167 E wifi    : getStaticLongField sWifiHalHandle 0x9c71499c
08-04 10:46:16.117   746  1167 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0xc01c9e
08-04 10:46:16.117   746  1167 I WifiNative-HAL: Could not start hal
08-04 10:46:16.117   746  1167 E WifiScanningService: could not start HAL
08-04 10:46:16.117   746  1168 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-04 10:46:16.117   305  1066 D CommandListener: Setting iface cfg
08-04 10:46:16.117   305  1066 D CommandListener: Trying to bring up p2p0
,08-04 10:46:16.117   746  1149 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-04 10:46:16.117   746  1150 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
08-04 10:46:16.117   746  1150 D WifiNative-HAL: callSECStringApiVoid - ID [215]
08-04 10:46:16.117   746  1150 E WifiNative-HAL: invaild command id : 215
08-04 10:46:16.117   746  1149 D WifiP2pService: P2pEnablingState
08-04 10:46:16.117   746  1149 D WifiP2pService: P2pEnablingState{ what=147457 }
,08-04 10:46:16.117   746  1149 D WifiP2pService: P2p socket connection successful
08-04 10:46:16.117   746  1149 D WifiP2pService: P2pEnabledState
,08-04 10:46:16.117   746  1030 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-04 10:46:16.117   746  1030 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-04 10:46:16.117   746  1030 D WifiDisplayController: disconnect
08-04 10:46:16.117   746  1030 D WifiDisplayController: updateConnection
08-04 10:46:16.117   746  1030 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-04 10:46:16.117   746  1030 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-04 10:46:16.117   746   746 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-04 10:46:16.117  1190  1190 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-04 10:46:16.117   746  1461 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-04 10:46:16.117  1190  1190 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-04 10:46:16.127   746  1149 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-04 10:46:16.127   746  1030 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:16.127   746  1030 D WifiDisplayAdapter: onP2pDisconnected
08-04 10:46:16.127   746  1030 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-04 10:46:16.127   746  1030 D IpRemoteDisplayController: WfdBridgeServer is already null
08-04 10:46:16.127   746  1152 E ConnectivityService: updateNetworkInfo()
08-04 10:46:16.127   746  1152 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,08-04 10:46:16.147  7938  7938 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-04 10:46:16.147   746  1149 D WifiNative-HAL: p2pGetDeviceAddress
,08-04 10:46:16.147   746  1149 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:de:28:a3
08-04 10:46:16.147   746  1149 D WifiP2pService: DeviceAddress: ea:28:a3
,08-04 10:46:16.147   746  1030 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
08-04 10:46:16.147   746  1030 D WifiDisplayController:  deviceAddress: ea:50:8b:de:28:a3
08-04 10:46:16.147   746  1030 D WifiDisplayController:  primary type: 10-0050F204-5
08-04 10:46:16.147   746  1030 D WifiDisplayController:  secondary type: null
08-04 10:46:16.147   746  1030 D WifiDisplayController:  wps: 0
08-04 10:46:16.147   746  1030 D WifiDisplayController:  grpcapab: 0
08-04 10:46:16.147   746  1030 D WifiDisplayController:  devcapab: 0
08-04 10:46:16.147   746  1030 D WifiDisplayController:  status: 3
08-04 10:46:16.147   746  1030 D WifiDisplayController:  wfdInfo: null
08-04 10:46:16.147   746  1030 D WifiDisplayController:  groupownerAddress: null
08-04 10:46:16.147   746  1030 D WifiDisplayController:  GOdeviceName: null
08-04 10:46:16.147   746  1030 D WifiDisplayController:  interfaceAddress: 
08-04 10:46:16.147   746  1030 D WifiDisplayController:  SConnectInfo : null
,08-04 10:46:16.167   746  1298 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,08-04 10:46:16.167   746  1298 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:16.167   746  1298 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:16.167   746  1298 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:16.167   746  1298 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:16.167  7938  7938 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,08-04 10:46:16.177   746  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-04 10:46:16.177   746  1150 D SecContentProvider2: mCursor = null
,08-04 10:46:16.187   746  1149 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-04 10:46:16.207  8104  8104 E Zygote  : MountEmulatedStorage()
08-04 10:46:16.207  8104  8104 E Zygote  : v2
08-04 10:46:16.207  8104  8104 I libpersona: KNOX_SDCARD checking this for 10158
08-04 10:46:16.207  8104  8104 I libpersona: KNOX_SDCARD not a persona
,08-04 10:46:16.217   746  1298 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=8104 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,08-04 10:46:16.217   746  1149 D WifiP2pService: InactiveState
08-04 10:46:16.217   746  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-04 10:46:16.217   746  1150 D SecContentProvider2: mCursor = null
08-04 10:46:16.217   746  1149 D WifiP2pService: InactiveState{ what=143376 }
08-04 10:46:16.217   746  1149 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-04 10:46:16.217  7938  7938 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-04 10:46:16.217   746  1149 D WifiP2pService: InactiveState{ what=143376 }
,08-04 10:46:16.217   746  1149 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-04 10:46:16.227  8104  8104 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 10:46:16.227  8104  8104 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 10:46:16.227  8104  8104 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 10:46:16.237  8104  8104 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:16.237  8104  8104 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:16.257  8104  8104 D ResourcesManager: creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,08-04 10:46:16.257   310   310 E SMD     : DCD ON
,08-04 10:46:16.257  8104  8104 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-04 10:46:16.257  8104  8104 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
08-04 10:46:16.257  8104  8104 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-04 10:46:16.267  8104  8104 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:46:16.267  8104  8104 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-04 10:46:16.277  8104  8104 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-04 10:46:16.277   746   764 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
08-04 10:46:16.277   746   764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:16.277   746   764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:16.277   746   764 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:16.277   746   764 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:16.317  8119  8119 E Zygote  : MountEmulatedStorage()
08-04 10:46:16.317  8119  8119 E Zygote  : v2
08-04 10:46:16.317  8119  8119 I libpersona: KNOX_SDCARD checking this for 10186
08-04 10:46:16.317  8119  8119 I libpersona: KNOX_SDCARD not a persona
,08-04 10:46:16.327  8119  8119 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 10:46:16.327  8119  8119 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 10:46:16.327  8119  8119 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 10:46:16.327   746   764 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=8119 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
08-04 10:46:16.327   746   764 I ActivityManager: Killing 7136:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##41
,08-04 10:46:16.347  8119  8119 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:16.347  8119  8119 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:16.357  8119  8119 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,08-04 10:46:16.367  8119  8119 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,08-04 10:46:16.367  8119  8119 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 10:46:16.367  8119  8119 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
08-04 10:46:16.367  8119  8119 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-04 10:46:16.367  8119  8119 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,08-04 10:46:16.447   746  1718 D RCPManagerService: exchangeData() failure , invalid userId
,08-04 10:46:16.477   746  1455 D RCPManagerService: exchangeData() failure , invalid userId
,08-04 10:46:16.477   746  1401 D RCPManagerService: exchangeData() failure , invalid userId
,08-04 10:46:16.507   746  1401 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,08-04 10:46:16.507   746  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:16.507   746  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:16.507   746  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:16.507   746  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:16.527   746  1696 D RCPManagerService: exchangeData() failure , invalid userId
,08-04 10:46:16.547   746  1455 D RCPManagerService: exchangeData() failure , invalid userId
,08-04 10:46:16.557   746  1298 D RCPManagerService: exchangeData() failure , invalid userId
08-04 10:46:16.557  8142  8142 E Zygote  : MountEmulatedStorage()
08-04 10:46:16.557  8142  8142 I libpersona: KNOX_SDCARD checking this for 10092
08-04 10:46:16.557  8142  8142 E Zygote  : v2
08-04 10:46:16.557  8142  8142 I libpersona: KNOX_SDCARD not a persona
,08-04 10:46:16.557   746  1401 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8142 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,08-04 10:46:16.577  8142  8142 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 10:46:16.577  8142  8142 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 10:46:16.577  8142  8142 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,08-04 10:46:16.577   746  1471 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:16.577  7624  7624 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-04 10:46:16.577  7624  7624 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-04 10:46:16.577  7624  7624 D SecurityLogAgent: StateMachine : Current State = 1
08-04 10:46:16.577  7624  7624 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-04 10:46:16.587   746  1444 I ActivityManager: Killing 7153:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): emptyCount ##41
,08-04 10:46:16.587   746  3312 D SSRM:n  : SIOP:: AP = 390, PST = 361, CUR = 450
,08-04 10:46:16.587   746  1718 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
,08-04 10:46:16.587   746  1455 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:16.587   746  1145 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:16.587   746  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:16.587   746  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:16.587   746  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:16.587   746  1718 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:16.597  8142  8142 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:16.597  8142  8142 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:16.627  8157  8157 E Zygote  : MountEmulatedStorage()
08-04 10:46:16.627  8157  8157 I libpersona: KNOX_SDCARD checking this for 10200
08-04 10:46:16.627  8157  8157 E Zygote  : v2
08-04 10:46:16.627  8157  8157 I libpersona: KNOX_SDCARD not a persona
,08-04 10:46:16.637   746  1718 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8157 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-04 10:46:16.657  8157  8157 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 10:46:16.657  8157  8157 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 10:46:16.657  8157  8157 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,08-04 10:46:16.657   746  1461 I ActivityManager: Killing 7168:com.samsung.helphub/1000 (adj 15): emptyCount ##41
,08-04 10:46:16.677  8157  8157 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:16.677  8157  8157 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:16.757   746  1471 I art     : Explicit concurrent mark sweep GC freed 42537(2MB) AllocSpace objects, 4(64KB) LOS objects, 30% free, 37MB/53MB, paused 1.248ms total 95.235ms
,08-04 10:46:16.767  8142  8142 D ResourcesManager: creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
,08-04 10:46:16.777  8157  8157 D ResourcesManager: creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,08-04 10:46:16.777  8142  8142 D BadgeProvider: onCreate
,08-04 10:46:16.777  8142  8142 D BadgeProvider: DatabaseHelper
,08-04 10:46:16.787   746  1435 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,08-04 10:46:16.797  8142  8151 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,08-04 10:46:16.797   746  1401 I ActivityManager: Killing 7207:com.samsung.android.snote:provider/u0a168 (adj 15): emptyCount ##41
,08-04 10:46:16.797   746  1444 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-04 10:46:16.797   746  1444 D ActivityManager: caller:android.app.ApplicationThreadProxy@614b17e, r.packageName :com.google.android.gms
,08-04 10:46:16.807  4674  4674 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-04 10:46:16.807  4674  5582 I iu.UploadsManager: num queued entries: 0
,08-04 10:46:16.807  4674  5582 I iu.UploadsManager: num updated entries: 0
,08-04 10:46:16.807  4674  5582 I iu.SyncManager: NEXT; no task
,08-04 10:46:16.817  1419  1419 D Launcher.Model: reloadBadges entered.
,08-04 10:46:16.817  8142  8151 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
08-04 10:46:16.817  8142  8151 D BadgeProvider: sendNotify, [notify] : null
08-04 10:46:16.817  8142  8151 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
,08-04 10:46:16.817  8142  8151 D BadgeProvider: update, [BadgeCount] : badgecount=0
08-04 10:46:16.817  8142  8151 D BadgeProvider: update, [UpdateCount] : 1
,08-04 10:46:16.827  7187  7187 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-04 10:46:16.837   746  1459 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:16.837  7624  7624 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-04 10:46:16.837  7624  7624 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-04 10:46:16.837  7624  7624 D SecurityLogAgent: StateMachine : Current State = 1
08-04 10:46:16.837  7624  7624 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-04 10:46:16.847  7187  7187 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-04 10:46:16.847   746  1145 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:16.847  7624  7624 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-04 10:46:16.847  7624  7624 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-04 10:46:16.847  7624  7624 D SecurityLogAgent: StateMachine : Current State = 1
08-04 10:46:16.847  7624  7624 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-04 10:46:16.857  7754  7754 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,08-04 10:46:16.857  1320  1320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-04 10:46:16.857  1320  1320 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-04 10:46:16.857   746  1366 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:16.857  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-04 10:46:16.867   746  1696 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:16.867  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-04 10:46:16.867  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-04 10:46:16.867  1320  1320 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-04 10:46:16.867  1320  3147 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-04 10:46:16.867  7318  7318 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-04 10:46:16.867  7754  7754 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-04 10:46:16.867  7754  7754 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
08-04 10:46:16.867  7754  7754 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,08-04 10:46:16.867  7754  7754 D WifiDirectBR: stopServiceTest : false
,08-04 10:46:16.887  7938  7938 I wpa_supplicant: nl80211: Received scan results (26 BSSes)
08-04 10:46:16.887  7938  7938 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-04 10:46:16.887  7938  7938 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
08-04 10:46:16.887  7938  7938 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-04 10:46:16.887  7938  7938 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=5 BSSID=00.00.00 SSID=4E47373030
,08-04 10:46:16.897   746  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-04 10:46:16.897   746  1150 D SecContentProvider2: mCursor = null
,08-04 10:46:16.957  7938  7938 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,08-04 10:46:16.957  7938  7938 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=6 BSSID=00.00.00 SSID=4E47373030
08-04 10:46:16.957  7938  7938 I wpa_supplicant: Associated with F4.99.3E
08-04 10:46:16.957  7938  7938 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-04 10:46:16.957  7938  7938 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-04 10:46:16.967   746  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-04 10:46:16.967   746  1150 D SecContentProvider2: mCursor = null
,08-04 10:46:16.967   746  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-04 10:46:16.967   746  1150 D SecContentProvider2: mCursor = null
,08-04 10:46:16.977  7938  7938 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-04 10:46:16.977  7938  7938 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-04 10:46:16.977  7938  7938 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-04 10:46:16.977  7938  7938 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-04 10:46:16.977  7938  7938 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-04 10:46:16.977  7938  7938 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=1 id_str=]
,08-04 10:46:16.977  7938  7938 I wpa_supplicant: Blacklist: Clear (temp) 
08-04 10:46:16.977  7938  7938 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-04 10:46:16.977   746  1150 D WifiNative-HAL: callSECApiVoid - ID [50]
,08-04 10:46:16.977  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 10:46:16.977  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 10:46:16.987  1320  1320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-04 10:46:16.987  1320  1320 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-04 10:46:16.987   746  1366 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:16.987  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-04 10:46:16.987   746  1455 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:16.987  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-04 10:46:16.987  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-04 10:46:16.987  1320  1320 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-04 10:46:16.987  1320  3147 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-04 10:46:16.987   746  1150 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-04 10:46:16.987   746  1150 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 10:46:16.987   746  1152 D ConnectivityService: Got NetworkAgent Messenger
08-04 10:46:16.987   746  1152 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-04 10:46:16.987   746  1152 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 10:46:16.987   746  1152 E ConnectivityService: updateNetworkInfo()
08-04 10:46:16.987   746  1152 D ConnectivityService: NetworkAgent connected
,08-04 10:46:16.997   746  1426 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:16.997  7187  7187 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-04 10:46:16.997   746  1150 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 10:46:17.007   305  1066 D CommandListener: Setting iface cfg
,08-04 10:46:17.007   746  1150 E WifiStateMachine: Start Dhcp Watchdog 2
,08-04 10:46:17.007   746  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-04 10:46:17.007   746  1150 D SecContentProvider2: mCursor = null
,08-04 10:46:17.017  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 10:46:17.017  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 10:46:17.017   746  1152 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,08-04 10:46:17.097   746  1150 E native  : do suspend false
,08-04 10:46:17.097   746  1149 D WifiP2pService: InactiveState{ what=143375 }
,08-04 10:46:17.097   746  1149 D WifiP2pService: P2pEnabledState{ what=143375 }
08-04 10:46:17.097   746  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-04 10:46:17.097   746  1150 D SecContentProvider2: mCursor = null
,08-04 10:46:17.317  8199  8199 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-04 10:46:17.317  8199  8199 I dhcpcd  : version 5.5.6 starting
,08-04 10:46:17.317  8199  8199 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-04 10:46:17.387  8199  8199 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-04 10:46:17.387  8199  8199 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-04 10:46:17.387  8199  8199 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-04 10:46:17.387  8199  8199 I dhcpcd  : bssid match
08-04 10:46:17.387  8199  8199 I dhcpcd  : wlan0: rebinding lease of 192.168.1.122
,08-04 10:46:17.397  1942  3175 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-04 10:46:17.407  8199  8199 I dhcpcd  : wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,08-04 10:46:17.417  8199  8199 I dhcpcd  : wlan0: leased 192.168.1.122 for 172800 seconds
,08-04 10:46:17.417   746  1152 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,08-04 10:46:17.497  7553  7621 I WifiManager: packageName : com.test.thalitest
08-04 10:46:17.497   746   764 D SecContentProvider: uri = 18 selection = isWifiEnabled
08-04 10:46:17.497   746   764 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-04 10:46:17.497   746   764 D SecContentProvider2: mCursor = null
,08-04 10:46:17.497   746   764 D WifiService: setWifiEnabled: false pid=7553, uid=10079
,08-04 10:46:17.497   746   764 D SettingsProvider: name = wifi_on
,08-04 10:46:17.507   746  1150 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 10:46:17.517   746  1150 E native  : do suspend true
,08-04 10:46:17.527   746  1149 D WifiP2pService: InactiveState{ what=143375 }
,08-04 10:46:17.527   746  1149 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-04 10:46:17.527   305  1066 D CommandListener: Clearing all IP addresses on wlan0
,08-04 10:46:17.527  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-04 10:46:17.527  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 10:46:17.567   746  1150 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 10:46:17.567   746  1152 E ConnectivityService: updateNetworkInfo()
08-04 10:46:17.567   746  1152 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-04 10:46:17.567   746   746 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-04 10:46:17.567  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 10:46:17.567   746  1152 E ConnectivityService: updateNetworkInfo()
,08-04 10:46:17.567   746  1152 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
,08-04 10:46:17.567   746  1152 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
08-04 10:46:17.567   305  1066 E Netd    : no such netId 503
08-04 10:46:17.567  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 10:46:17.577   746  1152 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '77 network destroy 503' failed with '400 77 destroyNetwork() failed (Machine is not on the network)'
08-04 10:46:17.577   746  1152 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
08-04 10:46:17.577   746  1152 D ConnectivityService: calling update connectivity
,08-04 10:46:17.577   746  1152 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
08-04 10:46:17.577   746  1152 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
08-04 10:46:17.577   746  8179 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:17.577   746  8179 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,08-04 10:46:17.577   746   746 D WifiScanningService: SCAN_AVAILABLE : 1
,08-04 10:46:17.577   746  1149 D WifiP2pService: InactiveState{ what=131204 }
08-04 10:46:17.577   746  1149 D WifiP2pService: P2pEnabledState{ what=131204 }
08-04 10:46:17.577   746   746 D RttService: SCAN_AVAILABLE : 1
08-04 10:46:17.577   746  1149 D WifiP2pService: sending p2p connection changed broadcast: FAILED
08-04 10:46:17.577   746  1167 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:17.577   746  1168 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-04 10:46:17.587   746  1030 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:17.587   746  1030 D WifiDisplayAdapter: onP2pDisconnected
08-04 10:46:17.587   746  1030 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-04 10:46:17.587   746  1030 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-04 10:46:17.587   746  1152 E ConnectivityService: updateNetworkInfo()
,08-04 10:46:17.587   746  1152 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,08-04 10:46:17.587   746  1150 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-04 10:46:17.587   746  1030 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
08-04 10:46:17.587   746   746 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
08-04 10:46:17.587   746  1030 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-04 10:46:17.587   746  1030 D WifiDisplayController: disconnect
08-04 10:46:17.587   746  1030 D WifiDisplayController: updateConnection
08-04 10:46:17.587   746  1030 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-04 10:46:17.587   746  1030 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-04 10:46:17.587  1190  1190 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
08-04 10:46:17.587   746  1426 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
08-04 10:46:17.587  1190  1190 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-04 10:46:17.597   746  1149 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-04 10:46:17.597   746  1030 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-04 10:46:17.597   746  1030 D WifiDisplayAdapter: onP2pDisconnected
08-04 10:46:17.597   746  1030 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-04 10:46:17.597   746  1030 D IpRemoteDisplayController: WfdBridgeServer is already null
08-04 10:46:17.597   746  1152 E ConnectivityService: updateNetworkInfo()
08-04 10:46:17.597   746  1152 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
08-04 10:46:17.597   746  1149 D WifiP2pService: P2pDisablingState
,08-04 10:46:17.597   746  1149 D WifiP2pService: P2pDisablingState{ what=147458 }
08-04 10:46:17.597   746  1149 D WifiP2pService: p2p socket connection lost
08-04 10:46:17.597   746  1149 D WifiP2pService: P2pDisabledState
,08-04 10:46:17.597   746  1150 E native  : do suspend true
,08-04 10:46:17.597  1320  1320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
08-04 10:46:17.597  1320  1320 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-04 10:46:17.597   746  1435 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:17.597  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-04 10:46:17.597   746  1401 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-04 10:46:17.607  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-04 10:46:17.607  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-04 10:46:17.607  1320  1320 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-04 10:46:17.607  1320  3147 V NearbySettings: MountReceiver.mPrefHandler - 7002
08-04 10:46:17.607   746  1149 D WifiP2pService: P2pDisabledState{ what=143375 }
08-04 10:46:17.607   746  1149 D WifiP2pService: DefaultState{ what=143375 }
,08-04 10:46:17.607   305  1066 D CommandListener: Clearing all IP addresses on wlan0
,08-04 10:46:17.607  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 10:46:17.607  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 10:46:17.607   746  1471 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:17.607  7938  7938 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
08-04 10:46:17.617   746   746 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-04 10:46:17.617  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 10:46:17.617  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 10:46:17.617  7187  7187 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-04 10:46:17.627   746   746 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,08-04 10:46:17.627   746  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
08-04 10:46:17.627   746  1150 D SecContentProvider2: mCursor = null
,08-04 10:46:17.627  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 10:46:17.627  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-04 10:46:17.627  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:17.627  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:17.627  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:17.627  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:17.627  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:17.627  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:17.627  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:17.627  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:17.627  1190  1190 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 10:46:17.627  1190  1190 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,08-04 10:46:17.627  1190  1602 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-04 10:46:17.627  7553  7553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:17.627  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:17.627  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:17.627  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:17.627  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:46:17.627  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:46:17.627  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:17.627  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:17.627  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:46:17.627  7553  7553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:17.627  1190  1190 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 10:46:17.627  7553  7553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:46:17.627  1190  1190 D HotspotTile: onReceive : 0, 0
,08-04 10:46:17.627  1320  1320 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
08-04 10:46:17.627   746  1154 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
08-04 10:46:17.627  7553  7553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:17.627  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:17.627  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:17.627  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:17.627  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:46:17.627  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:46:17.627  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:17.627  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:17.627  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:46:17.627  7553  7553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:17.627  7553  7553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:46:17.637  1320  1320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-04 10:46:17.637  1320  1320 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-04 10:46:17.637   746  1426 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:17.637  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
08-04 10:46:17.637   746  1298 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,08-04 10:46:17.637  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-04 10:46:17.637  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-04 10:46:17.637  1320  1320 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-04 10:46:17.637  1320  3147 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-04 10:46:17.637  7318  7318 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-04 10:46:17.637  7754  7754 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-04 10:46:17.637  7754  7754 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
08-04 10:46:17.637  7754  7754 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,08-04 10:46:17.647  7754  7754 D WifiDirectBR: stopServiceTest : false
,08-04 10:46:17.647  7754  7754 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,08-04 10:46:17.657  1320  1320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-04 10:46:17.657  1320  1320 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-04 10:46:17.657   746  1297 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:17.657  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-04 10:46:17.657   746  1459 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-04 10:46:17.657  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-04 10:46:17.657  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-04 10:46:17.657  1320  1320 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-04 10:46:17.657  1320  3147 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-04 10:46:17.657   746  1298 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:17.657  7938  7938 I wpa_supplicant: Blacklist: Clear (all) 
,08-04 10:46:17.667  7187  7187 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-04 10:46:17.667  7187  7187 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-04 10:46:17.677   746  1444 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:17.677  7624  7624 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-04 10:46:17.677  7624  7624 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-04 10:46:17.677  7624  7624 D SecurityLogAgent: StateMachine : Current State = 1
08-04 10:46:17.677  7624  7624 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-04 10:46:17.687  7938  7938 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,08-04 10:46:17.687  7938  7938 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,08-04 10:46:17.687  7938  7938 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
08-04 10:46:17.687  7938  7938 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=0 BSSID=F4.99.3E SSID=4E47373030
08-04 10:46:17.687  7938  7938 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-04 10:46:17.757  7938  7938 I wpa_supplicant: Blacklist: Clear (all) 
,08-04 10:46:17.887   746  1153 D Tethering: InitialState.processMessage what=4
,08-04 10:46:17.887   746  1153 E Tethering: No numeric data
,08-04 10:46:17.887   746  1153 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-04 10:46:17.887  7938  7938 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-04 10:46:17.887   746  1147 V NetworkStats: performPollLocked(flags=0x1)
08-04 10:46:17.887   746  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 10:46:17.887  1190  1190 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-04 10:46:17.887  1190  1190 D HotspotTile: updateTetherState():false, false
,08-04 10:46:17.887   746  1147 D NetworkStatsFactory: UpdateStatsForKnox
08-04 10:46:17.887   746  1147 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:17.887   746  1147 V NetworkStats: performPollLocked() took 6ms
08-04 10:46:17.887   746  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 10:46:17.887   746  1148 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:17.887   746  1148 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 10:46:17.987   746  1150 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
08-04 10:46:17.997   746   746 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
08-04 10:46:17.987   746  1150 D WifiNative-HAL: callSECApiBoolean - ID [21]
,08-04 10:46:17.997  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 10:46:17.997  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,08-04 10:46:17.997  1942  2393 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-04 10:46:17.997  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:17.997   746  1154 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,08-04 10:46:17.997  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:17.997  1190  1190 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 10:46:17.997  1190  1190 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
08-04 10:46:17.997  1190  1190 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 10:46:17.997  7770  7770 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:17.997  1190  1602 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-04 10:46:17.997  1190  1190 D HotspotTile: onReceive : 1, 0
08-04 10:46:17.997  1320  1320 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-04 10:46:17.997  7187  7187 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-04 10:46:18.007   746   762 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:18.007  7624  7624 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-04 10:46:18.007  7624  7624 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-04 10:46:18.007  7624  7624 D SecurityLogAgent: StateMachine : Current State = 1
08-04 10:46:18.007  7624  7624 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-04 10:46:18.197   746  1150 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,08-04 10:46:18.207   746  1298 I ActivityManager: Killing 7227:com.sec.kidsplat.installer/u0a189 (adj 15): emptyCount ##41
,08-04 10:46:18.337   746  1145 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-04 10:46:18.667   746   764 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-04 10:46:18.667   746   764 D ActivityManager: caller:android.app.ApplicationThreadProxy@961b148, r.packageName :com.google.android.music
,08-04 10:46:18.677   746  1696 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-04 10:46:18.687   746  1426 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-04 10:46:18.687   746  1401 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-04 10:46:18.697   746  1145 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,08-04 10:46:18.697   746  1145 D ActivityManager: caller:android.app.ApplicationThreadProxy@211ac6de, r.packageName :com.google.android.music
,08-04 10:46:18.717  1942  1942 D WearableService: callingUid 10015, callindPid: 1942
,08-04 10:46:18.727   746  1444 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,08-04 10:46:18.767  7823  7823 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-04 10:46:18.767  7823  8263 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,08-04 10:46:18.807  7823  8258 I MusicLeanback: Conditions not met for autocaching.
08-04 10:46:18.807  7823  8258 I MusicLeanback: Stop autocaching.
,08-04 10:46:19.267   310   310 E SMD     : DCD ON
,08-04 10:46:20.507  7553  7621 D BluetoothAdapter: enable()
,08-04 10:46:20.507   746   762 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-04 10:46:20.507   746   762 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7553, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-04 10:46:20.507   746   762 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
08-04 10:46:20.507   746   762 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
08-04 10:46:20.507   746   762 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
08-04 10:46:20.507   746   762 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-04 10:46:20.507   746   762 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-04 10:46:20.507   746   762 W ActivityManager: Permission Denial: getCurrentUser() from pid=7553, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-04 10:46:20.507   746   762 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-04 10:46:20.507   746   762 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-04 10:46:20.507   746   762 D SettingsProvider: name = bluetooth_on
,08-04 10:46:20.517   746  1028 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-04 10:46:20.517   746  1028 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-04 10:46:20.517   746  1028 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-04 10:46:20.557  7799  7799 D BluetoothAdapterState: make
,08-04 10:46:20.557  7799  7799 I bluedroid: init
,08-04 10:46:20.567  7799  8275 I BluetoothAdapterState: Entering OffState
,08-04 10:46:20.567  7799  7799 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-04 10:46:20.567  7799  7799 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,08-04 10:46:20.567  7799  7799 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-04 10:46:20.567  7799  7799 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-04 10:46:20.567  7799  7799 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-04 10:46:20.567  7799  7799 I bluedroid: get_profile_interface socket
,08-04 10:46:20.567  7799  7799 I bluedroid: get_profile_interface map_client
,08-04 10:46:20.567  7799  7799 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-04 10:46:20.577   746  1461 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-04 10:46:20.577  7799  7808 I bluedroid: config_hci_snoop_log
,08-04 10:46:20.577   746  1028 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 14 receivers.
,08-04 10:46:20.577   746  1028 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-04 10:46:20.577   746  1028 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-04 10:46:20.587   746  1028 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-04 10:46:20.587  7799  8278 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,08-04 10:46:20.587  7799  8278 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
,08-04 10:46:20.587  7799  8278 E BluetoothServiceJni: populateRssiValuesNative
08-04 10:46:20.587  7799  8278 I bluedroid: getModelRssiValues
08-04 10:46:20.587  7799  8278 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-04 10:46:20.587  7799  8278 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-04 10:46:20.587   746   746 D SettingsProvider: name = bluetooth_name
,08-04 10:46:20.587  7799  8278 D BluetoothAdapterProperties: Name is: Note3-1
,08-04 10:46:20.587  7799  8275 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-04 10:46:20.587  7799  8275 D BluetoothAdapterProperties: Setting state to 11
,08-04 10:46:20.587  7799  8275 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-04 10:46:20.587  7799  8275 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-04 10:46:20.587  7799  8275 D BluetoothAdapterService: updateAdapterState state is 11
,08-04 10:46:20.597   746   746 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-04 10:46:20.597   746   746 I InputMethodManagerService: [BT Setting State] State =11
,08-04 10:46:20.607  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:20.607  1190  1190 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-04 10:46:20.607  1190  1190 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-04 10:46:20.607  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:20.607   746  1455 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,08-04 10:46:20.607  1190  1602 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-04 10:46:20.607   746  1426 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-04 10:46:20.607  1190  1190 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,08-04 10:46:20.607   746  1718 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-04 10:46:20.617   746  1718 D ActivityManager: caller:android.app.ApplicationThreadProxy@1e359666, r.packageName :com.google.android.gms
,08-04 10:46:20.617  7799  8275 D BluetoothAdapterService: Autoconnection is available 
,08-04 10:46:20.617  7799  8275 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-04 10:46:20.617  7799  8275 D BluetoothSecureManager: getInstant: null
,08-04 10:46:20.627  7799  8275 D BluetoothSecureManager: calling getMethod for getService
,08-04 10:46:20.627  7799  8275 D BluetoothSecureManager: calling getService
,08-04 10:46:20.627  7799  8275 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@308be73e
,08-04 10:46:20.627   746  1459 D BluetoothSecureManagerService: isSecureModeEnabled
08-04 10:46:20.627   746  1459 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,08-04 10:46:20.627  7799  8275 D BtConfig.SecureMode: isSecureModeOn:false
08-04 10:46:20.627  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-04 10:46:20.627  7799  8275 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
,08-04 10:46:20.627  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-04 10:46:20.637  7799  8275 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,08-04 10:46:20.637  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-04 10:46:20.637  7799  8275 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
08-04 10:46:20.637  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-04 10:46:20.637  7799  8275 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-04 10:46:20.637  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-04 10:46:20.637  7799  8275 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-04 10:46:20.637  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-04 10:46:20.637  7799  8275 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-04 10:46:20.637  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-04 10:46:20.637  7799  8275 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-04 10:46:20.637  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-04 10:46:20.637  7799  8275 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
08-04 10:46:20.637  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-04 10:46:20.637  7799  8275 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-04 10:46:20.637  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-04 10:46:20.647  7799  8275 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-04 10:46:20.647  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-04 10:46:20.647  7799  8275 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-04 10:46:20.647  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,08-04 10:46:20.647  7799  8275 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-04 10:46:20.647  7799  8275 D BluetoothBondStateMachine: make
,08-04 10:46:20.657  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,08-04 10:46:20.657  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-04 10:46:20.657  7799  8275 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-04 10:46:20.657   746  1366 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:20.657   746  1366 D ActivityManager: caller:android.app.ApplicationThreadProxy@2cdc2254, r.packageName :com.android.bluetooth
,08-04 10:46:20.657  7799  7799 I BtGatt.JNI: classInitNative(L890): classInitNative: Success!
,08-04 10:46:20.667  7799  8280 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-04 10:46:20.667  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
,08-04 10:46:20.667  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-04 10:46:20.667  7799  8275 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-04 10:46:20.667  7799  7799 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 10:46:20.667   746   764 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 10:46:20.667  7799  7799 D BtGatt.GattService: Received start request. Starting profile...
08-04 10:46:20.667  7799  7799 D BtGatt.GattService: start()
08-04 10:46:20.667  7799  7799 I bluedroid: get_profile_interface gatt
,08-04 10:46:20.667   746   764 D ActivityManager: caller:android.app.ApplicationThreadProxy@7f4b2f2, r.packageName :com.android.bluetooth
08-04 10:46:20.667  7799  7799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbb25c1
08-04 10:46:20.667  7799  7799 D BtGatt.AdvertiseManager: advertise manager created
,08-04 10:46:20.677  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-04 10:46:20.677  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-04 10:46:20.677  7799  8275 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-04 10:46:20.677  7727  7727 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:20.677   746  1426 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:20.677   746  1426 D ActivityManager: caller:android.app.ApplicationThreadProxy@2c030fc0, r.packageName :com.android.bluetooth
08-04 10:46:20.677  1320  1320 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:20.677  1688  1688 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-04 10:46:20.677  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-04 10:46:20.677  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-04 10:46:20.677  7799  8275 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-04 10:46:20.677  1320  1320 D BluetoothNotiBroadcastReceiver: onReceive
,08-04 10:46:20.687   746  1459 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,08-04 10:46:20.687   746  1435 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:20.687   746  1435 D ActivityManager: caller:android.app.ApplicationThreadProxy@25e967ec, r.packageName :com.android.bluetooth
,08-04 10:46:20.687  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-04 10:46:20.687  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-04 10:46:20.687  7799  8275 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-04 10:46:20.687   746  1461 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:20.687   746  1461 D ActivityManager: caller:android.app.ApplicationThreadProxy@3aeeba31, r.packageName :com.android.bluetooth
,08-04 10:46:20.687  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-04 10:46:20.687  7799  7799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbb25c1
,08-04 10:46:20.697  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-04 10:46:20.697  7799  8275 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,08-04 10:46:20.697  8038  8060 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-04 10:46:20.697   746   762 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:20.697   746   762 D ActivityManager: caller:android.app.ApplicationThreadProxy@10c9ee97, r.packageName :com.android.bluetooth
,08-04 10:46:20.697  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-04 10:46:20.697  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-04 10:46:20.697  7799  8275 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-04 10:46:20.697   746  1455 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:20.697  7799  7799 D HeadsetService: Received start request. Starting profile...
,08-04 10:46:20.697   746  1455 D ActivityManager: caller:android.app.ApplicationThreadProxy@19c3c86d, r.packageName :com.android.bluetooth
,08-04 10:46:20.697  7799  7799 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-04 10:46:20.697  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-04 10:46:20.697  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-04 10:46:20.697  7799  8275 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-04 10:46:20.707   746  1401 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 10:46:20.707  7799  7799 D HeadsetStateMachine: make
,08-04 10:46:20.707   746  1401 D ActivityManager: caller:android.app.ApplicationThreadProxy@1ab4dd33, r.packageName :com.android.bluetooth
,08-04 10:46:20.707  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-04 10:46:20.707  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-04 10:46:20.707  7799  8275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-04 10:46:20.707  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-04 10:46:20.707  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-04 10:46:20.707  7799  8275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-04 10:46:20.707  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-04 10:46:20.707  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-04 10:46:20.707  7799  8275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-04 10:46:20.707  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-04 10:46:20.707  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-04 10:46:20.707  7799  8275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-04 10:46:20.707  7799  8275 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-04 10:46:20.707  7799  7799 E HeadsetStateMachine: # of Max HF connection is 2
,08-04 10:46:20.717   746  1459 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-04 10:46:20.717   746  1444 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
,08-04 10:46:20.717  7799  7799 I bluedroid: get_profile_interface handsfree
,08-04 10:46:20.727  7799  7799 I DualScoManager: Instantiating Dual Sco Manager
08-04 10:46:20.727  7799  7799 I DualScoManager: Set HeadsetServiceHelper
,08-04 10:46:20.727  7799  7799 D BluetoothAtMessage: createCMTIContentObservers
,08-04 10:46:20.727   746  1471 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
08-04 10:46:20.727   746  1471 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:20.727   746  1471 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:20.727   746  1471 D SettingsProvider: selectionArgs: false
08-04 10:46:20.727   746  1471 D SettingsProvider: selectionArgs: 1002
08-04 10:46:20.727   746  1471 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:20.727   746  1471 D SettingsProvider: ret = -1
,08-04 10:46:20.727  7799  8303 D HeadsetStateMachine: Enter Disconnected: -2
08-04 10:46:20.727  7799  7799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbb25c1
,08-04 10:46:20.727  7799  8303 E HeadsetStateMachine: set to mRemoteBrsf = 0
,08-04 10:46:20.727  7799  7799 D A2dpService: Received start request. Starting profile...
,08-04 10:46:20.727  7799  8303 D HeadsetStateMachine: map size, before remove : 0
08-04 10:46:20.727  7799  8303 D HeadsetStateMachine: map size, after remove: 0
,08-04 10:46:20.727  7799  8303 D HeadsetStateMachine: mNextConnectingDevice : null
,08-04 10:46:20.727  7799  7799 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-04 10:46:20.727  7799  7799 V Avrcp   : make
,08-04 10:46:20.737  7799  7799 V Avrcp   : Avrcp
08-04 10:46:20.737  7799  7799 I bluedroid: get_profile_interface avrcp
,08-04 10:46:20.737  7799  7799 V Avrcp   : start
,08-04 10:46:20.737  7799  7799 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-04 10:46:20.737  7799  7799 V Avrcp   : ++registerMediaPlayers++
,08-04 10:46:20.737  7799  7799 I Avrcp   : No of Audio players :: 2
,08-04 10:46:20.737  7799  7799 I Avrcp   : App Package name is com.google.android.music
,08-04 10:46:20.747  7799  7799 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,08-04 10:46:20.747  7799  7799 I Avrcp   : App pkg name is Google Play Music
,08-04 10:46:20.747  7799  7799 I Avrcp   : Name::Google Play Music
08-04 10:46:20.747  7799  7799 V Avrcp   : MediaPlayerInfo: mPlayerId=1
08-04 10:46:20.747  7799  7799 I Avrcp   : App Package name is com.sec.android.app.music
,08-04 10:46:20.747  7799  7799 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,08-04 10:46:20.747  7799  7799 I Avrcp   : App pkg name is Music
,08-04 10:46:20.747  7799  7799 I Avrcp   : Name::Music
08-04 10:46:20.747  7799  7799 V Avrcp   : MediaPlayerInfo: mPlayerId=2
08-04 10:46:20.747  7799  7799 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,08-04 10:46:20.747  7799  7799 I Avrcp   : No of Video players :: 1
08-04 10:46:20.747  7799  7799 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
,08-04 10:46:20.757  7799  7799 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,08-04 10:46:20.757  7799  7799 I Avrcp   : Video App pkg name is Video Player
,08-04 10:46:20.757  7799  7799 I Avrcp   : Name::Video Player
08-04 10:46:20.757  7799  7799 V Avrcp   : MediaPlayerInfo: mPlayerId=3
08-04 10:46:20.757  7799  7799 I Avrcp   : Add tempPlayer
08-04 10:46:20.757  7799  7799 V Avrcp   : MediaPlayerInfo: mPlayerId=4
08-04 10:46:20.757  7799  7799 I Avrcp   : Total no of players: 4
08-04 10:46:20.757  7799  7799 V Avrcp   : swapping the samsung player with 1st player
08-04 10:46:20.757  7799  7799 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-04 10:46:20.757  7799  8304 V Avrcp   : handleMessage, msg=207
,08-04 10:46:20.757  7799  8304 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
08-04 10:46:20.757  7799  7799 I BluetoothA2dpServiceJni: classInitNative: succeeds
,08-04 10:46:20.757  7799  7799 D A2dpStateMachine: make
,08-04 10:46:20.757  7799  7799 I bluedroid: get_profile_interface a2dp
,08-04 10:46:20.757  7799  8306 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-04 10:46:20.757  7799  7799 E bt-btif : warning : media task started media_task_refcnt 1 
,08-04 10:46:20.757  7799  7799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbb25c1
,08-04 10:46:20.767  7799  8305 D A2dpStateMachine: Enter Disconnected: -2
,08-04 10:46:20.767  7799  7799 I BluetoothHidServiceJni: classInitNative: succeeds
,08-04 10:46:20.767  7799  7799 D HidService: Received start request. Starting profile...
08-04 10:46:20.767  7799  7799 I bluedroid: get_profile_interface hidhost
,08-04 10:46:20.767  7799  7799 D HidService: setHidService(): set to: null
08-04 10:46:20.767  7799  7799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbb25c1
08-04 10:46:20.767  7799  7799 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-04 10:46:20.767  7799  7799 D HealthService: Received start request. Starting profile...
,08-04 10:46:20.767  7799  8304 D BluetoothMediaBrowser: no now playing list
08-04 10:46:20.767  7799  8304 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-04 10:46:20.767  7799  8304 D Avrcp   :  checkNowPlayingList start
,08-04 10:46:20.767  7799  7799 I bluedroid: get_profile_interface health
,08-04 10:46:20.767  7799  7799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbb25c1
08-04 10:46:20.767  7799  7799 E BluetoothAdapterService(532358593): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-04 10:46:20.767  7799  7799 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-04 10:46:20.767  1942  1942 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-04 10:46:20.767  7799  7799 D PanService: Received start request. Starting profile...
08-04 10:46:20.767  7799  7799 D BluetoothPanServiceJni: initializeNative(L110): pan
08-04 10:46:20.767  7799  7799 I bluedroid: get_profile_interface pan
,08-04 10:46:20.777  7799  7799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbb25c1
,08-04 10:46:20.777  1942  1942 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-04 10:46:20.777  7799  7799 D BluetoothMapService: Received start request. Starting profile...
,08-04 10:46:20.797  7799  7799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbb25c1
,08-04 10:46:20.797  7799  7799 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-04 10:46:20.807  7799  7799 D SapService: Received start request. Starting profile...
08-04 10:46:20.807  7799  7799 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-04 10:46:20.807  7799  7799 I bluedroid: get_profile_interface sap
08-04 10:46:20.807  7799  7799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbb25c1
,08-04 10:46:20.807  7799  7799 D HeadsetStateMachine: Try to query the phonestate on bind
,08-04 10:46:20.807  1356  1387 I Telecom : BluetoothPhoneService: queryPhoneState
08-04 10:46:20.807  1356  1356 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-04 10:46:20.807  7799  7799 D HeadsetStateMachine: Proxy object connected
,08-04 10:46:20.807  7799  7799 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-04 10:46:20.807  7799  7799 D HeadsetPhoneState: sendDeviceDataStateChanged
08-04 10:46:20.807  7799  8303 D HeadsetStateMachine: Disconnected process message: 11
08-04 10:46:20.807  7799  8303 D HeadsetStateMachine: Disconnected process message: 18
08-04 10:46:20.807  7799  7799 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-04 10:46:20.807  7799  7799 E BluetoothAdapterService(532358593): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-04 10:46:20.807  7799  7799 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-04 10:46:20.807  7799  7799 D BluetoothA2dp: Proxy object connected
08-04 10:46:20.807  7799  7799 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-04 10:46:20.807  7799  7799 E BluetoothAdapterService(532358593): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-04 10:46:20.807  7799  7799 E BluetoothAdapterService(532358593): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,08-04 10:46:20.807  7799  7799 E BluetoothAdapterService(532358593): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
08-04 10:46:20.807  7799  7799 E BluetoothAdapterService(532358593): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-04 10:46:20.807  7799  8303 D HeadsetStateMachine: Disconnected process message: 10
08-04 10:46:20.807  7799  8303 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-04 10:46:20.807  7799  8303 D HeadsetStateMachine: Disconnected process message: 11
,08-04 10:46:20.817  7799  7799 E BluetoothAdapterService(532358593): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
08-04 10:46:20.817  7799  7799 E BluetoothAdapterService(532358593): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,08-04 10:46:20.817  7799  8275 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-04 10:46:20.817  7799  8275 I bluedroid: enable
,08-04 10:46:20.817  7799  8310 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-04 10:46:20.817  7799  8275 I bt_hci_bdroid: init
,08-04 10:46:20.817  7799  8275 I bt_vendor: init
,08-04 10:46:20.817  7799  8275 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-04 10:46:20.817  7799  8275 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
08-04 10:46:20.817  7799  8275 D bt_userial: userial_init
08-04 10:46:20.817  7799  8275 D bt_vendor: op for 5
,08-04 10:46:20.817  7799  8275 D bt_vendor: op for 0
08-04 10:46:20.817  7799  8275 D bt_upio : upio_set_bluetooth_power(on: 0)
08-04 10:46:20.817  7799  8275 D bt_upio : is_emulator_context : 0
08-04 10:46:20.817  7799  8275 D bt_upio : is_rfkill_disabled ? [0]
,08-04 10:46:20.817  7799  8275 D bt_upio : is_rfkill_disabled ? [0]
,08-04 10:46:20.817  7799  8275 D bt_vendor: op for 0
08-04 10:46:20.817  7799  8275 D bt_upio : upio_set_bluetooth_power(on: 1)
08-04 10:46:20.817  7799  8275 D bt_upio : is_emulator_context : 0
08-04 10:46:20.817  7799  8275 D bt_upio : is_rfkill_disabled ? [0]
,08-04 10:46:20.817  7799  8312 D bt_vendor: op for 3
08-04 10:46:20.817  7799  8312 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-04 10:46:20.817  7799  8312 I bt_userial_vendor: userial_vendor_open():UART is setup
08-04 10:46:20.817  7799  8312 I bt_userial_vendor: device fd = 66 open
,08-04 10:46:20.827  7799  8312 D bt_vendor: op for 1
08-04 10:46:20.827  7799  8312 E bt_hwcfg: Start CFG HW, HCI reset
08-04 10:46:20.827  7799  8314 D bt_userial: Entering userial_read_thread()
,08-04 10:46:20.897  7799  8312 E bt_hwcfg: Read Local Name after HCI reset
,08-04 10:46:20.927  7799  8312 D bt_hwcfg: Chipset BCM4335C0
08-04 10:46:20.927  7799  8312 D bt_hwcfg: Target name = [BCM4335C0]
,08-04 10:46:20.927  7799  8312 I bt_hwcfg: module_type[semco].
08-04 10:46:20.927  7799  8312 I bt_hwcfg: not ZERO...
08-04 10:46:20.927  7799  8312 I bt_hwcfg: module_type[semco] is invalid.
,08-04 10:46:20.927  7799  8312 E bt_hwcfg: patchram path ORG . BCM4335C0
08-04 10:46:20.927  7799  8312 E bt_hwcfg: patchram path ORG .. BCM4335C0
08-04 10:46:20.927  7799  8312 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
08-04 10:46:20.927  7799  8312 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
08-04 10:46:20.927  7799  8312 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
08-04 10:46:20.927  7799  8312 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
08-04 10:46:20.927  7799  8312 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335C0
08-04 10:46:20.927  7799  8312 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559_wisol.hcd BCM4335C0
08-04 10:46:20.927  7799  8312 E bt_hwcfg: fw ver (org)0.0
08-04 10:46:20.927  7799  8312 E bt_hwcfg: vendor lib preload failed to locate firmware patch file
08-04 10:46:20.927  7799  8312 E bt_hwcfg: Remove module rev, try again BCM4335
08-04 10:46:20.927  7799  8312 D bt_hwcfg: Target name = [BCM4335]
,08-04 10:46:20.927  7799  8312 I bt_hwcfg: module_type[semco].
08-04 10:46:20.927  7799  8312 I bt_hwcfg: not ZERO...
08-04 10:46:20.927  7799  8312 I bt_hwcfg: module_type[semco] is invalid.
08-04 10:46:20.927  7799  8312 E bt_hwcfg: patchram path ORG . BCM4335
08-04 10:46:20.927  7799  8312 E bt_hwcfg: patchram path ORG .. BCM4335
08-04 10:46:20.927  7799  8312 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335
08-04 10:46:20.927  7799  8312 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
08-04 10:46:20.927  7799  8312 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335
08-04 10:46:20.927  7799  8312 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
08-04 10:46:20.927  7799  8312 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335
08-04 10:46:20.927  7799  8312 I bt_hwcfg: patch(org) : bcm4335_V0111.0559.hcd
08-04 10:46:20.927  7799  8312 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4335_V0111.0559.hcd
08-04 10:46:20.927  7799  8312 E bt_hwcfg: ORG patchram base 0111
08-04 10:46:20.927  7799  8312 E bt_hwcfg: ORG patchram minor 0559
08-04 10:46:20.927  7799  8312 E bt_hwcfg: fw ver (org)111.559
08-04 10:46:20.927  7799  8312 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4335_V0111.0559.hcd
,08-04 10:46:20.947  7799  8312 I bt_hwcfg: Axi patch failure or not include AXI patching
,08-04 10:46:20.947  7799  8312 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 10:46:20.987   746   915 W ProcessCpuTracker: Skipping unknown process pid 8289
,08-04 10:46:20.987   746   915 W ProcessCpuTracker: Skipping unknown process pid 8292
,08-04 10:46:21.367  7799  8312 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-04 10:46:21.367  7799  8312 I bt_hwcfg: FW Download delta = 472756
08-04 10:46:21.367  7799  8312 D bt_hwcfg: Settlement delay -- 100 ms
08-04 10:46:21.367  7799  8312 I bt_hwcfg: Setting fw settlement delay to 100 
,08-04 10:46:21.477  7799  8312 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 10:46:21.517  7799  8312 I bt_hwcfg: vendor lib fwcfg completed
,08-04 10:46:21.517  7799  8310 I         : BTE_InitTraceLevels -- TRC_HCI
,08-04 10:46:21.517  7799  8310 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-04 10:46:21.517  7799  8310 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-04 10:46:21.517  7799  8310 I         : BTE_InitTraceLevels -- TRC_AVDT
08-04 10:46:21.517  7799  8310 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-04 10:46:21.517  7799  8310 I         : BTE_InitTraceLevels -- TRC_A2D
08-04 10:46:21.517  7799  8310 I         : BTE_InitTraceLevels -- TRC_BNEP
08-04 10:46:21.517  7799  8310 I         : BTE_InitTraceLevels -- TRC_BTM
08-04 10:46:21.517  7799  8310 I         : BTE_InitTraceLevels -- TRC_GAP
08-04 10:46:21.517  7799  8310 I         : BTE_InitTraceLevels -- TRC_PAN
,08-04 10:46:21.517  7799  8310 I         : BTE_InitTraceLevels -- TRC_SAP
08-04 10:46:21.517  7799  8310 I         : BTE_InitTraceLevels -- TRC_SDP
08-04 10:46:21.517  7799  8310 I         : BTE_InitTraceLevels -- TRC_GATT
08-04 10:46:21.517  7799  8310 I         : BTE_InitTraceLevels -- TRC_SMP
08-04 10:46:21.517  7799  8310 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-04 10:46:21.517  7799  8310 I         : BTE_InitTraceLevels -- TRC_BTIF
08-04 10:46:21.517  7799  8310 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-04 10:46:21.727  7799  8310 W bt-l2cap: l2c_link_processs_ble_num_bufs 15
,08-04 10:46:21.727  7799  8310 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa19ddb5d 
,08-04 10:46:21.727  7799  8310 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa19ddb5d 
,08-04 10:46:21.947  7799  8278 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 1 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
,08-04 10:46:21.947  7799  8278 E bt-btif : Calling BTA_HhEnable
,08-04 10:46:21.957  7799  8278 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-04 10:46:21.957  7799  8278 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
08-04 10:46:21.957  7799  8278 E BluetoothServiceJni: populateRssiValuesNative
08-04 10:46:21.957  7799  8278 I bluedroid: getModelRssiValues
,08-04 10:46:21.957  7799  8278 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-04 10:46:21.957  7799  8278 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-04 10:46:21.957   746   746 D SettingsProvider: name = bluetooth_name
,08-04 10:46:21.957  7799  8278 D BluetoothAdapterProperties: Name is: Note3-1
,08-04 10:46:21.957  7799  8278 D BluetoothAdapterProperties: Scan Mode:20
,08-04 10:46:21.957  7799  8278 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-04 10:46:21.957  7799  8278 D BluetoothAdapterProperties: LE Address is:E0:B7:20:3E:93:BC
08-04 10:46:21.957  7799  8278 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
,08-04 10:46:21.957  7799  8278 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-04 10:46:21.957  7799  8278 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-04 10:46:21.957  7799  8278 E bt-btif : btif_sock_init: !vhci_init
,08-04 10:46:21.957  7799  8278 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-04 10:46:21.957  7799  8312 D bt_vendor: op for 2
,08-04 10:46:21.957  7799  8278 D IOP_DB_BT: db_open: db_open : handle 3026722832l, read 14063 bytes onto local cache
08-04 10:46:21.957  7799  8312 D bt_vendor: op for 6
,08-04 10:46:21.967  7799  8278 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-04 10:46:21.967  7799  8278 D IOP_DB_BT: db_query: result 1
,08-04 10:46:21.967  7799  8312 D bt_vendor: op for 7
,08-04 10:46:21.967  7799  8278 I         : iop_db_open: iop_db_open status 0
08-04 10:46:21.967  7799  8278 D bte_conf: Device ID record 1 : primary
,08-04 10:46:21.967  7799  8312 D bt_upio : proc btwrite assertion
,08-04 10:46:21.967  7799  8278 D bte_conf:   vendorId            = 0075
08-04 10:46:21.967  7799  8278 D bte_conf:   vendorIdSource      = 0001
,08-04 10:46:21.967  7799  8312 D bt_vendor: op for 7
08-04 10:46:21.967  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:21.967  7799  8278 D bte_conf:   product             = 0100
08-04 10:46:21.967  7799  8278 D bte_conf:   version             = 0200
08-04 10:46:21.967  7799  8278 D bte_conf:   clientExecutableURL = 
,08-04 10:46:21.967  7799  8312 D bt_vendor: op for 7
08-04 10:46:21.967  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:21.967  7799  8278 D bte_conf:   serviceDescription  = 
,08-04 10:46:21.967  7799  8278 D bte_conf:   documentationURL    = 
08-04 10:46:21.967  7799  8278 D bte_conf: bte_load_did_conf no section named DID2.
,08-04 10:46:21.967  7799  8275 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-04 10:46:21.967  7799  8275 D BluetoothAdapterProperties: ScanMode =  20
08-04 10:46:21.977  7799  8275 D BluetoothAdapterProperties: State =  11
,08-04 10:46:21.977  7799  8278 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-04 10:46:21.977   746  1718 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-04 10:46:21.977  7799  8275 D BluetoothAdapterProperties: Setting state to 12
,08-04 10:46:21.977  7799  8275 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-04 10:46:21.977   746  1444 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-04 10:46:21.977   746  1444 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:21.977   746  1444 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:21.977   746  1444 D SettingsProvider: selectionArgs: false
,08-04 10:46:21.977   746  1444 D SettingsProvider: selectionArgs: 1002
08-04 10:46:21.977   746  1444 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:21.977   746  1444 D SettingsProvider: ret = -1
,08-04 10:46:21.977  7799  8275 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-04 10:46:21.977  7799  8275 D BluetoothAdapterService: updateAdapterState state is 12
,08-04 10:46:21.977   746  1459 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:21.987   746  1459 D ActivityManager: caller:android.app.ApplicationThreadProxy@2d6f7923, r.packageName :com.android.bluetooth
,08-04 10:46:21.987  7799  8312 D bt_vendor: op for 7
,08-04 10:46:21.987  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:21.987  7799  8312 E bt_h4   : vendor lib postload completed
08-04 10:46:21.987  7799  8312 D bt_vendor: op for 7
,08-04 10:46:21.987  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:21.997  7799  8312 D bt_vendor: op for 7
,08-04 10:46:21.997  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:21.997  7799  8312 D bt_vendor: op for 7
,08-04 10:46:21.997  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:21.997  7799  8312 D bt_vendor: op for 7
,08-04 10:46:21.997  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:21.997  7799  8312 D bt_vendor: op for 7
08-04 10:46:21.997  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:21.997  7799  8312 D bt_vendor: op for 7
,08-04 10:46:21.997  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:21.997  7799  8278 D BluetoothAdapterProperties: Scan Mode:21
,08-04 10:46:22.007  7799  8278 D BluetoothAdapterProperties: Discoverable Timeout:120
08-04 10:46:22.007  7799  8312 D bt_vendor: op for 7
,08-04 10:46:22.007  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:22.007  7799  8312 D bt_vendor: op for 7
,08-04 10:46:22.007  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:22.007  7799  8312 D bt_vendor: op for 7
,08-04 10:46:22.007  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:22.007   746  1028 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 10:46:22.007  7799  8312 D bt_vendor: op for 7
08-04 10:46:22.007  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:22.007  7799  8312 D bt_vendor: op for 7
,08-04 10:46:22.007  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:22.007  7799  8275 D BluetoothAdapterService: Autoconnection is available 
08-04 10:46:22.007  7799  8275 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
,08-04 10:46:22.007  7799  8275 D BluetoothAdapterService: starting service from this receiver
,08-04 10:46:22.007  7799  8312 D bt_vendor: op for 7
08-04 10:46:22.007  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:22.017  7799  8312 D bt_vendor: op for 7
,08-04 10:46:22.017  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:22.017  7799  8312 D bt_vendor: op for 7
,08-04 10:46:22.017  7799  8312 D bt_upio : BT_WAKE is asserted already
08-04 10:46:22.017  7799  7799 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-04 10:46:22.017  7799  8312 D bt_vendor: op for 7
08-04 10:46:22.017  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:22.017   746  1028 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-04 10:46:22.017  7799  8312 D bt_vendor: op for 7
08-04 10:46:22.017  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:22.017  7799  7799 I BluetoothPbapService: Handler(): got msg=1
,08-04 10:46:22.017   746  1426 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-04 10:46:22.027   746  1366 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:22.027   746  1366 D ActivityManager: caller:android.app.ApplicationThreadProxy@8b6847f, r.packageName :com.android.bluetooth
,08-04 10:46:22.027   746   746 D BluetoothA2dp: Proxy object connected
,08-04 10:46:22.027  7799  8312 D bt_vendor: op for 7
,08-04 10:46:22.027  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:22.037  1320  1347 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 10:46:22.037  7799  8275 I BluetoothAdapterState: Entering On State from state = 11
,08-04 10:46:22.037  7799  8312 D bt_vendor: op for 7
,08-04 10:46:22.037  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:22.037  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:22.037  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:22.037  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:22.037  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:46:22.037  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:22.037  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:22.037  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:22.037  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:46:22.037  7799  8312 D bt_vendor: op for 7
08-04 10:46:22.037  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:22.037  7799  8312 D bt_vendor: op for 7
,08-04 10:46:22.037  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:22.037  7799  8312 D bt_vendor: op for 7
,08-04 10:46:22.037  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:22.047  7799  8312 D bt_vendor: op for 7
,08-04 10:46:22.047  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:22.047  7799  8312 D bt_vendor: op for 7
,08-04 10:46:22.047  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:22.047  7799  8312 D bt_vendor: op for 7
08-04 10:46:22.047  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:22.047  7553  7553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:46:22.047  7799  8312 D bt_vendor: op for 7
08-04 10:46:22.047  7799  8312 D bt_upio : BT_WAKE is asserted already
08-04 10:46:22.047  7799  8327 V BluetoothPbapService: PBAP Service initSocket try: 0
,08-04 10:46:22.047   746  1028 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
08-04 10:46:22.047  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:22.047  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:22.047  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:22.047  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:46:22.047  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:22.047  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:22.047  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:22.047  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:46:22.047  7553  7553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:46:22.047  7799  8327 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 10:46:22.057   746  1028 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
08-04 10:46:22.057  1320  1320 D BluetoothA2dp: Proxy object connected
,08-04 10:46:22.057  7799  8327 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[73]}
08-04 10:46:22.057  7799  8327 D BluetoothSocket: bindListen(), new LocalSocket 
08-04 10:46:22.057  7799  8327 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-04 10:46:22.057  7799  8312 D bt_vendor: op for 7
08-04 10:46:22.057  7799  8312 D bt_upio : BT_WAKE is asserted already
08-04 10:46:22.057  7799  8327 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@5d9f02
08-04 10:46:22.057  7799  8327 D BluetoothSocket: channel: 19
08-04 10:46:22.057  7799  8327 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,08-04 10:46:22.057  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:22.057  1402  1587 E BluetoothHeadset: BluetoothHeadset service is binded
08-04 10:46:22.057  1320  1320 D A2dpProfile: Bluetooth service connected
,08-04 10:46:22.057  1320  1386 D BluetoothPan: Binding service...
,08-04 10:46:22.057  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:22.057   746  1028 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-04 10:46:22.057  1320  1365 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-04 10:46:22.057   746  1028 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-04 10:46:22.057  1320  1386 D Bluetoothsap: onBluetoothStateChange: up=true
,08-04 10:46:22.057  1320  1386 D Bluetoothsap: Binding service...
,08-04 10:46:22.057  1320  1386 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
08-04 10:46:22.057  1320  1320 D BluetoothPan: BluetoothPAN Proxy object connected
08-04 10:46:22.057  1320  1320 D PanProfile: Bluetooth service connected
,08-04 10:46:22.057   746  1028 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-04 10:46:22.057  1320  1386 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-04 10:46:22.067  1320  1320 D BluetoothInputDevice: Proxy object connected
08-04 10:46:22.067  1320  1320 D HidProfile: Bluetooth service connected
,08-04 10:46:22.067   746  1028 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 10:46:22.067  1320  1320 D Bluetoothsap: BluetoothSAP Proxy object connected
08-04 10:46:22.067  1320  1320 D SapProfile: Bluetooth service connected
08-04 10:46:22.067  1320  1320 D Bluetoothsap: getConnectedDevices()
08-04 10:46:22.067  1356  3302 E BluetoothHeadset: BluetoothHeadset service is binded
,08-04 10:46:22.067   746  1028 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 10:46:22.067  1320  1320 D HeadsetProfile: Bluetooth service connected
,08-04 10:46:22.067  1320  1347 E BluetoothHeadset: BluetoothHeadset service is binded
,08-04 10:46:22.067   746  1028 D BluetoothPan: Binding service...
,08-04 10:46:22.067   746  1028 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-04 10:46:22.067   746   746 D BluetoothPan: BluetoothPAN Proxy object connected
,08-04 10:46:22.067   746  1028 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 10:46:22.067  1356  1387 E BluetoothHeadset: BluetoothHeadset service is binded
,08-04 10:46:22.067  1320  1365 D BluetoothMap: onBluetoothStateChange: up=true
,08-04 10:46:22.067   746  1028 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-04 10:46:22.067  1320  1386 D BluetoothPbap: onBluetoothStateChange: up=true
,08-04 10:46:22.077  1320  1320 D BluetoothMap: Proxy object connected
08-04 10:46:22.077  1320  1320 D MapProfile: Bluetooth service connected
,08-04 10:46:22.077   746  1028 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-04 10:46:22.077  1320  1320 D BluetoothPbap: Proxy object connected
,08-04 10:46:22.077   746  1028 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 10:46:22.077  3420  3429 E BluetoothHeadset: BluetoothHeadset service is binded
08-04 10:46:22.077  1320  1320 D PbapServerProfile: Bluetooth service connected
08-04 10:46:22.077  7799  7812 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 10:46:22.077   746  1028 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 10:46:22.077   746  1028 E BluetoothHeadset: BluetoothHeadset service is binded
,08-04 10:46:22.077   746  1028 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 10:46:22.077  1356  1395 E BluetoothHeadset: BluetoothHeadset service is binded
08-04 10:46:22.077  3420  3429 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 10:46:22.087   746  1028 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-04 10:46:22.087  3420  3420 D BluetoothA2dp: Proxy object connected
,08-04 10:46:22.087   746  1028 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-04 10:46:22.087   746   746 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:22.087   746   746 I InputMethodManagerService: [BT Setting State] State =12
08-04 10:46:22.087   746   746 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-04 10:46:22.087   746  1028 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-04 10:46:22.087  1356  1356 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2a778a87, true
,08-04 10:46:22.087  1190  1190 D BluetoothTile:  onBluetoothStateChange:
,08-04 10:46:22.087  1356  1356 D BluetoothHeadset: registerMessageListener
08-04 10:46:22.087  1688  1688 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-04 10:46:22.087  7727  7727 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,08-04 10:46:22.087  1190  1190 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-04 10:46:22.097  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:22.097  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:22.097  7799  8294 D HeadsetService: registerMessageListener
08-04 10:46:22.097  1190  1190 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-04 10:46:22.097  7799  8294 D HeadsetService: registerMessageListener
08-04 10:46:22.097  7799  8303 D HeadsetStateMachine: Disconnected process message: 70
08-04 10:46:22.097   746  1297 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-04 10:46:22.097   746  1297 D ActivityManager: caller:android.app.ApplicationThreadProxy@1c9a05b0, r.packageName :com.google.android.gms
08-04 10:46:22.097  7799  8303 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@2bdb8013
08-04 10:46:22.097  1320  1320 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-04 10:46:22.097  1356  1356 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-04 10:46:22.097  1356  1356 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-04 10:46:22.097   746  1401 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,08-04 10:46:22.097   746   764 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
08-04 10:46:22.097  1190  1190 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,08-04 10:46:22.097  7799  8303 D HeadsetStateMachine: Disconnected process message: 9
,08-04 10:46:22.097  1320  1320 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-04 10:46:22.097  1320  1320 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
08-04 10:46:22.097  7799  8303 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-04 10:46:22.107  1190  1602 D BluetoothTile:  handleUpdatestate:false name:null
08-04 10:46:22.107  1190  1602 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-04 10:46:22.107  7799  8345 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-04 10:46:22.107   325   747 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-04 10:46:22.107   325   747 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-04 10:46:22.107   325   747 V voice   : voice_set_parameters: exit with code(-2)
08-04 10:46:22.107   325   747 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-04 10:46:22.107   325   747 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-04 10:46:22.107   325   747 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-04 10:46:22.107   325   747 V audio_hw_primary: adev_set_parameters: exit
,08-04 10:46:22.107  7799  8303 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-04 10:46:22.107  7799  8345 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 10:46:22.107  7799  8345 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
,08-04 10:46:22.117  7799  8345 D BluetoothSocket: bindListen(), new LocalSocket 
08-04 10:46:22.117  7799  8312 D bt_vendor: op for 7
08-04 10:46:22.117  7799  8312 D bt_upio : BT_WAKE is asserted already
08-04 10:46:22.117  7799  8345 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-04 10:46:22.117  7799  8345 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f2d8250
,08-04 10:46:22.117  7799  8345 D BluetoothSocket: channel: 5
,08-04 10:46:22.117  1320  1320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 10:46:22.117   746  1471 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-04 10:46:22.117   746  1471 D ActivityManager: caller:android.app.ApplicationThreadProxy@3076d4f, r.packageName :com.android.settings
,08-04 10:46:22.127  1320  1320 D DockEventReceiver: finishStartingService: stopping service
,08-04 10:46:22.127  1320  1320 D BluetoothNotiBroadcastReceiver: onReceive
,08-04 10:46:22.127  7799  7799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbb25c1
08-04 10:46:22.127  7799  7799 D BtConfig.SecureMode: isSecureModeOn:false
,08-04 10:46:22.127   746  1459 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:22.127   746  1459 D ActivityManager: caller:android.app.ApplicationThreadProxy@13a771e5, r.packageName :com.android.bluetooth
,08-04 10:46:22.137  1942  1942 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-04 10:46:22.137   746  1366 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-04 10:46:22.137   746  1366 D ActivityManager: caller:android.app.ApplicationThreadProxy@3af78f6b, r.packageName :com.google.android.gms
,08-04 10:46:22.147  1942  8351 D EasyUnlockInitService: Handling intent for initializer IntentService.
08-04 10:46:22.147  1942  1942 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-04 10:46:22.147   746  1444 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-04 10:46:22.157  7799  8355 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 10:46:22.157  7799  8355 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[79]}
08-04 10:46:22.157  7799  8355 D BluetoothSocket: bindListen(), new LocalSocket 
08-04 10:46:22.157  7799  8355 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-04 10:46:22.157  7799  8355 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39f0737c
08-04 10:46:22.157  7799  8312 D bt_vendor: op for 7
08-04 10:46:22.157  7799  8312 D bt_upio : BT_WAKE is asserted already
08-04 10:46:22.157  7799  8355 D BluetoothSocket: channel: 12
08-04 10:46:22.157  7799  8355 I BtOppRfcommListener: Accept thread started.
,08-04 10:46:22.157   746  1696 D ActivityManager: caller:android.app.ApplicationThreadProxy@215480e3, r.packageName :com.google.android.gms
,08-04 10:46:22.167  1942  8351 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-04 10:46:22.257   310   310 E SMD     : DCD ON
,08-04 10:46:23.527  7553  7621 D BluetoothAdapter: disable()
,08-04 10:46:23.527   746   762 D SettingsProvider: name = bluetooth_on
,08-04 10:46:23.557  7799  8275 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,08-04 10:46:23.557  7799  8275 D BluetoothAdapterProperties: Setting state to 13
08-04 10:46:23.557  7799  8275 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-04 10:46:23.557  7799  8275 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-04 10:46:23.557  7799  8275 D BluetoothAdapterService: updateAdapterState state is 13
,08-04 10:46:23.557   746  1297 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:23.557   746  1297 D ActivityManager: caller:android.app.ApplicationThreadProxy@2ab38199, r.packageName :com.android.bluetooth
,08-04 10:46:23.557  7799  7799 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,08-04 10:46:23.557  7799  8275 D BluetoothAdapterService: Autoconnection is available 
,08-04 10:46:23.567  7799  8275 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
08-04 10:46:23.567  7799  8275 D BluetoothAdapterService: terminating service from this receiver
,08-04 10:46:23.567  7799  7799 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@3c792405, channel: 19, state: LISTENING
,08-04 10:46:23.567  7799  7799 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@3c792405, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@5d9f02, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@96c0c5amSocket: android.net.LocalSocket@1660de8b impl:android.net.LocalSocketImpl@358f4b68 fd:FileDescriptor[73]
08-04 10:46:23.567  7799  7799 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1660de8b impl:android.net.LocalSocketImpl@358f4b68 fd:FileDescriptor[73]
,08-04 10:46:23.567  7799  8275 D BluetoothAdapterProperties: onBluetoothDisable()
,08-04 10:46:23.567   746  1145 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-04 10:46:23.567  7799  8275 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
,08-04 10:46:23.567  7799  8312 D bt_vendor: op for 7
,08-04 10:46:23.567  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:23.577  7799  8312 D bt_vendor: op for 7
,08-04 10:46:23.577  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:23.577  7799  8312 D bt_vendor: op for 7
,08-04 10:46:23.577  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:23.577  7799  8278 D BluetoothAdapterProperties: Scan Mode:20
,08-04 10:46:23.577  7799  8275 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,08-04 10:46:23.577  7799  8275 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,08-04 10:46:23.577  7799  8275 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,08-04 10:46:23.577  7799  8275 E bt-btif : cmd socket is not created
,08-04 10:46:23.587  7799  8275 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-04 10:46:23.587  7799  8310 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
08-04 10:46:23.587  7799  8312 D bt_vendor: op for 7
,08-04 10:46:23.587  7799  8312 D bt_upio : BT_WAKE is asserted already
08-04 10:46:23.587  7799  8310 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,08-04 10:46:23.587  7799  8310 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 10:46:23.587  7799  8310 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 10:46:23.587  7799  8310 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-04 10:46:23.587  7799  8312 D bt_vendor: op for 7
,08-04 10:46:23.587  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:23.587  7799  8312 D bt_vendor: op for 7
,08-04 10:46:23.587  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:23.587  7799  8312 D bt_vendor: op for 7
,08-04 10:46:23.587  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:23.587  7799  8355 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-04 10:46:23.597  7799  8312 D bt_vendor: op for 7
,08-04 10:46:23.597  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:23.597  7799  8312 D bt_vendor: op for 7
,08-04 10:46:23.597  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:23.597  7799  8312 D bt_vendor: op for 7
,08-04 10:46:23.597  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:23.597  7799  8312 D bt_vendor: op for 7
,08-04 10:46:23.597  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:23.597  7799  8312 D bt_vendor: op for 7
,08-04 10:46:23.597  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:23.597  7799  8312 D bt_vendor: op for 7
,08-04 10:46:23.597  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:23.597  7799  8312 D bt_vendor: op for 7
,08-04 10:46:23.597  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:23.607  7799  8312 D bt_vendor: op for 7
,08-04 10:46:23.607  7799  8312 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:23.607  7553  7553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 10:46:23.607  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:23.607  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:23.607  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:23.607  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:46:23.607  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:46:23.607  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:23.607  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:23.607  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:46:23.607  7553  7553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 10:46:23.607  7553  7553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:46:23.607  7553  7553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-04 10:46:23.607  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:23.607  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:23.607  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:23.607  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:46:23.607  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-04 10:46:23.607  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:23.607  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:23.607  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:46:23.607  7553  7553 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-04 10:46:23.607  7553  7553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:46:23.617   746   746 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-04 10:46:23.617  1190  1190 D BluetoothTile:  onBluetoothStateChange:
,08-04 10:46:23.617   746   746 I InputMethodManagerService: [BT Setting State] State =13
,08-04 10:46:23.617  7799  7799 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@6ce9426, channel: 5, state: LISTENING
,08-04 10:46:23.617  7799  7799 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@6ce9426, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2f2d8250, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@127cd867mSocket: android.net.LocalSocket@2fc1b614 impl:android.net.LocalSocketImpl@26ccebd fd:FileDescriptor[75]
08-04 10:46:23.617  7799  7799 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@2fc1b614 impl:android.net.LocalSocketImpl@26ccebd fd:FileDescriptor[75]
,08-04 10:46:23.617  7799  7799 I BtOppRfcommListener: stopping Accept Thread
,08-04 10:46:23.617  7799  7799 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@127fccb2, channel: 12, state: LISTENING
08-04 10:46:23.617  7799  7799 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@127fccb2, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39f0737c, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@14749403mSocket: android.net.LocalSocket@380e1f80 impl:android.net.LocalSocketImpl@89c99b9 fd:FileDescriptor[79]
08-04 10:46:23.617  7799  7799 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@380e1f80 impl:android.net.LocalSocketImpl@89c99b9 fd:FileDescriptor[79]
,08-04 10:46:23.617  7799  8355 I BtOppRfcommListener: BluetoothSocket listen thread finished
,08-04 10:46:23.627  1190  1190 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,08-04 10:46:23.627  1190  1190 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-04 10:46:23.627  1190  1602 D BluetoothTile:  handleUpdatestate:false name:null
,08-04 10:46:23.627  1190  1602 D BluetoothTile:  handleUpdatestate:false name:null
,08-04 10:46:23.627  1190  1602 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-04 10:46:23.627   746  1471 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,08-04 10:46:23.627   746  1696 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-04 10:46:23.627  1190  1190 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,08-04 10:46:23.627  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:23.637  7727  7727 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,08-04 10:46:23.637  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:23.637  1688  1688 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-04 10:46:23.637  1320  1320 D BluetoothPbap: Proxy object disconnected
,08-04 10:46:23.637   746  1435 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-04 10:46:23.637   746  1435 D ActivityManager: caller:android.app.ApplicationThreadProxy@3540fc5e, r.packageName :com.google.android.gms
,08-04 10:46:23.647  1320  1320 D PbapServerProfile: Bluetooth service disconnected
,08-04 10:46:23.647  1320  1320 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-04 10:46:23.647  1320  1320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 10:46:23.647   746  1459 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-04 10:46:23.647   746  1459 D ActivityManager: caller:android.app.ApplicationThreadProxy@32d0250c, r.packageName :com.android.settings
,08-04 10:46:23.667  1320  1320 D DockEventReceiver: finishStartingService: stopping service
,08-04 10:46:23.667  1320  1320 D BluetoothNotiBroadcastReceiver: onReceive
,08-04 10:46:23.677  1942  1942 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-04 10:46:23.677  1942  1942 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-04 10:46:23.717  7799  8312 D bt_vendor: op for 6
08-04 10:46:23.717  7799  8314 D bt_userial: RX termination
08-04 10:46:23.717  7799  8314 W bt_userial: select_read return size <=0:-1, exiting userial_read_thread
08-04 10:46:23.717  7799  8314 D bt_userial: Leaving userial_read_thread()
08-04 10:46:23.717  7799  8312 D bt_vendor: op for 7
08-04 10:46:23.717  7799  8312 D bt_upio : BT_WAKE is asserted already
08-04 10:46:23.717  7799  8310 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 10:46:23.717  7799  8310 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 10:46:23.717  7799  8310 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 10:46:23.717  7799  8310 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 10:46:23.717  7799  8310 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 10:46:23.717  7799  8310 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 10:46:23.717  7799  8310 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-04 10:46:23.717  7799  8310 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-04 10:46:23.717  7799  8310 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-04 10:46:23.717  7799  8310 W bt-btif : ag scb idx 1 not allocated
08-04 10:46:23.717  7799  8310 W bt-btif : ag scb idx 2 not allocated
08-04 10:46:23.717  7799  8310 E bt-btif : BTA AG is already disabled, ignoring ...
08-04 10:46:23.717  7799  8278 D bt_userial: userial_close_reader Joined userial reader thread: 0
08-04 10:46:23.717  7799  8312 D bt_vendor: op for 9
08-04 10:46:23.717  7799  8312 D bt_hwcfg: hw_epilog_process
08-04 10:46:23.717  7799  8278 D bt_vendor: op for 4
08-04 10:46:23.717  7799  8278 I bt_userial_vendor: device fd = 66 close
,08-04 10:46:23.717  7799  8278 D bt_vendor: op for 0
,08-04 10:46:23.717  7799  8278 D bt_upio : upio_set_bluetooth_power(on: 0)
08-04 10:46:23.717  7799  8278 D bt_upio : is_emulator_context : 0
08-04 10:46:23.717  7799  8278 D bt_upio : is_rfkill_disabled ? [0]
,08-04 10:46:23.717  7799  8278 D bt_vendor: cleanup
,08-04 10:46:23.717  7799  8310 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
,08-04 10:46:23.717  7799  8278 I GKI_LINUX: GKI_exit_task 0 done
08-04 10:46:23.717  7799  8278 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,08-04 10:46:23.717  7799  8275 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-04 10:46:23.717  7799  8275 D BtConfig.SecureMode: isSecureModeOn:false
08-04 10:46:23.717  7799  8275 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
08-04 10:46:23.717  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-04 10:46:23.717  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
08-04 10:46:23.717  7799  8275 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-04 10:46:23.727   746  1461 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:23.727   746  1461 D ActivityManager: caller:android.app.ApplicationThreadProxy@2b1c806a, r.packageName :com.android.bluetooth
,08-04 10:46:23.727  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-04 10:46:23.727  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-04 10:46:23.727  7799  8275 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
08-04 10:46:23.727   746   762 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 10:46:23.727   746   762 D ActivityManager: caller:android.app.ApplicationThreadProxy@63f295b, r.packageName :com.android.bluetooth
,08-04 10:46:23.727  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
08-04 10:46:23.727  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
,08-04 10:46:23.727  7799  8275 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-04 10:46:23.727  7799  7799 D BtGatt.DebugUtils: handleDebugAction() action=null
08-04 10:46:23.727   746  1145 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 10:46:23.727   746  1145 D ActivityManager: caller:android.app.ApplicationThreadProxy@3ee085f8, r.packageName :com.android.bluetooth
,08-04 10:46:23.727  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
08-04 10:46:23.727  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-04 10:46:23.727  7799  8275 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
,08-04 10:46:23.727   746  1401 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 10:46:23.727  7799  7799 D BtGatt.GattService: Received stop request...Stopping profile...
08-04 10:46:23.727   746  1401 D ActivityManager: caller:android.app.ApplicationThreadProxy@43acad1, r.packageName :com.android.bluetooth
,08-04 10:46:23.727  7799  7799 D BtGatt.GattService: stop()
08-04 10:46:23.727  7799  7799 D BtGatt.AdvertiseManager: advertise clients cleared
08-04 10:46:23.727  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-04 10:46:23.727  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-04 10:46:23.727  7799  8275 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-04 10:46:23.727   746  1444 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:23.727   746  1444 D ActivityManager: caller:android.app.ApplicationThreadProxy@257a3936, r.packageName :com.android.bluetooth
08-04 10:46:23.727  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,08-04 10:46:23.727  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-04 10:46:23.727  7799  8275 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-04 10:46:23.727  7799  7799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbb25c1
,08-04 10:46:23.727   746  1696 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 10:46:23.727   746  1696 D ActivityManager: caller:android.app.ApplicationThreadProxy@283d0037, r.packageName :com.android.bluetooth
,08-04 10:46:23.727  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
08-04 10:46:23.727  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-04 10:46:23.727  7799  8275 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,08-04 10:46:23.727  7799  7799 D HeadsetService: Received stop request...Stopping profile...
,08-04 10:46:23.737   746   762 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:23.737   746   762 D ActivityManager: caller:android.app.ApplicationThreadProxy@199409a4, r.packageName :com.android.bluetooth
08-04 10:46:23.737  7799  7799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbb25c1
08-04 10:46:23.737  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-04 10:46:23.737  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-04 10:46:23.737  7799  8275 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-04 10:46:23.737   746  1401 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:23.737   746  1401 D ActivityManager: caller:android.app.ApplicationThreadProxy@17d0430d, r.packageName :com.android.bluetooth
,08-04 10:46:23.737   746   746 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-04 10:46:23.737  7799  7799 D A2dpService: Received stop request...Stopping profile...
08-04 10:46:23.737  7799  7799 V Avrcp   : doQuit
08-04 10:46:23.737  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-04 10:46:23.737  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,08-04 10:46:23.737  7799  8275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-04 10:46:23.737  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
08-04 10:46:23.737  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-04 10:46:23.737  7799  8275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-04 10:46:23.737  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-04 10:46:23.737  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
08-04 10:46:23.737  7799  8275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-04 10:46:23.737  7799  8275 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-04 10:46:23.737  7799  8275 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-04 10:46:23.737  7799  8275 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-04 10:46:23.737  7799  8275 D BluetoothAdapterState: Stopping profile services that were post enabled
08-04 10:46:23.737  7799  8305 D A2dpStateMachine: Exit Disconnected: -1
,08-04 10:46:23.737  7799  7799 D Avrcp   : Unregistering previous receiver
,08-04 10:46:23.737  7727  7727 W BluetoothHeadset: Proxy not attached to service
,08-04 10:46:23.737  1320  1320 D HeadsetProfile: Bluetooth service disconnected
,08-04 10:46:23.737  7799  7799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbb25c1
,08-04 10:46:23.737  1320  1320 D BluetoothA2dp: Proxy object disconnected
08-04 10:46:23.737  1320  1320 D A2dpProfile: Bluetooth service disconnected
,08-04 10:46:23.737   746   746 D BluetoothA2dp: Proxy object disconnected
08-04 10:46:23.737   746   746 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-04 10:46:23.737  3420  3420 D BluetoothA2dp: Proxy object disconnected
,08-04 10:46:23.737  7799  7799 D HidService: Received stop request...Stopping profile...
,08-04 10:46:23.737  7799  7799 D HidService: Stopping Bluetooth HidService
08-04 10:46:23.737  7799  7799 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-04 10:46:23.737  7799  7799 W bt-btif : cleanup: HH disabling or disabled already, status = 0
08-04 10:46:23.737  7799  7799 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-04 10:46:23.737  7799  7799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbb25c1
,08-04 10:46:23.747  7799  7799 D HealthService: Received stop request...Stopping profile...
,08-04 10:46:23.747  7799  7799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbb25c1
,08-04 10:46:23.747  7799  7799 E BluetoothAdapterService(532358593): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
08-04 10:46:23.747  1320  1320 D BluetoothInputDevice: Proxy object disconnected
08-04 10:46:23.747  1320  1320 D HidProfile: Bluetooth service disconnected
,08-04 10:46:23.747  7799  7799 D PanService: Received stop request...Stopping profile...
08-04 10:46:23.747  7799  7799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbb25c1
,08-04 10:46:23.747   746   746 D BluetoothPan: BluetoothPAN Proxy object disconnected
,08-04 10:46:23.747  1320  1320 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-04 10:46:23.747  1320  1320 D PanProfile: Bluetooth service disconnected
08-04 10:46:23.747  7799  7799 E BluetoothAdapterService(532358593): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
08-04 10:46:23.747  7799  7799 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,08-04 10:46:23.747  7799  7799 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-04 10:46:23.747  7799  7799 D BluetoothMapService: Received stop request...Stopping profile...
,08-04 10:46:23.747  7799  7799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbb25c1
,08-04 10:46:23.747  1320  1320 D BluetoothMap: Proxy object disconnected
08-04 10:46:23.747  1320  1320 D MapProfile: Bluetooth service disconnected
,08-04 10:46:23.757  7799  7799 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-04 10:46:23.757  7799  7799 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-04 10:46:23.757  7799  7799 D SapService: Received stop request...Stopping profile...
08-04 10:46:23.757  7799  7799 D SapService: Stopping Bluetooth SapService
08-04 10:46:23.757  7799  7799 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@1fbb25c1
,08-04 10:46:23.757  1320  1320 D Bluetoothsap: BluetoothSAP Proxy object disconnected
08-04 10:46:23.757  1320  1320 D SapProfile: Bluetooth service disconnected
08-04 10:46:23.757  7799  7799 E BluetoothAdapterService(532358593): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
08-04 10:46:23.757  7799  7799 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-04 10:46:23.757  7799  7799 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
08-04 10:46:23.757  7799  7799 D BluetoothA2dp: Proxy object disconnected
,08-04 10:46:23.757  7799  7799 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
08-04 10:46:23.757  7799  8306 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-04 10:46:23.757  7799  7799 I GKI_LINUX: GKI_exit_task 2 done
08-04 10:46:23.757  7799  7799 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-04 10:46:23.757  7799  7799 V Avrcp   : cleanup
,08-04 10:46:23.757  7799  7799 E BluetoothAdapterService(532358593): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
08-04 10:46:23.757  7799  7799 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-04 10:46:23.757  7799  7799 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-04 10:46:23.757  7799  7799 E BluetoothAdapterService(532358593): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
08-04 10:46:23.757  7799  7799 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-04 10:46:23.757  7799  7799 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-04 10:46:23.757  7799  7799 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-04 10:46:23.757  7799  7799 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-04 10:46:23.757  7799  7799 E BluetoothAdapterService(532358593): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
08-04 10:46:23.757  7799  7799 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-04 10:46:23.757  7799  7799 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
08-04 10:46:23.757  7799  7799 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-04 10:46:23.757  7799  7799 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-04 10:46:23.757  7799  7799 E BluetoothAdapterService(532358593): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
08-04 10:46:23.757  7799  7799 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
08-04 10:46:23.757  7799  7799 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,08-04 10:46:23.757  7799  7799 E BluetoothAdapterService(532358593): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
08-04 10:46:23.757  7799  8275 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
08-04 10:46:23.757  7799  7799 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
08-04 10:46:23.757  7799  7799 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
08-04 10:46:23.757  7799  8275 D BluetoothAdapterProperties: Setting state to 10
08-04 10:46:23.757  7799  8275 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-04 10:46:23.757  7799  8275 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-04 10:46:23.757  7799  8275 D BluetoothAdapterService: updateAdapterState state is 10
,08-04 10:46:23.757   746  1028 D BluetoothA2dp: onBluetoothStateChange: up=false
08-04 10:46:23.757  7799  8275 D BluetoothAdapterService: Autoconnection is available 
08-04 10:46:23.757  7799  8275 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
08-04 10:46:23.757  7799  8275 I BluetoothAdapterState: Entering OffState
,08-04 10:46:23.757  1320  1365 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-04 10:46:23.757  1320  1386 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-04 10:46:23.757  1320  1365 D Bluetoothsap: onBluetoothStateChange: up=false
08-04 10:46:23.757  1320  1365 D Bluetoothsap: Unbinding service...
,08-04 10:46:23.757  1320  1386 D BluetoothMap: onBluetoothStateChange: up=false
,08-04 10:46:23.767  1320  1365 D BluetoothPbap: onBluetoothStateChange: up=false
,08-04 10:46:23.767  7799  7808 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-04 10:46:23.767  3420  3429 D BluetoothA2dp: onBluetoothStateChange: up=false
,08-04 10:46:23.767   746  1028 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 14 receivers.
,08-04 10:46:23.767   746  1028 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,08-04 10:46:23.767   746   746 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-04 10:46:23.767   746   746 I InputMethodManagerService: [BT Setting State] State =10
08-04 10:46:23.767   746   746 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-04 10:46:23.767  1190  1190 D BluetoothAdapter: 616952615: getState() :  mService = null. Returning STATE_OFF
,08-04 10:46:23.767  1190  1190 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-04 10:46:23.767  1190  1602 D BluetoothAdapter: 616952615: getState() :  mService = null. Returning STATE_OFF
,08-04 10:46:23.777  1190  1190 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:23.777  1190  1190 D BluetoothAdapter: 616952615: getState() :  mService = null. Returning STATE_OFF
08-04 10:46:23.777  1688  1688 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
08-04 10:46:23.777  1320  1320 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:23.777  7799  8278 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-04 10:46:23.777  1190  1602 D BluetoothAdapter: 616952615: getState() :  mService = null. Returning STATE_OFF
08-04 10:46:23.777  1190  1602 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
08-04 10:46:23.777  7799  7799 I GKI_LINUX: GKI_exit_task 1 done
08-04 10:46:23.777  7799  7799 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-04 10:46:23.777  1190  1190 D BluetoothAdapter: 616952615: getState() :  mService = null. Returning STATE_OFF
,08-04 10:46:23.777  1942  2393 D BluetoothAdapter: 955132242: getState() :  mService = null. Returning STATE_OFF
08-04 10:46:23.777  1942  2393 D BluetoothAdapter: 955132242: getState() :  mService = null. Returning STATE_OFF
,08-04 10:46:23.777  7799  7799 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-04 10:46:23.777   746  1298 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,08-04 10:46:23.777  7727  7727 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:23.777   746  1297 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
08-04 10:46:23.777  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:23.777  1190  1190 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
08-04 10:46:23.777  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:23.777   746  1435 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-04 10:46:23.777  1320  1320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-04 10:46:23.777   746  1435 D ActivityManager: caller:android.app.ApplicationThreadProxy@128b2c2, r.packageName :com.google.android.gms
,08-04 10:46:23.777  7799  7799 I art     : System.exit called, status: 0
08-04 10:46:23.777  7799  7799 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-04 10:46:23.787   746  1471 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,08-04 10:46:23.787   746  1471 D ActivityManager: caller:android.app.ApplicationThreadProxy@2bda1c10, r.packageName :com.android.settings
,08-04 10:46:23.797  1320  1320 D DockEventReceiver: finishStartingService: stopping service
,08-04 10:46:23.797  1320  1320 D BluetoothNotiBroadcastReceiver: onReceive
,08-04 10:46:23.827   746  1471 I ActivityManager: Process com.android.bluetooth (pid 7799)(adj 0) has died(151,1602)
,08-04 10:46:23.827  1942  1942 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-04 10:46:23.837   746  1426 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-04 10:46:23.837   746  1426 D ActivityManager: caller:android.app.ApplicationThreadProxy@3c2ce93c, r.packageName :com.google.android.gms
,08-04 10:46:23.837  1942  8395 D EasyUnlockInitService: Handling intent for initializer IntentService.
,08-04 10:46:23.837  1942  1942 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-04 10:46:23.847   746  1471 D ActivityManager: caller:android.app.ApplicationThreadProxy@168dd81a, r.packageName :com.google.android.gms
,08-04 10:46:23.847  1942  8395 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,08-04 10:46:24.257   746  3345 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-04 10:46:25.267   310   310 E SMD     : DCD ON
,08-04 10:46:26.637  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
,08-04 10:46:26.637  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:26.658   746  3312 D SSRM:n  : SIOP:: AP = 350, PST = 361, CUR = 450
,08-04 10:46:28.267   310   310 E SMD     : DCD ON
,08-04 10:46:28.478   746  1297 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-04 10:46:28.478   746  1297 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 282, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
08-04 10:46:28.478   746  1297 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,08-04 10:46:28.478   746  1297 D BatteryService: stay LED for fully charged
08-04 10:46:28.478   746   746 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-04 10:46:28.488  1190  1190 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-04 10:46:28.488  1190  1190 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,08-04 10:46:28.488   746   746 I MotionRecognitionService: Plugged
08-04 10:46:28.488   746   746 I MotionRecognitionService: setPowerConnected  = true
,08-04 10:46:28.488  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-04 10:46:28.488  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-04 10:46:28.488  1190  1190 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-04 10:46:28.488  1190  1190 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-04 10:46:29.647  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 10:46:29.657  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1aab3f38 added. We now have 6 listener(s)
,08-04 10:46:29.657  7553  7621 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:46:29.657  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-04 10:46:29.657  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@257d2b11 added. We now have 7 listener(s)
08-04 10:46:29.657  7553  7621 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:46:29.657  7553  7621 I System.out: IsBluetoothEnabled
,08-04 10:46:29.657  7553  7621 D BluetoothAdapter: disable()
,08-04 10:46:29.657   746   764 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,08-04 10:46:29.667  7553  7621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:29.667  7553  7621 D BluetoothAdapter: enable()
,08-04 10:46:29.667   746  1455 W ActivityManager: Permission Denial: getCurrentUser() from pid=7553, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-04 10:46:29.667   746  1455 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
08-04 10:46:29.667   746  1455 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7553, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-04 10:46:29.667   746  1455 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
08-04 10:46:29.667   746  1455 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
08-04 10:46:29.667   746  1455 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
08-04 10:46:29.667   746  1455 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
08-04 10:46:29.667   746  1455 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
08-04 10:46:29.667   746  1455 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-04 10:46:29.667   746  1455 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-04 10:46:29.667   746  1455 D SettingsProvider: name = bluetooth_on
,08-04 10:46:29.677   746  1028 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-04 10:46:29.677   746  1028 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-04 10:46:29.677   746  1028 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,08-04 10:46:29.677   746  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:29.677   746  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:29.677   746  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:29.677   746  1028 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:29.727  8410  8410 E Zygote  : MountEmulatedStorage()
,08-04 10:46:29.727  8410  8410 E Zygote  : v2
,08-04 10:46:29.727  8410  8410 I libpersona: KNOX_SDCARD checking this for 1002
08-04 10:46:29.727  8410  8410 I libpersona: KNOX_SDCARD not a persona
,08-04 10:46:29.727   746  1028 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=8410 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,08-04 10:46:29.747  8410  8410 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-04 10:46:29.747  8410  8410 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 10:46:29.747  8410  8410 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 10:46:29.767   361   361 I art     : Explicit concurrent mark sweep GC freed 8719(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 302us total 30.782ms
,08-04 10:46:29.787   361   361 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 272us total 15.493ms
,08-04 10:46:29.797   361   361 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 270us total 10.844ms
,08-04 10:46:29.807  8410  8410 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:29.807  8410  8410 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:29.817  8410  8410 D ResourcesManager: creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,08-04 10:46:29.817  8410  8410 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-04 10:46:29.817  8410  8410 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-04 10:46:29.837  8410  8410 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,08-04 10:46:29.867  8410  8410 D BtSettings.ProfileConfig: Adding GattService
,08-04 10:46:29.867  8410  8410 D BtSettings.ProfileConfig: Adding HeadsetService
08-04 10:46:29.867  8410  8410 D BtSettings.ProfileConfig: Adding A2dpService
,08-04 10:46:29.867  8410  8410 D BtSettings.ProfileConfig: Adding HidService
08-04 10:46:29.867  8410  8410 D BtSettings.ProfileConfig: Adding HealthService
08-04 10:46:29.867  8410  8410 D BtSettings.ProfileConfig: Adding PanService
,08-04 10:46:29.867  8410  8410 D BtSettings.ProfileConfig: Adding BluetoothMapService
08-04 10:46:29.867  8410  8410 D BtSettings.ProfileConfig: Adding SapService
,08-04 10:46:29.867  8410  8410 D BtSettings.ProfileConfig: Adding HeadsetClientService
08-04 10:46:29.867  8410  8410 D BtSettings.ProfileConfig: Adding A2dpSinkService
08-04 10:46:29.867  8410  8410 D BtSettings.ProfileConfig: Adding SapClientService
08-04 10:46:29.867  8410  8410 D BtSettings.ProfileConfig: Adding HidDevService
08-04 10:46:29.867  8410  8410 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,08-04 10:46:29.867   746  1435 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,08-04 10:46:29.867   746  1435 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:29.867   746  1435 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:29.867   746  1435 D SettingsProvider: selectionArgs: false
08-04 10:46:29.867   746  1435 D SettingsProvider: selectionArgs: 1002
08-04 10:46:29.867   746  1435 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:29.867   746  1435 D SettingsProvider: ret = -1
,08-04 10:46:29.867   746  1298 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
08-04 10:46:29.867   746  1298 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:29.867   746  1298 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:29.867   746  1298 D SettingsProvider: selectionArgs: false
,08-04 10:46:29.867   746  1298 D SettingsProvider: selectionArgs: 1002
08-04 10:46:29.867   746  1298 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:29.867   746  1298 D SettingsProvider: ret = -1
,08-04 10:46:29.877   746  1366 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
08-04 10:46:29.877   746  1366 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:29.877   746  1366 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:29.877   746  1366 D SettingsProvider: selectionArgs: false
08-04 10:46:29.877   746  1366 D SettingsProvider: selectionArgs: 1002
08-04 10:46:29.877   746  1366 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-04 10:46:29.877   746  1366 D SettingsProvider: ret = -1
08-04 10:46:29.877   746  1297 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
08-04 10:46:29.877   746  1297 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:29.877   746  1297 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-04 10:46:29.877   746  1297 D SettingsProvider: selectionArgs: false
08-04 10:46:29.877   746  1297 D SettingsProvider: selectionArgs: 1002
08-04 10:46:29.877   746  1297 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:29.877   746  1297 D SettingsProvider: ret = -1
,08-04 10:46:29.877   746  1471 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
08-04 10:46:29.877   746  1471 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:29.877   746  1471 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:29.877   746  1471 D SettingsProvider: selectionArgs: false
08-04 10:46:29.877   746  1471 D SettingsProvider: selectionArgs: 1002
,08-04 10:46:29.877   746  1471 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:29.877   746  1471 D SettingsProvider: ret = -1
08-04 10:46:29.877   746  1696 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
08-04 10:46:29.877   746  1696 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:29.877   746  1696 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:29.877   746  1696 D SettingsProvider: selectionArgs: false
08-04 10:46:29.877   746  1696 D SettingsProvider: selectionArgs: 1002
08-04 10:46:29.877   746  1696 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:29.877   746  1696 D SettingsProvider: ret = -1
,08-04 10:46:29.877   746  1718 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
08-04 10:46:29.877   746  1718 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:29.877   746  1718 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:29.877   746  1718 D SettingsProvider: selectionArgs: false
08-04 10:46:29.877   746  1718 D SettingsProvider: selectionArgs: 1002
08-04 10:46:29.877   746  1718 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:29.877   746  1718 D SettingsProvider: ret = -1
,08-04 10:46:29.877   746   762 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
08-04 10:46:29.877   746   762 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:29.877   746   762 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:29.877   746   762 D SettingsProvider: selectionArgs: false
08-04 10:46:29.877   746   762 D SettingsProvider: selectionArgs: 1002
08-04 10:46:29.877   746   762 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:29.877   746   762 D SettingsProvider: ret = -1
,08-04 10:46:29.877   746  1145 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
08-04 10:46:29.877   746  1145 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:29.877   746  1145 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:29.877   746  1145 D SettingsProvider: selectionArgs: false
08-04 10:46:29.877   746  1145 D SettingsProvider: selectionArgs: 1002
08-04 10:46:29.877   746  1145 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:29.877   746  1145 D SettingsProvider: ret = -1
,08-04 10:46:29.877   746  1444 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
08-04 10:46:29.877   746  1444 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:29.877   746  1444 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:29.877   746  1444 D SettingsProvider: selectionArgs: false
08-04 10:46:29.877   746  1444 D SettingsProvider: selectionArgs: 1002
,08-04 10:46:29.877   746  1444 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:29.877   746  1444 D SettingsProvider: ret = -1
08-04 10:46:29.877   746  1426 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
08-04 10:46:29.877   746  1426 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:29.877   746  1426 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-04 10:46:29.877   746  1426 D SettingsProvider: selectionArgs: false
08-04 10:46:29.877   746  1426 D SettingsProvider: selectionArgs: 1002
08-04 10:46:29.877   746  1426 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:29.877   746  1426 D SettingsProvider: ret = -1
,08-04 10:46:29.877   746  1459 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
08-04 10:46:29.877   746  1459 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:29.877   746  1459 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:29.877   746  1459 D SettingsProvider: selectionArgs: false
,08-04 10:46:29.877   746  1459 D SettingsProvider: selectionArgs: 1002
08-04 10:46:29.877   746  1459 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
08-04 10:46:29.877   746  1459 D SettingsProvider: ret = -1
,08-04 10:46:29.897  8410  8410 D BluetoothAdapterState: make
,08-04 10:46:29.897  8410  8410 I bluedroid: init
,08-04 10:46:29.897  8410  8431 I BluetoothAdapterState: Entering OffState
,08-04 10:46:29.897  8410  8410 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,08-04 10:46:29.897  8410  8410 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-04 10:46:29.897  8410  8410 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-04 10:46:29.907  8410  8410 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,08-04 10:46:29.907  8410  8410 E bt-btif : btif_fetch_local_ble_random_bdaddr
08-04 10:46:29.907  8410  8410 I bluedroid: get_profile_interface socket
08-04 10:46:29.907  8410  8434 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-04 10:46:29.907  8410  8410 I bluedroid: get_profile_interface map_client
,08-04 10:46:29.907  8410  8410 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,08-04 10:46:29.907   746  1471 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-04 10:46:29.917  8410  8418 I bluedroid: config_hci_snoop_log
,08-04 10:46:29.917   746  1028 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 14 receivers.
08-04 10:46:29.917  8410  8434 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
,08-04 10:46:29.917  8410  8434 E BluetoothServiceJni: populateRssiValuesNative
08-04 10:46:29.917  8410  8434 I bluedroid: getModelRssiValues
08-04 10:46:29.917  8410  8434 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
08-04 10:46:29.917  8410  8434 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-04 10:46:29.917  8410  8434 D BluetoothAdapterProperties: Name is: Note3-1
,08-04 10:46:29.917   746   746 D SettingsProvider: name = bluetooth_name
,08-04 10:46:29.917   746  1028 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
08-04 10:46:29.917   746  1028 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,08-04 10:46:29.917   746  1028 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,08-04 10:46:29.917  8410  8431 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
08-04 10:46:29.917  8410  8431 D BluetoothAdapterProperties: Setting state to 11
,08-04 10:46:29.917  8410  8431 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-04 10:46:29.917  8410  8431 D BluetoothAdapterService: Bluetooth PBAP supproted is true
08-04 10:46:29.917  8410  8431 D BluetoothAdapterService: updateAdapterState state is 11
,08-04 10:46:29.917  8410  8431 D BluetoothAdapterService: Autoconnection is available 
08-04 10:46:29.917  8410  8431 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,08-04 10:46:29.927   746   746 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:29.927   746   746 I InputMethodManagerService: [BT Setting State] State =11
,08-04 10:46:29.927  8410  8431 D BluetoothSecureManager: getInstant: null
,08-04 10:46:29.927  8410  8431 D BluetoothSecureManager: calling getMethod for getService
08-04 10:46:29.927  8410  8431 D BluetoothSecureManager: calling getService
,08-04 10:46:29.927  1688  1688 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-04 10:46:29.927  1190  1190 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-04 10:46:29.927  1190  1190 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-04 10:46:29.927  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:29.927   746  1696 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,08-04 10:46:29.927  1320  1320 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:29.927   746  1444 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,08-04 10:46:29.927  1190  1190 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,08-04 10:46:29.937   746  1455 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-04 10:46:29.937  7727  7727 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:29.937   746  1455 D ActivityManager: caller:android.app.ApplicationThreadProxy@a3205b1, r.packageName :com.google.android.gms
08-04 10:46:29.937  1190  1602 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-04 10:46:29.937  8410  8431 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@3687b2c0
,08-04 10:46:29.937   746   764 D BluetoothSecureManagerService: isSecureModeEnabled
,08-04 10:46:29.937   746   764 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
08-04 10:46:29.937  8410  8431 D BtConfig.SecureMode: isSecureModeOn:false
08-04 10:46:29.937  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-04 10:46:29.937  8410  8431 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
08-04 10:46:29.937  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
,08-04 10:46:29.937  8410  8431 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
08-04 10:46:29.937  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-04 10:46:29.937  8410  8431 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,08-04 10:46:29.937  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-04 10:46:29.937  8410  8431 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
08-04 10:46:29.937  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,08-04 10:46:29.937  8410  8431 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
08-04 10:46:29.937  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
08-04 10:46:29.937  1320  1320 D BluetoothNotiBroadcastReceiver: onReceive
,08-04 10:46:29.937  8410  8431 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
08-04 10:46:29.937  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,08-04 10:46:29.947  8410  8431 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
08-04 10:46:29.947  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-04 10:46:29.947  8410  8431 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,08-04 10:46:29.947  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-04 10:46:29.947  8410  8431 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
08-04 10:46:29.947  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,08-04 10:46:29.947  8410  8431 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
08-04 10:46:29.947  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-04 10:46:29.947  8410  8431 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
08-04 10:46:29.947  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-04 10:46:29.947  8410  8431 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,08-04 10:46:29.947  8410  8431 D BluetoothBondStateMachine: make
,08-04 10:46:29.957  8410  8431 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
08-04 10:46:29.957  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,08-04 10:46:29.957  8410  8431 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,08-04 10:46:29.957   746  1444 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:29.957   746  1444 D ActivityManager: caller:android.app.ApplicationThreadProxy@15cee617, r.packageName :com.android.bluetooth
,08-04 10:46:29.957  1942  1942 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-04 10:46:29.957  8410  8410 I BtGatt.JNI: classInitNative(L890): classInitNative: Success!
,08-04 10:46:29.967  8410  8431 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
08-04 10:46:29.967  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
08-04 10:46:29.967  8410  8431 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,08-04 10:46:29.967   746  1145 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 10:46:29.967   746  1145 D ActivityManager: caller:android.app.ApplicationThreadProxy@4b04bed, r.packageName :com.android.bluetooth
,08-04 10:46:29.967  8410  8431 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,08-04 10:46:29.967  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
08-04 10:46:29.967  8410  8431 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
08-04 10:46:29.967   746  1426 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:29.967   746  1426 D ActivityManager: caller:android.app.ApplicationThreadProxy@33d1ccb3, r.packageName :com.android.bluetooth
,08-04 10:46:29.977  8410  8410 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-04 10:46:29.977  8410  8410 D BtGatt.GattService: Received start request. Starting profile...
08-04 10:46:29.977  8410  8410 D BtGatt.GattService: start()
08-04 10:46:29.977  8410  8410 I bluedroid: get_profile_interface gatt
,08-04 10:46:29.977  8410  8410 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2839eecb
,08-04 10:46:29.977  8410  8410 D BtGatt.AdvertiseManager: advertise manager created
08-04 10:46:29.977  1942  1942 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-04 10:46:29.977  8410  8431 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,08-04 10:46:29.977  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
08-04 10:46:29.977  8410  8431 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
08-04 10:46:29.977   746  1298 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 10:46:29.977   746  1298 D ActivityManager: caller:android.app.ApplicationThreadProxy@3952b9e9, r.packageName :com.android.bluetooth
,08-04 10:46:29.977  8410  8431 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
,08-04 10:46:29.977  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
08-04 10:46:29.977  8410  8431 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
08-04 10:46:29.977   746  1297 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:29.977   746  1297 D ActivityManager: caller:android.app.ApplicationThreadProxy@1212810f, r.packageName :com.android.bluetooth
,08-04 10:46:29.977  8410  8437 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-04 10:46:29.987  8410  8431 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
08-04 10:46:29.987  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,08-04 10:46:29.987  8410  8431 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
08-04 10:46:29.987   746  1461 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:29.987   746  1461 D ActivityManager: caller:android.app.ApplicationThreadProxy@28940ba5, r.packageName :com.android.bluetooth
,08-04 10:46:29.987  8410  8431 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,08-04 10:46:29.987  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
08-04 10:46:29.987  8410  8431 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
08-04 10:46:29.987   746  1471 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:29.987   746  1471 D ActivityManager: caller:android.app.ApplicationThreadProxy@25fcc546, r.packageName :com.android.bluetooth
,08-04 10:46:29.987  8410  8431 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
08-04 10:46:29.987  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,08-04 10:46:29.987  8410  8431 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
08-04 10:46:29.987   746  1718 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 10:46:29.987   746  1718 D ActivityManager: caller:android.app.ApplicationThreadProxy@19811c34, r.packageName :com.android.bluetooth
,08-04 10:46:29.987  8410  8431 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
08-04 10:46:29.987  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
08-04 10:46:29.987  8410  8431 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
08-04 10:46:29.987  8410  8431 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
,08-04 10:46:29.987  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
08-04 10:46:29.987  8410  8431 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
08-04 10:46:29.987  8410  8431 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
08-04 10:46:29.987  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,08-04 10:46:29.997  8410  8431 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
08-04 10:46:29.997  8410  8431 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
08-04 10:46:29.997  8410  8431 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
08-04 10:46:29.997  8410  8431 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
08-04 10:46:29.997  8410  8431 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,08-04 10:46:29.997  8410  8410 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2839eecb
,08-04 10:46:29.997  8410  8410 D HeadsetService: Received start request. Starting profile...
,08-04 10:46:29.997  8410  8410 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-04 10:46:29.997  8410  8410 D HeadsetStateMachine: make
,08-04 10:46:30.017  8410  8410 E HeadsetStateMachine: # of Max HF connection is 2
,08-04 10:46:30.017   746  1455 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,08-04 10:46:30.027   746   762 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
,08-04 10:46:30.027  8410  8410 I bluedroid: get_profile_interface handsfree
,08-04 10:46:30.037  8410  8410 I DualScoManager: Instantiating Dual Sco Manager
,08-04 10:46:30.037  8410  8410 I DualScoManager: Set HeadsetServiceHelper
,08-04 10:46:30.037  8410  8410 D BluetoothAtMessage: createCMTIContentObservers
,08-04 10:46:30.037   746  1471 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
,08-04 10:46:30.037   746  1471 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:30.037   746  1471 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
08-04 10:46:30.037   746  1471 D SettingsProvider: selectionArgs: false
08-04 10:46:30.037   746  1471 D SettingsProvider: selectionArgs: 1002
08-04 10:46:30.037   746  1471 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-04 10:46:30.037   746  1471 D SettingsProvider: ret = -1
,08-04 10:46:30.037  8410  8451 D HeadsetStateMachine: Enter Disconnected: -2
,08-04 10:46:30.037  8410  8410 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2839eecb
,08-04 10:46:30.037  8410  8451 E HeadsetStateMachine: set to mRemoteBrsf = 0
,08-04 10:46:30.047  8410  8410 D A2dpService: Received start request. Starting profile...
,08-04 10:46:30.047  8410  8410 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-04 10:46:30.047  8410  8410 V Avrcp   : make
,08-04 10:46:30.047  8410  8410 V Avrcp   : Avrcp
,08-04 10:46:30.047  8410  8410 I bluedroid: get_profile_interface avrcp
,08-04 10:46:30.047  8410  8451 D HeadsetStateMachine: map size, before remove : 0
08-04 10:46:30.047  8410  8451 D HeadsetStateMachine: map size, after remove: 0
08-04 10:46:30.047  8410  8451 D HeadsetStateMachine: mNextConnectingDevice : null
,08-04 10:46:30.047  8410  8410 V Avrcp   : start
,08-04 10:46:30.057  8410  8410 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-04 10:46:30.057  8410  8410 V Avrcp   : ++registerMediaPlayers++
,08-04 10:46:30.057  8410  8410 I Avrcp   : No of Audio players :: 2
08-04 10:46:30.057  8410  8410 I Avrcp   : App Package name is com.google.android.music
,08-04 10:46:30.057  8410  8410 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,08-04 10:46:30.067  8410  8410 I Avrcp   : App pkg name is Google Play Music
,08-04 10:46:30.067  8410  8410 I Avrcp   : Name::Google Play Music
08-04 10:46:30.067  8410  8410 V Avrcp   : MediaPlayerInfo: mPlayerId=1,
08-04 10:46:30.067  8410  8410 I Avrcp   : App Package name is com.sec.android.app.music
08-04 10:46:30.067  8410  8410 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,08-04 10:46:30.067  8410  8410 I Avrcp   : App pkg name is Music
,08-04 10:46:30.067  8410  8410 I Avrcp   : Name::Music
08-04 10:46:30.067  8410  8410 V Avrcp   : MediaPlayerInfo: mPlayerId=2
,08-04 10:46:30.067  8410  8410 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,08-04 10:46:30.067  8410  8410 I Avrcp   : No of Video players :: 1
08-04 10:46:30.067  8410  8410 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
,08-04 10:46:30.067  8410  8410 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,08-04 10:46:30.077  8410  8410 I Avrcp   : Video App pkg name is Video Player
,08-04 10:46:30.077  8410  8410 I Avrcp   : Name::Video Player
08-04 10:46:30.077  8410  8410 V Avrcp   : MediaPlayerInfo: mPlayerId=3
,08-04 10:46:30.077  8410  8410 I Avrcp   : Add tempPlayer
08-04 10:46:30.077  8410  8410 V Avrcp   : MediaPlayerInfo: mPlayerId=4
08-04 10:46:30.077  8410  8410 I Avrcp   : Total no of players: 4
,08-04 10:46:30.077  8410  8410 V Avrcp   : swapping the samsung player with 1st player
08-04 10:46:30.077  8410  8410 I Avrcp   :  Updating now playing list upon AVRCP Start
,08-04 10:46:30.077  8410  8454 V Avrcp   : handleMessage, msg=207
,08-04 10:46:30.077  8410  8454 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
08-04 10:46:30.077  8410  8410 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-04 10:46:30.077  8410  8410 D A2dpStateMachine: make
,08-04 10:46:30.087  8410  8410 I bluedroid: get_profile_interface a2dp
,08-04 10:46:30.087  8410  8456 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-04 10:46:30.087  8410  8410 E bt-btif : warning : media task started media_task_refcnt 1 
,08-04 10:46:30.087  8410  8454 D BluetoothMediaBrowser: no now playing list
08-04 10:46:30.087  8410  8454 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
08-04 10:46:30.087  8410  8454 D Avrcp   :  checkNowPlayingList start
,08-04 10:46:30.087  8410  8410 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2839eecb
08-04 10:46:30.097  8410  8455 D A2dpStateMachine: Enter Disconnected: -2
,08-04 10:46:30.097  8410  8410 I BluetoothHidServiceJni: classInitNative: succeeds
,08-04 10:46:30.097  8410  8410 D HidService: Received start request. Starting profile...
08-04 10:46:30.097  8410  8410 I bluedroid: get_profile_interface hidhost
,08-04 10:46:30.097  8410  8410 D HidService: setHidService(): set to: null
08-04 10:46:30.097  8410  8410 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2839eecb
,08-04 10:46:30.097  8410  8410 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-04 10:46:30.097  8410  8410 D HealthService: Received start request. Starting profile...
,08-04 10:46:30.097  8410  8410 I bluedroid: get_profile_interface health
,08-04 10:46:30.097  8410  8410 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2839eecb
,08-04 10:46:30.107  8410  8410 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-04 10:46:30.107  8410  8410 D PanService: Received start request. Starting profile...
,08-04 10:46:30.107  8410  8410 D BluetoothPanServiceJni: initializeNative(L110): pan
08-04 10:46:30.107  8410  8410 I bluedroid: get_profile_interface pan
,08-04 10:46:30.107  8410  8410 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2839eecb
,08-04 10:46:30.107  8410  8410 D BluetoothMapService: Received start request. Starting profile...
,08-04 10:46:30.137  8410  8410 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2839eecb
,08-04 10:46:30.137  8410  8410 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,08-04 10:46:30.137  8410  8410 D SapService: Received start request. Starting profile...
,08-04 10:46:30.137  8410  8410 D BluetoothSAPServiceJni: initializeNative(L209): sap
08-04 10:46:30.137  8410  8410 I bluedroid: get_profile_interface sap
08-04 10:46:30.137  8410  8410 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2839eecb
,08-04 10:46:30.137  8410  8410 E BluetoothAdapterService(674885323): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,08-04 10:46:30.137  8410  8410 D HeadsetStateMachine: Try to query the phonestate on bind
08-04 10:46:30.137  1356  1395 I Telecom : BluetoothPhoneService: queryPhoneState
,08-04 10:46:30.147  1356  1356 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-04 10:46:30.147  8410  8410 D HeadsetStateMachine: Proxy object connected
,08-04 10:46:30.147  8410  8410 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
08-04 10:46:30.147  8410  8410 D HeadsetPhoneState: sendDeviceDataStateChanged
,08-04 10:46:30.147  8410  8410 D HeadsetPhoneState: Signal level : previous=0 curr=0
08-04 10:46:30.147  8410  8410 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-04 10:46:30.147  8410  8410 E BluetoothAdapterService(674885323): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,08-04 10:46:30.147  8410  8410 D BluetoothA2dp: Proxy object connected
08-04 10:46:30.147  8410  8410 D BluetoothAdapterService: Bluetooth A2dp source service connected
08-04 10:46:30.147  8410  8451 D HeadsetStateMachine: Disconnected process message: 11
08-04 10:46:30.147  8410  8451 D HeadsetStateMachine: Disconnected process message: 18
,08-04 10:46:30.147  8410  8451 D HeadsetStateMachine: Disconnected process message: 10
08-04 10:46:30.147  8410  8451 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-04 10:46:30.147  8410  8451 D HeadsetStateMachine: Disconnected process message: 11
,08-04 10:46:30.147  8410  8410 E BluetoothAdapterService(674885323): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
08-04 10:46:30.147  8410  8410 E BluetoothAdapterService(674885323): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
08-04 10:46:30.147  8410  8410 E BluetoothAdapterService(674885323): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,08-04 10:46:30.147  8410  8410 E BluetoothAdapterService(674885323): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,08-04 10:46:30.147  8410  8410 E BluetoothAdapterService(674885323): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,08-04 10:46:30.147  8410  8410 E BluetoothAdapterService(674885323): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
08-04 10:46:30.147  8410  8431 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
08-04 10:46:30.147  8410  8431 I bluedroid: enable
,08-04 10:46:30.147  8410  8462 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-04 10:46:30.147  8410  8431 I bt_hci_bdroid: init
,08-04 10:46:30.157  8410  8431 I bt_vendor: init
08-04 10:46:30.157  8410  8431 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-04 10:46:30.157  8410  8431 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
08-04 10:46:30.157  8410  8431 D bt_userial: userial_init
08-04 10:46:30.157  8410  8431 D bt_vendor: op for 5
08-04 10:46:30.157  8410  8431 D bt_vendor: op for 0
,08-04 10:46:30.157  8410  8431 D bt_upio : upio_set_bluetooth_power(on: 0)
08-04 10:46:30.157  8410  8431 D bt_upio : is_emulator_context : 0
08-04 10:46:30.157  8410  8431 D bt_upio : is_rfkill_disabled ? [0]
08-04 10:46:30.157  8410  8431 D bt_upio : is_rfkill_disabled ? [0]
08-04 10:46:30.157  8410  8431 D bt_vendor: op for 0
08-04 10:46:30.157  8410  8431 D bt_upio : upio_set_bluetooth_power(on: 1)
08-04 10:46:30.157  8410  8431 D bt_upio : is_emulator_context : 0
08-04 10:46:30.157  8410  8431 D bt_upio : is_rfkill_disabled ? [0]
,08-04 10:46:30.157  8410  8464 D bt_vendor: op for 3
08-04 10:46:30.157  8410  8464 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-04 10:46:30.157  8410  8464 I bt_userial_vendor: userial_vendor_open():UART is setup
08-04 10:46:30.157  8410  8464 I bt_userial_vendor: device fd = 65 open
08-04 10:46:30.157  8410  8464 D bt_vendor: op for 1
08-04 10:46:30.157  8410  8464 E bt_hwcfg: Start CFG HW, HCI reset
08-04 10:46:30.157  8410  8465 D bt_userial: Entering userial_read_thread()
,08-04 10:46:30.237  8410  8464 E bt_hwcfg: Read Local Name after HCI reset
,08-04 10:46:30.257  8410  8464 D bt_hwcfg: Chipset BCM4335C0,
08-04 10:46:30.257  8410  8464 D bt_hwcfg: Target name = [BCM4335C0]
08-04 10:46:30.257  8410  8464 I bt_hwcfg: module_type[semco].
08-04 10:46:30.257  8410  8464 I bt_hwcfg: not ZERO...
08-04 10:46:30.257  8410  8464 I bt_hwcfg: module_type[semco] is invalid.
08-04 10:46:30.257  8410  8464 E bt_hwcfg: patchram path ORG . BCM4335C0,
08-04 10:46:30.257  8410  8464 E bt_hwcfg: patchram path ORG .. BCM4335C0
08-04 10:46:30.257  8410  8464 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
,08-04 10:46:30.257  8410  8464 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
08-04 10:46:30.257  8410  8464 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
08-04 10:46:30.257  8410  8464 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
,08-04 10:46:30.257  8410  8464 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335C0
08-04 10:46:30.257  8410  8464 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559_wisol.hcd BCM4335C0
,08-04 10:46:30.257  8410  8464 E bt_hwcfg: fw ver (org)0.0
08-04 10:46:30.257  8410  8464 E bt_hwcfg: vendor lib preload failed to locate firmware patch file
,08-04 10:46:30.257  8410  8464 E bt_hwcfg: Remove module rev, try again BCM4335
08-04 10:46:30.257  8410  8464 D bt_hwcfg: Target name = [BCM4335]
08-04 10:46:30.257  8410  8464 I bt_hwcfg: module_type[semco].
,08-04 10:46:30.257  8410  8464 I bt_hwcfg: not ZERO...
08-04 10:46:30.257  8410  8464 I bt_hwcfg: module_type[semco] is invalid.
08-04 10:46:30.257  8410  8464 E bt_hwcfg: patchram path ORG . BCM4335
08-04 10:46:30.257  8410  8464 E bt_hwcfg: patchram path ORG .. BCM4335
,08-04 10:46:30.257  8410  8464 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335
08-04 10:46:30.257  8410  8464 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
08-04 10:46:30.257  8410  8464 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335
08-04 10:46:30.257  8410  8464 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
08-04 10:46:30.257  8410  8464 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335
08-04 10:46:30.257  8410  8464 I bt_hwcfg: patch(org) : bcm4335_V0111.0559.hcd
,08-04 10:46:30.257  8410  8464 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4335_V0111.0559.hcd
08-04 10:46:30.257  8410  8464 E bt_hwcfg: ORG patchram base 0111
08-04 10:46:30.257  8410  8464 E bt_hwcfg: ORG patchram minor 0559
08-04 10:46:30.257  8410  8464 E bt_hwcfg: fw ver (org)111.559
08-04 10:46:30.257  8410  8464 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4335_V0111.0559.hcd
,08-04 10:46:30.267  8410  8464 I bt_hwcfg: Axi patch failure or not include AXI patching
,08-04 10:46:30.277  8410  8464 I bt_hwcfg: bt vendor lib: set UART baud 3000000,
,08-04 10:46:30.787  8410  8464 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-04 10:46:30.787  8410  8464 I bt_hwcfg: FW Download delta = 554408
,08-04 10:46:30.787  8410  8464 D bt_hwcfg: Settlement delay -- 100 ms
08-04 10:46:30.787  8410  8464 I bt_hwcfg: Setting fw settlement delay to 100 
,08-04 10:46:30.897  8410  8464 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-04 10:46:30.937  8410  8464 I bt_hwcfg: vendor lib fwcfg completed
,08-04 10:46:30.947  8410  8462 I         : BTE_InitTraceLevels -- TRC_HCI
,08-04 10:46:30.947  8410  8462 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-04 10:46:30.947  8410  8462 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-04 10:46:30.947  8410  8462 I         : BTE_InitTraceLevels -- TRC_AVDT
08-04 10:46:30.947  8410  8462 I         : BTE_InitTraceLevels -- TRC_AVRC
,08-04 10:46:30.947  8410  8462 I         : BTE_InitTraceLevels -- TRC_A2D
08-04 10:46:30.947  8410  8462 I         : BTE_InitTraceLevels -- TRC_BNEP
08-04 10:46:30.947  8410  8462 I         : BTE_InitTraceLevels -- TRC_BTM
08-04 10:46:30.947  8410  8462 I         : BTE_InitTraceLevels -- TRC_GAP
,08-04 10:46:30.947  8410  8462 I         : BTE_InitTraceLevels -- TRC_PAN
08-04 10:46:30.947  8410  8462 I         : BTE_InitTraceLevels -- TRC_SAP
08-04 10:46:30.947  8410  8462 I         : BTE_InitTraceLevels -- TRC_SDP
08-04 10:46:30.947  8410  8462 I         : BTE_InitTraceLevels -- TRC_GATT
,08-04 10:46:30.947  8410  8462 I         : BTE_InitTraceLevels -- TRC_SMP
08-04 10:46:30.947  8410  8462 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-04 10:46:30.947  8410  8462 I         : BTE_InitTraceLevels -- TRC_BTIF
08-04 10:46:30.947  8410  8462 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,08-04 10:46:30.987   746  1036 I PowerManagerService: [PWL] Off : 105s ago
,08-04 10:46:30.987   746  1036 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
08-04 10:46:30.987   746  1036 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
08-04 10:46:30.987   746  1036 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=746, ws=null) (elapsedTime=19329)
,08-04 10:46:30.987   746  1036 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'bluedroid_timer' (uid=1002, pid=8410, ws=null) (elapsedTime=46)
,08-04 10:46:31.167  8410  8462 W bt-l2cap: l2c_link_processs_ble_num_bufs 15
,08-04 10:46:31.177  8410  8462 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xaf918b5d 
,08-04 10:46:31.177  8410  8462 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xaf918b5d 
,08-04 10:46:31.257   310   310 E SMD     : DCD ON
,08-04 10:46:31.397  8410  8434 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 1 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
,08-04 10:46:31.407  8410  8434 E bt-btif : Calling BTA_HhEnable
,08-04 10:46:31.407  8410  8434 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,08-04 10:46:31.407  8410  8434 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
,08-04 10:46:31.407  8410  8434 E BluetoothServiceJni: populateRssiValuesNative
,08-04 10:46:31.417  8410  8434 I bluedroid: getModelRssiValues
,08-04 10:46:31.417  8410  8434 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,08-04 10:46:31.417  8410  8434 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,08-04 10:46:31.417   746   746 D SettingsProvider: name = bluetooth_name
,08-04 10:46:31.417  8410  8434 D BluetoothAdapterProperties: Name is: Note3-1
,08-04 10:46:31.417  8410  8434 D BluetoothAdapterProperties: Scan Mode:20
,08-04 10:46:31.417  8410  8434 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-04 10:46:31.417  8410  8434 D BluetoothAdapterProperties: LE Address is:E0:B7:20:3E:93:BC
,08-04 10:46:31.417  8410  8464 D bt_vendor: op for 2
08-04 10:46:31.417  8410  8464 D bt_vendor: op for 6
,08-04 10:46:31.417  8410  8464 D bt_vendor: op for 7
,08-04 10:46:31.417  8410  8464 D bt_upio : proc btwrite assertion
,08-04 10:46:31.427  8410  8464 D bt_vendor: op for 7
08-04 10:46:31.427  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.427  8410  8434 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
08-04 10:46:31.427  8410  8434 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
08-04 10:46:31.427  8410  8434 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,08-04 10:46:31.427  8410  8434 E bt-btif : btif_sock_init: !vhci_init
08-04 10:46:31.427  8410  8434 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
,08-04 10:46:31.427  8410  8434 D IOP_DB_BT: db_open: db_open : handle 3026780176l, read 14063 bytes onto local cache
08-04 10:46:31.427  8410  8434 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,08-04 10:46:31.427  8410  8434 D IOP_DB_BT: db_query: result 1
08-04 10:46:31.427  8410  8434 I         : iop_db_open: iop_db_open status 0
,08-04 10:46:31.427  8410  8434 D bte_conf: Device ID record 1 : primary
08-04 10:46:31.427  8410  8434 D bte_conf:   vendorId            = 0075
,08-04 10:46:31.427  8410  8434 D bte_conf:   vendorIdSource      = 0001
08-04 10:46:31.427  8410  8434 D bte_conf:   product             = 0100
08-04 10:46:31.427  8410  8434 D bte_conf:   version             = 0200
08-04 10:46:31.427  8410  8434 D bte_conf:   clientExecutableURL = 
,08-04 10:46:31.427  8410  8434 D bte_conf:   serviceDescription  = 
08-04 10:46:31.427  8410  8434 D bte_conf:   documentationURL    = 
08-04 10:46:31.427  8410  8434 D bte_conf: bte_load_did_conf no section named DID2.
,08-04 10:46:31.427  8410  8431 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,08-04 10:46:31.427  8410  8431 D BluetoothAdapterProperties: ScanMode =  20
08-04 10:46:31.427  8410  8431 D BluetoothAdapterProperties: State =  11
,08-04 10:46:31.427   746  1461 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,08-04 10:46:31.427  8410  8431 D BluetoothAdapterProperties: Setting state to 12
,08-04 10:46:31.437  8410  8431 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-04 10:46:31.437   746  1461 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,08-04 10:46:31.437   746  1461 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
08-04 10:46:31.437   746  1461 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,08-04 10:46:31.437   746  1461 D SettingsProvider: selectionArgs: false
08-04 10:46:31.437   746  1461 D SettingsProvider: selectionArgs: 1002
08-04 10:46:31.437   746  1461 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,08-04 10:46:31.437   746  1461 D SettingsProvider: ret = -1
,08-04 10:46:31.437  8410  8431 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,08-04 10:46:31.437  8410  8431 D BluetoothAdapterService: updateAdapterState state is 12
,08-04 10:46:31.437   746  1426 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:31.437   746  1426 D ActivityManager: caller:android.app.ApplicationThreadProxy@2bdfa64, r.packageName :com.android.bluetooth
,08-04 10:46:31.447   746  1028 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 10:46:31.447  8410  8431 D BluetoothAdapterService: Autoconnection is available 
,08-04 10:46:31.447  8410  8431 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
08-04 10:46:31.447  8410  8431 D BluetoothAdapterService: starting service from this receiver
,08-04 10:46:31.447   746  1028 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-04 10:46:31.447  8410  8464 E bt_h4   : vendor lib postload completed
,08-04 10:46:31.457  8410  8434 D BluetoothAdapterProperties: Scan Mode:21
,08-04 10:46:31.457  8410  8434 D BluetoothAdapterProperties: Discoverable Timeout:120
,08-04 10:46:31.457  8410  8410 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,08-04 10:46:31.457  8410  8410 I BluetoothPbapService: Handler(): got msg=1
,08-04 10:46:31.457   746  1718 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-04 10:46:31.467   746  1366 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,08-04 10:46:31.467   746  1366 D ActivityManager: caller:android.app.ApplicationThreadProxy@1a9258d0, r.packageName :com.android.bluetooth
,08-04 10:46:31.467   746   746 D BluetoothA2dp: Proxy object connected
,08-04 10:46:31.477  1320  1347 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 10:46:31.477  8410  8431 I BluetoothAdapterState: Entering On State from state = 11
,08-04 10:46:31.477  8410  8464 D bt_vendor: op for 7
08-04 10:46:31.477  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.477  8410  8434 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-04 10:46:31.477  8410  8464 D bt_vendor: op for 7
08-04 10:46:31.477  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.477  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:31.477  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:31.477  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:31.477  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:46:31.477  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:31.477  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:31.477  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:31.477  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:46:31.477  8410  8464 D bt_vendor: op for 7
08-04 10:46:31.477  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.477  8410  8464 D bt_vendor: op for 7
08-04 10:46:31.477  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.487  8410  8478 V BluetoothPbapService: PBAP Service initSocket try: 0
08-04 10:46:31.487  8410  8464 D bt_vendor: op for 7
08-04 10:46:31.487  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.487  8410  8464 D bt_vendor: op for 7
08-04 10:46:31.487  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.487  8410  8464 D bt_vendor: op for 7
08-04 10:46:31.487  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.487  8410  8464 D bt_vendor: op for 7
08-04 10:46:31.487  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.487  7553  7553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:46:31.487  8410  8464 D bt_vendor: op for 7
08-04 10:46:31.487  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.487  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:31.487  8410  8464 D bt_vendor: op for 7
08-04 10:46:31.487  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.497  8410  8464 D bt_vendor: op for 7
08-04 10:46:31.497  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.497  8410  8464 D bt_vendor: op for 7
08-04 10:46:31.497  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.497  8410  8478 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 10:46:31.497  8410  8464 D bt_vendor: op for 7
08-04 10:46:31.497  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.497  8410  8478 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
08-04 10:46:31.497  8410  8478 D BluetoothSocket: bindListen(), new LocalSocket 
08-04 10:46:31.497  8410  8478 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-04 10:46:31.497  8410  8478 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@25f18be4
,08-04 10:46:31.497  8410  8464 D bt_vendor: op for 7
08-04 10:46:31.497  8410  8464 D bt_upio : BT_WAKE is asserted already
08-04 10:46:31.497  8410  8478 D BluetoothSocket: channel: 19
08-04 10:46:31.497  8410  8478 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
08-04 10:46:31.497  8410  8464 D bt_vendor: op for 7
,08-04 10:46:31.497  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.497  8410  8464 D bt_vendor: op for 7
,08-04 10:46:31.497  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.497  8410  8464 D bt_vendor: op for 7
,08-04 10:46:31.497  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.497  8410  8464 D bt_vendor: op for 7
08-04 10:46:31.497  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.507  8410  8464 D bt_vendor: op for 7
,08-04 10:46:31.507  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.507  8410  8464 D bt_vendor: op for 7
,08-04 10:46:31.507  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.507  8410  8464 D bt_vendor: op for 7
,08-04 10:46:31.507  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.507  8410  8464 D bt_vendor: op for 7
,08-04 10:46:31.507  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.507  8410  8464 D bt_vendor: op for 7
,08-04 10:46:31.507  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.517  8410  8464 D bt_vendor: op for 7
,08-04 10:46:31.517  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.517  8410  8464 D bt_vendor: op for 7
08-04 10:46:31.517  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.517  8410  8464 D bt_vendor: op for 7
,08-04 10:46:31.517  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.517  8410  8464 D bt_vendor: op for 7
,08-04 10:46:31.517  8410  8464 D bt_upio : BT_WAKE is asserted already
,08-04 10:46:31.587   746  1028 I art     : Explicit concurrent mark sweep GC freed 52771(2MB) AllocSpace objects, 4(64KB) LOS objects, 30% free, 37MB/53MB, paused 1.310ms total 107.078ms
08-04 10:46:31.587   746  1028 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-04 10:46:31.587  1320  1320 D BluetoothA2dp: Proxy object connected
08-04 10:46:31.587  1320  1320 D A2dpProfile: Bluetooth service connected
,08-04 10:46:31.597   746  1028 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 10:46:31.597  1402  1580 E BluetoothHeadset: BluetoothHeadset service is binded
,08-04 10:46:31.597  1320  1347 D BluetoothPan: Binding service...
,08-04 10:46:31.597   746  1028 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,08-04 10:46:31.597  1320  1320 D BluetoothPan: BluetoothPAN Proxy object connected
,08-04 10:46:31.597  1320  1320 D PanProfile: Bluetooth service connected
08-04 10:46:31.597  1320  1347 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-04 10:46:31.607   746  1028 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,08-04 10:46:31.607  1320  1320 D BluetoothInputDevice: Proxy object connected
08-04 10:46:31.607  1320  1320 D HidProfile: Bluetooth service connected
,08-04 10:46:31.607  1320  1365 D Bluetoothsap: onBluetoothStateChange: up=true
08-04 10:46:31.607  1320  1365 D Bluetoothsap: Binding service...
,08-04 10:46:31.607  1320  1365 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,08-04 10:46:31.617   746  1028 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,08-04 10:46:31.617  1320  1365 D Bluetoothsap: bindService called to Bluetooth SAP Service
,08-04 10:46:31.617  1320  1320 D Bluetoothsap: BluetoothSAP Proxy object connected
08-04 10:46:31.617  1320  1320 D SapProfile: Bluetooth service connected
08-04 10:46:31.617  1320  1320 D Bluetoothsap: getConnectedDevices()
,08-04 10:46:31.617   746  1028 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 10:46:31.617  1356  3302 E BluetoothHeadset: BluetoothHeadset service is binded
,08-04 10:46:31.617   746  1028 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 10:46:31.617  1320  1347 E BluetoothHeadset: BluetoothHeadset service is binded
08-04 10:46:31.617  1320  1320 D HeadsetProfile: Bluetooth service connected
,08-04 10:46:31.617   746  1028 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 10:46:31.617  7727  7735 E BluetoothHeadset: BluetoothHeadset service is binded
08-04 10:46:31.617   746  1028 D BluetoothPan: Binding service...
,08-04 10:46:31.617   746  1028 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
08-04 10:46:31.617   746   746 D BluetoothPan: BluetoothPAN Proxy object connected
,08-04 10:46:31.627   746  1028 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 10:46:31.627  1356  1395 E BluetoothHeadset: BluetoothHeadset service is binded
08-04 10:46:31.627  1320  1386 D BluetoothMap: onBluetoothStateChange: up=true
,08-04 10:46:31.627   746  1028 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,08-04 10:46:31.627  1320  1365 D BluetoothPbap: onBluetoothStateChange: up=true
,08-04 10:46:31.627  1320  1320 D BluetoothMap: Proxy object connected
08-04 10:46:31.627  1320  1320 D MapProfile: Bluetooth service connected
,08-04 10:46:31.627   746  1028 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,08-04 10:46:31.627  1320  1320 D BluetoothPbap: Proxy object connected
08-04 10:46:31.627  1320  1320 D PbapServerProfile: Bluetooth service connected
,08-04 10:46:31.627   746  1028 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 10:46:31.627  3420  3428 E BluetoothHeadset: BluetoothHeadset service is binded
,08-04 10:46:31.627  8410  8429 D BluetoothA2dp: onBluetoothStateChange: up=true
08-04 10:46:31.627   746  1028 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 10:46:31.627   746  1028 E BluetoothHeadset: BluetoothHeadset service is binded
,08-04 10:46:31.627   746  1028 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,08-04 10:46:31.627  1356  3302 E BluetoothHeadset: BluetoothHeadset service is binded
,08-04 10:46:31.637  3420  8338 D BluetoothA2dp: onBluetoothStateChange: up=true
,08-04 10:46:31.637   746  1028 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,08-04 10:46:31.637  3420  3420 D BluetoothA2dp: Proxy object connected
08-04 10:46:31.637   746  1028 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,08-04 10:46:31.637   746   746 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,08-04 10:46:31.637   746   746 I InputMethodManagerService: [BT Setting State] State =12
08-04 10:46:31.637   746   746 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,08-04 10:46:31.637  1190  1190 D BluetoothTile:  onBluetoothStateChange:
,08-04 10:46:31.637  1356  1356 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@2c854db4, true
,08-04 10:46:31.637  1688  1688 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,08-04 10:46:31.637  7727  7727 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
08-04 10:46:31.637  1356  1356 D BluetoothHeadset: registerMessageListener
08-04 10:46:31.637  1320  1320 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,08-04 10:46:31.637  1190  1190 D BluetoothTile:  onBluetoothPairedDevicesChanged:
08-04 10:46:31.637  1190  1190 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,08-04 10:46:31.647  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:31.647   746  1459 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,08-04 10:46:31.647   746  1028 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-04 10:46:31.647   746   764 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-04 10:46:31.647   746   764 D ActivityManager: caller:android.app.ApplicationThreadProxy@1d67d063, r.packageName :com.google.android.gms
,08-04 10:46:31.647   746  1366 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,08-04 10:46:31.647  1190  1190 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
08-04 10:46:31.647  1190  1602 D BluetoothTile:  handleUpdatestate:false name:null
08-04 10:46:31.647  1190  1602 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,08-04 10:46:31.647  8410  8418 D HeadsetService: registerMessageListener
,08-04 10:46:31.647  8410  8418 D HeadsetService: registerMessageListener
08-04 10:46:31.647  8410  8451 D HeadsetStateMachine: Disconnected process message: 70
,08-04 10:46:31.647  1356  1356 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,08-04 10:46:31.647  8410  8451 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@16d0384d
08-04 10:46:31.647  1356  1356 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,08-04 10:46:31.657  8410  8451 D HeadsetStateMachine: Disconnected process message: 9
,08-04 10:46:31.657  1320  1320 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
08-04 10:46:31.657  8410  8494 D BluetoothMapMasInstance: set MAP SDP message type : 1
,08-04 10:46:31.657  8410  8451 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,08-04 10:46:31.657  8410  8494 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 10:46:31.657  1320  1320 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,08-04 10:46:31.657   325  1093 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
08-04 10:46:31.657   325  1093 V voice   : voice_set_parameters: enter: A2dpSuspended=false
08-04 10:46:31.657   325  1093 V voice   : voice_set_parameters: exit with code(-2)
08-04 10:46:31.657   325  1093 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
08-04 10:46:31.657   325  1093 V msm8974_platform: platform_set_parameters: exit with code(-2)
08-04 10:46:31.657   325  1093 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
08-04 10:46:31.657   325  1093 V audio_hw_primary: adev_set_parameters: exit
08-04 10:46:31.657  8410  8451 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,08-04 10:46:31.667  8410  8464 D bt_vendor: op for 7
08-04 10:46:31.667  8410  8464 D bt_upio : BT_WAKE is asserted already
08-04 10:46:31.667  8410  8494 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
08-04 10:46:31.667  8410  8494 D BluetoothSocket: bindListen(), new LocalSocket 
08-04 10:46:31.667  8410  8494 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-04 10:46:31.667  8410  8494 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@5d9f02
08-04 10:46:31.667  8410  8494 D BluetoothSocket: channel: 5
,08-04 10:46:31.667  1320  1320 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-04 10:46:31.667   746  1298 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
08-04 10:46:31.667   746  1298 D ActivityManager: caller:android.app.ApplicationThreadProxy@2eca31de, r.packageName :com.android.settings
,08-04 10:46:31.677  1320  1320 D DockEventReceiver: finishStartingService: stopping service
,08-04 10:46:31.677  1320  1320 D BluetoothNotiBroadcastReceiver: onReceive
,08-04 10:46:31.677  8410  8410 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2839eecb
,08-04 10:46:31.677  8410  8410 D BtConfig.SecureMode: isSecureModeOn:false
,08-04 10:46:31.677   746  1435 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
08-04 10:46:31.677   746  1435 D ActivityManager: caller:android.app.ApplicationThreadProxy@3146168c, r.packageName :com.android.bluetooth
,08-04 10:46:31.697  1942  1942 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,08-04 10:46:31.697   746  1461 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
08-04 10:46:31.697   746  1461 D ActivityManager: caller:android.app.ApplicationThreadProxy@fc38dea, r.packageName :com.google.android.gms
,08-04 10:46:31.697  7553  7621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:31.697  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:31.697  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:31.697  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-04 10:46:31.697  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:31.697  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:31.697  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:31.697  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:46:31.697  7553  7621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:46:31.697  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:31.697  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3990b476 added. We now have 8 listener(s)
08-04 10:46:31.697  7553  7621 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:46:31.707  7553  7621 I WifiManager: packageName : com.test.thalitest
,08-04 10:46:31.707   746  1435 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-04 10:46:31.707   746  1435 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-04 10:46:31.707   746  1435 D SecContentProvider2: mCursor = null
,08-04 10:46:31.707  1942  8500 D EasyUnlockInitService: Handling intent for initializer IntentService.
08-04 10:46:31.707   746  1435 D WifiService: setWifiEnabled: false pid=7553, uid=10079
,08-04 10:46:31.707   746  1435 D SettingsProvider: name = wifi_on
,08-04 10:46:31.707  1942  1942 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,08-04 10:46:31.707   746   764 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,08-04 10:46:31.717  7553  7621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:31.717  7553  7621 I WifiManager: packageName : com.test.thalitest
08-04 10:46:31.717   746  1471 D SecContentProvider: uri = 18 selection = isWifiEnabled
,08-04 10:46:31.717   746  1471 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
08-04 10:46:31.717   746  1471 D SecContentProvider2: mCursor = null
,08-04 10:46:31.717   746  1471 D WifiService: setWifiEnabled: true pid=7553, uid=10079
,08-04 10:46:31.717   746  1471 W ActivityManager: Permission Denial: getCurrentUser() from pid=7553, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,08-04 10:46:31.717   746  1471 W WifiService: Failed getting userId using ActivityManagerNative
08-04 10:46:31.717   746  1471 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7553, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
08-04 10:46:31.717   746  1471 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
08-04 10:46:31.717   746  1471 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
08-04 10:46:31.717   746  1471 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
08-04 10:46:31.717   746  1471 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
08-04 10:46:31.717   746  1471 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
08-04 10:46:31.717   746  1471 D SettingsProvider: name = wifi_on
,08-04 10:46:31.727  8410  8505 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-04 10:46:31.727   746  1461 D ActivityManager: caller:android.app.ApplicationThreadProxy@26f3f042, r.packageName :com.google.android.gms
,08-04 10:46:31.727   746  1150 E WifiHW  : ##################### set firmware type 0 #####################
,08-04 10:46:31.727   305  1066 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
08-04 10:46:31.727   305  1066 I WifiHW  : module is semco
08-04 10:46:31.727   305  1066 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
08-04 10:46:31.727   305  1066 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
08-04 10:46:31.727   305  1066 E WifiHW  : TEMP_FAILURE_RETRY complete
08-04 10:46:31.727   305  1066 D SoftapController: Softap fwReload - Ok
,08-04 10:46:31.727  8410  8464 D bt_vendor: op for 7
08-04 10:46:31.727  8410  8464 D bt_upio : BT_WAKE is asserted already
08-04 10:46:31.727  8410  8505 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
08-04 10:46:31.727  8410  8505 D BluetoothSocket: bindListen(), new LocalSocket 
,08-04 10:46:31.727   305  1066 D CommandListener: Setting iface cfg
08-04 10:46:31.727   305  1066 D CommandListener: Trying to bring down wlan0
08-04 10:46:31.727  8410  8505 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
08-04 10:46:31.727  8410  8505 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@39f0737c
08-04 10:46:31.727   305  1066 D CommandListener: Clearing all IP addresses on wlan0
08-04 10:46:31.727  8410  8505 D BluetoothSocket: channel: 12
,08-04 10:46:31.727  8410  8505 I BtOppRfcommListener: Accept thread started.
,08-04 10:46:31.737   746  1150 E WifiHW  : supplicant_name : p2p_supplicant
,08-04 10:46:31.737  1942  8500 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,08-04 10:46:31.737  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:31.737   746   746 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,08-04 10:46:31.737  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 10:46:31.737  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
08-04 10:46:31.737  1190  1190 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 10:46:31.737  1190  1190 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
08-04 10:46:31.737  1190  1190 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 10:46:31.737  1190  1602 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-04 10:46:31.737  1190  1190 D HotspotTile: onReceive : 2, 0
08-04 10:46:31.737   746  1150 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-04 10:46:31.737  1320  1320 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-04 10:46:31.737   746  1154 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,08-04 10:46:31.737   746  1150 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-04 10:46:31.747  7187  7187 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-04 10:46:31.747   746  1145 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:31.747  7624  7624 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-04 10:46:31.747  7624  7624 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-04 10:46:31.747  7624  7624 D SecurityLogAgent: StateMachine : Current State = 1
08-04 10:46:31.747  7624  7624 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-04 10:46:31.777  8512  8512 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
08-04 10:46:31.777  8512  8512 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-04 10:46:31.777  8512  8512 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-04 10:46:31.777  8512  8512 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-04 10:46:31.777   385   385 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8512
08-04 10:46:31.777   385   385 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
08-04 10:46:31.777  8512  8512 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-04 10:46:31.777  8512  8512 I wpa_supplicant: ssSupport state is = 1
,08-04 10:46:31.777  8512  8512 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,08-04 10:46:31.777  8512  8512 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,08-04 10:46:31.777   385   385 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8512
08-04 10:46:31.777   385   385 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,08-04 10:46:32.047   385   385 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,08-04 10:46:32.297  8512  8512 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,08-04 10:46:32.337  8512  8512 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,08-04 10:46:32.337  8512  8512 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-04 10:46:32.337   385   385 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8512
,08-04 10:46:32.337   385   385 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
08-04 10:46:32.337  8512  8512 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-04 10:46:32.337  8512  8512 I wpa_supplicant: ssSupport state is = 1
,08-04 10:46:32.337  8512  8512 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-04 10:46:32.337  8512  8512 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-04 10:46:32.337  8512  8512 E wpa_supplicant: SIM READ ERROR
,08-04 10:46:32.337  8512  8512 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-04 10:46:32.337  8512  8512 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-04 10:46:32.337  8512  8512 E wpa_supplicant: SIM READ ERROR
08-04 10:46:32.337  8512  8512 I wpa_supplicant: Blacklist: Clear (all) 
,08-04 10:46:32.337  8512  8512 I wpa_supplicant: wpa_default_ap_write_once
,08-04 10:46:32.337  8512  8512 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-04 10:46:32.337  8512  8512 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-04 10:46:32.337  8512  8512 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
08-04 10:46:32.337  8512  8512 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,08-04 10:46:32.337  8512  8512 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,08-04 10:46:32.337  8512  8512 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-04 10:46:32.567   369   369 I ServiceManager: Waiting for service AtCmdFwd...
,08-04 10:46:32.997   746  1153 E Tethering: No numeric data
,08-04 10:46:32.997   746  1153 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-04 10:46:32.997  1190  1190 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
08-04 10:46:32.997   746  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:32.997   746  1147 V NetworkStats: performPollLocked(flags=0x1)
,08-04 10:46:32.997  1190  1190 D HotspotTile: updateTetherState():false, false
08-04 10:46:32.997   746  1147 D NetworkStatsFactory: UpdateStatsForKnox
08-04 10:46:32.997   746  1147 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:32.997   746  1147 V NetworkStats: performPollLocked() took 4ms
08-04 10:46:32.997   746  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 10:46:32.997   746  1148 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:32.997   746  1148 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 10:46:33.007  8512  8512 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,08-04 10:46:33.017  8512  8512 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,08-04 10:46:33.017  8512  8512 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-04 10:46:33.017  8512  8512 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,08-04 10:46:33.017   385   385 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8512
08-04 10:46:33.017   385   385 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
08-04 10:46:33.017  8512  8512 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-04 10:46:33.017  8512  8512 I wpa_supplicant: ssSupport state is = 1
,08-04 10:46:33.017  8512  8512 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
08-04 10:46:33.017  8512  8512 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
08-04 10:46:33.017   385   385 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8512
08-04 10:46:33.017   385   385 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,08-04 10:46:33.017  8512  8512 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
08-04 10:46:33.017  8512  8512 I wpa_supplicant: ssSupport state is = 1
08-04 10:46:33.017  8512  8512 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-04 10:46:33.017  8512  8512 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-04 10:46:33.017  8512  8512 E wpa_supplicant: SIM READ ERROR
,08-04 10:46:33.017  8512  8512 I wpa_supplicant: wpa_default_ap_write_once
08-04 10:46:33.017  8512  8512 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
08-04 10:46:33.017  8512  8512 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-04 10:46:33.037  8512  8512 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
08-04 10:46:33.037  8512  8512 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,08-04 10:46:33.047  8512  8512 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
08-04 10:46:33.047  8512  8512 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,08-04 10:46:33.047   746  1150 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,08-04 10:46:33.047   746  1150 D WifiNative-HAL: callSECApiBoolean - ID [21]
08-04 10:46:33.047  8512  8512 I wpa_supplicant: HOTSPOT20_ENABLE called
08-04 10:46:33.047  8512  8512 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
08-04 10:46:33.047  8512  8512 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
08-04 10:46:33.047  8512  8512 E wpa_supplicant: SIM READ ERROR
08-04 10:46:33.047  8512  8512 I wpa_supplicant: Blacklist: Clear (all) 
,08-04 10:46:33.067  8512  8512 I wpa_supplicant: Skip scan - bUseNetwork false
,08-04 10:46:33.067   746   746 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,08-04 10:46:33.067   746  1150 D WifiNative-HAL: callSECApiInt - ID [210]
,08-04 10:46:33.077  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-04 10:46:33.077  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
08-04 10:46:33.077   746  1154 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
08-04 10:46:33.077  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:33.077  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:33.077  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,08-04 10:46:33.077  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:33.077  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:33.077  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:33.077  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,08-04 10:46:33.077  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:33.077  1190  1190 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 10:46:33.077  1190  1190 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,08-04 10:46:33.077  1190  1190 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
08-04 10:46:33.077  1190  1602 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,08-04 10:46:33.077  1190  1190 D HotspotTile: onReceive : 3, 0
,08-04 10:46:33.077  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:33.077  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:33.077  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:33.077  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:33.077  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:33.077  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:33.077  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:33.077  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:46:33.077   746  1150 D WifiConfigStore: Loading config and enabling all networks 
,08-04 10:46:33.077  7553  7553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:46:33.077  1320  1320 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,08-04 10:46:33.087  7187  7187 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,08-04 10:46:33.087   746  1150 E WifiConfigStore: Not a HS20
,08-04 10:46:33.087   746  1426 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:33.087  7624  7624 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,08-04 10:46:33.097  7624  7624 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-04 10:46:33.097  7624  7624 D SecurityLogAgent: StateMachine : Current State = 1
08-04 10:46:33.097  7624  7624 D SecurityLogAgent: StateMachine : Changed Current State = 1
,08-04 10:46:33.097   746  1150 E WifiConfigStore: Not a HS20
,08-04 10:46:33.107   746  1150 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-04 10:46:33.107   746  1150 D WifiNative-HAL: callSECApiInt - ID [65]
,08-04 10:46:33.117   746  1150 D WifiNative-HAL: callSECApiBoolean - ID [13]
08-04 10:46:33.117  8512  8512 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
08-04 10:46:33.117  8512  8512 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,08-04 10:46:33.117  8512  8512 I wpa_supplicant: reset timer : RESET_TIMER 0
08-04 10:46:33.117  8512  8512 I wpa_supplicant: P2P: Current p2p state = IDLE
08-04 10:46:33.117  8512  8512 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
08-04 10:46:33.117  8512  8512 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
08-04 10:46:33.117  8512  8512 I wpa_supplicant: First Scan Start
,08-04 10:46:33.117  8512  8512 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,08-04 10:46:33.117  7770  7770 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-04 10:46:33.117   746  1150 D WifiNative-HAL: Setting external_sim to 1
,08-04 10:46:33.117   746  1150 D WifiStateMachine: Setting OUI to DA-A1-19
08-04 10:46:33.117   746  1150 I WifiNative-HAL: startHal
08-04 10:46:33.117   746  1150 E wifi    : getStaticLongField sWifiHalHandle 0x933b986c
08-04 10:46:33.117   746  1150 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x801ac2
08-04 10:46:33.117   746  1150 I WifiNative-HAL: Could not start hal
,08-04 10:46:33.137   746  1150 E native  : do suspend true
,08-04 10:46:33.137   746  1149 D WifiP2pService: P2pDisabledState{ what=131203 }
,08-04 10:46:33.147   746  1150 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,08-04 10:46:33.147   746   746 D WifiScanningService: SCAN_AVAILABLE : 3
08-04 10:46:33.147   746   746 D RttService: SCAN_AVAILABLE : 3
08-04 10:46:33.147   746  1167 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:33.147   746  1167 I WifiNative-HAL: startHal
08-04 10:46:33.147   746  1167 E wifi    : getStaticLongField sWifiHalHandle 0x9c71499c
08-04 10:46:33.147   746  1167 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x601abe
08-04 10:46:33.147   746  1167 I WifiNative-HAL: Could not start hal
08-04 10:46:33.147   746  1167 E WifiScanningService: could not start HAL
08-04 10:46:33.147   746  1168 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:33.147   305  1066 D CommandListener: Setting iface cfg
08-04 10:46:33.147   305  1066 D CommandListener: Trying to bring up p2p0
,08-04 10:46:33.147   746  1149 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-04 10:46:33.147   746  1149 D WifiP2pService: P2pEnablingState
,08-04 10:46:33.147   746  1149 D WifiP2pService: P2pEnablingState{ what=147457 }
08-04 10:46:33.147   746  1149 D WifiP2pService: P2p socket connection successful
08-04 10:46:33.147   746  1149 D WifiP2pService: P2pEnabledState
,08-04 10:46:33.147   746  1150 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
,08-04 10:46:33.147   746  1150 D WifiNative-HAL: callSECStringApiVoid - ID [215]
08-04 10:46:33.147   746  1150 E WifiNative-HAL: invaild command id : 215
08-04 10:46:33.147   746  1030 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
08-04 10:46:33.147   746  1030 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-04 10:46:33.147   746  1030 D WifiDisplayController: disconnect
08-04 10:46:33.147   746  1030 D WifiDisplayController: updateConnection
08-04 10:46:33.147   746  1030 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
08-04 10:46:33.147   746  1030 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-04 10:46:33.147   746   746 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,08-04 10:46:33.147   746  1149 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,08-04 10:46:33.147  7754  7754 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,08-04 10:46:33.147  1190  1190 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,08-04 10:46:33.157   746  1435 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,08-04 10:46:33.157  1190  1190 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,08-04 10:46:33.157   746  1152 E ConnectivityService: updateNetworkInfo()
08-04 10:46:33.157   746  1152 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,08-04 10:46:33.157   746  1030 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:33.157   746  1030 D WifiDisplayAdapter: onP2pDisconnected
08-04 10:46:33.157   746  1030 D IpRemoteDisplayController: disconnectWfdBridgeServer
08-04 10:46:33.157   746  1030 D IpRemoteDisplayController: WfdBridgeServer is already null
,08-04 10:46:33.157  1320  1320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-04 10:46:33.157  1320  1320 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
08-04 10:46:33.157   746  1455 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:33.157  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-04 10:46:33.157   746  1461 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:33.157  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-04 10:46:33.157  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-04 10:46:33.157  1320  1320 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-04 10:46:33.167  1320  3147 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-04 10:46:33.177  7318  7318 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,08-04 10:46:33.177  7754  7754 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,08-04 10:46:33.177  7754  7754 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,08-04 10:46:33.177  7754  7754 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,08-04 10:46:33.187  7754  7754 D WifiDirectBR: stopServiceTest : false
,08-04 10:46:33.187  8512  8512 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-04 10:46:33.187   746  1149 D WifiNative-HAL: p2pGetDeviceAddress
,08-04 10:46:33.207  8512  8512 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,08-04 10:46:33.207   746  1149 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:de:28:a3
,08-04 10:46:33.207   746  1030 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
08-04 10:46:33.207   746  1030 D WifiDisplayController:  deviceAddress: ea:50:8b:de:28:a3
08-04 10:46:33.207   746  1030 D WifiDisplayController:  primary type: 10-0050F204-5
08-04 10:46:33.207   746  1030 D WifiDisplayController:  secondary type: null
08-04 10:46:33.207   746  1030 D WifiDisplayController:  wps: 0
08-04 10:46:33.207   746  1030 D WifiDisplayController:  grpcapab: 0
08-04 10:46:33.207   746  1030 D WifiDisplayController:  devcapab: 0
08-04 10:46:33.207   746  1030 D WifiDisplayController:  status: 3
08-04 10:46:33.207   746  1030 D WifiDisplayController:  wfdInfo: null
08-04 10:46:33.207   746  1030 D WifiDisplayController:  groupownerAddress: null
08-04 10:46:33.207   746  1030 D WifiDisplayController:  GOdeviceName: null
08-04 10:46:33.207   746  1030 D WifiDisplayController:  interfaceAddress: 
08-04 10:46:33.207   746  1030 D WifiDisplayController:  SConnectInfo : null
08-04 10:46:33.207   746  1149 D WifiP2pService: DeviceAddress: ea:28:a3
,08-04 10:46:33.207   746  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-04 10:46:33.207   746  1150 D SecContentProvider2: mCursor = null
,08-04 10:46:33.207   746  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-04 10:46:33.207   746  1150 D SecContentProvider2: mCursor = null
,08-04 10:46:33.217   746  1149 D WifiP2pService: sending p2p persistent groups changed broadcast
,08-04 10:46:33.217   746  1149 D WifiP2pService: InactiveState
08-04 10:46:33.217   746  1149 D WifiP2pService: InactiveState{ what=143376 }
08-04 10:46:33.217   746  1149 D WifiP2pService: P2pEnabledState{ what=143376 }
08-04 10:46:33.217  8512  8512 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,08-04 10:46:33.217   746  1149 D WifiP2pService: InactiveState{ what=143376 }
08-04 10:46:33.217   746  1149 D WifiP2pService: P2pEnabledState{ what=143376 }
,08-04 10:46:33.227  8410  8464 D bt_vendor: op for 7
,08-04 10:46:33.417  8410  8475 D bt_upio : ..proc_btwrite_timeout..
,08-04 10:46:33.517   746   915 W ProcessCpuTracker: Skipping unknown process pid 8527
,08-04 10:46:33.527   746   915 W ProcessCpuTracker: Skipping unknown process pid 8528
,08-04 10:46:33.527   746   915 W ProcessCpuTracker: Skipping unknown process pid 8530
08-04 10:46:33.527   746   915 W ProcessCpuTracker: Skipping unknown process pid 8531
,08-04 10:46:33.527   746   915 W ProcessCpuTracker: Skipping unknown process pid 8543
,08-04 10:46:33.567   369   369 I ServiceManager: Waiting for service AtCmdFwd...
,08-04 10:46:33.747  7553  7621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:33.747  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:33.747  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:33.747  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:33.747  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:33.747  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:33.747  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:33.747  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:46:33.747  7553  7621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:46:33.747  7553  7621 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-04 10:46:33.757  7553  7621 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-04 10:46:33.757  7553  7621 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@100820bb Bundle[{}]
,08-04 10:46:33.757  7553  7621 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-04 10:46:33.757  7553  7621 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-04 10:46:33.757  7553  7621 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-04 10:46:33.757  7553  7621 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-04 10:46:33.757  7553  7621 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-04 10:46:33.757  7553  7621 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-04 10:46:33.757  7553  7621 I System.out: Running OutgoingSocketThread
,08-04 10:46:33.767  7553  8546 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1333)
,08-04 10:46:33.767  7553  8546 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 42511
,08-04 10:46:33.767  7553  8546 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-04 10:46:33.917  8512  8512 I wpa_supplicant: nl80211: Received scan results (31 BSSes)
08-04 10:46:33.917  8512  8512 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
08-04 10:46:33.917  8512  8512 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
08-04 10:46:33.917  8512  8512 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
08-04 10:46:33.917  8512  8512 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=5 BSSID=00.00.00 SSID=4E47373030
,08-04 10:46:33.927   746  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-04 10:46:33.927   746  1150 D SecContentProvider2: mCursor = null
,08-04 10:46:33.977  8512  8512 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
08-04 10:46:33.977  8512  8512 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=6 BSSID=00.00.00 SSID=4E47373030
,08-04 10:46:33.977  8512  8512 I wpa_supplicant: Associated with F4.99.3E
08-04 10:46:33.977  8512  8512 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
08-04 10:46:33.977  8512  8512 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=7 BSSID=F4.99.3E SSID=4E47373030
,08-04 10:46:33.987   746  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-04 10:46:33.987   746  1150 D SecContentProvider2: mCursor = null
,08-04 10:46:33.987   746  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-04 10:46:33.987   746  1150 D SecContentProvider2: mCursor = null
,08-04 10:46:33.997  8512  8512 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,08-04 10:46:33.997  8512  8512 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
08-04 10:46:33.997  8512  8512 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=8 BSSID=F4.99.3E SSID=4E47373030
,08-04 10:46:33.997  8512  8512 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-04 10:46:33.997  8512  8512 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
08-04 10:46:33.997  8512  8512 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=1 id_str=]
08-04 10:46:33.997  8512  8512 I wpa_supplicant: Blacklist: Clear (temp) 
08-04 10:46:33.997  8512  8512 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=9 BSSID=F4.99.3E SSID=4E47373030
,08-04 10:46:33.997   746  1150 D WifiNative-HAL: callSECApiVoid - ID [50]
,08-04 10:46:34.007  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-04 10:46:34.007  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 10:46:34.007   746  1150 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,08-04 10:46:34.007   746  1150 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-04 10:46:34.007   746  1152 D ConnectivityService: Got NetworkAgent Messenger
08-04 10:46:34.007   746  1152 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
08-04 10:46:34.007   746  1152 E ConnectivityService: updateNetworkInfo()
,08-04 10:46:34.007   746  1152 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 10:46:34.007   746  1152 D ConnectivityService: NetworkAgent connected
,08-04 10:46:34.017  1320  1320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-04 10:46:34.017  1320  1320 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-04 10:46:34.017   746  1426 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:34.017  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-04 10:46:34.027   746  1150 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,08-04 10:46:34.027   746  1471 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:34.027  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-04 10:46:34.027  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-04 10:46:34.027  1320  1320 I NearbySettings: MountReceiver.onReceive - Set preference state off
,08-04 10:46:34.027  1320  3147 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-04 10:46:34.037   305  1066 D CommandListener: Setting iface cfg
,08-04 10:46:34.037   746  1150 E WifiStateMachine: Start Dhcp Watchdog 3
,08-04 10:46:34.037   746  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-04 10:46:34.037   746  1150 D SecContentProvider2: mCursor = null
,08-04 10:46:34.047  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-04 10:46:34.047   746  1297 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:34.047  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 10:46:34.057   746  1152 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,08-04 10:46:34.057   746  1150 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,08-04 10:46:34.057   746  1150 D SecContentProvider2: mCursor = null
,08-04 10:46:34.057  7187  7187 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-04 10:46:34.137   746  1150 E native  : do suspend false
,08-04 10:46:34.137   746  1149 D WifiP2pService: InactiveState{ what=143375 }
,08-04 10:46:34.137   746  1149 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-04 10:46:34.267   310   310 E SMD     : DCD ON
,08-04 10:46:34.357  8551  8551 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-04 10:46:34.357  8551  8551 I dhcpcd  : version 5.5.6 starting
,08-04 10:46:34.357  8551  8551 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,08-04 10:46:34.417  8551  8551 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
08-04 10:46:34.417  8551  8551 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
08-04 10:46:34.427  8551  8551 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
08-04 10:46:34.427  8551  8551 I dhcpcd  : bssid match
08-04 10:46:34.427  8551  8551 I dhcpcd  : wlan0: rebinding lease of 192.168.1.122
,08-04 10:46:34.437  8551  8551 I dhcpcd  : wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,08-04 10:46:34.437  8551  8551 I dhcpcd  : wlan0: leased 192.168.1.122 for 172800 seconds
,08-04 10:46:34.437   746  1152 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,08-04 10:46:34.567   369   369 I ServiceManager: Waiting for service AtCmdFwd...
,08-04 10:46:34.747   746  1150 E native  : do suspend true
,08-04 10:46:34.757   746  1149 D WifiP2pService: InactiveState{ what=143375 }
,08-04 10:46:34.757   746  1149 D WifiP2pService: P2pEnabledState{ what=143375 }
,08-04 10:46:34.757   746  1152 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,08-04 10:46:34.757  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 10:46:34.757  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 10:46:34.757   746  1150 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-04 10:46:34.757   746  1150 E WifiStateMachine: VerifyingLinkState enter
,08-04 10:46:34.767   746  1150 D WifiNative-HAL: callSECApiInt - ID [210]
,08-04 10:46:34.767   746  1152 E ConnectivityService: updateNetworkInfo()
,08-04 10:46:34.767   746  1162 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,08-04 10:46:34.767   746  1152 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-04 10:46:34.767   746  1162 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-04 10:46:34.767   746  1162 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-04 10:46:34.767   746  1152 D ConnectivityService: Adding iface wlan0 to network 504
,08-04 10:46:34.767  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 10:46:34.767  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 10:46:34.777   746  1162 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
08-04 10:46:34.777   746  1162 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,08-04 10:46:34.777  7553  7621 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1334)
08-04 10:46:34.777  7553  7621 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1334)
,08-04 10:46:34.787   746  1150 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,08-04 10:46:34.787  1190  1190 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,08-04 10:46:34.797   746   746 I WifiTrafficPoller: evaluateTrafficStatsPolling
08-04 10:46:34.797  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,08-04 10:46:34.797   746   746 I WifiTrafficPoller: evaluateTrafficStatsPolling
,08-04 10:46:34.797   746   746 I WifiTrafficPoller: mBoosterFLAG : 0
,08-04 10:46:34.797   746   746 I WifiTrafficPoller: current booster mode : FullMode
08-04 10:46:34.797   746   746 D WifiNative-HAL: callSECApiVoid - ID [212]
08-04 10:46:34.797  7553  7621 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1339)
,08-04 10:46:34.797  7553  7621 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-04 10:46:34.797  1190  1190 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 10:46:34.797  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-04 10:46:34.797  7553  7621 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1340)
,08-04 10:46:34.797  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:34.797  1190  1190 D StatusBar.NetworkController: applyOpen
,08-04 10:46:34.807   746  1150 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,08-04 10:46:34.807  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:34.807  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:34.807  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:34.807  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:34.807  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,08-04 10:46:34.807  1190  1190 D StatusBar.NetworkController: applyOpen
,08-04 10:46:34.817  1320  1320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-04 10:46:34.817  1320  1320 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-04 10:46:34.817   746  1152 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,08-04 10:46:34.817   746  1152 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
,08-04 10:46:34.817   746  1152 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 504
,08-04 10:46:34.827   746  1152 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-04 10:46:34.827   746  1152 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
08-04 10:46:34.827   746  1152 D ConnectivityService: updateSourceRoutes : add src route for:192.168.1.122
,08-04 10:46:34.827   305  1066 V         : QcRouteController
,08-04 10:46:34.827   746  1471 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:34.827  7187  7187 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-04 10:46:34.837  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 10:46:34.837  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22dcfa77 added. We now have 2 listener(s)
,08-04 10:46:34.837  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,08-04 10:46:34.847  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-04 10:46:34.847  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:46:34.847  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:34.847  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b7116e4 added. We now have 9 listener(s)
08-04 10:46:34.847  7553  7621 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:46:34.847  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 10:46:34.847  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 10:46:34.847   305  1066 V         : QcRouteController
,08-04 10:46:34.847  7553  7621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:46:34.847  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:34.847  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:34.847  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:34.847  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:34.847  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:34.847  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:34.847  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:46:34.847  7553  7621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:46:34.847  7553  7621 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 10:46:34.847  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:34.847  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:34.847  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:46:34.857  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@214ba202 added. We now have 3 listener(s)
,08-04 10:46:34.857  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,08-04 10:46:34.857  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:46:34.857  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 10:46:34.857  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:34.857  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81cc713 added. We now have 10 listener(s)
08-04 10:46:34.857  7553  7621 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:46:34.857  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:34.857  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,08-04 10:46:34.857  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:34.857  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:34.857  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:34.857  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:46:34.857  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-04 10:46:34.857  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22dcfa77 removed from the list
08-04 10:46:34.857  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:34.857  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b7116e4 removed from the list
08-04 10:46:34.857  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:34.857  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:34.857  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:34.857  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:34.867  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:34.867  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:34.867  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-04 10:46:34.867  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b7116e4 not in the list
08-04 10:46:34.867  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:34.867  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:34.867  1320  1320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-04 10:46:34.867  1320  1320 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,08-04 10:46:34.867   746  1459 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:34.867  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,08-04 10:46:34.867  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:34.867  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:34.867  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:34.867   746  1718 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:34.867  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@81cc713 removed from the list
08-04 10:46:34.867  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:34.867  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:34.867  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:34.867  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-04 10:46:34.867  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@214ba202 removed from the list
08-04 10:46:34.867  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
08-04 10:46:34.867  1320  1320 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
08-04 10:46:34.867  1320  1320 I NearbySettings: MountReceiver.onReceive - Set preference state off
08-04 10:46:34.867  1320  3147 V NearbySettings: MountReceiver.mPrefHandler - 7002
,08-04 10:46:34.867  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-04 10:46:34.867  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49abd50 added. We now have 2 listener(s)
,08-04 10:46:34.877   746   762 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:34.877  7187  7187 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-04 10:46:34.877  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,08-04 10:46:34.877  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:46:34.877  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:46:34.877  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:34.877  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17712b49 added. We now have 9 listener(s)
08-04 10:46:34.877  7553  7621 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:46:34.877  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 10:46:34.887  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 10:46:34.887   305  1066 V         : QcRouteController
,08-04 10:46:34.887  7553  7621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:46:34.887  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:34.887  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:34.887  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:34.887  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:34.887  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:34.887  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:34.887  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:46:34.887  7553  7621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-04 10:46:34.887  7553  7621 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:46:34.887  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:46:34.887  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b82c16f added. We now have 3 listener(s)
,08-04 10:46:34.887  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:34.887  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
08-04 10:46:34.887  1320  1320 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,08-04 10:46:34.887  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:34.887  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:46:34.887  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 10:46:34.887  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:34.897  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38765e7c added. We now have 10 listener(s)
08-04 10:46:34.897  7553  7621 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:46:34.897  1320  1320 I NearbySettings: MountReceiver.onReceive - Keep current state
,08-04 10:46:34.897  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 10:46:34.897  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 10:46:34.897  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 10:46:34.897  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:34.897  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-04 10:46:34.897  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-04 10:46:34.897   746  1471 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,08-04 10:46:34.907   305  1066 V         : QcRouteController
,08-04 10:46:34.907  7553  7621 E BluetoothAdapter: bluetooth le advertising not supported
08-04 10:46:34.907  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 10:46:34.907  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 10:46:34.907   746   764 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:34.917  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-04 10:46:34.917  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 10:46:34.917  7187  7187 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,08-04 10:46:34.917  7553  7621 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-04 10:46:34.917  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:34.917  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-04 10:46:34.917  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:34.917  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:34.917  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:34.917  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:34.917  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:34.917  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:46:34.917  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:46:34.917  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49abd50 removed from the list
08-04 10:46:34.917  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:34.917  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17712b49 removed from the list
08-04 10:46:34.917  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:34.917  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:34.917  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:34.917  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:34.917  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:34.917  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:34.917  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:34.917  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@17712b49 not in the list
08-04 10:46:34.917  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:34.917  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:34.917  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:34.917  7553  7621 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:34.917  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:34.917  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:34.917  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:34.917  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38765e7c removed from the list
08-04 10:46:34.917  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:34.917  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:34.917  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:34.917  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:46:34.917  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b82c16f removed from the list
,08-04 10:46:34.917  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:46:34.917  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22a4058b added. We now have 2 listener(s)
,08-04 10:46:34.927  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
08-04 10:46:34.927  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:46:34.927  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:46:34.927  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:34.927  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e08e668 added. We now have 9 listener(s)
08-04 10:46:34.927  7553  7621 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:46:34.927  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 10:46:34.927  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 10:46:34.927   267   267 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
,08-04 10:46:34.937  7553  7621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:46:34.937  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:34.937  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:34.937  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:34.937  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:34.937  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:34.937  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:34.937  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:46:34.937   305  1066 V         : QcRouteController
,08-04 10:46:34.937  7553  7621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:46:34.937  7553  7621 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:46:34.937  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:46:34.937  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ded2726 added. We now have 3 listener(s)
,08-04 10:46:34.937  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:34.937  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:34.947   746  1401 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=746
,08-04 10:46:34.947  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
08-04 10:46:34.947  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:46:34.947  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 10:46:34.947  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:34.947  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d4b6f67 added. We now have 10 listener(s)
08-04 10:46:34.947  7553  7621 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:46:34.947  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,08-04 10:46:34.947  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 10:46:34.947  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 10:46:34.947  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-04 10:46:34.947  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:34.947  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-04 10:46:34.957   305  1066 V         : QcRouteController
,08-04 10:46:34.957  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-04 10:46:34.957   305  1066 V         : QcRouteController
,08-04 10:46:34.957  7553  7621 E BluetoothAdapter: bluetooth le advertising not supported
08-04 10:46:34.957  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 10:46:34.957  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 10:46:34.957  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-04 10:46:34.957  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 10:46:34.957  7553  7621 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-04 10:46:34.957  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:34.957  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:34.957  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:34.957  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:34.957  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:34.957  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:46:34.957  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:46:34.967  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@22a4058b removed from the list
08-04 10:46:34.967  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:34.967  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e08e668 removed from the list
08-04 10:46:34.967  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:34.967  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:34.967  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:34.967  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:34.967  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:34.967  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:34.967  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:34.967  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e08e668 not in the list
08-04 10:46:34.967  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:34.967  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:34.967  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:34.967  7553  7621 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:34.967  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:34.967  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:34.967  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:34.967  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d4b6f67 removed from the list
08-04 10:46:34.967  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:34.967  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:34.967  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:34.967  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:46:34.967  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ded2726 removed from the list
,08-04 10:46:34.967  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:46:34.967  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28748fb2 added. We now have 2 listener(s)
,08-04 10:46:34.967  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
08-04 10:46:34.967  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:46:34.967  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:46:34.967  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:34.967  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13159b03 added. We now have 9 listener(s)
08-04 10:46:34.967  7553  7621 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 10:46:34.967  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 10:46:34.967  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-04 10:46:34.967  7553  7621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:46:34.967  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:34.967  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:34.967  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:34.967  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:34.967  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:34.967  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:34.967  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-04 10:46:34.977  7553  7621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:46:34.977  7553  7621 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:46:34.977  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:46:34.977  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4de78b9 added. We now have 3 listener(s)
,08-04 10:46:34.977  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:34.977  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 10:46:34.977   305  1066 V         : QcRouteController
,08-04 10:46:34.977  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
08-04 10:46:34.977  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:46:34.977  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:46:34.977  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:34.977  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3397f4fe added. We now have 10 listener(s)
08-04 10:46:34.977  7553  7621 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:46:34.977  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 10:46:34.977  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-04 10:46:34.977  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-04 10:46:34.977  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:34.977  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-04 10:46:34.977  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-04 10:46:34.987  7553  7621 E BluetoothAdapter: bluetooth le advertising not supported
,08-04 10:46:34.987  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-04 10:46:34.987  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-04 10:46:34.987  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-04 10:46:34.987  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-04 10:46:34.987  7553  7621 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-04 10:46:34.987  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-04 10:46:34.987  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:34.987  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:34.987  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:34.987  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:34.987  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:46:34.987  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:46:34.987  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28748fb2 removed from the list
,08-04 10:46:34.987  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:34.987  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13159b03 removed from the list
08-04 10:46:34.987  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:34.987  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:34.987  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:34.987  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-04 10:46:34.987  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:34.987  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:34.987  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:34.987  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@13159b03 not in the list
,08-04 10:46:34.987  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:34.987  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:34.987  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:34.987  7553  7621 D BluetoothLeScanner: could not find callback wrapper
08-04 10:46:34.997  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-04 10:46:34.997  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:34.997  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:34.997  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3397f4fe removed from the list
08-04 10:46:34.997  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:34.997  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:34.997  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:34.997  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:46:34.997  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4de78b9 removed from the list
08-04 10:46:34.997  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:46:34.997  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1964e775 added. We now have 2 listener(s)
08-04 10:46:34.997  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
08-04 10:46:34.997  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:46:34.997  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:46:34.997   746  1152 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
08-04 10:46:34.997  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:34.997   746  1152 D ConnectivityService: LTETest block dns file not exists
08-04 10:46:34.997  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fa630a added. We now have 9 listener(s)
08-04 10:46:34.997  7553  7621 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:46:34.997  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-04 10:46:34.997   746  1152 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
08-04 10:46:34.997   746  1152 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
08-04 10:46:34.997   746  1152 D ConnectivityService: calling update connectivity
08-04 10:46:34.997   746  1152 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
08-04 10:46:34.997   746  1152 E ConnectivityService: updateNetworkInfo()
08-04 10:46:34.997   746  1152 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
08-04 10:46:34.997   746  1152 E ConnectivityService: updateNetworkInfo()
08-04 10:46:34.997   746  1152 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 10:46:34.997   746  1152 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
08-04 10:46:34.997   746  1152 D ConnectivityService: calling update connectivity
08-04 10:46:34.997   746  1152 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-04 10:46:34.997   746  1152 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 10:46:34.997   746  1152 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 10:46:34.997   746  1152 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:34.997   746  1152 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:34.997   746  1028 D EntConnectivity: Not allowed due to - mEnabled false
08-04 10:46:34.997   746  8547 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:34.997   746  8547 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
08-04 10:46:34.997   746  8547 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-04 10:46:34.997   746  8547 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-04 10:46:34.997   746  8547 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
08-04 10:46:35.007  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 10:46:35.007  7553  7621 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 10:46:35.007  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:35.007  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:35.007  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:35.007  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:35.007  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-04 10:46:35.007  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-04 10:46:35.007  7553  7621 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-04 10:46:35.007   746  1152 D ConnectivityService: currentScore = 0, newScore = 60
08-04 10:46:35.007   746  1152 D ConnectivityService:    accepting network in place of null
08-04 10:46:35.007   746  1152 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:35.007  1402  1402 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:35.007  7553  7621 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-04 10:46:35.007   746  1152 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-04 10:46:35.007   746  1152 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
08-04 10:46:35.007   746  1152 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-04 10:46:35.007  7553  7621 D io.jxcore.node.ConnectivityMonitor: start: OK
08-04 10:46:35.007  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-04 10:46:35.007   746  1152 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
08-04 10:46:35.007  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3976b998 added. We now have 3 listener(s)
08-04 10:46:35.007   746  1298 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.007   746  1152 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
08-04 10:46:35.007   746  1153 D Tethering: MasterInitialState.processMessage what=3
08-04 10:46:35.007   746   746 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-04 10:46:35.007   746  1154 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
08-04 10:46:35.007   746  1154 D SmartBondingService: getSBEnabled() enabled =false
08-04 10:46:35.007   746  1154 D SmartBondingService: getSBEnabled() enabled =false
08-04 10:46:35.007   746  1154 D SmartBondingService: getSBEnabled() enabled =false
08-04 10:46:35.007   746  1147 V NetworkStats: updateIfacesLocked()
08-04 10:46:35.007   746  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:35.007   746  1147 V NetworkStats: performPollLocked(flags=0x1)
08-04 10:46:35.017   746  1471 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.017   746  1028 D EntConnectivity: Not allowed due to - mEnabled false
08-04 10:46:35.017   746  1152 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-04 10:46:35.017   746  1152 D ConnectivityService: calling update connectivity
08-04 10:46:35.017   746  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:35.017   746  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 10:46:35.017   746  1154 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
08-04 10:46:35.017   746  1148 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:35.017  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-04 10:46:35.017  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 10:46:35.017  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-04 10:46:35.017  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 10:46:35.017  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 10:46:35.017  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:35.017  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 10:46:35.017  7553  7553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-04 10:46:35.017   746  1152 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 10:46:35.017   746  1148 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:35.017  1190  1594 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-04 10:46:35.017  1190  1190 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-04 10:46:35.017  1190  1190 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-04 10:46:35.017   746  1147 D NetworkStatsFactory: UpdateStatsForKnox
08-04 10:46:35.017  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
08-04 10:46:35.017  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 10:46:35.017   746  1147 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.017  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-04 10:46:35.017  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-04 10:46:35.017  7553  7553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-04 10:46:35.017  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a985f1 added. We now have 10 listener(s)
08-04 10:46:35.017  7553  7621 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-04 10:46:35.017   746  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:35.017   746  1461 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.017  1190  1190 D StatusBar.NetworkController: updateDataNetType()
08-04 10:46:35.017  1190  1190 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-04 10:46:35.017  7553  7621 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-04 10:46:35.017  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:35.017  7553  7621 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-04 10:46:35.017  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:35.017  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:35.017  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-04 10:46:35.017  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:46:35.017  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1964e775 removed from the list
08-04 10:46:35.017  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:35.017  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fa630a removed from the list
08-04 10:46:35.017  7553  7553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-04 10:46:35.017  7553  7621 D io.jxcore.node.ConnectivityMonitor: stop
08-04 10:46:35.017  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:35.017   746  1152 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:35.017   746  1148 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:35.017  1190  1190 E StatusBar.NetworkController: updateLTEICONDataNetType:0
08-04 10:46:35.017   746  1148 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
08-04 10:46:35.017   746  1148 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:35.017  4674  7399 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-04 10:46:35.017  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:35.017  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:35.017   746  1147 V NetworkStats: performPollLocked() took 7ms
08-04 10:46:35.017   746  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:35.017  1190  1190 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
08-04 10:46:35.017  1190  1190 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-04 10:46:35.017  1190  1190 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-04 10:46:35.017  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:35.017  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:35.017  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:35.017  7553  7621 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7fa630a not in the list
08-04 10:46:35.017  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:35.017  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:35.017  1190  1190 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 10:46:35.017  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
08-04 10:46:35.017  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:35.017  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:35.017  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:35.017  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:35.017  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:35.017  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:35.017  1190  1190 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
08-04 10:46:35.017  1190  1190 D StatusBar.NetworkController: applyOpen
08-04 10:46:35.017   746  1444 I AudioService: getStreamVolume 3 index 0
08-04 10:46:35.017  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-04 10:46:35.017  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-04 10:46:35.017  7553  7621 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 10:46:35.017  7553  7621 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7a985f1 removed from the list
08-04 10:46:35.017  7553  7621 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-04 10:46:35.017  7553  7621 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 10:46:35.017  7553  7621 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 10:46:35.017  7553  7621 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 10:46:35.017  7553  7621 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3976b998 removed from the list
08-04 10:46:35.017  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-04 10:46:35.017  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-04 10:46:35.017  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-04 10:46:35.017  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-04 10:46:35.017  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-04 10:46:35.027  7553  7621 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-04 10:46:35.027   746  1148 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:35.027   746  1148 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:35.027  7553  8623 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1347, name: My test thread name)
08-04 10:46:35.027  7553  8623 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1347, thread name: My test thread name)
08-04 10:46:35.027  7553  8623 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1347, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-04 10:46:35.037  7553  8624 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1349, name: My test thread name)
08-04 10:46:35.037  7553  8624 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1349, thread name: My test thread name)
08-04 10:46:35.037  7553  8624 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1349, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
08-04 10:46:35.037  7553  7621 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-04 10:46:35.037  7553  7621 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-04 10:46:35.037  7553  7621 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-04 10:46:35.037  7553  7621 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-04 10:46:35.037  7553  7621 D com.test.thalitest.ThaliTestRunner: Total duration: 23826 ms
08-04 10:46:35.037  7553  7621 I jxcore-log: Total number of executed tests:  80
08-04 10:46:35.037  7553  7621 I jxcore-log: 
08-04 10:46:35.037  7553  7621 I jxcore-log: Number of passed tests:  80
08-04 10:46:35.037  7553  7621 I jxcore-log: 
08-04 10:46:35.037  7553  7621 I jxcore-log: Number of failed tests:  0
08-04 10:46:35.037  7553  7621 I jxcore-log: 
08-04 10:46:35.037  7553  7621 I jxcore-log: Number of ignored tests:  0
08-04 10:46:35.037  7553  7621 I jxcore-log: 
08-04 10:46:35.037  7553  7621 I jxcore-log: Total duration:  23826
08-04 10:46:35.037  7553  7621 I jxcore-log: 
08-04 10:46:35.037  7553  7621 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-04 10:46:35.037  7553  7621 I jxcore-log: 
08-04 10:46:35.037  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:46:35.037  7553  7621 I jxcore-log: 
08-04 10:46:35.037  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:46:35.037  7553  7621 I jxcore-log: 
08-04 10:46:35.047  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:46:35.047  7553  7621 I jxcore-log: 
08-04 10:46:35.047  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:46:35.047  7553  7621 I jxcore-log: 
08-04 10:46:35.047  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:46:35.047  7553  7621 I jxcore-log: 
08-04 10:46:35.047  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:46:35.047  7553  7621 I jxcore-log: 
08-04 10:46:35.047  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:46:35.047  7553  7621 I jxcore-log: 
08-04 10:46:35.047  7553  7553 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-04 10:46:35.047  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 10:46:35.047  7553  7621 I jxcore-log: 
08-04 10:46:35.047  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 10:46:35.047  7553  7621 I jxcore-log: 
08-04 10:46:35.047  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-04 10:46:35.047  7553  7621 I jxcore-log: 
08-04 10:46:35.047  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 10:46:35.047  7553  7621 I jxcore-log: 
08-04 10:46:35.047  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-04 10:46:35.047  7553  7621 I jxcore-log: 
08-04 10:46:35.057  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 10:46:35.057  7553  7621 I jxcore-log: 
08-04 10:46:35.057  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 10:46:35.057  7553  7621 I jxcore-log: 
,08-04 10:46:35.057  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 10:46:35.057  7553  7621 I jxcore-log: 
08-04 10:46:35.057  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 10:46:35.057  7553  7621 I jxcore-log: 
08-04 10:46:35.057  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 10:46:35.057  7553  7621 I jxcore-log: 
08-04 10:46:35.057  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-04 10:46:35.057  7553  7621 I jxcore-log: 
08-04 10:46:35.057  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 10:46:35.057  7553  7621 I jxcore-log: 
08-04 10:46:35.057  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-04 10:46:35.057  7553  7621 I jxcore-log: 
08-04 10:46:35.057  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 10:46:35.057  7553  7621 I jxcore-log: 
08-04 10:46:35.057  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 10:46:35.057  7553  7621 I jxcore-log: 
08-04 10:46:35.057  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 10:46:35.057  7553  7621 I jxcore-log: 
08-04 10:46:35.057  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 10:46:35.057  7553  7621 I jxcore-log: 
08-04 10:46:35.057  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 10:46:35.057  7553  7621 I jxcore-log: 
08-04 10:46:35.057  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 10:46:35.057  7553  7621 I jxcore-log: 
08-04 10:46:35.057  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-04 10:46:35.057  7553  7621 I jxcore-log: 
08-04 10:46:35.057  7553  7621 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-04 10:46:35.057  7553  7621 I jxcore-log: 
08-04 10:46:35.087   746  8547 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,08-04 10:46:35.167   746  8547 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 04 Aug 2016 08:46:35 GMT], X-Android-Received-Millis=[1470300395180], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1470300395137]}
08-04 10:46:35.167   746  8547 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-04 10:46:35.167   746  8547 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,08-04 10:46:35.167   746  1152 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
08-04 10:46:35.167   746  1152 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
08-04 10:46:35.167   746  1152 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-04 10:46:35.167   746  1152 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 10:46:35.167   746  1152 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:35.167   746  1152 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
08-04 10:46:35.167   746  1152 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
08-04 10:46:35.167   746  1152 D ConnectivityService: calling update connectivity
08-04 10:46:35.167   746  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:35.167   746  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-04 10:46:35.167   746  1152 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-04 10:46:35.167  1190  1594 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-04 10:46:35.167   746  1152 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:35.167  4674  7399 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-04 10:46:35.167   746  1152 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-04 10:46:35.167   746  1152 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-04 10:46:35.167   746  1426 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:35.167  1190  1190 D StatusBar.NetworkController: getUpdateDataNetType(): 0
08-04 10:46:35.167  1190  1190 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
08-04 10:46:35.167  1190  1190 D StatusBar.NetworkController: updateDataNetType()
08-04 10:46:35.167  1190  1190 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
08-04 10:46:35.167  1190  1190 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,08-04 10:46:35.177  1190  1190 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false,
08-04 10:46:35.177  1190  1190 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
08-04 10:46:35.177  1190  1190 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
08-04 10:46:35.177  1190  1190 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020509/com.android.systemui:drawable/stat_sys_signal_no_inout mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
08-04 10:46:35.177  1190  1190 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,08-04 10:46:35.307  8625  8625 D AndroidRuntime: 
08-04 10:46:35.307  8625  8625 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-04 10:46:35.307  8625  8625 D AndroidRuntime: CheckJNI is OFF
,08-04 10:46:35.307  8625  8625 D AndroidRuntime: readGMSProperty: start
,08-04 10:46:35.307  8625  8625 D AndroidRuntime: readGMSProperty: already setted!!
,08-04 10:46:35.307  8625  8625 D AndroidRuntime: readGMSProperty: end
08-04 10:46:35.307  8625  8625 D AndroidRuntime: addProductProperty: start
,08-04 10:46:35.437  8625  8625 E AffinityControl: AffinityControl: registerfunction enter
,08-04 10:46:35.457  8625  8625 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-04 10:46:35.467   746   762 D PackageManager: START PACKAGE DELETE: observer{1060399259}
08-04 10:46:35.467   746   762 D PackageManager: pkg{<packageName>}
08-04 10:46:35.467   746   762 D PackageManager: user{0}
08-04 10:46:35.467   746   762 D PackageManager: caller{2000}
08-04 10:46:35.467   746   762 D PackageManager: flags{2}
,08-04 10:46:35.467   746   762 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-04 10:46:35.467   746   762 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
,08-04 10:46:35.467   746   762 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
08-04 10:46:35.467   746   762 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-04 10:46:35.467   746   762 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-04 10:46:35.467   746  1052 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
,08-04 10:46:35.467   746  1052 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-04 10:46:35.467   746  1052 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
08-04 10:46:35.467   746  1052 D ApplicationPolicy: getApplicationUninstallationEnabled
,08-04 10:46:35.467   746  1052 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-04 10:46:35.477   746  1052 D PackageManager: !@killApplicatoin: 10079, uninstall pkg
08-04 10:46:35.477   746   915 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
,08-04 10:46:35.477   746   915 I ActivityManager: Killing 7553:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-04 10:46:35.477   746   915 I ActivityManager:   Force finishing activity ActivityRecord{3510508c u0 com.test.thalitest/.MainActivity t99}
,08-04 10:46:35.477   746   915 D FocusedStackFrame: Set to : 0
,08-04 10:46:35.477   746  1030 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-04 10:46:35.477   746  1030 D PointerIcon: setMouseCustomIcon IconType is same.101
08-04 10:46:35.477   746  1030 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-04 10:46:35.477   746  1030 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-04 10:46:35.487   267   323 I SurfaceFlinger: id=12 Removed NainActivit (6/9)
,08-04 10:46:35.487   267   336 I SurfaceFlinger: id=12 Removed NainActivit (-2/9)
,08-04 10:46:35.507   746  1152 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:46:35.577   369   369 I ServiceManager: Waiting for service AtCmdFwd...
,08-04 10:46:35.577   746  1052 W PackageSettings: Skipping PackageSetting{18d1e948 com.example.hello/10078} due to missing metadata
,08-04 10:46:35.597   746  3312 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:35.597   746   746 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.597   746   746 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:35.597   746   746 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:46:35.607   746   746 D SmartBondingService: SmartBondingReceiver: wifi is connected
08-04 10:46:35.607   746   746 D SmartBondingService: SmartBondingReceiver: wifi ap is not changed
08-04 10:46:35.607   746  1461 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.607   746   746 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:35.607   746   746 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.607   746  1154 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
08-04 10:46:35.607   746  1154 D SmartBondingService: getSBEnabled() enabled =false
08-04 10:46:35.607   746  1154 D SmartBondingService: getSBEnabled() enabled =false
,08-04 10:46:35.607   746  1154 D SmartBondingService: getSBEnabled() enabled =false
,08-04 10:46:35.607   746   746 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:35.607   746   746 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.607   746   746 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:35.607   746  1145 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:35.607   746  1145 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:35.607   746  1154 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,08-04 10:46:35.617  1574  1574 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,08-04 10:46:35.617   746  1366 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:35.617   746   902 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.617   746   762 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.617   746  1696 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.617   746  1718 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:35.617   746  1455 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.617   746  1471 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.617   746  1435 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:35.627   746  1718 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:35.627   746  1297 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:35.627   746  3312 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:35.627   746  1444 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:35.637  7823  7823 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-04 10:46:35.637  6932  6932 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
,08-04 10:46:35.637  6932  6932 I PCWCLIENTTRACE_PushUtil: sales region : global
,08-04 10:46:35.637  6932  6932 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-04 10:46:35.637  6932  6932 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:46:35.647   746  1426 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:35.647   746   902 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:46:35.647   746   902 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:35.667  7823  7823 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,08-04 10:46:35.667   746  1426 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-04 10:46:35.667   746  1426 D SecContentProvider2: mCursor = null
,08-04 10:46:35.667   746  1052 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=0: pkg removed
,08-04 10:46:35.697   746  3120 E libprocessgroup: failed to kill 1 processes for processgroup 7553
,08-04 10:46:35.697  3890  3890 I art     : Explicit concurrent mark sweep GC freed 5482(303KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 15MB/26MB, paused 358us total 18.273ms
,08-04 10:46:35.707  6502  6502 I art     : Explicit concurrent mark sweep GC freed 638(36KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 330us total 16.166ms
,08-04 10:46:35.707   746   746 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,08-04 10:46:35.707   746  1030 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,08-04 10:46:35.717  4674  4674 I art     : Explicit concurrent mark sweep GC freed 3373(157KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 24MB/40MB, paused 575us total 35.203ms
,08-04 10:46:35.717   746  1123 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-04 10:46:35.717  1942  2361 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-04 10:46:35.717   746   746 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,08-04 10:46:35.717  1688  1688 E SamsungIME: mOCRHelper is null
08-04 10:46:35.727   746   902 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,08-04 10:46:35.727  1574  1574 I art     : Explicit concurrent mark sweep GC freed 917(47KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 19MB/33MB, paused 2.380ms total 48.576ms
,08-04 10:46:35.727  1419  1419 D ResourcesManager: creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
,08-04 10:46:35.727   746   746 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,08-04 10:46:35.727  1419  1419 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-04 10:46:35.727  1419  1419 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-04 10:46:35.727  1419  1419 D ResourcesManager: creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
,08-04 10:46:35.737   746   746 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,08-04 10:46:35.737  1419  1419 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-04 10:46:35.737  1419  1419 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-04 10:46:35.737  1419  1419 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-04 10:46:35.737  1419  1419 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,08-04 10:46:35.737   746   746 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,08-04 10:46:35.737  1419  1419 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-04 10:46:35.737  1419  1419 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-04 10:46:35.737  7187  7187 I art     : Explicit concurrent mark sweep GC freed 6263(422KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 16MB/21MB, paused 800us total 63.025ms
,08-04 10:46:35.747   746   746 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,08-04 10:46:35.757  1388  1388 D RegisteredServicesCache: empty dynamic service
,08-04 10:46:35.757   746   746 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,08-04 10:46:35.757   746   746 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,08-04 10:46:35.757  7884  7884 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:46:35.757  7884  7884 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
08-04 10:46:35.767   746   746 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,08-04 10:46:35.767   746   902 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,08-04 10:46:35.767   746   746 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,08-04 10:46:35.777   746   746 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,08-04 10:46:35.787   746  1147 V NetworkStats: removeUidsLocked() for UIDs [10079]
08-04 10:46:35.787   746  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:35.787   746  1147 V NetworkStats: performPollLocked(flags=0x3)
,08-04 10:46:35.787   746  1147 D NetworkStatsFactory: UpdateStatsForKnox
,08-04 10:46:35.787   746  1147 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:35.787   746  1147 V NetworkStats: performPollLocked() took 5ms
08-04 10:46:35.787   746  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 10:46:35.807   746   746 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,08-04 10:46:35.847   746   746 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,08-04 10:46:35.847   746   746 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,08-04 10:46:35.857   746   746 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,08-04 10:46:35.857   746   746 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,08-04 10:46:35.857   746  1148 D NtpTrustedTime: currentTimeMillis() cache hit
08-04 10:46:35.857   746  1148 D NtpTrustedTime: currentTimeMillis() cache hit
,08-04 10:46:35.857   746   746 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
,08-04 10:46:35.867   746   746 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,08-04 10:46:35.867   746   902 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
,08-04 10:46:35.877   746   746 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,08-04 10:46:35.877   746   746 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,08-04 10:46:35.897   746   746 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,08-04 10:46:35.897   746   746 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,08-04 10:46:35.897   746  1471 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-04 10:46:35.897   746  1471 D SecContentProvider2: mCursor = null
,08-04 10:46:35.907   746   746 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,08-04 10:46:35.917   746   746 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,08-04 10:46:35.917   746   746 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,08-04 10:46:35.927  7906  7906 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,08-04 10:46:35.927   746   746 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,08-04 10:46:35.927   746   902 D EnterpriseDeviceManagerService: Package has changed for user 0
08-04 10:46:35.927   746   902 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-04 10:46:35.927   746   746 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
,08-04 10:46:35.937  7906  7906 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,08-04 10:46:35.947  7906  7906 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,08-04 10:46:35.947  2494  2494 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
08-04 10:46:35.947   746   746 D RCPManagerService: PackageReceiver onReceive()
08-04 10:46:35.947   746   902 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
08-04 10:46:35.947   746   746 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-04 10:46:35.957  2494  2494 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1470300395965
,08-04 10:46:35.957   746   746 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,08-04 10:46:35.957  2494  2494 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
08-04 10:46:35.957   746   762 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.957   746   746 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-04 10:46:35.957   746  1459 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:35.957   746   746 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-04 10:46:35.957   746   746 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-04 10:46:35.957   746   746 V EnterpriseBillingPolicy: uID is 10079
08-04 10:46:35.957   746   746 V EnterpriseBillingPolicy: Removed Packageuid is0
08-04 10:46:35.957   746   746 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-04 10:46:35.957  2494  2494 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
08-04 10:46:35.957   746   746 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
08-04 10:46:35.957   746   746 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
08-04 10:46:35.957   746   746 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
08-04 10:46:35.957   746   746 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-04 10:46:35.957  2494  2494 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().START
08-04 10:46:35.957   746   746 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-04 10:46:35.957   746   902 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 10:46:35.957  2494  2494 I KLMS-2.4.511: : NetworkChangeOperations(): uploadRequestLog().START 
,08-04 10:46:35.957   746  1179 D TaskPersister: removeObsoleteFile: deleting file=99_task.xml
,08-04 10:46:35.957   746   746 V AlarmManagerEXT: com.test.thalitest(10079) is removed.
,08-04 10:46:35.967  2494  2494 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,08-04 10:46:35.967   746   902 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 10:46:35.967   746   902 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,08-04 10:46:35.967   746  1444 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:35.987   746   902 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 10:46:35.987   746   902 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,08-04 10:46:35.987   746   762 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,08-04 10:46:35.987   746   762 D ActivityManager: caller:android.app.ApplicationThreadProxy@bcf7c6c, r.packageName :com.samsung.android.app.galaxyfinder
,08-04 10:46:35.987  7947  7947 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
,08-04 10:46:35.997   746   902 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
08-04 10:46:35.997   746   902 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,08-04 10:46:36.007   746   902 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 10:46:36.007   746   902 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 10:46:36.007   746   902 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 10:46:36.007   746   902 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,08-04 10:46:36.017   746   902 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 10:46:36.017   746  1152 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,08-04 10:46:36.017   746   902 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,08-04 10:46:36.027   746   902 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 10:46:36.027   746   902 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 10:46:36.027   746   902 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,08-04 10:46:36.037  7965  7965 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,08-04 10:46:36.037   746  3312 I SQLiteConnectionPool: exportDB...
,08-04 10:46:36.037   746  1145 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.037  7981  7981 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
08-04 10:46:36.037  3737  8656 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
08-04 10:46:36.037  3737  8656 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,08-04 10:46:36.037   746   902 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
08-04 10:46:36.037   746   902 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-04 10:46:36.037  3737  8656 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
08-04 10:46:36.037  7981  7981 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
08-04 10:46:36.037  7981  7981 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
08-04 10:46:36.037   746   902 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-04 10:46:36.037  7981  7981 I SA      : [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,08-04 10:46:36.037  7981  7981 I SA      : [OR] == isSIMCardReady false ==
,08-04 10:46:36.037   746  1435 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.047  7981  7981 I SA      : [SCU] == networkStateCheck == true
,08-04 10:46:36.047  7981  7981 I SA      : [DM] getCountryCodeFromCSC : PL
08-04 10:46:36.047  7981  7981 I SA      : isChinaCountryCode : false
08-04 10:46:36.047  7981  7981 I SA      : [SCU] is ChinestModel Data Restricted   : false
08-04 10:46:36.047  7981  7981 I SA      : [OR] == networkStateCheck true ==
,08-04 10:46:36.047   746   902 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 10:46:36.047   746   902 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
08-04 10:46:36.047  7981  7981 I SA      : [OR] GetMyCountryZoneTask
,08-04 10:46:36.047  7981  7981 I SA      : [OR] onReceive END
,08-04 10:46:36.047   746   902 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
,08-04 10:46:36.057   746   762 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.057   746  1459 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,08-04 10:46:36.057   746  1459 D ActivityManager: caller:android.app.ApplicationThreadProxy@1f759f34, r.packageName :com.android.providers.downloads
08-04 10:46:36.057   746   902 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,08-04 10:46:36.057  7981  8657 I SA      : [SRS] prepareGetMyCountryZone
,08-04 10:46:36.067  8003  8003 I SCloudBackupReceiver: Other Intent
,08-04 10:46:36.067  7333  7333 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
08-04 10:46:36.067  7333  7333 I KnoxUsageLogPro: premStatus:2
,08-04 10:46:36.077  7333  7333 I KnoxUsageLogPro: isEulaShown : false
08-04 10:46:36.077  7333  7333 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,08-04 10:46:36.077  3737  8656 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
,08-04 10:46:36.077  7981  8657 I SA      : [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,08-04 10:46:36.077  3737  8656 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
,08-04 10:46:36.077  3737  8656 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,08-04 10:46:36.077  3737  8656 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,08-04 10:46:36.077  3737  8656 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,08-04 10:46:36.077  7981  8657 I SA      : [SSP] query invoked
,08-04 10:46:36.077  3737  8656 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,08-04 10:46:36.077  3737  8656 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,08-04 10:46:36.087  7981  8657 I SA      : [TPMU] GetMccFromDB : null
,08-04 10:46:36.087  3737  8656 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,08-04 10:46:36.097  7981  8657 I SA      : [SCU] getMccFromPreferece mcc = 260
,08-04 10:46:36.097  7981  8657 I SA      : [TPM] isNoProxy(default) : true
,08-04 10:46:36.097   746   902 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
08-04 10:46:36.097   746  1298 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.107   746  1052 I art     : Explicit concurrent mark sweep GC freed 83466(5MB) AllocSpace objects, 16(256KB) LOS objects, 29% free, 38MB/54MB, paused 3.240ms total 320.541ms
,08-04 10:46:36.107  7981  8657 E File    : fail readDirectory() errno=2
,08-04 10:46:36.107  3737  8656 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,08-04 10:46:36.107   746  1459 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.117   746   762 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.117   746   902 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,08-04 10:46:36.127   746  3312 I SQLiteConnectionPool: ...exportDB
,08-04 10:46:36.127  8104  8104 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,08-04 10:46:36.127   746  3312 D SSRM:aY : MSG_TYPE_APP_REMOVED::
,08-04 10:46:36.137  8104  8104 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,08-04 10:46:36.137  8104  8104 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,08-04 10:46:36.147   746  1052 D PackageManager: delete codoeFile: 
,08-04 10:46:36.147   746  1298 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:36.147   746   764 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.147   746  1461 D RCPManagerService: exchangeData() failure , invalid userId
,08-04 10:46:36.147   746  1455 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.147   746  1297 D RCPManagerService: exchangeData() failure , invalid userId
08-04 10:46:36.147  3737  8656 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,08-04 10:46:36.157   746  1052 D AASAuninstall: userId = 0, info.removedAppID = 10079, info.uid = 10079, packageName = com.test.thalitest
,08-04 10:46:36.157   746  1052 I AASA_removePackage: UID=10079 Target=com.test.thalitest
,08-04 10:46:36.177   746  1052 D PackageManager: result of delete: 1{1060399259}
,08-04 10:46:36.177  8625  8625 D AndroidRuntime: Shutting down VM
,08-04 10:46:36.187   746  1471 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.187  7624  7624 D SecurityLogAgent: KnoxConfiguration : Current State = 1
08-04 10:46:36.187  7624  7624 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
08-04 10:46:36.187  7624  7624 D SecurityLogAgent: StateMachine : Current State = 1
08-04 10:46:36.187   746  1459 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.187  7624  7624 D SecurityLogAgent: StateMachine : Changed Current State = 1
08-04 10:46:36.187   746   902 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 10:46:36.187   746  1052 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-04 10:46:36.187   746  1052 D PackageManager: userId{-1}
08-04 10:46:36.187   746  1052 D PackageManager: andCode{true}
,08-04 10:46:36.187   746   902 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,08-04 10:46:36.187   746  1145 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.187   746  1426 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.197   746   902 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 10:46:36.197   746   902 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,08-04 10:46:36.197   746  1052 D ActivityManager: caller:null, r.packageName :com.android.defcontainer
,08-04 10:46:36.197   746  1052 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:36.197   746  1052 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:36.197   746  1052 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:36.197   746  1052 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:36.197   746   902 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 10:46:36.197   746   902 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-04 10:46:36.197   746   902 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,08-04 10:46:36.197   746   902 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 10:46:36.207   746   902 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,08-04 10:46:36.207   746   902 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 10:46:36.207   746   902 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-04 10:46:36.207   746   902 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,08-04 10:46:36.207   746   902 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 10:46:36.207   746   902 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-04 10:46:36.207   746   902 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,08-04 10:46:36.207   746   902 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-04 10:46:36.237  8665  8665 E Zygote  : MountEmulatedStorage()
08-04 10:46:36.237  8665  8665 E Zygote  : v2
08-04 10:46:36.237  8665  8665 I libpersona: KNOX_SDCARD checking this for 10007
08-04 10:46:36.237  8665  8665 I libpersona: KNOX_SDCARD not a persona
,08-04 10:46:36.247   746  1052 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8665 uid=10007 gids={50007, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-04 10:46:36.247   746  1366 D ActivityManager: startService callerProcessName:com.sec.android.app.SmartClipService, calleePkgName: com.sec.android.app.SmartClipService
08-04 10:46:36.247   746  1366 D ActivityManager: caller:android.app.ApplicationThreadProxy@34ac6c82, r.packageName :com.sec.android.app.SmartClipService
,08-04 10:46:36.247   746   902 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
08-04 10:46:36.247   746   902 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-04 10:46:36.257  8665  8665 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,08-04 10:46:36.257  8665  8665 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 10:46:36.257  8665  8665 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 10:46:36.257   746  1471 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,08-04 10:46:36.257   746  1471 D ActivityManager: caller:android.app.ApplicationThreadProxy@2505ff93, r.packageName :com.google.android.gms
,08-04 10:46:36.257   746  1401 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:36.257   746  1145 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.257   746  1459 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.257   746  1435 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.257   746   764 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.267   746  1298 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:36.267  4674  4674 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,08-04 10:46:36.267  4674  5582 I iu.UploadsManager: num queued entries: 0
,08-04 10:46:36.267  4674  5582 I iu.UploadsManager: num updated entries: 0
08-04 10:46:36.267  4674  5582 I iu.SyncManager: NEXT; no task
,08-04 10:46:36.277   746   762 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.277  7249  7249 D WaitQueueForNetworkActivate: notifyNetworkActivated
,08-04 10:46:36.287  8665  8665 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:36.287  8665  8665 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:36.297  8665  8665 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DefaultContainerService/DefaultContainerService.apk
,08-04 10:46:36.307  1419  1419 D SurfaceWidgetView: destroyHardwareResources():1033425470
,08-04 10:46:36.307   746   762 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-04 10:46:36.307   746   762 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
08-04 10:46:36.307   746   762 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-04 10:46:36.307   746   762 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-04 10:46:36.307   746   762 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,08-04 10:46:36.317  1419  1419 D Launcher: onRestart, Launcher: 309767335
08-04 10:46:36.317  1419  1419 D Launcher: onStart, Launcher: 309767335
08-04 10:46:36.317  1419  1419 D Launcher.HomeView: onStart
,08-04 10:46:36.317  1419  1419 V ActivityThread: updateVisibility : ActivityRecord{24c5f327 token=android.os.BinderProxy@1bab3900 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-04 10:46:36.317  1760  1773 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
,08-04 10:46:36.317  1760  1907 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
08-04 10:46:36.317  1760  1907 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,08-04 10:46:36.337   267   267 I SurfaceFlinger: id=14 createSurf (1080x1920),1 flag=4, Mauncher
,08-04 10:46:36.337   746  1026 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-04 10:46:36.337   746  1026 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-04 10:46:36.337   746  1030 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-04 10:46:36.337   746  1030 D PointerIcon: setMouseCustomIcon IconType is same.101
08-04 10:46:36.337   746  1030 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-04 10:46:36.337   746  1030 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-04 10:46:36.347   746  1435 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-04 10:46:36.347   746  1435 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 7553 uid 10079
,08-04 10:46:36.347   746  8687 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-04 10:46:36.407   746  1030 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{146201fc u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t97} time:189441
,08-04 10:46:36.437   746  1455 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.437  1942  8672 I qtaguid : Tagging socket 52 with tag 1000040700000000{268436487,0} uid -1, pid: 1942, getuid(): 10015
,08-04 10:46:36.437   746  1145 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.437   746  1366 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.437   746  1297 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.447   746  1455 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,08-04 10:46:36.447   746  1455 D ActivityManager: caller:android.app.ApplicationThreadProxy@1657c9, r.packageName :com.sec.android.app.samsungapps
,08-04 10:46:36.457  2494  2494 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-04 10:46:36.457  2494  2494 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1470300396473
,08-04 10:46:36.457  2494  2494 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
,08-04 10:46:36.467  2494  2494 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,08-04 10:46:36.467  7249  7249 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,08-04 10:46:36.467  7249  7249 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,08-04 10:46:36.467  7249  7249 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,08-04 10:46:36.467  7249  7249 D InitializeManagerStateMachine: exit::IDLE
08-04 10:46:36.467  7249  7249 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,08-04 10:46:36.477   746  1426 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.477   746  1718 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-04 10:46:36.477  7249  7249 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
08-04 10:46:36.477  7249  7249 D InitializeManagerStateMachine: exit::NETWORK_CHECK
08-04 10:46:36.477  7249  7249 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
08-04 10:46:36.477  7249  7249 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
08-04 10:46:36.477  7249  7249 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
08-04 10:46:36.477  7249  7249 D InitializeManagerStateMachine: entry::SUCCESS
08-04 10:46:36.477  7249  7249 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,08-04 10:46:36.487  7249  7249 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
08-04 10:46:36.487  7249  7249 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
,08-04 10:46:36.487   746  1435 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.487  7249  7249 D InitializeManagerStateMachine: exit::SUCCESS
08-04 10:46:36.487  7249  7249 D InitializeManagerStateMachine: entry::IDLE
,08-04 10:46:36.517  2494  2494 I KLMS-2.4.511: : MainReciver(): Notification App List is Null. Remove Notification.
,08-04 10:46:36.517  2494  2494 I KLMS-2.4.511: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-04 10:46:36.517   746  1401 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-04 10:46:36.517   746  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:36.517   746  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:36.517   746  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:36.517   746  1401 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:36.557  8692  8692 E Zygote  : MountEmulatedStorage()
08-04 10:46:36.557  8692  8692 E Zygote  : v2
08-04 10:46:36.557  8692  8692 I libpersona: KNOX_SDCARD checking this for 10116
08-04 10:46:36.557  8692  8692 I libpersona: KNOX_SDCARD not a persona
,08-04 10:46:36.567   746  1401 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8692 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,08-04 10:46:36.567   746  1123 I EventHub: Removing device '/dev/input/event6' due to inotify event
,08-04 10:46:36.577   369   369 I ServiceManager: Waiting for service AtCmdFwd...
,08-04 10:46:36.597  8692  8692 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-04 10:46:36.597  8692  8692 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
08-04 10:46:36.597   746  1123 I EventHub: Removing device '/dev/input/event7' due to inotify event
,08-04 10:46:36.607   746  1426 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.607   746  1718 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.617   746  1297 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.617   746  1298 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.627   746  1459 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.627   746  1718 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.627  8692  8692 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:36.637   746  1366 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-04 10:46:36.637  8692  8692 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:36.647  8692  8692 D ResourcesManager: creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,08-04 10:46:36.647  8692  8692 W ContextImpl: Unable to create files subdir /data/data/com.sec.esdk.elm/cache
08-04 10:46:36.647  8692  8692 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,08-04 10:46:36.657   746  1123 I EventHub: Removing device '/dev/input/event8' due to inotify event
,08-04 10:46:36.657  8692  8692 D AndroidRuntime: Shutting down VM
,08-04 10:46:36.657  3829  3829 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,08-04 10:46:36.657  3829  3829 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-04 10:46:36.657  3829  3829 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
08-04 10:46:36.657  3829  3829 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
08-04 10:46:36.657  3829  3829 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
08-04 10:46:36.657  3829  3829 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
08-04 10:46:36.657  3829  3829 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: FATAL EXCEPTION: main
08-04 10:46:36.657  8692  8692 E AndroidRuntime: Process: com.sec.esdk.elm, PID: 8692
08-04 10:46:36.657  8692  8692 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate receiver com.sec.esdk.elm.receiver.MainReceiver: java.lang.ClassNotFoundException: Didn't find class "com.sec.esdk.elm.receiver.MainReceiver" on path: DexPathList[[zip file "/system/app/ELMAgent/ELMAgent.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2970)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: Caused by: java.lang.ClassNotFoundException: Didn't find class "com.sec.esdk.elm.receiver.MainReceiver" on path: DexPathList[[zip file "/system/app/ELMAgent/ELMAgent.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2965)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 	... 9 more
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 	Suppressed: java.io.IOException: Zip archive '/system/app/ELMAgent/ELMAgent.apk' doesn't contain classes.dex (error msg: Entry not found)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFileNative(Native Method)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:80)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:59)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at ,dalvik.system.DexPathList.<init>(DexPathList.java:109)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Native Method)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Method.java:372)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5082)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		... 7 more
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/app/ELMAgent/ELMAgent.apk'
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		... 27 more
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from /system/app/ELMAgent/arm/ELMAgent.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		... 27 more
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 	Caused by: java.io.IOException: 
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		... 27 more
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 	Suppressed: java.lang.ClassNotFoundException: com.sec.esdk.elm.receiver.MainReceiver
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at java.lang.Class.classForName(Native Method)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 		... 11 more
08-04 10:46:36.657  8692  8692 E AndroidRuntime: 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
08-04 10:46:36.657  3829  3829 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:46:36.657   746  1455 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.service.health, hostingType: broadcast
08-04 10:46:36.657  3829  3829 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-04 10:46:36.657  3829  3829 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 10:46:36.657  3829  3829 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:46:36.657  3829  3829 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 10:46:36.657  3829  3829 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 10:46:36.657  3829  3829 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,08-04 10:46:36.667   746  1455 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:36.667   746  1455 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:36.667   746  1455 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-04 10:46:36.667   746  1455 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-04 10:46:36.707   746  1123 I EventHub: Removing device '/dev/input/event9' due to inotify event
,08-04 10:46:36.717  8707  8707 E Zygote  : MountEmulatedStorage()
08-04 10:46:36.717  8707  8707 E Zygote  : v2
08-04 10:46:36.717  8707  8707 I libpersona: KNOX_SDCARD checking this for 10021
08-04 10:46:36.717  8707  8707 I libpersona: KNOX_SDCARD not a persona
,08-04 10:46:36.717   746  1455 I ActivityManager: Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8707 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,08-04 10:46:36.727   746  1298 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.esdk.elm
,08-04 10:46:36.727  8692  8692 I Process : Sending signal. PID: 8692 SIG: 9
,08-04 10:46:36.727   746  8713 E DropBoxManagerService: Can't write: system_app_crash
08-04 10:46:36.727   746  8713 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop206.tmp: open failed: ENOENT (No such file or directory)
08-04 10:46:36.727   746  8713 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-04 10:46:36.727   746  8713 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 10:46:36.727   746  8713 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 10:46:36.727   746  8713 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 10:46:36.727   746  8713 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-04 10:46:36.727   746  8713 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
08-04 10:46:36.727   746  8713 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
08-04 10:46:36.727   746  8713 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 10:46:36.727   746  8713 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 10:46:36.727   746  8713 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-04 10:46:36.727   746  8713 E DropBoxManagerService: 	... 5 more
,08-04 10:46:36.737  7981  8657 I SA      : [RC New] Execute method=[GET] start
,08-04 10:46:36.747   746  1123 I EventHub: Removing device '/dev/input/event10' due to inotify event
,08-04 10:46:36.757  8707  8707 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-04 10:46:36.757  8707  8707 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-04 10:46:36.767   746  1435 I ActivityManager: Killing 7266:com.sec.enterprise.knox.cloudmdm.smdms/u0a201 (adj 15): emptyCount ##41
,08-04 10:46:36.777   746  1426 I ActivityManager: Process com.sec.esdk.elm (pid 8692)(adj 9) has died(295,1537)
,08-04 10:46:36.787  8707  8707 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-04 10:46:36.787   746  1123 I EventHub: Removing device '/dev/input/event11' due to inotify event
08-04 10:46:36.787  8707  8707 D ActivityThread: Added TimaKeyStore provider
,08-04 10:46:36.797  8707  8707 D ResourcesManager: creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,08-04 10:46:36.797  7981  8657 I SA      : [RC New] Security=[true]
,08-04 10:46:36.797  7981  8657 I System.out: Thread-1290(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,08-04 10:46:36.807  8707  8707 W ContextImpl: Unable to create files subdir /data/data/com.sec.android.service.health/cache
08-04 10:46:36.807  8707  8707 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,08-04 10:46:36.807  8707  8707 W         : Zip: inflate read failed (14837 vs 32768)
,08-04 10:46:36.817  8707  8707 D AndroidRuntime: Shutting down VM
,08-04 10:46:36.817  8707  8707 E AndroidRuntime: FATAL EXCEPTION: main
08-04 10:46:36.817  8707  8707 E AndroidRuntime: Process: com.sec.android.service.health, PID: 8707
08-04 10:46:36.817  8707  8707 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.sec.android.service.health.cp.TrustZoneSecurityProvider: java.lang.ClassNotFoundException: Didn't find class "com.sec.android.service.health.cp.TrustZoneSecurityProvider" on path: DexPathList[[zip file "/system/priv-app/HealthService/HealthService.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5558)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5150)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5090)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: Caused by: java.lang.ClassNotFoundException: Didn't find class "com.sec.android.service.health.cp.TrustZoneSecurityProvider" on path: DexPathList[[zip file "/system/priv-app/HealthService/HealthService.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5543)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	... 11 more
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	Suppressed: java.io.IOException: Failed to extract 'classes.dex' from '/system/priv-app/HealthService/HealthService.apk': I/O Error
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFileNative(Native Method)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:80)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:59)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		at dalvik.system.PathClassLoader.openArtFile,(PathClassLoader.java:76)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Native Method)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Method.java:372)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5082)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		... 9 more
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open file '/data/dalvik-cache/arm/system@priv-app@HealthService@HealthService.apk@classes.dex': Read-only file system
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		... 27 more
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/priv-app/HealthService/HealthService.apk'
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		... 27 more
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from /system/priv-app/HealthService/arm/HealthService.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		... 27 more
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	Caused by: java.io.IOException: 
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		... 27 more
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	Suppressed: java.lang.ClassNotFoundException: com.sec.android.service.health.cp.TrustZoneSecurityProvider
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		at java.lang.Class.classForName(Native Method)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 		... 13 more
08-04 10:46:36.817  8707  8707 E AndroidRuntime: 	Ca
,08-04 10:46:36.817   746  1435 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.sec.android.service.health
,08-04 10:46:36.827   746  1123 I EventHub: Removing device '/dev/input/event12' due to inotify event
,08-04 10:46:36.827   746  8723 E AndroidRuntime: *** FATAL EXCEPTION IN SYSTEM PROCESS: Error dump: system_app_crash
08-04 10:46:36.827   746  8723 E AndroidRuntime: java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
08-04 10:46:36.827   746  8723 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:46)
08-04 10:46:36.827   746  8723 E AndroidRuntime: 	at android.os.StatFs.restat(StatFs.java:56)
08-04 10:46:36.827   746  8723 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
08-04 10:46:36.827   746  8723 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
08-04 10:46:36.827   746  8723 E AndroidRuntime: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-04 10:46:36.827   746  8723 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
08-04 10:46:36.827   746  8723 E AndroidRuntime: Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
08-04 10:46:36.827   746  8723 E AndroidRuntime: 	at libcore.io.Posix.statvfs(Native Method)
08-04 10:46:36.827   746  8723 E AndroidRuntime: 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
08-04 10:46:36.827   746  8723 E AndroidRuntime: 	at android.system.Os.statvfs(Os.java:473)
08-04 10:46:36.827   746  8723 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:44)
08-04 10:46:36.827   746  8723 E AndroidRuntime: 	... 5 more
,08-04 10:46:36.827  8707  8707 I Process : Sending signal. PID: 8707 SIG: 9
,08-04 10:46:36.837  6264  6264 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-04 10:46:36.837  6264  6264 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM config WHERE config_id=?] disk I/O error
,08-04 10:46:36.837   746  8723 E android.os.Debug: ro.product_ship = true
08-04 10:46:36.837   746  8723 E android.os.Debug: ro.debug_level = 0x4f4c
,08-04 10:46:36.847   746  8723 E AndroidRuntime: Error reporting crash
08-04 10:46:36.847   746  8723 E AndroidRuntime: java.lang.IllegalArgumentException: Invalid path: /data/system/dropbox
08-04 10:46:36.847   746  8723 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:46)
08-04 10:46:36.847   746  8723 E AndroidRuntime: 	at android.os.StatFs.restat(StatFs.java:56)
08-04 10:46:36.847   746  8723 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.trimToFit(DropBoxManagerService.java:726)
08-04 10:46:36.847   746  8723 E AndroidRuntime: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:188)
08-04 10:46:36.847   746  8723 E AndroidRuntime: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-04 10:46:36.847   746  8723 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
08-04 10:46:36.847   746  8723 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:15161)
08-04 10:46:36.847   746  8723 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService.handleApplicationCrashInner(ActivityManagerService.java:14749)
08-04 10:46:36.847   746  8723 E AndroidRuntime: 	at com.android.server.am.ActivityManagerService.handleApplicationCrash(ActivityManagerService.java:14733)
08-04 10:46:36.847   746  8723 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
08-04 10:46:36.847   746  8723 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
08-04 10:46:36.847   746  8723 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
08-04 10:46:36.847   746  8723 E AndroidRuntime: Caused by: android.system.ErrnoException: statvfs failed: ENOENT (No such file or directory)
08-04 10:46:36.847   746  8723 E AndroidRuntime: 	at libcore.io.Posix.statvfs(Native Method)
08-04 10:46:36.847   746  8723 E AndroidRuntime: 	at libcore.io.BlockGuardOs.statvfs(BlockGuardOs.java:298)
08-04 10:46:36.847   746  8723 E AndroidRuntime: 	at android.system.Os.statvfs(Os.java:473)
08-04 10:46:36.847   746  8723 E AndroidRuntime: 	at android.os.StatFs.doStat(StatFs.java:44)
08-04 10:46:36.847   746  8723 E AndroidRuntime: 	... 11 more
,08-04 10:46:36.847   746  8723 I Process : Sending signal. PID: 746 SIG: 9
,08-04 10:46:36.847  6264  6264 D AndroidRuntime: Shutting down VM
,08-04 10:46:36.847  7981  8657 I System.out: Thread-1290(ApacheHTTPLog):isShipBuild true
,08-04 10:46:36.847  6264  6264 D HockeyApp: Writing unhandled exception to: /data/data/sstream.app/files/c8f72ae1-46d2-481e-849f-eb670caac790.stacktrace
,08-04 10:46:36.847  6264  6264 E HockeyApp: Error saving exception stacktrace!
08-04 10:46:36.847  6264  6264 E HockeyApp: 
08-04 10:46:36.847  6264  6264 E HockeyApp: java.io.FileNotFoundException: /data/data/sstream.app/files/c8f72ae1-46d2-481e-849f-eb670caac790.stacktrace: open failed: ENOENT (No such file or directory)
08-04 10:46:36.847  6264  6264 E HockeyApp: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-04 10:46:36.847  6264  6264 E HockeyApp: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 10:46:36.847  6264  6264 E HockeyApp: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 10:46:36.847  6264  6264 E HockeyApp: 	at java.io.FileWriter.<init>(FileWriter.java:80)
08-04 10:46:36.847  6264  6264 E HockeyApp: 	at net.hockeyapp.android.internal.ExceptionHandler.saveException(ExceptionHandler.java:83)
08-04 10:46:36.847  6264  6264 E HockeyApp: 	at net.hockeyapp.android.internal.ExceptionHandler.uncaughtException(ExceptionHandler.java:108)
08-04 10:46:36.847  6264  6264 E HockeyApp: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
08-04 10:46:36.847  6264  6264 E HockeyApp: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
08-04 10:46:36.847  6264  6264 E HockeyApp: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
08-04 10:46:36.847  6264  6264 E HockeyApp: 	at libcore.io.Posix.open(Native Method)
08-04 10:46:36.847  6264  6264 E HockeyApp: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 10:46:36.847  6264  6264 E HockeyApp: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-04 10:46:36.847  6264  6264 E HockeyApp: 	... 7 more
,08-04 10:46:36.977   265   265 I ServiceManager: service 'backup' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'appwidget' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'voiceinteraction' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'SecExternalDisplayService' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'diskstats' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'mDNIe' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'spengestureservice' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'quickconnect' died
08-04 10:46:36.977  1419  1949 W Sensors : sensorservice died [0xafa07240]
08-04 10:46:36.977   265   265 I ServiceManager: service 'samplingprofiler' died
08-04 10:46:36.977  1963  2002 W Sensors : sensorservice died [0xaf0f6a40]
08-04 10:46:36.977   265   265 I ServiceManager: service 'commontime_management' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'dreams' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'print' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'restrictions' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'media_session' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'media_router' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'trust' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'fingerprint' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'launcherapps' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'voip' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'media_projection' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'lpnet' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'imms' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'servicediscovery' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'updatelock' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'notification' died
08-04 10:46:36.977  1402  1436 W Sensors : sensorservice died [0xafa031c0]
08-04 10:46:36.977   265   265 I ServiceManager: service 'devicestoragemonitor' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'location' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'country_detector' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'search' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'dropbox' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'wallpaper' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'audio' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'DockObserver' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'wifip2p' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'connectivity' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'sb_service' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'sec_analytics' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'motion_recognition' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'cover' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'mount' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'lock_settings' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'device_policy' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'harmony_eas_service' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'sdp' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'log_manager_service' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'wifi' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'msapwifi' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'wifiscanner' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'rttmanager' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'mum_container_policy' died
08-04 10:46:36.,977   265   265 I ServiceManager: service 'enterprise_billing_policy' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'knox_timakeystore_policy' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'enterprise_policy' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'statusbar' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'clipboard' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'clipboardEx' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'network_management' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'ABTPersistenceService' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'textservices' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'network_score' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'netstats' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'netpolicy' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'enterprise_license_policy' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'application_policy' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'wifi_policy' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'phone_restriction_policy' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'remoteinjection' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'alarm' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'context_aware' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'usb' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'serial' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'uimode' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'jobscheduler' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'scontext' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'barbeam' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'multiwindow_facade' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'window' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'input' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'tactileassist' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'bluetooth_manager' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'bluetooth_secure_mode_manager' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'rcp' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'input_method' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'accessibility' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'persona_policy' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'batterystats' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'appops' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'power' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'display' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'battery' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'usagestats' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'webviewupdate' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'scheduling_policy' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'telephony.registry' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'entropy' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'dbinfo' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'SEAMService' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'persona' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'account' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'content' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'DirEncryptService' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'ReactiveService' died
08-04 10:46:36.977   265   265 I ServiceManager:, service 'sedenial' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'vibrator' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'tima' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'cepproxyks' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'CustomFrequencyManagerService' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'samsung.smartfaceservice' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'consumer_ir' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'cpuinfo' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'user' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'permission' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'hardware' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'meminfo' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'gfxinfo' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'activity' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'package' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'edmnativehelper' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'procstats' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'mdm.remotedesktop' died
08-04 10:46:36.977   265   265 I ServiceManager: service 'sensorservice' died
08-04 10:46:36.977  1356  1387 W Sensors : sensorservice died [0xaf0f6940]
08-04 10:46:36.977   325   747 W AudioFlinger: power manager service died !!!
08-04 10:46:36.977   325   747 W AudioCache: clearPowerManager -mWakeLockCount is 0, failed to releaseWakeLock function
08-04 10:46:36.977  1942  2006 W Sensors : sensorservice died [0xaf0533c0]
08-04 10:46:36.987   267   336 I SurfaceFlinger: restart the boot-animation @ binderDied
08-04 10:46:36.987   267   323 I SurfaceFlinger: id=5 Removed EimLayer (2/9)
08-04 10:46:36.987   267   323 I SurfaceFlinger: id=6 Removed EimLayer (2/8)
08-04 10:46:36.987   267   323 I SurfaceFlinger: id=14 Removed Mauncher (4/7)
08-04 10:46:36.987   267   323 I SurfaceFlinger: id=8 Removed JmageWallpa (2/6)
08-04 10:46:36.987   267   323 I SurfaceFlinger: id=8 Removed JmageWallpa (-2/6)
08-04 10:46:36.987   267   323 I SurfaceFlinger: id=9 Removed TtatusBar (3/5)
08-04 10:46:36.987   267   323 I SurfaceFlinger: id=13 Removed Uoast (3/4)
08-04 10:46:36.987   267   323 I SurfaceFlinger: id=9 Removed TtatusBar (-2/4)
08-04 10:46:36.987   267   323 I SurfaceFlinger: id=14 Removed Mauncher (-2/4)
08-04 10:46:36.987   267   323 I SurfaceFlinger: id=13 Removed Uoast (-2/4)
08-04 10:46:36.987   267   323 I SurfaceFlinger: id=11 Removed DolorFade (3/3)
08-04 10:46:36.987   267   323 I SurfaceFlinger: id=11 Removed DolorFade (-2/3)
08-04 10:46:36.987  1190  3262 W Sensors : sensorservice died [0xaf07e280]
08-04 10:46:36.987  1320  3148 E WifiManager: Channel connection lost
08-04 10:46:36.987  1190  1589 E WifiManager: Channel connection lost
08-04 10:46:36.987  1760  1774 W Sensors : sensorservice died [0xaf070340]
08-04 10:46:36.987  1574  4068 E WifiManager: Channel connection lost
08-04 10:46:36.987  1402  1799 E WifiManager: Channel connection lost
08-04 10:46:36.987  1942  2360 E WifiManager: Channel connection lost
08-04 10:46:36.987  7981  8657 I System.out: Thread-1290(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
08-04 10:46:36.987   267   267 D SurfaceFlinger: Set power mode=2, type=0 flinger=0xb6962000
08-04 10:46:36.987   267   267 D qdhwcomposer: hwc_blank: Unblanking display: 0
08-04 10:46:36.987  1639  2301 E WifiManager: Channel connection lost
08-04 10:46:36.987  7727  7749 E WifiManager: Channel connection lost
08-04 10:46:36.997   267  1647 I SurfaceFlinger: id=2 Removed GocusedStac (2/2)
08-04 10:46:36.997   267  1647 I SurfaceFlinger: id=3 Removed EimLayer (0/1)
08-04 10:46:36.997   267  1647 I SurfaceFlinger: id=4 Removed EimLayer (0/0)
08-04 10:46:36.997   267  1647 I SurfaceFlinger: id=5 Removed EimLayer (-2/0)
08-04 10:46:36.997   267  1647 I SurfaceFlinger: id=6 Removed EimLayer (-2/0)
08-04 10:46:36.997   267  1647 I SurfaceFlinger: id=2 Removed GocusedStac (-2/0)
08-04 10:46:36.997   267  1647 I SurfaceFlinger: id=3 Removed EimLayer (-2/0)
08-04 10:46:36.997   267  1647 I SurfaceFlinger: id=4 Removed EimLayer (-2/0)
08-04 10:46:36.997   328   328 E installd: eof
08-04 10:46:36.997   328   328 E installd: failed to read size
08-04 10:46:36.997   328   328 I installd: closing connection
08-04 10:46:36.997  6932  6932 D AndroidRuntime: Shutting down VM
08-04 10:46:36.997  6932  6932 E AndroidRuntime: FATAL EXCEPTION: main
08-04 10:46:36.997  6932  6932 E AndroidRuntime: Process: com.sec.pcw.device, PID: 6932
08-04 10:46:36.997  6932  6932 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.sec.pcw.device.receiver.SYSTEMReceiver: java.lang.RuntimeException: Package manager has died
08-04 10:46:36.997  6932  6932 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2996)
08-04 10:46:36.997  6932  6932 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
08-04 10:46:36.997  6932  6932 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
08-04 10:46:36.997  6932  6932 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 10:46:36.997  6932  6932 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-04 10:46:36.997  6932  6932 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-04 10:46:36.997  6932  6932 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 10:46:36.997  6932  6932 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-04 10:46:36.997  6932  6932 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-04 10:46:36.997  6932  6932 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-04 10:46:36.997  6932  6932 E AndroidRuntime: Caused by: java.lang.RuntimeException: Package manager has died
08-04 10:46:36.997  6932  6932 E AndroidRuntime: 	at android.app.ApplicationPackageManager.queryBroadcastReceivers(ApplicationPackageManager.java:679)
08-04 10:46:36.997  6932  6932 E AndroidRuntime: 	at android.app.ApplicationPackageManager.queryBroadcastReceivers(ApplicationPackageManager.java:685)
08-04 10:46:36.997  6932  6932 E AndroidRuntime: 	at com.sec.pcw.device.util.h.a(PushUtil.java:136)
08-04 10:46:36.997  6932  6932 E AndroidRuntime: 	at com.sec.pcw.device.receiver.SYSTEMReceiver.onReceive(SYSTEMReceiver.java:84)
08-04 10:46:36.997  6932  6932 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
08-04 10:46:36.997  6932  6932 E AndroidRuntime: 	... 9 more
08-04 10:46:36.997  6932  6932 E AndroidRuntime: Caused by: android.os.DeadObjectException
08-04 10:46:36.997  6932  6932 E AndroidRuntime: 	at android.os.BinderProxy.transactNative(Native Method)
08-04 10:46:36.997  6932  6932 E AndroidRuntime: 	at android.os.BinderProxy.transact(Binder.java:496)
08-04 10:46:36.997  6932  6932 E AndroidRuntime: 	at android.content.pm.IPackageManager$Stub$Proxy.queryIntentReceivers(IPackageManager.java:3231)
08-04 10:46:36.997  6932  6932 E AndroidRuntime: 	at android.app.ApplicationPackageManager.queryBroadcastReceivers(ApplicationPackageManager.java:673)
08-04 10:46:36.997  6932  6932 E AndroidRuntime: 	... 13 more
08-04 10:46:37.007  6932  6932 E AndroidRuntime: Error reporting crash
08-04 10:46:37.007  6932  6932 E AndroidRuntime: android.os.DeadObjectException
08-04 10:46:37.007  6932  6932 E AndroidRuntime: 	at android.os.BinderProxy.transactNative(Native Method)
08-04 10:46:37.007  6932  6932 E AndroidRuntime: 	at android.os.BinderProxy.transact(Binder.java:496)
08-04 10:46:37.007  6932  6932 E AndroidRuntime: 	at android.app.ActivityManagerProxy.handleApplicationCrash(ActivityManagerNative.java:4706)
08-04 10:46:37.007  6932  6932 E AndroidRuntime: 	at com.android.internal.os.RuntimeInit$UncaughtHandler.uncaughtException(RuntimeInit.java:95)
08-04 10:46:37.007  6932  6932 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
08-04 10:46:37.007  6932  6932 E AndroidRuntime: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
08-04 10:46:37.007  6932  6932 I Process : Sending signal. PID: 6932 SIG: 9
,08-04 10:46:37.227   267   518 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 1
,08-04 10:46:37.227   267   267 E qdexternal: writeHPDOption: file write failed '/sys/devices/virtual/graphics/fb1/hpd'
08-04 10:46:37.227   267   267 D qdhwcomposer: hwc_blank: Done unblanking display: 0
08-04 10:46:37.227   267   541 E qdhwcomposer: hwc_vsync_control: vsync control failed. Dpy=0, enable=1 : Operation not permitted
08-04 10:46:37.227   267   541 E SurfaceFlinger: eventControl(0, 1) failed Operation not permitted
,08-04 10:46:37.267   310   310 E SMD     : DCD ON
,08-04 10:46:37.397   267   518 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
