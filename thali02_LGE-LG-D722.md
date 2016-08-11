#### Test 797638305bc0289_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-11 13:30:50.983   295   358 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 13:30:54.864  6833  6833 D AndroidRuntime: 
08-11 13:30:54.864  6833  6833 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-11 13:30:54.875  6833  6833 D AndroidRuntime: CheckJNI is OFF
08-11 13:30:55.131   915   992 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-11 13:30:55.131   915   992 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-11 13:30:55.131   915   992 D sensors_hal_Time: tsOffsetIs: Apps: 212625687723; DSPS: 7059042; Offset : -2808779301
08-11 13:30:55.227  6833  6833 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-11 13:30:55.242   915  2043 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 13:30:55.283   915  2043 D ActivityManager: setTaskToReturnTo : TaskRecord{f8965b9 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 13:30:55.284   915  2043 D ActivityManager: setTaskToReturnTo : TaskRecord{f8965b9 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 13:30:55.287   915  2043 D WindowStateEx: AppWindowTokenEx init.. 
08-11 13:30:55.332   915  2043 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6854 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-11 13:30:55.333   915  2043 D InputDispatcher: Focus left window: Window{4df467d u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-11 13:30:55.335  6833  6833 D AndroidRuntime: Shutting down VM
08-11 13:30:55.341  1951  1951 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-11 13:30:55.370   915   915 V ActivityManager: Display changed displayId=0
08-11 13:30:55.370  1792  1792 D DSDPConnection: Display #0 changed.
08-11 13:30:55.495  6854  6854 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-11 13:30:55.606  6854  6854 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-11 13:30:55.660  6854  6854 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 3153-3155)
08-11 13:30:55.661  6854  6854 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 13:30:55.691  6854  6854 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {26b52ac3}
08-11 13:30:55.692  6854  6854 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 13:30:55.693  6854  6854 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-11 13:30:55.707  6854  6854 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-11 13:30:55.707  6854  6854 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 13:30:55.709  6854  6854 E SysUtils: ApplicationContext is null in ApplicationStatus
08-11 13:30:55.737  6854  6854 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-11 13:30:55.743  6854  6854 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 13:30:55.743  6854  6854 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 13:30:55.744  6854  6854 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 13:30:55.744  6854  6854 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 13:30:55.744  6854  6854 I Adreno-EGL: Build Date: 03/02/15 Mon
08-11 13:30:55.744  6854  6854 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-11 13:30:55.744  6854  6854 I Adreno-EGL: Remote Branch: 
08-11 13:30:55.744  6854  6854 I Adreno-EGL: Local Patches: 
08-11 13:30:55.744  6854  6854 I Adreno-EGL: Reconstruct Branch: 
08-11 13:30:55.844   284  1297 V AudioPolicyService: registerClient() client 0xb3840e20, uid 10030
08-11 13:30:55.865   915  1054 D BluetoothManagerService: Message: 20
08-11 13:30:55.866   915  1054 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@31e6ed2d:true
08-11 13:30:55.870  2061  3526 D BluetoothAdapterService(88731257): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27378417
08-11 13:30:55.899   915  1019 W ActivityManager: Activity pause timeout for ActivityRecord{2094ddfe u0 com.test.thalitest/.MainActivity t259}
08-11 13:30:55.987   295   358 I ThermalEngine: Sensor:pa_therm0:29000 mC
08-11 13:30:56.027  6854  6854 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 13:30:56.039  6854  6854 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-11 13:30:56.045  6854  6854 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-11 13:30:56.049  6854  6854 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-11 13:30:56.050  6854  6854 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-11 13:30:56.066  6854  6854 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-11 13:30:56.074  6854  6854 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 13:30:56.074  6854  6854 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 13:30:56.134  6854  6854 I Activity: Activity.onPostResume() called 
08-11 13:30:56.139  6854  6897 D OpenGLRenderer: Render dirty regions requested: true
08-11 13:30:56.139  6854  6897 I OpenGLRenderer: Initialized EGL, version 1.4
08-11 13:30:56.144  6854  6897 D OpenGLRenderer: Enabling debug mode 0
08-11 13:30:56.158  6854  6854 D Atlas   : Validating map...
08-11 13:30:56.164   915  2043 D SplitWindow: check instance of lgWin Window{8a7b9d u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 13:30:56.179  6854  6884 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-11 13:30:56.198   915  1053 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-11 13:30:56.201   915  1053 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-11 13:30:56.201  1374  1374 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-11 13:30:56.201  1374  1374 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-11 13:30:56.201  1374  1374 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-11 13:30:56.201  1374  1374 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-11 13:30:56.202   915  1053 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-11 13:30:56.202   915  1053 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-11 13:30:56.202   915  1053 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-11 13:30:56.202   915  1053 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1d1106e9,  pkg=WindowManager.LayoutParams
08-11 13:30:56.202   915  1053 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-11 13:30:56.212   915  1644 D InputDispatcher: Focus entered window: Window{8a7b9d u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 13:30:56.235   915  1950 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-11 13:30:56.251   915  1055 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +852ms (total +962ms)
08-11 13:30:56.251   915  1055 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2094ddfe u0 com.test.thalitest/.MainActivity t259} time:213746
08-11 13:30:56.255  6854  6854 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-11 13:30:56.257  6854  6854 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2b9499a5 time:213751
08-11 13:30:56.306  6854  6854 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
08-11 13:30:56.311  1636  1636 E b       : Unable to connect to the editor to retrieve text... will retry later
08-11 13:30:56.327  6854  6854 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-11 13:30:56.396  6854  6854 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6854
,08-11 13:30:56.530  6854  6854 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 13:30:56.898  6854  6900 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1631417600
,08-11 13:30:56.925  6854  6900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 13:30:56.925  6854  6900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 13:30:56.925  6854  6900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 13:30:56.925  6854  6900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 13:30:56.925  6854  6900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-11 13:30:56.925  6854  6900 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21cc1d59 added. We now have 1 listener(s)
,08-11 13:30:56.934   915  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 13:30:56.938  6854  6900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
08-11 13:30:56.941  6854  6900 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-11 13:30:56.942  6854  6900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 13:30:56.942  6854  6900 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-11 13:30:56.950  6854  6900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 13:30:56.950  6854  6900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 13:30:56.950  6854  6900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 13:30:56.950  6854  6900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-11 13:30:56.950  6854  6900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 13:30:56.950  6854  6900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 13:30:56.950  6854  6900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 13:30:56.950  6854  6900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 13:30:56.950  6854  6900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 13:30:56.950  6854  6900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 13:30:56.950  6854  6900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 13:30:56.950  6854  6900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 13:30:56.950  6854  6900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 13:30:56.950  6854  6900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-11 13:30:56.950  6854  6900 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@65743cc added. We now have 1 listener(s)
08-11 13:30:56.951  6854  6900 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 13:30:56.961  6854  6900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 13:30:56.961  6854  6900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-11 13:30:56.964  6854  6900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-11 13:30:56.965  6854  6900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-11 13:30:56.965  6854  6900 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-11 13:30:56.969  6854  6900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 13:30:56.970   915   972 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 13:30:56.971  6854  6900 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-11 13:30:56.981  2061  2079 D BluetoothAdapterService(88731257): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27378417
,08-11 13:30:56.986  6854  6900 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-11 13:30:56.986  6854  6900 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 13:30:56.986  6854  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 13:30:56.986  6854  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 13:30:56.986  6854  6900 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 13:30:56.986  6854  6900 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 13:30:56.986  6854  6900 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 13:30:56.986  6854  6900 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 13:30:56.986  6854  6900 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 13:30:56.986  6854  6900 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-11 13:30:56.986  6854  6900 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 13:30:56.988  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 13:30:56.988  6854  6900 I io.jxcore.node.LifeCycleMonitor: start: OK
08-11 13:30:56.990  6854  6854 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 13:30:57.021  6854  6854 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 13:30:57.197  6854  6869 I art     : CheckpointMarkThreadRoots callback created = 0xb03fc640
,08-11 13:30:57.235  6854  6869 I art     : CheckpointMarkThreadRoots callback created = 0xb03fc600
,08-11 13:30:57.776  6854  6906 W jxcore-log: Initializing JXcore engine
,08-11 13:30:57.778  6854  6906 W jxcore-log: JXcore engine is ready
08-11 13:30:57.878  6906  6906 W Thread-815: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5706]" dev="sockfs" ino=5706 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-11 13:30:57.878  6906  6906 W Thread-815: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-11 13:30:57.878  6906  6906 W Thread-815: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8199]" dev="sockfs" ino=8199 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-11 13:30:57.878  6906  6906 W Thread-815: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-11 13:30:57.878  6906  6906 W Thread-815: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-11 13:30:57.878  6906  6906 W Thread-815: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[32109]" dev="sockfs" ino=32109 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-11 13:30:57.914  6854  6906 W jxcore-log: Starting JXcore engine
,08-11 13:30:58.069  6854  6906 W jxcore-log: Platform android
08-11 13:30:58.069  6854  6906 W jxcore-log: 
,08-11 13:30:58.069  6854  6906 W jxcore-log: Process ARCH arm
08-11 13:30:58.069  6854  6906 W jxcore-log: 
08-11 13:30:58.331  6854  6906 I jxcore-log: JXcore Cordova bridge is ready!
08-11 13:30:58.331  6854  6906 I jxcore-log: 
08-11 13:30:58.332  6854  6906 W jxcore-log: JXcore engine is started
,08-11 13:30:58.339  6854  6900 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-11 13:30:58.341  6854  6854 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-11 13:31:00.038  1374  1374 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-11 13:31:00.038  1374  1374 I KeyguardUpdateMonitor: called onTimeUpdated()
08-11 13:31:00.038  1374  1374 I [SystemUI]Clock: called onTimeUpdated()
,08-11 13:31:00.040  1374  1374 I LgeClockWidgetControlView: called onTimeUpdated()
08-11 13:31:00.040  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-11 13:31:00.057  1374  1374 I [SystemUI]DateView: called onTimeUpdated()
08-11 13:31:00.058  1374  1374 D KeyguardUpdateMonitor: handleTimeUpdate
,08-11 13:31:00.992   295   358 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 13:31:05.997   295   358 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 13:31:09.973   915  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{76104f8 type 2 when 214103 android} when 214103
,08-11 13:31:11.002   295   358 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 13:31:12.452  1763  3671 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-11 13:31:14.362  6854  6906 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 13:31:14.362  6854  6906 I jxcore-log: 
,08-11 13:31:14.365  6854  6906 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 13:31:14.365  6854  6906 I jxcore-log: 
08-11 13:31:14.372  2061  2079 D BluetoothAdapterService(88731257): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27378417
08-11 13:31:14.372  6854  6906 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 13:31:14.372  6854  6906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 13:31:14.372  6854  6906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 13:31:14.372  6854  6906 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 13:31:14.372  6854  6906 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 13:31:14.372  6854  6906 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 13:31:14.372  6854  6906 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 13:31:14.372  6854  6906 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-11 13:31:14.374  2061  2079 D BluetoothAdapterService(88731257): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27378417
08-11 13:31:14.375  6854  6906 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 13:31:14.381  6854  6906 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 13:31:14.381  6854  6906 I jxcore-log: 
08-11 13:31:14.383  6854  6906 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 13:31:14.383  6854  6906 I jxcore-log: 
,08-11 13:31:14.910  6854  6906 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-11 13:31:14.910  6854  6906 I jxcore-log: Failed to execute UT.
08-11 13:31:14.910  6854  6906 I jxcore-log: 
,08-11 13:31:14.910  6854  6906 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-11 13:31:14.910  6854  6906 I jxcore-log: 
08-11 13:31:14.921  6854  6906 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 13:31:14.921  6854  6906 I jxcore-log: 
08-11 13:31:14.936  6854  6854 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-11 13:31:15.132   915   992 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-11 13:31:15.132   915   992 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-11 13:31:15.132   915   992 D sensors_hal_Time: tsOffsetIs: Apps: 232626597677; DSPS: 7714432; Offset : -2808784431
,08-11 13:31:15.336  6922  6922 D AndroidRuntime: 
08-11 13:31:15.336  6922  6922 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-11 13:31:15.344  6922  6922 D AndroidRuntime: CheckJNI is OFF
08-11 13:31:15.665  6922  6922 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-11 13:31:15.717   915  1019 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
08-11 13:31:15.717   915  1019 I ActivityManager: Killing 6854:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
,08-11 13:31:15.766   915  2018 I WindowState: WIN DEATH: Window{8a7b9d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 13:31:15.800   915  2018 D InputDispatcher: Focus left window: Window{8a7b9d u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 13:31:15.800   915  2018 D InputDispatcher: Window went away: Window{8a7b9d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 13:31:15.830   915  1067 W PackageSettings: Skipping PackageSetting{28b3d905 com.example.hello/10317} due to missing metadata
,08-11 13:31:15.840   915  1019 I ActivityManager:   Force finishing activity ActivityRecord{2094ddfe u0 com.test.thalitest/.MainActivity t259}
,08-11 13:31:15.901   915  4303 W ActivityManager: Spurious death for ProcessRecord{3a2ddd1 6854:com.test.thalitest/u0a30}, curProc for 6854: null
,08-11 13:31:15.904   915  1067 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
08-11 13:31:15.906   915  1067 I ActivityManager:   Force finishing activity ActivityRecord{2094ddfe u0 com.test.thalitest/.MainActivity t259 f}
08-11 13:31:15.907   915  1067 W ActivityManager: Duplicate finish request for ActivityRecord{2094ddfe u0 com.test.thalitest/.MainActivity t259 f}
,08-11 13:31:15.992  2034  2034 I art     : Explicit concurrent mark sweep GC freed 519(32KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 12MB/21MB, paused 1.588ms total 83.283ms
,08-11 13:31:16.006  1374  1374 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-11 13:31:16.007   295   358 I ThermalEngine: Sensor:pa_therm0:29000 mC
08-11 13:31:16.017  1763  2506 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-11 13:31:16.019  3681  3681 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-11 13:31:16.021  3681  3681 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-11 13:31:16.021  3681  3681 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-11 13:31:16.021  3681  3681 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-11 13:31:16.021  3681  3681 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 13:31:16.021  3681  3681 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 13:31:16.021  3681  3681 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 13:31:16.021  3681  3681 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-11 13:31:16.021  3681  3681 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 13:31:16.021  3681  3681 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 13:31:16.021  3681  3681 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-11 13:31:16.021  3681  3681 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-11 13:31:16.033  1912  1912 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,08-11 13:31:16.044   915  1288 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-11 13:31:16.049  3370  3370 I art     : Explicit concurrent mark sweep GC freed 5065(268KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 16MB/22MB, paused 1.040ms total 119.996ms
,08-11 13:31:16.079   915  1019 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6947 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-11 13:31:16.081  1951  1951 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
08-11 13:31:16.112  1374  1374 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-11 13:31:16.146  1951  1951 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
,08-11 13:31:16.186  1951  1951 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-11 13:31:16.192  1951  1951 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-11 13:31:16.192  1951  1951 I Activity: Activity.onPostResume() called 
,08-11 13:31:16.211  1951  1951 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
,08-11 13:31:16.247  1951  6965 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
,08-11 13:31:16.250   915  1053 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
08-11 13:31:16.251   915  1053 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-11 13:31:16.252   915  1053 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-11 13:31:16.252   915  1053 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-11 13:31:16.252   915  1053 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-11 13:31:16.252   915  1053 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1d1106e9,  pkg=WindowManager.LayoutParams
08-11 13:31:16.252   915  1053 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-11 13:31:16.255  1374  1374 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-11 13:31:16.255   915  2184 D InputDispatcher: Focus entered window: Window{4df467d u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-11 13:31:16.258  1374  1374 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-11 13:31:16.258  1374  1374 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-11 13:31:16.258  1374  1374 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-11 13:31:16.258  1374  1374 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-11 13:31:16.258  1374  1374 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-11 13:31:16.271  1374  1513 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-11 13:31:16.271  1374  1513 D KeyguardModel: createShortcutInfo...
,08-11 13:31:16.273   915   915 I art     : Explicit concurrent mark sweep GC freed 57677(3MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 24MB/36MB, paused 16.233ms total 322.921ms
08-11 13:31:16.273   915  1067 I art     : WaitForGcToComplete blocked for 184.471ms for cause Explicit
08-11 13:31:16.276  6947  6947 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 13:31:16.277  6947  6947 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 13:31:16.277  6947  6947 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-11 13:31:16.279  1951  1951 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-11 13:31:16.280  1951  1951 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-11 13:31:16.280  1951  1951 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-11 13:31:16.308  1374  1513 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 13:31:16.308  1374  1513 D KeyguardModel: createShortcutInfo...
,08-11 13:31:16.311  1374  1513 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 13:31:16.311  1374  1513 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-11 13:31:16.314  1374  1513 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-11 13:31:16.314  1374  1513 D KeyguardModel: createShortcutInfo...
08-11 13:31:16.314  1951  1951 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-11 13:31:16.315  1951  1951 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
08-11 13:31:16.316  1374  1513 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 13:31:16.316  1951  1951 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-11 13:31:16.316  1374  1513 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-11 13:31:16.318  1374  1513 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 13:31:16.318  1374  1513 D KeyguardModel: createShortcutInfo...
08-11 13:31:16.319   915  1292 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-11 13:31:16.323   915  1292 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6854 uid 10030
08-11 13:31:16.326  1374  1513 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 13:31:16.326  1374  1513 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-11 13:31:16.329  1374  1513 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 13:31:16.329  1374  1513 D KeyguardModel: createShortcutInfo...
08-11 13:31:16.331   915   915 D administrator: Handling package changes for user 0
,08-11 13:31:16.347  1374  1374 D KeyguardModel: handleShortcutListChanged...
,08-11 13:31:16.363  1374  1513 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,08-11 13:31:16.363  1374  1513 D KeyguardModel: createShortcutInfo...
08-11 13:31:16.372  1374  1513 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 13:31:16.373  1374  1513 D KeyguardModel: createShortcutInfo...
08-11 13:31:16.375  1374  1513 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 13:31:16.375  1374  1513 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-11 13:31:16.376  1951  1951 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-11 13:31:16.378  1374  1513 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-11 13:31:16.378  1374  1513 D KeyguardModel: createShortcutInfo...
08-11 13:31:16.378  1636  1636 E b       : Unable to connect to the editor to retrieve text... will retry later
08-11 13:31:16.380  1374  1513 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 13:31:16.380  1374  1513 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-11 13:31:16.382  1374  1513 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 13:31:16.382  1374  1513 D KeyguardModel: createShortcutInfo...
08-11 13:31:16.387  1374  1513 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 13:31:16.387  1374  1513 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-11 13:31:16.390  1951  1951 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1d9aa5a9 time:233884
08-11 13:31:16.393  1374  1513 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 13:31:16.393  1374  1513 D KeyguardModel: createShortcutInfo...
08-11 13:31:16.395   915  1055 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1030e395 u0 com.lge.launcher2/.Launcher t258} time:233890
08-11 13:31:16.405  1374  1374 D KeyguardModel: handleShortcutListChanged...
,08-11 13:31:16.453  1951  1951 I art     : Explicit concurrent mark sweep GC freed 3978(228KB) AllocSpace objects, 4(645KB) LOS objects, 40% free, 15MB/25MB, paused 1.872ms total 62.196ms
08-11 13:31:16.453  1951  1951 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-11 13:31:16.483   915   915 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-11 13:31:16.483   915   915 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-11 13:31:16.487   915   915 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-11 13:31:16.495   915  1352 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
08-11 13:31:16.546   915  1017 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-11 13:31:16.576  6947  6947 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-11 13:31:16.588   915  1067 I art     : Explicit concurrent mark sweep GC freed 10931(1057KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.373ms total 314.897ms
,08-11 13:31:16.588   915  2043 I art     : WaitForGcToComplete blocked for 316.027ms for cause Explicit
,08-11 13:31:16.597  6947  6947 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
08-11 13:31:16.663   915  1017 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-11 13:31:16.672  1951  1951 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-11 13:31:16.685  6922  6922 D AndroidRuntime: Shutting down VM
,08-11 13:31:16.758   915  2043 I art     : Explicit concurrent mark sweep GC freed 4055(222KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 3.048ms total 168.616ms
,08-11 13:31:16.796  6947  6947 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-11 13:31:16.844   915  1893 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6972 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-11 13:31:16.845   915  1893 I ActivityManager: Killing 6467:com.google.android.talk/u0a61 (adj 15): empty #11
,08-11 13:31:16.916   915  1930 W libprocessgroup: failed to open /acct/uid_10061/pid_6467/cgroup.procs: No such file or directory
,08-11 13:31:16.977   915  1067 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6994 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-11 13:31:16.986  6972  6972 I AppUp4:AppBoxCP: onCreate
08-11 13:31:17.010  6972  6972 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-11 13:31:17.053  6972  6972 E SQLiteDatabase: Failed to open database '/data/data/com.lge.appbox.client/databases/appbox.db'.
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-11 13:31:17.053  6972  6972 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-11 13:31:17.053  6972  6972 D AndroidRuntime: Shutting down VM
,--------- beginning of crash
08-11 13:31:17.062  6972  6972 E AndroidRuntime: FATAL EXCEPTION: main
08-11 13:31:17.062  6972  6972 E AndroidRuntime: Process: com.lge.appbox.client, PID: 6972
08-11 13:31:17.062  6972  6972 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.lge.appbox.databases.AppBoxContentProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5106)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4698)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4638)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.app.ActivityThread.access$1500(ActivityThread.java:155)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1384)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:212)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:196)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:464)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:186)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:178)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:916)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:893)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:796)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1254)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at com.lge.appbox.databases.AppBoxContentProvider.onCreate(AppBoxContentProvider.java:147)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1720)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1689)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5103)
08-11 13:31:17.062  6972  6972 E AndroidRuntime: 	... 11 more
08-11 13:31:17.087   915  7012 E DropBoxManagerService: Can't write: system_app_crash
08-11 13:31:17.087   915  7012 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
08-11 13:31:17.087   915  7012 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-11 13:31:17.087   915  7012 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-11 13:31:17.087   915  7012 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-11 13:31:17.087   915  7012 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-11 13:31:17.087   915  7012 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-11 13:31:17.087   915  7012 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$21.run(ActivityManagerService.java:12621)
08-11 13:31:17.087   915  7012 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-11 13:31:17.087   915  7012 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-11 13:31:17.087   915  7012 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-11 13:31:17.087   915  7012 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-11 13:31:17.087   915  7012 E DropBoxManagerService: 	... 5 more

```
