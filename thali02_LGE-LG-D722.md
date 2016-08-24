#### Test 82203060198550b_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-24 14:04:45.521   294   350 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-24 14:04:47.193  6987  6987 D AndroidRuntime: 
08-24 14:04:47.193  6987  6987 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-24 14:04:47.203  6987  6987 D AndroidRuntime: CheckJNI is OFF
08-24 14:04:47.568  6987  6987 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-24 14:04:47.581   945  1860 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-24 14:04:47.610   945  1860 D ActivityManager: setTaskToReturnTo : TaskRecord{1efa7df6 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-24 14:04:47.610   945  1860 D ActivityManager: setTaskToReturnTo : TaskRecord{1efa7df6 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-24 14:04:47.614   945  1860 D WindowStateEx: AppWindowTokenEx init.. 
08-24 14:04:47.655   945  1860 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7001 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-24 14:04:47.658   945  1860 D InputDispatcher: Focus left window: Window{15f67860 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-24 14:04:47.658  6987  6987 D AndroidRuntime: Shutting down VM
08-24 14:04:47.684  1951  1951 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-24 14:04:47.701   945   945 V ActivityManager: Display changed displayId=0
08-24 14:04:47.707  1782  1782 D DSDPConnection: Display #0 changed.
08-24 14:04:47.821  7001  7001 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-24 14:04:47.920  7001  7001 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-24 14:04:47.974  7001  7001 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 789-792)
08-24 14:04:47.974  7001  7001 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 14:04:47.998  7001  7001 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a85f6d5}
08-24 14:04:47.999  7001  7001 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 14:04:48.003  7001  7001 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 14:04:48.016  7001  7001 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-24 14:04:48.017  7001  7001 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 14:04:48.021  7001  7001 E SysUtils: ApplicationContext is null in ApplicationStatus
08-24 14:04:48.060  7001  7001 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-24 14:04:48.066  7001  7001 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 14:04:48.066  7001  7001 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-24 14:04:48.066  7001  7001 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 14:04:48.066  7001  7001 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 14:04:48.066  7001  7001 I Adreno-EGL: Build Date: 03/02/15 Mon
08-24 14:04:48.066  7001  7001 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-24 14:04:48.066  7001  7001 I Adreno-EGL: Remote Branch: 
08-24 14:04:48.066  7001  7001 I Adreno-EGL: Local Patches: 
08-24 14:04:48.066  7001  7001 I Adreno-EGL: Reconstruct Branch: 
08-24 14:04:48.125   282  1596 V AudioPolicyService: registerClient() client 0xb4027280, uid 10030
08-24 14:04:48.130   945  1053 D BluetoothManagerService: Message: 20
08-24 14:04:48.131   945  1053 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@173f00da:true
08-24 14:04:48.144  2079  3645 D BluetoothAdapterService(403994075): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2007f389
08-24 14:04:48.227   945  1018 W ActivityManager: Activity pause timeout for ActivityRecord{254cc5f7 u0 com.test.thalitest/.MainActivity t259}
08-24 14:04:48.272  7001  7001 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 14:04:48.284  7001  7001 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-24 14:04:48.291  7001  7001 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-24 14:04:48.296  7001  7001 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-24 14:04:48.297  7001  7001 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-24 14:04:48.312  7001  7001 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-24 14:04:48.320  7001  7001 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 14:04:48.320  7001  7001 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-24 14:04:48.375  7001  7001 I Activity: Activity.onPostResume() called 
08-24 14:04:48.381  7001  7056 D OpenGLRenderer: Render dirty regions requested: true
08-24 14:04:48.381  7001  7056 I OpenGLRenderer: Initialized EGL, version 1.4
08-24 14:04:48.389  7001  7056 D OpenGLRenderer: Enabling debug mode 0
08-24 14:04:48.408  7001  7001 D Atlas   : Validating map...
08-24 14:04:48.412   945  1920 D SplitWindow: check instance of lgWin Window{1349548a u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-24 14:04:48.428  7001  7043 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-24 14:04:48.448   945  1052 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-24 14:04:48.451   945  1052 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-24 14:04:48.452  1372  1372 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-24 14:04:48.452  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-24 14:04:48.452  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-24 14:04:48.452  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-24 14:04:48.452   945  1052 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-24 14:04:48.452   945  1052 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-24 14:04:48.452   945  1052 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-24 14:04:48.452   945  1052 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3805a6c0,  pkg=WindowManager.LayoutParams
08-24 14:04:48.453   945  1052 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-24 14:04:48.462   945  1371 D InputDispatcher: Focus entered window: Window{1349548a u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-24 14:04:48.489   945  2021 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-24 14:04:48.508   945  1055 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +781ms (total +892ms)
08-24 14:04:48.508   945  1055 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{254cc5f7 u0 com.test.thalitest/.MainActivity t259} time:181326
08-24 14:04:48.518  7001  7001 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-24 14:04:48.518  7001  7001 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3a8419a7 time:181337
08-24 14:04:48.557  7001  7001 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
08-24 14:04:48.561  1631  1631 E b       : Unable to connect to the editor to retrieve text... will retry later
08-24 14:04:48.590  7001  7001 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
08-24 14:04:48.623  7001  7001 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7001
,08-24 14:04:48.762  7001  7001 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 14:04:49.114  7001  7058 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426156288
,08-24 14:04:49.130  7001  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 14:04:49.130  7001  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 14:04:49.130  7001  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 14:04:49.130  7001  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 14:04:49.130  7001  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-24 14:04:49.131  7001  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3609fdbb added. We now have 1 listener(s)
,08-24 14:04:49.142   945  2085 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:04:49.147  7001  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,08-24 14:04:49.151  7001  7058 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-24 14:04:49.152  7001  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-24 14:04:49.153  7001  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:04:49.159  7001  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 14:04:49.159  7001  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 14:04:49.159  7001  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 14:04:49.159  7001  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-24 14:04:49.159  7001  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 14:04:49.159  7001  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 14:04:49.159  7001  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 14:04:49.159  7001  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 14:04:49.159  7001  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 14:04:49.159  7001  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 14:04:49.159  7001  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 14:04:49.159  7001  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 14:04:49.159  7001  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 14:04:49.159  7001  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 14:04:49.160  7001  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b8e116 added. We now have 1 listener(s)
08-24 14:04:49.160  7001  7058 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:04:49.169  7001  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 14:04:49.169  7001  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-24 14:04:49.170  7001  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 14:04:49.170  7001  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 14:04:49.170  7001  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-24 14:04:49.173  7001  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-24 14:04:49.174   945  2000 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:04:49.176  7001  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-24 14:04:49.185  2079  2096 D BluetoothAdapterService(403994075): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2007f389
,08-24 14:04:49.192  7001  7058 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-24 14:04:49.192  7001  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:04:49.192  7001  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:04:49.192  7001  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:04:49.192  7001  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:04:49.192  7001  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:04:49.192  7001  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:04:49.192  7001  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:04:49.192  7001  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:04:49.193  7001  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 14:04:49.193  7001  7058 D io.jxcore.node.ConnectivityMonitor: start: OK
08-24 14:04:49.194  7001  7058 I io.jxcore.node.LifeCycleMonitor: start: OK
08-24 14:04:49.203  7001  7001 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-24 14:04:49.205  7001  7001 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:04:49.228  7001  7001 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 14:04:49.372  7001  7020 I art     : CheckpointMarkThreadRoots callback created = 0x9ed2c810
,08-24 14:04:49.417  7001  7020 I art     : CheckpointMarkThreadRoots callback created = 0xaaeaa180
,08-24 14:04:50.089  7001  7072 W jxcore-log: Initializing JXcore engine
,08-24 14:04:50.092  7001  7072 W jxcore-log: JXcore engine is ready
08-24 14:04:50.220  7072  7072 W Thread-843: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6558]" dev="sockfs" ino=6558 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-24 14:04:50.220  7072  7072 W Thread-843: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-24 14:04:50.220  7072  7072 W Thread-843: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7946]" dev="sockfs" ino=7946 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-24 14:04:50.220  7072  7072 W Thread-843: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-24 14:04:50.220  7072  7072 W Thread-843: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-24 14:04:50.220  7072  7072 W Thread-843: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[32106]" dev="sockfs" ino=32106 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-24 14:04:50.249  7001  7072 W jxcore-log: Starting JXcore engine
,08-24 14:04:50.428  7001  7072 W jxcore-log: Platform android
08-24 14:04:50.428  7001  7072 W jxcore-log: 
,08-24 14:04:50.429  7001  7072 W jxcore-log: Process ARCH arm
08-24 14:04:50.429  7001  7072 W jxcore-log: 
08-24 14:04:50.525   294   350 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-24 14:04:50.727  7001  7072 I jxcore-log: JXcore Cordova bridge is ready!
08-24 14:04:50.727  7001  7072 I jxcore-log: 
08-24 14:04:50.728  7001  7072 W jxcore-log: JXcore engine is started
,08-24 14:04:50.732  7001  7058 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-24 14:04:50.734  7001  7001 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-24 14:04:53.589   945  1285 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1d0531a9 type 2 when 186398 com.google.android.gms} when 186398
,08-24 14:04:53.674   945  2085 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-24 14:04:53.738  1753  1753 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 14:04:53.739  1753  1753 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,08-24 14:04:54.443  1879  1879 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-24 14:04:54.443  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-24 14:04:54.443  1372  1372 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-24 14:04:54.443  1372  1372 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-24 14:04:54.443  1372  1372 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-24 14:04:54.457   490   490 D charger_monitor: init target 500000
,08-24 14:04:54.462   490   490 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-24 14:04:54.485  1914  1914 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-24 14:04:54.485  1914  1914 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
,08-24 14:04:54.487  1879  2044 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-24 14:04:54.487  1879  2044 D LEDHandler: Battery Level Remaining: 100%
08-24 14:04:54.487  1879  2044 D LEDHandler: Battery Temp: 302, mChargingStatus=5, mChargingStop=false
08-24 14:04:54.487  2079  3646 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-24 14:04:54.489   945   945 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:04:54.489   945   945 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-24 14:04:54.489   945  1314 D WifiController: battery changed pluggedType: 2
08-24 14:04:54.489  1372  1372 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 302
08-24 14:04:54.489  1372  1372 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-24 14:04:54.489  1372  1372 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 302
08-24 14:04:54.492  1372  1372 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-24 14:04:55.530   294   350 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-24 14:04:59.128  1753  3587 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,08-24 14:05:00.047  1372  1372 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-24 14:05:00.047  1372  1372 I KeyguardUpdateMonitor: called onTimeUpdated()
08-24 14:05:00.047  1372  1372 I [SystemUI]Clock: called onTimeUpdated()
,08-24 14:05:00.050  1372  1372 I LgeClockWidgetControlView: called onTimeUpdated()
08-24 14:05:00.051  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
08-24 14:05:00.052  1372  1372 I [SystemUI]DateView: called onTimeUpdated()
08-24 14:05:00.052  1372  1372 D KeyguardUpdateMonitor: handleTimeUpdate
08-24 14:05:00.535   294   350 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-24 14:05:00.589  7001  7072 E jxcore  : Error!: syntax error
08-24 14:05:00.589  7001  7072 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"14","_columnNumber":"19","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:14:19"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"}]
,08-24 14:05:00.602  7001  7001 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "syntax error\nSyntaxError: syntax error\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:14:19\n    at $w.prototype._compile@module.js:621:8\n    at $w._extensions[\".js\"]@module.js:651:1"", source: file:///android_asset/www/js/thali_main.js (56)
,08-24 14:05:00.603  7001  7001 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,08-24 14:05:00.623   945  1920 D InputDispatcher: Focus left window: Window{1349548a u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-24 14:05:00.627   945  1920 I ActivityManager: Killing 6656:com.google.android.talk/u0a61 (adj 15): empty #11
08-24 14:05:00.657   945  1861 W libprocessgroup: failed to open /acct/uid_10061/pid_6656/cgroup.procs: No such file or directory
08-24 14:05:00.657  7001  7058 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 53ms. Plugin should use CordovaInterface.getThreadPool().
,08-24 14:05:00.660  7001  7001 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-24 14:05:00.667  7001  7001 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,08-24 14:05:00.674  7001  7001 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-24 14:05:00.674  7001  7001 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:05:00.674  7001  7001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:05:00.674  7001  7001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:05:00.676  7001  7001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3609fdbb removed from the list
08-24 14:05:00.676  7001  7001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:05:00.676  7001  7001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16b8e116 removed from the list
08-24 14:05:00.676  7001  7001 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:05:00.676  7001  7001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-24 14:05:00.680  7001  7001 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-24 14:05:00.699  1951  1951 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
,08-24 14:05:00.705   945  3676 D InputDispatcher: Window went away: Window{1349548a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-24 14:05:00.795  1951  1951 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
,08-24 14:05:00.838  1951  1951 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-24 14:05:00.842  1951  1951 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-24 14:05:00.842  1951  1951 I Activity: Activity.onPostResume() called 
08-24 14:05:00.847  1951  1951 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-24 14:05:00.853  2849  2849 D WeatherAncestor: 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 14:5:0
,08-24 14:05:00.859  2849  2849 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-24 14:05:00.861  1951  7110 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
08-24 14:05:00.862   945  1052 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
08-24 14:05:00.862   945  1052 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-24 14:05:00.862  1372  1372 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
,08-24 14:05:00.862   945  1052 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-24 14:05:00.862  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-24 14:05:00.862  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-24 14:05:00.862  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-24 14:05:00.862   945  1052 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-24 14:05:00.863   945  1052 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-24 14:05:00.863   945  1052 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@3805a6c0,  pkg=WindowManager.LayoutParams
08-24 14:05:00.863   945  1052 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-24 14:05:00.864  2849  2849 D WeatherService: 2 : shouldTimeTickRegistered : false
08-24 14:05:00.864  2849  2849 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 14:5:0
08-24 14:05:00.866   945  1861 D InputDispatcher: Focus entered window: Window{15f67860 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-24 14:05:00.867  2849  2849 D WeatherService: 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
08-24 14:05:00.867  2849  2849 D WeatherService: 2 : shouldTimeTickRegistered : false
,08-24 14:05:00.883  1951  1951 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
,08-24 14:05:00.884  1951  1951 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
08-24 14:05:00.885  1951  1951 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-24 14:05:00.887   945  1902 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-24 14:05:00.890  7001  7001 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-24 14:05:00.944  1951  1951 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
08-24 14:05:00.944  1951  1951 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@20e67b8b time:193763
,08-24 14:05:00.947  1631  1631 E b       : Unable to connect to the editor to retrieve text... will retry later
08-24 14:05:00.956  1951  1951 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-24 14:05:00.968   945  1055 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1cba3c17 u0 com.lge.launcher2/.Launcher t258} time:193786
,08-24 14:05:01.093  7103  7103 D AndroidRuntime: 
08-24 14:05:01.093  7103  7103 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-24 14:05:01.101  7103  7103 D AndroidRuntime: CheckJNI is OFF
,08-24 14:05:01.433  7103  7103 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-24 14:05:01.492   945  1018 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
08-24 14:05:01.492   945  1018 I ActivityManager: Killing 7001:com.test.thalitest/u0a30 (adj 9): stop com.test.thalitest
,08-24 14:05:01.508   945   979 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-24 14:05:01.508   945   979 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-24 14:05:01.508   945   979 D sensors_hal_Time: tsOffsetIs: Apps: 194326384514; DSPS: 6466344; Offset : -3015922074
,08-24 14:05:01.600   945  1902 W ActivityManager: Spurious death for ProcessRecord{32ab63de 7001:com.test.thalitest/u0a30}, curProc for 7001: null
,08-24 14:05:01.636   945  1062 W PackageSettings: Skipping PackageSetting{33dcee07 com.example.hello/10317} due to missing metadata
,08-24 14:05:01.702   945  1062 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
,08-24 14:05:01.753  1951  1951 I art     : Explicit concurrent mark sweep GC freed 3720(230KB) AllocSpace objects, 5(681KB) LOS objects, 39% free, 15MB/25MB, paused 1.364ms total 46.778ms
,08-24 14:05:01.769  2025  2025 I art     : Explicit concurrent mark sweep GC freed 1607(104KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/20MB, paused 2.011ms total 60.339ms
,08-24 14:05:01.793  1951  1951 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-24 14:05:01.794  1951  1951 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-24 14:05:01.794  1951  1951 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-24 14:05:01.808  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-24 14:05:01.828   945  1287 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-24 14:05:01.837  1914  1914 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
08-24 14:05:01.838  1753  2401 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-24 14:05:01.867   945  1018 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7138 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-24 14:05:01.871  3805  3805 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-24 14:05:01.876  3805  3805 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-24 14:05:01.876  3805  3805 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-24 14:05:01.876  3805  3805 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-24 14:05:01.876  3805  3805 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 14:05:01.876  3805  3805 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 14:05:01.876  3805  3805 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-24 14:05:01.876  3805  3805 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-24 14:05:01.876  3805  3805 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:05:01.876  3805  3805 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:05:01.876  3805  3805 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-24 14:05:01.876  3805  3805 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-24 14:05:01.889   305   305 I art     : Explicit concurrent mark sweep GC freed 708(30KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 324us total 22.639ms
,08-24 14:05:01.903  3627  3627 I art     : Explicit concurrent mark sweep GC freed 18826(1124KB) AllocSpace objects, 3(48KB) LOS objects, 24% free, 16MB/22MB, paused 1.208ms total 193.312ms
,08-24 14:05:01.911   305   305 I art     : Explicit concurrent mark sweep GC freed 6(208B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 284us total 22.386ms
08-24 14:05:01.921  1372  1372 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-24 14:05:01.936   305   305 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 39% free, 6MB/11MB, paused 306us total 21.898ms
,08-24 14:05:01.993  1372  1372 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-24 14:05:01.997  1372  1372 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-24 14:05:02.001  7138  7138 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:05:02.002  7138  7138 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 14:05:02.003  7138  7138 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
,08-24 14:05:02.014  1372  1504 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-24 14:05:02.014  1372  1504 D KeyguardModel: createShortcutInfo...
08-24 14:05:02.017  1372  1504 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-24 14:05:02.017  1372  1504 D KeyguardModel: createShortcutInfo...
,08-24 14:05:02.035  1372  1504 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-24 14:05:02.038  1372  1504 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-24 14:05:02.040  1372  1504 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-24 14:05:02.040  1372  1504 D KeyguardModel: createShortcutInfo...
08-24 14:05:02.042  1372  1504 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 14:05:02.042  1372  1504 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-24 14:05:02.048  1372  1504 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-24 14:05:02.048  1372  1504 D KeyguardModel: createShortcutInfo...
,08-24 14:05:02.051  1372  1504 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 14:05:02.051  1372  1504 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-24 14:05:02.053  1372  1504 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-24 14:05:02.053  1372  1504 D KeyguardModel: createShortcutInfo...
08-24 14:05:02.058  1372  1372 D KeyguardModel: handleShortcutListChanged...
08-24 14:05:02.062  1372  1504 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-24 14:05:02.063  1372  1504 D KeyguardModel: createShortcutInfo...
,08-24 14:05:02.066  1372  1504 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-24 14:05:02.066  1372  1504 D KeyguardModel: createShortcutInfo...
08-24 14:05:02.070   945   945 I art     : Explicit concurrent mark sweep GC freed 43771(3MB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 23MB/35MB, paused 3.256ms total 285.246ms
08-24 14:05:02.070   945  1062 I art     : WaitForGcToComplete blocked for 183.955ms for cause Explicit
08-24 14:05:02.072  1372  1504 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 14:05:02.072  1372  1504 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-24 14:05:02.086  1372  1504 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-24 14:05:02.087  1372  1504 D KeyguardModel: createShortcutInfo...
,08-24 14:05:02.094  1372  1504 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 14:05:02.094  1372  1504 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-24 14:05:02.095  1372  1504 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-24 14:05:02.095  1372  1504 D KeyguardModel: createShortcutInfo...
08-24 14:05:02.103  1372  1504 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 14:05:02.103  1372  1504 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-24 14:05:02.105  1372  1504 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-24 14:05:02.105  1372  1504 D KeyguardModel: createShortcutInfo...
,08-24 14:05:02.113  1372  1372 D KeyguardModel: handleShortcutListChanged...
,08-24 14:05:02.132   945   945 D administrator: Handling package changes for user 0
,08-24 14:05:02.237  7138  7138 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-24 14:05:02.245   945   945 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-24 14:05:02.245   945   945 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-24 14:05:02.249   945   945 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-24 14:05:02.262   945  1349 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
,08-24 14:05:02.268  7138  7138 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
08-24 14:05:02.359   945  1062 I art     : Explicit concurrent mark sweep GC freed 7094(408KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.899ms total 287.880ms
,08-24 14:05:02.418  1852  1852 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-24 14:05:02.418  1852  1852 D LCardEmulationManager: getDefaultRoute
,08-24 14:05:02.432   945  1017 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-24 14:05:02.440  7103  7103 D AndroidRuntime: Shutting down VM
,08-24 14:05:02.477   945  1017 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-24 14:05:02.481  1951  1951 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-24 14:05:02.506  7138  7138 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-24 14:05:02.552   945  1383 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7166 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-24 14:05:02.623  7166  7166 I AppUp4:AppBoxCP: onCreate
,08-24 14:05:02.628  7166  7166 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-24 14:05:02.638  7166  7166 I AppUp4:DB:  setFingerPrint start
08-24 14:05:02.638  7166  7166 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
,08-24 14:05:02.645  7166  7166 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
08-24 14:05:02.645  7166  7166 I AppUp4:DB:  SDK version = 21
08-24 14:05:02.645  7166  7166 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-24 14:05:02.647  7166  7166 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
,08-24 14:05:02.671  7166  7166 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-24 14:05:02.720   945  1062 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7183 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-24 14:05:02.761   945  1957 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7205 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
08-24 14:05:02.762   945  1957 I ActivityManager: Killing 6719:com.android.gallery3d/u0a23 (adj 15): empty #11
,08-24 14:05:02.806   945  2085 W libprocessgroup: failed to open /acct/uid_10023/pid_6719/cgroup.procs: No such file or directory
08-24 14:05:02.837  1951  2236 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-24 14:05:02.837  1951  2236 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-24 14:05:02.841  1951  2236 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
08-24 14:05:02.842  1951  2236 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
08-24 14:05:02.842  1951  2236 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
08-24 14:05:02.842  1951  2236 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 0
08-24 14:05:02.842  1951  2236 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
08-24 14:05:02.861   945  1942 I ActivityManager: Killing 6746:com.android.contacts/u0a18 (adj 15): empty #11
,08-24 14:05:02.892   945  1383 W libprocessgroup: failed to open /acct/uid_10018/pid_6746/cgroup.procs: No such file or directory

```
