#### Test 797510151e03ec5_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-12 16:32:00.064  1601  1601 I [SystemUI]Clock: called onTimeUpdated()
08-12 16:32:00.073  1601  1601 I LgeClockWidgetControlView: called onTimeUpdated()
08-12 16:32:00.074  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-12 16:32:00.077  1601  1601 I [SystemUI]DateView: called onTimeUpdated()
08-12 16:32:00.078  1601  1601 D KeyguardUpdateMonitor: handleTimeUpdate
,08-12 16:32:12.274  6755  6755 D AndroidRuntime: 
08-12 16:32:12.274  6755  6755 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-12 16:32:12.281  6755  6755 D AndroidRuntime: CheckJNI is OFF
08-12 16:32:12.483  6755  6755 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-12 16:32:12.494  1034  1940 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-12 16:32:12.511  1941  1957 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-12 16:32:12.516  1034  1940 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-12 16:32:12.518  1034  1940 D ActivityManager: setTaskToReturnTo : TaskRecord{8fa98ac #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 16:32:12.518  1034  1940 D ActivityManager: setTaskToReturnTo : TaskRecord{8fa98ac #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-12 16:32:12.520  1034  1940 D WindowStateEx: AppWindowTokenEx init.. 
08-12 16:32:12.520   349   369 E GBMv2   : DFP En is all cleared set to be enabled
08-12 16:32:12.549  1034  1940 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6770 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-12 16:32:12.551  6755  6755 D AndroidRuntime: Shutting down VM
08-12 16:32:12.605  1941  3973 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-12 16:32:12.605  1941  3973 D SplitWindowPolicy: topRunningActivity=ActivityInfo{7d7c477 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 16:32:12.606  1941  1956 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-12 16:32:12.606  1941  1956 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3fc518e4 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-12 16:32:12.677  6770  6770 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-12 16:32:12.778  6770  6770 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-12 16:32:12.787  6770  6770 I LibraryLoader: Loading: webviewchromium
08-12 16:32:12.791  6770  6770 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 1890-1895)
,08-12 16:32:12.792  6770  6770 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 16:32:12.823  6770  6770 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {79cf43d}
,08-12 16:32:12.825  6770  6770 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-12 16:32:12.825  6770  6770 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-12 16:32:12.837  6770  6770 I BrowserStartupController: Initializing chromium process, renderers=0
,08-12 16:32:12.839  6770  6770 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 16:32:12.851   330  1382 V AudioPolicyService: registerClient() client 0xb14b7d40, uid 10118
08-12 16:32:12.851  6770  6770 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-12 16:32:12.853  6770  6770 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,08-12 16:32:12.853  6770  6770 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-12 16:32:12.857  1034  1116 D BluetoothManagerService: Message: 20
08-12 16:32:12.857  1034  1116 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f900fd6:true
08-12 16:32:12.875  6770  6770 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-12 16:32:12.875  6770  6770 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-12 16:32:12.875  6770  6770 I Adreno-EGL: Build Date: 12/12/14 금
08-12 16:32:12.875  6770  6770 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-12 16:32:12.875  6770  6770 I Adreno-EGL: Remote Branch: 
08-12 16:32:12.875  6770  6770 I Adreno-EGL: Local Patches: 
08-12 16:32:12.875  6770  6770 I Adreno-EGL: Reconstruct Branch: 
,08-12 16:32:12.976  6770  6811 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-12 16:32:12.983  6770  6770 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-12 16:32:13.002  6770  6770 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 16:32:13.007  6770  6770 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-12 16:32:13.010  6770  6770 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-12 16:32:13.013  6770  6770 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-12 16:32:13.014  6770  6770 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-12 16:32:13.029  6770  6770 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-12 16:32:13.037  6770  6770 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-12 16:32:13.037  6770  6770 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-12 16:32:13.073  6770  6826 D OpenGLRenderer: Render dirty regions requested: true
08-12 16:32:13.073  6770  6826 I OpenGLRenderer: Initialized EGL, version 1.4
,08-12 16:32:13.080  6770  6826 D OpenGLRenderer: Enabling debug mode 0
08-12 16:32:13.092  6770  6770 D Atlas   : Validating map...
,08-12 16:32:13.097  1034  2044 D SplitWindow: check instance of lgWin Window{22be72e0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-12 16:32:13.103  1034  1094 W ActivityManager: Activity pause timeout for ActivityRecord{2e3f9975 u0 com.test.thalitest/.MainActivity t6}
,08-12 16:32:13.148  6770  6824 D LgDataFeature: LgDataFeature() Constructor: none
,08-12 16:32:13.148  6770  6824 D LgDataFeature: LgDataFeature() Constructor Done, null
08-12 16:32:13.289  1034  1575 I art     : Explicit concurrent mark sweep GC freed 28513(1313KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.280ms total 135.129ms
,08-12 16:32:13.370  1034  1117 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +766ms (total +848ms)
08-12 16:32:13.370  1034  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2e3f9975 u0 com.test.thalitest/.MainActivity t6} time:292474
,08-12 16:32:13.376  6770  6770 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2ea4cc30 time:292480
,08-12 16:32:13.487  6770  6770 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-12 16:32:13.487  6770  6770 I chromium: 
,08-12 16:32:13.525  6770  6770 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-12 16:32:13.599  6770  6824 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-12 16:32:13.599  6770  6824 I chromium: 
,08-12 16:32:13.744  6770  6836 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435060736
,08-12 16:32:13.749   349   371 E GBMv2   : DFP En is all cleared set to be enabled
08-12 16:32:13.749   349   371 E GBMv2   : Set value is all cleared set the max
08-12 16:32:13.749   349   371 I GBMv2   : DFP Enabled. Ignore VFP set
08-12 16:32:13.762  6770  6836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-12 16:32:13.762  6770  6836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-12 16:32:13.762  6770  6836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-12 16:32:13.762  6770  6836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-12 16:32:13.762  6770  6836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-12 16:32:13.763  6770  6836 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2b10d9f4 added. We now have 1 listener(s)
,08-12 16:32:13.776  1034  2050 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 16:32:13.780  6770  6836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,08-12 16:32:13.782  6770  6836 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-12 16:32:13.787  6770  6836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-12 16:32:13.788  6770  6836 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-12 16:32:13.797  6770  6836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-12 16:32:13.797  6770  6836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-12 16:32:13.797  6770  6836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-12 16:32:13.797  6770  6836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-12 16:32:13.797  6770  6836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-12 16:32:13.797  6770  6836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-12 16:32:13.797  6770  6836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-12 16:32:13.797  6770  6836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-12 16:32:13.797  6770  6836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-12 16:32:13.797  6770  6836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-12 16:32:13.797  6770  6836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-12 16:32:13.797  6770  6836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-12 16:32:13.797  6770  6836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-12 16:32:13.797  6770  6836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-12 16:32:13.797  6770  6836 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26217163 added. We now have 1 listener(s)
08-12 16:32:13.798  6770  6836 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-12 16:32:13.803  1034  1543 D WifiService: New client listening to asynchronous messages
08-12 16:32:13.808  6770  6836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-12 16:32:13.810  6770  6836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-12 16:32:13.810  6770  6836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-12 16:32:13.810  6770  6836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-12 16:32:13.810  6770  6836 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-12 16:32:13.815  6770  6836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-12 16:32:13.816  1034  1976 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-12 16:32:13.819  6770  6836 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-12 16:32:13.833  6770  6836 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-12 16:32:13.836  6770  6836 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 16:32:13.836  6770  6836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 16:32:13.836  6770  6836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 16:32:13.836  6770  6836 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 16:32:13.836  6770  6836 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 16:32:13.836  6770  6836 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 16:32:13.836  6770  6836 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 16:32:13.836  6770  6836 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 16:32:13.836  6770  6836 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-12 16:32:13.836  6770  6836 D io.jxcore.node.ConnectivityMonitor: start: OK
08-12 16:32:13.840  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 16:32:13.841  6770  6836 I io.jxcore.node.LifeCycleMonitor: start: OK
08-12 16:32:13.842  6770  6770 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-12 16:32:13.900  6770  6770 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-12 16:32:15.220  6770  6839 W jxcore-log: Initializing JXcore engine
08-12 16:32:15.220  6770  6839 W jxcore-log: JXcore engine is ready
,08-12 16:32:15.294  6839  6839 W Thread-781: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10247]" dev="sockfs" ino=10247 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-12 16:32:15.294  6839  6839 W Thread-781: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-12 16:32:15.294  6839  6839 W Thread-781: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9980]" dev="sockfs" ino=9980 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-12 16:32:15.294  6839  6839 W Thread-781: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-12 16:32:15.294  6839  6839 W Thread-781: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[30590]" dev="sockfs" ino=30590 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-12 16:32:15.324  6770  6839 W jxcore-log: Starting JXcore engine
,08-12 16:32:15.482  6770  6839 W jxcore-log: Platform android
08-12 16:32:15.482  6770  6839 W jxcore-log: 
08-12 16:32:15.482  6770  6839 W jxcore-log: Process ARCH arm
08-12 16:32:15.482  6770  6839 W jxcore-log: 
,08-12 16:32:15.933  6770  6839 I jxcore-log: JXcore Cordova bridge is ready!
08-12 16:32:15.933  6770  6839 I jxcore-log: 
08-12 16:32:15.933  6770  6839 W jxcore-log: JXcore engine is started
,08-12 16:32:15.942  6770  6836 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-12 16:32:15.944  6770  6770 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-12 16:32:29.560  1601  1601 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-12 16:32:29.560  1601  1601 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-12 16:32:29.572  1601  1601 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
08-12 16:32:29.572  1601  1601 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
,08-12 16:32:29.574  3875  4007 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-12 16:32:29.574  1941  2110 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
08-12 16:32:29.574  1941  2110 D LEDHandler: Battery Level Remaining: 100%
08-12 16:32:29.574  1941  2110 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
08-12 16:32:29.575  1034  1034 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-12 16:32:29.575  1034  1034 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-12 16:32:29.575  1034  1543 D WifiController: battery changed pluggedType: 2
08-12 16:32:29.575  1601  1601 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-12 16:32:29.586  6632  6632 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-12 16:32:31.621  6770  6839 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-12 16:32:31.621  6770  6839 I jxcore-log: 
,08-12 16:32:31.624  6770  6839 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-12 16:32:31.624  6770  6839 I jxcore-log: 
08-12 16:32:31.629  6770  6839 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-12 16:32:31.629  6770  6839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-12 16:32:31.629  6770  6839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-12 16:32:31.629  6770  6839 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-12 16:32:31.629  6770  6839 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-12 16:32:31.629  6770  6839 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-12 16:32:31.629  6770  6839 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-12 16:32:31.629  6770  6839 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-12 16:32:31.632  6770  6839 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-12 16:32:31.635  6770  6839 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-12 16:32:31.635  6770  6839 I jxcore-log: 
,08-12 16:32:31.637  6770  6839 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-12 16:32:31.637  6770  6839 I jxcore-log: 
,08-12 16:32:31.975  6770  6839 I jxcore-log: Unit Test app is loaded
08-12 16:32:31.975  6770  6839 I jxcore-log: 
,08-12 16:32:31.983  6770  6770 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
08-12 16:32:31.994  6770  6839 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-12 16:32:31.994  6770  6839 I jxcore-log: 
08-12 16:32:32.000  6770  6839 I jxcore-log: My device name is: LGE-LG-D855
08-12 16:32:32.000  6770  6839 I jxcore-log: 
,08-12 16:32:36.473  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-12 16:32:36.473  6770  6839 I jxcore-log: 
,08-12 16:32:37.697  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-12 16:32:37.697  6770  6839 I jxcore-log: 
,08-12 16:32:37.747  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js,
08-12 16:32:37.747  6770  6839 I jxcore-log: 
,08-12 16:32:40.394  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-12 16:32:40.394  6770  6839 I jxcore-log: 
,08-12 16:32:40.834  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
08-12 16:32:40.834  6770  6839 I jxcore-log: 
,08-12 16:32:40.846  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js
08-12 16:32:40.846  6770  6839 I jxcore-log: 
08-12 16:32:40.856  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
08-12 16:32:40.856  6770  6839 I jxcore-log: 
,08-12 16:32:40.890  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
08-12 16:32:40.890  6770  6839 I jxcore-log: 
,08-12 16:32:40.899  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
08-12 16:32:40.899  6770  6839 I jxcore-log: 
08-12 16:32:42.206  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
08-12 16:32:42.206  6770  6839 I jxcore-log: 
,08-12 16:32:42.232  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
08-12 16:32:42.232  6770  6839 I jxcore-log: 
,08-12 16:32:42.250  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
08-12 16:32:42.250  6770  6839 I jxcore-log: 
,08-12 16:32:42.265  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
08-12 16:32:42.265  6770  6839 I jxcore-log: 
08-12 16:32:42.359  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
08-12 16:32:42.359  6770  6839 I jxcore-log: 
,08-12 16:32:42.471  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
08-12 16:32:42.471  6770  6839 I jxcore-log: 
,08-12 16:32:42.487  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
08-12 16:32:42.487  6770  6839 I jxcore-log: 
08-12 16:32:42.808  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
08-12 16:32:42.808  6770  6839 I jxcore-log: 
,08-12 16:32:42.863  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
08-12 16:32:42.863  6770  6839 I jxcore-log: 
,08-12 16:32:42.874  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
08-12 16:32:42.874  6770  6839 I jxcore-log: 
08-12 16:32:42.885  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
08-12 16:32:42.885  6770  6839 I jxcore-log: 
,08-12 16:32:42.922  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js
08-12 16:32:42.922  6770  6839 I jxcore-log: 
,08-12 16:32:43.092  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js
08-12 16:32:43.092  6770  6839 I jxcore-log: 
,08-12 16:32:43.130  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js
08-12 16:32:43.130  6770  6839 I jxcore-log: 
,08-12 16:32:43.189  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js
08-12 16:32:43.189  6770  6839 I jxcore-log: 
,08-12 16:32:43.217  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
08-12 16:32:43.217  6770  6839 I jxcore-log: 
,08-12 16:32:43.255  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
08-12 16:32:43.255  6770  6839 I jxcore-log: 
,08-12 16:32:43.324  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
08-12 16:32:43.324  6770  6839 I jxcore-log: 
,08-12 16:32:43.339  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
08-12 16:32:43.339  6770  6839 I jxcore-log: 
,08-12 16:32:43.713  6770  6839 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
08-12 16:32:43.713  6770  6839 I jxcore-log: 
,08-12 16:32:43.731  6770  6839 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
08-12 16:32:43.735  6770  6839 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
08-12 16:32:43.735  6770  6839 I jxcore-log: 
,08-12 16:32:50.994  6770  6839 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-12 16:32:50.994  6770  6839 I jxcore-log: 
,08-12 16:32:51.364  6851  6851 D AndroidRuntime: 
08-12 16:32:51.364  6851  6851 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-12 16:32:51.369  6851  6851 D AndroidRuntime: CheckJNI is OFF
08-12 16:32:51.593  6851  6851 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-12 16:32:51.617  1034  1094 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
,08-12 16:32:51.621  1034  1094 I ActivityManager: Killing 6770:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-12 16:32:51.690  1034  1575 I WindowState: WIN DEATH: Window{22be72e0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 16:32:51.692  1034  1543 D WifiService: Client connection lost with reason: 4
08-12 16:32:51.699  1034  1575 D InputDispatcher: Window went away: Window{22be72e0 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-12 16:32:51.841  1034  1094 I ActivityManager:   Force finishing activity ActivityRecord{2e3f9975 u0 com.test.thalitest/.MainActivity t6}
,08-12 16:32:51.882   349   369 E GBMv2   : DFP En is all cleared set to be enabled
,08-12 16:32:51.890  1034  1122 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-12 16:32:51.897  1034  1122 I ActivityManager:   Force finishing activity ActivityRecord{2e3f9975 u0 com.test.thalitest/.MainActivity t6 f}
08-12 16:32:51.897  1034  1122 W ActivityManager: Duplicate finish request for ActivityRecord{2e3f9975 u0 com.test.thalitest/.MainActivity t6 f}
,08-12 16:32:51.944  4597  4597 I art     : Explicit concurrent mark sweep GC freed 476(32KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 585us total 39.426ms
08-12 16:32:51.945  1034  1940 W ActivityManager: Spurious death for ProcessRecord{17743136 6770:com.test.thalitest/u0a118}, curProc for 6770: null
,08-12 16:32:51.949  1941  1957 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-12 16:32:51.949  1941  1957 D SplitWindowPolicy: topRunningActivity=ActivityInfo{18d9414d co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-12 16:32:51.949  2032  2032 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-12 16:32:51.951  2032  2032 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-12 16:32:51.952  1941  3973 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-12 16:32:51.952  1941  3973 D SplitWindowPolicy: topRunningActivity=ActivityInfo{14f47402 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-12 16:32:51.958  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,08-12 16:32:51.959  2032  2128 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-12 16:32:51.974  2496  2607 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-12 16:32:51.975  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-12 16:32:51.977  3875  3875 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-12 16:32:51.978  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-12 16:32:51.979  1995  1995 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-12 16:32:51.980  3836  3836 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-12 16:32:51.991  1034  1456 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-12 16:32:52.022  1034  1049 V SIM_STK : Menu title from STK is T-Mobile
,08-12 16:32:52.035  6455  6455 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-12 16:32:52.037  4499  4499 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-12 16:32:52.038  4499  4499 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
,08-12 16:32:52.038  4499  4499 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-12 16:32:52.038  4499  4499 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-12 16:32:52.038  4499  4499 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-12 16:32:52.038  4499  4499 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-12 16:32:52.038  4499  4499 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-12 16:32:52.038  4499  4499 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-12 16:32:52.038  4499  4499 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-12 16:32:52.038  4499  4499 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-12 16:32:52.038  4499  4499 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-12 16:32:52.038  4499  4499 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-12 16:32:52.043  1904  1904 D ActionManagerService: notifyUserLog: 1000003
08-12 16:32:52.043  3836  4493 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-12 16:32:52.045  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-12 16:32:52.047  1816  1816 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-12 16:32:52.047  2032  2032 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-12 16:32:52.048  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-12 16:32:52.054  2032  2032 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-12 16:32:52.059  2032  2032 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-12 16:32:52.061  2187  2187 I ConfigService: onCreate
08-12 16:32:52.062  2187  2187 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,08-12 16:32:52.063  1904  1904 D ActionManagerService: notifyUserLog: 1000004
08-12 16:32:52.064  3836  4493 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-12 16:32:52.067  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-12 16:32:52.068  1816  1816 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-12 16:32:52.071  3836  4490 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 16:32:52.075  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-12 16:32:52.078  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
,08-12 16:32:52.084  2187  2187 I ConfigService: onBind returning update interface
08-12 16:32:52.093  2187  2187 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-12 16:32:52.093  2187  2187 I ConfigService: onBind returning config service
,08-12 16:32:52.097  1601  1665 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 16:32:52.097  1601  1665 D KeyguardModel: createShortcutInfo...
08-12 16:32:52.103  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-12 16:32:52.103  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262123
08-12 16:32:52.103  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-12 16:32:52.103  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-12 16:32:52.103  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-12 16:32:52.103  2032  2032 I GBoardWebViewUtils: , display: false
08-12 16:32:52.103  2032  2032 I GBoardWebViewUtils: , animation: false }
08-12 16:32:52.103  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-12 16:32:52.103  2032  2032 I GBoardWebViewUtils: , create_time: 1430832262287
08-12 16:32:52.103  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-12 16:32:52.103  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-12 16:32:52.103  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 16:32:52.103  2032  2032 I GBoardWebViewUtils: , display: false
08-12 16:32:52.103  2032  2032 I GBoardWebViewUtils: , animation: false }
08-12 16:32:52.103  2032  2032 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-12 16:32:52.103  2032  2032 I GBoardWebViewUtils: , create_time: 1471007226523
08-12 16:32:52.103  2032  2032 I GBoardWebViewUtils: , expire_time: 0
08-12 16:32:52.103  2032  2032 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-12 16:32:52.103  2032  2032 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-12 16:32:52.103  2032  2032 I GBoardWebViewUtils: , display: false
08-12 16:32:52.103  2032  2032 I GBoardWebViewUtils: , animation: false }
08-12 16:32:52.104  2187  2187 I ConfigService: onDestroy
08-12 16:32:52.108  1601  1665 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 16:32:52.108  1601  1665 D KeyguardModel: createShortcutInfo...
,08-12 16:32:52.110  1816  6885 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-12 16:32:52.116  1601  1665 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-12 16:32:52.116  1601  1665 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 16:32:52.116  1601  1665 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-12 16:32:52.117  1601  1665 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-12 16:32:52.118  1601  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 16:32:52.118  1601  1665 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 16:32:52.119  2032  6886 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-12 16:32:52.126  1868  1868 D SplitUIManager: split_name #11 / not available #0
08-12 16:32:52.127  1868  1868 D SplitUIService: removed split : 
08-12 16:32:52.129  1601  1665 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 16:32:52.129  1601  1665 D KeyguardModel: createShortcutInfo...
08-12 16:32:52.135  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 16:32:52.135  2032  2032 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-12 16:32:52.136  1601  1665 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-12 16:32:52.136  1601  1665 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-12 16:32:52.137  1601  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 16:32:52.137  1601  1665 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 16:32:52.137  1034  1994 V SIM_STK : Menu title from STK is T-Mobile
08-12 16:32:52.137  1034  1994 V SIM_STK : Menu title from STK is T-Mobile
08-12 16:32:52.138  1601  1665 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 16:32:52.138  1601  1665 D KeyguardModel: createShortcutInfo...
08-12 16:32:52.143  1601  1665 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 16:32:52.143  1601  1665 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-12 16:32:52.143  1601  1665 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-12 16:32:52.144  1601  1665 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-12 16:32:52.145  1601  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 16:32:52.145  1601  1665 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 16:32:52.146  1601  1665 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 16:32:52.146  1601  1665 D KeyguardModel: createShortcutInfo...
,08-12 16:32:52.161  5943  6894 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-12 16:32:52.175  1034  1034 I art     : Explicit concurrent mark sweep GC freed 12945(1006KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 2.525ms total 259.004ms
08-12 16:32:52.177  1034  1122 I art     : WaitForGcToComplete blocked for 103.327ms for cause Explicit
,08-12 16:32:52.182  1601  1601 D KeyguardModel: handleShortcutListChanged...
08-12 16:32:52.182  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-12 16:32:52.189  1601  1665 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-12 16:32:52.189  1601  1665 D KeyguardModel: createShortcutInfo...
,08-12 16:32:52.197  2032  2032 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-12 16:32:52.210  1034  2044 V SIM_STK : Menu title from STK is T-Mobile
,08-12 16:32:52.212  1034  2050 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-12 16:32:52.213  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-12 16:32:52.213  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-12 16:32:52.213  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-12 16:32:52.213  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-12 16:32:52.213  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-12 16:32:52.213  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 16:32:52.213  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-12 16:32:52.213  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-12 16:32:52.213  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-12 16:32:52.213  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-12 16:32:52.213  3875  3875 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-12 16:32:52.221  1601  1665 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-12 16:32:52.221  1601  1665 D KeyguardModel: createShortcutInfo...
08-12 16:32:52.223  1816  6898 I PeopleContactsSync: CP2 sync disabled
08-12 16:32:52.225  1601  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 16:32:52.225  1601  1665 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-12 16:32:52.225  6007  6007 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-12 16:32:52.230  1601  1665 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-12 16:32:52.230  1601  1665 D KeyguardModel: createShortcutInfo...
08-12 16:32:52.231  1601  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 16:32:52.231  1601  1665 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-12 16:32:52.232  1601  1665 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-12 16:32:52.232  1601  1665 D KeyguardModel: createShortcutInfo...
08-12 16:32:52.233  1601  1665 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-12 16:32:52.233  1601  1665 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-12 16:32:52.236  1601  1665 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-12 16:32:52.236  1601  1665 D KeyguardModel: createShortcutInfo...
08-12 16:32:52.244  1868  1868 D SplitUIManager: split_name #11 / not available #0
08-12 16:32:52.244  1868  1868 I SplitUIService: split app #11
08-12 16:32:52.244  1816  4769 I Icing   : doRemovePackageData com.test.thalitest
,08-12 16:32:52.247  1034  1092 W InputMethodInfo: Duplicated subtype definition found: , voice
08-12 16:32:52.250  1034  1034 D administrator: Handling package changes for user 0
08-12 16:32:52.261  6542  6542 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-12 16:32:52.262  1601  1601 D KeyguardModel: handleShortcutListChanged...
08-12 16:32:52.262  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-12 16:32:52.267  2365  6899 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-12 16:32:52.269  1816  6896 W GmsApplication: Using Auth Proxy for data requests.
08-12 16:32:52.273  1816  6896 W GmsApplication: Using Auth Proxy for data requests.
,08-12 16:32:52.278  1995  1995 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-12 16:32:52.278  1995  1995 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-12 16:32:52.280  1995  1995 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-12 16:32:52.287  6455  6455 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-12 16:32:52.315  1034  1702 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6901 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-12 16:32:52.335  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-12 16:32:52.337  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 16:32:52.339  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-12 16:32:52.340  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-12 16:32:52.341  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-12 16:32:52.342  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
,08-12 16:32:52.358  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-12 16:32:52.358  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 16:32:52.366  2032  2317 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-12 16:32:52.366  2032  2317 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-12 16:32:52.369  1034  1117 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2b0521d6 u0 com.lge.launcher2/.Launcher t5} time:331473
08-12 16:32:52.373  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-12 16:32:52.374  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-12 16:32:52.374  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-12 16:32:52.382  2032  2032 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-12 16:32:52.384  2613  2613 D [Concierge]Service: onStartCommand(). Type : 8
08-12 16:32:52.384  2613  2613 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-12 16:32:52.385  2613  2613 D [Concierge]Service: Update widget ID : 11
08-12 16:32:52.387  2032  2032 D [Concierge]WidgetView: change position of spinner
08-12 16:32:52.388  2613  2613 D [Concierge]Service: onStartCommand(). Type : 0
08-12 16:32:52.388  2032  2032 I [Concierge]WidgetView: initWebView(). Time : 1471012372388
,08-12 16:32:52.389  1034  1122 I art     : Explicit concurrent mark sweep GC freed 8279(647KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.408ms total 212.252ms
08-12 16:32:52.401  2032  2032 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 185643496
08-12 16:32:52.401  2032  2032 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-12 16:32:52.401  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-12 16:32:52.404  2032  2032 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@1baf1b68
08-12 16:32:52.404  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-12 16:32:52.405  2032  2032 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-12 16:32:52.405  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 16:32:52.410  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-12 16:32:52.410  2032  2032 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-12 16:32:52.411  2032  2032 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471012069317, New one : 1471012372388
08-12 16:32:52.411  2032  2032 D [Concierge]WidgetView: Unregister all receivers
08-12 16:32:52.411  2032  2032 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-12 16:32:52.411  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 16:32:52.413  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-12 16:32:52.414  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
,08-12 16:32:52.415  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-12 16:32:52.416  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-12 16:32:52.417  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-12 16:32:52.422  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 16:32:52.422  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 16:32:52.429  6901  6901 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-12 16:32:52.429  6901  6901 W LG Account v2.2: No ProfileInfo entries
08-12 16:32:52.429  6901  6901 I LG Account v2.2: isEnabled: false
08-12 16:32:52.429  6901  6901 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-12 16:32:52.430  6901  6901 I Feature : [Lifetracker]Country: EU
08-12 16:32:52.430  6901  6901 I Feature : [Lifetracker]Operator: OPEN
08-12 16:32:52.430  6901  6901 I Feature : [Lifetracker]Ranking support: false
08-12 16:32:52.430  6901  6901 I Feature : [Lifetracker]Comfort support: false
08-12 16:32:52.430  6901  6901 I Feature : [Lifetracker]Accessory: true
08-12 16:32:52.430  6901  6901 I Feature : [Lifetracker]Health device: true
08-12 16:32:52.430  6901  6901 I Feature : [Lifetracker]Extra Pedometer: false
08-12 16:32:52.430  6901  6901 I Feature : [Lifetracker]Blood glucose device: false
08-12 16:32:52.430  6901  6901 I Feature : [Lifetracker]Device Number: 3
08-12 16:32:52.430  6901  6901 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,08-12 16:32:52.435  1034  1034 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-12 16:32:52.435  1034  1034 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-12 16:32:52.435  1034  1034 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-12 16:32:52.449  2032  2032 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-12 16:32:52.457  2032  2032 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-12 16:32:52.457  2032  2032 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-12 16:32:52.458  2032  2032 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-12 16:32:52.464  1034  2044 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6923 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-12 16:32:52.468  1034  2044 I ActivityManager: Killing 6347:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-12 16:32:52.475  2032  2032 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-12 16:32:52.477  2032  2032 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2feb086d time:331581
08-12 16:32:52.479   353   353 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 263us total 14.523ms
08-12 16:32:52.495   353   353 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 252us total 12.327ms
,08-12 16:32:52.508   353   353 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 252us total 11.904ms
,08-12 16:32:52.510  6851  6851 D AndroidRuntime: Shutting down VM
,08-12 16:32:52.537  1034  1092 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-12 16:32:52.542  1034  1092 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-12 16:32:52.568  1034  1122 W ActivityManager: Application dead when creating service ServiceRecord{37aa9a3a u0 com.android.defcontainer/.DefaultContainerService}
,08-12 16:32:52.568  1034  1122 W libprocessgroup: failed to open /acct/uid_10004/pid_6347/cgroup.procs: No such file or directory
08-12 16:32:52.569  1034  1122 W ActivityManager: Scheduling restart of crashed service com.android.defcontainer/.DefaultContainerService in 1000ms
08-12 16:32:52.572  1034  1122 W ActivityManager: Scheduling restart of crashed service com.android.defcontainer/.DefaultContainerService in 4000ms
08-12 16:32:52.572  2032  2032 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-12 16:32:52.577  1034  1940 W ActivityManager: Spurious death for ProcessRecord{317d86eb 0:com.android.defcontainer/u0a4}, curProc for 6347: null
08-12 16:32:52.578  1034  1577 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-12 16:32:52.590  6923  6923 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-12 16:32:52.590  6923  6923 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-12 16:32:52.590  6923  6923 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-12 16:32:52.590  6923  6923 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-12 16:32:52.591  6923  6923 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-12 16:32:52.591  6923  6923 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-12 16:32:52.636  2032  2032 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-12 16:32:52.672  2032  2882 I GBoardtInterface: onReloaded()
,08-12 16:32:52.674  2032  2032 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-12 16:32:52.675  3836  4490 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 16:32:52.677  3836  3852 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 16:32:52.684  1904  1904 D ActionManagerService: notifyUserLog: 1000001
08-12 16:32:52.685  3836  4493 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-12 16:32:52.685  3836  4493 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-12 16:32:52.690  6923  6923 D PackageIntentReceiver: Not supported Hotkey customization function 
08-12 16:32:52.690  1904  1904 D ActionManagerService: notifyUserLog: 1000001
08-12 16:32:52.692  3836  3852 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-12 16:32:52.695  3836  4493 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-12 16:32:52.695  3836  4493 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-12 16:32:52.695  3836  4493 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-12 16:32:52.695  3836  4493 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-12 16:32:52.699  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-12 16:32:52.699  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
,08-12 16:32:52.702  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-12 16:32:52.702  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-12 16:32:52.704  2032  2032 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-12 16:32:52.704  2032  2032 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-12 16:32:52.704  6923  6923 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-12 16:32:52.705  6923  6923 D HideNavigationAppsReceiver: replacing : false
08-12 16:32:52.711  6923  6923 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
,08-12 16:32:52.715  6923  6923 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-12 16:32:52.715  6923  6923 D ButtonCombinationReceiver: replacing : false
08-12 16:32:52.723  1034  1958 I ActivityManager: Killing 6490:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-12 16:32:52.771  1034  2050 W libprocessgroup: failed to open /acct/uid_10008/pid_6490/cgroup.procs: No such file or directory
,08-12 16:32:52.776  4597  6940 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-12 16:32:52.818  1034  1940 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6942 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-12 16:32:52.829  1034  1886 V SIM_STK : Menu title from STK is T-Mobile
08-12 16:32:52.848  4597  6940 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,--------- beginning of crash
08-12 16:32:52.851  4597  6940 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-12 16:32:52.851  4597  6940 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 4597
08-12 16:32:52.851  4597  6940 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-12 16:32:52.851  4597  6940 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-12 16:32:52.851  4597  6940 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-12 16:32:52.851  4597  6940 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-12 16:32:52.851  4597  6940 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-12 16:32:52.851  4597  6940 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-12 16:32:52.851  4597  6940 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-12 16:32:52.851  4597  6940 E AndroidRuntime: 	at csx.d(PG:186)
08-12 16:32:52.851  4597  6940 E AndroidRuntime: 	at cun.g(PG:594)
08-12 16:32:52.851  4597  6940 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
08-12 16:32:52.851  4597  6940 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
08-12 16:32:52.851  4597  6940 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1349)
08-12 16:32:52.851  4597  6940 E AndroidRuntime: 	at cuw.Tg(PG:368)
08-12 16:32:52.851  4597  6940 E AndroidRuntime: 	at cuy.ub(PG:301)
08-12 16:32:52.851  4597  6940 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
08-12 16:32:52.851  4597  6940 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
08-12 16:32:52.851  4597  6940 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-12 16:32:52.851  4597  6940 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-12 16:32:52.851  4597  6940 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-12 16:32:52.851  4597  6940 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-12 16:32:52.855  4597  6940 I Process : Sending signal. PID: 4597 SIG: 9
08-12 16:32:52.860  1034  6960 E DropBoxManagerService: Can't write: system_app_crash
08-12 16:32:52.860  1034  6960 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-12 16:32:52.860  1034  6960 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-12 16:32:52.860  1034  6960 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-12 16:32:52.860  1034  6960 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-12 16:32:52.860  1034  6960 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-12 16:32:52.860  1034  6960 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-12 16:32:52.860  1034  6960 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-12 16:32:52.860  1034  6960 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-12 16:32:52.860  1034  6960 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-12 16:32:52.860  1034  6960 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-12 16:32:52.860  1034  6960 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-12 16:32,:52.860  1034  6960 E DropBoxManagerService: 	... 5 more
08-12 16:32:52.879  1034  1543 D WifiService: Client connection lost with reason: 4
08-12 16:32:52.891  6942  6942 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2586 
,08-12 16:32:52.908   279   795 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
