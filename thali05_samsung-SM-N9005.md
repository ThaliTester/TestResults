#### Test 794266509fa1f7f_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
08-05 02:10:09.868   772  3276 D SSRM:n  : SIOP:: AP = 330, PST = 355, CUR = 450
,--------- beginning of main
08-05 02:10:11.468  7383  7383 D AndroidRuntime: 
08-05 02:10:11.468  7383  7383 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-05 02:10:11.478  7383  7383 D AndroidRuntime: CheckJNI is OFF
08-05 02:10:11.478  7383  7383 D AndroidRuntime: readGMSProperty: start
08-05 02:10:11.478  7383  7383 D AndroidRuntime: readGMSProperty: already setted!!
08-05 02:10:11.478  7383  7383 D AndroidRuntime: readGMSProperty: end
08-05 02:10:11.478  7383  7383 D AndroidRuntime: addProductProperty: start
08-05 02:10:11.588   306   306 E SMD     : DCD ON
08-05 02:10:11.648  7383  7383 E AffinityControl: AffinityControl: registerfunction enter
08-05 02:10:11.668  7383  7383 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-05 02:10:11.668   772  1654 E PersonaManagerService: inState():  stateMachine is null !!
08-05 02:10:11.668   772  1654 I PersonaManagerService: PersonaId don't exist
08-05 02:10:11.668   772  1654 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
08-05 02:10:11.678   772  1654 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
08-05 02:10:11.678   772  1654 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-05 02:10:11.678   772  1654 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
08-05 02:10:11.688   772  1654 W ActivityManager: mDVFSHelper.acquire()
08-05 02:10:11.688   772  1654 D FocusedStackFrame: Set to : 0
08-05 02:10:11.688   772  1654 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:11.688   772  1654 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:11.688   772  1654 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:11.688   772  1654 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:11.738   772  1654 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7398 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-05 02:10:11.738  7383  7383 D AndroidRuntime: Shutting down VM
08-05 02:10:11.748   772  1041 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-05 02:10:11.748   772  1041 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 02:10:11.748   772  1041 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-05 02:10:11.748   772  1041 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-05 02:10:11.748  7398  7398 E Zygote  : MountEmulatedStorage()
08-05 02:10:11.748  7398  7398 E Zygote  : v2
08-05 02:10:11.748  7398  7398 I libpersona: KNOX_SDCARD checking this for 10079
08-05 02:10:11.748  7398  7398 I libpersona: KNOX_SDCARD not a persona
08-05 02:10:11.768  7398  7398 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 02:10:11.768  7398  7398 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-05 02:10:11.778  7398  7398 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
08-05 02:10:11.818  7398  7398 D TimaKeyStoreProvider: TimaSignature is unavailable
08-05 02:10:11.818  7398  7398 D ActivityThread: Added TimaKeyStore provider
08-05 02:10:11.818   772  1426 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-05 02:10:11.818   772  1426 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
08-05 02:10:11.818   772  1426 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-05 02:10:11.818   772  1426 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-05 02:10:11.828   772  1426 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
08-05 02:10:11.848  1438  1438 D SurfaceWidgetView: destroyHardwareResources():785377010
08-05 02:10:11.858   772  3276 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 02:10:11.868  7398  7398 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
08-05 02:10:11.888   267  1775 I SurfaceFlinger: id=8 Removed Mauncher (6/8)
08-05 02:10:11.898   267  1468 I SurfaceFlinger: id=8 Removed Mauncher (-2/8)
08-05 02:10:11.908   772   802 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
08-05 02:10:11.908   772   802 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
08-05 02:10:11.908   772   802 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
08-05 02:10:11.908   772   772 D BatteryService: Sending ACTION_BATTERY_CHANGED.
08-05 02:10:11.918   772   802 D BatteryService: stay LED for fully charged
08-05 02:10:11.918   772   772 I MotionRecognitionService: Plugged
08-05 02:10:11.918   772   772 I MotionRecognitionService: setPowerConnected  = true
08-05 02:10:11.918  1438  1438 V ActivityThread: updateVisibility : ActivityRecord{3297d3c token=android.os.BinderProxy@290db832 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
08-05 02:10:11.918  1438  1438 D Launcher: onTrimMemory. Level: 20
08-05 02:10:11.918  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-05 02:10:11.918  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
08-05 02:10:11.928  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
08-05 02:10:11.928  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-05 02:10:11.928  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-05 02:10:11.928  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-05 02:10:11.928  3204  3204 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-05 02:10:11.928  1768  1783 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
08-05 02:10:11.928  3204  3274 D HeadsetStateMachine: Disconnected process message: 10
,08-05 02:10:12.008  7398  7398 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,08-05 02:10:12.008  7398  7398 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,08-05 02:10:12.028  7398  7398 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 1651-1654)
,08-05 02:10:12.028  7398  7398 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-05 02:10:12.048  7398  7398 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {31a2b045}
,08-05 02:10:12.058  7398  7398 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-05 02:10:12.058  7398  7398 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,08-05 02:10:12.088  7398  7398 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-05 02:10:12.088  7398  7398 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-05 02:10:12.088  7398  7398 E SysUtils: ApplicationContext is null in ApplicationStatus
,08-05 02:10:12.138  7398  7398 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,08-05 02:10:12.138  7398  7398 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
08-05 02:10:12.138  7398  7398 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,08-05 02:10:12.158  7398  7398 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
08-05 02:10:12.158  7398  7398 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
08-05 02:10:12.158  7398  7398 I Adreno-EGL: Build Date: 11/19/14 Wed
08-05 02:10:12.158  7398  7398 I Adreno-EGL: Local Branch: mybranch5813579
08-05 02:10:12.158  7398  7398 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
08-05 02:10:12.158  7398  7398 I Adreno-EGL: Local Patches: NONE
08-05 02:10:12.158  7398  7398 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,08-05 02:10:12.348   772   996 W ActivityManager: Activity pause timeout for ActivityRecord{3138f885 u0 com.test.thalitest/.MainActivity t99}
,08-05 02:10:12.368  7398  7440 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,08-05 02:10:12.408  7398  7398 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-05 02:10:12.428  7398  7398 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-05 02:10:12.448  7398  7398 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,08-05 02:10:12.458  7398  7398 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-05 02:10:12.458  7398  7398 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-05 02:10:12.518  7398  7398 D Activity: performCreate Call secproduct feature valuefalse
08-05 02:10:12.518  7398  7398 D Activity: performCreate Call debug elastic valuetrue
,08-05 02:10:12.528  7398  7456 D OpenGLRenderer: Render dirty regions requested: true
,08-05 02:10:12.538   772   804 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
,08-05 02:10:12.538   772   804 D KnoxTimeoutHandler: postActiveUserChange for user 0
08-05 02:10:12.538   772   804 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
08-05 02:10:12.538   772   772 D KnoxTimeoutHandler: handleActiveUserChange for user 0
,08-05 02:10:12.538   772   772 D PersonaManagerService: getPersonasForUser(): returning null!
,08-05 02:10:12.548  7398  7398 V ActivityThread: updateVisibility : ActivityRecord{4a8e397 token=android.os.BinderProxy@13856731 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,08-05 02:10:12.568   267   267 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,08-05 02:10:12.568   772  1037 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-05 02:10:12.578   772  1037 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-05 02:10:12.588   772  1041 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
08-05 02:10:12.588   772  1041 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 02:10:12.588   772  1041 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-05 02:10:12.588   772  1041 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-05 02:10:12.598  7398  7456 I OpenGLRenderer: Initialized EGL, version 1.4
,08-05 02:10:12.598  7398  7456 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xb3ccb3a8 ,&mEglDisplay = 1 , &mEglConfig = 8 
,08-05 02:10:12.608  7398  7456 D OpenGLRenderer: Enabling debug mode 0
,08-05 02:10:12.638   772  1575 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-05 02:10:12.648   772  7459 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-05 02:10:12.658   772  1041 W ActivityManager: mDVFSHelper.release()
,08-05 02:10:12.658   772  1041 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3138f885 u0 com.test.thalitest/.MainActivity t99} time:152287
,08-05 02:10:12.668  7398  7398 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-05 02:10:12.668  7398  7398 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@13856731 time:152296
,08-05 02:10:12.668  1744  1744 I SamsungIME: getCurrentCandidateView
,08-05 02:10:12.708  7398  7398 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7398
,08-05 02:10:12.748  1744  1744 D SamsungIME: Dismiss ExpandCandiate
,08-05 02:10:12.808  7398  7398 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-05 02:10:12.838  1744  1744 I SamsungIME: getDebugLevel  : 0x4f4c
,08-05 02:10:12.868  1744  1744 I SamsungIME: getDebugLevel  : 0x4f4c
,08-05 02:10:12.888  1744  1744 I SamsungIME: KeybaordView init() : load resources
,08-05 02:10:12.918  1744  1744 I SamsungIME: getCurrentKeyboard
08-05 02:10:12.918  1744  1744 I SamsungIME: getTextKeyboard
,08-05 02:10:12.918  7398  7461 D jxcore_app_log: JniHelper::setJavaVM(0xb4e5c280), pthread_self() = -1361356288
,08-05 02:10:12.928  7398  7461 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-05 02:10:12.928  7398  7461 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-05 02:10:12.928  7398  7461 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-05 02:10:12.928  7398  7461 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-05 02:10:12.928  7398  7461 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-05 02:10:12.928  7398  7461 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f3e087 added. We now have 1 listener(s)
,08-05 02:10:12.938  1744  1744 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-05 02:10:12.938  7398  7461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:1F:C9:5E
,08-05 02:10:12.938  7398  7461 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,08-05 02:10:12.938  7398  7461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-05 02:10:12.938  7398  7461 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-05 02:10:12.948  7398  7461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-05 02:10:12.948  7398  7461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-05 02:10:12.948  7398  7461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-05 02:10:12.948  7398  7461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:1F:C9:5E
08-05 02:10:12.948  7398  7461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-05 02:10:12.948  7398  7461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-05 02:10:12.948  7398  7461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-05 02:10:12.948  7398  7461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-05 02:10:12.948  7398  7461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-05 02:10:12.948  7398  7461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-05 02:10:12.948  7398  7461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-05 02:10:12.948  7398  7461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-05 02:10:12.948  7398  7461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-05 02:10:12.948  7398  7461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-05 02:10:12.948  7398  7461 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e400b52 added. We now have 1 listener(s)
08-05 02:10:12.948  7398  7461 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-05 02:10:12.958  7398  7461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-05 02:10:12.958  7398  7461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-05 02:10:12.958  7398  7461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-05 02:10:12.958  7398  7461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-05 02:10:12.958  7398  7461 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-05 02:10:12.958  7398  7461 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-05 02:10:12.958  7398  7461 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:1F:C9:5E
,08-05 02:10:12.968   772  2590 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 02:10:12.968  7398  7461 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-05 02:10:12.968  7398  7461 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 02:10:12.968  7398  7461 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 02:10:12.968  7398  7461 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 02:10:12.968  7398  7461 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 02:10:12.968  7398  7461 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 02:10:12.968  7398  7461 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 02:10:12.968  7398  7461 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 02:10:12.968  7398  7461 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-05 02:10:12.968  7398  7461 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-05 02:10:12.968  7398  7461 D io.jxcore.node.ConnectivityMonitor: start: OK
08-05 02:10:12.968   772  1575 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 02:10:12.968  7398  7461 I io.jxcore.node.LifeCycleMonitor: start: OK
08-05 02:10:12.968  7398  7398 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-05 02:10:12.968   772  1425 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-05 02:10:12.978  7398  7398 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-05 02:10:13.008  7398  7398 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-05 02:10:13.328  1744  7465 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,08-05 02:10:13.958  7398  7469 W jxcore-log: Initializing JXcore engine
,08-05 02:10:13.958  7398  7469 W jxcore-log: JXcore engine is ready
,08-05 02:10:14.008  1826  1826 E auditd  : In denial and Property audit_ondenial is set to 1 
,08-05 02:10:14.008  1826  1826 E audit   : type=1400 msg=audit(1470355813.998:203): avc:  denied  { ioctl } for  pid=7469 comm="Thread-1223" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-05 02:10:14.008   772  1028 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
08-05 02:10:14.008   772  1028 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,08-05 02:10:14.008   772   996 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
,08-05 02:10:14.008   772   996 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:14.008   772   996 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:14.008  1826  1826 E audit   :  SEPF_SM-N9005_5.0-1_0032
08-05 02:10:14.008  1826  1826 E audit   : 
08-05 02:10:14.008   772   996 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:14.008   772   996 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 02:10:14.008  1826  1826 E audit   : type=1300 msg=audit(1470355813.998:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=9a4008d8 items=0 ppid=348 ppcomm=main pid=7469 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1223" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
,08-05 02:10:14.008   772  1028 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,08-05 02:10:14.008  1826  1826 E audit   : type=1320 msg=audit(1470355813.998:203): 
,08-05 02:10:14.038  7398  7469 W jxcore-log: Starting JXcore engine
,08-05 02:10:14.048   772   996 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7488 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-05 02:10:14.048  7488  7488 E Zygote  : MountEmulatedStorage()
08-05 02:10:14.048  7488  7488 E Zygote  : v2
08-05 02:10:14.048  7488  7488 I libpersona: KNOX_SDCARD checking this for 1000
08-05 02:10:14.048  7488  7488 I libpersona: KNOX_SDCARD not a persona
,08-05 02:10:14.088  7488  7488 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 02:10:14.088  7488  7488 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-05 02:10:14.088  7488  7488 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-05 02:10:14.158  7488  7488 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 02:10:14.158  7488  7488 D ActivityThread: Added TimaKeyStore provider
,08-05 02:10:14.158  7398  7469 W jxcore-log: Platform android
08-05 02:10:14.158  7398  7469 W jxcore-log: 
,08-05 02:10:14.158  7398  7469 W jxcore-log: Process ARCH arm
08-05 02:10:14.158  7398  7469 W jxcore-log: 
,08-05 02:10:14.178  7488  7488 D ResourcesManager: creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,08-05 02:10:14.188  7488  7488 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,08-05 02:10:14.188  7488  7488 D SecurityLogAgent:  SeDenialReceiver : File path = null
,08-05 02:10:14.198   772  2590 I ActivityManager: Killing 5522:com.sec.android.widgetapp.SPlannerAppWidget/u0a171 (adj 15): emptyCount ##41
,08-05 02:10:14.388  7398  7469 I jxcore-log: JXcore Cordova bridge is ready!
08-05 02:10:14.388  7398  7469 I jxcore-log: 
,08-05 02:10:14.388  7398  7469 W jxcore-log: JXcore engine is started
,08-05 02:10:14.398  7398  7461 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-05 02:10:14.398  7398  7398 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-05 02:10:14.448   772  1046 I PowerManagerService: [PWL] Off : 75s ago
,08-05 02:10:14.588   306   306 E SMD     : DCD ON
,08-05 02:10:17.118   772  3312 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-05 02:10:17.588   306   306 E SMD     : DCD ON
,08-05 02:10:19.918   772  3276 D SSRM:n  : SIOP:: AP = 370, PST = 356, CUR = 450
,08-05 02:10:20.588   306   306 E SMD     : DCD ON
,08-05 02:10:20.898   371   371 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 02:10:21.738   772  1064 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,08-05 02:10:21.898   371   371 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 02:10:21.958   772  1425 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-05 02:10:21.958   772  1425 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4336, temperature: 286, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
,08-05 02:10:21.958   772  1425 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,08-05 02:10:21.958   772   772 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-05 02:10:21.958   772   772 I MotionRecognitionService: Plugged
,08-05 02:10:21.958   772   772 I MotionRecognitionService: setPowerConnected  = true
,08-05 02:10:21.968  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,08-05 02:10:21.968  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-05 02:10:21.968  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,08-05 02:10:21.968  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-05 02:10:21.968   772  1425 D BatteryService: stay LED for fully charged
,08-05 02:10:21.968  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-05 02:10:21.978  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-05 02:10:21.978  3204  3204 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-05 02:10:21.978  3204  3274 D HeadsetStateMachine: Disconnected process message: 10
,08-05 02:10:22.898   371   371 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 02:10:23.588   306   306 E SMD     : DCD ON
,08-05 02:10:23.898   371   371 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 02:10:24.898   371   371 I ServiceManager: Waiting for service AtCmdFwd...
,08-05 02:10:25.898   371   371 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-05 02:10:26.588   306   306 E SMD     : DCD ON
,08-05 02:10:29.418   772  1341 E Watchdog: !@Sync 5
,08-05 02:10:29.588   306   306 E SMD     : DCD ON
,08-05 02:10:29.988   772  3276 D SSRM:n  : SIOP:: AP = 380, PST = 359, CUR = 450
,08-05 02:10:30.018  7398  7469 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-05 02:10:30.018  7398  7469 I jxcore-log: 
,08-05 02:10:30.018  7398  7469 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-05 02:10:30.018  7398  7469 I jxcore-log: 
,08-05 02:10:30.018   772  1636 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 02:10:30.028  7398  7469 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-05 02:10:30.028  7398  7469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-05 02:10:30.028  7398  7469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-05 02:10:30.028  7398  7469 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-05 02:10:30.028  7398  7469 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-05 02:10:30.028  7398  7469 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-05 02:10:30.028  7398  7469 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-05 02:10:30.028  7398  7469 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-05 02:10:30.028  7398  7469 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-05 02:10:30.028  7398  7469 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-05 02:10:30.028  7398  7469 I jxcore-log: 
,08-05 02:10:30.028  7398  7469 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-05 02:10:30.028  7398  7469 I jxcore-log: 
,08-05 02:10:30.368  7398  7469 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-05 02:10:30.368  7398  7469 I jxcore-log: Failed to execute UT.
08-05 02:10:30.368  7398  7469 I jxcore-log: 
08-05 02:10:30.368  7398  7469 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-05 02:10:30.368  7398  7469 I jxcore-log: 
,08-05 02:10:30.378  7398  7469 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-05 02:10:30.378  7398  7469 I jxcore-log: 
08-05 02:10:30.378  7398  7398 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-05 02:10:30.678  7528  7528 D AndroidRuntime: 
08-05 02:10:30.678  7528  7528 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-05 02:10:30.678  7528  7528 D AndroidRuntime: CheckJNI is OFF
,08-05 02:10:30.678  7528  7528 D AndroidRuntime: readGMSProperty: start
08-05 02:10:30.678  7528  7528 D AndroidRuntime: readGMSProperty: already setted!!
,08-05 02:10:30.678  7528  7528 D AndroidRuntime: readGMSProperty: end
08-05 02:10:30.678  7528  7528 D AndroidRuntime: addProductProperty: start
,08-05 02:10:30.878  7528  7528 E AffinityControl: AffinityControl: registerfunction enter
,08-05 02:10:30.908  7528  7528 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-05 02:10:30.928   772  1318 D PackageManager: START PACKAGE DELETE: observer{725521437}
08-05 02:10:30.928   772  1318 D PackageManager: pkg{<packageName>}
08-05 02:10:30.928   772  1318 D PackageManager: user{0}
08-05 02:10:30.928   772  1318 D PackageManager: caller{2000}
08-05 02:10:30.928   772  1318 D PackageManager: flags{2}
,08-05 02:10:30.928   772  1318 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
08-05 02:10:30.928   772  1318 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
08-05 02:10:30.928   772  1318 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,08-05 02:10:30.928   772  1318 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
08-05 02:10:30.928   772  1318 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,08-05 02:10:30.928   772  1064 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
08-05 02:10:30.928   772  1064 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
,08-05 02:10:30.928   772  1064 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
,08-05 02:10:30.928   772  1064 D ApplicationPolicy: getApplicationUninstallationEnabled
08-05 02:10:30.928   772  1064 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,08-05 02:10:30.928   772  1064 D PackageManager: !@killApplicatoin: 10079, uninstall pkg
,08-05 02:10:30.938   772   996 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
,08-05 02:10:30.938   772   996 I ActivityManager: Killing 7398:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest cause uninstall pkg
,08-05 02:10:30.938   772   996 I ActivityManager:   Force finishing activity ActivityRecord{3138f885 u0 com.test.thalitest/.MainActivity t99}
,08-05 02:10:30.938   772   996 D FocusedStackFrame: Set to : 0
,08-05 02:10:30.948   267  1468 I SurfaceFlinger: id=12 Removed NainActivit (6/8)
,08-05 02:10:30.948   267   330 I SurfaceFlinger: id=12 Removed NainActivit (-2/8)
,08-05 02:10:30.958   772  1041 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-05 02:10:30.958   772  1041 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 02:10:30.958   772  1041 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-05 02:10:30.958   772  1041 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,08-05 02:10:31.078   772  1064 W PackageSettings: Skipping PackageSetting{33910818 com.example.hello/10078} due to missing metadata
,08-05 02:10:31.108   772  3276 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 02:10:31.118   772  1064 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=0: pkg removed
,08-05 02:10:31.138  1484  1484 I art     : Explicit concurrent mark sweep GC freed 558(33KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 19MB/33MB, paused 436us total 23.931ms
,08-05 02:10:31.148  6511  6511 I art     : Explicit concurrent mark sweep GC freed 645(36KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 317us total 28.049ms
,08-05 02:10:31.178  7016  7016 I art     : Explicit concurrent mark sweep GC freed 7710(364KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 318us total 29.174ms
,08-05 02:10:31.188   772  1041 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,08-05 02:10:31.188  3816  3816 I art     : Explicit concurrent mark sweep GC freed 5622(339KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 15MB/26MB, paused 341us total 18.759ms
,08-05 02:10:31.188  1744  1744 E SamsungIME: mOCRHelper is null
08-05 02:10:31.188   772   993 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,08-05 02:10:31.198  4572  4572 I art     : Explicit concurrent mark sweep GC freed 104(4KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 24MB/32MB, paused 999us total 50.183ms
,08-05 02:10:31.198   772  1122 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-05 02:10:31.198  1839  2316 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-05 02:10:31.198  1438  1438 D ResourcesManager: creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
,08-05 02:10:31.198  1438  1438 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-05 02:10:31.198  1438  1438 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-05 02:10:31.198  1406  1406 D RegisteredServicesCache: empty dynamic service
,08-05 02:10:31.198  1438  1438 D ResourcesManager: creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
,08-05 02:10:31.208   772  1146 V NetworkStats: removeUidsLocked() for UIDs [10079]
,08-05 02:10:31.208  1438  1438 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 02:10:31.208  1438  1438 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-05 02:10:31.208  1438  1438 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-05 02:10:31.208   772  1146 V NetworkStats: performPollLocked(flags=0x3)
08-05 02:10:31.208   772  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 02:10:31.208   772  1146 D NetworkStatsFactory: UpdateStatsForKnox
,08-05 02:10:31.208  1438  1438 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,08-05 02:10:31.208   772  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-05 02:10:31.208  1438  1438 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
08-05 02:10:31.208  1438  1438 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,08-05 02:10:31.218   772  1146 V NetworkStats: performPollLocked() took 9ms
,08-05 02:10:31.218   772  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 02:10:31.218   772   993 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,08-05 02:10:31.228  2498  2498 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,08-05 02:10:31.288  2498  2498 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1470355831250
,08-05 02:10:31.298  2498  2498 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
,08-05 02:10:31.308   772   993 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,08-05 02:10:31.318  2498  2498 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,08-05 02:10:31.328   772  1147 D NtpTrustedTime: currentTimeMillis() cache hit
08-05 02:10:31.328   772  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,08-05 02:10:31.338   772   772 I art     : Explicit concurrent mark sweep GC freed 57214(4MB) AllocSpace objects, 28(448KB) LOS objects, 29% free, 37MB/53MB, paused 2.251ms total 166.541ms
,08-05 02:10:31.338   772   772 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
08-05 02:10:31.348   772  1064 I art     : WaitForGcToComplete blocked for 139.625ms for cause Explicit
,08-05 02:10:31.358   772   993 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,08-05 02:10:31.368   772   772 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,08-05 02:10:31.368   772  1425 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,08-05 02:10:31.368   772  1425 D SecContentProvider2: mCursor = null
,08-05 02:10:31.388   772   772 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,08-05 02:10:31.388   772   993 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
,08-05 02:10:31.398   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,08-05 02:10:31.398   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
08-05 02:10:31.398   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
08-05 02:10:31.408   772   993 D EnterpriseDeviceManagerService: Package has changed for user 0
08-05 02:10:31.408   772   993 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,08-05 02:10:31.408   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,08-05 02:10:31.408   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,08-05 02:10:31.408   772   993 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,08-05 02:10:31.418   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,08-05 02:10:31.428   772   772 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,08-05 02:10:31.428   772   993 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,08-05 02:10:31.428   772   772 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,08-05 02:10:31.428   772   772 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,08-05 02:10:31.438   772   993 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 02:10:31.438   772   993 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
,08-05 02:10:31.438   772   772 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,08-05 02:10:31.448   772   772 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,08-05 02:10:31.448   772   772 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,08-05 02:10:31.448  2498  2498 I KLMS-2.4.511: : MainReciver(): Notification App List is Null. Remove Notification.
,08-05 02:10:31.448   772   772 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,08-05 02:10:31.458   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
,08-05 02:10:31.458  2498  2498 I KLMS-2.4.511: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,08-05 02:10:31.458   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
08-05 02:10:31.458   772  1426 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,08-05 02:10:31.458   772  1426 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:31.458   772  1426 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:31.458   772  1426 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:31.458   772  1426 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 02:10:31.458   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,08-05 02:10:31.468   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,08-05 02:10:31.468   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,08-05 02:10:31.468   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,08-05 02:10:31.478   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,08-05 02:10:31.478   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,08-05 02:10:31.488   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,08-05 02:10:31.488   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
08-05 02:10:31.498   772  1426 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=7549 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
08-05 02:10:31.498  7549  7549 E Zygote  : MountEmulatedStorage()
08-05 02:10:31.498  7549  7549 I libpersona: KNOX_SDCARD checking this for 10116
08-05 02:10:31.498  7549  7549 E Zygote  : v2
08-05 02:10:31.498  7549  7549 I libpersona: KNOX_SDCARD not a persona
,08-05 02:10:31.498   772   993 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 02:10:31.498   772   993 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
08-05 02:10:31.498   772   772 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
,08-05 02:10:31.508   772   772 D RCPManagerService: PackageReceiver onReceive()
,08-05 02:10:31.508   772   772 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,08-05 02:10:31.508   772   772 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,08-05 02:10:31.508   772   772 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-05 02:10:31.508   772   772 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-05 02:10:31.508   772   993 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 02:10:31.508   772   772 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
08-05 02:10:31.508   772   993 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
08-05 02:10:31.508   772   772 V EnterpriseBillingPolicy: uID is 10079
08-05 02:10:31.508   772   772 V EnterpriseBillingPolicy: Removed Packageuid is0
08-05 02:10:31.508   772   772 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
,08-05 02:10:31.518  7549  7549 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 02:10:31.518  7549  7549 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-05 02:10:31.518  7549  7549 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-05 02:10:31.518   772   772 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
08-05 02:10:31.518   772   772 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
,08-05 02:10:31.518   772   772 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
,08-05 02:10:31.518   772   772 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,08-05 02:10:31.528   772   772 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,08-05 02:10:31.528   772  3276 D SSRM:aY : MSG_TYPE_APP_REMOVED::
,08-05 02:10:31.528   772  1178 D TaskPersister: removeObsoleteFile: deleting file=99_task.xml
,08-05 02:10:31.538  7549  7549 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 02:10:31.538  7549  7549 D ActivityThread: Added TimaKeyStore provider
,08-05 02:10:31.538   772   772 V AlarmManagerEXT: com.test.thalitest(10079) is removed.
,08-05 02:10:31.548   772   993 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 02:10:31.548   772   993 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,08-05 02:10:31.558   772   993 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 02:10:31.558   772   993 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 02:10:31.558   772   993 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,08-05 02:10:31.558   772  1064 I art     : Explicit concurrent mark sweep GC freed 14760(898KB) AllocSpace objects, 1(16KB) LOS objects, 29% free, 37MB/53MB, paused 5.556ms total 214.635ms
,08-05 02:10:31.568  7549  7549 D ResourcesManager: creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,08-05 02:10:31.568  1438  1438 D SurfaceWidgetView: destroyHardwareResources():785377010
,08-05 02:10:31.568   772  1575 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-05 02:10:31.568   772  1575 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
08-05 02:10:31.568   772  1575 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
08-05 02:10:31.568   772  1575 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
08-05 02:10:31.568   772  1575 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,08-05 02:10:31.568  1438  1438 D Launcher: onRestart, Launcher: 170816680
,08-05 02:10:31.568  1438  1438 D Launcher: onStart, Launcher: 170816680
,08-05 02:10:31.568  1438  1438 D Launcher.HomeView: onStart
,08-05 02:10:31.568  1438  1438 V ActivityThread: updateVisibility : ActivityRecord{3297d3c token=android.os.BinderProxy@290db832 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
08-05 02:10:31.568  1768  1783 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
,08-05 02:10:31.568  1768  2100 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
08-05 02:10:31.568  1768  2100 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,08-05 02:10:31.578   772   993 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 02:10:31.578   772   993 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,08-05 02:10:31.588  7549  7549 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,08-05 02:10:31.588   267   267 I SurfaceFlinger: id=13 createSurf (1080x1920),1 flag=4, Mauncher
,08-05 02:10:31.588   772  1037 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-05 02:10:31.588   772  1037 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,08-05 02:10:31.598  7549  7549 D elm:14491: ELMEngine.ELMEngine( context ).
,08-05 02:10:31.598   772  1041 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,08-05 02:10:31.598   772  1041 D PointerIcon: setMouseCustomIcon IconType is same.101
08-05 02:10:31.598   772  1041 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
08-05 02:10:31.598   772  1041 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
08-05 02:10:31.598  7549  7549 D elm:14491: MDMBridge.setEnterpriseBridge()
,08-05 02:10:31.598   772  1447 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,08-05 02:10:31.598   772  1447 D ActivityManager: caller:android.app.ApplicationThreadProxy@278b355f, r.packageName :com.sec.esdk.elm
,08-05 02:10:31.598  7549  7549 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,08-05 02:10:31.598  3917  3917 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
,08-05 02:10:31.608   772  1426 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,08-05 02:10:31.608   772  1426 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 7398 uid 10079
,08-05 02:10:31.608   772  7568 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,08-05 02:10:31.608  3917  3917 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-05 02:10:31.608  3917  3917 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
,08-05 02:10:31.608  3917  3917 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
08-05 02:10:31.608  3917  3917 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
08-05 02:10:31.608  3917  3917 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
,08-05 02:10:31.608  3917  3917 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
08-05 02:10:31.608  3917  3917 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:10:31.608  3917  3917 W System.err: 	at android.os.Looper.loop(Looper.java:145)
08-05 02:10:31.608  3917  3917 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-05 02:10:31.608  3917  3917 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
,08-05 02:10:31.608  3917  3917 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 02:10:31.608  3917  3917 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-05 02:10:31.608  3917  3917 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,08-05 02:10:31.618  6791  6791 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
,08-05 02:10:31.618  7549  7549 D elm:14491: ElmAgentService : onCreate()
08-05 02:10:31.618  6791  6791 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
08-05 02:10:31.618  6791  6791 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
,08-05 02:10:31.618   772   993 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,08-05 02:10:31.618  7549  7570 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,08-05 02:10:31.618  7549  7570 D elm:14491: MainReceiver.listeningToPackageRemoved()
08-05 02:10:31.618  7549  7570 D elm:14491: MDMBridge.getInstance()
08-05 02:10:31.618  7549  7570 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,08-05 02:10:31.618  7549  7570 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,08-05 02:10:31.628  6811  6811 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
08-05 02:10:31.628  6811  6811 I PCWCLIENTTRACE_PushUtil: sales region : global
08-05 02:10:31.628  6811  6811 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
08-05 02:10:31.628  6811  6811 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,08-05 02:10:31.648   772   804 D ActivityManager: startService callerProcessName:com.sec.android.app.shealth, calleePkgName: com.sec.android.app.shealth
,08-05 02:10:31.648   772   804 D ActivityManager: caller:android.app.ApplicationThreadProxy@324d4ef1, r.packageName :com.sec.android.app.shealth
,08-05 02:10:31.648   772   993 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,08-05 02:10:31.648  7549  7549 D elm:14491: ElmAgentService : onDestroy().
,08-05 02:10:31.658   772   993 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,08-05 02:10:31.658   772  1575 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,08-05 02:10:31.658   772  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:31.658   772  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:31.658   772  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:31.658   772  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 02:10:31.668   772   993 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 02:10:31.668   772   993 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,08-05 02:10:31.668   772   993 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,08-05 02:10:31.668   772   993 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,08-05 02:10:31.678   772   993 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 02:10:31.678   772   993 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 02:10:31.678   772   993 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,08-05 02:10:31.678   772   993 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
,08-05 02:10:31.678   772   993 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-05 02:10:31.678   772   993 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,08-05 02:10:31.678   772   993 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 02:10:31.678   772   993 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
,08-05 02:10:31.688   772   993 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-1/base.apk
08-05 02:10:31.688   772   993 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
08-05 02:10:31.688   772   993 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
08-05 02:10:31.688   772  1064 D PackageManager: delete codoeFile: 
08-05 02:10:31.688   772  1064 D AASAuninstall: userId = 0, info.removedAppID = 10079, info.uid = 10079, packageName = com.test.thalitest
08-05 02:10:31.688   772  1064 I AASA_removePackage: UID=10079 Target=com.test.thalitest
08-05 02:10:31.698   772  1064 D PackageManager: result of delete: 1{725521437}
,08-05 02:10:31.698   772   993 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,08-05 02:10:31.698  7528  7528 D AndroidRuntime: Shutting down VM
,08-05 02:10:31.698   772   993 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 02:10:31.698   772   993 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,08-05 02:10:31.698  7574  7574 E Zygote  : MountEmulatedStorage()
08-05 02:10:31.698  7574  7574 I libpersona: KNOX_SDCARD checking this for 10043
08-05 02:10:31.698  7574  7574 E Zygote  : v2
08-05 02:10:31.698  7574  7574 I libpersona: KNOX_SDCARD not a persona
,08-05 02:10:31.708   772  1575 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=7574 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-05 02:10:31.708   772  1041 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3c9568c4 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t97} time:171331
,08-05 02:10:31.708   772   993 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 02:10:31.708   772   993 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,08-05 02:10:31.708   772   993 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 02:10:31.718   772   993 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-05 02:10:31.718   772   993 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,08-05 02:10:31.718   772   993 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 02:10:31.718   772   993 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,08-05 02:10:31.718   772   993 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 02:10:31.718   772   993 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
08-05 02:10:31.718   772   993 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,08-05 02:10:31.718   348   348 I art     : Explicit concurrent mark sweep GC freed 8761(372KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 311us total 17.005ms
,08-05 02:10:31.728  7574  7574 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
08-05 02:10:31.728  7574  7574 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
08-05 02:10:31.728  7574  7574 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,08-05 02:10:31.728   772   993 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 02:10:31.728   772  1575 I ActivityManager: Killing 5539:com.android.calendar/u0a172 (adj 15): emptyCount ##41
,08-05 02:10:31.728   772   993 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,08-05 02:10:31.728   772   993 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
08-05 02:10:31.728   772  1064 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
08-05 02:10:31.728   772  1064 D PackageManager: userId{-1}
08-05 02:10:31.728   772  1064 D PackageManager: andCode{true}
,08-05 02:10:31.728   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 282us total 9.735ms
,08-05 02:10:31.738   772  1064 D ActivityManager: caller:null, r.packageName :com.android.defcontainer
,08-05 02:10:31.738   772   993 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,08-05 02:10:31.748   348   348 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 284us total 9.660ms
,08-05 02:10:31.748  7574  7574 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 02:10:31.748  7574  7574 D ActivityThread: Added TimaKeyStore provider
,08-05 02:10:31.758   772   993 D UsbSettingsManager: clearDefaults: com.test.thalitest
,08-05 02:10:31.758   772   993 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,08-05 02:10:31.768  7574  7574 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,08-05 02:10:31.798  7574  7574 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,08-05 02:10:31.798  7574  7574 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,08-05 02:10:31.808  7574  7574 D SPPClientService: PushLog.txt file is not deleted.
08-05 02:10:31.808  7574  7574 D SPPClientService: PushLog.txt file is not deleted.
,08-05 02:10:31.808  7574  7574 D SPPClientService: ============PushLog. stop!
,08-05 02:10:31.818   772  1522 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,08-05 02:10:31.818   772  1522 D ActivityManager: caller:android.app.ApplicationThreadProxy@34aff412, r.packageName :com.samsung.android.app.galaxyfinder
,08-05 02:10:31.828  6878  6878 I SA      : [SUR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,08-05 02:10:31.828  6878  6878 I SA      : [SUR] onReceive Intent=[ action_PACKAGE_REMOVED package extra.REMOVED_FOR_ALL_USERS.:true extra.UID.:10079 extra.DATA_REMOVED.:true extra.user_handle.:0 ]
,08-05 02:10:31.828   772  1144 I ActivityManager: Killing 6480:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 15): emptyCount ##41
,08-05 02:10:31.838   772   802 D ActivityManager: startService callerProcessName:com.android.providers.contacts, calleePkgName: com.android.providers.contacts
,08-05 02:10:31.838   772   802 D ActivityManager: caller:android.app.ApplicationThreadProxy@233497e3, r.packageName :com.android.providers.contacts
,08-05 02:10:31.918  6898  6898 D Mms/FreeMessageReceiver: onReceive, action : android.intent.action.PACKAGE_REMOVED
,08-05 02:10:31.918   772  1575 D ActivityManager: startService callerProcessName:com.android.mms, calleePkgName: com.android.mms
08-05 02:10:31.918   772  1575 D ActivityManager: caller:android.app.ApplicationThreadProxy@b72f099, r.packageName :com.android.mms
,08-05 02:10:31.928   772  1426 I TactileAssist: enable value -1
08-05 02:10:31.928   772  1426 I TactileAssist: internal enable value -1
08-05 02:10:31.928   772  1426 I TactileAssist: intensity value -1
08-05 02:10:31.928   772  1426 I TactileAssist: saveAppList value true
,08-05 02:10:31.928   772  1426 I TactileAssist: List of disabled apps :
,08-05 02:10:31.938  6898  7592 D Mms/FreeMessageReceiverService: onHandleIntent, action : android.intent.action.PACKAGE_REMOVED
08-05 02:10:31.938  6898  7592 D Mms/FreeMessageReceiverService: onHandleIntent: ACTION_PACKAGE_REMOVED
,08-05 02:10:31.948   772   804 D SettingsProvider: name = reading_mode_app_list
,08-05 02:10:31.948  6939  6939 D Compatibility: onReceive() it will make start service
,08-05 02:10:31.948   772  1425 D ActivityManager: startService callerProcessName:com.sec.android.app.soundalive, calleePkgName: com.sec.android.app.soundalive
08-05 02:10:31.948   772  1425 D ActivityManager: caller:android.app.ApplicationThreadProxy@1d8ecf3f, r.packageName :com.sec.android.app.soundalive
,08-05 02:10:31.958  6939  7593 D Compatibility: onHandleIntent()
,08-05 02:10:31.958  6939  7593 D Compatibility: intentservice saw: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.android.app.soundalive/.compatibility.Compatibility$Receiver (has extras) } Bundle[{android.intent.extra.REMOVED_FOR_ALL_USERS=true, android.intent.extra.UID=10079, android.intent.extra.DATA_REMOVED=true, android.intent.extra.user_handle=0}]
,08-05 02:10:31.958  6939  7593 D Compatibility: found: 2
,08-05 02:10:31.958  6939  7593 D Compatibility: saved default: com.sec.android.app.soundalive.SAControlPanelActivity
08-05 02:10:31.958  6939  7593 D Compatibility: skipping ResolveInfo{2349e4cb com.sec.android.app.soundalive/.compatibility.Compatibility$Redirector p=2147483647 m=0x108000}
08-05 02:10:31.958   772  1240 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-05 02:10:31.958  6939  7593 D Compatibility: considering ResolveInfo{a2e74a8 com.sec.android.app.soundalive/.SAControlPanelActivity m=0x108000}
08-05 02:10:31.958  6939  7593 D Compatibility: default: com.sec.android.app.soundalive.SAControlPanelActivity
,08-05 02:10:31.958   772  1240 D ActivityManager: caller:android.app.ApplicationThreadProxy@3ff8fd55, r.packageName :com.google.android.googlequicksearchbox
,08-05 02:10:31.958  6939  7593 D Compatibility: enabling receiver ResolveInfo{1f430bc1 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-05 02:10:31.968  6939  7593 D Compatibility: enabling receiver ResolveInfo{1566ff66 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-05 02:10:31.968  6939  7593 D Compatibility: enabling receiver ResolveInfo{2d9002a7 com.sec.android.app.soundalive/.SAControlPanelReceiver m=0x108000}
,08-05 02:10:31.968  1484  7595 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-05 02:10:31.978  6939  7593 D Compatibility: enabling receiver ResolveInfo{3b4a3354 com.sec.android.app.soundalive/.compatibility.HelperGooglePlayMusic m=0x108000}
,08-05 02:10:31.978  6939  7593 D Compatibility: wrote com.sec.android.app.soundalive/com.sec.android.app.soundalive.SAControlPanelActivity as default
,08-05 02:10:31.998   772   804 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,08-05 02:10:31.998   772   804 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 287, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
08-05 02:10:31.998   772   804 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,08-05 02:10:31.998   772   804 D BatteryService: stay LED for fully charged
08-05 02:10:31.998   772   772 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,08-05 02:10:32.008  1191  1191 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
08-05 02:10:32.008   772   772 I MotionRecognitionService: Plugged
08-05 02:10:32.008   772   772 I MotionRecognitionService: setPowerConnected  = true
,08-05 02:10:32.008  1191  1191 D KeyguardUpdateMonitor: handleBatteryUpdate
,08-05 02:10:32.008  1191  1191 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
08-05 02:10:32.008  3204  3204 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
08-05 02:10:32.008  3204  3274 D HeadsetStateMachine: Disconnected process message: 10
,08-05 02:10:32.008  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
08-05 02:10:32.008  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-05 02:10:32.008  1191  1191 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,08-05 02:10:32.008  6511  6511 I art     : Explicit concurrent mark sweep GC freed 122(6KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 15MB/20MB, paused 379us total 23.843ms
,08-05 02:10:32.018  6511  6511 E SQLiteLog: (28) failed to open "/data/user/0/com.samsung.android.sm/databases/seatbelt.db" with flag (131138) and mode_t (0) due to error (30)
,08-05 02:10:32.018  6511  6511 E SQLiteDatabase: Failed to open database '/data/user/0/com.samsung.android.sm/databases/seatbelt.db'.
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.i.<init>(MalwareDatabaseHelper.java:40)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.i.a(MalwareDatabaseHelper.java:28)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.b.<init>(ApkManager.java:52)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at com.samsung.android.sm.common.security.b.a(ApkManager.java:36)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:188)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-05 02:10:32.018  6511  6511 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,08-05 02:10:32.018  6511  6511 D AndroidRuntime: Shutting down VM
08-05 02:10:32.018  6511  6511 E AndroidRuntime: FATAL EXCEPTION: main
08-05 02:10:32.018  6511  6511 E AndroidRuntime: Process: com.samsung.android.sm, PID: 6511
08-05 02:10:32.018  6511  6511 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.samsung.android.sm.ui.security.MonitorReceiver: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2996)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at com.samsung.android.sm.common.security.i.<init>(MalwareDatabaseHelper.java:40)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at com.samsung.android.sm.common.security.i.a(MalwareDatabaseHelper.java:28)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at com.samsung.android.sm.common.security.b.<init>(ApkManager.java:52)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at com.samsung.android.sm.common.security.b.a(ApkManager.java:36)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.b(MonitorReceiver.java:188)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at com.samsung.android.sm.ui.security.MonitorReceiver.onReceive(MonitorReceiver.java:67)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
08-05 02:10:32.018  6511  6511 E AndroidRuntime: 	... 9 more
08-05 02:10:32.018   772  1425 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.sm
08-05 02:10:32.028  6511  6511 I Process : Sending signal. PID: 6511 SIG: 9
08-05 02:10:32.028   772  7597 E DropBoxManagerService: Can't write: system_app_crash
08-05 02:10:32.028   772  7597 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop186.tmp: open failed: EROFS (Read-only file system)
08-05 02:10:32.028   772  7597 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-05 02:10:32.028   772  7597 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 02:10:32.028   772  7597 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 02:10:32.028   772  7597 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 02:10:32.028   772  7597 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-05 02:10:32.028   772  7597 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
08-05 02:10:32.028   772  7597 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 02:10:32.028   772  7597 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 02:10:32.028   772  7597 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 02:10:32.028   772  7597 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-05 02:10:32.028   772  7597 E DropBoxManagerService: 	... 5 more
08-05 02:10:32.038  1484  7595 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
08-05 02:10:32.038  1484  7595 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-05 02:10:32.038   772  1144 D ActivityManager: startService callerProcessName:com.google.android.googlequicksearchbox, calleePkgName: com.google.android.googlequicksearchbox
08-05 02:10:32.038   772  1144 W ActivityManager: Unable to start service Intent { cmp=com.google.android.googlequicksearchbox/com.google.android.apps.gsa.d.b (has extras) } U=0: not found
08-05 02:10:32.038  1484  7595 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
08-05 02:10:32.048  1484  7595 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-05 02:10:32.048  1484  7595 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 1484
08-05 02:10:32.048  1484  7595 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-05 02:10:32.048  1484  7595 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-05 02:10:32.048  1484  7595 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:725)
08-05 02:10:32.048  1484  7595 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-05 02:10:32.048  1484  7595 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-05 02:10:32.048  1484  7595 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:510)
08-05 02:10:32.048  1484  7595 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:421)
08-05 02:10:32.048  1484  7595 E AndroidRuntime: 	at com.google.android.search.core.icingsync.c.e(ApplicationsHelper.java:193)
08-05 02:10:32.048  1484  7595 E AndroidRuntime: 	at com.google.android.search.core.icingsync.w.g(InternalIcingCorporaProvider.java:587)
08-05 02:10:32.048  1484  7595 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:290)
08-05 02:10:32.048  1484  7595 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:330)
08-05 02:10:32.048  1484  7595 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1343)
08-05 02:10:32.048  1484  7595 E AndroidRuntime: 	at com.google.android.search.core.icingsync.z.amO(UpdateIcingCorporaService.java:358)
08-05 02:10:32.048  1484  7595 E AndroidRuntime: 	at com.google.android.search.core.icingsync.ab.amQ(UpdateIcingCorporaService.java:297)
08-05 02:10:32.048  1484  7595 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:270)
08-05 02:10:32.048  1484  7595 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.aF(UpdateIcingCorporaService.java:194)
08-05 02:10:32.048  1484  7595 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:182)
08-05 02:10:32.048  1484  7595 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-05 02:10:32.048  1484  7595 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:10:32.048  1484  7595 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-05 02:10:32.048  1484  7595 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-05 02:10:32.048   772   802 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.google.android.googlequicksearchbox:search
08-05 02:10:32.048  1484  7595 I Process : Sending signal. PID: 1484 SIG: 9
08-05 02:10:32.048   772  7598 E DropBoxManagerService: Can't write: system_app_crash
08-05 02:10:32.048   772  7598 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop187.tmp: open failed: EROFS (Read-only file system)
08-05 02:10:32.048   772  7598 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-05 02:10:32.048   772  7598 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 02:10:32.048   772  7598 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 02:10:32.048   772  7598 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 02:10:32.048   772  7598 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-05 02:10:32.048   772  7598 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
08-05 02:10:32.048   772  7598 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 02:10:32.048   772  7598 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 02:10:32.048   772  7598 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 02:10:32.048   772  7598 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-05 02:10:32.048   772  7598 E DropBoxManagerService: 	... 5 more
,08-05 02:10:32.068   772  1706 I ActivityManager: Process com.samsung.android.sm (pid 6511)(adj 0) has died(355,1509)
08-05 02:10:32.068   772   996 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.assistantmenu, hostingType: broadcast
08-05 02:10:32.068   772   996 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:32.068   772   996 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:32.068   772   996 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:32.068   772   996 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:32.098   772  1122 I EventHub: Removing device '/dev/input/event6' due to inotify event
,08-05 02:10:32.118  7599  7599 E Zygote  : MountEmulatedStorage()
08-05 02:10:32.118  7599  7599 E Zygote  : v2
,08-05 02:10:32.118  7599  7599 I libpersona: KNOX_SDCARD checking this for 1000
08-05 02:10:32.118  7599  7599 I libpersona: KNOX_SDCARD not a persona
,08-05 02:10:32.128   772  1122 I EventHub: Removing device '/dev/input/event7' due to inotify event
,08-05 02:10:32.128   772   996 I ActivityManager: Start proc com.samsung.android.app.assistantmenu for broadcast com.samsung.android.app.assistantmenu/.AssistantMenuReceiver: pid=7599 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-05 02:10:32.128   772  1636 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 1484)(adj 1) has died(365,1509)
,08-05 02:10:32.128   772  1636 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 1000ms
,08-05 02:10:32.128   772  1636 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.hotword.service.HotwordService in 10999ms
,08-05 02:10:32.168   772  1122 I EventHub: Removing device '/dev/input/event8' due to inotify event
,08-05 02:10:32.178  7599  7599 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-05 02:10:32.178  7599  7599 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-05 02:10:32.198   772  1122 I EventHub: Removing device '/dev/input/event9' due to inotify event
,08-05 02:10:32.198  7599  7599 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 02:10:32.198  7599  7599 D ActivityThread: Added TimaKeyStore provider
,08-05 02:10:32.218  7599  7599 D ResourcesManager: creating new AssetManager and set to /system/app/AssistantMenu2/AssistantMenu2.apk
,08-05 02:10:32.218  7599  7599 W ContextImpl: Unable to create files subdir /data/data/com.samsung.android.app.assistantmenu/cache
08-05 02:10:32.218  7599  7599 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,08-05 02:10:32.228  7599  7599 W         : Zip: inflate read failed (14029 vs 32768)
,08-05 02:10:32.228  7599  7599 D AndroidRuntime: Shutting down VM
,08-05 02:10:32.238   772  1122 I EventHub: Removing device '/dev/input/event10' due to inotify event
,08-05 02:10:32.238  7599  7599 E AndroidRuntime: FATAL EXCEPTION: main
08-05 02:10:32.238  7599  7599 E AndroidRuntime: Process: com.samsung.android.app.assistantmenu, PID: 7599
08-05 02:10:32.238  7599  7599 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate receiver com.samsung.android.app.assistantmenu.AssistantMenuReceiver: java.lang.ClassNotFoundException: Didn't find class "com.samsung.android.app.assistantmenu.AssistantMenuReceiver" on path: DexPathList[[zip file "/system/app/AssistantMenu2/AssistantMenu2.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2970)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: Caused by: java.lang.ClassNotFoundException: Didn't find class "com.samsung.android.app.assistantmenu.AssistantMenuReceiver" on path: DexPathList[[zip file "/system/app/AssistantMenu2/AssistantMenu2.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2965)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 	... 9 more
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 	Suppressed: java.io.IOException: Failed to extract 'classes.dex' from '/system/app/AssistantMenu2/AssistantMenu2.apk': I/O Error
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFileNative(Native Method)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:80)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:59)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Native Method)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Method.java:372)
08-05 02:10:32.238  7599,  7599 E AndroidRuntime: 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5082)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		... 7 more
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open file '/data/dalvik-cache/arm/system@app@AssistantMenu2@AssistantMenu2.apk@classes.dex': Read-only file system
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		... 27 more
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/app/AssistantMenu2/AssistantMenu2.apk'
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		... 27 more
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from /system/app/AssistantMenu2/arm/AssistantMenu2.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		... 27 more
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 	Caused by: java.io.IOException: 
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		... 27 more
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 	Suppressed: java.lang.ClassNotFoundException: com.samsung.android.app.assistantmenu.AssistantMenuReceiver
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		at java.lang.Class.classForName(Native Method)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 		... 11 more
08-05 02:10:32.238  7599  7599 E AndroidRuntime: 	Caused by: java.lang.NoCl
,08-05 02:10:32.238   772  1425 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.app.assistantmenu
,08-05 02:10:32.238  7599  7599 I Process : Sending signal. PID: 7599 SIG: 9
,08-05 02:10:32.238   772  7614 E DropBoxManagerService: Can't write: system_app_crash
08-05 02:10:32.238   772  7614 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop188.tmp: open failed: EROFS (Read-only file system)
08-05 02:10:32.238   772  7614 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-05 02:10:32.238   772  7614 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 02:10:32.238   772  7614 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 02:10:32.238   772  7614 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 02:10:32.238   772  7614 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-05 02:10:32.238   772  7614 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
08-05 02:10:32.238   772  7614 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 02:10:32.238   772  7614 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 02:10:32.238   772  7614 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 02:10:32.238   772  7614 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-05 02:10:32.238   772  7614 E DropBoxManagerService: 	... 5 more
,08-05 02:10:32.248  7196  7196 D RCPManager:  in createShortcut() for packageName: com.test.thalitest userId0
,08-05 02:10:32.248   772  1636 D RCPManagerService:  in createShortcut() for packageName: com.test.thalitest userId0
08-05 02:10:32.248   772  1636 D RCPManagerService: queryAllProviders():  providerCallBack is not register for 0
,08-05 02:10:32.248   264   264 E lowmemorykiller: Error writing /proc/7599/oom_score_adj; errno=22
,08-05 02:10:32.258   264   264 E lowmemorykiller: Error writing /proc/7599/oom_score_adj; errno=22
,08-05 02:10:32.268  7016  7016 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.samsung.android.app.filterinstaller.PackageIntentReceiver.onReceive:55 android.app.ActivityThread.handleReceiver:2989 
,08-05 02:10:32.268   772  1575 D ActivityManager: startService callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.app.filterinstaller
,08-05 02:10:32.268   772  1575 D ActivityManager: caller:android.app.ApplicationThreadProxy@2cb3dc36, r.packageName :com.samsung.android.app.filterinstaller
,08-05 02:10:32.278   264   264 E lowmemorykiller: Error writing /proc/7599/oom_score_adj; errno=22
,08-05 02:10:32.278   772  1425 D ActivityManager: startProcessLocked calleePkgName: com.android.keychain, hostingType: broadcast
,08-05 02:10:32.278   772  1425 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:32.278   772  1425 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:32.278   772  1425 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:32.278   772  1425 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 02:10:32.308   772  1122 I EventHub: Removing device '/dev/input/event11' due to inotify event
,08-05 02:10:32.318   772  1425 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7616 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-05 02:10:32.318  7616  7616 E Zygote  : MountEmulatedStorage()
08-05 02:10:32.318  7616  7616 E Zygote  : v2
08-05 02:10:32.318  7616  7616 I libpersona: KNOX_SDCARD checking this for 1000
08-05 02:10:32.318  7616  7616 I libpersona: KNOX_SDCARD not a persona
,08-05 02:10:32.318   772  1636 D ActivityManager: getContentProviderImpl callerProcessName:com.samsung.android.app.filterinstaller, calleePkgName: com.samsung.android.provider.filterprovider
,08-05 02:10:32.328   772  1636 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 02:10:32.328   772  1636 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:32.328   772  1636 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:32.328   772  1636 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 02:10:32.348   772  1122 I EventHub: Removing device '/dev/input/event12' due to inotify event
,08-05 02:10:32.368  7616  7616 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-05 02:10:32.368  7616  7616 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-05 02:10:32.378   772  1122 I EventHub: Removing device '/dev/input/event13' due to inotify event
,08-05 02:10:32.378  7624  7624 E Zygote  : MountEmulatedStorage()
08-05 02:10:32.378  7624  7624 E Zygote  : v2
08-05 02:10:32.378  7624  7624 I libpersona: KNOX_SDCARD checking this for 10121
08-05 02:10:32.378  7624  7624 I libpersona: KNOX_SDCARD not a persona
,08-05 02:10:32.378   772  1636 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for content provider com.samsung.android.provider.filterprovider/.FilterProvider: pid=7624 uid=10121 gids={50121, 9997, 1023} abi=armeabi-v7a
,08-05 02:10:32.378   772   804 I ActivityManager: Process com.samsung.android.app.assistantmenu (pid 7599)(adj 15) has died(365,1509)
,08-05 02:10:32.388   772  3130 E libprocessgroup: failed to kill 1 processes for processgroup 1484
,08-05 02:10:32.418  7624  7624 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-05 02:10:32.418   772  1122 I EventHub: Removing device '/dev/input/event14' due to inotify event
,08-05 02:10:32.418  7624  7624 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-05 02:10:32.418  7616  7616 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 02:10:32.418  7616  7616 D ActivityThread: Added TimaKeyStore provider
,08-05 02:10:32.438  7616  7616 D ResourcesManager: creating new AssetManager and set to /system/app/KeyChain/KeyChain.apk
,08-05 02:10:32.448  7616  7616 W ContextImpl: Unable to create files subdir /data/data/com.android.keychain/cache
08-05 02:10:32.448  7616  7616 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,08-05 02:10:32.448  7624  7624 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 02:10:32.448  7624  7624 D ActivityThread: Added TimaKeyStore provider
,08-05 02:10:32.458  7624  7624 D ResourcesManager: creating new AssetManager and set to /system/app/FilterProvider/FilterProvider.apk
,08-05 02:10:32.458  7624  7624 W ContextImpl: Unable to create files subdir /data/user/0/com.samsung.android.provider.filterprovider/cache
08-05 02:10:32.458  7624  7624 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,08-05 02:10:32.468  7616  7616 D AndroidRuntime: Shutting down VM
,08-05 02:10:32.468   772  1426 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
08-05 02:10:32.468   772  1426 D ActivityManager: caller:android.app.ApplicationThreadProxy@2245e4a4, r.packageName :com.google.android.apps.plus
,08-05 02:10:32.468  7624  7624 D AndroidRuntime: Shutting down VM
,08-05 02:10:32.468  7616  7616 E AndroidRuntime: FATAL EXCEPTION: main
08-05 02:10:32.468  7616  7616 E AndroidRuntime: Process: com.android.keychain, PID: 7616
08-05 02:10:32.468  7616  7616 E AndroidRuntime: java.lang.RuntimeException: Unable to instantiate receiver com.android.keychain.KeyChainBroadcastReceiver: java.lang.ClassNotFoundException: Didn't find class "com.android.keychain.KeyChainBroadcastReceiver" on path: DexPathList[[zip file "/system/app/KeyChain/KeyChain.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2970)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: Caused by: java.lang.ClassNotFoundException: Didn't find class "com.android.keychain.KeyChainBroadcastReceiver" on path: DexPathList[[zip file "/system/app/KeyChain/KeyChain.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2965)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 	... 9 more
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 	Suppressed: java.io.IOException: Zip archive '/system/app/KeyChain/KeyChain.apk' doesn't contain classes.dex (error msg: Entry not found)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFileNative(Native Method)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:80)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:59)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Native Method)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Method.java:372)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at android.app.ApplicationLoaders.openArtFil,e(ApplicationLoaders.java:62)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5082)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		... 7 more
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/app/KeyChain/KeyChain.apk'
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		... 27 more
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from /system/app/KeyChain/arm/KeyChain.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		... 27 more
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 	Caused by: java.io.IOException: 
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		... 27 more
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 	Suppressed: java.lang.ClassNotFoundException: com.android.keychain.KeyChainBroadcastReceiver
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at java.lang.Class.classForName(Native Method)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 		... 11 more
08-05 02:10:32.468  7616  7616 E AndroidRuntime: 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
08-05 02:10:32.478  7624  7624 E AndroidRuntime: FATAL EXCEPTION: main
08-05 02:10:32.478  7624  7624 E AndroidRuntime: Process: com.samsung.android.provider.filterprovider, PID: 7624
08-05 02:10:32.478  7624  7624 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.samsung.android.provider.filterprovider.FilterProvider: java.lang.ClassNotFoundException: Didn't find class "com.samsung.android.provider.filterprovider.FilterProvider" on path: DexPathList[[zip file "/system/app/FilterProvider/FilterProvider.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5558)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:5150)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5090)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:145)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
,08-05 02:10:32.478  7624  7624 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: Caused by: java.lang.ClassNotFoundException: Didn't find class "com.samsung.android.provider.filterprovider.FilterProvider" on path: DexPathList[[zip file "/system/app/FilterProvider/FilterProvider.apk"],nativeLibraryDirectories=[/vendor/lib, /system/lib]]
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 	at dalvik.system.BaseDexClassLoader.findClass(BaseDexClassLoader.java:56)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:511)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 	at java.lang.ClassLoader.loadClass(ClassLoader.java:469)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5543)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 	... 11 more
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 	Suppressed: java.io.IOException: Zip archive '/system/app/FilterProvider/FilterProvider.apk' doesn't contain classes.dex (error msg: Entry not found)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFileNative(Native Method)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		at dalvik.system.DexFile.openDexFile(DexFile.java:295)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:80)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		at dalvik.system.DexFile.<init>(DexFile.java:59)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		at dalvik.system.DexPathList.loadDexFile(DexPathList.java:262)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		at dalvik.system.DexPathList.makeDexElements(DexPathList.java:231)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		at dalvik.system.DexPathList.<init>(DexPathList.java:109)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		at dalvik.system.BaseDexClassLoader.<init>(BaseDexClassLoader.java:48)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		at dalvik.system.PathClassLoader.<init>(PathClassLoader.java:65)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		at dalvik.system.PathClassLoader.openArtFile(PathClassLoader.java:76)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Native Method)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		at java.lang.reflect.Method.invoke(Method.java:372)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		at android.app.ApplicationLoaders.openArtFile(ApplicationLoaders.java:62)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:118)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		at android.app.ApplicationLoaders.getClassLoader(ApplicationLoaders.java:45)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		at android.app.LoadedApk.getClassLoader(LoadedApk.java:415)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		at android.app.LoadedApk.makeApplication(LoadedApk.java:615)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5082)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		... 9 more
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from dex location '/system/app/FilterProvider/FilterProvider.apk'
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		... 27 more
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 	Caused by: java.io.IOException: Failed to open oat file from /system/app/FilterProvider/arm/FilterProvider.odex (error Failed to open oat filename for reading: No such file or directory) (no dalvik_cache availible) and relocation failed.
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		... 27 more
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 	Caused by: java.io.IOException: 
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		... 27 more
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 	Suppressed: java.lang.ClassNotFoundException: com.samsung.android.provider.filterprovider.FilterProvider
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		at java.lang.Class.classForName(Native Method)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		at java.lang.BootClassLoader.findClass(ClassLoader.java:781)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		at java.lang.BootClassLoader.loadClass(ClassLoader.java:841)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		at java.lang.ClassLoader.loadClass(ClassLoader.java:504)
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 		... 13 more
08-05 02:10:32.478  7624  7624 E AndroidRuntime: 	Caused by: java.lang.NoClassDefFoundError: Class not found using the boot class loader; no stack available
08-05 02:10:32.478   772  1690 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.samsung.android.provider.filterprovider
08-05 02:10:32.478  7624  7624 I Process : Sending signal. PID: 7624 SIG: 9
08-05 02:10:32.478   772  1654 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.android.keychain
08-05 02:10:32.478   772  7648 E DropBoxManagerService: Can't write: system_app_crash
08-05 02:10:32.478   772  7648 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop190.tmp: open failed: EROFS (Read-only file system)
08-05 02:10:32.478   772  7648 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-05 02:10:32.478   772  7648 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 02:10:32.478   772  7648 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 02:10:32.478   772  7648 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 02:10:32.478   772  7648 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-05 02:10:32.478   772  7648 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
08-05 02:10:32.478   772  7648 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 02:10:32.478   772  7648 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 02:10:32.478   772  7648 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 02:10:32.478   772  7648 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-05 02:10:32.478   772  7648 E DropBoxManagerService: 	... 5 more
08-05 02:10:32.488   772  7647 E DropBoxManagerService: Can't write: system_app_crash
08-05 02:10:32.488   772  7647 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop189.tmp: open failed: EROFS (Read-only file system)
08-05 02:10:32.488   772  7647 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-05 02:10:32.488   772  7647 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-05 02:10:32.488   772  7647 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-05 02:10:32.488   772  7647 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-05 02:10:32.488   772  7647 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-05 02:10:32.488   772  7647 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$24.run(ActivityManagerService.java:15154)
08-05 02:10:32.488   772  7647 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-05 02:10:32.488   772  7647 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-05 02:10:32.488   772  7647 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-05 02:10:32.488   772  7647 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-05 02:10:32.488   772  7647 E DropBoxManagerService: 	... 5 more
08-05 02:10:32.488   772  1447 D ActivityManager: startService callerProcessName:com.google.android.apps.plus, calleePkgName: com.google.android.apps.plus
08-05 02:10:32.488   772  1447 D ActivityManager: caller:android.app.ApplicationThreadProxy@25d985c2, r.packageName :com.google.android.apps.plus
08-05 02:10:32.488   772   802 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.app.popupuireceiver, hostingType: broadcast
08-05 02:10:32.488   772   802 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:32.488   772   802 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:32.488   772   802 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:32.488   772   802 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:32.508  7616  7616 I Process : Sending signal. PID: 7616 SIG: 9
,08-05 02:10:32.528  7650  7650 E Zygote  : MountEmulatedStorage()
08-05 02:10:32.528  7650  7650 E Zygote  : v2
08-05 02:10:32.528  7650  7650 I libpersona: KNOX_SDCARD checking this for 1000
08-05 02:10:32.528  7650  7650 I libpersona: KNOX_SDCARD not a persona
08-05 02:10:32.528   772   802 I ActivityManager: Start proc com.sec.android.app.popupuireceiver for broadcast com.sec.android.app.popupuireceiver/.PopupuiReceiver: pid=7650 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,08-05 02:10:32.578  7650  7650 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,08-05 02:10:32.578  7650  7650 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,08-05 02:10:32.578   772  1690 I ActivityManager: Process com.android.keychain (pid 7616)(adj 9) has died(364,1509)
,08-05 02:10:32.578   772  1575 I ActivityManager: Process com.samsung.android.provider.filterprovider (pid 7624)(adj 5) has died(364,1509)
,08-05 02:10:32.578   772  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 02:10:32.578   772  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:32.578   772  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
08-05 02:10:32.578   772  1575 E ActivityManager: checkUser: useridlist=null, currentuser=0
,08-05 02:10:32.588   306   306 E SMD     : DCD ON
,08-05 02:10:32.608  7650  7650 D TimaKeyStoreProvider: TimaSignature is unavailable
,08-05 02:10:32.608  7650  7650 D ActivityThread: Added TimaKeyStore provider
,08-05 02:10:32.658  7666  7666 E Zygote  : MountEmulatedStorage()
,08-05 02:10:32.658  7666  7666 E Zygote  : v2
08-05 02:10:32.658  7666  7666 I libpersona: KNOX_SDCARD checking this for 10121
08-05 02:10:32.658  7666  7666 I libpersona: KNOX_SDCARD not a persona
,08-05 02:10:32.668   772  1575 I ActivityManager: Start proc com.samsung.android.provider.filterprovider for restart com.samsung.android.provider.filterprovider: pid=7666 uid=10121 gids={50121, 9997, 1023} abi=armeabi-v7a
,08-05 02:10:32.668   267   516 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-05 02:10:32.678  7650  7650 D ResourcesManager: creating new AssetManager and set to /system/app/PopupuiReceiver/PopupuiReceiver.apk
,08-05 02:10:32.688  7650  7650 W ContextImpl: Unable to create files subdir /data/data/com.sec.android.app.popupuireceiver/cache
,08-05 02:10:32.688  7650  7650 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory

```
