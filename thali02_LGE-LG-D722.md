#### Test 797638306af5278_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-12 18:23:38.173   297   354 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-12 18:23:39.709  6872  6872 D AndroidRuntime: 
08-12 18:23:39.709  6872  6872 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-12 18:23:39.720  6872  6872 D AndroidRuntime: CheckJNI is OFF
08-12 18:23:40.094  6872  6872 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 18:23:40.112   975  5548 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 18:23:40.151   975  5548 D ActivityManager: setTaskToReturnTo : TaskRecord{b6edbb4 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 18:23:40.151   975  5548 D ActivityManager: setTaskToReturnTo : TaskRecord{b6edbb4 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 18:23:40.157   975  5548 D WindowStateEx: AppWindowTokenEx init.. 
08-12 18:23:40.202   975  5548 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6891 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-12 18:23:40.203   975  5548 D InputDispatcher: Focus left window: Window{2ee4bb68 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-12 18:23:40.205  6872  6872 D AndroidRuntime: Shutting down VM
08-12 18:23:40.215  1949  1949 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-12 18:23:40.241   975   975 V ActivityManager: Display changed displayId=0
08-12 18:23:40.244  1788  1788 D DSDPConnection: Display #0 changed.
08-12 18:23:40.358  6891  6891 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-12 18:23:40.451  6891  6891 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,08-12 18:23:40.499  6891  6891 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 5740-5741)
,08-12 18:23:40.499  6891  6891 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 18:23:40.528  6891  6891 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2e44ecf3}
,08-12 18:23:40.529  6891  6891 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 18:23:40.530  6891  6891 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 18:23:40.543  6891  6891 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-12 18:23:40.544  6891  6891 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 18:23:40.545  6891  6891 E SysUtils: ApplicationContext is null in ApplicationStatus
08-12 18:23:40.569  6891  6891 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-12 18:23:40.576  6891  6891 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 18:23:40.576  6891  6891 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 18:23:40.576  6891  6891 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-12 18:23:40.576  6891  6891 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-12 18:23:40.576  6891  6891 I Adreno-EGL: Build Date: 03/02/15 Mon
08-12 18:23:40.576  6891  6891 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-12 18:23:40.576  6891  6891 I Adreno-EGL: Remote Branch: 
08-12 18:23:40.576  6891  6891 I Adreno-EGL: Local Patches: 
08-12 18:23:40.576  6891  6891 I Adreno-EGL: Reconstruct Branch: 
08-12 18:23:40.648   286   286 V AudioPolicyService: registerClient() client 0xb3827f60, uid 10030
,08-12 18:23:40.665   975  1051 D BluetoothManagerService: Message: 20
08-12 18:23:40.665   975  1051 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@7f29238:true
,08-12 18:23:40.669  2085  2101 D BluetoothAdapterService(477197353): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3db4af47
08-12 18:23:40.765   975  1045 W ActivityManager: Activity pause timeout for ActivityRecord{65c93dd u0 com.test.thalitest/.MainActivity t259}
,08-12 18:23:40.812  6891  6891 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 18:23:40.825  6891  6891 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-12 18:23:40.832  6891  6891 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-12 18:23:40.837  6891  6891 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-12 18:23:40.837  6891  6891 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-12 18:23:40.853  6891  6891 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-12 18:23:40.862  6891  6891 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 18:23:40.862  6891  6891 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 18:23:40.916  6891  6891 I Activity: Activity.onPostResume() called 
,08-12 18:23:40.925  6891  6943 D OpenGLRenderer: Render dirty regions requested: true
08-12 18:23:40.925  6891  6943 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 18:23:40.931  6891  6943 D OpenGLRenderer: Enabling debug mode 0
,08-12 18:23:40.951  6891  6891 D Atlas   : Validating map...
,08-12 18:23:40.956   975   993 D SplitWindow: check instance of lgWin Window{214af968 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 18:23:40.973  6891  6930 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-12 18:23:40.997   975  1050 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
,08-12 18:23:41.000   975  1050 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-12 18:23:41.001  1371  1371 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-12 18:23:41.002  1371  1371 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-12 18:23:41.002  1371  1371 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-12 18:23:41.002  1371  1371 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-12 18:23:41.003   975  1050 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-12 18:23:41.003   975  1050 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-12 18:23:41.003   975  1050 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-12 18:23:41.004   975  1050 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@16f7d8b0,  pkg=WindowManager.LayoutParams
08-12 18:23:41.004   975  1050 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-12 18:23:41.010   975  1294 D InputDispatcher: Focus entered window: Window{214af968 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 18:23:41.035   975  5548 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-12 18:23:41.050   975  1052 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +785ms (total +889ms)
08-12 18:23:41.050   975  1052 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{65c93dd u0 com.test.thalitest/.MainActivity t259} time:196293
08-12 18:23:41.054  6891  6891 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-12 18:23:41.054  6891  6891 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@33ac5655 time:196297
08-12 18:23:41.102  6891  6891 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-12 18:23:41.107  1623  1623 E b       : Unable to connect to the editor to retrieve text... will retry later
08-12 18:23:41.123  6891  6891 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-12 18:23:41.206  6891  6891 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6891
,08-12 18:23:41.541  6891  6891 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 18:23:41.715  6891  6945 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1631415040
,08-12 18:23:41.736  6891  6945 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 18:23:41.736  6891  6945 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 18:23:41.736  6891  6945 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 18:23:41.736  6891  6945 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 18:23:41.736  6891  6945 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-12 18:23:41.736  6891  6945 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@38c83b09 added. We now have 1 listener(s)
,08-12 18:23:41.744   975  1948 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 18:23:41.749  6891  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,08-12 18:23:41.751  6891  6945 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-12 18:23:41.752  6891  6945 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 18:23:41.753  6891  6945 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 18:23:41.758  6891  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 18:23:41.758  6891  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 18:23:41.758  6891  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 18:23:41.758  6891  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-12 18:23:41.758  6891  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 18:23:41.758  6891  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 18:23:41.758  6891  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 18:23:41.758  6891  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 18:23:41.758  6891  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 18:23:41.758  6891  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 18:23:41.758  6891  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 18:23:41.758  6891  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 18:23:41.758  6891  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 18:23:41.758  6891  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 18:23:41.758  6891  6945 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b55813c added. We now have 1 listener(s)
08-12 18:23:41.759  6891  6945 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 18:23:41.775  6891  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-12 18:23:41.775  6891  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 18:23:41.777  6891  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 18:23:41.777  6891  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 18:23:41.777  6891  6945 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-12 18:23:41.781  6891  6945 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 18:23:41.781   975  1844 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 18:23:41.782  6891  6945 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-12 18:23:41.805  2085  3516 D BluetoothAdapterService(477197353): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3db4af47
,08-12 18:23:41.808  6891  6945 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-12 18:23:41.808  6891  6945 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 18:23:41.808  6891  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 18:23:41.808  6891  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 18:23:41.808  6891  6945 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 18:23:41.808  6891  6945 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 18:23:41.808  6891  6945 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 18:23:41.808  6891  6945 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 18:23:41.808  6891  6945 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 18:23:41.809  6891  6945 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 18:23:41.809  6891  6945 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 18:23:41.811  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 18:23:41.811  6891  6945 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 18:23:41.812  6891  6891 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 18:23:41.852  6891  6891 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 18:23:42.012  6891  6906 I art     : CheckpointMarkThreadRoots callback created = 0xb067d160
,08-12 18:23:42.043  6891  6906 I art     : CheckpointMarkThreadRoots callback created = 0xb067d120
,08-12 18:23:42.590  6891  6951 W jxcore-log: Initializing JXcore engine
,08-12 18:23:42.591  6891  6951 W jxcore-log: JXcore engine is ready
08-12 18:23:42.678  6951  6951 W Thread-809: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5066]" dev="sockfs" ino=5066 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-12 18:23:42.678  6951  6951 W Thread-809: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-12 18:23:42.678  6951  6951 W Thread-809: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7888]" dev="sockfs" ino=7888 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-12 18:23:42.678  6951  6951 W Thread-809: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-12 18:23:42.678  6951  6951 W Thread-809: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-12 18:23:42.678  6951  6951 W Thread-809: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[32208]" dev="sockfs" ino=32208 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-12 18:23:42.722  6891  6951 W jxcore-log: Starting JXcore engine
,08-12 18:23:42.903  6891  6951 W jxcore-log: Platform android
08-12 18:23:42.903  6891  6951 W jxcore-log: 
08-12 18:23:42.903  6891  6951 W jxcore-log: Process ARCH arm
08-12 18:23:42.903  6891  6951 W jxcore-log: 
,08-12 18:23:43.156  6891  6951 I jxcore-log: JXcore Cordova bridge is ready!
08-12 18:23:43.156  6891  6951 I jxcore-log: 
,08-12 18:23:43.157  6891  6951 W jxcore-log: JXcore engine is started
08-12 18:23:43.163  6891  6945 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-12 18:23:43.165  6891  6891 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-12 18:23:43.177   297   354 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-12 18:23:48.182   297   354 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-12 18:23:49.766   975  1007 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-12 18:23:49.766   975  1007 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-12 18:23:49.766   975  1007 D sensors_hal_Time: tsOffsetIs: Apps: 205008621801; DSPS: 6815562; Offset : -2991053633
,08-12 18:23:53.187   297   354 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-12 18:23:58.192   297   354 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-12 18:23:58.872  6891  6951 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 18:23:58.872  6891  6951 I jxcore-log: 
,08-12 18:23:58.876  6891  6951 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 18:23:58.876  6891  6951 I jxcore-log: 
08-12 18:23:58.883  2085  3516 D BluetoothAdapterService(477197353): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3db4af47
08-12 18:23:58.883  6891  6951 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 18:23:58.883  6891  6951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 18:23:58.883  6891  6951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 18:23:58.883  6891  6951 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 18:23:58.883  6891  6951 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 18:23:58.883  6891  6951 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 18:23:58.883  6891  6951 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 18:23:58.883  6891  6951 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 18:23:58.887  2085  3516 D BluetoothAdapterService(477197353): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3db4af47
,08-12 18:23:58.888  6891  6951 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 18:23:58.891  6891  6951 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 18:23:58.891  6891  6951 I jxcore-log: 
08-12 18:23:58.894  6891  6951 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 18:23:58.894  6891  6951 I jxcore-log: 
08-12 18:23:59.419  6891  6951 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-12 18:23:59.419  6891  6951 I jxcore-log: Failed to execute UT.
08-12 18:23:59.419  6891  6951 I jxcore-log: 
,08-12 18:23:59.419  6891  6951 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 18:23:59.419  6891  6951 I jxcore-log: 
,08-12 18:23:59.432  6891  6951 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 18:23:59.432  6891  6951 I jxcore-log: 
08-12 18:23:59.445  6891  6891 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 18:23:59.812  6968  6968 D AndroidRuntime: 
08-12 18:23:59.812  6968  6968 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-12 18:23:59.819  6968  6968 D AndroidRuntime: CheckJNI is OFF
08-12 18:24:00.038  1371  1371 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 18:24:00.039  1371  1371 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 18:24:00.039  1371  1371 I [SystemUI]Clock: called onTimeUpdated()
,08-12 18:24:00.045  1371  1371 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 18:24:00.045  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-12 18:24:00.046  1371  1371 I [SystemUI]DateView: called onTimeUpdated()
08-12 18:24:00.046  1371  1371 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 18:24:00.157  6968  6968 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 18:24:00.218   975  1045 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
,08-12 18:24:00.221   975  1045 I ActivityManager: Killing 6891:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
08-12 18:24:00.272   975  1294 I WindowState: WIN DEATH: Window{214af968 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 18:24:00.282   975  1294 D InputDispatcher: Focus left window: Window{214af968 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 18:24:00.282   975  1294 D InputDispatcher: Window went away: Window{214af968 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 18:24:00.325   975  1059 W PackageSettings: Skipping PackageSetting{8cccdb5 com.example.hello/10317} due to missing metadata
,08-12 18:24:00.342   975  1045 I ActivityManager:   Force finishing activity ActivityRecord{65c93dd u0 com.test.thalitest/.MainActivity t259}
,08-12 18:24:00.391   975  1865 W ActivityManager: Spurious death for ProcessRecord{2797335f 6891:com.test.thalitest/u0a30}, curProc for 6891: null
08-12 18:24:00.393   975  1059 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
,08-12 18:24:00.458  1949  1949 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
,08-12 18:24:00.474  1371  1371 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-12 18:24:00.486  1911  1911 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,08-12 18:24:00.494   975  1287 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-12 18:24:00.499  1757  2406 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-12 18:24:00.524  3668  3668 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-12 18:24:00.524  2034  2034 I art     : Explicit concurrent mark sweep GC freed 2021(87KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 12MB/20MB, paused 2.941ms total 126.428ms
,08-12 18:24:00.532  1949  1949 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
08-12 18:24:00.543   975  1045 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6992 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-12 18:24:00.548  3668  3668 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-12 18:24:00.548  3668  3668 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-12 18:24:00.548  3668  3668 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-12 18:24:00.548  3668  3668 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 18:24:00.548  3668  3668 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 18:24:00.548  3668  3668 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-12 18:24:00.548  3668  3668 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-12 18:24:00.548  3668  3668 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 18:24:00.548  3668  3668 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 18:24:00.548  3668  3668 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-12 18:24:00.548  3668  3668 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-12 18:24:00.601  1371  1371 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-12 18:24:00.605  3431  3431 I art     : Explicit concurrent mark sweep GC freed 4235(234KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 16MB/22MB, paused 3.014ms total 203.743ms
08-12 18:24:00.648  1949  1949 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-12 18:24:00.689  1371  1532 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 18:24:00.689  1371  1532 D KeyguardModel: createShortcutInfo...
08-12 18:24:00.690  1949  1949 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-12 18:24:00.690  1949  1949 I Activity: Activity.onPostResume() called 
08-12 18:24:00.695  1949  1949 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
,08-12 18:24:00.710   975   975 I art     : Explicit concurrent mark sweep GC freed 43530(2MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 23MB/35MB, paused 6.484ms total 273.661ms
,08-12 18:24:00.711   975  1059 I art     : WaitForGcToComplete blocked for 118.350ms for cause Explicit
08-12 18:24:00.714  1371  1371 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-12 18:24:00.714  1371  1371 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-12 18:24:00.726  1949  7010 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
08-12 18:24:00.727   975  1050 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
,08-12 18:24:00.730  1371  1532 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 18:24:00.730  1371  1532 D KeyguardModel: createShortcutInfo...
08-12 18:24:00.731   975  1050 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-12 18:24:00.732   975  1050 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-12 18:24:00.732   975  1050 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-12 18:24:00.732   975  1050 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-12 18:24:00.732   975  1844 D InputDispatcher: Focus entered window: Window{2ee4bb68 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-12 18:24:00.732   975  1050 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@16f7d8b0,  pkg=WindowManager.LayoutParams
08-12 18:24:00.732   975  1050 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-12 18:24:00.732  1371  1371 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-12 18:24:00.733  1371  1532 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 18:24:00.733  1371  1371 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-12 18:24:00.733  1371  1371 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-12 18:24:00.733  1371  1371 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-12 18:24:00.736  1371  1532 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 18:24:00.738  1371  1532 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 18:24:00.738  1371  1532 D KeyguardModel: createShortcutInfo...
,08-12 18:24:00.747  6992  6992 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 18:24:00.747  6992  6992 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 18:24:00.749  6992  6992 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-12 18:24:00.758  1371  1532 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 18:24:00.758  1949  1949 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-12 18:24:00.758  1371  1532 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 18:24:00.758  1949  1949 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 18:24:00.758  1949  1949 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-12 18:24:00.763  1371  1532 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 18:24:00.763  1371  1532 D KeyguardModel: createShortcutInfo...
,08-12 18:24:00.769  1371  1532 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 18:24:00.769  1371  1532 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 18:24:00.771  1371  1532 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 18:24:00.771  1371  1532 D KeyguardModel: createShortcutInfo...
08-12 18:24:00.771  1949  1949 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-12 18:24:00.771  1949  1949 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
08-12 18:24:00.773  1949  1949 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-12 18:24:00.776  1371  1371 D KeyguardModel: handleShortcutListChanged...
08-12 18:24:00.777   975  1377 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-12 18:24:00.780  1371  1532 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 18:24:00.780  1371  1532 D KeyguardModel: createShortcutInfo...
08-12 18:24:00.782  1371  1532 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 18:24:00.782  1371  1532 D KeyguardModel: createShortcutInfo...
08-12 18:24:00.783   975   975 D administrator: Handling package changes for user 0
,08-12 18:24:00.786  1371  1532 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 18:24:00.786  1371  1532 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 18:24:00.788  1371  1532 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 18:24:00.788  1371  1532 D KeyguardModel: createShortcutInfo...
08-12 18:24:00.790  1371  1532 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 18:24:00.790  1371  1532 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 18:24:00.792  1371  1532 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 18:24:00.792  1371  1532 D KeyguardModel: createShortcutInfo...
08-12 18:24:00.794  1371  1532 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 18:24:00.794  1371  1532 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-12 18:24:00.796  1371  1532 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 18:24:00.796  1371  1532 D KeyguardModel: createShortcutInfo...
08-12 18:24:00.803   975  1377 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6891 uid 10030
08-12 18:24:00.813  1371  1371 D KeyguardModel: handleShortcutListChanged...
,08-12 18:24:00.856  1949  1949 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
08-12 18:24:00.856  1623  1623 E b       : Unable to connect to the editor to retrieve text... will retry later
,08-12 18:24:00.867  1949  1949 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
08-12 18:24:00.867  1949  1949 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1c82759 time:216110
08-12 18:24:00.879   975  1052 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{376a0c45 u0 com.lge.launcher2/.Launcher t258} time:216122
,08-12 18:24:00.924  1949  1949 I art     : Explicit concurrent mark sweep GC freed 3988(228KB) AllocSpace objects, 4(645KB) LOS objects, 40% free, 15MB/25MB, paused 1.570ms total 55.421ms
,08-12 18:24:01.048   975   975 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,08-12 18:24:01.050   975   975 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 18:24:01.052   975   975 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-12 18:24:01.059   975  1349 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
,08-12 18:24:01.067  6992  6992 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-12 18:24:01.082   975  1059 I art     : Explicit concurrent mark sweep GC freed 16751(1969KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 4.015ms total 369.847ms
,08-12 18:24:01.119  6992  6992 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,08-12 18:24:01.166  1856  1856 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-12 18:24:01.166  1856  1856 D LCardEmulationManager: getDefaultRoute
,08-12 18:24:01.169   975  1044 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 18:24:01.191  6968  6968 D AndroidRuntime: Shutting down VM
,08-12 18:24:01.224   975  1044 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-12 18:24:01.242   975  1059 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7015 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-12 18:24:01.318  1949  1949 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-12 18:24:01.387   975   993 I ActivityManager: Killing 6569:com.lge.appbox.client/u0a11 (adj 15): empty #11
,08-12 18:24:01.440   975  1899 W libprocessgroup: failed to open /acct/uid_10011/pid_6569/cgroup.procs: No such file or directory
,08-12 18:24:01.461  6992  6992 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-12 18:24:01.509   975   994 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7041 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-12 18:24:01.509   975   994 I ActivityManager: Killing 6525:com.google.android.talk/u0a61 (adj 15): empty #11
,08-12 18:24:01.558   975  1865 W libprocessgroup: failed to open /acct/uid_10061/pid_6525/cgroup.procs: No such file or directory
,08-12 18:24:01.596  7041  7041 I AppUp4:AppBoxCP: onCreate
08-12 18:24:01.596  7041  7041 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-12 18:24:01.609  7041  7041 E SQLiteDatabase: Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-12 18:24:01.609  7041  7041 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-12 18:24:01.609  7041  7041 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
08-12 18:24:01.611  7041  7041 E AndroidRuntime: FATAL EXCEPTION: main
08-12 18:24:01.611  7041  7041 E AndroidRuntime: Process: com.lge.appbox.client, PID: 7041
08-12 18:24:01.611  7041  7041 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
08-12 18:24:01.611  7041  7041 E AndroidRuntime: 	... 11 more
08-12 18:24:01.625   975  7058 E DropBoxManagerService: Can't write: system_app_crash
08-12 18:24:01.625   975  7058 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
08-12 18:24:01.625   975  7058 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-12 18:24:01.625   975  7058 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 18:24:01.625   975  7058 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 18:24:01.625   975  7058 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 18:24:01.625   975  7058 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-12 18:24:01.625   975  7058 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12621)
08-12 18:24:01.625   975  7058 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 18:24:01.625   975  7058 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 18:24:01.625   975  7058 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 18:24:01.625   975  7058 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-12 18:24:01.625   975  7058 E DropBoxManagerService: 	... 5 more

```
