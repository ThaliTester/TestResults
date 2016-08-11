#### Test 80912877ea0a40f_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-11 12:03:36.453   295   352 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 12:03:39.282  6900  6900 D AndroidRuntime: 
08-11 12:03:39.282  6900  6900 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-11 12:03:39.293  6900  6900 D AndroidRuntime: CheckJNI is OFF
08-11 12:03:39.689  6900  6900 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-11 12:03:39.706   845  1636 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 12:03:39.742   845  1636 D ActivityManager: setTaskToReturnTo : TaskRecord{1589b415 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 12:03:39.743   845  1636 D ActivityManager: setTaskToReturnTo : TaskRecord{1589b415 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 12:03:39.747   845  1636 D WindowStateEx: AppWindowTokenEx init.. 
08-11 12:03:39.792   845  1636 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6920 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-11 12:03:39.794   845  1636 D InputDispatcher: Focus left window: Window{35922f23 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-11 12:03:39.795  6900  6900 D AndroidRuntime: Shutting down VM
08-11 12:03:39.801  1881  1881 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-11 12:03:39.829   845   845 V ActivityManager: Display changed displayId=0
08-11 12:03:39.831  1754  1754 D DSDPConnection: Display #0 changed.
08-11 12:03:39.963  6920  6920 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-11 12:03:40.064  6920  6920 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-11 12:03:40.117  6920  6920 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 2035-2037)
08-11 12:03:40.117  6920  6920 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 12:03:40.153  6920  6920 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3a596c12}
08-11 12:03:40.154  6920  6920 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 12:03:40.155  6920  6920 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-11 12:03:40.169  6920  6920 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-11 12:03:40.170  6920  6920 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 12:03:40.171  6920  6920 E SysUtils: ApplicationContext is null in ApplicationStatus
08-11 12:03:40.195  6920  6920 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-11 12:03:40.202  6920  6920 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 12:03:40.202  6920  6920 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 12:03:40.203  6920  6920 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 12:03:40.203  6920  6920 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 12:03:40.203  6920  6920 I Adreno-EGL: Build Date: 03/02/15 Mon
08-11 12:03:40.203  6920  6920 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-11 12:03:40.203  6920  6920 I Adreno-EGL: Remote Branch: 
08-11 12:03:40.203  6920  6920 I Adreno-EGL: Local Patches: 
08-11 12:03:40.203  6920  6920 I Adreno-EGL: Reconstruct Branch: 
08-11 12:03:40.266   845   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-11 12:03:40.266   845   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-11 12:03:40.266   845   986 D sensors_hal_Time: tsOffsetIs: Apps: 212186038570; DSPS: 7051606; Offset : -3016532424
08-11 12:03:40.270   285   285 V AudioPolicyService: registerClient() client 0xb382be40, uid 10030
08-11 12:03:40.285   845  1041 D BluetoothManagerService: Message: 20
08-11 12:03:40.285   845  1041 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22fb2cc9:true
08-11 12:03:40.293  2059  2092 D BluetoothAdapterService(351288800): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30a3d436
08-11 12:03:40.356   845  1001 W ActivityManager: Activity pause timeout for ActivityRecord{3dbe432a u0 com.test.thalitest/.MainActivity t259}
08-11 12:03:40.497  6920  6920 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 12:03:40.513  6920  6920 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-11 12:03:40.519  6920  6920 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-11 12:03:40.524  6920  6920 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-11 12:03:40.524  6920  6920 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-11 12:03:40.541  6920  6920 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-11 12:03:40.550  6920  6920 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 12:03:40.550  6920  6920 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 12:03:40.618  6920  6920 I Activity: Activity.onPostResume() called 
08-11 12:03:40.625  6920  6971 D OpenGLRenderer: Render dirty regions requested: true
08-11 12:03:40.629  6920  6971 I OpenGLRenderer: Initialized EGL, version 1.4
08-11 12:03:40.640  6920  6971 D OpenGLRenderer: Enabling debug mode 0
08-11 12:03:40.659  6920  6920 D Atlas   : Validating map...
08-11 12:03:40.664   845  1789 D SplitWindow: check instance of lgWin Window{35abda39 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 12:03:40.679  6920  6957 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-11 12:03:40.704   845  1040 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-11 12:03:40.707   845  1040 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-11 12:03:40.708  1375  1375 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-11 12:03:40.709  1375  1375 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-11 12:03:40.709  1375  1375 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-11 12:03:40.709  1375  1375 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-11 12:03:40.709   845  1040 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-11 12:03:40.709   845  1040 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-11 12:03:40.709   845  1040 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-11 12:03:40.709   845  1040 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3100f02d,  pkg=WindowManager.LayoutParams
08-11 12:03:40.709   845  1040 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-11 12:03:40.726   845  1905 D InputDispatcher: Focus entered window: Window{35abda39 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 12:03:40.754   845  1880 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-11 12:03:40.758   845  1042 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +901ms (total +1s9ms)
08-11 12:03:40.760   845  1042 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3dbe432a u0 com.test.thalitest/.MainActivity t259} time:212678
08-11 12:03:40.779  6920  6920 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-11 12:03:40.780  6920  6920 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@305adc3c time:212699
,08-11 12:03:40.887  6920  6920 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-11 12:03:40.892  1628  1628 E b       : Unable to connect to the editor to retrieve text... will retry later
08-11 12:03:40.894  6920  6920 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6920
08-11 12:03:40.914  6920  6920 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-11 12:03:41.064  6920  6920 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 12:03:41.445  6920  6973 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1635609344
,08-11 12:03:41.458   295   352 I ThermalEngine: Sensor:pa_therm0:29000 mC
08-11 12:03:41.464  6920  6973 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 12:03:41.464  6920  6973 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 12:03:41.464  6920  6973 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 12:03:41.464  6920  6973 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 12:03:41.464  6920  6973 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-11 12:03:41.465  6920  6973 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@34502c40 added. We now have 1 listener(s)
08-11 12:03:41.473   845  2162 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:03:41.479  6920  6973 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,08-11 12:03:41.482  6920  6973 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-11 12:03:41.483  6920  6973 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 12:03:41.483  6920  6973 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 12:03:41.489  6920  6973 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 12:03:41.489  6920  6973 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 12:03:41.489  6920  6973 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 12:03:41.489  6920  6973 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-11 12:03:41.489  6920  6973 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 12:03:41.489  6920  6973 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 12:03:41.489  6920  6973 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 12:03:41.489  6920  6973 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 12:03:41.489  6920  6973 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 12:03:41.489  6920  6973 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 12:03:41.489  6920  6973 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 12:03:41.489  6920  6973 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 12:03:41.489  6920  6973 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 12:03:41.489  6920  6973 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-11 12:03:41.489  6920  6973 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1f72711f added. We now have 1 listener(s)
08-11 12:03:41.493  6920  6973 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-11 12:03:41.506  6920  6973 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 12:03:41.506  6920  6973 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-11 12:03:41.509  6920  6973 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-11 12:03:41.509  6920  6973 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-11 12:03:41.510  6920  6973 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-11 12:03:41.516  6920  6973 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 12:03:41.517   845  1789 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 12:03:41.518  6920  6973 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
,08-11 12:03:41.538  2059  3767 D BluetoothAdapterService(351288800): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30a3d436
,08-11 12:03:41.541  6920  6973 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-11 12:03:41.541  6920  6973 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:03:41.541  6920  6973 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:03:41.541  6920  6973 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:03:41.541  6920  6973 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:03:41.541  6920  6973 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:03:41.541  6920  6973 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:03:41.541  6920  6973 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:03:41.541  6920  6973 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:03:41.541  6920  6973 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-11 12:03:41.542  6920  6973 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 12:03:41.542  6920  6973 I io.jxcore.node.LifeCycleMonitor: start: OK
08-11 12:03:41.543  6920  6920 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:03:41.545  6920  6920 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 12:03:41.575  6920  6920 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 12:03:41.741  6920  6934 I art     : CheckpointMarkThreadRoots callback created = 0xb07ae3e0
,08-11 12:03:41.780  6920  6934 I art     : CheckpointMarkThreadRoots callback created = 0xb07ae3b0
,08-11 12:03:42.329  6920  6979 W jxcore-log: Initializing JXcore engine
,08-11 12:03:42.333  6920  6979 W jxcore-log: JXcore engine is ready
08-11 12:03:42.442  6979  6979 W Thread-829: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6263]" dev="sockfs" ino=6263 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-11 12:03:42.442  6979  6979 W Thread-829: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-11 12:03:42.442  6979  6979 W Thread-829: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8520]" dev="sockfs" ino=8520 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-11 12:03:42.442  6979  6979 W Thread-829: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-11 12:03:42.442  6979  6979 W Thread-829: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-11 12:03:42.442  6979  6979 W Thread-829: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[31327]" dev="sockfs" ino=31327 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-11 12:03:42.485  6920  6979 W jxcore-log: Starting JXcore engine
,08-11 12:03:42.636  6920  6979 W jxcore-log: Platform android
08-11 12:03:42.636  6920  6979 W jxcore-log: 
08-11 12:03:42.636  6920  6979 W jxcore-log: Process ARCH arm
08-11 12:03:42.636  6920  6979 W jxcore-log: 
,08-11 12:03:42.949   845  1966 I art     : Explicit concurrent mark sweep GC freed 54929(2MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 23MB/35MB, paused 2.338ms total 205.435ms
,08-11 12:03:42.965  6920  6979 I jxcore-log: JXcore Cordova bridge is ready!
08-11 12:03:42.965  6920  6979 I jxcore-log: 
08-11 12:03:42.965  6920  6979 W jxcore-log: JXcore engine is started
08-11 12:03:42.971  6920  6973 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-11 12:03:42.974  6920  6920 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-11 12:03:46.463   295   352 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 12:03:47.860   845  2141 I ActivityManager: Process com.google.android.talk (pid 6545) has died
,08-11 12:03:51.468   295   352 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 12:03:55.088   845  1287 V AlarmManager: ELAPSED_WAKEUP set : Alarm{145836c4 type 2 when 213461 android} when 213461
,08-11 12:03:56.472   295   352 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-11 12:03:58.735  6920  6979 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 12:03:58.735  6920  6979 I jxcore-log: 
08-11 12:03:58.739  6920  6979 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 12:03:58.739  6920  6979 I jxcore-log: 
,08-11 12:03:58.745  2059  3767 D BluetoothAdapterService(351288800): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30a3d436
08-11 12:03:58.746  6920  6979 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 12:03:58.746  6920  6979 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 12:03:58.746  6920  6979 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 12:03:58.746  6920  6979 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 12:03:58.746  6920  6979 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 12:03:58.746  6920  6979 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 12:03:58.746  6920  6979 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 12:03:58.746  6920  6979 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 12:03:58.747  2059  3767 D BluetoothAdapterService(351288800): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@30a3d436
08-11 12:03:58.748  6920  6979 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 12:03:58.753  6920  6979 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 12:03:58.753  6920  6979 I jxcore-log: 
08-11 12:03:58.755  6920  6979 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 12:03:58.755  6920  6979 I jxcore-log: 
,08-11 12:03:59.281  6920  6979 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
,08-11 12:03:59.281  6920  6979 I jxcore-log: Failed to execute UT.
08-11 12:03:59.281  6920  6979 I jxcore-log: 
08-11 12:03:59.281  6920  6979 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-11 12:03:59.281  6920  6979 I jxcore-log: 
,08-11 12:03:59.289  6920  6979 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 12:03:59.289  6920  6979 I jxcore-log: 
08-11 12:03:59.305  6920  6920 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-11 12:03:59.649  6997  6997 D AndroidRuntime: 
08-11 12:03:59.649  6997  6997 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-11 12:03:59.656  6997  6997 D AndroidRuntime: CheckJNI is OFF
08-11 12:03:59.979  6997  6997 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-11 12:04:00.030   845  1001 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
08-11 12:04:00.031   845  1001 I ActivityManager: Killing 6920:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
,08-11 12:04:00.050  1375  1375 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-11 12:04:00.050  1375  1375 I KeyguardUpdateMonitor: called onTimeUpdated()
08-11 12:04:00.050  1375  1375 I [SystemUI]Clock: called onTimeUpdated()
,08-11 12:04:00.079   845  2162 I WindowState: WIN DEATH: Window{35abda39 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 12:04:00.091   845  2162 D InputDispatcher: Focus left window: Window{35abda39 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 12:04:00.091   845  2162 D InputDispatcher: Window went away: Window{35abda39 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 12:04:00.144   845  1001 I ActivityManager:   Force finishing activity ActivityRecord{3dbe432a u0 com.test.thalitest/.MainActivity t259}
,08-11 12:04:00.163   845  1065 W PackageSettings: Skipping PackageSetting{240a8d1c com.example.hello/10317} due to missing metadata
,08-11 12:04:00.199  1375  1375 I LgeClockWidgetControlView: called onTimeUpdated()
08-11 12:04:00.199  1375  1375 I [SystemUI]DateView: called onTimeUpdated()
08-11 12:04:00.201  1375  1375 I [SystemUI]DateView: called onTimeUpdated()
08-11 12:04:00.203  1375  1375 D KeyguardUpdateMonitor: handleTimeUpdate
,08-11 12:04:00.231   845   863 W ActivityManager: Spurious death for ProcessRecord{29d739ad 6920:com.test.thalitest/u0a30}, curProc for 6920: null
08-11 12:04:00.234   845  1065 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
08-11 12:04:00.237   845  1065 I ActivityManager:   Force finishing activity ActivityRecord{3dbe432a u0 com.test.thalitest/.MainActivity t259 f}
08-11 12:04:00.237   845  1065 W ActivityManager: Duplicate finish request for ActivityRecord{3dbe432a u0 com.test.thalitest/.MainActivity t259 f}
,08-11 12:04:00.271   845   986 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-11 12:04:00.271   845   986 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-11 12:04:00.271   845   986 D sensors_hal_Time: tsOffsetIs: Apps: 232190477365; DSPS: 7707112; Offset : -3016547973
,08-11 12:04:00.307  1941  1941 I art     : Explicit concurrent mark sweep GC freed 195(19KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/21MB, paused 1.941ms total 67.899ms
,08-11 12:04:00.335  1881  1881 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
,08-11 12:04:00.355  1375  1375 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-11 12:04:00.358   845  1290 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-11 12:04:00.358  3664  3664 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-11 12:04:00.360  3664  3664 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
,08-11 12:04:00.360  3664  3664 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-11 12:04:00.360  3664  3664 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-11 12:04:00.361  3664  3664 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 12:04:00.361  3664  3664 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 12:04:00.361  3664  3664 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 12:04:00.361  3664  3664 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-11 12:04:00.361  3664  3664 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 12:04:00.361  3664  3664 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 12:04:00.361  3664  3664 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-11 12:04:00.361  3664  3664 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-11 12:04:00.370  1843  1843 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
08-11 12:04:00.376  3399  3399 I art     : Explicit concurrent mark sweep GC freed 4660(244KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 16MB/21MB, paused 1.032ms total 119.072ms
,08-11 12:04:00.394  1735  2407 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-11 12:04:00.395  1881  1881 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
,08-11 12:04:00.410   845  1001 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7023 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-11 12:04:00.451  1375  1375 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-11 12:04:00.454  1881  1881 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-11 12:04:00.461  1881  1881 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-11 12:04:00.462  1881  1881 I Activity: Activity.onPostResume() called 
,08-11 12:04:00.475  1881  1881 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-11 12:04:00.507  1375  1375 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-11 12:04:00.507  1375  1375 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-11 12:04:00.531  1881  7040 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,08-11 12:04:00.538   845  1040 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
08-11 12:04:00.538   845  1040 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-11 12:04:00.538   845  1040 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-11 12:04:00.538   845  1040 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-11 12:04:00.539   845  1040 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-11 12:04:00.539   845  1040 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3100f02d,  pkg=WindowManager.LayoutParams
08-11 12:04:00.539   845  1040 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-11 12:04:00.540  1375  1375 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-11 12:04:00.540  1375  1375 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-11 12:04:00.540  1375  1375 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-11 12:04:00.540  1375  1375 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-11 12:04:00.543   845   845 I art     : Explicit concurrent mark sweep GC freed 15997(1666KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/35MB, paused 12.645ms total 232.225ms
08-11 12:04:00.544   845  1065 I art     : WaitForGcToComplete blocked for 189.938ms for cause Explicit
08-11 12:04:00.575   845  1852 D InputDispatcher: Focus entered window: Window{35922f23 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-11 12:04:00.577  1375  1520 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-11 12:04:00.577  1375  1520 D KeyguardModel: createShortcutInfo...
,08-11 12:04:00.580  1375  1520 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 12:04:00.580  1375  1520 D KeyguardModel: createShortcutInfo...
08-11 12:04:00.595  1881  1881 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-11 12:04:00.596  1881  1881 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-11 12:04:00.596  1881  1881 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-11 12:04:00.598  1375  1520 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-11 12:04:00.605  1881  1881 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-11 12:04:00.606  1375  1520 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-11 12:04:00.607  1881  1881 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
08-11 12:04:00.608  1881  1881 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-11 12:04:00.609  1375  1520 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
,08-11 12:04:00.609  1375  1520 D KeyguardModel: createShortcutInfo...
08-11 12:04:00.611  1375  1520 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 12:04:00.611  1375  1520 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-11 12:04:00.613  1375  1520 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 12:04:00.613  1375  1520 D KeyguardModel: createShortcutInfo...
08-11 12:04:00.614  7023  7023 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 12:04:00.614  7023  7023 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 12:04:00.616  1375  1520 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 12:04:00.616  1375  1520 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-11 12:04:00.617  1375  1520 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 12:04:00.617  1375  1520 D KeyguardModel: createShortcutInfo...
08-11 12:04:00.620  7023  7023 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-11 12:04:00.623  1375  1375 D KeyguardModel: handleShortcutListChanged...
,08-11 12:04:00.625   845   845 D administrator: Handling package changes for user 0
08-11 12:04:00.632  1375  1520 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-11 12:04:00.632  1375  1520 D KeyguardModel: createShortcutInfo...
08-11 12:04:00.635  1375  1520 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 12:04:00.635  1375  1520 D KeyguardModel: createShortcutInfo...
08-11 12:04:00.636  1375  1520 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 12:04:00.636  1375  1520 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-11 12:04:00.638  1375  1520 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-11 12:04:00.638  1375  1520 D KeyguardModel: createShortcutInfo...
08-11 12:04:00.640  1375  1520 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 12:04:00.641  1375  1520 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-11 12:04:00.644  1375  1520 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 12:04:00.644  1375  1520 D KeyguardModel: createShortcutInfo...
08-11 12:04:00.646  1375  1520 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 12:04:00.646  1375  1520 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-11 12:04:00.649  1375  1520 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 12:04:00.649  1375  1520 D KeyguardModel: createShortcutInfo...
,08-11 12:04:00.658   845  1852 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-11 12:04:00.663  1375  1375 D KeyguardModel: handleShortcutListChanged...
,08-11 12:04:00.668   845  1852 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6920 uid 10030
08-11 12:04:00.722   845   845 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-11 12:04:00.722   845   845 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-11 12:04:00.725  1881  1881 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
08-11 12:04:00.726   845   845 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-11 12:04:00.728  1628  1628 E b       : Unable to connect to the editor to retrieve text... will retry later
,08-11 12:04:00.733  1881  1881 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@21b21bd0 time:232653
08-11 12:04:00.737   845  1353 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
08-11 12:04:00.753   845  1042 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3205bf89 u0 com.lge.launcher2/.Launcher t258} time:232672
,08-11 12:04:00.777  1881  1881 I art     : Explicit concurrent mark sweep GC freed 4555(271KB) AllocSpace objects, 4(645KB) LOS objects, 39% free, 15MB/25MB, paused 1.362ms total 42.304ms
08-11 12:04:00.777  1881  1881 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-11 12:04:00.888   845   997 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-11 12:04:00.893  7023  7023 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-11 12:04:00.912  7023  7023 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,08-11 12:04:00.940   845   997 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-11 12:04:00.943  1881  1881 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-11 12:04:00.949   845  1065 I art     : Explicit concurrent mark sweep GC freed 11713(1064KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.491ms total 403.892ms
08-11 12:04:00.996  1790  1790 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-11 12:04:00.996  1790  1790 D LCardEmulationManager: getDefaultRoute
,08-11 12:04:01.023  6997  6997 D AndroidRuntime: Shutting down VM
,08-11 12:04:01.151  7023  7023 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-11 12:04:01.174  6587  6587 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-11 12:04:01.222   845  1852 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7050 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,08-11 12:04:01.293   845  1065 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7070 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-11 12:04:01.388   845   863 I ActivityManager: Killing 6607:com.android.gallery3d/u0a23 (adj 15): empty #11
,08-11 12:04:01.421   845  1948 W libprocessgroup: failed to open /acct/uid_10023/pid_6607/cgroup.procs: No such file or directory
,08-11 12:04:01.477   295   352 I ThermalEngine: Sensor:pa_therm0:30000 mC

```
