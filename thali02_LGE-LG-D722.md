#### Test 836273370459b7a_thali02_LGE-LG-D722 Logs


```
--------- beginning of main
09-13 16:34:53.307   295   358 I ThermalEngine: Sensor:pa_therm0:33000 mC
,09-13 16:34:55.005  6994  6994 D AndroidRuntime: 
09-13 16:34:55.005  6994  6994 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
09-13 16:34:55.016  6994  6994 D AndroidRuntime: CheckJNI is OFF
09-13 16:34:55.405  6994  6994 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
09-13 16:34:55.422   835  1942 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
09-13 16:34:55.461   835  1942 D ActivityManager: setTaskToReturnTo : TaskRecord{2d2a1a17 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 16:34:55.461   835  1942 D ActivityManager: setTaskToReturnTo : TaskRecord{2d2a1a17 #259 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
09-13 16:34:55.465   835  1942 D WindowStateEx: AppWindowTokenEx init.. 
09-13 16:34:55.510   835  1942 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=7014 uid=10030 gids={50030, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
09-13 16:34:55.512   835  1942 D InputDispatcher: Focus left window: Window{3b3d977d u0 com.lge.launcher2/com.lge.launcher2.Launcher}
09-13 16:34:55.512  6994  6994 D AndroidRuntime: Shutting down VM
09-13 16:34:55.518  1951  1951 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus false
09-13 16:34:55.541   835   835 V ActivityManager: Display changed displayId=0
09-13 16:34:55.542  1794  1794 D DSDPConnection: Display #0 changed.
09-13 16:34:55.680  7014  7014 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,09-13 16:34:55.785  7014  7014 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.90 (code 240309000)
,09-13 16:34:55.847  7014  7014 I LibraryLoader: Time to load native libraries: 7 ms (timestamps 1332-1339)
09-13 16:34:55.847  7014  7014 I LibraryLoader: Expected native library version number "",actual native library version number ""
,09-13 16:34:55.874  7014  7014 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3bf4f5c4}
,09-13 16:34:55.875  7014  7014 I LibraryLoader: Expected native library version number "",actual native library version number ""
09-13 16:34:55.880  7014  7014 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,09-13 16:34:55.895  7014  7014 I BrowserStartupController: Initializing chromium process, singleProcess=true
09-13 16:34:55.897  7014  7014 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 16:34:55.901  7014  7014 E SysUtils: ApplicationContext is null in ApplicationStatus
09-13 16:34:55.957  7014  7014 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,09-13 16:34:55.962  7014  7014 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 16:34:55.962  7014  7014 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
09-13 16:34:55.968  7014  7014 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
09-13 16:34:55.968  7014  7014 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
09-13 16:34:55.968  7014  7014 I Adreno-EGL: Build Date: 03/02/15 Mon
09-13 16:34:55.968  7014  7014 I Adreno-EGL: Local Branch: LA.BF.1.1.2_RB1-AU017-20150302-1163306-1163307-1163308-1163309
09-13 16:34:55.968  7014  7014 I Adreno-EGL: Remote Branch: 
09-13 16:34:55.968  7014  7014 I Adreno-EGL: Local Patches: 
09-13 16:34:55.968  7014  7014 I Adreno-EGL: Reconstruct Branch: 
,09-13 16:34:56.036   284  1610 V AudioPolicyService: registerClient() client 0xb4143140, uid 10030
,09-13 16:34:56.057   835  1035 D BluetoothManagerService: Message: 20
09-13 16:34:56.057   835  1035 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1e35132b:true
,09-13 16:34:56.071  2083  2099 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
,09-13 16:34:56.073   835   972 W ActivityManager: Activity pause timeout for ActivityRecord{13aa4e04 u0 com.test.thalitest/.MainActivity t259}
09-13 16:34:56.215  7014  7014 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,09-13 16:34:56.230  7014  7014 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,09-13 16:34:56.237  7014  7014 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
09-13 16:34:56.241  7014  7014 D PhoneWindowEx: [PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
09-13 16:34:56.241  7014  7014 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,09-13 16:34:56.257  7014  7014 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,09-13 16:34:56.266  7014  7014 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 16:34:56.266  7014  7014 W art     : Attempt to remove local handle scope entry from IRT, ignoring
09-13 16:34:56.339  7014  7014 I Activity: Activity.onPostResume() called 
,09-13 16:34:56.345  7014  7056 D OpenGLRenderer: Render dirty regions requested: true
09-13 16:34:56.345  7014  7056 I OpenGLRenderer: Initialized EGL, version 1.4
09-13 16:34:56.354  7014  7056 D OpenGLRenderer: Enabling debug mode 0
,09-13 16:34:56.373  7014  7014 D Atlas   : Validating map...
,09-13 16:34:56.378   835  2187 D SplitWindow: check instance of lgWin Window{28c51d1b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 16:34:56.396  7014  7043 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
09-13 16:34:56.423   835  1034 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0xfff5f5f5
,09-13 16:34:56.426   835  1034 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.test.thalitest
09-13 16:34:56.426  1376  1376 I [SystemUI]NavigationThemeResource: notify navigation bar color(0xfff5f5f5)
09-13 16:34:56.429  1376  1376 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(WHITE_WITH_SHADOW -> BLACK)
09-13 16:34:56.429  1376  1376 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=true (NOT Transparent)
09-13 16:34:56.429  1376  1376 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
09-13 16:34:56.429   835  1034 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
09-13 16:34:56.429   835  1034 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
09-13 16:34:56.429   835  1034 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-13 16:34:56.429   835  1034 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@bd4b004,  pkg=WindowManager.LayoutParams
09-13 16:34:56.430   835  1034 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
09-13 16:34:56.445   835  1902 D InputDispatcher: Focus entered window: Window{28c51d1b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 16:34:56.475   835  1942 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
,09-13 16:34:56.495   835  1036 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +922ms (total +1s24ms)
09-13 16:34:56.495   835  1036 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{13aa4e04 u0 com.test.thalitest/.MainActivity t259} time:181988
09-13 16:34:56.499  7014  7014 W IInputConnectionWrapper: showStatusIcon on inactive InputConnection
09-13 16:34:56.499  7014  7014 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@16d394de time:181992
09-13 16:34:56.569  7014  7014 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,09-13 16:34:56.580  1634  1634 E b       : Unable to connect to the editor to retrieve text... will retry later
09-13 16:34:56.614  7014  7014 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 7014
,09-13 16:34:56.615  7014  7014 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
09-13 16:34:56.784  7014  7014 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,09-13 16:34:57.156  7014  7058 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1635609344
,09-13 16:34:57.176  7014  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
09-13 16:34:57.176  7014  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
09-13 16:34:57.176  7014  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
09-13 16:34:57.176  7014  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
09-13 16:34:57.176  7014  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,09-13 16:34:57.178  7014  7058 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c4fe342 added. We now have 1 listener(s)
09-13 16:34:57.187   835  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:34:57.192  7014  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:95:C7:87:85:54
,09-13 16:34:57.196  7014  7058 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-13 16:34:57.198  7014  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:34:57.198  7014  7058 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:34:57.204  7014  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
09-13 16:34:57.204  7014  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
09-13 16:34:57.204  7014  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
09-13 16:34:57.204  7014  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:95:C7:87:85:54
09-13 16:34:57.204  7014  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
09-13 16:34:57.204  7014  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
09-13 16:34:57.204  7014  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
09-13 16:34:57.204  7014  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
09-13 16:34:57.204  7014  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
09-13 16:34:57.204  7014  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
09-13 16:34:57.204  7014  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
09-13 16:34:57.204  7014  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
09-13 16:34:57.204  7014  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
09-13 16:34:57.204  7014  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
09-13 16:34:57.205  7014  7058 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3d9e4d89 added. We now have 1 listener(s)
09-13 16:34:57.205  7014  7058 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,09-13 16:34:57.221  7014  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 16:34:57.221  7014  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,09-13 16:34:57.224  7014  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
09-13 16:34:57.224  7014  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
09-13 16:34:57.225  7014  7058 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
09-13 16:34:57.230  7014  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:34:57.230   835  1401 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:34:57.231  7014  7058 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:95:C7:87:85:54
09-13 16:34:57.242  2083  2099 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
,09-13 16:34:57.249  7014  7058 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
09-13 16:34:57.250  7014  7058 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:34:57.250  7014  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:34:57.250  7014  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:34:57.250  7014  7058 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:34:57.250  7014  7058 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:34:57.250  7014  7058 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:34:57.250  7014  7058 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:34:57.250  7014  7058 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:34:57.250  7014  7058 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,09-13 16:34:57.250  7014  7058 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:34:57.252  7014  7014 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:34:57.256  7014  7058 I io.jxcore.node.LifeCycleMonitor: start: OK
09-13 16:34:57.256  7014  7014 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:34:57.292  7014  7014 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,09-13 16:34:57.425  7014  7028 I art     : CheckpointMarkThreadRoots callback created = 0xb069f040
,09-13 16:34:57.478  7014  7028 I art     : CheckpointMarkThreadRoots callback created = 0xb0674fd0
,09-13 16:34:58.174  7014  7072 W jxcore-log: Initializing JXcore engine
,09-13 16:34:58.177  7014  7072 W jxcore-log: JXcore engine is ready
09-13 16:34:58.315   295   358 I ThermalEngine: Sensor:pa_therm0:33000 mC
,09-13 16:34:58.339  7072  7072 W Thread-830: type=1400 audit(0.0:4): avc: denied { ioctl } for path="socket:[7551]" dev="sockfs" ino=7551 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
,09-13 16:34:58.339  7072  7072 W Thread-830: type=1400 audit(0.0:5): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2072 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
09-13 16:34:58.339  7072  7072 W Thread-830: type=1400 audit(0.0:6): avc: denied { ioctl } for path="socket:[8423]" dev="sockfs" ino=8423 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
09-13 16:34:58.339  7072  7072 W Thread-830: type=1400 audit(0.0:7): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/framework-res.apk" dev="mmcblk0p30" ino=93 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
,09-13 16:34:58.349  7072  7072 W Thread-830: type=1400 audit(0.0:8): avc: denied { ioctl } for path="/cust/OPEN_EU/overlay/framework/com.lge.apk" dev="mmcblk0p30" ino=71 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=file permissive=0
,09-13 16:34:58.349  7072  7072 W Thread-830: type=1400 audit(0.0:9): avc: denied { ioctl } for path="socket:[31575]" dev="sockfs" ino=31575 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
09-13 16:34:58.375  7014  7072 W jxcore-log: Starting JXcore engine
,09-13 16:34:58.535  7014  7072 W jxcore-log: Platform android
09-13 16:34:58.535  7014  7072 W jxcore-log: 
09-13 16:34:58.535  7014  7072 W jxcore-log: Process ARCH arm
09-13 16:34:58.535  7014  7072 W jxcore-log: 
,09-13 16:34:58.624   835  2023 I art     : Explicit concurrent mark sweep GC freed 37959(1856KB) AllocSpace objects, 8(128KB) LOS objects, 33% free, 23MB/35MB, paused 2.173ms total 164.155ms
,09-13 16:34:58.819  7014  7072 I jxcore-log: JXcore Cordova bridge is ready!
09-13 16:34:58.819  7014  7072 I jxcore-log: 
,09-13 16:34:58.819  7014  7072 W jxcore-log: JXcore engine is started
09-13 16:34:58.823  7014  7058 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
09-13 16:34:58.824  7014  7014 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
09-13 16:35:00.093  1376  1376 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
09-13 16:35:00.094  1376  1376 I KeyguardUpdateMonitor: called onTimeUpdated()
,09-13 16:35:00.097  1376  1376 I [SystemUI]Clock: called onTimeUpdated()
09-13 16:35:00.099  1376  1376 I LgeClockWidgetControlView: called onTimeUpdated()
09-13 16:35:00.099  1376  1376 I [SystemUI]DateView: called onTimeUpdated()
09-13 16:35:00.100  1376  1376 I [SystemUI]DateView: called onTimeUpdated()
09-13 16:35:00.101  1376  1376 D KeyguardUpdateMonitor: handleTimeUpdate
09-13 16:35:01.000   835  1290 D PowerManagerServiceEx: acquireWakeLockInternal: lock=573394160, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=835
,09-13 16:35:01.003   835  1290 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3be5a7ce type 2 when 186483 com.google.android.gms} when 186483
09-13 16:35:01.058   835   835 D PowerManagerServiceEx: releaseWakeLockInternal: lock=573394160 [*alarm*], flags=0x0
,09-13 16:35:01.763   496   496 D charger_monitor: init target 500000
,09-13 16:35:01.772  1376  1376 D KeyguardUpdateMonitor: Intent.ACTION_BATTERYEX_CHANGED EXTRA_CHARGING_CURRENT : 0 / EXTRA_HVDCP_TYPE : false
09-13 16:35:01.772  1878  1878 D PowerService: isACConnected: false, isFastChargerType: false, isCharging: false, isFastChargerConnected: false
09-13 16:35:01.772  1376  1376 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
09-13 16:35:01.772  1376  1376 I [SystemUI]LGPowerUI: levelEx = 100, plugTypeEx = 2, WirelessAlignment = 0, chargingCurrent = 0, orientation = PORTRAIT
09-13 16:35:01.772  1376  1376 I [SystemUI]LGPowerUI: On Skip Timer : true
09-13 16:35:01.794  1914  1914 I QCNEJ   : |CORE| CNE received action: android.intent.action.BATTERY_CHANGED
09-13 16:35:01.794  1878  2051 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
09-13 16:35:01.794  1878  2051 D LEDHandler: Battery Level Remaining: 100%
09-13 16:35:01.794  1878  2051 D LEDHandler: Battery Temp: 310, mChargingStatus=5, mChargingStop=false
,09-13 16:35:01.797   835   835 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:35:01.797   835   835 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:35:01.797   835  1317 D WifiController: battery changed pluggedType: 2
09-13 16:35:01.798  2083  3541 D HeadsetStateMachine: Disconnected process message: 10, size: 0
09-13 16:35:01.798  1376  1376 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 310
09-13 16:35:01.799  1376  1376 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
09-13 16:35:01.800  1914  1914 I QCNEJ   : |CORE| UpdateBatteryStatus status=5 pluginType=2 level=100
09-13 16:35:01.801  1376  1376 I [SystemUI]LGPowerUI: level = 100, plugType = 2, plugged = true, mCharging = false, temperature = 310
09-13 16:35:01.803  1376  1376 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
09-13 16:35:01.815   496   496 D charger_monitor: vchg_loop stable: 1, is_settled = 0,usb_target_ua = 500000, usbin_current_now = 500000,fastchg_sts = 0, num_attempts = 0
,09-13 16:35:03.320   295   358 I ThermalEngine: Sensor:pa_therm0:33000 mC
,09-13 16:35:03.971   835   988 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-13 16:35:03.971   835   988 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-13 16:35:03.971   835   988 D sensors_hal_Time: tsOffsetIs: Apps: 189463628161; DSPS: 6300160; Offset : -2811836472
,09-13 16:35:04.064   835  2187 I ActivityManager: Process com.google.android.talk (pid 6535) has died
,09-13 16:35:08.325   295   358 I ThermalEngine: Sensor:pa_therm0:33000 mC
,09-13 16:35:13.329   295   358 I ThermalEngine: Sensor:pa_therm0:33000 mC
,09-13 16:35:14.772  7014  7072 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
09-13 16:35:14.772  7014  7072 I jxcore-log: 
09-13 16:35:14.775  7014  7072 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
09-13 16:35:14.775  7014  7072 I jxcore-log: 
,09-13 16:35:14.782  2083  3549 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
09-13 16:35:14.783  7014  7072 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:35:14.783  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:35:14.783  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:35:14.783  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:35:14.783  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:35:14.783  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:14.783  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:35:14.783  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:35:14.785  2083  2100 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
09-13 16:35:14.786  7014  7072 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:14.789  7014  7072 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
09-13 16:35:14.789  7014  7072 I jxcore-log: 
,09-13 16:35:14.791  7014  7072 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
09-13 16:35:14.791  7014  7072 I jxcore-log: 
09-13 16:35:15.617  7014  7072 I jxcore-log: Unit Test app is loaded
09-13 16:35:15.617  7014  7072 I jxcore-log: 
,09-13 16:35:15.632  7014  7072 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:35:15.632  7014  7072 I jxcore-log: 
,09-13 16:35:15.641  7014  7072 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 16:35:15.641  7014  7072 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@39694aa9 added. We now have 2 listener(s)
09-13 16:35:15.641   835  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:35:15.644  7014  7014 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,09-13 16:35:15.644  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-13 16:35:15.644  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:35:15.645  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:35:15.645  7014  7072 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:35:15.645  7014  7072 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2e4a782e added. We now have 2 listener(s)
09-13 16:35:15.645  7014  7072 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 16:35:15.645  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 16:35:15.648  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:15.651  2083  2099 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
09-13 16:35:15.651  7014  7072 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:35:15.651  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:35:15.651  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:35:15.651  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:35:15.651  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:35:15.651  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:15.651  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:35:15.651  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:35:15.652  2083  3549 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
09-13 16:35:15.653  7014  7072 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:15.653  7014  7072 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:35:15.654  7014  7014 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:35:15.657  7014  7072 D ExecuteNativeTests: Running unit tests
09-13 16:35:15.658  7014  7014 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:35:15.661  7014  7072 D BluetoothAdapter: enable(): BT is already enabled..!
09-13 16:35:15.666   835  1957 D WifiServiceImplEx: setWifiEnabled: true pid=7014, uid=10030, package= com.test.thalitest, App Lable : ThaliTest
09-13 16:35:15.676   835  1957 D WifiService: setWifiEnabled: true pid=7014, uid=10030
,09-13 16:35:15.686  7014  7072 I System.out: Running UT
09-13 16:35:18.335   295   358 I ThermalEngine: Sensor:pa_therm0:33000 mC
,09-13 16:35:23.341   295   358 I ThermalEngine: Sensor:pa_therm0:33000 mC
,09-13 16:35:23.972   835   988 D sensors_hal_Time: time_service_sensor1_cb: msg_type 2
09-13 16:35:23.972   835   988 D sensors_hal_Time: time_service_sensor1_cb: Sn 24, msg Id 3, txn Id 0
09-13 16:35:23.972   835   988 D sensors_hal_Time: tsOffsetIs: Apps: 209465088195; DSPS: 6955570; Offset : -2811901716
,09-13 16:35:25.924  7014  7072 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 16:35:25.924  7014  7072 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2045dabf added. We now have 3 listener(s)
,09-13 16:35:25.926   835  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:35:25.929  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-13 16:35:25.929  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:35:25.929  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:35:25.930  7014  7072 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:35:25.930  7014  7072 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@351e858c added. We now have 3 listener(s)
09-13 16:35:25.930  7014  7072 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 16:35:25.930  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 16:35:25.934  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:25.937  2083  2099 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
,09-13 16:35:25.940  7014  7072 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:35:25.940  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:35:25.940  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:35:25.940  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:35:25.940  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:35:25.940  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:25.940  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:35:25.940  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:35:25.941  2083  3550 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
09-13 16:35:25.942  7014  7072 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:25.942  7014  7072 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:35:25.944  7014  7014 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:35:25.946  7014  7014 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:35:25.948  2083  2099 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
,09-13 16:35:25.960  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,09-13 16:35:25.964  7014  7072 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:35:25.964  7014  7072 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:35:25.965  7014  7072 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:35:25.971  7014  7072 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,09-13 16:35:25.973  7014  7072 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 16:35:25.974  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 16:35:25.977  7014  7072 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:35:25.977  7014  7072 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:35:25.977  7014  7072 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:35:25.982  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:25.982  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:25.983  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:35:25.983  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 16:35:25.983  7014  7072 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2045dabf removed from the list
09-13 16:35:25.983  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:25.983  7014  7072 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@351e858c removed from the list
09-13 16:35:25.983  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:25.983  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:25.994  7014  7072 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
09-13 16:35:25.994  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:25.994  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:25.994  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:25.994  7014  7072 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2045dabf not in the list
09-13 16:35:25.994  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:25.994  7014  7072 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@351e858c not in the list
09-13 16:35:25.994  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:25.994  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:25.994  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,09-13 16:35:26.007  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 16:35:26.007  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 16:35:26.007  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 16:35:26.007  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 16:35:26.007  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 16:35:26.007  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 16:35:26.007  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 16:35:26.007  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 16:35:26.007  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 16:35:26.007  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 16:35:26.007  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 16:35:26.007  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 16:35:26.007  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 16:35:26.007  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 16:35:26.007  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 16:35:26.007  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 16:35:26.007  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 16:35:26.007  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 16:35:26.008  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 16:35:26.008  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 16:35:26.008  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 16:35:26.008  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 16:35:26.008  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 16:35:26.008  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 16:35:26.008  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 16:35:26.008  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 16:35:26.008  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
09-13 16:35:26.008  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 16:35:26.008  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 16:35:26.008  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 16:35:26.008  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 16:35:26.008  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:26.008  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.008  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.008  7014  7072 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2045dabf not in the list
09-13 16:35:26.008  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:26.008  7014  7072 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@351e858c not in the list
09-13 16:35:26.008  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop,
09-13 16:35:26.008  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.008  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.009  7014  7072 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 16:35:26.014  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:35:26.023  2083  2099 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
09-13 16:35:26.024  7014  7072 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:35:26.024  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:35:26.024  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:35:26.024  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:35:26.024  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:35:26.024  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:26.024  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:35:26.024  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:35:26.025  2083  3550 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
09-13 16:35:26.027  7014  7072 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:26.027  7014  7072 D io.jxcore.node.ConnectivityMonitor: start: OK
,09-13 16:35:26.031  7014  7014 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:35:26.032  7014  7014 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:35:26.034  7014  7072 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:35:26.034  7014  7072 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 16:35:26.034  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 16:35:26.034  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:26.034  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:35:26.044  7014  7072 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:35:26.047   835  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:35:26.060  2083  2100 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
,09-13 16:35:26.064  2083  3549 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
09-13 16:35:26.066  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 16:35:26.076  2083  2099 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
,09-13 16:35:26.084  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 16:35:26.086  2083  3549 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
09-13 16:35:26.087  7014  7072 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
,09-13 16:35:26.092  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:35:26.093  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:35:26.095  7014  7072 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 16:35:26.096  7014  7072 I io.jxcore.node.ConnectionHelper: start: OK
09-13 16:35:26.098  7014  7072 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-13 16:35:26.098  7014  7072 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 16:35:26.099  7014  7072 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 16:35:26.104  7014  7072 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 16:35:26.104  7014  7072 V io.jxcore.node.ConnectivityMonitor: start: Already started
09-13 16:35:26.104  7014  7072 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:35:26.104  7014  7072 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 16:35:26.104  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 16:35:26.104  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:26.104  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:35:26.109  2083  2099 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
09-13 16:35:26.110  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:35:26.111  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,09-13 16:35:26.115  7014  7072 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 16:35:26.115  7014  7072 I io.jxcore.node.ConnectionHelper: start: OK
09-13 16:35:26.115  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:26.116  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.116  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:35:26.116  7014  7072 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2045dabf not in the list
09-13 16:35:26.116  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:26.116  7014  7072 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@351e858c not in the list
09-13 16:35:26.116  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:26.116  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.118  7014  7072 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 16:35:26.120  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:26.123  2083  3549 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
,09-13 16:35:26.132  7014  7072 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:35:26.132  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:35:26.132  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:35:26.132  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:35:26.132  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:35:26.132  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:26.132  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:35:26.132  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:35:26.133  2083  2100 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
09-13 16:35:26.134  7014  7072 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:26.134  7014  7072 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:35:26.137  7014  7014 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:35:26.139  7014  7072 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:35:26.139  7014  7072 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 16:35:26.139  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 16:35:26.139  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:26.139  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:35:26.142  7014  7014 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:35:26.145  2083  3550 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
09-13 16:35:26.146  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:35:26.147  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:35:26.148  7014  7072 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-13 16:35:26.150  7014  7072 I io.jxcore.node.ConnectionHelper: start: OK
09-13 16:35:26.150  7014  7072 I io.jxcore.node.ConnectionHelper: stop: Stopping only listening for advertisements
09-13 16:35:26.151  7014  7072 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 16:35:26.151  7014  7072 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
09-13 16:35:26.156  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:26.156  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.156  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:35:26.156  7014  7072 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2045dabf not in the list
09-13 16:35:26.156  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:26.156  7014  7072 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@351e858c not in the list
09-13 16:35:26.156  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:26.156  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.158  7014  7072 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
09-13 16:35:26.158  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:26.158  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.158  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.158  7014  7072 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2045dabf not in the list
09-13 16:35:26.158  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:26.158  7014  7072 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@351e858c not in the list
09-13 16:35:26.158  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:26.158  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.158  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.160  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 16:35:26.160  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:26.160  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.160  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.160  7014  7072 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2045dabf not in the list
09-13 16:35:26.160  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:26.160  7014  7072 E org.thal,iproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@351e858c not in the list
09-13 16:35:26.160  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:26.160  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.160  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.161  7014  7072 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
09-13 16:35:26.161  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:26.161  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.161  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.161  7014  7072 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2045dabf not in the list
09-13 16:35:26.161  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:26.162  7014  7072 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@351e858c not in the list
09-13 16:35:26.162  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:26.162  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.162  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.163  7014  7072 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
09-13 16:35:26.163  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:26.163  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.163  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.163  7014  7072 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2045dabf not in the list
09-13 16:35:26.163  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:26.163  7014  7072 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@351e858c not in the list
09-13 16:35:26.163  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:26.163  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.163  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.164  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 16:35:26.169  7014  7072 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:35:26.169  7014  7072 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:35:26.170  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 16:35:26.170  7014  7072 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:35:26.170  7014  7072 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:35:26.171  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
09-13 16:35:26.171  7014  7072 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:35:26.171  7014  7072 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
09-13 16:35:26.171  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:26.171  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.171  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.171  7014  7072 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2045dabf not in the list
09-13 16:35:26.171  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:26.171  7014  7072 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@351e858c not in the list
09-13 16:35:26.172  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:26.172  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.172  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.173  7014  7072 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:35:26.173  7014  7072 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 16:35:26.173  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
09-13 16:35:26.186  7014  7072 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:35:26.186  7014  7072 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
09-13 16:35:26.186  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
09-13 16:35:26.186  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
09-13 16:35:26.187  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
09-13 16:35:26.187  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
09-13 16:35:26.187  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
09-13 16:35:26.187  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
09-13 16:35:26.187  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
09-13 16:35:26.187  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
09-13 16:35:26.187  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
09-13 16:35:26.187  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
09-13 16:35:26.187  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
09-13 16:35:26.187  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
09-13 16:35:26.188  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
09-13 16:35:26.188  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
09-13 16:35:26.188  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
09-13 16:35:26.188  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
09-13 16:35:26.188  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
09-13 16:35:26.188  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
09-13 16:35:26.188  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
09-13 16:35:26.188  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
09-13 16:35:26.188  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
09-13 16:35:26.188  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
09-13 16:35:26.188  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
09-13 16:35:26.188  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
09-13 16:35:26.188  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
09-13 16:35:26.188  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
09-13 16:35:26.188  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
09-13 16:35:26.188  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
09-13 16:35:26.188  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
09-13 16:35:26.188  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
09-13 16:35:26.188  7014  7072 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
09-13 16:35:26.188  7014  7072 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:35:26.189  7014  7072 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
09-13 16:35:26.189  7014  7072 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:35:26.189  7014  7072 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:35:26.189  7014  7072 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
09-13 16:35:26.189  7014  7072 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:35:26.189  7014  7072 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
09-13 16:35:26.189  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
09-13 16:35:26.195  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
09-13 16:35:26.196  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
09-13 16:35:26.196  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,09-13 16:35:26.208  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
09-13 16:35:26.208  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
09-13 16:35:26.209  7014  7072 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
09-13 16:35:26.209  7014  7072 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
09-13 16:35:26.209  7014  7072 E io.jxcore.node.ConnectionHelper: connect: Callback is null
09-13 16:35:26.209  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:26.209  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.209  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.210  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
09-13 16:35:26.210  7014  7116 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 928)
09-13 16:35:26.211  7014  7072 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2045dabf not in the list
09-13 16:35:26.211  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:26.211  7014  7072 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@351e858c not in the list
09-13 16:35:26.211  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:26.211  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.211  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.213  7014  7072 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
09-13 16:35:26.214  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:26.214  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.214  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.214  7014  7072 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2045dabf not in the list
09-13 16:35:26.214  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:26.214  7014  7072 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@351e858c not in the list
09-13 16:35:26.214  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:26.214  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.214  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.214  7014  7117 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 928
09-13 16:35:26.215  7014  7072 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
09-13 16:35:26.216  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:26.216  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.216  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.216  7014  7072 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2045dabf not in the list
09-13 16:35:26.216  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:26.216  7014  7072 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@351e858c not in the list
09-13 16:35:26.216  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:26.216  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.216  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.218  7014  7072 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
09-13 16:35:26.218  7014  7072 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
09-13 16:35:26.219  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 16:35:26.219  7014  7072 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
09-13 16:35:26.219  7014  7072 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 16:35:26.219  7014  7072 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
09-13 16:35:26.219  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 16:35:26.219  7014  7072 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
09-13 16:35:26.219  7014  7072 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
09-13 16:35:26.219  7014  7072 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
09-13 16:35:26.219  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 16:35:26.219  7014  7072 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
09-13 16:35:26.219  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:26.219  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.219  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.219  7014  7072 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2045dabf not in the list
09-13 16:35:26.219  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:26.219  7014  7072 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@351e858c not in the list
09-13 16:35:26.219  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:26.219  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.220  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.220  7014  7072 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
09-13 16:35:26.222  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:26.224  2083  3549 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
09-13 16:35:26.225  7014  7072 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:35:26.225  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:35:26.225  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:35:26.225  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:35:26.225  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:35:26.225  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:26.225  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:35:26.225  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:35:26.226  2083  2100 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
09-13 16:35:26.227  7014  7072 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:26.227  7014  7072 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:35:26.227  7014  7072 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:35:26.227  7014  7072 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 16:35:26.227  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 16:35:26.227  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:26.227  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:35:26.231  7014  7014 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:35:26.234  7014  7014 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:35:26.235  2083  3550 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
09-13 16:35:26.236  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:35:26.236  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:35:26.238  7014  7072 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,09-13 16:35:26.239  7014  7072 I io.jxcore.node.ConnectionHelper: start: OK
09-13 16:35:26.240  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:26.240  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.240  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:35:26.240  7014  7072 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2045dabf not in the list
09-13 16:35:26.240  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:26.240  7014  7072 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@351e858c not in the list
09-13 16:35:26.240  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:26.240  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.244  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:26.244  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.244  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.244  7014  7072 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2045dabf not in the list
09-13 16:35:26.244  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:26.244  7014  7072 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@351e858c not in the list
09-13 16:35:26.244  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:26.244  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.244  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.247  7014  7072 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:35:26.247  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:26.248  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 16:35:26.250  7014  7072 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,09-13 16:35:26.252  7014  7072 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:35:26.252  7014  7014 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:35:26.252  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:35:26.252  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
09-13 16:35:26.253  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:26.253  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:35:26.254  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:35:26.254  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:35:26.254  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.254  7014  7072 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:35:26.254  7014  7072 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2045dabf not in the list
09-13 16:35:26.254  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:26.254  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
09-13 16:35:26.254  7014  7014 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
09-13 16:35:26.254  7014  7120 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:35:26.254  7014  7120 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:35:26.255  7014  7014 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:35:26.256  7014  7072 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
09-13 16:35:26.256  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
09-13 16:35:26.256  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
09-13 16:35:26.257  2083  2099 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
09-13 16:35:26.260  7014  7072 D BluetoothLeScanner: could not find callback wrapper
09-13 16:35:26.260  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
09-13 16:35:26.260  7014  7072 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
09-13 16:35:26.260  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.260  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.263  7014  7072 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,09-13 16:35:26.263  7014  7072 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@351e858c not in the list
09-13 16:35:26.263  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:26.263  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.263  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.263  7014  7014 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:35:26.264  7014  7014 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
09-13 16:35:26.264  7014  7014 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
09-13 16:35:26.264  7014  7072 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
09-13 16:35:26.264  7014  7072 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
09-13 16:35:26.265  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
09-13 16:35:26.268  7014  7072 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:35:26.268  7014  7072 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
09-13 16:35:26.272  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:26.273  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.273  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.273  7014  7072 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2045dabf not in the list
09-13 16:35:26.273  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:26.273  7014  7072 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@351e858c not in the list
09-13 16:35:26.273  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:26.273  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.273  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.275   835  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,09-13 16:35:26.275   835  2089 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:35:26.277   835  1895 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:35:26.278  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:26.278  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.278  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.278  7014  7072 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2045dabf not in the list
09-13 16:35:26.278  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:26.278  7014  7072 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@351e858c not in the list
09-13 16:35:26.278  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:26.278  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.278  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.279  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:26.279  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.279  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.279  7014  7072 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2045dabf not in the list
09-13 16:35:26.279  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:26.279  7014  7072 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@351e858c not in the list
09-13 16:35:26.279  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:26.279  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:26.280  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:26.281  7014  7072 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
09-13 16:35:26.281  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 16:35:26.281  7014  7072 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
09-13 16:35:26.281  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
09-13 16:35:26.281  7014  7072 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
09-13 16:35:26.281  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
09-13 16:35:26.283  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
09-13 16:35:26.283  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
09-13 16:35:26.284  7014  7072 I io.jxcore.node.ConnectionMode,l: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
09-13 16:35:26.284  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 16:35:26.284  7014  7072 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
09-13 16:35:26.284  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
09-13 16:35:26.284  7014  7072 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
09-13 16:35:26.284  7014  7072 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
09-13 16:35:26.285  7014  7072 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
09-13 16:35:26.285  7014  7072 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
09-13 16:35:26.285  7014  7072 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
09-13 16:35:26.285  7014  7072 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
09-13 16:35:26.285  7014  7072 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
09-13 16:35:26.286  7014  7072 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
09-13 16:35:26.292  7014  7121 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
09-13 16:35:26.293  7014  7121 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 16:35:26.349  7014  7116 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
09-13 16:35:26.349  7014  7116 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,09-13 16:35:26.374  2083  3549 D BTIF_SOCK: service_uuid: fa87c0d0-afac-11de-8a39-0800200c9a66
,09-13 16:35:26.377  2083  3549 I bt-btif : BTA_JvStartDiscovery
09-13 16:35:26.383  2083  3549 D LGBluetoothServiceAdapter: [BTUI] connectSocket FD=87 mFd=85
09-13 16:35:26.764  7014  7014 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,09-13 16:35:26.795  7014  7129 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-13 16:35:26.795  7014  7129 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-13 16:35:26.796  7014  7129 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-13 16:35:26.796  7014  7129 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
,09-13 16:35:26.797   279  1061 E BandwidthController: [LG DATA] No such appUid: 10030
09-13 16:35:26.798   279  1061 D DnsProxyListener: App 10030 tries DNS query. Accept family:0 protocol:0
09-13 16:35:26.798   279  7131 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=100; mark=917604
09-13 16:35:26.798   279  7131 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=1024; ai_family=0
09-13 16:35:26.798   279  7131 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=local, netid=0; mark=0
09-13 16:35:26.798   279  7131 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-13 16:35:26.799  7014  7129 I System.out: propertyValue:false
09-13 16:35:26.801  7014  7121 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
09-13 16:35:26.801  7014  7121 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:35:26.801  7014  7121 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:35:26.801  7014  7121 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:35:26.801  7014  7121 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-13 16:35:26.803  7014  7129 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
09-13 16:35:26.803  7014  7129 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:35:26.803  7014  7129 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:35:26.803  7014  7129 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:35:26.803  7014  7129 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 16:35:26.805  7014  7133 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 981, name: OutgoingSocketThread/Receiver)
09-13 16:35:26.806  7014  7133 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 981, thread name: OutgoingSocketThread/Receiver)
09-13 16:35:26.806  7014  7133 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 16:35:26.806  7014  7133 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 981, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 16:35:26.808  7014  7132 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 980, name: OutgoingSocketThread/Sender)
,09-13 16:35:26.811  7014  7134 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 982, name: IncomingSocketThread/Sender)
09-13 16:35:26.812  7014  7135 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 983, name: IncomingSocketThread/Receiver)
09-13 16:35:26.813  7014  7135 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 983, thread name: IncomingSocketThread/Receiver)
09-13 16:35:26.813  7014  7135 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 16:35:26.813  7014  7135 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 983, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 16:35:27.300  7014  7072 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
09-13 16:35:27.301  7014  7072 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
09-13 16:35:27.303  7014  7072 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@69ff53a Bundle[{}]
09-13 16:35:27.304  7014  7072 I io.jxcore.node.LifeCycleMonitor: start: OK
,09-13 16:35:27.312  7014  7072 I io.jxcore.node.LifeCycleMonitor: stop: OK
09-13 16:35:27.313  7014  7072 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
09-13 16:35:27.314  7014  7072 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
09-13 16:35:27.314  7014  7072 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
09-13 16:35:27.315  7014  7072 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
09-13 16:35:27.326  7014  7136 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
09-13 16:35:27.326  7014  7136 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,09-13 16:35:27.830  7014  7138 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-13 16:35:27.831  7014  7138 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-13 16:35:27.835  7014  7136 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
09-13 16:35:27.835  7014  7136 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:35:27.835  7014  7136 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:35:27.835  7014  7136 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:35:27.835  7014  7136 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
09-13 16:35:27.837  7014  7138 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
09-13 16:35:27.837  7014  7138 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
09-13 16:35:27.837  7014  7138 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:35:27.837  7014  7138 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:35:27.837  7014  7138 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
09-13 16:35:27.840  7014  7141 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 995, name: OutgoingSocketThread/Receiver)
09-13 16:35:27.841  7014  7141 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 995, thread name: OutgoingSocketThread/Receiver)
09-13 16:35:27.841  7014  7141 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
09-13 16:35:27.841  7014  7141 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 995, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
09-13 16:35:27.844  7014  7140 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 994, name: OutgoingSocketThread/Sender)
,09-13 16:35:27.849  7014  7142 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 996, name: IncomingSocketThread/Sender)
09-13 16:35:27.850  7014  7143 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 997, name: IncomingSocketThread/Receiver)
09-13 16:35:27.850  7014  7143 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 997, thread name: IncomingSocketThread/Receiver)
09-13 16:35:27.850  7014  7143 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
09-13 16:35:27.850  7014  7143 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 997, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
09-13 16:35:28.335  7014  7072 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1006)
,09-13 16:35:28.339  7014  7072 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
09-13 16:35:28.339  7014  7072 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 1007)
09-13 16:35:28.343  7014  7072 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
09-13 16:35:28.343  7014  7072 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12895742 added. We now have 3 listener(s)
09-13 16:35:28.343   835  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:35:28.346   295   358 I ThermalEngine: Sensor:pa_therm0:33000 mC
09-13 16:35:28.346  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:95:C7:87:85:54"
09-13 16:35:28.347  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
09-13 16:35:28.347  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
09-13 16:35:28.347  7014  7072 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
09-13 16:35:28.347  7014  7072 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c1c7353 added. We now have 3 listener(s)
09-13 16:35:28.347  7014  7072 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
09-13 16:35:28.348  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
09-13 16:35:28.352  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,09-13 16:35:28.357  2083  3550 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
09-13 16:35:28.358  7014  7072 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
09-13 16:35:28.358  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
09-13 16:35:28.358  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
09-13 16:35:28.358  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
09-13 16:35:28.358  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
09-13 16:35:28.358  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:28.358  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
09-13 16:35:28.358  7014  7072 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
09-13 16:35:28.359  2083  3549 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
09-13 16:35:28.361  7014  7072 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
09-13 16:35:28.361  7014  7072 D io.jxcore.node.ConnectivityMonitor: start: OK
09-13 16:35:28.363  7014  7014 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,09-13 16:35:28.367  7014  7014 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
09-13 16:35:28.368  2083  3550 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
09-13 16:35:28.370  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:28.370  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:28.370  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:35:28.370  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
09-13 16:35:28.370  7014  7072 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12895742 removed from the list
09-13 16:35:28.370  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:28.371  7014  7072 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c1c7353 removed from the list
09-13 16:35:28.371  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:28.371  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:28.373  7014  7072 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:35:28.373  7014  7072 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 16:35:28.373  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 16:35:28.373  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:28.373  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:35:28.377  7014  7072 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,09-13 16:35:28.380   835  1919 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:35:28.383  2083  3550 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
09-13 16:35:28.385  2083  2099 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
09-13 16:35:28.386  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
09-13 16:35:28.386  2083  3549 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
09-13 16:35:28.387  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
09-13 16:35:28.388  2083  2099 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
09-13 16:35:28.389  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,09-13 16:35:28.392  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:28.394  7014  7072 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 16:35:31.398  7014  7072 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 16:35:31.398  7014  7072 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,09-13 16:35:31.417  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:31.417  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:31.417  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:31.417  7014  7072 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12895742 not in the list
09-13 16:35:31.417  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:31.417  7014  7072 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c1c7353 not in the list
09-13 16:35:31.417  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:31.417  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:31.417  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:31.418  7014  7072 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:35:31.419  7014  7072 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
09-13 16:35:31.419  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
,09-13 16:35:31.424  7014  7072 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
09-13 16:35:31.424  7014  7072 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
09-13 16:35:31.425  7014  7072 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
09-13 16:35:31.425  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:31.428  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
09-13 16:35:31.428  7014  7072 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
09-13 16:35:31.428  7014  7072 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
09-13 16:35:31.429  7014  7014 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
09-13 16:35:31.430  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
09-13 16:35:31.431  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
09-13 16:35:31.431  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:31.431  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:35:31.437  2083  3550 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
,09-13 16:35:31.441  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:35:31.442  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
09-13 16:35:31.443   835  2089 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
09-13 16:35:31.445  7014  7072 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 16:35:31.445  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:31.445  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
09-13 16:35:31.446  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
09-13 16:35:31.446  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
09-13 16:35:31.446  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:31.446  7014  7072 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
09-13 16:35:31.446  7014  7145 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
09-13 16:35:31.448  2083  2099 I bt-btif : BTA_JvCreateRecordByUser
09-13 16:35:31.448  2083  3611 I bt-btif : BTA_JvRfcommStartServer
09-13 16:35:31.448  2083  2099 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=88 mFd=87
09-13 16:35:31.449  7014  7014 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,09-13 16:35:31.453  7014  7072 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12895742 not in the list
09-13 16:35:31.453  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:31.453  7014  7072 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c1c7353 not in the list
09-13 16:35:31.453  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:31.454  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:31.454  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:31.455  7014  7072 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:35:31.455  7014  7072 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
09-13 16:35:31.455  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
09-13 16:35:31.455  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
09-13 16:35:31.455  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
09-13 16:35:31.456  2083  3720 I bt-btif : BTA_JvDeleteRecord
09-13 16:35:31.456  2083  3720 I bt-btif : BTA_JvRfcommStopServer
09-13 16:35:31.457  7014  7145 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
09-13 16:35:31.457  7014  7145 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
09-13 16:35:31.457  7014  7145 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
09-13 16:35:31.457  7014  7014 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
09-13 16:35:31.470  2083  3550 D BluetoothAdapterService(355781602): getState() - mAdapterProperties: com.android.bluetooth.btservice.AdapterProperties@27b08f48
,09-13 16:35:31.474  7014  7072 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
09-13 16:35:31.475  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:31.477  7014  7072 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
09-13 16:35:31.522  2083  3611 W bt-sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
09-13 16:35:31.522  2083  3611 E bt-btif : DISCOVERY_COMP_EVT slot id:3, failed to find channle,                                       status:1, scn:0
,09-13 16:35:31.525  2083  3720 W bt-btif : invalid rfc slot id: 3
09-13 16:35:31.525  7014  7116 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 928)
09-13 16:35:32.411   835  1290 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1b20301d type 2 when 214860 android} when 214860
,09-13 16:35:33.351   295   358 I ThermalEngine: Sensor:pa_therm0:33000 mC
,09-13 16:35:34.477  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:34.477  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:34.478  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:34.478  7014  7072 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12895742 not in the list
09-13 16:35:34.478  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:34.478  7014  7072 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c1c7353 not in the list
09-13 16:35:34.478  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:34.478  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:34.478  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:34.479  7014  7072 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
09-13 16:35:34.479  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:34.479  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:34.479  7014  7072 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12895742 not in the list
09-13 16:35:34.479  7014  7072 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
09-13 16:35:34.479  7014  7072 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3c1c7353 not in the list
09-13 16:35:34.479  7014  7072 D io.jxcore.node.ConnectivityMonitor: stop
09-13 16:35:34.479  7014  7072 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
09-13 16:35:34.479  7014  7072 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
09-13 16:35:34.480  7014  7072 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
09-13 16:35:34.480  7014  7072 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
09-13 16:35:34.481  7014  7072 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
,09-13 16:35:34.481  7014  7072 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
09-13 16:35:34.481  7014  7072 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
09-13 16:35:34.481  7014  7072 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,09-13 16:35:34.502  7014  7147 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1026, name: My test thread name)
,09-13 16:35:36.500  7014  7072 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 1026
09-13 16:35:36.501  7014  7072 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 1026, name: My test thread name)
,09-13 16:35:36.505  7014  7148 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1027, name: My test thread name)
09-13 16:35:36.505  7014  7148 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 1027, thread name: My test thread name)
09-13 16:35:36.505  7014  7148 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1027, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
09-13 16:35:36.508  7014  7072 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
09-13 16:35:36.512  7014  7149 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 1031, name: My test thread name)
09-13 16:35:36.513  7014  7149 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 1031, thread name: My test thread name): Test exception.
09-13 16:35:36.513  7014  7149 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1031, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
09-13 16:35:36.516  7014  7072 I jxcore-log: Total number of executed tests:  76
09-13 16:35:36.516  7014  7072 I jxcore-log: 
,09-13 16:35:36.519  7014  7072 I jxcore-log: Number of passed tests:  76
09-13 16:35:36.519  7014  7072 I jxcore-log: 
09-13 16:35:36.519  7014  7072 I jxcore-log: Number of failed tests:  0
09-13 16:35:36.519  7014  7072 I jxcore-log: 
09-13 16:35:36.521  7014  7072 I jxcore-log: Number of ignored tests:  0
09-13 16:35:36.521  7014  7072 I jxcore-log: 
09-13 16:35:36.521  7014  7072 I jxcore-log: Total duration:  10600
09-13 16:35:36.521  7014  7072 I jxcore-log: 
09-13 16:35:36.523  7014  7072 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
09-13 16:35:36.523  7014  7072 I jxcore-log: 
09-13 16:35:36.524  7014  7072 I jxcore-log: My device name is: LGE-LG-D722
09-13 16:35:36.524  7014  7072 I jxcore-log: 
09-13 16:35:36.529  7014  7072 I jxcore-log: WARN testUtils: myNameCallback not set!
09-13 16:35:36.529  7014  7072 I jxcore-log: 
,09-13 16:35:36.543  7014  7072 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:35:36.543  7014  7072 I jxcore-log: 
09-13 16:35:36.544  7014  7072 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:35:36.544  7014  7072 I jxcore-log: 
09-13 16:35:36.545  7014  7072 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:35:36.545  7014  7072 I jxcore-log: 
,09-13 16:35:36.558  7014  7072 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:35:36.558  7014  7072 I jxcore-log: 
09-13 16:35:36.563  7014  7072 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:35:36.563  7014  7072 I jxcore-log: 
09-13 16:35:36.565  7014  7072 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
09-13 16:35:36.565  7014  7072 I jxcore-log: 
,09-13 16:35:36.569  7014  7072 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
09-13 16:35:36.569  7014  7072 I jxcore-log: 
09-13 16:35:36.579  7014  7147 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 1026, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,09-13 16:35:37.011  7150  7150 D AndroidRuntime: 
09-13 16:35:37.011  7150  7150 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,09-13 16:35:37.018  7150  7150 D AndroidRuntime: CheckJNI is OFF
09-13 16:35:37.307  7150  7150 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,09-13 16:35:37.344   835   972 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=-1: uninstall pkg
,09-13 16:35:37.347   835   972 I ActivityManager: Killing 7014:com.test.thalitest/u0a30 (adj 0): stop com.test.thalitest
09-13 16:35:37.393   835  1919 I WindowState: WIN DEATH: Window{28c51d1b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,09-13 16:35:37.401   835  1919 D InputDispatcher: Focus left window: Window{28c51d1b u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 16:35:37.401   835  1919 D InputDispatcher: Window went away: Window{28c51d1b u0 com.test.thalitest/com.test.thalitest.MainActivity}
09-13 16:35:37.466   835   972 I ActivityManager:   Force finishing activity ActivityRecord{13aa4e04 u0 com.test.thalitest/.MainActivity t259}
,09-13 16:35:37.469   835  1067 W PackageSettings: Skipping PackageSetting{27876abe com.example.hello/10317} due to missing metadata
,09-13 16:35:37.531   835  1902 W ActivityManager: Spurious death for ProcessRecord{2ecb8292 7014:com.test.thalitest/u0a30}, curProc for 7014: null
09-13 16:35:37.531   835  1067 I ActivityManager: Force stopping com.test.thalitest appid=10030 user=0: pkg removed
09-13 16:35:37.534   835  1067 I ActivityManager:   Force finishing activity ActivityRecord{13aa4e04 u0 com.test.thalitest/.MainActivity t259 f}
09-13 16:35:37.534   835  1067 W ActivityManager: Duplicate finish request for ActivityRecord{13aa4e04 u0 com.test.thalitest/.MainActivity t259 f}
,09-13 16:35:37.627  1951  1951 I [LGHome]EVENT: [Launcher.java:5209:onStart()]onStart
,09-13 16:35:37.638  2031  2031 I art     : Explicit concurrent mark sweep GC freed 1882(115KB) AllocSpace objects, 0(0B) LOS objects, 39% free, 12MB/20MB, paused 2.342ms total 95.073ms
09-13 16:35:37.656  1914  1914 I QCNEJ   : |CORE| CNE- sendBrowserInfoList: browsers list size = 2
,09-13 16:35:37.656  1376  1376 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
09-13 16:35:37.666  3678  3678 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
,09-13 16:35:37.670  3390  3390 I art     : Explicit concurrent mark sweep GC freed 3792(193KB) AllocSpace objects, 0(0B) LOS objects, 24% free, 16MB/22MB, paused 1.575ms total 121.005ms
,09-13 16:35:37.678  1765  2414 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
09-13 16:35:37.695  1951  1951 I [LGHome]EVENT: [Launcher.java:776:onResume()]onResume
,09-13 16:35:37.700   835  1292 I InputReader: Reconfiguring input devices.  changes=0x00000010
09-13 16:35:37.702  3678  3678 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
09-13 16:35:37.702  3678  3678 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
09-13 16:35:37.702  3678  3678 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:1034)
09-13 16:35:37.703  3678  3678 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
09-13 16:35:37.703  3678  3678 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
09-13 16:35:37.703  3678  3678 W System.err: 	at android.os.Looper.loop(Looper.java:135)
09-13 16:35:37.704  3678  3678 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5376)
09-13 16:35:37.704  3678  3678 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
09-13 16:35:37.704  3678  3678 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
09-13 16:35:37.705  3678  3678 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:908)
09-13 16:35:37.705  3678  3678 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:703)
09-13 16:35:37.713   835   972 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=7182 uid=10021 gids={50021, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,09-13 16:35:37.737  1376  1376 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,09-13 16:35:37.768  1951  1951 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
,09-13 16:35:37.770  1951  1951 I [LGHome]EVENT: [Launcher.java:929:onResume()]onResume end
09-13 16:35:37.770  1951  1951 I Activity: Activity.onPostResume() called 
09-13 16:35:37.772  1376  1494 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-13 16:35:37.772  1376  1494 D KeyguardModel: createShortcutInfo...
09-13 16:35:37.775  1951  1951 I [LGHome]EVENT: [Launcher.java:986:onPause()]onPause
09-13 16:35:37.775  1376  1494 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-13 16:35:37.775  1376  1494 D KeyguardModel: createShortcutInfo...
09-13 16:35:37.778  1376  1494 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 16:35:37.779  1376  1494 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-13 16:35:37.781  1376  1494 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 16:35:37.781  1376  1494 D KeyguardModel: createShortcutInfo...
09-13 16:35:37.783  1376  1494 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 16:35:37.783  1376  1494 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,09-13 16:35:37.784  1376  1494 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-13 16:35:37.784  1376  1494 D KeyguardModel: createShortcutInfo...
09-13 16:35:37.787  1376  1494 W ResourceType: No package identifier when getting value for resource number 0x00000000
,09-13 16:35:37.787  1376  1494 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-13 16:35:37.789  1376  1494 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 16:35:37.789  1376  1494 D KeyguardModel: createShortcutInfo...
09-13 16:35:37.790  1951  7199 D WallpaperManager: suggestDesiredDimensions(1440, 1280) by package(com.lge.launcher2)
09-13 16:35:37.793   835  1034 D WindowManager: [PWM]1.notifyNavigationBarColor => mLastColorNavigationBar=0x0
09-13 16:35:37.793   835  1034 I SystemUI[Framework]: PhoneWindowManager.updateSystemUiVisibilityLw() :visibility=0x8600, pkg=com.lge.launcher2
09-13 16:35:37.794   835  1034 W PhoneWindowManagerEx: Call!!!getLGSystemUiVisibility. =0x0
09-13 16:35:37.794   835  1034 D StatusBarManagerServiceEx: setLGSystemUiVisibility(0x0)
09-13 16:35:37.794   835  1034 D StatusBarManagerServiceEx: manageNaviBtnDisableList userId=0 what=0x0 pkg=WindowManager.LayoutParams
09-13 16:35:37.794   835  1034 I SystemUI[Framework]: ==>disabledNaviBtn() what=0x0, token=android.os.Binder@bd4b004,  pkg=WindowManager.LayoutParams
09-13 16:35:37.794   835  1034 I SystemUI[Framework]: disableNaviBtn: mDisabledNaviBtn=0x0,  mDisableRecords.size=0
09-13 16:35:37.796   835   854 D InputDispatcher: Focus entered window: Window{3b3d977d u0 com.lge.launcher2/com.lge.launcher2.Launcher}
,09-13 16:35:37.816  1376  1376 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
09-13 16:35:37.816  1376  1376 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,09-13 16:35:37.816  1376  1376 I [SystemUI]NavigationThemeResource: notify navigation bar color(0x0)
09-13 16:35:37.816  1376  1376 I [SystemUI]NavigationThemeResource: NavigationKey Color is changed(BLACK -> WHITE_WITH_SHADOW)
09-13 16:35:37.816  1376  1376 I [SystemUI]NavigationThemeResource:  BarMode=4, Theme=WHITE, LightBackground=false (Transparent)
09-13 16:35:37.816  1376  1376 I [SystemUI]NavigationThemeResource: , Keyguard show=false, IME shown=false, Panel expanded=false
09-13 16:35:37.818  1376  1376 D KeyguardModel: handleShortcutListChanged...
09-13 16:35:37.824  1376  1494 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
09-13 16:35:37.824  1376  1494 D KeyguardModel: createShortcutInfo...
09-13 16:35:37.825  1951  1951 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 16:35:37.825  1951  1951 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:308:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
09-13 16:35:37.826  1951  1951 I [LGHome]LGPlusHomeDBManager: [LGPlusHomeDBManager.java:374:packageUpdate()]PackageUpdatedTask: 3
09-13 16:35:37.829  1376  1494 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
09-13 16:35:37.829  1376  1494 D KeyguardModel: createShortcutInfo...
,09-13 16:35:37.851  1951  1951 I [LGHome]EVENT: [Launcher.java:5220:onStop()]onStop
09-13 16:35:37.851  1951  1951 I [LGHome]EVENT: [Launcher.java:5704:onWindowFocusChanged()]onWindowFocusChanged() hasFocus true
,09-13 16:35:37.853  1951  1951 I PhoneWindow: [setNavigationBarColor] color=0x 0
09-13 16:35:37.854  1376  1494 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 16:35:37.854  1376  1494 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
09-13 16:35:37.856  1376  1494 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
09-13 16:35:37.856  1376  1494 D KeyguardModel: createShortcutInfo...
09-13 16:35:37.858  1376  1494 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 16:35:37.858  1376  1494 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
09-13 16:35:37.861  7182  7182 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
09-13 16:35:37.861  7182  7182 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
09-13 16:35:37.862  7182  7182 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
09-13 16:35:37.865  1376  1494 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
09-13 16:35:37.865  1376  1494 D KeyguardModel: createShortcutInfo...
,09-13 16:35:37.873  1376  1494 W ResourceType: No package identifier when getting value for resource number 0x00000000
09-13 16:35:37.873  1376  1494 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
09-13 16:35:37.875  1376  1494 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
09-13 16:35:37.875  1376  1494 D KeyguardModel: createShortcutInfo...
09-13 16:35:37.890  1376  1376 D KeyguardModel: handleShortcutListChanged...
,09-13 16:35:37.892   835   835 I art     : Explicit concurrent mark sweep GC freed 21153(1879KB) AllocSpace objects, 6(96KB) LOS objects, 33% free, 23MB/35MB, paused 4.030ms total 296.791ms
09-13 16:35:37.893   835  1067 I art     : WaitForGcToComplete blocked for 263.092ms for cause Explicit
,09-13 16:35:37.931   835   835 D administrator: Handling package changes for user 0
,09-13 16:35:37.947   835  1401 W InputMethodManagerService: setImeState(/sys/devices/virtual/input/lge_touch/ime_status): file does not exist
09-13 16:35:37.949   835  1401 W InputMethodManagerService: Got RemoteException sending setActive(false) notification to pid 7014 uid 10030
,09-13 16:35:38.011  1951  1951 W IInputConnectionWrapper: getTextBeforeCursor on inactive InputConnection
,09-13 16:35:38.014  1634  1634 E b       : Unable to connect to the editor to retrieve text... will retry later
09-13 16:35:38.015  1951  1951 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2b68052 time:223508
09-13 16:35:38.035   835  1036 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{22c3390e u0 com.lge.launcher2/.Launcher t258} time:223528
,09-13 16:35:38.067  1951  1951 I art     : Explicit concurrent mark sweep GC freed 3140(208KB) AllocSpace objects, 5(681KB) LOS objects, 39% free, 15MB/25MB, paused 1.182ms total 51.463ms
09-13 16:35:38.067  1951  1951 W IInputConnectionWrapper: getTextAfterCursor on inactive InputConnection
,09-13 16:35:38.101   835   835 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
09-13 16:35:38.102   835   835 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,09-13 16:35:38.108   835   835 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
09-13 16:35:38.114   835  1353 D TaskPersister: removeObsoleteFile: deleting file=259_task.xml
09-13 16:35:38.142   835  1067 I art     : Explicit concurrent mark sweep GC freed 6428(446KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 23MB/35MB, paused 7.848ms total 247.656ms
,09-13 16:35:38.155  7182  7182 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,09-13 16:35:38.178  7182  7182 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3516)[v:6.41.27]
,09-13 16:35:38.186   279  1059 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-13 16:35:38.206  2737  2737 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=0
,09-13 16:35:38.214  2737  2737 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
09-13 16:35:38.214   279  1059 I Netd    : M: Get netlink event, ifname: wlan0 action: 4
09-13 16:35:38.229   835  1311 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,09-13 16:35:38.280  1878  2896 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
,09-13 16:35:38.287  7150  7150 D AndroidRuntime: Shutting down VM
09-13 16:35:38.321   835  1310 D LGWifiP2pService: InactiveState{ when=-2ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:35:38.321   835  1310 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,09-13 16:35:38.335  2737  2737 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
,09-13 16:35:38.336   279  1066 D CommandListener: Clearing all IP addresses on wlan0
09-13 16:35:38.337   279  1059 I Netd    : M: Get netlink event, ifname: wlan0 action: 7
09-13 16:35:38.338   835  2926 D DhcpStateMachine: RunningState{ when=-2ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:35:38.347   835  1067 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7203 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
09-13 16:35:38.348  1860  1860 D LCardEmulationManager: getHceAppCount hostAppNum : 0
09-13 16:35:38.348  1860  1860 D LCardEmulationManager: getDefaultRoute
,09-13 16:35:38.354  1765  4392 V NativeCrypto: Read error: ssl=0xb049d800: I/O error during system call, Connection timed out
09-13 16:35:38.355   295   358 I ThermalEngine: Sensor:pa_therm0:33000 mC
09-13 16:35:38.374   279  1059 I Netd    : M: Get netlink event, ifname: wlan0 action: 10
09-13 16:35:38.374   279  1059 I Netd    : M: Get netlink event, ifname: wlan0 action: 7
09-13 16:35:38.375   835  1032 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
,09-13 16:35:38.375   835  1032 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-13 16:35:38.383   835  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
09-13 16:35:38.384   835  1318 D ConnectivityService: ignoring duplicate network state non-change
09-13 16:35:38.386   835  1032 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-13 16:35:38.386   835  1032 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
09-13 16:35:38.386   835   835 D WifiHS20: hidePasspointNotification off =false
09-13 16:35:38.386   835   835 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:35:38.386   835   835 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:35:38.386   835   835 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 16:35:38.388   835  1318 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,09-13 16:35:38.389   835   835 D WifiHS20: hidePasspointNotification off =false
09-13 16:35:38.389   835   835 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:35:38.389   835   835 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:35:38.389   835   835 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 16:35:38.400  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-13 16:35:38.401  1376  1376 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 16:35:38.401  1765  4392 V NativeCrypto: SSL shutdown failed: ssl=0xb049d800: I/O error during system call, Broken pipe
09-13 16:35:38.403   835  1032 D libc-netbsd: [getaddrinfo]: hostname=xxxxx; servname=(null); cache_mode=(null), netid=0; mark=0
09-13 16:35:38.403   835  1032 D libc-netbsd: [getaddrinfo]: ai_addrlen=0; ai_canonname=xxxxx; ai_flags=4; ai_family=0
,09-13 16:35:38.408  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-13 16:35:38.404 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-13 16:35:38.412  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-13 16:35:38.413  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-13 16:35:38.413  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-13 16:35:38.413 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-13 16:35:38.413  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-13 16:35:38.417  1765  4392 E GCM     : Wifi connection closed with errorCode 20
,09-13 16:35:38.418  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-13 16:35:38.419  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-13 16:35:38.419  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-13 16:35:38.419  1376  1376 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-13 16:35:38.420   835  1401 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10006
09-13 16:35:38.424   835  2923 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:35:38.424   835  2923 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4ms what=532488 arg1=10006 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:35:38.424   835  2923 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
09-13 16:35:38.426  1376  1376 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-13 16:35:38.426  1376  1376 I [SystemUI]QuickSettingsHandler: Remote
09-13 16:35:38.427  1376  1376 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 16:35:38.430  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-13 16:35:38.430  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-13 16:35:38.430  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-13 16:35:38.430  1376  1376 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-13 16:35:38.430  1376  1376 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-13 16:35:38.430  1376  1376 I [SystemUI]QuickSettingsHandler: Remote
,09-13 16:35:38.431  1878  1894 D WifiServiceExtension: isInternetCheckAvailable return false
09-13 16:35:38.433  1878  1893 D WifiServiceExtension: isInternetCheckAvailable return false
09-13 16:35:38.438   835  1311 E WifiStateMachine: WifiStateMachine: Leaving Connected state
09-13 16:35:38.444   835   970 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,09-13 16:35:38.450   835   835 D WifiHS20: hidePasspointNotification off =false
09-13 16:35:38.452  1376  1376 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 16:35:38.452  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-13 16:35:38.453  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-13 16:35:38.452 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-13 16:35:38.453  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-13 16:35:38.454   835   835 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:35:38.454   835   835 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:35:38.454   835   835 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
09-13 16:35:38.455  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-13 16:35:38.455  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-13 16:35:38.455  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-13 16:35:38.455  1376  1376 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-13 16:35:38.455  1376  1376 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-13 16:35:38.455  1376  1376 I [SystemUI]QuickSettingsHandler: Remote
09-13 16:35:38.457  1376  1376 I [SystemUI]StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
09-13 16:35:38.457  1914  1914 I QCNEJ   : |CORE| CNE received action Network/Wifi State Changed: android.net.wifi.STATE_CHANGE
09-13 16:35:38.458  1914  1914 I QCNEJ   : |CORE| sendWifiStatus - subType: 21 networkState: 4 softApState: 11 rssi=0 ssid= bssid=00:00:00:00:00:00 ipV4Addr= ifNameV4= ipAddrV6= ifNameV6= timeStamp:2016-09-13 16:35:38.458 DNS addrs= 0.0.0.0, 0.0.0.0, 
09-13 16:35:38.458  1914  1914 I QCNEJ   : |CORE| notifyRatConnectStatus ratType=1 status=4 ipV4Addr= ipV6Addr=
09-13 16:35:38.459   835   835 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:35:38.459   835   835 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:35:38.459   835   835 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,09-13 16:35:38.462  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-13 16:35:38.462  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-13 16:35:38.463  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-13 16:35:38.463  1376  1376 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at null
09-13 16:35:38.463  1376  1376 I [SystemUI]QuickSettingsHandler: Got action android.net.wifi.STATE_CHANGE at Quick
09-13 16:35:38.463  1376  1376 I [SystemUI]QuickSettingsHandler: Remote
09-13 16:35:38.464   835  1311 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
09-13 16:35:38.471   835   835 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 16:35:38.471   835   835 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
09-13 16:35:38.476   835   835 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
09-13 16:35:38.476   835   835 D WifiServerServiceExt: setSupplicantStateSCANNING
,09-13 16:35:38.481   835  1318 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
09-13 16:35:38.481   835  1318 D DSQN    : disableDataServiceNotify
09-13 16:35:38.481   835  1318 D DSQN    : stop dsqn bin
09-13 16:35:38.510   835   970 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,09-13 16:35:38.515  1951  1951 I [LGHome]EVENT: [LauncherModel.java:1142:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
09-13 16:35:38.540   835  1318 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
09-13 16:35:38.540   835  1318 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:35:38.540   835  1318 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
,09-13 16:35:38.541   835  1318 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
09-13 16:35:38.541   835  1318 D ConnectivityService:  sending notification for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:35:38.542   835  1318 D ConnectivityService: sending notification LOST for NetworkRequest [ id=3, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:35:38.542   835  1318 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
09-13 16:35:38.542   835  2923 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:35:38.542   835  2923 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
09-13 16:35:38.542   835  2923 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
09-13 16:35:38.543  1376  1731 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-13 16:35:38.544   835  1318 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.109/24,fe80::a239:f7ff:fe70:1280/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
09-13 16:35:38.544   835  1318 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
09-13 16:35:38.544   835  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 16:35:38.545  3390  3673 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
09-13 16:35:38.545   835  1318 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 16:35:38.545   835  1318 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
09-13 16:35:38.546  1914  1914 W QCNEJ   : |CORE| No family connected
09-13 16:35:38.547   835  1309 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 16:35:38.547   835  1035 D Tethering: MasterInitialState.processMessage what=3
09-13 16:35:38.547   835  1318 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
09-13 16:35:38.547   835  1035 D Tethering: MasterInitialState.processMessage what=3
09-13 16:35:38.548   835  1318 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:35:38.548   835  1318 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:35:38.548   835  1309 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
09-13 16:35:38.548   835  1311 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:35:38.548   835  1318 D NetworkManagementService: Removing idletimer
09-13 16:35:38.548   835  1311 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps],
09-13 16:35:38.548  1914  1914 W QCNEJ   : |CORE| No family connected
09-13 16:35:38.548  1914  1914 I QCNEJ   : |CORE| Got CONNECTIVITY_ACTION_IMMEDIATE on default nw
09-13 16:35:38.549   835  1318 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
09-13 16:35:38.550  1914  1914 I QCNEJ   : |CORE| sendDefaultNwMsg: default = -1
,09-13 16:35:38.558   835  2926 D DhcpStateMachine: StoppedState
09-13 16:35:38.560  1794  1794 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
09-13 16:35:38.561  1794  1794 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800&VTIMS&WAP Specifier: <-1>]
,09-13 16:35:38.586  1376  1376 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,09-13 16:35:38.603  1376  1376 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
,09-13 16:35:38.604  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-13 16:35:38.605  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-13 16:35:38.605  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-13 16:35:38.608  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-13 16:35:38.609  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-13 16:35:38.609  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-13 16:35:38.621  1376  1376 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
09-13 16:35:38.621  7182  7182 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,09-13 16:35:38.622  1376  1376 I [SystemUI]LGNetworkController: updateLGTelephonySignalStrength : !hasService()
09-13 16:35:38.625  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-13 16:35:38.625  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-13 16:35:38.625  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-13 16:35:38.626  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 1 connected={ } level=5 mobileLabel=Emergency calls only wifiLabel= emergencyOnly=true
09-13 16:35:38.627  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 2  mPhoneSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataSignalIconId=com.android.systemui:drawable/stat_sys_signal_bar5_null mDataTypeIconId=(null) mDataActivity=0 mLGNetworkController.mLGDataTypeIconId=(null) mLGNetworkController.mLGDataActivityIconId=(null)
09-13 16:35:38.627  1376  1376 I [SystemUI]StatusBar.NetworkController: refreshViews 3  mAirplaneMode=false mNoSimIconId=com.android.systemui:drawable/stat_sys_no_sim mWifiIconId=com.android.systemui:drawable/stat_sys_wifi_signal_null mWifiActivityIconId=com.android.systemui:drawable/stat_sys_wifi_inout
09-13 16:35:38.657   835   854 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7233 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
09-13 16:35:38.657   835   854 I ActivityManager: Killing 6600:com.android.gallery3d/u0a23 (adj 15): empty #11
,09-13 16:35:38.687   835   853 W libprocessgroup: failed to open /acct/uid_10023/pid_6600/cgroup.procs: No such file or directory

```
