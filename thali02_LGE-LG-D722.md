#### Test 79751015007586f_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-12 22:30:33.575   953   991 D sensors_hal_Time: tsOffsetIs: Apps: 315266229263; DSPS: 10429291; Offset : -3022016792
,08-12 22:30:36.966  7044  7044 D AndroidRuntime: 
08-12 22:30:36.966  7044  7044 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-12 22:30:36.973  7044  7044 D AndroidRuntime: CheckJNI is OFF
08-12 22:30:37.124   296   346 I ThermalEngine: Sensor:pa_therm0:29000 mC
08-12 22:30:37.355  7044  7044 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 22:30:37.376   953  1954 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 22:30:37.426   953  1954 D ActivityManager: setTaskToReturnTo : TaskRecord{d0adad9 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 22:30:37.426   953  1954 D ActivityManager: setTaskToReturnTo : TaskRecord{d0adad9 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 22:30:37.430   953  1954 D WindowStateEx: AppWindowTokenEx init.. 
08-12 22:30:37.479   953  1954 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7063 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-12 22:30:37.480   953  1954 D InputDispatcher: Focus left window: Window{3c56cb4a u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-12 22:30:37.481  7044  7044 D AndroidRuntime: Shutting down VM
08-12 22:30:37.487  1948  1948 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-12 22:30:37.522   953   953 V ActivityManager: Display changed displayId=0
08-12 22:30:37.524  1771  1771 D DSDPConnection: Display #0 changed.
08-12 22:30:37.653  7063  7063 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-12 22:30:37.767  7063  7063 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-12 22:30:37.819  7063  7063 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 9509-9511)
08-12 22:30:37.819  7063  7063 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 22:30:37.845  7063  7063 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {762e598}
08-12 22:30:37.846  7063  7063 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 22:30:37.852  7063  7063 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 22:30:37.870  7063  7063 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-12 22:30:37.872  7063  7063 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 22:30:37.876  7063  7063 E SysUtils: ApplicationContext is null in ApplicationStatus
08-12 22:30:37.902  7063  7063 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-12 22:30:37.908  7063  7063 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 22:30:37.908  7063  7063 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 22:30:37.908  7063  7063 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-12 22:30:37.908  7063  7063 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-12 22:30:37.908  7063  7063 I Adreno-EGL: Build Date: 03/02/15 Mon
08-12 22:30:37.908  7063  7063 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-12 22:30:37.908  7063  7063 I Adreno-EGL: Remote Branch: 
08-12 22:30:37.908  7063  7063 I Adreno-EGL: Local Patches: 
08-12 22:30:37.908  7063  7063 I Adreno-EGL: Reconstruct Branch: 
08-12 22:30:37.977   282   282 V AudioPolicyService: registerClient() client 0xb4027260, uid 10030
08-12 22:30:37.990   953  1054 D BluetoothManagerService: Message: 20
08-12 22:30:37.990   953  1054 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1304584d:true
08-12 22:30:37.992  2081  2100 D BluetoothAdapterService(330936790): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1bef36dc
08-12 22:30:38.047   953  1029 W ActivityManager: Activity pause timeout for ActivityRecord{39237c9e u0 com.test.thalitest/.MainActivity t259}
08-12 22:30:38.191  7063  7063 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 22:30:38.204  7063  7063 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-12 22:30:38.210  7063  7063 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-12 22:30:38.216  7063  7063 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-12 22:30:38.217  7063  7063 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-12 22:30:38.233  7063  7063 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-12 22:30:38.242  7063  7063 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 22:30:38.242  7063  7063 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 22:30:38.301  7063  7063 I Activity: Activity.onPostResume() called 
08-12 22:30:38.310  7063  7116 D OpenGLRenderer: Render dirty regions requested: true
08-12 22:30:38.310  7063  7116 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 22:30:38.318  7063  7116 D OpenGLRenderer: Enabling debug mode 0
08-12 22:30:38.334  7063  7063 D Atlas   : Validating map...
08-12 22:30:38.340   953  2087 D SplitWindow: check instance of lgWin Window{3e8eebd u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 22:30:38.356  7063  7102 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-12 22:30:38.380   953  1053 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
,08-12 22:30:38.382   953  1053 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-12 22:30:38.383  1373  1373 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-12 22:30:38.383  1373  1373 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-12 22:30:38.383  1373  1373 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-12 22:30:38.383  1373  1373 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-12 22:30:38.384   953  1053 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-12 22:30:38.384   953  1053 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-12 22:30:38.384   953  1053 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-12 22:30:38.384   953  1053 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2080edf3,  pkg=WindowManager.LayoutParams
08-12 22:30:38.384   953  1053 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-12 22:30:38.395   953  3647 D InputDispatcher: Focus entered window: Window{3e8eebd u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 22:30:38.435   953  1954 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-12 22:30:38.452   953  1055 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +907ms (total +1s17ms)
08-12 22:30:38.453   953  1055 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{39237c9e u0 com.test.thalitest/.MainActivity t259} time:320144
08-12 22:30:38.458  7063  7063 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-12 22:30:38.458  7063  7063 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@e139b12 time:320150
08-12 22:30:38.505  7063  7063 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-12 22:30:38.510  1624  1624 E b       : Unable to connect to the editor to retrieve text... will retry later
08-12 22:30:38.557  7063  7063 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-12 22:30:38.589  7063  7063 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7063
,08-12 22:30:38.981  7063  7063 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 22:30:39.172  7063  7118 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1635606784
,08-12 22:30:39.192  7063  7118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 22:30:39.192  7063  7118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 22:30:39.192  7063  7118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 22:30:39.192  7063  7118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 22:30:39.192  7063  7118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-12 22:30:39.192  7063  7118 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3d16d336 added. We now have 1 listener(s)
,08-12 22:30:39.202   953  1834 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 22:30:39.204  7063  7118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
08-12 22:30:39.206  7063  7118 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
,08-12 22:30:39.207  7063  7118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 22:30:39.208  7063  7118 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 22:30:39.213  7063  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 22:30:39.213  7063  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 22:30:39.213  7063  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 22:30:39.213  7063  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-12 22:30:39.213  7063  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 22:30:39.213  7063  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 22:30:39.213  7063  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 22:30:39.213  7063  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 22:30:39.213  7063  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 22:30:39.213  7063  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 22:30:39.213  7063  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 22:30:39.213  7063  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 22:30:39.213  7063  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 22:30:39.213  7063  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 22:30:39.214  7063  7118 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ca1250d added. We now have 1 listener(s)
08-12 22:30:39.214  7063  7118 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 22:30:39.237  7063  7118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 22:30:39.237  7063  7118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 22:30:39.238  7063  7118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 22:30:39.238  7063  7118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 22:30:39.238  7063  7118 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-12 22:30:39.245  7063  7118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 22:30:39.245   953  1884 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 22:30:39.246  7063  7118 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-12 22:30:39.255  2081  2101 D BluetoothAdapterService(330936790): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1bef36dc
,08-12 22:30:39.258  7063  7118 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-12 22:30:39.258  7063  7118 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 22:30:39.258  7063  7118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 22:30:39.258  7063  7118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 22:30:39.258  7063  7118 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 22:30:39.258  7063  7118 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 22:30:39.258  7063  7118 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 22:30:39.258  7063  7118 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 22:30:39.258  7063  7118 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 22:30:39.259  7063  7118 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 22:30:39.259  7063  7118 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 22:30:39.261  7063  7063 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 22:30:39.263  7063  7063 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 22:30:39.264  7063  7118 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-12 22:30:39.303  7063  7063 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 22:30:39.421  7063  7078 I art     : CheckpointMarkThreadRoots callback created = 0xb06380c0
,08-12 22:30:39.457  7063  7078 I art     : CheckpointMarkThreadRoots callback created = 0xb0638080
,08-12 22:30:40.365  7063  7124 W jxcore-log: Initializing JXcore engine
,08-12 22:30:40.367  7063  7124 W jxcore-log: JXcore engine is ready
08-12 22:30:40.498  7124  7124 W Thread-839: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7304]" dev="sockfs" ino=7304 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-12 22:30:40.498  7124  7124 W Thread-839: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-12 22:30:40.498  7124  7124 W Thread-839: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7369]" dev="sockfs" ino=7369 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-12 22:30:40.498  7124  7124 W Thread-839: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-12 22:30:40.498  7124  7124 W Thread-839: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-12 22:30:40.498  7124  7124 W Thread-839: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[32880]" dev="sockfs" ino=32880 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-12 22:30:40.536  7063  7124 W jxcore-log: Starting JXcore engine
,08-12 22:30:40.679  7063  7124 W jxcore-log: Platform android
08-12 22:30:40.679  7063  7124 W jxcore-log: 
08-12 22:30:40.679  7063  7124 W jxcore-log: Process ARCH arm
08-12 22:30:40.679  7063  7124 W jxcore-log: 
,08-12 22:30:40.989  7063  7124 I jxcore-log: JXcore Cordova bridge is ready!
08-12 22:30:40.989  7063  7124 I jxcore-log: 
,08-12 22:30:40.990  7063  7124 W jxcore-log: JXcore engine is started
08-12 22:30:40.994  7063  7118 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-12 22:30:40.996  7063  7063 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-12 22:30:42.129   296   346 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-12 22:30:47.134   296   346 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-12 22:30:52.139   296   346 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-12 22:30:55.631   953   991 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-12 22:30:55.631   953   991 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-12 22:30:55.631   953   991 D sensors_hal_Time: tsOffsetIs: Apps: 337323127948; DSPS: 11152045; Offset : -3021820160
,08-12 22:30:57.144   296   346 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-12 22:31:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 22:31:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-12 22:31:00.054  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-12 22:31:00.058  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 22:31:00.061  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-12 22:31:00.075  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
,08-12 22:31:00.078  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 22:31:01.003   953  3203 I LocationManagerService: remove 17fb795c
,08-12 22:31:01.016   953  3203 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-12 22:31:01.017   953  3203 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-12 22:31:01.017   953  3203 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-12 22:31:01.017   953  3203 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-12 22:31:01.018   953  3203 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-12 22:31:02.148   296   346 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-12 22:31:05.982  7063  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 22:31:05.982  7063  7124 I jxcore-log: 
08-12 22:31:05.985  7063  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 22:31:05.985  7063  7124 I jxcore-log: 
,08-12 22:31:05.992  2081  2101 D BluetoothAdapterService(330936790): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1bef36dc
08-12 22:31:05.993  7063  7124 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 22:31:05.993  7063  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 22:31:05.993  7063  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 22:31:05.993  7063  7124 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 22:31:05.993  7063  7124 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 22:31:05.993  7063  7124 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 22:31:05.993  7063  7124 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 22:31:05.993  7063  7124 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 22:31:05.996  2081  2101 D BluetoothAdapterService(330936790): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1bef36dc
08-12 22:31:05.997  7063  7124 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 22:31:06.000  7063  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 22:31:06.000  7063  7124 I jxcore-log: 
,08-12 22:31:06.004  7063  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 22:31:06.004  7063  7124 I jxcore-log: 
08-12 22:31:06.553  7063  7124 I jxcore-log: Unit Test app is loaded
08-12 22:31:06.553  7063  7124 I jxcore-log: 
,08-12 22:31:06.563  7063  7124 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 22:31:06.563  7063  7124 I jxcore-log: 
08-12 22:31:06.568  7063  7124 I jxcore-log: My device name is: LGE-LG-D722
08-12 22:31:06.568  7063  7124 I jxcore-log: 
08-12 22:31:06.570  7063  7124 I jxcore-log: WARN testUtils: myNameCallback not set!
08-12 22:31:06.570  7063  7124 I jxcore-log: 
08-12 22:31:06.575  7063  7063 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-12 22:31:07.153   296   346 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-12 22:31:10.593  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-12 22:31:10.593  7063  7124 I jxcore-log: 
,08-12 22:31:11.575  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-12 22:31:11.575  7063  7124 I jxcore-log: 
,08-12 22:31:11.611  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-12 22:31:11.611  7063  7124 I jxcore-log: 
,08-12 22:31:12.158   296   346 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-12 22:31:13.763  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-12 22:31:13.763  7063  7124 I jxcore-log: 
,08-12 22:31:14.113  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-12 22:31:14.113  7063  7124 I jxcore-log: 
,08-12 22:31:14.121  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-12 22:31:14.121  7063  7124 I jxcore-log: 
08-12 22:31:14.129  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-12 22:31:14.129  7063  7124 I jxcore-log: 
,08-12 22:31:14.153  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-12 22:31:14.153  7063  7124 I jxcore-log: 
,08-12 22:31:14.160  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-12 22:31:14.160  7063  7124 I jxcore-log: 
,08-12 22:31:15.201  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-12 22:31:15.201  7063  7124 I jxcore-log: 
,08-12 22:31:15.223  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-12 22:31:15.223  7063  7124 I jxcore-log: 
,08-12 22:31:15.236  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-12 22:31:15.236  7063  7124 I jxcore-log: 
,08-12 22:31:15.246  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-12 22:31:15.246  7063  7124 I jxcore-log: 
08-12 22:31:15.319  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-12 22:31:15.319  7063  7124 I jxcore-log: 
,08-12 22:31:15.405  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-12 22:31:15.405  7063  7124 I jxcore-log: 
,08-12 22:31:15.416  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-12 22:31:15.416  7063  7124 I jxcore-log: 
,08-12 22:31:15.632   953   991 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-12 22:31:15.632   953   991 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-12 22:31:15.632   953   991 D sensors_hal_Time: tsOffsetIs: Apps: 357323984556; DSPS: 11807434; Offset : -3021848274
,08-12 22:31:15.667  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-12 22:31:15.667  7063  7124 I jxcore-log: 
,08-12 22:31:15.707  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-12 22:31:15.707  7063  7124 I jxcore-log: 
,08-12 22:31:15.714  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-12 22:31:15.714  7063  7124 I jxcore-log: 
,08-12 22:31:15.722  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-12 22:31:15.722  7063  7124 I jxcore-log: 
,08-12 22:31:15.750  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-12 22:31:15.750  7063  7124 I jxcore-log: 
,08-12 22:31:15.880  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-12 22:31:15.880  7063  7124 I jxcore-log: 
,08-12 22:31:15.902  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-12 22:31:15.902  7063  7124 I jxcore-log: 
,08-12 22:31:15.947  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-12 22:31:15.947  7063  7124 I jxcore-log: 
,08-12 22:31:15.969  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-12 22:31:15.969  7063  7124 I jxcore-log: 
,08-12 22:31:15.996  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-12 22:31:15.996  7063  7124 I jxcore-log: 
,08-12 22:31:16.055  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-12 22:31:16.055  7063  7124 I jxcore-log: 
,08-12 22:31:16.063  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-12 22:31:16.063  7063  7124 I jxcore-log: 
,08-12 22:31:16.379  7063  7124 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-12 22:31:16.379  7063  7124 I jxcore-log: 
,08-12 22:31:16.391  2081  2101 D BluetoothAdapterService(330936790): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1bef36dc
,08-12 22:31:16.392  7063  7124 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,08-12 22:31:16.400  7063  7124 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-12 22:31:16.400  7063  7124 I jxcore-log: 
08-12 22:31:16.752  7063  7124 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-12 22:31:16.752  7063  7124 I jxcore-log: 
,08-12 22:31:17.120  7168  7168 D AndroidRuntime: 
08-12 22:31:17.120  7168  7168 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-12 22:31:17.135  7168  7168 D AndroidRuntime: CheckJNI is OFF
,08-12 22:31:17.163   296   346 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-12 22:31:17.481  7168  7168 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 22:31:17.528   953  1029 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
,08-12 22:31:17.530   953  1029 I ActivityManager: Killing 7063:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
08-12 22:31:17.590   953   971 I WindowState: WIN DEATH: Window{3e8eebd u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 22:31:17.599   953   971 D InputDispatcher: Focus left window: Window{3e8eebd u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 22:31:17.599   953   971 D InputDispatcher: Window went away: Window{3e8eebd u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 22:31:17.652   953  1067 W PackageSettings: Skipping PackageSetting{21df92f2 com.example.hello/10317} due to missing metadata
,08-12 22:31:17.656   953  1029 I ActivityManager:   Force finishing activity ActivityRecord{39237c9e u0 com.test.thalitest/.MainActivity t259}
,08-12 22:31:17.708   953  1284 W ActivityManager: Spurious death for ProcessRecord{bd6fe98 7063:com.test.thalitest/u0a30}, curProc for 7063: null
,08-12 22:31:17.716   953  1067 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
,08-12 22:31:17.790  2028  2028 I art     : Explicit concurrent mark sweep GC freed 702(39KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/20MB, paused 4.615ms total 69.712ms
08-12 22:31:17.813  1373  1373 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-12 22:31:17.817  1948  1948 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
,08-12 22:31:17.855   953  1289 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-12 22:31:17.869  1911  1911 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
08-12 22:31:17.886  1948  1948 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
,08-12 22:31:17.895  3705  3705 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-12 22:31:17.897  3705  3705 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-12 22:31:17.897  3705  3705 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-12 22:31:17.897  3705  3705 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-12 22:31:17.897  3705  3705 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 22:31:17.897  3705  3705 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 22:31:17.897  3705  3705 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-12 22:31:17.897  3705  3705 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-12 22:31:17.897  3705  3705 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 22:31:17.897  3705  3705 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 22:31:17.897  3705  3705 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-12 22:31:17.897  3705  3705 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-12 22:31:17.900  5678  5678 I art     : Explicit concurrent mark sweep GC freed 17747(1117KB) AllocSpace objects, 5(80KB) LOS objects, 24% free, 15MB/20MB, paused 1.244ms total 137.901ms
08-12 22:31:17.900   953  1029 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7195 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-12 22:31:17.928  1373  1373 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-12 22:31:17.951  1948  1948 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-12 22:31:17.953  1948  1948 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-12 22:31:17.953  1948  1948 I Activity: Activity.onPostResume() called 
08-12 22:31:17.962  1948  1948 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-12 22:31:17.963  1373  1514 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 22:31:17.963  1373  1514 D KeyguardModel: createShortcutInfo...
08-12 22:31:17.969  1373  1514 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 22:31:17.969  1373  1514 D KeyguardModel: createShortcutInfo...
,08-12 22:31:17.971  1373  1514 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 22:31:17.973  1373  1514 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 22:31:17.976  1373  1514 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 22:31:17.976  1373  1514 D KeyguardModel: createShortcutInfo...
08-12 22:31:17.979  1373  1514 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 22:31:17.979  1373  1514 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 22:31:17.982  1948  7212 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
08-12 22:31:17.988   953  1053 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
08-12 22:31:17.989   953  1053 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-12 22:31:17.989   953  1053 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-12 22:31:17.989   953  1053 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-12 22:31:17.989   953  1053 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-12 22:31:17.989   953  1053 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2080edf3,  pkg=WindowManager.LayoutParams
08-12 22:31:17.989   953  1053 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-12 22:31:17.990  1373  1514 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 22:31:17.994  1373  1514 D KeyguardModel: createShortcutInfo...
,08-12 22:31:18.031  1373  1514 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 22:31:18.031   953  2038 D InputDispatcher: Focus entered window: Window{3c56cb4a u0 com.lge.launcher2/com.lge.launcher2.Launcher}
,08-12 22:31:18.032  1373  1514 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 22:31:18.034  1373  1514 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 22:31:18.034  1373  1514 D KeyguardModel: createShortcutInfo...
08-12 22:31:18.036  1373  1373 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-12 22:31:18.036  1373  1373 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-12 22:31:18.036  1373  1373 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-12 22:31:18.036  1373  1373 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-12 22:31:18.036  1373  1373 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-12 22:31:18.036  1373  1373 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-12 22:31:18.048  1373  1373 D KeyguardModel: handleShortcutListChanged...
,08-12 22:31:18.058  1373  1514 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 22:31:18.058  1373  1514 D KeyguardModel: createShortcutInfo...
08-12 22:31:18.060  7195  7195 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 22:31:18.060  7195  7195 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 22:31:18.061  7195  7195 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-12 22:31:18.066   953   953 I art     : Explicit concurrent mark sweep GC freed 48097(2MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 23MB/35MB, paused 6.308ms total 281.671ms
08-12 22:31:18.067   953  1067 I art     : WaitForGcToComplete blocked for 269.949ms for cause Explicit
08-12 22:31:18.078  1373  1514 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 22:31:18.079  1373  1514 D KeyguardModel: createShortcutInfo...
08-12 22:31:18.081  1373  1514 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 22:31:18.081  1373  1514 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 22:31:18.083  1373  1514 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 22:31:18.083  1373  1514 D KeyguardModel: createShortcutInfo...
,08-12 22:31:18.086  1373  1514 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 22:31:18.086  1373  1514 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 22:31:18.089  1373  1514 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 22:31:18.089  1373  1514 D KeyguardModel: createShortcutInfo...
08-12 22:31:18.103  1373  1514 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 22:31:18.103  1373  1514 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-12 22:31:18.105  1373  1514 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 22:31:18.105  1373  1514 D KeyguardModel: createShortcutInfo...
08-12 22:31:18.115  1373  1373 D KeyguardModel: handleShortcutListChanged...
,08-12 22:31:18.130   953   953 D administrator: Handling package changes for user 0
,08-12 22:31:18.286  7195  7195 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-12 22:31:18.286   953   953 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-12 22:31:18.286   953   953 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-12 22:31:18.288   953   953 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-12 22:31:18.298   953  1351 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
,08-12 22:31:18.322  7195  7195 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,08-12 22:31:18.388   953  1067 I art     : Explicit concurrent mark sweep GC freed 7448(423KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.306ms total 320.380ms
,08-12 22:31:18.389   953  1921 I art     : WaitForGcToComplete blocked for 550.592ms for cause Explicit
,08-12 22:31:18.450   953  1027 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-12 22:31:18.530  7168  7168 D AndroidRuntime: Shutting down VM
,08-12 22:31:18.561   953  1921 I art     : Explicit concurrent mark sweep GC freed 3940(194KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.500ms total 170.995ms
,08-12 22:31:18.562  7195  7195 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-12 22:31:18.565  1741  2409 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-12 22:31:18.568  1842  1842 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-12 22:31:18.568  1842  1842 D LCardEmulationManager: getDefaultRoute
08-12 22:31:18.586  1948  1948 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 22:31:18.586  1948  1948 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 22:31:18.587  1948  1948 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,08-12 22:31:18.594  1948  1948 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-12 22:31:18.598  6704  6704 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-12 22:31:18.599  1948  1948 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
08-12 22:31:18.600  1948  1948 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-12 22:31:18.604   953   971 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-12 22:31:18.610   953   971 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 7063 uid 10030
,08-12 22:31:18.612   953  1027 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-12 22:31:18.637   953  1936 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7218 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,08-12 22:31:18.638   953  1936 I ActivityManager: Killing 6668:com.google.android.talk/u0a61 (adj 15): empty #11
08-12 22:31:18.661   308   308 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 296us total 24.195ms
,08-12 22:31:18.682   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 311us total 21.205ms
,08-12 22:31:18.686  1948  1948 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
08-12 22:31:18.690   953  2038 W libprocessgroup: failed to open /acct/uid_10061/pid_6668/cgroup.procs: No such file or directory
08-12 22:31:18.692  1948  1948 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2888df46 time:360383
08-12 22:31:18.698  1624  1624 E b       : Unable to connect to the editor to retrieve text... will retry later
,08-12 22:31:18.705   308   308 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 293us total 21.830ms
08-12 22:31:18.710   953  1055 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{6cbc42 u0 com.lge.launcher2/.Launcher t258} time:360401
,08-12 22:31:18.745  1948  1948 I art     : Explicit concurrent mark sweep GC freed 4479(267KB) AllocSpace objects, 4(645KB) LOS objects, 40% free, 15MB/25MB, paused 1.476ms total 51.743ms
,08-12 22:31:18.745  1948  1948 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-12 22:31:18.750  1948  1948 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
08-12 22:31:18.795   953  1067 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7235 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-12 22:31:18.864   953  2038 I ActivityManager: Killing 6727:com.android.gallery3d/u0a23 (adj 15): empty #11
,08-12 22:31:18.898   953  3647 W libprocessgroup: failed to open /acct/uid_10023/pid_6727/cgroup.procs: No such file or directory
,08-12 22:31:19.002  7218  7218 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-12 22:31:19.003  7218  7218 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.

```
