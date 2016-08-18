#### Test 80807573fdd3b64_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-18 11:58:54.892   294   364 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-18 11:58:56.538  6716  6716 D AndroidRuntime: 
08-18 11:58:56.538  6716  6716 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-18 11:58:56.543  6716  6716 D AndroidRuntime: CheckJNI is OFF
08-18 11:58:56.927  6716  6716 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-18 11:58:56.944   990  1299 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-18 11:58:56.995   990  1299 D ActivityManager: setTaskToReturnTo : TaskRecord{148c2d6c #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-18 11:58:56.995   990  1299 D ActivityManager: setTaskToReturnTo : TaskRecord{148c2d6c #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-18 11:58:57.004   990  1299 D WindowStateEx: AppWindowTokenEx init.. 
08-18 11:58:57.054   990  1299 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6730 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-18 11:58:57.055   990  1299 D InputDispatcher: Focus left window: Window{efd203 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-18 11:58:57.056  6716  6716 D AndroidRuntime: Shutting down VM
08-18 11:58:57.072  1955  1955 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-18 11:58:57.104   990   990 V ActivityManager: Display changed displayId=0
08-18 11:58:57.106  1783  1783 D DSDPConnection: Display #0 changed.
08-18 11:58:57.244  6730  6730 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-18 11:58:57.355  6730  6730 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
08-18 11:58:57.410  6730  6730 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 6222-6224)
08-18 11:58:57.411  6730  6730 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-18 11:58:57.446  6730  6730 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {23a751d4}
08-18 11:58:57.447  6730  6730 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-18 11:58:57.447  6730  6730 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-18 11:58:57.460  6730  6730 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-18 11:58:57.461  6730  6730 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-18 11:58:57.462  6730  6730 E SysUtils: ApplicationContext is null in ApplicationStatus
08-18 11:58:57.488  6730  6730 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-18 11:58:57.493  6730  6730 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-18 11:58:57.493  6730  6730 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-18 11:58:57.494  6730  6730 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-18 11:58:57.494  6730  6730 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-18 11:58:57.494  6730  6730 I Adreno-EGL: Build Date: 03/02/15 Mon
08-18 11:58:57.494  6730  6730 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-18 11:58:57.494  6730  6730 I Adreno-EGL: Remote Branch: 
08-18 11:58:57.494  6730  6730 I Adreno-EGL: Local Patches: 
08-18 11:58:57.494  6730  6730 I Adreno-EGL: Reconstruct Branch: 
08-18 11:58:57.559   272  1593 V AudioPolicyService: registerClient() client 0xb40275c0, uid 10030
08-18 11:58:57.581   990  1058 D BluetoothManagerService: Message: 20
08-18 11:58:57.582   990  1058 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d89b670:true
08-18 11:58:57.585  2064  2083 D BluetoothAdapterService(182333042): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9472e58
08-18 11:58:57.632   990  1051 W ActivityManager: Activity pause timeout for ActivityRecord{30e6f35 u0 com.test.thalitest/.MainActivity t259}
08-18 11:58:57.771  6730  6730 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-18 11:58:57.793  6730  6730 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-18 11:58:57.802  6730  6730 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-18 11:58:57.806  6730  6730 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-18 11:58:57.806  6730  6730 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-18 11:58:57.823  6730  6730 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-18 11:58:57.833  6730  6730 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-18 11:58:57.833  6730  6730 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-18 11:58:57.887  6730  6730 I Activity: Activity.onPostResume() called 
08-18 11:58:57.896  6730  6778 D OpenGLRenderer: Render dirty regions requested: true
08-18 11:58:57.896  6730  6778 I OpenGLRenderer: Initialized EGL, version 1.4
08-18 11:58:57.905  6730  6778 D OpenGLRenderer: Enabling debug mode 0
08-18 11:58:57.921  6730  6730 D Atlas   : Validating map...
08-18 11:58:57.925   990  1954 D SplitWindow: check instance of lgWin Window{3e6f9ba0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-18 11:58:57.946  6730  6765 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-18 11:58:57.977   990  1057 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
,08-18 11:58:57.979   990  1057 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-18 11:58:57.979  1380  1380 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-18 11:58:57.980  1380  1380 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-18 11:58:57.980  1380  1380 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-18 11:58:57.980  1380  1380 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-18 11:58:57.981   990  1057 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-18 11:58:57.981   990  1057 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-18 11:58:57.981   990  1057 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-18 11:58:57.981   990  1057 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@32150c4b,  pkg=WindowManager.LayoutParams
08-18 11:58:57.981   990  1057 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-18 11:58:57.991   990  2002 D InputDispatcher: Focus entered window: Window{3e6f9ba0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-18 11:58:58.019   990  2090 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-18 11:58:58.040   990  1059 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +905ms (total +1s32ms)
,08-18 11:58:58.040   990  1059 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{30e6f35 u0 com.test.thalitest/.MainActivity t259} time:246854
08-18 11:58:58.048  6730  6730 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-18 11:58:58.053  6730  6730 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3496946e time:246867
,08-18 11:58:58.095  6730  6730 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-18 11:58:58.099  1630  1630 E b       : Unable to connect to the editor to retrieve text... will retry later
08-18 11:58:58.123  6730  6730 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-18 11:58:58.183  6730  6730 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6730
,08-18 11:58:58.591  6730  6730 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-18 11:58:58.601  1878  1878 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-18 11:58:58.602  1380  1380 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-18 11:58:58.602  1380  1380 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-18 11:58:58.602  1380  1380 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-18 11:58:58.602  1380  1380 I [SystemUI]LGPowerUI: On Skip Timer : true
08-18 11:58:58.603   495   495 D charger_monitor: init target 500000
,08-18 11:58:58.608   495   495 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-18 11:58:58.645  1380  1380 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 287
08-18 11:58:58.645  1380  1380 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-18 11:58:58.645  1380  1380 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 287
,08-18 11:58:58.647   990   990 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 11:58:58.647   990   990 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-18 11:58:58.647  1878  2053 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-18 11:58:58.647  1878  2053 D LEDHandler: Battery Level Remaining: 100%
08-18 11:58:58.647  1878  2053 D LEDHandler: Battery Temp: 287, mChargingStatus=5, mChargingStop=false
08-18 11:58:58.647  1917  1917 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-18 11:58:58.648  1917  1917 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-18 11:58:58.648   990  1322 D WifiController: battery changed pluggedType: 2
08-18 11:58:58.648  2064  3488 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-18 11:58:58.649  6402  6402 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-18 11:58:58.651  1380  1380 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-18 11:58:58.771  6730  6784 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1635609344
,08-18 11:58:58.791  6730  6784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-18 11:58:58.791  6730  6784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-18 11:58:58.791  6730  6784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-18 11:58:58.791  6730  6784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-18 11:58:58.791  6730  6784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-18 11:58:58.791  6730  6784 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@383dcdd2 added. We now have 1 listener(s)
08-18 11:58:58.800   990  1890 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 11:58:58.804  6730  6784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,08-18 11:58:58.806  6730  6784 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-18 11:58:58.807  6730  6784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-18 11:58:58.807  6730  6784 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-18 11:58:58.813  6730  6784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-18 11:58:58.813  6730  6784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-18 11:58:58.813  6730  6784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-18 11:58:58.813  6730  6784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-18 11:58:58.813  6730  6784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-18 11:58:58.813  6730  6784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-18 11:58:58.813  6730  6784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-18 11:58:58.813  6730  6784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-18 11:58:58.813  6730  6784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-18 11:58:58.813  6730  6784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-18 11:58:58.813  6730  6784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-18 11:58:58.813  6730  6784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-18 11:58:58.813  6730  6784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-18 11:58:58.813  6730  6784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-18 11:58:58.813  6730  6784 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d66e559 added. We now have 1 listener(s)
08-18 11:58:58.813  6730  6784 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-18 11:58:58.833  6730  6784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-18 11:58:58.833  6730  6784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-18 11:58:58.835  6730  6784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-18 11:58:58.836  6730  6784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-18 11:58:58.836  6730  6784 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-18 11:58:58.841  6730  6784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-18 11:58:58.841   990  1979 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-18 11:58:58.842  6730  6784 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-18 11:58:58.852  2064  2083 D BluetoothAdapterService(182333042): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@9472e58
,08-18 11:58:58.855  6730  6784 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-18 11:58:58.855  6730  6784 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-18 11:58:58.855  6730  6784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-18 11:58:58.855  6730  6784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-18 11:58:58.855  6730  6784 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-18 11:58:58.855  6730  6784 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-18 11:58:58.855  6730  6784 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-18 11:58:58.855  6730  6784 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-18 11:58:58.855  6730  6784 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-18 11:58:58.855  6730  6784 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-18 11:58:58.855  6730  6784 D io.jxcore.node.ConnectivityMonitor: start: OK
08-18 11:58:58.857  6730  6730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:58:58.860  6730  6730 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-18 11:58:58.861  6730  6784 I io.jxcore.node.LifeCycleMonitor: start: OK
08-18 11:58:58.898  6730  6730 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-18 11:58:58.999  6730  6749 I art     : CheckpointMarkThreadRoots callback created = 0xb0682060
,08-18 11:58:59.044  6730  6749 I art     : CheckpointMarkThreadRoots callback created = 0xb0682030
,08-18 11:58:59.896   294   364 I ThermalEngine: Sensor:pa_therm0:30000 mC
,08-18 11:59:00.038  1380  1380 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-18 11:59:00.038  1380  1380 I KeyguardUpdateMonitor: called onTimeUpdated()
08-18 11:59:00.038  1380  1380 I [SystemUI]Clock: called onTimeUpdated()
,08-18 11:59:00.040  1380  1380 I LgeClockWidgetControlView: called onTimeUpdated()
08-18 11:59:00.040  1380  1380 I [SystemUI]DateView: called onTimeUpdated()
08-18 11:59:00.041  1380  1380 I [SystemUI]DateView: called onTimeUpdated()
08-18 11:59:00.041  1380  1380 D KeyguardUpdateMonitor: handleTimeUpdate
08-18 11:59:00.073  6730  6795 W jxcore-log: Initializing JXcore engine
,08-18 11:59:00.074  6730  6795 W jxcore-log: JXcore engine is ready
08-18 11:59:00.177  6795  6795 W Thread-784: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[6342]" dev="sockfs" ino=6342 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-18 11:59:00.177  6795  6795 W Thread-784: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-18 11:59:00.177  6795  6795 W Thread-784: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[5746]" dev="sockfs" ino=5746 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-18 11:59:00.177  6795  6795 W Thread-784: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-18 11:59:00.177  6795  6795 W Thread-784: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-18 11:59:00.177  6795  6795 W Thread-784: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[31340]" dev="sockfs" ino=31340 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-18 11:59:00.213  6730  6795 W jxcore-log: Starting JXcore engine
,08-18 11:59:00.357  6730  6795 W jxcore-log: Platform android
08-18 11:59:00.357  6730  6795 W jxcore-log: 
08-18 11:59:00.357  6730  6795 W jxcore-log: Process ARCH arm
08-18 11:59:00.357  6730  6795 W jxcore-log: 
,08-18 11:59:00.715  6730  6795 I jxcore-log: JXcore Cordova bridge is ready!
08-18 11:59:00.715  6730  6795 I jxcore-log: 
08-18 11:59:00.715  6730  6795 W jxcore-log: JXcore engine is started

```
