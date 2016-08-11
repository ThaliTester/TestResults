#### Test 80912877b687439_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
08-11 10:50:11.310  1376  1376 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
08-11 10:50:11.310  1376  1376 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-11 10:50:11.310  1376  1376 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
08-11 10:50:11.310  1376  1376 I [SystemUI]LGPowerUI: On Skip Timer : true
08-11 10:50:11.316   497   497 D charger_monitor: init target 500000
,08-11 10:50:11.321   497   497 D charger_monitor: vchg_loop stable: 0, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
--------- beginning of system
08-11 10:50:11.325  1877  1877 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
08-11 10:50:11.368  1376  1376 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 278
08-11 10:50:11.368  1376  1376 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-11 10:50:11.368  1376  1376 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 278
08-11 10:50:11.370  1914  1914 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
08-11 10:50:11.370  1914  1914 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
08-11 10:50:11.372  1877  2050 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-11 10:50:11.372  1877  2050 D LEDHandler: Battery Level Remaining: 100%
08-11 10:50:11.372  1877  2050 D LEDHandler: Battery Temp: 278, mChargingStatus=5, mChargingStop=false
08-11 10:50:11.374  1376  1376 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-11 10:50:11.375  2063  3533 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-11 10:50:11.378   840   840 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 10:50:11.378   840   840 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-11 10:50:11.378   840  1315 D WifiController: battery changed pluggedType: 2
08-11 10:50:11.745  6815  6815 D AndroidRuntime: 
08-11 10:50:11.745  6815  6815 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-11 10:50:11.757  6815  6815 D AndroidRuntime: CheckJNI is OFF
08-11 10:50:12.141  6815  6815 D AndroidRuntime: Calling main entry com.android.commands.am.Am
08-11 10:50:12.168   840   857 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-11 10:50:12.216   840   857 D ActivityManager: setTaskToReturnTo : TaskRecord{367f5d59 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 10:50:12.216   840   857 D ActivityManager: setTaskToReturnTo : TaskRecord{367f5d59 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-11 10:50:12.225   840   857 D WindowStateEx: AppWindowTokenEx init.. 
08-11 10:50:12.285   840   857 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6829 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-11 10:50:12.288   840   857 D InputDispatcher: Focus left window: Window{8dc9e51 u0 com.lge.launcher2/com.lge.launcher2.Launcher}
08-11 10:50:12.288  6815  6815 D AndroidRuntime: Shutting down VM
08-11 10:50:12.296  1952  1952 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
08-11 10:50:12.339   840   840 V ActivityManager: Display changed displayId=0
08-11 10:50:12.343  1780  1780 D DSDPConnection: Display #0 changed.
08-11 10:50:12.481  6829  6829 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-11 10:50:12.585  6829  6829 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,08-11 10:50:12.639  6829  6829 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 8591-8593)
,08-11 10:50:12.639  6829  6829 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 10:50:12.685  6829  6829 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {373952f2}
,08-11 10:50:12.687  6829  6829 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-11 10:50:12.688  6829  6829 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-11 10:50:12.704  6829  6829 I BrowserStartupController: Initializing chromium process, singleProcess=true
,08-11 10:50:12.705  6829  6829 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-11 10:50:12.707  6829  6829 E SysUtils: ApplicationContext is null in ApplicationStatus
08-11 10:50:12.744  6829  6829 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,08-11 10:50:12.751  6829  6829 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 10:50:12.751  6829  6829 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-11 10:50:12.752  6829  6829 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-11 10:50:12.752  6829  6829 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-11 10:50:12.752  6829  6829 I Adreno-EGL: Build Date: 03/02/15 Mon
08-11 10:50:12.752  6829  6829 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
08-11 10:50:12.752  6829  6829 I Adreno-EGL: Remote Branch: 
08-11 10:50:12.752  6829  6829 I Adreno-EGL: Local Patches: 
08-11 10:50:12.752  6829  6829 I Adreno-EGL: Reconstruct Branch: 
08-11 10:50:12.822   277  1608 V AudioPolicyService: registerClient() client 0xb57ecc20, uid 10030
,08-11 10:50:12.844   840  1011 D BluetoothManagerService: Message: 20
08-11 10:50:12.844   840  1011 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1a4952cd:true
,08-11 10:50:12.848  2063  2079 D BluetoothAdapterService(392736704): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@11690516
,08-11 10:50:12.869   840   879 W ActivityManager: Activity pause timeout for ActivityRecord{e820d1e u0 com.test.thalitest/.MainActivity t259}
,08-11 10:50:12.994   293   360 I ThermalEngine: Sensor:pa_therm0:29000 mC
,08-11 10:50:13.021  6829  6829 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-11 10:50:13.035  6829  6829 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-11 10:50:13.043  6829  6829 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
,08-11 10:50:13.048  6829  6829 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-11 10:50:13.048  6829  6829 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-11 10:50:13.067  6829  6829 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-11 10:50:13.077  6829  6829 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 10:50:13.077  6829  6829 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-11 10:50:13.142  6829  6829 I Activity: Activity.onPostResume() called 
,08-11 10:50:13.148  6829  6891 D OpenGLRenderer: Render dirty regions requested: true
08-11 10:50:13.148  6829  6891 I OpenGLRenderer: Initialized EGL, version 1.4
08-11 10:50:13.154  6829  6891 D OpenGLRenderer: Enabling debug mode 0
,08-11 10:50:13.173  6829  6829 D Atlas   : Validating map...
,08-11 10:50:13.178   840  1883 D SplitWindow: check instance of lgWin Window{25a1893d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-11 10:50:13.201  6829  6878 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
08-11 10:50:13.234   840  1008 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
,08-11 10:50:13.237   840  1008 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
08-11 10:50:13.237  1376  1376 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
08-11 10:50:13.237  1376  1376 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
08-11 10:50:13.237  1376  1376 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
08-11 10:50:13.237  1376  1376 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
08-11 10:50:13.238   840  1008 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
08-11 10:50:13.238   840  1008 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
08-11 10:50:13.238   840  1008 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
08-11 10:50:13.238   840  1008 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@9110d54,  pkg=WindowManager.LayoutParams
08-11 10:50:13.238   840  1008 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
08-11 10:50:13.240   840   857 D InputDispatcher: Focus entered window: Window{25a1893d u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-11 10:50:13.270   840  1940 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,08-11 10:50:13.293   840  1013 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +922ms (total +1s63ms)
08-11 10:50:13.293   840  1013 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{e820d1e u0 com.test.thalitest/.MainActivity t259} time:189247
08-11 10:50:13.297  6829  6829 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
08-11 10:50:13.299  6829  6829 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1a54441c time:189254
08-11 10:50:13.361  6829  6829 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,08-11 10:50:13.364  1635  1635 E b       : Unable to connect to the editor to retrieve text... will retry later
08-11 10:50:13.393  6829  6829 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,08-11 10:50:13.436  6829  6829 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 6829
,08-11 10:50:13.583  6829  6829 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-11 10:50:13.956  6829  6894 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1426137344
,08-11 10:50:13.975  6829  6894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-11 10:50:13.975  6829  6894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-11 10:50:13.975  6829  6894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-11 10:50:13.975  6829  6894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-11 10:50:13.975  6829  6894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-11 10:50:13.975  6829  6894 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@32270e20 added. We now have 1 listener(s)
,08-11 10:50:13.984   840   857 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 10:50:13.987  6829  6894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,08-11 10:50:13.989  6829  6894 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
08-11 10:50:13.991  6829  6894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-11 10:50:13.991  6829  6894 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-11 10:50:14.002  6829  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-11 10:50:14.002  6829  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-11 10:50:14.002  6829  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-11 10:50:14.002  6829  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
08-11 10:50:14.002  6829  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-11 10:50:14.002  6829  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-11 10:50:14.002  6829  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-11 10:50:14.002  6829  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-11 10:50:14.002  6829  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-11 10:50:14.002  6829  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-11 10:50:14.002  6829  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-11 10:50:14.002  6829  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-11 10:50:14.002  6829  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-11 10:50:14.002  6829  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-11 10:50:14.003  6829  6894 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30a0a47f added. We now have 1 listener(s)
,08-11 10:50:14.004  6829  6894 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-11 10:50:14.014  6829  6894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-11 10:50:14.014  6829  6894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-11 10:50:14.016  6829  6894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-11 10:50:14.016  6829  6894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-11 10:50:14.016  6829  6894 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-11 10:50:14.020  6829  6894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-11 10:50:14.020   840  1356 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-11 10:50:14.021  6829  6894 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
08-11 10:50:14.030  2063  3709 D BluetoothAdapterService(392736704): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@11690516
,08-11 10:50:14.033  6829  6894 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-11 10:50:14.033  6829  6894 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-11 10:50:14.033  6829  6894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-11 10:50:14.033  6829  6894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-11 10:50:14.033  6829  6894 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-11 10:50:14.033  6829  6894 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-11 10:50:14.033  6829  6894 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-11 10:50:14.033  6829  6894 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-11 10:50:14.033  6829  6894 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-11 10:50:14.033  6829  6894 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-11 10:50:14.033  6829  6894 D io.jxcore.node.ConnectivityMonitor: start: OK
08-11 10:50:14.035  6829  6829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 10:50:14.036  6829  6829 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-11 10:50:14.037  6829  6894 I io.jxcore.node.LifeCycleMonitor: start: OK
08-11 10:50:14.076  6829  6829 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-11 10:50:14.221  6829  6843 I art     : CheckpointMarkThreadRoots callback created = 0xb07ff7a0
,08-11 10:50:14.256  6829  6843 I art     : CheckpointMarkThreadRoots callback created = 0xb07ff770
,08-11 10:50:14.819  6829  6901 W jxcore-log: Initializing JXcore engine
,08-11 10:50:14.822  6829  6901 W jxcore-log: JXcore engine is ready
08-11 10:50:14.952  6901  6901 W Thread-801: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[5896]" dev="sockfs" ino=5896 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-11 10:50:14.952  6901  6901 W Thread-801: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-11 10:50:14.952  6901  6901 W Thread-801: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[6012]" dev="sockfs" ino=6012 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-11 10:50:14.952  6901  6901 W Thread-801: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-11 10:50:14.952  6901  6901 W Thread-801: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
08-11 10:50:14.952  6901  6901 W Thread-801: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[31190]" dev="sockfs" ino=31190 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
08-11 10:50:14.988  6829  6901 W jxcore-log: Starting JXcore engine
,08-11 10:50:15.175  6829  6901 W jxcore-log: Platform android
08-11 10:50:15.175  6829  6901 W jxcore-log: 

```
