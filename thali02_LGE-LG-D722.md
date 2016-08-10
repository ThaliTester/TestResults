#### Test 7976383036177d0_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-10 16:36:30.075   300   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-10 16:36:33.086  6781  6781 D AndroidRuntime: 
08-10 16:36:33.086  6781  6781 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-10 16:36:33.096  6781  6781 D AndroidRuntime: CheckJNI is OFF
08-10 16:36:33.509  6781  6781 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-10 16:36:33.525   956  1290 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-10 16:36:33.569   956  1290 D ActivityManager: setTaskToReturnTo : TaskRecord{3bdc46da #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-10 16:36:33.570   956  1290 D ActivityManager: setTaskToReturnTo : TaskRecord{3bdc46da #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-10 16:36:33.574   956  1290 D WindowStateEx: AppWindowTokenEx init.. 
08-10 16:36:33.619   956  1290 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6801 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-10 16:36:33.621   956  1290 D InputDispatcher: Focus left window: Window{15293e43 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-10 16:36:33.623  6781  6781 D AndroidRuntime: Shutting down VM
08-10 16:36:33.627  1948  1948 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-10 16:36:33.648   956   956 V ActivityManager: Display changed displayId=0
08-10 16:36:33.653  1790  1790 D DSDPConnection: Display #0 changed.
08-10 16:36:33.789  6801  6801 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-10 16:36:33.860  6801  6801 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-10 16:36:33.893  6801  6801 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2080-2082)
08-10 16:36:33.894  6801  6801 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 16:36:33.924  6801  6801 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1b026c9a}
08-10 16:36:33.925  6801  6801 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 16:36:33.925  6801  6801 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-10 16:36:33.939  6801  6801 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-10 16:36:33.941  6801  6801 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 16:36:33.944  6801  6801 E SysUtils: ApplicationContext is null in ApplicationStatus
08-10 16:36:33.967  6801  6801 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-10 16:36:33.975  6801  6801 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 16:36:33.975  6801  6801 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 16:36:33.975  6801  6801 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 16:36:33.975  6801  6801 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 16:36:33.975  6801  6801 I Adreno-EGL: Build Date: 03/02/15 Mon
08-10 16:36:33.975  6801  6801 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-10 16:36:33.975  6801  6801 I Adreno-EGL: Remote Branch: 
08-10 16:36:33.975  6801  6801 I Adreno-EGL: Local Patches: 
08-10 16:36:33.975  6801  6801 I Adreno-EGL: Reconstruct Branch: 
08-10 16:36:34.041   288  1358 V AudioPolicyService: registerClient() client 0xb2c1e340, uid 10030
08-10 16:36:34.066   956  1055 D BluetoothManagerService: Message: 20
08-10 16:36:34.066   956  1055 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@198d347e:true
08-10 16:36:34.076  2078  2094 D BluetoothAdapterService(178472360): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3c2e6e3e
08-10 16:36:34.182   956  1022 W ActivityManager: Activity pause timeout for ActivityRecord{fcc70b u0 com.test.thalitest/.MainActivity t259}
08-10 16:36:34.234  6801  6801 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 16:36:34.248  6801  6801 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-10 16:36:34.256  6801  6801 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-10 16:36:34.258  6801  6801 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-10 16:36:34.258  6801  6801 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-10 16:36:34.277  6801  6801 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-10 16:36:34.286  6801  6801 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 16:36:34.286  6801  6801 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 16:36:34.351  6801  6801 I Activity: Activity.onPostResume() called 
08-10 16:36:34.357  6801  6851 D OpenGLRenderer: Render dirty regions requested: true
08-10 16:36:34.357  6801  6851 I OpenGLRenderer: Initialized EGL, version 1.4
08-10 16:36:34.363  6801  6851 D OpenGLRenderer: Enabling debug mode 0
08-10 16:36:34.379  6801  6801 D Atlas   : Validating map...
08-10 16:36:34.386   956  1952 D SplitWindow: check instance of lgWin Window{21adb92e u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-10 16:36:34.408  6801  6838 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-10 16:36:34.430   956  1054 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-10 16:36:34.433   956  1054 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-10 16:36:34.433  1372  1372 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-10 16:36:34.433  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-10 16:36:34.433  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-10 16:36:34.433  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-10 16:36:34.434   956  1054 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-10 16:36:34.434   956  1054 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-10 16:36:34.434   956  1054 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-10 16:36:34.434   956  1054 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@17db1a23,  pkg=WindowManager.LayoutParams
08-10 16:36:34.434   956  1054 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-10 16:36:34.437   956  2174 D InputDispatcher: Focus entered window: Window{21adb92e u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-10 16:36:34.465   956  1290 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-10 16:36:34.485   956  1056 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +802ms (total +904ms)
08-10 16:36:34.486   956  1056 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{fcc70b u0 com.test.thalitest/.MainActivity t259} time:192674
08-10 16:36:34.489  6801  6801 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-10 16:36:34.489  6801  6801 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@12f63a84 time:192678
08-10 16:36:34.535  6801  6801 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-10 16:36:34.544  1632  1632 E b       : Unable to connect to the editor to retrieve text... will retry later
08-10 16:36:34.603  6801  6801 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-10 16:36:34.655  6801  6801 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6801
,08-10 16:36:34.802  6801  6801 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-10 16:36:35.079   300   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-10 16:36:35.186  6801  6853 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1635611904
,08-10 16:36:35.204  6801  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-10 16:36:35.204  6801  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-10 16:36:35.204  6801  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-10 16:36:35.204  6801  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-10 16:36:35.204  6801  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-10 16:36:35.204  6801  6853 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3e12b808 added. We now have 1 listener(s)
,08-10 16:36:35.213   956   974 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-10 16:36:35.220  6801  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,08-10 16:36:35.224  6801  6853 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-10 16:36:35.225  6801  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 16:36:35.225  6801  6853 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-10 16:36:35.235  6801  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-10 16:36:35.235  6801  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-10 16:36:35.235  6801  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-10 16:36:35.235  6801  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-10 16:36:35.235  6801  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-10 16:36:35.235  6801  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-10 16:36:35.235  6801  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-10 16:36:35.235  6801  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-10 16:36:35.235  6801  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-10 16:36:35.235  6801  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-10 16:36:35.235  6801  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-10 16:36:35.235  6801  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-10 16:36:35.235  6801  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-10 16:36:35.235  6801  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-10 16:36:35.235  6801  6853 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@254e2587 added. We now have 1 listener(s)
,08-10 16:36:35.237  6801  6853 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 16:36:35.246  6801  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 16:36:35.246  6801  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-10 16:36:35.248  6801  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-10 16:36:35.249  6801  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-10 16:36:35.249  6801  6853 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-10 16:36:35.255  6801  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-10 16:36:35.256   956  2196 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 16:36:35.257  6801  6853 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-10 16:36:35.267  2078  3619 D BluetoothAdapterService(178472360): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3c2e6e3e
,08-10 16:36:35.271  6801  6853 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-10 16:36:35.271  6801  6853 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 16:36:35.271  6801  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 16:36:35.271  6801  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 16:36:35.271  6801  6853 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 16:36:35.271  6801  6853 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 16:36:35.271  6801  6853 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 16:36:35.271  6801  6853 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 16:36:35.271  6801  6853 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 16:36:35.271  6801  6853 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-10 16:36:35.272  6801  6853 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 16:36:35.274  6801  6853 I io.jxcore.node.LifeCycleMonitor: start: OK
08-10 16:36:35.274  6801  6801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 16:36:35.276  6801  6801 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 16:36:35.307  6801  6801 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-10 16:36:35.476  6801  6815 I art     : CheckpointMarkThreadRoots callback created = 0xb0776400
,08-10 16:36:35.520  6801  6815 I art     : CheckpointMarkThreadRoots callback created = 0xb07763c0
,08-10 16:36:36.052  6801  6860 W jxcore-log: Initializing JXcore engine
,08-10 16:36:36.053  6801  6860 W jxcore-log: JXcore engine is ready
08-10 16:36:36.148  6860  6860 W Thread-815: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7619]" dev="sockfs" ino=7619 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-10 16:36:36.148  6860  6860 W Thread-815: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-10 16:36:36.148  6860  6860 W Thread-815: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7756]" dev="sockfs" ino=7756 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-10 16:36:36.148  6860  6860 W Thread-815: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-10 16:36:36.148  6860  6860 W Thread-815: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-10 16:36:36.148  6860  6860 W Thread-815: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[32307]" dev="sockfs" ino=32307 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-10 16:36:36.177  6801  6860 W jxcore-log: Starting JXcore engine
,08-10 16:36:36.381  6801  6860 W jxcore-log: Platform android
08-10 16:36:36.381  6801  6860 W jxcore-log: 
,08-10 16:36:36.382  6801  6860 W jxcore-log: Process ARCH arm
08-10 16:36:36.382  6801  6860 W jxcore-log: 
08-10 16:36:36.656  6801  6860 I jxcore-log: JXcore Cordova bridge is ready!
08-10 16:36:36.656  6801  6860 I jxcore-log: 
08-10 16:36:36.657  6801  6860 W jxcore-log: JXcore engine is started
,08-10 16:36:36.661  6801  6853 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-10 16:36:36.663  6801  6801 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-10 16:36:40.084   300   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-10 16:36:45.089   300   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-10 16:36:46.858   956   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-10 16:36:46.858   956   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-10 16:36:46.858   956   986 D sensors_hal_Time: tsOffsetIs: Apps: 205046208624; DSPS: 6817664; Offset : -3024803510
,08-10 16:36:49.912  1761  4334 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-10 16:36:50.094   300   353 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-10 16:36:52.348  6801  6860 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-10 16:36:52.348  6801  6860 I jxcore-log: 
,08-10 16:36:52.352  6801  6860 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-10 16:36:52.352  6801  6860 I jxcore-log: 
,08-10 16:36:52.358  2078  2093 D BluetoothAdapterService(178472360): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3c2e6e3e
08-10 16:36:52.359  6801  6860 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 16:36:52.359  6801  6860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 16:36:52.359  6801  6860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 16:36:52.359  6801  6860 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 16:36:52.359  6801  6860 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 16:36:52.359  6801  6860 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 16:36:52.359  6801  6860 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 16:36:52.359  6801  6860 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 16:36:52.361  2078  3546 D BluetoothAdapterService(178472360): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3c2e6e3e
08-10 16:36:52.362  6801  6860 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-10 16:36:52.367  6801  6860 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-10 16:36:52.367  6801  6860 I jxcore-log: 
08-10 16:36:52.369  6801  6860 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-10 16:36:52.369  6801  6860 I jxcore-log: 
08-10 16:36:52.890  6801  6860 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-10 16:36:52.891  6801  6860 I jxcore-log: Failed to execute UT.
08-10 16:36:52.891  6801  6860 I jxcore-log: 
,08-10 16:36:52.891  6801  6860 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-10 16:36:52.891  6801  6860 I jxcore-log: 
08-10 16:36:52.901  6801  6860 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 16:36:52.901  6801  6860 I jxcore-log: 
08-10 16:36:52.914  6801  6801 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-10 16:36:53.294  6879  6879 D AndroidRuntime: 
08-10 16:36:53.294  6879  6879 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-10 16:36:53.302  6879  6879 D AndroidRuntime: CheckJNI is OFF
08-10 16:36:53.624  6879  6879 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-10 16:36:53.683   956  1022 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
,08-10 16:36:53.684   956  1022 I ActivityManager: Killing 6801:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
08-10 16:36:53.733   956  1952 I WindowState: WIN DEATH: Window{21adb92e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-10 16:36:53.746   956  1952 D InputDispatcher: Focus left window: Window{21adb92e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-10 16:36:53.746   956  1952 D InputDispatcher: Window went away: Window{21adb92e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-10 16:36:53.803   956  1066 W PackageSettings: Skipping PackageSetting{999df64 com.example.hello/10317} due to missing metadata
,08-10 16:36:53.814   956  1022 I ActivityManager:   Force finishing activity ActivityRecord{fcc70b u0 com.test.thalitest/.MainActivity t259}
,08-10 16:36:53.867   956  1856 W ActivityManager: Spurious death for ProcessRecord{2df1541d 6801:com.test.thalitest/u0a30}, curProc for 6801: null
,08-10 16:36:53.868   956  1066 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
08-10 16:36:53.873   956  1066 I ActivityManager:   Force finishing activity ActivityRecord{fcc70b u0 com.test.thalitest/.MainActivity t259 f}
08-10 16:36:53.873   956  1066 W ActivityManager: Duplicate finish request for ActivityRecord{fcc70b u0 com.test.thalitest/.MainActivity t259 f}
,08-10 16:36:53.919  1948  1948 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
,08-10 16:36:53.926  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-10 16:36:53.948  1910  1910 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,08-10 16:36:53.961  1761  2509 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-10 16:36:53.973  1948  1948 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
,08-10 16:36:53.983   956  1286 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-10 16:36:53.989   956  1022 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6899 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-10 16:36:54.001  3679  3679 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-10 16:36:54.006  3679  3679 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-10 16:36:54.006  3679  3679 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-10 16:36:54.006  3679  3679 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-10 16:36:54.006  3679  3679 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 16:36:54.006  3679  3679 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 16:36:54.006  3679  3679 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-10 16:36:54.006  3679  3679 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-10 16:36:54.006  3679  3679 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 16:36:54.006  3679  3679 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 16:36:54.006  3679  3679 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-10 16:36:54.006  3679  3679 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-10 16:36:54.029  2028  2028 I art     : Explicit concurrent mark sweep GC freed 173(18KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/21MB, paused 3.592ms total 151.688ms
,08-10 16:36:54.036  1372  1372 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-10 16:36:54.077  1372  1511 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-10 16:36:54.078  1372  1511 D KeyguardModel: createShortcutInfo...
,08-10 16:36:54.079  3390  3390 I art     : Explicit concurrent mark sweep GC freed 3093(151KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 16MB/21MB, paused 1.060ms total 196.579ms
08-10 16:36:54.086  1372  1511 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-10 16:36:54.086  1372  1511 D KeyguardModel: createShortcutInfo...
08-10 16:36:54.087  1948  1948 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-10 16:36:54.088  1948  1948 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-10 16:36:54.088  1948  1948 I Activity: Activity.onPostResume() called 
08-10 16:36:54.088  1372  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-10 16:36:54.093  1372  1511 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-10 16:36:54.099  1372  1511 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-10 16:36:54.099  1372  1511 D KeyguardModel: createShortcutInfo...
08-10 16:36:54.101  1372  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 16:36:54.101  1372  1511 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-10 16:36:54.103  1372  1511 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-10 16:36:54.103  1372  1511 D KeyguardModel: createShortcutInfo...
08-10 16:36:54.106  1372  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 16:36:54.106  1372  1511 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-10 16:36:54.108  1372  1511 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-10 16:36:54.108  1372  1511 D KeyguardModel: createShortcutInfo...
08-10 16:36:54.115  1372  1372 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-10 16:36:54.115  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-10 16:36:54.118  1948  1948 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-10 16:36:54.119  1372  1372 D KeyguardModel: handleShortcutListChanged...
08-10 16:36:54.122  1372  1511 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-10 16:36:54.122  1372  1511 D KeyguardModel: createShortcutInfo...
08-10 16:36:54.142  1372  1511 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-10 16:36:54.142  1372  1511 D KeyguardModel: createShortcutInfo...
08-10 16:36:54.144  1372  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 16:36:54.144  1372  1511 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-10 16:36:54.146  1372  1511 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-10 16:36:54.146  1372  1511 D KeyguardModel: createShortcutInfo...
08-10 16:36:54.149  1372  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 16:36:54.149  1372  1511 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-10 16:36:54.150  1948  6921 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
08-10 16:36:54.151  1372  1511 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-10 16:36:54.151  1372  1511 D KeyguardModel: createShortcutInfo...
08-10 16:36:54.154  1372  1511 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 16:36:54.154   956  1054 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
08-10 16:36:54.154  1372  1511 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-10 16:36:54.154   956  1054 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-10 16:36:54.155   956  1054 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-10 16:36:54.155   956  1054 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-10 16:36:54.155  1372  1372 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-10 16:36:54.155   956  1054 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-10 16:36:54.155  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-10 16:36:54.155  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-10 16:36:54.155  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-10 16:36:54.155   956  1054 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@17db1a23,  pkg=WindowManager.LayoutParams
08-10 16:36:54.155   956  1054 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-10 16:36:54.156  1372  1511 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-10 16:36:54.156  1372  1511 D KeyguardModel: createShortcutInfo...
08-10 16:36:54.159   956  1971 D InputDispatcher: Focus entered window: Window{15293e43 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
,08-10 16:36:54.169  1372  1372 D KeyguardModel: handleShortcutListChanged...
08-10 16:36:54.176  1948  1948 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-10 16:36:54.176  1948  1948 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-10 16:36:54.176  1948  1948 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,08-10 16:36:54.183  1948  1948 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-10 16:36:54.184  1948  1948 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
08-10 16:36:54.184  1948  1948 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-10 16:36:54.189  6899  6899 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 16:36:54.189  6899  6899 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 16:36:54.195  6899  6899 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-10 16:36:54.203   956   956 I art     : Explicit concurrent mark sweep GC freed 48259(2MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 24MB/36MB, paused 5.433ms total 300.286ms
08-10 16:36:54.205   956  1066 I art     : WaitForGcToComplete blocked for 156.943ms for cause Explicit
,08-10 16:36:54.230   956  2174 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-10 16:36:54.231   956  2174 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6801 uid 10030
08-10 16:36:54.267   956   956 D administrator: Handling package changes for user 0
,08-10 16:36:54.283  1948  1948 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-10 16:36:54.285  1632  1632 E b       : Unable to connect to the editor to retrieve text... will retry later
08-10 16:36:54.292  1948  1948 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@19b769f1 time:212480
08-10 16:36:54.305   956  1056 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{34ec5034 u0 com.lge.launcher2/.Launcher t258} time:212494
,08-10 16:36:54.336  1948  1948 I art     : Explicit concurrent mark sweep GC freed 3832(206KB) AllocSpace objects, 4(645KB) LOS objects, 40% free, 15MB/25MB, paused 927us total 44.017ms
08-10 16:36:54.336  1948  1948 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-10 16:36:54.498   956   956 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-10 16:36:54.498   956   956 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-10 16:36:54.501   956   956 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-10 16:36:54.514   956  1348 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
,08-10 16:36:54.552   956  1020 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-10 16:36:54.564   956  1066 I art     : Explicit concurrent mark sweep GC freed 12898(1394KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.871ms total 358.692ms
,08-10 16:36:54.578  6899  6899 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-10 16:36:54.609  6899  6899 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,08-10 16:36:54.611  1857  1857 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-10 16:36:54.611  1857  1857 D LCardEmulationManager: getDefaultRoute
08-10 16:36:54.661   956  1020 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-10 16:36:54.681  6879  6879 D AndroidRuntime: Shutting down VM
,08-10 16:36:54.686  1948  1948 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-10 16:36:54.737   956  1066 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6926 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-10 16:36:54.838  6899  6899 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-10 16:36:54.844   956  5421 I ActivityManager: Killing 6431:com.google.android.talk/u0a61 (adj 15): empty #11
08-10 16:36:54.866  6469  6469 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-10 16:36:54.873   956  1290 W libprocessgroup: failed to open /acct/uid_10061/pid_6431/cgroup.procs: No such file or directory
,08-10 16:36:54.875   956  1290 I ActivityManager: Killing 6490:com.android.gallery3d/u0a23 (adj 15): empty #11
08-10 16:36:54.950   956  5421 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6948 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
08-10 16:36:54.951   956  3349 W libprocessgroup: failed to open /acct/uid_10023/pid_6490/cgroup.procs: No such file or directory
,08-10 16:36:55.098   300   353 I ThermalEngine: Sensor:pa_therm0:30000 mC

```
