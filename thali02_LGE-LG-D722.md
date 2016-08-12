#### Test 79751015f24a8ad_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-12 17:17:39.209   298   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-12 17:17:43.100  6753  6753 D AndroidRuntime: 
08-12 17:17:43.100  6753  6753 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-12 17:17:43.107  6753  6753 D AndroidRuntime: CheckJNI is OFF
08-12 17:17:43.512  6753  6753 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 17:17:43.542   844  1924 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 17:17:43.587   844  1924 D ActivityManager: setTaskToReturnTo : TaskRecord{2ffe1e0e #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 17:17:43.588   844  1924 D ActivityManager: setTaskToReturnTo : TaskRecord{2ffe1e0e #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 17:17:43.592   844  1924 D WindowStateEx: AppWindowTokenEx init.. 
08-12 17:17:43.646   844  1924 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6767 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-12 17:17:43.648   844  1924 D InputDispatcher: Focus left window: Window{799fd1f u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-12 17:17:43.649  6753  6753 D AndroidRuntime: Shutting down VM
08-12 17:17:43.667  1950  1950 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-12 17:17:43.694   844   844 V ActivityManager: Display changed displayId=0
08-12 17:17:43.695  1792  1792 D DSDPConnection: Display #0 changed.
08-12 17:17:43.837  6767  6767 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-12 17:17:43.942  6767  6767 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-12 17:17:43.995  6767  6767 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 3330-3334)
08-12 17:17:43.996  6767  6767 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 17:17:44.033  6767  6767 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {376fe848}
08-12 17:17:44.034  6767  6767 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 17:17:44.038  6767  6767 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 17:17:44.052  6767  6767 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-12 17:17:44.053  6767  6767 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 17:17:44.054  6767  6767 E SysUtils: ApplicationContext is null in ApplicationStatus
08-12 17:17:44.106  6767  6767 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-12 17:17:44.113  6767  6767 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 17:17:44.113  6767  6767 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 17:17:44.114  6767  6767 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-12 17:17:44.114  6767  6767 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-12 17:17:44.114  6767  6767 I Adreno-EGL: Build Date: 03/02/15 Mon
08-12 17:17:44.114  6767  6767 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-12 17:17:44.114  6767  6767 I Adreno-EGL: Remote Branch: 
08-12 17:17:44.114  6767  6767 I Adreno-EGL: Local Patches: 
08-12 17:17:44.114  6767  6767 I Adreno-EGL: Reconstruct Branch: 
08-12 17:17:44.189   285   285 V AudioPolicyService: registerClient() client 0xb551c6e0, uid 10030
08-12 17:17:44.205   844  1045 D BluetoothManagerService: Message: 20
08-12 17:17:44.206   844  1045 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2bbd2572:true
08-12 17:17:44.213  2085  2103 D BluetoothAdapterService(806202374): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7fdba8c
08-12 17:17:44.214   298   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
08-12 17:17:44.227   844   982 W ActivityManager: Activity pause timeout for ActivityRecord{292f402f u0 com.test.thalitest/.MainActivity t259}
08-12 17:17:44.363  6767  6767 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 17:17:44.379  6767  6767 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-12 17:17:44.386  6767  6767 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-12 17:17:44.390  6767  6767 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-12 17:17:44.390  6767  6767 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-12 17:17:44.409  6767  6767 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-12 17:17:44.419  6767  6767 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 17:17:44.419  6767  6767 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 17:17:44.472  6767  6767 I Activity: Activity.onPostResume() called 
08-12 17:17:44.482  6767  6815 D OpenGLRenderer: Render dirty regions requested: true
08-12 17:17:44.482  6767  6815 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 17:17:44.492  6767  6815 D OpenGLRenderer: Enabling debug mode 0
08-12 17:17:44.506  6767  6767 D Atlas   : Validating map...
08-12 17:17:44.512   844  1349 D SplitWindow: check instance of lgWin Window{12c5cf22 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 17:17:44.530  6767  6801 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-12 17:17:44.559   844  1044 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-12 17:17:44.560   844  1044 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
,08-12 17:17:44.560  1362  1362 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-12 17:17:44.561   844  1044 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-12 17:17:44.561   844  1044 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-12 17:17:44.561   844  1044 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-12 17:17:44.562  1362  1362 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-12 17:17:44.562  1362  1362 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-12 17:17:44.562  1362  1362 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-12 17:17:44.562   844  1044 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3cd18e88,  pkg=WindowManager.LayoutParams
08-12 17:17:44.562   844  1044 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-12 17:17:44.579   844  1907 D InputDispatcher: Focus entered window: Window{12c5cf22 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 17:17:44.611   844  3541 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-12 17:17:44.627   844  1055 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +903ms (total +1s33ms)
08-12 17:17:44.628   844  1055 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{292f402f u0 com.test.thalitest/.MainActivity t259} time:313966
,08-12 17:17:44.634  6767  6767 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-12 17:17:44.634  6767  6767 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d72b442 time:313973
08-12 17:17:44.685  6767  6767 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-12 17:17:44.695  1631  1631 E b       : Unable to connect to the editor to retrieve text... will retry later
08-12 17:17:44.734  6767  6767 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-12 17:17:44.740  6767  6767 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6767
08-12 17:17:44.903  6767  6767 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 17:17:45.299  6767  6817 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1635611904
,08-12 17:17:45.320  6767  6817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 17:17:45.320  6767  6817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 17:17:45.320  6767  6817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 17:17:45.320  6767  6817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 17:17:45.320  6767  6817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-12 17:17:45.320  6767  6817 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1793a566 added. We now have 1 listener(s)
08-12 17:17:45.329   844  1924 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 17:17:45.337  6767  6817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,08-12 17:17:45.340  6767  6817 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-12 17:17:45.341  6767  6817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 17:17:45.342  6767  6817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 17:17:45.355  6767  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 17:17:45.355  6767  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 17:17:45.355  6767  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 17:17:45.355  6767  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-12 17:17:45.355  6767  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 17:17:45.355  6767  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 17:17:45.355  6767  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 17:17:45.355  6767  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 17:17:45.355  6767  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 17:17:45.355  6767  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 17:17:45.355  6767  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 17:17:45.355  6767  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 17:17:45.355  6767  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 17:17:45.355  6767  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 17:17:45.355  6767  6817 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2ad00fd added. We now have 1 listener(s)
08-12 17:17:45.355  6767  6817 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 17:17:45.365  6767  6817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 17:17:45.365  6767  6817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 17:17:45.366  6767  6817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 17:17:45.366  6767  6817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 17:17:45.366  6767  6817 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-12 17:17:45.370  6767  6817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-12 17:17:45.371   844  1956 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 17:17:45.373  6767  6817 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-12 17:17:45.387  2085  2102 D BluetoothAdapterService(806202374): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7fdba8c
,08-12 17:17:45.392  6767  6817 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-12 17:17:45.392  6767  6817 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 17:17:45.392  6767  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 17:17:45.392  6767  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 17:17:45.392  6767  6817 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 17:17:45.392  6767  6817 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 17:17:45.392  6767  6817 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 17:17:45.392  6767  6817 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 17:17:45.392  6767  6817 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 17:17:45.393  6767  6817 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 17:17:45.393  6767  6817 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 17:17:45.395  6767  6767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 17:17:45.397  6767  6767 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 17:17:45.398  6767  6817 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 17:17:45.432  6767  6767 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 17:17:45.543  6767  6786 I art     : CheckpointMarkThreadRoots callback created = 0xb07c00d0
,08-12 17:17:45.587  6767  6786 I art     : CheckpointMarkThreadRoots callback created = 0xb07c00a0
,08-12 17:17:46.498  6767  6823 W jxcore-log: Initializing JXcore engine
,08-12 17:17:46.500  6767  6823 W jxcore-log: JXcore engine is ready
08-12 17:17:46.601  6823  6823 W Thread-814: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5852]" dev="sockfs" ino=5852 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-12 17:17:46.601  6823  6823 W Thread-814: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-12 17:17:46.601  6823  6823 W Thread-814: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6472]" dev="sockfs" ino=6472 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-12 17:17:46.601  6823  6823 W Thread-814: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-12 17:17:46.601  6823  6823 W Thread-814: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-12 17:17:46.601  6823  6823 W Thread-814: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[31973]" dev="sockfs" ino=31973 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-12 17:17:46.659  6767  6823 W jxcore-log: Starting JXcore engine
,08-12 17:17:46.821  6767  6823 W jxcore-log: Platform android
08-12 17:17:46.821  6767  6823 W jxcore-log: 
,08-12 17:17:46.821  6767  6823 W jxcore-log: Process ARCH arm
08-12 17:17:46.821  6767  6823 W jxcore-log: 
08-12 17:17:47.152  6767  6823 I jxcore-log: JXcore Cordova bridge is ready!
08-12 17:17:47.152  6767  6823 I jxcore-log: 
08-12 17:17:47.153  6767  6823 W jxcore-log: JXcore engine is started
,08-12 17:17:47.160  6767  6817 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-12 17:17:47.162  6767  6767 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-12 17:17:48.031   844   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-12 17:17:48.031   844   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-12 17:17:48.031   844   995 D sensors_hal_Time: tsOffsetIs: Apps: 317369016863; DSPS: 10498277; Offset : -3020828667
,08-12 17:17:49.219   298   351 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-12 17:17:54.224   298   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-12 17:17:59.229   298   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-12 17:18:00.048  1362  1362 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 17:18:00.048  1362  1362 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 17:18:00.048  1362  1362 I [SystemUI]Clock: called onTimeUpdated()
,08-12 17:18:00.053  1362  1362 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 17:18:00.053  1362  1362 I [SystemUI]DateView: called onTimeUpdated()
08-12 17:18:00.054  1362  1362 I [SystemUI]DateView: called onTimeUpdated()
08-12 17:18:00.054  1362  1362 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 17:18:04.234   298   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-12 17:18:08.031   844   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-12 17:18:08.031   844   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-12 17:18:08.031   844   995 D sensors_hal_Time: tsOffsetIs: Apps: 337369911855; DSPS: 11153667; Offset : -3020847560
,08-12 17:18:09.238   298   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-12 17:18:12.509  6767  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 17:18:12.509  6767  6823 I jxcore-log: 
,08-12 17:18:12.513  6767  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 17:18:12.513  6767  6823 I jxcore-log: 
08-12 17:18:12.520  2085  2102 D BluetoothAdapterService(806202374): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7fdba8c
08-12 17:18:12.520  6767  6823 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 17:18:12.520  6767  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 17:18:12.520  6767  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 17:18:12.520  6767  6823 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 17:18:12.520  6767  6823 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 17:18:12.520  6767  6823 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 17:18:12.520  6767  6823 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 17:18:12.520  6767  6823 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 17:18:12.527  2085  2102 D BluetoothAdapterService(806202374): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7fdba8c
,08-12 17:18:12.528  6767  6823 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 17:18:12.533  6767  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 17:18:12.533  6767  6823 I jxcore-log: 
08-12 17:18:12.535  6767  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 17:18:12.535  6767  6823 I jxcore-log: 
08-12 17:18:13.086  6767  6823 I jxcore-log: Unit Test app is loaded
08-12 17:18:13.086  6767  6823 I jxcore-log: 
,08-12 17:18:13.101  6767  6823 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 17:18:13.101  6767  6823 I jxcore-log: 
08-12 17:18:13.105  6767  6823 I jxcore-log: My device name is: LGE-LG-D722
08-12 17:18:13.105  6767  6823 I jxcore-log: 
08-12 17:18:13.108  6767  6823 I jxcore-log: WARN testUtils: myNameCallback not set!
08-12 17:18:13.108  6767  6823 I jxcore-log: 
,08-12 17:18:13.114  6767  6767 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-12 17:18:13.126   844  3225 I LocationManagerService: remove 11e5b86a
,08-12 17:18:13.136   844  3225 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-12 17:18:13.136   844  3225 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-12 17:18:13.139   844  3225 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
,08-12 17:18:13.143   844  3225 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-12 17:18:13.143   844  3225 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-12 17:18:14.243   298   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-12 17:18:16.822  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-12 17:18:16.822  6767  6823 I jxcore-log: 
,08-12 17:18:17.808  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-12 17:18:17.808  6767  6823 I jxcore-log: 
,08-12 17:18:17.845  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-12 17:18:17.845  6767  6823 I jxcore-log: 
,08-12 17:18:19.248   298   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-12 17:18:20.026  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-12 17:18:20.026  6767  6823 I jxcore-log: 
,08-12 17:18:20.383  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-12 17:18:20.383  6767  6823 I jxcore-log: 
,08-12 17:18:20.390  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-12 17:18:20.390  6767  6823 I jxcore-log: 
08-12 17:18:20.398  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-12 17:18:20.398  6767  6823 I jxcore-log: 
,08-12 17:18:20.423  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-12 17:18:20.423  6767  6823 I jxcore-log: 
,08-12 17:18:20.429  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-12 17:18:20.429  6767  6823 I jxcore-log: 
08-12 17:18:21.490  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-12 17:18:21.490  6767  6823 I jxcore-log: 
,08-12 17:18:21.513  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-12 17:18:21.513  6767  6823 I jxcore-log: 
,08-12 17:18:21.525  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-12 17:18:21.525  6767  6823 I jxcore-log: 
08-12 17:18:21.535  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-12 17:18:21.535  6767  6823 I jxcore-log: 
,08-12 17:18:21.610  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-12 17:18:21.610  6767  6823 I jxcore-log: 
,08-12 17:18:21.697  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-12 17:18:21.697  6767  6823 I jxcore-log: 
,08-12 17:18:21.708  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-12 17:18:21.708  6767  6823 I jxcore-log: 
08-12 17:18:21.961  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-12 17:18:21.961  6767  6823 I jxcore-log: 
,08-12 17:18:22.002  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-12 17:18:22.002  6767  6823 I jxcore-log: 
,08-12 17:18:22.008  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-12 17:18:22.008  6767  6823 I jxcore-log: 
,08-12 17:18:22.017  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-12 17:18:22.017  6767  6823 I jxcore-log: 
,08-12 17:18:22.045  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-12 17:18:22.045  6767  6823 I jxcore-log: 
,08-12 17:18:22.177  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-12 17:18:22.177  6767  6823 I jxcore-log: 
,08-12 17:18:22.199  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-12 17:18:22.199  6767  6823 I jxcore-log: 
,08-12 17:18:22.244  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-12 17:18:22.244  6767  6823 I jxcore-log: 
,08-12 17:18:22.266  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-12 17:18:22.266  6767  6823 I jxcore-log: 
,08-12 17:18:22.295  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-12 17:18:22.295  6767  6823 I jxcore-log: 
,08-12 17:18:22.349  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-12 17:18:22.349  6767  6823 I jxcore-log: 
,08-12 17:18:22.358  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-12 17:18:22.358  6767  6823 I jxcore-log: 
08-12 17:18:22.672  6767  6823 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-12 17:18:22.672  6767  6823 I jxcore-log: 
,08-12 17:18:22.684  2085  2102 D BluetoothAdapterService(806202374): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@7fdba8c
,08-12 17:18:22.685  6767  6823 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
08-12 17:18:22.692  6767  6823 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-12 17:18:22.692  6767  6823 I jxcore-log: 
,08-12 17:18:23.082  6767  6823 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-12 17:18:23.082  6767  6823 I jxcore-log: 
,08-12 17:18:23.460  6844  6844 D AndroidRuntime: 
08-12 17:18:23.460  6844  6844 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-12 17:18:23.471  6844  6844 D AndroidRuntime: CheckJNI is OFF
08-12 17:18:23.838  6844  6844 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 17:18:23.905   844   982 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
,08-12 17:18:23.908   844   982 I ActivityManager: Killing 6767:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
08-12 17:18:23.968   844  2177 I WindowState: WIN DEATH: Window{12c5cf22 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 17:18:23.992   844  2177 D InputDispatcher: Focus left window: Window{12c5cf22 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 17:18:23.992   844  2177 D InputDispatcher: Window went away: Window{12c5cf22 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 17:18:24.040   844  1060 W PackageSettings: Skipping PackageSetting{39eb2422 com.example.hello/10317} due to missing metadata
,08-12 17:18:24.124   844   982 I ActivityManager:   Force finishing activity ActivityRecord{292f402f u0 com.test.thalitest/.MainActivity t259}
,08-12 17:18:24.150   844  1361 W ActivityManager: Spurious death for ProcessRecord{18a4b621 6767:com.test.thalitest/u0a30}, curProc for 6767: null
,08-12 17:18:24.150   844  1060 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
08-12 17:18:24.154   844  1060 I ActivityManager:   Force finishing activity ActivityRecord{292f402f u0 com.test.thalitest/.MainActivity t259 f}
08-12 17:18:24.157   844  1060 W ActivityManager: Duplicate finish request for ActivityRecord{292f402f u0 com.test.thalitest/.MainActivity t259 f}
,08-12 17:18:24.197  1950  1950 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
,08-12 17:18:24.219  1362  1362 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-12 17:18:24.250   844  1288 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-12 17:18:24.257   298   351 I ThermalEngine: Sensor:pa_therm0:30000 mC
08-12 17:18:24.281  1763  2473 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 17:18:24.282  1913  1913 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
08-12 17:18:24.290  3652  3652 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-12 17:18:24.295   844   982 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6868 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-12 17:18:24.304  1950  1950 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
08-12 17:18:24.309  3652  3652 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-12 17:18:24.309  3652  3652 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-12 17:18:24.309  3652  3652 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-12 17:18:24.309  3652  3652 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 17:18:24.309  3652  3652 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 17:18:24.309  3652  3652 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-12 17:18:24.309  3652  3652 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-12 17:18:24.309  3652  3652 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 17:18:24.309  3652  3652 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 17:18:24.309  3652  3652 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-12 17:18:24.309  3652  3652 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
,08-12 17:18:24.315  2030  2030 I art     : Explicit concurrent mark sweep GC freed 663(38KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/20MB, paused 1.867ms total 152.844ms
08-12 17:18:24.346  1362  1362 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-12 17:18:24.381  1950  1950 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-12 17:18:24.385  1950  1950 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-12 17:18:24.386  1950  1950 I Activity: Activity.onPostResume() called 
08-12 17:18:24.391  1950  1950 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-12 17:18:24.407  1362  1362 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-12 17:18:24.407  1362  1362 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-12 17:18:24.410   844  1044 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
08-12 17:18:24.411   844  1044 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-12 17:18:24.412  1950  6886 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
08-12 17:18:24.412   844  1044 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-12 17:18:24.412   844  1044 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-12 17:18:24.412   844  1044 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-12 17:18:24.412   844  1044 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3cd18e88,  pkg=WindowManager.LayoutParams
08-12 17:18:24.412   844  1044 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-12 17:18:24.413  1362  1362 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-12 17:18:24.413  1362  1362 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-12 17:18:24.413  1362  1362 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-12 17:18:24.413  1362  1362 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-12 17:18:24.420  3406  3406 I art     : Explicit concurrent mark sweep GC freed 3542(172KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 16MB/22MB, paused 2.319ms total 249.450ms
,08-12 17:18:24.425   844  1349 D InputDispatcher: Focus entered window: Window{799fd1f u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-12 17:18:24.436  1362  1493 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 17:18:24.436  1362  1493 D KeyguardModel: createShortcutInfo...
,08-12 17:18:24.441  1362  1493 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 17:18:24.441  1362  1493 D KeyguardModel: createShortcutInfo...
08-12 17:18:24.444  1362  1493 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:18:24.445  1362  1493 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 17:18:24.447  1362  1493 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 17:18:24.447  1362  1493 D KeyguardModel: createShortcutInfo...
08-12 17:18:24.452  1950  1950 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 17:18:24.452  1950  1950 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 17:18:24.453  1950  1950 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
,08-12 17:18:24.456  1362  1493 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:18:24.456  1362  1493 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 17:18:24.458  1362  1493 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 17:18:24.458  1362  1493 D KeyguardModel: createShortcutInfo...
08-12 17:18:24.459  1950  1950 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-12 17:18:24.460  1362  1493 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:18:24.460  1362  1493 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 17:18:24.462  1950  1950 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
08-12 17:18:24.463  1362  1493 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 17:18:24.463  1362  1493 D KeyguardModel: createShortcutInfo...
08-12 17:18:24.463  1950  1950 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-12 17:18:24.470  1362  1362 D KeyguardModel: handleShortcutListChanged...
,08-12 17:18:24.511  1362  1493 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 17:18:24.511  1362  1493 D KeyguardModel: createShortcutInfo...
,08-12 17:18:24.515  1362  1493 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 17:18:24.515  1362  1493 D KeyguardModel: createShortcutInfo...
08-12 17:18:24.517  6868  6868 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 17:18:24.517  6868  6868 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 17:18:24.518  6868  6868 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-12 17:18:24.526  1362  1493 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:18:24.526  1362  1493 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-12 17:18:24.532  1362  1493 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 17:18:24.532  1362  1493 D KeyguardModel: createShortcutInfo...
08-12 17:18:24.535  1362  1493 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:18:24.535  1362  1493 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 17:18:24.536  1362  1493 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 17:18:24.536  1362  1493 D KeyguardModel: createShortcutInfo...
08-12 17:18:24.539  1362  1493 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:18:24.539  1362  1493 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-12 17:18:24.544  1362  1493 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 17:18:24.544  1362  1493 D KeyguardModel: createShortcutInfo...
08-12 17:18:24.550  1362  1362 D KeyguardModel: handleShortcutListChanged...
08-12 17:18:24.555   844   844 I art     : Explicit concurrent mark sweep GC freed 48931(3MB) AllocSpace objects, 13(208KB) LOS objects, 33% free, 23MB/35MB, paused 8.569ms total 370.205ms
,08-12 17:18:24.556   844  1060 I art     : WaitForGcToComplete blocked for 366.248ms for cause Explicit
08-12 17:18:24.613   844   844 D administrator: Handling package changes for user 0
,08-12 17:18:24.638   844   862 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-12 17:18:24.641   844   862 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6767 uid 10030
08-12 17:18:24.694  1950  1950 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-12 17:18:24.698  1631  1631 E b       : Unable to connect to the editor to retrieve text... will retry later
08-12 17:18:24.701  1950  1950 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d7d2777 time:354040
08-12 17:18:24.726   844  1055 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{180a6172 u0 com.lge.launcher2/.Launcher t258} time:354064
,08-12 17:18:24.745  1950  1950 I art     : Explicit concurrent mark sweep GC freed 3900(209KB) AllocSpace objects, 4(645KB) LOS objects, 40% free, 15MB/25MB, paused 1.701ms total 42.748ms
08-12 17:18:24.745  1950  1950 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-12 17:18:24.772   844   844 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
,08-12 17:18:24.772   844   844 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 17:18:24.776   844   844 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-12 17:18:24.786   844  1351 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
,08-12 17:18:24.793  6868  6868 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-12 17:18:24.825  6868  6868 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,08-12 17:18:24.901   844  1060 I art     : Explicit concurrent mark sweep GC freed 9395(587KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.819ms total 344.219ms
,08-12 17:18:24.923  1858  1858 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-12 17:18:24.923  1858  1858 D LCardEmulationManager: getDefaultRoute
,08-12 17:18:24.967  6844  6844 D AndroidRuntime: Shutting down VM
,08-12 17:18:24.967   844   980 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 17:18:25.014   844   980 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-12 17:18:25.018  1950  1950 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-12 17:18:25.042  6868  6868 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-12 17:18:25.088   844  3541 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6894 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-12 17:18:25.088   844  3541 I ActivityManager: Killing 6359:com.google.android.talk/u0a61 (adj 15): empty #11
08-12 17:18:25.166   844  1886 W libprocessgroup: failed to open /acct/uid_10061/pid_6359/cgroup.procs: No such file or directory
,08-12 17:18:25.201  6894  6894 I AppUp4:AppBoxCP: onCreate
,08-12 17:18:25.209  6894  6894 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-12 17:18:25.218  6894  6894 I AppUp4:DB:  setFingerPrint start
08-12 17:18:25.219  6894  6894 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
,08-12 17:18:25.225  6894  6894 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
,08-12 17:18:25.225  6894  6894 I AppUp4:DB:  SDK version = 21
08-12 17:18:25.225  6894  6894 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-12 17:18:25.237   844  1060 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6915 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-12 17:18:25.237  6894  6894 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-12 17:18:25.306  6894  6894 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-12 17:18:25.352   844  1874 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6934 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi

```
