#### Test 8091287736177d0_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-11 09:34:51.137  1734  2930 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-11 09:34:53.099  6542  6542 D AndroidRuntime: 
08-11 09:34:53.099  6542  6542 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-11 09:34:53.110  6542  6542 D AndroidRuntime: CheckJNI is OFF
08-11 09:34:53.437  6542  6542 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-11 09:34:53.452   855  2064 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 09:34:53.493   855  2064 D ActivityManager: setTaskToReturnTo : TaskRecord{1ba51d97 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 09:34:53.494   855  2064 D ActivityManager: setTaskToReturnTo : TaskRecord{1ba51d97 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 09:34:53.499   855  2064 D WindowStateEx: AppWindowTokenEx init.. 
08-11 09:34:53.544   855  2064 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6562 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-11 09:34:53.545   855  2064 D InputDispatcher: Focus left window: Window{2bbc5e2e u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-11 09:34:53.546  6542  6542 D AndroidRuntime: Shutting down VM
08-11 09:34:53.556  1878  1878 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-11 09:34:53.581   855   855 V ActivityManager: Display changed displayId=0
08-11 09:34:53.584  1752  1752 D DSDPConnection: Display #0 changed.
08-11 09:34:53.713  6562  6562 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-11 09:34:53.827  6562  6562 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,08-11 09:34:53.884  6562  6562 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 1712-1716)
08-11 09:34:53.884  6562  6562 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-11 09:34:53.917  6562  6562 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3f235c87}
,08-11 09:34:53.918  6562  6562 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 09:34:53.922  6562  6562 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,08-11 09:34:53.937  6562  6562 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-11 09:34:53.940  6562  6562 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 09:34:53.944  6562  6562 E SysUtils: ApplicationContext is null in ApplicationStatus
08-11 09:34:53.990  6562  6562 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-11 09:34:53.996  6562  6562 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 09:34:53.996  6562  6562 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 09:34:53.997  6562  6562 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 09:34:53.997  6562  6562 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 09:34:53.997  6562  6562 I Adreno-EGL: Build Date: 03/02/15 Mon
08-11 09:34:53.997  6562  6562 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-11 09:34:53.997  6562  6562 I Adreno-EGL: Remote Branch: 
08-11 09:34:53.997  6562  6562 I Adreno-EGL: Local Patches: 
08-11 09:34:53.997  6562  6562 I Adreno-EGL: Reconstruct Branch: 
08-11 09:34:54.065   285  1359 V AudioPolicyService: registerClient() client 0xb39b2b60, uid 10030
,08-11 09:34:54.091   855  1021 D BluetoothManagerService: Message: 20
08-11 09:34:54.091   855  1021 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6e8beab:true
,08-11 09:34:54.099  2038  3444 D BluetoothAdapterService(443826141): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7afca9b
08-11 09:34:54.109   855   896 W ActivityManager: Activity pause timeout for ActivityRecord{e1bcb84 u0 com.test.thalitest/.MainActivity t259}
,08-11 09:34:54.239  6562  6562 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-11 09:34:54.254  6562  6562 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-11 09:34:54.262  6562  6562 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-11 09:34:54.265  6562  6562 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-11 09:34:54.265  6562  6562 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-11 09:34:54.281  6562  6562 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-11 09:34:54.291  6562  6562 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 09:34:54.291  6562  6562 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 09:34:54.358  6562  6562 I Activity: Activity.onPostResume() called 
,08-11 09:34:54.364  6562  6605 D OpenGLRenderer: Render dirty regions requested: true
08-11 09:34:54.365  6562  6605 I OpenGLRenderer: Initialized EGL, version 1.4
08-11 09:34:54.373  6562  6605 D OpenGLRenderer: Enabling debug mode 0
,08-11 09:34:54.388  6562  6562 D Atlas   : Validating map...
,08-11 09:34:54.400   855  1877 D SplitWindow: check instance of lgWin Window{317aa89b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 09:34:54.421  6562  6592 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-11 09:34:54.452   855  1020 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
,08-11 09:34:54.455   855  1020 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-11 09:34:54.456  1373  1373 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-11 09:34:54.456  1373  1373 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-11 09:34:54.456  1373  1373 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-11 09:34:54.456  1373  1373 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-11 09:34:54.457   855  1020 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-11 09:34:54.457   855  1020 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-11 09:34:54.457   855  1020 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-11 09:34:54.457   855  1020 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1d4a6e19,  pkg=WindowManager.LayoutParams
08-11 09:34:54.457   855  1020 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-11 09:34:54.468   855   873 D InputDispatcher: Focus entered window: Window{317aa89b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 09:34:54.499   855  1641 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-11 09:34:54.518   855  1022 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +909ms (total +1s17ms)
,08-11 09:34:54.518   855  1022 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{e1bcb84 u0 com.test.thalitest/.MainActivity t259} time:192350
08-11 09:34:54.526  6562  6562 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-11 09:34:54.527  6562  6562 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2846ce49 time:192359
08-11 09:34:54.574  6562  6562 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-11 09:34:54.578  1634  1634 E b       : Unable to connect to the editor to retrieve text... will retry later
,08-11 09:34:54.603  6562  6562 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-11 09:34:54.650  6562  6562 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6562
,08-11 09:34:55.046  6562  6562 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 09:34:55.229  6562  6607 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426129152
,08-11 09:34:55.250  6562  6607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 09:34:55.250  6562  6607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 09:34:55.250  6562  6607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 09:34:55.250  6562  6607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 09:34:55.250  6562  6607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-11 09:34:55.250  6562  6607 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@672f0bd added. We now have 1 listener(s)
,08-11 09:34:55.259   855  1840 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 09:34:55.263  6562  6607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
08-11 09:34:55.264  6562  6607 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
,08-11 09:34:55.266  6562  6607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 09:34:55.267  6562  6607 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 09:34:55.273  6562  6607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 09:34:55.273  6562  6607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 09:34:55.273  6562  6607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 09:34:55.273  6562  6607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-11 09:34:55.273  6562  6607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 09:34:55.273  6562  6607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 09:34:55.273  6562  6607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 09:34:55.273  6562  6607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 09:34:55.273  6562  6607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 09:34:55.273  6562  6607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 09:34:55.273  6562  6607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 09:34:55.273  6562  6607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 09:34:55.273  6562  6607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 09:34:55.273  6562  6607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-11 09:34:55.273  6562  6607 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b5c2980 added. We now have 1 listener(s)
08-11 09:34:55.274  6562  6607 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 09:34:55.286  6562  6607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 09:34:55.286  6562  6607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-11 09:34:55.290  6562  6607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-11 09:34:55.290  6562  6607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-11 09:34:55.291  6562  6607 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-11 09:34:55.297  6562  6607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 09:34:55.298   855  1877 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-11 09:34:55.305  6562  6607 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-11 09:34:55.318  2038  2056 D BluetoothAdapterService(443826141): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7afca9b
,08-11 09:34:55.322  6562  6607 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-11 09:34:55.324  6562  6607 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 09:34:55.324  6562  6607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 09:34:55.324  6562  6607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 09:34:55.324  6562  6607 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 09:34:55.324  6562  6607 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 09:34:55.324  6562  6607 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 09:34:55.324  6562  6607 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 09:34:55.324  6562  6607 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 09:34:55.324  6562  6607 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-11 09:34:55.324  6562  6607 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 09:34:55.326  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 09:34:55.328  6562  6562 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 09:34:55.329  6562  6607 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-11 09:34:55.362  6562  6562 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 09:34:55.512  6562  6577 I art     : CheckpointMarkThreadRoots callback created = 0xb064c030
,08-11 09:34:55.561  6562  6577 I art     : CheckpointMarkThreadRoots callback created = 0xb067bfc0
,08-11 09:34:55.634   297   350 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-11 09:34:56.081  6562  6622 W jxcore-log: Initializing JXcore engine
,08-11 09:34:56.083  6562  6622 W jxcore-log: JXcore engine is ready
08-11 09:34:56.186  6622  6622 W Thread-779: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6680]" dev="sockfs" ino=6680 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-11 09:34:56.186  6622  6622 W Thread-779: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-11 09:34:56.186  6622  6622 W Thread-779: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7383]" dev="sockfs" ino=7383 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-11 09:34:56.186  6622  6622 W Thread-779: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-11 09:34:56.186  6622  6622 W Thread-779: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-11 09:34:56.186  6622  6622 W Thread-779: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[30294]" dev="sockfs" ino=30294 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-11 09:34:56.212  6562  6622 W jxcore-log: Starting JXcore engine
,08-11 09:34:56.267  6562  6577 I art     : Background sticky concurrent mark sweep GC freed 42801(2MB) AllocSpace objects, 9(2MB) LOS objects, 31% free, 12MB/18MB, paused 8.106ms total 56.610ms
,08-11 09:34:56.423  6562  6622 W jxcore-log: Platform android
08-11 09:34:56.423  6562  6622 W jxcore-log: 
08-11 09:34:56.424  6562  6622 W jxcore-log: Process ARCH arm
08-11 09:34:56.424  6562  6622 W jxcore-log: 
,08-11 09:34:56.667  6562  6622 I jxcore-log: JXcore Cordova bridge is ready!
08-11 09:34:56.667  6562  6622 I jxcore-log: 
08-11 09:34:56.667  6562  6622 W jxcore-log: JXcore engine is started
,08-11 09:34:56.671  6562  6607 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-11 09:34:56.673  6562  6562 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-11 09:35:00.047  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-11 09:35:00.047  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-11 09:35:00.047  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
08-11 09:35:00.050  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-11 09:35:00.050  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-11 09:35:00.051  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-11 09:35:00.052  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-11 09:35:00.638   297   350 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-11 09:35:05.643   297   350 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-11 09:35:06.728   855  1028 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-11 09:35:06.728   855  1028 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-11 09:35:06.728   855  1028 D sensors_hal_Time: tsOffsetIs: Apps: 204559409822; DSPS: 6801575; Offset : -3012312367
,08-11 09:35:10.648   297   350 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-11 09:35:12.424  6562  6622 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 09:35:12.424  6562  6622 I jxcore-log: 
,08-11 09:35:12.428  6562  6622 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 09:35:12.428  6562  6622 I jxcore-log: 
08-11 09:35:12.434  2038  2056 D BluetoothAdapterService(443826141): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7afca9b
08-11 09:35:12.435  6562  6622 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 09:35:12.435  6562  6622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 09:35:12.435  6562  6622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 09:35:12.435  6562  6622 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 09:35:12.435  6562  6622 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 09:35:12.435  6562  6622 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 09:35:12.435  6562  6622 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 09:35:12.435  6562  6622 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 09:35:12.437  2038  2056 D BluetoothAdapterService(443826141): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7afca9b
08-11 09:35:12.438  6562  6622 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 09:35:12.440  6562  6622 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 09:35:12.440  6562  6622 I jxcore-log: 
08-11 09:35:12.443  6562  6622 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 09:35:12.443  6562  6622 I jxcore-log: 
08-11 09:35:12.972  6562  6622 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-11 09:35:12.972  6562  6622 I jxcore-log: Failed to execute UT.
08-11 09:35:12.972  6562  6622 I jxcore-log: 
,08-11 09:35:12.972  6562  6622 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-11 09:35:12.972  6562  6622 I jxcore-log: 
08-11 09:35:12.984  6562  6622 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 09:35:12.984  6562  6622 I jxcore-log: 
08-11 09:35:12.999  6562  6562 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-11 09:35:13.371  6653  6653 D AndroidRuntime: 
08-11 09:35:13.371  6653  6653 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-11 09:35:13.379  6653  6653 D AndroidRuntime: CheckJNI is OFF
08-11 09:35:13.704  6653  6653 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-11 09:35:13.758   855   896 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
,08-11 09:35:13.761   855   896 I ActivityManager: Killing 6562:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
08-11 09:35:13.806   855  1641 I WindowState: WIN DEATH: Window{317aa89b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 09:35:13.817   855  1641 D InputDispatcher: Focus left window: Window{317aa89b u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 09:35:13.817   855  1641 D InputDispatcher: Window went away: Window{317aa89b u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 09:35:13.879   855  1063 W PackageSettings: Skipping PackageSetting{1479c7a9 com.example.hello/10317} due to missing metadata
,08-11 09:35:13.879   855   896 I ActivityManager:   Force finishing activity ActivityRecord{e1bcb84 u0 com.test.thalitest/.MainActivity t259}
,08-11 09:35:13.941   855  1819 W ActivityManager: Spurious death for ProcessRecord{2915f94e 6562:com.test.thalitest/u0a30}, curProc for 6562: null
08-11 09:35:13.942   855  1063 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
,08-11 09:35:13.949   855  1063 I ActivityManager:   Force finishing activity ActivityRecord{e1bcb84 u0 com.test.thalitest/.MainActivity t259 f}
08-11 09:35:13.949   855  1063 W ActivityManager: Duplicate finish request for ActivityRecord{e1bcb84 u0 com.test.thalitest/.MainActivity t259 f}
,08-11 09:35:14.024  1966  1966 I art     : Explicit concurrent mark sweep GC freed 538(32KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 12MB/20MB, paused 1.861ms total 71.236ms
,08-11 09:35:14.042  1878  1878 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
,08-11 09:35:14.056  1373  1373 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-11 09:35:14.067  1841  1841 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,08-11 09:35:14.091   855  1289 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-11 09:35:14.096  1734  2496 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-11 09:35:14.100  3635  3635 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-11 09:35:14.103  3635  3635 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-11 09:35:14.104  3635  3635 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
,08-11 09:35:14.104  3635  3635 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-11 09:35:14.105  3635  3635 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 09:35:14.105  3635  3635 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 09:35:14.105  3635  3635 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 09:35:14.105  3635  3635 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-11 09:35:14.105  3635  3635 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 09:35:14.105  3635  3635 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 09:35:14.105  3635  3635 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-11 09:35:14.105  3635  3635 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-11 09:35:14.114  1878  1878 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
08-11 09:35:14.120   855   896 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6678 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-11 09:35:14.152  3420  3420 I art     : Explicit concurrent mark sweep GC freed 17303(1066KB) AllocSpace objects, 6(96KB) LOS objects, 24% free, 16MB/22MB, paused 1.076ms total 192.989ms
,08-11 09:35:14.179  1373  1373 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-11 09:35:14.200  1878  1878 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-11 09:35:14.202  1878  1878 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-11 09:35:14.202  1878  1878 I Activity: Activity.onPostResume() called 
,08-11 09:35:14.210  1373  1512 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-11 09:35:14.210  1373  1512 D KeyguardModel: createShortcutInfo...
08-11 09:35:14.214  1373  1512 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 09:35:14.214  1373  1512 D KeyguardModel: createShortcutInfo...
08-11 09:35:14.214  1878  1878 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
,08-11 09:35:14.230  1373  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 09:35:14.230  1373  1512 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-11 09:35:14.234  1373  1512 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-11 09:35:14.234  1373  1512 D KeyguardModel: createShortcutInfo...
,08-11 09:35:14.236  1373  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 09:35:14.236  1373  1512 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-11 09:35:14.238  1373  1512 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 09:35:14.238  1373  1512 D KeyguardModel: createShortcutInfo...
08-11 09:35:14.243  1878  6698 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
08-11 09:35:14.245   855  1020 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
08-11 09:35:14.245  1373  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-11 09:35:14.245  1373  1512 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-11 09:35:14.245   855  1020 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-11 09:35:14.246   855  1020 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-11 09:35:14.246   855  1020 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
,08-11 09:35:14.246   855  1020 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-11 09:35:14.246   855  1020 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1d4a6e19,  pkg=WindowManager.LayoutParams
08-11 09:35:14.246   855  1020 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-11 09:35:14.247  1373  1512 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 09:35:14.247  1373  1512 D KeyguardModel: createShortcutInfo...
,08-11 09:35:14.276   855  1641 D InputDispatcher: Focus entered window: Window{2bbc5e2e u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-11 09:35:14.302  1878  1878 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-11 09:35:14.303  1373  1373 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-11 09:35:14.303  1373  1373 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-11 09:35:14.304  1373  1373 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-11 09:35:14.304  1373  1373 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-11 09:35:14.304  1373  1373 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-11 09:35:14.304  1373  1373 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-11 09:35:14.304  1878  1878 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-11 09:35:14.305  1878  1878 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-11 09:35:14.306  1373  1373 D KeyguardModel: handleShortcutListChanged...
08-11 09:35:14.307   855   855 I art     : Explicit concurrent mark sweep GC freed 49073(2MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 23MB/35MB, paused 21.520ms total 328.356ms
08-11 09:35:14.308   855  1063 I art     : WaitForGcToComplete blocked for 145.529ms for cause Explicit
08-11 09:35:14.314  1878  1878 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-11 09:35:14.315  1878  1878 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,08-11 09:35:14.320  1878  1878 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-11 09:35:14.323   855   874 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-11 09:35:14.326   855   874 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6562 uid 10030
,08-11 09:35:14.334  1373  1512 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-11 09:35:14.334  1373  1512 D KeyguardModel: createShortcutInfo...
08-11 09:35:14.342  1373  1512 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 09:35:14.342  1373  1512 D KeyguardModel: createShortcutInfo...
,08-11 09:35:14.344  1373  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 09:35:14.345  1373  1512 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-11 09:35:14.348  1373  1512 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-11 09:35:14.349  1373  1512 D KeyguardModel: createShortcutInfo...
08-11 09:35:14.350  1373  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 09:35:14.350  1373  1512 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-11 09:35:14.360  1373  1512 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 09:35:14.360  1373  1512 D KeyguardModel: createShortcutInfo...
08-11 09:35:14.361  1373  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 09:35:14.362  1373  1512 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-11 09:35:14.365  1373  1512 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 09:35:14.365  1373  1512 D KeyguardModel: createShortcutInfo...
08-11 09:35:14.383  1373  1373 D KeyguardModel: handleShortcutListChanged...
,08-11 09:35:14.389  1878  1878 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
08-11 09:35:14.392  1634  1634 E b       : Unable to connect to the editor to retrieve text... will retry later
08-11 09:35:14.395  6678  6678 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 09:35:14.395  6678  6678 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 09:35:14.399  1878  1878 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
08-11 09:35:14.399  1878  1878 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@19e91c0d time:212231
08-11 09:35:14.400  6678  6678 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-11 09:35:14.407   855   855 D administrator: Handling package changes for user 0
08-11 09:35:14.420   855  1022 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3be3a0e8 u0 com.lge.launcher2/.Launcher t258} time:212252
,08-11 09:35:14.457  1878  1878 I art     : Explicit concurrent mark sweep GC freed 4451(265KB) AllocSpace objects, 4(645KB) LOS objects, 40% free, 15MB/25MB, paused 2.631ms total 53.664ms
,08-11 09:35:14.630   855   855 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-11 09:35:14.631   855   855 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-11 09:35:14.632   855   855 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-11 09:35:14.633   855  1063 I art     : Explicit concurrent mark sweep GC freed 12815(1618KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 3.124ms total 323.833ms
08-11 09:35:14.641   855  1349 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
08-11 09:35:14.654  6678  6678 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-11 09:35:14.673  6678  6678 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,08-11 09:35:14.703  1787  1787 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-11 09:35:14.703  1787  1787 D LCardEmulationManager: getDefaultRoute
,08-11 09:35:14.710  6653  6653 D AndroidRuntime: Shutting down VM
08-11 09:35:14.719   855   894 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-11 09:35:14.762   855  1063 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6701 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-11 09:35:14.849   855  2064 I ActivityManager: Killing 6185:com.lge.eula/1000 (adj 15): empty #11
,08-11 09:35:14.850   855   894 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-11 09:35:14.889  1878  1878 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-11 09:35:14.889   855  1877 W libprocessgroup: failed to open /acct/uid_1000/pid_6185/cgroup.procs: No such file or directory
,08-11 09:35:14.942  6678  6678 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-11 09:35:14.986   855  1347 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6724 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-11 09:35:14.987   855  1347 I ActivityManager: Killing 6266:com.google.android.apps.docs/u0a58 (adj 15): empty #11
,08-11 09:35:15.009   308   308 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 290us total 20.965ms
,08-11 09:35:15.030   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 301us total 21.100ms
,08-11 09:35:15.052   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 273us total 21.022ms
,08-11 09:35:15.068   855  2177 W libprocessgroup: failed to open /acct/uid_10058/pid_6266/cgroup.procs: No such file or directory
,08-11 09:35:15.104  6724  6724 I AppUp4:AppBoxCP: onCreate
,08-11 09:35:15.107  6724  6724 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-11 09:35:15.114  6724  6724 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-11 09:35:15.114  6724  6724 D AndroidRuntime: Shutting down VM
--------- beginning of crash
08-11 09:35:15.115  6724  6724 E AndroidRuntime: FATAL EXCEPTION: main
08-11 09:35:15.115  6724  6724 E AndroidRuntime: Process: com.l,ge.appbox.client, PID: 6724
08-11 09:35:15.115  6724  6724 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
08-11 09:35:15.115  6724  6724 E AndroidRuntime: 	... 11 more
08-11 09:35:15.131   855  6745 E DropBoxManagerService: Can't write: system_app_crash
08-11 09:35:15.131   855  6745 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
08-11 09:35:15.131   855  6745 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-11 09:35:15.131   855  6745 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 09:35:15.131   855  6745 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 09:35:15.131   855  6745 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 09:35:15.131   855  6745 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-11 09:35:15.131   855  6745 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12621)
08-11 09:35:15.131   855  6745 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 09:35:15.131   855  6745 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 09:35:15.131   855  6745 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 09:35:15.131   855  6745 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-11 09:35:15.131   855  6745 E DropBoxManagerService: 	... 5 more

```
