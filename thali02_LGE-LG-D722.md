#### Test 797510151684451_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-12 18:39:20.228   294   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-12 18:39:22.263  7153  7153 D AndroidRuntime: 
08-12 18:39:22.263  7153  7153 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-12 18:39:22.270  7153  7153 D AndroidRuntime: CheckJNI is OFF
08-12 18:39:22.621  7153  7153 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 18:39:22.642   867  1809 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 18:39:22.684   867  1809 D ActivityManager: setTaskToReturnTo : TaskRecord{f3f125f #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 18:39:22.684   867  1809 D ActivityManager: setTaskToReturnTo : TaskRecord{f3f125f #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 18:39:22.689   867  1809 D WindowStateEx: AppWindowTokenEx init.. 
08-12 18:39:22.735   867  1809 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7167 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-12 18:39:22.736   867  1809 D InputDispatcher: Focus left window: Window{22e6dba7 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-12 18:39:22.742  7153  7153 D AndroidRuntime: Shutting down VM
08-12 18:39:22.761  1874  1874 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-12 18:39:22.784   867   867 V ActivityManager: Display changed displayId=0
08-12 18:39:22.790  1746  1746 D DSDPConnection: Display #0 changed.
08-12 18:39:22.916  7167  7167 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-12 18:39:23.012  7167  7167 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-12 18:39:23.062  7167  7167 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6384-6386)
08-12 18:39:23.062  7167  7167 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 18:39:23.087  7167  7167 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {176c8368}
08-12 18:39:23.088  7167  7167 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 18:39:23.090  7167  7167 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 18:39:23.104  7167  7167 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-12 18:39:23.105  7167  7167 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 18:39:23.106  7167  7167 E SysUtils: ApplicationContext is null in ApplicationStatus
08-12 18:39:23.137  7167  7167 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-12 18:39:23.144  7167  7167 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 18:39:23.144  7167  7167 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 18:39:23.145  7167  7167 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-12 18:39:23.145  7167  7167 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-12 18:39:23.145  7167  7167 I Adreno-EGL: Build Date: 03/02/15 Mon
08-12 18:39:23.145  7167  7167 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-12 18:39:23.145  7167  7167 I Adreno-EGL: Remote Branch: 
08-12 18:39:23.145  7167  7167 I Adreno-EGL: Local Patches: 
08-12 18:39:23.145  7167  7167 I Adreno-EGL: Reconstruct Branch: 
08-12 18:39:23.214   281  1293 V AudioPolicyService: registerClient() client 0xb57e9560, uid 10030
08-12 18:39:23.231   867  1052 D BluetoothManagerService: Message: 20
08-12 18:39:23.231   867  1052 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@91e18f3:true
08-12 18:39:23.244  2026  3565 D BluetoothAdapterService(775588902): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2bcd6bac
08-12 18:39:23.315   867  1031 W ActivityManager: Activity pause timeout for ActivityRecord{9edf4ac u0 com.test.thalitest/.MainActivity t259}
08-12 18:39:23.371  7167  7167 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 18:39:23.384  7167  7167 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-12 18:39:23.390  7167  7167 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-12 18:39:23.396  7167  7167 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-12 18:39:23.397  7167  7167 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-12 18:39:23.412  7167  7167 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-12 18:39:23.420  7167  7167 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 18:39:23.420  7167  7167 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 18:39:23.474  7167  7167 I Activity: Activity.onPostResume() called 
08-12 18:39:23.481  7167  7232 D OpenGLRenderer: Render dirty regions requested: true
08-12 18:39:23.481  7167  7232 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 18:39:23.487  7167  7232 D OpenGLRenderer: Enabling debug mode 0
08-12 18:39:23.503  7167  7167 D Atlas   : Validating map...
08-12 18:39:23.508   867  3649 D SplitWindow: check instance of lgWin Window{397f24e3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 18:39:23.521  7167  7219 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-12 18:39:23.548   867  1051 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-12 18:39:23.551   867  1051 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-12 18:39:23.551  1380  1380 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-12 18:39:23.551  1380  1380 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-12 18:39:23.551  1380  1380 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-12 18:39:23.551  1380  1380 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-12 18:39:23.552   867  1051 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-12 18:39:23.552   867  1051 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-12 18:39:23.552   867  1051 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-12 18:39:23.553   867  1051 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@222dc162,  pkg=WindowManager.LayoutParams
08-12 18:39:23.553   867  1051 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-12 18:39:23.562   867  1781 D InputDispatcher: Focus entered window: Window{397f24e3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 18:39:23.590   867  1836 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-12 18:39:23.610  7167  7167 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
,08-12 18:39:23.610  7167  7167 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1a223e62 time:316934
08-12 18:39:23.612   867  1053 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +796ms (total +917ms)
08-12 18:39:23.613   867  1053 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{9edf4ac u0 com.test.thalitest/.MainActivity t259} time:316937
08-12 18:39:23.659  7167  7167 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-12 18:39:23.665  1621  1621 E b       : Unable to connect to the editor to retrieve text... will retry later
08-12 18:39:23.686  7167  7167 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-12 18:39:23.765  7167  7167 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7167
,08-12 18:39:23.913  7167  7167 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 18:39:24.259  7167  7234 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426119424
,08-12 18:39:24.278  7167  7234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 18:39:24.278  7167  7234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 18:39:24.278  7167  7234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 18:39:24.278  7167  7234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 18:39:24.278  7167  7234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-12 18:39:24.278  7167  7234 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@13731586 added. We now have 1 listener(s)
,08-12 18:39:24.286   867   894 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 18:39:24.290  7167  7234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,08-12 18:39:24.293  7167  7234 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-12 18:39:24.295  7167  7234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 18:39:24.295  7167  7234 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 18:39:24.306  7167  7234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 18:39:24.306  7167  7234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 18:39:24.306  7167  7234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 18:39:24.306  7167  7234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-12 18:39:24.306  7167  7234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 18:39:24.306  7167  7234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 18:39:24.306  7167  7234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 18:39:24.306  7167  7234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 18:39:24.306  7167  7234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 18:39:24.306  7167  7234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 18:39:24.306  7167  7234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 18:39:24.306  7167  7234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 18:39:24.306  7167  7234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 18:39:24.306  7167  7234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 18:39:24.306  7167  7234 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2d9ec79d added. We now have 1 listener(s)
08-12 18:39:24.306  7167  7234 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 18:39:24.316  7167  7234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 18:39:24.316  7167  7234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 18:39:24.318  7167  7234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 18:39:24.319  7167  7234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 18:39:24.319  7167  7234 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-12 18:39:24.325  7167  7234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 18:39:24.327   867  1880 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 18:39:24.328  7167  7234 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-12 18:39:24.337  2026  2062 D BluetoothAdapterService(775588902): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2bcd6bac
,08-12 18:39:24.343  7167  7234 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-12 18:39:24.344  7167  7234 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 18:39:24.344  7167  7234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 18:39:24.344  7167  7234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 18:39:24.344  7167  7234 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 18:39:24.344  7167  7234 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 18:39:24.344  7167  7234 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 18:39:24.344  7167  7234 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 18:39:24.344  7167  7234 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 18:39:24.344  7167  7234 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 18:39:24.345  7167  7234 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 18:39:24.346  7167  7234 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 18:39:24.347  7167  7167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 18:39:24.348  7167  7167 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 18:39:24.383  7167  7167 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 18:39:24.492  7167  7188 I art     : CheckpointMarkThreadRoots callback created = 0x9980e470
,08-12 18:39:24.523  7167  7188 I art     : CheckpointMarkThreadRoots callback created = 0x9980e440
,08-12 18:39:25.233   294   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-12 18:39:25.489  7167  7240 W jxcore-log: Initializing JXcore engine
,08-12 18:39:25.493  7167  7240 W jxcore-log: JXcore engine is ready
08-12 18:39:25.613  7240  7240 W Thread-864: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7321]" dev="sockfs" ino=7321 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-12 18:39:25.613  7240  7240 W Thread-864: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-12 18:39:25.613  7240  7240 W Thread-864: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7514]" dev="sockfs" ino=7514 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-12 18:39:25.613  7240  7240 W Thread-864: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-12 18:39:25.613  7240  7240 W Thread-864: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-12 18:39:25.613  7240  7240 W Thread-864: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[33858]" dev="sockfs" ino=33858 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-12 18:39:25.641  7167  7240 W jxcore-log: Starting JXcore engine
,08-12 18:39:25.792  7167  7240 W jxcore-log: Platform android
08-12 18:39:25.792  7167  7240 W jxcore-log: 
08-12 18:39:25.792  7167  7240 W jxcore-log: Process ARCH arm
08-12 18:39:25.792  7167  7240 W jxcore-log: 
,08-12 18:39:26.127  7167  7240 I jxcore-log: JXcore Cordova bridge is ready!
08-12 18:39:26.127  7167  7240 I jxcore-log: 
,08-12 18:39:26.128  7167  7240 W jxcore-log: JXcore engine is started
08-12 18:39:26.135  7167  7234 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-12 18:39:26.137  7167  7167 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-12 18:39:29.823  1380  1380 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-12 18:39:29.823  1380  1380 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-12 18:39:29.823  1380  1380 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-12 18:39:29.823  1380  1380 I [SystemUI]LGPowerUI: On Skip Timer : true
08-12 18:39:29.823  1799  1799 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-12 18:39:29.857   480   480 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-12 18:39:29.880  1799  1951 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-12 18:39:29.880  1799  1951 D LEDHandler: Battery Level Remaining: 100%
08-12 18:39:29.880  1799  1951 D LEDHandler: Battery Temp: 298, mChargingStatus=5, mChargingStop=false
,08-12 18:39:29.883  1380  1380 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
08-12 18:39:29.883  1380  1380 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-12 18:39:29.883  1380  1380 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 298
08-12 18:39:29.884  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-12 18:39:29.884  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-12 18:39:29.886  2026  3601 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-12 18:39:29.892   867  1311 D WifiController: battery changed pluggedType: 2
08-12 18:39:29.892   867   867 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-12 18:39:29.892   867   867 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-12 18:39:29.893  1380  1380 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-12 18:39:29.912  1837  1837 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-12 18:39:29.912  1837  1837 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,08-12 18:39:29.916  1380  1380 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
08-12 18:39:29.916  1380  1380 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-12 18:39:29.916  1380  1380 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 297
08-12 18:39:29.917  1799  1951 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-12 18:39:29.917  1799  1951 D LEDHandler: Battery Level Remaining: 100%
08-12 18:39:29.917  1799  1951 D LEDHandler: Battery Temp: 297, mChargingStatus=5, mChargingStop=false
08-12 18:39:29.917  2026  3601 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-12 18:39:29.920  1380  1380 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-12 18:39:29.920   867   867 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-12 18:39:29.920   867   867 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-12 18:39:29.921   867  1311 D WifiController: battery changed pluggedType: 2
08-12 18:39:30.237   294   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-12 18:39:30.950   867  1781 I ActivityManager: Process com.google.android.talk (pid 6776) has died
,08-12 18:39:34.383   867  1002 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-12 18:39:34.383   867  1002 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-12 18:39:34.383   867  1002 D sensors_hal_Time: tsOffsetIs: Apps: 327706524150; DSPS: 10829707; Offset : -2801449641
,08-12 18:39:35.242   294   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-12 18:39:40.247   294   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-12 18:39:45.252   294   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-12 18:39:49.399   867  3217 I LocationManagerService: remove 429f9ad
,08-12 18:39:49.409   867  3217 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-12 18:39:49.409   867  3217 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-12 18:39:49.410   867  3217 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-12 18:39:49.410   867  3217 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-12 18:39:49.410   867  3217 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-12 18:39:50.257   294   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-12 18:39:51.175  7167  7240 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 18:39:51.175  7167  7240 I jxcore-log: 
,08-12 18:39:51.179  7167  7240 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 18:39:51.179  7167  7240 I jxcore-log: 
08-12 18:39:51.185  2026  2066 D BluetoothAdapterService(775588902): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2bcd6bac
08-12 18:39:51.186  7167  7240 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 18:39:51.186  7167  7240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 18:39:51.186  7167  7240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 18:39:51.186  7167  7240 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 18:39:51.186  7167  7240 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 18:39:51.186  7167  7240 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 18:39:51.186  7167  7240 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 18:39:51.186  7167  7240 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 18:39:51.189  2026  2066 D BluetoothAdapterService(775588902): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2bcd6bac
,08-12 18:39:51.190  7167  7240 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 18:39:51.193  7167  7240 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 18:39:51.193  7167  7240 I jxcore-log: 
08-12 18:39:51.195  7167  7240 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 18:39:51.195  7167  7240 I jxcore-log: 
08-12 18:39:51.750  7167  7240 I jxcore-log: Unit Test app is loaded
08-12 18:39:51.750  7167  7240 I jxcore-log: 
,08-12 18:39:51.763  7167  7240 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 18:39:51.763  7167  7240 I jxcore-log: 
,08-12 18:39:51.768  7167  7240 I jxcore-log: My device name is: LGE-LG-D722
08-12 18:39:51.768  7167  7240 I jxcore-log: 
08-12 18:39:51.771  7167  7240 I jxcore-log: WARN testUtils: myNameCallback not set!
08-12 18:39:51.771  7167  7240 I jxcore-log: 
08-12 18:39:51.777  7167  7167 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 18:39:54.383   867  1002 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-12 18:39:54.383   867  1002 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-12 18:39:54.383   867  1002 D sensors_hal_Time: tsOffsetIs: Apps: 347707374508; DSPS: 11485095; Offset : -2801455442
,08-12 18:39:55.261   294   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-12 18:39:55.488  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-12 18:39:55.488  7167  7240 I jxcore-log: 
,08-12 18:39:56.472  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-12 18:39:56.472  7167  7240 I jxcore-log: 
,08-12 18:39:56.509  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-12 18:39:56.509  7167  7240 I jxcore-log: 
,08-12 18:39:58.666  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-12 18:39:58.666  7167  7240 I jxcore-log: 
,08-12 18:39:59.027  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-12 18:39:59.027  7167  7240 I jxcore-log: 
,08-12 18:39:59.035  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-12 18:39:59.035  7167  7240 I jxcore-log: 
08-12 18:39:59.043  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-12 18:39:59.043  7167  7240 I jxcore-log: 
,08-12 18:39:59.070  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-12 18:39:59.070  7167  7240 I jxcore-log: 
,08-12 18:39:59.076  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-12 18:39:59.076  7167  7240 I jxcore-log: 
08-12 18:40:00.056  1380  1380 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 18:40:00.056  1380  1380 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-12 18:40:00.060  1380  1380 I [SystemUI]Clock: called onTimeUpdated()
08-12 18:40:00.062  1380  1380 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 18:40:00.066  1380  1380 I [SystemUI]DateView: called onTimeUpdated()
08-12 18:40:00.070  1380  1380 I [SystemUI]DateView: called onTimeUpdated()
,08-12 18:40:00.072  1380  1380 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 18:40:00.134  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-12 18:40:00.134  7167  7240 I jxcore-log: 
,08-12 18:40:00.152  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-12 18:40:00.152  7167  7240 I jxcore-log: 
,08-12 18:40:00.165  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-12 18:40:00.165  7167  7240 I jxcore-log: 
,08-12 18:40:00.175  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-12 18:40:00.175  7167  7240 I jxcore-log: 
08-12 18:40:00.247  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-12 18:40:00.247  7167  7240 I jxcore-log: 
,08-12 18:40:00.273   294   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-12 18:40:00.333  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-12 18:40:00.333  7167  7240 I jxcore-log: 
,08-12 18:40:00.344  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-12 18:40:00.344  7167  7240 I jxcore-log: 
,08-12 18:40:00.592  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-12 18:40:00.592  7167  7240 I jxcore-log: 
,08-12 18:40:00.632  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-12 18:40:00.632  7167  7240 I jxcore-log: 
,08-12 18:40:00.639  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-12 18:40:00.639  7167  7240 I jxcore-log: 
,08-12 18:40:00.648  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-12 18:40:00.648  7167  7240 I jxcore-log: 
,08-12 18:40:00.675  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-12 18:40:00.675  7167  7240 I jxcore-log: 
,08-12 18:40:00.806  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-12 18:40:00.806  7167  7240 I jxcore-log: 
,08-12 18:40:00.828  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-12 18:40:00.828  7167  7240 I jxcore-log: 
,08-12 18:40:00.873  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-12 18:40:00.873  7167  7240 I jxcore-log: 
,08-12 18:40:00.894  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-12 18:40:00.894  7167  7240 I jxcore-log: 
,08-12 18:40:00.922  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-12 18:40:00.922  7167  7240 I jxcore-log: 
,08-12 18:40:00.976  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-12 18:40:00.976  7167  7240 I jxcore-log: 
,08-12 18:40:00.984  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-12 18:40:00.984  7167  7240 I jxcore-log: 
,08-12 18:40:01.300  7167  7240 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-12 18:40:01.300  7167  7240 I jxcore-log: 
,08-12 18:40:01.313  2026  2066 D BluetoothAdapterService(775588902): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2bcd6bac
,08-12 18:40:01.314  7167  7240 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,08-12 18:40:01.320  7167  7240 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-12 18:40:01.320  7167  7240 I jxcore-log: 
08-12 18:40:01.701  7167  7240 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-12 18:40:01.701  7167  7240 I jxcore-log: 
,08-12 18:40:02.112  7261  7261 D AndroidRuntime: 
08-12 18:40:02.112  7261  7261 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-12 18:40:02.119  7261  7261 D AndroidRuntime: CheckJNI is OFF
08-12 18:40:02.418  7261  7261 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 18:40:02.468   867  1031 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
,08-12 18:40:02.470   867  1031 I ActivityManager: Killing 7167:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
08-12 18:40:02.522   867  1920 I WindowState: WIN DEATH: Window{397f24e3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 18:40:02.532   867  1920 D InputDispatcher: Focus left window: Window{397f24e3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 18:40:02.532   867  1920 D InputDispatcher: Window went away: Window{397f24e3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 18:40:02.578   867  1061 W PackageSettings: Skipping PackageSetting{30dcfe42 com.example.hello/10317} due to missing metadata
,08-12 18:40:02.579   867  1031 I ActivityManager:   Force finishing activity ActivityRecord{9edf4ac u0 com.test.thalitest/.MainActivity t259}
,08-12 18:40:02.638   867  1809 W ActivityManager: Spurious death for ProcessRecord{365aad36 7167:com.test.thalitest/u0a30}, curProc for 7167: null
08-12 18:40:02.640   867  1061 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
,08-12 18:40:02.714  1380  1380 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-12 18:40:02.722  1934  1934 I art     : Explicit concurrent mark sweep GC freed 659(37KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 12MB/20MB, paused 1.497ms total 75.996ms
,08-12 18:40:02.748  1837  1837 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,08-12 18:40:02.757  1728  2409 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-12 18:40:02.760   867  1285 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-12 18:40:02.776  3816  3816 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-12 18:40:02.780  3816  3816 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-12 18:40:02.780  3816  3816 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-12 18:40:02.780  3816  3816 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-12 18:40:02.780  3816  3816 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 18:40:02.780  3816  3816 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 18:40:02.780  3816  3816 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-12 18:40:02.780  3816  3816 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-12 18:40:02.780  3816  3816 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 18:40:02.780  3816  3816 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 18:40:02.780  3816  3816 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-12 18:40:02.781  3816  3816 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-12 18:40:02.800  5799  5799 I art     : Explicit concurrent mark sweep GC freed 4394(203KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 15MB/20MB, paused 944us total 147.515ms
,08-12 18:40:02.811   867  1031 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7285 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-12 18:40:02.816  1874  1874 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
,08-12 18:40:02.840  1874  1874 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
,08-12 18:40:02.855  1380  1380 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-12 18:40:02.876  1380  1527 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,08-12 18:40:02.877  1380  1527 D KeyguardModel: createShortcutInfo...
08-12 18:40:02.883  1380  1527 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 18:40:02.883  1380  1527 D KeyguardModel: createShortcutInfo...
08-12 18:40:02.886  1380  1527 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 18:40:02.888  1380  1527 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-12 18:40:02.947  1380  1527 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
,08-12 18:40:02.947  1380  1527 D KeyguardModel: createShortcutInfo...
08-12 18:40:02.949  1380  1380 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-12 18:40:02.949  1380  1380 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-12 18:40:02.953  1874  1874 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-12 18:40:02.957  1380  1527 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 18:40:02.957  1380  1527 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 18:40:02.959  1380  1527 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 18:40:02.959  1380  1527 D KeyguardModel: createShortcutInfo...
,08-12 18:40:02.967  1874  1874 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-12 18:40:02.967  1874  1874 I Activity: Activity.onPostResume() called 
08-12 18:40:02.968  1380  1527 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 18:40:02.968  1380  1527 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 18:40:02.970  1380  1527 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 18:40:02.970  1380  1527 D KeyguardModel: createShortcutInfo...
08-12 18:40:02.973  1874  1874 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-12 18:40:02.976  1380  1380 D KeyguardModel: handleShortcutListChanged...
08-12 18:40:02.980   867   867 I art     : Explicit concurrent mark sweep GC freed 46355(2MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 23MB/35MB, paused 7.573ms total 273.149ms
08-12 18:40:02.980   867  1873 I art     : WaitForGcToComplete blocked for 13.703ms for cause Explicit
08-12 18:40:02.980  1380  1527 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 18:40:02.980  1380  1527 D KeyguardModel: createShortcutInfo...
,08-12 18:40:02.994  1380  1527 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 18:40:02.994  1380  1527 D KeyguardModel: createShortcutInfo...
,08-12 18:40:03.004  1380  1527 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 18:40:03.004  1380  1527 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 18:40:03.005  1380  1527 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 18:40:03.005  1380  1527 D KeyguardModel: createShortcutInfo...
,08-12 18:40:03.007  1380  1527 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 18:40:03.007  1380  1527 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 18:40:03.009  1380  1527 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 18:40:03.009  1380  1527 D KeyguardModel: createShortcutInfo...
08-12 18:40:03.013  1380  1527 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 18:40:03.013  1380  1527 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 18:40:03.016  1380  1527 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 18:40:03.016  1380  1527 D KeyguardModel: createShortcutInfo...
08-12 18:40:03.025  1380  1380 D KeyguardModel: handleShortcutListChanged...
,08-12 18:40:03.046   867   867 D administrator: Handling package changes for user 0
,08-12 18:40:03.161   867  1873 I art     : Explicit concurrent mark sweep GC freed 12346(1650KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 4.745ms total 176.605ms
08-12 18:40:03.161   867  1061 I art     : WaitForGcToComplete blocked for 303.264ms for cause Explicit
,08-12 18:40:03.163   867   867 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-12 18:40:03.164   867   867 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 18:40:03.166   867   867 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-12 18:40:03.179   867  1051 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
08-12 18:40:03.179   867  1051 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-12 18:40:03.180  1380  1380 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-12 18:40:03.180  1380  1380 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-12 18:40:03.180  1380  1380 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-12 18:40:03.180  1380  1380 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-12 18:40:03.181   867  1051 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-12 18:40:03.181   867  1051 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-12 18:40:03.181   867  1051 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-12 18:40:03.181   867  1051 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@222dc162,  pkg=WindowManager.LayoutParams
08-12 18:40:03.181   867  1051 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-12 18:40:03.181  1874  7304 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,08-12 18:40:03.186   867  1349 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
08-12 18:40:03.186   867  1359 D InputDispatcher: Focus entered window: Window{22e6dba7 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-12 18:40:03.191  7285  7285 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 18:40:03.191  7285  7285 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 18:40:03.192  7285  7285 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-12 18:40:03.204  1874  1874 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-12 18:40:03.204  1874  1874 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 18:40:03.205  1874  1874 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-12 18:40:03.213  1874  1874 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-12 18:40:03.213  1874  1874 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
08-12 18:40:03.214  1874  1874 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-12 18:40:03.220   867  1920 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-12 18:40:03.223   867  1920 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 7167 uid 10030
08-12 18:40:03.267  1874  1874 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-12 18:40:03.268  1621  1621 E b       : Unable to connect to the editor to retrieve text... will retry later
08-12 18:40:03.273  1874  1874 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d379d17 time:356597
08-12 18:40:03.289   867  1053 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{12170218 u0 com.lge.launcher2/.Launcher t258} time:356613
,08-12 18:40:03.326  1874  1874 I art     : Explicit concurrent mark sweep GC freed 4013(214KB) AllocSpace objects, 4(645KB) LOS objects, 39% free, 15MB/25MB, paused 2.009ms total 51.873ms
08-12 18:40:03.326  1874  1874 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-12 18:40:03.415   867  1061 I art     : Explicit concurrent mark sweep GC freed 4933(318KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 4.650ms total 249.382ms
,08-12 18:40:03.421  7285  7285 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-12 18:40:03.433   867  1029 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 18:40:03.441  7285  7285 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,08-12 18:40:03.473  1782  1782 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-12 18:40:03.473  1782  1782 D LCardEmulationManager: getDefaultRoute
,08-12 18:40:03.500  7261  7261 D AndroidRuntime: Shutting down VM
,08-12 18:40:03.515   867  1029 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-12 18:40:03.524  1874  1874 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-12 18:40:03.611  7285  7285 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-12 18:40:03.630  6822  6822 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-12 18:40:03.666   867  1347 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7311 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,08-12 18:40:03.756   867  1061 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7331 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-12 18:40:03.862   867  1873 I ActivityManager: Killing 6848:com.android.gallery3d/u0a23 (adj 15): empty #11
,08-12 18:40:03.877   867  1781 W libprocessgroup: failed to open /acct/uid_10023/pid_6848/cgroup.procs: No such file or directory
,08-12 18:40:03.959  7311  7311 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.

```
