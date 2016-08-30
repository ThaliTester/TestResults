#### Test 832729920321fb3_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-30 17:27:36.232   963   998 D sensors_hal_Time: tsOffsetIs: Apps: 307696627267; DSPS: 10174072; Offset : -2802319318
,08-30 17:27:37.059   295   356 I ThermalEngine: Sensor:pa_therm0:32000 mC
08-30 17:27:37.386  6577  6577 D AndroidRuntime: 
08-30 17:27:37.386  6577  6577 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-30 17:27:37.396  6577  6577 D AndroidRuntime: CheckJNI is OFF
08-30 17:27:37.770  6577  6577 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 17:27:37.790   963  1642 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 17:27:37.852   963  1642 D ActivityManager: setTaskToReturnTo : TaskRecord{2058a679 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 17:27:37.852   963  1642 D ActivityManager: setTaskToReturnTo : TaskRecord{2058a679 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-30 17:27:37.858   963  1642 D WindowStateEx: AppWindowTokenEx init.. 
08-30 17:27:37.904   963  1642 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6595 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-30 17:27:37.905   963  1642 D InputDispatcher: Focus left window: Window{35aed235 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-30 17:27:37.906  6577  6577 D AndroidRuntime: Shutting down VM
08-30 17:27:37.915  1949  1949 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-30 17:27:37.947   963   963 V ActivityManager: Display changed displayId=0
08-30 17:27:37.950  1802  1802 D DSDPConnection: Display #0 changed.
08-30 17:27:38.068  6595  6595 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-30 17:27:38.163  6595  6595 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-30 17:27:38.225  6595  6595 I LibraryLoader: Time to load native libraries: 13 ms (timestamps 9676-9689)
08-30 17:27:38.225  6595  6595 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 17:27:38.251  6595  6595 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3dc5ef1e}
08-30 17:27:38.252  6595  6595 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 17:27:38.255  6595  6595 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 17:27:38.269  6595  6595 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 17:27:38.271  6595  6595 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 17:27:38.276  6595  6595 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 17:27:38.339  6595  6595 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-30 17:27:38.347  6595  6595 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 17:27:38.347  6595  6595 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 17:27:38.348  6595  6595 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-30 17:27:38.348  6595  6595 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-30 17:27:38.348  6595  6595 I Adreno-EGL: Build Date: 03/02/15 Mon
08-30 17:27:38.348  6595  6595 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-30 17:27:38.348  6595  6595 I Adreno-EGL: Remote Branch: 
08-30 17:27:38.348  6595  6595 I Adreno-EGL: Local Patches: 
08-30 17:27:38.348  6595  6595 I Adreno-EGL: Reconstruct Branch: 
08-30 17:27:38.421   285   285 V AudioPolicyService: registerClient() client 0xb551c860, uid 10030
08-30 17:27:38.445   963  1054 D BluetoothManagerService: Message: 20
08-30 17:27:38.445   963  1054 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bf651ed:true
08-30 17:27:38.451  2079  3672 D BluetoothAdapterService(148846028): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2c5f2982
08-30 17:27:38.469   963  1034 W ActivityManager: Activity pause timeout for ActivityRecord{30defbe u0 com.test.thalitest/.MainActivity t259}
08-30 17:27:38.553  6595  6595 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 17:27:38.576  6595  6595 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-30 17:27:38.582  6595  6595 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-30 17:27:38.587  6595  6595 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-30 17:27:38.587  6595  6595 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-30 17:27:38.607  6595  6595 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-30 17:27:38.614  6595  6595 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 17:27:38.614  6595  6595 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-30 17:27:38.668  6595  6595 I Activity: Activity.onPostResume() called 
08-30 17:27:38.674  6595  6639 D OpenGLRenderer: Render dirty regions requested: true
08-30 17:27:38.674  6595  6639 I OpenGLRenderer: Initialized EGL, version 1.4
08-30 17:27:38.684  6595  6639 D OpenGLRenderer: Enabling debug mode 0
08-30 17:27:38.696  6595  6595 D Atlas   : Validating map...
08-30 17:27:38.701   963   980 D SplitWindow: check instance of lgWin Window{369c905d u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 17:27:38.715  6595  6626 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-30 17:27:38.743   963  1053 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-30 17:27:38.746   963  1053 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-30 17:27:38.746  1374  1374 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-30 17:27:38.747  1374  1374 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-30 17:27:38.747  1374  1374 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-30 17:27:38.747  1374  1374 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-30 17:27:38.748   963  1053 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-30 17:27:38.748   963  1053 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-30 17:27:38.748   963  1053 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-30 17:27:38.748   963  1053 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@12bff207,  pkg=WindowManager.LayoutParams
08-30 17:27:38.748   963  1053 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-30 17:27:38.760   963  5923 D InputDispatcher: Focus entered window: Window{369c905d u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 17:27:38.787   963  1857 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-30 17:27:38.788   963  1055 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +818ms (total +927ms)
08-30 17:27:38.789   963  1055 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{30defbe u0 com.test.thalitest/.MainActivity t259} time:310253
08-30 17:27:38.807  6595  6595 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-30 17:27:38.807  6595  6595 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@393d69e8 time:310272
08-30 17:27:38.849  6595  6595 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
08-30 17:27:38.856  1636  1636 E b       : Unable to connect to the editor to retrieve text... will retry later
08-30 17:27:38.875  6595  6595 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-30 17:27:38.931  6595  6595 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6595
,08-30 17:27:39.083  6595  6595 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 17:27:39.430  6595  6642 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426113792
,08-30 17:27:39.446  6595  6642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 17:27:39.446  6595  6642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 17:27:39.446  6595  6642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 17:27:39.446  6595  6642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 17:27:39.446  6595  6642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-30 17:27:39.447  6595  6642 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b818a2c added. We now have 1 listener(s)
,08-30 17:27:39.456   963  2270 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:27:39.459  6595  6642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
08-30 17:27:39.462  6595  6642 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-30 17:27:39.463  6595  6642 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-30 17:27:39.464  6595  6642 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-30 17:27:39.470  6595  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 17:27:39.470  6595  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 17:27:39.470  6595  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 17:27:39.470  6595  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-30 17:27:39.470  6595  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 17:27:39.470  6595  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 17:27:39.470  6595  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 17:27:39.470  6595  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 17:27:39.470  6595  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 17:27:39.470  6595  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 17:27:39.470  6595  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 17:27:39.470  6595  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 17:27:39.470  6595  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 17:27:39.470  6595  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-30 17:27:39.471  6595  6642 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@128f28fb added. We now have 1 listener(s)
08-30 17:27:39.471  6595  6642 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-30 17:27:39.485  6595  6642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 17:27:39.485  6595  6642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 17:27:39.485  6595  6642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 17:27:39.485  6595  6642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 17:27:39.485  6595  6642 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 17:27:39.489  6595  6642 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 17:27:39.490   963  1893 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-30 17:27:39.491  6595  6642 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-30 17:27:39.501  2079  2101 D BluetoothAdapterService(148846028): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2c5f2982
,08-30 17:27:39.503  6595  6642 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-30 17:27:39.503  6595  6642 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:27:39.503  6595  6642 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:27:39.503  6595  6642 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:27:39.503  6595  6642 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:27:39.503  6595  6642 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:27:39.503  6595  6642 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:27:39.503  6595  6642 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:27:39.503  6595  6642 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 17:27:39.503  6595  6642 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 17:27:39.503  6595  6642 D io.jxcore.node.ConnectivityMonitor: start: OK
08-30 17:27:39.505  6595  6642 I io.jxcore.node.LifeCycleMonitor: start: OK
08-30 17:27:39.506  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:27:39.507  6595  6595 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-30 17:27:39.538  6595  6595 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 17:27:39.656  6595  6609 I art     : CheckpointMarkThreadRoots callback created = 0xaafe0940
,08-30 17:27:39.707  6595  6609 I art     : CheckpointMarkThreadRoots callback created = 0xaafe0910
,08-30 17:27:40.378  6595  6648 W jxcore-log: Initializing JXcore engine
,08-30 17:27:40.379  6595  6648 W jxcore-log: JXcore engine is ready
08-30 17:27:40.511  6648  6648 W Thread-774: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7551]" dev="sockfs" ino=7551 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-30 17:27:40.511  6648  6648 W Thread-774: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 17:27:40.511  6648  6648 W Thread-774: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6607]" dev="sockfs" ino=6607 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-30 17:27:40.511  6648  6648 W Thread-774: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-30 17:27:40.511  6648  6648 W Thread-774: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-30 17:27:40.511  6648  6648 W Thread-774: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[31898]" dev="sockfs" ino=31898 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 17:27:40.537  6595  6648 W jxcore-log: Starting JXcore engine
,08-30 17:27:40.687  6595  6648 W jxcore-log: Platform android
08-30 17:27:40.687  6595  6648 W jxcore-log: 
,08-30 17:27:40.687  6595  6648 W jxcore-log: Process ARCH arm
08-30 17:27:40.687  6595  6648 W jxcore-log: 
08-30 17:27:40.969  6595  6648 I jxcore-log: JXcore Cordova bridge is ready!
08-30 17:27:40.969  6595  6648 I jxcore-log: 
08-30 17:27:40.970  6595  6648 W jxcore-log: JXcore engine is started
,08-30 17:27:40.975  6595  6642 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-30 17:27:40.977  6595  6595 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-30 17:27:42.064   295   356 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-30 17:27:47.068   295   356 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-30 17:27:52.073   295   356 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-30 17:27:57.078   295   356 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-30 17:27:57.484   963   998 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-30 17:27:57.484   963   998 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-30 17:27:57.484   963   998 D sensors_hal_Time: tsOffsetIs: Apps: 328949082483; DSPS: 10870467; Offset : -2802152948
,08-30 17:28:00.055  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-30 17:28:00.055  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-30 17:28:00.056  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-30 17:28:00.060  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-30 17:28:00.060  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-30 17:28:00.061  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-30 17:28:00.062  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
08-30 17:28:02.083   295   356 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-30 17:28:02.936  6595  6648 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 17:28:02.936  6595  6648 I jxcore-log: 
,08-30 17:28:02.940  6595  6648 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 17:28:02.940  6595  6648 I jxcore-log: 
08-30 17:28:02.947  2079  2101 D BluetoothAdapterService(148846028): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2c5f2982
08-30 17:28:02.947  6595  6648 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 17:28:02.947  6595  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 17:28:02.947  6595  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-30 17:28:02.947  6595  6648 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 17:28:02.947  6595  6648 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 17:28:02.947  6595  6648 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 17:28:02.947  6595  6648 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 17:28:02.947  6595  6648 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 17:28:02.952  2079  2101 D BluetoothAdapterService(148846028): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2c5f2982
08-30 17:28:02.953  6595  6648 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-30 17:28:02.956  6595  6648 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 17:28:02.956  6595  6648 I jxcore-log: 
08-30 17:28:02.959  6595  6648 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 17:28:02.959  6595  6648 I jxcore-log: 
,08-30 17:28:03.510  6595  6648 I jxcore-log: Running unit tests
08-30 17:28:03.510  6595  6648 I jxcore-log: 
,08-30 17:28:03.511  6595  6648 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 17:28:03.511  6595  6648 I jxcore-log: Failed to execute UT.
08-30 17:28:03.511  6595  6648 I jxcore-log: 
08-30 17:28:03.513  6595  6648 I jxcore-log: Unit Test app is loaded
08-30 17:28:03.513  6595  6648 I jxcore-log: 
08-30 17:28:03.530  6595  6648 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 17:28:03.530  6595  6648 I jxcore-log: 
,08-30 17:28:03.535  6595  6648 I jxcore-log: My device name is: LGE-LG-D722
08-30 17:28:03.535  6595  6648 I jxcore-log: 
08-30 17:28:03.539  6595  6595 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-30 17:28:07.088   295   356 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-30 17:28:07.520  6595  6648 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 17:28:07.520  6595  6648 I jxcore-log: 
,08-30 17:28:08.219  6595  6648 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 17:28:08.219  6595  6648 I jxcore-log: 
,08-30 17:28:08.255  6595  6648 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 17:28:08.255  6595  6648 I jxcore-log: 
,08-30 17:28:10.431  6595  6648 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 17:28:10.431  6595  6648 I jxcore-log: 
,08-30 17:28:10.796  6595  6648 I jxcore-log: ERROR runTests: 
08-30 17:28:10.796  6595  6648 I jxcore-log: 
08-30 17:28:10.799  6595  6648 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 17:28:10.799  6595  6648 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-30 17:28:10.800  6595  6648 I jxcore-log: WARN testUtils: logCallback not set!
08-30 17:28:10.800  6595  6648 I jxcore-log: 
08-30 17:28:10.816  6595  6648 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 17:28:10.816  6595  6648 I jxcore-log:     _functionName: 'loadFile',
08-30 17:28:10.816  6595  6648 I jxcore-log:     _lineNumber: '26',
08-30 17:28:10.816  6595  6648 I jxcore-log:     _columnNumber: '11',
08-30 17:28:10.816  6595  6648 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 17:28:10.816  6595  6648 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 17:28:10.816  6595  6648 I jxcore-log:     _functionName: '',
08-30 17:28:10.816  6595  6648 I jxcore-log:     _lineNumber: '38',
08-30 17:28:10.816  6595  6648 I jxcore-log:     _columnNumber: '7',
08-30 17:28:10.816  6595  6648 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 17:28:10.816  6595  6648 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 17:28:10.816  6595  6648 I jxcore-log:     _functionName: '',
08-30 17:28:10.816  6595  6648 I jxcore-log:     _lineNumber: '35',
08-30 17:28:10.816  6595  6648 I jxcore-log:     _columnNumber: '3',
08-30 17:28:10.816  6595  6648 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 17:28:10.816  6595  6648 I jxcore-log:   { _fileName: 'module.js',
08-30 17:28:10.816  6595  6648 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 17:28:10.816  6595  6648 I jxcore-log:     _lineNumber: '621',
08-30 17:28:10.816  6595  6648 I jxcore-log:     _columnNumber: '8',
08-30 17:28:10.816  6595  6648 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 17:28:10.816  6595  6648 I jxcore-log:   { _fileName: 'module.js',
08-30 17:28:10.816  6595  6648 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 17:28:10.816  6595  6648 I jxcore-log:     _lineNumber: '651',
08-30 17:28:10.816  6595  6648 I jxcore-log:     _columnNumber: '1',
08-30 17:28:10.816  6595  6648 I jxcore-log:    
08-30 17:28:10.816  6595  6648 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 17:28:10.816  6595  6648 I jxcore-log: 
08-30 17:28:10.816  6595  6648 E jxcore-log: Error: 
08-30 17:28:10.816  6595  6648 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 17:28:10.816  6595  6648 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 17:28:10.817  6595  6648 E jxcore-log: 
,08-30 17:28:10.856   963  3296 I LocationManagerService: remove 1eeb0f14
,08-30 17:28:10.864   963  3296 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-30 17:28:10.864   963  3296 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-30 17:28:10.865   963  3296 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-30 17:28:10.865   963  3296 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-30 17:28:10.866   963  3296 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-30 17:28:11.172  6670  6670 D AndroidRuntime: 
08-30 17:28:11.172  6670  6670 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-30 17:28:11.179  6670  6670 D AndroidRuntime: CheckJNI is OFF
08-30 17:28:11.476  6670  6670 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 17:28:11.533   963  1034 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
08-30 17:28:11.534   963  1034 I ActivityManager: Killing 6595:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
,08-30 17:28:11.587   963  1857 I WindowState: WIN DEATH: Window{369c905d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-30 17:28:11.597   963  1857 D InputDispatcher: Focus left window: Window{369c905d u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 17:28:11.597   963  1857 D InputDispatcher: Window went away: Window{369c905d u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 17:28:11.630   963  1062 W PackageSettings: Skipping PackageSetting{1c4da8c8 com.example.hello/10317} due to missing metadata
,08-30 17:28:11.658   963  1034 I ActivityManager:   Force finishing activity ActivityRecord{30defbe u0 com.test.thalitest/.MainActivity t259}
,08-30 17:28:11.694   963  1286 W ActivityManager: Spurious death for ProcessRecord{193868b8 6595:com.test.thalitest/u0a30}, curProc for 6595: null
,08-30 17:28:11.696   963  1062 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
08-30 17:28:11.703   963  1062 I ActivityManager:   Force finishing activity ActivityRecord{30defbe u0 com.test.thalitest/.MainActivity t259 f}
08-30 17:28:11.704   963  1062 W ActivityManager: Duplicate finish request for ActivityRecord{30defbe u0 com.test.thalitest/.MainActivity t259 f}
,08-30 17:28:11.765  2029  2029 I art     : Explicit concurrent mark sweep GC freed 1005(54KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/20MB, paused 1.675ms total 58.995ms
,08-30 17:28:11.799  1374  1374 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-30 17:28:11.815  3645  3645 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-30 17:28:11.817  1772  2496 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 17:28:11.820  3645  3645 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-30 17:28:11.820  3645  3645 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-30 17:28:11.820  3645  3645 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-30 17:28:11.820  3645  3645 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-30 17:28:11.820  3645  3645 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-30 17:28:11.824  3645  3645 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:28:11.825  3645  3645 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-30 17:28:11.825  3645  3645 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:28:11.825  3645  3645 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:28:11.825  3645  3645 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-30 17:28:11.825  3645  3645 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-30 17:28:11.826  1912  1912 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
08-30 17:28:11.827   963  1291 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 17:28:11.869   963  1034 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6695 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-30 17:28:11.872  1949  1949 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
08-30 17:28:11.880  3319  3319 I art     : Explicit concurrent mark sweep GC freed 17222(1052KB) AllocSpace objects, 4(64KB) LOS objects, 24% free, 16MB/22MB, paused 3.405ms total 157.036ms
,08-30 17:28:11.928  1949  1949 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
,08-30 17:28:11.945  1374  1374 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-30 17:28:12.004  1374  1513 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 17:28:12.004  1374  1513 D KeyguardModel: createShortcutInfo...
08-30 17:28:12.007  1949  1949 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-30 17:28:12.026  1374  1513 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 17:28:12.026  1374  1513 D KeyguardModel: createShortcutInfo...
08-30 17:28:12.027  1949  1949 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-30 17:28:12.027  1949  1949 I Activity: Activity.onPostResume() called 
,08-30 17:28:12.033  1374  1513 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:28:12.036  1374  1513 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 17:28:12.037  1949  1949 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-30 17:28:12.041  1374  1513 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 17:28:12.041  1374  1513 D KeyguardModel: createShortcutInfo...
,08-30 17:28:12.046   963   963 I art     : Explicit concurrent mark sweep GC freed 28535(1841KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 23MB/35MB, paused 11.140ms total 273.610ms
08-30 17:28:12.055   963  1062 I art     : WaitForGcToComplete blocked for 177.480ms for cause Explicit
,08-30 17:28:12.062  1949  6714 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
08-30 17:28:12.065  1374  1513 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-30 17:28:12.065  1374  1513 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 17:28:12.067  1374  1513 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 17:28:12.067  1374  1513 D KeyguardModel: createShortcutInfo...
08-30 17:28:12.067  6695  6695 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:28:12.067  6695  6695 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-30 17:28:12.069  6695  6695 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-30 17:28:12.079  1374  1513 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:28:12.079  1374  1513 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-30 17:28:12.080  1374  1374 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-30 17:28:12.080  1374  1374 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-30 17:28:12.082  1374  1513 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 17:28:12.082  1374  1513 D KeyguardModel: createShortcutInfo...
08-30 17:28:12.084   963  1053 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
08-30 17:28:12.085   963  1053 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-30 17:28:12.085  1374  1374 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-30 17:28:12.086   963  1053 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-30 17:28:12.086   963  1053 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-30 17:28:12.086   963  1053 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-30 17:28:12.086   963  1053 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@12bff207,  pkg=WindowManager.LayoutParams
08-30 17:28:12.086   963  1053 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-30 17:28:12.086  1374  1374 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-30 17:28:12.086  1374  1374 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-30 17:28:12.086  1374  1374 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-30 17:28:12.089   963  1955 D InputDispatcher: Focus entered window: Window{35aed235 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-30 17:28:12.092   295   356 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-30 17:28:12.105  1374  1374 D KeyguardModel: handleShortcutListChanged...
,08-30 17:28:12.122  1374  1513 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-30 17:28:12.122  1374  1513 D KeyguardModel: createShortcutInfo...
08-30 17:28:12.123  1949  1949 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 17:28:12.124  1949  1949 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-30 17:28:12.125  1949  1949 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-30 17:28:12.125  1374  1513 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-30 17:28:12.125  1374  1513 D KeyguardModel: createShortcutInfo...
,08-30 17:28:12.127  1374  1513 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:28:12.127  1374  1513 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-30 17:28:12.129  1374  1513 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-30 17:28:12.129  1374  1513 D KeyguardModel: createShortcutInfo...
08-30 17:28:12.130  1374  1513 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:28:12.130  1374  1513 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-30 17:28:12.132  1374  1513 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-30 17:28:12.132  1374  1513 D KeyguardModel: createShortcutInfo...
08-30 17:28:12.133  1949  1949 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-30 17:28:12.133  1949  1949 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
08-30 17:28:12.133  1374  1513 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-30 17:28:12.134  1374  1513 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-30 17:28:12.134  1949  1949 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-30 17:28:12.135  1374  1513 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-30 17:28:12.135  1374  1513 D KeyguardModel: createShortcutInfo...
08-30 17:28:12.136   963   963 D administrator: Handling package changes for user 0
,08-30 17:28:12.144  1374  1374 D KeyguardModel: handleShortcutListChanged...
08-30 17:28:12.244   963  1642 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-30 17:28:12.247   963  1642 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6595 uid 10030
08-30 17:28:12.306  1949  1949 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-30 17:28:12.307  1636  1636 E b       : Unable to connect to the editor to retrieve text... will retry later
08-30 17:28:12.315  1949  1949 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
08-30 17:28:12.316  1949  1949 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@36fb2bc time:343781
,08-30 17:28:12.332   963  1055 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{129f8898 u0 com.lge.launcher2/.Launcher t258} time:343797
08-30 17:28:12.336   963   963 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-30 17:28:12.337   963   963 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-30 17:28:12.357   963   963 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 17:28:12.373  1949  1949 I art     : Explicit concurrent mark sweep GC freed 4478(266KB) AllocSpace objects, 4(645KB) LOS objects, 40% free, 15MB/25MB, paused 1.525ms total 56.045ms
08-30 17:28:12.375   963  1352 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
08-30 17:28:12.386   963  1062 I art     : Explicit concurrent mark sweep GC freed 10741(1234KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 7.169ms total 317.907ms
,08-30 17:28:12.411  6695  6695 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-30 17:28:12.432  6695  6695 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,08-30 17:28:12.478  6670  6670 D AndroidRuntime: Shutting down VM
,08-30 17:28:12.561   963  1033 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-30 17:28:12.574  1858  1858 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-30 17:28:12.574  1858  1858 D LCardEmulationManager: getDefaultRoute
,08-30 17:28:12.688  6695  6695 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-30 17:28:12.711   963  1033 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-30 17:28:12.729   963  1893 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6721 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-30 17:28:12.731   963  1893 I ActivityManager: Killing 6195:com.lge.eula/1000 (adj 15): empty #11
08-30 17:28:12.815   963  1062 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6743 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-30 17:28:12.816   963  2014 W libprocessgroup: failed to open /acct/uid_1000/pid_6195/cgroup.procs: No such file or directory
08-30 17:28:12.821  1949  1949 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-30 17:28:12.878  6721  6721 I AppUp4:AppBoxCP: onCreate
,08-30 17:28:12.884  6721  6721 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-30 17:28:12.900  6721  6721 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,08-30 17:28:12.901  6721  6721 D AndroidRuntime: Shutting down VM
--------- beginning of crash
08-30 17:28:12.902  6721  6721 E AndroidRuntime: FATAL EXCEPTION: main
08-30 17:28:12.902  6721  6721 E AndroidRuntime: Process: com.lge.appbox.client, PID: 6721
08-30 17:28:12.902  6721  6721 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
08-30 17:28:12.902  6721  6721 E AndroidRuntime: 	... 11 more
08-30 17:28:12.908   963  5923 I ActivityManager: Killing 6223:com.google.android.apps.docs/u0a58 (adj 15): empty #11
08-30 17:28:12.920   963  6761 E DropBoxManagerService: Can't write: system_app_crash
08-30 17:28:12.920   963  6761 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
08-30 17:28:12.920   963  6761 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-30 17:28:12.920   963  6761 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 17:28:12.920   963  6761 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 17:28:12.920   963  6761 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 17:28:12.920   963  6761 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-30 17:28:12.920   963  6761 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12621)
08-30 17:28:12.920   963  6761 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 17:28:12.920   963  6761 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 17:28:12.920   963  6761 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 17:28:12.920   963  6761 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-30 17:28:12.920   963  6761 E DropBoxManagerService: 	... 5 more

```
