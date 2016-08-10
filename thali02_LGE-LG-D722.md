#### Test 797638305e9d4c1_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-10 15:48:03.685   298   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-10 15:48:04.860  6944  6944 D AndroidRuntime: 
08-10 15:48:04.860  6944  6944 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-10 15:48:04.869  6944  6944 D AndroidRuntime: CheckJNI is OFF
08-10 15:48:05.193  6944  6944 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-10 15:48:05.209   932  1868 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-10 15:48:05.251   932  1868 D ActivityManager: setTaskToReturnTo : TaskRecord{31eef36d #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-10 15:48:05.251   932  1868 D ActivityManager: setTaskToReturnTo : TaskRecord{31eef36d #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-10 15:48:05.254   932  1868 D WindowStateEx: AppWindowTokenEx init.. 
08-10 15:48:05.304   932  1868 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6964 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-10 15:48:05.306   932  1868 D InputDispatcher: Focus left window: Window{d113da2 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-10 15:48:05.306  6944  6944 D AndroidRuntime: Shutting down VM
08-10 15:48:05.322  1877  1877 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-10 15:48:05.350   932   932 V ActivityManager: Display changed displayId=0
08-10 15:48:05.352  1751  1751 D DSDPConnection: Display #0 changed.
08-10 15:48:05.477  6964  6964 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-10 15:48:05.583  6964  6964 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-10 15:48:05.638  6964  6964 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 5528-5532)
08-10 15:48:05.638  6964  6964 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 15:48:05.671  6964  6964 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {1e4ab77b}
08-10 15:48:05.672  6964  6964 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-10 15:48:05.673  6964  6964 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-10 15:48:05.689  6964  6964 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-10 15:48:05.692  6964  6964 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 15:48:05.693  6964  6964 E SysUtils: ApplicationContext is null in ApplicationStatus
08-10 15:48:05.743  6964  6964 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-10 15:48:05.750  6964  6964 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 15:48:05.750  6964  6964 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-10 15:48:05.752  6964  6964 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-10 15:48:05.752  6964  6964 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-10 15:48:05.752  6964  6964 I Adreno-EGL: Build Date: 03/02/15 Mon
08-10 15:48:05.752  6964  6964 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-10 15:48:05.752  6964  6964 I Adreno-EGL: Remote Branch: 
08-10 15:48:05.752  6964  6964 I Adreno-EGL: Local Patches: 
08-10 15:48:05.752  6964  6964 I Adreno-EGL: Reconstruct Branch: 
08-10 15:48:05.819   284  1355 V AudioPolicyService: registerClient() client 0xb57e7580, uid 10030
08-10 15:48:05.826   932  1030 D BluetoothManagerService: Message: 20
08-10 15:48:05.827   932  1030 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2cc4cca1:true
08-10 15:48:05.840  2028  3562 D BluetoothAdapterService(79123953): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1de1f34f
08-10 15:48:05.875   932  1007 W ActivityManager: Activity pause timeout for ActivityRecord{4370ba2 u0 com.test.thalitest/.MainActivity t259}
08-10 15:48:05.979  6964  6964 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 15:48:05.990  6964  6964 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-10 15:48:05.997  6964  6964 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-10 15:48:06.001  6964  6964 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-10 15:48:06.001  6964  6964 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-10 15:48:06.023  6964  6964 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-10 15:48:06.031  6964  6964 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 15:48:06.031  6964  6964 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-10 15:48:06.077  6964  6964 I Activity: Activity.onPostResume() called 
08-10 15:48:06.082  6964  7014 D OpenGLRenderer: Render dirty regions requested: true
08-10 15:48:06.082  6964  7014 I OpenGLRenderer: Initialized EGL, version 1.4
08-10 15:48:06.094  6964  7014 D OpenGLRenderer: Enabling debug mode 0
08-10 15:48:06.109  6964  6964 D Atlas   : Validating map...
08-10 15:48:06.114   932  2193 D SplitWindow: check instance of lgWin Window{2ae92011 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-10 15:48:06.130  6964  7001 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-10 15:48:06.153   932  1029 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-10 15:48:06.155   932  1029 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-10 15:48:06.155  1372  1372 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-10 15:48:06.155  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-10 15:48:06.155  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-10 15:48:06.155  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-10 15:48:06.157   932  1029 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-10 15:48:06.157   932  1029 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-10 15:48:06.157   932  1029 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-10 15:48:06.157   932  1029 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@29f9dcae,  pkg=WindowManager.LayoutParams
08-10 15:48:06.157   932  1029 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-10 15:48:06.161   932   951 D InputDispatcher: Focus entered window: Window{2ae92011 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-10 15:48:06.198   932  1830 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-10 15:48:06.218   932  1031 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +845ms (total +960ms)
08-10 15:48:06.218   932  1031 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{4370ba2 u0 com.test.thalitest/.MainActivity t259} time:196113
08-10 15:48:06.224  6964  6964 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-10 15:48:06.225  6964  6964 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@33c0ae9d time:196119
08-10 15:48:06.266  6964  6964 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
08-10 15:48:06.269  1629  1629 E b       : Unable to connect to the editor to retrieve text... will retry later
08-10 15:48:06.288  6964  6964 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-10 15:48:06.345  6964  6964 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6964
,08-10 15:48:06.485  6964  6964 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-10 15:48:06.826  6964  7016 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426142464
,08-10 15:48:06.843  6964  7016 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-10 15:48:06.843  6964  7016 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-10 15:48:06.843  6964  7016 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-10 15:48:06.843  6964  7016 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-10 15:48:06.843  6964  7016 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-10 15:48:06.843  6964  7016 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2392a0d1 added. We now have 1 listener(s)
08-10 15:48:06.850   932  2193 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 15:48:06.855  6964  7016 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
08-10 15:48:06.856  6964  7016 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-10 15:48:06.857  6964  7016 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-10 15:48:06.857  6964  7016 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-10 15:48:06.863  6964  7016 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-10 15:48:06.863  6964  7016 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-10 15:48:06.863  6964  7016 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-10 15:48:06.863  6964  7016 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-10 15:48:06.863  6964  7016 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-10 15:48:06.863  6964  7016 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-10 15:48:06.863  6964  7016 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-10 15:48:06.863  6964  7016 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-10 15:48:06.863  6964  7016 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-10 15:48:06.863  6964  7016 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-10 15:48:06.863  6964  7016 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-10 15:48:06.863  6964  7016 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-10 15:48:06.863  6964  7016 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-10 15:48:06.863  6964  7016 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-10 15:48:06.863  6964  7016 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1d657a4 added. We now have 1 listener(s)
08-10 15:48:06.864  6964  7016 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-10 15:48:06.878  6964  7016 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-10 15:48:06.878  6964  7016 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-10 15:48:06.882  6964  7016 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-10 15:48:06.883  6964  7016 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-10 15:48:06.883  6964  7016 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-10 15:48:06.890  6964  7016 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-10 15:48:06.891   932  1830 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-10 15:48:06.894  6964  7016 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-10 15:48:06.904  2028  2057 D BluetoothAdapterService(79123953): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1de1f34f
,08-10 15:48:06.911  6964  7016 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-10 15:48:06.913  6964  7016 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 15:48:06.913  6964  7016 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:48:06.913  6964  7016 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 15:48:06.913  6964  7016 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 15:48:06.913  6964  7016 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 15:48:06.913  6964  7016 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 15:48:06.913  6964  7016 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 15:48:06.913  6964  7016 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 15:48:06.914  6964  7016 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-10 15:48:06.914  6964  7016 D io.jxcore.node.ConnectivityMonitor: start: OK
08-10 15:48:06.916  6964  6964 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-10 15:48:06.918  6964  6964 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-10 15:48:06.920  6964  7016 I io.jxcore.node.LifeCycleMonitor: start: OK
08-10 15:48:06.958  6964  6964 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-10 15:48:07.111  6964  6978 I art     : CheckpointMarkThreadRoots callback created = 0xb07d83e0
,08-10 15:48:07.153  6964  6978 I art     : CheckpointMarkThreadRoots callback created = 0xb07d83b0
,08-10 15:48:07.279   932   969 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-10 15:48:07.279   932   969 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-10 15:48:07.279   932   969 D sensors_hal_Time: tsOffsetIs: Apps: 197173083001; DSPS: 6559828; Offset : -3018698546
,08-10 15:48:07.655  6964  7022 W jxcore-log: Initializing JXcore engine
,08-10 15:48:07.657  6964  7022 W jxcore-log: JXcore engine is ready
08-10 15:48:07.747  7022  7022 W Thread-854: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6529]" dev="sockfs" ino=6529 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-10 15:48:07.747  7022  7022 W Thread-854: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-10 15:48:07.747  7022  7022 W Thread-854: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7868]" dev="sockfs" ino=7868 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-10 15:48:07.747  7022  7022 W Thread-854: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-10 15:48:07.747  7022  7022 W Thread-854: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-10 15:48:07.747  7022  7022 W Thread-854: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[33070]" dev="sockfs" ino=33070 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-10 15:48:07.784  6964  7022 W jxcore-log: Starting JXcore engine
,08-10 15:48:07.947  6964  7022 W jxcore-log: Platform android
08-10 15:48:07.947  6964  7022 W jxcore-log: 
08-10 15:48:07.947  6964  7022 W jxcore-log: Process ARCH arm
08-10 15:48:07.947  6964  7022 W jxcore-log: 
,08-10 15:48:08.188  6964  7022 I jxcore-log: JXcore Cordova bridge is ready!
08-10 15:48:08.188  6964  7022 I jxcore-log: 
08-10 15:48:08.188  6964  7022 W jxcore-log: JXcore engine is started
,08-10 15:48:08.194  6964  7016 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-10 15:48:08.196  6964  6964 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-10 15:48:08.690   298   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-10 15:48:13.694   298   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-10 15:48:18.699   298   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-10 15:48:23.704   298   351 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-10 15:48:23.914  6964  7022 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-10 15:48:23.914  6964  7022 I jxcore-log: 
,08-10 15:48:23.917  6964  7022 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-10 15:48:23.917  6964  7022 I jxcore-log: 
08-10 15:48:23.925  2028  2057 D BluetoothAdapterService(79123953): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1de1f34f
,08-10 15:48:23.925  6964  7022 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-10 15:48:23.925  6964  7022 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-10 15:48:23.925  6964  7022 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-10 15:48:23.925  6964  7022 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-10 15:48:23.925  6964  7022 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-10 15:48:23.925  6964  7022 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-10 15:48:23.925  6964  7022 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-10 15:48:23.925  6964  7022 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-10 15:48:23.930  2028  2057 D BluetoothAdapterService(79123953): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@1de1f34f
08-10 15:48:23.931  6964  7022 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-10 15:48:23.933  6964  7022 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-10 15:48:23.933  6964  7022 I jxcore-log: 
08-10 15:48:23.936  6964  7022 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-10 15:48:23.936  6964  7022 I jxcore-log: 
,08-10 15:48:24.460  6964  7022 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-10 15:48:24.460  6964  7022 I jxcore-log: Failed to execute UT.
08-10 15:48:24.460  6964  7022 I jxcore-log: 
,08-10 15:48:24.460  6964  7022 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-10 15:48:24.460  6964  7022 I jxcore-log: 
08-10 15:48:24.463  6964  7022 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-10 15:48:24.463  6964  7022 I jxcore-log: 
08-10 15:48:24.482  6964  6964 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-10 15:48:24.875  7032  7032 D AndroidRuntime: 
08-10 15:48:24.875  7032  7032 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-10 15:48:24.883  7032  7032 D AndroidRuntime: CheckJNI is OFF
08-10 15:48:25.217  7032  7032 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-10 15:48:25.277   932  1007 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
,08-10 15:48:25.281   932  1007 I ActivityManager: Killing 6964:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
08-10 15:48:25.326   932  1638 I WindowState: WIN DEATH: Window{2ae92011 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-10 15:48:25.335   932  1638 D InputDispatcher: Focus left window: Window{2ae92011 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-10 15:48:25.335   932  1638 D InputDispatcher: Window went away: Window{2ae92011 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-10 15:48:25.400   932  1007 I ActivityManager:   Force finishing activity ActivityRecord{4370ba2 u0 com.test.thalitest/.MainActivity t259}
,08-10 15:48:25.402   932  1069 W PackageSettings: Skipping PackageSetting{159619fd com.example.hello/10317} due to missing metadata
,08-10 15:48:25.467   932   951 W ActivityManager: Spurious death for ProcessRecord{2564b77c 6964:com.test.thalitest/u0a30}, curProc for 6964: null
,08-10 15:48:25.473   932  1069 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
08-10 15:48:25.475   932  1069 I ActivityManager:   Force finishing activity ActivityRecord{4370ba2 u0 com.test.thalitest/.MainActivity t259 f}
08-10 15:48:25.476   932  1069 W ActivityManager: Duplicate finish request for ActivityRecord{4370ba2 u0 com.test.thalitest/.MainActivity t259 f}
,08-10 15:48:25.549  1970  1970 I art     : Explicit concurrent mark sweep GC freed 249(21KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 12MB/20MB, paused 2.031ms total 70.500ms
08-10 15:48:25.549  1877  1877 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
,08-10 15:48:25.588  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-10 15:48:25.594   932  1287 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-10 15:48:25.597  1877  1877 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
08-10 15:48:25.597  1840  1840 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
08-10 15:48:25.609  1733  2394 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-10 15:48:25.618  3782  3782 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-10 15:48:25.620  3782  3782 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-10 15:48:25.620  3782  3782 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-10 15:48:25.620  3782  3782 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-10 15:48:25.620  3782  3782 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-10 15:48:25.620  3782  3782 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-10 15:48:25.620  3782  3782 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-10 15:48:25.621  3782  3782 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-10 15:48:25.621  3782  3782 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 15:48:25.621  3782  3782 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 15:48:25.621  3782  3782 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-10 15:48:25.621  3782  3782 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-10 15:48:25.647  3411  3411 I art     : Explicit concurrent mark sweep GC freed 3046(149KB) AllocSpace objects, 0(0B) LOS objects, 25% free, 16MB/21MB, paused 1.022ms total 151.729ms
,08-10 15:48:25.649   932  1007 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7055 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-10 15:48:25.678  1372  1372 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-10 15:48:25.683  1372  1522 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-10 15:48:25.683  1372  1522 D KeyguardModel: createShortcutInfo...
08-10 15:48:25.687  1372  1522 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-10 15:48:25.687  1372  1522 D KeyguardModel: createShortcutInfo...
08-10 15:48:25.695  1372  1522 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 15:48:25.696  1372  1522 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-10 15:48:25.698  1372  1522 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 15:48:25.703  1372  1522 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-10 15:48:25.705  1877  1877 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-10 15:48:25.706  1877  1877 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-10 15:48:25.706  1877  1877 I Activity: Activity.onPostResume() called 
08-10 15:48:25.717  1372  1522 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-10 15:48:25.717  1372  1522 D KeyguardModel: createShortcutInfo...
,08-10 15:48:25.727  1877  1877 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
,08-10 15:48:25.735  1372  1522 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-10 15:48:25.737  1372  1522 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 15:48:25.737  1372  1522 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-10 15:48:25.739  1372  1522 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-10 15:48:25.739  1372  1522 D KeyguardModel: createShortcutInfo...
,08-10 15:48:25.752  1372  1522 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 15:48:25.753  1372  1522 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-10 15:48:25.753  1372  1522 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-10 15:48:25.774   932  1029 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
,08-10 15:48:25.774   932  1029 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-10 15:48:25.776  1877  7074 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
08-10 15:48:25.776  1372  1522 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 15:48:25.776  1372  1522 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-10 15:48:25.776   932  1029 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-10 15:48:25.776   932  1029 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-10 15:48:25.776   932  1029 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-10 15:48:25.776   932  1029 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@29f9dcae,  pkg=WindowManager.LayoutParams
08-10 15:48:25.776   932  1029 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-10 15:48:25.780   932  1868 D InputDispatcher: Focus entered window: Window{d113da2 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-10 15:48:25.794  7055  7055 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 15:48:25.794  7055  7055 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-10 15:48:25.796  7055  7055 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-10 15:48:25.797  1877  1877 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-10 15:48:25.798  1877  1877 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-10 15:48:25.799  1877  1877 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-10 15:48:25.824  1372  1522 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-10 15:48:25.824  1372  1522 D KeyguardModel: createShortcutInfo...
08-10 15:48:25.824  1877  1877 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
,08-10 15:48:25.826  1877  1877 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
08-10 15:48:25.828  1877  1877 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-10 15:48:25.831  1372  1372 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-10 15:48:25.831  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-10 15:48:25.831  1372  1372 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-10 15:48:25.831  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-10 15:48:25.831  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-10 15:48:25.831  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-10 15:48:25.833  1372  1372 D KeyguardModel: handleShortcutListChanged...
08-10 15:48:25.841  1372  1522 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-10 15:48:25.842  1372  1522 D KeyguardModel: createShortcutInfo...
,08-10 15:48:25.847   932   932 I art     : Explicit concurrent mark sweep GC freed 46962(2MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 23MB/35MB, paused 26.958ms total 326.838ms
08-10 15:48:25.849   932  1069 I art     : WaitForGcToComplete blocked for 170.114ms for cause Explicit
,08-10 15:48:25.858  1372  1522 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-10 15:48:25.858  1372  1522 D KeyguardModel: createShortcutInfo...
,08-10 15:48:25.870  1372  1522 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 15:48:25.870  1372  1522 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-10 15:48:25.871  1372  1522 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-10 15:48:25.871  1372  1522 D KeyguardModel: createShortcutInfo...
08-10 15:48:25.873  1372  1522 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 15:48:25.873  1372  1522 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-10 15:48:25.874  1372  1522 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-10 15:48:25.874  1372  1522 D KeyguardModel: createShortcutInfo...
08-10 15:48:25.876  1372  1522 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-10 15:48:25.876  1372  1522 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-10 15:48:25.878  1372  1522 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-10 15:48:25.878  1372  1522 D KeyguardModel: createShortcutInfo...
08-10 15:48:25.884  1372  1372 D KeyguardModel: handleShortcutListChanged...
08-10 15:48:25.926   932   932 D administrator: Handling package changes for user 0
,08-10 15:48:25.929   932  1347 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-10 15:48:25.931   932  1347 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6964 uid 10030
08-10 15:48:25.985  1877  1877 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
08-10 15:48:25.986  1629  1629 E b       : Unable to connect to the editor to retrieve text... will retry later
,08-10 15:48:25.992  1877  1877 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2a816346 time:215887
08-10 15:48:26.009   932  1031 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2f80268c u0 com.lge.launcher2/.Launcher t258} time:215903
,08-10 15:48:26.051  1877  1877 I art     : Explicit concurrent mark sweep GC freed 4231(241KB) AllocSpace objects, 5(681KB) LOS objects, 40% free, 15MB/25MB, paused 1.127ms total 56.992ms
,08-10 15:48:26.051  1877  1877 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-10 15:48:26.083   932   932 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-10 15:48:26.083   932   932 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-10 15:48:26.086   932   932 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-10 15:48:26.106   932  1350 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
,08-10 15:48:26.145   932  1069 I art     : Explicit concurrent mark sweep GC freed 13571(1662KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.909ms total 294.129ms
,08-10 15:48:26.149  7055  7055 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-10 15:48:26.190  7055  7055 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,08-10 15:48:26.240  1786  1786 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-10 15:48:26.240  1786  1786 D LCardEmulationManager: getDefaultRoute
,08-10 15:48:26.257  7032  7032 D AndroidRuntime: Shutting down VM
,08-10 15:48:26.262   932  1006 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-10 15:48:26.315   932  1069 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7078 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-10 15:48:26.345   932  1006 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-10 15:48:26.379  1877  1877 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-10 15:48:26.397   932  1382 I ActivityManager: Killing 6627:com.lge.appbox.client/u0a11 (adj 15): empty #11
,08-10 15:48:26.458   932  1819 W libprocessgroup: failed to open /acct/uid_10011/pid_6627/cgroup.procs: No such file or directory
,08-10 15:48:26.527  7055  7055 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-10 15:48:26.574   932  2107 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7101 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-10 15:48:26.575   932  2107 I ActivityManager: Killing 6648:com.android.gallery3d/u0a23 (adj 15): empty #11
08-10 15:48:26.606   932  1638 W libprocessgroup: failed to open /acct/uid_10023/pid_6648/cgroup.procs: No such file or directory
,08-10 15:48:26.655  7101  7101 I AppUp4:AppBoxCP: onCreate
,08-10 15:48:26.656  7101  7101 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-10 15:48:26.664  7101  7101 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-10 15:48:26.664  7101  7101 D AndroidRuntime: Shutting down VM
--------- beginning of crash
08-10 15:48:26.667  7101  7101 E AndroidRuntime: FATAL EXCEPTION: main
08-10 15:48:26.667  7101  7101 E AndroidRuntime: Process: com.l,ge.appbox.client, PID: 7101
08-10 15:48:26.667  7101  7101 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
08-10 15:48:26.667  7101  7101 E AndroidRuntime: 	... 11 more
08-10 15:48:26.682   932  7119 E DropBoxManagerService: Can't write: system_app_crash
08-10 15:48:26.682   932  7119 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
08-10 15:48:26.682   932  7119 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-10 15:48:26.682   932  7119 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-10 15:48:26.682   932  7119 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-10 15:48:26.682   932  7119 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-10 15:48:26.682   932  7119 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-10 15:48:26.682   932  7119 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12621)
08-10 15:48:26.682   932  7119 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-10 15:48:26.682   932  7119 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-10 15:48:26.682   932  7119 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-10 15:48:26.682   932  7119 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-10 15:48:26.682   932  7119 E DropBoxManagerService: 	... 5 more

```
