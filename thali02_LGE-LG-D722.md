#### Test 83627337a1c904e_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
09-07 09:35:38.424  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:35:38.424  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:35:38.424  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:35:38.424  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
--------- beginning of system
09-07 09:35:38.425  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 09:35:38.433   486   486 D charger_monitor: init target 500000
09-07 09:35:38.438   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-07 09:35:38.477  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 09:35:38.480  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 290
09-07 09:35:38.480  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:35:38.481  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:35:38.482  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:35:38.482  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:35:38.482  1804  1973 D LEDHandler: Battery Temp: 290, mChargingStatus=5, mChargingStop=false
09-07 09:35:38.483  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:35:38.483  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 290
09-07 09:35:38.485  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:35:38.489   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:35:38.489   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:35:38.492   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:35:38.891  6751  6751 D AndroidRuntime: 
09-07 09:35:38.891  6751  6751 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-07 09:35:38.902  6751  6751 D AndroidRuntime: CheckJNI is OFF
09-07 09:35:39.277  6751  6751 D AndroidRuntime: Calling main entry com.android.commands.am.Am
09-07 09:35:39.294   852  1875 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-07 09:35:39.340   852  1875 D ActivityManager: setTaskToReturnTo : TaskRecord{57803da #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-07 09:35:39.340   852  1875 D ActivityManager: setTaskToReturnTo : TaskRecord{57803da #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-07 09:35:39.350   852  1875 D WindowStateEx: AppWindowTokenEx init.. 
09-07 09:35:39.352   292   347 I ThermalEngine: Sensor:pa_therm0:31000 mC
09-07 09:35:39.393   852  1875 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6779 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-07 09:35:39.394   852  1875 D InputDispatcher: Focus left window: Window{2cb85150 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
09-07 09:35:39.395  6751  6751 D AndroidRuntime: Shutting down VM
09-07 09:35:39.408  1879  1879 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
09-07 09:35:39.437   852   852 V ActivityManager: Display changed displayId=0
09-07 09:35:39.440  1752  1752 D DSDPConnection: Display #0 changed.
09-07 09:35:39.575  6779  6779 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,09-07 09:35:39.692  6779  6779 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,09-07 09:35:39.749  6779  6779 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 8586-8589)
,09-07 09:35:39.749  6779  6779 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 09:35:39.791  6779  6779 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {16459db9}
,09-07 09:35:39.792  6779  6779 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-07 09:35:39.792  6779  6779 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
09-07 09:35:39.807  6779  6779 I BrowserStartupController: Initializing chromium process, singleProcess=true
,09-07 09:35:39.808  6779  6779 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 09:35:39.809  6779  6779 E SysUtils: ApplicationContext is null in ApplicationStatus
09-07 09:35:39.841  6779  6779 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-07 09:35:39.851  6779  6779 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 09:35:39.851  6779  6779 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-07 09:35:39.851  6779  6779 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-07 09:35:39.851  6779  6779 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-07 09:35:39.851  6779  6779 I Adreno-EGL: Build Date: 03/02/15 Mon
09-07 09:35:39.851  6779  6779 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-07 09:35:39.851  6779  6779 I Adreno-EGL: Remote Branch: 
09-07 09:35:39.851  6779  6779 I Adreno-EGL: Local Patches: 
09-07 09:35:39.851  6779  6779 I Adreno-EGL: Reconstruct Branch: 
,09-07 09:35:39.918   278  1376 V AudioPolicyService: registerClient() client 0xb3a4c960, uid 10030
,09-07 09:35:39.935   852  1043 D BluetoothManagerService: Message: 20
09-07 09:35:39.936   852  1043 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@acc617e:true
09-07 09:35:39.938  2027  2061 D BluetoothAdapterService(408752479): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2e6da52d
,09-07 09:35:39.982   852   988 W ActivityManager: Activity pause timeout for ActivityRecord{39e2400b u0 com.test.thalitest/.MainActivity t259}
,09-07 09:35:40.110  6779  6779 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-07 09:35:40.123  6779  6779 W AwContents: onDetachedFromWindow called when already detached. Ignoring
09-07 09:35:40.129  6779  6779 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,09-07 09:35:40.134  6779  6779 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-07 09:35:40.134  6779  6779 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
09-07 09:35:40.153  6779  6779 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-07 09:35:40.161  6779  6779 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 09:35:40.161  6779  6779 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-07 09:35:40.213  6779  6779 I Activity: Activity.onPostResume() called 
,09-07 09:35:40.219  6779  6830 D OpenGLRenderer: Render dirty regions requested: true
09-07 09:35:40.219  6779  6830 I OpenGLRenderer: Initialized EGL, version 1.4
09-07 09:35:40.228  6779  6830 D OpenGLRenderer: Enabling debug mode 0
,09-07 09:35:40.248  6779  6779 D Atlas   : Validating map...
,09-07 09:35:40.255   852  1382 D SplitWindow: check instance of lgWin Window{1b92262e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-07 09:35:40.271  6779  6817 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
09-07 09:35:40.299   852  1041 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
,09-07 09:35:40.302   852  1041 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
09-07 09:35:40.302  1373  1373 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
09-07 09:35:40.302  1373  1373 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
09-07 09:35:40.302  1373  1373 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
09-07 09:35:40.302  1373  1373 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
09-07 09:35:40.303   852  1041 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
09-07 09:35:40.303   852  1041 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
09-07 09:35:40.303   852  1041 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-07 09:35:40.303   852  1041 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2e5fcd98,  pkg=WindowManager.LayoutParams
09-07 09:35:40.303   852  1041 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
09-07 09:35:40.310   852  1847 D InputDispatcher: Focus entered window: Window{1b92262e u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 09:35:40.334   852  1792 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,09-07 09:35:40.354  6779  6779 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-07 09:35:40.354   852  1044 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +887ms (total +996ms)
09-07 09:35:40.355   852  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{39e2400b u0 com.test.thalitest/.MainActivity t259} time:189195
09-07 09:35:40.356  6779  6779 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@101a626b time:189196
09-07 09:35:40.403  6779  6779 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
09-07 09:35:40.407  1627  1627 E b       : Unable to connect to the editor to retrieve text... will retry later
,09-07 09:35:40.434  6779  6779 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,09-07 09:35:40.474  6779  6779 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6779
,09-07 09:35:40.610  6779  6779 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-07 09:35:40.971  6779  6837 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1635546368
,09-07 09:35:40.988  6779  6837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-07 09:35:40.988  6779  6837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-07 09:35:40.988  6779  6837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-07 09:35:40.988  6779  6837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-07 09:35:40.988  6779  6837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-07 09:35:40.988  6779  6837 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@247eab3f added. We now have 1 listener(s)
09-07 09:35:40.995   852  2157 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 09:35:41.000  6779  6837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
09-07 09:35:41.001  6779  6837 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-07 09:35:41.002  6779  6837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 09:35:41.002  6779  6837 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,09-07 09:35:41.007  6779  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-07 09:35:41.007  6779  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-07 09:35:41.007  6779  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-07 09:35:41.007  6779  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
09-07 09:35:41.007  6779  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-07 09:35:41.007  6779  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-07 09:35:41.007  6779  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-07 09:35:41.007  6779  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-07 09:35:41.007  6779  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-07 09:35:41.007  6779  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-07 09:35:41.007  6779  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-07 09:35:41.007  6779  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-07 09:35:41.007  6779  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-07 09:35:41.007  6779  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-07 09:35:41.007  6779  6837 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@18187f6a added. We now have 1 listener(s)
09-07 09:35:41.008  6779  6837 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-07 09:35:41.022  6779  6837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 09:35:41.022  6779  6837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
09-07 09:35:41.022  6779  6837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,09-07 09:35:41.022  6779  6837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-07 09:35:41.022  6779  6837 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-07 09:35:41.027  6779  6837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:35:41.027   852  2193 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 09:35:41.028  6779  6837 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
09-07 09:35:41.036  2027  2061 D BluetoothAdapterService(408752479): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2e6da52d
,09-07 09:35:41.040  6779  6837 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-07 09:35:41.040  6779  6837 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:35:41.040  6779  6837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:41.040  6779  6837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 09:35:41.040  6779  6837 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:35:41.040  6779  6837 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:35:41.040  6779  6837 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:35:41.040  6779  6837 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:35:41.040  6779  6837 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:35:41.040  6779  6837 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
09-07 09:35:41.040  6779  6837 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 09:35:41.042  6779  6779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:41.043  6779  6779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:41.043  6779  6837 I io.jxcore.node.LifeCycleMonitor: start: OK
09-07 09:35:41.100  6779  6779 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-07 09:35:41.222  6779  6793 I art     : CheckpointMarkThreadRoots callback created = 0x9e9b17c0
,09-07 09:35:41.264  6779  6793 I art     : CheckpointMarkThreadRoots callback created = 0x9e9b1780
,09-07 09:35:41.916  6779  6847 W jxcore-log: Initializing JXcore engine
,09-07 09:35:41.917  6779  6847 W jxcore-log: JXcore engine is ready
09-07 09:35:42.032  6847  6847 W Thread-804: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[4714]" dev="sockfs" ino=4714 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-07 09:35:42.032  6847  6847 W Thread-804: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-07 09:35:42.032  6847  6847 W Thread-804: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6862]" dev="sockfs" ino=6862 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-07 09:35:42.032  6847  6847 W Thread-804: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
09-07 09:35:42.032  6847  6847 W Thread-804: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
09-07 09:35:42.032  6847  6847 W Thread-804: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[30255]" dev="sockfs" ino=30255 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-07 09:35:42.066  6779  6847 W jxcore-log: Starting JXcore engine
,09-07 09:35:42.216  6779  6847 W jxcore-log: Platform android
09-07 09:35:42.216  6779  6847 W jxcore-log: 
09-07 09:35:42.216  6779  6847 W jxcore-log: Process ARCH arm
09-07 09:35:42.216  6779  6847 W jxcore-log: 
,09-07 09:35:42.500  6779  6847 I jxcore-log: JXcore Cordova bridge is ready!
09-07 09:35:42.500  6779  6847 I jxcore-log: 
09-07 09:35:42.500  6779  6847 W jxcore-log: JXcore engine is started
,09-07 09:35:42.505  6779  6837 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-07 09:35:42.513  6779  6779 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,09-07 09:35:43.718   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:35:43.718   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:35:43.718   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 192558050243; DSPS: 6408249; Offset : -3017802329
,09-07 09:35:44.357   292   347 I ThermalEngine: Sensor:pa_therm0:31000 mC
,09-07 09:35:49.362   292   347 I ThermalEngine: Sensor:pa_therm0:31000 mC
,09-07 09:35:54.366   292   347 I ThermalEngine: Sensor:pa_therm0:31000 mC
,09-07 09:35:58.069  6779  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-07 09:35:58.069  6779  6847 I jxcore-log: 
,09-07 09:35:58.073  6779  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-07 09:35:58.073  6779  6847 I jxcore-log: 
09-07 09:35:58.079  2027  2068 D BluetoothAdapterService(408752479): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2e6da52d
09-07 09:35:58.080  6779  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:35:58.080  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:58.080  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 09:35:58.080  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:35:58.080  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:35:58.080  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:35:58.080  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:35:58.080  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:35:58.086  2027  3462 D BluetoothAdapterService(408752479): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2e6da52d
,09-07 09:35:58.087  6779  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 09:35:58.091  6779  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-07 09:35:58.091  6779  6847 I jxcore-log: 
09-07 09:35:58.094  6779  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-07 09:35:58.094  6779  6847 I jxcore-log: 
09-07 09:35:58.902  6779  6847 I jxcore-log: Unit Test app is loaded
09-07 09:35:58.902  6779  6847 I jxcore-log: 
,09-07 09:35:58.914  6779  6847 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-07 09:35:58.914  6779  6847 I jxcore-log: 
,09-07 09:35:58.923  6779  6847 D executeNativeTests: Running unit tests
09-07 09:35:58.925  6779  6779 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
09-07 09:35:59.144  6779  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-07 09:35:59.144  6779  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11174eae added. We now have 2 listener(s)
,09-07 09:35:59.146   852  1875 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-07 09:35:59.148  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-07 09:35:59.148  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-07 09:35:59.148  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-07 09:35:59.148  6779  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-07 09:35:59.148  6779  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2979b44f added. We now have 2 listener(s)
09-07 09:35:59.148  6779  6847 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-07 09:35:59.149  6779  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-07 09:35:59.151  6779  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:35:59.153  2027  3461 D BluetoothAdapterService(408752479): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2e6da52d
09-07 09:35:59.154  6779  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:35:59.154  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:59.154  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 09:35:59.154  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:35:59.154  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:35:59.154  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:35:59.154  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:35:59.154  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:35:59.155  2027  2068 D BluetoothAdapterService(408752479): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2e6da52d
09-07 09:35:59.155  6779  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,09-07 09:35:59.155  6779  6847 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 09:35:59.157  6779  6779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:59.159  6779  6779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:59.160  2027  3461 D BluetoothAdapterService(408752479): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2e6da52d
09-07 09:35:59.167  6779  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 09:35:59.168  6779  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 09:35:59.168  6779  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 09:35:59.175  6779  6847 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
09-07 09:35:59.176  6779  6847 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-07 09:35:59.176  6779  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 09:35:59.176  6779  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 09:35:59.176  6779  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-07 09:35:59.178  6779  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:35:59.178  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:59.178  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 09:35:59.178  6779  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,09-07 09:35:59.179  6779  6847 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11174eae removed from the list
09-07 09:35:59.179  6779  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,09-07 09:35:59.179  6779  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2979b44f removed from the list
09-07 09:35:59.179  6779  6847 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:35:59.179  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:35:59.191  6779  6847 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-07 09:35:59.191  6779  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:35:59.191  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:59.191  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:35:59.191  6779  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11174eae not in the list
09-07 09:35:59.191  6779  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:35:59.191  6779  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2979b44f not in the list
09-07 09:35:59.191  6779  6847 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:35:59.191  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:59.191  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:35:59.197  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 09:35:59.197  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 09:35:59.197  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 09:35:59.197  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 09:35:59.197  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 09:35:59.197  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 09:35:59.197  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 09:35:59.197  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 09:35:59.197  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 09:35:59.197  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 09:35:59.197  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 09:35:59.197  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 09:35:59.197  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 09:35:59.197  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 09:35:59.197  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<,no peer name> 23:1310:1310:1310:1310:1310]
09-07 09:35:59.197  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 09:35:59.197  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 09:35:59.197  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 09:35:59.197  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,09-07 09:35:59.197  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 09:35:59.197  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 09:35:59.197  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 09:35:59.197  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 09:35:59.198  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-07 09:35:59.198  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 09:35:59.198  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 09:35:59.198  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 09:35:59.198  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 09:35:59.198  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 09:35:59.198  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 09:35:59.198  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-07 09:35:59.198  6779  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:35:59.198  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:59.198  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:35:59.198  6779  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11174eae not in the list
09-07 09:35:59.198  6779  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:35:59.198  6779  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2979b44f not in the list
09-07 09:35:59.198  6779  6847 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:35:59.198  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:35:59.198  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:35:59.199  6779  6847 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 09:35:59.201  6779  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:35:59.204  2027  3461 D BluetoothAdapterService(408752479): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2e6da52d
09-07 09:35:59.205  6779  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:35:59.205  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:35:59.205  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 09:35:59.205  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:35:59.205  6779  6847 V io.jxc,ore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:35:59.205  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:35:59.205  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:35:59.205  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:35:59.206  2027  2068 D BluetoothAdapterService(408752479): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2e6da52d
09-07 09:35:59.206  6779  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 09:35:59.207  6779  6847 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 09:35:59.207  6779  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 09:35:59.208  6779  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 09:35:59.208  6779  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 09:35:59.208  6779  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:35:59.208  6779  6847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 09:35:59.208  6779  6779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:59.211  6779  6779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:35:59.213  6779  6847 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
09-07 09:35:59.214   852  2157 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-07 09:35:59.221  2027  2061 D BluetoothAdapterService(408752479): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2e6da52d
09-07 09:35:59.224  2027  3462 D BluetoothAdapterService(408752479): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2e6da52d
09-07 09:35:59.225  6779  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,09-07 09:35:59.231  2027  3461 D BluetoothAdapterService(408752479): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2e6da52d
09-07 09:35:59.233  6779  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-07 09:35:59.234  2027  3462 D BluetoothAdapterService(408752479): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2e6da52d
09-07 09:35:59.235  6779  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
09-07 09:35:59.235  6779  6847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 09:35:59.236  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 09:35:59.240  6779  6847 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 09:35:59.240  6779  6847 I io.jxcore.node.ConnectionHelper: start: OK
,09-07 09:35:59.371   292   347 I ThermalEngine: Sensor:pa_therm0:31000 mC
,09-07 09:36:00.054  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:36:00.054  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:36:00.054  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:36:00.060  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:36:00.060  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:36:00.061  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:36:00.062  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:36:02.243  6779  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-07 09:36:02.243  6779  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-07 09:36:02.243  6779  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 09:36:03.720   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:36:03.720   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:36:03.720   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 212559763968; DSPS: 7063665; Offset : -3017795557
,09-07 09:36:04.378   292   347 I ThermalEngine: Sensor:pa_therm0:31000 mC
,09-07 09:36:05.250  6779  6847 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 09:36:05.250  6779  6847 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-07 09:36:05.250  6779  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 09:36:05.250  6779  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 09:36:05.250  6779  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 09:36:05.250  6779  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:36:05.250  6779  6847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,09-07 09:36:05.257  2027  3461 D BluetoothAdapterService(408752479): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2e6da52d
09-07 09:36:05.258  6779  6847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 09:36:05.259  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 09:36:05.261  6779  6847 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 09:36:05.261  6779  6847 I io.jxcore.node.ConnectionHelper: start: OK
09-07 09:36:08.262  6779  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:36:08.262  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:08.262  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 09:36:08.262  6779  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11174eae not in the list
09-07 09:36:08.262  6779  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:36:08.263  6779  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2979b44f not in the list
09-07 09:36:08.263  6779  6847 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:36:08.263  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:36:08.267  6779  6847 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 09:36:08.270  6779  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:36:08.273  2027  3462 D BluetoothAdapterService(408752479): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2e6da52d
09-07 09:36:08.274  6779  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:36:08.274  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:36:08.274  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 09:36:08.274  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:36:08.274  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:36:08.274  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:36:08.274  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:36:08.274  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:36:08.276  2027  2061 D BluetoothAdapterService(408752479): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2e6da52d
,09-07 09:36:08.278  6779  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 09:36:08.278  6779  6847 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 09:36:08.280  6779  6779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:36:08.282  6779  6779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:36:08.283  6779  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 09:36:08.283  6779  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 09:36:08.283  6779  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 09:36:08.283  6779  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:36:08.283  6779  6847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 09:36:08.288  2027  2068 D BluetoothAdapterService(408752479): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2e6da52d
,09-07 09:36:08.291  6779  6847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 09:36:08.292  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 09:36:08.293  6779  6847 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 09:36:08.294  6779  6847 I io.jxcore.node.ConnectionHelper: start: OK
09-07 09:36:09.384   292   347 I ThermalEngine: Sensor:pa_therm0:31000 mC
,09-07 09:36:11.295  6779  6847 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-07 09:36:11.295  6779  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-07 09:36:11.295  6779  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-07 09:36:14.304  6779  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:36:14.304  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:14.304  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-07 09:36:14.304  6779  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11174eae not in the list
09-07 09:36:14.304  6779  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:36:14.304  6779  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2979b44f not in the list
09-07 09:36:14.304  6779  6847 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:36:14.304  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,09-07 09:36:14.309  6779  6847 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-07 09:36:14.309  6779  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:36:14.310  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:14.310  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:14.310  6779  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11174eae not in the list
09-07 09:36:14.310  6779  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:36:14.310  6779  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2979b44f not in the list
09-07 09:36:14.310  6779  6847 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:36:14.310  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:14.310  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:14.312  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-07 09:36:14.312  6779  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:36:14.312  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:14.312  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:14.312  6779  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11174eae not in the list
09-07 09:36:14.312  6779  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:36:14.312  6779  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2979b44f not in the list
09-07 09:36:14.312  6779  6847 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:36:14.312  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:14.312  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:14.313  6779  6847 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-07 09:36:14.313  6779  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:36:14.313  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:14.313  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:14.313  6779  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11174eae not in the list
09-07 09:36:14.313  6779  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:36:14.313  6779  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2979b44f not in the list
09-07 09:36:14.313  6779  6847 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:36:14.313  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Bluetooth,Manager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:14.313  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:14.314  6779  6847 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-07 09:36:14.314  6779  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:36:14.314  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:14.315  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:14.315  6779  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11174eae not in the list
09-07 09:36:14.315  6779  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:36:14.315  6779  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2979b44f not in the list
09-07 09:36:14.315  6779  6847 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 09:36:14.315  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:14.315  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:14.316  6779  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-07 09:36:14.319  6779  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 09:36:14.319  6779  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-07 09:36:14.319  6779  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,09-07 09:36:14.329  6779  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-07 09:36:14.329  6779  6847 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-07 09:36:14.329  6779  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:36:14.329  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:14.329  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:14.329  6779  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11174eae not in the list
09-07 09:36:14.329  6779  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:36:14.330  6779  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2979b44f not in the list
09-07 09:36:14.330  6779  6847 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:36:14.330  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:14.330  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:14.334  6779  6847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,09-07 09:36:14.337  6779  6847 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 09:36:14.337  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-07 09:36:14.341  6779  6847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 09:36:14.344  6779  6847 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-07 09:36:14.344  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-07 09:36:14.344  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-07 09:36:14.345  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-07 09:36:14.345  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-07 09:36:14.345  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-07 09:36:14.345  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-07 09:36:14.345  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-07 09:36:14.345  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-07 09:36:14.345  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-07 09:36:14.345  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-07 09:36:14.345  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-07 09:36:14.345  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-07 09:36:14.345  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-07 09:36:14.345  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-07 09:36:14.345  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-07 09:36:14.345  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-07 09:36:14.346  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-07 09:36:14.346  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-07 09:36:14.346  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-07 09:36:14.346  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-07 09:36:14.346  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-07 09:36:14.346  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-07 09:36:14.346  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:22,10:2210]
09-07 09:36:14.347  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-07 09:36:14.347  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-07 09:36:14.347  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-07 09:36:14.347  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-07 09:36:14.347  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-07 09:36:14.347  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-07 09:36:14.347  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910],
09-07 09:36:14.347  6779  6847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
,09-07 09:36:14.354  6779  6847 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 09:36:14.355  6779  6847 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-07 09:36:14.355  6779  6847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 09:36:14.355  6779  6847 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 09:36:14.355  6779  6847 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-07 09:36:14.355  6779  6847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 09:36:14.355  6779  6847 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-07 09:36:14.355  6779  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-07 09:36:14.372  6779  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-07 09:36:14.374  6779  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-07 09:36:14.374  6779  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-07 09:36:14.379  6779  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-07 09:36:14.379  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-07 09:36:14.379  6779  6847 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-07 09:36:14.380  6779  6847 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-07 09:36:14.380  6779  6847 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-07 09:36:14.380  6779  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:36:14.380  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:14.380  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:14.381  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-07 09:36:14.381  6779  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11174eae not in the list
09-07 09:36:14.381  6779  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:36:14.381  6779  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2979b44f not in the list
09-07 09:36:14.381  6779  6847 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:36:14.381  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:14.381  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:14.382  6779  6847 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-07 09:36:14.383  6779  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:36:14.383  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:14.383  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:14.383  6779  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11174eae not in the list
09-07 09:36:14.383  6779  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:36:14.383  6779  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2979b44f not in the list
09-07 09:36:14.383  6779  6847 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:36:14.383  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:14.383  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:14.386  6779  6847 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-07 09:36:14.387  6779  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:36:14.387  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:14.387  6779  6847 D, org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:14.387  6779  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11174eae not in the list
09-07 09:36:14.387  6779  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:36:14.387  6779  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2979b44f not in the list
09-07 09:36:14.387  6779  6847 D io.jxcore.node.ConnectivityMonitor: stop
09-07 09:36:14.387  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:14.387  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:14.388  6779  6847 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-07 09:36:14.388   292   347 I ThermalEngine: Sensor:pa_therm0:31000 mC,
09-07 09:36:14.392  6779  6881 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 901
,09-07 09:36:14.398  6779  6847 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-07 09:36:14.399  6779  6880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 901)
09-07 09:36:14.399  6779  6880 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 901)
09-07 09:36:14.399  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-07 09:36:14.400  6779  6847 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-07 09:36:14.400  6779  6847 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 09:36:14.400  6779  6847 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-07 09:36:14.400  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 09:36:14.400  6779  6847 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-07 09:36:14.400  6779  6847 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-07 09:36:14.400  6779  6847 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-07 09:36:14.400  6779  6847 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-07 09:36:14.400  6779  6847 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-07 09:36:14.400  6779  6847 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-07 09:36:14.400  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:14.400  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:14.401  6779  6847 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@11174eae not in the list
09-07 09:36:14.401  6779  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-07 09:36:14.401  6779  6847 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2979b44f not in the list
09-07 09:36:14.401  6779  6847 D io.jxcore.node.ConnectivityMonitor: stop
,09-07 09:36:14.401  6779  6847 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-07 09:36:14.401  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
09-07 09:36:14.403  6779  6847 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-07 09:36:14.407  6779  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener,
,09-07 09:36:14.414  2027  3462 D BluetoothAdapterService(408752479): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2e6da52d
09-07 09:36:14.415  6779  6847 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-07 09:36:14.415  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-07 09:36:14.415  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-07 09:36:14.415  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-07 09:36:14.415  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-07 09:36:14.415  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-07 09:36:14.415  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-07 09:36:14.415  6779  6847 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-07 09:36:14.416  2027  2061 D BluetoothAdapterService(408752479): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2e6da52d
09-07 09:36:14.417  6779  6847 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-07 09:36:14.418  6779  6847 D io.jxcore.node.ConnectivityMonitor: start: OK
09-07 09:36:14.420  6779  6779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-07 09:36:14.423  6779  6779 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-07 09:36:14.424  6779  6847 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-07 09:36:14.424  6779  6847 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-07 09:36:14.424  6779  6847 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-07 09:36:14.424  6779  6847 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-07 09:36:14.424  6779  6847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-07 09:36:14.429  2027  2068 D BluetoothAdapterService(408752479): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@2e6da52d
09-07 09:36:14.431  6779  6847 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-07 09:36:14.431  6779  6847 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-07 09:36:14.435  6779  6847 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-07 09:36:14.435  6779  6847 I io.jxcore.node.ConnectionHelper: start: OK
09-07 09:36:18.169   852  1286 D PowerManagerServiceEx: acquireWakeLockInternal: lock=427605554, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=852
,09-07 09:36:18.174   852  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{e418345 type 2 when 214000 android} when 214000
09-07 09:36:18.175   852  1286 V AlarmManager: RTC_WAKEUP set : Alarm{14421a9a type 0 when 1473233774394 com.google.android.gms} when 1473233774394
09-07 09:36:18.233   852   852 D PowerManagerServiceEx: releaseWakeLockInternal: lock=427605554 [*alarm*], flags=0x0
,09-07 09:36:18.296  3400  6883 I EventLogChimeraService: Aggregate from 1473233661212 (log), 1473231974338 (data)
,09-07 09:36:18.427  3400  6895 D DropBoxEntryAddedChimeraService: User is not opted-in to Usage & Diagnostics or Lockbox.
,09-07 09:36:19.394   292   347 I ThermalEngine: Sensor:pa_therm0:31000 mC
,09-07 09:36:23.721   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:36:23.721   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:36:23.721   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 232561197771; DSPS: 7719072; Offset : -3017797278
,09-07 09:36:24.400   292   347 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 09:36:29.406   292   347 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 09:36:34.413   292   347 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 09:36:38.584  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:36:38.585  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:36:38.585  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:36:38.585  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:36:38.592   486   486 D charger_monitor: init target 500000
09-07 09:36:38.595  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:36:38.597   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:36:38.653  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:36:38.656  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
09-07 09:36:38.658  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:36:38.658  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:36:38.660  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:36:38.660  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:36:38.660  1804  1973 D LEDHandler: Battery Temp: 287, mChargingStatus=5, mChargingStop=false
09-07 09:36:38.661  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:36:38.661  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
09-07 09:36:38.663  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:36:38.668   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:36:38.668   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:36:38.671   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:36:39.419   292   347 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 09:36:43.723   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:36:43.723   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:36:43.723   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 252563489706; DSPS: 8374507; Offset : -3017793015
,09-07 09:36:44.425   292   347 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 09:36:47.598  1734  4302 I ClearcutLoggerApiImpl: disconnect managed GoogleApiClient
,09-07 09:36:49.431   292   347 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 09:36:54.437   292   347 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 09:36:59.443   292   347 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 09:37:00.055  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:37:00.055  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:37:00.055  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:37:00.059  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:37:00.059  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:37:00.060  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:37:00.061  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:37:03.726   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:37:03.726   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:37:03.726   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 272565782151; DSPS: 9029942; Offset : -3017791395
,09-07 09:37:04.450   292   347 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 09:37:09.456   292   347 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 09:37:14.462   292   347 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 09:37:19.468   292   347 I ThermalEngine: Sensor:pa_therm0:30000 mC
,09-07 09:37:23.728   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:37:23.728   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:37:23.728   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 292568093252; DSPS: 9685378; Offset : -3017797598
,09-07 09:37:24.474   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:37:29.480   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:37:33.434  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:37:33.434  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:37:33.434  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:37:33.434  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:37:33.441   486   486 D charger_monitor: init target 500000
09-07 09:37:33.444  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:37:33.446   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:37:33.511  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
09-07 09:37:33.511  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:37:33.511  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
,09-07 09:37:33.514  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:37:33.514  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:37:33.515  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:37:33.515  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:37:33.515  1804  1973 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
09-07 09:37:33.518  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 09:37:33.520  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:37:33.523   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:37:33.523   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:37:33.526   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:37:33.563  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:37:33.566  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
09-07 09:37:33.566  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:37:33.567  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:37:33.568  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:37:33.568  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:37:33.568  1804  1973 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
09-07 09:37:33.569  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:37:33.569  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 285
09-07 09:37:33.571  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:37:33.575   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:37:33.575   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:37:33.578   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:37:34.486   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:37:38.745   486   486 D charger_monitor: init target 500000
,09-07 09:37:38.750   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-07 09:37:38.753  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:37:38.760  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:37:38.760  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:37:38.760  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:37:38.763  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:37:38.794  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 284
,09-07 09:37:38.796  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:37:38.797  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 284
09-07 09:37:38.799  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:37:38.799  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:37:38.801  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:37:38.801  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:37:38.801  1804  1973 D LEDHandler: Battery Temp: 284, mChargingStatus=5, mChargingStop=false
09-07 09:37:38.804  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:37:38.806  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:37:38.812   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:37:38.812   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:37:38.812   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:37:39.493   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:37:43.730   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:37:43.730   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:37:43.730   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 312570450775; DSPS: 10340816; Offset : -3017820133
,09-07 09:37:44.499   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:37:49.505   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:37:54.511   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:37:59.517   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:38:00.055  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:38:00.055  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:38:00.055  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:38:00.058  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:38:00.058  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:38:00.059  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:38:00.061  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:38:03.731   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:38:03.732   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:38:03.732   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 332571741062; DSPS: 10996219; Offset : -3017842284
,09-07 09:38:04.528   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:38:09.535   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:38:13.528   852  3190 I LocationManagerService: remove 24871556
,09-07 09:38:13.536   852  3190 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
09-07 09:38:13.537   852  3190 D LocationManagerService: getAllProviders()=[passive, gps, network]
09-07 09:38:13.537   852  3190 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
09-07 09:38:13.537   852  3190 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
09-07 09:38:13.538   852  3190 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,09-07 09:38:14.540   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:38:19.546   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:38:23.734   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:38:23.734   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:38:23.734   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 352574030759; DSPS: 11651654; Offset : -3017841614
,09-07 09:38:24.552   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:38:29.559   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:38:34.565   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:38:38.736   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:38:38.736   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:38:38.736   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 367576356666; DSPS: 12143250; Offset : -3017837023
,09-07 09:38:38.916  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:38:38.916  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:38:38.916  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:38:38.916  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:38:38.918  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:38:38.924   486   486 D charger_monitor: init target 500000
09-07 09:38:38.929   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:38:38.969  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:38:38.972  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 280
09-07 09:38:38.972  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:38:38.972  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:38:38.974  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:38:38.974  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:38:38.974  1804  1973 D LEDHandler: Battery Temp: 280, mChargingStatus=5, mChargingStop=false
09-07 09:38:38.975  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:38:38.975  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 280
09-07 09:38:38.977  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:38:38.981   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:38:38.981   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:38:38.984   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:38:39.571   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:38:44.577   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:38:49.583   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:38:54.590   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:38:58.738   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:38:58.738   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:38:58.738   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 387578367075; DSPS: 12798678; Offset : -3017899725
,09-07 09:38:59.596   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:39:00.054  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:39:00.054  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:39:00.054  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:39:00.058  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:39:00.058  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:39:00.058  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:39:00.059  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:39:04.602   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:39:06.184  6151  6195 I PlayCommon: [742] com.google.android.play.a.l.e(787): Preparing logs for uploading
,09-07 09:39:06.200  1734  1734 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-07 09:39:06.216  1734  1734 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
,09-07 09:39:06.220  1734  1734 I Auth    : [AuthDelegateWrapper] Service intent: Intent { cmp=com.google.android.gms/.auth.account.authenticator.DefaultAuthDelegateService }.
09-07 09:39:06.272   852  1878 I NotificationManager: android: cancelAsUser(2) by android
,09-07 09:39:06.278  6151  6195 I PlayCommon: [742] com.google.android.play.a.l.a(927): Connecting to server: https://play.googleapis.com/play/log?format=raw&proto_v2=true
09-07 09:39:06.318  6151  6195 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-07 09:39:06.318  6151  6195 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-07 09:39:06.319  6151  6195 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-07 09:39:06.319  6151  6195 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,09-07 09:39:06.330   270  1050 E BandwidthController: [LG DATA] No such appUid: 10036
09-07 09:39:06.330   270  1050 D DnsProxyListener: App 10036 tries DNS query. Accept family:0 protocol:0
09-07 09:39:06.332   270  6920 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
09-07 09:39:06.332   270  6920 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-07 09:39:06.332   270  6920 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1, netid=100
,09-07 09:39:06.335   270  6920 D libc-netbsd: res_queryN name = xxxxx, class = 1, type = 1
09-07 09:39:06.433   270  6920 D libc-netbsd: res_queryN name = xxxxx succeed
,09-07 09:39:06.437  6151  6195 I System.out: propertyValue:false
09-07 09:39:06.784  6151  6195 I PlayCommon: [742] com.google.android.play.a.l.a(1002): Successfully uploaded logs.
,09-07 09:39:09.608   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:39:14.614   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:39:18.740   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:39:18.741   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:39:18.741   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 407580748413; DSPS: 13454112; Offset : -3017778564
,09-07 09:39:19.621   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:39:24.627   292   347 I ThermalEngine: Sensor:pa_therm0:29000 mC
,09-07 09:39:29.633   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:39:33.743   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:39:33.743   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:39:33.743   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 422583013928; DSPS: 13945706; Offset : -3017769578
,09-07 09:39:34.639   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:39:39.063  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:39:39.063  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:39:39.063  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:39:39.063  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:39:39.065  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:39:39.071   486   486 D charger_monitor: init target 500000
09-07 09:39:39.076   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:39:39.116  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:39:39.119  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 279
09-07 09:39:39.120  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:39:39.120  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:39:39.120  1804  1973 D LEDHandler: Battery Temp: 279, mChargingStatus=5, mChargingStop=false
09-07 09:39:39.121  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:39:39.121  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:39:39.122  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:39:39.123  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 279
09-07 09:39:39.125  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:39:39.128   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:39:39.128   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:39:39.131   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:39:39.645   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:39:44.651   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:39:48.747   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:39:48.747   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:39:48.747   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 437587575911; DSPS: 14437378; Offset : -3017848247
,09-07 09:39:49.658   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:39:54.679   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:39:59.685   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:40:00.001   852  1286 D PowerManagerServiceEx: acquireWakeLockInternal: lock=427605554, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=852
,09-07 09:40:00.038  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:40:00.038  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:40:00.038  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:40:00.042  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:40:00.042  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:40:00.043  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:40:00.043  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:40:00.148   852   852 D PowerManagerServiceEx: releaseWakeLockInternal: lock=427605554 [*alarm*], flags=0x0
,09-07 09:40:00.790   852  1875 I ActivityManager: Process com.google.android.talk (pid 6412) has died
,09-07 09:40:03.750   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:40:03.750   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:40:03.750   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 452590545753; DSPS: 14928993; Offset : -3017775726
,09-07 09:40:04.701   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:40:09.707   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:40:14.713   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:40:18.753   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:40:18.753   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:40:18.753   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 467592874797; DSPS: 15420591; Offset : -3017826870
,09-07 09:40:19.719   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:40:24.726   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:40:29.732   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:40:34.738   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:40:38.755   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:40:38.755   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:40:38.755   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 487595187783; DSPS: 16076024; Offset : -3017741771
,09-07 09:40:39.223  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:40:39.223  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:40:39.223  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:40:39.223  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:40:39.225  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:40:39.231   486   486 D charger_monitor: init target 500000
09-07 09:40:39.236   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:40:39.276  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:40:39.279  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 276
09-07 09:40:39.280  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:40:39.280  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:40:39.280  1804  1973 D LEDHandler: Battery Temp: 276, mChargingStatus=5, mChargingStop=false
09-07 09:40:39.281  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:40:39.281  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:40:39.283  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:40:39.283  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 276
09-07 09:40:39.285  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:40:39.288   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:40:39.288   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:40:39.291   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:40:39.744   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:40:44.750   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:40:49.756   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:40:53.758   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:40:53.758   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:40:53.758   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 502597772206; DSPS: 16567631; Offset : -3017812221
,09-07 09:40:54.762   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:40:59.769   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:41:00.055  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:41:00.055  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:41:00.055  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:41:00.058  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:41:00.058  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:41:00.059  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:41:00.061  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:41:04.775   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:41:08.760   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:41:08.760   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:41:08.760   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 517600613435; DSPS: 17059244; Offset : -3017809102
,09-07 09:41:09.781   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:41:14.787   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:41:19.793   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:41:24.799   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:41:28.763   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:41:28.763   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:41:28.763   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 537603031554; DSPS: 17714682; Offset : -3017771510
,09-07 09:41:29.805   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:41:34.811   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:41:39.383  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:41:39.383  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:41:39.383  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:41:39.383  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:41:39.385  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:41:39.391   486   486 D charger_monitor: init target 500000
09-07 09:41:39.396   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:41:39.437  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:41:39.439  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 275
09-07 09:41:39.440  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:41:39.440  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:41:39.441  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:41:39.441  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:41:39.441  1804  1973 D LEDHandler: Battery Temp: 275, mChargingStatus=5, mChargingStop=false
09-07 09:41:39.443  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:41:39.443  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 275
09-07 09:41:39.445  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:41:39.448   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:41:39.449   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:41:39.451   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:41:39.818   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:41:44.824   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:41:48.765   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:41:48.765   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:41:48.765   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 557605282211; DSPS: 18370118; Offset : -3017840135
,09-07 09:41:49.830   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:41:54.836   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:41:59.842   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:42:00.055  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:42:00.055  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:42:00.055  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:42:00.058  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:42:00.058  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:42:00.059  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:42:00.061  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:42:04.849   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:42:08.767   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:42:08.767   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:42:08.767   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 577607612775; DSPS: 19025554; Offset : -3017828986
,09-07 09:42:09.855   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:42:14.861   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:42:19.867   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:42:24.873   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:42:28.770   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:42:28.770   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:42:28.770   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 597609862822; DSPS: 19680987; Offset : -3017806411
,09-07 09:42:29.880   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:42:34.315  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:42:34.315  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:42:34.315  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:42:34.315  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:42:34.323   486   486 D charger_monitor: init target 500000
09-07 09:42:34.325  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:42:34.328   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:42:34.405  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:42:34.408  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
09-07 09:42:34.408  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:42:34.408  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
09-07 09:42:34.409  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:42:34.409  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:42:34.411  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:42:34.411  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:42:34.411  1804  1973 D LEDHandler: Battery Temp: 274, mChargingStatus=5, mChargingStop=false
09-07 09:42:34.413  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:42:34.417   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:42:34.417   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:42:34.420   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:42:34.457  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:42:34.460  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:42:34.460  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:42:34.461  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:42:34.461  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:42:34.461  1804  1973 D LEDHandler: Battery Temp: 274, mChargingStatus=5, mChargingStop=false
09-07 09:42:34.462  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
09-07 09:42:34.463  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:42:34.463  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
09-07 09:42:34.465  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:42:34.469   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:42:34.469   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:42:34.472   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:42:34.886   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:42:39.550  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,09-07 09:42:39.552   486   486 D charger_monitor: init target 500000
09-07 09:42:39.554  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:42:39.554  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:42:39.554  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:42:39.557   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-07 09:42:39.558  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:42:39.595  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
,09-07 09:42:39.598  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:42:39.598  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
09-07 09:42:39.600  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:42:39.600  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:42:39.602  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:42:39.603  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:42:39.603  1804  1973 D LEDHandler: Battery Temp: 273, mChargingStatus=5, mChargingStop=false
09-07 09:42:39.606  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:42:39.608  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:42:39.613   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:42:39.613   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:42:39.614   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:42:39.892   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:42:44.898   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:42:48.772   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:42:48.772   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:42:48.772   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 617612277906; DSPS: 20336431; Offset : -3017955037
,09-07 09:42:49.904   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:42:54.910   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:42:59.917   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:43:00.054  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:43:00.055  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:43:00.055  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:43:00.058  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:43:00.058  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:43:00.060  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:43:00.061  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:43:04.923   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:43:05.441  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 09:43:05.444  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:43:05.444  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:43:05.444  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:43:05.444  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:43:05.477   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:43:05.512  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
,09-07 09:43:05.513  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:43:05.514  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:43:05.516   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
09-07 09:43:05.516  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:43:05.516  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:43:05.560  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
09-07 09:43:05.560  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:43:05.560  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
,09-07 09:43:05.568  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:43:05.568  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:43:05.570  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:43:05.570  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:43:05.570  1804  1973 D LEDHandler: Battery Temp: 274, mChargingStatus=5, mChargingStop=false
09-07 09:43:05.571  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 09:43:05.573  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
,09-07 09:43:05.579   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:43:05.579   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:43:05.579   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:43:05.672  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:43:05.672  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:43:05.673  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:43:05.673  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:43:05.675  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:43:05.728   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:43:05.741  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
09-07 09:43:05.742  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:43:05.742  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
,09-07 09:43:05.744  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:43:05.744  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:43:05.745  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:43:05.745  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:43:05.745  1804  1973 D LEDHandler: Battery Temp: 274, mChargingStatus=5, mChargingStop=false
09-07 09:43:05.747  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:43:05.748  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 09:43:05.752   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:43:05.752   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:43:05.753   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:43:05.784  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:43:05.788  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:43:05.788  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:43:05.789  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:43:05.789  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:43:05.789  1804  1973 D LEDHandler: Battery Temp: 274, mChargingStatus=5, mChargingStop=false
09-07 09:43:05.791  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
09-07 09:43:05.791  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:43:05.791  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
09-07 09:43:05.793  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:43:05.797   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:43:05.797   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:43:05.800   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:43:07.485   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:43:07.488  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:43:07.488  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:43:07.488  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:43:07.488  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:43:07.488  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:43:07.531  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 274
09-07 09:43:07.531  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:43:07.531  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 274
,09-07 09:43:07.534  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:43:07.534  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:43:07.536  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:43:07.536  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:43:07.536  1804  1973 D LEDHandler: Battery Temp: 274, mChargingStatus=5, mChargingStop=false
09-07 09:43:07.538  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 09:43:07.540  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:43:07.544   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:43:07.544   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:43:07.546   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:43:09.929   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:43:11.276   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:43:11.276   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:43:11.276   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 640116528705; DSPS: 21073846; Offset : -3017824580
,09-07 09:43:14.325  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,09-07 09:43:14.327  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:43:14.327  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:43:14.327  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:43:14.336  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:43:14.337   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:43:14.401  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 273
,09-07 09:43:14.404  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:43:14.404  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 273
09-07 09:43:14.406  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:43:14.407  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:43:14.409  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:43:14.409  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:43:14.409  1804  1973 D LEDHandler: Battery Temp: 273, mChargingStatus=5, mChargingStop=false
09-07 09:43:14.412  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:43:14.414  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:43:14.455   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:43:14.455   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:43:14.457   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:43:14.697   852   880 I art     : Explicit concurrent mark sweep GC freed 46618(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 4.390ms total 269.486ms
,09-07 09:43:14.935   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:43:19.941   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:43:24.948   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:43:29.956   292   347 I ThermalEngine: Sensor:pa_therm0:28000 mC
,09-07 09:43:31.279   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:43:31.279   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:43:31.279   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 660118829161; DSPS: 21729282; Offset : -3017844996
,09-07 09:43:34.962   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:43:39.703  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:43:39.704  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:43:39.704  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:43:39.704  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:43:39.706  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:43:39.716   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:43:39.757  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:43:39.759  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 272
09-07 09:43:39.760  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:43:39.760  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:43:39.761  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:43:39.761  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:43:39.761  1804  1973 D LEDHandler: Battery Temp: 272, mChargingStatus=5, mChargingStop=false
09-07 09:43:39.763  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:43:39.763  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 272
09-07 09:43:39.765  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:43:39.768   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:43:39.768   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:43:39.771   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:43:39.969   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:43:44.975   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:43:49.981   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:43:51.281   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:43:51.281   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:43:51.281   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 680121100946; DSPS: 22384716; Offset : -3017829506
,09-07 09:43:54.987   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:43:59.993   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:44:00.055  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:44:00.055  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:44:00.055  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:44:00.059  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:44:00.059  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:44:00.060  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:44:00.060  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:44:04.999   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:44:10.006   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:44:11.283   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:44:11.283   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:44:11.283   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 700123391832; DSPS: 23040151; Offset : -3017827465
,09-07 09:44:15.012   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:44:20.018   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:44:25.024   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:44:30.030   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:44:31.285   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:44:31.285   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:44:31.286   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 720125674296; DSPS: 23695582; Offset : -3017711750
,09-07 09:44:35.036   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:44:39.863  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:44:39.863  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:44:39.863  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:44:39.863  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:44:39.866  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:44:39.876   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:44:39.916  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:44:39.919  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 271
09-07 09:44:39.919  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:44:39.920  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:44:39.920  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:44:39.920  1804  1973 D LEDHandler: Battery Temp: 271, mChargingStatus=5, mChargingStop=false
09-07 09:44:39.921  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:44:39.922  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:44:39.923  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 271
09-07 09:44:39.924  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:44:39.928   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:44:39.928   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:44:39.931   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:44:40.042   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:44:45.048   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:44:46.288   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:44:46.288   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:44:46.288   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 735127883100; DSPS: 24187178; Offset : -3017822151
,09-07 09:44:47.003   852  1286 D PowerManagerServiceEx: acquireWakeLockInternal: lock=427605554, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=852
,09-07 09:44:47.005   852  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{e13f884 type 2 when 735830 android} when 735830
09-07 09:44:47.044   852   852 D PowerManagerServiceEx: releaseWakeLockInternal: lock=427605554 [*alarm*], flags=0x0
,09-07 09:44:47.635   852   986 I NotificationManager: android: cancelAsUser(-1548111331) by android
,09-07 09:44:47.751   852   986 I NotificationManager: android: cancelAsUser(2145784878) by android
09-07 09:44:47.764  6539  6539 I NotificationManager: com.google.android.apps.plus: cancel(10436) by com.google.android.apps.plus
,09-07 09:44:50.054   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:44:55.060   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:45:00.046  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:45:00.046  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:45:00.046  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:45:00.050  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:45:00.051  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:45:00.051  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:45:00.052  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:45:00.066   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:45:05.072   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:45:06.290   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:45:06.291   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:45:06.291   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 755130769622; DSPS: 24842633; Offset : -3017834590
,09-07 09:45:10.078   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:45:15.084   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:45:17.268   852  1286 D PowerManagerServiceEx: acquireWakeLockInternal: lock=427605554, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=852
,09-07 09:45:17.272   852  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{78401a1 type 2 when 766095 android} when 766095
09-07 09:45:17.484   852   852 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.widget.DigitalAppWidgetProvider: pid=7011 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,09-07 09:45:17.683  7011  7011 I DigitalAppWidgetProvider: onReceive: com.android.deskclock.ON_QUARTER_HOUR
,09-07 09:45:17.691  7011  7011 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@10cd92bd
09-07 09:45:17.692   852   852 D PowerManagerServiceEx: releaseWakeLockInternal: lock=427605554 [*alarm*], flags=0x0
09-07 09:45:20.090   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:45:21.293   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:45:21.293   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:45:21.293   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 770132951926; DSPS: 25334224; Offset : -3017819373
,09-07 09:45:25.096   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:45:30.102   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:45:35.108   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:45:38.796   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:45:38.796   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:45:38.796   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 787636427718; DSPS: 25907777; Offset : -3017791989
,09-07 09:45:40.023  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:45:40.023  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:45:40.023  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:45:40.024  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:45:40.026  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:45:40.036   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:45:40.076  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:45:40.079  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 270
09-07 09:45:40.080  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:45:40.081  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:45:40.082  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:45:40.083  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:45:40.083  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:45:40.083  1804  1973 D LEDHandler: Battery Temp: 270, mChargingStatus=5, mChargingStop=false
09-07 09:45:40.083  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 270
09-07 09:45:40.086  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:45:40.089   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:45:40.089   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:45:40.092   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:45:40.113   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:45:45.118   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:45:50.124   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:45:55.130   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:45:58.798   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:45:58.798   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:45:58.798   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 807638347201; DSPS: 26563201; Offset : -3017827689
,09-07 09:46:00.054  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:46:00.054  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:46:00.054  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:46:00.058  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:46:00.058  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:46:00.059  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:46:00.060  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:46:00.137   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:46:05.143   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:46:10.150   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:46:13.802   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:46:13.803   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:46:13.803   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 822642764692; DSPS: 27054871; Offset : -3017985856
,09-07 09:46:15.156   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:46:20.161   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:46:25.168   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:46:28.807   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:46:28.807   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:46:28.807   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 837647313834; DSPS: 27546534; Offset : -3017800700
,09-07 09:46:30.174   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:46:35.179   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:46:40.183  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:46:40.183  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:46:40.183  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:46:40.183  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:46:40.185   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
09-07 09:46:40.186  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:46:40.196   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:46:40.236  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:46:40.239  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 269
09-07 09:46:40.240  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:46:40.240  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:46:40.241  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:46:40.241  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:46:40.241  1804  1973 D LEDHandler: Battery Temp: 269, mChargingStatus=5, mChargingStop=false
09-07 09:46:40.243  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:46:40.243  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 269
09-07 09:46:40.245  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:46:40.248   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:46:40.248   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:46:40.251   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:46:45.191   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:46:47.561   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:46:47.562   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:46:47.562   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 856401725577; DSPS: 28161086; Offset : -3018027680
,09-07 09:46:50.196   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:46:55.203   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:47:00.054  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:47:00.054  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:47:00.054  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:47:00.058  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:47:00.058  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:47:00.058  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:47:00.059  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:47:00.209   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:47:01.632   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:47:01.632   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:47:01.633   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 870472671283; DSPS: 28622157; Offset : -3017852187
,09-07 09:47:05.215   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:47:10.220   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:47:15.226   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:47:16.635   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:47:16.635   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:47:16.635   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 885475128583; DSPS: 29113756; Offset : -3017805750
,09-07 09:47:20.232   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:47:25.238   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:47:30.244   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:47:35.249   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:47:36.637   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:47:36.637   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:47:36.637   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 905477181122; DSPS: 29769184; Offset : -3017828406
,09-07 09:47:40.255   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:47:40.343  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:47:40.343  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:47:40.343  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:47:40.343  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:47:40.353  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:47:40.356   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:47:40.396  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:47:40.399  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:47:40.399  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:47:40.400  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:47:40.400  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:47:40.400  1804  1973 D LEDHandler: Battery Temp: 268, mChargingStatus=5, mChargingStop=false
09-07 09:47:40.402  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 268
09-07 09:47:40.402  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:47:40.402  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 268
09-07 09:47:40.404  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:47:40.408   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:47:40.408   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:47:40.411   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:47:45.261   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:47:50.267   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:47:55.272   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:47:56.639   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:47:56.639   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:47:56.639   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 925479561841; DSPS: 30424614; Offset : -3017584440
,09-07 09:48:00.053  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:48:00.053  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:48:00.053  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:48:00.057  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:48:00.057  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:48:00.058  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:48:00.059  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:48:00.279   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:48:05.285   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:48:09.772   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:48:09.772   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:48:09.772   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 938611976607; DSPS: 30854939; Offset : -3017645985
,09-07 09:48:10.291   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:48:15.297   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:48:17.113   852  1286 D PowerManagerServiceEx: acquireWakeLockInternal: lock=427605554, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=852
,09-07 09:48:17.119   852  1286 V AlarmManager: ELAPSED_WAKEUP set : Alarm{f39efc6 type 2 when 945941 com.android.bluetooth} when 945941
09-07 09:48:17.250   852   852 D PowerManagerServiceEx: releaseWakeLockInternal: lock=427605554 [*alarm*], flags=0x0
,09-07 09:48:17.287  2027  3513 W bt-smp  : Key(LSB ~ MSB) = e4 45 40 3d 2d fa da d3 91 04 60 2d 27 f0 c0 0e 
09-07 09:48:17.287  2027  3513 W bt-smp  : Plain text(LSB ~ MSB) = ec c8 56 00 00 00 00 00 00 00 00 00 00 00 00 00 
09-07 09:48:17.287  2027  3513 W bt-smp  : Encrypted text(LSB ~ MSB) = 64 00 15 fd 55 ee bb 9a b9 07 1c 50 da e1 a5 46 
09-07 09:48:17.287  2027  3513 W bt-btm  : Stopping oneshot timer
,09-07 09:48:20.301   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:48:25.307   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:48:30.314   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:48:32.279   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:48:32.279   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:48:32.279   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 961119335563; DSPS: 31592457; Offset : -3017550238
,09-07 09:48:35.320   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:48:40.326   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:48:40.503  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
,09-07 09:48:40.505  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:48:40.505  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:48:40.505  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
09-07 09:48:40.506  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:48:40.516   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:48:40.557  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:48:40.560  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:48:40.560  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:48:40.561  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:48:40.561  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:48:40.561  1804  1973 D LEDHandler: Battery Temp: 266, mChargingStatus=5, mChargingStop=false
09-07 09:48:40.562  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 266
09-07 09:48:40.563  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:48:40.563  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 266
09-07 09:48:40.565  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:48:40.568   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:48:40.568   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:48:40.571   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:48:45.333   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:48:47.284   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:48:47.284   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:48:47.284   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 976123963921; DSPS: 32084135; Offset : -3017743710
,09-07 09:48:50.349   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:48:55.355   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:49:00.054  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:49:00.054  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:49:00.054  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:49:00.058  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:49:00.058  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:49:00.058  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:49:00.059  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:49:00.361   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:49:00.416   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:49:00.416   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:49:00.417   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 989256659113; DSPS: 32514469; Offset : -3017799878
,09-07 09:49:05.367   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:49:10.374   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:49:14.800   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:49:14.800   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:49:14.800   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1003639580928; DSPS: 32985767; Offset : -3017751313
,09-07 09:49:15.380   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:49:20.386   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:49:25.392   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:49:28.871   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:49:28.871   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:49:28.872   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1017711698527; DSPS: 33446885; Offset : -3017838563
,09-07 09:49:30.398   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:49:35.404   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:49:40.411   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:49:40.663  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:49:40.663  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:49:40.663  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:49:40.664  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:49:40.666  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:49:40.676   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:49:40.716  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:49:40.719  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 265
09-07 09:49:40.719  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:49:40.719  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 265
09-07 09:49:40.720  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:49:40.720  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:49:40.721  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:49:40.721  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:49:40.721  1804  1973 D LEDHandler: Battery Temp: 265, mChargingStatus=5, mChargingStop=false
09-07 09:49:40.724  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:49:40.728   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:49:40.728   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:49:40.731   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:49:45.417   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:49:48.874   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:49:48.874   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:49:48.874   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1037713917970; DSPS: 34102316; Offset : -3017785895
,09-07 09:49:50.423   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:49:55.429   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:50:00.053  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:50:00.053  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:50:00.053  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:50:00.057  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:50:00.057  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:50:00.058  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:50:00.058  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:50:00.435   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:50:05.442   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:50:08.876   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:50:08.876   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:50:08.876   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1057716230682; DSPS: 34757759; Offset : -3018008173
,09-07 09:50:10.448   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:50:15.454   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:50:20.461   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:50:25.467   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:50:30.473   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:50:31.380   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:50:31.381   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:50:31.381   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1080220725052; DSPS: 35495183; Offset : -3017908307
,09-07 09:50:35.479   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:50:40.485   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:50:40.823  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:50:40.823  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:50:40.824  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:50:40.824  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:50:40.826  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:50:40.836   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:50:45.491   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:50:50.497   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:50:51.383   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:50:51.383   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:50:51.383   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1100222985317; DSPS: 36150613; Offset : -3017782321
,09-07 09:50:55.503   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:51:00.053  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:51:00.053  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:51:00.053  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:51:00.056  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:51:00.056  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:51:00.057  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:51:00.058  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:51:00.509   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:51:05.515   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:51:10.521   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:51:11.385   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:51:11.385   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:51:11.385   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1120225282836; DSPS: 36806047; Offset : -3017743180
,09-07 09:51:15.528   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:51:20.534   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:51:25.540   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:51:26.387   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:51:26.387   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:51:26.387   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1135227228105; DSPS: 37297643; Offset : -3018119147
,09-07 09:51:30.546   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:51:35.553   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:51:40.559   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:51:40.983  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:51:40.983  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:51:40.983  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:51:40.983  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:51:40.993  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:51:40.996   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:51:41.033  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:51:41.036  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 264
09-07 09:51:41.036  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:51:41.036  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:51:41.038  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:51:41.038  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:51:41.038  1804  1973 D LEDHandler: Battery Temp: 264, mChargingStatus=5, mChargingStop=false
09-07 09:51:41.039  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:51:41.039  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 264
09-07 09:51:41.042  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:51:41.045   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:51:41.045   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:51:41.048   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:51:41.391   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:51:41.391   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:51:41.392   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1150231692471; DSPS: 37789299; Offset : -3017803194
,09-07 09:51:45.565   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:51:50.571   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:51:55.578   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:51:56.398   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:51:56.398   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:51:56.398   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1165238572968; DSPS: 38281049; Offset : -3017941661
,09-07 09:52:00.053  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:52:00.053  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:52:00.053  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:52:00.057  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:52:00.057  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:52:00.058  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:52:00.058  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:52:00.584   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:52:05.590   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:52:09.530   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:52:09.531   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:52:09.531   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1178370744787; DSPS: 38711353; Offset : -3017605754
,09-07 09:52:10.596   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:52:15.603   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:52:20.609   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:52:25.617   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:52:30.624   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:52:31.103   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:52:31.103   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:52:31.103   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1199942891358; DSPS: 39418237; Offset : -3017847009
,09-07 09:52:35.630   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:52:40.636   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:52:41.143  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:52:41.143  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:52:41.143  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:52:41.143  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:52:41.153  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:52:41.155   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:52:41.195  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:52:41.198  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 263
09-07 09:52:41.198  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:52:41.199  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:52:41.200  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:52:41.200  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:52:41.201  1804  1973 D LEDHandler: Battery Temp: 263, mChargingStatus=5, mChargingStop=false
09-07 09:52:41.202  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:52:41.202  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 263
09-07 09:52:41.204  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:52:41.207   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:52:41.207   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:52:41.210   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:52:45.642   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:52:50.648   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:52:51.104   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:52:51.104   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:52:51.104   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1219944451527; DSPS: 40073652; Offset : -3017965566
,09-07 09:52:55.376   852   986 I UsageStatsService: User[0] Flushing usage stats to disk
,09-07 09:52:55.654   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:53:00.053  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:53:00.053  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:53:00.053  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:53:00.057  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:53:00.057  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:53:00.058  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:53:00.058  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:53:00.660   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:53:05.667   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:53:10.673   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:53:13.609   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:53:13.609   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:53:13.609   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1242449164488; DSPS: 40811080; Offset : -3017768816
,09-07 09:53:15.679   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:53:20.685   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:53:25.691   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:53:30.697   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:53:33.612   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:53:33.612   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:53:33.612   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1262451825614; DSPS: 41466528; Offset : -3017793289
,09-07 09:53:35.703   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:53:40.710   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:53:41.303  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:53:41.303  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:53:41.303  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:53:41.303  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:53:41.305  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:53:41.316   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:53:41.356  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:53:41.359  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 263
09-07 09:53:41.359  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:53:41.360  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:53:41.360  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:53:41.360  1804  1973 D LEDHandler: Battery Temp: 263, mChargingStatus=5, mChargingStop=false
09-07 09:53:41.361  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:53:41.362  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:53:41.362  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 263
09-07 09:53:41.364  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:53:41.368   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:53:41.368   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:53:41.371   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:53:45.716   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:53:50.722   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:53:53.614   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:53:53.614   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:53:53.614   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1282454213020; DSPS: 42121965; Offset : -3017755790
,09-07 09:53:55.728   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:54:00.052  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:54:00.052  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:54:00.052  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:54:00.056  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:54:00.056  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:54:00.057  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:54:00.057  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:54:00.734   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:54:05.740   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:54:06.890  6151  6195 I PlayCommon: [742] com.google.android.play.a.l.e(787): Preparing logs for uploading
09-07 09:54:06.890  6151  6195 I PlayCommon: [742] com.google.android.play.a.l.e(789): No file ready to send
,09-07 09:54:10.746   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:54:13.616   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:54:13.616   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:54:13.616   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1302456505575; DSPS: 42777403; Offset : -3017843605
,09-07 09:54:15.753   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:54:20.759   292   347 I ThermalEngine: Sensor:pa_therm0:27000 mC
,09-07 09:54:25.765   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:54:30.771   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:54:33.619   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:54:33.619   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:54:33.619   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1322458895974; DSPS: 43432839; Offset : -3017772516
,09-07 09:54:35.776   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:54:40.783   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:54:41.463  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:54:41.463  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:54:41.463  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:54:41.463  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:54:41.466  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:54:41.476   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:54:41.516  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:54:41.519  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 262
09-07 09:54:41.520  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:54:41.520  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:54:41.520  1804  1973 D LEDHandler: Battery Temp: 262, mChargingStatus=5, mChargingStop=false
09-07 09:54:41.521  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:54:41.521  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:54:41.522  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:54:41.523  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 262
09-07 09:54:41.525  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:54:41.528   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:54:41.528   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:54:41.531   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:54:45.789   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:54:50.795   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:54:53.621   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:54:53.621   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:54:53.622   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1342461692291; DSPS: 44088292; Offset : -3017814282
,09-07 09:54:55.801   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:55:00.052  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:55:00.052  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:55:00.052  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:55:00.056  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:55:00.056  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:55:00.057  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:55:00.057  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:55:00.807   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:55:01.914   852  2150 I ActivityManager: Process com.android.contacts (pid 6497) has died
,09-07 09:55:05.814   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:55:10.820   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:55:13.624   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:55:13.624   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:55:13.624   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1362463834494; DSPS: 44743723; Offset : -3017839035
,09-07 09:55:15.826   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:55:20.832   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:55:25.838   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:55:30.844   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:55:33.626   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:55:33.626   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:55:33.626   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1382465931349; DSPS: 45399153; Offset : -3017878384
,09-07 09:55:35.850   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:55:40.857   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:55:41.623  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:55:41.623  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:55:41.624  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:55:41.624  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:55:41.626  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:55:41.636   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:55:41.676  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:55:41.679  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 262
09-07 09:55:41.679  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:55:41.680  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:55:41.680  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:55:41.681  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:55:41.681  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:55:41.681  1804  1973 D LEDHandler: Battery Temp: 262, mChargingStatus=5, mChargingStop=false
09-07 09:55:41.682  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 262
09-07 09:55:41.685  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:55:41.688   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:55:41.688   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:55:41.691   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:55:45.863   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:55:50.869   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:55:53.628   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:55:53.628   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:55:53.628   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1402468077215; DSPS: 46054583; Offset : -3017868670
,09-07 09:55:55.875   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:56:00.052  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:56:00.052  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:56:00.053  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:56:00.056  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:56:00.057  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:56:00.057  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:56:00.058  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:56:00.881   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:56:05.888   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:56:10.894   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:56:13.630   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:56:13.630   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:56:13.630   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1422470629216; DSPS: 46710025; Offset : -3017818800
,09-07 09:56:14.325  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:56:14.325  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:56:14.326  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:56:14.326  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:56:14.336  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:56:14.338   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:56:14.403  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:56:14.406  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 261
09-07 09:56:14.406  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:56:14.406  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:56:14.408  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:56:14.408  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:56:14.408  1804  1973 D LEDHandler: Battery Temp: 261, mChargingStatus=5, mChargingStop=false
09-07 09:56:14.409  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:56:14.409  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 261
09-07 09:56:14.411  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:56:14.415   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:56:14.415   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:56:14.418   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:56:14.458  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 262
09-07 09:56:14.459  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:56:14.459  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 262
,09-07 09:56:14.461  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:56:14.462  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:56:14.463  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:56:14.463  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:56:14.463  1804  1973 D LEDHandler: Battery Temp: 262, mChargingStatus=5, mChargingStop=false
09-07 09:56:14.549   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:56:14.549   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:56:14.554   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:56:14.554  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-07 09:56:14.557  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:56:15.900   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:56:20.906   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:56:25.913   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:56:30.919   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:56:33.632   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:56:33.633   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:56:33.633   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1442472756059; DSPS: 47365456; Offset : -3017859120
,09-07 09:56:35.925   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:56:40.931   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:56:41.783  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:56:41.783  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:56:41.784  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:56:41.784  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:56:41.786  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:56:41.796   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:56:41.836  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:56:41.839  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 261
09-07 09:56:41.840  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:56:41.840  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:56:41.840  1804  1973 D LEDHandler: Battery Temp: 261, mChargingStatus=5, mChargingStop=false
09-07 09:56:41.841  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:56:41.841  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:56:41.843  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:56:41.843  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 261
09-07 09:56:41.845  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:56:41.848   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:56:41.848   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:56:41.851   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:56:45.938   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:56:50.944   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:56:53.635   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:56:53.635   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:56:53.635   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1462475083129; DSPS: 48020890; Offset : -3017790300
,09-07 09:56:55.950   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:57:00.052  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:57:00.052  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:57:00.052  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:57:00.056  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:57:00.056  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:57:00.057  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:57:00.057  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:57:00.956   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:57:05.962   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:57:10.968   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:57:13.637   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:57:13.637   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:57:13.637   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1482477350169; DSPS: 48676326; Offset : -3017842516
,09-07 09:57:15.975   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:57:20.981   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:57:25.987   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:57:30.993   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:57:33.639   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:57:33.639   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:57:33.640   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1502479643531; DSPS: 49331760; Offset : -3017807481
,09-07 09:57:35.999   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:57:41.006   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:57:41.943  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:57:41.943  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:57:41.944  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:57:41.944  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:57:41.946  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:57:41.965   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:57:46.019   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:57:51.025   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:57:53.642   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:57:53.642   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:57:53.642   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1522481838317; DSPS: 49987193; Offset : -3017840478
,09-07 09:57:56.031   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:58:00.052  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:58:00.052  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:58:00.052  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:58:00.056  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:58:00.056  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:58:00.057  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:58:00.057  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:58:01.037   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:58:06.043   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:58:11.050   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:58:13.644   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:58:13.644   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:58:13.644   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1542484226227; DSPS: 50642630; Offset : -3017802500
,09-07 09:58:16.056   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:58:21.062   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:58:26.068   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:58:31.074   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:58:33.646   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:58:33.646   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:58:33.646   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1562486568485; DSPS: 51298067; Offset : -3017810095
,09-07 09:58:36.081   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:58:41.087   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:58:42.103  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-07 09:58:42.103  1373  1373 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-07 09:58:42.103  1373  1373 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-07 09:58:42.104  1373  1373 I [SystemUI]LGPowerUI: On Skip Timer : true
,09-07 09:58:42.106  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-07 09:58:42.116   486   486 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-07 09:58:42.157  2027  3463 D HeadsetStateMachine: Disconnected process message: 10, size: 0
,09-07 09:58:42.160  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-07 09:58:42.160  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-07 09:58:42.161  1804  1973 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-07 09:58:42.161  1804  1973 D LEDHandler: Battery Level Remaining: 100%
09-07 09:58:42.161  1804  1973 D LEDHandler: Battery Temp: 260, mChargingStatus=5, mChargingStop=false
09-07 09:58:42.162  1373  1373 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 260
09-07 09:58:42.163  1373  1373 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:58:42.163  1373  1373 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 260
09-07 09:58:42.165  1373  1373 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-07 09:58:42.169   852   852 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-07 09:58:42.169   852   852 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,09-07 09:58:42.172   852  1315 D WifiController: battery changed pluggedType: 2
09-07 09:58:46.093   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:58:51.099   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:58:53.649   852   995 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-07 09:58:53.649   852   995 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-07 09:58:53.649   852   995 D sensors_hal_Time: tsOffsetIs: Apps: 1582488863798; DSPS: 51953503; Offset : -3017834092
,09-07 09:58:56.105   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:59:00.051  1373  1373 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-07 09:59:00.051  1373  1373 I KeyguardUpdateMonitor: called onTimeUpdated()
09-07 09:59:00.051  1373  1373 I [SystemUI]Clock: called onTimeUpdated()
,09-07 09:59:00.055  1373  1373 I LgeClockWidgetControlView: called onTimeUpdated()
09-07 09:59:00.055  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:59:00.056  1373  1373 I [SystemUI]DateView: called onTimeUpdated()
09-07 09:59:00.057  1373  1373 D KeyguardUpdateMonitor: handleTimeUpdate
09-07 09:59:01.111   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:59:06.117   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
,09-07 09:59:06.992  6151  6195 I PlayCommon: [742] com.google.android.play.a.l.e(787): Preparing logs for uploading
09-07 09:59:06.993  6151  6195 I PlayCommon: [742] com.google.android.play.a.l.e(789): No file ready to send
,TIME-OUT KILL (timeout was 1400000ms),09-07 09:59:10.073  7199  7199 D AndroidRuntime: 
09-07 09:59:10.073  7199  7199 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-07 09:59:10.084  7199  7199 D AndroidRuntime: CheckJNI is OFF
09-07 09:59:10.428  7199  7199 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
09-07 09:59:10.476   852   988 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
09-07 09:59:10.478   852   988 I ActivityManager: Killing 6779:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
09-07 09:59:10.525   852  1350 I WindowState: WIN DEATH: Window{1b92262e u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 09:59:10.535   852  1350 D InputDispatcher: Focus left window: Window{1b92262e u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 09:59:10.535   852  1350 D InputDispatcher: Window went away: Window{1b92262e u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-07 09:59:10.576   852  1062 W PackageSettings: Skipping PackageSetting{29f240cb com.example.hello/10317} due to missing metadata
09-07 09:59:10.588   852   988 I ActivityManager:   Force finishing activity ActivityRecord{39e2400b u0 com.test.thalitest/.MainActivity t259}
09-07 09:59:10.633   852  1573 W ActivityManager: Spurious death for ProcessRecord{1bdd9b87 6779:com.test.thalitest/u0a30}, curProc for 6779: null
09-07 09:59:10.636   852  1062 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
09-07 09:59:10.638   852  1062 I ActivityManager:   Force finishing activity ActivityRecord{39e2400b u0 com.test.thalitest/.MainActivity t259 f}
09-07 09:59:10.640   852  1062 W ActivityManager: Duplicate finish request for ActivityRecord{39e2400b u0 com.test.thalitest/.MainActivity t259 f}
09-07 09:59:10.709  1940  1940 I art     : Explicit concurrent mark sweep GC freed 818(45KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/20MB, paused 1.905ms total 66.351ms
09-07 09:59:10.715  1373  1373 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-07 09:59:10.718  1879  1879 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
09-07 09:59:10.736  1840  1840 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
09-07 09:59:10.739  3634  3634 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
09-07 09:59:10.740  3634  3634 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-07 09:59:10.740  3634  3634 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-07 09:59:10.740  3634  3634 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
09-07 09:59:10.740  3634  3634 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-07 09:59:10.740  3634  3634 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-07 09:59:10.740  3634  3634 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-07 09:59:10.740  3634  3634 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
09-07 09:59:10.741  1734  2465 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-07 09:59:10.741  3634  3634 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-07 09:59:10.741  3634  3634 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-07 09:59:10.741  3634  3634 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
09-07 09:59:10.741  3634  3634 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
09-07 09:59:10.746   852  1289 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-07 09:59:10.781  1879  1879 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
09-07 09:59:10.790   852   988 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7232 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
09-07 09:59:10.830  3400  3400 I art     : Explicit concurrent mark sweep GC freed 4511(243KB) AllocSpace objects, 2(32KB) LOS objects, 24% free, 16MB/21MB, paused 968us total 185.373ms
09-07 09:59:10.848  1373  1373 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
09-07 09:59:10.852  1373  1506 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-07 09:59:10.852  1373  1506 D KeyguardModel: createShortcutInfo...
09-07 09:59:10.855  1373  1506 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-07 09:59:10.855  1373  1506 D KeyguardModel: createShortcutInfo...
09-07 09:59:10.857  1373  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 09:59:10.862  1373  1506 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-07 09:59:10.864  1373  1506 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-07 09:59:10.864  1373  1506 D KeyguardModel: createShortcutInfo...
09-07 09:59:10.866  1373  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 09:59:10.866  1373  1506 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-07 09:59:10.868  1373  1506 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-07 09:59:10.868  1373  1506 D KeyguardModel: createShortcutInfo...
09-07 09:59:10.870  1373  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 09:59:10.870  1373  1506 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-07 09:59:10.873  1373  1506 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-07 09:59:10.874  1373  1506 D KeyguardModel: createShortcutInfo...
09-07 09:59:10.889  1879  1879 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
09-07 09:59:10.891  1879  1879 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
09-07 09:59:10.891  1879  1879 I Activity: Activity.onPostResume() called 
09-07 09:59:10.904  1879  1879 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
09-07 09:59:10.935  1373  1373 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-07 09:59:10.936  1373  1373 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
09-07 09:59:10.949  1373  1373 D KeyguardModel: handleShortcutListChanged...
09-07 09:59:10.952  1879  7250 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
09-07 09:59:10.955   852  1041 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
09-07 09:59:10.955   852  1041 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
09-07 09:59:10.956  1373  1373 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
09-07 09:59:10.956  1373  1373 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
09-07 09:59:10.956  1373  1373 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
09-07 09:59:10.956  1373  1373 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
09-07 09:59:10.960  1373  1506 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-07 09:59:10.960  1373  1506 D KeyguardModel: createShortcutInfo...
09-07 09:59:10.960   852  2150 D InputDispatcher: Focus entered window: Window{2cb85150 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
09-07 09:59:10.961   852  1041 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
09-07 09:59:10.961   852  1041 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
09-07 09:59:10.961   852  1041 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-07 09:59:10.962   852  1041 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@2e5fcd98,  pkg=WindowManager.LayoutParams
09-07 09:59:10.962   852  1041 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
09-07 09:59:10.964   852   852 I art     : Explicit concurrent mark sweep GC freed 39196(2MB) AllocSpace objects, 10(160KB) LOS objects, 33% free, 23MB/35MB, paused 5.843ms total 275.706ms
09-07 09:59:10.965   852  1062 I art     : WaitForGcToComplete blocked for 264.049ms for cause Explicit
09-07 09:59:10.971  1373  1506 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-07 09:59:10.971  1373  1506 D KeyguardModel: createShortcutInfo...
09-07 09:59:10.975  7232  7232 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 09:59:10.975  7232  7232 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-07 09:59:10.976  7232  7232 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-07 09:59:10.981  1879  1879 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-07 09:59:10.981  1879  1879 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-07 09:59:10.982  1879  1879 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
09-07 09:59:10.992  1879  1879 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
09-07 09:59:10.996  1879  1879 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
09-07 09:59:10.997  1879  1879 I PhoneWindow: [setNavigationBarColor] color=0x 0
09-07 09:59:11.001   852  6159 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
09-07 09:59:11.002  1373  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 09:59:11.002  1373  1506 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-07 09:59:11.003   852  6159 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6779 uid 10030
09-07 09:59:11.004  1373  1506 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-07 09:59:11.004  1373  1506 D KeyguardModel: createShortcutInfo...
09-07 09:59:11.006  1373  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 09:59:11.006  1373  1506 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-07 09:59:11.009  1373  1506 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-07 09:59:11.009  1373  1506 D KeyguardModel: createShortcutInfo...
09-07 09:59:11.011  1373  1506 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-07 09:59:11.011  1373  1506 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-07 09:59:11.013  1373  1506 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-07 09:59:11.013  1373  1506 D KeyguardModel: createShortcutInfo...
09-07 09:59:11.023  1373  1373 D KeyguardModel: handleShortcutListChanged...
09-07 09:59:11.059  1879  1879 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
09-07 09:59:11.062   852   852 D administrator: Handling package changes for user 0
09-07 09:59:11.064  1627  1627 E b       : Unable to connect to the editor to retrieve text... will retry later
09-07 09:59:11.069  1879  1879 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2b2b1c9c time:1599909
09-07 09:59:11.091   852  1044 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{34155ca9 u0 com.lge.launcher2/.Launcher t258} time:1599931
09-07 09:59:11.118  1879  1879 I art     : Explicit concurrent mark sweep GC freed 4493(268KB) AllocSpace objects, 4(645KB) LOS objects, 40% free, 15MB/25MB, paused 1.392ms total 47.796ms
09-07 09:59:11.118  1879  1879 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
09-07 09:59:11.122   292   347 I ThermalEngine: Sensor:pa_therm0:26000 mC
09-07 09:59:11.204   852   852 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-07 09:59:11.204   852   852 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-07 09:59:11.209   852   852 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-07 09:59:11.214   852  1352 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
09-07 09:59:11.252   852   986 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-07 09:59:11.255  7232  7232 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
09-07 09:59:11.275  7232  7232 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
09-07 09:59:11.297   852   986 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
09-07 09:59:11.303   852  1062 I art     : Explicit concurrent mark sweep GC freed 9362(722KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 2.890ms total 333.606ms
09-07 09:59:11.338  1879  1879 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-07 09:59:11.380  7199  7199 D AndroidRuntime: Shutting down VM
09-07 09:59:11.396  1786  1786 D LCardEmulationManager: getHceAppCount hostAppNum : 0
09-07 09:59:11.396  1786  1786 D LCardEmulationManager: getDefaultRoute
09-07 09:59:11.510  7232  7232 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
09-07 09:59:11.540  6445  6445 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
09-07 09:59:11.592   852   882 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7256 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi
09-07 09:59:11.667   852  1062 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7278 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-07 09:59:11.767   852  2150 I ActivityManager: Killing 6472:com.android.gallery3d/u0a23 (adj 15): empty #11
09-07 09:59:11.792   852  1573 W libprocessgroup: failed to open /acct/uid_10023/pid_6472/cgroup.procs: No such file or directory

```
