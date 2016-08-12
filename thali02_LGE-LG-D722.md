#### Test 7976383092ab77f_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-12 17:40:50.554   292   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-12 17:40:54.274  6773  6773 D AndroidRuntime: 
08-12 17:40:54.274  6773  6773 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-12 17:40:54.285  6773  6773 D AndroidRuntime: CheckJNI is OFF
08-12 17:40:54.679  6773  6773 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 17:40:54.692   834  2011 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 17:40:54.742   834  2011 D ActivityManager: setTaskToReturnTo : TaskRecord{30e98d44 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 17:40:54.742   834  2011 D ActivityManager: setTaskToReturnTo : TaskRecord{30e98d44 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 17:40:54.745   834  2011 D WindowStateEx: AppWindowTokenEx init.. 
08-12 17:40:54.790   834  2011 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6792 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-12 17:40:54.791   834  2011 D InputDispatcher: Focus left window: Window{11620ed0 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-12 17:40:54.792  6773  6773 D AndroidRuntime: Shutting down VM
08-12 17:40:54.809  1948  1948 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-12 17:40:54.838   834   834 V ActivityManager: Display changed displayId=0
08-12 17:40:54.838  1809  1809 D DSDPConnection: Display #0 changed.
08-12 17:40:54.850   834   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-12 17:40:54.850   834   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-12 17:40:54.850   834   981 D sensors_hal_Time: tsOffsetIs: Apps: 193116984148; DSPS: 6419689; Offset : -2799529752
08-12 17:40:54.968  6792  6792 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-12 17:40:55.073  6792  6792 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,08-12 17:40:55.140  6792  6792 I LibraryLoader: Time to load native libraries: 13 ms (timestamps 3393-3406)
08-12 17:40:55.140  6792  6792 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-12 17:40:55.169  6792  6792 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {303ca9ef}
08-12 17:40:55.170  6792  6792 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-12 17:40:55.170  6792  6792 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 17:40:55.185  6792  6792 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-12 17:40:55.185  6792  6792 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 17:40:55.187  6792  6792 E SysUtils: ApplicationContext is null in ApplicationStatus
08-12 17:40:55.209  6792  6792 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-12 17:40:55.214  6792  6792 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 17:40:55.215  6792  6792 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-12 17:40:55.215  6792  6792 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-12 17:40:55.215  6792  6792 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-12 17:40:55.215  6792  6792 I Adreno-EGL: Build Date: 03/02/15 Mon
08-12 17:40:55.215  6792  6792 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-12 17:40:55.215  6792  6792 I Adreno-EGL: Remote Branch: 
08-12 17:40:55.215  6792  6792 I Adreno-EGL: Local Patches: 
08-12 17:40:55.215  6792  6792 I Adreno-EGL: Reconstruct Branch: 
08-12 17:40:55.278   282  1357 V AudioPolicyService: registerClient() client 0xb551cfa0, uid 10030
,08-12 17:40:55.302   834  1026 D BluetoothManagerService: Message: 20
,08-12 17:40:55.303   834  1026 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@15698ec8:true
08-12 17:40:55.311  2077  3463 D BluetoothAdapterService(37064581): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17c31b83
08-12 17:40:55.367   834   973 W ActivityManager: Activity pause timeout for ActivityRecord{3140e2d u0 com.test.thalitest/.MainActivity t259}
,08-12 17:40:55.487  6792  6792 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 17:40:55.509  6792  6792 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-12 17:40:55.517  6792  6792 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-12 17:40:55.525  6792  6792 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-12 17:40:55.525  6792  6792 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-12 17:40:55.544  6792  6792 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-12 17:40:55.553  6792  6792 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 17:40:55.553  6792  6792 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 17:40:55.559   292   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-12 17:40:55.617  6792  6792 I Activity: Activity.onPostResume() called 
,08-12 17:40:55.623  6792  6836 D OpenGLRenderer: Render dirty regions requested: true
08-12 17:40:55.623  6792  6836 I OpenGLRenderer: Initialized EGL, version 1.4
08-12 17:40:55.629  6792  6836 D OpenGLRenderer: Enabling debug mode 0
08-12 17:40:55.654  6792  6792 D Atlas   : Validating map...
,08-12 17:40:55.660   834  1885 D SplitWindow: check instance of lgWin Window{1a0239f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 17:40:55.678  6792  6823 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-12 17:40:55.707   834  1024 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
,08-12 17:40:55.709   834  1024 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-12 17:40:55.710  1372  1372 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-12 17:40:55.710  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-12 17:40:55.710  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-12 17:40:55.710  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-12 17:40:55.712   834  1024 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-12 17:40:55.712   834  1024 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-12 17:40:55.712   834  1024 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-12 17:40:55.712   834  1024 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@205b193d,  pkg=WindowManager.LayoutParams
08-12 17:40:55.712   834  1024 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-12 17:40:55.728   834  1935 D InputDispatcher: Focus entered window: Window{1a0239f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 17:40:55.759   834  2342 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-12 17:40:55.780  6792  6792 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-12 17:40:55.780  6792  6792 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@bb24a71 time:194047
08-12 17:40:55.780   834  1027 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +910ms (total +1s30ms)
08-12 17:40:55.781   834  1027 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3140e2d u0 com.test.thalitest/.MainActivity t259} time:194047
08-12 17:40:55.835  6792  6792 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-12 17:40:55.842  1632  1632 E b       : Unable to connect to the editor to retrieve text... will retry later
08-12 17:40:55.876  6792  6792 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-12 17:40:55.885  6792  6792 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6792
08-12 17:40:56.048  6792  6792 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 17:40:56.432  6792  6838 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1631417600
,08-12 17:40:56.453  6792  6838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 17:40:56.453  6792  6838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 17:40:56.453  6792  6838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 17:40:56.453  6792  6838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 17:40:56.453  6792  6838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-12 17:40:56.453  6792  6838 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@31453465 added. We now have 1 listener(s)
,08-12 17:40:56.462   834  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 17:40:56.468  6792  6838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,08-12 17:40:56.471  6792  6838 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-12 17:40:56.472  6792  6838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-12 17:40:56.473  6792  6838 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 17:40:56.479  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 17:40:56.479  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 17:40:56.479  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 17:40:56.479  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-12 17:40:56.479  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 17:40:56.479  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 17:40:56.479  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 17:40:56.479  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 17:40:56.479  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 17:40:56.479  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 17:40:56.479  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 17:40:56.479  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 17:40:56.479  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 17:40:56.479  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 17:40:56.479  6792  6838 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@24bd5f48 added. We now have 1 listener(s)
08-12 17:40:56.479  6792  6838 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-12 17:40:56.496  6792  6838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 17:40:56.496  6792  6838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 17:40:56.496  6792  6838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 17:40:56.496  6792  6838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 17:40:56.496  6792  6838 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-12 17:40:56.501  6792  6838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 17:40:56.501   834  1934 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 17:40:56.502  6792  6838 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-12 17:40:56.515  2077  2094 D BluetoothAdapterService(37064581): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17c31b83
,08-12 17:40:56.522  6792  6838 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-12 17:40:56.523  6792  6838 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 17:40:56.523  6792  6838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 17:40:56.523  6792  6838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 17:40:56.523  6792  6838 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 17:40:56.523  6792  6838 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 17:40:56.523  6792  6838 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 17:40:56.523  6792  6838 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 17:40:56.523  6792  6838 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 17:40:56.523  6792  6838 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 17:40:56.523  6792  6838 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 17:40:56.524  6792  6838 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 17:40:56.525  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 17:40:56.527  6792  6792 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-12 17:40:56.555  6792  6792 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 17:40:56.719  6792  6806 I art     : CheckpointMarkThreadRoots callback created = 0xb0772f90
,08-12 17:40:56.768  6792  6806 I art     : CheckpointMarkThreadRoots callback created = 0xb0772f50
,08-12 17:40:57.340  6792  6844 W jxcore-log: Initializing JXcore engine
,08-12 17:40:57.341  6792  6844 W jxcore-log: JXcore engine is ready
08-12 17:40:57.443  6844  6844 W Thread-814: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6352]" dev="sockfs" ino=6352 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-12 17:40:57.443  6844  6844 W Thread-814: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-12 17:40:57.443  6844  6844 W Thread-814: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7845]" dev="sockfs" ino=7845 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-12 17:40:57.443  6844  6844 W Thread-814: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-12 17:40:57.443  6844  6844 W Thread-814: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-12 17:40:57.443  6844  6844 W Thread-814: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[32053]" dev="sockfs" ino=32053 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-12 17:40:57.484  6792  6844 W jxcore-log: Starting JXcore engine
,08-12 17:40:57.643  6792  6844 W jxcore-log: Platform android
08-12 17:40:57.643  6792  6844 W jxcore-log: 
,08-12 17:40:57.643  6792  6844 W jxcore-log: Process ARCH arm
08-12 17:40:57.643  6792  6844 W jxcore-log: 
08-12 17:40:57.905  6792  6844 I jxcore-log: JXcore Cordova bridge is ready!
08-12 17:40:57.905  6792  6844 I jxcore-log: 
08-12 17:40:57.906  6792  6844 W jxcore-log: JXcore engine is started
,08-12 17:40:57.914  6792  6838 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-12 17:40:57.916  6792  6792 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-12 17:41:00.055  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-12 17:41:00.055  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
08-12 17:41:00.055  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
08-12 17:41:00.057  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 17:41:00.058  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
,08-12 17:41:00.059  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
08-12 17:41:00.059  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
08-12 17:41:00.563   292   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-12 17:41:02.873   834  1639 I ActivityManager: Process com.google.android.talk (pid 6452) has died
,08-12 17:41:03.927   483   483 D charger_monitor: init target 500000
,08-12 17:41:03.932   483   483 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-12 17:41:03.935  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-12 17:41:03.935  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-12 17:41:03.935  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-12 17:41:03.936  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
08-12 17:41:03.936  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-12 17:41:03.990  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
08-12 17:41:03.990  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-12 17:41:03.990  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
,08-12 17:41:03.994   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-12 17:41:03.994   834  1313 D WifiController: battery changed pluggedType: 2
08-12 17:41:03.994   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-12 17:41:03.995  1873  2046 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-12 17:41:03.995  1873  2046 D LEDHandler: Battery Level Remaining: 100%
08-12 17:41:03.995  1873  2046 D LEDHandler: Battery Temp: 296, mChargingStatus=5, mChargingStop=false
08-12 17:41:03.996  2077  3446 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-12 17:41:03.997  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-12 17:41:03.997  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-12 17:41:03.999  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-12 17:41:04.027  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 297
08-12 17:41:04.027  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-12 17:41:04.027  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 297
,08-12 17:41:04.028  1909  1909 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-12 17:41:04.028  1909  1909 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-12 17:41:04.029  1873  2046 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-12 17:41:04.029  1873  2046 D LEDHandler: Battery Level Remaining: 100%
08-12 17:41:04.029  1873  2046 D LEDHandler: Battery Temp: 297, mChargingStatus=5, mChargingStop=false
08-12 17:41:04.029  2077  3446 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-12 17:41:04.031  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-12 17:41:04.032   834   834 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-12 17:41:04.032   834   834 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-12 17:41:04.032   834  1313 D WifiController: battery changed pluggedType: 2
,08-12 17:41:05.568   292   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-12 17:41:10.573   292   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-12 17:41:13.838  6792  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 17:41:13.838  6792  6844 I jxcore-log: 
,08-12 17:41:13.841  6792  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 17:41:13.841  6792  6844 I jxcore-log: 
08-12 17:41:13.847  2077  2093 D BluetoothAdapterService(37064581): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17c31b83
08-12 17:41:13.848  6792  6844 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 17:41:13.848  6792  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 17:41:13.848  6792  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 17:41:13.848  6792  6844 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 17:41:13.848  6792  6844 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 17:41:13.848  6792  6844 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 17:41:13.848  6792  6844 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 17:41:13.848  6792  6844 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 17:41:13.849  2077  2093 D BluetoothAdapterService(37064581): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@17c31b83
,08-12 17:41:13.852  6792  6844 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 17:41:13.855  6792  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 17:41:13.855  6792  6844 I jxcore-log: 
08-12 17:41:13.857  6792  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 17:41:13.857  6792  6844 I jxcore-log: 
08-12 17:41:14.377  6792  6844 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-12 17:41:14.378  6792  6844 I jxcore-log: Failed to execute UT.
08-12 17:41:14.378  6792  6844 I jxcore-log: 
,08-12 17:41:14.378  6792  6844 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-12 17:41:14.378  6792  6844 I jxcore-log: 
08-12 17:41:14.390  6792  6844 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 17:41:14.390  6792  6844 I jxcore-log: 
,08-12 17:41:14.399  6792  6792 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-12 17:41:14.764  6863  6863 D AndroidRuntime: 
08-12 17:41:14.764  6863  6863 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-12 17:41:14.772  6863  6863 D AndroidRuntime: CheckJNI is OFF
08-12 17:41:14.851   834   981 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-12 17:41:14.851   834   981 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-12 17:41:14.851   834   981 D sensors_hal_Time: tsOffsetIs: Apps: 213117882786; DSPS: 7075079; Offset : -2799545053
,08-12 17:41:15.077  6863  6863 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 17:41:15.129   834   973 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
08-12 17:41:15.130   834   973 I ActivityManager: Killing 6792:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
,08-12 17:41:15.179   834  1891 I WindowState: WIN DEATH: Window{1a0239f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 17:41:15.187   834  1891 D InputDispatcher: Focus left window: Window{1a0239f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 17:41:15.187   834  1891 D InputDispatcher: Window went away: Window{1a0239f8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 17:41:15.238   834   973 I ActivityManager:   Force finishing activity ActivityRecord{3140e2d u0 com.test.thalitest/.MainActivity t259}
,08-12 17:41:15.250   834  1056 W PackageSettings: Skipping PackageSetting{3c1c9236 com.example.hello/10317} due to missing metadata
,08-12 17:41:15.298   834  1855 W ActivityManager: Spurious death for ProcessRecord{276e832f 6792:com.test.thalitest/u0a30}, curProc for 6792: null
,08-12 17:41:15.299   834  1056 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
08-12 17:41:15.301   834  1056 I ActivityManager:   Force finishing activity ActivityRecord{3140e2d u0 com.test.thalitest/.MainActivity t259 f}
08-12 17:41:15.302   834  1056 W ActivityManager: Duplicate finish request for ActivityRecord{3140e2d u0 com.test.thalitest/.MainActivity t259 f}
,08-12 17:41:15.389  2025  2025 I art     : Explicit concurrent mark sweep GC freed 158(18KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/21MB, paused 1.997ms total 81.615ms
08-12 17:41:15.395  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-12 17:41:15.409  1770  2395 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-12 17:41:15.413  1909  1909 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
08-12 17:41:15.415   834  1288 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-12 17:41:15.439  3631  3631 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-12 17:41:15.442  3631  3631 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-12 17:41:15.442  3631  3631 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-12 17:41:15.442  3631  3631 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-12 17:41:15.442  3631  3631 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 17:41:15.443  3631  3631 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 17:41:15.443  3631  3631 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-12 17:41:15.443  3631  3631 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-12 17:41:15.443  3631  3631 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 17:41:15.443  3631  3631 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 17:41:15.443  3631  3631 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-12 17:41:15.443  3631  3631 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-12 17:41:15.466   834   973 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6890 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-12 17:41:15.468  1948  1948 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
08-12 17:41:15.485  3377  3377 I art     : Explicit concurrent mark sweep GC freed 16131(995KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 16MB/21MB, paused 1.066ms total 159.857ms
,08-12 17:41:15.495  1948  1948 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
08-12 17:41:15.515  1372  1372 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-12 17:41:15.555  1372  1501 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 17:41:15.555  1372  1501 D KeyguardModel: createShortcutInfo...
08-12 17:41:15.559  1948  1948 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-12 17:41:15.562  1948  1948 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-12 17:41:15.562  1948  1948 I Activity: Activity.onPostResume() called 
08-12 17:41:15.577   292   356 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-12 17:41:15.597  1372  1501 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
,08-12 17:41:15.597  1372  1501 D KeyguardModel: createShortcutInfo...
,08-12 17:41:15.599  1948  1948 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
,08-12 17:41:15.602  1372  1501 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:41:15.606  1372  1501 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 17:41:15.619  1372  1501 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 17:41:15.619  1372  1372 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-12 17:41:15.619  1372  1501 D KeyguardModel: createShortcutInfo...
08-12 17:41:15.619  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-12 17:41:15.624  1948  6909 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
08-12 17:41:15.626  1372  1501 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:41:15.626  1372  1501 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 17:41:15.628  1372  1501 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 17:41:15.628  1372  1501 D KeyguardModel: createShortcutInfo...
08-12 17:41:15.631   834  1024 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
08-12 17:41:15.632   834  1024 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-12 17:41:15.632  1372  1372 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-12 17:41:15.632  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-12 17:41:15.632  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-12 17:41:15.632  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-12 17:41:15.632   834  1024 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-12 17:41:15.632   834  1024 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-12 17:41:15.632   834  1024 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-12 17:41:15.632   834  1024 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@205b193d,  pkg=WindowManager.LayoutParams
08-12 17:41:15.632   834  1024 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-12 17:41:15.634   834  1381 D InputDispatcher: Focus entered window: Window{11620ed0 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
,08-12 17:41:15.649  6890  6890 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 17:41:15.650  6890  6890 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 17:41:15.651  6890  6890 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-12 17:41:15.652   834   834 I art     : Explicit concurrent mark sweep GC freed 43488(2MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 24MB/36MB, paused 11.804ms total 321.906ms
08-12 17:41:15.653  1948  1948 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 17:41:15.654  1948  1948 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 17:41:15.654  1948  1948 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-12 17:41:15.654   834  1056 I art     : WaitForGcToComplete blocked for 148.527ms for cause Explicit
08-12 17:41:15.674  1372  1501 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:41:15.674  1372  1501 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 17:41:15.674  1948  1948 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-12 17:41:15.675  1948  1948 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,08-12 17:41:15.675  1372  1501 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 17:41:15.675  1372  1501 D KeyguardModel: createShortcutInfo...
08-12 17:41:15.676  1948  1948 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-12 17:41:15.681   834  1935 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-12 17:41:15.691  1372  1372 D KeyguardModel: handleShortcutListChanged...
,08-12 17:41:15.696   834  1935 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6792 uid 10030
08-12 17:41:15.705  1372  1501 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,08-12 17:41:15.705  1372  1501 D KeyguardModel: createShortcutInfo...
08-12 17:41:15.711  1372  1501 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 17:41:15.711  1372  1501 D KeyguardModel: createShortcutInfo...
08-12 17:41:15.713  1372  1501 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:41:15.713  1372  1501 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 17:41:15.722  1372  1501 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 17:41:15.722  1372  1501 D KeyguardModel: createShortcutInfo...
,08-12 17:41:15.726  1372  1501 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:41:15.726  1372  1501 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 17:41:15.729  1372  1501 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 17:41:15.730  1372  1501 D KeyguardModel: createShortcutInfo...
08-12 17:41:15.730   834   834 D administrator: Handling package changes for user 0
08-12 17:41:15.732  1372  1501 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 17:41:15.732  1372  1501 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 17:41:15.734  1372  1501 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 17:41:15.734  1372  1501 D KeyguardModel: createShortcutInfo...
08-12 17:41:15.742  1372  1372 D KeyguardModel: handleShortcutListChanged...
,08-12 17:41:15.757  1948  1948 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-12 17:41:15.758  1632  1632 E b       : Unable to connect to the editor to retrieve text... will retry later
08-12 17:41:15.765  1948  1948 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
08-12 17:41:15.765  1948  1948 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1d078db5 time:214031
08-12 17:41:15.783   834  1027 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{108f7286 u0 com.lge.launcher2/.Launcher t258} time:214050
,08-12 17:41:15.827  1948  1948 I art     : Explicit concurrent mark sweep GC freed 3980(228KB) AllocSpace objects, 4(645KB) LOS objects, 39% free, 15MB/25MB, paused 1.275ms total 61.592ms
,08-12 17:41:15.857   834   834 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-12 17:41:15.858   834   834 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-12 17:41:15.861   834   834 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-12 17:41:15.870   834  1349 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
,08-12 17:41:15.932   834   972 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-12 17:41:15.959   834  1056 I art     : Explicit concurrent mark sweep GC freed 12377(1419KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 2.819ms total 302.597ms
,08-12 17:41:15.965  6890  6890 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-12 17:41:15.986  6890  6890 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,08-12 17:41:16.041  6863  6863 D AndroidRuntime: Shutting down VM
,08-12 17:41:16.051   834   972 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-12 17:41:16.104   834  1056 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6913 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-12 17:41:16.106  1948  1948 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-12 17:41:16.119  1856  1856 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-12 17:41:16.119  1856  1856 D LCardEmulationManager: getDefaultRoute
,08-12 17:41:16.219  6890  6890 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-12 17:41:16.244  6489  6489 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-12 17:41:16.291   834   851 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6933 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
08-12 17:41:16.292   834   851 I ActivityManager: Killing 6512:com.android.gallery3d/u0a23 (adj 15): empty #11
,08-12 17:41:16.314   834  1891 W libprocessgroup: failed to open /acct/uid_10023/pid_6512/cgroup.procs: No such file or directory

```
