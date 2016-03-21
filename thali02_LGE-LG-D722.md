#### Test 62548124bd1cdb6_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
03-21 07:35:41.567   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,03-21 07:35:43.486  6735  6735 D AndroidRuntime: 
03-21 07:35:43.486  6735  6735 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
03-21 07:35:43.496  6735  6735 D AndroidRuntime: CheckJNI is OFF
03-21 07:35:43.914  6735  6735 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
03-21 07:35:43.928   989  1284 V AlarmManager: ELAPSED_WAKEUP set : Alarm{25f0f56c type 2 when 211088 android} when 211088
03-21 07:35:43.932   989  1881 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
03-21 07:35:43.995   989  1881 D ActivityManager: setTaskToReturnTo : TaskRecord{fe79735 #226 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
03-21 07:35:43.995   989  1881 D ActivityManager: setTaskToReturnTo : TaskRecord{fe79735 #226 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
03-21 07:35:44.002   989  1881 D WindowStateEx: AppWindowTokenEx init.. 
03-21 07:35:44.046   989  1881 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6754 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
03-21 07:35:44.047   989  1881 D InputDispatcher: Focus left window: Window{e492c92 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
03-21 07:35:44.048  6735  6735 D AndroidRuntime: Shutting down VM
03-21 07:35:44.061  1875  1875 I [LGHome]EVENT: [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
03-21 07:35:44.087   989   989 V ActivityManager: Display changed displayId=0
03-21 07:35:44.088  1748  1748 D DSDPConnection: Display #0 changed.
03-21 07:35:44.197  6754  6754 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,03-21 07:35:44.306  6754  6754 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,03-21 07:35:44.359  6754  6754 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 1537-1539)
03-21 07:35:44.359  6754  6754 I LibraryLoader: Expected native library version number "",actual native library version number ""
,03-21 07:35:44.387  6754  6754 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {43ddf1}
,03-21 07:35:44.388  6754  6754 I LibraryLoader: Expected native library version number "",actual native library version number ""
03-21 07:35:44.389  6754  6754 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
03-21 07:35:44.403  6754  6754 I BrowserStartupController: Initializing chromium process, singleProcess=true
,03-21 07:35:44.405  6754  6754 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 07:35:44.409  6754  6754 E SysUtils: ApplicationContext is null in ApplicationStatus
03-21 07:35:44.438  6754  6754 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,03-21 07:35:44.445  6754  6754 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-21 07:35:44.445  6754  6754 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
03-21 07:35:44.446  6754  6754 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
03-21 07:35:44.446  6754  6754 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
03-21 07:35:44.446  6754  6754 I Adreno-EGL: Build Date: 03/02/15 Mon
03-21 07:35:44.446  6754  6754 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
03-21 07:35:44.446  6754  6754 I Adreno-EGL: Remote Branch: 
03-21 07:35:44.446  6754  6754 I Adreno-EGL: Local Patches: 
03-21 07:35:44.446  6754  6754 I Adreno-EGL: Reconstruct Branch: 
03-21 07:35:44.518   282  1299 V AudioPolicyService: registerClient() client 0xb4027060, uid 10030
,03-21 07:35:44.524   989  1050 D BluetoothManagerService: Message: 20
03-21 07:35:44.524   989  1050 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@28e9a5e9:true
03-21 07:35:44.529  2034  3451 D BluetoothAdapterService(397875287): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f4a6fe5
03-21 07:35:44.619   989  1044 W ActivityManager: Activity pause timeout for ActivityRecord{3dabb7ca u0 com.test.thalitest/.MainActivity t226}
,03-21 07:35:44.725  6754  6754 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 07:35:44.742  6754  6754 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,03-21 07:35:44.746  6754  6754 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
03-21 07:35:44.750  6754  6754 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
03-21 07:35:44.750  6754  6754 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
03-21 07:35:44.765  6754  6754 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,03-21 07:35:44.772  6754  6754 W art     : Attempt to remove local handle scope entry from IRT, ignoring
03-21 07:35:44.772  6754  6754 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,03-21 07:35:44.833  6754  6754 I Activity: Activity.onPostResume() called 
,03-21 07:35:44.839  6754  6812 D OpenGLRenderer: Render dirty regions requested: true
03-21 07:35:44.839  6754  6812 I OpenGLRenderer: Initialized EGL, version 1.4
03-21 07:35:44.844  6754  6812 D OpenGLRenderer: Enabling debug mode 0
03-21 07:35:44.858  6754  6754 D Atlas   : Validating map...
,03-21 07:35:44.862   989  1869 D SplitWindow: check instance of lgWin Window{133adb59 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-21 07:35:44.877  6754  6793 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
03-21 07:35:44.901   989  1049 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
,03-21 07:35:44.904   989  1049 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
03-21 07:35:44.904  1375  1375 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
03-21 07:35:44.904  1375  1375 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
03-21 07:35:44.904  1375  1375 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
03-21 07:35:44.904  1375  1375 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
03-21 07:35:44.906   989  1049 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
03-21 07:35:44.906   989  1049 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
03-21 07:35:44.906   989  1049 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-21 07:35:44.906   989  1049 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@13fee53,  pkg=WindowManager.LayoutParams
03-21 07:35:44.906   989  1049 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
03-21 07:35:44.917   989  2159 D InputDispatcher: Focus entered window: Window{133adb59 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-21 07:35:44.950   989  1818 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,03-21 07:35:44.969   989  1051 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +852ms (total +966ms)
03-21 07:35:44.971   989  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3dabb7ca u0 com.test.thalitest/.MainActivity t226} time:212150
03-21 07:35:44.975  6754  6754 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
03-21 07:35:44.976  6754  6754 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@cd26ee3 time:212156
03-21 07:35:45.028  6754  6754 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,03-21 07:35:45.035  1617  1617 E b       : Unable to connect to the editor to retrieve text... will retry later
03-21 07:35:45.058  6754  6754 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,03-21 07:35:45.101  6754  6754 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6754
,03-21 07:35:45.259  6754  6754 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,03-21 07:35:45.440   989  1016 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
03-21 07:35:45.440   989  1016 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
03-21 07:35:45.440   989  1016 D sensors_hal_Time: tsOffsetIs: Apps: 212619808932; DSPS: 7065362; Offset : -3010349080
,03-21 07:35:45.624  6754  6814 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1622893824
,03-21 07:35:45.632  6754  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
03-21 07:35:45.632  6754  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
03-21 07:35:45.632  6754  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
03-21 07:35:45.632  6754  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
03-21 07:35:45.632  6754  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
03-21 07:35:45.633  6754  6814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39467fa4 added. We now have 1 listener(s)
03-21 07:35:45.634   989  1825 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-21 07:35:45.642  6754  6814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,03-21 07:35:45.645  6754  6814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
03-21 07:35:45.646  6754  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
03-21 07:35:45.646  6754  6814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
03-21 07:35:45.651  6754  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
03-21 07:35:45.651  6754  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
03-21 07:35:45.651  6754  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
03-21 07:35:45.651  6754  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
03-21 07:35:45.651  6754  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
03-21 07:35:45.651  6754  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
03-21 07:35:45.651  6754  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
03-21 07:35:45.651  6754  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
03-21 07:35:45.651  6754  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
03-21 07:35:45.651  6754  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
03-21 07:35:45.651  6754  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
03-21 07:35:45.651  6754  6814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eacd6d3 added. We now have 1 listener(s)
03-21 07:35:45.651  6754  6814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
03-21 07:35:45.656  2034  2062 D BluetoothAdapterService(397875287): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f4a6fe5
,03-21 07:35:45.660  6754  6814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
03-21 07:35:45.670  6754  6814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
03-21 07:35:45.670  6754  6814 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
,03-21 07:35:45.675  6754  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
03-21 07:35:45.676   989  1874 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
03-21 07:35:45.676  6754  6814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
03-21 07:35:45.684  2034  2062 D BluetoothAdapterService(397875287): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f4a6fe5
,03-21 07:35:45.687  6754  6814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 07:35:45.687  6754  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 07:35:45.687  6754  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-21 07:35:45.687  6754  6814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 07:35:45.687  6754  6814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 07:35:45.687  6754  6814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 07:35:45.687  6754  6814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 07:35:45.687  6754  6814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-21 07:35:45.687  6754  6814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
03-21 07:35:45.687  6754  6814 D io.jxcore.node.ConnectivityMonitor: start: OK
03-21 07:35:45.689  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-21 07:35:45.690  6754  6754 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
03-21 07:35:45.692  6754  6814 I io.jxcore.node.LifeCycleMonitor: start: OK
03-21 07:35:45.720  6754  6754 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,03-21 07:35:45.857  6754  6770 I art     : Background sticky concurrent mark sweep GC freed 25566(1690KB) AllocSpace objects, 5(76KB) LOS objects, 7% free, 10MB/11MB, paused 5.821ms total 73.256ms
,03-21 07:35:45.924  6754  6770 I art     : CheckpointMarkThreadRoots callback created = 0xb0763fe0
,03-21 07:35:45.958  6754  6770 I art     : CheckpointMarkThreadRoots callback created = 0xb0763fa0
,03-21 07:35:46.486  6754  6825 W jxcore-log: Initializing JXcore engine
,03-21 07:35:46.487  6754  6825 W jxcore-log: JXcore engine is ready
03-21 07:35:46.572   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,03-21 07:35:46.602  6825  6825 W Thread-815: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7342]" dev="sockfs" ino=7342 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-21 07:35:46.602  6825  6825 W Thread-815: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
03-21 07:35:46.602  6825  6825 W Thread-815: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6541]" dev="sockfs" ino=6541 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
03-21 07:35:46.602  6825  6825 W Thread-815: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=73 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
03-21 07:35:46.602  6825  6825 W Thread-815: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
,03-21 07:35:46.602  6825  6825 W Thread-815: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[29320]" dev="sockfs" ino=29320 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
03-21 07:35:46.640  6754  6825 W jxcore-log: Starting JXcore engine
,03-21 07:35:46.809  6754  6825 W jxcore-log: Platform android
03-21 07:35:46.809  6754  6825 W jxcore-log: 
,03-21 07:35:46.810  6754  6825 W jxcore-log: Process ARCH arm
03-21 07:35:46.810  6754  6825 W jxcore-log: 
,03-21 07:35:47.134  6754  6825 I jxcore-log: JXcore Cordova bridge is ready!
03-21 07:35:47.134  6754  6825 I jxcore-log: 
03-21 07:35:47.135  6754  6825 W jxcore-log: JXcore engine is started
,03-21 07:35:47.143  6754  6814 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
03-21 07:35:47.144  6754  6754 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
03-21 07:35:47.210   989  1978 I art     : Explicit concurrent mark sweep GC freed 80916(3MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 23MB/35MB, paused 2.420ms total 213.692ms
,03-21 07:35:51.576   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,03-21 07:35:51.949   989  1775 I ActivityManager: Process com.google.android.apps.docs (pid 6463) has died
,03-21 07:35:56.581   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,03-21 07:36:00.040  1375  1375 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
03-21 07:36:00.040  1375  1375 I KeyguardUpdateMonitor: called onTimeUpdated()
03-21 07:36:00.040  1375  1375 I [SystemUI]Clock: called onTimeUpdated()
,03-21 07:36:00.044  1375  1375 I LgeClockWidgetControlView: called onTimeUpdated()
03-21 07:36:00.044  1375  1375 I [SystemUI]DateView: called onTimeUpdated()
03-21 07:36:00.045  1375  1375 I [SystemUI]DateView: called onTimeUpdated()
03-21 07:36:00.045  1375  1375 D KeyguardUpdateMonitor: handleTimeUpdate
03-21 07:36:01.586   295   356 I ThermalEngine: Sensor:pa_therm0:29000 mC
,03-21 07:36:02.476  6754  6825 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
03-21 07:36:02.476  6754  6825 I jxcore-log: 
,03-21 07:36:02.481  6754  6825 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
03-21 07:36:02.481  6754  6825 I jxcore-log: 
03-21 07:36:02.485  2034  2062 D BluetoothAdapterService(397875287): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f4a6fe5
03-21 07:36:02.486  6754  6825 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
03-21 07:36:02.486  6754  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
03-21 07:36:02.486  6754  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
03-21 07:36:02.486  6754  6825 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
03-21 07:36:02.486  6754  6825 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
03-21 07:36:02.486  6754  6825 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
03-21 07:36:02.486  6754  6825 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
03-21 07:36:02.486  6754  6825 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
03-21 07:36:02.487  2034  2062 D BluetoothAdapterService(397875287): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f4a6fe5
03-21 07:36:02.488  6754  6825 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
03-21 07:36:02.491  6754  6825 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
03-21 07:36:02.491  6754  6825 I jxcore-log: 
03-21 07:36:02.493  6754  6825 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
03-21 07:36:02.493  6754  6825 I jxcore-log: 
03-21 07:36:03.301  6754  6825 I jxcore-log: Unit Test app is loaded
03-21 07:36:03.301  6754  6825 I jxcore-log: 
,03-21 07:36:03.314  6754  6825 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
03-21 07:36:03.314  6754  6825 I jxcore-log: 
03-21 07:36:03.321  6754  6754 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,03-21 07:36:03.323  2034  2062 D BluetoothAdapterService(397875287): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2f4a6fe5
03-21 07:36:03.323  6754  6825 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
03-21 07:36:03.330  6754  6825 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
03-21 07:36:03.330  6754  6825 I jxcore-log: 
03-21 07:36:03.338  6754  6754 I chromium: [INFO:CONSOLE(86)] "logCallback Device did not have required hardware capabilities!", source: file:///android_asset/www/js/thali_main.js (86)
,03-21 07:36:03.349  6754  6825 I jxcore-log: { bluetoothLowEnergy: 'notHere',
03-21 07:36:03.349  6754  6825 I jxcore-log:   bluetooth: 'on',
03-21 07:36:03.349  6754  6825 I jxcore-log:   wifi: 'on',
03-21 07:36:03.349  6754  6825 I jxcore-log:   cellular: 'doNotCare',
03-21 07:36:03.349  6754  6825 I jxcore-log:   bssidName: 'f4:f2:6d:22:99:3e' }
03-21 07:36:03.349  6754  6825 I jxcore-log: 
03-21 07:36:03.349  6754  6825 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
03-21 07:36:03.349  6754  6825 I jxcore-log: 
,03-21 07:36:03.715  6835  6835 D AndroidRuntime: 
03-21 07:36:03.715  6835  6835 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,03-21 07:36:03.722  6835  6835 D AndroidRuntime: CheckJNI is OFF
03-21 07:36:04.072  6835  6835 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,03-21 07:36:04.113   989  1044 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
03-21 07:36:04.114   989  1044 I ActivityManager: Killing 6754:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
,03-21 07:36:04.160   989  1789 I WindowState: WIN DEATH: Window{133adb59 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,03-21 07:36:04.168   989  1789 D InputDispatcher: Focus left window: Window{133adb59 u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-21 07:36:04.168   989  1789 D InputDispatcher: Window went away: Window{133adb59 u0 com.test.thalitest/com.test.thalitest.MainActivity}
03-21 07:36:04.233   989  1044 I ActivityManager:   Force finishing activity ActivityRecord{3dabb7ca u0 com.test.thalitest/.MainActivity t226}
,03-21 07:36:04.235   989  1059 W PackageSettings: Skipping PackageSetting{136d8142 com.example.hello/10317} due to missing metadata
,03-21 07:36:04.291   989  1885 W ActivityManager: Spurious death for ProcessRecord{39d15664 6754:com.test.thalitest/u0a30}, curProc for 6754: null
,03-21 07:36:04.292   989  1059 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
03-21 07:36:04.294   989  1059 I ActivityManager:   Force finishing activity ActivityRecord{3dabb7ca u0 com.test.thalitest/.MainActivity t226 f}
03-21 07:36:04.294   989  1059 W ActivityManager: Duplicate finish request for ActivityRecord{3dabb7ca u0 com.test.thalitest/.MainActivity t226 f}
,03-21 07:36:04.369  1938  1938 I art     : Explicit concurrent mark sweep GC freed 937(58KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 12MB/21MB, paused 2.545ms total 68.631ms
,03-21 07:36:04.392  1375  1375 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,03-21 07:36:04.405   989  1287 I InputReader: Reconfiguring input devices.  changes=0x00000010
,03-21 07:36:04.407  1837  1837 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
03-21 07:36:04.421  1729  2384 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,03-21 07:36:04.444  3644  3644 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,03-21 07:36:04.447  3644  3644 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
03-21 07:36:04.447  3644  3644 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
03-21 07:36:04.447  3644  3644 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
03-21 07:36:04.447  3644  3644 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
03-21 07:36:04.447  3644  3644 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
03-21 07:36:04.447  3644  3644 W System.err: 	at android.os.Looper.loop(Looper.java:135)
03-21 07:36:04.447  3644  3644 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
03-21 07:36:04.447  3644  3644 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 07:36:04.447  3644  3644 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 07:36:04.447  3644  3644 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
03-21 07:36:04.447  3644  3644 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
03-21 07:36:04.464  4216  4216 I art     : Explicit concurrent mark sweep GC freed 3479(206KB) AllocSpace objects, 1(16KB) LOS objects, 24% free, 14MB/19MB, paused 987us total 146.780ms
,03-21 07:36:04.465  4216  4229 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/networkstatistics.sqlite' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
03-21 07:36:04.471   989  1044 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6859 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
03-21 07:36:04.473  1875  1875 I [LGHome]EVENT: [Launcher.java:5203:onStart()]onStart
03-21 07:36:04.503  1875  1875 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
,03-21 07:36:04.522   989  2710 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=6876 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
,03-21 07:36:04.601  1375  1375 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
03-21 07:36:04.602  1875  1875 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
03-21 07:36:04.604  1875  1875 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
03-21 07:36:04.604  1875  1875 I Activity: Activity.onPostResume() called 
,03-21 07:36:04.615  1875  1875 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
03-21 07:36:04.621   989   989 I art     : Explicit concurrent mark sweep GC freed 13506(1009KB) AllocSpace objects, 5(80KB) LOS objects, 33% free, 23MB/35MB, paused 9.589ms total 280.077ms
03-21 07:36:04.622   989  1059 I art     : WaitForGcToComplete blocked for 89.825ms for cause Explicit
,03-21 07:36:04.660  1875  6894 W [LGHome]LGWallpaperInfo: [LGWallpaperInfo.java:75:loadWallpaperScrollTypeFromSystemPref()]failed parsing java.io.FileNotFoundException: /data/system/wallpaper_prefs.xml: open failed: ENOENT (No such file or directory)
03-21 07:36:04.660  1875  6894 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,03-21 07:36:04.667   989  1049 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
03-21 07:36:04.667   989  1049 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
03-21 07:36:04.668   989  1049 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
03-21 07:36:04.668   989  1049 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
03-21 07:36:04.669   989  1049 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
03-21 07:36:04.669   989  1049 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@13fee53,  pkg=WindowManager.LayoutParams
03-21 07:36:04.669   989  1049 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
03-21 07:36:04.676  6876  6876 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
,03-21 07:36:04.679   989  1843 D InputDispatcher: Focus entered window: Window{e492c92 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
03-21 07:36:04.682  6859  6859 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
03-21 07:36:04.683  6859  6859 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
03-21 07:36:04.696  6859  6859 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
03-21 07:36:04.697  1875  1875 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-21 07:36:04.698  1875  1875 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
03-21 07:36:04.698  1875  1875 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
03-21 07:36:04.710  1375  1507 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
03-21 07:36:04.710  1375  1507 D KeyguardModel: createShortcutInfo...
,03-21 07:36:04.711  1875  1875 I [LGHome]EVENT: [Launcher.java:5214:onStop()]onStop
03-21 07:36:04.712  1875  1875 I [LGHome]EVENT: [Launcher.java:5698:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,03-21 07:36:04.713  1875  1875 I PhoneWindow: [setNavigationBarColor] color=0x 0
03-21 07:36:04.719   989   989 D administrator: Handling package changes for user 0
03-21 07:36:04.719  1375  1375 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
03-21 07:36:04.719  1375  1375 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
03-21 07:36:04.720  1375  1375 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
03-21 07:36:04.720  1375  1375 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
03-21 07:36:04.720  1375  1375 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
03-21 07:36:04.720  1375  1375 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
03-21 07:36:04.722  1375  1507 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
03-21 07:36:04.722  1375  1507 D KeyguardModel: createShortcutInfo...
,03-21 07:36:04.724  1375  1507 W ResourceType: No package identifier when getting value for resource number 0x00000000
03-21 07:36:04.725  1375  1507 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
03-21 07:36:04.731  1375  1507 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
03-21 07:36:04.731  1375  1507 D KeyguardModel: createShortcutInfo...
03-21 07:36:04.732  1375  1507 W ResourceType: No package identifier when getting value for resource number 0x00000000
03-21 07:36:04.733  1375  1507 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
03-21 07:36:04.734  1375  1507 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
03-21 07:36:04.734  1375  1507 D KeyguardModel: createShortcutInfo...
,03-21 07:36:04.741  1375  1507 W ResourceType: No package identifier when getting value for resource number 0x00000000
,03-21 07:36:04.741  1375  1507 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
03-21 07:36:04.742  1375  1507 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
03-21 07:36:04.742  1375  1507 D KeyguardModel: createShortcutInfo...
03-21 07:36:04.748  1375  1375 D KeyguardModel: handleShortcutListChanged...
,03-21 07:36:04.752  1375  1507 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
03-21 07:36:04.752  1375  1507 D KeyguardModel: createShortcutInfo...
03-21 07:36:04.754  1375  1507 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
03-21 07:36:04.754  1375  1507 D KeyguardModel: createShortcutInfo...
03-21 07:36:04.756  1375  1507 W ResourceType: No package identifier when getting value for resource number 0x00000000
03-21 07:36:04.756  1375  1507 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
03-21 07:36:04.757  1375  1507 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
03-21 07:36:04.757  1375  1507 D KeyguardModel: createShortcutInfo...
03-21 07:36:04.759  1375  1507 W ResourceType: No package identifier when getting value for resource number 0x00000000
03-21 07:36:04.759  1375  1507 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
03-21 07:36:04.761  1375  1507 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
03-21 07:36:04.761  1375  1507 D KeyguardModel: createShortcutInfo...
03-21 07:36:04.762  1375  1507 W ResourceType: No package identifier when getting value for resource number 0x00000000
03-21 07:36:04.762  1375  1507 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,03-21 07:36:04.764  1375  1507 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
03-21 07:36:04.765  1375  1507 D KeyguardModel: createShortcutInfo...
03-21 07:36:04.768   989  2710 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
03-21 07:36:04.770  1375  1375 D KeyguardModel: handleShortcutListChanged...
03-21 07:36:04.771   989  2710 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6754 uid 10030
03-21 07:36:04.817  1875  1875 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
03-21 07:36:04.819  1617  1617 E b       : Unable to connect to the editor to retrieve text... will retry later
,03-21 07:36:04.821  1875  1875 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1ac19b21 time:232001
03-21 07:36:04.841   989  1051 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3f9219d7 u0 com.lge.launcher2/.Launcher t225} time:232022
,03-21 07:36:04.867  1875  1875 I art     : Explicit concurrent mark sweep GC freed 4278(259KB) AllocSpace objects, 5(681KB) LOS objects, 40% free, 15MB/25MB, paused 925us total 46.020ms
03-21 07:36:04.867  1875  1875 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,03-21 07:36:04.932   989   989 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
03-21 07:36:04.933   989   989 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,03-21 07:36:04.935   989   989 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,03-21 07:36:04.947   989  1347 D TaskPersister: removeObsoleteFile: deleting file=226_task.xml
,03-21 07:36:04.980   989  1059 I art     : Explicit concurrent mark sweep GC freed 10485(843KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 4.973ms total 357.341ms
,03-21 07:36:04.986  6859  6859 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
03-21 07:36:05.005  6859  6859 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,03-21 07:36:05.073  6835  6835 D AndroidRuntime: Shutting down VM
,03-21 07:36:05.094  1783  1783 D LCardEmulationManager: getHceAppCount hostAppNum : 0
,03-21 07:36:05.095  1783  1783 D LCardEmulationManager: getDefaultRoute
,03-21 07:36:05.142   989  1043 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,03-21 07:36:05.208  6859  6859 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,03-21 07:36:05.213   989  1043 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
03-21 07:36:05.252   989  1818 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6901 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,03-21 07:36:05.253   989  1818 I ActivityManager: Killing 6429:com.android.providers.calendar/u0a14 (adj 15): empty #11
03-21 07:36:05.349  1875  1875 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,03-21 07:36:05.394   989  1059 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6923 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,03-21 07:36:05.412   989  1881 W libprocessgroup: failed to open /acct/uid_10014/pid_6429/cgroup.procs: No such file or directory
,03-21 07:36:05.441   989  1016 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
03-21 07:36:05.441   989  1016 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
03-21 07:36:05.441   989  1016 D sensors_hal_Time: tsOffsetIs: Apps: 232621137986; DSPS: 7720765; Offset : -3010331578
03-21 07:36:05.470  6901  6901 I AppUp4:AppBoxCP: onCreate
03-21 07:36:05.471  6901  6901 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,03-21 07:36:05.481   989  2159 I ActivityManager: Killing 6502:com.google.android.apps.plus/u0a86 (adj 15): empty #11
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
03-21 07:36:05.484  6901  6901 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
03-21 07:36:05.485  6901  6901 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
03-21 07:36:05.487  6901  6901 E AndroidRuntime: FATAL EXCEPTION: main
03-21 07:36:05.487  6901  6901 E AndroidRuntime: Process: com.lge.appbox.client, PID: 6901
03-21 07:36:05.487  6901  6901 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
03-21 07:36:05.487  6901  6901 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(Con
```
