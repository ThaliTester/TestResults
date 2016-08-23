#### Test 82337235c8e499b_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-23 13:41:38.903   298   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 13:41:39.946  6768  6768 D AndroidRuntime: 
08-23 13:41:39.946  6768  6768 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 13:41:39.956  6768  6768 D AndroidRuntime: CheckJNI is OFF
08-23 13:41:40.401  6768  6768 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-23 13:41:40.412   966  1564 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-23 13:41:40.454   966  1564 D ActivityManager: setTaskToReturnTo : TaskRecord{3a206b76 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 13:41:40.454   966  1564 D ActivityManager: setTaskToReturnTo : TaskRecord{3a206b76 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 13:41:40.459   966  1564 D WindowStateEx: AppWindowTokenEx init.. 
08-23 13:41:40.498   966  1564 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6786 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-23 13:41:40.499   966  1564 D InputDispatcher: Focus left window: Window{afc0122 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-23 13:41:40.500  6768  6768 D AndroidRuntime: Shutting down VM
08-23 13:41:40.520  1876  1876 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-23 13:41:40.543   966   966 V ActivityManager: Display changed displayId=0
08-23 13:41:40.547  1750  1750 D DSDPConnection: Display #0 changed.
08-23 13:41:40.679  6786  6786 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-23 13:41:40.790  6786  6786 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-23 13:41:40.855  6786  6786 I LibraryLoader: Time to load native libraries: 12 ms (timestamps 142-154)
08-23 13:41:40.855  6786  6786 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 13:41:40.889  6786  6786 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {4dbeb2a}
08-23 13:41:40.890  6786  6786 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 13:41:40.893  6786  6786 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 13:41:40.907  6786  6786 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-23 13:41:40.908  6786  6786 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 13:41:40.909  6786  6786 E SysUtils: ApplicationContext is null in ApplicationStatus
08-23 13:41:40.930  6786  6786 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-23 13:41:40.936  6786  6786 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 13:41:40.936  6786  6786 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-23 13:41:40.937  6786  6786 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 13:41:40.937  6786  6786 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 13:41:40.937  6786  6786 I Adreno-EGL: Build Date: 03/02/15 Mon
08-23 13:41:40.937  6786  6786 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-23 13:41:40.937  6786  6786 I Adreno-EGL: Remote Branch: 
08-23 13:41:40.937  6786  6786 I Adreno-EGL: Local Patches: 
08-23 13:41:40.937  6786  6786 I Adreno-EGL: Reconstruct Branch: 
08-23 13:41:40.998   286   286 V AudioPolicyService: registerClient() client 0xb40e8b60, uid 10030
08-23 13:41:41.010   966  1053 D BluetoothManagerService: Message: 20
08-23 13:41:41.010   966  1053 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3689765a:true
08-23 13:41:41.018  2045  2075 D BluetoothAdapterService(35311288): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d3aa7ce
08-23 13:41:41.075   966  1037 W ActivityManager: Activity pause timeout for ActivityRecord{33cfe577 u0 com.test.thalitest/.MainActivity t259}
08-23 13:41:41.205  6786  6786 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 13:41:41.220  6786  6786 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-23 13:41:41.228  6786  6786 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-23 13:41:41.233  6786  6786 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-23 13:41:41.233  6786  6786 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-23 13:41:41.252  6786  6786 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-23 13:41:41.262  6786  6786 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 13:41:41.262  6786  6786 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 13:41:41.321  6786  6786 I Activity: Activity.onPostResume() called 
08-23 13:41:41.328  6786  6831 D OpenGLRenderer: Render dirty regions requested: true
08-23 13:41:41.328  6786  6831 I OpenGLRenderer: Initialized EGL, version 1.4
08-23 13:41:41.338  6786  6831 D OpenGLRenderer: Enabling debug mode 0
08-23 13:41:41.354  6786  6786 D Atlas   : Validating map...
08-23 13:41:41.360   966  1378 D SplitWindow: check instance of lgWin Window{12dc2a0a u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-23 13:41:41.377  6786  6818 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-23 13:41:41.401   966  1052 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
08-23 13:41:41.404   966  1052 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-23 13:41:41.405  1371  1371 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-23 13:41:41.405  1371  1371 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-23 13:41:41.405  1371  1371 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-23 13:41:41.405  1371  1371 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-23 13:41:41.406   966  1052 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-23 13:41:41.406   966  1052 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-23 13:41:41.406   966  1052 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-23 13:41:41.406   966  1052 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2fcb8391,  pkg=WindowManager.LayoutParams
08-23 13:41:41.406   966  1052 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-23 13:41:41.413   966  2112 D InputDispatcher: Focus entered window: Window{12dc2a0a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-23 13:41:41.446   966   985 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-23 13:41:41.468   966  1054 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +892ms (total +1s6ms)
08-23 13:41:41.468   966  1054 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{33cfe577 u0 com.test.thalitest/.MainActivity t259} time:180767
08-23 13:41:41.473  6786  6786 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-23 13:41:41.474  6786  6786 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1b63e894 time:180773
08-23 13:41:41.530  6786  6786 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-23 13:41:41.535  1626  1626 E b       : Unable to connect to the editor to retrieve text... will retry later
08-23 13:41:41.574  6786  6786 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-23 13:41:41.606  6786  6786 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6786
,08-23 13:41:41.767  6786  6786 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 13:41:42.136  6786  6833 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1635611904
,08-23 13:41:42.156  6786  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 13:41:42.156  6786  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 13:41:42.156  6786  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 13:41:42.156  6786  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 13:41:42.156  6786  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-23 13:41:42.156  6786  6833 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18e40918 added. We now have 1 listener(s)
08-23 13:41:42.166   966  1564 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-23 13:41:42.171  6786  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
08-23 13:41:42.174  6786  6833 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-23 13:41:42.179  6786  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 13:41:42.180  6786  6833 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 13:41:42.187  6786  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 13:41:42.187  6786  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 13:41:42.187  6786  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 13:41:42.187  6786  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-23 13:41:42.187  6786  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 13:41:42.187  6786  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 13:41:42.187  6786  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 13:41:42.187  6786  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 13:41:42.187  6786  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 13:41:42.187  6786  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 13:41:42.187  6786  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 13:41:42.187  6786  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 13:41:42.187  6786  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 13:41:42.187  6786  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 13:41:42.187  6786  6833 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27a435d7 added. We now have 1 listener(s)
08-23 13:41:42.188  6786  6833 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 13:41:42.200  6786  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 13:41:42.200  6786  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-23 13:41:42.203  6786  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 13:41:42.204  6786  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 13:41:42.204  6786  6833 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-23 13:41:42.211  6786  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 13:41:42.211   966  1948 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-23 13:41:42.213  6786  6833 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-23 13:41:42.227  2045  2074 D BluetoothAdapterService(35311288): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@3d3aa7ce
,08-23 13:41:42.231  6786  6833 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-23 13:41:42.231  6786  6833 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 13:41:42.231  6786  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 13:41:42.231  6786  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 13:41:42.231  6786  6833 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 13:41:42.231  6786  6833 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 13:41:42.231  6786  6833 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 13:41:42.231  6786  6833 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 13:41:42.231  6786  6833 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 13:41:42.231  6786  6833 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 13:41:42.232  6786  6833 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 13:41:42.232  6786  6833 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 13:41:42.233  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 13:41:42.235  6786  6786 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 13:41:42.262  6786  6786 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 13:41:42.397  6786  6802 I art     : CheckpointMarkThreadRoots callback created = 0xb07b7030
,08-23 13:41:42.447  6786  6802 I art     : CheckpointMarkThreadRoots callback created = 0xb075efd0
,08-23 13:41:43.081  6786  6840 W jxcore-log: Initializing JXcore engine
,08-23 13:41:43.082  6786  6840 W jxcore-log: JXcore engine is ready
,08-23 13:41:43.196  6840  6840 W Thread-814: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5466]" dev="sockfs" ino=5466 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-23 13:41:43.196  6840  6840 W Thread-814: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-23 13:41:43.196  6840  6840 W Thread-814: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8849]" dev="sockfs" ino=8849 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-23 13:41:43.196  6840  6840 W Thread-814: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-23 13:41:43.196  6840  6840 W Thread-814: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-23 13:41:43.196  6840  6840 W Thread-814: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[31350]" dev="sockfs" ino=31350 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-23 13:41:43.230  6786  6840 W jxcore-log: Starting JXcore engine
,08-23 13:41:43.390  6786  6840 W jxcore-log: Platform android
08-23 13:41:43.390  6786  6840 W jxcore-log: 
08-23 13:41:43.390  6786  6840 W jxcore-log: Process ARCH arm
08-23 13:41:43.390  6786  6840 W jxcore-log: 
,08-23 13:41:43.731  6786  6840 I jxcore-log: JXcore Cordova bridge is ready!
08-23 13:41:43.731  6786  6840 I jxcore-log: 
08-23 13:41:43.731  6786  6840 W jxcore-log: JXcore engine is started
,08-23 13:41:43.747  6786  6833 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 13:41:43.750  6786  6786 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-23 13:41:43.779  6786  6840 E jxcore  : Error!: missing name after . operator
08-23 13:41:43.779  6786  6840 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,08-23 13:41:43.786  6786  6786 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "missing name after . operator\nSyntaxError: missing name after . operator\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (56)
08-23 13:41:43.787  6786  6786 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,08-23 13:41:43.796   966  1784 D InputDispatcher: Focus left window: Window{12dc2a0a u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-23 13:41:43.801   966  1784 I ActivityManager: Killing 6501:com.lge.appbox.client/u0a11 (adj 15): empty #11
08-23 13:41:43.833  6786  6833 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 46ms. Plugin should use CordovaInterface.getThreadPool().
,08-23 13:41:43.834   966   986 W libprocessgroup: failed to open /acct/uid_10011/pid_6501/cgroup.procs: No such file or directory
08-23 13:41:43.837  6786  6786 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-23 13:41:43.838  6786  6786 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-23 13:41:43.839  6786  6786 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 13:41:43.839  6786  6786 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 13:41:43.839  6786  6786 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 13:41:43.840  6786  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 13:41:43.840  6786  6786 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18e40918 removed from the list
08-23 13:41:43.840  6786  6786 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 13:41:43.840  6786  6786 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27a435d7 removed from the list
08-23 13:41:43.840  6786  6786 D io.jxcore.node.ConnectivityMonitor: stop
08-23 13:41:43.840  6786  6786 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-23 13:41:43.852  6786  6786 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-23 13:41:43.869  1876  1876 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
,08-23 13:41:43.883   966  1948 D InputDispatcher: Window went away: Window{12dc2a0a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-23 13:41:43.902  1876  1876 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
08-23 13:41:43.908   298   355 I ThermalEngine: Sensor:pa_therm0:32000 mC
,08-23 13:41:43.924  1876  1876 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,08-23 13:41:43.928  1876  1876 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-23 13:41:43.928  1876  1876 I Activity: Activity.onPostResume() called 
08-23 13:41:43.935  2867  2867 D WeatherAncestor: 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 13:41:43
08-23 13:41:43.937  1876  1876 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
,08-23 13:41:43.945  2867  2867 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-23 13:41:43.949  2867  2867 D WeatherService: 2 : shouldTimeTickRegistered : false
,08-23 13:41:43.949  1876  6853 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
08-23 13:41:43.950  2867  2867 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 13:41:43
08-23 13:41:43.951  2867  2867 D WeatherService: 2 : onStartCommand, intent!=null, action: com.lge.launcher2.RESUME
08-23 13:41:43.952  2867  2867 D WeatherService: 2 : shouldTimeTickRegistered : false
08-23 13:41:43.954   966  1052 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
08-23 13:41:43.955   966  1052 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
08-23 13:41:43.956  1371  1371 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-23 13:41:43.956  1371  1371 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-23 13:41:43.956  1371  1371 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-23 13:41:43.956  1371  1371 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-23 13:41:43.956   966  1052 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-23 13:41:43.956   966  1052 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-23 13:41:43.956   966  1052 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-23 13:41:43.956   966  1052 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2fcb8391,  pkg=WindowManager.LayoutParams
08-23 13:41:43.956   966  1052 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-23 13:41:43.957   966  1856 D InputDispatcher: Focus entered window: Window{afc0122 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-23 13:41:43.971  1876  1876 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
,08-23 13:41:43.972  1876  1876 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
08-23 13:41:43.973  1876  1876 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-23 13:41:43.976   966  1839 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-23 13:41:43.978  6786  6786 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-23 13:41:44.024  1876  1876 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
08-23 13:41:44.025  1876  1876 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1dad2aa8 time:183324
,08-23 13:41:44.026  1626  1626 E b       : Unable to connect to the editor to retrieve text... will retry later
,08-23 13:41:44.032  1876  1876 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
08-23 13:41:44.048   966  1054 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2fbf325a u0 com.lge.launcher2/.Launcher t258} time:183347
,08-23 13:41:44.090  6843  6843 D AndroidRuntime: 
08-23 13:41:44.090  6843  6843 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-23 13:41:44.093  6843  6843 D AndroidRuntime: CheckJNI is OFF
08-23 13:41:44.277  6843  6843 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 13:41:44.311   966  1037 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
,08-23 13:41:44.313   966  1037 I ActivityManager: Killing 6786:com.test.thalitest/u0a30 (adj 9): stop com.test.thalitest
08-23 13:41:44.423   966   985 W ActivityManager: Spurious death for ProcessRecord{15b939dc 6786:com.test.thalitest/u0a30}, curProc for 6786: null
,08-23 13:41:44.443   966  1062 W PackageSettings: Skipping PackageSetting{27f73574 com.example.hello/10317} due to missing metadata
,08-23 13:41:44.473   966  1062 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
,08-23 13:41:44.558  1876  1876 I art     : Explicit concurrent mark sweep GC freed 23996(1276KB) AllocSpace objects, 14(7MB) LOS objects, 39% free, 15MB/26MB, paused 1.436ms total 76.733ms
,08-23 13:41:44.568  1938  1938 I art     : Explicit concurrent mark sweep GC freed 9945(718KB) AllocSpace objects, 3(672KB) LOS objects, 40% free, 11MB/19MB, paused 1.396ms total 90.601ms
08-23 13:41:44.582  1876  1876 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-23 13:41:44.584  1876  1876 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-23 13:41:44.585  1876  1876 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-23 13:41:44.587  1371  1371 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-23 13:41:44.597  3666  3666 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-23 13:41:44.599   966  1288 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-23 13:41:44.602  1732  2395 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-23 13:41:44.602  3666  3666 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-23 13:41:44.602  3666  3666 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-23 13:41:44.602  3666  3666 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-23 13:41:44.602  3666  3666 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 13:41:44.603  3666  3666 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 13:41:44.603  3666  3666 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-23 13:41:44.603  3666  3666 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-23 13:41:44.603  3666  3666 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 13:41:44.603  3666  3666 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 13:41:44.603  3666  3666 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-23 13:41:44.603  3666  3666 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-23 13:41:44.605  1838  1838 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
08-23 13:41:44.638   966  1037 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6888 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-23 13:41:44.652  3338  3338 I art     : Explicit concurrent mark sweep GC freed 3096(150KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 16MB/21MB, paused 1.008ms total 168.966ms
08-23 13:41:44.671  1371  1371 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-23 13:41:44.720  1371  1371 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
,08-23 13:41:44.723  1371  1371 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-23 13:41:44.746  1371  1512 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-23 13:41:44.746  1371  1512 D KeyguardModel: createShortcutInfo...
,08-23 13:41:44.761  1371  1512 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-23 13:41:44.761  1371  1512 D KeyguardModel: createShortcutInfo...
,08-23 13:41:44.763  1371  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:41:44.765  1371  1512 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-23 13:41:44.767  1371  1512 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-23 13:41:44.767  1371  1512 D KeyguardModel: createShortcutInfo...
08-23 13:41:44.769  1371  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:41:44.769  1371  1512 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-23 13:41:44.771  1371  1512 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-23 13:41:44.771  1371  1512 D KeyguardModel: createShortcutInfo...
08-23 13:41:44.773  1371  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:41:44.773  1371  1512 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-23 13:41:44.782  1371  1512 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-23 13:41:44.783  1371  1512 D KeyguardModel: createShortcutInfo...
08-23 13:41:44.789  1371  1371 D KeyguardModel: handleShortcutListChanged...
,08-23 13:41:44.794  1371  1512 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-23 13:41:44.794  1371  1512 D KeyguardModel: createShortcutInfo...
08-23 13:41:44.795  6888  6888 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 13:41:44.796  6888  6888 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 13:41:44.797  6888  6888 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-23 13:41:44.800  1371  1512 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-23 13:41:44.800  1371  1512 D KeyguardModel: createShortcutInfo...
,08-23 13:41:44.802  1371  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:41:44.802  1371  1512 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-23 13:41:44.804  1371  1512 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-23 13:41:44.804  1371  1512 D KeyguardModel: createShortcutInfo...
08-23 13:41:44.805   966   966 I art     : Explicit concurrent mark sweep GC freed 46899(3MB) AllocSpace objects, 12(192KB) LOS objects, 33% free, 23MB/35MB, paused 3.389ms total 241.669ms
08-23 13:41:44.805   966  1062 I art     : WaitForGcToComplete blocked for 155.694ms for cause Explicit
08-23 13:41:44.806  1371  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:41:44.806  1371  1512 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-23 13:41:44.807  1371  1512 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-23 13:41:44.808  1371  1512 D KeyguardModel: createShortcutInfo...
08-23 13:41:44.813  1371  1512 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:41:44.813  1371  1512 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-23 13:41:44.819  1371  1512 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-23 13:41:44.819  1371  1512 D KeyguardModel: createShortcutInfo...
,08-23 13:41:44.832  1371  1371 D KeyguardModel: handleShortcutListChanged...
,08-23 13:41:44.868   966   966 D administrator: Handling package changes for user 0
,08-23 13:41:44.964   966   966 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-23 13:41:44.964   966   966 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-23 13:41:44.968   966   966 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-23 13:41:44.975   966  1351 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
08-23 13:41:44.981   966  1036 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 13:41:44.993  6888  6888 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-23 13:41:45.011  6888  6888 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,08-23 13:41:45.015   966  1036 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-23 13:41:45.035  1876  1876 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-23 13:41:45.039   966  1062 I art     : Explicit concurrent mark sweep GC freed 7416(451KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 4.195ms total 231.286ms
,08-23 13:41:45.114  6843  6843 D AndroidRuntime: Shutting down VM
,08-23 13:41:45.162   966  1062 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6910 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-23 13:41:45.162  1785  1785 D LCardEmulationManager: getHceAppCount hostAppNum : 0
08-23 13:41:45.162  1785  1785 D LCardEmulationManager: getDefaultRoute
,08-23 13:41:45.221  6888  6888 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-23 13:41:45.257   966  1349 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=6928 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-23 13:41:45.263   966   985 I ActivityManager: Killing 6464:com.google.android.talk/u0a61 (adj 15): empty #11
08-23 13:41:45.291   966  1784 W libprocessgroup: failed to open /acct/uid_10061/pid_6464/cgroup.procs: No such file or directory
,08-23 13:41:45.320  6928  6928 I AppUp4:AppBoxCP: onCreate
08-23 13:41:45.320  6928  6928 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-23 13:41:45.330  6928  6928 I AppUp4:DB:  setFingerPrint start
08-23 13:41:45.330  6928  6928 I AppUp4:DB:  newfinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys SDK version = 21
08-23 13:41:45.336  6928  6928 I AppUp4:DB:  beforefinger = lge/jagnm_global_com/jagnm:5.0.2/LRX22G.A1440040099/152321208d526:user/release-keys
08-23 13:41:45.336  6928  6928 I AppUp4:DB:  SDK version = 21
,08-23 13:41:45.336  6928  6928 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-23 13:41:45.338  6928  6928 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-23 13:41:45.353  6928  6928 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-23 13:41:45.389   966  1923 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6950 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
08-23 13:41:45.391   966  1923 I ActivityManager: Killing 6523:com.android.gallery3d/u0a23 (adj 15): empty #11
08-23 13:41:45.414   966  1875 W libprocessgroup: failed to open /acct/uid_10023/pid_6523/cgroup.procs: No such file or directory

```
