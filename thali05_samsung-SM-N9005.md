#### Test 68102130ea857b4_thali05_samsung-SM-N9005 Logs


```
--------- beginning of system
07-28 12:43:20.280   791  1657 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
07-28 12:43:20.290   791  1657 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 300, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-28 12:43:20.290   791  1657 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-28 12:43:20.290   791   791 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-28 12:43:20.290   791   791 I MotionRecognitionService: Plugged
07-28 12:43:20.290   791   791 I MotionRecognitionService: setPowerConnected  = true
--------- beginning of main
07-28 12:43:20.300  1193  1193 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-28 12:43:20.300  1193  1193 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-28 12:43:20.300   791  1657 D BatteryService: stay LED for fully charged
07-28 12:43:20.300  1193  1193 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-28 12:43:20.300  1193  1193 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-28 12:43:20.300  1193  1193 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-28 12:43:20.300  1193  1193 D KeyguardUpdateMonitor: handleBatteryUpdate
07-28 12:43:20.310  3222  3222 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-28 12:43:20.310  3222  3293 D HeadsetStateMachine: Disconnected process message: 10
07-28 12:43:21.120   304   304 E SMD     : DCD ON
,07-28 12:43:21.470  7425  7425 D AndroidRuntime: 
07-28 12:43:21.470  7425  7425 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
07-28 12:43:21.480  7425  7425 D AndroidRuntime: CheckJNI is OFF
07-28 12:43:21.480  7425  7425 D AndroidRuntime: readGMSProperty: start
07-28 12:43:21.480  7425  7425 D AndroidRuntime: readGMSProperty: already setted!!
07-28 12:43:21.480  7425  7425 D AndroidRuntime: readGMSProperty: end
07-28 12:43:21.480  7425  7425 D AndroidRuntime: addProductProperty: start
07-28 12:43:21.670  7425  7425 E AffinityControl: AffinityControl: registerfunction enter
07-28 12:43:21.690  7425  7425 D AndroidRuntime: Calling main entry com.android.commands.am.Am
07-28 12:43:21.700   791  1679 E PersonaManagerService: inState():  stateMachine is null !!
07-28 12:43:21.700   791  1679 I PersonaManagerService: PersonaId don't exist
07-28 12:43:21.700   791  1679 I ActivityManager: do not start freezing screen for locked container getKeyguardshowstate = false
07-28 12:43:21.710   791  1679 V ApplicationPolicy: isApplicationStateBlocked userId 0 pkgname com.test.thalitest
07-28 12:43:21.720   791  1679 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
07-28 12:43:21.720   791  1679 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-28 12:43:21.720   791  1679 W ActivityManager: mDVFSHelper.acquire()
07-28 12:43:21.720   791  1679 D FocusedStackFrame: Set to : 0
07-28 12:43:21.730   791  1679 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:21.730   791  1679 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:21.730   791  1679 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:21.730   791  1679 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:21.780   791  1679 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7441 uid=10079 gids={50079, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
07-28 12:43:21.780   791  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-28 12:43:21.780   791  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
07-28 12:43:21.780   791  1046 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-28 12:43:21.780   791  1046 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
07-28 12:43:21.780  7441  7441 E Zygote  : MountEmulatedStorage()
07-28 12:43:21.790  7425  7425 D AndroidRuntime: Shutting down VM
07-28 12:43:21.790  7441  7441 E Zygote  : v2
07-28 12:43:21.790  7441  7441 I libpersona: KNOX_SDCARD checking this for 10079
07-28 12:43:21.790  7441  7441 I libpersona: KNOX_SDCARD not a persona
07-28 12:43:21.810  7441  7441 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:43:21.810  7441  7441 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:43:21.810  7441  7441 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
07-28 12:43:21.850  7441  7441 D TimaKeyStoreProvider: TimaSignature is unavailable
07-28 12:43:21.850  7441  7441 D ActivityThread: Added TimaKeyStore provider
07-28 12:43:21.850   791  1366 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-28 12:43:21.850   791  1366 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
07-28 12:43:21.850   791  1366 V WindowManager: rotationForOrientationLw(orient=-1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-28 12:43:21.850   791  1366 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-28 12:43:21.850   791  1366 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
07-28 12:43:21.860  1441  1441 D SurfaceWidgetView: destroyHardwareResources():961023008
07-28 12:43:21.890   266   369 I SurfaceFlinger: id=9 Removed Mauncher (6/8)
07-28 12:43:21.900  1441  1441 V ActivityThread: updateVisibility : ActivityRecord{79997a token=android.os.BinderProxy@2c53ff60 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : false
07-28 12:43:21.900  1813  1833 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = false on instance = 1
07-28 12:43:21.900  1441  1441 D Launcher: onTrimMemory. Level: 20
07-28 12:43:21.930   791  3300 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:21.940  7441  7441 D ResourcesManager: creating new AssetManager and set to /data/app/com.test.thalitest-1/base.apk
07-28 12:43:21.940   791  3300 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:22.030  7441  7441 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,07-28 12:43:22.030  7441  7441 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,07-28 12:43:22.050  7441  7441 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 2199-2202)
,07-28 12:43:22.050  7441  7441 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-28 12:43:22.070  7441  7441 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {30b496ab}
,07-28 12:43:22.070  7441  7441 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-28 12:43:22.070  7441  7441 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-28 12:43:22.100  7441  7441 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-28 12:43:22.100  7441  7441 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-28 12:43:22.110  7441  7441 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-28 12:43:22.130  7441  7441 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-28 12:43:22.130  7441  7441 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=50556 len=3379
07-28 12:43:22.130  7441  7441 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:39 off:7638088 len:1165478
,07-28 12:43:22.130  7441  7441 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-28 12:43:22.130  7441  7441 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-28 12:43:22.130  7441  7441 I Adreno-EGL: Build Date: 11/19/14 Wed
07-28 12:43:22.130  7441  7441 I Adreno-EGL: Local Branch: mybranch5813579
07-28 12:43:22.130  7441  7441 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-28 12:43:22.130  7441  7441 I Adreno-EGL: Local Patches: NONE
07-28 12:43:22.130  7441  7441 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-28 12:43:22.270  7441  7476 W chromium: [WARNING:data_reduction_proxy_config.cc(318)] SPDY proxy OFF at startup
,07-28 12:43:22.300  7441  7441 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-28 12:43:22.310  7441  7441 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,07-28 12:43:22.320  7441  7441 D SystemWebViewEngine: CordovaWebView is running on device made by: samsung
,07-28 12:43:22.320  7441  7441 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-28 12:43:22.320  7441  7441 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-28 12:43:22.380  7441  7441 D Activity: performCreate Call secproduct feature valuefalse
,07-28 12:43:22.380  7441  7441 D Activity: performCreate Call debug elastic valuetrue
,07-28 12:43:22.390  7441  7493 D OpenGLRenderer: Render dirty regions requested: true
,07-28 12:43:22.390   791  1476 D ActivityManager: post active user change for 0 fullscreen true record.isFloatingActivity() false
07-28 12:43:22.390   791  1476 D KnoxTimeoutHandler: postActiveUserChange for user 0
07-28 12:43:22.390   791  1476 I KnoxTimeoutHandler: postActiveUserChange, showWhenLocked: false
07-28 12:43:22.390   791   791 D KnoxTimeoutHandler: handleActiveUserChange for user 0
07-28 12:43:22.390   791   791 D PersonaManagerService: getPersonasForUser(): returning null!
,07-28 12:43:22.410   266   266 I SurfaceFlinger: id=12 createSurf (1x1),1 flag=404, NainActivit
,07-28 12:43:22.410   791  1041 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-28 12:43:22.420   791  1041 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-28 12:43:22.420   791  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-28 12:43:22.420   791  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
07-28 12:43:22.420   791  1046 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-28 12:43:22.420   791  1046 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-28 12:43:22.420  7441  7493 I OpenGLRenderer: Initialized EGL, version 1.4
,07-28 12:43:22.430  7441  7493 I OpenGLRenderer: HWUI protection enabled for context ,  &this =0xb3d9cdd0 ,&mEglDisplay = 1 , &mEglConfig = 8 
,07-28 12:43:22.430  7441  7493 D OpenGLRenderer: Enabling debug mode 0
,07-28 12:43:22.450  7441  7441 V ActivityThread: updateVisibility : ActivityRecord{3710e04d token=android.os.BinderProxy@18888b77 {com.test.thalitest/com.test.thalitest.MainActivity}} show : true
,07-28 12:43:22.450   791  1638 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-28 12:43:22.450   791  7496 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-28 12:43:22.460  1865  1865 I SamsungIME: getCurrentCandidateView
,07-28 12:43:22.480  7441  7441 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,07-28 12:43:22.480  7441  7441 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@18888b77 time:152632
,07-28 12:43:22.500   791  1046 W ActivityManager: mDVFSHelper.release()
07-28 12:43:22.500   791  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{32cbb385 u0 com.test.thalitest/.MainActivity t99} time:152652
,07-28 12:43:22.520  7441  7441 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7441
,07-28 12:43:22.530  1865  1865 D SamsungIME: Dismiss ExpandCandiate
,07-28 12:43:22.600  7441  7441 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,07-28 12:43:22.610  1865  1865 I SamsungIME: getDebugLevel  : 0x4f4c
,07-28 12:43:22.650  1865  1865 I SamsungIME: getDebugLevel  : 0x4f4c
,07-28 12:43:22.660  1865  1865 I SamsungIME: KeybaordView init() : load resources
,07-28 12:43:22.680  1865  1865 I SamsungIME: getCurrentKeyboard
,07-28 12:43:22.680  1865  1865 I SamsungIME: getTextKeyboard
,07-28 12:43:22.680  7441  7499 D jxcore_app_log: JniHelper::setJavaVM(0xb4f5c280), pthread_self() = -1360017792
,07-28 12:43:22.690  1865  1865 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-28 12:43:22.690  7441  7499 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
07-28 12:43:22.690  7441  7499 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
07-28 12:43:22.690  7441  7499 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
07-28 12:43:22.690  7441  7499 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
07-28 12:43:22.690  7441  7499 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,07-28 12:43:22.690  7441  7499 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@282776bd added. We now have 1 listener(s)
,07-28 12:43:22.700  7441  7499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: E0:DB:10:1F:C9:5E
,07-28 12:43:22.700  7441  7499 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-28 12:43:22.700  7441  7499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,07-28 12:43:22.700  7441  7499 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-28 12:43:22.710  7441  7499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
07-28 12:43:22.710  7441  7499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
07-28 12:43:22.710  7441  7499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
07-28 12:43:22.710  7441  7499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: E0:DB:10:1F:C9:5E
07-28 12:43:22.710  7441  7499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
07-28 12:43:22.710  7441  7499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
07-28 12:43:22.710  7441  7499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
07-28 12:43:22.710  7441  7499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
07-28 12:43:22.710  7441  7499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
07-28 12:43:22.710  7441  7499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
07-28 12:43:22.710  7441  7499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
07-28 12:43:22.710  7441  7499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
07-28 12:43:22.710  7441  7499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
07-28 12:43:22.710  7441  7499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
07-28 12:43:22.710  7441  7499 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@66e780 added. We now have 1 listener(s)
,07-28 12:43:22.710  7441  7499 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:43:22.710  7441  7499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:43:22.710  7441  7499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,07-28 12:43:22.710  7441  7499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
07-28 12:43:22.710  7441  7499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
07-28 12:43:22.710  7441  7499 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,07-28 12:43:22.720  7441  7499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:43:22.720  7441  7499 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is E0:DB:10:1F:C9:5E
,07-28 12:43:22.720   791   832 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:22.730  7441  7499 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,07-28 12:43:22.730  7441  7499 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:22.730  7441  7499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:22.730  7441  7499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:22.730  7441  7499 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:22.730  7441  7499 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:22.730  7441  7499 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:22.730  7441  7499 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:43:22.730  7441  7499 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:43:22.730  7441  7499 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
07-28 12:43:22.730  7441  7499 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 12:43:22.730   791  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:22.730  7441  7499 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-28 12:43:22.730  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:22.730   791  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:22.730  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:22.770  7441  7441 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,07-28 12:43:23.040  1865  7504 D SamsungIME: [SwiftkeyWrapper] currentLangauge : 1701729619
,07-28 12:43:23.430  7441  7508 W jxcore-log: Initializing JXcore engine
07-28 12:43:23.430  7441  7508 W jxcore-log: JXcore engine is ready
,07-28 12:43:23.480  1871  1871 E auditd  : In denial and Property audit_ondenial is set to 1 
07-28 12:43:23.480  1871  1871 E audit   : type=1400 msg=audit(1469702603.480:203): avc:  denied  { ioctl } for  pid=7508 comm="Thread-1233" path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2886 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,07-28 12:43:23.480  1871  1871 E audit   :  SEPF_SM-N9005_5.0-1_0032
07-28 12:43:23.480  1871  1871 E audit   : 
07-28 12:43:23.480  1871  1871 E audit   : type=1300 msg=audit(1469702603.480:203): arch=40000028 syscall=54 per=800000 success=no exit=-13 a0=7 a1=5451 a2=2 a3=99f008d8 items=0 ppid=347 ppcomm=main pid=7508 auid=4294967295 uid=10079 gid=10079 euid=10079 suid=10079 fsuid=10079 egid=10079 sgid=10079 fsgid=10079 tty=(none) ses=4294967295 comm="Thread-1233" exe="/system/bin/app_process32" subj=u:r:untrusted_app:s0 key=(null)
,07-28 12:43:23.480  1871  1871 E audit   : type=1320 msg=audit(1469702603.480:203): 
07-28 12:43:23.480   791  1032 D SecurityLogAgent:SEDenialService: Got Modify Event and sending Denial Intent foraudit.log
07-28 12:43:23.480   791  1032 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.SEDenialService$AuditFileObserver.onEvent:76 android.os.FileObserver$ObserverThread.onEvent:122 android.os.FileObserver$ObserverThread.observe:-2 android.os.FileObserver$ObserverThread.run:85 
,07-28 12:43:23.480   791   997 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.securitylogagent, hostingType: broadcast
07-28 12:43:23.480   791   997 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:23.480   791   997 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:23.480   791   997 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:23.480   791   997 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:23.480   791  1032 D SecurityLogAgent:SEDenialService: audit.ondenial set to 0 after sending samsung.intent.action.knox.DENIAL_NOTIFICATION intent
,07-28 12:43:23.510  7441  7508 W jxcore-log: Starting JXcore engine
,07-28 12:43:23.540  7514  7514 E Zygote  : MountEmulatedStorage()
07-28 12:43:23.540  7514  7514 I libpersona: KNOX_SDCARD checking this for 1000
07-28 12:43:23.540  7514  7514 E Zygote  : v2
07-28 12:43:23.540  7514  7514 I libpersona: KNOX_SDCARD not a persona
07-28 12:43:23.540   791   997 I ActivityManager: Start proc com.samsung.android.securitylogagent for broadcast com.samsung.android.securitylogagent/.receivers.SeDenialReceiver: pid=7514 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-28 12:43:23.570  7514  7514 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:43:23.570  7514  7514 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:43:23.570  7514  7514 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:43:23.570   347   347 I art     : Explicit concurrent mark sweep GC freed 8782(373KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 9.596ms total 35.964ms
,07-28 12:43:23.580   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 271us total 9.663ms
,07-28 12:43:23.590   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 272us total 9.789ms
,07-28 12:43:23.600  7514  7514 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:43:23.600  7514  7514 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:23.610  7441  7508 W jxcore-log: Platform android
07-28 12:43:23.610  7441  7508 W jxcore-log: 
07-28 12:43:23.610  7441  7508 W jxcore-log: Process ARCH arm
07-28 12:43:23.610  7441  7508 W jxcore-log: 
,07-28 12:43:23.620  7514  7514 D ResourcesManager: creating new AssetManager and set to /system/app/SecurityLogAgent/SecurityLogAgent.apk
,07-28 12:43:23.630  7514  7514 D SecurityLogAgent:  SeDenialReceiver : Intent received : samsung.intent.action.knox.DENIAL_NOTIFICATION
,07-28 12:43:23.630  7514  7514 D SecurityLogAgent:  SeDenialReceiver : File path = null
,07-28 12:43:23.630   791   832 I ActivityManager: Killing 4694:com.google.android.talk/u0a131 (adj 15): emptyCount ##41
,07-28 12:43:23.800  7441  7508 I jxcore-log: JXcore Cordova bridge is ready!
07-28 12:43:23.800  7441  7508 I jxcore-log: 
,07-28 12:43:23.800  7441  7508 W jxcore-log: JXcore engine is started
,07-28 12:43:23.800  7441  7499 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,07-28 12:43:23.810  7441  7441 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,07-28 12:43:24.080   791  1052 I PowerManagerService: [PWL] Off : 75s ago
,07-28 12:43:24.110   304   304 E SMD     : DCD ON
,07-28 12:43:26.740   791  3332 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-28 12:43:27.120   304   304 E SMD     : DCD ON
,07-28 12:43:29.410   791  3300 D SSRM:n  : SIOP:: AP = 390, PST = 378, CUR = 450
,07-28 12:43:30.120   304   304 E SMD     : DCD ON
,07-28 12:43:30.300   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:43:30.330   791  1574 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-28 12:43:30.330   791  1574 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4333, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-28 12:43:30.330   791  1574 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-28 12:43:30.330   791   791 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-28 12:43:30.330  1193  1193 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-28 12:43:30.330  1193  1193 D KeyguardUpdateMonitor: handleBatteryUpdate
07-28 12:43:30.340   791   791 I MotionRecognitionService: Plugged
07-28 12:43:30.340   791   791 I MotionRecognitionService: setPowerConnected  = true
,07-28 12:43:30.340   791  1574 D BatteryService: stay LED for fully charged
,07-28 12:43:30.340  1193  1193 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-28 12:43:30.340  1193  1193 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-28 12:43:30.340  1193  1193 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:43:30.340  1193  1193 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:43:30.340  3222  3222 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
,07-28 12:43:30.340  3222  3293 D HeadsetStateMachine: Disconnected process message: 10
,07-28 12:43:31.300   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:43:31.770   791  1065 D PackageManager: [MSG] WRITE_PACKAGE_RESTRICTIONS
,07-28 12:43:32.300   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:43:33.120   304   304 E SMD     : DCD ON
,07-28 12:43:33.300   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:43:33.960  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
07-28 12:43:33.960  7441  7508 I jxcore-log: 
,07-28 12:43:33.960  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
07-28 12:43:33.960  7441  7508 I jxcore-log: 
,07-28 12:43:33.960   791  1679 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:33.970  7441  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:33.970  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:33.970  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:33.970  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:33.970  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:33.970  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:33.970  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:43:33.970  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:43:33.970  7441  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:43:33.980  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
07-28 12:43:33.980  7441  7508 I jxcore-log: 
,07-28 12:43:33.980  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
07-28 12:43:33.980  7441  7508 I jxcore-log: 
,07-28 12:43:34.300   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:43:34.330  7441  7508 D ExecuteNativeTests: Running unit tests
,07-28 12:43:34.430  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:43:34.430  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f added. We now have 2 listener(s)
,07-28 12:43:34.430  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-28 12:43:34.430  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:43:34.430  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:43:34.430  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:34.430  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac added. We now have 2 listener(s)
07-28 12:43:34.430  7441  7508 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:43:34.430  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:43:34.430  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:43:34.430   791  1428 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:34.440  7441  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:34.440  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:34.440  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:34.440  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:34.440  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:34.440  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:34.440  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:43:34.440  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:43:34.440  7441  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:43:34.440  7441  7508 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 12:43:34.440   791  1657 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:34.440  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,07-28 12:43:34.440  7441  7508 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:43:34.440  7441  7508 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,07-28 12:43:34.440  7441  7508 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,07-28 12:43:34.440  7441  7508 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-28 12:43:34.440  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-28 12:43:34.450  7441  7508 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:43:34.450  7441  7508 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-28 12:43:34.450  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,07-28 12:43:34.450  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.450  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:34.450  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.450  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:43:34.450  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.450   791   832 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:34.450  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:34.450  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:43:34.450  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f removed from the list
07-28 12:43:34.450  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.450  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac removed from the list
,07-28 12:43:34.450  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:34.450  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop,
07-28 12:43:34.450  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left,
,07-28 12:43:34.450  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:43:34.450  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:34.450  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:43:34.450  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 12:43:34.450  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.450  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list,
07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported,
,07-28 12:43:34.460  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,07-28 12:43:34.460  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-28 12:43:34.460  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:43:34.460  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.460  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:43:34.460  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:34.460  7441  7508 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f not in the list
07-28 12:43:34.460  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:43:34.460  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.460  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.460  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.460  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:43:34.460  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.460  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.460  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.460  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:43:34.460  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
,07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
,07-28 12:43:34.460  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-28 12:43:34.470   791  1657 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:34.470  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-28 12:43:34.470  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
07-28 12:43:34.470  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
,07-28 12:43:34.470  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-28 12:43:34.470  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-28 12:43:34.470  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-28 12:43:34.470  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-28 12:43:34.470  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
,07-28 12:43:34.470  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.470  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.470  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.470  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.470  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:43:34.470  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.470  7441  7508 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f not in the list
07-28 12:43:34.470  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.470  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.470  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.470  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:43:34.470  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.470  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.470  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.470  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.470  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,07-28 12:43:34.470  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.470  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.470   791  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:34.470  7441  7508 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 12:43:34.470  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:43:34.470  7441  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:34.470  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:34.470  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:34.470  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:34.470  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:34.470  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:34.470  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:43:34.470  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:43:34.470  7441  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:43:34.470  7441  7508 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:43:34.470  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:34.480   791  1468 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:34.480  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:34.480  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-28 12:43:34.480  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:43:34.480  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:43:34.480  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:43:34.480  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-28 12:43:34.480  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...,
,07-28 12:43:34.480  7441  7508 E BluetoothAdapter: bluetooth le advertising not supported,
07-28 12:43:34.480  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,07-28 12:43:34.490  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0,
,07-28 12:43:34.490  7441  7508 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,07-28 12:43:34.490  7441  7508 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage,
07-28 12:43:34.490  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:43:34.490  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:43:34.490  7441  7508 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager,
07-28 12:43:34.490  7441  7508 I io.jxcore.node.ConnectionHelper: start: OK
,07-28 12:43:34.490  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections,
07-28 12:43:34.490  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.490  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.490  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:43:34.490  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.490  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:34.490  7441  7508 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f not in the list
07-28 12:43:34.490  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.490  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.490  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.490  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.490  7441  7508 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
07-28 12:43:34.500  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:43:34.500   791  1366 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:34.500  7441  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:34.500  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:34.500  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:34.500  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:34.500  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:34.500  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:34.500  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:43:34.500  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:43:34.500  7441  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:43:34.500  7441  7508 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:43:34.500   791  1574 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:34.500  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:34.500   791  1358 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:34.500  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:34.500  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:43:34.500  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:43:34.500  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:43:34.500  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:43:34.500  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-28 12:43:34.510  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-28 12:43:34.510  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:43:34.510  7441  7508 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-28 12:43:34.510  7441  7508 I io.jxcore.node.ConnectionHelper: start: OK
,07-28 12:43:34.510  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,07-28 12:43:34.510  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.510  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.510  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.510  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.510  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:34.510  7441  7508 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f not in the list
07-28 12:43:34.510  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.510  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.510  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.510  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.510  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.510  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.510  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.510  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.510  7441  7508 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:34.510  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:34.510  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.510  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
,07-28 12:43:34.510  7441  7508 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,07-28 12:43:34.510  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:43:34.510   791  1259 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:34.520  7441  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:34.520  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:34.520  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:34.520  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:34.520  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:34.520  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:34.520  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:43:34.520  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:43:34.520  7441  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:34.520  7441  7508 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:43:34.520  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:43:34.520  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:43:34.520   791  1366 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:34.520  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:43:34.520  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:43:34.520  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
07-28 12:43:34.520  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:34.520   791  1468 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:34.520  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:34.520  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:43:34.520  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:34.520  7441  7508 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
07-28 12:43:34.530  7441  7508 I io.jxcore.node.ConnectionHelper: start: OK
07-28 12:43:34.530  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.530  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.530  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.530  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.530  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.530  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.530  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.530  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.530  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:34.530  7441  7508 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f not in the list
07-28 12:43:34.530  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.530  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.530  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.530  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.530  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.530  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.530  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.530  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.530  7441  7508 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:34.530  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:34.530  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.530  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.530  7441  7508 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
07-28 12:43:34.530  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.530  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.530  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.530  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.530  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.530  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.530  7441  7508 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f not in the list
07-28 12:43:34.530  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.530  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.530  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.530  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.530  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.530  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.530  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.530  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.530  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.530  7441  7508 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:34.530  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:34.530  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.530  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.530  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
07-28 12:43:34.530  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.530  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.530  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.530  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.540  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.540  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.540  7441  7508 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f not in the list
07-28 12:43:34.540  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.540  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.540  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.540  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.540  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.540  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.540  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.540  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.540  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.540  7441  7508 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:34.540  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:34.540  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.540  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.540  7441  7508 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
07-28 12:43:34.540  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.540  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.540  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.540  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.540  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.540  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.540  7441  7508 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f not in the list
07-28 12:43:34.540  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.540  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.540  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.540  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.540  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.540  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.540  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.540  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.540  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.540  7441  7508 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:34.540  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:34.540  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.540  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.540  7441  7508 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
07-28 12:43:34.540  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.540  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.540  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.540  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.540  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.540  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.540  7441  7508 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f not in the list
07-28 12:43:34.540  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.540  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.540  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.540  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.540  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.540  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.540  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.540  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.540  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.540  7441  7508 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:34.540  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:34.550  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.550  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.550  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-28 12:43:34.550  7441  7508 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:43:34.550  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
07-28 12:43:34.550  7441  7508 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
07-28 12:43:34.550  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
07-28 12:43:34.550  7441  7508 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
07-28 12:43:34.550  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.550  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.550  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.550  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.550  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.550  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.550  7441  7508 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f not in the list
07-28 12:43:34.550  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.550  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.550  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.550  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.550  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.550  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.550  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.550  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.550  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.550  7441  7508 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:34.550  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:34.550  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.550  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.550  7441  7508 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:43:34.550  7441  7508 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
07-28 12:43:34.550  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,07-28 12:43:34.550  7441  7508 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:43:34.550  7441  7508 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
07-28 12:43:34.550  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
07-28 12:43:34.550  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
07-28 12:43:34.550  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
07-28 12:43:34.550  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
07-28 12:43:34.550  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,07-28 12:43:34.550  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
07-28 12:43:34.550  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
07-28 12:43:34.550  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
07-28 12:43:34.550  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
07-28 12:43:34.550  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
07-28 12:43:34.550  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
07-28 12:43:34.550  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,07-28 12:43:34.550  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
07-28 12:43:34.560  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
07-28 12:43:34.560  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
07-28 12:43:34.560  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
07-28 12:43:34.560  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
07-28 12:43:34.560  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,07-28 12:43:34.560  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
07-28 12:43:34.560  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
07-28 12:43:34.560  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
07-28 12:43:34.560  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
07-28 12:43:34.560  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
07-28 12:43:34.560  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,07-28 12:43:34.560  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
07-28 12:43:34.560  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
07-28 12:43:34.560  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
07-28 12:43:34.560  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
07-28 12:43:34.560  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
07-28 12:43:34.560  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
07-28 12:43:34.560  7441  7508 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
07-28 12:43:34.560  7441  7508 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:43:34.560  7441  7508 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
07-28 12:43:34.560  7441  7508 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:43:34.560  7441  7508 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:43:34.560  7441  7508 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
07-28 12:43:34.560  7441  7508 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:43:34.560  7441  7508 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
07-28 12:43:34.560  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
07-28 12:43:34.560  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
07-28 12:43:34.560  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
07-28 12:43:34.560  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
07-28 12:43:34.570  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
07-28 12:43:34.570  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
07-28 12:43:34.570  7441  7508 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
07-28 12:43:34.570  7441  7508 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
07-28 12:43:34.570  7441  7508 E io.jxcore.node.ConnectionHelper: connect: Callback is null
07-28 12:43:34.570  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.570  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.570  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.570  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.570  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.570  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.570  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
07-28 12:43:34.570  7441  7508 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f not in the list
07-28 12:43:34.570  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.570  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.570  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.570  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.570  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.570  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.570  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.570  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.570  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.570  7441  7508 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:34.570  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:34.570  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.570  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.570  7441  7508 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
07-28 12:43:34.570  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.570  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.570  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.570  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.570  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.570  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.570  7441  7508 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f not in the list
07-28 12:43:34.570  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.570  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.570  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.580  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.580  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.580  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.580  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.580  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.580  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.580  7441  7508 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:34.580  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:34.580  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.580  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.580  7441  7508 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
07-28 12:43:34.580  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.580  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.580  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.580  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.580  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.580  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.580  7441  7508 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f not in the list
07-28 12:43:34.580  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.580  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.580  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.580  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.580  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.580  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.580  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.580  7441  7554 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 1297
07-28 12:43:34.580  7441  7553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 1297)
07-28 12:43:34.580  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.580  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.580  7441  7508 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:34.580  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:34.580  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.580  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.580  7441  7508 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
07-28 12:43:34.580  7441  7508 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
07-28 12:43:34.580  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:43:34.580  7441  7508 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
07-28 12:43:34.580  7441  7508 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-28 12:43:34.580  7441  7508 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
07-28 12:43:34.580  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:43:34.580  7441  7508 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
07-28 12:43:34.590  7441  7508 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
07-28 12:43:34.590  7441  7508 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
07-28 12:43:34.590  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
07-28 12:43:34.590  7441  7508 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
,07-28 12:43:34.590  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.590  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.590  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.590  7441  7553 D BluetoothUtils: isSocketAllowedBySecurityPolicy start : device null
07-28 12:43:34.590  7441  7553 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:43:34.590  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.600  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.600  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.600  7441  7508 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f not in the list
07-28 12:43:34.600  3222  3232 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:43:34.600  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.600  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.600  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.600  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.600  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.600  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.600  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.600  3222  3367 D bt_vendor: op for 7
07-28 12:43:34.600  7441  7553 D BluetoothSocket: connect(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[109]}
07-28 12:43:34.600  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.600  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.600  7441  7508 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:34.600  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:34.600  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.600  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.600  3222  3367 D bt_upio : proc btwrite assertion
07-28 12:43:34.600  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.600  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.600  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.600  7441  7508 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f not in the list
07-28 12:43:34.600  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.600  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.600  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.600  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.600  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.600  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.600  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.600  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.600  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.600  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.600  7441  7508 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f not in the list
07-28 12:43:34.600  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.600  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.600  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.600  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.600  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.600  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.600  7441  7508 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f not in the list
07-28 12:43:34.600  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.600  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.600  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.600  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.610  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.610  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.610  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.610  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.610  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.610  7441  7508 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:34.610  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:34.610  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.610  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.610  7441  7508 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
07-28 12:43:34.610  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:43:34.620  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
07-28 12:43:34.620  7441  7508 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
07-28 12:43:34.620  7441  7508 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
07-28 12:43:34.620  7441  7441 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
07-28 12:43:34.620  7441  7555 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
07-28 12:43:34.620  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
07-28 12:43:34.620  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
07-28 12:43:34.620  7441  7555 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[110]}
07-28 12:43:34.620  7441  7555 D BluetoothSocket: bindListen(), new LocalSocket 
07-28 12:43:34.620  7441  7555 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-28 12:43:34.620  7441  7555 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c14382d
07-28 12:43:34.620  7441  7555 D BluetoothSocket: channel: 6
07-28 12:43:34.620  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.620  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
07-28 12:43:34.620  7441  7555 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
07-28 12:43:34.620  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
07-28 12:43:34.620  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
07-28 12:43:34.620  7441  7508 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2d87d162, channel: 6, state: LISTENING
07-28 12:43:34.630  7441  7508 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2d87d162, channel: 6, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@c14382d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@186c32f3mSocket: android.net.LocalSocket@3889ebb0 impl:android.net.LocalSocketImpl@12a92a29 fd:FileDescriptor[110]
07-28 12:43:34.630  7441  7508 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3889ebb0 impl:android.net.LocalSocketImpl@12a92a29 fd:FileDescriptor[110]
07-28 12:43:34.630  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.630  7441  7555 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2d87d162, channel: 6, state: CLOSED
07-28 12:43:34.630  7441  7555 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
07-28 12:43:34.630  7441  7555 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
07-28 12:43:34.630  7441  7555 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
07-28 12:43:34.630  7441  7508 D org.thali,project.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
07-28 12:43:34.630  7441  7508 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f not in the list
07-28 12:43:34.630  7441  7441 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
07-28 12:43:34.630  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.630  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
07-28 12:43:34.630  7441  7508 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
07-28 12:43:34.630  7441  7441 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
07-28 12:43:34.630  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
07-28 12:43:34.630  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
07-28 12:43:34.630  7441  7508 D BluetoothLeScanner: could not find callback wrapper
,07-28 12:43:34.630  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:34.630  7441  7508 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
07-28 12:43:34.630  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.630  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:34.630  7441  7508 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,07-28 12:43:34.630  7441  7441 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:43:34.630  7441  7441 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
07-28 12:43:34.630  7441  7441 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
07-28 12:43:34.630  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.630  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,07-28 12:43:34.630  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.630  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.630  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.630  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.630  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.630  7441  7508 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f not in the list
07-28 12:43:34.630  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.630  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.630  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.630  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.630  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.630  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.630  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:34.630  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.630  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.630  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.630  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
,07-28 12:43:34.630  7441  7508 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,07-28 12:43:34.640  7441  7508 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
07-28 12:43:34.640  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,07-28 12:43:34.640  7441  7508 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,07-28 12:43:34.640  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:34.640  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.640  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:43:34.640  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.640  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.640  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.640  7441  7508 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f not in the list
07-28 12:43:34.640  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.640  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.640  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.640  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.640  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:34.640  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.640  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:34.640  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.640  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.640  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.640  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
,07-28 12:43:34.640  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,07-28 12:43:34.640  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.640  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.640  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.640  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.640  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:34.640  7441  7508 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f not in the list
07-28 12:43:34.640  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.650  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.650  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.650  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.650  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:34.650  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.650  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:34.650  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.650  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.650  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.650  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
,07-28 12:43:34.650  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,07-28 12:43:34.650  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:34.650  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:34.650  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:34.650  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.650  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:34.650  7441  7508 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e124c5f not in the list
07-28 12:43:34.650  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.650  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
07-28 12:43:34.650  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:34.650  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.650  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:34.650  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:34.650  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:34.650  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:34.650  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:34.650  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:34.650  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2189a6ac not in the list
,07-28 12:43:34.650  7441  7508 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,07-28 12:43:34.650  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:43:34.650  7441  7508 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
07-28 12:43:34.650  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
07-28 12:43:34.650  7441  7508 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
07-28 12:43:34.650  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,07-28 12:43:34.650  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,07-28 12:43:34.650  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,07-28 12:43:34.660  7441  7508 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,07-28 12:43:34.660  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-28 12:43:34.660  7441  7508 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
07-28 12:43:34.660  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
07-28 12:43:34.660  7441  7508 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
,07-28 12:43:34.660  7441  7508 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,07-28 12:43:34.660  7441  7508 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
07-28 12:43:34.660  7441  7508 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
,07-28 12:43:34.660  7441  7508 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
07-28 12:43:34.660  7441  7508 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
07-28 12:43:34.660  7441  7508 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,07-28 12:43:34.660  7441  7508 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
07-28 12:43:34.660  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:34.660  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@195a1ae added. We now have 2 listener(s)
07-28 12:43:34.660  7441  7508 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:43:34.660  7441  7508 D BluetoothAdapter: enable()
07-28 12:43:34.660  7441  7508 D BluetoothAdapter: enable(): BT is already enabled..!
07-28 12:43:34.660  7441  7508 I WifiManager: packageName : com.test.thalitest
07-28 12:43:34.660   791  1428 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-28 12:43:34.660   791  1428 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-28 12:43:34.660   791  1428 D SecContentProvider2: mCursor = null
07-28 12:43:34.660   791  1428 D WifiService: setWifiEnabled: true pid=7441, uid=10079
07-28 12:43:34.660   791  1428 W ActivityManager: Permission Denial: getCurrentUser() from pid=7441, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-28 12:43:34.660   791  1428 W WifiService: Failed getting userId using ActivityManagerNative
07-28 12:43:34.660   791  1428 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7441, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-28 12:43:34.660   791  1428 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-28 12:43:34.660   791  1428 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-28 12:43:34.660   791  1428 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-28 12:43:34.660   791  1428 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-28 12:43:34.660   791  1428 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
07-28 12:43:34.660   791  1428 D SettingsProvider: name = wifi_on
07-28 12:43:34.670  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:34.670  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3e8d0b4f added. We now have 3 listener(s)
07-28 12:43:34.670  7441  7508 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:43:34.670  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:43:34.670  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@299a12dc added. We now have 4 listener(s)
07-28 12:43:34.670  7441  7508 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:43:34.670  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:34.670  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1a813fe5 added. We now have 5 listener(s)
07-28 12:43:34.670  7441  7508 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:43:34.670  7441  7508 I WifiManager: packageName : com.test.thalitest
,07-28 12:43:34.670   791   831 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-28 12:43:34.670   791   831 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-28 12:43:34.670   791   831 D SecContentProvider2: mCursor = null
,07-28 12:43:34.670   791   831 D WifiService: setWifiEnabled: false pid=7441, uid=10079
,07-28 12:43:34.670   791   831 D SettingsProvider: name = wifi_on
,07-28 12:43:34.680  7441  7508 D BluetoothAdapter: disable()
,07-28 12:43:34.680   791  1428 D SettingsProvider: name = bluetooth_on
,07-28 12:43:34.680   791  1149 E WifiStateMachine: WifiStateMachine: Leaving Connected state
,07-28 12:43:34.680  1281  1281 I wpa_supplicant: reset timer : RESET_TIMER 0
07-28 12:43:34.680  1281  1281 I wpa_supplicant: wlan0: Setting scan request: 0 sec 0 usec
07-28 12:43:34.680  1281  1281 I wpa_supplicant: P2P: Current p2p state = IDLE
07-28 12:43:34.680   791  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:43:34.680  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:43:34.680   791  1679 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:34.690  3222  3282 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,07-28 12:43:34.690  3222  3282 D BluetoothAdapterProperties: Setting state to 13
07-28 12:43:34.690  3222  3282 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
07-28 12:43:34.690  3222  3282 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-28 12:43:34.690  3222  3282 D BluetoothAdapterService: updateAdapterState state is 13
,07-28 12:43:34.690   791  1469 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:43:34.690   791  1469 D ActivityManager: caller:android.app.ApplicationThreadProxy@26a2ed45, r.packageName :com.android.bluetooth
07-28 12:43:34.690  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:34.690  7441  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:34.690  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:34.690  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:34.690  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:34.690  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:34.690  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:34.690  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:43:34.690  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,07-28 12:43:34.690  3222  3222 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
07-28 12:43:34.690  3222  3282 D BluetoothAdapterService: Autoconnection is available 
07-28 12:43:34.690  3222  3222 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2a2a7dc, channel: 19, state: LISTENING
,07-28 12:43:34.690  3222  3222 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2a2a7dc, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@27471444, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1e8eb0e5mSocket: android.net.LocalSocket@32c547ba impl:android.net.LocalSocketImpl@2db6666b fd:FileDescriptor[72]
07-28 12:43:34.690  3222  3282 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
07-28 12:43:34.690  3222  3282 D BluetoothAdapterService: terminating service from this receiver
07-28 12:43:34.690  3222  3222 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@32c547ba impl:android.net.LocalSocketImpl@2db6666b fd:FileDescriptor[72]
,07-28 12:43:34.690  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:43:34.690  7441  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:34.690  3222  3282 D BluetoothAdapterProperties: onBluetoothDisable()
07-28 12:43:34.690  7441  7508 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:43:34.690  1281  1281 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-28 12:43:34.690   791  1428 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
07-28 12:43:34.690   791  1366 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:34.690  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:34.690   791  1469 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:34.690   791   791 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:34.690   791   791 I InputMethodManagerService: [BT Setting State] State =13
07-28 12:43:34.690  3222  3282 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-28 12:43:34.690  3222  3367 D bt_vendor: op for 7
07-28 12:43:34.690  3222  3367 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:34.690  3222  3367 D bt_vendor: op for 7
,07-28 12:43:34.690  3222  3367 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:34.700  3222  3367 D bt_vendor: op for 7
07-28 12:43:34.700  3222  3367 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:34.700  3222  3286 D BluetoothAdapterProperties: Scan Mode:20
,07-28 12:43:34.700  3222  3282 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
07-28 12:43:34.700  3222  3282 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
07-28 12:43:34.700  3222  3282 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
07-28 12:43:34.700  1193  1193 D BluetoothTile:  onBluetoothStateChange:
,07-28 12:43:34.700  1865  1865 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
07-28 12:43:34.700  3222  3282 E bt-btif : cmd socket is not created
07-28 12:43:34.700  3222  5782 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:43:34.700  3222  3365 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
07-28 12:43:34.700  3222  3367 D bt_vendor: op for 7
07-28 12:43:34.700  3222  3367 D bt_upio : BT_WAKE is asserted already
07-28 12:43:34.700  7441  7553 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2c390d6b, channel: -1, state: INIT
07-28 12:43:34.700  7441  7553 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2c390d6b, channel: -1, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@22380c8, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1d0af561mSocket: android.net.LocalSocket@1e743886 impl:android.net.LocalSocketImpl@1e591547 fd:FileDescriptor[109]
07-28 12:43:34.700  3222  3365 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-28 12:43:34.700  7441  7553 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@1e743886 impl:android.net.LocalSocketImpl@1e591547 fd:FileDescriptor[109]
07-28 12:43:34.700  7441  7553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 1297)
07-28 12:43:34.700  3222  3365 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:43:34.700  3222  3365 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:43:34.700  3222  3365 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:43:34.700  3222  3367 D bt_vendor: op for 7
07-28 12:43:34.700  3222  3367 D bt_upio : BT_WAKE is asserted already
07-28 12:43:34.700   791  1428 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-28 12:43:34.700   791  1428 D ActivityManager: caller:android.app.ApplicationThreadProxy@20083c9a, r.packageName :com.google.android.gms
,07-28 12:43:34.710  3222  3367 D bt_vendor: op for 7
07-28 12:43:34.710  3222  3367 D bt_upio : BT_WAKE is asserted already
07-28 12:43:34.710  1193  1193 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-28 12:43:34.710  1193  1193 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:34.710  3222  3367 D bt_vendor: op for 7
07-28 12:43:34.710  3222  3367 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:34.710  1193  1595 D BluetoothTile:  handleUpdatestate:false name:null
07-28 12:43:34.710  1313  1313 D BluetoothPbap: Proxy object disconnected
,07-28 12:43:34.710  1313  1313 D PbapServerProfile: Bluetooth service disconnected
07-28 12:43:34.710  1313  1313 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:34.710  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:34.710  3222  3367 D bt_vendor: op for 7
07-28 12:43:34.710  3222  3367 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:34.710   791  1366 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:34.710  3222  3367 D bt_vendor: op for 7
07-28 12:43:34.710  3222  3367 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:34.710  3222  3282 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-28 12:43:34.710  3222  3367 D bt_vendor: op for 7
07-28 12:43:34.710  3222  3367 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:34.710  3222  3367 D bt_vendor: op for 7
07-28 12:43:34.710  3222  3367 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:34.720  3222  3367 D bt_vendor: op for 7
07-28 12:43:34.720  3222  3367 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:34.720   791  1149 E native  : do suspend true
07-28 12:43:34.720  1313  1313 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 12:43:34.720  3222  3367 D bt_vendor: op for 7
07-28 12:43:34.720  3222  3367 D bt_upio : BT_WAKE is asserted already
07-28 12:43:34.720   791  1574 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,07-28 12:43:34.720   791  1574 D ActivityManager: caller:android.app.ApplicationThreadProxy@392595a8, r.packageName :com.android.settings
07-28 12:43:34.720  1193  1595 D BluetoothTile:  handleUpdatestate:false name:null
07-28 12:43:34.720   791  1638 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:43:34.720  3222  3367 D bt_vendor: op for 7
07-28 12:43:34.720  3222  3367 D bt_upio : BT_WAKE is asserted already
07-28 12:43:34.720  3222  3222 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@32fe7661, channel: 5, state: LISTENING
07-28 12:43:34.720  3222  3222 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@32fe7661, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1208892d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2e702586mSocket: android.net.LocalSocket@3cd2fe47 impl:android.net.LocalSocketImpl@213a1674 fd:FileDescriptor[74]
07-28 12:43:34.720  3222  3222 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3cd2fe47 impl:android.net.LocalSocketImpl@213a1674 fd:FileDescriptor[74]
,07-28 12:43:34.720  3222  3222 I BtOppRfcommListener: stopping Accept Thread
07-28 12:43:34.720  3222  3222 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2a4b179d, channel: 12, state: LISTENING
07-28 12:43:34.720  3222  3222 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2a4b179d, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2cb6d44f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3991412mSocket: android.net.LocalSocket@43737e3 impl:android.net.LocalSocketImpl@3b1c25e0 fd:FileDescriptor[78]
07-28 12:43:34.720  3222  3222 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@43737e3 impl:android.net.LocalSocketImpl@3b1c25e0 fd:FileDescriptor[78]
,07-28 12:43:34.720  3222  3367 D bt_vendor: op for 7
07-28 12:43:34.720  3222  3367 D bt_upio : BT_WAKE is asserted already
07-28 12:43:34.720  3222  5782 I BtOppRfcommListener: BluetoothSocket listen thread finished
,07-28 12:43:34.720   791  1428 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-28 12:43:34.720  7441  7441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:34.720  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:34.720  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:34.720  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:34.720  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:34.720  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:34.720  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
07-28 12:43:34.720  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
07-28 12:43:34.720  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
07-28 12:43:34.720  1193  1595 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-28 12:43:34.720  1193  1193 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-28 12:43:34.720  7441  7441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:34.720  7441  7441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,07-28 12:43:34.720   791  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:34.730   791  1148 D WifiP2pService: InactiveState{ what=143375 }
07-28 12:43:34.730   791  1148 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-28 12:43:34.730  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:34.730   791  1428 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:34.730  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:34.730   791  1469 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:34.730  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:34.730   299  1061 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:43:34.740  1313  1313 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:43:34.750  1193  1193 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:43:34.750  1897  5175 V NativeCrypto: Read error: ssl=0xafa75e00: I/O error during system call, Connection timed out
07-28 12:43:34.750  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-28 12:43:34.750   791   832 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:34.750  1897  5175 V NativeCrypto: SSL shutdown failed: ssl=0xafa75e00: I/O error during system call, Broken pipe
,07-28 12:43:34.750   791  1428 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:34.760  1897  5175 E GCM     : Wifi connection closed with errorCode 20
,07-28 12:43:34.760   791   831 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:34.760   791  1638 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 502]) by 10015
,07-28 12:43:34.760   791   832 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:34.760   791  1738 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:34.760   791  1738 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532488 arg1=10015 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:34.760   791  1738 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Forcing reevaluation
07-28 12:43:34.760   791  1738 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:34.760   791  1738 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,07-28 12:43:34.770   791  1738 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
,07-28 12:43:34.770   791  1738 I qtaguid : Tagging socket 346 with tag ffffffff00000000{4294967295,0} uid 10015, pid: 791, getuid(): 1000
,07-28 12:43:34.770   791  1532 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:34.770   791  1657 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:34.770   791  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:43:34.770   791  1151 E ConnectivityService: updateNetworkInfo()
,07-28 12:43:34.770   791  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:43:34.770   791  1151 E ConnectivityService: updateNetworkInfo()
07-28 12:43:34.770   791  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
,07-28 12:43:34.770   791  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 502] got DISCONNECTED, was satisfying 3
07-28 12:43:34.770   791   791 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-28 12:43:34.770  1193  1193 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:43:34.770  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-28 12:43:34.770  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:34.770  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:34.770  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:34.770  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:34.770  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:34.770  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:34.770  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:34.770  1193  1193 D StatusBar.NetworkController: applyOpen
,07-28 12:43:34.780   791  1148 D WifiP2pService: InactiveState{ what=131204 }
07-28 12:43:34.790   791   791 D WifiScanningService: SCAN_AVAILABLE : 1
07-28 12:43:34.780   791  1148 D WifiP2pService: P2pEnabledState{ what=131204 }
07-28 12:43:34.790   791   791 D RttService: SCAN_AVAILABLE : 1
07-28 12:43:34.790   791  1167 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:34.790   791  1166 D WifiScanningService: DefaultState got{ when=-1ms what=160007 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:34.790   791  1149 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-28 12:43:34.790   791  1148 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,07-28 12:43:34.790   791  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:34.790   791  1046 D WifiDisplayAdapter: onP2pDisconnected
07-28 12:43:34.790   791  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
,07-28 12:43:34.790   791  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-28 12:43:34.800   791   791 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,07-28 12:43:34.800   791  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
07-28 12:43:34.800   791  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-28 12:43:34.800   791  1738 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-28 12:43:34.800   791  1046 D WifiDisplayController: disconnect
07-28 12:43:34.800   791  1046 D WifiDisplayController: updateConnection
,07-28 12:43:34.800   791  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-28 12:43:34.800   791  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-28 12:43:34.800  1193  1193 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,07-28 12:43:34.800   791  1468 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-28 12:43:34.800  1193  1193 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-28 12:43:34.800   791  1148 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-28 12:43:34.800   791  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-28 12:43:34.800   791  1046 D WifiDisplayAdapter: onP2pDisconnected
07-28 12:43:34.800   791  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-28 12:43:34.800   791  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
,07-28 12:43:34.800   791  1148 D WifiP2pService: P2pDisablingState
07-28 12:43:34.800   791  1148 D WifiP2pService: P2pDisablingState{ what=147458 }
07-28 12:43:34.800   791  1148 D WifiP2pService: p2p socket connection lost
07-28 12:43:34.800   791  1148 D WifiP2pService: P2pDisabledState
,07-28 12:43:34.810   791  1149 E native  : do suspend true
,07-28 12:43:34.810  1313  1313 D BluetoothNotiBroadcastReceiver: onReceive
,07-28 12:43:34.810   791  1259 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.maps, hostingType: broadcast
,07-28 12:43:34.810   791  1259 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:34.810   791  1259 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:34.810   791  1259 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:34.810   791  1259 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:34.810   791  1148 D WifiP2pService: P2pDisabledState{ what=143375 }
07-28 12:43:34.810   791  1148 D WifiP2pService: DefaultState{ what=143375 }
,07-28 12:43:34.870  7577  7577 E Zygote  : MountEmulatedStorage()
07-28 12:43:34.870  7577  7577 E Zygote  : v2
07-28 12:43:34.870  7577  7577 I libpersona: KNOX_SDCARD checking this for 10140
07-28 12:43:34.870  7577  7577 I libpersona: KNOX_SDCARD not a persona
,07-28 12:43:34.870   791  1259 I ActivityManager: Start proc com.google.android.apps.maps for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver: pid=7577 uid=10140 gids={50140, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,07-28 12:43:34.870   791  1151 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 502]
07-28 12:43:34.870   791  1151 D ConnectivityService: calling update connectivity
07-28 12:43:34.870   791  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:34.870   791  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:34.870   791  1151 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:34.880   791  1738 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
07-28 12:43:34.880   791  1738 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
07-28 12:43:34.880   791  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:34.880   791  1151 D ConnectivityService: sending notification LOST for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:34.880   791  1043 D EntConnectivity: Not allowed due to - mEnabled false
07-28 12:43:34.880   791  1151 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
07-28 12:43:34.880   791  1151 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:34.880   791  1151 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:34.880   791  1738 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:34.880   791  1738 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:34.880   791  1738 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
,07-28 12:43:34.880   791  1151 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
07-28 12:43:34.880   791  1151 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 502] isDefaultNetwork=false
,07-28 12:43:34.880   791  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,07-28 12:43:34.880   299  1061 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:43:34.880   791  1152 D Tethering: MasterInitialState.processMessage what=3
07-28 12:43:34.880   791   791 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
07-28 12:43:34.880   791  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-28 12:43:34.880   791  1153 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:43:34.880   791  1153 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:43:34.880   791  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:43:34.880   791  1153 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:43:34.880   791  1146 V NetworkStats: updateIfacesLocked()
07-28 12:43:34.880   791  1146 V NetworkStats: performPollLocked(flags=0x1)
07-28 12:43:34.880   791  1151 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:43:34.880   791  1151 E ConnectivityService: updateNetworkInfo()
07-28 12:43:34.880   791  1151 E ConnectivityService: updateNetworkInfo()
07-28 12:43:34.880   791  1151 D ConnectivityService: NetworkAgentInfo [WIFI_P2P () - 501] EVENT_NETWORK_INFO_CHANGED, going from UNKNOWN to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: WIFI_P2P&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
07-28 12:43:34.880   791  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
07-28 12:43:34.880   791  1146 D NetworkStatsFactory: UpdateStatsForKnox
07-28 12:43:34.880   791  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:34.880   791  1151 E ConnectivityService: EVENT_NETWORK_VALIDATED - isLiveNetworkAgent found mismatched netId: null - NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{502}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} }
,07-28 12:43:34.880   791   791 I WifiTrafficPoller: evaluateTrafficStatsPolling,
,07-28 12:43:34.880  1281  1281 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,07-28 12:43:34.890   791  1146 V NetworkStats: performPollLocked() took 6ms,
07-28 12:43:34.890   791  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:43:34.890   791   791 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:43:34.890   791  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled,
07-28 12:43:34.890   791  1149 D SecContentProvider2: mCursor = null
,07-28 12:43:34.900  3222  3365 W bt-l2cap: btif_mce_execute_service enable:0,
07-28 12:43:34.900  3222  3365 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:43:34.900  3222  3365 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:43:34.900  3222  3365 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:43:34.900  3222  3365 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:43:34.900  3222  3367 D bt_vendor: op for 6
07-28 12:43:34.900  3222  3365 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,07-28 12:43:34.900  3222  3365 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:43:34.900  3222  3365 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:43:34.900  3222  3369 D bt_userial: RX termination
07-28 12:43:34.900  3222  3369 W bt_userial: select_read return size <=0:-1, exiting userial_read_thread
07-28 12:43:34.900  3222  3369 D bt_userial: Leaving userial_read_thread()
07-28 12:43:34.900  3222  3367 D bt_vendor: op for 7
07-28 12:43:34.900  3222  3367 D bt_upio : BT_WAKE is asserted already
07-28 12:43:34.900  3222  3286 D bt_userial: userial_close_reader Joined userial reader thread: 0
,07-28 12:43:34.900  3222  3365 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:43:34.900  3222  3365 W bt-btif : ag scb idx 1 not allocated
07-28 12:43:34.900  3222  3365 W bt-btif : ag scb idx 2 not allocated
07-28 12:43:34.900  3222  3365 E bt-btif : BTA AG is already disabled, ignoring ...
07-28 12:43:34.900  3222  3367 D bt_vendor: op for 9
07-28 12:43:34.900  3222  3367 D bt_hwcfg: hw_epilog_process
07-28 12:43:34.900  3222  3286 D bt_vendor: op for 4
07-28 12:43:34.900  3222  3286 I bt_userial_vendor: device fd = 65 close
,07-28 12:43:34.910  7577  7577 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:43:34.910  7577  7577 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:43:34.910  1426  1426 D TelephonyNetworkFactory: Cellular needs Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:34.910  1193  1581 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
,07-28 12:43:34.910  3222  3286 D bt_vendor: op for 0
07-28 12:43:34.910  3222  3286 D bt_upio : upio_set_bluetooth_power(on: 0)
07-28 12:43:34.910  3222  3286 D bt_upio : is_emulator_context : 0
07-28 12:43:34.910  3222  3286 D bt_upio : is_rfkill_disabled ? [0]
07-28 12:43:34.910  1193  1193 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:43:34.910  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-28 12:43:34.910  7577  7577 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-28 12:43:34.910  3222  3286 D bt_vendor: cleanup
,07-28 12:43:34.910   791  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
07-28 12:43:34.910  3222  3365 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-28 12:43:34.910  1193  1193 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-28 12:43:34.910  3222  3286 I GKI_LINUX: GKI_exit_task 0 done
07-28 12:43:34.910  3222  3286 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
,07-28 12:43:34.910  1193  1193 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-28 12:43:34.910  3222  3282 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
07-28 12:43:34.910  3222  3282 D BtConfig.SecureMode: isSecureModeOn:false
07-28 12:43:34.910  1193  1193 D StatusBar.NetworkController: updateDataNetType()
07-28 12:43:34.910  3222  3282 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
07-28 12:43:34.910  3222  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
07-28 12:43:34.910  3222  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-28 12:43:34.910  1193  1193 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
07-28 12:43:34.910  1193  1193 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,07-28 12:43:34.910  4536  7290 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
07-28 12:43:34.910   791  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:43:34.910   791  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:43:34.910   791  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:43:34.910  3222  3282 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
07-28 12:43:34.910  1313  1313 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:43:34.910   791  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:43:34.910   791  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:43:34.910   791  1443 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:43:34.910   791  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:43:34.910   791  1147 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
07-28 12:43:34.910   791  1443 D ActivityManager: caller:android.app.ApplicationThreadProxy@145e7ffd, r.packageName :com.android.bluetooth
,07-28 12:43:34.910  3222  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
07-28 12:43:34.910  3222  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-28 12:43:34.910  3222  3222 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 12:43:34.910  3222  3282 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,07-28 12:43:34.920   791  1574 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:43:34.920   791  1574 D ActivityManager: caller:android.app.ApplicationThreadProxy@31e9c4f2, r.packageName :com.android.bluetooth
,07-28 12:43:34.920  3222  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
07-28 12:43:34.920  3222  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-28 12:43:34.920  3222  3282 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,07-28 12:43:34.920   791  1366 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:43:34.920   791  1366 D ActivityManager: caller:android.app.ApplicationThreadProxy@3fb6c743, r.packageName :com.android.bluetooth
07-28 12:43:34.920  3222  3222 D BtGatt.GattService: Received stop request...Stopping profile...
07-28 12:43:34.920  3222  3222 D BtGatt.GattService: stop()
07-28 12:43:34.920  3222  3222 D BtGatt.AdvertiseManager: advertise clients cleared
07-28 12:43:34.920  3222  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
07-28 12:43:34.920  3222  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-28 12:43:34.920  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@159910fa
,07-28 12:43:34.920  3222  3222 D HeadsetService: Received stop request...Stopping profile...
07-28 12:43:34.920  1193  1193 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-28 12:43:34.920  1193  1193 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,07-28 12:43:34.920  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@159910fa
07-28 12:43:34.920   791  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-28 12:43:34.920   791   791 D AudioService: onServiceDisconnected: Bluetooth profile: 1
,07-28 12:43:34.920  1193  1193 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,07-28 12:43:34.920  7441  7441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:34.920  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:34.920  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:34.920  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:34.920  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:43:34.920  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:34.920  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:34.920  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:34.920  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:43:34.920  3222  3282 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-28 12:43:34.920   791  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:43:34.920   791  1476 D ActivityManager: caller:android.app.ApplicationThreadProxy@325b71c0, r.packageName :com.android.bluetooth
07-28 12:43:34.920  1193  1193 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:43:34.920  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-28 12:43:34.920  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:34.920  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:34.920  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:34.920  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:34.920  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:34.920  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:34.930  3222  3222 D A2dpService: Received stop request...Stopping profile...
,07-28 12:43:34.930  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:34.930  3222  3222 V Avrcp   : doQuit
07-28 12:43:34.930  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:34.930  3222  3295 D A2dpStateMachine: Exit Disconnected: -1
07-28 12:43:34.930  3222  3222 D Avrcp   : Unregistering previous receiver
07-28 12:43:34.930  7441  7441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:34.930  7441  7441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:43:34.930  1193  1193 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:43:34.930  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:43:34.930  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@159910fa
,07-28 12:43:34.930   791   791 D BluetoothA2dp: Proxy object disconnected
07-28 12:43:34.930   791   791 D AudioService: onServiceDisconnected: Bluetooth profile: 2
,07-28 12:43:34.930  1313  1313 D HeadsetProfile: Bluetooth service disconnected
07-28 12:43:34.930  3222  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
07-28 12:43:34.930  1313  1313 D BluetoothA2dp: Proxy object disconnected
07-28 12:43:34.930  3222  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-28 12:43:34.930  1313  1313 D A2dpProfile: Bluetooth service disconnected
,07-28 12:43:34.930  1193  1193 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:43:34.930  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-28 12:43:34.930  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:34.930  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:34.930  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:34.930  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:34.930  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:34.930  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:34.930  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:34.930  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:34.930  1193  1193 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:34.930  1193  1193 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,07-28 12:43:34.930  1193  1595 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-28 12:43:34.930  1193  1193 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:43:34.930  7441  7441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:34.930  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:34.930  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:34.930  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:34.930  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:43:34.930  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:34.930  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:34.930  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:34.930  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:43:34.930  3222  3282 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,07-28 12:43:34.930   791  1476 I AudioService: getStreamVolume 3 index 0
,07-28 12:43:34.930  7441  7441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:43:34.930  7441  7441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:43:34.930   791  1469 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:43:34.930   791  1469 D ActivityManager: caller:android.app.ApplicationThreadProxy@8181ef9, r.packageName :com.android.bluetooth
,07-28 12:43:34.930  1193  1193 D HotspotTile: onReceive : 0, 0
07-28 12:43:34.930  3222  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
07-28 12:43:34.930  3222  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-28 12:43:34.940  3222  3282 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-28 12:43:34.940   791   832 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:43:34.940   791   832 D ActivityManager: caller:android.app.ApplicationThreadProxy@394b3e3e, r.packageName :com.android.bluetooth
,07-28 12:43:34.940  3222  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
07-28 12:43:34.940  3222  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-28 12:43:34.940  3400  3400 D BluetoothA2dp: Proxy object disconnected
,07-28 12:43:34.940  3222  3282 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,07-28 12:43:34.940   791  1428 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:43:34.940   791  1428 D ActivityManager: caller:android.app.ApplicationThreadProxy@33f4949f, r.packageName :com.android.bluetooth
,07-28 12:43:34.940  3222  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
07-28 12:43:34.940  3222  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,07-28 12:43:34.940  3222  3282 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,07-28 12:43:34.940   791  1532 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:43:34.940   791  1532 D ActivityManager: caller:android.app.ApplicationThreadProxy@3665e9ec, r.packageName :com.android.bluetooth
,07-28 12:43:34.940  3222  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:43:34.940  3222  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:43:34.940  3222  3282 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:43:34.940  3222  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:43:34.940  3222  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,07-28 12:43:34.950  3222  3282 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:43:34.950  3222  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
07-28 12:43:34.950  3222  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,07-28 12:43:34.950  3222  3282 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-28 12:43:34.950  3222  3282 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
07-28 12:43:34.950  3222  3282 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-28 12:43:34.950  3222  3282 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
07-28 12:43:34.950  3222  3222 E BluetoothAdapterService(362352890): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
07-28 12:43:34.950  3222  3282 D BluetoothAdapterState: Stopping profile services that were post enabled
07-28 12:43:34.950  3222  3222 E BluetoothAdapterService(362352890): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,07-28 12:43:34.950  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-28 12:43:34.950  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
,07-28 12:43:34.950  3222  3222 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-28 12:43:34.950  3222  3222 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,07-28 12:43:34.950  3222  3222 D HidService: Received stop request...Stopping profile...
07-28 12:43:34.950  3222  3222 D HidService: Stopping Bluetooth HidService
07-28 12:43:34.950  3222  3222 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-28 12:43:34.950  3222  3222 W bt-btif : cleanup: HH disabling or disabled already, status = 0
07-28 12:43:34.950  3222  3222 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-28 12:43:34.950  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@159910fa
,07-28 12:43:34.950  1313  1313 D BluetoothInputDevice: Proxy object disconnected
07-28 12:43:34.950  1313  1313 D HidProfile: Bluetooth service disconnected
,07-28 12:43:34.950  3222  3222 E BluetoothAdapterService(362352890): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
07-28 12:43:34.950  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-28 12:43:34.950  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
07-28 12:43:34.950  3222  3222 D BluetoothA2dp: Proxy object disconnected
07-28 12:43:34.950  3222  3222 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
07-28 12:43:34.950  3222  3296 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-28 12:43:34.950  3222  3222 I GKI_LINUX: GKI_exit_task 2 done
07-28 12:43:34.950  3222  3222 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-28 12:43:34.950  3222  3222 V Avrcp   : cleanup
07-28 12:43:34.950  3222  3222 D HealthService: Received stop request...Stopping profile...
,07-28 12:43:34.950  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@159910fa
,07-28 12:43:34.950  3222  3222 D PanService: Received stop request...Stopping profile...
07-28 12:43:34.950  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@159910fa
,07-28 12:43:34.960   791   791 D BluetoothPan: BluetoothPAN Proxy object disconnected
,07-28 12:43:34.960  3222  3222 D BluetoothMapService: Received stop request...Stopping profile...
07-28 12:43:34.960  7577  7577 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:43:34.960  7577  7577 D ActivityThread: Added TimaKeyStore provider
07-28 12:43:34.960  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@159910fa
,07-28 12:43:34.960  3222  3222 D SapService: Received stop request...Stopping profile...
07-28 12:43:34.960  3222  3222 D SapService: Stopping Bluetooth SapService
07-28 12:43:34.960  3222  3222 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@159910fa
,07-28 12:43:34.960  1313  1313 D BluetoothPan: BluetoothPAN Proxy object disconnected
,07-28 12:43:34.960  3222  3222 E BluetoothAdapterService(362352890): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
07-28 12:43:34.960  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:43:34.960  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-28 12:43:34.960  3222  3222 E BluetoothAdapterService(362352890): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
07-28 12:43:34.960  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:43:34.960  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-28 12:43:34.960  3222  3222 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-28 12:43:34.960  3222  3222 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,07-28 12:43:34.960  3222  3222 E BluetoothAdapterService(362352890): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
07-28 12:43:34.960  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:43:34.960  3222  3222 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-28 12:43:34.960  3222  3222 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-28 12:43:34.960  3222  3222 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
07-28 12:43:34.960  3222  3222 E BluetoothAdapterService(362352890): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
07-28 12:43:34.960  3222  3222 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-28 12:43:34.960  3222  3222 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
,07-28 12:43:34.960  1313  1313 D PanProfile: Bluetooth service disconnected
07-28 12:43:34.960  1313  1313 D BluetoothMap: Proxy object disconnected
07-28 12:43:34.960  1313  1313 D MapProfile: Bluetooth service disconnected
07-28 12:43:34.960  3222  3222 E BluetoothAdapterService(362352890): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
07-28 12:43:34.960  1281  1281 I wpa_supplicant: Blacklist: Clear (all) 
07-28 12:43:34.960  3222  3222 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
07-28 12:43:34.960  3222  3282 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
07-28 12:43:34.960  3222  3222 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
07-28 12:43:34.960  3222  3282 D BluetoothAdapterProperties: Setting state to 10
07-28 12:43:34.960  3222  3282 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-28 12:43:34.960  3222  3282 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-28 12:43:34.960  3222  3282 D BluetoothAdapterService: updateAdapterState state is 10
07-28 12:43:34.960  1313  1313 D Bluetoothsap: BluetoothSAP Proxy object disconnected
07-28 12:43:34.960  1313  1313 D SapProfile: Bluetooth service disconnected
,07-28 12:43:34.960  3222  3282 D BluetoothAdapterService: Autoconnection is available 
07-28 12:43:34.960  3222  3282 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
07-28 12:43:34.960  3222  3282 I BluetoothAdapterState: Entering OffState
,07-28 12:43:34.970  3222  3234 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-28 12:43:34.970  1313  1329 D Bluetoothsap: onBluetoothStateChange: up=false
07-28 12:43:34.970  1313  1329 D Bluetoothsap: Unbinding service...
,07-28 12:43:34.970  1313  1327 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-28 12:43:34.970   791  1043 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-28 12:43:34.980  1281  1281 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
,07-28 12:43:34.980  1281  1281 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
,07-28 12:43:34.980  1281  1281 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
07-28 12:43:34.980  1281  1281 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=0 BSSID=F4.99.3E SSID=4E47373030
07-28 12:43:34.980  1281  1281 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-28 12:43:34.980  7577  7577 D ResourcesManager: creating new AssetManager and set to /system/app/Maps/Maps.apk
,07-28 12:43:34.980  1313  1329 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-28 12:43:34.990  1313  1327 D BluetoothMap: onBluetoothStateChange: up=false
,07-28 12:43:34.990  3400  3410 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-28 12:43:34.990  1313  5812 D BluetoothPbap: onBluetoothStateChange: up=false
,07-28 12:43:34.990   791  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 12 receivers.
,07-28 12:43:35.000   791  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,07-28 12:43:35.000  1426  1426 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:43:35.000  1426  1426 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:43:35.000   791   791 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:35.000   791   791 I InputMethodManagerService: [BT Setting State] State =10
07-28 12:43:35.010   791   791 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-28 12:43:35.010  1193  1193 D BluetoothAdapter: 913822534: getState() :  mService = null. Returning STATE_OFF
07-28 12:43:35.010  1193  1193 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-28 12:43:35.010  1193  1595 D BluetoothAdapter: 913822534: getState() :  mService = null. Returning STATE_OFF
07-28 12:43:35.010  1193  1193 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:35.010  1193  1595 D BluetoothAdapter: 913822534: getState() :  mService = null. Returning STATE_OFF
07-28 12:43:35.010  1193  1595 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-28 12:43:35.010  1426  1426 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
07-28 12:43:35.010  1193  1193 D BluetoothAdapter: 913822534: getState() :  mService = null. Returning STATE_OFF
07-28 12:43:35.010  1193  1193 D BluetoothAdapter: 913822534: getState() :  mService = null. Returning STATE_OFF
,07-28 12:43:35.010  1865  1865 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-28 12:43:35.010  1313  1313 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:35.010   791  1144 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-28 12:43:35.010   791  1144 D ActivityManager: caller:android.app.ApplicationThreadProxy@f32b1b5, r.packageName :com.google.android.gms
,07-28 12:43:35.010  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:35.010   791  1259 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:43:35.010  1897  2422 D BluetoothAdapter: 964148488: getState() :  mService = null. Returning STATE_OFF
07-28 12:43:35.010   791  1657 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
07-28 12:43:35.010  1897  2422 D BluetoothAdapter: 964148488: getState() :  mService = null. Returning STATE_OFF
07-28 12:43:35.010  1426  1426 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:43:35.010  1193  1193 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
07-28 12:43:35.010  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:35.020  1426  1426 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:43:35.020  3222  3285 E BluetoothAdapterService(362352890): Repeated wake lock release; aborting release: bluedroid_timer
,07-28 12:43:35.020  3222  3286 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
07-28 12:43:35.020  1426  1426 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:43:35.020  3222  3285 E GKI_LINUX: alarm_service_reschedule unable to release wake lock with no timers: 1
07-28 12:43:35.020  3222  3222 I GKI_LINUX: GKI_exit_task 1 done
07-28 12:43:35.020  3222  3222 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,07-28 12:43:35.020  3222  3222 I BluetoothServiceJni: cleanupNative: return from cleanup
,07-28 12:43:35.020  1426  1426 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:43:35.020  1426  1426 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:43:35.020  3222  3222 I art     : System.exit called, status: 0
07-28 12:43:35.020  3222  3222 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,07-28 12:43:35.030  1426  1426 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:43:35.030  1426  1426 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:43:35.030  1281  1281 I wpa_supplicant: Blacklist: Clear (all) 
,07-28 12:43:35.030  1426  1426 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:43:35.030  1426  1426 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:43:35.030  1426  1426 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:43:35.040  1426  1426 D FileWriteThread_Telephony: FileWriteThread : threadType = 3
,07-28 12:43:35.070   791  1366 I ActivityManager: Process com.android.bluetooth (pid 3222)(adj 0) has died(187,1564)
,07-28 12:43:35.130  7441  7441 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,07-28 12:43:35.160  1281  1281 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
07-28 12:43:35.160   791  1152 D Tethering: InitialState.processMessage what=4
,07-28 12:43:35.160   791  1152 E Tethering: No numeric data
,07-28 12:43:35.160   791  1152 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,07-28 12:43:35.160   791  1146 V NetworkStats: performPollLocked(flags=0x1)
07-28 12:43:35.160   791  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:43:35.160  1193  1193 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-28 12:43:35.160  1193  1193 D HotspotTile: updateTetherState():false, false
,07-28 12:43:35.160   791  1146 D NetworkStatsFactory: UpdateStatsForKnox
,07-28 12:43:35.160   791  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:35.160   791  1146 V NetworkStats: performPollLocked() took 5ms
,07-28 12:43:35.160   791  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:43:35.170   791  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:43:35.170   791  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:43:35.200   791  1574 D ActivityManager: bindService callerProcessName:com.google.android.apps.maps, calleePkgName: com.google.android.gms, action: null
,07-28 12:43:35.200  1897  1897 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-28 12:43:35.200  1897  1897 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,07-28 12:43:35.240  7577  7577 D StrictMode: StrictMode policy violation; ~duration=177 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:189)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.libraries.social.jni.crashreporter.NativeCrashHandler.a(PG:1060)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:82)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,07-28 12:43:35.240  7577  7577 D StrictMode: StrictMode policy violation; ~duration=165 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at libcore.io.IoUtils.canOpenReadOnly(IoUtils.java:165)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at dalvik.system.DexPathList.findLibrary(DexPathList.java:383)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at dalvik.system.BaseDexClassLoader.findLibrary(BaseDexClassLoader.java:77)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.lang.Runtime.loadLibrary(Runtime.java:360)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.lang.System.loadLibrary(System.java:989)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.map.util.jni.NativeHelper.initialize(PG:48)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.<clinit>(PG:92)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:43:35.240  7577  7577 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.io.File.doAccess(File.java:283)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.io.File.exists(File.java:363)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1319)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-28 12:43:35.240  7577  7577 D StrictMod,e: 	at com.google.b.a.ca.a(PG:125)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:43:35.240  7577  7577 D StrictMode: StrictMode policy violation; ~duration=128 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at androi,d.os.Looper.loop(Looper.java:145)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:43:35.240  7577  7577 D StrictMode: StrictMode policy violation; ~duration=127 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:445)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:1320)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:190)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:150)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:43:35.240  7577  7577 D StrictMode: StrictMode policy violation; ~duration=125 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.r.k.c(PG:1187)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.r.k.a(PG:2107)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:23)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.r.v.a(PG:1206)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.r.y.a(PG:2233)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.r.e.b(PG:170)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.r.e.b(PG:13188)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:43:35.240  7577  7577 D StrictMode: StrictMode policy violation; ~duration=124 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:472)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.r.k.c(PG:1187)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.r.k.b(PG:14147)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.r.k.c(PG:583)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.v.a.a.eq.<init>(PG:40)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.v.a.a.eq.a(PG:12397)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.r.v.a(PG:1206)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.r.y.a(PG:2233)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.r.e.b(PG:170)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.r.e.b(PG:13188)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.shared.f.h.a(PG:151)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7682)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:43:35.240  7577  7577 D StrictMode: StrictMode policy violation; ~duration=101 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=31 violation=2
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1137)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.io.File.doAccess(File.java:283)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.io.File.exists(File.java:363)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:1354)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:1377)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:1485)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:206)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.map.l.s.a(PG:7690)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.b.a.ca.a(PG:125)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.map.l.g.a(PG:1530)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:189)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:1211)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:195)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:164)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1020)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:5109)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.access$1600(ActivityThread.java:177)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1509)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:43:35.240  7577  7577 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:43:35.250   791  1638 I ActivityManager: Killing 6529:com.sec.android.widgetapp.activeapplicationwidget/u0a182 (adj 15): emptyCount ##41
07-28 12:43:35.250  1897  1897 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
07-28 12:43:35.260   791  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
07-28 12:43:35.260   791  1149 D WifiNative-HAL: callSECApiBoolean - ID [21]
07-28 12:43:35.260  1897  1897 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
07-28 12:43:35.260   791   791 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:35.260   791  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-28 12:43:35.260  1193  1193 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:43:35.260  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-28 12:43:35.260   791  1366 D ActivityManager: startProcessLocked calleePkgName: com.vlingo.midas, hostingType: broadcast
07-28 12:43:35.260  1193  1193 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:35.260  1193  1193 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
07-28 12:43:35.260  1193  1193 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:35.260  1313  1313 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:35.270   791  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:35.270   791  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:35.270  1193  1595 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-28 12:43:35.270   791  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:35.270   791  1366 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:35.270  1897  2422 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
07-28 12:43:35.270  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:35.270  1193  1193 D HotspotTile: onReceive : 1, 0
07-28 12:43:35.270  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:35.300  7577  7616 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
07-28 12:43:35.300   362   362 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
07-28 12:43:35.310  7624  7624 E Zygote  : MountEmulatedStorage()
07-28 12:43:35.310  7624  7624 E Zygote  : v2
07-28 12:43:35.310  7624  7624 I libpersona: KNOX_SDCARD checking this for 10038
07-28 12:43:35.310  7624  7624 I libpersona: KNOX_SDCARD not a persona
07-28 12:43:35.320  7624  7624 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:43:35.320  7624  7624 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:43:35.320  7624  7624 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
07-28 12:43:35.320   791  1366 I ActivityManager: Start proc com.vlingo.midas for broadcast com.vlingo.midas/com.samsung.myplace.WIFINotificationHandler: pid=7624 uid=10038 gids={50038, 9997, 3003, 1028, 1015, 3002, 3001} abi=armeabi-v7a
,07-28 12:43:35.350  7624  7624 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:43:35.350  7624  7624 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:35.370  7624  7624 D ResourcesManager: creating new AssetManager and set to /system/priv-app/S-Voice_Android_phone/S-Voice_Android_phone.apk
,07-28 12:43:35.370  7624  7624 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,07-28 12:43:35.380  1897  2588 I art     : Explicit concurrent mark sweep GC freed 115274(6MB) AllocSpace objects, 54(2MB) LOS objects, 40% free, 23MB/39MB, paused 721us total 53.035ms
,07-28 12:43:35.380   791  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:43:35.390   791   791 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:35.390   791   791 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:35.390   791   994 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:35.390   791   994 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:35.390   791   791 I ApplicationPolicy: updateDataUsageMap
,07-28 12:43:35.400   791  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-28 12:43:35.400   791  1153 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:43:35.400   791  1153 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:43:35.400   791  1153 D SmartBondingService: getSBEnabled() enabled =false
,07-28 12:43:35.400   791  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-28 12:43:35.400  1487  1487 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,07-28 12:43:35.400   791   831 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:35.400  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:35.400  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:35.400   791  1469 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:35.460   791  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,07-28 12:43:35.510  7624  7624 I VlingoApplication: VlingoApplication appVersion ='11.2.2.0.37791', ro.csc.sales_code=XEO
,07-28 12:43:35.570  7624  7624 D BluetoothAdapter: 1010427724: getState() :  mService = null. Returning STATE_OFF
,07-28 12:43:35.580  7624  7624 D BluetoothAdapter: 1010427724: getState() :  mService = null. Returning STATE_OFF
,07-28 12:43:35.580  7624  7624 D BluetoothAdapter: 1010427724: getState() :  mService = null. Returning STATE_OFF
,07-28 12:43:35.580  7624  7624 D BluetoothAdapter: 1010427724: getState() :  mService = null. Returning STATE_OFF
07-28 12:43:35.580  7624  7624 D BluetoothAdapter: 1010427724: getState() :  mService = null. Returning STATE_OFF
07-28 12:43:35.580  7624  7624 D BluetoothAdapter: 1010427724: getState() :  mService = null. Returning STATE_OFF
,07-28 12:43:35.610  7624  7624 E BluetoothHeadset: BTStateChangeCB is registed
,07-28 12:43:35.610   791  1679 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:43:35.610  7624  7624 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:43:35.610   791  1574 I ActivityManager: Killing 6580:com.google.android.gms:car/u0a15 (adj 15): emptyCount ##41
,07-28 12:43:35.620  1313  1313 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-28 12:43:35.620  1313  1313 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-28 12:43:35.620   791  1259 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:35.620  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-28 12:43:35.620   791  1443 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-28 12:43:35.620  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:43:35.620  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:43:35.620  1313  1313 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:43:35.620  1313  2966 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:43:35.620   791   832 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:35.630  7031  7031 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:43:35.630   791  1476 D SettingsProvider: name = driving_mode_on
,07-28 12:43:35.630   791  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:35.630   791  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:35.630   791  1476 D SettingsProvider: selectionArgs: false
07-28 12:43:35.630   791  1476 D SettingsProvider: selectionArgs: 10038
07-28 12:43:35.630   791  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-28 12:43:35.630   791  1476 D SettingsProvider: ret = -1
,07-28 12:43:35.630  7624  7624 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.media.ACTION_SCO_AUDIO_STATE_UPDATED
,07-28 12:43:35.640   791  1679 D ActivityManager: startProcessLocked calleePkgName: com.google.android.talk, hostingType: broadcast
,07-28 12:43:35.640   791  1679 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:35.640   791  1679 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:35.640   791  1679 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:35.640   791  1679 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:35.680  7647  7647 E Zygote  : MountEmulatedStorage()
07-28 12:43:35.680  7647  7647 E Zygote  : v2
07-28 12:43:35.680  7647  7647 I libpersona: KNOX_SDCARD checking this for 10131
07-28 12:43:35.680  7647  7647 I libpersona: KNOX_SDCARD not a persona
,07-28 12:43:35.690   791  1679 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.service.NetworkStateReceiver: pid=7647 uid=10131 gids={50131, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
07-28 12:43:35.690  7647  7647 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:43:35.690  7647  7647 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:43:35.690  7647  7647 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-28 12:43:35.710  7647  7647 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:43:35.710  7647  7647 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:35.720  7647  7647 D ResourcesManager: creating new AssetManager and set to /system/app/Hangouts/Hangouts.apk
,07-28 12:43:35.730  7647  7647 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,07-28 12:43:35.930  7647  7674 I Babel   : MmsConfig: mnc/mcc: 0/0
,07-28 12:43:35.930  7647  7674 I Babel   : MmsConfig.loadMmsSettings
07-28 12:43:35.930  7647  7674 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
07-28 12:43:35.930  7647  7674 I Babel   : MmsConfig.loadFromDatabase
,07-28 12:43:35.940  7647  7647 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,07-28 12:43:35.950  7647  7674 E Babel   : canonicalizeMccMnc: invalid mccmnc 
07-28 12:43:35.950  7647  7674 I Babel   : MmsConfig.loadFromResources
,07-28 12:43:35.960  7647  7674 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
,07-28 12:43:35.960  7647  7674 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=SAMSUNG-ANDROID-MMS/SM-N9005, mUaProfUrl=http://wap.samsungmobile.com/uaprof/SM-N9005.xml
,07-28 12:43:35.960   791   831 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: null
,07-28 12:43:35.960  7647  7647 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:43:35.990  7647  7647 I Babel_StickerModule: App launched.
,07-28 12:43:35.990  1313  1313 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-28 12:43:35.990  1313  1313 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-28 12:43:35.990   791  1532 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:35.990  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-28 12:43:35.990   791  1358 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-28 12:43:35.990  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:43:35.990  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:43:35.990  1313  1313 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:43:35.990  1313  2966 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:43:36.000  7175  7175 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-28 12:43:36.000   791   832 D ActivityManager: startProcessLocked calleePkgName: com.samsung.shareshot, hostingType: broadcast
,07-28 12:43:36.000   791   832 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:36.000   791   832 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:36.000   791   832 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:36.000   791   832 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:36.030   312  1509 W QCamera2Factory: getCameraInfo: E, camera_id = 0
07-28 12:43:36.030   312  1509 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
07-28 12:43:36.030   312  1509 W QCamera2Factory: getCameraInfo: X
,07-28 12:43:36.030   312   731 W QCamera2Factory: getCameraInfo: E, camera_id = 1
07-28 12:43:36.030   312   731 W QCamera2HWI: __dbg: info->orientation : 90 rc = 0
07-28 12:43:36.030   312   731 W QCamera2HWI: __dbg: info->orientation : 270 rc = 0
07-28 12:43:36.030   312   731 W QCamera2Factory: getCameraInfo: X
,07-28 12:43:36.040  7647  7647 W AudioCapabilities: Unsupported mime audio/evrc
,07-28 12:43:36.040  7676  7676 E Zygote  : MountEmulatedStorage()
07-28 12:43:36.040  7676  7676 E Zygote  : v2
07-28 12:43:36.040  7676  7676 I libpersona: KNOX_SDCARD checking this for 10192
07-28 12:43:36.040  7676  7676 I libpersona: KNOX_SDCARD not a persona
,07-28 12:43:36.040   791   832 I ActivityManager: Start proc com.samsung.shareshot for broadcast com.samsung.shareshot/.WifiDirectBroadcastReceiver: pid=7676 uid=10192 gids={50192, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:43:36.070  7676  7676 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:43:36.070  7676  7676 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:43:36.070  7676  7676 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:43:36.070  7647  7647 W AudioCapabilities: Unsupported mime audio/qcelp
,07-28 12:43:36.070  7647  7647 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,07-28 12:43:36.090  7647  7647 W AudioCapabilities: Unsupported mime audio/mpeg-L1
07-28 12:43:36.090  7647  7647 W AudioCapabilities: Unsupported mime audio/mpeg-L2
,07-28 12:43:36.090  7676  7676 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:43:36.100  7676  7676 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:36.100  7647  7647 W AudioCapabilities: Unsupported mime audio/x-ms-wma
,07-28 12:43:36.100  7647  7647 W AudioCapabilities: Unsupported mime audio/x-ima
,07-28 12:43:36.100  7647  7647 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,07-28 12:43:36.100  7647  7647 W AudioCapabilities: Unsupported mime audio/qcelp
,07-28 12:43:36.100  7647  7647 W AudioCapabilities: Unsupported mime audio/evrc
,07-28 12:43:36.110  7676  7676 D ResourcesManager: creating new AssetManager and set to /system/app/ShareShotService/ShareShotService.apk
,07-28 12:43:36.110  7647  7647 W VideoCapabilities: Unsupported mime video/wvc1
,07-28 12:43:36.110  7647  7647 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-28 12:43:36.120  7647  7647 W VideoCapabilities: Unrecognized profile/level 32768/2 for video/mp4v-es
,07-28 12:43:36.120   304   304 E SMD     : DCD ON
,07-28 12:43:36.120  7647  7647 W VideoCapabilities: Unsupported mime video/wvc1
,07-28 12:43:36.120  7647  7647 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,07-28 12:43:36.120  7647  7647 W VideoCapabilities: Unsupported mime video/x-ms-wmv7
,07-28 12:43:36.120  7647  7647 W VideoCapabilities: Unsupported mime video/x-ms-wmv8
,07-28 12:43:36.120  7647  7647 W VideoCapabilities: Unsupported mime video/mp43
,07-28 12:43:36.130  7676  7676 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-28 12:43:36.130  7647  7647 W VideoCapabilities: Unsupported mime video/sorenson
,07-28 12:43:36.130  7676  7676 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
,07-28 12:43:36.130  7676  7676 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-28 12:43:36.130  7647  7647 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,07-28 12:43:36.140  7676  7676 D WifiDirectBR: stopServiceTest : false
,07-28 12:43:36.140  7676  7676 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-28 12:43:36.140  7647  7647 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,07-28 12:43:36.150   791  1468 I ActivityManager: Killing 6711:com.google.android.partnersetup/u0a19 (adj 15): emptyCount ##41
,07-28 12:43:36.150  1313  1313 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-28 12:43:36.150  1313  1313 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-28 12:43:36.150   791  1638 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:36.150  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-28 12:43:36.150   791  1532 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
,07-28 12:43:36.150  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:43:36.150  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:43:36.150  1313  1313 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:43:36.150  1313  2966 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:43:36.160   791  1358 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:36.160  7031  7031 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:43:36.170  7031  7031 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-28 12:43:36.190   791  1679 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:36.190  7514  7514 D SecurityLogAgent: KnoxConfiguration : Current State = 1
,07-28 12:43:36.190  7514  7514 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
,07-28 12:43:36.190  7514  7514 D SecurityLogAgent: StateMachine : Current State = 1
,07-28 12:43:36.210  7514  7514 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:43:36.210  1313  1313 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 12:43:36.210   791  1366 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-28 12:43:36.210   791  1366 D ActivityManager: caller:android.app.ApplicationThreadProxy@300f9f49, r.packageName :com.android.settings
,07-28 12:43:36.220   791  1638 D ActivityManager: bindService callerProcessName:com.google.android.talk, calleePkgName: com.google.android.talk, action: com.google.android.talk.SOFT_BIND
,07-28 12:43:36.230  1313  1313 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:43:36.230  1313  1313 D BluetoothNotiBroadcastReceiver: onReceive
,07-28 12:43:36.230   791  1679 D ActivityManager: startProcessLocked calleePkgName: com.android.bluetooth, hostingType: broadcast
,07-28 12:43:36.230   791  1679 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:36.230   791  1679 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:36.230   791  1679 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:36.230   791  1679 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:36.270  7696  7696 E Zygote  : MountEmulatedStorage()
07-28 12:43:36.270  7696  7696 E Zygote  : v2
07-28 12:43:36.270  7696  7696 I libpersona: KNOX_SDCARD checking this for 1002
07-28 12:43:36.270  7696  7696 I libpersona: KNOX_SDCARD not a persona
,07-28 12:43:36.270   791  1679 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7696 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
07-28 12:43:36.270  7696  7696 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-28 12:43:36.270  7696  7696 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:43:36.270  7696  7696 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:43:36.280   791  1574 I ActivityManager: Killing 6729:com.samsung.groupcast/u0a20 (adj 15): emptyCount ##41
,07-28 12:43:36.310  7696  7696 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:43:36.310  7696  7696 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:36.320  7696  7696 D ResourcesManager: creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,07-28 12:43:36.320  7696  7696 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,07-28 12:43:36.320  7696  7696 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-28 12:43:36.350  7696  7696 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,07-28 12:43:36.370  7696  7696 D BtSettings.ProfileConfig: Adding GattService
,07-28 12:43:36.370  7696  7696 D BtSettings.ProfileConfig: Adding HeadsetService
07-28 12:43:36.370  7696  7696 D BtSettings.ProfileConfig: Adding A2dpService
,07-28 12:43:36.370  7696  7696 D BtSettings.ProfileConfig: Adding HidService
07-28 12:43:36.370  7696  7696 D BtSettings.ProfileConfig: Adding HealthService
07-28 12:43:36.370  7696  7696 D BtSettings.ProfileConfig: Adding PanService
07-28 12:43:36.370  7696  7696 D BtSettings.ProfileConfig: Adding BluetoothMapService
,07-28 12:43:36.370  7696  7696 D BtSettings.ProfileConfig: Adding SapService
07-28 12:43:36.370  7696  7696 D BtSettings.ProfileConfig: Adding HeadsetClientService
07-28 12:43:36.370  7696  7696 D BtSettings.ProfileConfig: Adding A2dpSinkService
,07-28 12:43:36.370  7696  7696 D BtSettings.ProfileConfig: Adding SapClientService
07-28 12:43:36.370  7696  7696 D BtSettings.ProfileConfig: Adding HidDevService
07-28 12:43:36.370  7696  7696 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,07-28 12:43:36.380   791  1657 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
,07-28 12:43:36.380   791  1657 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:36.380   791  1657 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:36.380   791  1657 D SettingsProvider: selectionArgs: false
07-28 12:43:36.380   791  1657 D SettingsProvider: selectionArgs: 1002
07-28 12:43:36.380   791  1657 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-28 12:43:36.380   791  1657 D SettingsProvider: ret = -1
07-28 12:43:36.380   791  1469 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
,07-28 12:43:36.380   791  1469 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:36.380   791  1469 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:36.380   791  1469 D SettingsProvider: selectionArgs: false
07-28 12:43:36.380   791  1469 D SettingsProvider: selectionArgs: 1002
07-28 12:43:36.380   791  1469 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:43:36.380   791  1469 D SettingsProvider: ret = -1
,07-28 12:43:36.380   791   832 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
07-28 12:43:36.380   791   832 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:36.380   791   832 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:36.380   791   832 D SettingsProvider: selectionArgs: false
07-28 12:43:36.380   791   832 D SettingsProvider: selectionArgs: 1002
07-28 12:43:36.380   791   832 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:43:36.380   791   832 D SettingsProvider: ret = -1
,07-28 12:43:36.380   791  1468 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
07-28 12:43:36.380   791  1468 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:36.380   791  1468 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:36.380   791  1468 D SettingsProvider: selectionArgs: false
07-28 12:43:36.380   791  1468 D SettingsProvider: selectionArgs: 1002
07-28 12:43:36.380   791  1468 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:43:36.380   791  1468 D SettingsProvider: ret = -1
07-28 12:43:36.380   791  1532 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
07-28 12:43:36.380   791  1532 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:36.380   791  1532 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:36.380   791  1532 D SettingsProvider: selectionArgs: false
07-28 12:43:36.380   791  1532 D SettingsProvider: selectionArgs: 1002
07-28 12:43:36.380   791  1532 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:43:36.380   791  1532 D SettingsProvider: ret = -1
,07-28 12:43:36.380   791  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
07-28 12:43:36.380   791  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:36.380   791  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:36.380   791  1476 D SettingsProvider: selectionArgs: false
07-28 12:43:36.380   791  1476 D SettingsProvider: selectionArgs: 1002
07-28 12:43:36.380   791  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:43:36.380   791  1476 D SettingsProvider: ret = -1
07-28 12:43:36.380   791   831 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
07-28 12:43:36.380   791   831 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:36.380   791   831 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:36.380   791   831 D SettingsProvider: selectionArgs: false
07-28 12:43:36.380   791   831 D SettingsProvider: selectionArgs: 1002
07-28 12:43:36.380   791   831 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:43:36.380   791   831 D SettingsProvider: ret = -1
,07-28 12:43:36.380   791  1574 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
07-28 12:43:36.380   791  1574 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:36.380   791  1574 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:36.380   791  1574 D SettingsProvider: selectionArgs: false
07-28 12:43:36.380   791  1574 D SettingsProvider: selectionArgs: 1002
07-28 12:43:36.380   791  1574 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:43:36.380   791  1574 D SettingsProvider: ret = -1
,07-28 12:43:36.380   791  1358 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:43:36.380   791  1358 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:36.380   791  1358 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:36.380   791  1358 D SettingsProvider: selectionArgs: false
07-28 12:43:36.380   791  1358 D SettingsProvider: selectionArgs: 1002
07-28 12:43:36.380   791  1358 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:43:36.380   791  1358 D SettingsProvider: ret = -1
,07-28 12:43:36.380   791  1679 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:43:36.380   791  1679 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:36.380   791  1679 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:36.380   791  1679 D SettingsProvider: selectionArgs: false
07-28 12:43:36.380   791  1679 D SettingsProvider: selectionArgs: 1002
07-28 12:43:36.380   791  1679 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:43:36.380   791  1679 D SettingsProvider: ret = -1
07-28 12:43:36.380   791  1443 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
,07-28 12:43:36.380   791  1443 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:36.380   791  1443 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:36.380   791  1443 D SettingsProvider: selectionArgs: false
07-28 12:43:36.380   791  1443 D SettingsProvider: selectionArgs: 1002
07-28 12:43:36.380   791  1443 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:43:36.380   791  1443 D SettingsProvider: ret = -1
07-28 12:43:36.380   791  1259 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
07-28 12:43:36.380   791  1259 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
,07-28 12:43:36.380   791  1259 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:36.380   791  1259 D SettingsProvider: selectionArgs: false
07-28 12:43:36.380   791  1259 D SettingsProvider: selectionArgs: 1002
07-28 12:43:36.380   791  1259 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:43:36.380   791  1259 D SettingsProvider: ret = -1
,07-28 12:43:36.390   791  1144 I ActivityManager: Killing 6747:com.sec.android.service.health/u0a21 (adj 15): emptyCount ##41
,07-28 12:43:36.390  1897  1897 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-28 12:43:36.400   791  1469 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-28 12:43:36.400   791  1469 D ActivityManager: caller:android.app.ApplicationThreadProxy@2129e705, r.packageName :com.google.android.gms
,07-28 12:43:36.400  1897  1897 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-28 12:43:36.400  1897  7712 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-28 12:43:36.410  7031  7031 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-28 12:43:36.420   791  1657 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:36.420  7514  7514 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:43:36.420  7514  7514 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:43:36.420  7514  7514 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:43:36.420  7514  7514 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:43:36.500   791  1366 I art     : Explicit concurrent mark sweep GC freed 65936(3MB) AllocSpace objects, 23(416KB) LOS objects, 29% free, 37MB/53MB, paused 1.276ms total 91.438ms
,07-28 12:43:36.510   791  1679 D ActivityManager: caller:android.app.ApplicationThreadProxy@1ec50b26, r.packageName :com.google.android.gms
,07-28 12:43:36.510  6764  6764 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-28 12:43:36.510  6764  6764 I PCWCLIENTTRACE_PushUtil: sales region : global
07-28 12:43:36.510  6764  6764 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-28 12:43:36.510  6764  6764 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:43:36.510  6764  6764 I PCWCLIENTTRACE_SYSTEMReceiver: noConnectivity : true
,07-28 12:43:36.520  1897  7712 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-28 12:43:36.520   791  1469 D ActivityManager: startProcessLocked calleePkgName: com.google.android.music, hostingType: broadcast
,07-28 12:43:36.520   791  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:36.520   791  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:36.520   791  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:36.520   791  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:36.560  7716  7716 E Zygote  : MountEmulatedStorage()
,07-28 12:43:36.560  7716  7716 E Zygote  : v2
07-28 12:43:36.560  7716  7716 I libpersona: KNOX_SDCARD checking this for 10144
07-28 12:43:36.560  7716  7716 I libpersona: KNOX_SDCARD not a persona
,07-28 12:43:36.570   791  1469 I ActivityManager: Start proc com.google.android.music:main for broadcast com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver: pid=7716 uid=10144 gids={50144, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:43:36.580  7716  7716 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:43:36.580  7716  7716 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:43:36.580  7716  7716 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-28 12:43:36.600  7716  7716 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:43:36.600  7716  7716 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:36.610  7716  7716 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-28 12:43:36.700  7716  7716 I MusicStore: Database version: 108
,07-28 12:43:36.710   791  1469 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:43:36.770  7716  7716 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,07-28 12:43:36.780  7716  7716 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,07-28 12:43:36.780  7716  7716 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,07-28 12:43:36.820  7716  7716 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 255 native methods...
,07-28 12:43:36.860  7716  7716 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,07-28 12:43:36.860  7716  7716 W System  : Could not create com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl with ClassLoader android.app.LoadedApk$WarningContextClassLoader@1494eeae: com.google.android.gms.org.conscrypt.OpenSSLSocketFactoryImpl
,07-28 12:43:36.860  7716  7716 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,07-28 12:43:36.860  7716  7716 D AndroidMusic: GMSCore installation verified
,07-28 12:43:36.870   791  1574 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:43:36.880  7716  7716 I ConfigStore: Config Database version: 1
,07-28 12:43:36.920   265   548 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-28 12:43:36.920   265   548 W Vold    : Returning OperationFailed - no handler for errno 0
,07-28 12:43:36.920  7716  7716 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-28 12:43:36.920   265   548 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-28 12:43:36.920   265   548 W Vold    : Returning OperationFailed - no handler for errno 0
,07-28 12:43:36.920  7716  7716 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-28 12:43:36.920   265   548 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.music/files/
07-28 12:43:36.920   265   548 W Vold    : Returning OperationFailed - no handler for errno 0
,07-28 12:43:36.920  7716  7716 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.music/files
,07-28 12:43:36.930   791  1259 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-28 12:43:36.930   791  1259 D ActivityManager: caller:android.app.ApplicationThreadProxy@394779f1, r.packageName :com.google.android.music
,07-28 12:43:36.940   791   832 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:43:36.950   791  1443 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-28 12:43:36.950   791  1428 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-28 12:43:36.960   791  1366 I AudioService: getStreamVolume 3 index 0
,07-28 12:43:36.960  7716  7716 I MediaRouter: Found default route: MediaRouter.RouteInfo{ uniqueId=android/.support.v7.media.SystemMediaRouteProvider:DEFAULT_ROUTE, name=Phone, description=null, enabled=true, connecting=false, canDisconnect=false, playbackType=0, playbackStream=3, volumeHandling=1, volume=0, volumeMax=15, presentationDisplayId=-1, extras=null, settingsIntent=null, providerPackageName=android }
,07-28 12:43:36.960  7716  7716 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,07-28 12:43:36.980   791   832 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:43:36.980   791  1428 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:43:36.980   791  1468 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:43:36.990   791  1638 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-28 12:43:36.990   791  1259 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.cloudagent, hostingType: broadcast
,07-28 12:43:36.990   791  1259 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:36.990   791  1259 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:36.990   791  1259 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:36.990   791  1259 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:37.030  7747  7747 E Zygote  : MountEmulatedStorage()
,07-28 12:43:37.030  7747  7747 E Zygote  : v2
07-28 12:43:37.030  7747  7747 I libpersona: KNOX_SDCARD checking this for 10004
07-28 12:43:37.030  7747  7747 I libpersona: KNOX_SDCARD not a persona
,07-28 12:43:37.030   791  1259 I ActivityManager: Start proc com.sec.android.cloudagent for broadcast com.sec.android.cloudagent/.detector.DetectorReceiver: pid=7747 uid=10004 gids={50004, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:43:37.060  7747  7747 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:43:37.060  7747  7747 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:43:37.060  7747  7747 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:43:37.060   791   831 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.gms, action: null
,07-28 12:43:37.070  7716  7716 I GHttpClientFactory: Using the GMSCore's GoogleHttpClient
,07-28 12:43:37.070   791  1366 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:43:37.080  7747  7747 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:43:37.080  7747  7747 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:37.100  7747  7747 D ResourcesManager: creating new AssetManager and set to /system/priv-app/CloudAgent/CloudAgent.apk
,07-28 12:43:37.140   791  1532 I ActivityManager: Killing 4968:com.sec.spp.push/u0a43 (adj 15): emptyCount ##41
,07-28 12:43:37.140   791  1144 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.diagmonagent, hostingType: broadcast
,07-28 12:43:37.140   791  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:37.140   791  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:37.140   791  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:37.140   791  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:37.180  7766  7766 E Zygote  : MountEmulatedStorage()
,07-28 12:43:37.180  7766  7766 E Zygote  : v2
07-28 12:43:37.180  7766  7766 I libpersona: KNOX_SDCARD checking this for 1000
07-28 12:43:37.180  7766  7766 I libpersona: KNOX_SDCARD not a persona
,07-28 12:43:37.180   791  1144 I ActivityManager: Start proc com.sec.android.diagmonagent for broadcast com.sec.android.diagmonagent/.DiagMonRegistrationReceiver: pid=7766 uid=1000 gids={41000, 9997, 3002, 3001, 3003, 1007, 1028, 1015, 1023, 2001, 1024, 1001} abi=armeabi-v7a
,07-28 12:43:37.210  7766  7766 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:43:37.210  7766  7766 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:43:37.210  7766  7766 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:43:37.230  7766  7766 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:43:37.230  7766  7766 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:37.240  7766  7766 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DiagMonAgent/DiagMonAgent.apk
,07-28 12:43:37.270  7766  7766 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(41/onCreate)] myUserId : 0
,07-28 12:43:37.290  7766  7766 I DIAGMON_AGENT: [com.diagmondm.db.file.XDB(374/llIlIIIIlIIIIIlIlIII)] 
,07-28 12:43:37.390  7766  7766 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(61/onCreate)] nStatus : 0
,07-28 12:43:37.400  7766  7766 I DIAGMON_AGENT: [com.sec.android.diagmonagent.DiagMonAgentApplication(78/onCreate)] DiagMon DM Application Start !
,07-28 12:43:37.400  7766  7766 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:43:37.400  7766  7766 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-28 12:43:37.460   791  1469 D ActivityManager: getContentProviderImpl callerProcessName:com.sec.android.diagmonagent, calleePkgName: com.sec.android.fotaclient
,07-28 12:43:37.460   791  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:37.460   791  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:37.460   791  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:37.460   791  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:37.500   791  1469 I ActivityManager: Start proc com.sec.android.fotaclient for content provider com.sec.android.fotaclient/.log.MasterLogProvider: pid=7782 uid=10014 gids={50014, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:43:37.500  7782  7782 E Zygote  : MountEmulatedStorage()
07-28 12:43:37.500  7782  7782 E Zygote  : v2
07-28 12:43:37.500  7782  7782 I libpersona: KNOX_SDCARD checking this for 10014
07-28 12:43:37.500  7782  7782 I libpersona: KNOX_SDCARD not a persona
,07-28 12:43:37.520  7782  7782 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-28 12:43:37.520  7782  7782 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:43:37.520  7782  7782 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-28 12:43:37.550  7782  7782 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:43:37.550  7782  7782 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:37.570  7782  7782 D ResourcesManager: creating new AssetManager and set to /system/priv-app/FotaClient/FotaClient.apk
,07-28 12:43:37.620   791  1366 I ActivityManager: Killing 6650:com.android.defcontainer/u0a7 (adj 15): emptyCount ##41
,07-28 12:43:37.630  7782  7782 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,07-28 12:43:37.630  7782  7782 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,07-28 12:43:37.650  7782  7782 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,07-28 12:43:37.650   791  1469 I ActivityManager: Killing 6805:com.samsung.android.sdk.samsunglink/u0a48 (adj 15): emptyCount ##41
,07-28 12:43:37.660  2502  2502 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-28 12:43:37.660  2502  2502 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1469702617669
,07-28 12:43:37.660  2502  2502 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,07-28 12:43:37.660   791  1476 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:37.660   791  1532 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:37.660  2502  2502 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : false| MOBILE : false
,07-28 12:43:37.660  2502  2502 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,07-28 12:43:37.660   791  1358 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.app.pinboard, hostingType: broadcast
,07-28 12:43:37.660   791  1358 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:37.660   791  1358 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:37.660   791  1358 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:37.660   791  1358 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:37.690  7441  7508 I WifiManager: packageName : com.test.thalitest
,07-28 12:43:37.700   791  1366 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-28 12:43:37.700   791  1366 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-28 12:43:37.700   791  1366 D SecContentProvider2: mCursor = null
,07-28 12:43:37.700   791  1366 D WifiService: setWifiEnabled: true pid=7441, uid=10079
07-28 12:43:37.700   791  1366 W ActivityManager: Permission Denial: getCurrentUser() from pid=7441, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,07-28 12:43:37.700   791  1366 W WifiService: Failed getting userId using ActivityManagerNative
07-28 12:43:37.700   791  1366 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7441, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-28 12:43:37.700   791  1366 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-28 12:43:37.700   791  1366 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-28 12:43:37.700   791  1366 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-28 12:43:37.700   791  1366 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-28 12:43:37.700   791  1366 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
07-28 12:43:37.700   791  1366 D SettingsProvider: name = wifi_on
,07-28 12:43:37.700   791  1149 E WifiHW  : ##################### set firmware type 0 #####################
,07-28 12:43:37.700   299  1061 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
07-28 12:43:37.700   299  1061 I WifiHW  : module is semco
07-28 12:43:37.700   299  1061 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-28 12:43:37.700   299  1061 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-28 12:43:37.700   299  1061 E WifiHW  : TEMP_FAILURE_RETRY complete
07-28 12:43:37.700   299  1061 D SoftapController: Softap fwReload - Ok
,07-28 12:43:37.700   299  1061 D CommandListener: Setting iface cfg
07-28 12:43:37.700   299  1061 D CommandListener: Trying to bring down wlan0
,07-28 12:43:37.710   791  1358 I ActivityManager: Start proc com.samsung.android.app.pinboard:tagService for broadcast com.samsung.android.app.pinboard/.service.TagReadyReceiver: pid=7798 uid=10036 gids={50036, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,07-28 12:43:37.710   299  1061 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:43:37.710  7798  7798 E Zygote  : MountEmulatedStorage()
,07-28 12:43:37.710   791  1149 E WifiHW  : supplicant_name : p2p_supplicant
07-28 12:43:37.710  7798  7798 E Zygote  : v2
,07-28 12:43:37.710  7798  7798 I libpersona: KNOX_SDCARD checking this for 10036
07-28 12:43:37.710  7798  7798 I libpersona: KNOX_SDCARD not a persona
,07-28 12:43:37.740  7798  7798 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-28 12:43:37.740  7798  7798 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:43:37.740  7798  7798 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:43:37.750  7813  7813 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-28 12:43:37.750  7813  7813 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-28 12:43:37.750  7813  7813 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-28 12:43:37.750  7813  7813 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-28 12:43:37.750   387   387 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7813
07-28 12:43:37.750   387   387 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x0000010C
07-28 12:43:37.750  7813  7813 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-28 12:43:37.750  7813  7813 I wpa_supplicant: ssSupport state is = 1
,07-28 12:43:37.750  7813  7813 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,07-28 12:43:37.750  7813  7813 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-28 12:43:37.750   387   387 I SecureStorage: [INFO]: SPID(0x00000003)Credentials: uid 1010, gid 1010, pid 7813
07-28 12:43:37.750   387   387 I SecureStorage: [INFO]: SPID(0x00000003)Received function mask & code: 0x00000106
,07-28 12:43:37.760  7798  7798 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:43:37.760  7798  7798 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:37.770  7798  7798 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,07-28 12:43:37.770  7798  7798 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-28 12:43:37.770  7798  7798 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-28 12:43:37.800  7798  7798 E Minikin : addFont failed to create font /system/fonts/SamsungSans-light.ttf
,07-28 12:43:37.810   791  1574 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:37.810   791  1428 I ActivityManager: Killing 6830:com.osp.app.signin/u0a50 (adj 15): emptyCount ##41
,07-28 12:43:37.820   791  1149 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-28 12:43:37.820   791   791 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:43:37.820  1193  1193 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:43:37.820  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,07-28 12:43:37.820  1193  1193 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:37.820  1193  1193 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
07-28 12:43:37.820  1193  1193 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:37.820  1193  1595 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
,07-28 12:43:37.820  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:37.820   791  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-28 12:43:37.820  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:37.820  1313  1313 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:37.820  1193  1193 D HotspotTile: onReceive : 2, 0
,07-28 12:43:37.820   791  1443 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.soagent, hostingType: broadcast
07-28 12:43:37.820   791  1443 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:37.820   791  1443 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:37.820   791  1443 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:37.820   791  1443 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:37.870  7825  7825 E Zygote  : MountEmulatedStorage()
07-28 12:43:37.870  7825  7825 E Zygote  : v2
07-28 12:43:37.870  7825  7825 I libpersona: KNOX_SDCARD checking this for 10042
07-28 12:43:37.870  7825  7825 I libpersona: KNOX_SDCARD not a persona
,07-28 12:43:37.870   791  1443 I ActivityManager: Start proc com.sec.android.soagent for broadcast com.sec.android.soagent/.RegisterReceiver: pid=7825 uid=10042 gids={50042, 9997, 3003} abi=armeabi-v7a
,07-28 12:43:37.890   347   347 I art     : Explicit concurrent mark sweep GC freed 8723(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 307us total 13.078ms
,07-28 12:43:37.900  7825  7825 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:43:37.900  7825  7825 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:43:37.900  7825  7825 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:43:37.900   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 276us total 10.311ms
,07-28 12:43:37.910   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 290us total 9.948ms
,07-28 12:43:37.920  7825  7825 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:43:37.920  7825  7825 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:37.930  7825  7825 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SOAgent/SOAgent.apk
,07-28 12:43:37.950  7825  7825 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(98/onReceive)] Network is not available
,07-28 12:43:37.950   791  1443 I ActivityManager: Killing 6850:com.android.mms/u0a55 (adj 15): emptyCount ##41
,07-28 12:43:37.960   791  1532 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,07-28 12:43:37.960   791  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:37.960   791  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:37.960   791  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:37.960   791  1532 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:37.960   791  1468 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:37.960  3705  7841 I DBG_POLICYDM: [com.policydm.XDMService(515/xdmProtoIsWIFIConnected)] WiFi network Connected : false
,07-28 12:43:37.960   791  1476 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:37.960  3705  7841 I DBG_POLICYDM: [com.policydm.XDMService(525/xdmProtoIsMobileDataConnected)] Mobile Data Connected : false
,07-28 12:43:37.960  3705  7841 E DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver$2(104/run)] network is unserviceable
,07-28 12:43:37.960  3705  7841 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 2, current network is 0
,07-28 12:43:37.960  3705  7841 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,07-28 12:43:38.000  7842  7842 E Zygote  : MountEmulatedStorage()
,07-28 12:43:38.000  7842  7842 E Zygote  : v2
07-28 12:43:38.000  7842  7842 I libpersona: KNOX_SDCARD checking this for 10043
07-28 12:43:38.000  7842  7842 I libpersona: KNOX_SDCARD not a persona
,07-28 12:43:38.000   791  1532 I ActivityManager: Start proc com.sec.spp.push for broadcast com.sec.spp.push/.monitor.SystemStateMoniter: pid=7842 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:43:38.020   387   387 I SecureStorage: [INFO]: SPID(0x00000003)Secure Storage Daemon finished processing with result: 0
,07-28 12:43:38.040  7842  7842 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:43:38.040   791  1259 D CountryDetector: No listener is left
07-28 12:43:38.040  7842  7842 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:43:38.040  7842  7842 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,07-28 12:43:38.060  7842  7842 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:43:38.060  7842  7842 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:38.070  7842  7842 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,07-28 12:43:38.090  7842  7842 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,07-28 12:43:38.090  7842  7842 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,07-28 12:43:38.100  7842  7842 D SPPClientService: PushLog.txt file is not deleted.
,07-28 12:43:38.100  7842  7842 D SPPClientService: PushLog.txt file is not deleted.
07-28 12:43:38.100  7842  7842 D SPPClientService: ============PushLog. stop!
,07-28 12:43:38.100  7842  7842 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : true
,07-28 12:43:38.100   791  1144 D ActivityManager: startProcessLocked calleePkgName: com.osp.app.signin, hostingType: broadcast
,07-28 12:43:38.110   791  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:38.110   791  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:38.110   791  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:38.110   791  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:38.140  7858  7858 E Zygote  : MountEmulatedStorage()
07-28 12:43:38.140  7858  7858 E Zygote  : v2
07-28 12:43:38.140  7858  7858 I libpersona: KNOX_SDCARD checking this for 10050
07-28 12:43:38.140  7858  7858 I libpersona: KNOX_SDCARD not a persona
,07-28 12:43:38.150   791  1144 I ActivityManager: Start proc com.osp.app.signin for broadcast com.osp.app.signin/.OspReceiver: pid=7858 uid=10050 gids={50050, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:43:38.150   791  1144 I ActivityManager: Killing 6875:com.sec.android.provider.badge/u0a92 (adj 15): emptyCount ##41
,07-28 12:43:38.150   791  1476 D ActivityManager: startService callerProcessName:com.sec.spp.push, calleePkgName: com.sec.spp.push
,07-28 12:43:38.150   791  1476 D ActivityManager: caller:android.app.ApplicationThreadProxy@1b04c4d1, r.packageName :com.sec.spp.push
,07-28 12:43:38.160  7858  7858 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:43:38.160  7858  7858 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:43:38.160  7858  7858 E SELinux : [DEBUG] get_category: variable seinfo: default sensitivity: NULL, cateogry: NULL
,07-28 12:43:38.180  7842  7865 E SPPClientService: [[SystemStateMonitorService]] No Active Internet
,07-28 12:43:38.180  7858  7858 D TimaKeyStoreProvider: TimaSignature is unavailable
07-28 12:43:38.180  7858  7858 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:38.200  7858  7858 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,07-28 12:43:38.230  7858  7858 I SA      : [SSP] onCreated
,07-28 12:43:38.240  7858  7858 I SA      : [TPM] There is no property file
,07-28 12:43:38.240  7858  7858 I SA      : [SCU] isHaveSA() - false
,07-28 12:43:38.240  7858  7858 I SA      : [TPM] getModelProperty : null
,07-28 12:43:38.240  7858  7858 I SA      : [TPM] getCSCProperty : null
,07-28 12:43:38.250  7858  7858 I SA      : [DM] init START
,07-28 12:43:38.250  7858  7858 I SA      : [DM] This device is not a Vodafone
,07-28 12:43:38.250  7858  7858 I SA      : checkReactivationActive for LOLLIPOP
,07-28 12:43:38.250  7858  7858 I SA      : checkReactivationActive for reactiveActive
07-28 12:43:38.250  7858  7858 I SA      : setSupportRL : true
,07-28 12:43:38.250  7858  7858 I SA      : [SCU] isHaveSA() - false
,07-28 12:43:38.250  7858  7858 I SA      : support phone number id : false
,07-28 12:43:38.260  7858  7858 I SA      : [DM] init END
,07-28 12:43:38.260  7858  7858 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,07-28 12:43:38.270  7858  7858 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? noConnectivity:true ]
,07-28 12:43:38.270  7858  7858 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-28 12:43:38.270  7858  7858 I SA      : [SLFUCHKMGR] constructor called
,07-28 12:43:38.270  7813  7813 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,07-28 12:43:38.270  7858  7858 I SA      : [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
07-28 12:43:38.270  7858  7858 I SA      : [OR] == isSIMCardReady false ==
,07-28 12:43:38.270  7858  7858 I SA      : [SCU] == networkStateCheck == false
07-28 12:43:38.270  7858  7858 I SA      : [OR] onReceive END
,07-28 12:43:38.280   791   831 I ActivityManager: Killing 6891:com.sec.android.app.soundalive/u0a64 (adj 15): emptyCount ##41
,07-28 12:43:38.280   791   832 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.scloud.backup, hostingType: broadcast
,07-28 12:43:38.280   791   832 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:38.280   791   832 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:38.280   791   832 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:38.280   791   832 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:38.310  7813  7813 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-28 12:43:38.310  7813  7813 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-28 12:43:38.310   387   387 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7813
07-28 12:43:38.310   387   387 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-28 12:43:38.310  7813  7813 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-28 12:43:38.310  7813  7813 I wpa_supplicant: ssSupport state is = 1
07-28 12:43:38.310  7813  7813 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,07-28 12:43:38.310  7813  7813 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-28 12:43:38.310  7813  7813 E wpa_supplicant: SIM READ ERROR
07-28 12:43:38.310  7813  7813 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:43:38.310  7813  7813 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-28 12:43:38.310  7813  7813 E wpa_supplicant: SIM READ ERROR
07-28 12:43:38.310  7813  7813 I wpa_supplicant: Blacklist: Clear (all) 
07-28 12:43:38.310  7813  7813 I wpa_supplicant: wpa_default_ap_write_once
07-28 12:43:38.310  7813  7813 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-28 12:43:38.310  7813  7813 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:43:38.310  7813  7813 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
07-28 12:43:38.310  7813  7813 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:43:38.310  7813  7813 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-28 12:43:38.320  7813  7813 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-28 12:43:38.320  7882  7882 E Zygote  : MountEmulatedStorage()
07-28 12:43:38.320  7882  7882 E Zygote  : v2
07-28 12:43:38.320  7882  7882 I libpersona: KNOX_SDCARD checking this for 10074
07-28 12:43:38.320  7882  7882 I libpersona: KNOX_SDCARD not a persona
,07-28 12:43:38.330   791   832 I ActivityManager: Start proc com.samsung.android.scloud.backup for broadcast com.samsung.android.scloud.backup/.SCloudBackupReceiver: pid=7882 uid=10074 gids={50074, 9997, 1028, 1015, 3003} abi=armeabi-v7a
,07-28 12:43:38.340  7882  7882 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-28 12:43:38.340  7882  7882 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:43:38.340  7882  7882 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:43:38.350  7882  7882 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:43:38.350  7882  7882 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:38.370  7882  7882 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudBackupApp/sCloudBackupApp.apk
,07-28 12:43:38.420  7882  7882 I sCloudBackupApp: sCloudBackupApp Version Info : 3.13.7.KK_APP
,07-28 12:43:38.420  7882  7882 I SCloudBackupReceiver: Other Intent
,07-28 12:43:38.420  7190  7190 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
,07-28 12:43:38.420  7190  7190 I KnoxUsageLogPro: premStatus:2
,07-28 12:43:38.430  7190  7190 I KnoxUsageLogPro: isEulaShown : false
07-28 12:43:38.430  7190  7190 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
,07-28 12:43:38.430   791  1679 D ActivityManager: startProcessLocked calleePkgName: com.android.chrome, hostingType: broadcast
,07-28 12:43:38.430   791  1679 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:38.430   791  1679 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:38.430   791  1679 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:38.430   791  1679 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:38.470  7898  7898 E Zygote  : MountEmulatedStorage()
07-28 12:43:38.470  7898  7898 E Zygote  : v2
07-28 12:43:38.470  7898  7898 I libpersona: KNOX_SDCARD checking this for 10104
07-28 12:43:38.470  7898  7898 I libpersona: KNOX_SDCARD not a persona
,07-28 12:43:38.480  7898  7898 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-28 12:43:38.480  7898  7898 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:43:38.480  7898  7898 E SELinux : [DEBUG] get_category: variable seinfo: chrome sensitivity: NULL, cateogry: NULL
,07-28 12:43:38.480   791  1679 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher: pid=7898 uid=10104 gids={50104, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:43:38.480   791  1679 I ActivityManager: Killing 5771:com.samsung.android.app.assistantmenu/1000 (adj 15): emptyCount ##41
,07-28 12:43:38.500  7898  7898 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:43:38.500  7898  7898 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:38.510  7898  7898 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,07-28 12:43:38.590   791  1358 D ActivityManager: startProcessLocked calleePkgName: com.google.android.apps.magazines, hostingType: broadcast
,07-28 12:43:38.590   791  1358 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:38.590   791  1358 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:38.590   791  1358 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:38.590   791  1358 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:38.630  7914  7914 E Zygote  : MountEmulatedStorage()
,07-28 12:43:38.630  7914  7914 E Zygote  : v2
07-28 12:43:38.630  7914  7914 I libpersona: KNOX_SDCARD checking this for 10146
07-28 12:43:38.630  7914  7914 I libpersona: KNOX_SDCARD not a persona
,07-28 12:43:38.630   791  1358 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7914 uid=10146 gids={50146, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:43:38.640   791  1358 I ActivityManager: Killing 6912:com.wsomacp/u0a29 (adj 15): emptyCount ##41
,07-28 12:43:38.650  7914  7914 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:43:38.650  7914  7914 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:43:38.650  7914  7914 E SELinux : [DEBUG] get_category: variable seinfo: untrusted sensitivity: NULL, cateogry: NULL
,07-28 12:43:38.660  7914  7914 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:43:38.660  7914  7914 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:38.680  7914  7914 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,07-28 12:43:38.870   265   548 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
07-28 12:43:38.870   265   548 W Vold    : Returning OperationFailed - no handler for errno 0
,07-28 12:43:38.870  7914  7932 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,07-28 12:43:38.870   265   548 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
07-28 12:43:38.870   265   548 W Vold    : Returning OperationFailed - no handler for errno 0
,07-28 12:43:38.870  7914  7932 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,07-28 12:43:38.880   265   548 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache/
07-28 12:43:38.880   265   548 W Vold    : Returning OperationFailed - no handler for errno 0
,07-28 12:43:38.880  7914  7935 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/cache
,07-28 12:43:38.890   265   548 E Vold    : Failed to find mounted volume for /storage/extSdCard/Android/data/com.google.android.apps.magazines/files/
07-28 12:43:38.890   265   548 W Vold    : Returning OperationFailed - no handler for errno 0
,07-28 12:43:38.890  7914  7935 W ContextImpl: Failed to ensure directory: /storage/extSdCard/Android/data/com.google.android.apps.magazines/files
,07-28 12:43:38.900   791  1343 E Watchdog: !@Sync 5
,07-28 12:43:39.050  7914  7914 I WebViewFactory: Loading com.google.android.webview version 43.0.2357.121 (code 2357121)
,07-28 12:43:39.050  7914  7914 D ResourcesManager: creating new AssetManager and set to /system/app/WebViewGoogle/WebViewGoogle.apk
,07-28 12:43:39.070  7914  7914 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 9218-9221)
,07-28 12:43:39.070  7914  7914 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-28 12:43:39.070  7914  7914 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3cd2fe47}
,07-28 12:43:39.070  7914  7914 I LibraryLoader: Expected native library version number "",actual native library version number ""
,07-28 12:43:39.070  7914  7914 I chromium: [INFO:library_loader_hooks.cc(112)] Chromium logging enabled: level = 0, default verbosity = 0
,07-28 12:43:39.090  7914  7914 I BrowserStartupController: Initializing chromium process, singleProcess=true
,07-28 12:43:39.090  7914  7914 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,07-28 12:43:39.100  7914  7914 E SysUtils: ApplicationContext is null in ApplicationStatus
,07-28 12:43:39.120   304   304 E SMD     : DCD ON
,07-28 12:43:39.130   791  1152 E Tethering: No numeric data
,07-28 12:43:39.130   791  1146 V NetworkStats: performPollLocked(flags=0x1)
07-28 12:43:39.130   791  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:43:39.130  1193  1193 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-28 12:43:39.130  1193  1193 D HotspotTile: updateTetherState():false, false
07-28 12:43:39.130   791  1152 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-28 12:43:39.130   791  1146 D NetworkStatsFactory: UpdateStatsForKnox
,07-28 12:43:39.130   791  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:39.130   791  1146 V NetworkStats: performPollLocked() took 3ms
07-28 12:43:39.130   791  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:43:39.130   791  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:43:39.130   791  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:43:39.140  7914  7914 W chromium: [WARNING:resource_bundle.cc(286)] locale_file_path.empty()
,07-28 12:43:39.140  7914  7914 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=44 off=50556 len=3379
07-28 12:43:39.140  7914  7914 I chromium: [INFO:aw_browser_main_parts.cc(76)] Loading webviewchromium.pak from, fd:45 off:7638088 len:1165478
,07-28 12:43:39.150  7914  7914 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025_msm8974_LA.BF.1.1_RB1__release_AU ()
07-28 12:43:39.150  7914  7914 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.01.03
07-28 12:43:39.150  7914  7914 I Adreno-EGL: Build Date: 11/19/14 Wed
07-28 12:43:39.150  7914  7914 I Adreno-EGL: Local Branch: mybranch5813579
07-28 12:43:39.150  7914  7914 I Adreno-EGL: Remote Branch: quic/LA.BF.1.1_rb1.11
07-28 12:43:39.150  7914  7914 I Adreno-EGL: Local Patches: NONE
07-28 12:43:39.150  7914  7914 I Adreno-EGL: Reconstruct Branch: AU_LINUX_ANDROID_LA.BF.1.1_RB1.05.00.00.002.025 + 30e7589 +  NOTHING
,07-28 12:43:39.150  7813  7813 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,07-28 12:43:39.180  7813  7813 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-28 12:43:39.180  7813  7813 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-28 12:43:39.180  7813  7813 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-28 12:43:39.180   387   387 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7813
07-28 12:43:39.180   387   387 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-28 12:43:39.180  7813  7813 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-28 12:43:39.180  7813  7813 I wpa_supplicant: ssSupport state is = 1
,07-28 12:43:39.180  7813  7813 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-28 12:43:39.180  7813  7813 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-28 12:43:39.180   387   387 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 7813
07-28 12:43:39.180   387   387 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-28 12:43:39.180  7813  7813 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-28 12:43:39.180  7813  7813 I wpa_supplicant: ssSupport state is = 1
07-28 12:43:39.180  7813  7813 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:43:39.180  7813  7813 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-28 12:43:39.180  7813  7813 E wpa_supplicant: SIM READ ERROR
07-28 12:43:39.180  7813  7813 I wpa_supplicant: wpa_default_ap_write_once
07-28 12:43:39.180  7813  7813 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-28 12:43:39.180  7813  7813 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-28 12:43:39.200  7813  7813 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
07-28 12:43:39.200  7813  7813 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,07-28 12:43:39.210  7813  7813 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
07-28 12:43:39.210  7813  7813 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,07-28 12:43:39.210   791  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,07-28 12:43:39.210   791  1149 D WifiNative-HAL: callSECApiBoolean - ID [21]
07-28 12:43:39.210  7813  7813 I wpa_supplicant: HOTSPOT20_ENABLE called
07-28 12:43:39.210  7813  7813 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:43:39.210  7813  7813 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-28 12:43:39.210  7813  7813 E wpa_supplicant: SIM READ ERROR
07-28 12:43:39.210  7813  7813 I wpa_supplicant: Blacklist: Clear (all) 
,07-28 12:43:39.220  7914  7970 W AudioManagerAndroid: Requires BLUETOOTH permission
,07-28 12:43:39.220  7914  7914 I NSApplication: Starting up...
,07-28 12:43:39.240   791   831 I ActivityManager: Killing 6925:com.google.android.apps.docs/u0a112 (adj 15): emptyCount ##41
,07-28 12:43:39.250  7813  7813 I wpa_supplicant: Skip scan - bUseNetwork false
,07-28 12:43:39.250   791  1149 D WifiNative-HAL: callSECApiInt - ID [210]
,07-28 12:43:39.250   791  1149 D WifiConfigStore: Loading config and enabling all networks 
,07-28 12:43:39.250   791   791 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:43:39.250  1193  1193 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:43:39.250  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-28 12:43:39.250  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:39.250  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:39.250  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:39.250  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:39.250  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:39.250  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:39.250  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:39.250  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:39.250  1193  1193 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:39.250  1193  1193 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,07-28 12:43:39.250  7441  7441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:43:39.250  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:39.250  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:39.250  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:39.250  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:39.250  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:39.250  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:39.250  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:39.250  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:43:39.250  7441  7441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:39.250  1193  1595 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-28 12:43:39.250  7441  7441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:43:39.250   791  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
07-28 12:43:39.250  1193  1193 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:43:39.250  1193  1193 D HotspotTile: onReceive : 3, 0
07-28 12:43:39.250  1313  1313 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:43:39.260  7441  7441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:43:39.260  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:39.260  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:39.260  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:39.260  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:39.260  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:39.260  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:39.260  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:39.260  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:43:39.260  7441  7441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:39.260  7441  7441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:43:39.260   791  1149 E WifiConfigStore: Not a HS20
,07-28 12:43:39.270   791  1149 E WifiConfigStore: Not a HS20
,07-28 12:43:39.280   791  1149 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-28 12:43:39.280   791  1149 D WifiNative-HAL: callSECApiInt - ID [65]
,07-28 12:43:39.290   791  1149 D WifiNative-HAL: callSECApiBoolean - ID [13]
07-28 12:43:39.290  7813  7813 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-28 12:43:39.290  7813  7813 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,07-28 12:43:39.290  7813  7813 I wpa_supplicant: reset timer : RESET_TIMER 0
07-28 12:43:39.290  7813  7813 I wpa_supplicant: P2P: Current p2p state = IDLE
07-28 12:43:39.290  7813  7813 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
07-28 12:43:39.290  7813  7813 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
07-28 12:43:39.290  7813  7813 I wpa_supplicant: First Scan Start
,07-28 12:43:39.290  7647  7647 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:43:39.290  7813  7813 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-28 12:43:39.290   791  1149 D WifiNative-HAL: Setting external_sim to 1
07-28 12:43:39.290   791  1149 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 12:43:39.290   791  1149 I WifiNative-HAL: startHal
07-28 12:43:39.290   791  1149 E wifi    : getStaticLongField sWifiHalHandle 0x933b986c
07-28 12:43:39.290   791  1149 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x8019c2
07-28 12:43:39.290   791  1149 I WifiNative-HAL: Could not start hal
,07-28 12:43:39.310   791  1149 E native  : do suspend true
,07-28 12:43:39.310   791  1148 D WifiP2pService: P2pDisabledState{ what=131203 }
07-28 12:43:39.310   791  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,07-28 12:43:39.310   791   791 D WifiScanningService: SCAN_AVAILABLE : 3
07-28 12:43:39.310   791   791 D RttService: SCAN_AVAILABLE : 3
07-28 12:43:39.310   791  1166 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:39.310   791  1166 I WifiNative-HAL: startHal
07-28 12:43:39.310   791  1166 E wifi    : getStaticLongField sWifiHalHandle 0x9af9699c
07-28 12:43:39.310   791  1166 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x5019b6
07-28 12:43:39.310   791  1166 I WifiNative-HAL: Could not start hal
07-28 12:43:39.310   791  1166 E WifiScanningService: could not start HAL
07-28 12:43:39.310   791  1167 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:43:39.310   299  1061 D CommandListener: Setting iface cfg
07-28 12:43:39.310   299  1061 D CommandListener: Trying to bring up p2p0
07-28 12:43:39.310   791  1148 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-28 12:43:39.310   791  1148 D WifiP2pService: P2pEnablingState
07-28 12:43:39.320   791  1148 D WifiP2pService: P2pEnablingState{ what=147457 }
07-28 12:43:39.320   791  1148 D WifiP2pService: P2p socket connection successful
,07-28 12:43:39.320   791  1148 D WifiP2pService: P2pEnabledState
07-28 12:43:39.320   791  1148 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-28 12:43:39.320   791   791 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
07-28 12:43:39.320   791  1149 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
07-28 12:43:39.320   791  1149 D WifiNative-HAL: callSECStringApiVoid - ID [215]
07-28 12:43:39.320   791  1149 E WifiNative-HAL: invaild command id : 215
07-28 12:43:39.320   791  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
07-28 12:43:39.320   791  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-28 12:43:39.320   791  1046 D WifiDisplayController: disconnect
07-28 12:43:39.320   791  1046 D WifiDisplayController: updateConnection
07-28 12:43:39.320   791  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-28 12:43:39.320   791  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-28 12:43:39.320  1193  1193 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,07-28 12:43:39.320   791  1679 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-28 12:43:39.320  1193  1193 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-28 12:43:39.320   791  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:39.320   791  1046 D WifiDisplayAdapter: onP2pDisconnected
07-28 12:43:39.320   791  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-28 12:43:39.320   791  1151 E ConnectivityService: updateNetworkInfo()
07-28 12:43:39.320   791  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
07-28 12:43:39.320   791  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,07-28 12:43:39.340   791  1358 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sconnect, hostingType: broadcast
,07-28 12:43:39.350   791  1358 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:39.350   791  1358 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:39.350   791  1358 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:39.350   791  1358 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:39.350  7813  7813 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-28 12:43:39.360   791  1148 D WifiNative-HAL: p2pGetDeviceAddress
,07-28 12:43:39.360   791  1148 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:de:28:a3
,07-28 12:43:39.370  7813  7813 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-28 12:43:39.380   791  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-28 12:43:39.380   791  1149 D SecContentProvider2: mCursor = null
,07-28 12:43:39.390  7984  7984 E Zygote  : MountEmulatedStorage()
07-28 12:43:39.390  7984  7984 E Zygote  : v2
07-28 12:43:39.390  7984  7984 I libpersona: KNOX_SDCARD checking this for 10158
07-28 12:43:39.390  7984  7984 I libpersona: KNOX_SDCARD not a persona
,07-28 12:43:39.400   791  1358 I ActivityManager: Start proc com.samsung.android.sconnect for broadcast com.samsung.android.sconnect/.periph.PeriphStartReceiver: pid=7984 uid=10158 gids={50158, 9997, 3002, 3001, 1028, 1015, 3003} abi=armeabi-v7a
,07-28 12:43:39.400   791  1148 D WifiP2pService: DeviceAddress: ea:28:a3
07-28 12:43:39.400   791  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
07-28 12:43:39.400   791  1046 D WifiDisplayController:  deviceAddress: ea:50:8b:de:28:a3
07-28 12:43:39.400   791  1046 D WifiDisplayController:  primary type: 10-0050F204-5
07-28 12:43:39.400   791  1046 D WifiDisplayController:  secondary type: null
07-28 12:43:39.400   791  1046 D WifiDisplayController:  wps: 0
07-28 12:43:39.400   791  1046 D WifiDisplayController:  grpcapab: 0
07-28 12:43:39.400   791  1046 D WifiDisplayController:  devcapab: 0
07-28 12:43:39.400   791  1046 D WifiDisplayController:  status: 3
07-28 12:43:39.400   791  1046 D WifiDisplayController:  wfdInfo: null
07-28 12:43:39.400   791  1046 D WifiDisplayController:  groupownerAddress: null
07-28 12:43:39.400   791  1046 D WifiDisplayController:  GOdeviceName: null
07-28 12:43:39.400   791  1046 D WifiDisplayController:  interfaceAddress: 
07-28 12:43:39.400   791  1046 D WifiDisplayController:  SConnectInfo : null
07-28 12:43:39.400   791  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:43:39.400   791  1149 D SecContentProvider2: mCursor = null
,07-28 12:43:39.410  7984  7984 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:43:39.410  7984  7984 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:43:39.410  7984  7984 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:43:39.420   791  1148 D WifiP2pService: sending p2p persistent groups changed broadcast
,07-28 12:43:39.420   791  1148 D WifiP2pService: InactiveState
07-28 12:43:39.420   791  1148 D WifiP2pService: InactiveState{ what=143376 }
,07-28 12:43:39.420   791  1148 D WifiP2pService: P2pEnabledState{ what=143376 }
07-28 12:43:39.420  7813  7813 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-28 12:43:39.420   791  1148 D WifiP2pService: InactiveState{ what=143376 }
,07-28 12:43:39.430   791  1148 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-28 12:43:39.430  7984  7984 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:43:39.430  7984  7984 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:39.440  7984  7984 D ResourcesManager: creating new AssetManager and set to /system/app/QuickConnect/QuickConnect.apk
,07-28 12:43:39.440  7984  7984 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,07-28 12:43:39.440  7984  7984 W ResourcesManager: Asset path '/system/framework/allshare.jar' does not exist or contains no resources.
07-28 12:43:39.440  7984  7984 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-28 12:43:39.450   791  3300 D SSRM:n  : SIOP:: AP = 410, PST = 382, CUR = 450
,07-28 12:43:39.450  7984  7984 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:39.450  7984  7984 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
,07-28 12:43:39.460  7984  7984 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,07-28 12:43:39.460   791  1144 D ActivityManager: startProcessLocked calleePkgName: com.android.email, hostingType: broadcast
07-28 12:43:39.460   791  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:39.460   791  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:39.460   791  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:39.460   791  1144 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:39.500  7999  7999 E Zygote  : MountEmulatedStorage()
07-28 12:43:39.500  7999  7999 E Zygote  : v2
07-28 12:43:39.500  7999  7999 I libpersona: KNOX_SDCARD checking this for 10186
07-28 12:43:39.500  7999  7999 I libpersona: KNOX_SDCARD not a persona
,07-28 12:43:39.510  7999  7999 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:43:39.510  7999  7999 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:43:39.510   791  1144 I ActivityManager: Start proc com.android.email for broadcast com.android.email/.EmailConnectivityManager: pid=7999 uid=10186 gids={50186, 9997, 3003, 1028, 1015, 1023, 3002, 3001, 1003} abi=armeabi-v7a
,07-28 12:43:39.510  7999  7999 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:43:39.510   791  1144 I ActivityManager: Killing 6976:com.samsung.android.app.filterinstaller/1000 (adj 15): emptyCount ##41
,07-28 12:43:39.530  7999  7999 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:43:39.530  7999  7999 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:39.550  7999  7999 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-28 12:43:39.550  7999  7999 W ResourcesManager: Asset path '/system/framework/secsmartcard.jar' does not exist or contains no resources.
,07-28 12:43:39.550  7999  7999 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:43:39.550  7999  7999 W ResourcesManager: Asset path '/system/framework/multiwindow.jar' does not exist or contains no resources.
,07-28 12:43:39.550  7999  7999 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-28 12:43:39.550  7999  7999 W ResourcesManager: Asset path '/system/framework/secvision.jar' does not exist or contains no resources.
,07-28 12:43:39.640   791  1679 D RCPManagerService: exchangeData() failure , invalid userId
,07-28 12:43:39.670   791  1574 D RCPManagerService: exchangeData() failure , invalid userId
,07-28 12:43:39.680   791   831 D RCPManagerService: exchangeData() failure , invalid userId
,07-28 12:43:39.720   791  1657 D ActivityManager: getContentProviderImpl callerProcessName:com.android.email, calleePkgName: com.sec.android.provider.badge
,07-28 12:43:39.720   791  1657 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:39.720   791  1657 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:39.720   791  1657 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:39.720   791  1657 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:39.730   791  1532 D RCPManagerService: exchangeData() failure , invalid userId
,07-28 12:43:39.760  8029  8029 E Zygote  : MountEmulatedStorage()
07-28 12:43:39.760  8029  8029 E Zygote  : v2
,07-28 12:43:39.760  8029  8029 I libpersona: KNOX_SDCARD checking this for 10092
07-28 12:43:39.760  8029  8029 I libpersona: KNOX_SDCARD not a persona
,07-28 12:43:39.770   791  1657 I ActivityManager: Start proc com.sec.android.provider.badge for content provider com.sec.android.provider.badge/.BadgeProvider: pid=8029 uid=10092 gids={50092, 9997} abi=armeabi-v7a
,07-28 12:43:39.770  8029  8029 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
,07-28 12:43:39.770  8029  8029 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:43:39.770  8029  8029 E SELinux : [DEBUG] get_category: variable seinfo: release sensitivity: NULL, cateogry: NULL
,07-28 12:43:39.780   791  1144 D RCPManagerService: exchangeData() failure , invalid userId
,07-28 12:43:39.800  8029  8029 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:43:39.800  8029  8029 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:39.810   791  1428 D RCPManagerService: exchangeData() failure , invalid userId
,07-28 12:43:39.810  8029  8029 D ResourcesManager: creating new AssetManager and set to /system/app/BadgeProvider/BadgeProvider.apk
07-28 12:43:39.810   791  1468 I ActivityManager: Killing 6997:com.samsung.android.app.watchmanagerstub/u0a126 (adj 15): emptyCount ##41
,07-28 12:43:39.810   791  1532 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:39.810  7514  7514 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:43:39.810  7514  7514 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:43:39.810  7514  7514 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:43:39.810  7514  7514 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:43:39.820   791  1469 I ActivityManager: Killing 7012:com.samsung.helphub/1000 (adj 15): emptyCount ##41
,07-28 12:43:39.820  8029  8029 D BadgeProvider: onCreate
,07-28 12:43:39.820   791  1358 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:39.820   791  1476 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:39.820   791  1469 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.service.travel, hostingType: broadcast
07-28 12:43:39.820  8029  8029 D BadgeProvider: DatabaseHelper
,07-28 12:43:39.820   791  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:39.820   791  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:39.820   791  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:39.820   791  1469 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:39.870  8049  8049 E Zygote  : MountEmulatedStorage()
07-28 12:43:39.870  8049  8049 E Zygote  : v2
07-28 12:43:39.870  8049  8049 I libpersona: KNOX_SDCARD checking this for 10200
07-28 12:43:39.870  8049  8049 I libpersona: KNOX_SDCARD not a persona
,07-28 12:43:39.880   791  1469 I ActivityManager: Start proc com.samsung.android.service.travel for broadcast com.samsung.android.service.travel/com.samsung.android.travel.bindService.TravelBroadcastReceiver: pid=8049 uid=10200 gids={50200, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:43:39.890  8049  8049 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:43:39.890  8049  8049 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:43:39.890  8049  8049 E SELinux : [DEBUG] get_category: variable seinfo: shared sensitivity: NULL, cateogry: NULL
,07-28 12:43:39.900  8029  8037 D BadgeProvider: query, [selection] : package='com.android.email' AND class='com.android.email.activity.Welcome' AND extraData='base_extra_badge'
,07-28 12:43:39.910  8029  8037 D BadgeProvider: sendNotify entered. [uri] : content://com.sec.badge/apps/1
07-28 12:43:39.910  8029  8037 D BadgeProvider: sendNotify, [notify] : null
,07-28 12:43:39.910  8029  8037 D BadgeProvider: update, [uri] : content://com.sec.badge/apps/1
07-28 12:43:39.910  8029  8037 D BadgeProvider: update, [BadgeCount] : badgecount=0
07-28 12:43:39.910  8029  8037 D BadgeProvider: update, [UpdateCount] : 1
,07-28 12:43:39.910  1441  1441 D Launcher.Model: reloadBadges entered.
,07-28 12:43:39.920  8049  8049 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:43:39.920  8049  8049 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:39.930  8049  8049 D ResourcesManager: creating new AssetManager and set to /system/app/TravelService_K/TravelService_K.apk
,07-28 12:43:39.950   791   831 I ActivityManager: Killing 7049:com.samsung.android.snote:provider/u0a168 (adj 15): emptyCount ##41
,07-28 12:43:39.950   791  1476 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-28 12:43:39.950   791  1476 D ActivityManager: caller:android.app.ApplicationThreadProxy@3bbd086e, r.packageName :com.google.android.gms
,07-28 12:43:39.950  4536  4536 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,07-28 12:43:39.950  4536  5525 I iu.UploadsManager: num queued entries: 0
,07-28 12:43:39.960  4536  5525 I iu.UploadsManager: num updated entries: 0
,07-28 12:43:39.960  4536  5525 I iu.SyncManager: NEXT; no task
,07-28 12:43:39.970  7031  7031 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-28 12:43:39.970   791  1259 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:39.970  7514  7514 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:43:39.970  7514  7514 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:43:39.970  7514  7514 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:43:39.970  7514  7514 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:43:39.980  7031  7031 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-28 12:43:39.980   791  1366 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:39.980  7514  7514 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:43:39.980  7514  7514 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:43:39.980  7514  7514 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:43:39.980  7514  7514 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:43:39.990  7676  7676 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-28 12:43:40.000  1313  1313 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-28 12:43:40.000  1313  1313 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-28 12:43:40.000   791   831 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:40.000  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-28 12:43:40.000   791  1358 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:40.000  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:43:40.000  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:43:40.000  1313  1313 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-28 12:43:40.000  1313  2966 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:43:40.010  7175  7175 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-28 12:43:40.010  7676  7676 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-28 12:43:40.010  7676  7676 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
07-28 12:43:40.010  7676  7676 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-28 12:43:40.010  7676  7676 D WifiDirectBR: stopServiceTest : false
,07-28 12:43:40.040   791  1428 W ActivityManager: Unable to start service Intent { cmp=com.android.email/.service.AttachmentDownloadService } U=0: not found
,07-28 12:43:40.060  7813  7813 I wpa_supplicant: nl80211: Received scan results (28 BSSes)
,07-28 12:43:40.070  7813  7813 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-28 12:43:40.070  7813  7813 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
07-28 12:43:40.070  7813  7813 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
07-28 12:43:40.070  7813  7813 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=5 BSSID=00.00.00 SSID=4E47373030
,07-28 12:43:40.080   791  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:43:40.080   791  1149 D SecContentProvider2: mCursor = null
,07-28 12:43:40.130  7813  7813 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
,07-28 12:43:40.130  7813  7813 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=6 BSSID=00.00.00 SSID=4E47373030
07-28 12:43:40.130  7813  7813 I wpa_supplicant: Associated with F4.99.3E
07-28 12:43:40.130  7813  7813 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
07-28 12:43:40.140  7813  7813 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=7 BSSID=F4.99.3E SSID=4E47373030
,07-28 12:43:40.140   791  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:43:40.140   791  1149 D SecContentProvider2: mCursor = null
,07-28 12:43:40.140   791  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:43:40.140   791  1149 D SecContentProvider2: mCursor = null
,07-28 12:43:40.150  7813  7813 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,07-28 12:43:40.150  7813  7813 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
07-28 12:43:40.150  7813  7813 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=8 BSSID=F4.99.3E SSID=4E47373030
,07-28 12:43:40.150  7813  7813 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:43:40.160  7813  7813 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
07-28 12:43:40.160  7813  7813 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=1 id_str=]
,07-28 12:43:40.160  7813  7813 I wpa_supplicant: Blacklist: Clear (temp) 
07-28 12:43:40.160  7813  7813 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=9 BSSID=F4.99.3E SSID=4E47373030
,07-28 12:43:40.160   791  1149 D WifiNative-HAL: callSECApiVoid - ID [50]
,07-28 12:43:40.160  1193  1193 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:43:40.160  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:43:40.160  1897  3184 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,07-28 12:43:40.160   791  1149 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,07-28 12:43:40.160   791  1151 D ConnectivityService: Got NetworkAgent Messenger
07-28 12:43:40.170   791  1151 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
07-28 12:43:40.170   791  1151 E ConnectivityService: updateNetworkInfo()
,07-28 12:43:40.170   791  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:43:40.170   791  1151 D ConnectivityService: NetworkAgent connected
07-28 12:43:40.170   791  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:43:40.170  1313  1313 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-28 12:43:40.170  1313  1313 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-28 12:43:40.170   791   831 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:40.170  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-28 12:43:40.170   791  1358 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:40.170  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:43:40.170  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:43:40.170  1313  1313 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:43:40.170  1313  2966 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:43:40.170   791   832 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:40.180  7031  7031 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:43:40.180   791  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:43:40.190   299  1061 D CommandListener: Setting iface cfg
,07-28 12:43:40.190   791  1149 E WifiStateMachine: Start Dhcp Watchdog 2
,07-28 12:43:40.200   791  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-28 12:43:40.200   791  1149 D SecContentProvider2: mCursor = null
,07-28 12:43:40.200  1193  1193 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:43:40.200  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:43:40.200   791  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,07-28 12:43:40.280   791  1149 E native  : do suspend false
,07-28 12:43:40.290   791  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:43:40.290   791  1149 D SecContentProvider2: mCursor = null
07-28 12:43:40.290   791  1148 D WifiP2pService: InactiveState{ what=143375 }
07-28 12:43:40.290   791  1148 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-28 12:43:40.450   791   997 W ProcessCpuTracker: Skipping unknown process pid 8064
,07-28 12:43:40.450   791   997 W ProcessCpuTracker: Skipping unknown process pid 8067
,07-28 12:43:40.510  8083  8083 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-28 12:43:40.520  8083  8083 I dhcpcd  : version 5.5.6 starting
,07-28 12:43:40.520  8083  8083 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-28 12:43:40.590  8083  8083 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-28 12:43:40.590  8083  8083 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
07-28 12:43:40.590  8083  8083 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
07-28 12:43:40.590  8083  8083 I dhcpcd  : bssid match
07-28 12:43:40.590  8083  8083 I dhcpcd  : wlan0: rebinding lease of 192.168.1.122
,07-28 12:43:40.610  8083  8083 I dhcpcd  : wlan0: acknowledged 192.168.1.122 from 192.168.1.1
,07-28 12:43:40.610  8083  8083 I dhcpcd  : wlan0: leased 192.168.1.122 for 172800 seconds
,07-28 12:43:40.620   791  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 503]; created=false
,07-28 12:43:40.700  7441  7508 I WifiManager: packageName : com.test.thalitest
,07-28 12:43:40.700   791   831 D SecContentProvider: uri = 18 selection = isWifiEnabled
,07-28 12:43:40.700   791   831 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-28 12:43:40.700   791   831 D SecContentProvider2: mCursor = null
,07-28 12:43:40.710   791   831 D WifiService: setWifiEnabled: false pid=7441, uid=10079
,07-28 12:43:40.710   791   831 D SettingsProvider: name = wifi_on
,07-28 12:43:40.710   791  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:43:40.750   791  1149 E native  : do suspend true
,07-28 12:43:40.780   791  1148 D WifiP2pService: InactiveState{ what=143375 }
,07-28 12:43:40.780   791  1148 D WifiP2pService: P2pEnabledState{ what=143375 }
,07-28 12:43:40.780   299  1061 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:43:40.780  1193  1193 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:43:40.790  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:43:40.830   791  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:43:40.830   791  1151 E ConnectivityService: updateNetworkInfo()
,07-28 12:43:40.830   791   791 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-28 12:43:40.830   791  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to DISCONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,07-28 12:43:40.830   791  1151 E ConnectivityService: updateNetworkInfo()
,07-28 12:43:40.830   791  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = DISCONNECTED
07-28 12:43:40.830   791  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 503] got DISCONNECTED, was satisfying 0
,07-28 12:43:40.830  1193  1193 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:43:40.830  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:43:40.830   299  1061 E Netd    : no such netId 503
07-28 12:43:40.840   791  1151 E ConnectivityService: Exception removing network: java.lang.IllegalStateException: command '77 network destroy 503' failed with '400 77 destroyNetwork() failed (Machine is not on the network)'
07-28 12:43:40.840   791  1151 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 503]
07-28 12:43:40.840   791  1151 D ConnectivityService: calling update connectivity
,07-28 12:43:40.840   791  1151 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
07-28 12:43:40.840   791  8071 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:40.840   791  8071 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Disconnected - quitting
07-28 12:43:40.840   791  1151 D CSLegacyTypeTracker: Removing agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{503}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,07-28 12:43:40.850  1313  1313 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-28 12:43:40.850   791  1149 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,07-28 12:43:40.860   791   791 D WifiScanningService: SCAN_AVAILABLE : 1
07-28 12:43:40.860   791   791 D RttService: SCAN_AVAILABLE : 1
07-28 12:43:40.860   791  1166 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:43:40.860   791  1148 D WifiP2pService: InactiveState{ what=131204 }
07-28 12:43:40.860   791  1167 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:43:40.860   791  1148 D WifiP2pService: P2pEnabledState{ what=131204 }
,07-28 12:43:40.860   791  1148 D WifiP2pService: sending p2p connection changed broadcast: FAILED
,07-28 12:43:40.860   791  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/FAILED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:40.860   791  1046 D WifiDisplayAdapter: onP2pDisconnected
07-28 12:43:40.860   791  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-28 12:43:40.860   791  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
07-28 12:43:40.860   791  1151 E ConnectivityService: updateNetworkInfo()
,07-28 12:43:40.860   791  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
,07-28 12:43:40.860   791   791 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
07-28 12:43:40.860   791  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=false
07-28 12:43:40.860   791  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
,07-28 12:43:40.860   791  1046 D WifiDisplayController: disconnect
07-28 12:43:40.860   791  1046 D WifiDisplayController: updateConnection
07-28 12:43:40.860   791  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-28 12:43:40.860   791  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-28 12:43:40.860   791  1148 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-28 12:43:40.870  1193  1193 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,07-28 12:43:40.870   791  1259 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=1, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-28 12:43:40.870  1193  1193 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
07-28 12:43:40.870   791  1148 D WifiP2pService: P2pDisablingState
,07-28 12:43:40.870   791  1148 D WifiP2pService: P2pDisablingState{ what=147458 }
07-28 12:43:40.870   791  1148 D WifiP2pService: p2p socket connection lost
07-28 12:43:40.870   791  1148 D WifiP2pService: P2pDisabledState
07-28 12:43:40.870   791  1151 E ConnectivityService: updateNetworkInfo()
07-28 12:43:40.870   791  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
07-28 12:43:40.870  1313  1313 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-28 12:43:40.870   791  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-28 12:43:40.870   791  1046 D WifiDisplayAdapter: onP2pDisconnected
07-28 12:43:40.870   791  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-28 12:43:40.870   791  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
07-28 12:43:40.870   791   832 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:40.870  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-28 12:43:40.870   791  1574 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-28 12:43:40.870  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:43:40.870  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:43:40.870  1313  1313 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:43:40.870  1313  2966 V NearbySettings: MountReceiver.mPrefHandler - 7002
07-28 12:43:40.870   791  1149 E native  : do suspend true
,07-28 12:43:40.880   791  1148 D WifiP2pService: P2pDisabledState{ what=143375 }
07-28 12:43:40.880   791  1148 D WifiP2pService: DefaultState{ what=143375 }
,07-28 12:43:40.880   791  1638 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:40.880  7031  7031 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:43:40.890   299  1061 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:43:40.890  1193  1193 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:43:40.890  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:43:40.890  7813  7813 I wpa_supplicant: p2p0: State: DISCONNECTED -> DISCONNECTED
,07-28 12:43:40.890   791   791 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-28 12:43:40.890  1193  1193 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:43:40.890  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:43:40.890   791   791 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:43:40.890   791  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:43:40.890   791  1149 D SecContentProvider2: mCursor = null
,07-28 12:43:40.890   791  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-28 12:43:40.890  1193  1193 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:43:40.890  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
07-28 12:43:40.890  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:40.890  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:40.890  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:40.890  1313  1313 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:40.890  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:40.890  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:40.890  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:40.890  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:40.890  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:40.890  1193  1193 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:40.890  1193  1193 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:40.890  1193  1193 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(0)
,07-28 12:43:40.890  1193  1595 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-28 12:43:40.900  1193  1193 D HotspotTile: onReceive : 0, 0
,07-28 12:43:40.900  7441  7441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:40.900  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:40.900  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:40.900  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:40.900  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:43:40.900  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:40.900  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:40.900  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:40.900  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:43:40.900  7441  7441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:40.900  7441  7441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:43:40.900  7441  7441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:40.900  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:40.900  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:40.900  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:40.900  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:43:40.900  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:40.900  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:40.900  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:40.900  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:43:40.900  7441  7441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:40.900  7441  7441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:43:40.900  1313  1313 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-28 12:43:40.900  1313  1313 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-28 12:43:40.900   791   832 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:40.900  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-28 12:43:40.900   791  1574 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-28 12:43:40.900  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:43:40.900  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:43:40.900  1313  1313 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:43:40.900  1313  2966 V NearbySettings: MountReceiver.mPrefHandler - 7002
07-28 12:43:40.910  7175  7175 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
07-28 12:43:40.910  7676  7676 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
07-28 12:43:40.910  7676  7676 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
07-28 12:43:40.910  7676  7676 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
07-28 12:43:40.910  7676  7676 D WifiDirectBR: stopServiceTest : false
07-28 12:43:40.910  7676  7676 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
07-28 12:43:40.920  1313  1313 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-28 12:43:40.920  1313  1313 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-28 12:43:40.920   791  1476 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:40.920  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-28 12:43:40.920   791  1358 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
07-28 12:43:40.920  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:43:40.920  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:43:40.920  1313  1313 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:43:40.920  1313  2966 V NearbySettings: MountReceiver.mPrefHandler - 7002
07-28 12:43:40.930   791  1574 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:40.930  7031  7031 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
07-28 12:43:40.930  7813  7813 I wpa_supplicant: Blacklist: Clear (all) 
,07-28 12:43:40.930  7031  7031 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
07-28 12:43:40.940   791  1532 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:40.940  7514  7514 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:43:40.940  7514  7514 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:43:40.940  7514  7514 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:43:40.940  7514  7514 D SecurityLogAgent: StateMachine : Changed Current State = 1
07-28 12:43:40.940  7813  7813 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
07-28 12:43:40.940  7813  7813 I wpa_supplicant: CTRL-EVENT-DISCONNECTED bssid=F4.99.3E reason=3 locally_generated=1
07-28 12:43:40.940  7813  7813 I wpa_supplicant: wlan0: State: COMPLETED -> DISCONNECTED
07-28 12:43:40.950  7813  7813 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=0 BSSID=F4.99.3E SSID=4E47373030
07-28 12:43:40.950  7813  7813 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-28 12:43:40.980  7813  7813 I wpa_supplicant: Blacklist: Clear (all) 
,07-28 12:43:41.100   791  1152 D Tethering: InitialState.processMessage what=4
,07-28 12:43:41.100   791  1152 E Tethering: No numeric data
,07-28 12:43:41.100   791  1152 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
07-28 12:43:41.100  7813  7813 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,07-28 12:43:41.100  1193  1193 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-28 12:43:41.100  1193  1193 D HotspotTile: updateTetherState():false, false
,07-28 12:43:41.100   791  1146 V NetworkStats: performPollLocked(flags=0x1)
,07-28 12:43:41.100   791  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:43:41.100   791  1146 D NetworkStatsFactory: UpdateStatsForKnox
,07-28 12:43:41.100   791  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:41.100   791  1146 V NetworkStats: performPollLocked() took 4ms
,07-28 12:43:41.100   791  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:43:41.110   791  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:43:41.110   791  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:43:41.200   791  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:0
07-28 12:43:41.200   791  1149 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-28 12:43:41.200   791   791 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:43:41.200  1193  1193 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:43:41.200  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,07-28 12:43:41.200  1193  1193 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:41.200  1897  2422 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:43:41.200  1193  1193 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(1)
07-28 12:43:41.200  1193  1193 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:41.210   791  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
,07-28 12:43:41.210  1193  1595 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-28 12:43:41.210  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:41.210  1313  1313 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:43:41.210  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:41.210  1193  1193 D HotspotTile: onReceive : 1, 0
07-28 12:43:41.210  7647  7647 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:43:41.210  7031  7031 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-28 12:43:41.210   791  1144 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:41.210  7514  7514 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:43:41.210  7514  7514 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:43:41.210  7514  7514 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:43:41.210  7514  7514 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:43:41.400   791  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:1
,07-28 12:43:41.540   791   832 I ActivityManager: Killing 7068:com.sec.kidsplat.installer/u0a189 (adj 15): emptyCount ##41
,07-28 12:43:41.970   791  1638 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-28 12:43:41.970   791  1638 D ActivityManager: caller:android.app.ApplicationThreadProxy@6a88cb8, r.packageName :com.google.android.music
,07-28 12:43:41.980   791  1469 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:43:41.980   791  1657 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:43:41.990   791  1259 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:43:41.990   791  1679 D ActivityManager: startService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music
,07-28 12:43:41.990   791  1679 D ActivityManager: caller:android.app.ApplicationThreadProxy@d955ce, r.packageName :com.google.android.music
,07-28 12:43:42.020  1897  1897 D WearableService: callingUid 10015, callindPid: 1897
,07-28 12:43:42.030   791   832 D ActivityManager: bindService callerProcessName:com.google.android.music, calleePkgName: com.google.android.music, action: null
,07-28 12:43:42.060  7716  7716 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,07-28 12:43:42.060  7716  8142 E GmsUtils: Failed to connect to Google API client: ConnectionResult{statusCode=unknown status code 16, resolution=null}
,07-28 12:43:42.120   304   304 E SMD     : DCD ON
,07-28 12:43:42.200   791  1259 I art     : Explicit concurrent mark sweep GC freed 67326(3MB) AllocSpace objects, 4(64KB) LOS objects, 30% free, 37MB/53MB, paused 1.194ms total 86.569ms
,07-28 12:43:42.220  7716  8137 I MusicLeanback: Conditions not met for autocaching.
07-28 12:43:42.220  7716  8137 I MusicLeanback: Stop autocaching.
,07-28 12:43:43.260   791  1116 V AlarmManager: waitForAlarm result :4
,07-28 12:43:43.260   791   791 V AlarmManager: ___SyncScheduler (v3) ACTIVATED___
,07-28 12:43:43.260   791   791 V AlarmManagerEXT: <AppSync3 Whitelist>
,07-28 12:43:43.270   791   791 V AlarmManagerEXT: (AppSync) ### 0 added ###
,07-28 12:43:43.270  1193  1193 D KeyguardUpdateMonitor: received broadcast android.intent.action.TIME_TICK
,07-28 12:43:43.270  1193  1193 D KeyguardUpdateMonitor: handleTimeUpdate
,07-28 12:43:43.270  1193  1193 D KeyguardEffectViewController: onReceive action : android.intent.action.TIME_TICK
,07-28 12:43:43.270  1193  1193 I KeyguardEffectViewController: *** don't update sliding image ***
,07-28 12:43:43.310   791  1532 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-28 12:43:43.320   791  1532 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4335, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-28 12:43:43.320   791  1532 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
,07-28 12:43:43.320   791  1532 D BatteryService: stay LED for fully charged
07-28 12:43:43.320   791   791 D BatteryService: Sending ACTION_BATTERY_CHANGED.
,07-28 12:43:43.320   791   791 I MotionRecognitionService: Plugged
,07-28 12:43:43.320   791   791 I MotionRecognitionService: setPowerConnected  = true
,07-28 12:43:43.330  1193  1193 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
,07-28 12:43:43.330  1193  1193 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
,07-28 12:43:43.330  1193  1193 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-28 12:43:43.330  1193  1193 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:43:43.330  1193  1193 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:43:43.330  1193  1193 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-28 12:43:43.340  1193  1193 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-28 12:43:43.340  1193  1193 D DateView: regionalDateFormat = 11/22/3333 isRTLlanguage = false returnDateFormat = E, MMMM d
,07-28 12:43:43.720  7441  7508 D BluetoothAdapter: enable()
,07-28 12:43:43.720   791   832 W ActivityManager: Permission Denial: getCurrentUser() from pid=7441, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,07-28 12:43:43.730   791   832 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-28 12:43:43.730   791   832 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7441, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-28 12:43:43.730   791   832 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-28 12:43:43.730   791   832 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
07-28 12:43:43.730   791   832 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
07-28 12:43:43.730   791   832 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-28 12:43:43.730   791   832 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,07-28 12:43:43.730   791   832 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:43:43.730   791   832 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:43:43.730   791   832 D SettingsProvider: name = bluetooth_on
,07-28 12:43:43.750   791  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:43:43.750   791  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:43:43.750   791  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,07-28 12:43:43.790  7696  7696 D BluetoothAdapterState: make
,07-28 12:43:43.790  7696  7696 I bluedroid: init
,07-28 12:43:43.790  7696  8163 I BluetoothAdapterState: Entering OffState
,07-28 12:43:43.790  7696  7696 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-28 12:43:43.800  7696  7696 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-28 12:43:43.800  7696  7696 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,07-28 12:43:43.800  7696  7696 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,07-28 12:43:43.800  7696  7696 E bt-btif : btif_fetch_local_ble_random_bdaddr
07-28 12:43:43.800  7696  7696 I bluedroid: get_profile_interface socket
07-28 12:43:43.800  7696  7696 I bluedroid: get_profile_interface map_client
,07-28 12:43:43.800  7696  7696 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,07-28 12:43:43.800  7696  8166 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,07-28 12:43:43.810  7696  8166 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
,07-28 12:43:43.810   791  1366 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-28 12:43:43.810  7696  7706 I bluedroid: config_hci_snoop_log
,07-28 12:43:43.810   791  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 14 receivers.
,07-28 12:43:43.820   791  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:43:43.820   791  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:43:43.820   791  1043 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,07-28 12:43:43.820  7696  8163 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
,07-28 12:43:43.820  7696  8166 E BluetoothServiceJni: populateRssiValuesNative
07-28 12:43:43.820  7696  8166 I bluedroid: getModelRssiValues
,07-28 12:43:43.820  7696  8166 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
07-28 12:43:43.820  7696  8166 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-28 12:43:43.820   791   791 D SettingsProvider: name = bluetooth_name
,07-28 12:43:43.820  7696  8166 D BluetoothAdapterProperties: Name is: Note3-1
,07-28 12:43:43.820  7696  8163 D BluetoothAdapterProperties: Setting state to 11
07-28 12:43:43.820  7696  8163 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,07-28 12:43:43.820  7696  8163 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-28 12:43:43.820  7696  8163 D BluetoothAdapterService: updateAdapterState state is 11
,07-28 12:43:43.830   791   791 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:43.830  1865  1865 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-28 12:43:43.830   791   791 I InputMethodManagerService: [BT Setting State] State =11
,07-28 12:43:43.830  1193  1193 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-28 12:43:43.830  1193  1193 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:43.840  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:43.840  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:43.840   791  1259 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:43:43.840  1193  1595 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-28 12:43:43.840   791   832 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-28 12:43:43.840  1193  1193 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-28 12:43:43.840  1313  1313 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:43.840   791  1476 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-28 12:43:43.840   791  1476 D ActivityManager: caller:android.app.ApplicationThreadProxy@196f3cc4, r.packageName :com.google.android.gms
,07-28 12:43:43.850  7624  7624 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:43.850  7696  8163 D BluetoothAdapterService: Autoconnection is available 
07-28 12:43:43.850  7696  8163 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,07-28 12:43:43.850  7696  8163 D BluetoothSecureManager: getInstant: null
,07-28 12:43:43.850  7696  8163 D BluetoothSecureManager: calling getMethod for getService
,07-28 12:43:43.860  7696  8163 D BluetoothSecureManager: calling getService
,07-28 12:43:43.860  7696  8163 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@2085e2d9
,07-28 12:43:43.860   791  1679 D BluetoothSecureManagerService: isSecureModeEnabled
07-28 12:43:43.860   791  1679 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
,07-28 12:43:43.860  7696  8163 D BtConfig.SecureMode: isSecureModeOn:false
07-28 12:43:43.860  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-28 12:43:43.860  7696  8163 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
,07-28 12:43:43.860  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-28 12:43:43.860  7696  8163 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
,07-28 12:43:43.860  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-28 12:43:43.860  7696  8163 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
,07-28 12:43:43.860  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-28 12:43:43.860  7696  8163 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
,07-28 12:43:43.860  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-28 12:43:43.860  7696  8163 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
,07-28 12:43:43.860  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-28 12:43:43.860  7696  8163 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,07-28 12:43:43.860  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
,07-28 12:43:43.860  7696  8163 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,07-28 12:43:43.860  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
,07-28 12:43:43.870  7696  8163 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
,07-28 12:43:43.870  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-28 12:43:43.870  7696  8163 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,07-28 12:43:43.870  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:43:43.870  7696  8163 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
,07-28 12:43:43.870  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,07-28 12:43:43.870  7696  8163 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
07-28 12:43:43.870  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-28 12:43:43.870  7696  8163 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
07-28 12:43:43.870  1313  1313 D BluetoothNotiBroadcastReceiver: onReceive
,07-28 12:43:43.880   791  1574 D ActivityManager: bindService callerProcessName:com.google.android.apps.magazines, calleePkgName: com.google.android.gms, action: com.google.android.gms.analytics.service.START
,07-28 12:43:43.880  7696  8163 D BluetoothBondStateMachine: make
,07-28 12:43:43.880  7914  7933 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,07-28 12:43:43.890  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
07-28 12:43:43.890  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-28 12:43:43.890  7696  8163 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,07-28 12:43:43.890   791  1638 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:43:43.890  7696  8177 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-28 12:43:43.890   791  1638 D ActivityManager: caller:android.app.ApplicationThreadProxy@1a856130, r.packageName :com.android.bluetooth
,07-28 12:43:43.890  7696  7696 I BtGatt.JNI: classInitNative(L890): classInitNative: Success!
,07-28 12:43:43.890  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
07-28 12:43:43.900  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-28 12:43:43.900  7696  8163 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,07-28 12:43:43.900   791  1366 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:43:43.900   791  1366 D ActivityManager: caller:android.app.ApplicationThreadProxy@1167d32e, r.packageName :com.android.bluetooth
,07-28 12:43:43.900  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,07-28 12:43:43.900  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-28 12:43:43.900  7696  8163 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
07-28 12:43:43.900   791  1469 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:43:43.900   791  1469 D ActivityManager: caller:android.app.ApplicationThreadProxy@2b97605c, r.packageName :com.android.bluetooth
,07-28 12:43:43.900  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,07-28 12:43:43.900  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-28 12:43:43.900  7696  8163 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-28 12:43:43.900   791  1657 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:43:43.900   791  1657 D ActivityManager: caller:android.app.ApplicationThreadProxy@3721f43a, r.packageName :com.android.bluetooth
,07-28 12:43:43.900  7696  7696 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 12:43:43.900  7696  7696 D BtGatt.GattService: Received start request. Starting profile...
07-28 12:43:43.900  7696  7696 D BtGatt.GattService: start()
,07-28 12:43:43.900  7696  7696 I bluedroid: get_profile_interface gatt
07-28 12:43:43.900  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
07-28 12:43:43.900  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-28 12:43:43.900  7696  8163 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,07-28 12:43:43.900  7696  7696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@360e7108
07-28 12:43:43.900  7696  7696 D BtGatt.AdvertiseManager: advertise manager created
07-28 12:43:43.900   791  1358 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:43:43.900   791  1358 D ActivityManager: caller:android.app.ApplicationThreadProxy@1e682648, r.packageName :com.android.bluetooth
,07-28 12:43:43.910  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
07-28 12:43:43.910  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-28 12:43:43.910  7696  8163 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-28 12:43:43.910   791   832 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:43:43.910   791   832 D ActivityManager: caller:android.app.ApplicationThreadProxy@3d2b1a06, r.packageName :com.android.bluetooth
,07-28 12:43:43.910  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,07-28 12:43:43.910  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:43:43.910  7696  8163 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,07-28 12:43:43.910   791  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:43:43.910   791  1476 D ActivityManager: caller:android.app.ApplicationThreadProxy@1bfd5ef4, r.packageName :com.android.bluetooth
,07-28 12:43:43.910  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
07-28 12:43:43.910  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-28 12:43:43.910  7696  8163 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,07-28 12:43:43.910   791  1144 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:43:43.910   791  1144 D ActivityManager: caller:android.app.ApplicationThreadProxy@2f32d719, r.packageName :com.android.bluetooth
,07-28 12:43:43.910  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:43:43.910  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-28 12:43:43.910  7696  8163 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,07-28 12:43:43.920  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:43:43.920  7696  7696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@360e7108
,07-28 12:43:43.920  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,07-28 12:43:43.920  7696  8163 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,07-28 12:43:43.920  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
07-28 12:43:43.920  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
,07-28 12:43:43.920  7696  8163 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
,07-28 12:43:43.920  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,07-28 12:43:43.920  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
,07-28 12:43:43.920  7696  8163 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,07-28 12:43:43.920  7696  8163 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
07-28 12:43:43.920  7696  7696 D HeadsetService: Received start request. Starting profile...
,07-28 12:43:43.930  7696  7696 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 12:43:43.930  7696  7696 D HeadsetStateMachine: make
,07-28 12:43:43.930  1897  1897 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-28 12:43:43.930  7696  7696 E HeadsetStateMachine: # of Max HF connection is 2
,07-28 12:43:43.940  1897  1897 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-28 12:43:43.940   791  1468 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,07-28 12:43:43.940   791  1428 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
,07-28 12:43:43.940  7696  7696 I bluedroid: get_profile_interface handsfree
,07-28 12:43:43.950  7696  7696 I DualScoManager: Instantiating Dual Sco Manager
07-28 12:43:43.950  7696  7696 I DualScoManager: Set HeadsetServiceHelper
,07-28 12:43:43.950  7696  7696 D BluetoothAtMessage: createCMTIContentObservers
,07-28 12:43:43.950   791  1358 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
07-28 12:43:43.950   791  1358 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:43.950   791  1358 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:43.950   791  1358 D SettingsProvider: selectionArgs: false
07-28 12:43:43.950   791  1358 D SettingsProvider: selectionArgs: 1002
07-28 12:43:43.950   791  1358 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:43:43.950   791  1358 D SettingsProvider: ret = -1
,07-28 12:43:43.950  7696  8190 D HeadsetStateMachine: Enter Disconnected: -2
,07-28 12:43:43.950  7696  7696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@360e7108
,07-28 12:43:43.950  7696  8190 E HeadsetStateMachine: set to mRemoteBrsf = 0
,07-28 12:43:43.950  7696  7696 D A2dpService: Received start request. Starting profile...
,07-28 12:43:43.960  7696  8190 D HeadsetStateMachine: map size, before remove : 0
07-28 12:43:43.960  7696  8190 D HeadsetStateMachine: map size, after remove: 0
,07-28 12:43:43.960  7696  8190 D HeadsetStateMachine: mNextConnectingDevice : null
,07-28 12:43:43.960  7696  7696 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-28 12:43:43.960  7696  7696 V Avrcp   : make
,07-28 12:43:43.960  7696  7696 V Avrcp   : Avrcp
,07-28 12:43:43.960  7696  7696 I bluedroid: get_profile_interface avrcp
,07-28 12:43:43.960  7696  7696 V Avrcp   : start
,07-28 12:43:43.970  7696  7696 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-28 12:43:43.970  7696  7696 V Avrcp   : ++registerMediaPlayers++
,07-28 12:43:43.970  7696  7696 I Avrcp   : No of Audio players :: 2
,07-28 12:43:43.970  7696  7696 I Avrcp   : App Package name is com.google.android.music
,07-28 12:43:43.970  7696  7696 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-28 12:43:43.980  7696  7696 I Avrcp   : App pkg name is Google Play Music
,07-28 12:43:43.980  7696  7696 I Avrcp   : Name::Google Play Music
,07-28 12:43:43.980  7696  7696 V Avrcp   : MediaPlayerInfo: mPlayerId=1
07-28 12:43:43.980  7696  7696 I Avrcp   : App Package name is com.sec.android.app.music
,07-28 12:43:43.980  7696  7696 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,07-28 12:43:43.980  7696  7696 I Avrcp   : App pkg name is Music
,07-28 12:43:43.980  7696  7696 I Avrcp   : Name::Music
07-28 12:43:43.980  7696  7696 V Avrcp   : MediaPlayerInfo: mPlayerId=2
07-28 12:43:43.980  7696  7696 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,07-28 12:43:43.980  7696  7696 I Avrcp   : No of Video players :: 1
07-28 12:43:43.980  7696  7696 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
,07-28 12:43:43.980  7696  7696 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,07-28 12:43:43.980  7696  7696 I Avrcp   : Video App pkg name is Video Player
,07-28 12:43:43.980  7696  7696 I Avrcp   : Name::Video Player
07-28 12:43:43.980  7696  7696 V Avrcp   : MediaPlayerInfo: mPlayerId=3
07-28 12:43:43.980  7696  7696 I Avrcp   : Add tempPlayer
07-28 12:43:43.980  7696  7696 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-28 12:43:43.980  7696  7696 I Avrcp   : Total no of players: 4
07-28 12:43:43.980  7696  7696 V Avrcp   : swapping the samsung player with 1st player
07-28 12:43:43.980  7696  7696 I Avrcp   :  Updating now playing list upon AVRCP Start
,07-28 12:43:43.980  7696  8194 V Avrcp   : handleMessage, msg=207
,07-28 12:43:43.980  7696  8194 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,07-28 12:43:43.990  7696  7696 I BluetoothA2dpServiceJni: classInitNative: succeeds
07-28 12:43:43.990  7696  7696 D A2dpStateMachine: make
,07-28 12:43:43.990  7696  7696 I bluedroid: get_profile_interface a2dp
,07-28 12:43:43.990  7696  8196 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-28 12:43:43.990  7696  7696 E bt-btif : warning : media task started media_task_refcnt 1 
,07-28 12:43:43.990  7696  7696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@360e7108
07-28 12:43:43.990  7696  8195 D A2dpStateMachine: Enter Disconnected: -2
,07-28 12:43:43.990  7696  7696 I BluetoothHidServiceJni: classInitNative: succeeds
,07-28 12:43:43.990  7696  7696 D HidService: Received start request. Starting profile...
07-28 12:43:43.990  7696  7696 I bluedroid: get_profile_interface hidhost
,07-28 12:43:43.990  7696  7696 D HidService: setHidService(): set to: null
07-28 12:43:43.990  7696  7696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@360e7108
07-28 12:43:43.990  7696  8194 D BluetoothMediaBrowser: no now playing list
07-28 12:43:43.990  7696  8194 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
,07-28 12:43:43.990  7696  7696 I BluetoothHealthServiceJni: classInitNative: succeeds
07-28 12:43:43.990  7696  8194 D Avrcp   :  checkNowPlayingList start
,07-28 12:43:44.000  7696  7696 D HealthService: Received start request. Starting profile...
,07-28 12:43:44.000  7696  7696 I bluedroid: get_profile_interface health
07-28 12:43:44.000  7696  7696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@360e7108
,07-28 12:43:44.000  7696  7696 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-28 12:43:44.000  7696  7696 D PanService: Received start request. Starting profile...
07-28 12:43:44.000  7696  7696 D BluetoothPanServiceJni: initializeNative(L110): pan
07-28 12:43:44.000  7696  7696 I bluedroid: get_profile_interface pan
,07-28 12:43:44.000  7696  7696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@360e7108
,07-28 12:43:44.000  7696  7696 D BluetoothMapService: Received start request. Starting profile...
,07-28 12:43:44.030  7696  7696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@360e7108
,07-28 12:43:44.030  7696  7696 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
,07-28 12:43:44.040  7696  7696 D SapService: Received start request. Starting profile...
07-28 12:43:44.040  7696  7696 D BluetoothSAPServiceJni: initializeNative(L209): sap
07-28 12:43:44.040  7696  7696 I bluedroid: get_profile_interface sap
07-28 12:43:44.040  7696  7696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@360e7108
,07-28 12:43:44.040  7696  7696 E BluetoothAdapterService(906916104): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
07-28 12:43:44.040  7696  7696 D HeadsetStateMachine: Try to query the phonestate on bind
,07-28 12:43:44.040  1404  1419 I Telecom : BluetoothPhoneService: queryPhoneState
,07-28 12:43:44.040  1404  1404 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,07-28 12:43:44.040  7696  7696 D HeadsetStateMachine: Proxy object connected
,07-28 12:43:44.040  7696  7696 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,07-28 12:43:44.040  7696  7696 D HeadsetPhoneState: sendDeviceDataStateChanged
07-28 12:43:44.040  7696  8190 D HeadsetStateMachine: Disconnected process message: 11
07-28 12:43:44.040  7696  8190 D HeadsetStateMachine: Disconnected process message: 18
07-28 12:43:44.040  7696  7696 D HeadsetPhoneState: Signal level : previous=0 curr=0
,07-28 12:43:44.040  7696  7696 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-28 12:43:44.040  7696  8190 D HeadsetStateMachine: Disconnected process message: 10
07-28 12:43:44.040  7696  7696 E BluetoothAdapterService(906916104): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
07-28 12:43:44.040  7696  8190 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-28 12:43:44.040  7696  8190 D HeadsetStateMachine: Disconnected process message: 11
07-28 12:43:44.040  7696  7696 D BluetoothA2dp: Proxy object connected
07-28 12:43:44.040  7696  7696 D BluetoothAdapterService: Bluetooth A2dp source service connected
07-28 12:43:44.040  7696  7696 E BluetoothAdapterService(906916104): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
,07-28 12:43:44.040  7696  7696 E BluetoothAdapterService(906916104): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
07-28 12:43:44.040  7696  7696 E BluetoothAdapterService(906916104): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
07-28 12:43:44.040  7696  7696 E BluetoothAdapterService(906916104): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,07-28 12:43:44.050  7696  7696 E BluetoothAdapterService(906916104): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
07-28 12:43:44.050  7696  7696 E BluetoothAdapterService(906916104): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
,07-28 12:43:44.050  7696  8163 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
,07-28 12:43:44.050  7696  8163 I bluedroid: enable
07-28 12:43:44.050  7696  8200 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
,07-28 12:43:44.050  7696  8163 I bt_hci_bdroid: init
,07-28 12:43:44.050  7696  8163 I bt_vendor: init
07-28 12:43:44.050  7696  8163 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-28 12:43:44.050  7696  8163 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
07-28 12:43:44.050  7696  8163 D bt_userial: userial_init
07-28 12:43:44.050  7696  8163 D bt_vendor: op for 5
,07-28 12:43:44.050  7696  8163 D bt_vendor: op for 0
,07-28 12:43:44.050  7696  8163 D bt_upio : upio_set_bluetooth_power(on: 0)
07-28 12:43:44.050  7696  8163 D bt_upio : is_emulator_context : 0
07-28 12:43:44.050  7696  8163 D bt_upio : is_rfkill_disabled ? [0]
07-28 12:43:44.050  7696  8163 D bt_upio : is_rfkill_disabled ? [0]
,07-28 12:43:44.050  7696  8163 D bt_vendor: op for 0
07-28 12:43:44.050  7696  8163 D bt_upio : upio_set_bluetooth_power(on: 1)
07-28 12:43:44.050  7696  8163 D bt_upio : is_emulator_context : 0
07-28 12:43:44.050  7696  8163 D bt_upio : is_rfkill_disabled ? [0]
,07-28 12:43:44.050  7696  8202 D bt_vendor: op for 3
07-28 12:43:44.050  7696  8202 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-28 12:43:44.060  7696  8202 I bt_userial_vendor: userial_vendor_open():UART is setup
07-28 12:43:44.060  7696  8202 I bt_userial_vendor: device fd = 66 open
,07-28 12:43:44.060  7696  8202 D bt_vendor: op for 1
07-28 12:43:44.060  7696  8203 D bt_userial: Entering userial_read_thread()
07-28 12:43:44.060  7696  8202 E bt_hwcfg: Start CFG HW, HCI reset
,07-28 12:43:44.130  7696  8202 E bt_hwcfg: Read Local Name after HCI reset
,07-28 12:43:44.160  7696  8202 D bt_hwcfg: Chipset BCM4335C0
,07-28 12:43:44.160  7696  8202 D bt_hwcfg: Target name = [BCM4335C0]
,07-28 12:43:44.160  7696  8202 I bt_hwcfg: module_type[semco].
07-28 12:43:44.160  7696  8202 I bt_hwcfg: not ZERO...
07-28 12:43:44.160  7696  8202 I bt_hwcfg: module_type[semco] is invalid.
,07-28 12:43:44.160  7696  8202 E bt_hwcfg: patchram path ORG . BCM4335C0
07-28 12:43:44.160  7696  8202 E bt_hwcfg: patchram path ORG .. BCM4335C0
07-28 12:43:44.160  7696  8202 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
07-28 12:43:44.160  7696  8202 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
07-28 12:43:44.160  7696  8202 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
07-28 12:43:44.160  7696  8202 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
,07-28 12:43:44.160  7696  8202 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335C0
07-28 12:43:44.160  7696  8202 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559_wisol.hcd BCM4335C0
07-28 12:43:44.160  7696  8202 E bt_hwcfg: fw ver (org)0.0
07-28 12:43:44.160  7696  8202 E bt_hwcfg: vendor lib preload failed to locate firmware patch file
07-28 12:43:44.160  7696  8202 E bt_hwcfg: Remove module rev, try again BCM4335
07-28 12:43:44.160  7696  8202 D bt_hwcfg: Target name = [BCM4335]
07-28 12:43:44.160  7696  8202 I bt_hwcfg: module_type[semco].
07-28 12:43:44.160  7696  8202 I bt_hwcfg: not ZERO...
07-28 12:43:44.160  7696  8202 I bt_hwcfg: module_type[semco] is invalid.
,07-28 12:43:44.160  7696  8202 E bt_hwcfg: patchram path ORG . BCM4335
07-28 12:43:44.160  7696  8202 E bt_hwcfg: patchram path ORG .. BCM4335
07-28 12:43:44.160  7696  8202 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335
07-28 12:43:44.160  7696  8202 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
07-28 12:43:44.160  7696  8202 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335
07-28 12:43:44.160  7696  8202 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
07-28 12:43:44.160  7696  8202 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335
07-28 12:43:44.160  7696  8202 I bt_hwcfg: patch(org) : bcm4335_V0111.0559.hcd
,07-28 12:43:44.160  7696  8202 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4335_V0111.0559.hcd
07-28 12:43:44.160  7696  8202 E bt_hwcfg: ORG patchram base 0111
07-28 12:43:44.160  7696  8202 E bt_hwcfg: ORG patchram minor 0559
07-28 12:43:44.160  7696  8202 E bt_hwcfg: fw ver (org)111.559
07-28 12:43:44.160  7696  8202 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4335_V0111.0559.hcd
,07-28 12:43:44.180  7696  8202 I bt_hwcfg: Axi patch failure or not include AXI patching
,07-28 12:43:44.190  7696  8202 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-28 12:43:44.640  7696  8202 I bt_hwcfg: bt vendor lib: set UART baud 115200,
,07-28 12:43:44.650  7696  8202 I bt_hwcfg: FW Download delta = 512443
,07-28 12:43:44.650  7696  8202 D bt_hwcfg: Settlement delay -- 100 ms
07-28 12:43:44.650  7696  8202 I bt_hwcfg: Setting fw settlement delay to 100 
,07-28 12:43:44.750  7696  8202 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-28 12:43:44.790  7696  8202 I bt_hwcfg: vendor lib fwcfg completed
,07-28 12:43:44.800  7696  8200 I         : BTE_InitTraceLevels -- TRC_HCI
,07-28 12:43:44.800  7696  8200 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-28 12:43:44.800  7696  8200 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-28 12:43:44.800  7696  8200 I         : BTE_InitTraceLevels -- TRC_AVDT
07-28 12:43:44.800  7696  8200 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-28 12:43:44.800  7696  8200 I         : BTE_InitTraceLevels -- TRC_A2D
07-28 12:43:44.800  7696  8200 I         : BTE_InitTraceLevels -- TRC_BNEP
07-28 12:43:44.800  7696  8200 I         : BTE_InitTraceLevels -- TRC_BTM
07-28 12:43:44.800  7696  8200 I         : BTE_InitTraceLevels -- TRC_GAP
,07-28 12:43:44.800  7696  8200 I         : BTE_InitTraceLevels -- TRC_PAN
07-28 12:43:44.800  7696  8200 I         : BTE_InitTraceLevels -- TRC_SAP
07-28 12:43:44.800  7696  8200 I         : BTE_InitTraceLevels -- TRC_SDP
07-28 12:43:44.800  7696  8200 I         : BTE_InitTraceLevels -- TRC_GATT
,07-28 12:43:44.800  7696  8200 I         : BTE_InitTraceLevels -- TRC_SMP
,07-28 12:43:44.800  7696  8200 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-28 12:43:44.800  7696  8200 I         : BTE_InitTraceLevels -- TRC_BTIF
07-28 12:43:44.800  7696  8200 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,07-28 12:43:45.040  7696  8200 W bt-l2cap: l2c_link_processs_ble_num_bufs 15
,07-28 12:43:45.040  7696  8200 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa1a64b5d 
,07-28 12:43:45.040  7696  8200 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa1a64b5d 
,07-28 12:43:45.120   304   304 E SMD     : DCD ON
,07-28 12:43:45.260  7696  8166 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 1 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
,07-28 12:43:45.260  7696  8166 E bt-btif : Calling BTA_HhEnable
,07-28 12:43:45.260  7696  8166 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
,07-28 12:43:45.260  7696  8166 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
,07-28 12:43:45.260  7696  8166 E BluetoothServiceJni: populateRssiValuesNative
07-28 12:43:45.260  7696  8166 I bluedroid: getModelRssiValues
07-28 12:43:45.260  7696  8166 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,07-28 12:43:45.270  7696  8166 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-28 12:43:45.270  7696  8166 D BluetoothAdapterProperties: Name is: Note3-1
,07-28 12:43:45.270  7696  8166 D BluetoothAdapterProperties: Scan Mode:20
,07-28 12:43:45.270  7696  8166 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-28 12:43:45.270   791   791 D SettingsProvider: name = bluetooth_name
,07-28 12:43:45.270  7696  8166 D BluetoothAdapterProperties: LE Address is:E0:B7:20:3E:93:BC
,07-28 12:43:45.270  7696  8202 D bt_vendor: op for 2
07-28 12:43:45.270  7696  8202 D bt_vendor: op for 6
,07-28 12:43:45.270  7696  8166 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
07-28 12:43:45.270  7696  8166 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,07-28 12:43:45.270  7696  8202 D bt_vendor: op for 7
,07-28 12:43:45.280  7696  8202 D bt_upio : proc btwrite assertion
,07-28 12:43:45.280  7696  8166 E bt-btif : btif_sock_init: !radio_req && !rfc_init
07-28 12:43:45.280  7696  8202 D bt_vendor: op for 7
,07-28 12:43:45.280  7696  8202 D bt_upio : BT_WAKE is asserted already
07-28 12:43:45.280  7696  8166 E bt-btif : btif_sock_init: !vhci_init
,07-28 12:43:45.280  7696  8202 D bt_vendor: op for 7
07-28 12:43:45.280  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:45.280  7696  8166 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
07-28 12:43:45.280  7696  8166 D IOP_DB_BT: db_open: db_open : handle 3037822992l, read 14063 bytes onto local cache
07-28 12:43:45.280  7696  8166 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
,07-28 12:43:45.280  7696  8166 D IOP_DB_BT: db_query: result 1
07-28 12:43:45.280  7696  8166 I         : iop_db_open: iop_db_open status 0
,07-28 12:43:45.280  7696  8166 D bte_conf: Device ID record 1 : primary
07-28 12:43:45.280  7696  8166 D bte_conf:   vendorId            = 0075
,07-28 12:43:45.280  7696  8166 D bte_conf:   vendorIdSource      = 0001
07-28 12:43:45.280  7696  8166 D bte_conf:   product             = 0100
07-28 12:43:45.280  7696  8166 D bte_conf:   version             = 0200
07-28 12:43:45.280  7696  8166 D bte_conf:   clientExecutableURL = 
07-28 12:43:45.280  7696  8166 D bte_conf:   serviceDescription  = 
,07-28 12:43:45.280  7696  8166 D bte_conf:   documentationURL    = 
07-28 12:43:45.280  7696  8166 D bte_conf: bte_load_did_conf no section named DID2.
,07-28 12:43:45.280  7696  8163 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
07-28 12:43:45.280  7696  8163 D BluetoothAdapterProperties: ScanMode =  20
,07-28 12:43:45.280  7696  8163 D BluetoothAdapterProperties: State =  11
,07-28 12:43:45.280  7696  8166 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-28 12:43:45.280   791  1679 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
07-28 12:43:45.280  7696  8163 D BluetoothAdapterProperties: Setting state to 12
,07-28 12:43:45.280  7696  8163 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-28 12:43:45.290   791  1574 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,07-28 12:43:45.290   791  1574 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:45.290   791  1574 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:45.290   791  1574 D SettingsProvider: selectionArgs: false
07-28 12:43:45.290   791  1574 D SettingsProvider: selectionArgs: 1002
,07-28 12:43:45.290   791  1574 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:43:45.290   791  1574 D SettingsProvider: ret = -1
07-28 12:43:45.290  7696  8163 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,07-28 12:43:45.290  7696  8163 D BluetoothAdapterService: updateAdapterState state is 12
,07-28 12:43:45.290   791  1443 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:43:45.290   791  1443 D ActivityManager: caller:android.app.ApplicationThreadProxy@308ab889, r.packageName :com.android.bluetooth
,07-28 12:43:45.290  7696  8163 D BluetoothAdapterService: Autoconnection is available 
,07-28 12:43:45.290  7696  8163 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-28 12:43:45.290  7696  8163 D BluetoothAdapterService: starting service from this receiver
,07-28 12:43:45.300   791  1638 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:43:45.300   791  1638 D ActivityManager: caller:android.app.ApplicationThreadProxy@87630af, r.packageName :com.android.bluetooth
,07-28 12:43:45.300  7696  8163 I BluetoothAdapterState: Entering On State from state = 11
,07-28 12:43:45.300  7696  8202 D bt_vendor: op for 7
,07-28 12:43:45.300  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:45.300  7696  8202 E bt_h4   : vendor lib postload completed
07-28 12:43:45.300  7696  8202 D bt_vendor: op for 7
07-28 12:43:45.300  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:45.300  7696  8202 D bt_vendor: op for 7
,07-28 12:43:45.300  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:45.300  7696  8202 D bt_vendor: op for 7
,07-28 12:43:45.310  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:45.310  7696  8202 D bt_vendor: op for 7
,07-28 12:43:45.310  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:45.310  7696  8202 D bt_vendor: op for 7
07-28 12:43:45.310  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:45.310  7696  8202 D bt_vendor: op for 7
,07-28 12:43:45.310  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:45.310  7696  8202 D bt_vendor: op for 7
,07-28 12:43:45.310  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:45.320  7696  8166 D BluetoothAdapterProperties: Scan Mode:21
,07-28 12:43:45.320  7696  8166 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-28 12:43:45.320  7696  7696 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,07-28 12:43:45.330  7696  8202 D bt_vendor: op for 7
,07-28 12:43:45.330  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:45.330  7696  8202 D bt_vendor: op for 7
,07-28 12:43:45.330  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:45.330  7696  8202 D bt_vendor: op for 7
07-28 12:43:45.330  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:45.330  7696  8202 D bt_vendor: op for 7
,07-28 12:43:45.330  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:45.330  7696  8202 D bt_vendor: op for 7
,07-28 12:43:45.330  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:45.330  7696  8202 D bt_vendor: op for 7
,07-28 12:43:45.330  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:45.330  7696  7696 I BluetoothPbapService: Handler(): got msg=1
,07-28 12:43:45.340  7696  8202 D bt_vendor: op for 7
,07-28 12:43:45.340  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:45.340   791  1469 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-28 12:43:45.340  7696  8202 D bt_vendor: op for 7
07-28 12:43:45.340  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:45.340  7696  8202 D bt_vendor: op for 7
,07-28 12:43:45.340  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:45.340  7696  8202 D bt_vendor: op for 7
07-28 12:43:45.340  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:45.340  7696  8202 D bt_vendor: op for 7
,07-28 12:43:45.340  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:45.340  7696  8202 D bt_vendor: op for 7
07-28 12:43:45.340  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:45.350  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:45.350  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:45.350  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:45.350  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:43:45.350  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:45.350  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:45.350  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:45.350  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:43:45.350  7441  7441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:43:45.350   791  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:43:45.350  3400  7715 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:43:45.350  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:45.350  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:45.350  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:45.350  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:43:45.350  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:45.350  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:45.350  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:45.350  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:43:45.350  7441  7441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:43:45.350  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:45.350   791  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:43:45.360   791  1043 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:43:45.360  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:45.360   791  1043 D BluetoothPan: Binding service...
07-28 12:43:45.360   791  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,07-28 12:43:45.360   791   791 D BluetoothPan: BluetoothPAN Proxy object connected
,07-28 12:43:45.360  7696  7706 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:43:45.360  1313  1327 D Bluetoothsap: onBluetoothStateChange: up=true
,07-28 12:43:45.360  1313  1327 D Bluetoothsap: Binding service...
,07-28 12:43:45.360  1313  1327 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,07-28 12:43:45.360   791  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,07-28 12:43:45.360  1313  1327 D Bluetoothsap: bindService called to Bluetooth SAP Service
,07-28 12:43:45.370  1313  1313 D Bluetoothsap: BluetoothSAP Proxy object connected
,07-28 12:43:45.370  1313  1313 D SapProfile: Bluetooth service connected
07-28 12:43:45.370  1313  1313 D Bluetoothsap: getConnectedDevices()
,07-28 12:43:45.370  1313  5812 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 12:43:45.370  7696  8216 V BluetoothPbapService: PBAP Service initSocket try: 0
,07-28 12:43:45.370   791  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-28 12:43:45.370  1313  1313 D BluetoothA2dp: Proxy object connected
07-28 12:43:45.370  1313  1313 D A2dpProfile: Bluetooth service connected
,07-28 12:43:45.370   791  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:43:45.370  1404  1413 E BluetoothHeadset: BluetoothHeadset service is binded
07-28 12:43:45.370  7696  8216 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:43:45.370  7696  8216 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[73]}
07-28 12:43:45.370  7696  8216 D BluetoothSocket: bindListen(), new LocalSocket 
07-28 12:43:45.370  7696  8216 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-28 12:43:45.370  7696  8216 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1208892d
07-28 12:43:45.370  7696  8202 D bt_vendor: op for 7
07-28 12:43:45.370  7696  8202 D bt_upio : BT_WAKE is asserted already
07-28 12:43:45.370  7696  8216 D BluetoothSocket: channel: 19
07-28 12:43:45.380  7696  8216 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,07-28 12:43:45.380   791  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
07-28 12:43:45.380  1313  1327 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:43:45.380  1313  1313 D HeadsetProfile: Bluetooth service connected
07-28 12:43:45.380   791  1043 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:43:45.380   791  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-28 12:43:45.380   791   791 D BluetoothA2dp: Proxy object connected
07-28 12:43:45.380  1313  5812 D BluetoothInputDevice: onBluetoothStateChange: up=true
,07-28 12:43:45.380   791  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,07-28 12:43:45.380   791  1043 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:43:45.380  1313  1313 D BluetoothInputDevice: Proxy object connected
07-28 12:43:45.380  1313  1313 D HidProfile: Bluetooth service connected
07-28 12:43:45.380  1426  1708 E BluetoothHeadset: BluetoothHeadset service is binded
07-28 12:43:45.380  1313  1327 D BluetoothMap: onBluetoothStateChange: up=true
,07-28 12:43:45.380   791  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,07-28 12:43:45.380  3400  3410 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 12:43:45.380  1313  1313 D BluetoothMap: Proxy object connected
07-28 12:43:45.380  1313  1313 D MapProfile: Bluetooth service connected
,07-28 12:43:45.390   791  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-28 12:43:45.390  3400  3400 D BluetoothA2dp: Proxy object connected
,07-28 12:43:45.390   791  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:43:45.390  1404  1419 E BluetoothHeadset: BluetoothHeadset service is binded
07-28 12:43:45.390  1313  1329 D BluetoothPbap: onBluetoothStateChange: up=true
,07-28 12:43:45.390   791  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,07-28 12:43:45.390  1313  1313 D BluetoothPbap: Proxy object connected
,07-28 12:43:45.390  1313  1313 D PbapServerProfile: Bluetooth service connected
,07-28 12:43:45.390   791  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
07-28 12:43:45.390  1404  3550 E BluetoothHeadset: BluetoothHeadset service is binded
07-28 12:43:45.390  1313  5812 D BluetoothPan: Binding service...
,07-28 12:43:45.390   791  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,07-28 12:43:45.390  1313  1313 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:43:45.390  1313  1313 D PanProfile: Bluetooth service connected
07-28 12:43:45.390   791  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,07-28 12:43:45.390   791   791 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:45.390   791   791 I InputMethodManagerService: [BT Setting State] State =12
07-28 12:43:45.390   791   791 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
07-28 12:43:45.400  1193  1193 D BluetoothTile:  onBluetoothStateChange:
,07-28 12:43:45.400  1865  1865 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-28 12:43:45.400  1404  1404 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@296f9c26, true
,07-28 12:43:45.400  1404  1404 D BluetoothHeadset: registerMessageListener
,07-28 12:43:45.400  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:45.400  1193  1193 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-28 12:43:45.400  1193  1193 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:45.400  7624  7624 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:45.400   791  1638 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-28 12:43:45.400   791  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
07-28 12:43:45.400   791  1638 D ActivityManager: caller:android.app.ApplicationThreadProxy@2fb11e9e, r.packageName :com.google.android.gms
07-28 12:43:45.400  7696  7704 D HeadsetService: registerMessageListener
,07-28 12:43:45.400  7696  7704 D HeadsetService: registerMessageListener
07-28 12:43:45.400  7696  8190 D HeadsetStateMachine: Disconnected process message: 70
07-28 12:43:45.400  1404  1404 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
,07-28 12:43:45.400  1404  1404 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
07-28 12:43:45.400  7696  8190 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@d3c4e62
,07-28 12:43:45.400  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:45.410   791   832 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:43:45.410   791  1144 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
07-28 12:43:45.410  1193  1193 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
07-28 12:43:45.410  7696  8190 D HeadsetStateMachine: Disconnected process message: 9
,07-28 12:43:45.410  7696  8190 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
,07-28 12:43:45.410  1313  1313 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:45.410  1193  1595 D BluetoothTile:  handleUpdatestate:false name:null
,07-28 12:43:45.410  1193  1595 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-28 12:43:45.410   312   731 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
07-28 12:43:45.410   312   731 V voice   : voice_set_parameters: enter: A2dpSuspended=false
07-28 12:43:45.410   312   731 V voice   : voice_set_parameters: exit with code(-2)
07-28 12:43:45.410   312   731 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
07-28 12:43:45.410   312   731 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-28 12:43:45.410   312   731 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-28 12:43:45.410   312   731 V audio_hw_primary: adev_set_parameters: exit
07-28 12:43:45.410  7696  8190 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,07-28 12:43:45.410  1313  1313 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
07-28 12:43:45.410  1313  1313 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
,07-28 12:43:45.420  1313  1313 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 12:43:45.420   791  1476 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-28 12:43:45.420  7696  8235 D BluetoothMapMasInstance: set MAP SDP message type : 1
07-28 12:43:45.420   791  1476 D ActivityManager: caller:android.app.ApplicationThreadProxy@24e0d595, r.packageName :com.android.settings
,07-28 12:43:45.420  7696  8235 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:43:45.420  7696  8202 D bt_vendor: op for 7
07-28 12:43:45.420  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:45.420  7696  8235 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[75]}
07-28 12:43:45.420  7696  8235 D BluetoothSocket: bindListen(), new LocalSocket 
07-28 12:43:45.420  7696  8235 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-28 12:43:45.420  7696  8235 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@45b6bf3
07-28 12:43:45.420  7696  8235 D BluetoothSocket: channel: 5
,07-28 12:43:45.420  1313  1313 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:43:45.420  1313  1313 D BluetoothNotiBroadcastReceiver: onReceive
,07-28 12:43:45.430  7696  7696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@360e7108
07-28 12:43:45.430  7696  7696 D BtConfig.SecureMode: isSecureModeOn:false
,07-28 12:43:45.430   791  1468 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:43:45.430   791  1468 D ActivityManager: caller:android.app.ApplicationThreadProxy@6d9529b, r.packageName :com.android.bluetooth
,07-28 12:43:45.450   791  1476 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-28 12:43:45.470  7696  8240 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:43:45.470  7696  8202 D bt_vendor: op for 7
07-28 12:43:45.470  7696  8202 D bt_upio : BT_WAKE is asserted already
07-28 12:43:45.470  7696  8240 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
,07-28 12:43:45.470  7696  8240 D BluetoothSocket: bindListen(), new LocalSocket 
07-28 12:43:45.470  7696  8240 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-28 12:43:45.470  7696  8240 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2cb6d44f
07-28 12:43:45.470  7696  8240 D BluetoothSocket: channel: 12
07-28 12:43:45.470  7696  8240 I BtOppRfcommListener: Accept thread started.
,07-28 12:43:45.490  1897  1897 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-28 12:43:45.490   791   832 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-28 12:43:45.490   791   832 D ActivityManager: caller:android.app.ApplicationThreadProxy@b29dde4, r.packageName :com.google.android.gms
,07-28 12:43:45.500  1897  8244 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-28 12:43:45.500  1897  1897 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-28 12:43:45.510   791  1574 D ActivityManager: caller:android.app.ApplicationThreadProxy@15709649, r.packageName :com.google.android.gms
,07-28 12:43:45.520  1897  8244 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-28 12:43:46.750   791  3332 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.absolute.android.persistservice.a.run:1062 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> ,
,07-28 12:43:46.760  7441  7508 D BluetoothAdapter: disable()
,07-28 12:43:46.770   791  1366 D SettingsProvider: name = bluetooth_on
,07-28 12:43:46.790  7696  8163 D BluetoothAdapterState: CURRENT_STATE=ON, MSG = USER_TURN_OFF
,07-28 12:43:46.790  7696  8163 D BluetoothAdapterProperties: Setting state to 13
,07-28 12:43:46.790  7696  8163 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,07-28 12:43:46.790  7696  8163 D BluetoothAdapterService: Bluetooth PBAP supproted is true
,07-28 12:43:46.790  7696  8163 D BluetoothAdapterService: updateAdapterState state is 13
,07-28 12:43:46.790   791  1469 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:43:46.790   791  1469 D ActivityManager: caller:android.app.ApplicationThreadProxy@5a3a46f, r.packageName :com.android.bluetooth
,07-28 12:43:46.800  7696  8163 D BluetoothAdapterService: Autoconnection is available 
,07-28 12:43:46.800  7696  8163 D BluetoothAdapterService: updateAdapterState prevState = 12newState = 13
,07-28 12:43:46.800  7696  8163 D BluetoothAdapterService: terminating service from this receiver
,07-28 12:43:46.800  7696  8163 D BluetoothAdapterProperties: onBluetoothDisable()
,07-28 12:43:46.810   791  1638 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,07-28 12:43:46.810  7696  8202 D bt_vendor: op for 7
,07-28 12:43:46.810  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:46.810  7696  8202 D bt_vendor: op for 7
,07-28 12:43:46.810  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:46.810  7696  8202 D bt_vendor: op for 7
,07-28 12:43:46.810  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:46.810  7696  8166 D BluetoothAdapterProperties: Scan Mode:20
,07-28 12:43:46.810  7696  8163 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
07-28 12:43:46.810  7696  8163 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
,07-28 12:43:46.810  7696  8163 E bt-btif : btif_vhci_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:1
,07-28 12:43:46.810  7696  8163 E bt-btif : btif_sock_cleanup, sock_thread_handle:6, rfc_init:1, vhci_init:0
,07-28 12:43:46.820  7696  7696 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 13
,07-28 12:43:46.820  7696  8163 E bt-btif : cmd socket is not created
07-28 12:43:46.820  7696  7696 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2a2a7dc, channel: 19, state: LISTENING
,07-28 12:43:46.820  7696  7696 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2a2a7dc, channel: 19, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1208892d, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@1e8eb0e5mSocket: android.net.LocalSocket@32c547ba impl:android.net.LocalSocketImpl@2db6666b fd:FileDescriptor[73]
07-28 12:43:46.820  7696  7696 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@32c547ba impl:android.net.LocalSocketImpl@2db6666b fd:FileDescriptor[73]
,07-28 12:43:46.820  7696  8202 D bt_vendor: op for 7
,07-28 12:43:46.820  7696  8202 D bt_upio : BT_WAKE is asserted already
07-28 12:43:46.820  7696  8163 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,07-28 12:43:46.820  7441  7441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:43:46.820  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:46.820  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:46.820  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:46.820  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:43:46.820  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:46.820  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:46.820  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:46.820  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:43:46.820  7696  8200 E bt-btm  : btm_ble_start_auto_conn start : 0, 0
07-28 12:43:46.820  7696  8200 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
07-28 12:43:46.820  7696  8200 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,07-28 12:43:46.820  7696  8200 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:43:46.820  7696  8200 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:43:46.830  7696  8202 D bt_vendor: op for 7
,07-28 12:43:46.830  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:46.830  7696  8202 D bt_vendor: op for 7
07-28 12:43:46.830  7696  8202 D bt_upio : BT_WAKE is asserted already
07-28 12:43:46.830  7696  8240 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
07-28 12:43:46.830  7696  8202 D bt_vendor: op for 7
07-28 12:43:46.830  7696  8202 D bt_upio : BT_WAKE is asserted already
07-28 12:43:46.830  7696  8202 D bt_vendor: op for 7
07-28 12:43:46.830  7696  8202 D bt_upio : BT_WAKE is asserted already
07-28 12:43:46.830  7696  8202 D bt_vendor: op for 7
07-28 12:43:46.830  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:46.840  7696  8202 D bt_vendor: op for 7
,07-28 12:43:46.840  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:46.840  7696  8202 D bt_vendor: op for 7
,07-28 12:43:46.840  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:46.840  7696  8202 D bt_vendor: op for 7
07-28 12:43:46.840  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:46.840  7696  8202 D bt_vendor: op for 7
,07-28 12:43:46.840  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:46.840  7696  8202 D bt_vendor: op for 7
,07-28 12:43:46.840  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:46.840  7696  8202 D bt_vendor: op for 7
07-28 12:43:46.840  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:46.850  7441  7441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:43:46.850  7441  7441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:43:46.850  7441  7441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,07-28 12:43:46.850  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:46.850  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:46.850  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:46.850  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:43:46.850  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
07-28 12:43:46.850  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:46.850  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:46.850  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:43:46.850  7441  7441 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
07-28 12:43:46.850  7441  7441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:43:46.850   791   791 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:46.850   791   791 I InputMethodManagerService: [BT Setting State] State =13
,07-28 12:43:46.860  1193  1193 D BluetoothTile:  onBluetoothStateChange:
,07-28 12:43:46.860  7696  7696 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@32fe7661, channel: 5, state: LISTENING
,07-28 12:43:46.860  7696  7696 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@32fe7661, channel: 5, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@45b6bf3, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@2e702586mSocket: android.net.LocalSocket@3cd2fe47 impl:android.net.LocalSocketImpl@213a1674 fd:FileDescriptor[75]
07-28 12:43:46.860  7696  7696 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@3cd2fe47 impl:android.net.LocalSocketImpl@213a1674 fd:FileDescriptor[75]
,07-28 12:43:46.860  7696  7696 I BtOppRfcommListener: stopping Accept Thread
07-28 12:43:46.860  7696  7696 D BluetoothSocket: close() in, this: android.bluetooth.BluetoothSocket@2a4b179d, channel: 12, state: LISTENING
,07-28 12:43:46.860  7696  7696 D BluetoothSocket: close() this: android.bluetooth.BluetoothSocket@2a4b179d, channel: 12, mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2cb6d44f, mSocketOS: android.net.LocalSocketImpl$SocketOutputStream@3991412mSocket: android.net.LocalSocket@43737e3 impl:android.net.LocalSocketImpl@3b1c25e0 fd:FileDescriptor[78]
07-28 12:43:46.860  7696  7696 D BluetoothSocket: Closing mSocket: android.net.LocalSocket@43737e3 impl:android.net.LocalSocketImpl@3b1c25e0 fd:FileDescriptor[78]
07-28 12:43:46.860  7696  8240 I BtOppRfcommListener: BluetoothSocket listen thread finished
,07-28 12:43:46.860  1193  1193 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-28 12:43:46.870  1193  1193 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:46.870  1193  1595 D BluetoothTile:  handleUpdatestate:false name:null
,07-28 12:43:46.870  1193  1595 D BluetoothTile:  handleUpdatestate:false name:null
,07-28 12:43:46.870  1193  1595 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-28 12:43:46.870   791   831 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:43:46.870   791  1443 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-28 12:43:46.870  1193  1193 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-28 12:43:46.870  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:46.870  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:46.880   791  1476 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-28 12:43:46.880   791  1476 D ActivityManager: caller:android.app.ApplicationThreadProxy@1fa1057c, r.packageName :com.google.android.gms
,07-28 12:43:46.890  1865  1865 I SamsungIME: STATE_CHANGED = 13, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-28 12:43:46.890  7624  7624 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:46.890  1313  1313 D BluetoothPbap: Proxy object disconnected
,07-28 12:43:46.890  1313  1313 D PbapServerProfile: Bluetooth service disconnected
07-28 12:43:46.890  1313  1313 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:46.890  1313  1313 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 12:43:46.890   791  1679 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,07-28 12:43:46.890   791  1679 D ActivityManager: caller:android.app.ApplicationThreadProxy@1aabee5a, r.packageName :com.android.settings
,07-28 12:43:46.910  1313  1313 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:43:46.910  1313  1313 D BluetoothNotiBroadcastReceiver: onReceive
,07-28 12:43:47.000  7696  8200 W bt-l2cap: btif_mce_execute_service enable:0
07-28 12:43:47.000  7696  8200 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:43:47.000  7696  8200 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:43:47.000  7696  8200 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:43:47.000  7696  8200 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:43:47.000  7696  8200 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:43:47.000  7696  8200 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
07-28 12:43:47.000  7696  8200 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
07-28 12:43:47.000  7696  8200 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
07-28 12:43:47.000  7696  8200 W bt-btif : ag scb idx 1 not allocated
07-28 12:43:47.000  7696  8200 W bt-btif : ag scb idx 2 not allocated
07-28 12:43:47.000  7696  8200 E bt-btif : BTA AG is already disabled, ignoring ...
,07-28 12:43:47.000  7696  8202 D bt_vendor: op for 6
07-28 12:43:47.000  7696  8203 D bt_userial: RX termination
07-28 12:43:47.000  7696  8203 W bt_userial: select_read return size <=0:-1, exiting userial_read_thread
07-28 12:43:47.000  7696  8203 D bt_userial: Leaving userial_read_thread()
07-28 12:43:47.000  7696  8166 D bt_userial: userial_close_reader Joined userial reader thread: 0
,07-28 12:43:47.000  7696  8202 D bt_vendor: op for 9
07-28 12:43:47.000  7696  8202 D bt_hwcfg: hw_epilog_process
07-28 12:43:47.000  7696  8202 D bt_vendor: op for 7
07-28 12:43:47.000  7696  8202 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:47.000  7696  8166 D bt_vendor: op for 4
07-28 12:43:47.000  7696  8166 I bt_userial_vendor: device fd = 66 close
,07-28 12:43:47.010  7696  8166 D bt_vendor: op for 0
,07-28 12:43:47.010  7696  8166 D bt_upio : upio_set_bluetooth_power(on: 0)
07-28 12:43:47.010  7696  8166 D bt_upio : is_emulator_context : 0
07-28 12:43:47.010  7696  8166 D bt_upio : is_rfkill_disabled ? [0]
07-28 12:43:47.010  1897  1897 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-28 12:43:47.010  7696  8166 D bt_vendor: cleanup
,07-28 12:43:47.010  7696  8200 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
07-28 12:43:47.010  7696  8166 I GKI_LINUX: GKI_exit_task 0 done
07-28 12:43:47.010  7696  8166 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
07-28 12:43:47.010  7696  8163 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true,
07-28 12:43:47.010  7696  8163 D BtConfig.SecureMode: isSecureModeOn:false
07-28 12:43:47.010  7696  8163 D BluetoothAdapterService: mProfilesStarted : true supportedProfileServices.length : 12
07-28 12:43:47.010  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
07-28 12:43:47.010  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
,07-28 12:43:47.010  7696  8163 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,07-28 12:43:47.010   791   831 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth,
07-28 12:43:47.010   791   831 D ActivityManager: caller:android.app.ApplicationThreadProxy@3ab6fd68, r.packageName :com.android.bluetooth
,07-28 12:43:47.010  1897  1897 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
07-28 12:43:47.010  7696  7696 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 12:43:47.010  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
07-28 12:43:47.010  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-28 12:43:47.010  7696  8163 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,07-28 12:43:47.020  7696  7696 D BtGatt.GattService: Received stop request...Stopping profile...
,07-28 12:43:47.020  7696  7696 D BtGatt.GattService: stop()
07-28 12:43:47.020  7696  7696 D BtGatt.AdvertiseManager: advertise clients cleared
,07-28 12:43:47.020   791  1144 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:43:47.020   791  1144 D ActivityManager: caller:android.app.ApplicationThreadProxy@278fc581, r.packageName :com.android.bluetooth
07-28 12:43:47.020  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
07-28 12:43:47.020  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-28 12:43:47.020  7696  8163 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,07-28 12:43:47.020  7696  7696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@360e7108
07-28 12:43:47.020   791  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:43:47.020   791  1476 D ActivityManager: caller:android.app.ApplicationThreadProxy@292a9626, r.packageName :com.android.bluetooth
,07-28 12:43:47.020  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
07-28 12:43:47.020  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-28 12:43:47.020  7696  8163 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-28 12:43:47.020  7696  7696 D HeadsetService: Received stop request...Stopping profile...
07-28 12:43:47.020   791  1574 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:43:47.020   791  1574 D ActivityManager: caller:android.app.ApplicationThreadProxy@845b267, r.packageName :com.android.bluetooth
07-28 12:43:47.020  7696  7696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@360e7108
,07-28 12:43:47.020   791   791 D AudioService: onServiceDisconnected: Bluetooth profile: 1
07-28 12:43:47.020  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
07-28 12:43:47.020  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-28 12:43:47.020  7696  8163 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
07-28 12:43:47.020   791  1358 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:43:47.020   791  1358 D ActivityManager: caller:android.app.ApplicationThreadProxy@24b28814, r.packageName :com.android.bluetooth
,07-28 12:43:47.020  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
07-28 12:43:47.020  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-28 12:43:47.020  7696  8163 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
07-28 12:43:47.020   791  1366 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:43:47.020  1313  1313 D HeadsetProfile: Bluetooth service disconnected
07-28 12:43:47.020   791  1366 D ActivityManager: caller:android.app.ApplicationThreadProxy@18f238bd, r.packageName :com.android.bluetooth
07-28 12:43:47.020  7624  7624 W BluetoothHeadset: Proxy not attached to service
07-28 12:43:47.020  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
07-28 12:43:47.020  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:43:47.020   791  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:43:47.020  7696  8163 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
07-28 12:43:47.020   791  1476 D ActivityManager: caller:android.app.ApplicationThreadProxy@b99eeb2, r.packageName :com.android.bluetooth
07-28 12:43:47.020  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
07-28 12:43:47.020  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-28 12:43:47.020   791  1443 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:43:47.020  7696  8163 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
07-28 12:43:47.020   791  1443 D ActivityManager: caller:android.app.ApplicationThreadProxy@26f10e03, r.packageName :com.android.bluetooth
07-28 12:43:47.020  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:43:47.020  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:43:47.020  7696  8163 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:43:47.020  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:43:47.020  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:43:47.020  7696  8163 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:43:47.020  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
07-28 12:43:47.020  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-28 12:43:47.020  7696  8163 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-28 12:43:47.020  7696  8163 W BluetoothAdapterService: check For Quiet mode profile 10 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
07-28 12:43:47.020  7696  8163 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-28 12:43:47.020  7696  8163 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,07-28 12:43:47.020  7696  7696 E BluetoothAdapterService(906916104): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=10, doUpdate=false
07-28 12:43:47.020  7696  8163 D BluetoothAdapterState: Stopping profile services that were post enabled
07-28 12:43:47.020  7696  7696 D A2dpService: Received stop request...Stopping profile...
07-28 12:43:47.020  7696  7696 V Avrcp   : doQuit
07-28 12:43:47.020  7696  8195 D A2dpStateMachine: Exit Disconnected: -1
,07-28 12:43:47.020  7696  7696 D Avrcp   : Unregistering previous receiver
07-28 12:43:47.030  7696  7696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@360e7108
07-28 12:43:47.030  3400  3400 D BluetoothA2dp: Proxy object disconnected
07-28 12:43:47.030  7696  7696 E BluetoothAdapterService(906916104): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=10, doUpdate=true
,07-28 12:43:47.030  7696  7696 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-28 12:43:47.030  1313  1313 D BluetoothA2dp: Proxy object disconnected
07-28 12:43:47.030  1313  1313 D A2dpProfile: Bluetooth service disconnected
07-28 12:43:47.030   791   791 D BluetoothA2dp: Proxy object disconnected
,07-28 12:43:47.030   791   791 D AudioService: onServiceDisconnected: Bluetooth profile: 2
07-28 12:43:47.030  7696  7696 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
07-28 12:43:47.030  7696  7696 D HidService: Received stop request...Stopping profile...
07-28 12:43:47.030  7696  7696 D HidService: Stopping Bluetooth HidService
,07-28 12:43:47.030  7696  7696 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
07-28 12:43:47.030  7696  7696 W bt-btif : cleanup: HH disabling or disabled already, status = 0
07-28 12:43:47.030  7696  7696 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
07-28 12:43:47.030  7696  7696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@360e7108
,07-28 12:43:47.030  1313  1313 D BluetoothInputDevice: Proxy object disconnected
07-28 12:43:47.030  1313  1313 D HidProfile: Bluetooth service disconnected
07-28 12:43:47.030  7696  7696 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
07-28 12:43:47.030  7696  7696 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,07-28 12:43:47.030  7696  7696 D HealthService: Received stop request...Stopping profile...
07-28 12:43:47.030  7696  7696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@360e7108
07-28 12:43:47.030  7696  7696 D PanService: Received stop request...Stopping profile...
07-28 12:43:47.030  7696  7696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@360e7108
,07-28 12:43:47.030   791   791 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-28 12:43:47.030  1313  1313 D BluetoothPan: BluetoothPAN Proxy object disconnected
07-28 12:43:47.030  7696  7696 D BluetoothMapService: Received stop request...Stopping profile...
07-28 12:43:47.030  1313  1313 D PanProfile: Bluetooth service disconnected
,07-28 12:43:47.030  7696  7696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@360e7108
,07-28 12:43:47.030  1313  1313 D BluetoothMap: Proxy object disconnected
07-28 12:43:47.030  1313  1313 D MapProfile: Bluetooth service disconnected
07-28 12:43:47.030  7696  7696 D SapService: Received stop request...Stopping profile...
07-28 12:43:47.030  7696  7696 D SapService: Stopping Bluetooth SapService
07-28 12:43:47.030  7696  7696 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@360e7108
,07-28 12:43:47.030  1313  1313 D Bluetoothsap: BluetoothSAP Proxy object disconnected
07-28 12:43:47.030  7696  7696 E BluetoothAdapterService(906916104): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=10, doUpdate=true
07-28 12:43:47.030  1313  1313 D SapProfile: Bluetooth service disconnected
07-28 12:43:47.030  7696  7696 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-28 12:43:47.030  7696  7696 D BluetoothAdapterService: Profile still running: com.android.bluetooth.hid.HidService
07-28 12:43:47.030  7696  7696 D BluetoothA2dp: Proxy object disconnected
07-28 12:43:47.030  7696  7696 D BluetoothAdapterService: Bluetooth A2dp source service disconnected
,07-28 12:43:47.030  7696  8196 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
07-28 12:43:47.040  7696  7696 I GKI_LINUX: GKI_exit_task 2 done
07-28 12:43:47.040  7696  7696 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
07-28 12:43:47.040  7696  7696 V Avrcp   : cleanup
,07-28 12:43:47.040  7696  7696 E BluetoothAdapterService(906916104): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=10, doUpdate=true
07-28 12:43:47.040  7696  7696 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:43:47.040  7696  7696 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-28 12:43:47.040  7696  7696 E BluetoothAdapterService(906916104): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=10, doUpdate=true
07-28 12:43:47.040  7696  7696 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:43:47.040  7696  7696 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-28 12:43:47.040  7696  7696 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
07-28 12:43:47.040  7696  7696 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
07-28 12:43:47.040  7696  7696 E BluetoothAdapterService(906916104): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=10, doUpdate=true
07-28 12:43:47.040  7696  7696 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:43:47.040  7696  7696 D BluetoothAdapterService: Profile still running: com.android.bluetooth.map.BluetoothMapService
07-28 12:43:47.040  7696  7696 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
07-28 12:43:47.040  7696  7696 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,07-28 12:43:47.040  7696  7696 E BluetoothAdapterService(906916104): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=10, doUpdate=true
07-28 12:43:47.040  7696  7696 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-28 12:43:47.040  7696  7696 D BluetoothAdapterService: Profile still running: com.broadcom.bt.service.sap.SapService
07-28 12:43:47.040  7696  7696 E BluetoothAdapterService(906916104): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=10, doUpdate=true
,07-28 12:43:47.040  7696  8163 D BluetoothAdapterState: CURRENT_STATE=PENDING,MSG = STOPPED, isTurningOn=false, isTurningOff=true
07-28 12:43:47.040  7696  8163 D BluetoothAdapterProperties: Setting state to 10
07-28 12:43:47.040  7696  8163 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
07-28 12:43:47.040  7696  8163 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-28 12:43:47.040  7696  8163 D BluetoothAdapterService: updateAdapterState state is 10
07-28 12:43:47.040  7696  8163 D BluetoothAdapterService: Autoconnection is available 
07-28 12:43:47.040  7696  8163 D BluetoothAdapterService: updateAdapterState prevState = 13newState = 10
07-28 12:43:47.040  7696  8163 I BluetoothAdapterState: Entering OffState
07-28 12:43:47.040  7696  7696 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L251): Cleaning up Bluetooth SAP Interface...##
07-28 12:43:47.040  7696  7696 W BluetoothSAPServiceJni: ## WARNING : cleanupNative(L257): Cleaning up Bluetooth SAP callback object##
,07-28 12:43:47.040  7696  7706 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-28 12:43:47.040  1313  5812 D Bluetoothsap: onBluetoothStateChange: up=false
07-28 12:43:47.040  1313  5812 D Bluetoothsap: Unbinding service...
,07-28 12:43:47.040  1313  1329 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-28 12:43:47.040   791  1043 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-28 12:43:47.040  1313  5812 D BluetoothInputDevice: onBluetoothStateChange: up=false
,07-28 12:43:47.040  1313  1329 D BluetoothMap: onBluetoothStateChange: up=false
,07-28 12:43:47.040  3400  3409 D BluetoothA2dp: onBluetoothStateChange: up=false
,07-28 12:43:47.050  1313  1327 D BluetoothPbap: onBluetoothStateChange: up=false
,07-28 12:43:47.050   791  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 14 receivers.
,07-28 12:43:47.050   791  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
,07-28 12:43:47.060   791   791 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:47.060   791   791 I InputMethodManagerService: [BT Setting State] State =10
07-28 12:43:47.060   791   791 I InputMethodManagerService: [BT Setting on -> off] mBTKeyboardCount =0, KEYBOARD_BT(0)
07-28 12:43:47.060  7696  8166 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,07-28 12:43:47.060  7696  7696 I GKI_LINUX: GKI_exit_task 1 done
07-28 12:43:47.060  7696  7696 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
,07-28 12:43:47.060  1193  1193 D BluetoothAdapter: 913822534: getState() :  mService = null. Returning STATE_OFF
07-28 12:43:47.060  1193  1193 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-28 12:43:47.060  7696  7696 I BluetoothServiceJni: cleanupNative: return from cleanup
07-28 12:43:47.060  1193  1595 D BluetoothAdapter: 913822534: getState() :  mService = null. Returning STATE_OFF
,07-28 12:43:47.060  1897  2422 D BluetoothAdapter: 964148488: getState() :  mService = null. Returning STATE_OFF
07-28 12:43:47.060  1193  1193 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:47.060  1897  2422 D BluetoothAdapter: 964148488: getState() :  mService = null. Returning STATE_OFF
07-28 12:43:47.060  1193  1595 D BluetoothAdapter: 913822534: getState() :  mService = null. Returning STATE_OFF
07-28 12:43:47.060  1193  1595 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-28 12:43:47.060   791   832 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-28 12:43:47.060  1193  1193 D BluetoothAdapter: 913822534: getState() :  mService = null. Returning STATE_OFF
07-28 12:43:47.060  1193  1193 D BluetoothAdapter: 913822534: getState() :  mService = null. Returning STATE_OFF
07-28 12:43:47.060  7696  7696 I art     : System.exit called, status: 0
07-28 12:43:47.060  7696  7696 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
07-28 12:43:47.060   791  1574 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:43:47.060   791   832 D ActivityManager: caller:android.app.ApplicationThreadProxy@203a1180, r.packageName :com.google.android.gms
,07-28 12:43:47.060   791  1144 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
07-28 12:43:47.060  1193  1193 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
,07-28 12:43:47.060  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:47.060  1865  1865 I SamsungIME: STATE_CHANGED = 10, KEYBOARD_BT(0), mBTKeyboardCount =0
07-28 12:43:47.060  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:47.060  1313  1313 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:47.070  1313  1313 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 12:43:47.070   791  1657 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
,07-28 12:43:47.070   791  1657 D ActivityManager: caller:android.app.ApplicationThreadProxy@d3443fe, r.packageName :com.android.settings
07-28 12:43:47.070  7624  7624 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:47.080  1313  1313 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:43:47.080  1313  1313 D BluetoothNotiBroadcastReceiver: onReceive
,07-28 12:43:47.110   791  1358 I ActivityManager: Process com.android.bluetooth (pid 7696)(adj 0) has died(184,1564)
,07-28 12:43:47.150  1897  1897 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-28 12:43:47.150   791  1366 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-28 12:43:47.150   791  1366 D ActivityManager: caller:android.app.ApplicationThreadProxy@208ca20a, r.packageName :com.google.android.gms
,07-28 12:43:47.160  1897  8283 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-28 12:43:47.160  1897  1897 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-28 12:43:47.170   791   831 D ActivityManager: caller:android.app.ApplicationThreadProxy@25589098, r.packageName :com.google.android.gms
,07-28 12:43:47.170  1897  8283 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=false
,07-28 12:43:48.120   304   304 E SMD     : DCD ON
,07-28 12:43:49.510   791  3300 D SSRM:n  : SIOP:: AP = 380, PST = 383, CUR = 450
,07-28 12:43:49.890  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
,07-28 12:43:49.890  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:51.131   304   304 E SMD     : DCD ON
,07-28 12:43:52.890  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:43:52.890  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c53e174 added. We now have 6 listener(s)
07-28 12:43:52.890  7441  7508 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:43:52.900  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:43:52.900  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2220869d added. We now have 7 listener(s)
07-28 12:43:52.900  7441  7508 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:43:52.900  7441  7508 I System.out: IsBluetoothEnabled
,07-28 12:43:52.900  7441  7508 D BluetoothAdapter: disable()
,07-28 12:43:52.910   791  1366 E BluetoothManagerService: Bluetooth is already disabled. DO NOT disable again.
,07-28 12:43:52.910  7441  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:52.910  7441  7508 D BluetoothAdapter: enable()
,07-28 12:43:52.910   791  1259 W ActivityManager: Permission Denial: getCurrentUser() from pid=7441, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
,07-28 12:43:52.920   791  1259 W BluetoothManagerService: Failed getting userId using ActivityManagerNative
07-28 12:43:52.920   791  1259 W BluetoothManagerService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7441, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-28 12:43:52.920   791  1259 W BluetoothManagerService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-28 12:43:52.920   791  1259 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.CheckItPolicy(BluetoothManagerService.java:2144)
07-28 12:43:52.920   791  1259 W BluetoothManagerService: 	at com.android.server.BluetoothManagerService.enable(BluetoothManagerService.java:674)
07-28 12:43:52.920   791  1259 W BluetoothManagerService: 	at android.bluetooth.IBluetoothManager$Stub.onTransact(IBluetoothManager.java:98)
07-28 12:43:52.920   791  1259 W BluetoothManagerService: 	at android.os.Binder.execTransact(Binder.java:446)
,07-28 12:43:52.920   791  1259 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
07-28 12:43:52.920   791  1259 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:43:52.920   791  1259 D SettingsProvider: name = bluetooth_on
,07-28 12:43:52.930   791  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:43:52.930   791  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:43:52.930   791  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetooth
,07-28 12:43:52.930   791  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:52.930   791  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:52.930   791  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:52.930   791  1043 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:52.980  8297  8297 E Zygote  : MountEmulatedStorage()
,07-28 12:43:52.980  8297  8297 E Zygote  : v2
07-28 12:43:52.980  8297  8297 I libpersona: KNOX_SDCARD checking this for 1002
07-28 12:43:52.980  8297  8297 I libpersona: KNOX_SDCARD not a persona
,07-28 12:43:52.990   791  1043 I ActivityManager: Start proc com.android.bluetooth for service com.android.bluetooth/.btservice.AdapterService: pid=8297 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008} abi=armeabi-v7a
,07-28 12:43:52.990  8297  8297 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:43:52.990  8297  8297 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:43:52.990  8297  8297 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:43:53.020  8297  8297 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:43:53.020  8297  8297 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:53.050  8297  8297 D ResourcesManager: creating new AssetManager and set to /system/app/Bluetooth/Bluetooth.apk
,07-28 12:43:53.050  8297  8297 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,07-28 12:43:53.050  8297  8297 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,07-28 12:43:53.080  8297  8297 I BluetoothA2dpSinkServiceJni: register_com_android_bluetooth_a2dp_sink
,07-28 12:43:53.100  8297  8297 D BtSettings.ProfileConfig: Adding GattService
,07-28 12:43:53.100  8297  8297 D BtSettings.ProfileConfig: Adding HeadsetService
07-28 12:43:53.100  8297  8297 D BtSettings.ProfileConfig: Adding A2dpService
,07-28 12:43:53.100  8297  8297 D BtSettings.ProfileConfig: Adding HidService
07-28 12:43:53.100  8297  8297 D BtSettings.ProfileConfig: Adding HealthService
,07-28 12:43:53.100  8297  8297 D BtSettings.ProfileConfig: Adding PanService
07-28 12:43:53.100  8297  8297 D BtSettings.ProfileConfig: Adding BluetoothMapService
07-28 12:43:53.100  8297  8297 D BtSettings.ProfileConfig: Adding SapService
,07-28 12:43:53.100  8297  8297 D BtSettings.ProfileConfig: Adding HeadsetClientService
07-28 12:43:53.100  8297  8297 D BtSettings.ProfileConfig: Adding A2dpSinkService
07-28 12:43:53.100  8297  8297 D BtSettings.ProfileConfig: Adding SapClientService
,07-28 12:43:53.100  8297  8297 D BtSettings.ProfileConfig: Adding HidDevService
07-28 12:43:53.100  8297  8297 I BtSettings.ProfileConfig: *********Initializing Bluetooth Profile Settings*******
,07-28 12:43:53.110   791  1144 D SettingsProvider: name = bt_svcst_com.android.bluetooth.gatt.GattService
07-28 12:43:53.110   791  1144 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:53.110   791  1144 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:53.110   791  1144 D SettingsProvider: selectionArgs: false
07-28 12:43:53.110   791  1144 D SettingsProvider: selectionArgs: 1002
07-28 12:43:53.110   791  1144 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:43:53.110   791  1144 D SettingsProvider: ret = -1
,07-28 12:43:53.110   791  1443 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfp.HeadsetService
07-28 12:43:53.110   791  1443 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:53.110   791  1443 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:53.110   791  1443 D SettingsProvider: selectionArgs: false
07-28 12:43:53.110   791  1443 D SettingsProvider: selectionArgs: 1002
07-28 12:43:53.110   791  1443 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:43:53.110   791  1443 D SettingsProvider: ret = -1
,07-28 12:43:53.110   791  1469 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpService
07-28 12:43:53.110   791  1469 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:53.110   791  1469 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:53.110   791  1469 D SettingsProvider: selectionArgs: false
07-28 12:43:53.110   791  1469 D SettingsProvider: selectionArgs: 1002
07-28 12:43:53.110   791  1469 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:43:53.110   791  1469 D SettingsProvider: ret = -1
,07-28 12:43:53.110   791  1638 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidService
07-28 12:43:53.110   791  1638 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:53.110   791  1638 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:53.110   791  1638 D SettingsProvider: selectionArgs: false
07-28 12:43:53.110   791  1638 D SettingsProvider: selectionArgs: 1002
07-28 12:43:53.110   791  1638 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:43:53.110   791  1638 D SettingsProvider: ret = -1
07-28 12:43:53.110   791   832 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hdp.HealthService
07-28 12:43:53.110   791   832 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:53.110   791   832 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,07-28 12:43:53.110   791   832 D SettingsProvider: selectionArgs: false
07-28 12:43:53.110   791   832 D SettingsProvider: selectionArgs: 1002
07-28 12:43:53.110   791   832 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:43:53.110   791   832 D SettingsProvider: ret = -1
07-28 12:43:53.110   791  1657 D SettingsProvider: name = bt_svcst_com.android.bluetooth.pan.PanService
07-28 12:43:53.110   791  1657 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:53.110   791  1657 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
,07-28 12:43:53.110   791  1657 D SettingsProvider: selectionArgs: false
07-28 12:43:53.110   791  1657 D SettingsProvider: selectionArgs: 1002
07-28 12:43:53.110   791  1657 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:43:53.110   791  1657 D SettingsProvider: ret = -1
07-28 12:43:53.110   791  1468 D SettingsProvider: name = bt_svcst_com.android.bluetooth.map.BluetoothMapService
07-28 12:43:53.110   791  1468 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:53.110   791  1468 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:53.110   791  1468 D SettingsProvider: selectionArgs: false
07-28 12:43:53.110   791  1468 D SettingsProvider: selectionArgs: 1002
,07-28 12:43:53.110   791  1468 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:43:53.110   791  1468 D SettingsProvider: ret = -1
07-28 12:43:53.110   791  1532 D SettingsProvider: name = bt_svcst_com.broadcom.bt.service.sap.SapService
07-28 12:43:53.110   791  1532 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:53.110   791  1532 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:53.110   791  1532 D SettingsProvider: selectionArgs: false
07-28 12:43:53.110   791  1532 D SettingsProvider: selectionArgs: 1002
07-28 12:43:53.110   791  1532 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-28 12:43:53.110   791  1532 D SettingsProvider: ret = -1
07-28 12:43:53.110   791   831 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:43:53.110   791   831 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:53.110   791   831 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:53.110   791   831 D SettingsProvider: selectionArgs: false
07-28 12:43:53.110   791   831 D SettingsProvider: selectionArgs: 1002
07-28 12:43:53.110   791   831 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-28 12:43:53.110   791   831 D SettingsProvider: ret = -1
07-28 12:43:53.110   791  1574 D SettingsProvider: name = bt_svcst_com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:43:53.110   791  1574 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:53.110   791  1574 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:53.110   791  1574 D SettingsProvider: selectionArgs: false
07-28 12:43:53.110   791  1574 D SettingsProvider: selectionArgs: 1002
07-28 12:43:53.110   791  1574 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-28 12:43:53.110   791  1574 D SettingsProvider: ret = -1
07-28 12:43:53.110   791  1679 D SettingsProvider: name = bt_svcst_com.android.bluetooth.sapclient.SapClientService
07-28 12:43:53.110   791  1679 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:53.110   791  1679 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:53.110   791  1679 D SettingsProvider: selectionArgs: false
07-28 12:43:53.110   791  1679 D SettingsProvider: selectionArgs: 1002
07-28 12:43:53.110   791  1679 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-28 12:43:53.110   791  1679 D SettingsProvider: ret = -1
07-28 12:43:53.110   791  1476 D SettingsProvider: name = bt_svcst_com.android.bluetooth.hid.HidDevService
07-28 12:43:53.110   791  1476 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:53.110   791  1476 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:53.110   791  1476 D SettingsProvider: selectionArgs: false
07-28 12:43:53.110   791  1476 D SettingsProvider: selectionArgs: 1002
07-28 12:43:53.110   791  1476 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:43:53.110   791  1476 D SettingsProvider: ret = -1
,07-28 12:43:53.130  8297  8297 D BluetoothAdapterState: make
,07-28 12:43:53.130  8297  8297 I bluedroid: init
,07-28 12:43:53.140  8297  8297 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,07-28 12:43:53.140  8297  8319 I BluetoothAdapterState: Entering OffState
07-28 12:43:53.140  8297  8297 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
07-28 12:43:53.140  8297  8297 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
07-28 12:43:53.140  8297  8297 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
,07-28 12:43:53.140  8297  8297 E bt-btif : btif_fetch_local_ble_random_bdaddr
07-28 12:43:53.140  8297  8297 I bluedroid: get_profile_interface socket
07-28 12:43:53.140  8297  8297 I bluedroid: get_profile_interface map_client
07-28 12:43:53.140  8297  8322 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
,07-28 12:43:53.140  8297  8297 D BluetoothAdapterService: checkAddrForIOP: Loading from conf
,07-28 12:43:53.140  8297  8322 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
07-28 12:43:53.140   791   832 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-28 12:43:53.140  8297  8322 E BluetoothServiceJni: populateRssiValuesNative
07-28 12:43:53.140  8297  8322 I bluedroid: getModelRssiValues
07-28 12:43:53.140  8297  8322 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
,07-28 12:43:53.150  8297  8322 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-28 12:43:53.150  8297  8322 D BluetoothAdapterProperties: Name is: Note3-1
07-28 12:43:53.150   791   791 D SettingsProvider: name = bluetooth_name
,07-28 12:43:53.150  8297  8305 I bluedroid: config_hci_snoop_log
,07-28 12:43:53.150   791  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 14 receivers.
,07-28 12:43:53.150   791  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:43:53.150   791  1043 E DevicePolicyManagerService: getAllowBluetoothMode - value retunrs : 2
,07-28 12:43:53.160   791  1043 D SecContentProvider: uri = 3 selection = isBluetoothEnabled
,07-28 12:43:53.160  8297  8319 D BluetoothAdapterState: CURRENT_STATE=OFF, MSG = USER_TURN_ON
07-28 12:43:53.160  8297  8319 D BluetoothAdapterProperties: Setting state to 11
,07-28 12:43:53.160  8297  8319 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
07-28 12:43:53.160  8297  8319 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-28 12:43:53.160  8297  8319 D BluetoothAdapterService: updateAdapterState state is 11
,07-28 12:43:53.160  8297  8319 D BluetoothAdapterService: Autoconnection is available 
07-28 12:43:53.160  8297  8319 D BluetoothAdapterService: updateAdapterState prevState = 10newState = 11
,07-28 12:43:53.160   791   791 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:53.160   791   791 I InputMethodManagerService: [BT Setting State] State =11
,07-28 12:43:53.160  8297  8319 D BluetoothSecureManager: getInstant: null
,07-28 12:43:53.160  8297  8319 D BluetoothSecureManager: calling getMethod for getService
07-28 12:43:53.160  8297  8319 D BluetoothSecureManager: calling getService
,07-28 12:43:53.160  1193  1193 D BluetoothTile:  onBluetoothPairedDevicesChanged:
07-28 12:43:53.160  1193  1193 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:53.160  1865  1865 I SamsungIME: STATE_CHANGED = 11, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-28 12:43:53.160  8297  8319 D BluetoothSecureManager: getService return binder: android.os.BinderProxy@3a433023
07-28 12:43:53.160   791  1428 D BluetoothSecureManagerService: isSecureModeEnabled
,07-28 12:43:53.160   791  1428 D BluetoothSecureManagerService: getSecureModeSetting, name: secure_mode_enable
07-28 12:43:53.160  8297  8319 D BtConfig.SecureMode: isSecureModeOn:false
,07-28 12:43:53.160  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-28 12:43:53.170  7624  7624 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:53.170  1313  1313 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:53.170   791   832 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:43:53.170   791  1532 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=false
,07-28 12:43:53.170  1193  1193 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 )
07-28 12:43:53.170  1193  1595 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-28 12:43:53.170  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:53.170  8297  8319 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.gatt.GattService
07-28 12:43:53.170  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-28 12:43:53.170  8297  8319 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hfp.HeadsetService
07-28 12:43:53.170   791  1476 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-28 12:43:53.170  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-28 12:43:53.170   791  1476 D ActivityManager: caller:android.app.ApplicationThreadProxy@3cbc7047, r.packageName :com.google.android.gms
07-28 12:43:53.170  8297  8319 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.a2dp.A2dpService
07-28 12:43:53.170  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
,07-28 12:43:53.170  8297  8319 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hid.HidService
07-28 12:43:53.170  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
,07-28 12:43:53.170  8297  8319 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.hdp.HealthService
07-28 12:43:53.170  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
,07-28 12:43:53.170  8297  8319 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.pan.PanService
,07-28 12:43:53.170  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:43:53.170  8297  8319 W BluetoothAdapterService: isProfileEnabled(): profile not found com.android.bluetooth.map.BluetoothMapService
,07-28 12:43:53.170  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-28 12:43:53.170  8297  8319 W BluetoothAdapterService: isProfileEnabled(): profile not found com.broadcom.bt.service.sap.SapService
07-28 12:43:53.170  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
,07-28 12:43:53.170  8297  8319 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hfpclient.HeadsetClientService
,07-28 12:43:53.180  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
,07-28 12:43:53.180  8297  8319 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:43:53.180  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-28 12:43:53.180  8297  8319 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.sapclient.SapClientService
,07-28 12:43:53.180  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-28 12:43:53.180  8297  8319 W BluetoothAdapterService: processStart(): removed Client profile: com.android.bluetooth.hid.HidDevService
,07-28 12:43:53.180  8297  8319 D BluetoothBondStateMachine: make
,07-28 12:43:53.180  1313  1313 D BluetoothNotiBroadcastReceiver: onReceive
,07-28 12:43:53.180  8297  8319 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.gatt.GattService
,07-28 12:43:53.180  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.gatt.GattService
07-28 12:43:53.180  8297  8319 W BluetoothAdapterService: Not skipping com.android.bluetooth.gatt.GattService
,07-28 12:43:53.180  8297  8324 I BluetoothBondStateMachine: StableState(): Entering Off State
,07-28 12:43:53.190   791  1679 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:43:53.190   791  1679 D ActivityManager: caller:android.app.ApplicationThreadProxy@339ed99d, r.packageName :com.android.bluetooth
,07-28 12:43:53.190  8297  8319 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfp.HeadsetService
07-28 12:43:53.190  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfp.HeadsetService
07-28 12:43:53.190  8297  8319 W BluetoothAdapterService: Not skipping com.android.bluetooth.hfp.HeadsetService
,07-28 12:43:53.190  8297  8297 I BtGatt.JNI: classInitNative(L890): classInitNative: Success!
07-28 12:43:53.190   791  1358 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:43:53.190   791  1358 D ActivityManager: caller:android.app.ApplicationThreadProxy@3e45c9e3, r.packageName :com.android.bluetooth
,07-28 12:43:53.190  8297  8319 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpService
,07-28 12:43:53.190  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpService
07-28 12:43:53.190  8297  8319 W BluetoothAdapterService: Not skipping com.android.bluetooth.a2dp.A2dpService
,07-28 12:43:53.200   791  1259 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:43:53.200   791  1259 D ActivityManager: caller:android.app.ApplicationThreadProxy@21947299, r.packageName :com.android.bluetooth
,07-28 12:43:53.200  8297  8319 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidService
,07-28 12:43:53.200  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidService
07-28 12:43:53.200  8297  8319 W BluetoothAdapterService: Not skipping com.android.bluetooth.hid.HidService
07-28 12:43:53.200   791  1144 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:43:53.200   791  1144 D ActivityManager: caller:android.app.ApplicationThreadProxy@1d81213f, r.packageName :com.android.bluetooth
,07-28 12:43:53.200  8297  8297 D BtGatt.DebugUtils: handleDebugAction() action=null
,07-28 12:43:53.200  8297  8297 D BtGatt.GattService: Received start request. Starting profile...
07-28 12:43:53.200  8297  8297 D BtGatt.GattService: start()
07-28 12:43:53.200  8297  8297 I bluedroid: get_profile_interface gatt
,07-28 12:43:53.200  8297  8319 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hdp.HealthService
07-28 12:43:53.200  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hdp.HealthService
07-28 12:43:53.200  8297  8297 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@159910fa
07-28 12:43:53.200  8297  8297 D BtGatt.AdvertiseManager: advertise manager created
07-28 12:43:53.200  8297  8319 W BluetoothAdapterService: Not skipping com.android.bluetooth.hdp.HealthService
,07-28 12:43:53.200   791  1476 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:43:53.210   791  1476 D ActivityManager: caller:android.app.ApplicationThreadProxy@23b09f55, r.packageName :com.android.bluetooth
,07-28 12:43:53.210  8297  8319 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.pan.PanService
,07-28 12:43:53.210  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.pan.PanService
07-28 12:43:53.210  8297  8319 W BluetoothAdapterService: Not skipping com.android.bluetooth.pan.PanService
,07-28 12:43:53.210   791  1638 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:43:53.210   791  1638 D ActivityManager: caller:android.app.ApplicationThreadProxy@34f0925b, r.packageName :com.android.bluetooth
,07-28 12:43:53.210  8297  8319 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.map.BluetoothMapService
,07-28 12:43:53.210  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.map.BluetoothMapService
07-28 12:43:53.210  8297  8319 W BluetoothAdapterService: Not skipping com.android.bluetooth.map.BluetoothMapService
,07-28 12:43:53.220  8297  8297 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@159910fa
,07-28 12:43:53.220  8297  8297 D HeadsetService: Received start request. Starting profile...
,07-28 12:43:53.220   791   832 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:43:53.220   791   832 D ActivityManager: caller:android.app.ApplicationThreadProxy@28620ea4, r.packageName :com.android.bluetooth
,07-28 12:43:53.230  8297  8297 I BluetoothHeadsetServiceJni: classInitNative: succeeds
07-28 12:43:53.230  8297  8297 D HeadsetStateMachine: make
,07-28 12:43:53.230  8297  8319 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.broadcom.bt.service.sap.SapService
07-28 12:43:53.230  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.broadcom.bt.service.sap.SapService
07-28 12:43:53.230  8297  8319 W BluetoothAdapterService: Not skipping com.broadcom.bt.service.sap.SapService
,07-28 12:43:53.230   791  1679 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:43:53.230   791  1679 D ActivityManager: caller:android.app.ApplicationThreadProxy@2caabfc2, r.packageName :com.android.bluetooth
,07-28 12:43:53.230  8297  8319 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:43:53.230  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hfpclient.HeadsetClientService
07-28 12:43:53.230  8297  8319 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hfpclient.HeadsetClientService
,07-28 12:43:53.230  8297  8319 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:43:53.230  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.a2dp.A2dpSinkService
07-28 12:43:53.230  8297  8319 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.a2dp.A2dpSinkService
,07-28 12:43:53.230  8297  8319 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.sapclient.SapClientService
07-28 12:43:53.230  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.sapclient.SapClientService
07-28 12:43:53.230  8297  8319 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.sapclient.SapClientService
07-28 12:43:53.230  8297  8319 W BluetoothAdapterService: check For Quiet mode profile 12 RadioCount =0 srv name=com.android.bluetooth.hid.HidDevService
,07-28 12:43:53.230  8297  8319 D BtSettings.ProfileConfig: getProfileSaveSetting: com.android.bluetooth.hid.HidDevService
07-28 12:43:53.230  8297  8319 W BluetoothAdapterService: Profile supported, But not enabled com.android.bluetooth.hid.HidDevService
,07-28 12:43:53.230  8297  8319 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
,07-28 12:43:53.240  8297  8297 E HeadsetStateMachine: # of Max HF connection is 2
,07-28 12:43:53.240   791  1532 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetPhone
,07-28 12:43:53.250   791  1358 D ActivityManager: bindService callerProcessName:com.android.bluetooth, calleePkgName: com.android.server.telecom, action: android.bluetooth.IBluetoothHeadsetVoIP
07-28 12:43:53.250  8297  8297 I bluedroid: get_profile_interface handsfree
,07-28 12:43:53.260  8297  8297 I DualScoManager: Instantiating Dual Sco Manager
07-28 12:43:53.260  8297  8297 I DualScoManager: Set HeadsetServiceHelper
,07-28 12:43:53.260  8297  8297 D BluetoothAtMessage: createCMTIContentObservers
,07-28 12:43:53.260   791   832 D SettingsProvider: name = bluetooth_hfp_allowed_bvra
07-28 12:43:53.260   791   832 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:53.260   791   832 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:53.260   791   832 D SettingsProvider: selectionArgs: false
07-28 12:43:53.260   791   832 D SettingsProvider: selectionArgs: 1002
07-28 12:43:53.260   791   832 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
07-28 12:43:53.260   791   832 D SettingsProvider: ret = -1
,07-28 12:43:53.260  8297  8331 D HeadsetStateMachine: Enter Disconnected: -2
07-28 12:43:53.260  8297  8297 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@159910fa
,07-28 12:43:53.260  8297  8331 E HeadsetStateMachine: set to mRemoteBrsf = 0
,07-28 12:43:53.260  8297  8297 D A2dpService: Received start request. Starting profile...
,07-28 12:43:53.260  8297  8331 D HeadsetStateMachine: map size, before remove : 0
,07-28 12:43:53.270  8297  8297 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,07-28 12:43:53.270  8297  8297 V Avrcp   : make
,07-28 12:43:53.270  8297  8297 V Avrcp   : Avrcp
07-28 12:43:53.270  8297  8297 I bluedroid: get_profile_interface avrcp
,07-28 12:43:53.270  8297  8331 D HeadsetStateMachine: map size, after remove: 0
,07-28 12:43:53.270  8297  8297 V Avrcp   : start
,07-28 12:43:53.270  8297  8331 D HeadsetStateMachine: mNextConnectingDevice : null
,07-28 12:43:53.280  8297  8297 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,07-28 12:43:53.280  8297  8297 V Avrcp   : ++registerMediaPlayers++
,07-28 12:43:53.280  8297  8297 I Avrcp   : No of Audio players :: 2
,07-28 12:43:53.280  8297  8297 I Avrcp   : App Package name is com.google.android.music
,07-28 12:43:53.280  8297  8297 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-28 12:43:53.280  1897  1897 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-28 12:43:53.280  8297  8297 I Avrcp   : App pkg name is Google Play Music
,07-28 12:43:53.290  8297  8297 I Avrcp   : Name::Google Play Music
,07-28 12:43:53.290  8297  8297 V Avrcp   : MediaPlayerInfo: mPlayerId=1
07-28 12:43:53.290  8297  8297 I Avrcp   : App Package name is com.sec.android.app.music
,07-28 12:43:53.290  8297  8297 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,07-28 12:43:53.290  8297  8297 I Avrcp   : App pkg name is Music
,07-28 12:43:53.290  8297  8297 I Avrcp   : Name::Music
07-28 12:43:53.290  8297  8297 V Avrcp   : MediaPlayerInfo: mPlayerId=2
07-28 12:43:53.290  8297  8297 I Avrcp   :  set player publishabilty with player id::2 toBePublished ::true
,07-28 12:43:53.290  8297  8297 I Avrcp   : No of Video players :: 1
,07-28 12:43:53.290  8297  8297 I Avrcp   : Video App Package name is com.sec.android.app.videoplayer
,07-28 12:43:53.290  8297  8297 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,07-28 12:43:53.290  1897  1897 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-28 12:43:53.290  8297  8297 I Avrcp   : Video App pkg name is Video Player
,07-28 12:43:53.290  8297  8297 I Avrcp   : Name::Video Player
07-28 12:43:53.290  8297  8297 V Avrcp   : MediaPlayerInfo: mPlayerId=3
07-28 12:43:53.300  8297  8297 I Avrcp   : Add tempPlayer
,07-28 12:43:53.300  8297  8297 V Avrcp   : MediaPlayerInfo: mPlayerId=4
07-28 12:43:53.300  8297  8297 I Avrcp   : Total no of players: 4
07-28 12:43:53.300  8297  8297 V Avrcp   : swapping the samsung player with 1st player
07-28 12:43:53.300  8297  8297 I Avrcp   :  Updating now playing list upon AVRCP Start
,07-28 12:43:53.300  8297  8338 V Avrcp   : handleMessage, msg=207
,07-28 12:43:53.300  8297  8297 I BluetoothA2dpServiceJni: classInitNative: succeeds
,07-28 12:43:53.300  8297  8297 D A2dpStateMachine: make
07-28 12:43:53.300  8297  8338 D BluetoothMediaBrowser:  getNowPlayingListcontent://media/external/audio/playlists?secFilter=include
,07-28 12:43:53.300  8297  8297 I bluedroid: get_profile_interface a2dp
,07-28 12:43:53.300  8297  8342 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
07-28 12:43:53.300  8297  8297 E bt-btif : warning : media task started media_task_refcnt 1 
,07-28 12:43:53.300  8297  8297 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@159910fa
07-28 12:43:53.300  8297  8341 D A2dpStateMachine: Enter Disconnected: -2
,07-28 12:43:53.300  8297  8297 I BluetoothHidServiceJni: classInitNative: succeeds
,07-28 12:43:53.310  8297  8297 D HidService: Received start request. Starting profile...
,07-28 12:43:53.310  8297  8297 I bluedroid: get_profile_interface hidhost
07-28 12:43:53.310  8297  8297 D HidService: setHidService(): set to: null
07-28 12:43:53.310  8297  8297 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@159910fa
,07-28 12:43:53.310  8297  8297 I BluetoothHealthServiceJni: classInitNative: succeeds
,07-28 12:43:53.310  8297  8297 D HealthService: Received start request. Starting profile...
,07-28 12:43:53.310  8297  8297 I bluedroid: get_profile_interface health
,07-28 12:43:53.310  8297  8297 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@159910fa
,07-28 12:43:53.310  8297  8297 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,07-28 12:43:53.320  8297  8338 D BluetoothMediaBrowser: no now playing list
07-28 12:43:53.320  8297  8338 D BluetoothMediaBrowser:  getNowPlayingId now playing id : -1
07-28 12:43:53.320  8297  8338 D Avrcp   :  checkNowPlayingList start
,07-28 12:43:53.320  8297  8297 D PanService: Received start request. Starting profile...
07-28 12:43:53.320  8297  8297 D BluetoothPanServiceJni: initializeNative(L110): pan
07-28 12:43:53.320  8297  8297 I bluedroid: get_profile_interface pan
,07-28 12:43:53.320  8297  8297 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@159910fa
,07-28 12:43:53.320  8297  8297 E BluetoothAdapterService(362352890): onProfileServiceStateChange() serviceName=com.android.bluetooth.gatt.GattService, state=12, doUpdate=false
,07-28 12:43:53.320  8297  8297 D BluetoothMapService: Received start request. Starting profile...
,07-28 12:43:53.340  8297  8297 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@159910fa
,07-28 12:43:53.350   791  1468 D BatteryService: !@BatteryListener : batteryPropertiesChanged!
,07-28 12:43:53.350  8297  8297 I BluetoothSAPServiceJni: classInitNative(L204): succeeds
07-28 12:43:53.350   791  1468 D BatteryService: level:100, scale:100, status:5, health:2, present:true, voltage: 4323, temperature: 301, technology: Li-ion, AC powered:false, USB powered:true, Wireless powered:false, icon:17303723, invalid charger:0
07-28 12:43:53.350   791  1468 D BatteryService: online:4, current avg:450, charge type:1, power sharing:false, high voltage charger:false, capacity:280000, current_now:450
07-28 12:43:53.350   791  1468 D BatteryService: stay LED for fully charged
,07-28 12:43:53.350   791   791 D BatteryService: Sending ACTION_BATTERY_CHANGED.
07-28 12:43:53.350  8297  8297 D SapService: Received start request. Starting profile...
07-28 12:43:53.350  8297  8297 D BluetoothSAPServiceJni: initializeNative(L209): sap
07-28 12:43:53.350  8297  8297 I bluedroid: get_profile_interface sap
07-28 12:43:53.350  8297  8297 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@159910fa
,07-28 12:43:53.350  8297  8297 D HeadsetStateMachine: Try to query the phonestate on bind
07-28 12:43:53.350  1404  3550 I Telecom : BluetoothPhoneService: queryPhoneState
,07-28 12:43:53.350  1193  1193 D KeyguardUpdateMonitor: received broadcast android.intent.action.BATTERY_CHANGED
07-28 12:43:53.350  1404  1404 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
07-28 12:43:53.350  1193  1193 D KeyguardUpdateMonitor: handleBatteryUpdate
,07-28 12:43:53.350  8297  8297 D HeadsetStateMachine: Proxy object connected
07-28 12:43:53.350  8297  8297 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=0
,07-28 12:43:53.350   791   791 I MotionRecognitionService: Plugged
07-28 12:43:53.350   791   791 I MotionRecognitionService: setPowerConnected  = true
07-28 12:43:53.350  1193  1193 D STATUSBAR-PhoneStatusBar:  mBrightnessEnablebySettings = true mBrightnessEnablebyBattery = true mBrightnessEnablebyDisableFlag = true mPmsBrightnessEnablebySettings = true
07-28 12:43:53.350  1193  1193 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:43:53.350  8297  8297 D HeadsetPhoneState: sendDeviceDataStateChanged
07-28 12:43:53.350  8297  8331 D HeadsetStateMachine: Disconnected process message: 11
07-28 12:43:53.350  1193  1193 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
07-28 12:43:53.350  1193  1193 D BatteryMeterView: ACTION_BATTERY_CHANGED : level:100 status:5 health:2
,07-28 12:43:53.350  8297  8297 D HeadsetPhoneState: Signal level : previous=0 curr=0
07-28 12:43:53.350  8297  8331 D HeadsetStateMachine: Disconnected process message: 18
07-28 12:43:53.350  8297  8297 E BluetoothAdapterService(362352890): onProfileServiceStateChange() serviceName=com.android.bluetooth.hfp.HeadsetService, state=12, doUpdate=true
,07-28 12:43:53.350  8297  8297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-28 12:43:53.350  8297  8297 D BluetoothA2dp: Proxy object connected
07-28 12:43:53.350  8297  8331 D HeadsetStateMachine: Disconnected process message: 10
07-28 12:43:53.350  8297  8331 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
,07-28 12:43:53.350  8297  8331 D HeadsetStateMachine: Disconnected process message: 11
07-28 12:43:53.350  8297  8297 D BluetoothAdapterService: Bluetooth A2dp source service connected
07-28 12:43:53.350  8297  8297 E BluetoothAdapterService(362352890): onProfileServiceStateChange() serviceName=com.android.bluetooth.a2dp.A2dpService, state=12, doUpdate=true
07-28 12:43:53.350  8297  8297 E BluetoothAdapterService(362352890): onProfileServiceStateChange() serviceName=com.android.bluetooth.hid.HidService, state=12, doUpdate=true
,07-28 12:43:53.360  8297  8297 E BluetoothAdapterService(362352890): onProfileServiceStateChange() serviceName=com.android.bluetooth.hdp.HealthService, state=12, doUpdate=true
,07-28 12:43:53.360  8297  8297 E BluetoothAdapterService(362352890): onProfileServiceStateChange() serviceName=com.android.bluetooth.pan.PanService, state=12, doUpdate=true
,07-28 12:43:53.360  8297  8297 E BluetoothAdapterService(362352890): onProfileServiceStateChange() serviceName=com.android.bluetooth.map.BluetoothMapService, state=12, doUpdate=true
,07-28 12:43:53.360  8297  8297 E BluetoothAdapterService(362352890): onProfileServiceStateChange() serviceName=com.broadcom.bt.service.sap.SapService, state=12, doUpdate=true
07-28 12:43:53.360  8297  8297 V HeadsetService: HeadsetService - Received Intent.ACTION_BATTERY_CHANGED
07-28 12:43:53.360  8297  8319 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = STARTED, isTurningOn=true, isTurningOff=false
07-28 12:43:53.360  8297  8319 I bluedroid: enable
07-28 12:43:53.360  8297  8331 D HeadsetStateMachine: Disconnected process message: 10
,07-28 12:43:53.360  8297  8347 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
07-28 12:43:53.360  8297  8319 I bt_hci_bdroid: init
,07-28 12:43:53.360  8297  8319 I bt_vendor: init
07-28 12:43:53.360  8297  8319 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
07-28 12:43:53.360  8297  8319 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
07-28 12:43:53.360  8297  8319 D bt_userial: userial_init
07-28 12:43:53.360  8297  8319 D bt_vendor: op for 5
,07-28 12:43:53.360  8297  8319 D bt_vendor: op for 0
07-28 12:43:53.360  8297  8319 D bt_upio : upio_set_bluetooth_power(on: 0)
07-28 12:43:53.360  8297  8319 D bt_upio : is_emulator_context : 0
07-28 12:43:53.360  8297  8319 D bt_upio : is_rfkill_disabled ? [0]
07-28 12:43:53.360  8297  8319 D bt_upio : is_rfkill_disabled ? [0]
07-28 12:43:53.370  8297  8319 D bt_vendor: op for 0
07-28 12:43:53.370  8297  8319 D bt_upio : upio_set_bluetooth_power(on: 1)
07-28 12:43:53.370  8297  8319 D bt_upio : is_emulator_context : 0
07-28 12:43:53.370  8297  8319 D bt_upio : is_rfkill_disabled ? [0]
,07-28 12:43:53.370  8297  8349 D bt_vendor: op for 3
07-28 12:43:53.370  8297  8349 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,07-28 12:43:53.370  8297  8349 I bt_userial_vendor: userial_vendor_open():UART is setup
07-28 12:43:53.370  8297  8349 I bt_userial_vendor: device fd = 65 open
07-28 12:43:53.370  8297  8349 D bt_vendor: op for 1
07-28 12:43:53.370  8297  8349 E bt_hwcfg: Start CFG HW, HCI reset
,07-28 12:43:53.370  8297  8350 D bt_userial: Entering userial_read_thread()
,07-28 12:43:53.450  8297  8349 E bt_hwcfg: Read Local Name after HCI reset
,07-28 12:43:53.470  8297  8349 D bt_hwcfg: Chipset BCM4335C0
07-28 12:43:53.470  8297  8349 D bt_hwcfg: Target name = [BCM4335C0]
,07-28 12:43:53.470  8297  8349 I bt_hwcfg: module_type[semco].
07-28 12:43:53.470  8297  8349 I bt_hwcfg: not ZERO...
07-28 12:43:53.470  8297  8349 I bt_hwcfg: module_type[semco] is invalid.
07-28 12:43:53.470  8297  8349 E bt_hwcfg: patchram path ORG . BCM4335C0
07-28 12:43:53.470  8297  8349 E bt_hwcfg: patchram path ORG .. BCM4335C0
07-28 12:43:53.470  8297  8349 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335C0
07-28 12:43:53.470  8297  8349 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335C0
07-28 12:43:53.470  8297  8349 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335C0
07-28 12:43:53.470  8297  8349 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335C0
07-28 12:43:53.470  8297  8349 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335C0
07-28 12:43:53.470  8297  8349 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559_wisol.hcd BCM4335C0
07-28 12:43:53.470  8297  8349 E bt_hwcfg: fw ver (org)0.0
07-28 12:43:53.470  8297  8349 E bt_hwcfg: vendor lib preload failed to locate firmware patch file
07-28 12:43:53.470  8297  8349 E bt_hwcfg: Remove module rev, try again BCM4335
07-28 12:43:53.470  8297  8349 D bt_hwcfg: Target name = [BCM4335]
07-28 12:43:53.470  8297  8349 I bt_hwcfg: module_type[semco].
07-28 12:43:53.470  8297  8349 I bt_hwcfg: not ZERO...
07-28 12:43:53.470  8297  8349 I bt_hwcfg: module_type[semco] is invalid.
07-28 12:43:53.470  8297  8349 E bt_hwcfg: patchram path ORG . BCM4335
07-28 12:43:53.470  8297  8349 E bt_hwcfg: patchram path ORG .. BCM4335
07-28 12:43:53.470  8297  8349 E bt_hwcfg: patchram path ORG bcm2079xB4_firmware.ncd BCM4335
07-28 12:43:53.470  8297  8349 E bt_hwcfg: patchram path ORG bcm2079xB4_pre_firmware.ncd BCM4335
07-28 12:43:53.470  8297  8349 E bt_hwcfg: patchram path ORG bcm2079xB5_firmware.ncd BCM4335
07-28 12:43:53.470  8297  8349 E bt_hwcfg: patchram path ORG bcm2079xB5_pre_firmware.ncd BCM4335
07-28 12:43:53.470  8297  8349 E bt_hwcfg: patchram path ORG bcm4335_V0111.0559.hcd BCM4335
07-28 12:43:53.470  8297  8349 I bt_hwcfg: patch(org) : bcm4335_V0111.0559.hcd
07-28 12:43:53.470  8297  8349 I bt_hwcfg: Found patchfile: /vendor/firmware/bcm4335_V0111.0559.hcd
07-28 12:43:53.470  8297  8349 E bt_hwcfg: ORG patchram base 0111
07-28 12:43:53.470  8297  8349 E bt_hwcfg: ORG patchram minor 0559
07-28 12:43:53.470  8297  8349 E bt_hwcfg: fw ver (org)111.559
07-28 12:43:53.470  8297  8349 E bt_hwcfg: Final Patchram is /vendor/firmware/bcm4335_V0111.0559.hcd
,07-28 12:43:53.490  8297  8349 I bt_hwcfg: Axi patch failure or not include AXI patching
,07-28 12:43:53.490  8297  8349 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-28 12:43:53.950  8297  8349 I bt_hwcfg: bt vendor lib: set UART baud 115200
,07-28 12:43:53.950  8297  8349 I bt_hwcfg: FW Download delta = 507187
,07-28 12:43:53.950  8297  8349 D bt_hwcfg: Settlement delay -- 100 ms
07-28 12:43:53.950  8297  8349 I bt_hwcfg: Setting fw settlement delay to 100 
,07-28 12:43:54.060  8297  8349 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,07-28 12:43:54.090   791  1052 I PowerManagerService: [PWL] Off : 105s ago
,07-28 12:43:54.090   791  1052 I PowerManagerService: [PWL]   PowerManagerService.WakeLocks: ref count=1
,07-28 12:43:54.090   791  1052 I PowerManagerService: [PWL]     mWakeLockSummary : 0x1
,07-28 12:43:54.090   791  1052 I PowerManagerService: [PWL]       PARTIAL_WAKE_LOCK              'ConnectivityService' (uid=1000, pid=791, ws=null) (elapsedTime=19209)
,07-28 12:43:54.090  8297  8349 I bt_hwcfg: vendor lib fwcfg completed
,07-28 12:43:54.110  8297  8347 I         : BTE_InitTraceLevels -- TRC_HCI
,07-28 12:43:54.110  8297  8347 I         : BTE_InitTraceLevels -- TRC_L2CAP
07-28 12:43:54.110  8297  8347 I         : BTE_InitTraceLevels -- TRC_RFCOMM
07-28 12:43:54.110  8297  8347 I         : BTE_InitTraceLevels -- TRC_AVDT
07-28 12:43:54.110  8297  8347 I         : BTE_InitTraceLevels -- TRC_AVRC
,07-28 12:43:54.110  8297  8347 I         : BTE_InitTraceLevels -- TRC_A2D
07-28 12:43:54.110  8297  8347 I         : BTE_InitTraceLevels -- TRC_BNEP
07-28 12:43:54.110  8297  8347 I         : BTE_InitTraceLevels -- TRC_BTM
07-28 12:43:54.110  8297  8347 I         : BTE_InitTraceLevels -- TRC_GAP
,07-28 12:43:54.110  8297  8347 I         : BTE_InitTraceLevels -- TRC_PAN
07-28 12:43:54.110  8297  8347 I         : BTE_InitTraceLevels -- TRC_SAP
07-28 12:43:54.110  8297  8347 I         : BTE_InitTraceLevels -- TRC_SDP
07-28 12:43:54.110  8297  8347 I         : BTE_InitTraceLevels -- TRC_GATT
,07-28 12:43:54.120  8297  8347 I         : BTE_InitTraceLevels -- TRC_SMP
07-28 12:43:54.120  8297  8347 I         : BTE_InitTraceLevels -- TRC_BTAPP
07-28 12:43:54.120  8297  8347 I         : BTE_InitTraceLevels -- TRC_BTIF
07-28 12:43:54.120  8297  8347 I         : BTE_InitTraceLevels -- TRC_PROTOCOL
,07-28 12:43:54.120   304   304 E SMD     : DCD ON
,07-28 12:43:54.340  8297  8347 W bt-l2cap: l2c_link_processs_ble_num_bufs 15
,07-28 12:43:54.350  8297  8347 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xb3af1b5d 
,07-28 12:43:54.350  8297  8347 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xb3af1b5d 
,07-28 12:43:54.570  8297  8322 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 1 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 16 mOffloadedScanResultStorageBytes= 0 mIsActivityAndEnergyReporting = false
,07-28 12:43:54.570  8297  8322 E bt-btif : Calling BTA_HhEnable
,07-28 12:43:54.570  8297  8322 E bt-btif : btif_storage_get_adapter_property service_mask:0x2120048
07-28 12:43:54.570  8297  8322 D BluetoothAdapterProperties: Address is:E0:DB:10:1F:C9:5E
07-28 12:43:54.570  8297  8322 E BluetoothServiceJni: populateRssiValuesNative
07-28 12:43:54.570  8297  8322 I bluedroid: getModelRssiValues
07-28 12:43:54.570  8297  8322 E BluetoothServiceJni: model_rssi_values_callback: low = -70, mid = -60, high = 127
07-28 12:43:54.570  8297  8322 D BluetoothAdapterProperties: modelRssiValuesCallback, low, mid, high = -70,-60,127
,07-28 12:43:54.570  8297  8322 D BluetoothAdapterProperties: Name is: Note3-1
,07-28 12:43:54.580  8297  8322 D BluetoothAdapterProperties: Scan Mode:20
,07-28 12:43:54.580  8297  8322 D BluetoothAdapterProperties: Discoverable Timeout:120
07-28 12:43:54.580  8297  8322 D BluetoothAdapterProperties: LE Address is:E0:B7:20:3E:93:BC
,07-28 12:43:54.580  8297  8322 E bt-btif : btif_handle_bluetooth_enable_evt: btif_core_radio_ref_count:1
07-28 12:43:54.580  8297  8349 D bt_vendor: op for 2
07-28 12:43:54.580  8297  8349 D bt_vendor: op for 6
,07-28 12:43:54.580  8297  8349 D bt_vendor: op for 7
07-28 12:43:54.580  8297  8322 E bt-btif : btif_sock_init, radio_req:0, rfc_init:0, vhci_init:0
,07-28 12:43:54.580  8297  8349 D bt_upio : proc btwrite assertion
07-28 12:43:54.580  8297  8322 E bt-btif : btif_sock_init: !radio_req && !rfc_init
,07-28 12:43:54.580  8297  8322 E bt-btif : btif_sock_init: !vhci_init
07-28 12:43:54.580  8297  8349 D bt_vendor: op for 7
07-28 12:43:54.580  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.580  8297  8322 D IOP_DB_BT: db_open: file /etc/bluetooth/iop_bt.db
07-28 12:43:54.580  8297  8349 D bt_vendor: op for 7
07-28 12:43:54.580  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.580  8297  8322 D IOP_DB_BT: db_open: db_open : handle 3026157584l, read 14063 bytes onto local cache
07-28 12:43:54.580  8297  8322 D IOP_DB_BT: db_query: id __IOPFLAGS :: key __KEY_ENABLE_VERBOSE, value 1
07-28 12:43:54.580  8297  8322 D IOP_DB_BT: db_query: result 1
,07-28 12:43:54.580  8297  8322 I         : iop_db_open: iop_db_open status 0
07-28 12:43:54.580  8297  8322 D bte_conf: Device ID record 1 : primary
07-28 12:43:54.580  8297  8322 D bte_conf:   vendorId            = 0075
07-28 12:43:54.580  8297  8322 D bte_conf:   vendorIdSource      = 0001
,07-28 12:43:54.580  8297  8322 D bte_conf:   product             = 0100
07-28 12:43:54.580  8297  8322 D bte_conf:   version             = 0200
07-28 12:43:54.580  8297  8322 D bte_conf:   clientExecutableURL = 
07-28 12:43:54.580  8297  8322 D bte_conf:   serviceDescription  = 
07-28 12:43:54.580  8297  8322 D bte_conf:   documentationURL    = 
,07-28 12:43:54.580  8297  8322 D bte_conf: bte_load_did_conf no section named DID2.
,07-28 12:43:54.590  8297  8319 D BluetoothAdapterState: CURRENT_STATE=PENDING, MSG = ENABLE_READY, isTurningOn=true, isTurningOff=false
,07-28 12:43:54.590  8297  8319 D BluetoothAdapterProperties: ScanMode =  20
07-28 12:43:54.590  8297  8319 D BluetoothAdapterProperties: State =  11
07-28 12:43:54.590   791  1679 D SecContentProvider: uri = 3 selection = isDiscoverableEnabled
,07-28 12:43:54.590  8297  8319 D BluetoothAdapterProperties: Setting state to 12
07-28 12:43:54.590  8297  8319 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,07-28 12:43:54.590   791  1574 D SettingsProvider: name = bluetooth_a2dp_sink_mode
,07-28 12:43:54.590   791  1574 D SettingsProvider: edmUri: content://com.sec.knox.provider/RestrictionPolicy3
07-28 12:43:54.590   791  1574 D SettingsProvider: projectionArgs: isSettingsChangesAllowed
07-28 12:43:54.590   791  1574 D SettingsProvider: selectionArgs: false
07-28 12:43:54.590   791  1574 D SettingsProvider: selectionArgs: 1002
07-28 12:43:54.590   791  1574 D SecContentProvider: uri = 17 selection = isSettingsChangesAllowed
,07-28 12:43:54.590   791  1574 D SettingsProvider: ret = -1
07-28 12:43:54.590  8297  8319 D BluetoothAdapterService: Bluetooth PBAP supproted is true
07-28 12:43:54.590  8297  8319 D BluetoothAdapterService: updateAdapterState state is 12
,07-28 12:43:54.590   791   791 D SettingsProvider: name = bluetooth_name
,07-28 12:43:54.590   791  1443 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:43:54.600   791  1443 D ActivityManager: caller:android.app.ApplicationThreadProxy@13b69d72, r.packageName :com.android.bluetooth
,07-28 12:43:54.600  8297  8319 D BluetoothAdapterService: Autoconnection is available 
07-28 12:43:54.600  8297  8319 D BluetoothAdapterService: updateAdapterState prevState = 11newState = 12
07-28 12:43:54.600  8297  8319 D BluetoothAdapterService: starting service from this receiver
,07-28 12:43:54.600   791  1144 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
07-28 12:43:54.600   791  1144 D ActivityManager: caller:android.app.ApplicationThreadProxy@a9d3e40, r.packageName :com.android.bluetooth
,07-28 12:43:54.610  8297  8319 I BluetoothAdapterState: Entering On State from state = 11
,07-28 12:43:54.610  8297  8349 E bt_h4   : vendor lib postload completed
07-28 12:43:54.610  8297  8322 D BluetoothAdapterProperties: Scan Mode:21
,07-28 12:43:54.610  8297  8322 D BluetoothAdapterProperties: Discoverable Timeout:120
,07-28 12:43:54.620  8297  8349 D bt_vendor: op for 7
,07-28 12:43:54.620  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.630  8297  8322 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,07-28 12:43:54.630  8297  8349 D bt_vendor: op for 7
,07-28 12:43:54.630  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.630  8297  8349 D bt_vendor: op for 7
,07-28 12:43:54.630  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.630  8297  8349 D bt_vendor: op for 7
,07-28 12:43:54.630  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.630  8297  8349 D bt_vendor: op for 7
,07-28 12:43:54.630  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.630  8297  8297 I BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED, state: 12
,07-28 12:43:54.640  8297  8349 D bt_vendor: op for 7
,07-28 12:43:54.640  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.640  8297  8349 D bt_vendor: op for 7
,07-28 12:43:54.640  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.640  8297  8349 D bt_vendor: op for 7
,07-28 12:43:54.640  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.640  8297  8349 D bt_vendor: op for 7
,07-28 12:43:54.640  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.640  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:54.640  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:54.640  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:54.640  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:43:54.640  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:54.640  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:54.640  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:54.640  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:43:54.640  8297  8349 D bt_vendor: op for 7
,07-28 12:43:54.640  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.640  8297  8349 D bt_vendor: op for 7
,07-28 12:43:54.640  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.650  8297  8349 D bt_vendor: op for 7
,07-28 12:43:54.650  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.650  8297  8349 D bt_vendor: op for 7
,07-28 12:43:54.650  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.650  8297  8349 D bt_vendor: op for 7
,07-28 12:43:54.650  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.650  8297  8349 D bt_vendor: op for 7
,07-28 12:43:54.650  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.650  7441  7441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:43:54.650  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:54.660  8297  8349 D bt_vendor: op for 7
,07-28 12:43:54.670  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.670  8297  8349 D bt_vendor: op for 7
,07-28 12:43:54.670  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.670  8297  8349 D bt_vendor: op for 7
07-28 12:43:54.670  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.670  8297  8349 D bt_vendor: op for 7
,07-28 12:43:54.670  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.670  8297  8349 D bt_vendor: op for 7
,07-28 12:43:54.670  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.670  8297  8349 D bt_vendor: op for 7
,07-28 12:43:54.670  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.680  8297  8349 D bt_vendor: op for 7
,07-28 12:43:54.680  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.680  8297  8349 D bt_vendor: op for 7
,07-28 12:43:54.680  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.680  8297  8349 D bt_vendor: op for 7
07-28 12:43:54.680  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.680  8297  8349 D bt_vendor: op for 7
07-28 12:43:54.680  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.680  8297  8349 D bt_vendor: op for 7
,07-28 12:43:54.680  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.760   791  1043 I art     : Explicit concurrent mark sweep GC freed 20980(1318KB) AllocSpace objects, 4(64KB) LOS objects, 30% free, 37MB/53MB, paused 1.168ms total 153.531ms
,07-28 12:43:54.760   791  1043 D ActivityManager: bindService callerProcessName:com.vlingo.midas, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:43:54.770  7624  7636 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:43:54.770   791  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:43:54.770  3400  3409 E BluetoothHeadset: BluetoothHeadset service is binded
07-28 12:43:54.770   791  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
07-28 12:43:54.770   791  1043 E BluetoothHeadset: BluetoothHeadset service is binded
07-28 12:43:54.770   791  1043 D BluetoothPan: Binding service...
,07-28 12:43:54.770   791  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
,07-28 12:43:54.770  1313  1329 D Bluetoothsap: onBluetoothStateChange: up=true
,07-28 12:43:54.770  8297  8297 I BluetoothPbapService: Handler(): got msg=1
07-28 12:43:54.770  1313  1329 D Bluetoothsap: Binding service...
,07-28 12:43:54.770   791  1476 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-28 12:43:54.770  1313  1329 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:2124 android.content.ContextWrapper.bindService:559 com.broadcom.bt.service.sap.BluetoothSap.doBind:186 com.broadcom.bt.service.sap.BluetoothSap$1.onBluetoothStateChange:156 android.bluetooth.IBluetoothStateChangeCallback$Stub.onTransact:55 
,07-28 12:43:54.770   791  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: com.broadcom.bt.service.sap.IBluetoothSap
,07-28 12:43:54.780  8297  8374 V BluetoothPbapService: PBAP Service initSocket try: 0
,07-28 12:43:54.780  1313  1329 D Bluetoothsap: bindService called to Bluetooth SAP Service
,07-28 12:43:54.780   791   791 D BluetoothPan: BluetoothPAN Proxy object connected
,07-28 12:43:54.780  1313  1327 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 12:43:54.780   791  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-28 12:43:54.780   791  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:43:54.780  1313  1313 D Bluetoothsap: BluetoothSAP Proxy object connected
07-28 12:43:54.780  1404  3550 E BluetoothHeadset: BluetoothHeadset service is binded
07-28 12:43:54.780  1313  1313 D SapProfile: Bluetooth service connected
07-28 12:43:54.780  1313  1313 D Bluetoothsap: getConnectedDevices()
,07-28 12:43:54.780  8297  8374 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:43:54.780  8297  8374 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[72]}
07-28 12:43:54.780   791  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
07-28 12:43:54.780  8297  8374 D BluetoothSocket: bindListen(), new LocalSocket 
07-28 12:43:54.780  8297  8374 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-28 12:43:54.780  8297  8374 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@18411157
07-28 12:43:54.780  8297  8374 D BluetoothSocket: channel: 19
07-28 12:43:54.780  8297  8349 D bt_vendor: op for 7
07-28 12:43:54.780  8297  8349 D bt_upio : BT_WAKE is asserted already
07-28 12:43:54.780  8297  8374 D BluetoothPbapService: PBAP Socket is BluetoothServerSocket
,07-28 12:43:54.780  1313  1329 E BluetoothHeadset: BluetoothHeadset service is binded
07-28 12:43:54.780  1313  1313 D BluetoothA2dp: Proxy object connected
07-28 12:43:54.780  1313  1313 D A2dpProfile: Bluetooth service connected
,07-28 12:43:54.780   791  1043 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:43:54.780   791  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-28 12:43:54.780  1313  1327 D BluetoothInputDevice: onBluetoothStateChange: up=true
07-28 12:43:54.780   791   791 D BluetoothA2dp: Proxy object connected
,07-28 12:43:54.790  1313  1313 D HeadsetProfile: Bluetooth service connected
07-28 12:43:54.790   791  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothInputDevice
,07-28 12:43:54.790   791  1043 D ActivityManager: bindService callerProcessName:com.android.phone, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:43:54.790  1426  3549 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:43:54.790  1313  1329 D BluetoothMap: onBluetoothStateChange: up=true
,07-28 12:43:54.790   791  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothMap
,07-28 12:43:54.790  1313  1313 D BluetoothInputDevice: Proxy object connected
07-28 12:43:54.790  3400  3410 D BluetoothA2dp: onBluetoothStateChange: up=true
07-28 12:43:54.790  1313  1313 D HidProfile: Bluetooth service connected
,07-28 12:43:54.790   791  1043 D ActivityManager: bindService callerProcessName:com.samsung.android.providers.context, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothA2dp
,07-28 12:43:54.790  8297  8305 D BluetoothA2dp: onBluetoothStateChange: up=true
,07-28 12:43:54.790  3400  3400 D BluetoothA2dp: Proxy object connected
,07-28 12:43:54.790  1313  1313 D BluetoothMap: Proxy object connected
07-28 12:43:54.790  1313  1313 D MapProfile: Bluetooth service connected
,07-28 12:43:54.790   791  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:43:54.790  1404  3550 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:43:54.790  1313  1329 D BluetoothPbap: onBluetoothStateChange: up=true
,07-28 12:43:54.800   791  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPbap
,07-28 12:43:54.800   791  1043 D ActivityManager: bindService callerProcessName:com.android.server.telecom, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothHeadset
,07-28 12:43:54.800  1313  1313 D BluetoothPbap: Proxy object connected
07-28 12:43:54.800  1313  1313 D PbapServerProfile: Bluetooth service connected
07-28 12:43:54.800  1404  1419 E BluetoothHeadset: BluetoothHeadset service is binded
,07-28 12:43:54.800  1313  5812 D BluetoothPan: Binding service...
,07-28 12:43:54.800   791  1043 D ActivityManager: bindService callerProcessName:com.android.settings, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothPan
07-28 12:43:54.800  1313  1313 D BluetoothPan: BluetoothPAN Proxy object connected
07-28 12:43:54.800   791  1043 D ActivityManager: bindService callerProcessName:android, calleePkgName: com.android.bluetooth, action: android.bluetooth.IBluetoothGatt
,07-28 12:43:54.800  1313  1313 D PanProfile: Bluetooth service connected
,07-28 12:43:54.800   791   791 W InputMethodManagerService: InputMethodService onReceive() intentActionandroid.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:54.800   791   791 I InputMethodManagerService: [BT Setting State] State =12
07-28 12:43:54.800   791   791 I InputMethodManagerService: [BT Setting off -> on] mBTKeyboardCount =0, KEYBOARD_BT(0)
,07-28 12:43:54.800  7624  7624 D BluetoothManager: [SVoiceBT, LatencyCheck] BTStateBroadcastReceiver Received intent: android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:54.800  1193  1193 D BluetoothTile:  onBluetoothStateChange:
,07-28 12:43:54.810  1404  1404 D BluetoothHeadset: registerListener : 11, listenercom.android.server.telecom.wearable.BluetoothMessageListener@117d4067, true
07-28 12:43:54.810  1865  1865 I SamsungIME: STATE_CHANGED = 12, KEYBOARD_BT(0), mBTKeyboardCount =0
,07-28 12:43:54.810   791  1043 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 0 receivers.
07-28 12:43:54.810  1313  1313 V BluetoothEventManager: Received android.bluetooth.adapter.action.STATE_CHANGED
07-28 12:43:54.810   791  1259 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-28 12:43:54.810   791  1259 D ActivityManager: caller:android.app.ApplicationThreadProxy@30d791c9, r.packageName :com.google.android.gms
,07-28 12:43:54.810  1404  1404 D BluetoothHeadset: registerMessageListener
07-28 12:43:54.810  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:54.810  1193  1193 D BluetoothTile:  onBluetoothPairedDevicesChanged:
,07-28 12:43:54.810  1193  1193 D BluetoothTile: onReceive : android.bluetooth.adapter.action.STATE_CHANGED
,07-28 12:43:54.810  8297  8375 D BluetoothMapMasInstance: set MAP SDP message type : 1
,07-28 12:43:54.810  1313  1313 W LocalBluetoothProfileManager: Warning: SAP profile was previously added but the UUID is now missing.
,07-28 12:43:54.810  8297  8305 D HeadsetService: registerMessageListener
07-28 12:43:54.810  1313  1313 W LocalBluetoothProfileManager: Warning: HID profile was previously added but the UUID is now missing.
07-28 12:43:54.810  8297  8305 D HeadsetService: registerMessageListener
07-28 12:43:54.810  8297  8331 D HeadsetStateMachine: Disconnected process message: 70
07-28 12:43:54.810  8297  8331 D HeadsetStateMachine: processRegisterMessageListener : 11, com.samsung.bt.hfp.IMessageListener$Stub$Proxy@27471444
,07-28 12:43:54.810  1404  1404 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState
07-28 12:43:54.810  1404  1404 I Telecom : BluetoothPhoneService: updateHeadsetWithCallState numActive 0, numHeld 0, callState 6, ringing number [da39a3ee5e6b4b0d3255bfef95601890afd80709], ringing type 128
,07-28 12:43:54.820  8297  8331 D HeadsetStateMachine: Disconnected process message: 9
,07-28 12:43:54.820  1193  1595 D BluetoothTile:  handleUpdatestate:false name:null
07-28 12:43:54.820  8297  8331 D HeadsetStateMachine: mNumActive: 0 mNumHeld: 0 mCallState: 6
07-28 12:43:54.820  1193  1595 D STATUSBAR-QSTileView: onStateChanged: Bluetooth
,07-28 12:43:54.820  8297  8375 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:43:54.820  8297  8375 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[74]}
07-28 12:43:54.820  8297  8375 D BluetoothSocket: bindListen(), new LocalSocket 
07-28 12:43:54.820  8297  8375 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-28 12:43:54.820  8297  8375 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@1208892d
07-28 12:43:54.820  8297  8375 D BluetoothSocket: channel: 5
07-28 12:43:54.820  8297  8349 D bt_vendor: op for 7
07-28 12:43:54.820  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.820   791   831 D StatusBarManagerService: setIcon slot=bluetooth index=16 icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:43:54.820   791  1679 D StatusBarManagerService: setIconVisibility slot=bluetooth visible=true
,07-28 12:43:54.820  1193  1193 D PhoneStatusBar: updateIcon slot=bluetooth index=16 viewIndex=2 old=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=false num=0 ) icon=StatusBarIcon(pkg=com.android.systemuiuser=0 id=0x7f02031d level=0 visible=true num=0 )
,07-28 12:43:54.820  1313  1313 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:2051 android.content.ContextWrapper.startService:533 android.content.ContextWrapper.startService:533 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,07-28 12:43:54.820   791  1468 D ActivityManager: startService callerProcessName:com.android.settings, calleePkgName: com.android.settings
07-28 12:43:54.820   791  1468 D ActivityManager: caller:android.app.ApplicationThreadProxy@2da2d6fc, r.packageName :com.android.settings
,07-28 12:43:54.820   312   312 D audio_hw_primary: adev_set_parameters: enter: A2dpSuspended=false
,07-28 12:43:54.820   312   312 V voice   : voice_set_parameters: enter: A2dpSuspended=false
07-28 12:43:54.820   312   312 V voice   : voice_set_parameters: exit with code(-2)
07-28 12:43:54.820   312   312 V msm8974_platform: platform_set_parameters: enter: A2dpSuspended=false
07-28 12:43:54.820   312   312 V msm8974_platform: platform_set_parameters: exit with code(-2)
07-28 12:43:54.820   312   312 D audio_hw_hfp: audio_extn_hfp_set_parameters: enter
07-28 12:43:54.820   312   312 V audio_hw_primary: adev_set_parameters: exit
,07-28 12:43:54.820  8297  8331 E HeadsetStateMachine: terminateScoUsingVirtualVoiceCall:No present call to terminate
,07-28 12:43:54.830  1313  1313 D DockEventReceiver: finishStartingService: stopping service
,07-28 12:43:54.830  1313  1313 D BluetoothNotiBroadcastReceiver: onReceive
,07-28 12:43:54.830  8297  8297 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@159910fa
07-28 12:43:54.830  8297  8297 D BtConfig.SecureMode: isSecureModeOn:false
,07-28 12:43:54.840   791  1366 D ActivityManager: startService callerProcessName:com.android.bluetooth, calleePkgName: com.android.bluetooth
,07-28 12:43:54.840   791  1366 D ActivityManager: caller:android.app.ApplicationThreadProxy@471dbda, r.packageName :com.android.bluetooth
,07-28 12:43:54.870   791  1366 D SecContentProvider: uri = 4 selection = isProfileAuthorizedBySecurityPolicy
,07-28 12:43:54.880  8297  8388 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,07-28 12:43:54.880  8297  8388 D BluetoothSocket: bindListen(), SocketState: INIT, mPfd: {ParcelFileDescriptor: FileDescriptor[78]}
07-28 12:43:54.880  8297  8388 D BluetoothSocket: bindListen(), new LocalSocket 
07-28 12:43:54.880  8297  8388 D BluetoothSocket: bindListen(), new LocalSocket.getInputStream() 
07-28 12:43:54.880  8297  8388 D BluetoothSocket: bindListen(), readInt mSocketIS: android.net.LocalSocketImpl$SocketInputStream@2cb6d44f
07-28 12:43:54.880  8297  8388 D BluetoothSocket: channel: 12
07-28 12:43:54.880  8297  8388 I BtOppRfcommListener: Accept thread started.
07-28 12:43:54.880  8297  8349 D bt_vendor: op for 7
07-28 12:43:54.880  8297  8349 D bt_upio : BT_WAKE is asserted already
,07-28 12:43:54.900  1897  1897 D EasyUnlockReceiver: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.easyunlock.authorization.BluetoothStateChangeReceiver (has extras) }.
,07-28 12:43:54.910   791  1638 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
07-28 12:43:54.910   791  1638 D ActivityManager: caller:android.app.ApplicationThreadProxy@4bb49e7, r.packageName :com.google.android.gms
,07-28 12:43:54.910  1897  8391 D EasyUnlockInitService: Handling intent for initializer IntentService.
,07-28 12:43:54.920  1897  1897 D BtServices: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.proximity.BluetoothServicesAdapterStateChangeReceiver (has extras) }.
,07-28 12:43:54.930   791  1532 D ActivityManager: caller:android.app.ApplicationThreadProxy@225b2b00, r.packageName :com.google.android.gms
,07-28 12:43:54.930  1897  8391 D EasyUnlockInitService: Not initializing EasyUnlock: remote_devices=0, bluetooth_on=true
,07-28 12:43:54.960  7441  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:54.960  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:54.960  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:54.960  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
07-28 12:43:54.960  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:54.960  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:54.960  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:54.960  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:43:54.960  7441  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:43:54.960  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:54.960  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b4b5712 added. We now have 8 listener(s)
07-28 12:43:54.960  7441  7508 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:43:54.960  7441  7508 I WifiManager: packageName : com.test.thalitest
,07-28 12:43:54.960   791  1358 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-28 12:43:54.960   791  1358 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-28 12:43:54.960   791  1358 D SecContentProvider2: mCursor = null
,07-28 12:43:54.960   791  1358 D WifiService: setWifiEnabled: false pid=7441, uid=10079
,07-28 12:43:54.960   791  1358 D SettingsProvider: name = wifi_on
,07-28 12:43:54.970  7441  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:54.970  7441  7508 I WifiManager: packageName : com.test.thalitest
07-28 12:43:54.970   791  1366 D SecContentProvider: uri = 18 selection = isWifiEnabled
07-28 12:43:54.970   791  1366 D SecContentProvider2: uri = 20 selection = isWifiStateChangeAllowed
07-28 12:43:54.970   791  1366 D SecContentProvider2: mCursor = null
,07-28 12:43:54.970   791  1366 D WifiService: setWifiEnabled: true pid=7441, uid=10079
07-28 12:43:54.970   791  1366 W ActivityManager: Permission Denial: getCurrentUser() from pid=7441, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-28 12:43:54.970   791  1366 W WifiService: Failed getting userId using ActivityManagerNative
07-28 12:43:54.970   791  1366 W WifiService: java.lang.SecurityException: Permission Denial: getCurrentUser() from pid=7441, uid=10079 requires android.permission.INTERACT_ACROSS_USERS
07-28 12:43:54.970   791  1366 W WifiService: 	at com.android.server.am.ActivityManagerService.getCurrentUser(ActivityManagerService.java:23226)
07-28 12:43:54.970   791  1366 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2187)
07-28 12:43:54.970   791  1366 W WifiService: 	at com.android.server.wifi.WifiServiceImpl.setWifiEnabled(WifiServiceImpl.java:2175)
07-28 12:43:54.970   791  1366 W WifiService: 	at android.net.wifi.IWifiManager$Stub.onTransact(IWifiManager.java:223)
07-28 12:43:54.970   791  1366 W WifiService: 	at android.os.Binder.execTransact(Binder.java:446)
,07-28 12:43:54.970   791  1366 D SettingsProvider: name = wifi_on
,07-28 12:43:54.970   791  1149 E WifiHW  : ##################### set firmware type 0 #####################
,07-28 12:43:54.970   299  1061 I WifiHW  : wifi_change_fw_path(): fwpath = /system/etc/wifi/bcmdhd_sta.bin
,07-28 12:43:54.970   299  1061 I WifiHW  : module is semco
07-28 12:43:54.970   299  1061 E WifiHW  : ==========[WIFI] SEMCO MODULE ===========
07-28 12:43:54.970   299  1061 I WifiHW  : wifi_change_nvram_path() = /system/etc/wifi/nvram_net.txt
07-28 12:43:54.970   299  1061 E WifiHW  : TEMP_FAILURE_RETRY complete
07-28 12:43:54.970   299  1061 D SoftapController: Softap fwReload - Ok
,07-28 12:43:54.970   299  1061 D CommandListener: Setting iface cfg
07-28 12:43:54.970   299  1061 D CommandListener: Trying to bring down wlan0
,07-28 12:43:54.970   299  1061 D CommandListener: Clearing all IP addresses on wlan0
,07-28 12:43:54.980   791  1149 E WifiHW  : supplicant_name : p2p_supplicant
,07-28 12:43:54.980   791  1149 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,07-28 12:43:54.980   791   791 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:43:54.980  1193  1193 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x0/(null) mQSWifiIconId=0x0/(null) mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:43:54.980  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=false enabledDesc:null
,07-28 12:43:54.980  1193  1193 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:54.980  1193  1193 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(2)
07-28 12:43:54.980  1193  1193 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:54.980  1313  1313 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:54.980   791  1153 D SmartBondingService: getNetworkEnabled : wifi : false mobile : true
07-28 12:43:54.980  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:54.980  1193  1595 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-28 12:43:54.980  1193  1193 D HotspotTile: onReceive : 2, 0
,07-28 12:43:54.990  7031  7031 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-28 12:43:54.990   791  1476 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:54.990  7514  7514 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:43:54.990  7514  7514 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:43:54.990  7514  7514 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:43:54.990  7514  7514 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:43:55.010  8395  8395 I wpa_supplicant: [wpa_supplicant_init]: use SECRIL
07-28 12:43:55.010  8395  8395 I wpa_supplicant: Successfully initialized wpa_supplicant
,07-28 12:43:55.010  8395  8395 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-28 12:43:55.010  8395  8395 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-28 12:43:55.010   387   387 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8395
07-28 12:43:55.010   387   387 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x0000010C
07-28 12:43:55.010  8395  8395 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-28 12:43:55.010  8395  8395 I wpa_supplicant: ssSupport state is = 1
,07-28 12:43:55.010  8395  8395 I wpa_supplicant: >>>>> GET KEY, IV <<<<<
,07-28 12:43:55.020  8395  8395 I SecureStorage: [INFO]: SPID(0x00000000)Processing data
,07-28 12:43:55.020   387   387 I SecureStorage: [INFO]: SPID(0x00000004)Credentials: uid 1010, gid 1010, pid 8395
07-28 12:43:55.020   387   387 I SecureStorage: [INFO]: SPID(0x00000004)Received function mask & code: 0x00000106
,07-28 12:43:55.280   387   387 I SecureStorage: [INFO]: SPID(0x00000004)Secure Storage Daemon finished processing with result: 0
,07-28 12:43:55.300   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:43:55.540  8395  8395 I SecureStorage: [INFO]: SPID(0x00000000)Processing data has been completed
,07-28 12:43:55.590  8395  8395 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
,07-28 12:43:55.590  8395  8395 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-28 12:43:55.590   387   387 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8395
07-28 12:43:55.590   387   387 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,07-28 12:43:55.590  8395  8395 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-28 12:43:55.590  8395  8395 I wpa_supplicant: ssSupport state is = 1
07-28 12:43:55.590  8395  8395 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,07-28 12:43:55.590  8395  8395 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-28 12:43:55.590  8395  8395 E wpa_supplicant: SIM READ ERROR
07-28 12:43:55.590  8395  8395 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,07-28 12:43:55.590  8395  8395 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-28 12:43:55.590  8395  8395 E wpa_supplicant: SIM READ ERROR
07-28 12:43:55.590  8395  8395 I wpa_supplicant: Blacklist: Clear (all) 
,07-28 12:43:55.600  8395  8395 I wpa_supplicant: wpa_default_ap_write_once
,07-28 12:43:55.600  8395  8395 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-28 12:43:55.600  8395  8395 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:43:55.600  8395  8395 E wpa_supplicant: getSavedIMSI cannot open /data/misc/wifi/.kmem: No such file or directory
07-28 12:43:55.600  8395  8395 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
,07-28 12:43:55.600  8395  8395 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
,07-28 12:43:55.600  8395  8395 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-28 12:43:56.250   791  1152 E Tethering: No numeric data
,07-28 12:43:56.250   791  1152 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,07-28 12:43:56.250   791  1146 V NetworkStats: performPollLocked(flags=0x1)
07-28 12:43:56.250  1193  1193 D HotspotTile: onReceive : android.net.conn.TETHER_STATE_CHANGED
07-28 12:43:56.250  1193  1193 D HotspotTile: updateTetherState():false, false
,07-28 12:43:56.250   791  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:43:56.250   791  1146 D NetworkStatsFactory: UpdateStatsForKnox
,07-28 12:43:56.250   791  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:56.250   791  1146 V NetworkStats: performPollLocked() took 4ms
,07-28 12:43:56.250   791  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:43:56.250   791  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:43:56.250   791  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:43:56.260  8395  8395 I wpa_supplicant: wlan0: Setting scan request: 0 sec 100000 usec
,07-28 12:43:56.270  8395  8395 I wpa_supplicant: wlan0: State: DISCONNECTED -> DISCONNECTED
,07-28 12:43:56.270  8395  8395 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-28 12:43:56.270  8395  8395 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
07-28 12:43:56.270   387   387 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8395
07-28 12:43:56.270   387   387 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
,07-28 12:43:56.270  8395  8395 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-28 12:43:56.270  8395  8395 I wpa_supplicant: ssSupport state is = 1
07-28 12:43:56.270  8395  8395 I SecureStorage: [INFO]: SPID(0x00000000)Checking if this device supports Secure Storage
07-28 12:43:56.270  8395  8395 I SecureStorage: [INFO]: SPID(0x00000000)This device supports Secure Storage
,07-28 12:43:56.270   387   387 I SecureStorage: [INFO]: SPID(0x00000005)Credentials: uid 1010, gid 1010, pid 8395
07-28 12:43:56.270   387   387 I SecureStorage: [INFO]: SPID(0x00000005)Received function mask & code: 0x0000010C
07-28 12:43:56.270  8395  8395 I SecureStorage: [INFO]: SPID(0x00000000)SS Daemon is running
07-28 12:43:56.270  8395  8395 I wpa_supplicant: ssSupport state is = 1
07-28 12:43:56.270  8395  8395 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:43:56.270  8395  8395 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-28 12:43:56.270  8395  8395 E wpa_supplicant: SIM READ ERROR
07-28 12:43:56.270  8395  8395 I wpa_supplicant: wpa_default_ap_write_once
07-28 12:43:56.270  8395  8395 I wpa_supplicant: There is no /data/misc/wifi/default_ap.check. Start copy default ap
07-28 12:43:56.270  8395  8395 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,07-28 12:43:56.290  8395  8395 I wpa_supplicant: p2p0: State: DISCONNECTED -> INACTIVE
07-28 12:43:56.290  8395  8395 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=2 BSSID=00.00.00 SSID=
,07-28 12:43:56.300  8395  8395 I wpa_supplicant: p2p0: State: INACTIVE -> DISCONNECTED
07-28 12:43:56.300  8395  8395 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=0 BSSID=00.00.00 SSID=
,07-28 12:43:56.300   791  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:2
,07-28 12:43:56.300   791  1149 D WifiNative-HAL: callSECApiBoolean - ID [21]
,07-28 12:43:56.300  8395  8395 I wpa_supplicant: HOTSPOT20_ENABLE called
07-28 12:43:56.300  8395  8395 I wpa_supplicant: [set_default_callid]: set_default_callid simnumber = 0,default_callid = 0
07-28 12:43:56.300  8395  8395 E wpa_supplicant: getIMSI cannot open /data/misc/radio/kmem: No such file or directory
07-28 12:43:56.300  8395  8395 E wpa_supplicant: SIM READ ERROR
07-28 12:43:56.300  8395  8395 I wpa_supplicant: Blacklist: Clear (all) 
,07-28 12:43:56.300   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:43:56.330   791  1149 D WifiNative-HAL: callSECApiInt - ID [210]
07-28 12:43:56.330  8395  8395 I wpa_supplicant: Skip scan - bUseNetwork false
,07-28 12:43:56.330   791  1149 D WifiConfigStore: Loading config and enabling all networks 
,07-28 12:43:56.330  1193  1193 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:43:56.330  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-28 12:43:56.330  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:56.330  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:56.330  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:56.330  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:56.330  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:56.330  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:56.330  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:56.330  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:56.330  1193  1193 D STATUSBAR-WifiQuickSettingButton: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:56.330  1193  1193 D HotspotTile: onReceive : android.net.wifi.WIFI_STATE_CHANGED
07-28 12:43:56.330  1193  1193 D STATUSBAR-WifiQuickSettingButton: Wifi onReceive(3)
,07-28 12:43:56.330  1193  1595 D STATUSBAR-QSTileView: onStateChanged: Wi-Fi
07-28 12:43:56.330   791   791 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:43:56.330  1313  1313 D WifiCredService: Action received :android.net.wifi.WIFI_STATE_CHANGED
,07-28 12:43:56.330  1193  1193 D HotspotTile: onReceive : 3, 0
,07-28 12:43:56.340  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:56.340  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:56.340  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:56.340  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:56.340  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:56.340  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:56.340  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:56.340  7441  7441 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:43:56.340   791  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-28 12:43:56.340  7441  7441 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:43:56.340  7031  7031 E SignOutReceiver: WIFI_STATE_CHANGED_ACTION
,07-28 12:43:56.340   791  1469 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:56.340  7514  7514 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:43:56.340  7514  7514 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:43:56.340  7514  7514 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:43:56.340  7514  7514 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:43:56.340   791  1149 E WifiConfigStore: Not a HS20
,07-28 12:43:56.360   791  1149 E WifiConfigStore: Not a HS20
,07-28 12:43:56.360   791  1149 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,07-28 12:43:56.360   791  1149 D WifiNative-HAL: callSECApiInt - ID [65]
,07-28 12:43:56.370   791  1149 D WifiNative-HAL: callSECApiBoolean - ID [13]
07-28 12:43:56.370  8395  8395 I wpa_supplicant: USE_NETWORK : USE_NETWORK ON
07-28 12:43:56.370  8395  8395 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
,07-28 12:43:56.370  8395  8395 I wpa_supplicant: reset timer : RESET_TIMER 0
07-28 12:43:56.370  8395  8395 I wpa_supplicant: P2P: Current p2p state = IDLE
07-28 12:43:56.370  8395  8395 I wpa_supplicant: wlan0: State: DISCONNECTED -> SCANNING
07-28 12:43:56.370  8395  8395 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00.00.00 SSID=
07-28 12:43:56.370  8395  8395 I wpa_supplicant: First Scan Start
,07-28 12:43:56.370  8395  8395 I wpa_supplicant: Scan requested (ret=0) - scan timeout 30 seconds
,07-28 12:43:56.370   791  1149 D WifiNative-HAL: Setting external_sim to 1
07-28 12:43:56.370  7647  7647 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,07-28 12:43:56.370   791  1149 D WifiStateMachine: Setting OUI to DA-A1-19
07-28 12:43:56.370   791  1149 I WifiNative-HAL: startHal
07-28 12:43:56.370   791  1149 E wifi    : getStaticLongField sWifiHalHandle 0x933b986c
07-28 12:43:56.370   791  1149 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0xf017f2
07-28 12:43:56.370   791  1149 I WifiNative-HAL: Could not start hal
,07-28 12:43:56.380  8297  8349 D bt_vendor: op for 7
,07-28 12:43:56.390   791  1149 E native  : do suspend true
,07-28 12:43:56.400   791  1148 D WifiP2pService: P2pDisabledState{ what=131203 }
,07-28 12:43:56.400   791  1149 E WifiStateMachine: skipWifiStateBroadcast:false, LastBroadcastedWifiState:3
,07-28 12:43:56.400   791   791 D WifiScanningService: SCAN_AVAILABLE : 3
07-28 12:43:56.400   791   791 D RttService: SCAN_AVAILABLE : 3
07-28 12:43:56.400   791  1166 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
,07-28 12:43:56.400   791  1166 I WifiNative-HAL: startHal
07-28 12:43:56.400   791  1167 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:56.400   791  1166 E wifi    : getStaticLongField sWifiHalHandle 0x9af9699c
07-28 12:43:56.400   791  1166 D wifi    : halHandle = 0x0, mVM = 0xb4f5c280, mCls = 0x6017ea
,07-28 12:43:56.400   791  1166 I WifiNative-HAL: Could not start hal
07-28 12:43:56.400   791  1166 E WifiScanningService: could not start HAL
,07-28 12:43:56.400   299  1061 D CommandListener: Setting iface cfg
07-28 12:43:56.400   299  1061 D CommandListener: Trying to bring up p2p0
07-28 12:43:56.400   791  1148 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,07-28 12:43:56.400   791  1148 D WifiP2pService: P2pEnablingState
07-28 12:43:56.400   791  1148 D WifiP2pService: P2pEnablingState{ what=147457 }
07-28 12:43:56.400   791  1148 D WifiP2pService: P2p socket connection successful
,07-28 12:43:56.400   791  1148 D WifiP2pService: P2pEnabledState
,07-28 12:43:56.400   791  1046 D WifiDisplayController: Received WIFI_P2P_STATE_CHANGED_ACTION: enabled=true
,07-28 12:43:56.400   791  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-28 12:43:56.400   791  1046 D WifiDisplayController: disconnect
07-28 12:43:56.400   791  1046 D WifiDisplayController: updateConnection
07-28 12:43:56.400   791  1046 D WifiDisplayController: updateScanState() mScanRequested = false, mWfdEnabled = false, mDiscoverPeersInProgress = false
07-28 12:43:56.400   791  1046 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
,07-28 12:43:56.400   791   791 E WifiStateMachine: BroadcastReceiver : WIFI_P2P_STATE_CHANGED_ACTION is : android.net.wifi.p2p.STATE_CHANGED
,07-28 12:43:56.400  1193  1193 D AllShareCastTile: action: android.hardware.display.action.WIFI_DISPLAY_STATUS_CHANGED
,07-28 12:43:56.400   791  1638 D WifiDisplayAdapter: getWifiDisplayStatusLocked: result=WifiDisplayStatus{featureState=2, scanState=0, activeDisplayState=0, activeDisplay=null, displays=[], sessionInfo=WifiDisplaySessionInfo: Client/Owner: Client GroupId:  Passphrase:  SessionId: 0 IP Address: , connectedState=-1, networkQoS=0}
07-28 12:43:56.400   791  1149 E WifiStateMachine: DriverStatedState::CMD_SEC_STRING_API - inner msg [207]
07-28 12:43:56.400   791  1149 D WifiNative-HAL: callSECStringApiVoid - ID [215]
07-28 12:43:56.400   791  1149 E WifiNative-HAL: invaild command id : 215
,07-28 12:43:56.400  1193  1193 D AllShareCastTile: wifi display status changed! scanstate : 0, ActiveDisplayState : 0
,07-28 12:43:56.400   791  1148 D WifiP2pService: sending p2p connection changed broadcast: DISCONNECTED
,07-28 12:43:56.410   791  1046 D WifiDisplayController: Received WIFI_P2P_CONNECTION_CHANGED_ACTION: networkInfo=[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:56.410   791  1046 D WifiDisplayAdapter: onP2pDisconnected
07-28 12:43:56.410   791  1046 D IpRemoteDisplayController: disconnectWfdBridgeServer
07-28 12:43:56.410   791  1046 D IpRemoteDisplayController: WfdBridgeServer is already null
07-28 12:43:56.410   791  1151 E ConnectivityService: updateNetworkInfo()
,07-28 12:43:56.410   791  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI_P2P, state = DISCONNECTED
07-28 12:43:56.410  7676  7676 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.STATE_CHANGED
,07-28 12:43:56.410  1313  1313 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-28 12:43:56.410  1313  1313 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
07-28 12:43:56.410   791  1428 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:56.410  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
07-28 12:43:56.410   791  1532 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:56.410  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:43:56.410  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:43:56.410  1313  1313 I NearbySettings: MountReceiver.onReceive - Set preference state off
07-28 12:43:56.410  1313  2966 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:43:56.420  7175  7175 D FileShare-Server: ServerBroadcastReceiver.onReceive - action android.net.wifi.p2p.CONNECTION_STATE_CHANGE // null
,07-28 12:43:56.420  7676  7676 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive() : android.net.wifi.p2p.CONNECTION_STATE_CHANGE
,07-28 12:43:56.420  7676  7676 D WifiDirectBR: WifiDirectBroadcastReceiver::onReceive(), Action : WifiP2pManager.WIFI_P2P_CONNECTION_CHANGED_ACTION, isConnected() == false
07-28 12:43:56.420  7676  7676 W ContextImpl: Implicit intents with startService are not safe: Intent { act=com.samsung.shareshot.IShareShotService } android.content.ContextWrapper.stopService:538 android.content.ContextWrapper.stopService:538 com.samsung.shareshot.WifiDirectBroadcastReceiver.onReceive:59 
,07-28 12:43:56.420  7676  7676 D WifiDirectBR: stopServiceTest : false
,07-28 12:43:56.430  8395  8395 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-28 12:43:56.450  8395  8395 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=UNKNOWN
,07-28 12:43:56.450   791  1148 D WifiNative-HAL: p2pGetDeviceAddress
,07-28 12:43:56.460   791  1148 D WifiNative-HAL: p2pGetDeviceAddress returning ea:50:8b:de:28:a3
,07-28 12:43:56.460   791  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-28 12:43:56.460   791  1046 D WifiDisplayController: Received WIFI_P2P_THIS_DEVICE_CHANGED_ACTION: mThisDevice= Device: Note3-1
07-28 12:43:56.460   791  1046 D WifiDisplayController:  deviceAddress: ea:50:8b:de:28:a3
07-28 12:43:56.460   791  1046 D WifiDisplayController:  primary type: 10-0050F204-5
07-28 12:43:56.460   791  1046 D WifiDisplayController:  secondary type: null
07-28 12:43:56.460   791  1046 D WifiDisplayController:  wps: 0
07-28 12:43:56.460   791  1046 D WifiDisplayController:  grpcapab: 0
07-28 12:43:56.460   791  1046 D WifiDisplayController:  devcapab: 0
07-28 12:43:56.460   791  1046 D WifiDisplayController:  status: 3
07-28 12:43:56.460   791  1046 D WifiDisplayController:  wfdInfo: null
07-28 12:43:56.460   791  1046 D WifiDisplayController:  groupownerAddress: null
07-28 12:43:56.460   791  1046 D WifiDisplayController:  GOdeviceName: null
07-28 12:43:56.460   791  1046 D WifiDisplayController:  interfaceAddress: 
07-28 12:43:56.460   791  1046 D WifiDisplayController:  SConnectInfo : null
,07-28 12:43:56.460   791  1148 D WifiP2pService: DeviceAddress: ea:28:a3
,07-28 12:43:56.460   791  1149 D SecContentProvider2: mCursor = null
,07-28 12:43:56.460   791  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-28 12:43:56.460   791  1149 D SecContentProvider2: mCursor = null
,07-28 12:43:56.470   791  1148 D WifiP2pService: sending p2p persistent groups changed broadcast
,07-28 12:43:56.470   791  1148 D WifiP2pService: InactiveState
07-28 12:43:56.470   791  1148 D WifiP2pService: InactiveState{ what=143376 }
,07-28 12:43:56.470   791  1148 D WifiP2pService: P2pEnabledState{ what=143376 }
07-28 12:43:56.470  8395  8395 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=PL
,07-28 12:43:56.470   791  1148 D WifiP2pService: InactiveState{ what=143376 }
,07-28 12:43:56.470   791  1148 D WifiP2pService: P2pEnabledState{ what=143376 }
,07-28 12:43:56.580  8297  8360 D bt_upio : ..proc_btwrite_timeout..
,07-28 12:43:56.990  7441  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
07-28 12:43:56.990  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:56.990  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:56.990  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:56.990  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:56.990  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:56.990  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:56.990  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:43:56.990  7441  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:43:56.990  7441  7508 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,07-28 12:43:57.000  7441  7508 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,07-28 12:43:57.000  7441  7508 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@12d7acaa Bundle[{}]
,07-28 12:43:57.000  7441  7508 I io.jxcore.node.LifeCycleMonitor: start: OK
,07-28 12:43:57.000  7441  7508 I io.jxcore.node.LifeCycleMonitor: stop: OK
,07-28 12:43:57.000  7441  7508 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,07-28 12:43:57.000  7441  7508 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,07-28 12:43:57.000  7441  7508 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,07-28 12:43:57.000  7441  7508 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,07-28 12:43:57.010  7441  7508 I System.out: Running OutgoingSocketThread
,07-28 12:43:57.010  7441  8424 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 1327)
,07-28 12:43:57.010  7441  8424 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 41069
,07-28 12:43:57.010  7441  8424 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,07-28 12:43:57.120   304   304 E SMD     : DCD ON
,07-28 12:43:57.190  8395  8395 I wpa_supplicant: nl80211: Received scan results (18 BSSes)
07-28 12:43:57.190  8395  8395 I wpa_supplicant: wlan0: Setting scan request: 8 sec 0 usec
07-28 12:43:57.190  8395  8395 I wpa_supplicant: Trying to associate with F4.99.3E (SSID='4E47373030' freq=2447 MHz)
07-28 12:43:57.190  8395  8395 I wpa_supplicant: wlan0: State: SCANNING -> ASSOCIATING
07-28 12:43:57.190  8395  8395 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=5 BSSID=00.00.00 SSID=4E47373030
,07-28 12:43:57.210   791  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
,07-28 12:43:57.210   791  1149 D SecContentProvider2: mCursor = null
,07-28 12:43:57.260  8395  8395 I wpa_supplicant: wlan0: State: ASSOCIATING -> ASSOCIATED
07-28 12:43:57.260  8395  8395 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=6 BSSID=00.00.00 SSID=4E47373030
07-28 12:43:57.260  8395  8395 I wpa_supplicant: Associated with F4.99.3E
07-28 12:43:57.260  8395  8395 I wpa_supplicant: wlan0: State: ASSOCIATED -> 4WAY_HANDSHAKE
07-28 12:43:57.270  8395  8395 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=7 BSSID=F4.99.3E SSID=4E47373030
07-28 12:43:57.270   791  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:43:57.270   791  1149 D SecContentProvider2: mCursor = null
07-28 12:43:57.270   791  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:43:57.270   791  1149 D SecContentProvider2: mCursor = null
,07-28 12:43:57.280  8395  8395 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> 4WAY_HANDSHAKE
,07-28 12:43:57.280  8395  8395 I wpa_supplicant: wlan0: State: 4WAY_HANDSHAKE -> GROUP_HANDSHAKE
07-28 12:43:57.280  8395  8395 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=8 BSSID=F4.99.3E SSID=4E47373030
,07-28 12:43:57.280  8395  8395 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
07-28 12:43:57.280  8395  8395 I wpa_supplicant: wlan0: State: GROUP_HANDSHAKE -> COMPLETED
07-28 12:43:57.280  8395  8395 I wpa_supplicant: CTRL-EVENT-CONNECTED - Connection to F4.99.3E completed (auth) [id=1 id_str=]
07-28 12:43:57.280  8395  8395 I wpa_supplicant: Blacklist: Clear (temp) 
07-28 12:43:57.280  8395  8395 I wpa_supplicant: CTRL-EVENT-STATE-CHANGE id=1 state=9 BSSID=F4.99.3E SSID=4E47373030
,07-28 12:43:57.290   791  1149 D WifiNative-HAL: callSECApiVoid - ID [50]
,07-28 12:43:57.290  1193  1193 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:43:57.290  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:43:57.300   791  1149 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{false} explicitlySelected{false} }
,07-28 12:43:57.300   791  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
07-28 12:43:57.300   791  1151 D ConnectivityService: Got NetworkAgent Messenger
07-28 12:43:57.300   791  1151 D ConnectivityService: hsengiv:checkWhatTypeOfNetwork and the value is false
,07-28 12:43:57.300   791  1151 E ConnectivityService: updateNetworkInfo()
07-28 12:43:57.300   791  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:43:57.300   791  1151 D ConnectivityService: NetworkAgent connected
,07-28 12:43:57.300   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:43:57.310  1313  1313 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-28 12:43:57.310  1313  1313 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-28 12:43:57.310   791  1144 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:57.310  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-28 12:43:57.310   791  1574 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:57.310   791  1149 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,07-28 12:43:57.310  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
,07-28 12:43:57.310  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:43:57.310  1313  1313 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-28 12:43:57.310  1313  2966 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:43:57.320   791  1638 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:57.320   299  1061 D CommandListener: Setting iface cfg
,07-28 12:43:57.330  7031  7031 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:43:57.330   791  1149 E WifiStateMachine: Start Dhcp Watchdog 3
,07-28 12:43:57.330   791  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:43:57.330   791  1149 D SecContentProvider2: mCursor = null
,07-28 12:43:57.340  1193  1193 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:43:57.340  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:43:57.340   791  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,07-28 12:43:57.420   791  1149 E native  : do suspend false
,07-28 12:43:57.430   791  1148 D WifiP2pService: InactiveState{ what=143375 }
,07-28 12:43:57.430   791  1148 D WifiP2pService: P2pEnabledState{ what=143375 }
07-28 12:43:57.430   791  1149 D SecContentProvider2: uri = 20 selection = getPromptCredentialsEnabled
07-28 12:43:57.430   791  1149 D SecContentProvider2: mCursor = null
,07-28 12:43:57.640  8450  8450 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-28 12:43:57.640  8450  8450 I dhcpcd  : version 5.5.6 starting
,07-28 12:43:57.640  8450  8450 E dhcpcd  : fopen `/system/etc/dhcpcd/dhcpcd.conf': No such file or directory
,07-28 12:43:57.710  8450  8450 I dhcpcd  : wlan0: sending IPv6 Router Solicitation
07-28 12:43:57.710  8450  8450 E dhcpcd  : wlan0: sendmsg: Cannot assign requested address
07-28 12:43:57.720  8450  8450 I dhcpcd  : if(wlan0) info get Success. (MAC : F4.99.3E)
07-28 12:43:57.720  8450  8450 I dhcpcd  : bssid match
07-28 12:43:57.720  8450  8450 I dhcpcd  : wlan0: rebinding lease of 192.168.1.122
,07-28 12:43:57.740  8450  8450 I dhcpcd  : wlan0: acknowledged 192.168.1.122 from 192.168.1.1,
,07-28 12:43:57.740  8450  8450 I dhcpcd  : wlan0: leased 192.168.1.122 for 172800 seconds
,07-28 12:43:57.740   791  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,07-28 12:43:58.010  7441  7508 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 1328)
07-28 12:43:58.010  7441  7508 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 1328)
,07-28 12:43:58.010  7441  7508 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1333)
,07-28 12:43:58.010  7441  7508 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
07-28 12:43:58.010  7441  7508 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1334)
,07-28 12:43:58.010  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:43:58.010  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d87bee3 added. We now have 2 listener(s)
,07-28 12:43:58.020  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-28 12:43:58.020  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:43:58.020  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:43:58.020  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:58.020  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2587a0e0 added. We now have 9 listener(s)
07-28 12:43:58.020  7441  7508 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:43:58.020  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:43:58.030  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:43:58.030  7441  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:58.030  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:58.030  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:58.030  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:58.030  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:58.030  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:58.030  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:58.030  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:43:58.030  7441  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:43:58.030  7441  7508 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 12:43:58.030  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:43:58.030  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d03d25e added. We now have 3 listener(s)
,07-28 12:43:58.040   791  1149 E native  : do suspend true
,07-28 12:43:58.040  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:58.040  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:58.040  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-28 12:43:58.040  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:43:58.040  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:43:58.040  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:58.040  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@176d663f added. We now have 10 listener(s)
07-28 12:43:58.040  7441  7508 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:43:58.040  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:58.040  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:58.040  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:58.040  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:58.040  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:58.040  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:58.040  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:43:58.040  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d87bee3 removed from the list
07-28 12:43:58.040  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:58.040  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2587a0e0 removed from the list
07-28 12:43:58.040  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:58.040  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:58.040  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:58.040  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:58.040  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:43:58.040  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:58.040  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:58.040  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2587a0e0 not in the list
07-28 12:43:58.040  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:58.040  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:58.040   791  1148 D WifiP2pService: InactiveState{ what=143375 }
,07-28 12:43:58.040   791  1148 D WifiP2pService: P2pEnabledState{ what=143375 }
07-28 12:43:58.040  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:58.040  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,07-28 12:43:58.040  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:58.050  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@176d663f removed from the list
07-28 12:43:58.050  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:58.050  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:58.050  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:58.050  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-28 12:43:58.050  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1d03d25e removed from the list
,07-28 12:43:58.050  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:43:58.050  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2275eb0c added. We now have 2 listener(s)
,07-28 12:43:58.050   791  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=false
,07-28 12:43:58.050   791  1149 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
07-28 12:43:58.050   791  1149 E WifiStateMachine: VerifyingLinkState enter
,07-28 12:43:58.050  1193  1193 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:43:58.050  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:43:58.050   791  1149 D WifiNative-HAL: callSECApiInt - ID [210]
,07-28 12:43:58.050   791  1151 E ConnectivityService: updateNetworkInfo()
,07-28 12:43:58.050   791  1151 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-28 12:43:58.050   791  1151 D ConnectivityService: Adding iface wlan0 to network 504
,07-28 12:43:58.060   791  1161 D WifiWatchdogStateMachine: updateDnsLinkProperty: enter
,07-28 12:43:58.060   791  1161 D WifiWatchdogStateMachine.DnsPinger: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-28 12:43:58.060  1193  1193 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:43:58.060  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
,07-28 12:43:58.060   791  1161 D WifiWatchdogStateMachine.DnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-28 12:43:58.060   791  1161 D WifiWatchdogStateMachine.SingDnsChecker: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-28 12:43:58.060   791  1161 D WifiWatchdogStateMachine.CaptivePortalDnsResolver: setCurrentLinkProperties: lp={InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
,07-28 12:43:58.070  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-28 12:43:58.070  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:43:58.070  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:43:58.070  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:58.070  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@311aec55 added. We now have 9 listener(s)
07-28 12:43:58.070  7441  7508 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:43:58.080  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:43:58.090  1313  1313 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-28 12:43:58.090  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:43:58.090  7441  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:58.090  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:58.090  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:58.090  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:58.090  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:58.090  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:58.090  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:58.090  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
07-28 12:43:58.090  7441  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:43:58.090  7441  7508 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:43:58.090  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:43:58.090  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21dc275b added. We now have 3 listener(s)
,07-28 12:43:58.090  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:58.100   791  1151 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 504
,07-28 12:43:58.100   791  1149 E WifiStateMachine: VerifyingLinkState GOOD_LINK_DETECTED: transition to (new) connected (old)captive portal check
,07-28 12:43:58.100   791  1151 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 504
07-28 12:43:58.100  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:58.100   791  1151 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 504
,07-28 12:43:58.100   791  1151 E ConnectivityService: Unexpected mtu value: 0, wlan0
07-28 12:43:58.100   791  1151 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
07-28 12:43:58.100   791   791 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-28 12:43:58.100   791  1151 D ConnectivityService: updateSourceRoutes : add src route for:192.168.1.122
,07-28 12:43:58.100  1193  1193 D StatusBar.NetworkController: refreshViews connected={ } level=0 combinedSignalIconId=0x0/(null) mobileLabel=No service wifiLabel= emergencyOnly=false combinedLabel= mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020539/com.android.systemui:drawable/stat_sys_wifi_signal_null mQSWifiIconId=0x7f020154/com.android.systemui:drawable/ic_qs_wifi_no_network mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:43:58.100  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:null
07-28 12:43:58.100   299  1061 V         : QcRouteController
,07-28 12:43:58.100  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-28 12:43:58.100  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:43:58.100  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:43:58.100  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:58.100  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cabf8 added. We now have 10 listener(s)
07-28 12:43:58.100  7441  7508 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:43:58.100  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:43:58.100  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:43:58.100  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:43:58.100  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:43:58.100  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-28 12:43:58.100   791   791 I WifiTrafficPoller: evaluateTrafficStatsPolling
,07-28 12:43:58.110   791   791 I WifiTrafficPoller: mBoosterFLAG : 0
07-28 12:43:58.110   791   791 I WifiTrafficPoller: current booster mode : FullMode
07-28 12:43:58.110   791   791 D WifiNative-HAL: callSECApiVoid - ID [212]
,07-28 12:43:58.110   791  1149 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,07-28 12:43:58.110  1193  1193 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
,07-28 12:43:58.110  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-28 12:43:58.110  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-28 12:43:58.110  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-28 12:43:58.110  1193  1193 D StatusBar.NetworkController: applyOpen
,07-28 12:43:58.120  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:58.120  7441  7508 E BluetoothAdapter: bluetooth le advertising not supported
07-28 12:43:58.120  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:43:58.120  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 12:43:58.120  1193  1193 D StatusBar.NetworkController: applyOpen
,07-28 12:43:58.120  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
07-28 12:43:58.120  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:58.120  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:43:58.120  1193  1193 D StatusBar.NetworkController: applyOpen
,07-28 12:43:58.120  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
,07-28 12:43:58.120  1193  1193 D StatusBar.NetworkController: applyOpen
,07-28 12:43:58.120  7441  7508 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-28 12:43:58.120  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:58.120  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:43:58.120  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,07-28 12:43:58.120  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,07-28 12:43:58.130  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,07-28 12:43:58.130  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:58.130  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:58.130  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:58.130  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:43:58.130  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2275eb0c removed from the list
07-28 12:43:58.130  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:43:58.130  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@311aec55 removed from the list
07-28 12:43:58.130  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:58.130  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:58.130  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:43:58.130  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:58.130  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:58.130  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:58.130  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:58.130  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@311aec55 not in the list
07-28 12:43:58.130  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,07-28 12:43:58.130  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:58.130  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:58.130  7441  7508 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:58.130  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:58.130  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:58.130  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,07-28 12:43:58.130  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a1cabf8 removed from the list
07-28 12:43:58.130  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:58.130  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:58.130  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:58.130  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-28 12:43:58.130  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21dc275b removed from the list
,07-28 12:43:58.130  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:43:58.130  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13abde37 added. We now have 2 listener(s)
,07-28 12:43:58.140  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-28 12:43:58.140  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:43:58.140  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:43:58.140  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:58.140  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@136c8fa4 added. We now have 9 listener(s)
07-28 12:43:58.140  7441  7508 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:43:58.140  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
07-28 12:43:58.140  1313  1313 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-28 12:43:58.140   299  1061 V         : QcRouteController
,07-28 12:43:58.140  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:43:58.140  7441  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:58.140  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:58.140  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:58.140  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:58.140  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:58.140  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:58.140  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:58.140  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:43:58.150  7441  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:43:58.150  7441  7508 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 12:43:58.150  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:43:58.150  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@793a8c2 added. We now have 3 listener(s)
,07-28 12:43:58.150  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:58.150   791  1679 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:58.150  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
07-28 12:43:58.150  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
07-28 12:43:58.150  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:43:58.150  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:43:58.150  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:58.150  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f5626d3 added. We now have 10 listener(s)
07-28 12:43:58.150  7441  7508 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:43:58.150  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:43:58.150  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:43:58.150  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
07-28 12:43:58.150  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:43:58.150  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:43:58.150  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-28 12:43:58.150  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-28 12:43:58.150  7031  7031 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
07-28 12:43:58.150  7441  7508 E BluetoothAdapter: bluetooth le advertising not supported
07-28 12:43:58.150  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:43:58.150  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 12:43:58.160  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-28 12:43:58.160  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:43:58.160  7441  7508 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-28 12:43:58.160  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:58.160  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:58.160  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:58.160  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:58.160  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:58.160  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:58.160  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:43:58.160  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13abde37 removed from the list
07-28 12:43:58.160  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:58.160  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@136c8fa4 removed from the list
07-28 12:43:58.160  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:58.160  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:58.160  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:58.160  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:58.160  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:58.160  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:58.160  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:58.160  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@136c8fa4 not in the list
07-28 12:43:58.160  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:58.160  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:58.160  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:58.160  7441  7508 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:58.160  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:58.160  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:58.160  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:58.160  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f5626d3 removed from the list
07-28 12:43:58.160  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:58.160  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:58.160  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:58.160  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:43:58.160  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@793a8c2 removed from the list
,07-28 12:43:58.160  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:43:58.160  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28778f0e added. We now have 2 listener(s)
,07-28 12:43:58.160  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-28 12:43:58.160  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:43:58.160  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:43:58.160  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:58.160  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b525d2f added. We now have 9 listener(s)
07-28 12:43:58.160  7441  7508 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:43:58.160  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:43:58.160  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:43:58.160   299  1061 V         : QcRouteController
,07-28 12:43:58.170  7441  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:58.170  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:58.170  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:58.170  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:58.170  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:58.170  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:58.170  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:58.170  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:43:58.170  7441  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
07-28 12:43:58.170  7441  7508 D io.jxcore.node.ConnectivityMonitor: start: OK
,07-28 12:43:58.180  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:43:58.180  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a7094c5 added. We now have 3 listener(s)
,07-28 12:43:58.180  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:58.180  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:58.180  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-28 12:43:58.180  1313  1313 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
07-28 12:43:58.180  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:43:58.180  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,07-28 12:43:58.180  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:58.180  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a18e1a added. We now have 10 listener(s)
07-28 12:43:58.180  7441  7508 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
07-28 12:43:58.180  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
07-28 12:43:58.180  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,07-28 12:43:58.180  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
07-28 12:43:58.180  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
07-28 12:43:58.180  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,07-28 12:43:58.180  1313  1313 V NearbySettings: DMSUtil.isNetworkConnected - flag-null, state-null
,07-28 12:43:58.180   299  1061 V         : QcRouteController
07-28 12:43:58.180   791  1657 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:58.180  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - WIFI: DISCONNECTED
,07-28 12:43:58.190   791  1574 D ConnectivityService: returning getNetworkInfo(networkType - 13) :[type: WIFI_P2P[] - WIFI_P2P, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:58.190  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,07-28 12:43:58.190  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - P2P: DISCONNECTED
07-28 12:43:58.190  1313  1313 I NearbySettings: DMSUtil.isNetworkConnected - WIFI-false, Hotspot-false, P2P-false, Eth-false
07-28 12:43:58.190  1313  1313 I NearbySettings: MountReceiver.onReceive - Set preference state off
,07-28 12:43:58.190  1313  2966 V NearbySettings: MountReceiver.mPrefHandler - 7002
,07-28 12:43:58.190  7441  7508 E BluetoothAdapter: bluetooth le advertising not supported
07-28 12:43:58.190  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
07-28 12:43:58.190  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,07-28 12:43:58.190  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,07-28 12:43:58.190  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,07-28 12:43:58.200   791  1574 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:58.200  7441  7508 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,07-28 12:43:58.200  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
07-28 12:43:58.200  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:58.200  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:58.200  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:58.200  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:58.200  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:58.200  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:43:58.200  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@28778f0e removed from the list
07-28 12:43:58.200  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:58.200  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b525d2f removed from the list
07-28 12:43:58.200  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:58.200  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:58.200  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:58.200  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:58.200  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:58.200  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:58.200  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:58.200  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b525d2f not in the list
07-28 12:43:58.200  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:58.200  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:58.200  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:58.200  7441  7508 D BluetoothLeScanner: could not find callback wrapper
07-28 12:43:58.200  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
07-28 12:43:58.200  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:58.200  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:58.200  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34a18e1a removed from the list
07-28 12:43:58.200  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:58.200  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:58.200  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:58.200  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:43:58.200  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2a7094c5 removed from the list
,07-28 12:43:58.200  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
07-28 12:43:58.200  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@244ab841 added. We now have 2 listener(s)
07-28 12:43:58.200  7031  7031 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:43:58.200  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-28 12:43:58.200  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:43:58.200  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:43:58.200  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
07-28 12:43:58.200   299  1061 V         : QcRouteController
07-28 12:43:58.200  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b3a71e6 added. We now have 9 listener(s)
,07-28 12:43:58.200  7441  7508 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:43:58.210  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,07-28 12:43:58.210  1313  1313 D NearbySettings: MountReceiver.onReceive - ACTION: android.net.wifi.STATE_CHANGE
,07-28 12:43:58.210  1313  1313 I NearbySettings: MountReceiver.onReceive - Keep current state
,07-28 12:43:58.210  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,07-28 12:43:58.210   791   997 W ProcessCpuTracker: Skipping unknown process pid 8498
,07-28 12:43:58.210  7441  7508 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
07-28 12:43:58.210  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
07-28 12:43:58.210  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
07-28 12:43:58.210  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
07-28 12:43:58.210  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
07-28 12:43:58.210  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
07-28 12:43:58.210  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
07-28 12:43:58.210  7441  7508 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,07-28 12:43:58.220   791  1469 D WifiStateMachine: SEC_COMMAND_ID_GET_FWS_OPEN_AP_CHECK : 0
,07-28 12:43:58.220  7441  7508 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,07-28 12:43:58.220  7441  7508 D io.jxcore.node.ConnectivityMonitor: start: OK
07-28 12:43:58.220  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,07-28 12:43:58.220  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e529d4 added. We now have 3 listener(s)
,07-28 12:43:58.220  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:58.220  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "E0:DB:10:1F:C9:5E"
,07-28 12:43:58.220  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
07-28 12:43:58.220  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
07-28 12:43:58.220  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,07-28 12:43:58.220  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1049977d added. We now have 10 listener(s)
07-28 12:43:58.220  7441  7508 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,07-28 12:43:58.220  7441  7508 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,07-28 12:43:58.220   299  1061 V         : QcRouteController
,07-28 12:43:58.220  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
07-28 12:43:58.220  7441  7508 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
07-28 12:43:58.220  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,07-28 12:43:58.220  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:58.220  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
07-28 12:43:58.230  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,07-28 12:43:58.230  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@244ab841 removed from the list
07-28 12:43:58.230   299  1061 V         : QcRouteController
07-28 12:43:58.230   791  1469 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:58.230  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:58.230  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b3a71e6 removed from the list
,07-28 12:43:58.230  7441  7441 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,07-28 12:43:58.230  7441  7508 D io.jxcore.node.ConnectivityMonitor: stop
07-28 12:43:58.230  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:58.230  7031  7031 E SignOutReceiver: NETWORK_STATE_CHANGED_ACTION
,07-28 12:43:58.230  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:58.230  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:58.230  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:58.230  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:58.230  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:58.230  7441  7508 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3b3a71e6 not in the list
07-28 12:43:58.230  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:58.230  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,07-28 12:43:58.230  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
07-28 12:43:58.230  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
07-28 12:43:58.230  7441  7508 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
07-28 12:43:58.230  7441  7508 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1049977d removed from the list
07-28 12:43:58.230  7441  7508 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
07-28 12:43:58.230  7441  7508 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
07-28 12:43:58.230  7441  7508 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
07-28 12:43:58.230  7441  7508 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
07-28 12:43:58.230  7441  7508 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@26e529d4 removed from the list
,07-28 12:43:58.240  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
07-28 12:43:58.240  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
07-28 12:43:58.240  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
07-28 12:43:58.240  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,07-28 12:43:58.240  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
,07-28 12:43:58.240  7441  7508 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,07-28 12:43:58.240   299  1061 V         : QcRouteController
,07-28 12:43:58.250  7441  8510 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1341, name: My test thread name)
,07-28 12:43:58.250   266   266 I SurfaceFlinger: id=13 createSurf (1x1),1 flag=4, Uoast
07-28 12:43:58.250  7441  8510 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1341, thread name: My test thread name)
07-28 12:43:58.250  7441  8510 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1341, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,07-28 12:43:58.250  7441  8512 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1343, name: My test thread name)
,07-28 12:43:58.250  7441  8512 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1343, thread name: My test thread name)
07-28 12:43:58.250  7441  8512 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1343, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,07-28 12:43:58.250  7441  7508 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
,07-28 12:43:58.250  7441  7508 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
07-28 12:43:58.250  7441  7508 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
07-28 12:43:58.250  7441  7508 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
,07-28 12:43:58.250  7441  7508 D com.test.thalitest.ThaliTestRunner: Total duration: 23829 ms
,07-28 12:43:58.250  7441  7508 I jxcore-log: Total number of executed tests:  80
07-28 12:43:58.250  7441  7508 I jxcore-log: 
07-28 12:43:58.250  7441  7508 I jxcore-log: Number of passed tests:  80
07-28 12:43:58.250  7441  7508 I jxcore-log: 
,07-28 12:43:58.250  7441  7508 I jxcore-log: Number of failed tests:  0
07-28 12:43:58.250  7441  7508 I jxcore-log: 
07-28 12:43:58.250  7441  7508 I jxcore-log: Number of ignored tests:  0
07-28 12:43:58.250  7441  7508 I jxcore-log: 
07-28 12:43:58.250  7441  7508 I jxcore-log: Total duration:  23829
07-28 12:43:58.250  7441  7508 I jxcore-log: 
,07-28 12:43:58.260  7441  7508 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
07-28 12:43:58.260  7441  7508 I jxcore-log: 
,07-28 12:43:58.260  7441  7508 I jxcore-log: Unit Test app is loaded
07-28 12:43:58.260  7441  7508 I jxcore-log: 
07-28 12:43:58.260  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:43:58.260  7441  7508 I jxcore-log: 
07-28 12:43:58.260   791  1532 D PowerManagerService: [api] acquire WakeLock flags=0x2000000a tag=WindowManager uid=1000 pid=791
07-28 12:43:58.260  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:43:58.260  7441  7508 I jxcore-log: 
07-28 12:43:58.260   791  1151 D ConnectivityService: Setting Dns servers for network 504 to [/192.168.1.1]
07-28 12:43:58.260   791  1151 D ConnectivityService: LTETest block dns file not exists
07-28 12:43:58.270   791  1151 V Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true
07-28 12:43:58.270   791  1151 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
07-28 12:43:58.270   791  1151 D ConnectivityService: calling update connectivity
07-28 12:43:58.270   791  1151 E ConnectivityService: updateNetworkInfo()
07-28 12:43:58.270   791  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-28 12:43:58.270   791  1151 E ConnectivityService: updateNetworkInfo()
07-28 12:43:58.270   791  1151 D ConnectivityService: ignoring duplicate network state non-change. WIFI, state = CONNECTING
07-28 12:43:58.270   791  1151 D ConnectivityService: NetworkAgentInfo [WIFI () - 504] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED, reason = null, [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:43:58.270   791  1151 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 504]
07-28 12:43:58.270   791  1151 D ConnectivityService: calling update connectivity
07-28 12:43:58.270   791  1151 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
07-28 12:43:58.270   791  1151 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:43:58.270   791  1043 D EntConnectivity: Not allowed due to - mEnabled false
07-28 12:43:58.270   791  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:58.270   791  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:58.270   791  8426 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:58.270   791  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:58.270   791  8426 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Connected
07-28 12:43:58.270   791  8426 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
07-28 12:43:58.270   791  8426 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
07-28 12:43:58.270  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:43:58.270  7441  7508 I jxcore-log: 
07-28 12:43:58.270   791  8426 I System.out: (HTTPLog)-Static: isSBSettingEnabled false
07-28 12:43:58.270  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:43:58.270  7441  7508 I jxcore-log: 
07-28 12:43:58.270  7441  7441 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,07-28 12:43:58.270   791  1151 D ConnectivityService: currentScore = 0, newScore = 60
07-28 12:43:58.270   791  1151 D ConnectivityService:    accepting network in place of null
07-28 12:43:58.270   791  1151 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:58.280  1426  1426 D TelephonyNetworkFactory: Cellular releasing Network for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-28 12:43:58.280   791  1151 E CSLegacyTypeTracker: add() : Adding agent NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
07-28 12:43:58.280   791  1151 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 504] isDefaultNetwork=true
07-28 12:43:58.280   791  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,07-28 12:43:58.280   791  1151 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=500, action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:58.280   791  1151 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{504}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{false} created{true} explicitlySelected{false} }
,07-28 12:43:58.280  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:43:58.280  7441  7508 I jxcore-log: 
07-28 12:43:58.280   791  1151 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
07-28 12:43:58.280   791  1043 D EntConnectivity: Not allowed due to - mEnabled false
07-28 12:43:58.280   791  1152 D Tethering: MasterInitialState.processMessage what=3
07-28 12:43:58.280   791  1151 D ConnectivityService: calling update connectivity
07-28 12:43:58.280  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:43:58.280  7441  7508 I jxcore-log: 
07-28 12:43:58.280   791   791 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
,07-28 12:43:58.280   791  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-28 12:43:58.280   791  1153 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:43:58.280   791  1153 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:43:58.280   791  1153 D SmartBondingService: getSBEnabled() enabled =false
,07-28 12:43:58.280   791  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:58.280  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
07-28 12:43:58.280  7441  7508 I jxcore-log: 
07-28 12:43:58.280   791  1146 V NetworkStats: updateIfacesLocked()
07-28 12:43:58.280   791  1146 V NetworkStats: performPollLocked(flags=0x1)
,07-28 12:43:58.280   791  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:43:58.280   791  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:43:58.280  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:43:58.280  7441  7508 I jxcore-log: 
07-28 12:43:58.290   791  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:43:58.290   791  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:43:58.290   791  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:43:58.290   791  1147 V NetworkStats: advisePersistThreshold() given 9223372036854775, clamped to 2097152
07-28 12:43:58.290   791  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-28 12:43:58.290  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:43:58.290  7441  7508 I jxcore-log: 
,07-28 12:43:58.290  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
07-28 12:43:58.290  7441  7508 I jxcore-log: 
07-28 12:43:58.290   791  1146 D NetworkStatsFactory: UpdateStatsForKnox
07-28 12:43:58.290   791  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:58.290  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:43:58.290  7441  7508 I jxcore-log: 
07-28 12:43:58.290   791  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-28 12:43:58.290   791  1151 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:58.290  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
07-28 12:43:58.290  7441  7508 I jxcore-log: 
,07-28 12:43:58.290  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:43:58.290  7441  7508 I jxcore-log: 
07-28 12:43:58.290  1193  1581 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-28 12:43:58.290   791  1146 V NetworkStats: performPollLocked() took 6ms
07-28 12:43:58.290   791  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:43:58.290  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:43:58.290  7441  7508 I jxcore-log: 
07-28 12:43:58.290   791  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:58.290  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:43:58.290  7441  7508 I jxcore-log: 
,07-28 12:43:58.290   791  1259 I AudioService: getStreamVolume 3 index 0
07-28 12:43:58.290  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:43:58.290  7441  7508 I jxcore-log: 
07-28 12:43:58.290   791  1151 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-28 12:43:58.290  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:43:58.290  7441  7508 I jxcore-log: 
07-28 12:43:58.290  4536  7290 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-28 12:43:58.290  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
07-28 12:43:58.290  7441  7508 I jxcore-log: 
,07-28 12:43:58.290  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:43:58.290  7441  7508 I jxcore-log: 
07-28 12:43:58.290  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
07-28 12:43:58.290  7441  7508 I jxcore-log: 
,07-28 12:43:58.290   791  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:43:58.290   791  1147 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:43:58.290  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:43:58.290  7441  7508 I jxcore-log: 
,07-28 12:43:58.290  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:43:58.290  7441  7508 I jxcore-log: 
,07-28 12:43:58.290  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:43:58.290  7441  7508 I jxcore-log: 
07-28 12:43:58.300  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:43:58.300  7441  7508 I jxcore-log: 
,07-28 12:43:58.300  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:43:58.300  7441  7508 I jxcore-log: 
,07-28 12:43:58.300  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:43:58.300  7441  7508 I jxcore-log: 
07-28 12:43:58.300  7441  7508 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
07-28 12:43:58.300  7441  7508 I jxcore-log: 
,07-28 12:43:58.300  7441  7508 I jxcore-log: My device name is: samsung-SM-N9005
07-28 12:43:58.300  7441  7508 I jxcore-log: 
,07-28 12:43:58.300  7441  7508 I jxcore-log: WARN testUtils: myNameCallback not set!
07-28 12:43:58.300  7441  7508 I jxcore-log: 
,07-28 12:43:58.310   362   362 I ServiceManager: Waiting for service AtCmdFwd...
,07-28 12:43:58.310   791  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:58.310  1193  1193 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-28 12:43:58.310  1193  1193 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-28 12:43:58.310  1193  1193 D StatusBar.NetworkController: updateDataNetType()
07-28 12:43:58.310  1193  1193 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
07-28 12:43:58.310  1193  1193 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,07-28 12:43:58.310  1193  1193 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
07-28 12:43:58.310  1193  1193 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
,07-28 12:43:58.310  1193  1193 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
07-28 12:43:58.310  1193  1193 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:43:58.310  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
07-28 12:43:58.310  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:58.310  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:58.310  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:58.310  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:58.310  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:58.310  1193  1193 D StatusBar.NetworkController: applyOpen
07-28 12:43:58.310  1193  1193 D StatusBar.NetworkController: refreshSignalCluster - setNWBoosterIndicators(false)
07-28 12:43:58.310  1193  1193 D StatusBar.NetworkController: applyOpen
,07-28 12:43:58.360   791  8426 I System.out: KnoxVpnUidStorageknoxVpnSupported API value returned is false
,07-28 12:43:58.420   791  8426 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 28 Jul 2016 10:43:58 GMT], X-Android-Received-Millis=[1469702638429], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1469702638398]}
07-28 12:43:58.420   791  8426 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
07-28 12:43:58.420   791  8426 D NetworkMonitorNetworkAgentInfo [WIFI () - null]: Validated
,07-28 12:43:58.420   791  1151 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 504]
07-28 12:43:58.420   791  1151 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 504]
07-28 12:43:58.420   791  1151 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
07-28 12:43:58.420   791  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:58.420   791  1151 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:58.420   791  1151 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 504] was already satisfying request 1. No change.
07-28 12:43:58.420   791  1151 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 504]
07-28 12:43:58.420   791  1151 D ConnectivityService: calling update connectivity
07-28 12:43:58.420   791  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:58.420   791  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-28 12:43:58.420   791  1151 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:58.420   791  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:58.420   791  1151 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-28 12:43:58.420  1193  1581 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
07-28 12:43:58.420   791  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,07-28 12:43:58.420  4536  7290 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,07-28 12:43:58.420   791  1679 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:58.420  1193  1193 D StatusBar.NetworkController: getUpdateDataNetType(): 0
07-28 12:43:58.420  1193  1193 D StatusBar.NetworkController: getUpdateDataNetType(): mDataTypeBrand = LTE
07-28 12:43:58.420  1193  1193 D StatusBar.NetworkController: updateDataNetType()
07-28 12:43:58.420  1193  1193 D StatusBar.NetworkController: NoService, mRoamingIconId = 0
,07-28 12:43:58.420  1193  1193 E StatusBar.NetworkController: updateLTEICONDataNetType:0
,07-28 12:43:58.430  1193  1193 D StatusBar.NetworkController: updateDataIcon, mDataDirectionIconId = (null) mDataConnected = false
,07-28 12:43:58.430  1193  1193 D StatusBar.NetworkController: updateTelephonySignalStrength: hasService=false ss=SignalStrength: 99 99 -120 -160 -120 -1 -1 99 2147483647 2147483647 2147483647 -1 2147483647 0x0 gsm|lte
07-28 12:43:58.430  1193  1193 D StatusBar.NetworkController: updateTelephonySignalStrength, No signal level. mPhoneSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mDataSignalIconId = com.android.systemui:drawable/tw_stat_sys_signal_null mQSPhoneSignalIconId = com.android.systemui:drawable/ic_qs_signal_no_signal mContentDescriptionPhoneSignal = No phone signal
,07-28 12:43:58.430  1193  1193 D StatusBar.NetworkController: refreshViews connected={ wifi } level=0 combinedSignalIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mobileLabel= wifiLabel="NG700"xxxxXXXXxxxxXXXX emergencyOnly=false combinedLabel="NG700"xxxxXXXXxxxxXXXX mAirplaneMode=true mDataActivity=0 mPhoneSignalIconId=0x0/(null) mQSPhoneSignalIconId=0x0/(null) mDataDirectionIconId=0x0/(null) mDataSignalIconId=0x0/(null) mDataTypeIconId=0x0/(null) mQSDataTypeIconId=0x0/(null) mNoSimIconId=0x0/(null) mWifiIconId=0x7f020536/com.android.systemui:drawable/stat_sys_wifi_signal_4 mQSWifiIconId=0x7f02014c/com.android.systemui:drawable/ic_qs_wifi_4 mWifiActivityIconId=0x7f020505/com.android.systemui:drawable/stat_sys_signal_in mBluetoothTetherIconId=0x10808f0/android:drawable/stat_sys_tether_bluetooth
07-28 12:43:58.430  1193  1193 D STATUSBAR-WifiQuickSettingButton: onWifiSignalChanged enabled=true enabledDesc:"NG700"
,07-28 12:43:58.510  8518  8518 D AndroidRuntime: 
07-28 12:43:58.510  8518  8518 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,07-28 12:43:58.510  8518  8518 D AndroidRuntime: CheckJNI is OFF
,07-28 12:43:58.510  8518  8518 D AndroidRuntime: readGMSProperty: start
07-28 12:43:58.510  8518  8518 D AndroidRuntime: readGMSProperty: already setted!!
,07-28 12:43:58.510  8518  8518 D AndroidRuntime: readGMSProperty: end
07-28 12:43:58.510  8518  8518 D AndroidRuntime: addProductProperty: start
,07-28 12:43:58.650  8518  8518 E AffinityControl: AffinityControl: registerfunction enter
,07-28 12:43:58.670  8518  8518 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,07-28 12:43:58.670   791  1638 D PackageManager: START PACKAGE DELETE: observer{339330753}
07-28 12:43:58.670   791  1638 D PackageManager: pkg{<packageName>}
07-28 12:43:58.670   791  1638 D PackageManager: user{0}
07-28 12:43:58.670   791  1638 D PackageManager: caller{2000}
07-28 12:43:58.670   791  1638 D PackageManager: flags{2}
07-28 12:43:58.670   791  1638 D PersonaManagerService: isFromApprovedUnInstaller: uid, userId, appid : 2000 0 2000
07-28 12:43:58.670   791  1638 D PersonaManagerService: isFromApprovedUnInstaller: isApproved : true
07-28 12:43:58.670   791  1638 D PersonaManagerService: isFromApprovedUnInstaller: isApproved before exit: true
,07-28 12:43:58.680   791  1638 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
07-28 12:43:58.680   791  1638 D PackageManager: deletePackageAsUser- pkg:com.test.thalitest, userId:0, flag2
,07-28 12:43:58.680   791  1065 D PackageManager: [MSG] DELETE_PACKAGE_AS_USER
07-28 12:43:58.680   791  1065 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:0
07-28 12:43:58.680   791  1065 D PackageManagerService: deletePackage- pkg:com.test.thalitest, edmuserId:-1
07-28 12:43:58.680   791  1065 D ApplicationPolicy: getApplicationUninstallationEnabled
07-28 12:43:58.680   791  1065 D ApplicationPolicy: getApplicationUninstallationEnabled :  enabled true
,07-28 12:43:58.680   791  1065 D PackageManager: !@killApplicatoin: 10079, uninstall pkg
,07-28 12:43:58.680   791   997 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=-1: uninstall pkg
07-28 12:43:58.680   791   997 I ActivityManager: Killing 7441:com.test.thalitest/u0a79 (adj 0): stop com.test.thalitest cause uninstall pkg
,07-28 12:43:58.680   791   997 I ActivityManager:   Force finishing activity ActivityRecord{32cbb385 u0 com.test.thalitest/.MainActivity t99}
,07-28 12:43:58.680   791   997 D FocusedStackFrame: Set to : 0
,07-28 12:43:58.690   791  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
,07-28 12:43:58.690   791  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
07-28 12:43:58.690   791  1046 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-28 12:43:58.690   791  1046 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-28 12:43:58.690   266   358 I SurfaceFlinger: id=12 Removed NainActivit (6/9)
,07-28 12:43:58.690   266   369 I SurfaceFlinger: id=12 Removed NainActivit (-2/9)
,07-28 12:43:58.780   791  1151 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:43:58.790   791  1065 W PackageSettings: Skipping PackageSetting{35286824 com.example.hello/10078} due to missing metadata
,07-28 12:43:58.810   791  3300 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:58.810   791   791 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:58.820   791   791 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:58.820   791   791 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:58.820   791   791 D SmartBondingService: SmartBondingReceiver: wifi is connected
07-28 12:43:58.820   791   994 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
07-28 12:43:58.820   791   791 D SmartBondingService: SmartBondingReceiver: wifi ap is not changed
07-28 12:43:58.820   791   994 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:58.820   791  1638 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:58.820   791  1259 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:58.820   791  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:58.820   791   791 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:58.820   791   791 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:58.820   791  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-28 12:43:58.820   791   791 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:58.820   791  1153 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:43:58.820   791  1153 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:43:58.820   791  1153 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:43:58.820   791   791 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:58.820   791   791 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:58.820   791  1574 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:58.820  1487  1487 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,07-28 12:43:58.820   791  1443 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:58.830   791  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:58.830   791  1657 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:58.830   791  1638 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:58.830   791  1358 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:58.830   791  1358 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:58.830   791  1638 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:58.830   791  1638 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:58.840   791  1153 D SmartBondingService: getNetworkEnabled : wifi : true mobile : true
,07-28 12:43:58.840   791  3300 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:58.840  7716  7716 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,07-28 12:43:58.840   791  1657 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:58.840   791   831 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:58.840  6764  6764 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-28 12:43:58.840  6764  6764 I PCWCLIENTTRACE_PushUtil: sales region : global
07-28 12:43:58.840  6764  6764 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-28 12:43:58.840  6764  6764 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:43:58.850   791   994 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:58.850  7716  7716 V MusicLeanback: onReceive: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.music/.leanback.notifications.LeanbackRecommendationsService$LeanbackRecommendationReceiver (has extras) }
,07-28 12:43:58.860   791  1065 I ActivityManager: Force stopping com.test.thalitest appid=10079 user=0: pkg removed
,07-28 12:43:58.870   791  1358 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
,07-28 12:43:58.870   791  1358 D SecContentProvider2: mCursor = null
,07-28 12:43:58.900  1487  1487 I art     : Explicit concurrent mark sweep GC freed 1924(81KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 19MB/33MB, paused 459us total 34.276ms
,07-28 12:43:58.900   791  3075 E libprocessgroup: failed to kill 1 processes for processgroup 7441
,07-28 12:43:58.900  3809  3809 I art     : Explicit concurrent mark sweep GC freed 5482(303KB) AllocSpace objects, 1(16KB) LOS objects, 40% free, 15MB/26MB, paused 790us total 19.107ms
,07-28 12:43:58.910  7031  7031 I art     : Explicit concurrent mark sweep GC freed 5537(392KB) AllocSpace objects, 3(48KB) LOS objects, 25% free, 16MB/21MB, paused 323us total 44.029ms
,07-28 12:43:58.920   791   791 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.gms-2/base.apk
,07-28 12:43:58.920   791  1046 D ResourcesManager: creating new AssetManager and set to /system/priv-app/InputDevices/InputDevices.apk
,07-28 12:43:58.920  6471  6471 I art     : Explicit concurrent mark sweep GC freed 638(36KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 321us total 17.838ms
,07-28 12:43:58.920   791   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Velvet/Velvet.apk
,07-28 12:43:58.920  1441  1441 D ResourcesManager: creating new AssetManager and set to /system/priv-app/StoryAlbumWidget/StoryAlbumWidget.apk
,07-28 12:43:58.930  1441  1441 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-28 12:43:58.930  1865  1865 E SamsungIME: mOCRHelper is null
,07-28 12:43:58.930  1441  1441 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-28 12:43:58.930  1897  2390 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,07-28 12:43:58.930  4536  4536 I art     : Explicit concurrent mark sweep GC freed 32020(1853KB) AllocSpace objects, 4(64KB) LOS objects, 39% free, 24MB/40MB, paused 1.307ms total 50.408ms
,07-28 12:43:58.930  1441  1441 D ResourcesManager: creating new AssetManager and set to /system/app/AccuweatherPhone2013_H_LMR/AccuweatherPhone2013_H_LMR.apk
,07-28 12:43:58.930  1441  1441 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:43:58.930  1441  1441 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-28 12:43:58.930  1441  1441 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-28 12:43:58.940   791  1122 I InputReader: Reconfiguring input devices.  changes=0x00000010
,07-28 12:43:58.940   791   791 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SNS/SNS.apk
,07-28 12:43:58.940  1441  1441 D ResourcesManager: creating new AssetManager and set to /system/app/SPlannerWidget_OS_UPG/SPlannerWidget_OS_UPG.apk
,07-28 12:43:58.940  1441  1441 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
07-28 12:43:58.940  1441  1441 W ResourcesManager: Asset path '/system/framework/sws.jar' does not exist or contains no resources.
,07-28 12:43:58.940   791   791 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Samsungservice2_xxhdpi/Samsungservice2_xxhdpi.apk
,07-28 12:43:58.950  1420  1420 D RegisteredServicesCache: empty dynamic service
,07-28 12:43:58.950   791   791 D ResourcesManager: creating new AssetManager and set to /system/app/ChatON_MARKET/ChatON_MARKET.apk
,07-28 12:43:58.960   791   791 D ResourcesManager: creating new AssetManager and set to /system/app/Dropbox/Dropbox.apk
,07-28 12:43:58.960   791   791 D ResourcesManager: creating new AssetManager and set to /system/app/Gmail2/Gmail2.apk
,07-28 12:43:58.960   791   994 D ResourcesManager: creating new AssetManager and set to /system/app/SamsungIME/SamsungIME.apk
,07-28 12:43:58.960  7766  7766 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(17/llIIIIlllllIIllIIllI)] Receive broadcast: android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:43:58.970  7766  7766 I DIAGMON_AGENT: [lIIllllllllIlIlIllll(31/llIIIIlllllIIllIIllI)] Running with RegistrationReceiver
,07-28 12:43:58.970   791   791 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,07-28 12:43:58.980   791  1146 V NetworkStats: removeUidsLocked() for UIDs [10079]
07-28 12:43:58.980   791  1146 D NtpTrustedTime: currentTimeMillis() cache hit
07-28 12:43:58.980   791  1146 V NetworkStats: performPollLocked(flags=0x3)
,07-28 12:43:58.990   791  1146 D NetworkStatsFactory: UpdateStatsForKnox
,07-28 12:43:58.990   791  1146 D ConnectivityService: returning getNetworkInfo(networkType - 28) :[type: MOBILE_ENT1[] - MOBILE_ENT1, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:58.990   791  1146 V NetworkStats: performPollLocked() took 16ms
07-28 12:43:58.990   791  1146 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:43:58.990   791   791 D ResourcesManager: creating new AssetManager and set to /system/app/SecEmail_K/SecEmail_K.apk
,07-28 12:43:59.000   791   791 D ResourcesManager: creating new AssetManager and set to /system/app/Evernote/Evernote.apk
,07-28 12:43:59.010   791   791 D ResourcesManager: creating new AssetManager and set to /system/priv-app/GoogleServicesFramework/GoogleServicesFramework.apk
,07-28 12:43:59.020   791   791 D ResourcesManager: creating new AssetManager and set to /system/priv-app/Pinboard/Pinboard.apk
,07-28 12:43:59.020   791   994 D ResourcesManager: creating new AssetManager and set to /system/app/talkback/talkback.apk
,07-28 12:43:59.030   791   791 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SHealth3_5/SHealth3_5.apk
,07-28 12:43:59.070   791   791 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,07-28 12:43:59.080   791   791 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncCalendar/sCloudSyncCalendar.apk
,07-28 12:43:59.080   791   791 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncContacts/sCloudSyncContacts.apk
,07-28 12:43:59.080   791  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:43:59.080   791  1147 D NtpTrustedTime: currentTimeMillis() cache hit
,07-28 12:43:59.080   791   791 D ResourcesManager: creating new AssetManager and set to /system/priv-app/sCloudSyncSBrowser/sCloudSyncSBrowser.apk
,07-28 12:43:59.090   791   791 D ResourcesManager: creating new AssetManager and set to /system/app/Books/Books.apk
,07-28 12:43:59.090   791   994 D EnterpriseDeviceManagerService: Package has changed for user 0
,07-28 12:43:59.090   791   994 D EnterpriseDeviceManagerService: Admin package name: com.google.android.gms
,07-28 12:43:59.090   791  1657 D SecContentProvider2: uri = 11 selection = getMyKnoxAdmin
07-28 12:43:59.090   791  1657 D SecContentProvider2: mCursor = null
,07-28 12:43:59.100   791   791 D ResourcesManager: creating new AssetManager and set to /system/app/Chrome/Chrome.apk
,07-28 12:43:59.100   791   791 D ResourcesManager: creating new AssetManager and set to /system/app/Drive/Drive.apk
,07-28 12:43:59.100   791   791 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleCalendarSyncAdapter/GoogleCalendarSyncAdapter.apk
,07-28 12:43:59.100   791   791 D ResourcesManager: creating new AssetManager and set to /system/app/GoogleContactsSyncAdapter/GoogleContactsSyncAdapter.apk
,07-28 12:43:59.110   791   791 D ResourcesManager: creating new AssetManager and set to /system/app/Music2/Music2.apk
,07-28 12:43:59.110   791   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMms_Candy/SecMms_Candy.apk
,07-28 12:43:59.110   791   791 D ResourcesManager: creating new AssetManager and set to /system/app/Newsstand/Newsstand.apk
,07-28 12:43:59.120   791   791 D ResourcesManager: creating new AssetManager and set to /system/app/PlusOne/PlusOne.apk
,07-28 12:43:59.120  7782  7782 I FOTA_Client: [com.sec.android.fotaclient.FotaRegisterReceiver(113/onReceive)] Already device registered...
,07-28 12:43:59.130   791   791 D ResourcesManager: creating new AssetManager and set to /system/app/SNote4.1Preload/SNote4.1Preload.apk
,07-28 12:43:59.130  7782  7782 I FOTA_Client: [com.sec.android.fotaclient.FotaUpdaterReceiver(103/onReceive)] Auto update settings is activated
,07-28 12:43:59.130   791   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:43:59.130  7782  7782 I FOTA_Client: [lIIIIlIlIlIlllllllll(197/lllIlIlIIIllIIlIllIl)] Polling time is vaild
,07-28 12:43:59.140   791   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:43:59.140   791   994 D ResourcesManager: creating new AssetManager and set to /system/app/YouTube/YouTube.apk
07-28 12:43:59.140   791   791 D ResourcesManager: creating new AssetManager and set to /system/app/SecExchange/SecExchange.apk
,07-28 12:43:59.140  2502  2502 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-28 12:43:59.140   791   791 D ResourcesManager: creating new AssetManager and set to /system/app/Videos/Videos.apk
07-28 12:43:59.140   791   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-28 12:43:59.140   791   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SFinder/SFinder.apk
,07-28 12:43:59.140  2502  2502 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.net.conn.CONNECTIVITY_CHANGE , timestamp: 1469702639151
,07-28 12:43:59.140  2502  2502 I KLMS-2.4.511: : MainReciver(): NETWORK_STATE_CHANGED_ACTION
,07-28 12:43:59.140   791  1469 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:59.140   791  1679 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.150  2502  2502 I KLMS-2.4.511: : KLMSUtility(): isNetworkAvailable() - WIFI : true| MOBILE : false
,07-28 12:43:59.150  2502  2502 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().START
,07-28 12:43:59.150  2502  2502 I KLMS-2.4.511: : NetworkChangeOperations(): uploadRequestLog().START 
,07-28 12:43:59.150  2502  2502 I KLMS-2.4.511: : StateImplV2(): networkChangeListener().END
,07-28 12:43:59.150   791   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-28 12:43:59.150   791   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungLink20/SamsungLink20.apk
,07-28 12:43:59.150   791   791 D RCPManagerService: PackageReceiver onReceive()
07-28 12:43:59.150   791   791 I HarmonyEASService: onReceive : android.intent.action.PACKAGE_REMOVED for 0
,07-28 12:43:59.160   791   791 D KnoxMUMContainerPolicy: mPackageReceiver : action - android.intent.action.PACKAGE_REMOVED
,07-28 12:43:59.160   791   791 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,07-28 12:43:59.160   791   791 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,07-28 12:43:59.160   791   791 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - start - android.intent.action.PACKAGE_REMOVED
07-28 12:43:59.160   791   791 V EnterpriseBillingPolicy: uID is 10079
07-28 12:43:59.160   791   791 V EnterpriseBillingPolicy: Removed Packageuid is0
07-28 12:43:59.160   791   791 V EnterpriseBillingPolicyStorage: getProfileForApplication - enter
07-28 12:43:59.160   791   791 V EnterpriseBillingPolicyStorage: getProfileForApplication - exit null
07-28 12:43:59.160   791   791 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - personal application - profile null
07-28 12:43:59.160   791   791 V EnterpriseBillingPolicy: packageModificationReceiver - onreceive - might be a vpn vendor package 
07-28 12:43:59.160   791   791 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - start - com.test.thalitest
,07-28 12:43:59.160   791   791 V EnterpriseBillingPolicyStorage: getBillingProfileForVpnEngine - end - null
,07-28 12:43:59.160   791  1476 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.160   791   791 V AlarmManagerEXT: com.test.thalitest(10079) is removed.
,07-28 12:43:59.170   791  1178 D TaskPersister: removeObsoleteFile: deleting file=99_task.xml
,07-28 12:43:59.170   791   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:43:59.170  7825  7825 I SO_AGENT: [com.sec.android.soagent.RegisterReceiver(104/onReceive)] Get Accessory List
07-28 12:43:59.170   791  1476 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
,07-28 12:43:59.180   791  1476 D ActivityManager: caller:android.app.ApplicationThreadProxy@3668a2c8, r.packageName :com.samsung.android.app.galaxyfinder
,07-28 12:43:59.180   791   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:43:59.180   791   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:43:59.190   791   994 D ResourcesManager: creating new AssetManager and set to /system/app/InteractiveTutorial/InteractiveTutorial.apk
,07-28 12:43:59.200   791   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:43:59.200   791   994 D ResourcesManager: creating new AssetManager and set to /system/app/Peel_L/Peel_L.apk
,07-28 12:43:59.210   791   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:43:59.210   791   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-28 12:43:59.210   791   994 D ResourcesManager: creating new AssetManager and set to /system/app/SPlanner_LEGACY/SPlanner_LEGACY.apk
,07-28 12:43:59.210   791  1468 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.210  7842  7842 E SPPClientService: [[SystemStateMoniter]] SystemStateMonitorService : noConnect? : false
,07-28 12:43:59.210   791   994 W ResourcesManager: Asset path '/system/framework/sechardware.jar' does not exist or contains no resources.
07-28 12:43:59.220   791   994 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
07-28 12:43:59.220   791   994 W ResourcesManager: Asset path '/system/framework/twframework.jar' does not exist or contains no resources.
,07-28 12:43:59.220  3705  8541 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,07-28 12:43:59.220  3705  8541 I DBG_POLICYDM: [com.policydm.XDMService(481/isNetworkChanged)] a previous network is 0, current network is 2
,07-28 12:43:59.220  3705  8541 E DBG_POLICYDM: [com.policydm.XDMService(483/isNetworkChanged)] network changed.... 
,07-28 12:43:59.220   791   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:43:59.220   791   994 D ResourcesManager: creating new AssetManager and set to /data/app/com.google.android.play.games-1/base.apk
,07-28 12:43:59.220   791  3300 I SQLiteConnectionPool: exportDB...
07-28 12:43:59.220  7858  7858 I SA      : [OR] onReceive log=[SA = 2.1.0081 V = 21 HWD = 1920X1080 3.0 dpi = 480  SIZE = 2 LOCALE = en_US CSC = XEO MCC = 0 MNC 0 T = user DEVICE = hlte P = hltexx I = LRX21V M = SM-N9005 OKLEFT false DIS LRX21V.N9005XXUGBOK6 PSS = 5.701607447389803  ]
,07-28 12:43:59.220  7858  7858 I SA      : [OR] onReceive Intent=[ conn.CONNECTIVITY_CHANGE. networkInfo:[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] networkType:1 inetCondition:0 extraInfo:? isDefault:true ]
,07-28 12:43:59.230  7858  7858 I SA      : [OR] == ACTION_CONNECTIVITY_CHANGE ==
,07-28 12:43:59.230  7858  7858 I SA      : [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,07-28 12:43:59.230  7858  7858 I SA      : [OR] == isSIMCardReady false ==
07-28 12:43:59.230   791  1469 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:59.230  7858  7858 I SA      : [SCU] == networkStateCheck == true
,07-28 12:43:59.230  7858  7858 I SA      : [DM] getCountryCodeFromCSC : PL
,07-28 12:43:59.230  7858  7858 I SA      : isChinaCountryCode : false
07-28 12:43:59.230  7858  7858 I SA      : [SCU] is ChinestModel Data Restricted   : false
,07-28 12:43:59.230  7858  7858 I SA      : [OR] == networkStateCheck true ==
,07-28 12:43:59.230   791   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SamsungMusic_20/SamsungMusic_20.apk
,07-28 12:43:59.240  7858  7858 I SA      : [OR] GetMyCountryZoneTask
,07-28 12:43:59.240  7858  7858 I SA      : [OR] onReceive END
,07-28 12:43:59.240  7858  8543 I SA      : [SRS] prepareGetMyCountryZone
,07-28 12:43:59.240  3705  8541 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(277/xdmExecResumeCase)] 
07-28 12:43:59.240   791   832 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.240  3705  8541 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/sepolicy
07-28 12:43:59.250  7858  8543 I SA      : [TPMU]  strSIMState 	:SIM_STATE_UNKNOWN
,07-28 12:43:59.250  7858  8543 I SA      : [SSP] query invoked
07-28 12:43:59.250  3705  8541 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/seapp_contexts
,07-28 12:43:59.250   791  1428 D ActivityManager: startService callerProcessName:com.android.providers.media, calleePkgName: com.android.providers.downloads
,07-28 12:43:59.250   791  1428 D ActivityManager: caller:android.app.ApplicationThreadProxy@2cf450d3, r.packageName :com.android.providers.downloads
,07-28 12:43:59.250  7882  7882 I SCloudBackupReceiver: Other Intent
,07-28 12:43:59.250  3705  8541 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/property_contexts
,07-28 12:43:59.250  3705  8541 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/file_contexts
,07-28 12:43:59.250  3705  8541 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/service_contexts
,07-28 12:43:59.260  7190  7190 I KnoxUsageLogPro: KnoxUsageReceiver onReceive :android.net.conn.CONNECTIVITY_CHANGE myUserId=0
07-28 12:43:59.260  7190  7190 I KnoxUsageLogPro: premStatus:2
,07-28 12:43:59.260  7190  7190 I KnoxUsageLogPro: isEulaShown : false
07-28 12:43:59.260  7190  7190 I KnoxUsageLogPro: KnoxUsageReceiver onReceive : not Processible, just return
07-28 12:43:59.260  7858  8543 I SA      : [TPMU] GetMccFromDB : null
,07-28 12:43:59.260  3705  8541 I DBG_POLICYDM: [com.policydm.db.XDBFile(61/xdbFileExists)] doesn't exist target file: /data/security/mac_permissions.xml
,07-28 12:43:59.260  7858  8543 I SA      : [SCU] getMccFromPreferece mcc = 260
,07-28 12:43:59.260  7858  8543 I SA      : [TPM] isNoProxy(default) : true
,07-28 12:43:59.270  3705  8541 I DBG_POLICYDM: [com.policydm.XDMBroadcastReceiver(294/xdmExecResumeCase)] Start resumecase for INIT
,07-28 12:43:59.280  3705  8541 E DBG_POLICYDM: [com.policydm.db.XDBSpdAdp(35/xdbGetSpdDeviceRegister)] Device is Registered
,07-28 12:43:59.280  7858  8543 E File    : fail readDirectory() errno=2
,07-28 12:43:59.280   791   832 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.290   791  1151 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 502] cleared because we found a replacement network
,07-28 12:43:59.290   791   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:43:59.290   791   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecContacts_Phone_OSup/SecContacts_Phone_OSup.apk
,07-28 12:43:59.290   791  1259 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.290   791  3300 I SQLiteConnectionPool: ...exportDB
,07-28 12:43:59.300  3705  8541 I DBG_POLICYDM: [com.sec.android.fota.common.Network(88/isWiFiNetworkConnected)] WiFi Network is connected
,07-28 12:43:59.300   791  3300 D SSRM:aY : MSG_TYPE_APP_REMOVED::
,07-28 12:43:59.300   791   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-28 12:43:59.300   791   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecGallery2013/SecGallery2013.apk
,07-28 12:43:59.310   791  1469 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.310   362   362 I ServiceManager: Waiting for service AtCmdFwd...
07-28 12:43:59.310   791   832 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.310   791   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-28 12:43:59.310   791   994 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-28 12:43:59.310   791   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecMyFiles2/SecMyFiles2.apk
,07-28 12:43:59.320   791  1065 I art     : Explicit concurrent mark sweep GC freed 85720(5MB) AllocSpace objects, 16(256KB) LOS objects, 29% free, 37MB/53MB, paused 1.948ms total 342.047ms
,07-28 12:43:59.320  7984  7984 D QuickConnect: PeriphStartReceiver.onReceive - android.net.conn.CONNECTIVITY_CHANGE
,07-28 12:43:59.320  7984  7984 I QuickConnect: PeriphStartReceiver.onReceive - USER_OWNER care CONNECTIVITY_ACTION. run P service
07-28 12:43:59.320  7984  7984 I QuickConnect: PeriphStartReceiver.onReceive - no need to start
,07-28 12:43:59.330   791  1638 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.330   791  1443 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.330   791  1532 D RCPManagerService: exchangeData() failure , invalid userId
,07-28 12:43:59.330   791  1657 D RCPManagerService: exchangeData() failure , invalid userId
,07-28 12:43:59.340   791  1574 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.340  7514  7514 D SecurityLogAgent: KnoxConfiguration : Current State = 1
07-28 12:43:59.340  7514  7514 D SecurityLogAgent: KnoxConfiguration : Current State Mapping Found 
07-28 12:43:59.340  7514  7514 D SecurityLogAgent: StateMachine : Current State = 1
07-28 12:43:59.340   791  1144 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:59.340  7514  7514 D SecurityLogAgent: StateMachine : Changed Current State = 1
,07-28 12:43:59.340   791  1065 D PackageManager: delete codoeFile: 
,07-28 12:43:59.340   791  1259 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.340   791   832 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.350   791   831 D ActivityManager: startService callerProcessName:com.sec.android.app.SmartClipService, calleePkgName: com.sec.android.app.SmartClipService
,07-28 12:43:59.350   791   831 D ActivityManager: caller:android.app.ApplicationThreadProxy@5a0cd27, r.packageName :com.sec.android.app.SmartClipService
,07-28 12:43:59.350   791  1532 D ActivityManager: startService callerProcessName:com.google.android.gms, calleePkgName: com.google.android.gms
,07-28 12:43:59.350   791  1532 D ActivityManager: caller:android.app.ApplicationThreadProxy@37236bd4, r.packageName :com.google.android.gms
07-28 12:43:59.350   791  1065 D AASAuninstall: userId = 0, info.removedAppID = 10079, info.uid = 10079, packageName = com.test.thalitest
,07-28 12:43:59.350   791  1065 I AASA_removePackage: UID=10079 Target=com.test.thalitest
,07-28 12:43:59.350   791  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.360   791  1468 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.360   791  1358 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:59.360  4536  4536 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
07-28 12:43:59.360   791  1065 D PackageManager: result of delete: 1{339330753}
,07-28 12:43:59.360  8518  8518 D AndroidRuntime: Shutting down VM
,07-28 12:43:59.360  4536  5525 I iu.UploadsManager: num queued entries: 0
,07-28 12:43:59.360  4536  5525 I iu.UploadsManager: num updated entries: 0
,07-28 12:43:59.360  4536  5525 I iu.SyncManager: NEXT; no task
,07-28 12:43:59.390   791  1469 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.390   791  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.390   791   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-28 12:43:59.390   791   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SecVideoPlayer/SecVideoPlayer.apk
,07-28 12:43:59.390   791   832 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.390   791  1358 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.390  7089  7089 D WaitQueueForNetworkActivate: notifyNetworkActivated
,07-28 12:43:59.400   791   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
07-28 12:43:59.400   791   994 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
,07-28 12:43:59.400   791   994 D ResourcesManager: creating new AssetManager and set to /system/priv-app/VoiceNote/VoiceNote.apk
,07-28 12:43:59.400   791   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:43:59.400   791   994 W Resources: Converting to string: TypedValue{t=0x12/d=0x0 a=-1}
07-28 12:43:59.400   791   994 D ResourcesManager: creating new AssetManager and set to /system/app/SBrowser/SBrowser.apk
,07-28 12:43:59.410   791   994 W Resources: Converting to string: TypedValue{t=0x12/d=0xffffffff a=-1}
,07-28 12:43:59.410   791   994 D UsbSettingsManager: clearDefaults: com.test.thalitest
,07-28 12:43:59.410   791   994 I CrashAnrDetector: onPackageRemoved : com.test.thalitest
,07-28 12:43:59.510   791  1532 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.510  1897  8548 I qtaguid : Tagging socket 52 with tag 1000040700000000{268436487,0} uid -1, pid: 1897, getuid(): 10015
,07-28 12:43:59.510   791  1144 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.510   791  1468 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.510   791  1358 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.530   791  1574 D ActivityManager: startService callerProcessName:com.sec.android.app.samsungapps, calleePkgName: com.sec.android.app.samsungapps
,07-28 12:43:59.530   791  1574 D ActivityManager: caller:android.app.ApplicationThreadProxy@13c2e879, r.packageName :com.sec.android.app.samsungapps
,07-28 12:43:59.530  2502  2502 I KLMS-2.4.511: : KLMSSystemProperties(): getBoolean(): ro.product_ship = true
,07-28 12:43:59.530  2502  2502 I KLMS-2.4.511: : MainReciver(): EventNotificationReciver- method called: AppActivityListner onReceive for Intent Action : android.intent.action.PACKAGE_REMOVED , timestamp: 1469702639543
,07-28 12:43:59.530  2502  2502 I KLMS-2.4.511: : MainReciver(): PACKAGE_REMOVED
,07-28 12:43:59.530  2502  2502 I KLMS-2.4.511: : MainReciver(): REPLACING: false | pkgName: com.test.thalitest
,07-28 12:43:59.540  7089  7089 D hcjo    : AutoUpdateManager:IDLE:AutoUpdateManager::execute : false false true state: IDLE
,07-28 12:43:59.540  7089  7089 D hcjo    : AutoUpdateManager:INITCHECK:AutoUpdateManager::checkInitialize
,07-28 12:43:59.540  7089  7089 D InitializeManagerStateMachine: execute::IDLE:EXECUTE
,07-28 12:43:59.540  7089  7089 D InitializeManagerStateMachine: exit::IDLE
07-28 12:43:59.540  7089  7089 D InitializeManagerStateMachine: entry::NETWORK_CHECK
,07-28 12:43:59.540   791  1443 D ConnectivityService: returning getNetworkInfo(networkType - 0) :[type: MOBILE[] - MOBILE, state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:59.540   791  1532 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.540  7089  7089 D InitializeManagerStateMachine: execute::NETWORK_CHECK:NETWORK_STATE_OK
07-28 12:43:59.540  7089  7089 D InitializeManagerStateMachine: exit::NETWORK_CHECK
07-28 12:43:59.540  7089  7089 D InitializeManagerStateMachine: entry::CHECK_COUNTRY_INFO
07-28 12:43:59.540  7089  7089 D InitializeManagerStateMachine: execute::CHECK_COUNTRY_INFO:COUNTRY_INFO_OK
07-28 12:43:59.540  7089  7089 D InitializeManagerStateMachine: exit::CHECK_COUNTRY_INFO
07-28 12:43:59.540  7089  7089 D InitializeManagerStateMachine: entry::SUCCESS
,07-28 12:43:59.540  7089  7089 D hcjo    : AutoUpdateManager:INITCHECK:onInitializeSuccess
,07-28 12:43:59.550   791  1151 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 504]; created=true
,07-28 12:43:59.550   791   791 D SmartBondingService: SmartBondingReceiver: onReceive action=android.net.wifi.LINK_CONFIGURATION_CHANGED
07-28 12:43:59.550   791  1151 D ConnectivityService: updateLinkProperties: newLp = {InterfaceName: wlan0 LinkAddresses: [192.168.1.122/24,fe80::ea50:8bff:fede:28a3/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,4525824,524288,1048576,4525824}
07-28 12:43:59.550   791  1151 D ConnectivityService: identical MTU - not setting
07-28 12:43:59.550   791  1151 D ConnectivityService: updateSourceRoutes : add source routing for type : 1
07-28 12:43:59.550   791  1151 D ConnectivityService: updateSourceRoutes : add src route for:fe80::ea50:8bff:fede:28a3
07-28 12:43:59.550   791   791 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
07-28 12:43:59.550   299  1061 V         : QcRouteController
,07-28 12:43:59.550   791  1153 D SmartBondingService: EVENT_UPDATE_SB_STATE called / mDisableBySIOP false
07-28 12:43:59.550   791  1153 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:43:59.550   791  1153 D SmartBondingService: getSBEnabled() enabled =false
07-28 12:43:59.550   791  1153 D SmartBondingService: getSBEnabled() enabled =false
,07-28 12:43:59.550  7089  7089 D hcjo    : AutoUpdateTriggerManager:IDLE:notifyNextTime
,07-28 12:43:59.550  7089  7089 D hcjo    : AutoUpdateManager:UPD_CHECK_TIMING:onNoUpdateTime
07-28 12:43:59.550   791  1469 D ConnectivityService: returning getNetworkInfo(networkType - 1) :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.550  7089  7089 D InitializeManagerStateMachine: exit::SUCCESS
07-28 12:43:59.550  7089  7089 D InitializeManagerStateMachine: entry::IDLE
,07-28 12:43:59.550   791  3300 D SSRM:n  : SIOP:: AP = 390, PST = 382, CUR = 450
,07-28 12:43:59.570   299  1061 V         : QcRouteController
,07-28 12:43:59.570   791  1151 W NetworkManagementService: route cmd failed: 
07-28 12:43:59.570   791  1151 W NetworkManagementService: com.android.server.NativeDaemonConnector$NativeDaemonFailureException: command '105 route replace src v6 wlan0 fe80::ea50:8bff:fede:28a3 2 ::' failed with '400 105 -6 route replace default via :: dev wlan0 scope global table 2: RTNETLINK answers: Invalid argument
07-28 12:43:59.570   791  1151 W NetworkManagementService: '
07-28 12:43:59.570   791  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:444)
07-28 12:43:59.570   791  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.executeForList(NativeDaemonConnector.java:377)
07-28 12:43:59.570   791  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:342)
07-28 12:43:59.570   791  1151 W NetworkManagementService: 	at com.android.server.NativeDaemonConnector.execute(NativeDaemonConnector.java:327)
07-28 12:43:59.570   791  1151 W NetworkManagementService: 	at com.android.server.NetworkManagementService.replaceSrcRoute(NetworkManagementService.java:2844)
07-28 12:43:59.570   791  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateSourceRoutes(ConnectivityService.java:5632)
07-28 12:43:59.570   791  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService.updateLinkProperties(ConnectivityService.java:5444)
07-28 12:43:59.570   791  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService.access$2400(ConnectivityService.java:230)
07-28 12:43:59.570   791  1151 W NetworkManagementService: 	at com.android.server.ConnectivityService$NetworkStateTrackerHandler.handleMessage(ConnectivityService.java:2387)
07-28 12:43:59.570   791  1151 W NetworkManagementService: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:43:59.570   791  1151 W NetworkManagementService: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:43:59.570   791  1151 W NetworkManagementService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,07-28 12:43:59.570   791  1151 V Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true
07-28 12:43:59.570   791  1151 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
07-28 12:43:59.570   791  1151 D ConnectivityService: calling update connectivity
07-28 12:43:59.570   791  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-28 12:43:59.570   791  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:59.570   791  1151 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-28 12:43:59.570   791  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:59.570  1193  1581 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,07-28 12:43:59.570   791  1151 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-28 12:43:59.570  4536  7290 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
07-28 12:43:59.570   791  1151 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 504]
07-28 12:43:59.570   791  1151 D ConnectivityService: calling update connectivity
,07-28 12:43:59.570   791  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
07-28 12:43:59.570   791  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,07-28 12:43:59.570   791  1151 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
07-28 12:43:59.570  1193  1581 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,07-28 12:43:59.570   791  1151 D ConnectivityService:  sending notification for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-28 12:43:59.570   791  1151 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,07-28 12:43:59.580  4536  7290 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,07-28 12:43:59.600   791  1065 D PackageManager: [MSG] START_CLEANING_PACKAGE packageName{com.test.thalitest}
07-28 12:43:59.600   791  1065 D PackageManager: userId{-1}
07-28 12:43:59.600   791  1065 D PackageManager: andCode{true}
,07-28 12:43:59.600   791  1065 D ActivityManager: caller:null, r.packageName :com.android.defcontainer
,07-28 12:43:59.600   791  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:59.600   791  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:59.600   791  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:59.600   791  1065 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:59.610  2502  2502 I KLMS-2.4.511: : MainReciver(): Notification App List is Null. Remove Notification.
,07-28 12:43:59.610  2502  2502 I KLMS-2.4.511: : KLMSValidator(): IsPackageExistInDevice().Not Exsit: com.test.thalitest
,07-28 12:43:59.630   791  1476 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.630   791  1469 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.630   791  1259 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.630   791   832 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.640  8556  8556 E Zygote  : MountEmulatedStorage()
07-28 12:43:59.640  8556  8556 E Zygote  : v2
07-28 12:43:59.640  8556  8556 I libpersona: KNOX_SDCARD checking this for 10007
07-28 12:43:59.640  8556  8556 I libpersona: KNOX_SDCARD not a persona
,07-28 12:43:59.650   791  1065 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8556 uid=10007 gids={50007, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,07-28 12:43:59.650   791  1443 D ActivityManager: startProcessLocked calleePkgName: com.sec.esdk.elm, hostingType: broadcast
,07-28 12:43:59.650   791  1443 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:59.650   791  1443 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:59.650   791  1443 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:59.650   791  1443 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:59.670   347   347 I art     : Explicit concurrent mark sweep GC freed 8716(371KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 308us total 14.538ms
,07-28 12:43:59.680   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 276us total 9.621ms
,07-28 12:43:59.680  8556  8556 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:43:59.680  8556  8556 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:43:59.680  8556  8556 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:43:59.690   347   347 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 15MB/25MB, paused 274us total 9.817ms
,07-28 12:43:59.710  8556  8556 D TimaKeyStoreProvider: TimaSignature is unavailable
07-28 12:43:59.710  8556  8556 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:59.730  8572  8572 E Zygote  : MountEmulatedStorage()
07-28 12:43:59.730  8572  8572 I libpersona: KNOX_SDCARD checking this for 10116
07-28 12:43:59.730  8572  8572 E Zygote  : v2
07-28 12:43:59.730  8572  8572 I libpersona: KNOX_SDCARD not a persona
,07-28 12:43:59.730   791  1443 I ActivityManager: Start proc com.sec.esdk.elm for broadcast com.sec.esdk.elm/.receiver.MainReceiver: pid=8572 uid=10116 gids={50116, 9997, 3003} abi=armeabi-v7a
,07-28 12:43:59.760  8572  8572 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:43:59.760  8572  8572 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:43:59.760  8572  8572 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:43:59.770  8556  8556 D ResourcesManager: creating new AssetManager and set to /system/priv-app/DefaultContainerService/DefaultContainerService.apk
,07-28 12:43:59.770   791   832 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.770   791   831 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.770   791  1574 D ConnectivityService: returning getActiveNetworkInfo :[type: WIFI[] - WIFI, state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,07-28 12:43:59.780  1441  1441 D SurfaceWidgetView: destroyHardwareResources():961023008
,07-28 12:43:59.780   791  1638 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
,07-28 12:43:59.780   791  1638 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
07-28 12:43:59.780   791  1638 V WindowManager: rotationForOrientationLw(orient=1, last=0); user=0  sensorRotation=-1 mLidState=-1 mDockMode=0 mHdmiPlugged=false
07-28 12:43:59.780   791  1638 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, mbResultFaceDectection: false
07-28 12:43:59.780   791  1638 V WindowOrientationListener: mSContextAutoRotationListener.getProposedRotation, Rotation: -1
,07-28 12:43:59.780  1441  1441 D Launcher: onRestart, Launcher: 114770630
,07-28 12:43:59.780  1441  1441 D Launcher: onStart, Launcher: 114770630
07-28 12:43:59.780  1441  1441 D Launcher.HomeView: onStart
,07-28 12:43:59.780  1441  1441 V ActivityThread: updateVisibility : ActivityRecord{79997a token=android.os.BinderProxy@2c53ff60 {com.sec.android.app.launcher/com.android.launcher2.Launcher}} show : true
,07-28 12:43:59.780  1813  1833 D SurfaceWidgetClient$ISurfaceWidgetStub: [237392/8] Surface widget visibility changed visibility = true on instance = 1
,07-28 12:43:59.790  1813  2089 D SurfaceWidget.Renderer: [237392/8] SurfaceWidget drawing first frame
,07-28 12:43:59.790  1813  2089 D accuweather: [Accuweather J]>>> WR:623 [0:0] onGLDraw : BG texture = 5
,07-28 12:43:59.790  8572  8572 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:43:59.790  8572  8572 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:59.800   266   266 I SurfaceFlinger: id=14 createSurf (1080x1920),1 flag=4, Mauncher
,07-28 12:43:59.800   791  1041 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-28 12:43:59.800   791  1041 D StatusBarManagerService: manageDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
,07-28 12:43:59.810   791  1046 D PointerIcon: setMouseIconStyle1 pointerType: 1001iconType:101 flag:0
07-28 12:43:59.810   791  1046 D PointerIcon: setMouseCustomIcon IconType is same.101
07-28 12:43:59.810   791  1046 D PointerIcon: setHoveringSpenIconStyle1 pointerType: 10001iconType:1 flag:0
07-28 12:43:59.810   791  1046 D PointerIcon: setHoveringSpenCustomIcon IconType is same.1
,07-28 12:43:59.820   791  1122 I EventHub: Removing device '/dev/input/event6' due to inotify event
,07-28 12:43:59.820   791  1259 D InputMethodManagerService: windowGainedFocus mCurrentFocusedUserId - 0 and mSecureKeypadEnabled-false
,07-28 12:43:59.820   791  1259 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 7441 uid 10079
,07-28 12:43:59.820   791  8591 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1686 com.android.server.InputMethodManagerService$6.run:2733 java.lang.Thread.run:818 <bottom of call stack> <bottom of call stack> 
,07-28 12:43:59.820  8572  8572 D ResourcesManager: creating new AssetManager and set to /system/app/ELMAgent/ELMAgent.apk
,07-28 12:43:59.820  8572  8572 W ContextImpl: Unable to create files subdir /data/data/com.sec.esdk.elm/cache
07-28 12:43:59.820  8572  8572 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,07-28 12:43:59.830  8572  8572 D elm:14491: ELMAbstractReceiver.onReceive() : Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.receiver.MainReceiver (has extras) }
,07-28 12:43:59.840  8572  8572 D elm:14491: ELMEngine.ELMEngine( context ).
,07-28 12:43:59.840  8572  8572 D elm:14491: MDMBridge.setEnterpriseBridge()
,07-28 12:43:59.840   791  1638 D ActivityManager: startService callerProcessName:com.sec.esdk.elm, calleePkgName: com.sec.esdk.elm
,07-28 12:43:59.840   791  1638 D ActivityManager: caller:android.app.ApplicationThreadProxy@5a0616c, r.packageName :com.sec.esdk.elm
,07-28 12:43:59.840  8572  8572 D elm:14491: ELMAbstractReceiver : Receive Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) } END.
,07-28 12:43:59.850   791  1122 I EventHub: Removing device '/dev/input/event7' due to inotify event
,07-28 12:43:59.850  3821  3821 D AASAservice-UpdateReceiver: AASAUpdateReceiver: android.intent.action.PACKAGE_REMOVED, package = com.test.thalitest, uid = -1
07-28 12:43:59.850  3821  3821 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
07-28 12:43:59.850  3821  3821 W System.err: 	at android.app.ApplicationPackageManager.getApplicationInfo(ApplicationPackageManager.java:304)
07-28 12:43:59.850  3821  3821 W System.err: 	at com.samsung.aasaservice.AASAUpdateReceiver.onReceive(AASAUpdateReceiver.java:33)
07-28 12:43:59.850  3821  3821 W System.err: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
07-28 12:43:59.850  3821  3821 W System.err: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-28 12:43:59.850  3821  3821 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-28 12:43:59.850  3821  3821 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:43:59.850  3821  3821 W System.err: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:43:59.850  3821  3821 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:43:59.850  3821  3821 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:43:59.850  3821  3821 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:43:59.850  3821  3821 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:43:59.850   791  1657 D ActivityManager: startProcessLocked calleePkgName: com.sec.android.service.health, hostingType: broadcast
07-28 12:43:59.850  3821  3821 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,07-28 12:43:59.860  8572  8572 D elm:14491: ElmAgentService : onCreate()
,07-28 12:43:59.860  8572  8593 D elm:14491: ElmAgentService : onHandleIntent() Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.sec.esdk.elm/.service.ElmAgentService (has extras) }
,07-28 12:43:59.860  8572  8593 D elm:14491: MainReceiver.listeningToPackageRemoved()
07-28 12:43:59.860  8572  8593 D elm:14491: MDMBridge.getInstance()
07-28 12:43:59.860  8572  8593 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,07-28 12:43:59.860   791  1657 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:59.860   791  1657 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:59.860   791  1657 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:43:59.860   791  1657 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:43:59.860  8572  8593 D elm:14491: MDMBridge.getAllLicenseInfoFromSDK()
,07-28 12:43:59.890   791  1122 I EventHub: Removing device '/dev/input/event8' due to inotify event
,07-28 12:43:59.890  7858  8543 I SA      : [RC New] Execute method=[GET] start
,07-28 12:43:59.900  8595  8595 E Zygote  : MountEmulatedStorage()
07-28 12:43:59.900  8595  8595 E Zygote  : v2
07-28 12:43:59.900  8595  8595 I libpersona: KNOX_SDCARD checking this for 10021
07-28 12:43:59.900  8595  8595 I libpersona: KNOX_SDCARD not a persona
,07-28 12:43:59.910   791  1657 I ActivityManager: Start proc com.sec.android.service.health for broadcast com.sec.android.service.health/.upgrade.UninstallReceiver: pid=8595 uid=10021 gids={50021, 9997} abi=armeabi-v7a
,07-28 12:43:59.930  7858  8543 I SA      : [RC New] Security=[true]
,07-28 12:43:59.930  7858  8543 I System.out: Thread-1285(ApacheHTTPLog):Reading from variable values from setDefaultValuesToVariables
,07-28 12:43:59.940   791  1122 I EventHub: Removing device '/dev/input/event9' due to inotify event
,07-28 12:43:59.940  7858  8543 I System.out: Thread-1285(ApacheHTTPLog):isShipBuild true
,07-28 12:43:59.960  8595  8595 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:43:59.960  8595  8595 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:43:59.960  8595  8595 E SELinux : [DEBUG] get_category: variable seinfo: platform sensitivity: NULL, cateogry: NULL
,07-28 12:43:59.960  8572  8572 D elm:14491: ElmAgentService : onDestroy().
,07-28 12:43:59.960   791  1046 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1f2ced90 u0 com.sec.android.app.launcher/com.android.launcher2.Launcher t97} time:190118
,07-28 12:43:59.970   791  1468 I ActivityManager: Killing 7110:com.sec.enterprise.knox.cloudmdm.smdms/u0a201 (adj 15): emptyCount ##41
,07-28 12:43:59.980   791  1122 I EventHub: Removing device '/dev/input/event10' due to inotify event
,07-28 12:43:59.980  8595  8595 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:43:59.980  8595  8595 D ActivityThread: Added TimaKeyStore provider
,07-28 12:43:59.990  7858  8543 I System.out: Thread-1285(ApacheHTTPLog):SmartBonding Enabling is true, SHIP_BUILD is true, log to file is false, DBG is false
,07-28 12:43:59.990   791  1116 V AlarmManager: waitForAlarm result :8
,07-28 12:43:59.990  8595  8595 D ResourcesManager: creating new AssetManager and set to /system/priv-app/HealthService/HealthService.apk
,07-28 12:44:00.000  8595  8595 W ContextImpl: Unable to create files subdir /data/data/com.sec.android.service.health/cache
07-28 12:44:00.000  8595  8595 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,07-28 12:44:00.030  8595  8595 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive()
07-28 12:44:00.030  8595  8595 I com.sec.android.service.health.upgrade.UninstallReceiver: onReceive called  PACKAGE_REMOVED package:com.test.thalitest
07-28 12:44:00.030  8595  8595 D com.sec.android.service.health.upgrade.UninstallReceiver: onReceive() : package name is not s health. Return !!!
,07-28 12:44:00.030  6096  6096 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-28 12:44:00.030  6096  6096 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM config WHERE config_id=?] disk I/O error
,07-28 12:44:00.030  6096  6096 D AndroidRuntime: Shutting down VM
,07-28 12:44:00.040  6764  6764 I PCWCLIENTTRACE_PushUtil: SPPPushClient is installed : true
07-28 12:44:00.040  6764  6764 I PCWCLIENTTRACE_PushUtil: sales region : global
07-28 12:44:00.040  6764  6764 I PCWCLIENTTRACE_PushUtil: getPushTypeList : [SPP, GCM]
07-28 12:44:00.040  6764  6764 I PCWCLIENTTRACE_SYSTEMReceiver: [onReceive] - android.intent.action.PACKAGE_REMOVED
,07-28 12:44:00.040  6096  6096 D HockeyApp: Writing unhandled exception to: /data/data/sstream.app/files/e16601b4-5af7-4af5-949f-49a0bf8eb967.stacktrace
,07-28 12:44:00.040  6096  6096 E HockeyApp: Error saving exception stacktrace!
07-28 12:44:00.040  6096  6096 E HockeyApp: 
07-28 12:44:00.040  6096  6096 E HockeyApp: java.io.FileNotFoundException: /data/data/sstream.app/files/e16601b4-5af7-4af5-949f-49a0bf8eb967.stacktrace: open failed: ENOENT (No such file or directory)
07-28 12:44:00.040  6096  6096 E HockeyApp: 	at libcore.io.IoBridge.open(IoBridge.java:456)
07-28 12:44:00.040  6096  6096 E HockeyApp: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
07-28 12:44:00.040  6096  6096 E HockeyApp: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
07-28 12:44:00.040  6096  6096 E HockeyApp: 	at java.io.FileWriter.<init>(FileWriter.java:80)
07-28 12:44:00.040  6096  6096 E HockeyApp: 	at net.hockeyapp.android.internal.ExceptionHandler.saveException(ExceptionHandler.java:83)
07-28 12:44:00.040  6096  6096 E HockeyApp: 	at net.hockeyapp.android.internal.ExceptionHandler.uncaughtException(ExceptionHandler.java:108)
07-28 12:44:00.040  6096  6096 E HockeyApp: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:693)
07-28 12:44:00.040  6096  6096 E HockeyApp: 	at java.lang.ThreadGroup.uncaughtException(ThreadGroup.java:690)
07-28 12:44:00.040  6096  6096 E HockeyApp: Caused by: android.system.ErrnoException: open failed: ENOENT (No such file or directory)
07-28 12:44:00.040  6096  6096 E HockeyApp: 	at libcore.io.Posix.open(Native Method)
07-28 12:44:00.040  6096  6096 E HockeyApp: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
07-28 12:44:00.040  6096  6096 E HockeyApp: 	at libcore.io.IoBridge.open(IoBridge.java:442)
07-28 12:44:00.040  6096  6096 E HockeyApp: 	... 7 more
,07-28 12:44:00.050   791  1122 I EventHub: Removing device '/dev/input/event11' due to inotify event
,07-28 12:44:00.050   791  1443 D ActivityManager: startService callerProcessName:com.sec.android.app.shealth, calleePkgName: com.sec.android.app.shealth
,07-28 12:44:00.050   791  1443 D ActivityManager: caller:android.app.ApplicationThreadProxy@1b9703ca, r.packageName :com.sec.android.app.shealth
,07-28 12:44:00.060  7842  7842 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/registration_db" with flag (131138) and mode_t (0) due to error (2)
07-28 12:44:00.060  7842  7842 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/registration_db" with flag (131072) and mode_t (0) due to error (2)
07-28 12:44:00.060  7842  7842 E SQLiteLog: (14) cannot open file at line 32509 of [b3bb660af9]
07-28 12:44:00.060  7842  7842 E SQLiteLog: (14) os_unix.c:32509: (2) open(/data/data/com.sec.spp.push/databases/registration_db) - 
,07-28 12:44:00.060  7842  7842 E SQLiteDatabase: Failed to open database '/data/data/com.sec.spp.push/databases/registration_db'.
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at com.sec.spp.push.h.a.a(Unknown Source)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at com.sec.spp.push.h.c.d(Unknown Source)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.a(Unknown Source)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at com.sec.spp.push.receiver.PackageInfoChangeReceiver.onReceive(Unknown Source)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:44:00.060  7842  7842 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
07-28 12:44:00.060  7842  7842 E SPPClientService: [c] [getAppId()] SQLiteException with message =unknown error (code 14): Could not open database
,07-28 12:44:00.060   791  1574 D ActivityManager: startProcessLocked calleePkgName: com.sec.spp.push, hostingType: broadcast
,07-28 12:44:00.060   791  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:44:00.060   791  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:44:00.060   791  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:44:00.060   791  1574 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:44:00.070  4602  8611 E SQLiteLog: (10) POSIX Error : 9 SQLite Error : 3850
07-28 12:44:00.070  4602  8611 E SQLiteLog: (3850) statement aborts at 19: [delete  from app_registry where package_name= "com.test.thalitest" AND plugin_id= "1"] disk I/O error
,07-28 12:44:00.070  4602  8611 E SQLiteQuery: exception: disk I/O error (code 3850); query: delete  from app_registry where package_name= "com.test.thalitest" AND plugin_id= "1"
,07-28 12:44:00.070  4602  8611 F libc    : Fatal signal 7 (SIGBUS), code 2, fault addr 0x9f449f8c in tid 8611 (IntentService[H)
,07-28 12:44:00.080   791  1122 I EventHub: Removing device '/dev/input/event12' due to inotify event
,07-28 12:44:00.120   791  1122 I EventHub: Removing device '/dev/input/event13' due to inotify event
,07-28 12:44:00.120  6133  6133 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/data/com.samsung.android.app.galaxyfinder/shared_prefs/pref_package.xml
,07-28 12:44:00.120   300   300 I DEBUG   : failed to change ownership of /data/tombstones: Read-only file system
07-28 12:44:00.120   300   300 E         : ro.product_ship = true
07-28 12:44:00.120   300   300 E         : ro.debug_level = 0x4f4c
,07-28 12:44:00.120  1871  1871 E audit_log: File locking failed. error= Bad file number
,07-28 12:44:00.120   304   304 E SMD     : DCD ON
,07-28 12:44:00.150  8613  8613 E Zygote  : MountEmulatedStorage()
07-28 12:44:00.150  8613  8613 I libpersona: KNOX_SDCARD checking this for 10043
07-28 12:44:00.150  8613  8613 E Zygote  : v2
07-28 12:44:00.150  8613  8613 I libpersona: KNOX_SDCARD not a persona
,07-28 12:44:00.150   791  1574 I ActivityManager: Start proc com.sec.spp.push:RemoteNotiProcess for broadcast com.sec.spp.push/.notisvc.registration.PackageRemovedReceiver: pid=8613 uid=10043 gids={50043, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,07-28 12:44:00.160   791  1358 D ActivityManager: startService callerProcessName:com.samsung.android.app.galaxyfinder, calleePkgName: com.samsung.android.app.galaxyfinder
07-28 12:44:00.160   791  1358 D ActivityManager: caller:android.app.ApplicationThreadProxy@36e82858, r.packageName :com.samsung.android.app.galaxyfinder
,07-28 12:44:00.170   791  1122 I EventHub: Removing device '/dev/input/event14' due to inotify event
,07-28 12:44:00.210  8613  8613 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:44:00.210  8613  8613 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
,07-28 12:44:00.210  8613  8613 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,07-28 12:44:00.210   791  1259 I ActivityManager: Process com.sec.android.app.shealth (pid 4602)(adj 5) has died(342,1498)
,07-28 12:44:00.210   791  1259 W ActivityManager: Scheduling restart of crashed service com.sec.android.app.shealth/.service.HandleAppDataService in 1000ms
,07-28 12:44:00.230  8613  8613 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:44:00.230  8613  8613 D ActivityThread: Added TimaKeyStore provider
,07-28 12:44:00.240  8613  8613 D ResourcesManager: creating new AssetManager and set to /system/priv-app/SPPPushClient_Prod/SPPPushClient_Prod.apk
,07-28 12:44:00.240  8613  8613 W ContextImpl: Unable to create files subdir /data/data/com.sec.spp.push/cache
07-28 12:44:00.240  8613  8613 E ActivityThread: Unable to setupGraphicsSupport due to missing cache directory
,07-28 12:44:00.260   347   347 I Zygote  : Process 4602 exited due to signal (7)
,07-28 12:44:00.270  8613  8613 E SPPClientService: ============PushLog. commonIsShipBuild. stop!
,07-28 12:44:00.270  8613  8613 E SPPClientService: [PushClientApplication] Push log off : This is Ship build version
,07-28 12:44:00.280  8613  8613 W ContextImpl: Unable to create files subdir /data/data/com.sec.spp.push/files
,07-28 12:44:00.280  8613  8613 D SPPClientService: PushLog.txt file is not deleted.
07-28 12:44:00.280  8613  8613 W ContextImpl: Unable to create files subdir /data/data/com.sec.spp.push/files
,07-28 12:44:00.280  8613  8613 D SPPClientService: PushLog.txt file is not deleted.
07-28 12:44:00.280  8613  8613 D SPPClientService: ============PushLog. stop!
,07-28 12:44:00.280  8613  8613 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131138) and mode_t (0) due to error (2)
,07-28 12:44:00.280  8613  8613 E SQLiteLog: (28) failed to open "/data/data/com.sec.spp.push/databases/push_noti_db" with flag (131072) and mode_t (0) due to error (2)
07-28 12:44:00.280  8613  8613 E SQLiteLog: (14) cannot open file at line 32509 of [b3bb660af9]
07-28 12:44:00.280  8613  8613 E SQLiteLog: (14) os_unix.c:32509: (2) open(/data/data/com.sec.spp.push/databases/push_noti_db) - 
,07-28 12:44:00.280  8613  8613 E SQLiteDatabase: Failed to open database '/data/data/com.sec.spp.push/databases/push_noti_db'.
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: android.database.sqlite.SQLiteCantOpenDatabaseException: unknown error (code 14): Could not open database
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:318)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:228)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:512)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:206)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:894)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:864)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:699)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1507)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:282)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.a.b.<init>(Unknown Source)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.a.b.a(Unknown Source)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.l.b(Unknown Source)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.l.a(Unknown Source)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.a(Unknown Source)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at com.sec.spp.push.notisvc.registration.PackageRemovedReceiver.onReceive(Unknown Source)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2989)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at android.app.ActivityThread.access$1800(ActivityThread.java:177)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1525)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:145)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5938)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:1400)
07-28 12:44:00.280  8613  8613 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:1195)
,07-28 12:44:00.290  8613  8613 E LNoti   : [b] open fail. SQLException occured
,07-28 12:44:00.290   791  1259 D ActivityManager: startProcessLocked calleePkgName: com.samsung.android.sdk.samsunglink, hostingType: broadcast
,07-28 12:44:00.290   791  1259 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:44:00.290   791  1259 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:44:00.290   791  1259 E ActivityManager: checkUser: useridlist=null, currentuser=0
07-28 12:44:00.290   791  1259 E ActivityManager: checkUser: useridlist=null, currentuser=0
,07-28 12:44:00.310   362   362 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,07-28 12:44:00.330   791  1259 I ActivityManager: Start proc com.samsung.android.sdk.samsunglink for broadcast com.samsung.android.sdk.samsunglink/com.sec.pcw.service.push.spp.SPPReceiver: pid=8629 uid=10048 gids={50048, 9997, 1007, 3003, 1028, 1015, 1023, 3002, 3001} abi=armeabi-v7a
,07-28 12:44:00.330   791  1259 I ActivityManager: Killing 5725:com.sec.android.gallery3d/u0a53 (adj 15): emptyCount ##41
,07-28 12:44:00.330  8629  8629 E Zygote  : MountEmulatedStorage()
07-28 12:44:00.330  8629  8629 E Zygote  : v2
07-28 12:44:00.330  8629  8629 I libpersona: KNOX_SDCARD checking this for 10048
07-28 12:44:00.330  8629  8629 I libpersona: KNOX_SDCARD not a persona
,07-28 12:44:00.410  8629  8629 I SELinux : Function: selinux_compare_spd_ram, SPD-policy is existed. and_ver=SEPF_SM-N9005_5.0-1 ver=1
07-28 12:44:00.410  8629  8629 I SELinux : Function: selinux_compare_spd_ram , priority [2] , priority version is VE=SEPF_SM-N9005_5.0-1_0032
07-28 12:44:00.410  8629  8629 E SELinux : [DEBUG] get_category: variable seinfo: samsung sensitivity: NULL, cateogry: NULL
,07-28 12:44:00.420   266   512 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,07-28 12:44:00.430  8629  8629 D TimaKeyStoreProvider: TimaSignature is unavailable
,07-28 12:44:00.430  8629  8629 D ActivityThread: Added TimaKeyStore provider

```
