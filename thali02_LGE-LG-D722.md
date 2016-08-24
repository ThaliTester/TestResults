#### Test 79763830e108614_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-24 13:24:35.731   289   369 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-24 13:24:37.980  6694  6694 D AndroidRuntime: 
08-24 13:24:37.980  6694  6694 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-24 13:24:37.991  6694  6694 D AndroidRuntime: CheckJNI is OFF
08-24 13:24:38.390  6694  6694 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-24 13:24:38.401   844  1894 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-24 13:24:38.446   844  1894 D ActivityManager: setTaskToReturnTo : TaskRecord{3aaa48a9 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-24 13:24:38.447   844  1894 D ActivityManager: setTaskToReturnTo : TaskRecord{3aaa48a9 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-24 13:24:38.454   844  1894 D WindowStateEx: AppWindowTokenEx init.. 
08-24 13:24:38.510   844  1894 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6712 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-24 13:24:38.511   844  1894 D InputDispatcher: Focus left window: Window{13e742e7 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-24 13:24:38.514  6694  6694 D AndroidRuntime: Shutting down VM
08-24 13:24:38.523  1949  1949 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-24 13:24:38.551   844   844 V ActivityManager: Display changed displayId=0
08-24 13:24:38.552  1770  1770 D DSDPConnection: Display #0 changed.
08-24 13:24:38.683  6712  6712 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-24 13:24:38.805  6712  6712 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-24 13:24:38.860  6712  6712 I LibraryLoader: Time to load native libraries: 1 ms (timestamps 6751-6752)
08-24 13:24:38.861  6712  6712 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 13:24:38.902  6712  6712 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {26142e30}
08-24 13:24:38.904  6712  6712 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 13:24:38.905  6712  6712 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 13:24:38.918  6712  6712 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-24 13:24:38.919  6712  6712 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 13:24:38.920  6712  6712 E SysUtils: ApplicationContext is null in ApplicationStatus
08-24 13:24:38.942  6712  6712 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-24 13:24:38.949  6712  6712 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 13:24:38.949  6712  6712 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 13:24:38.950  6712  6712 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 13:24:38.950  6712  6712 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 13:24:38.950  6712  6712 I Adreno-EGL: Build Date: 03/02/15 Mon
08-24 13:24:38.950  6712  6712 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-24 13:24:38.950  6712  6712 I Adreno-EGL: Remote Branch: 
08-24 13:24:38.950  6712  6712 I Adreno-EGL: Local Patches: 
08-24 13:24:38.950  6712  6712 I Adreno-EGL: Reconstruct Branch: 
08-24 13:24:39.009   275   275 V AudioPolicyService: registerClient() client 0xb551cb00, uid 10030
08-24 13:24:39.019   844  1015 D BluetoothManagerService: Message: 20
08-24 13:24:39.019   844  1015 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@138f5d1d:true
08-24 13:24:39.032  2060  2078 D BluetoothAdapterService(810281006): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2fc29bf4
08-24 13:24:39.079   844   898 W ActivityManager: Activity pause timeout for ActivityRecord{385a9e2e u0 com.test.thalitest/.MainActivity t259}
08-24 13:24:39.231  6712  6712 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 13:24:39.246  6712  6712 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-24 13:24:39.254  6712  6712 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-24 13:24:39.258  6712  6712 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-24 13:24:39.258  6712  6712 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-24 13:24:39.276  6712  6712 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-24 13:24:39.284  6712  6712 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 13:24:39.284  6712  6712 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 13:24:39.354  6712  6712 I Activity: Activity.onPostResume() called 
08-24 13:24:39.360  6712  6756 D OpenGLRenderer: Render dirty regions requested: true
08-24 13:24:39.360  6712  6756 I OpenGLRenderer: Initialized EGL, version 1.4
08-24 13:24:39.370  6712  6756 D OpenGLRenderer: Enabling debug mode 0
08-24 13:24:39.389  6712  6712 D Atlas   : Validating map...
08-24 13:24:39.395   844  1928 D SplitWindow: check instance of lgWin Window{1de6c78d u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-24 13:24:39.413  6712  6743 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-24 13:24:39.444   844  1014 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-24 13:24:39.446   844  1014 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-24 13:24:39.446  1373  1373 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-24 13:24:39.446  1373  1373 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-24 13:24:39.446  1373  1373 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-24 13:24:39.446  1373  1373 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-24 13:24:39.448   844  1014 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-24 13:24:39.448   844  1014 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-24 13:24:39.448   844  1014 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-24 13:24:39.449   844  1014 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1106e206,  pkg=WindowManager.LayoutParams
08-24 13:24:39.449   844  1014 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-24 13:24:39.455   844  1892 D InputDispatcher: Focus entered window: Window{1de6c78d u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-24 13:24:39.481   844   864 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-24 13:24:39.499   844  1016 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +917ms (total +1s43ms)
08-24 13:24:39.501   844  1016 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{385a9e2e u0 com.test.thalitest/.MainActivity t259} time:177392
08-24 13:24:39.505  6712  6712 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-24 13:24:39.506  6712  6712 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3ff384ea time:177398
08-24 13:24:39.556  6712  6712 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-24 13:24:39.560  1632  1632 E b       : Unable to connect to the editor to retrieve text... will retry later
08-24 13:24:39.585  6712  6712 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-24 13:24:39.634  6712  6712 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6712
,08-24 13:24:39.662  1734  4415 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-24 13:24:39.991  6712  6712 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 13:24:40.142  6712  6758 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1635606784
,08-24 13:24:40.158  6712  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 13:24:40.158  6712  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 13:24:40.158  6712  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 13:24:40.158  6712  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 13:24:40.158  6712  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-24 13:24:40.158  6712  6758 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ad3158e added. We now have 1 listener(s)
,08-24 13:24:40.165   844  1972 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 13:24:40.169  6712  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
08-24 13:24:40.171  6712  6758 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
,08-24 13:24:40.172  6712  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 13:24:40.173  6712  6758 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 13:24:40.178  6712  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 13:24:40.178  6712  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 13:24:40.178  6712  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 13:24:40.178  6712  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-24 13:24:40.178  6712  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 13:24:40.178  6712  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 13:24:40.178  6712  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 13:24:40.178  6712  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 13:24:40.178  6712  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 13:24:40.178  6712  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 13:24:40.178  6712  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 13:24:40.178  6712  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 13:24:40.178  6712  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 13:24:40.178  6712  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 13:24:40.179  6712  6758 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@286cad45 added. We now have 1 listener(s)
08-24 13:24:40.179  6712  6758 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-24 13:24:40.191  6712  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-24 13:24:40.191  6712  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-24 13:24:40.193  6712  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 13:24:40.193  6712  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 13:24:40.193  6712  6758 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-24 13:24:40.198  6712  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 13:24:40.198   844  2011 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 13:24:40.199  6712  6758 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-24 13:24:40.211  2060  3575 D BluetoothAdapterService(810281006): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2fc29bf4
,08-24 13:24:40.213  6712  6758 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-24 13:24:40.213  6712  6758 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 13:24:40.213  6712  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 13:24:40.213  6712  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 13:24:40.213  6712  6758 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 13:24:40.213  6712  6758 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 13:24:40.213  6712  6758 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 13:24:40.213  6712  6758 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 13:24:40.213  6712  6758 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 13:24:40.213  6712  6758 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 13:24:40.213  6712  6758 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 13:24:40.215  6712  6712 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 13:24:40.218  6712  6712 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 13:24:40.219  6712  6758 I io.jxcore.node.LifeCycleMonitor: start: OK
08-24 13:24:40.250  6712  6712 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 13:24:40.395  6712  6726 I art     : CheckpointMarkThreadRoots callback created = 0xb066bfd0
,08-24 13:24:40.424  6712  6726 I art     : CheckpointMarkThreadRoots callback created = 0xb066bfa0
,08-24 13:24:40.735   289   369 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-24 13:24:41.030  6712  6764 W jxcore-log: Initializing JXcore engine
,08-24 13:24:41.032  6712  6764 W jxcore-log: JXcore engine is ready
08-24 13:24:41.180  6764  6764 W Thread-799: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7492]" dev="sockfs" ino=7492 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-24 13:24:41.180  6764  6764 W Thread-799: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-24 13:24:41.180  6764  6764 W Thread-799: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6407]" dev="sockfs" ino=6407 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-24 13:24:41.180  6764  6764 W Thread-799: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-24 13:24:41.180  6764  6764 W Thread-799: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-24 13:24:41.180  6764  6764 W Thread-799: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[31468]" dev="sockfs" ino=31468 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-24 13:24:41.210  6712  6764 W jxcore-log: Starting JXcore engine
,08-24 13:24:41.356  6712  6764 W jxcore-log: Platform android
08-24 13:24:41.356  6712  6764 W jxcore-log: 
08-24 13:24:41.356  6712  6764 W jxcore-log: Process ARCH arm
08-24 13:24:41.356  6712  6764 W jxcore-log: 
,08-24 13:24:41.622  6712  6764 I jxcore-log: JXcore Cordova bridge is ready!
08-24 13:24:41.622  6712  6764 I jxcore-log: 
,08-24 13:24:41.622  6712  6764 W jxcore-log: JXcore engine is started
08-24 13:24:41.628  6712  6758 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-24 13:24:41.630  6712  6712 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-24 13:24:45.740   289   369 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-24 13:24:46.570   844   864 I ActivityManager: Process com.google.android.apps.docs (pid 6327) has died
,08-24 13:24:46.576   844  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{ee5ba8 type 2 when 184387 com.google.android.gms} when 184387
,08-24 13:24:49.365  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:24:49.365  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:24:49.365  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:24:49.365  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:24:49.365  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 13:24:49.383   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-24 13:24:49.404  1873  2051 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:24:49.404  1873  2051 D LEDHandler: Battery Level Remaining: 100%
08-24 13:24:49.404  1873  2051 D LEDHandler: Battery Temp: 303, mChargingStatus=5, mChargingStop=false
,08-24 13:24:49.407  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 303
08-24 13:24:49.407  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:24:49.407  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 303
08-24 13:24:49.407   844   844 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:24:49.407   844   844 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:24:49.407   844  1313 D WifiController: battery changed pluggedType: 2
08-24 13:24:49.409  1900  1900 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-24 13:24:49.409  1900  1900 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-24 13:24:49.411  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:24:49.413  2060  3587 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 13:24:49.414  6372  6372 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 13:24:50.744   289   369 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-24 13:24:54.679   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:24:54.679   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:24:54.679   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 192571600921; DSPS: 6408523; Offset : -3012455499
,08-24 13:24:55.749   289   369 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-24 13:24:56.948  6712  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-24 13:24:56.948  6712  6764 I jxcore-log: 
08-24 13:24:56.951  6712  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-24 13:24:56.951  6712  6764 I jxcore-log: 
,08-24 13:24:56.956  2060  2078 D BluetoothAdapterService(810281006): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2fc29bf4
08-24 13:24:56.957  6712  6764 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 13:24:56.957  6712  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 13:24:56.957  6712  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 13:24:56.957  6712  6764 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 13:24:56.957  6712  6764 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 13:24:56.957  6712  6764 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 13:24:56.957  6712  6764 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 13:24:56.957  6712  6764 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 13:24:56.959  2060  2078 D BluetoothAdapterService(810281006): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2fc29bf4
08-24 13:24:56.960  6712  6764 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-24 13:24:56.963  6712  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-24 13:24:56.963  6712  6764 I jxcore-log: 
08-24 13:24:56.966  6712  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-24 13:24:56.966  6712  6764 I jxcore-log: 
,08-24 13:24:57.765  6712  6764 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-24 13:24:57.765  6712  6764 I jxcore-log: Failed to execute UT.
08-24 13:24:57.765  6712  6764 I jxcore-log: 
,08-24 13:24:57.768  6712  6764 I jxcore-log: Unit Test app is loaded
08-24 13:24:57.768  6712  6764 I jxcore-log: 
08-24 13:24:57.782  6712  6764 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-24 13:24:57.782  6712  6764 I jxcore-log: 
,08-24 13:24:57.789  6712  6764 I jxcore-log: My device name is: LGE-LG-D722
08-24 13:24:57.789  6712  6764 I jxcore-log: 
08-24 13:24:57.791  6712  6712 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-24 13:24:57.792  6712  6764 I jxcore-log: WARN testUtils: myNameCallback not set!
08-24 13:24:57.792  6712  6764 I jxcore-log: 
08-24 13:25:00.044  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:25:00.044  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-24 13:25:00.049  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
08-24 13:25:00.051  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:25:00.051  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:25:00.052  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:25:00.053  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:25:00.754   289   369 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-24 13:25:04.149  6712  6764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-24 13:25:04.149  6712  6764 I jxcore-log: 
,08-24 13:25:05.609  6712  6764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-24 13:25:05.609  6712  6764 I jxcore-log: 
,08-24 13:25:05.646  6712  6764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-24 13:25:05.646  6712  6764 I jxcore-log: 
,08-24 13:25:05.653  6712  6764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-24 13:25:05.653  6712  6764 I jxcore-log: 
08-24 13:25:05.678  6712  6764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-24 13:25:05.678  6712  6764 I jxcore-log: 
,08-24 13:25:05.684  6712  6764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-24 13:25:05.684  6712  6764 I jxcore-log: 
08-24 13:25:05.759   289   369 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-24 13:25:10.705  6712  6764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-24 13:25:10.705  6712  6764 I jxcore-log: 
,08-24 13:25:10.723  6712  6764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-24 13:25:10.723  6712  6764 I jxcore-log: 
,08-24 13:25:10.736  6712  6764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-24 13:25:10.736  6712  6764 I jxcore-log: 
,08-24 13:25:10.764   289   369 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-24 13:25:10.985  6712  6764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-24 13:25:10.985  6712  6764 I jxcore-log: 
,08-24 13:25:12.289  6712  6764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-24 13:25:12.289  6712  6764 I jxcore-log: 
,08-24 13:25:12.664  6712  6764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-24 13:25:12.664  6712  6764 I jxcore-log: 
,08-24 13:25:12.675  6712  6764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-24 13:25:12.675  6712  6764 I jxcore-log: 
,08-24 13:25:12.971  6712  6764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-24 13:25:12.971  6712  6764 I jxcore-log: 
,08-24 13:25:13.002  6712  6764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-24 13:25:13.002  6712  6764 I jxcore-log: 
,08-24 13:25:13.009  6712  6764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-24 13:25:13.009  6712  6764 I jxcore-log: 
,08-24 13:25:13.017  6712  6764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-24 13:25:13.017  6712  6764 I jxcore-log: 
,08-24 13:25:13.040  6712  6764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-24 13:25:13.040  6712  6764 I jxcore-log: 
,08-24 13:25:13.069  6712  6764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-24 13:25:13.069  6712  6764 I jxcore-log: 
,08-24 13:25:13.196  6712  6764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-24 13:25:13.196  6712  6764 I jxcore-log: 
,08-24 13:25:13.204  6712  6764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-24 13:25:13.204  6712  6764 I jxcore-log: 
,08-24 13:25:13.240  6712  6764 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-24 13:25:13.240  6712  6764 I jxcore-log: 
,08-24 13:25:13.254  2060  2078 D BluetoothAdapterService(810281006): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2fc29bf4
,08-24 13:25:13.255  6712  6764 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
,08-24 13:25:13.390  6712  6764 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-24 13:25:13.390  6712  6764 I jxcore-log: 
,08-24 13:25:14.680   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:25:14.680   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:25:14.680   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 212572457737; DSPS: 7063911; Offset : -3012453070
,08-24 13:25:15.769   289   369 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-24 13:25:20.773   289   369 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-24 13:25:25.778   289   369 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-24 13:25:29.360   844  1286 D PowerManagerServiceEx: acquireWakeLockInternal: lock=682679303, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=844
,08-24 13:25:29.364   844  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3ba18a54 type 2 when 214946 android} when 214946
08-24 13:25:29.500   844   844 D PowerManagerServiceEx: releaseWakeLockInternal: lock=682679303 [*alarm*], flags=0x0
,08-24 13:25:30.782   289   369 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-24 13:25:34.681   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:25:34.681   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:25:34.681   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 232573208874; DSPS: 7719296; Offset : -3012465108
,08-24 13:25:35.787   289   369 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-24 13:25:40.792   289   369 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-24 13:25:45.796   289   369 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-24 13:25:49.527   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-24 13:25:49.529  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:25:49.536  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:25:49.536  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:25:49.536  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
08-24 13:25:49.537  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:25:49.580  2060  3587 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:25:49.583  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 300
08-24 13:25:49.584  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:25:49.585  1900  1900 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-24 13:25:49.585  1900  1900 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-24 13:25:49.586  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 300
08-24 13:25:49.588  1873  2051 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:25:49.588  1873  2051 D LEDHandler: Battery Level Remaining: 100%
08-24 13:25:49.588  1873  2051 D LEDHandler: Battery Temp: 300, mChargingStatus=5, mChargingStop=false
08-24 13:25:49.590  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:25:49.593   844   844 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:25:49.593   844   844 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 13:25:49.597   844  1313 D WifiController: battery changed pluggedType: 2
08-24 13:25:49.599  6372  6372 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 13:25:50.801   289   369 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-24 13:25:54.682   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:25:54.682   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:25:54.682   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 252573985481; DSPS: 8374681; Offset : -3012451076
,08-24 13:25:55.805   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:26:00.042  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:26:00.042  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:26:00.042  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:26:00.046  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:26:00.046  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:26:00.047  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:26:00.048  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:26:00.810   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:26:05.086  3352  4371 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-24 13:26:05.814   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:26:10.819   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:26:14.683   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:26:14.683   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:26:14.683   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 272574811411; DSPS: 9030069; Offset : -3012479872
,08-24 13:26:15.824   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:26:20.828   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:26:25.833   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:26:30.837   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:26:34.683   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:26:34.683   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:26:34.683   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 292575404424; DSPS: 9685448; Offset : -3012467084
,08-24 13:26:35.842   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:26:40.846   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:26:45.851   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:26:49.688  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:26:49.688  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:26:49.688  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:26:49.688  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 13:26:49.690   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-24 13:26:49.691  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:26:49.730  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 298
08-24 13:26:49.730  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:26:49.730  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 298
,08-24 13:26:49.733  1900  1900 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-24 13:26:49.734  1873  2051 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:26:49.734  1873  2051 D LEDHandler: Battery Level Remaining: 100%
08-24 13:26:49.734  1873  2051 D LEDHandler: Battery Temp: 298, mChargingStatus=5, mChargingStop=false
08-24 13:26:49.735  2060  3587 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 13:26:49.735  1900  1900 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-24 13:26:49.737  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:26:49.740   844   844 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:26:49.740   844   844 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:26:49.741   844  1313 D WifiController: battery changed pluggedType: 2
08-24 13:26:49.743  6372  6372 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-24 13:26:50.856   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:26:54.684   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:26:54.684   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:26:54.684   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 312576084521; DSPS: 10340830; Offset : -3012458270
,08-24 13:26:55.860   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:27:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:27:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:27:00.039  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:27:00.043  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:27:00.043  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:27:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:27:00.044  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:27:00.865   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:27:05.869   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:27:10.874   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:27:14.685   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:27:14.685   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:27:14.685   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 332576841440; DSPS: 10996215; Offset : -3012465826
,08-24 13:27:15.878   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:27:20.892   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:27:25.211   844  3376 I LocationManagerService: remove 1756e8f8
,08-24 13:27:25.215   844  3376 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-24 13:27:25.215   844  3376 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-24 13:27:25.215   844  3376 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-24 13:27:25.216   844  3376 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-24 13:27:25.216   844  3376 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-24 13:27:25.896   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:27:30.901   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:27:34.685   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:27:34.685   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:27:34.686   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 352577600391; DSPS: 11651600; Offset : -3012467835
,08-24 13:27:35.905   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:27:40.910   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:27:45.914   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:27:49.860   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-24 13:27:49.863  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:27:49.866  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:27:49.870  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:27:49.870  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:27:49.870  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
08-24 13:27:49.901  2060  3587 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:27:49.904  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
08-24 13:27:49.905  1900  1900 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-24 13:27:49.905  1900  1900 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-24 13:27:49.906  1873  2051 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:27:49.906  1873  2051 D LEDHandler: Battery Level Remaining: 100%
08-24 13:27:49.906  1873  2051 D LEDHandler: Battery Temp: 296, mChargingStatus=5, mChargingStop=false
08-24 13:27:49.908  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:27:49.908  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
08-24 13:27:49.910  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:27:49.915   844   844 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:27:49.915   844   844 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 13:27:49.918   844  1313 D WifiController: battery changed pluggedType: 2
08-24 13:27:49.918  6372  6372 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 13:27:50.919   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:27:54.686   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:27:54.686   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:27:54.686   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 372578363665; DSPS: 12306985; Offset : -3012467710
,08-24 13:27:55.924   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:28:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:28:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:28:00.039  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:28:00.043  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:28:00.043  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:28:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:28:00.044  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:28:00.928   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:28:04.280  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,08-24 13:28:04.283  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:28:04.283  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:28:04.283  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:28:04.283  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
08-24 13:28:04.303   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-24 13:28:04.337  2060  3587 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:28:04.340  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
08-24 13:28:04.340  1900  1900 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-24 13:28:04.340  1900  1900 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-24 13:28:04.341  1873  2051 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:28:04.341  1873  2051 D LEDHandler: Battery Level Remaining: 100%
08-24 13:28:04.342  1873  2051 D LEDHandler: Battery Temp: 296, mChargingStatus=5, mChargingStop=false
08-24 13:28:04.343  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:28:04.343  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
08-24 13:28:04.345  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:28:04.349   844   844 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:28:04.349   844   844 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 13:28:04.352   844  1313 D WifiController: battery changed pluggedType: 2
08-24 13:28:04.353  6372  6372 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 13:28:04.387  2060  3587 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:28:04.390  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 296
08-24 13:28:04.391  1900  1900 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-24 13:28:04.391  1900  1900 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-24 13:28:04.392  1873  2051 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:28:04.392  1873  2051 D LEDHandler: Battery Level Remaining: 100%
08-24 13:28:04.392  1873  2051 D LEDHandler: Battery Temp: 296, mChargingStatus=5, mChargingStop=false
08-24 13:28:04.394  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:28:04.394  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 296
08-24 13:28:04.396  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:28:04.400   844   844 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:28:04.400   844   844 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 13:28:04.403   844  1313 D WifiController: battery changed pluggedType: 2
08-24 13:28:04.404  6372  6372 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 13:28:05.933   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:28:10.937   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:28:14.687   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:28:14.687   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:28:14.687   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 392579112303; DSPS: 12962369; Offset : -3012451103
,08-24 13:28:15.942   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:28:16.155  6184  6222 I PlayCommon: [742] com.google.android.play.a.l.e(787): Preparing logs for uploading
,08-24 13:28:16.172  1734  1734 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 13:28:16.185  1734  1734 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 13:28:16.189  1734  1734 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
08-24 13:28:16.242   844  1383 I NotificationManager: android: cancelAsUser(2) by android
,08-24 13:28:16.249  6184  6222 I PlayCommon: [742] com.google.android.play.a.l.a(927): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
08-24 13:28:16.271  6184  6222 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-24 13:28:16.271  6184  6222 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
08-24 13:28:16.272  6184  6222 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
08-24 13:28:16.272  6184  6222 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,08-24 13:28:16.279   267  1006 E BandwidthController: [LG DATA] No such appUid: 10036
08-24 13:28:16.279   267  1006 D DnsProxyListener: App 10036 tries DNS query. Accept family:0 protocol:0
08-24 13:28:16.280   267  6824 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
08-24 13:28:16.280   267  6824 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
08-24 13:28:16.280   267  6824 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
08-24 13:28:16.281   267  6824 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
08-24 13:28:16.325   267  6824 D libc-netbsd: res_queryN name = xxxxx succeed
,08-24 13:28:16.328  6184  6222 I System.out: propertyValue:false
08-24 13:28:16.610  6184  6222 I PlayCommon: [742] com.google.android.play.a.l.a(1002): Successfully uploaded logs.
,08-24 13:28:20.947   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:28:25.951   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:28:30.956   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:28:34.688   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:28:34.688   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:28:34.688   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 412579803701; DSPS: 13617752; Offset : -3012461974
,08-24 13:28:35.960   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:28:40.965   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:28:45.969   289   369 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-24 13:28:50.007   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-24 13:28:50.009  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:28:50.016  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:28:50.017  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:28:50.017  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:28:50.017  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
08-24 13:28:50.050  2060  3587 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:28:50.053  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 295
08-24 13:28:50.054  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:28:50.054  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 295
08-24 13:28:50.055  1900  1900 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-24 13:28:50.055  1900  1900 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-24 13:28:50.056  1873  2051 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:28:50.056  1873  2051 D LEDHandler: Battery Level Remaining: 100%
08-24 13:28:50.056  1873  2051 D LEDHandler: Battery Temp: 295, mChargingStatus=5, mChargingStop=false
08-24 13:28:50.059  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:28:50.063   844   844 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:28:50.063   844   844 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 13:28:50.066   844  1313 D WifiController: battery changed pluggedType: 2
08-24 13:28:50.067  6372  6372 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 13:28:50.974   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:28:54.689   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:28:54.689   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:28:54.689   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 432580790778; DSPS: 14273144; Offset : -3012451408
,08-24 13:28:55.978   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:29:00.001   844  1286 D PowerManagerServiceEx: acquireWakeLockInternal: lock=682679303, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=844
,08-24 13:29:00.025   844   844 D PowerManagerServiceEx: releaseWakeLockInternal: lock=682679303 [*alarm*], flags=0x0
,08-24 13:29:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:29:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:29:00.039  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:29:00.042  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:29:00.042  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:29:00.043  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:29:00.044  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:29:00.847   844  1972 I ActivityManager: Process com.google.android.apps.plus (pid 6236) has died
,08-24 13:29:00.983   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:29:05.988   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:29:10.992   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:29:14.689   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:29:14.689   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:29:14.689   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 452581559728; DSPS: 14928530; Offset : -3012475732
,08-24 13:29:15.997   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:29:21.002   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:29:26.006   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:29:31.011   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:29:34.690   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:29:34.690   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:29:34.690   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 472582243367; DSPS: 15583912; Offset : -3012464001
,08-24 13:29:36.015   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:29:41.020   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:29:46.024   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:29:50.168  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:29:50.168  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:29:50.168  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:29:50.169  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 13:29:50.170   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-24 13:29:50.177  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:29:50.212  2060  3587 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:29:50.215  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 294
08-24 13:29:50.215  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:29:50.215  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 294
08-24 13:29:50.216  1900  1900 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-24 13:29:50.216  1900  1900 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-24 13:29:50.218  1873  2051 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:29:50.218  1873  2051 D LEDHandler: Battery Level Remaining: 100%
08-24 13:29:50.218  1873  2051 D LEDHandler: Battery Temp: 294, mChargingStatus=5, mChargingStop=false
08-24 13:29:50.220  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:29:50.225   844   844 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:29:50.225   844   844 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 13:29:50.228   844  1313 D WifiController: battery changed pluggedType: 2
08-24 13:29:50.229  6372  6372 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 13:29:51.029   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:29:54.691   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:29:54.691   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:29:54.691   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 492582995130; DSPS: 16239297; Offset : -3012474370
,08-24 13:29:56.034   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:30:00.038  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:30:00.038  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:30:00.038  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:30:00.042  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:30:00.042  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:30:00.043  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:30:00.044  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:30:01.038   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:30:06.043   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:30:11.047   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:30:14.692   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:30:14.692   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:30:14.692   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 512583746424; DSPS: 16894681; Offset : -3012455809
,08-24 13:30:16.052   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:30:21.057   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:30:26.061   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:30:31.066   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:30:34.692   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:30:34.692   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:30:34.692   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 532584432406; DSPS: 17550064; Offset : -3012471888
,08-24 13:30:36.070   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:30:41.075   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:30:46.079   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:30:50.328  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:30:50.328  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:30:50.328  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:30:50.328  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 13:30:50.330   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-24 13:30:50.331  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:30:50.369  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
08-24 13:30:50.369  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:30:50.369  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
,08-24 13:30:50.373  1900  1900 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-24 13:30:50.373  1900  1900 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-24 13:30:50.374  1873  2051 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:30:50.374  1873  2051 D LEDHandler: Battery Level Remaining: 100%
08-24 13:30:50.374  1873  2051 D LEDHandler: Battery Temp: 293, mChargingStatus=5, mChargingStop=false
08-24 13:30:50.377  2060  3587 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 13:30:50.380   844   844 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:30:50.380   844   844 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:30:50.381   844  1313 D WifiController: battery changed pluggedType: 2
,08-24 13:30:50.385  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:30:50.386  6372  6372 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 13:30:51.084   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:30:54.693   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:30:54.693   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:30:54.693   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 552585200159; DSPS: 18205449; Offset : -3012467023
,08-24 13:30:56.089   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:31:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:31:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:31:00.039  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:31:00.043  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:31:00.043  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:31:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:31:00.045  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:31:01.093   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:31:06.098   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:31:11.102   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:31:14.694   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:31:14.694   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:31:14.694   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 572585964474; DSPS: 18860834; Offset : -3012465803
,08-24 13:31:16.107   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:31:21.111   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:31:26.120   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:31:31.125   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:31:34.695   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:31:34.695   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:31:34.695   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 592586650039; DSPS: 19516216; Offset : -3012451912
,08-24 13:31:36.129   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:31:41.134   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:31:46.139   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:31:50.487   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-24 13:31:50.495  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:31:50.495  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:31:50.495  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:31:50.495  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
08-24 13:31:50.496  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:31:50.530  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
08-24 13:31:50.531  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:31:50.531  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
,08-24 13:31:50.535  1873  2051 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:31:50.535  1873  2051 D LEDHandler: Battery Level Remaining: 100%
08-24 13:31:50.535  1873  2051 D LEDHandler: Battery Temp: 292, mChargingStatus=5, mChargingStop=false
08-24 13:31:50.535  2060  3587 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 13:31:50.536  1900  1900 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-24 13:31:50.536  1900  1900 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-24 13:31:50.538  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:31:50.542   844   844 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:31:50.543   844   844 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 13:31:50.545   844  1313 D WifiController: battery changed pluggedType: 2
08-24 13:31:50.546  6372  6372 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 13:31:51.143   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:31:54.695   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:31:54.695   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:31:54.695   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 612587420344; DSPS: 20171602; Offset : -3012474334
,08-24 13:31:56.148   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:32:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:32:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:32:00.039  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:32:00.043  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:32:00.043  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:32:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:32:00.044  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:32:01.152   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:32:06.157   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:32:06.344  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-24 13:32:06.347  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:32:06.347  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:32:06.347  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:32:06.347  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
08-24 13:32:06.371   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-24 13:32:06.405   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-24 13:32:06.408  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:32:06.408  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:32:06.409  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:32:06.409  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:32:06.409  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
08-24 13:32:06.483  2060  3587 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:32:06.486  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
08-24 13:32:06.486  1900  1900 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-24 13:32:06.486  1900  1900 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-24 13:32:06.488  1873  2051 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:32:06.488  1873  2051 D LEDHandler: Battery Level Remaining: 100%
08-24 13:32:06.488  1873  2051 D LEDHandler: Battery Temp: 293, mChargingStatus=5, mChargingStop=false
08-24 13:32:06.489  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:32:06.489  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
08-24 13:32:06.491  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:32:06.494   844   844 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:32:06.494   844   844 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:32:06.494   844  1313 D WifiController: battery changed pluggedType: 2
,08-24 13:32:06.500  6372  6372 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 13:32:06.538  2060  3587 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:32:06.541  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 293
08-24 13:32:06.542  1900  1900 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-24 13:32:06.542  1900  1900 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-24 13:32:06.543  1873  2051 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:32:06.543  1873  2051 D LEDHandler: Battery Level Remaining: 100%
08-24 13:32:06.543  1873  2051 D LEDHandler: Battery Temp: 293, mChargingStatus=5, mChargingStop=false
08-24 13:32:06.544  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:32:06.545  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 293
08-24 13:32:06.547  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:32:06.551   844   844 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:32:06.551   844   844 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 13:32:06.554   844  1313 D WifiController: battery changed pluggedType: 2
08-24 13:32:06.555  6372  6372 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 13:32:08.384   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-24 13:32:08.387  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:32:08.393  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:32:08.394  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:32:08.394  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:32:08.394  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
08-24 13:32:11.161   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:32:14.696   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:32:14.696   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:32:14.696   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 632588181066; DSPS: 20826987; Offset : -3012476994
,08-24 13:32:16.166   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:32:21.171   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:32:26.175   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:32:31.180   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:32:34.697   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:32:34.697   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:32:34.697   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 652588860901; DSPS: 21482369; Offset : -3012470474
,08-24 13:32:36.184   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:32:41.189   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:32:46.193   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:32:50.648  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:32:50.648  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:32:50.648  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:32:50.648  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 13:32:50.650   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-24 13:32:50.651  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:32:50.690  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 292
08-24 13:32:50.690  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:32:50.690  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 292
,08-24 13:32:50.692  1900  1900 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-24 13:32:50.692  1900  1900 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-24 13:32:50.694  1873  2051 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:32:50.694  1873  2051 D LEDHandler: Battery Level Remaining: 100%
08-24 13:32:50.694  1873  2051 D LEDHandler: Battery Temp: 292, mChargingStatus=5, mChargingStop=false
08-24 13:32:50.697  2060  3587 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 13:32:50.700   844   844 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:32:50.700   844   844 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:32:50.701   844  1313 D WifiController: battery changed pluggedType: 2
08-24 13:32:50.702  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-24 13:32:50.705  6372  6372 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 13:32:51.198   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:32:54.698   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:32:54.698   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:32:54.698   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 672589625112; DSPS: 22137754; Offset : -3012466988
,08-24 13:32:56.203   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:33:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:33:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:33:00.039  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:33:00.043  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:33:00.043  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:33:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:33:00.045  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:33:01.207   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:33:06.212   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:33:11.221   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:33:14.698   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:33:14.698   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:33:14.698   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 692590607293; DSPS: 22793146; Offset : -3012462021
,08-24 13:33:16.225   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:33:21.230   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:33:26.234   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:33:31.239   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:33:34.699   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:33:34.699   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:33:34.699   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 712591381244; DSPS: 23448532; Offset : -3012480928
,08-24 13:33:36.243   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:33:41.248   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:33:46.253   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:33:50.808  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:33:50.808  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:33:50.808  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:33:50.808  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 13:33:50.810   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-24 13:33:50.811  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:33:50.849  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 291
08-24 13:33:50.850  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:33:50.850  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 291
,08-24 13:33:50.852  1900  1900 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-24 13:33:50.852  1900  1900 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-24 13:33:50.854  1873  2051 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:33:50.854  1873  2051 D LEDHandler: Battery Level Remaining: 100%
08-24 13:33:50.854  1873  2051 D LEDHandler: Battery Temp: 291, mChargingStatus=5, mChargingStop=false
08-24 13:33:50.857  2060  3587 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 13:33:50.860   844   844 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:33:50.860   844   844 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:33:50.861   844  1313 D WifiController: battery changed pluggedType: 2
08-24 13:33:50.862  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-24 13:33:50.865  6372  6372 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 13:33:51.257   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:33:54.700   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:33:54.700   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:33:54.700   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 732592082850; DSPS: 24103914; Offset : -3012450891
,08-24 13:33:56.262   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:34:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:34:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:34:00.039  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:34:00.043  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:34:00.043  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:34:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:34:00.045  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:34:01.266   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:34:06.271   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:34:11.276   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:34:14.701   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:34:14.701   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:34:14.701   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 752592866124; DSPS: 24759300; Offset : -3012461283
,08-24 13:34:16.280   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:34:21.285   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:34:26.289   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:34:31.294   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:34:34.701   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:34:34.701   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:34:34.702   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 772593641481; DSPS: 25414686; Offset : -3012479226
,08-24 13:34:36.298   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:34:41.303   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:34:46.307   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:34:50.968  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:34:50.968  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:34:50.968  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:34:50.968  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 13:34:50.970   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-24 13:34:50.971  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:34:51.009  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
08-24 13:34:51.010  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:34:51.010  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
,08-24 13:34:51.012  1900  1900 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-24 13:34:51.012  1900  1900 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-24 13:34:51.014  1873  2051 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:34:51.014  1873  2051 D LEDHandler: Battery Level Remaining: 100%
08-24 13:34:51.014  1873  2051 D LEDHandler: Battery Temp: 290, mChargingStatus=5, mChargingStop=false
08-24 13:34:51.017  2060  3587 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 13:34:51.020   844   844 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:34:51.020   844   844 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:34:51.021   844  1313 D WifiController: battery changed pluggedType: 2
08-24 13:34:51.024  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-24 13:34:51.026  6372  6372 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 13:34:51.312   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:34:54.702   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:34:54.702   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:34:54.702   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 792594348817; DSPS: 26070069; Offset : -3012473612
,08-24 13:34:56.317   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:35:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:35:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:35:00.039  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:35:00.043  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:35:00.043  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:35:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:35:00.045  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:35:01.321   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:35:06.326   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:35:11.330   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:35:14.703   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:35:14.703   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:35:14.703   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 812595031101; DSPS: 26725451; Offset : -3012462794
,08-24 13:35:16.335   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:35:21.339   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:35:26.344   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:35:31.349   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:35:34.704   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:35:34.704   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:35:34.704   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 832595709999; DSPS: 27380833; Offset : -3012455283
,08-24 13:35:36.353   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:35:41.358   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:35:46.362   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:35:51.127   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-24 13:35:51.135  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:35:51.136  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:35:51.137  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:35:51.137  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:35:51.137  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
08-24 13:35:51.367   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:35:54.704   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:35:54.704   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:35:54.704   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 852596453794; DSPS: 28036218; Offset : -3012474244
,08-24 13:35:56.371   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:36:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:36:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:36:00.039  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:36:00.043  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:36:00.043  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:36:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:36:00.045  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:36:01.376   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:36:06.381   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:36:11.385   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:36:14.705   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:36:14.705   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:36:14.705   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 872597297953; DSPS: 28691605; Offset : -3012454243
,08-24 13:36:16.390   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:36:21.394   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:36:26.399   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:36:31.403   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:36:34.706   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:36:34.706   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:36:34.706   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 892598082216; DSPS: 29346991; Offset : -3012463254
,08-24 13:36:36.408   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:36:41.413   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:36:46.417   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:36:51.287   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-24 13:36:51.292  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:36:51.292  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:36:51.292  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:36:51.292  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
08-24 13:36:51.293  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:36:51.326  2060  3587 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:36:51.330  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 289
08-24 13:36:51.330  1900  1900 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-24 13:36:51.331  1900  1900 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-24 13:36:51.332  1873  2051 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:36:51.332  1873  2051 D LEDHandler: Battery Level Remaining: 100%
08-24 13:36:51.332  1873  2051 D LEDHandler: Battery Temp: 289, mChargingStatus=5, mChargingStop=false
08-24 13:36:51.333  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:36:51.333  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 289
08-24 13:36:51.335  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:36:51.340   844   844 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:36:51.340   844   844 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 13:36:51.343   844  1313 D WifiController: battery changed pluggedType: 2
08-24 13:36:51.345  6372  6372 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 13:36:51.422   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:36:54.707   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:36:54.707   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:36:54.707   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 912598857886; DSPS: 30002376; Offset : -3012450914
,08-24 13:36:56.426   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:37:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:37:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:37:00.039  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:37:00.043  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:37:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:37:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:37:00.045  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:37:01.431   289   369 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-24 13:37:06.436   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:37:11.440   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:37:14.707   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:37:14.707   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:37:14.708   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 932599618815; DSPS: 30657761; Offset : -3012454695
,08-24 13:37:16.445   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:37:21.449   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:37:26.454   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:37:28.710   844  1286 D PowerManagerServiceEx: acquireWakeLockInternal: lock=682679303, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=844
,08-24 13:37:28.715   844  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{385379bb type 2 when 946590 com.android.bluetooth} when 946590
08-24 13:37:28.914   844   864 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=6917 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-24 13:37:28.948  2060  3636 W bt-smp  : Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
08-24 13:37:28.948  2060  3636 W bt-smp  : Plain text(LSB ~ MSB) = 33 08 58 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-24 13:37:28.948  2060  3636 W bt-smp  : Encrypted text(LSB ~ MSB) = 9d 37 94 53 1e 2f a4 d6 43 18 71 92 83 7e 30 52 
08-24 13:37:28.948  2060  3636 W bt-btm  : Stopping oneshot timer
,08-24 13:37:29.114  6917  6917 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,08-24 13:37:29.125  6917  6917 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1fbb39c4
08-24 13:37:29.129   844   844 D PowerManagerServiceEx: releaseWakeLockInternal: lock=682679303 [*alarm*], flags=0x0
,08-24 13:37:31.458   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:37:34.709   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:37:34.709   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:37:34.709   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 952600796985; DSPS: 31313160; Offset : -3012464705
,08-24 13:37:36.463   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:37:41.468   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:37:46.472   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:37:51.448  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:37:51.448  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:37:51.448  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:37:51.448  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 13:37:51.450   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-24 13:37:51.451  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:37:51.477   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:37:54.709   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:37:54.709   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:37:54.709   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 972601561561; DSPS: 31968545; Offset : -3012463017
,08-24 13:37:56.482   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:38:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:38:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:38:00.039  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:38:00.043  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:38:00.043  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:38:00.045  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:38:00.045  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:38:01.486   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:38:06.491   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:38:11.496   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:38:14.710   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:38:14.710   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:38:14.710   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 992602254105; DSPS: 32623928; Offset : -3012472534
,08-24 13:38:16.500   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:38:21.505   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:38:26.509   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:38:31.514   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:38:34.711   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:38:34.711   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:38:34.711   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1012603020244; DSPS: 33279313; Offset : -3012469412
,08-24 13:38:36.518   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:38:41.523   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:38:46.528   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:38:51.532   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:38:51.608  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:38:51.608  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:38:51.608  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:38:51.608  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 13:38:51.610   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-24 13:38:51.611  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:38:51.650  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 288
08-24 13:38:51.650  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:38:51.650  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 288
,08-24 13:38:51.652  1900  1900 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-24 13:38:51.653  1900  1900 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-24 13:38:51.654  1873  2051 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:38:51.654  1873  2051 D LEDHandler: Battery Level Remaining: 100%
08-24 13:38:51.654  1873  2051 D LEDHandler: Battery Temp: 288, mChargingStatus=5, mChargingStop=false
08-24 13:38:51.657  2060  3587 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 13:38:51.660   844   844 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:38:51.660   844   844 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:38:51.661   844  1313 D WifiController: battery changed pluggedType: 2
08-24 13:38:51.662  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,08-24 13:38:51.665  6372  6372 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 13:38:54.712   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:38:54.712   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:38:54.712   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1032603788778; DSPS: 33934698; Offset : -3012463661
,08-24 13:38:56.537   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:39:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:39:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:39:00.039  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:39:00.043  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:39:00.043  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:39:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:39:00.045  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:39:01.541   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:39:06.546   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:39:11.550   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:39:14.712   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:39:14.712   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:39:14.712   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1052604491218; DSPS: 34590081; Offset : -3012463177
,08-24 13:39:16.555   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:39:21.560   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:39:26.564   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:39:31.569   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:39:34.713   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:39:34.713   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:39:34.713   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1072605286315; DSPS: 35245467; Offset : -3012461693
,08-24 13:39:36.573   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:39:41.578   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:39:46.582   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:39:51.587   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:39:51.768  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:39:51.768  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:39:51.768  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:39:51.768  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 13:39:51.770   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-24 13:39:51.771  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:39:54.714   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:39:54.714   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:39:54.714   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1092606087505; DSPS: 35900853; Offset : -3012454013
,08-24 13:39:56.591   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:40:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:40:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:40:00.039  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:40:00.044  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:40:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:40:00.045  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:40:00.045  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:40:01.596   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:40:06.601   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:40:11.605   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:40:14.715   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:40:14.715   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:40:14.715   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1112606773642; DSPS: 36556236; Offset : -3012469728
,08-24 13:40:16.610   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:40:21.614   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:40:26.619   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:40:31.623   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:40:34.715   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:40:34.715   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:40:34.716   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1132607641968; DSPS: 37211624; Offset : -3012455608
,08-24 13:40:36.628   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:40:41.633   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:40:46.637   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:40:51.642   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:40:51.928  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:40:51.928  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:40:51.928  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:40:51.928  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 13:40:51.930   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-24 13:40:51.931  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:40:51.970  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
08-24 13:40:51.970  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:40:51.970  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
,08-24 13:40:51.973  1900  1900 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-24 13:40:51.974  1900  1900 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-24 13:40:51.975  1873  2051 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:40:51.975  1873  2051 D LEDHandler: Battery Level Remaining: 100%
08-24 13:40:51.975  1873  2051 D LEDHandler: Battery Temp: 287, mChargingStatus=5, mChargingStop=false
08-24 13:40:51.976  2060  3587 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 13:40:51.977  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:40:51.980   844   844 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:40:51.980   844   844 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:40:51.981   844  1313 D WifiController: battery changed pluggedType: 2
08-24 13:40:51.983  6372  6372 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-24 13:40:54.716   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:40:54.716   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:40:54.716   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1152608487481; DSPS: 37867012; Offset : -3012464718
,08-24 13:40:56.646   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:41:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:41:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:41:00.039  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:41:00.044  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:41:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:41:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:41:00.045  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:41:01.651   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:41:06.655   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:41:11.660   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:41:14.717   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:41:14.717   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:41:14.717   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1172609264349; DSPS: 38522397; Offset : -3012450762
,08-24 13:41:16.665   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:41:21.669   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:41:26.674   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:41:31.678   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:41:34.727   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:41:34.727   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:41:34.728   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1192619372310; DSPS: 39178089; Offset : -3012474950
,08-24 13:41:36.683   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:41:41.687   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:41:46.692   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:41:51.697   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:41:52.087  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,08-24 13:41:52.090   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-24 13:41:52.096  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:41:52.097  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:41:52.097  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:41:52.097  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
08-24 13:41:54.728   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:41:54.728   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:41:54.728   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1212620336209; DSPS: 39833480; Offset : -3012457147
,08-24 13:41:56.701   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:42:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:42:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:42:00.039  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:42:00.043  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:42:00.043  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:42:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:42:00.045  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:42:01.706   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:42:06.304   844   896 I UsageStatsService: User[0] Flushing usage stats to disk
,08-24 13:42:06.710   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:42:11.715   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:42:14.729   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:42:14.729   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:42:14.729   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1232621014744; DSPS: 40488863; Offset : -3012480231
,08-24 13:42:16.719   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:42:21.724   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:42:26.729   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:42:31.733   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:42:34.730   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:42:34.730   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:42:34.730   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1252621770569; DSPS: 41144247; Offset : -3012456723
,08-24 13:42:36.738   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:42:41.742   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:42:46.747   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:42:51.751   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:42:52.248  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:42:52.248  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:42:52.248  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:42:52.248  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 13:42:52.250   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-24 13:42:52.251  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:42:52.291  2060  3587 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:42:52.294  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
08-24 13:42:52.294  1900  1900 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-24 13:42:52.295  1900  1900 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-24 13:42:52.296  1873  2051 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:42:52.296  1873  2051 D LEDHandler: Battery Level Remaining: 100%
08-24 13:42:52.296  1873  2051 D LEDHandler: Battery Temp: 286, mChargingStatus=5, mChargingStop=false
08-24 13:42:52.297  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:42:52.298  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
08-24 13:42:52.300  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:42:52.304   844   844 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:42:52.304   844   844 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 13:42:52.307   844  1313 D WifiController: battery changed pluggedType: 2
08-24 13:42:52.308  6372  6372 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 13:42:54.730   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:42:54.730   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:42:54.730   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1272622532019; DSPS: 41799632; Offset : -3012458396
,08-24 13:42:56.756   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:43:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:43:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:43:00.039  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:43:00.044  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:43:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:43:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:43:00.045  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:43:01.761   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:43:06.765   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:43:11.770   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:43:14.731   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:43:14.731   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:43:14.731   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1292623216699; DSPS: 42455015; Offset : -3012475567
,08-24 13:43:16.619  6184  6222 I PlayCommon: [742] com.google.android.play.a.l.e(787): Preparing logs for uploading
08-24 13:43:16.619  6184  6222 I PlayCommon: [742] com.google.android.play.a.l.e(789): No file ready to send
,08-24 13:43:16.774   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:43:21.779   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:43:26.783   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:43:31.788   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:43:34.732   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:43:34.732   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:43:34.732   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1312623968879; DSPS: 43110399; Offset : -3012455887
,08-24 13:43:36.793   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:43:41.797   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:43:46.802   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:43:51.806   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:43:52.427  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,08-24 13:43:52.429  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:43:52.430   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-24 13:43:52.430  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:43:52.431  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:43:52.431  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
08-24 13:43:52.464  2060  3587 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,08-24 13:43:52.468  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 286
08-24 13:43:52.468  1900  1900 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-24 13:43:52.469  1900  1900 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-24 13:43:52.470  1873  2051 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:43:52.470  1873  2051 D LEDHandler: Battery Level Remaining: 100%
08-24 13:43:52.470  1873  2051 D LEDHandler: Battery Temp: 286, mChargingStatus=5, mChargingStop=false
08-24 13:43:52.471  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:43:52.472  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 286
08-24 13:43:52.474  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:43:52.478   844   844 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:43:52.478   844   844 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-24 13:43:52.481   844  1313 D WifiController: battery changed pluggedType: 2
08-24 13:43:52.482  6372  6372 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 13:43:54.732   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:43:54.733   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:43:54.733   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1332624726527; DSPS: 43765784; Offset : -3012461230
,08-24 13:43:56.811   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:44:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:44:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:44:00.039  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:44:00.044  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:44:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:44:00.045  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:44:00.045  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:44:01.816   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:44:06.820   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:44:11.825   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:44:14.733   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:44:14.733   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:44:14.733   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1352625401364; DSPS: 44421166; Offset : -3012457858
,08-24 13:44:16.829   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:44:21.834   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:44:26.838   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:44:31.843   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:44:34.734   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:44:34.734   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:44:34.734   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1372626225262; DSPS: 45076553; Offset : -3012457780
,08-24 13:44:36.847   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:44:41.852   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:44:46.857   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:44:47.006   844  1286 D PowerManagerServiceEx: acquireWakeLockInternal: lock=682679303, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=844
,08-24 13:44:47.019   844  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{c43fed8 type 2 when 1384886 android} when 1384886
,08-24 13:44:47.037   844   844 D PowerManagerServiceEx: releaseWakeLockInternal: lock=682679303 [*alarm*], flags=0x0
,08-24 13:44:48.329   844   896 I ActivityManager: Start proc com.google.android.apps.plus for service com.google.android.apps.plus/.service.EsSyncAdapterService: pid=7012 uid=10086 gids={50086, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
,08-24 13:44:48.347   844   863 I ActivityManager: Process com.lge.qremote (pid 6397) has died
,08-24 13:44:48.357  6418  6418 D UEI.SmartControl: Service.onUnbind: IControl
08-24 13:44:48.358  6418  6418 D UEI.SmartControl: Service.onDestroy
08-24 13:44:48.360  6418  6418 D UEI.SmartControl: Shutdown IRRCPlayer... 
08-24 13:44:48.367  6418  6418 W irrc_jni: IRRCPlayer_nativeFinalize ++ 
08-24 13:44:48.367  6418  6418 D irrcClient: ~IrrcClient ++ 
08-24 13:44:48.367  6418  6418 D irrcClient: ~IrrcClient -- 
08-24 13:44:48.367  6418  6418 W irrc_jni: IRRCPlayer_nativeFinalize -- 
,08-24 13:44:48.367  6418  6418 D UEI.SmartControl: Blaster closed
08-24 13:44:48.367  6418  6418 D UEI.SmartControl: Blaster closed
08-24 13:44:48.368  6418  6418 D UEI.SmartControl: Shut down QS...
08-24 13:44:48.368  6418  6418 D UEI.SmartControl: Stopped file observer...
08-24 13:44:48.382  6418  6418 I UEI.SmartControl: QS lib stop result = true
,08-24 13:44:48.389  6418  6418 D UEI.SmartControl: QS shutdown complete
08-24 13:44:48.405  7012  7012 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-24 13:44:48.642   844   896 I NotificationManager: android: cancelAsUser(-1548111331) by android
,08-24 13:44:49.023   844  1059 I art     : Explicit concurrent mark sweep GC freed 61032(3MB) AllocSpace objects, 16(256KB) LOS objects, 33% free, 23MB/35MB, paused 2.863ms total 240.196ms
,08-24 13:44:49.130   844   896 I NotificationManager: android: cancelAsUser(2145784878) by android
,08-24 13:44:49.136  7012  7012 I NotificationManager: com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
08-24 13:44:49.429   275  1358 V AudioFlinger: 2902 died, releasing its sessions
,08-24 13:44:49.429   275  1358 V AudioFlinger:  pid 1770 @ 0
08-24 13:44:49.429   275  1358 V AudioFlinger:  pid 3219 @ 1
08-24 13:44:49.429   275  1358 V AudioFlinger:  pid 3219 @ 2
08-24 13:44:49.449   844  1972 I ActivityManager: Process com.lge.music (pid 2902) has died
,08-24 13:44:51.861   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:44:52.567  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,08-24 13:44:52.569   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-24 13:44:52.571  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:44:52.571  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:44:52.571  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:44:52.571  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
08-24 13:44:52.605  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
08-24 13:44:52.605  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:44:52.605  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
,08-24 13:44:52.608  2060  3587 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 13:44:52.610  1873  2051 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 13:44:52.610  1873  2051 D LEDHandler: Battery Level Remaining: 100%
08-24 13:44:52.610  1873  2051 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
08-24 13:44:52.610  1900  1900 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-24 13:44:52.611  1900  1900 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-24 13:44:52.614  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 13:44:52.616   844   844 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:44:52.616   844   844 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 13:44:52.616   844  1313 D WifiController: battery changed pluggedType: 2
08-24 13:44:52.616  6372  6372 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-24 13:44:54.735   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:44:54.735   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:44:54.735   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1392626923015; DSPS: 45731936; Offset : -3012461644
,08-24 13:44:56.866   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:45:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:45:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:45:00.039  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:45:00.044  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:45:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:45:00.045  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:45:00.045  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:45:01.870   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:45:06.875   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:45:11.880   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:45:14.735   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:45:14.735   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:45:14.735   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1412627593372; DSPS: 46387318; Offset : -3012462570
,08-24 13:45:16.884   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:45:18.355   844  1286 D PowerManagerServiceEx: acquireWakeLockInternal: lock=682679303, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=844
,08-24 13:45:18.359   844  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3d4ae025 type 2 when 1416235 android} when 1416235
08-24 13:45:18.365  6917  6917 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
08-24 13:45:18.386  6917  6917 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@1fbb39c4
,08-24 13:45:18.390   844   844 D PowerManagerServiceEx: releaseWakeLockInternal: lock=682679303 [*alarm*], flags=0x0
08-24 13:45:21.889   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:45:26.893   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:45:31.898   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:45:34.736   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:45:34.736   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:45:34.736   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1432628269458; DSPS: 47042700; Offset : -3012457949
,08-24 13:45:36.902   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:45:41.907   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:45:46.912   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:45:51.916   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:45:52.730   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-24 13:45:52.733  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:45:52.734  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:45:52.734  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:45:52.734  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:45:52.734  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
08-24 13:45:54.737   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:45:54.737   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:45:54.737   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1452628946273; DSPS: 47698082; Offset : -3012453458
,08-24 13:45:56.921   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:46:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:46:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:46:00.039  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:46:00.043  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:46:00.043  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:46:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
,08-24 13:46:00.045  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:46:01.925   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:46:06.930   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:46:11.934   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:46:14.738   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:46:14.738   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:46:14.738   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1472629685745; DSPS: 48353467; Offset : -3012476066
,08-24 13:46:16.939   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:46:21.943   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:46:26.948   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:46:31.953   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:46:34.739   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:46:34.739   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:46:34.739   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1492630792404; DSPS: 49008863; Offset : -3012468039
,08-24 13:46:36.957   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:46:41.962   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:46:46.966   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:46:51.971   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:46:52.887   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-24 13:46:52.890  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:46:52.891  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:46:52.897  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:46:52.897  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:46:52.897  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
08-24 13:46:54.739   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:46:54.739   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:46:54.739   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1512631543334; DSPS: 49664248; Offset : -3012481091
,08-24 13:46:56.976   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:47:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:47:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:47:00.039  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:47:00.043  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:47:00.043  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:47:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:47:00.045  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:47:01.980   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:47:06.985   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:47:11.989   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:47:14.740   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:47:14.740   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:47:14.740   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1532632218014; DSPS: 50319630; Offset : -3012477043
,08-24 13:47:16.994   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:47:21.998   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:47:27.003   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:47:32.008   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:47:34.741   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:47:34.741   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:47:34.741   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1552632971496; DSPS: 50975014; Offset : -3012457466
,08-24 13:47:37.012   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:47:42.017   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:47:47.021   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:47:52.026   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:47:53.047   468   468 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,08-24 13:47:53.055  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 13:47:53.055  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 13:47:53.056  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 13:47:53.056  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
08-24 13:47:53.057  1873  1873 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 13:47:54.741   844  1027 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 13:47:54.742   844  1027 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 13:47:54.742   844  1027 D sensors_hal_Time: tsOffsetIs: Apps: 1572633707634; DSPS: 51630398; Offset : -3012452578
,08-24 13:47:57.030   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:48:00.039  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 13:48:00.039  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 13:48:00.039  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,08-24 13:48:00.043  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 13:48:00.043  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:48:00.044  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
08-24 13:48:00.045  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 13:48:02.035   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-24 13:48:07.040   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
,TIME-OUT KILL (timeout was 1400000ms),08-24 13:48:10.343  7077  7077 D AndroidRuntime: 
08-24 13:48:10.343  7077  7077 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-24 13:48:10.356  7077  7077 D AndroidRuntime: CheckJNI is OFF
08-24 13:48:10.739  7077  7077 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
08-24 13:48:10.803   844   898 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
08-24 13:48:10.803   844   898 I ActivityManager: Killing 6712:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
08-24 13:48:10.855   844  2145 I WindowState: WIN DEATH: Window{1de6c78d u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-24 13:48:10.863   844  2145 D InputDispatcher: Focus left window: Window{1de6c78d u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-24 13:48:10.863   844  2145 D InputDispatcher: Window went away: Window{1de6c78d u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-24 13:48:10.911   844  1058 W PackageSettings: Skipping PackageSetting{cd8d8ca com.example.hello/10317} due to missing metadata
08-24 13:48:10.932   844   898 I ActivityManager:   Force finishing activity ActivityRecord{385a9e2e u0 com.test.thalitest/.MainActivity t259}
08-24 13:48:10.977   844  1928 W ActivityManager: Spurious death for ProcessRecord{2acae5fa 6712:com.test.thalitest/u0a30}, curProc for 6712: null
08-24 13:48:10.983   844  1058 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
08-24 13:48:11.048  1949  1949 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
08-24 13:48:11.081  1373  1373 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-24 13:48:11.094  2024  2024 I art     : Explicit concurrent mark sweep GC freed 1667(108KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 12MB/20MB, paused 1.505ms total 101.663ms
08-24 13:48:11.098  1900  1900 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
08-24 13:48:11.098  1949  1949 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
08-24 13:48:11.110  1734  2560 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-24 13:48:11.116   844  1288 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-24 13:48:11.124  3712  3712 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-24 13:48:11.128  3712  3712 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-24 13:48:11.128  3712  3712 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-24 13:48:11.128  3712  3712 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-24 13:48:11.129  3712  3712 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 13:48:11.129  3712  3712 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 13:48:11.129  3712  3712 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-24 13:48:11.129  3712  3712 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-24 13:48:11.129  3712  3712 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 13:48:11.129  3712  3712 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 13:48:11.129  3712  3712 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-24 13:48:11.129  3712  3712 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-24 13:48:11.159   844   898 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7108 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-24 13:48:11.207   844  1059 I ActivityManager: Start proc com.lge.lockscreensettings for content provider com.lge.lockscreensettings/.LockSettingsProvider: pid=7114 uid=10069 gids={50069, 9997, 1028, 1015} abi=armeabi-v7a
08-24 13:48:11.219   844   844 I art     : Explicit concurrent mark sweep GC freed 14411(1006KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 23MB/35MB, paused 3.512ms total 190.177ms
08-24 13:48:11.223   844  1058 I art     : WaitForGcToComplete blocked for 88.471ms for cause Explicit
08-24 13:48:11.236  3352  3352 I art     : Explicit concurrent mark sweep GC freed 16506(1004KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 16MB/22MB, paused 965us total 224.577ms
08-24 13:48:11.250  1949  1949 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-24 13:48:11.268  1949  1949 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-24 13:48:11.268  1949  1949 I Activity: Activity.onPostResume() called 
08-24 13:48:11.268  1373  1373 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-24 13:48:11.274   844   844 D administrator: Handling package changes for user 0
08-24 13:48:11.278  1949  1949 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-24 13:48:11.302  1949  7143 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
08-24 13:48:11.309   844  1014 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
08-24 13:48:11.313   844  1929 D InputDispatcher: Focus entered window: Window{13e742e7 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-24 13:48:11.314  7108  7108 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 13:48:11.315  7108  7108 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 13:48:11.316  7108  7108 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-24 13:48:11.320   844  1014 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-24 13:48:11.334   844  1014 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-24 13:48:11.334   844  1014 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-24 13:48:11.335   844  1014 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-24 13:48:11.337   844  1014 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@1106e206,  pkg=WindowManager.LayoutParams
08-24 13:48:11.337   844  1014 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-24 13:48:11.338  1949  1949 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-24 13:48:11.340  1949  1949 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-24 13:48:11.341  1949  1949 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-24 13:48:11.348  7114  7114 I LockScreenSettings: Wallpaper base directory = /data/user/0/com.lge.lockscreensettings/files/
08-24 13:48:11.354  1949  1949 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
08-24 13:48:11.355  1949  1949 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-24 13:48:11.379  1373  1373 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-24 13:48:11.379  1373  1373 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-24 13:48:11.379  1373  1373 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-24 13:48:11.379  1373  1373 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-24 13:48:11.379  1373  1373 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-24 13:48:11.379  1373  1373 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-24 13:48:11.385  1373  1497 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-24 13:48:11.385  1373  1497 D KeyguardModel: createShortcutInfo...
08-24 13:48:11.390  1373  1497 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-24 13:48:11.390  1373  1497 D KeyguardModel: createShortcutInfo...
08-24 13:48:11.392  1373  1497 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 13:48:11.392  1373  1497 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-24 13:48:11.393  1373  1497 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-24 13:48:11.393  1373  1497 D KeyguardModel: createShortcutInfo...
08-24 13:48:11.395  1373  1497 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 13:48:11.395  1373  1497 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-24 13:48:11.396  1373  1497 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-24 13:48:11.396  1373  1497 D KeyguardModel: createShortcutInfo...
08-24 13:48:11.401  1373  1497 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 13:48:11.401  1373  1497 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-24 13:48:11.403  1373  1497 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-24 13:48:11.403  1373  1497 D KeyguardModel: createShortcutInfo...
08-24 13:48:11.409  1373  1373 D KeyguardModel: handleShortcutListChanged...
08-24 13:48:11.415  1373  1497 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-24 13:48:11.415  1373  1497 D KeyguardModel: createShortcutInfo...
08-24 13:48:11.417  1373  1497 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-24 13:48:11.418  1373  1497 D KeyguardModel: createShortcutInfo...
08-24 13:48:11.419  1373  1497 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 13:48:11.419  1373  1497 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-24 13:48:11.421  1373  1497 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-24 13:48:11.421  1373  1497 D KeyguardModel: createShortcutInfo...
08-24 13:48:11.424  1373  1497 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 13:48:11.424  1373  1497 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-24 13:48:11.426  1373  1497 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-24 13:48:11.426  1373  1497 D KeyguardModel: createShortcutInfo...
08-24 13:48:11.428  1373  1497 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 13:48:11.428  1373  1497 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-24 13:48:11.429  1373  1497 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-24 13:48:11.429  1373  1497 D KeyguardModel: createShortcutInfo...
08-24 13:48:11.435  1373  1373 D KeyguardModel: handleShortcutListChanged...
08-24 13:48:11.493   844   844 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-24 13:48:11.493   844   844 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-24 13:48:11.497   844   844 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-24 13:48:11.508   844  1349 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
08-24 13:48:11.527   844  5526 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-24 13:48:11.535   844  5526 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6712 uid 10030
08-24 13:48:11.586  1949  1949 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-24 13:48:11.588  1949  1949 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
08-24 13:48:11.589  1632  1632 E b       : Unable to connect to the editor to retrieve text... will retry later
08-24 13:48:11.597  1949  1949 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@c21739e time:1589489
08-24 13:48:11.604  2024  2024 I HotwordDetector: Closing mic
08-24 13:48:11.628   844  1016 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{137a3c1a u0 com.lge.launcher2/.Launcher t258} time:1589521
08-24 13:48:11.642  2024  2601 I HotwordRecognitionRnr: Stopping hotword detection.
08-24 13:48:11.652  1949  1949 I art     : Explicit concurrent mark sweep GC freed 4477(266KB) AllocSpace objects, 4(645KB) LOS objects, 39% free, 15MB/25MB, paused 1.242ms total 54.340ms
08-24 13:48:11.655  1949  1949 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
08-24 13:48:11.657   844  1058 I art     : Explicit concurrent mark sweep GC freed 11502(1317KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 23MB/35MB, paused 17.338ms total 433.408ms
08-24 13:48:11.698  7108  7108 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-24 13:48:11.727  7108  7108 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
08-24 13:48:11.765  7077  7077 D AndroidRuntime: Shutting down VM
08-24 13:48:11.798  1837  1837 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-24 13:48:11.798  1837  1837 D LCardEmulationManager: getDefaultRoute
08-24 13:48:11.897   844   896 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 13:48:11.969  7108  7108 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-24 13:48:12.009   844  1972 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7151 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
08-24 13:48:12.044   289   369 I ThermalEngine: Sensor:pa_therm0:29000 mC
08-24 13:48:12.062   844  1058 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7170 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-24 13:48:12.159   844   896 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-24 13:48:12.159  7151  7151 I AppUp4:AppBoxCP: onCreate
08-24 13:48:12.170  7151  7151 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-24 13:48:12.172  1949  1949 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }

```
