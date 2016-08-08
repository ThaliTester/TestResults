#### Test 79689775d0c6cb6_thali05_LGE-LG-D722 Logs


```
--------- beginning of main
08-08 16:37:37.678   873   995 D sensors_hal_Time: tsOffsetIs: Apps: 327991515952; DSPS: 10846270; Offset : -3019052724
,08-08 16:37:38.341   293   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
08-08 16:37:38.515  6965  6965 D AndroidRuntime: 
08-08 16:37:38.515  6965  6965 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-08 16:37:38.522  6965  6965 D AndroidRuntime: CheckJNI is OFF
08-08 16:37:38.844  6965  6965 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-08 16:37:38.860   873  1349 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-08 16:37:38.908   873  1349 D ActivityManager: setTaskToReturnTo : TaskRecord{ee7b6af #255 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-08 16:37:38.909   873  1349 D ActivityManager: setTaskToReturnTo : TaskRecord{ee7b6af #255 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-08 16:37:38.913   873  1349 D WindowStateEx: AppWindowTokenEx init.. 
08-08 16:37:38.953   873  1349 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6983 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-08 16:37:38.954   873  1349 D InputDispatcher: Focus left window: Window{3ac4a9a1 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-08 16:37:38.955  6965  6965 D AndroidRuntime: Shutting down VM
08-08 16:37:38.972  1950  1950 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-08 16:37:38.998   873   873 V ActivityManager: Display changed displayId=0
08-08 16:37:39.001  1780  1780 D DSDPConnection: Display #0 changed.
08-08 16:37:39.136  6983  6983 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-08 16:37:39.262  6983  6983 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-08 16:37:39.327  6983  6983 I LibraryLoader: Time to load native libraries: 9 ms (timestamps 9631-9640)
08-08 16:37:39.327  6983  6983 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-08 16:37:39.362  6983  6983 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {373e0752}
08-08 16:37:39.365  6983  6983 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-08 16:37:39.369  6983  6983 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-08 16:37:39.384  6983  6983 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-08 16:37:39.386  6983  6983 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-08 16:37:39.389  6983  6983 E SysUtils: ApplicationContext is null in ApplicationStatus
08-08 16:37:39.461  6983  6983 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-08 16:37:39.467  6983  6983 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-08 16:37:39.467  6983  6983 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-08 16:37:39.469  6983  6983 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-08 16:37:39.469  6983  6983 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-08 16:37:39.469  6983  6983 I Adreno-EGL: Build Date: 03/02/15 Mon
08-08 16:37:39.469  6983  6983 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-08 16:37:39.469  6983  6983 I Adreno-EGL: Remote Branch: 
08-08 16:37:39.469  6983  6983 I Adreno-EGL: Local Patches: 
08-08 16:37:39.469  6983  6983 I Adreno-EGL: Reconstruct Branch: 
08-08 16:37:39.526   873  1033 W ActivityManager: Activity pause timeout for ActivityRecord{2cac4abc u0 com.test.thalitest/.MainActivity t255}
08-08 16:37:39.552   280  1608 V AudioPolicyService: registerClient() client 0xb551c640, uid 10030
08-08 16:37:39.576   873  1055 D BluetoothManagerService: Message: 20
08-08 16:37:39.577   873  1055 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@13248c43:true
08-08 16:37:39.577  2080  2099 D BluetoothAdapterService(311978784): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@23418b76
08-08 16:37:39.703  6983  6983 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-08 16:37:39.718  6983  6983 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-08 16:37:39.725  6983  6983 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-08 16:37:39.730  6983  6983 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-08 16:37:39.730  6983  6983 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-08 16:37:39.750  6983  6983 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-08 16:37:39.758  6983  6983 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-08 16:37:39.758  6983  6983 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-08 16:37:39.819  6983  6983 I Activity: Activity.onPostResume() called 
08-08 16:37:39.824  6983  7036 D OpenGLRenderer: Render dirty regions requested: true
08-08 16:37:39.824  6983  7036 I OpenGLRenderer: Initialized EGL, version 1.4
08-08 16:37:39.830  6983  7036 D OpenGLRenderer: Enabling debug mode 0
08-08 16:37:39.850  6983  6983 D Atlas   : Validating map...
08-08 16:37:39.855   873   978 D SplitWindow: check instance of lgWin Window{3bf10c33 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-08 16:37:39.874  6983  7014 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-08 16:37:39.895   873  1054 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-08 16:37:39.897   873  1054 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-08 16:37:39.898  1372  1372 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-08 16:37:39.898  1372  1372 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-08 16:37:39.898  1372  1372 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-08 16:37:39.898  1372  1372 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-08 16:37:39.899   873  1054 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-08 16:37:39.899   873  1054 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-08 16:37:39.899   873  1054 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-08 16:37:39.899   873  1054 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@7418068,  pkg=WindowManager.LayoutParams
08-08 16:37:39.899   873  1054 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-08 16:37:39.901   873  1381 D InputDispatcher: Focus entered window: Window{3bf10c33 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-08 16:37:39.933   873  1938 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-08 16:37:39.952   873  1056 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +927ms (total +1s37ms)
08-08 16:37:39.952   873  1056 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2cac4abc u0 com.test.thalitest/.MainActivity t255} time:330265
08-08 16:37:39.956  6983  6983 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-08 16:37:39.956  6983  6983 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3b0b6d7c time:330269
08-08 16:37:40.023  6983  6983 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
08-08 16:37:40.029  1632  1632 E b       : Unable to connect to the editor to retrieve text... will retry later
08-08 16:37:40.049  6983  6983 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
08-08 16:37:40.053  6983  6983 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6983
08-08 16:37:40.226  6983  6983 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-08 16:37:40.557  6983  7043 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426135808
08-08 16:37:40.577  6983  7043 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-08 16:37:40.577  6983  7043 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-08 16:37:40.577  6983  7043 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-08 16:37:40.577  6983  7043 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-08 16:37:40.577  6983  7043 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-08 16:37:40.577  6983  7043 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b17f980 added. We now have 1 listener(s)
08-08 16:37:40.586   873  1921 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 16:37:40.588  6983  7043 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
08-08 16:37:40.590  6983  7043 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-08 16:37:40.591  6983  7043 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-08 16:37:40.592  6983  7043 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-08 16:37:40.597  6983  7043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-08 16:37:40.597  6983  7043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-08 16:37:40.597  6983  7043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-08 16:37:40.597  6983  7043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-08 16:37:40.597  6983  7043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-08 16:37:40.597  6983  7043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-08 16:37:40.597  6983  7043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-08 16:37:40.597  6983  7043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-08 16:37:40.597  6983  7043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-08 16:37:40.597  6983  7043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-08 16:37:40.597  6983  7043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-08 16:37:40.597  6983  7043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-08 16:37:40.597  6983  7043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-08 16:37:40.597  6983  7043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-08 16:37:40.598  6983  7043 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2db18f5f added. We now have 1 listener(s)
08-08 16:37:40.598  6983  7043 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 16:37:40.619  6983  7043 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-08 16:37:40.619  6983  7043 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-08 16:37:40.620  6983  7043 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-08 16:37:40.620  6983  7043 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-08 16:37:40.620  6983  7043 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-08 16:37:40.626  6983  7043 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 16:37:40.627   873  1882 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 16:37:40.629  6983  7043 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-08 16:37:40.641  2080  3501 D BluetoothAdapterService(311978784): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@23418b76
08-08 16:37:40.655  6983  7043 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-08 16:37:40.657  6983  7043 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 16:37:40.657  6983  7043 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 16:37:40.657  6983  7043 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-08 16:37:40.657  6983  7043 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 16:37:40.657  6983  7043 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 16:37:40.657  6983  7043 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 16:37:40.657  6983  7043 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 16:37:40.657  6983  7043 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-08 16:37:40.658  6983  7043 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-08 16:37:40.658  6983  7043 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 16:37:40.660  6983  6983 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 16:37:40.662  6983  6983 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 16:37:40.662  6983  7043 I io.jxcore.node.LifeCycleMonitor: start: OK
08-08 16:37:40.700  6983  6983 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-08 16:37:40.825  6983  6998 I art     : CheckpointMarkThreadRoots callback created = 0xb07d4390
,08-08 16:37:40.860  6983  6998 I art     : CheckpointMarkThreadRoots callback created = 0xb07d4360
,08-08 16:37:41.734  6983  7052 W jxcore-log: Initializing JXcore engine
08-08 16:37:41.734  6983  7052 W jxcore-log: JXcore engine is ready
,08-08 16:37:41.788  7052  7052 W Thread-809: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5623]" dev="sockfs" ino=5623 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-08 16:37:41.788  7052  7052 W Thread-809: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-08 16:37:41.788  7052  7052 W Thread-809: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[7351]" dev="sockfs" ino=7351 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-08 16:37:41.788  7052  7052 W Thread-809: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-08 16:37:41.788  7052  7052 W Thread-809: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-08 16:37:41.788  7052  7052 W Thread-809: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[32316]" dev="sockfs" ino=32316 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-08 16:37:41.820  6983  7052 W jxcore-log: Starting JXcore engine
,08-08 16:37:41.963  6983  7052 W jxcore-log: Platform android
08-08 16:37:41.963  6983  7052 W jxcore-log: 
,08-08 16:37:41.963  6983  7052 W jxcore-log: Process ARCH arm
08-08 16:37:41.963  6983  7052 W jxcore-log: 
08-08 16:37:42.294  6983  7052 I jxcore-log: JXcore Cordova bridge is ready!
08-08 16:37:42.294  6983  7052 I jxcore-log: 
08-08 16:37:42.295  6983  7052 W jxcore-log: JXcore engine is started
,08-08 16:37:42.300  6983  7043 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-08 16:37:42.302  6983  6983 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-08 16:37:43.346   293   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-08 16:37:48.351   293   352 I ThermalEngine: Sensor:pa_therm0:31000 mC
,08-08 16:37:52.067   873  3208 I LocationManagerService: remove 363feacd
,08-08 16:37:52.077   873  3208 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-08 16:37:52.077   873  3208 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-08 16:37:52.077   873  3208 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-08 16:37:52.078   873  3208 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-08 16:37:52.078   873  3208 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-08 16:37:53.356   293   352 I ThermalEngine: Sensor:pa_therm0:31000 mC

```
