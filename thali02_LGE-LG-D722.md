#### Test 7975101549b9187_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-12 13:47:41.694   816  1008 D sensors_hal_Time: tsOffsetIs: Apps: 315047162674; DSPS: 10422063; Offset : -3019118603
,08-12 13:47:44.072  6882  6882 D AndroidRuntime: 
08-12 13:47:44.072  6882  6882 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-12 13:47:44.079  6882  6882 D AndroidRuntime: CheckJNI is OFF
08-12 13:47:44.475  6882  6882 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 13:47:44.492   816  1361 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 13:47:44.537   816  1361 D ActivityManager: setTaskToReturnTo : TaskRecord{3b049f6f #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 13:47:44.537   816  1361 D ActivityManager: setTaskToReturnTo : TaskRecord{3b049f6f #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 13:47:44.541   816  1361 D WindowStateEx: AppWindowTokenEx init.. 
08-12 13:47:44.585   816  1361 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6900 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-12 13:47:44.586   816  1361 D InputDispatcher: Focus left window: Window{7ff966a u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-12 13:47:44.587  6882  6882 D AndroidRuntime: Shutting down VM
08-12 13:47:44.595  1949  1949 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-12 13:47:44.622   816   816 V ActivityManager: Display changed displayId=0
08-12 13:47:44.623  1790  1790 D DSDPConnection: Display #0 changed.
08-12 13:47:44.761  6900  6900 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-12 13:47:44.873  6900  6900 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-12 13:47:44.919  6900  6900 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8269-8271)
08-12 13:47:44.919  6900  6900 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 13:47:44.962  6900  6900 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2673a00c}
08-12 13:47:44.964  6900  6900 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 13:47:44.966  6900  6900 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 13:47:44.979  6900  6900 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-12 13:47:44.980  6900  6900 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 13:47:44.981  6900  6900 E SysUtils: ApplicationContext is null in ApplicationStatus
08-12 13:47:45.007  6900  6900 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-12 13:47:45.012  6900  6900 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 13:47:45.012  6900  6900 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 13:47:45.013  6900  6900 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-12 13:47:45.013  6900  6900 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-12 13:47:45.013  6900  6900 I Adreno-EGL: Build Date: 03/02/15 Mon
08-12 13:47:45.013  6900  6900 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-12 13:47:45.013  6900  6900 I Adreno-EGL: Remote Branch: 
08-12 13:47:45.013  6900  6900 I Adreno-EGL: Local Patches: 
08-12 13:47:45.013  6900  6900 I Adreno-EGL: Reconstruct Branch: 
08-12 13:47:45.089   284  1353 V AudioPolicyService: registerClient() client 0xb4027300, uid 10030
08-12 13:47:45.105   816   989 D BluetoothManagerService: Message: 20
08-12 13:47:45.107   816   989 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e911903:true
08-12 13:47:45.110  2080  2097 D BluetoothAdapterService(120058730): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3634a710
08-12 13:47:45.151   816   871 W ActivityManager: Activity pause timeout for ActivityRecord{865e47c u0 com.test.thalitest/.MainActivity t259}
08-12 13:47:45.286  6900  6900 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 13:47:45.301  6900  6900 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-12 13:47:45.308  6900  6900 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-12 13:47:45.315  6900  6900 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-12 13:47:45.315  6900  6900 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-12 13:47:45.333  6900  6900 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-12 13:47:45.342  6900  6900 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 13:47:45.342  6900  6900 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 13:47:45.400  6900  6900 I Activity: Activity.onPostResume() called 
08-12 13:47:45.406  6900  6953 D OpenGLRenderer: Render dirty regions requested: true
08-12 13:47:45.406  6900  6953 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 13:47:45.411  6900  6953 D OpenGLRenderer: Enabling debug mode 0
08-12 13:47:45.417   296   357 I ThermalEngine: Sensor:pa_therm0:29000 mC
08-12 13:47:45.426  6900  6900 D Atlas   : Validating map...
08-12 13:47:45.431   816  1037 D SplitWindow: check instance of lgWin Window{38fa48f3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 13:47:45.453  6900  6940 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-12 13:47:45.479   816   988 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-12 13:47:45.481   816   988 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-12 13:47:45.481  1366  1366 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-12 13:47:45.482  1366  1366 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-12 13:47:45.482  1366  1366 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-12 13:47:45.482  1366  1366 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-12 13:47:45.484   816   988 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-12 13:47:45.484   816   988 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-12 13:47:45.484   816   988 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-12 13:47:45.484   816   988 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3d316658,  pkg=WindowManager.LayoutParams
08-12 13:47:45.484   816   988 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-12 13:47:45.497   816  1939 D InputDispatcher: Focus entered window: Window{38fa48f3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 13:47:45.526   816   991 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +876ms (total +982ms)
08-12 13:47:45.528   816  1886 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-12 13:47:45.530   816   991 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{865e47c u0 com.test.thalitest/.MainActivity t259} time:318879
08-12 13:47:45.546  6900  6900 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-12 13:47:45.546  6900  6900 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2e1fbee6 time:318899
,08-12 13:47:45.609  6900  6900 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-12 13:47:45.614  1634  1634 E b       : Unable to connect to the editor to retrieve text... will retry later
08-12 13:47:45.636  6900  6900 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-12 13:47:45.690  6900  6900 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6900
,08-12 13:47:45.838  6900  6900 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 13:47:46.210  6900  6955 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1635606784
,08-12 13:47:46.229  6900  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 13:47:46.229  6900  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 13:47:46.229  6900  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 13:47:46.229  6900  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 13:47:46.229  6900  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-12 13:47:46.230  6900  6955 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@295d6eca added. We now have 1 listener(s)
,08-12 13:47:46.240   816  1361 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 13:47:46.244  6900  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,08-12 13:47:46.247  6900  6955 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-12 13:47:46.248  6900  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 13:47:46.249  6900  6955 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 13:47:46.261  6900  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 13:47:46.261  6900  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 13:47:46.261  6900  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 13:47:46.261  6900  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-12 13:47:46.261  6900  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 13:47:46.261  6900  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 13:47:46.261  6900  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 13:47:46.261  6900  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 13:47:46.261  6900  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 13:47:46.261  6900  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 13:47:46.261  6900  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 13:47:46.261  6900  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 13:47:46.261  6900  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 13:47:46.261  6900  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 13:47:46.261  6900  6955 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1c11d4b1 added. We now have 1 listener(s)
08-12 13:47:46.262  6900  6955 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 13:47:46.274  6900  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 13:47:46.274  6900  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-12 13:47:46.278  6900  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 13:47:46.278  6900  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 13:47:46.279  6900  6955 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-12 13:47:46.286  6900  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 13:47:46.287   816  1977 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 13:47:46.291  6900  6955 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-12 13:47:46.302  2080  2096 D BluetoothAdapterService(120058730): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3634a710
,08-12 13:47:46.307  6900  6955 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-12 13:47:46.307  6900  6955 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 13:47:46.307  6900  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 13:47:46.307  6900  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 13:47:46.307  6900  6955 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 13:47:46.307  6900  6955 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 13:47:46.307  6900  6955 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 13:47:46.307  6900  6955 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 13:47:46.307  6900  6955 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 13:47:46.307  6900  6955 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 13:47:46.308  6900  6955 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 13:47:46.310  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 13:47:46.311  6900  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 13:47:46.313  6900  6955 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-12 13:47:46.344  6900  6900 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 13:47:46.468  6900  6914 I art     : CheckpointMarkThreadRoots callback created = 0xb07b10e0
,08-12 13:47:46.512  6900  6914 I art     : CheckpointMarkThreadRoots callback created = 0xb07b10b0
,08-12 13:47:47.368  6900  6961 W jxcore-log: Initializing JXcore engine
,08-12 13:47:47.370  6900  6961 W jxcore-log: JXcore engine is ready
08-12 13:47:47.490  6961  6961 W Thread-819: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6269]" dev="sockfs" ino=6269 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-12 13:47:47.490  6961  6961 W Thread-819: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-12 13:47:47.490  6961  6961 W Thread-819: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5895]" dev="sockfs" ino=5895 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-12 13:47:47.490  6961  6961 W Thread-819: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
,08-12 13:47:47.490  6961  6961 W Thread-819: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-12 13:47:47.490  6961  6961 W Thread-819: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[30704]" dev="sockfs" ino=30704 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-12 13:47:47.524  6900  6961 W jxcore-log: Starting JXcore engine
,08-12 13:47:47.690  6900  6961 W jxcore-log: Platform android
08-12 13:47:47.690  6900  6961 W jxcore-log: 
08-12 13:47:47.691  6900  6961 W jxcore-log: Process ARCH arm
08-12 13:47:47.691  6900  6961 W jxcore-log: 
,08-12 13:47:48.051  6900  6961 I jxcore-log: JXcore Cordova bridge is ready!
08-12 13:47:48.051  6900  6961 I jxcore-log: 
08-12 13:47:48.052  6900  6961 W jxcore-log: JXcore engine is started
,08-12 13:47:48.059  6900  6955 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-12 13:47:48.061  6900  6900 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-12 13:47:50.421   296   357 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-12 13:47:55.426   296   357 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-12 13:48:00.047  1366  1366 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 13:48:00.047  1366  1366 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 13:48:00.048  1366  1366 I [SystemUI]Clock: called onTimeUpdated()
,08-12 13:48:00.049  1366  1366 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 13:48:00.049  1366  1366 I [SystemUI]DateView: called onTimeUpdated()
08-12 13:48:00.050  1366  1366 I [SystemUI]DateView: called onTimeUpdated()
08-12 13:48:00.051  1366  1366 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 13:48:00.431   296   357 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-12 13:48:01.697   816  1008 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-12 13:48:01.697   816  1008 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-12 13:48:01.697   816  1008 D sensors_hal_Time: tsOffsetIs: Apps: 335049524773; DSPS: 11077501; Offset : -3019137162
,08-12 13:48:05.436   296   357 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-12 13:48:08.997   816  3194 I LocationManagerService: remove 1f6d31c1
,08-12 13:48:09.008   816  3194 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-12 13:48:09.008   816  3194 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-12 13:48:09.008   816  3194 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-12 13:48:09.012   816  3194 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,08-12 13:48:09.014   816  3194 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
08-12 13:48:10.441   296   357 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-12 13:48:13.365  6900  6961 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 13:48:13.365  6900  6961 I jxcore-log: 
,08-12 13:48:13.369  6900  6961 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 13:48:13.369  6900  6961 I jxcore-log: 
08-12 13:48:13.376  2080  2096 D BluetoothAdapterService(120058730): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3634a710
08-12 13:48:13.377  6900  6961 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 13:48:13.377  6900  6961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 13:48:13.377  6900  6961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 13:48:13.377  6900  6961 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 13:48:13.377  6900  6961 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 13:48:13.377  6900  6961 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 13:48:13.377  6900  6961 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 13:48:13.377  6900  6961 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-12 13:48:13.381  2080  2096 D BluetoothAdapterService(120058730): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3634a710
08-12 13:48:13.383  6900  6961 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 13:48:13.388  6900  6961 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 13:48:13.388  6900  6961 I jxcore-log: 
,08-12 13:48:13.390  6900  6961 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 13:48:13.390  6900  6961 I jxcore-log: 
08-12 13:48:13.935  6900  6961 I jxcore-log: Unit Test app is loaded
08-12 13:48:13.935  6900  6961 I jxcore-log: 
,08-12 13:48:13.952  6900  6961 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 13:48:13.952  6900  6961 I jxcore-log: 
08-12 13:48:13.956  6900  6961 I jxcore-log: My device name is: LGE-LG-D722
08-12 13:48:13.956  6900  6961 I jxcore-log: 
,08-12 13:48:13.960  6900  6961 I jxcore-log: WARN testUtils: myNameCallback not set!
08-12 13:48:13.960  6900  6961 I jxcore-log: 
08-12 13:48:13.962  6900  6900 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-12 13:48:15.446   296   357 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-12 13:48:17.739  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-12 13:48:17.739  6900  6961 I jxcore-log: 
,08-12 13:48:18.715  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-12 13:48:18.715  6900  6961 I jxcore-log: 
,08-12 13:48:18.751  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-12 13:48:18.751  6900  6961 I jxcore-log: 
,08-12 13:48:20.451   296   357 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-12 13:48:20.903  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-12 13:48:20.903  6900  6961 I jxcore-log: 
,08-12 13:48:21.256  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-12 13:48:21.256  6900  6961 I jxcore-log: 
,08-12 13:48:21.264  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-12 13:48:21.264  6900  6961 I jxcore-log: 
08-12 13:48:21.272  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-12 13:48:21.272  6900  6961 I jxcore-log: 
,08-12 13:48:21.297  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-12 13:48:21.297  6900  6961 I jxcore-log: 
,08-12 13:48:21.303  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-12 13:48:21.303  6900  6961 I jxcore-log: 
08-12 13:48:21.697   816  1008 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-12 13:48:21.697   816  1008 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-12 13:48:21.698   816  1008 D sensors_hal_Time: tsOffsetIs: Apps: 355050412579; DSPS: 11732889; Offset : -3019104031
,08-12 13:48:22.355  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-12 13:48:22.355  6900  6961 I jxcore-log: 
,08-12 13:48:22.373  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-12 13:48:22.373  6900  6961 I jxcore-log: 
,08-12 13:48:22.386  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-12 13:48:22.386  6900  6961 I jxcore-log: 
,08-12 13:48:22.396  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-12 13:48:22.396  6900  6961 I jxcore-log: 
,08-12 13:48:22.469  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-12 13:48:22.469  6900  6961 I jxcore-log: 
,08-12 13:48:22.555  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-12 13:48:22.555  6900  6961 I jxcore-log: 
,08-12 13:48:22.567  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-12 13:48:22.567  6900  6961 I jxcore-log: 
,08-12 13:48:22.819  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-12 13:48:22.819  6900  6961 I jxcore-log: 
,08-12 13:48:22.859  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-12 13:48:22.859  6900  6961 I jxcore-log: 
,08-12 13:48:22.867  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-12 13:48:22.867  6900  6961 I jxcore-log: 
,08-12 13:48:22.875  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-12 13:48:22.875  6900  6961 I jxcore-log: 
,08-12 13:48:22.903  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-12 13:48:22.903  6900  6961 I jxcore-log: 
,08-12 13:48:23.034  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-12 13:48:23.034  6900  6961 I jxcore-log: 
,08-12 13:48:23.056  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-12 13:48:23.056  6900  6961 I jxcore-log: 
,08-12 13:48:23.101  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-12 13:48:23.101  6900  6961 I jxcore-log: 
,08-12 13:48:23.123  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-12 13:48:23.123  6900  6961 I jxcore-log: 
,08-12 13:48:23.151  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-12 13:48:23.151  6900  6961 I jxcore-log: 
,08-12 13:48:23.205  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-12 13:48:23.205  6900  6961 I jxcore-log: 
,08-12 13:48:23.214  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-12 13:48:23.214  6900  6961 I jxcore-log: 
,08-12 13:48:23.527  6900  6961 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-12 13:48:23.527  6900  6961 I jxcore-log: 
,08-12 13:48:23.539  2080  2096 D BluetoothAdapterService(120058730): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3634a710
,08-12 13:48:23.540  6900  6961 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,08-12 13:48:23.548  6900  6961 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-12 13:48:23.548  6900  6961 I jxcore-log: 
,08-12 13:48:25.455   296   357 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-12 13:48:30.460   296   357 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-12 13:48:31.656  6900  6961 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-12 13:48:31.656  6900  6961 I jxcore-log: 
,08-12 13:48:32.132  6988  6988 D AndroidRuntime: 
08-12 13:48:32.132  6988  6988 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-12 13:48:32.142  6988  6988 D AndroidRuntime: CheckJNI is OFF
08-12 13:48:32.518  6988  6988 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 13:48:32.568   816   871 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
,08-12 13:48:32.570   816   871 I ActivityManager: Killing 6900:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
08-12 13:48:32.622   816  1939 I WindowState: WIN DEATH: Window{38fa48f3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 13:48:32.632   816  1939 D InputDispatcher: Focus left window: Window{38fa48f3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 13:48:32.632   816  1939 D InputDispatcher: Window went away: Window{38fa48f3 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 13:48:32.686   816  1064 W PackageSettings: Skipping PackageSetting{3bf2e8c6 com.example.hello/10317} due to missing metadata
,08-12 13:48:32.691   816   871 I ActivityManager:   Force finishing activity ActivityRecord{865e47c u0 com.test.thalitest/.MainActivity t259}
,08-12 13:48:32.767   816  1948 W ActivityManager: Spurious death for ProcessRecord{21758686 6900:com.test.thalitest/u0a30}, curProc for 6900: null
08-12 13:48:32.771   816  1064 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
,08-12 13:48:32.843  2027  2027 I art     : Explicit concurrent mark sweep GC freed 328(25KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/21MB, paused 2.256ms total 67.893ms
,08-12 13:48:32.890  1949  1949 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
,08-12 13:48:32.903  1366  1366 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-12 13:48:32.904   816  1289 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-12 13:48:32.910  1760  2396 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-12 13:48:32.917  3712  3712 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-12 13:48:32.925  3712  3712 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-12 13:48:32.925  3712  3712 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-12 13:48:32.925  3712  3712 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-12 13:48:32.925  3712  3712 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 13:48:32.925  3712  3712 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 13:48:32.925  3712  3712 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-12 13:48:32.925  3712  3712 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-12 13:48:32.925  3712  3712 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 13:48:32.925  3712  3712 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 13:48:32.925  3712  3712 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-12 13:48:32.925  3712  3712 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-12 13:48:32.930  3458  3458 I art     : Explicit concurrent mark sweep GC freed 2974(146KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 16MB/21MB, paused 2.769ms total 148.766ms
08-12 13:48:32.930  1912  1912 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,08-12 13:48:32.933  1949  1949 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
08-12 13:48:32.969   816   871 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7018 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-12 13:48:33.008  1366  1366 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-12 13:48:33.016  1949  1949 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-12 13:48:33.018  1949  1949 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-12 13:48:33.019  1949  1949 I Activity: Activity.onPostResume() called 
,08-12 13:48:33.035  1949  1949 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-12 13:48:33.074   816   816 W art     : Suspending all threads took: 10.507ms
,08-12 13:48:33.094  1949  7036 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,08-12 13:48:33.101   816   988 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
08-12 13:48:33.103   816   988 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-12 13:48:33.103   816   988 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-12 13:48:33.103   816   988 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-12 13:48:33.103   816   988 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-12 13:48:33.103   816   988 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3d316658,  pkg=WindowManager.LayoutParams
08-12 13:48:33.103   816   988 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-12 13:48:33.113   816  2038 D InputDispatcher: Focus entered window: Window{7ff966a u0 com.lge.launcher2/com.lge.launcher2.Launcher}
,08-12 13:48:33.131   816   816 I art     : Explicit concurrent mark sweep GC freed 41939(2MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 23MB/35MB, paused 27.609ms total 273.763ms
08-12 13:48:33.132   816  1064 I art     : WaitForGcToComplete blocked for 161.371ms for cause Explicit
08-12 13:48:33.133  1949  1949 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 13:48:33.133  1949  1949 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-12 13:48:33.133  1949  1949 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-12 13:48:33.142  7018  7018 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 13:48:33.142  7018  7018 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 13:48:33.143  7018  7018 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-12 13:48:33.154  1949  1949 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
,08-12 13:48:33.155  1949  1949 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
08-12 13:48:33.157  1949  1949 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-12 13:48:33.164  1366  1366 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-12 13:48:33.166  1366  1366 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-12 13:48:33.167  1366  1366 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-12 13:48:33.167  1366  1366 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-12 13:48:33.167  1366  1366 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-12 13:48:33.167  1366  1366 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
,08-12 13:48:33.177  1366  1533 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 13:48:33.177  1366  1533 D KeyguardModel: createShortcutInfo...
08-12 13:48:33.188  1366  1533 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 13:48:33.188  1366  1533 D KeyguardModel: createShortcutInfo...
,08-12 13:48:33.193  1366  1533 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 13:48:33.193  1366  1533 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 13:48:33.195  1366  1533 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 13:48:33.195  1366  1533 D KeyguardModel: createShortcutInfo...
08-12 13:48:33.197  1366  1533 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 13:48:33.197  1366  1533 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 13:48:33.199  1366  1533 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 13:48:33.199  1366  1533 D KeyguardModel: createShortcutInfo...
08-12 13:48:33.202  1366  1533 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 13:48:33.202  1366  1533 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-12 13:48:33.205  1366  1533 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 13:48:33.205  1366  1533 D KeyguardModel: createShortcutInfo...
08-12 13:48:33.211  1366  1366 D KeyguardModel: handleShortcutListChanged...
08-12 13:48:33.214  1366  1533 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 13:48:33.214  1366  1533 D KeyguardModel: createShortcutInfo...
,08-12 13:48:33.217  1366  1533 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 13:48:33.217  1366  1533 D KeyguardModel: createShortcutInfo...
08-12 13:48:33.220  1366  1533 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 13:48:33.220  1366  1533 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 13:48:33.223  1366  1533 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 13:48:33.223  1366  1533 D KeyguardModel: createShortcutInfo...
08-12 13:48:33.225  1366  1533 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 13:48:33.225  1366  1533 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 13:48:33.227  1366  1533 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 13:48:33.227  1366  1533 D KeyguardModel: createShortcutInfo...
08-12 13:48:33.230  1366  1533 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 13:48:33.230  1366  1533 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 13:48:33.232  1366  1533 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 13:48:33.232  1366  1533 D KeyguardModel: createShortcutInfo...
,08-12 13:48:33.242  1366  1366 D KeyguardModel: handleShortcutListChanged...
08-12 13:48:33.245   816   816 D administrator: Handling package changes for user 0
08-12 13:48:33.281   816  1886 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-12 13:48:33.286   816  1886 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6900 uid 10030
08-12 13:48:33.353  1949  1949 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
08-12 13:48:33.353  1634  1634 E b       : Unable to connect to the editor to retrieve text... will retry later
,08-12 13:48:33.360  1949  1949 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@379f61da time:366713
08-12 13:48:33.402   816   991 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3ab94516 u0 com.lge.launcher2/.Launcher t258} time:366755
,08-12 13:48:33.412  1949  1949 I art     : Explicit concurrent mark sweep GC freed 3802(222KB) AllocSpace objects, 4(645KB) LOS objects, 40% free, 15MB/25MB, paused 1.507ms total 50.758ms
,08-12 13:48:33.413  1949  1949 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
08-12 13:48:33.423   816  1064 I art     : Explicit concurrent mark sweep GC freed 13593(1702KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 21.069ms total 287.731ms
,08-12 13:48:33.479  7018  7018 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-12 13:48:33.495   816   816 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-12 13:48:33.495   816   816 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-12 13:48:33.504  7018  7018 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
08-12 13:48:33.506   816   816 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-12 13:48:33.513   816  1350 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
08-12 13:48:33.523  6988  6988 D AndroidRuntime: Shutting down VM
,08-12 13:48:33.578   816  1064 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7040 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-12 13:48:33.634  1858  1858 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-12 13:48:33.634  1858  1858 D LCardEmulationManager: getDefaultRoute
,08-12 13:48:33.636   816   869 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-12 13:48:33.673   816  1905 I ActivityManager: Killing 6481:com.google.android.talk/u0a61 (adj 15): empty #11
,08-12 13:48:33.708   816  1977 W libprocessgroup: failed to open /acct/uid_10061/pid_6481/cgroup.procs: No such file or directory
,08-12 13:48:33.777   816   869 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-12 13:48:33.780  7018  7018 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-12 13:48:33.818   816  1361 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7063 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-12 13:48:33.820   816  1361 I ActivityManager: Killing 6543:com.android.gallery3d/u0a23 (adj 15): empty #11
08-12 13:48:33.848   816  1886 W libprocessgroup: failed to open /acct/uid_10023/pid_6543/cgroup.procs: No such file or directory
,08-12 13:48:33.852  1949  1949 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-12 13:48:33.913  7063  7063 I AppUp4:AppBoxCP: onCreate
,08-12 13:48:33.920  7063  7063 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-12 13:48:33.930  7063  7063 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,08-12 13:48:33.931  7063  7063 D AndroidRuntime: Shutting down VM
--------- beginning of crash
08-12 13:48:33.933  7063  7063 E AndroidRuntime: FATAL EXCEPTION: main
08-12 13:48:33.933  7063  7063 E AndroidRuntime: Process: com.lge.appbox.client, PID: 7063
08-12 13:48:33.933  7063  7063 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
08-12 13:48:33.933  7063  7063 E AndroidRuntime: 	... 11 more
,08-12 13:48:33.949   816  7083 E DropBoxManagerService: Can't write: system_app_crash
08-12 13:48:33.949   816  7083 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
08-12 13:48:33.949   816  7083 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-12 13:48:33.949   816  7083 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 13:48:33.949   816  7083 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 13:48:33.949   816  7083 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 13:48:33.949   816  7083 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-12 13:48:33.949   816  7083 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12621)
08-12 13:48:33.949   816  7083 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 13:48:33.949   816  7083 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 13:48:33.949   816  7083 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 13:48:33.949   816  7083 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-12 13:48:33.949   816  7083 E DropBoxManagerService: 	... 5 more
08-12 13:48:33.991   816   871 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7084 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a

```
