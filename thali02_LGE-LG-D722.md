#### Test 8091062436177d0_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-11 09:07:21.785  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-11 09:07:21.785  1374  1374 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-11 09:07:21.785  1374  1374 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-11 09:07:21.785  1374  1374 I [SystemUI]LGPowerUI: On Skip Timer : true
--------- beginning of system
08-11 09:07:21.786  1804  1804 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-11 09:07:21.809   490   490 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
08-11 09:07:21.849  2038  3493 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-11 09:07:21.852  1374  1374 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
08-11 09:07:21.852  1840  1840 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-11 09:07:21.852  1840  1840 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-11 09:07:21.853  1804  1985 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-11 09:07:21.854  1804  1985 D LEDHandler: Battery Level Remaining: 100%
08-11 09:07:21.854  1804  1985 D LEDHandler: Battery Temp: 277, mChargingStatus=5, mChargingStop=false
08-11 09:07:21.855  1374  1374 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-11 09:07:21.855  1374  1374 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 277
08-11 09:07:21.857  1374  1374 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-11 09:07:21.860   842   842 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 09:07:21.861   842   842 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-11 09:07:21.863   842  1317 D WifiController: battery changed pluggedType: 2
08-11 09:07:22.536  6873  6873 D AndroidRuntime: 
08-11 09:07:22.536  6873  6873 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-11 09:07:22.547  6873  6873 D AndroidRuntime: CheckJNI is OFF
08-11 09:07:22.936  6873  6873 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-11 09:07:22.952   842  2139 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 09:07:22.991   842  2139 D ActivityManager: setTaskToReturnTo : TaskRecord{956fea1 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 09:07:22.992   842  2139 D ActivityManager: setTaskToReturnTo : TaskRecord{956fea1 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 09:07:22.998   842  2139 D WindowStateEx: AppWindowTokenEx init.. 
08-11 09:07:23.035   842  2139 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6893 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-11 09:07:23.037   842  2139 D InputDispatcher: Focus left window: Window{1339a028 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-11 09:07:23.038  6873  6873 D AndroidRuntime: Shutting down VM
08-11 09:07:23.044  1878  1878 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-11 09:07:23.072   842   842 V ActivityManager: Display changed displayId=0
08-11 09:07:23.076  1751  1751 D DSDPConnection: Display #0 changed.
08-11 09:07:23.161   842  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-11 09:07:23.161   842  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-11 09:07:23.161   842  1006 D sensors_hal_Time: tsOffsetIs: Apps: 188640921860; DSPS: 6279938; Offset : -3020821933
08-11 09:07:23.197  6893  6893 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-11 09:07:23.197   294   346 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 09:07:23.316  6893  6893 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,08-11 09:07:23.370  6893  6893 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 8844-8849)
08-11 09:07:23.370  6893  6893 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-11 09:07:23.423  6893  6893 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {33ac0858}
,08-11 09:07:23.424  6893  6893 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 09:07:23.424  6893  6893 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-11 09:07:23.438  6893  6893 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-11 09:07:23.439  6893  6893 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 09:07:23.441  6893  6893 E SysUtils: ApplicationContext is null in ApplicationStatus
08-11 09:07:23.466  6893  6893 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-11 09:07:23.471  6893  6893 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 09:07:23.471  6893  6893 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 09:07:23.472  6893  6893 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 09:07:23.472  6893  6893 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 09:07:23.472  6893  6893 I Adreno-EGL: Build Date: 03/02/15 Mon
08-11 09:07:23.472  6893  6893 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-11 09:07:23.472  6893  6893 I Adreno-EGL: Remote Branch: 
08-11 09:07:23.472  6893  6893 I Adreno-EGL: Local Patches: 
08-11 09:07:23.472  6893  6893 I Adreno-EGL: Reconstruct Branch: 
08-11 09:07:23.538   284  1361 V AudioPolicyService: registerClient() client 0xb39b15e0, uid 10030
,08-11 09:07:23.561   842   996 D BluetoothManagerService: Message: 20
,08-11 09:07:23.562   842   996 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@524b195:true
08-11 09:07:23.570  2038  3659 D BluetoothAdapterService(975205014): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@38b2dd9c
08-11 09:07:23.600   842   878 W ActivityManager: Activity pause timeout for ActivityRecord{d25a8c6 u0 com.test.thalitest/.MainActivity t259}
,08-11 09:07:23.744  6893  6893 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-11 09:07:23.760  6893  6893 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-11 09:07:23.767  6893  6893 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-11 09:07:23.771  6893  6893 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-11 09:07:23.771  6893  6893 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-11 09:07:23.792  6893  6893 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-11 09:07:23.801  6893  6893 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 09:07:23.801  6893  6893 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 09:07:23.867  6893  6893 I Activity: Activity.onPostResume() called 
,08-11 09:07:23.875  6893  6936 D OpenGLRenderer: Render dirty regions requested: true
08-11 09:07:23.875  6893  6936 I OpenGLRenderer: Initialized EGL, version 1.4
08-11 09:07:23.883  6893  6936 D OpenGLRenderer: Enabling debug mode 0
,08-11 09:07:23.902  6893  6893 D Atlas   : Validating map...
,08-11 09:07:23.909   842  2139 D SplitWindow: check instance of lgWin Window{18162a05 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 09:07:23.928  6893  6923 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-11 09:07:23.959   842   995 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
,08-11 09:07:23.961   842   995 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-11 09:07:23.962  1374  1374 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-11 09:07:23.962   842   995 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-11 09:07:23.962   842   995 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-11 09:07:23.962  1374  1374 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-11 09:07:23.962  1374  1374 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-11 09:07:23.962  1374  1374 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-11 09:07:23.962   842   995 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-11 09:07:23.962   842   995 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@355ceaa0,  pkg=WindowManager.LayoutParams
08-11 09:07:23.962   842   995 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-11 09:07:23.976   842  1896 D InputDispatcher: Focus entered window: Window{18162a05 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 09:07:24.003   842   998 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +906ms (total +1s2ms)
08-11 09:07:24.003   842   998 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{d25a8c6 u0 com.test.thalitest/.MainActivity t259} time:189482
,08-11 09:07:24.013   842  1846 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-11 09:07:24.030  6893  6893 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@70257d2 time:189509
,08-11 09:07:24.036  6893  6893 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-11 09:07:24.092  6893  6893 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-11 09:07:24.102  1622  1622 E b       : Unable to connect to the editor to retrieve text... will retry later
08-11 09:07:24.130  6893  6893 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-11 09:07:24.155  6893  6893 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6893
,08-11 09:07:24.312  6893  6893 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 09:07:24.704  6893  6938 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1635588864
,08-11 09:07:24.724  6893  6938 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 09:07:24.724  6893  6938 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 09:07:24.724  6893  6938 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 09:07:24.724  6893  6938 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 09:07:24.724  6893  6938 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-11 09:07:24.724  6893  6938 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6cf3f6 added. We now have 1 listener(s)
,08-11 09:07:24.733   842  1896 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 09:07:24.740  6893  6938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,08-11 09:07:24.743  6893  6938 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-11 09:07:24.744  6893  6938 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 09:07:24.745  6893  6938 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 09:07:24.756  6893  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 09:07:24.756  6893  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 09:07:24.756  6893  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 09:07:24.756  6893  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-11 09:07:24.756  6893  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 09:07:24.756  6893  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 09:07:24.756  6893  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 09:07:24.756  6893  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 09:07:24.756  6893  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 09:07:24.756  6893  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 09:07:24.756  6893  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 09:07:24.756  6893  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 09:07:24.756  6893  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 09:07:24.756  6893  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-11 09:07:24.756  6893  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@16534ccd added. We now have 1 listener(s)
,08-11 09:07:24.758  6893  6938 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 09:07:24.771  6893  6938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-11 09:07:24.771  6893  6938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-11 09:07:24.771  6893  6938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-11 09:07:24.771  6893  6938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-11 09:07:24.771  6893  6938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-11 09:07:24.777  6893  6938 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 09:07:24.778   842  1877 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 09:07:24.779  6893  6938 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-11 09:07:24.794  2038  2070 D BluetoothAdapterService(975205014): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@38b2dd9c
,08-11 09:07:24.798  6893  6938 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-11 09:07:24.798  6893  6938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 09:07:24.798  6893  6938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 09:07:24.798  6893  6938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 09:07:24.798  6893  6938 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 09:07:24.798  6893  6938 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 09:07:24.798  6893  6938 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 09:07:24.798  6893  6938 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 09:07:24.798  6893  6938 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 09:07:24.798  6893  6938 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-11 09:07:24.798  6893  6938 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 09:07:24.799  6893  6938 I io.jxcore.node.LifeCycleMonitor: start: OK
08-11 09:07:24.800  6893  6893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 09:07:24.802  6893  6893 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 09:07:24.829  6893  6893 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 09:07:24.977  6893  6907 I art     : CheckpointMarkThreadRoots callback created = 0xb07cb2f0
,08-11 09:07:25.024  6893  6907 I art     : CheckpointMarkThreadRoots callback created = 0xb07cb2b0
,08-11 09:07:25.598  6893  6944 W jxcore-log: Initializing JXcore engine
,08-11 09:07:25.601  6893  6944 W jxcore-log: JXcore engine is ready
08-11 09:07:25.729  6944  6944 W Thread-804: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[8242]" dev="sockfs" ino=8242 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-11 09:07:25.729  6944  6944 W Thread-804: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-11 09:07:25.729  6944  6944 W Thread-804: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8311]" dev="sockfs" ino=8311 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,08-11 09:07:25.729  6944  6944 W Thread-804: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-11 09:07:25.729  6944  6944 W Thread-804: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-11 09:07:25.729  6944  6944 W Thread-804: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[30528]" dev="sockfs" ino=30528 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-11 09:07:25.776  6893  6944 W jxcore-log: Starting JXcore engine
,08-11 09:07:25.955  6893  6944 W jxcore-log: Platform android
08-11 09:07:25.955  6893  6944 W jxcore-log: 
08-11 09:07:25.956  6893  6944 W jxcore-log: Process ARCH arm
08-11 09:07:25.956  6893  6944 W jxcore-log: 
,08-11 09:07:26.202  6893  6944 I jxcore-log: JXcore Cordova bridge is ready!
08-11 09:07:26.202  6893  6944 I jxcore-log: 
08-11 09:07:26.203  6893  6944 W jxcore-log: JXcore engine is started
,08-11 09:07:26.211  6893  6938 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-11 09:07:26.213  6893  6893 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-11 09:07:28.202   294   346 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 09:07:33.207   294   346 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 09:07:38.212   294   346 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 09:07:42.008  6893  6944 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-11 09:07:42.008  6893  6944 I jxcore-log: 
,08-11 09:07:42.012  6893  6944 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-11 09:07:42.012  6893  6944 I jxcore-log: 
08-11 09:07:42.018  2038  2070 D BluetoothAdapterService(975205014): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@38b2dd9c
08-11 09:07:42.019  6893  6944 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 09:07:42.019  6893  6944 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 09:07:42.019  6893  6944 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 09:07:42.019  6893  6944 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 09:07:42.019  6893  6944 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 09:07:42.019  6893  6944 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 09:07:42.019  6893  6944 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 09:07:42.019  6893  6944 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 09:07:42.022  2038  2070 D BluetoothAdapterService(975205014): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@38b2dd9c
,08-11 09:07:42.023  6893  6944 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-11 09:07:42.027  6893  6944 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-11 09:07:42.027  6893  6944 I jxcore-log: 
08-11 09:07:42.029  6893  6944 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-11 09:07:42.029  6893  6944 I jxcore-log: 
08-11 09:07:42.555  6893  6944 E JX-Cordova: JavaCall recevied a call for unknown method executeNativeTests
08-11 09:07:42.555  6893  6944 I jxcore-log: Failed to execute UT.
08-11 09:07:42.555  6893  6944 I jxcore-log: 
,08-11 09:07:42.555  6893  6944 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-11 09:07:42.555  6893  6944 I jxcore-log: 
08-11 09:07:42.563  6893  6944 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-11 09:07:42.563  6893  6944 I jxcore-log: 
08-11 09:07:42.574  6893  6893 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-11 09:07:42.903  6960  6960 D AndroidRuntime: 
08-11 09:07:42.903  6960  6960 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-11 09:07:42.910  6960  6960 D AndroidRuntime: CheckJNI is OFF
08-11 09:07:43.162   842  1006 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
08-11 09:07:43.162   842  1006 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
08-11 09:07:43.162   842  1006 D sensors_hal_Time: tsOffsetIs: Apps: 208641806852; DSPS: 6935327; Offset : -3020822341
,08-11 09:07:43.216   294   346 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 09:07:43.232  6960  6960 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-11 09:07:43.296   842   878 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
,08-11 09:07:43.297   842   878 I ActivityManager: Killing 6893:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
,08-11 09:07:43.347   842  1877 I WindowState: WIN DEATH: Window{18162a05 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 09:07:43.372   842  1877 D InputDispatcher: Focus left window: Window{18162a05 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 09:07:43.372   842  1877 D InputDispatcher: Window went away: Window{18162a05 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 09:07:43.415   842  1066 W PackageSettings: Skipping PackageSetting{101c2fb2 com.example.hello/10317} due to missing metadata
,08-11 09:07:43.417   842   878 I ActivityManager:   Force finishing activity ActivityRecord{d25a8c6 u0 com.test.thalitest/.MainActivity t259}
,08-11 09:07:43.479   842  1380 W ActivityManager: Spurious death for ProcessRecord{39251d80 6893:com.test.thalitest/u0a30}, curProc for 6893: null
,08-11 09:07:43.479   842  1066 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
,08-11 09:07:43.487   842  1066 I ActivityManager:   Force finishing activity ActivityRecord{d25a8c6 u0 com.test.thalitest/.MainActivity t259 f}
08-11 09:07:43.489   842  1066 W ActivityManager: Duplicate finish request for ActivityRecord{d25a8c6 u0 com.test.thalitest/.MainActivity t259 f}
,08-11 09:07:43.560  1940  1940 I art     : Explicit concurrent mark sweep GC freed 2497(114KB) AllocSpace objects, 0(0B) LOS objects, 40% free, 12MB/21MB, paused 1.851ms total 68.140ms
,08-11 09:07:43.602  1374  1374 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-11 09:07:43.605  1840  1840 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,08-11 09:07:43.624  3635  3635 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,08-11 09:07:43.634  1733  2415 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-11 09:07:43.638   842  1300 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-11 09:07:43.640  3635  3635 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-11 09:07:43.640  3635  3635 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-11 09:07:43.640  3635  3635 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
08-11 09:07:43.640  3635  3635 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-11 09:07:43.640  3635  3635 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-11 09:07:43.641  3635  3635 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-11 09:07:43.641  3635  3635 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
08-11 09:07:43.641  3635  3635 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-11 09:07:43.641  3635  3635 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-11 09:07:43.641  3635  3635 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
08-11 09:07:43.641  3635  3635 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
08-11 09:07:43.665  3422  3422 I art     : Explicit concurrent mark sweep GC freed 3186(154KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 16MB/21MB, paused 1.130ms total 170.111ms
,08-11 09:07:43.668   842   878 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=6986 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-11 09:07:43.671  1878  1878 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
08-11 09:07:43.699  1374  1508 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-11 09:07:43.699  1374  1508 D KeyguardModel: createShortcutInfo...
,08-11 09:07:43.706  1374  1374 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-11 09:07:43.708  1374  1508 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 09:07:43.708  1374  1508 D KeyguardModel: createShortcutInfo...
08-11 09:07:43.711  1374  1508 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-11 09:07:43.748  1878  1878 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
,08-11 09:07:43.790  1374  1508 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-11 09:07:43.792  1374  1508 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-11 09:07:43.792  1374  1508 D KeyguardModel: createShortcutInfo...
08-11 09:07:43.794  1374  1508 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 09:07:43.794  1374  1508 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-11 09:07:43.798  1374  1508 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 09:07:43.798  1374  1508 D KeyguardModel: createShortcutInfo...
,08-11 09:07:43.800  1374  1508 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 09:07:43.800  1374  1508 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-11 09:07:43.806  1374  1508 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 09:07:43.806  1374  1508 D KeyguardModel: createShortcutInfo...
08-11 09:07:43.814  1374  1374 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-11 09:07:43.814  1374  1374 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-11 09:07:43.830  1374  1374 D KeyguardModel: handleShortcutListChanged...
,08-11 09:07:43.832  1878  1878 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-11 09:07:43.834  1878  1878 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
08-11 09:07:43.834  1878  1878 I Activity: Activity.onPostResume() called 
08-11 09:07:43.834  1374  1508 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-11 09:07:43.834  1374  1508 D KeyguardModel: createShortcutInfo...
,08-11 09:07:43.842  1374  1508 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-11 09:07:43.842  1374  1508 D KeyguardModel: createShortcutInfo...
08-11 09:07:43.844  1374  1508 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 09:07:43.845  1374  1508 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-11 09:07:43.846  1374  1508 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-11 09:07:43.846  1374  1508 D KeyguardModel: createShortcutInfo...
,08-11 09:07:43.848  1374  1508 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 09:07:43.848  1374  1508 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-11 09:07:43.850  1374  1508 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-11 09:07:43.850  1374  1508 D KeyguardModel: createShortcutInfo...
08-11 09:07:43.851  6986  6986 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-11 09:07:43.851  6986  6986 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-11 09:07:43.852  1878  1878 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
08-11 09:07:43.853  6986  6986 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-11 09:07:43.857   842   842 I art     : Explicit concurrent mark sweep GC freed 49278(2MB) AllocSpace objects, 14(224KB) LOS objects, 33% free, 24MB/36MB, paused 16.485ms total 309.736ms
08-11 09:07:43.857   842  1066 I art     : WaitForGcToComplete blocked for 180.314ms for cause Explicit
08-11 09:07:43.877  1374  1508 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-11 09:07:43.877  1374  1508 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-11 09:07:43.877  1878  7004 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
08-11 09:07:43.879   842   995 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
08-11 09:07:43.879   842   995 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
,08-11 09:07:43.880   842   995 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-11 09:07:43.880   842   995 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-11 09:07:43.880   842   995 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-11 09:07:43.880   842   995 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@355ceaa0,  pkg=WindowManager.LayoutParams
08-11 09:07:43.880  1374  1508 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-11 09:07:43.880   842   995 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-11 09:07:43.880  1374  1508 D KeyguardModel: createShortcutInfo...
08-11 09:07:43.881  1374  1374 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
08-11 09:07:43.881  1374  1374 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
08-11 09:07:43.881  1374  1374 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
08-11 09:07:43.881  1374  1374 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-11 09:07:43.888   842  1038 D InputDispatcher: Focus entered window: Window{1339a028 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
,08-11 09:07:43.891  1374  1374 D KeyguardModel: handleShortcutListChanged...
08-11 09:07:43.906  1878  1878 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-11 09:07:43.908  1878  1878 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-11 09:07:43.908  1878  1878 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
08-11 09:07:43.916  1878  1878 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
08-11 09:07:43.917  1878  1878 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
08-11 09:07:43.917  1878  1878 I PhoneWindow: [setNavigationBarColor] color=0x 0
08-11 09:07:43.918   842   842 D administrator: Handling package changes for user 0
,08-11 09:07:43.924   842  1947 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
08-11 09:07:43.931   842  1947 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 6893 uid 10030
,08-11 09:07:43.984  1878  1878 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-11 09:07:43.984  1622  1622 E b       : Unable to connect to the editor to retrieve text... will retry later
08-11 09:07:43.988  1878  1878 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@13c01006 time:209467
08-11 09:07:44.010   842   998 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1b050308 u0 com.lge.launcher2/.Launcher t258} time:209489
,08-11 09:07:44.042  1878  1878 I art     : Explicit concurrent mark sweep GC freed 3840(207KB) AllocSpace objects, 4(645KB) LOS objects, 40% free, 15MB/25MB, paused 1.119ms total 52.985ms
08-11 09:07:44.042  1878  1878 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-11 09:07:44.054   842   842 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-11 09:07:44.054   842   842 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-11 09:07:44.056   842   842 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-11 09:07:44.062   842  1351 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
08-11 09:07:44.122   842   877 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-11 09:07:44.138  6986  6986 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-11 09:07:44.161  6986  6986 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,08-11 09:07:44.164   842  1066 I art     : Explicit concurrent mark sweep GC freed 14083(1541KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 4.831ms total 304.853ms
08-11 09:07:44.234   842   877 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-11 09:07:44.246  1878  1878 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-11 09:07:44.254  6960  6960 D AndroidRuntime: Shutting down VM
,08-11 09:07:44.308   842  1066 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7008 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-11 09:07:44.309  1787  1787 D LCardEmulationManager: getHceAppCount hostAppNum : 0
,08-11 09:07:44.309  1787  1787 D LCardEmulationManager: getDefaultRoute
,08-11 09:07:44.409  6986  6986 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-11 09:07:44.417   842  1846 I ActivityManager: Killing 6537:com.google.android.talk/u0a61 (adj 15): empty #11
08-11 09:07:44.438  6582  6582 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-11 09:07:44.493   842  1846 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7028 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3003, 1023, 1004, 2002, 3002, 3001, 3008, 1007, 1026, 3005, 1009, 1027, 1003, 1014, 1010, 4002, 1002, 1021, 3004, 3009} abi=armeabi-v7a
,08-11 09:07:44.494   842  1846 I ActivityManager: Killing 6611:com.android.gallery3d/u0a23 (adj 15): empty #11
08-11 09:07:44.521   842  1819 W libprocessgroup: failed to open /acct/uid_10061/pid_6537/cgroup.procs: No such file or directory
,08-11 09:07:44.523   842  1786 W libprocessgroup: failed to open /acct/uid_10023/pid_6611/cgroup.procs: No such file or directory

```
