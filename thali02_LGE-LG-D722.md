#### Test 7975101513b55b4_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-12 11:28:41.319   948   987 D sensors_hal_Time: tsOffsetIs: Apps: 310222737866; DSPS: 10257143; Offset : -2806374714
,08-12 11:28:44.843   296   357 I ThermalEngine: Sensor:pa_therm0:30000 mC
08-12 11:28:45.211  6847  6847 D AndroidRuntime: 
08-12 11:28:45.211  6847  6847 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-12 11:28:45.218  6847  6847 D AndroidRuntime: CheckJNI is OFF
08-12 11:28:45.599  6847  6847 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 11:28:45.616   948  1293 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 11:28:45.677   948  1293 D ActivityManager: setTaskToReturnTo : TaskRecord{18569cf4 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 11:28:45.677   948  1293 D ActivityManager: setTaskToReturnTo : TaskRecord{18569cf4 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 11:28:45.681   948  1293 D WindowStateEx: AppWindowTokenEx init.. 
08-12 11:28:45.717   948  1293 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6867 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-12 11:28:45.720   948  1293 D InputDispatcher: Focus left window: Window{2b4a5cc6 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-12 11:28:45.721  6847  6847 D AndroidRuntime: Shutting down VM
08-12 11:28:45.725  1877  1877 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-12 11:28:45.766  1751  1751 D DSDPConnection: Display #0 changed.
08-12 11:28:45.768   948   948 V ActivityManager: Display changed displayId=0
08-12 11:28:45.903  6867  6867 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-12 11:28:45.998  6867  6867 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-12 11:28:46.080  6867  6867 I LibraryLoader: Time to load native libraries: 20 ms (timestamps 4964-4984)
08-12 11:28:46.080  6867  6867 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 11:28:46.109  6867  6867 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {35fbe9bd}
08-12 11:28:46.110  6867  6867 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 11:28:46.117  6867  6867 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 11:28:46.135  6867  6867 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-12 11:28:46.138  6867  6867 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 11:28:46.142  6867  6867 E SysUtils: ApplicationContext is null in ApplicationStatus
08-12 11:28:46.225  6867  6867 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-12 11:28:46.232  6867  6867 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 11:28:46.232  6867  6867 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 11:28:46.233  6867  6867 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-12 11:28:46.233  6867  6867 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-12 11:28:46.233  6867  6867 I Adreno-EGL: Build Date: 03/02/15 Mon
08-12 11:28:46.233  6867  6867 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-12 11:28:46.233  6867  6867 I Adreno-EGL: Remote Branch: 
08-12 11:28:46.233  6867  6867 I Adreno-EGL: Local Patches: 
08-12 11:28:46.233  6867  6867 I Adreno-EGL: Reconstruct Branch: 
08-12 11:28:46.293   948  1024 W ActivityManager: Activity pause timeout for ActivityRecord{196b5c1d u0 com.test.thalitest/.MainActivity t259}
08-12 11:28:46.312   281   281 V AudioPolicyService: registerClient() client 0xb4027220, uid 10030
08-12 11:28:46.323   948  1056 D BluetoothManagerService: Message: 20
08-12 11:28:46.323   948  1056 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@344a8f78:true
08-12 11:28:46.337  2046  3517 D BluetoothAdapterService(644130563): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@335ef1f1
08-12 11:28:46.458  6867  6867 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 11:28:46.472  6867  6867 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-12 11:28:46.480  6867  6867 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-12 11:28:46.487  6867  6867 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-12 11:28:46.487  6867  6867 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-12 11:28:46.505  6867  6867 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-12 11:28:46.513  6867  6867 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 11:28:46.513  6867  6867 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 11:28:46.571  6867  6867 I Activity: Activity.onPostResume() called 
08-12 11:28:46.577  6867  6918 D OpenGLRenderer: Render dirty regions requested: true
08-12 11:28:46.577  6867  6918 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 11:28:46.585  6867  6918 D OpenGLRenderer: Enabling debug mode 0
08-12 11:28:46.602  6867  6867 D Atlas   : Validating map...
08-12 11:28:46.607   948  1845 D SplitWindow: check instance of lgWin Window{133cc6a8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 11:28:46.635  6867  6904 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-12 11:28:46.660   948  1053 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-12 11:28:46.662   948  1053 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-12 11:28:46.663  1372  1372 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-12 11:28:46.664  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-12 11:28:46.664  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-12 11:28:46.664  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-12 11:28:46.666   948  1053 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-12 11:28:46.666   948  1053 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-12 11:28:46.666   948  1053 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-12 11:28:46.666   948  1053 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@fbfa6aa,  pkg=WindowManager.LayoutParams
08-12 11:28:46.666   948  1053 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-12 11:28:46.682   948  1637 D InputDispatcher: Focus entered window: Window{133cc6a8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 11:28:46.708   948  1809 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-12 11:28:46.713   948  1057 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +919ms (total +1s29ms)
08-12 11:28:46.714   948  1057 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{196b5c1d u0 com.test.thalitest/.MainActivity t259} time:315617
08-12 11:28:46.731  6867  6867 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-12 11:28:46.731  6867  6867 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@30dc6f4f time:315635
,08-12 11:28:46.780  6867  6867 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-12 11:28:46.784  1624  1624 E b       : Unable to connect to the editor to retrieve text... will retry later
08-12 11:28:46.808  6867  6867 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-12 11:28:46.860  6867  6867 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6867
,08-12 11:28:46.997  6867  6867 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 11:28:47.320  6867  6920 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426119424
,08-12 11:28:47.340  6867  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 11:28:47.340  6867  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 11:28:47.340  6867  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 11:28:47.340  6867  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 11:28:47.340  6867  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-12 11:28:47.340  6867  6920 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d79e2e3 added. We now have 1 listener(s)
08-12 11:28:47.348   948  3592 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 11:28:47.353  6867  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
08-12 11:28:47.355  6867  6920 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
,08-12 11:28:47.357  6867  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 11:28:47.357  6867  6920 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 11:28:47.364  6867  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 11:28:47.364  6867  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 11:28:47.364  6867  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 11:28:47.364  6867  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-12 11:28:47.364  6867  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 11:28:47.364  6867  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 11:28:47.364  6867  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 11:28:47.364  6867  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 11:28:47.364  6867  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 11:28:47.364  6867  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 11:28:47.364  6867  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 11:28:47.364  6867  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 11:28:47.364  6867  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 11:28:47.364  6867  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 11:28:47.365  6867  6920 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@29a7465e added. We now have 1 listener(s)
08-12 11:28:47.365  6867  6920 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 11:28:47.384  6867  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 11:28:47.384  6867  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-12 11:28:47.387  6867  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 11:28:47.388  6867  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 11:28:47.388  6867  6920 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-12 11:28:47.393  6867  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 11:28:47.394   948  1845 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 11:28:47.394  6867  6920 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-12 11:28:47.407  2046  2074 D BluetoothAdapterService(644130563): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@335ef1f1
,08-12 11:28:47.413  6867  6920 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-12 11:28:47.414  6867  6920 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 11:28:47.414  6867  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 11:28:47.414  6867  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 11:28:47.414  6867  6920 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 11:28:47.414  6867  6920 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 11:28:47.414  6867  6920 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 11:28:47.414  6867  6920 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 11:28:47.414  6867  6920 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 11:28:47.415  6867  6920 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 11:28:47.415  6867  6920 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 11:28:47.417  6867  6867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 11:28:47.418  6867  6867 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 11:28:47.421  6867  6920 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 11:28:47.452  6867  6867 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 11:28:47.578  6867  6881 I art     : CheckpointMarkThreadRoots callback created = 0xb061c830
,08-12 11:28:47.607  6867  6881 I art     : CheckpointMarkThreadRoots callback created = 0xb061c800
,08-12 11:28:48.556  6867  6926 W jxcore-log: Initializing JXcore engine
,08-12 11:28:48.558  6867  6926 W jxcore-log: JXcore engine is ready
08-12 11:28:48.692  6926  6926 W Thread-810: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8372]" dev="sockfs" ino=8372 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-12 11:28:48.692  6926  6926 W Thread-810: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-12 11:28:48.692  6926  6926 W Thread-810: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6004]" dev="sockfs" ino=6004 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-12 11:28:48.692  6926  6926 W Thread-810: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-12 11:28:48.692  6926  6926 W Thread-810: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-12 11:28:48.692  6926  6926 W Thread-810: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[30436]" dev="sockfs" ino=30436 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-12 11:28:48.724  6867  6926 W jxcore-log: Starting JXcore engine
,08-12 11:28:48.877  6867  6926 W jxcore-log: Platform android
08-12 11:28:48.877  6867  6926 W jxcore-log: 
08-12 11:28:48.877  6867  6926 W jxcore-log: Process ARCH arm
08-12 11:28:48.877  6867  6926 W jxcore-log: 
,08-12 11:28:49.192  6867  6926 I jxcore-log: JXcore Cordova bridge is ready!
08-12 11:28:49.192  6867  6926 I jxcore-log: 
08-12 11:28:49.193  6867  6926 W jxcore-log: JXcore engine is started
,08-12 11:28:49.201  6867  6920 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-12 11:28:49.203  6867  6867 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-12 11:28:49.847   296   357 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-12 11:28:53.746   948  5563 I ActivityManager: Process com.google.android.talk (pid 6493) has died
,08-12 11:28:54.852   296   357 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-12 11:28:59.857   296   357 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-12 11:29:00.040  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 11:29:00.040  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 11:29:00.040  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,08-12 11:29:00.042  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 11:29:00.042  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
08-12 11:29:00.043  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
08-12 11:29:00.044  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 11:29:01.319   948   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-12 11:29:01.319   948   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-12 11:29:01.319   948   987 D sensors_hal_Time: tsOffsetIs: Apps: 330223529982; DSPS: 10912532; Offset : -2806467763
,08-12 11:29:04.862   296   357 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-12 11:29:09.867   296   357 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-12 11:29:14.201   948  3211 I LocationManagerService: remove 3d703056
,08-12 11:29:14.213   948  3211 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
,08-12 11:29:14.215   948  3211 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-12 11:29:14.217   948  3211 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-12 11:29:14.218   948  3211 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-12 11:29:14.218   948  3211 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-12 11:29:14.256  6867  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 11:29:14.256  6867  6926 I jxcore-log: 
,08-12 11:29:14.260  6867  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 11:29:14.260  6867  6926 I jxcore-log: 
08-12 11:29:14.266  2046  2074 D BluetoothAdapterService(644130563): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@335ef1f1
08-12 11:29:14.267  6867  6926 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 11:29:14.267  6867  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 11:29:14.267  6867  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 11:29:14.267  6867  6926 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 11:29:14.267  6867  6926 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 11:29:14.267  6867  6926 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 11:29:14.267  6867  6926 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 11:29:14.267  6867  6926 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 11:29:14.270  2046  2074 D BluetoothAdapterService(644130563): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@335ef1f1
,08-12 11:29:14.271  6867  6926 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 11:29:14.276  6867  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 11:29:14.276  6867  6926 I jxcore-log: 
08-12 11:29:14.279  6867  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 11:29:14.279  6867  6926 I jxcore-log: 
,08-12 11:29:14.828  6867  6926 I jxcore-log: Unit Test app is loaded
08-12 11:29:14.828  6867  6926 I jxcore-log: 
,08-12 11:29:14.842  6867  6926 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 11:29:14.842  6867  6926 I jxcore-log: 
,08-12 11:29:14.846  6867  6926 I jxcore-log: My device name is: LGE-LG-D722
08-12 11:29:14.846  6867  6926 I jxcore-log: 
08-12 11:29:14.849  6867  6926 I jxcore-log: WARN testUtils: myNameCallback not set!
08-12 11:29:14.849  6867  6926 I jxcore-log: 
08-12 11:29:14.854  6867  6867 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-12 11:29:14.872   296   357 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-12 11:29:18.542  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-12 11:29:18.542  6867  6926 I jxcore-log: 
,08-12 11:29:19.529  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-12 11:29:19.529  6867  6926 I jxcore-log: 
,08-12 11:29:19.566  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-12 11:29:19.566  6867  6926 I jxcore-log: 
,08-12 11:29:19.877   296   357 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-12 11:29:21.320   948   987 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-12 11:29:21.320   948   987 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-12 11:29:21.320   948   987 D sensors_hal_Time: tsOffsetIs: Apps: 350224400078; DSPS: 11567920; Offset : -2806452289
,08-12 11:29:21.719  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-12 11:29:21.719  6867  6926 I jxcore-log: 
,08-12 11:29:22.071  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-12 11:29:22.071  6867  6926 I jxcore-log: 
,08-12 11:29:22.079  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-12 11:29:22.079  6867  6926 I jxcore-log: 
08-12 11:29:22.087  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-12 11:29:22.087  6867  6926 I jxcore-log: 
,08-12 11:29:22.112  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-12 11:29:22.112  6867  6926 I jxcore-log: 
,08-12 11:29:22.119  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-12 11:29:22.119  6867  6926 I jxcore-log: 
,08-12 11:29:23.167  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-12 11:29:23.167  6867  6926 I jxcore-log: 
,08-12 11:29:23.186  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-12 11:29:23.186  6867  6926 I jxcore-log: 
,08-12 11:29:23.199  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-12 11:29:23.199  6867  6926 I jxcore-log: 
,08-12 11:29:23.208  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-12 11:29:23.208  6867  6926 I jxcore-log: 
08-12 11:29:23.282  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-12 11:29:23.282  6867  6926 I jxcore-log: 
,08-12 11:29:23.367  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-12 11:29:23.367  6867  6926 I jxcore-log: 
,08-12 11:29:23.378  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-12 11:29:23.378  6867  6926 I jxcore-log: 
08-12 11:29:23.629  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-12 11:29:23.629  6867  6926 I jxcore-log: 
,08-12 11:29:23.670  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-12 11:29:23.670  6867  6926 I jxcore-log: 
,08-12 11:29:23.677  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-12 11:29:23.677  6867  6926 I jxcore-log: 
,08-12 11:29:23.685  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-12 11:29:23.685  6867  6926 I jxcore-log: 
,08-12 11:29:23.713  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-12 11:29:23.713  6867  6926 I jxcore-log: 
,08-12 11:29:23.844  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-12 11:29:23.844  6867  6926 I jxcore-log: 
,08-12 11:29:23.866  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-12 11:29:23.866  6867  6926 I jxcore-log: 
,08-12 11:29:23.911  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-12 11:29:23.911  6867  6926 I jxcore-log: 
,08-12 11:29:23.933  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-12 11:29:23.933  6867  6926 I jxcore-log: 
,08-12 11:29:23.960  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-12 11:29:23.960  6867  6926 I jxcore-log: 
,08-12 11:29:24.015  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-12 11:29:24.015  6867  6926 I jxcore-log: 
,08-12 11:29:24.023  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-12 11:29:24.023  6867  6926 I jxcore-log: 
08-12 11:29:24.339  6867  6926 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-12 11:29:24.339  6867  6926 I jxcore-log: 
,08-12 11:29:24.351  2046  2074 D BluetoothAdapterService(644130563): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@335ef1f1
,08-12 11:29:24.352  6867  6926 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,08-12 11:29:24.360  6867  6926 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-12 11:29:24.360  6867  6926 I jxcore-log: 
,08-12 11:29:24.714  6867  6926 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-12 11:29:24.714  6867  6926 I jxcore-log: 
,08-12 11:29:24.881   296   357 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-12 11:29:25.067  6948  6948 D AndroidRuntime: 
08-12 11:29:25.067  6948  6948 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-12 11:29:25.074  6948  6948 D AndroidRuntime: CheckJNI is OFF
08-12 11:29:25.338  6948  6948 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 11:29:25.392   948  1024 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
08-12 11:29:25.393   948  1024 I ActivityManager: Killing 6867:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
,08-12 11:29:25.457   948  1863 I WindowState: WIN DEATH: Window{133cc6a8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 11:29:25.474   948  1863 D InputDispatcher: Focus left window: Window{133cc6a8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 11:29:25.474   948  1863 D InputDispatcher: Window went away: Window{133cc6a8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 11:29:25.517   948  1024 I ActivityManager:   Force finishing activity ActivityRecord{196b5c1d u0 com.test.thalitest/.MainActivity t259}
,08-12 11:29:25.523   948  1068 W PackageSettings: Skipping PackageSetting{1156a7af com.example.hello/10317} due to missing metadata
,08-12 11:29:25.571   948  1845 W ActivityManager: Spurious death for ProcessRecord{745d99f 6867:com.test.thalitest/u0a30}, curProc for 6867: null
,08-12 11:29:25.573   948  1068 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
08-12 11:29:25.576   948  1068 I ActivityManager:   Force finishing activity ActivityRecord{196b5c1d u0 com.test.thalitest/.MainActivity t259 f}
08-12 11:29:25.576   948  1068 W ActivityManager: Duplicate finish request for ActivityRecord{196b5c1d u0 com.test.thalitest/.MainActivity t259 f}
,08-12 11:29:25.699  1948  1948 I art     : Explicit concurrent mark sweep GC freed 737(41KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/20MB, paused 1.577ms total 119.203ms
,08-12 11:29:25.704  1733  2389 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-12 11:29:25.708  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-12 11:29:25.710  3686  3686 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-12 11:29:25.713  3686  3686 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-12 11:29:25.713  3686  3686 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-12 11:29:25.713  3686  3686 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-12 11:29:25.713  3686  3686 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 11:29:25.713  3686  3686 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 11:29:25.713  3686  3686 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-12 11:29:25.713  3686  3686 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-12 11:29:25.714  3686  3686 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 11:29:25.714  3686  3686 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 11:29:25.714  3686  3686 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-12 11:29:25.714  3686  3686 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,08-12 11:29:25.726  1839  1839 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,08-12 11:29:25.729   948  1289 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-12 11:29:25.772   948  1024 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6973 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-12 11:29:25.780  1877  1877 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
08-12 11:29:25.819  3441  3441 I art     : Explicit concurrent mark sweep GC freed 2706(135KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 16MB/21MB, paused 1.280ms total 171.209ms
,08-12 11:29:25.826  1877  1877 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
08-12 11:29:25.852  1372  1372 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-12 11:29:25.892  1877  1877 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-12 11:29:25.895  1877  1877 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-12 11:29:25.895  1877  1877 I Activity: Activity.onPostResume() called 
,08-12 11:29:25.902  1877  1877 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-12 11:29:25.911   948   948 I art     : Explicit concurrent mark sweep GC freed 41247(2MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 24MB/36MB, paused 21.227ms total 320.736ms
08-12 11:29:25.912   948  1068 I art     : WaitForGcToComplete blocked for 132.061ms for cause Explicit
,08-12 11:29:25.921  1877  6991 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
08-12 11:29:25.935   948  1053 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
08-12 11:29:25.935   948  1053 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
,08-12 11:29:25.938   948  1053 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-12 11:29:25.938   948  1053 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-12 11:29:25.938   948  1053 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-12 11:29:25.938   948  1053 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@fbfa6aa,  pkg=WindowManager.LayoutParams
08-12 11:29:25.938   948  1053 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-12 11:29:25.939   948  3592 D InputDispatcher: Focus entered window: Window{2b4a5cc6 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-12 11:29:25.939  6973  6973 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 11:29:25.939  1372  1372 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-12 11:29:25.940  6973  6973 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 11:29:25.941  6973  6973 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-12 11:29:25.942  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-12 11:29:25.942  1372  1372 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-12 11:29:25.942  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-12 11:29:25.942  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-12 11:29:25.942  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-12 11:29:25.956  1877  1877 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 11:29:25.957  1877  1877 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 11:29:25.957  1877  1877 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,08-12 11:29:25.969  1877  1877 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-12 11:29:25.970  1877  1877 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
08-12 11:29:25.970  1372  1512 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 11:29:25.970  1372  1512 D KeyguardModel: createShortcutInfo...
08-12 11:29:25.971  1877  1877 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-12 11:29:25.976  1372  1512 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
,08-12 11:29:25.976  1372  1512 D KeyguardModel: createShortcutInfo...
08-12 11:29:25.978  1372  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 11:29:25.978  1372  1512 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 11:29:25.980  1372  1512 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 11:29:25.981  1372  1512 D KeyguardModel: createShortcutInfo...
08-12 11:29:25.990  1372  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 11:29:25.990  1372  1512 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 11:29:25.992   948  1876 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-12 11:29:25.994   948  1876 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6867 uid 10030
08-12 11:29:25.995  1372  1512 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 11:29:25.995  1372  1512 D KeyguardModel: createShortcutInfo...
,08-12 11:29:25.997  1372  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 11:29:25.997  1372  1512 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 11:29:26.000  1372  1512 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 11:29:26.000  1372  1512 D KeyguardModel: createShortcutInfo...
08-12 11:29:26.007   948   948 D administrator: Handling package changes for user 0
08-12 11:29:26.012  1372  1372 D KeyguardModel: handleShortcutListChanged...
,08-12 11:29:26.021  1372  1512 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 11:29:26.021  1372  1512 D KeyguardModel: createShortcutInfo...
08-12 11:29:26.023  1372  1512 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 11:29:26.023  1372  1512 D KeyguardModel: createShortcutInfo...
08-12 11:29:26.025  1372  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 11:29:26.025  1372  1512 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-12 11:29:26.029  1372  1512 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 11:29:26.029  1372  1512 D KeyguardModel: createShortcutInfo...
08-12 11:29:26.036  1372  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 11:29:26.036  1372  1512 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 11:29:26.038  1372  1512 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 11:29:26.039  1372  1512 D KeyguardModel: createShortcutInfo...
08-12 11:29:26.041  1372  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 11:29:26.042  1372  1512 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 11:29:26.043  1372  1512 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 11:29:26.043  1372  1512 D KeyguardModel: createShortcutInfo...
,08-12 11:29:26.052  1372  1372 D KeyguardModel: handleShortcutListChanged...
08-12 11:29:26.060  1877  1877 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
08-12 11:29:26.061  1624  1624 E b       : Unable to connect to the editor to retrieve text... will retry later
08-12 11:29:26.064  1877  1877 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1facaeb3 time:354968
08-12 11:29:26.081   948  1057 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{ee259ad u0 com.lge.launcher2/.Launcher t258} time:354985
,08-12 11:29:26.120  1877  1877 I art     : Explicit concurrent mark sweep GC freed 4374(262KB) AllocSpace objects, 5(681KB) LOS objects, 40% free, 15MB/25MB, paused 2.077ms total 55.515ms
08-12 11:29:26.120  1877  1877 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-12 11:29:26.227  6973  6973 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-12 11:29:26.230   948   948 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-12 11:29:26.230   948   948 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 11:29:26.232   948   948 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-12 11:29:26.238   948  1350 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
08-12 11:29:26.251  6973  6973 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,08-12 11:29:26.294   948  1068 I art     : Explicit concurrent mark sweep GC freed 15561(1789KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.763ms total 379.430ms
,08-12 11:29:26.327  1786  1786 D LCardEmulationManager: getHceAppCount hostAppNum : 0
,08-12 11:29:26.327  1786  1786 D LCardEmulationManager: getDefaultRoute
,08-12 11:29:26.350   948  1022 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-12 11:29:26.371  6948  6948 D AndroidRuntime: Shutting down VM
,08-12 11:29:26.470   948  1022 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-12 11:29:26.472  6973  6973 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-12 11:29:26.476  1877  1877 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-12 11:29:26.492  6537  6537 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-12 11:29:26.536   948  3592 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6997 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,08-12 11:29:26.646   948  1068 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7017 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-12 11:29:26.719   948  2701 I ActivityManager: Killing 6559:com.android.gallery3d/u0a23 (adj 15): empty #11
,08-12 11:29:26.751   948  5563 W libprocessgroup: failed to open /acct/uid_10023/pid_6559/cgroup.procs: No such file or directory
,08-12 11:29:26.811  6997  6997 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.

```
