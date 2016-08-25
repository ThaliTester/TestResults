#### Test 82642184a744340_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-25 03:24:00.083  1586  1586 I [SystemUI]Clock: called onTimeUpdated()
08-25 03:24:00.093  1586  1586 I LgeClockWidgetControlView: called onTimeUpdated()
08-25 03:24:00.093  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
08-25 03:24:00.095  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
08-25 03:24:00.097  1586  1586 D KeyguardUpdateMonitor: handleTimeUpdate
,08-25 03:24:03.727  6111  6111 D AndroidRuntime: 
08-25 03:24:03.727  6111  6111 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-25 03:24:03.734  6111  6111 D AndroidRuntime: CheckJNI is OFF
08-25 03:24:03.934  6111  6111 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-25 03:24:03.945  1069  1918 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-25 03:24:03.960  1925  1942 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-25 03:24:03.966  1069  1918 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-25 03:24:03.968  1069  1918 D ActivityManager: setTaskToReturnTo : TaskRecord{3e491faf #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-25 03:24:03.968  1069  1918 D ActivityManager: setTaskToReturnTo : TaskRecord{3e491faf #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-25 03:24:03.970  1069  1918 D WindowStateEx: AppWindowTokenEx init.. 
08-25 03:24:03.971   340   355 E GBMv2   : DFP En is all cleared set to be enabled
08-25 03:24:04.000  1069  1918 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6126 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-25 03:24:04.003  6111  6111 D AndroidRuntime: Shutting down VM
08-25 03:24:04.066  1925  2062 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-25 03:24:04.067  1925  2062 D SplitWindowPolicy: topRunningActivity=ActivityInfo{34e1c8e2 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-25 03:24:04.068  1925  1941 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-25 03:24:04.068  1925  1941 D SplitWindowPolicy: topRunningActivity=ActivityInfo{10239473 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-25 03:24:04.139  6126  6126 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-25 03:24:04.219  6126  6126 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-25 03:24:04.234  6126  6126 I LibraryLoader: Loading: webviewchromium
08-25 03:24:04.238  6126  6126 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 6243-6247)
08-25 03:24:04.238  6126  6126 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-25 03:24:04.257  6126  6126 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {29776c5e}
,08-25 03:24:04.258  6126  6126 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 03:24:04.259  6126  6126 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-25 03:24:04.269  6126  6126 I BrowserStartupController: Initializing chromium process, renderers=0
08-25 03:24:04.270  6126  6126 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 03:24:04.282  6126  6162 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
08-25 03:24:04.286  6126  6126 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-25 03:24:04.287  6126  6126 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,08-25 03:24:04.287  6126  6126 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-25 03:24:04.298   310  1381 V AudioPolicyService: registerClient() client 0xb57c0da0, uid 10118
,08-25 03:24:04.307  6126  6126 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 03:24:04.307  6126  6126 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 03:24:04.307  6126  6126 I Adreno-EGL: Build Date: 12/12/14 금
08-25 03:24:04.307  6126  6126 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 03:24:04.307  6126  6126 I Adreno-EGL: Remote Branch: 
08-25 03:24:04.307  6126  6126 I Adreno-EGL: Local Patches: 
08-25 03:24:04.307  6126  6126 I Adreno-EGL: Reconstruct Branch: 
08-25 03:24:04.315  1069  1176 D BluetoothManagerService: Message: 20
,08-25 03:24:04.315  1069  1176 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@286766c1:true
08-25 03:24:04.417  6126  6172 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-25 03:24:04.432  6126  6126 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-25 03:24:04.462  6126  6126 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 03:24:04.468  6126  6126 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-25 03:24:04.472  6126  6126 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-25 03:24:04.475  6126  6126 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-25 03:24:04.475  6126  6126 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-25 03:24:04.492  6126  6126 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-25 03:24:04.565  1069  1171 W ActivityManager: Activity pause timeout for ActivityRecord{3d23ffbc u0 com.test.thalitest/.MainActivity t6}
,08-25 03:24:04.654  1069  1701 I art     : Explicit concurrent mark sweep GC freed 37635(1807KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.434ms total 153.011ms
,08-25 03:24:04.656  6126  6126 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-25 03:24:04.656  6126  6126 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 03:24:04.681  6126  6187 D OpenGLRenderer: Render dirty regions requested: true
08-25 03:24:04.682  6126  6187 I OpenGLRenderer: Initialized EGL, version 1.4
08-25 03:24:04.686  6126  6187 D OpenGLRenderer: Enabling debug mode 0
08-25 03:24:04.694  6126  6126 D Atlas   : Validating map...
,08-25 03:24:04.698  1069  2014 D SplitWindow: check instance of lgWin Window{1c3e6533 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 03:24:04.741  6126  6185 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 03:24:04.742  6126  6185 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 03:24:04.828  1069  1177 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +763ms (total +856ms)
,08-25 03:24:04.829  1069  1177 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3d23ffbc u0 com.test.thalitest/.MainActivity t6} time:286838
,08-25 03:24:04.833  6126  6126 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@500f6c5 time:286842
08-25 03:24:04.969  6126  6126 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-25 03:24:04.969  6126  6126 I chromium: 
,08-25 03:24:05.029  6126  6126 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-25 03:24:05.119  6126  6185 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-25 03:24:05.119  6126  6185 I chromium: 
,08-25 03:24:05.270  6126  6202 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435141120
,08-25 03:24:05.296  6126  6202 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-25 03:24:05.296  6126  6202 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-25 03:24:05.296  6126  6202 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-25 03:24:05.296  6126  6202 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-25 03:24:05.296  6126  6202 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-25 03:24:05.296  6126  6202 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e5ff079 added. We now have 1 listener(s)
,08-25 03:24:05.303  1069  1896 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:24:05.307  6126  6202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-25 03:24:05.308  6126  6202 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 03:24:05.309  6126  6202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 03:24:05.310  6126  6202 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 03:24:05.319  6126  6202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-25 03:24:05.319  6126  6202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-25 03:24:05.319  6126  6202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-25 03:24:05.319  6126  6202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-25 03:24:05.319  6126  6202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-25 03:24:05.319  6126  6202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-25 03:24:05.319  6126  6202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-25 03:24:05.319  6126  6202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-25 03:24:05.319  6126  6202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-25 03:24:05.319  6126  6202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-25 03:24:05.319  6126  6202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-25 03:24:05.319  6126  6202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-25 03:24:05.319  6126  6202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-25 03:24:05.319  6126  6202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-25 03:24:05.319  6126  6202 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@87096c added. We now have 1 listener(s)
08-25 03:24:05.320  6126  6202 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:24:05.324  1069  1428 D WifiService: New client listening to asynchronous messages
08-25 03:24:05.329  6126  6202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 03:24:05.329  6126  6202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-25 03:24:05.329  6126  6202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-25 03:24:05.329  6126  6202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-25 03:24:05.329  6126  6202 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-25 03:24:05.333  6126  6202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:24:05.333  1069  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:24:05.334  6126  6202 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-25 03:24:05.342  6126  6202 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-25 03:24:05.342  6126  6202 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:24:05.342  6126  6202 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:24:05.342  6126  6202 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:24:05.342  6126  6202 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:24:05.342  6126  6202 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:24:05.342  6126  6202 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:24:05.342  6126  6202 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:24:05.342  6126  6202 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:24:05.343  6126  6202 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-25 03:24:05.343  6126  6202 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:24:05.344  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:24:05.345  6126  6202 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-25 03:24:05.386  6126  6126 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-25 03:24:05.809   340   357 E GBMv2   : DFP En is all cleared set to be enabled
08-25 03:24:05.809   340   357 E GBMv2   : Set value is all cleared set the max
08-25 03:24:05.809   340   357 I GBMv2   : DFP Enabled. Ignore VFP set
,08-25 03:24:06.333  6126  6205 W jxcore-log: Initializing JXcore engine
08-25 03:24:06.333  6126  6205 W jxcore-log: JXcore engine is ready
,08-25 03:24:06.398  6205  6205 W Thread-702: type=1400 audit(0.0:158): avc: denied { ioctl } for path="socket:[7500]" dev="sockfs" ino=7500 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-25 03:24:06.408  6205  6205 W Thread-702: type=1400 audit(0.0:159): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-25 03:24:06.408  6205  6205 W Thread-702: type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[10466]" dev="sockfs" ino=10466 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-25 03:24:06.408  6205  6205 W Thread-702: type=1400 audit(0.0:161): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-25 03:24:06.408  6205  6205 W Thread-702: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[29491]" dev="sockfs" ino=29491 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-25 03:24:06.441  6126  6205 W jxcore-log: Starting JXcore engine
,08-25 03:24:06.591  6126  6205 W jxcore-log: Platform android
08-25 03:24:06.591  6126  6205 W jxcore-log: 
08-25 03:24:06.591  6126  6205 W jxcore-log: Process ARCH arm
08-25 03:24:06.591  6126  6205 W jxcore-log: 
,08-25 03:24:06.926  6126  6205 I jxcore-log: JXcore Cordova bridge is ready!
08-25 03:24:06.926  6126  6205 I jxcore-log: 
08-25 03:24:06.927  6126  6205 W jxcore-log: JXcore engine is started
,08-25 03:24:06.939  6126  6202 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-25 03:24:06.943  6126  6126 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-25 03:24:28.870  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-25 03:24:28.870  6126  6205 I jxcore-log: 
,08-25 03:24:28.873  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-25 03:24:28.873  6126  6205 I jxcore-log: 
08-25 03:24:28.876  6126  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:24:28.876  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:24:28.876  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:24:28.876  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:24:28.876  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:24:28.876  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:24:28.876  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:24:28.876  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:24:28.878  6126  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:24:28.881  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-25 03:24:28.881  6126  6205 I jxcore-log: 
08-25 03:24:28.883  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-25 03:24:28.883  6126  6205 I jxcore-log: 
08-25 03:24:29.227  6126  6205 I jxcore-log: Running unit tests
08-25 03:24:29.227  6126  6205 I jxcore-log: 
08-25 03:24:29.228  6126  6205 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 03:24:29.228  6126  6205 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25a6a5e0 added. We now have 2 listener(s)
08-25 03:24:29.229  1069  2611 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:24:29.231  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 03:24:29.231  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 03:24:29.231  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 03:24:29.231  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:24:29.231  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@39bf1099 added. We now have 2 listener(s)
08-25 03:24:29.231  6126  6205 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:24:29.231  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 03:24:29.233  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:24:29.235  6126  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:24:29.235  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:24:29.235  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:24:29.235  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:24:29.235  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:24:29.235  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:24:29.235  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:24:29.235  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:24:29.236  6126  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:24:29.236  6126  6205 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:24:29.237  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:24:29.237  6126  6205 D ExecuteNativeTests: Running unit tests
08-25 03:24:29.321  6126  6205 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 03:24:29.321  6126  6205 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f added. We now have 3 listener(s)
08-25 03:24:29.322  1069  1918 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 03:24:29.323  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 03:24:29.323  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 03:24:29.323  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 03:24:29.323  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:24:29.323  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c added. We now have 3 listener(s)
08-25 03:24:29.323  6126  6205 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 03:24:29.324  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 03:24:29.326  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:24:29.327  6126  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:24:29.327  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:24:29.327  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:24:29.327  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:24:29.327  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:24:29.327  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:24:29.327  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:24:29.327  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:24:29.328  6126  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:24:29.329  6126  6205 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:24:29.329  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:24:29.332  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 03:24:29.333  6126  6205 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 03:24:29.333  6126  6205 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 03:24:29.333  6126  6205 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 03:24:29.334  6126  6205 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-25 03:24:29.335  6126  6205 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 03:24:29.335  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-25 03:24:29.335  6126  6205 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 03:24:29.335  6126  6205 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 03:24:29.335  6126  6205 V org.thaliproject,.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 03:24:29.336  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:24:29.336  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:24:29.337  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:24:29.337  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:24:29.337  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:29.337  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:24:29.338  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 03:24:29.338  6126  6205 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f removed from the list,
,08-25 03:24:29.338  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:24:29.338  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c removed from the list
08-25 03:24:29.338  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop,
08-25 03:24:29.338  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:24:29.339  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:29.339  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-25 03:24:29.340  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 03:24:29.340  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 03:24:29.340  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:29.340  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:29.342  6126  6205 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-25 03:24:29.342  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:24:29.342  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:24:29.342  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:24:29.342  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose,
08-25 03:24:29.342  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:29.342  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:24:29.342  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f not in the list
08-25 03:24:29.342  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:29.343  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:29.343  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:24:29.343  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:29.343  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left,
08-25 03:24:29.343  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:29.343  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:29.343  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:24:29.343  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:24:29.343  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:29.343  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list,
08-25 03:24:29.348  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 03:24:29.348  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 03:24:29.348  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 03:24:29.348  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 03:24:29.348  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 03:24:29.348  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410],
08-25 03:24:29.348  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 03:24:29.348  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 03:24:29.348  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 03:24:29.348  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 03:24:29.348  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 03:24:29.348  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-25 03:24:29.348  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 03:24:29.348  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 03:24:29.348  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 03:24:29.348  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 03:24:29.348  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 03:24:29.348  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 03:24:29.348  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 03:24:29.348  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,08-25 03:24:29.348  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 03:24:29.348  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 03:24:29.348  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 03:24:29.349  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 03:24:29.349  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 03:24:29.349  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 03:24:29.349  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
,08-25 03:24:29.349  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 03:24:29.349  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 03:24:29.349  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-25 03:24:29.349  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 03:24:29.349  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:24:29.349  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:24:29.349  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:24:29.349  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-25 03:24:29.349  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:29.349  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:29.349  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f not in the list
08-25 03:24:29.349  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:29.349  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:29.349  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:24:29.349  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:24:29.349  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:29.350  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:29.350  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:29.351  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:24:29.351  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:24:29.351  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:29.351  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:29.352  6126  6205 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-25 03:24:29.354  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:24:29.355  6126  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:24:29.355  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:24:29.355  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:24:29.355  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:24:29.355  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:24:29.355  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:24:29.355  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:24:29.355  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:24:29.357  6126  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:24:29.358  6126  6205 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-25 03:24:29.358  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:24:29.358  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 03:24:29.359  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 03:24:29.359  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 03:24:29.359  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:24:29.359  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener,
08-25 03:24:29.362  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 03:24:29.362  1069  1896 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 03:24:29.365  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 03:24:29.369  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 03:24:29.370  6126  6205 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-25 03:24:29.371  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 03:24:29.372  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:24:29.373  6126  6205 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 03:24:29.373  6126  6205 I io.jxcore.node.ConnectionHelper: start: OK
08-25 03:24:30.414  1069  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=506181987, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1069
,08-25 03:24:30.434  1069  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{22aa1c95 type 2 when 258676 com.google.android.gms} when 258676
,08-25 03:24:30.451   306  6235 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
,08-25 03:24:30.455  1069  1174 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-25 03:24:30.474  2563  2563 D [Concierge]Service: onStartCommand(). Type : 9
,08-25 03:24:30.504  1069  1069 D PowerManagerServiceEx: releaseWakeLockInternal: lock=506181987 [*alarm*], flags=0x0
,08-25 03:24:34.385  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:24:34.385  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:24:34.385  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 03:24:34.392  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:24:34.392  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:34.392  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:24:34.392  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f not in the list
08-25 03:24:34.393  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:34.393  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
,08-25 03:24:34.393  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:24:34.393  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:39.394  6126  6205 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-25 03:24:39.410  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:24:39.417  6126  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:24:39.417  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:24:39.417  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:24:39.417  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:24:39.417  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:24:39.417  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:24:39.417  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:24:39.417  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:24:39.418  6126  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:24:39.419  6126  6205 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:24:39.420  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:24:39.420  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 03:24:39.420  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 03:24:39.420  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 03:24:39.420  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:24:39.420  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 03:24:39.426  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-25 03:24:39.428  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:24:39.430  6126  6205 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 03:24:39.431  6126  6205 I io.jxcore.node.ConnectionHelper: start: OK
08-25 03:24:39.433  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:24:39.433  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:24:39.433  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:24:39.433  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:24:39.433  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:39.433  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:24:39.433  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f not in the list
08-25 03:24:39.433  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:39.433  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:39.433  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:24:39.433  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:39.434  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:39.434  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:39.435  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:24:39.435  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:24:39.437  6126  6205 D BluetoothLeScanner: could not find callback wrapper
08-25 03:24:39.437  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:24:39.437  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:39.438  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:39.438  6126  6205 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-25 03:24:39.444  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:24:39.447  6126  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:24:39.447  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:24:39.447  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:24:39.447  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:24:39.447  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:24:39.447  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:24:39.447  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:24:39.447  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:24:39.449  6126  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:24:39.449  6126  6205 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:24:39.450  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:24:39.451  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 03:24:39.451  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 03:24:39.451  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 03:24:39.451  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:24:39.451  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-25 03:24:39.458  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 03:24:39.459  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:24:39.461  6126  6205 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 03:24:39.462  6126  6205 I io.jxcore.node.ConnectionHelper: start: OK
08-25 03:24:44.462  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:24:44.462  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:24:44.463  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 03:24:49.473  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:24:49.473  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:24:49.474  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 03:24:49.480  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:24:49.480  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.480  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:24:49.480  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f not in the list
08-25 03:24:49.480  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:49.480  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:49.483  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:24:49.483  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.484  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.484  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.485  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:24:49.485  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:24:49.486  6126  6205 D BluetoothLeScanner: could not find callback wrapper
08-25 03:24:49.486  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:24:49.486  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:49.486  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:49.487  6126  6205 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-25 03:24:49.487  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:24:49.487  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:24:49.487  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:24:49.488  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:24:49.488  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.488  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.488  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f not in the list
08-25 03:24:49.488  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:49.488  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:49.488  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:24:49.488  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.488  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blu,etoothManager: release: 2 listener(s) left
08-25 03:24:49.488  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.488  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:24:49.493  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:24:49.493  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:24:49.494  6126  6205 D BluetoothLeScanner: could not find callback wrapper
08-25 03:24:49.494  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:24:49.494  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:49.494  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:49.496  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 03:24:49.496  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:24:49.496  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:24:49.496  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:24:49.497  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:24:49.497  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.497  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.497  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f not in the list
08-25 03:24:49.497  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:49.497  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:49.497  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:24:49.497  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.497  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.497  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.497  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.498  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:24:49.498  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:24:49.499  6126  6205 D BluetoothLeScanner: could not find callback wrapper
08-25 03:24:49.499  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:24:49.499  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:49.499  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:49.500  6126  6205 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-25 03:24:49.501  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:24:49.501  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: ,false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:24:49.501  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 03:24:49.505  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:24:49.505  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.505  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.505  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f not in the list
08-25 03:24:49.505  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:49.505  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
,08-25 03:24:49.505  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:24:49.505  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.506  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:24:49.506  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.506  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.507  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:24:49.507  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 03:24:49.508  6126  6205 D BluetoothLeScanner: could not find callback wrapper
08-25 03:24:49.508  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:24:49.508  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:49.508  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:49.509  6126  6205 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-25 03:24:49.509  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:24:49.509  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:24:49.509  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:24:49.510  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:24:49.510  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.510  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.510  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f not in the list
08-25 03:24:49.510  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:49.510  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:49.510  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:24:49.510  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.510  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.510  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.510  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.512  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:24:49.512  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:24:49.512  6126  6205 D BluetoothLeScanner: could not find callback wrapper
08-25 03:24:49.513  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:24:49.513  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:49.513  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:49.513  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 03:24:49.517  6126  6205 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 03:24:49.517  6126  6205 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 03:24:49.517  6126  6205 I org.thaliproject.p2p.btc,onnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-25 03:24:49.524  6126  6205 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 03:24:49.525  6126  6205 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 03:24:49.525  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-25 03:24:49.526  6126  6205 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 03:24:49.526  6126  6205 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-25 03:24:49.526  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:24:49.527  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:24:49.527  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:24:49.530  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:24:49.530  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.530  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.530  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f not in the list
08-25 03:24:49.531  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:49.531  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:49.531  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:24:49.531  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.531  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.531  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.531  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.534  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-25 03:24:49.537  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:24:49.539  6126  6205 D BluetoothLeScanner: could not find callback wrapper
08-25 03:24:49.539  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:24:49.539  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:49.539  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:49.541  6126  6205 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 03:24:49.542  6126  6205 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 03:24:49.542  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-25 03:24:49.545  6126  6205 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 03:24:49.545  6126  6205 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-25 03:24:49.545  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-25 03:24:49.545  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-25 03:24:49.545  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-25 03:24:49.545  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-25 03:24:49.545  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-25 03:24:49.545  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-25 03:24:49.546  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-25 03:24:49.546  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-25 03:24:49.546  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-25 03:24:49.546  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-25 03:24:49.546  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-25 03:24:49.546  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-25 03:24:49.546  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-25 03:24:49.546  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-25 03:24:49.546  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-25 03:24:49.546  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-25 03:24:49.546  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-25 03:24:49.546  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-25 03:24:49.546  6126  6205 D io.,jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-25 03:24:49.546  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-25 03:24:49.546  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-25 03:24:49.546  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-25 03:24:49.546  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-25 03:24:49.546  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-25 03:24:49.546  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-25 03:24:49.546  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-25 03:24:49.546  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-25 03:24:49.546  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-25 03:24:49.546  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810],
08-25 03:24:49.547  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-25 03:24:49.547  6126  6205 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-25 03:24:49.547  6126  6205 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 03:24:49.547  6126  6205 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-25 03:24:49.547  6126  6205 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 03:24:49.547  6126  6205 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-25 03:24:49.547  6126  6205 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-25 03:24:49.547  6126  6205 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 03:24:49.547  6126  6205 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,08-25 03:24:49.547  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-25 03:24:49.551  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-25 03:24:49.553  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-25 03:24:49.553  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-25 03:24:49.554  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,08-25 03:24:49.554  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-25 03:24:49.554  6126  6205 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-25 03:24:49.554  6126  6205 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-25 03:24:49.554  6126  6205 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-25 03:24:49.555  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:24:49.555  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:24:49.555  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 03:24:49.565  6126  6236 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 766)
08-25 03:24:49.571  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:24:49.571  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.571  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.571  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-25 03:24:49.572  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f not in the list
08-25 03:24:49.572  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:49.572  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:49.572  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:24:49.572  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.572  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.572  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.572  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:24:49.577  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:24:49.577  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:24:49.578  6126  6205 D BluetoothLeScanner: could not find callback wrapper
08-25 03:24:49.578  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:24:49.578  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:49.578  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:49.580  6126  6205 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-25 03:24:49.580  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:24:49.580  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:24:49.580  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:24:49.581  6126  6237 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 766
08-25 03:24:49.581  6126  6237 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 766)
08-25 03:24:49.582  6126  6237 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 766)
08-25 03:24:49.582  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:24:49.582  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.582  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.582  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f not in the list
08-25 03:24:49.582  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:49.582  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:49.582  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:24:49.582  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.582  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.582  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.582  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.584  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:24:49.584  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:24:49.584  6126  6205 D BluetoothLeScanner: could not find callback wrapper
08-25 03:24:49.584  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:24:49.584  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:49.584  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSett,ings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:49.585  6126  6205 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-25 03:24:49.586  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:24:49.586  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:24:49.586  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:24:49.588  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:24:49.588  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.588  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.588  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f not in the list
08-25 03:24:49.588  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:49.588  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:49.588  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:24:49.588  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.588  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.588  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.588  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.601  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:24:49.601  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 03:24:49.603  6126  6205 D BluetoothLeScanner: could not find callback wrapper
08-25 03:24:49.603  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:24:49.604  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:49.604  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:49.605  6126  6205 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-25 03:24:49.605  6126  6205 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-25 03:24:49.605  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 03:24:49.605  6126  6205 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-25 03:24:49.605  6126  6205 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 03:24:49.606  6126  6205 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-25 03:24:49.606  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 03:24:49.606  6126  6205 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-25 03:24:49.606  6126  6205 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-25 03:24:49.606  6126  6205 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-25 03:24:49.606  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 03:24:49.606  6126  6205 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-25 03:24:49.606  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:24:49.606  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:24:49.606  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...,
08-25 03:24:49.607  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:24:49.607  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:24:49.607  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.607  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f not in the list
08-25 03:24:49.607  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:49.607  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
,08-25 03:24:49.607  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:24:49.607  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.607  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:24:49.607  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:49.607  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.609  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising,
08-25 03:24:49.609  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 03:24:49.609  6126  6205 D BluetoothLeScanner: could not find callback wrapper
08-25 03:24:49.609  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:24:49.609  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:24:49.609  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:49.610  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:24:49.610  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed,
08-25 03:24:49.610  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:49.610  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f not in the list
08-25 03:24:49.610  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-25 03:24:49.610  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:49.623  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:24:49.623  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-25 03:24:49.623  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:24:49.712  6126  6236 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
,08-25 03:24:49.713  6126  6236 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 766)
,08-25 03:24:53.066  1069  3448 I LocationManagerService: remove 16a8dc
08-25 03:24:53.067  1069  3448 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-25 03:24:53.068  1069  3448 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 03:24:53.069  1069  3448 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-25 03:24:53.070  1069  3448 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
,08-25 03:24:53.078  1069  3448 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-25 03:24:54.625  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:54.625  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:54.625  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:24:54.625  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:54.626  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:54.626  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f not in the list
08-25 03:24:54.626  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:24:54.626  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:24:54.626  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 03:24:54.635  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:24:54.635  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:54.636  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:54.636  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f not in the list
08-25 03:24:54.636  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:54.636  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:54.636  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:24:54.636  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:54.636  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:54.636  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:54.636  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:54.642  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:24:54.642  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 03:24:54.645  6126  6205 D BluetoothLeScanner: could not find callback wrapper
08-25 03:24:54.645  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:24:54.645  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:54.645  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:54.648  6126  6205 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 03:24:54.648  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:24:54.649  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-25 03:24:54.650  6126  6205 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 03:24:54.651  6126  6205 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 03:24:54.653  6126  6126 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,08-25 03:24:54.656  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 03:24:54.656  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 03:24:54.658  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:24:54.658  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 03:24:54.658  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 03:24:54.658  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-25 03:24:54.658  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:54.658  6126  6205 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 03:24:54.659  1069  1701 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:24:54.660  6126  6255 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 03:24:54.661  3750  4113 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-25 03:24:54.662  6126  6126 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-25 03:24:54.662  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f not in the list
08-25 03:24:54.662  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:54.662  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-25 03:24:54.663  6126  6205 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-25 03:24:54.663  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-25 03:24:54.664  6126  6255 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-25 03:24:54.664  6126  6255 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 03:24:54.664  6126  6255 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 03:24:54.665  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-25 03:24:54.670  6126  6205 D BluetoothLeScanner: could not find callback wrapper
08-25 03:24:54.670  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:24:54.670  6126  6205 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-25 03:24:54.671  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:54.671  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:54.673  6126  6205 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 03:24:54.673  6126  6126 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 03:24:54.673  6126  6126 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-25 03:24:54.673  6126  6126 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 03:24:54.674  6126  6126 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-25 03:24:54.674  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:54.674  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:24:54.674  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:24:54.674  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:24:54.675  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:24:54.675  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:54.675  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:54.675  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f not in the list
08-25 03:24:54.675  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:54.675  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:54.675  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:24:54.675  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:54.675  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:54.675  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:54.675  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:54.676  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:24:54.676  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:24:54.676  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: disp,ose
08-25 03:24:54.676  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:54.678  6126  6205 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-25 03:24:54.678  6126  6205 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-25 03:24:54.678  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-25 03:24:54.685  6126  6205 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 03:24:54.685  6126  6205 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-25 03:24:54.685  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:24:54.686  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:24:54.686  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:24:54.686  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:24:54.686  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:54.686  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:54.686  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f not in the list
08-25 03:24:54.686  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:54.687  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:54.687  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:24:54.687  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:54.687  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:54.687  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:54.687  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:54.689  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:24:54.689  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:24:54.689  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:54.689  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:54.692  1069  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 03:24:54.697  1069  1977 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:24:54.699  1069  1559 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:24:54.700  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:24:54.700  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:24:54.700  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:24:54.700  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:24:54.700  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:54.700  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:54.701  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f not in the list
08-25 03:24:54.701  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:54.701  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:54.701  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:24:54.701  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:54.701  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:54.701  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:54.701  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:54.702  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:24:54.702  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:24:54.702  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:54.702  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:54.704  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:24:54.704  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:24:54.704  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:24:54.705  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:24:54.705  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:54.705  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:54.705  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e21262f not in the list
0,8-25 03:24:54.705  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:54.705  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:54.705  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:24:54.705  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:54.705  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:54.705  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:54.705  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:24:54.710  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:24:54.710  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:24:54.710  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:54.711  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2519c43c not in the list
08-25 03:24:54.713  6126  6205 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-25 03:24:54.713  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 03:24:54.713  6126  6205 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-25 03:24:54.713  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-25 03:24:54.713  6126  6205 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-25 03:24:54.713  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-25 03:24:54.716  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-25 03:24:54.716  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-25 03:24:54.717  6126  6205 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-25 03:24:54.717  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 03:24:54.717  6126  6205 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-25 03:24:54.717  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-25 03:24:54.717  6126  6205 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-25 03:24:54.717  6126  6205 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-25 03:24:54.718  6126  6205 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-25 03:24:54.718  6126  6205 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-25 03:24:54.719  6126  6205 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-25 03:24:54.719  6126  6205 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-25 03:24:54.719  6126  6205 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-25 03:24:54.719  6126  6205 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-25 03:24:54.722  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:24:54.722  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@3ac1287d added. We now have 3 listener(s)
08-25 03:24:54.722  6126  6205 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:24:54.727  6126  6205 D BluetoothAdapter: enable(): BT is already enabled..!
08-25 03:24:54.728  1069  1960 D WifiServiceImplEx: setWifiEnabled: true pid=6126, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 03:24:54.729  1069  1960 D WifiService: setWifiEnabled: true pid=6126, uid=10118
08-25 03:24:54.729  1069  1960 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 03:24:55.174  6126  6126 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-25 03:24:59.737  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-25 03:24:59.737  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c428372 added. We now have 4 listener(s)
08-25 03:24:59.737  6126  6205 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:24:59.754  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:59.754  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2c428372 removed from the list
08-25 03:24:59.754  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:24:59.755  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:59.755  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:59.755  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:24:59.756  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@388ae3c3 added. We now have 4 listener(s)
08-25 03:24:59.756  6126  6205 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:24:59.760  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:24:59.760  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@388ae3c3 removed from the list
08-25 03:24:59.760  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:24:59.760  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:24:59.760  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:24:59.761  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:24:59.761  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@105a9440 added. We now have 4 listener(s)
08-25 03:24:59.761  6126  6205 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 03:24:59.765  1069  1896 D WifiServiceImplEx: setWifiEnabled: false pid=6126, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 03:24:59.765  1069  1896 D WifiService: setWifiEnabled: false pid=6126, uid=10118
08-25 03:24:59.765  1069  1896 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 03:24:59.786  1069  1069 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 03:24:59.787  1069  1069 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 03:24:59.787  1069  1069 D Ulp_jni : JNI:system_update. Event-4
08-25 03:24:59.789  1069  1376 E WifiStateMachine:  DisconnectedState CMD_STOP_SUPPLICANT 0 0
08-25 03:24:59.789  1069  1376 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-25 03:24:59.790  1069  1376 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-25 03:24:59.790  1069  1376 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-25 03:24:59.791  1069  1069 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 03:24:59.792  1069  1540 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:24:59.792  1069  1069 D RttService: SCAN_AVAILABLE : 1
08-25 03:24:59.792  1069  1541 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:24:59.794  1069  1374 D LGWifiP2pService: InactiveState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:24:59.794  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:24:59.794  1069  1374 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1f46102c
08-25 03:24:59.794  1069  1374 D LGWifiP2pService: P2pDisablingState
08-25 03:24:59.795  1069  1374 D LGWifiP2pService: P2pDisablingState{ when=-1ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:24:59.795  1069  1374 D LGWifiP2pService: p2p socket connection lost
08-25 03:24:59.795  1069  1374 D LGWifiP2pService: P2pDisabledState
,08-25 03:24:59.800  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 03:24:59.802  1925  1925 D WfdsService: WifiP2pState is changed : false
08-25 03:24:59.802  1925  2274 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-25 03:24:59.802  1925  2274 D WfdsService: Set the WFDS Monitor: false
08-25 03:24:59.803  1925  2274 D WfdsMonitor: WFDS Monitor is stopped
08-25 03:24:59.803  1925  2274 D WfdsService: STATE : WfdsDisabledState - enter
08-25 03:24:59.804  1925  2853 D CtrlSupplicant: Received on exit socket, terminate
08-25 03:24:59.804  1925  2853 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-25 03:24:59.804  1925  2853 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-25 03:24:59.804  1925  2853 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-25 03:24:59.805  1925  2277 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-25 03:24:59.808  1925  2274 W WfdsService: DefaultState - msg [9445378] is not handled
,08-25 03:24:59.811  1069  1376 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-25 03:24:59.812   306   911 D CommandListener: Clearing all IP addresses on wlan0
08-25 03:24:59.813  1069  1096 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:24:59.814  1069  1096 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@c90b64e mBinding = false
08-25 03:24:59.823  1069  1069 D WifiHS20: hidePasspointNotification off =false
08-25 03:24:59.823  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:24:59.823  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:24:59.823  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-25 03:24:59.827  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 03:24:59.827  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 03:24:59.830  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:24:59.834  1069  1176 D BluetoothManagerService: Message: 2
08-25 03:24:59.835  1069  1176 D BluetoothManagerService: Sending off request.
,08-25 03:24:59.838  3750  3768 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-25 03:24:59.839  3750  3824 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-25 03:24:59.840  3750  3824 D BluetoothAdapterProperties: Setting state to 13
08-25 03:24:59.840  3750  3824 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 03:24:59.840  3750  3824 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 03:24:59.841  3750  3824 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-25 03:24:59.843  1069  1176 D BluetoothManagerService: Message: 60
08-25 03:24:59.843  1069  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-25 03:24:59.843  1069  1176 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-25 03:24:59.848  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:24:59.853  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:24:59.853  6126  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:24:59.853  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:24:59.853  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:24:59.853  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:24:59.853  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:24:59.853  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:24:59.853  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:24:59.853  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:24:59.854  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:24:59.854  6126  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:24:59.854  6126  6205 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:24:59.860  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:24:59.863  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:24:59.866  3750  3750 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:24:59.866  3750  3750 D BluetoothMapService: STATE_TURNING_OFF
08-25 03:24:59.866  3750  3750 V BluetoothMapService: Handler(): got msg=4
08-25 03:24:59.866  3750  3750 D BluetoothMapService: MAP Service closeService in
08-25 03:24:59.866  3750  3750 D BluetoothMapMasInstance: MAP Service shutdown
08-25 03:24:59.867  3750  4096 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-25 03:24:59.867  3750  4096 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 03:24:59.867  3750  4096 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-25 03:24:59.867  3750  4096 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-25 03:24:59.867  3750  4096 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-25 03:24:59.867  3750  4096 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-25 03:24:59.867  3750  4096 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-25 03:24:59.867  3750  4096 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-25 03:24:59.868  3750  3750 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 03:24:59.868  3750  3750 V BluetoothMapService: MAP Service closeService out
08-25 03:24:59.870  1069  1069 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 03:24:59.870  1069  1069 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 03:24:59.870  1069  1069 D Ulp_jni : JNI:system_update. Event-4
08-25 03:24:59.873  3750  3750 V BtOppService: Receiver DISABLED_ACTION 
08-25 03:24:59.873  3750  3750 I BtOppRfcommListener: stopping Accept Thread
08-25 03:24:59.873  3750  3750 V BtOppRfcommListener: close mBtServerSocket
08-25 03:24:59.873  3750  3750 V BtOppRfcommListener: waiting for thread to terminate
,08-25 03:24:59.876  3750  4115 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 03:24:59.877  3750  4115 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 03:24:59.878  3750  3750 V BtOppRfcommListener: done waiting for thread to terminate
08-25 03:24:59.882  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:24:59.882  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:24:59.882  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:24:59.882  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:24:59.882  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:24:59.882  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:24:59.882  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:24:59.882  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:24:59.882  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:24:59.883  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:24:59.883  6126  6126 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:24:59.884  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:24:59.885  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:24:59.885  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:24:59.885  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:24:59.885  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:24:59.885  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:24:59.885  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:24:59.885  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:24:59.885  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:24:59.886  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:24:59.886  6126  6126 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:24:59.889  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:24:59.912  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 03:24:59.921  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 03:24:59.948  1069  1171 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=6274 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-25 03:24:59.949  1069  1376 D WifiNative-p2p0: doBoolean: TERMINATE
08-25 03:24:59.949  1069  1376 D WifiNative-p2p0: TERMINATE: returned true
08-25 03:24:59.952  1069  1069 D WifiHS20: hidePasspointNotification off =false
08-25 03:24:59.952  3750  3750 V BtOppService: onDestroy
08-25 03:24:59.952  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:24:59.953  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:24:59.953  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 03:24:59.954  3750  3750 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-25 03:24:59.954  3750  3828 D BluetoothAdapterProperties: Scan Mode:20
08-25 03:24:59.954  3750  3824 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-25 03:24:59.955  3750  4136 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 03:24:59.955  3750  3824 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 03:24:59.955  3750  4134 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 03:24:59.956  3750  3893 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-25 03:24:59.957  3750  4098 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 03:24:59.957  3750  3893 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-25 03:24:59.960  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:24:59.964  3750  3893 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 03:24:59.964  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:24:59.965  1069  1376 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 03:24:59.965  1069  1376 E WifiStateMachine: useWiFiOffloading() : false
08-25 03:24:59.965  1069  1376 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 03:24:59.965  3750  3893 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 03:24:59.965  3750  3893 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 03:24:59.965  3750  3893 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 03:24:59.965  3750  3893 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 03:24:59.965  3750  3893 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 03:24:59.965  3750  3893 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 03:24:59.965  3750  3893 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 03:24:59.965  3750  3893 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 03:24:59.965  3750  3893 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-25 03:24:59.965  3750  3893 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-25 03:24:59.965  3750  3893 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 03:24:59.969  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:24:59.969  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:24:59.969  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:24:59.969  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:24:59.969  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:24:59.969  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:24:59.969  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:24:59.969  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:24:59.969  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:24:59.969  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 03:24:59.969  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 03:24:59.970  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:24:59.971  6126  6126 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:24:59.971  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:00.013  1069  1960 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=6294 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-25 03:25:00.020  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 03:25:00.021  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-25 03:25:00.022  1069  1069 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-25 03:25:00.022  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 03:25:00.022  1069  1069 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-25 03:25:00.024  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:00.024  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:00.024  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:00.024  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:00.024  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:25:00.024  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:25:00.024  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:25:00.024  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:25:00.024  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:25:00.025  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:00.025  6126  6126 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:25:00.027  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:00.027  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:00.027  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:00.027  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:00.027  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:25:00.027  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:25:00.027  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:25:00.027  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:25:00.027  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:25:00.028  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:00.028  6126  6126 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:25:00.029  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:00.037  6274  6274 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 03:25:00.037  6274  6274 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-25 03:25:00.037  6274  6274 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 03:25:00.037  6274  6274 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-25 03:25:00.038  6274  6274 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 03:25:00.041  6274  6274 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-25 03:25:00.047  1586  1586 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-25 03:25:00.047  1586  1586 I KeyguardUpdateMonitor: called onTimeUpdated()
08-25 03:25:00.047  1586  1586 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-25 03:25:00.047  1586  1586 I [SystemUI]Clock: called onTimeUpdated()
08-25 03:25:00.048  1586  1586 I LgeClockWidgetControlView: called onTimeUpdated()
08-25 03:25:00.048  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
08-25 03:25:00.049  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
08-25 03:25:00.049  1586  1586 D KeyguardUpdateMonitor: handleTimeUpdate
,08-25 03:25:00.067  2734  2734 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-25 03:25:00.067  2734  2734 I wpa_supplicant: monitor socket send errors count : 1
08-25 03:25:00.067  2734  2734 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1925-2\x00 that cannot receive messages
08-25 03:25:00.069  1069  2852 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-25 03:25:00.069  1069  2852 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 03:25:00.087  6294  6294 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
,08-25 03:25:00.092  6294  6294 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 03:25:00.092  6294  6294 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 03:25:00.094  1069  1918 I ActivityManager: Killing 4827:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-25 03:25:00.112  2734  2734 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-25 03:25:00.112  1069  2852 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-25 03:25:00.112  1069  2852 E WifiMonitor: WifiMonitor:wlan0 cnt=12 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 03:25:00.112  1069  2852 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 03:25:00.112  2734  2734 W wpa_supplicant: USIM:  scard_deinit function
08-25 03:25:00.112  1069  1176 D Tethering: InitialState.processMessage what=4
08-25 03:25:00.113  1069  2852 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-25 03:25:00.113  1069  2852 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 03:25:00.113  1069  2852 E WifiMonitor: WifiMonitor:wlan0 cnt=13 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 03:25:00.114  1069  1376 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=342111
08-25 03:25:00.114  1069  1376 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=342112
08-25 03:25:00.114  1069  1376 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=342112  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 03:25:00.115  1069  1376 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 13 0 rt=342112  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 03:25:00.136  1069  1960 W libprocessgroup: failed to open /acct/uid_10014/pid_4827/cgroup.procs: No such file or directory
,08-25 03:25:00.138  1069  1176 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 03:25:00.138  1069  1376 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-25 03:25:00.139  1069  1376 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 03:25:00.140   306  6315 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-25 03:25:00.141  1069  1174 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-25 03:25:00.172  2734  2734 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-25 03:25:00.172  1069  2852 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-25 03:25:00.173  1069  2852 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-TERMINATING 
08-25 03:25:00.173  1069  2852 D WifiMonitor: Disconnecting from the supplicant, no more events
08-25 03:25:00.174  1069  1376 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 14 0
,08-25 03:25:00.189  6274  6274 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-25 03:25:00.195  3750  3750 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 03:25:00.195  3750  3750 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:00.195  3750  3750 V BluetoothPbapReceiver: ***********state = 13
08-25 03:25:00.197  3750  3750 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-25 03:25:00.198  3750  3750 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:00.198  3750  3750 V BluetoothPbapService: state: 13
08-25 03:25:00.198  3750  3750 V BluetoothPbapService: Pbap Service closeService in
08-25 03:25:00.199  3750  3750 V BluetoothPbapService: successfully stopped pbap service
08-25 03:25:00.199  3750  3750 V BluetoothPbapService: Pbap Service closeService out
08-25 03:25:00.199  3750  3750 V BluetoothPbapService: Pbap Service onDestroy
08-25 03:25:00.199  3750  3750 V BluetoothPbapService: Pbap Service closeService in
08-25 03:25:00.199  3750  3750 V BluetoothPbapService: Pbap Service closeService out
08-25 03:25:00.199  3750  3750 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-25 03:25:00.203  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 03:25:00.215  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 03:25:00.255  1069  1097 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6317 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-25 03:25:00.256  6274  6274 D LgDataFeature: LgDataFeature() Constructor: none
08-25 03:25:00.257  6274  6274 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 03:25:00.269  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 03:25:00.276  1069  1376 D WifiOffDelayIfNotUsed: stopMonitoring
08-25 03:25:00.276  1069  1376 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 03:25:00.276  1069  1376 E WifiStateMachine: useWiFiOffloading() : false
08-25 03:25:00.276  1069  1376 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 03:25:00.276  1925  1925 D WfdsService: Supplicant Connection state is changed : false
08-25 03:25:00.276  1925  2274 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-25 03:25:00.276  1925  2274 D WfdsService: Set the WFDS Monitor: false
08-25 03:25:00.276  1925  2274 D WfdsMonitor: WFDS Monitor is stopped
08-25 03:25:00.278  1069  1069 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-25 03:25:00.279  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 03:25:00.279  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:00.279  1069  1425 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-25 03:25:00.280  1069  1425 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-25 03:25:00.281  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:00.282  2485  2485 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:00.283  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:00.284  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:25:00.293  1069  1176 D BluetoothManagerService: Message: 20
08-25 03:25:00.293  1069  1176 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1ddcf068:true
08-25 03:25:00.304  1069  1176 D BluetoothManagerService: Message: 30
,08-25 03:25:00.314  1069  1176 D BluetoothManagerService: Message: 30
08-25 03:25:00.317  6274  6274 D LocalBluetoothProfileManager: Adding local MAP profile
08-25 03:25:00.319  6274  6274 D BluetoothMap: Create BluetoothMap proxy object
,08-25 03:25:00.319  1069  1176 D BluetoothManagerService: Message: 30
08-25 03:25:00.324  1069  1176 D BluetoothManagerService: Message: 30
08-25 03:25:00.325  6274  6274 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-25 03:25:00.326  6274  6274 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
08-25 03:25:00.341  6274  6274 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
,08-25 03:25:00.346  6274  6274 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
08-25 03:25:00.361  6274  6274 D DockEventReceiver: finishStartingService: stopping service
,08-25 03:25:00.368  6317  6317 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-25 03:25:00.369  6317  6317 W LG Account v2.2: No ProfileInfo entries
08-25 03:25:00.369  6317  6317 I LG Account v2.2: isEnabled: false
08-25 03:25:00.369  6317  6317 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-25 03:25:00.370  6317  6317 I Feature : [Lifetracker]Country: EU
08-25 03:25:00.370  6317  6317 I Feature : [Lifetracker]Operator: OPEN
08-25 03:25:00.370  6317  6317 I Feature : [Lifetracker]Ranking support: false
08-25 03:25:00.370  6317  6317 I Feature : [Lifetracker]Comfort support: false
08-25 03:25:00.370  6317  6317 I Feature : [Lifetracker]Accessory: true
08-25 03:25:00.370  6317  6317 I Feature : [Lifetracker]Health device: true
08-25 03:25:00.370  6317  6317 I Feature : [Lifetracker]Extra Pedometer: false
08-25 03:25:00.370  6317  6317 I Feature : [Lifetracker]Blood glucose device: false
08-25 03:25:00.371  6317  6317 I Feature : [Lifetracker]Device Number: 3
08-25 03:25:00.375  1069  1896 I ActivityManager: Killing 5734:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-25 03:25:00.387  6274  6274 D BluetoothInputDevice: Proxy object connected
,08-25 03:25:00.389  6274  6274 D HidProfile: Bluetooth service connected
,08-25 03:25:00.391  6274  6274 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 03:25:00.391  6274  6274 D PanProfile: Bluetooth service connected
08-25 03:25:00.392  6274  6274 D BluetoothMap: Proxy object connected
08-25 03:25:00.393  6274  6274 D MapProfile: Bluetooth service connected
08-25 03:25:00.393  6274  6274 D BluetoothMap: getConnectedDevices()
08-25 03:25:00.393  6274  6274 D BluetoothMap: Bluetooth is Not enabled
08-25 03:25:00.394  6274  6274 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-25 03:25:00.405  1069  1097 W libprocessgroup: failed to open /acct/uid_10008/pid_5734/cgroup.procs: No such file or directory
,08-25 03:25:00.409  6274  6274 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-25 03:25:00.413  6274  6274 D BluetoothPermissionRequest: onReceive
08-25 03:25:00.416  6274  6274 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-25 03:25:00.421  1069  1097 I ActivityManager: Killing 5766:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-25 03:25:00.425  6274  6274 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 03:25:00.483  3750  3750 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-25 03:25:00.483  1069  1896 W libprocessgroup: failed to open /acct/uid_10011/pid_5766/cgroup.procs: No such file or directory
,08-25 03:25:00.484  3750  3750 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-25 03:25:00.486  3750  3750 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-25 03:25:00.553  1069  1097 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=6343 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-25 03:25:00.562  3750  3750 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:00.562  3750  3750 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 03:25:00.564  3750  3750 V BluetoothFtpService: Ftp Service onStartCommand
08-25 03:25:00.564  3750  3750 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:00.564  3750  3750 V BluetoothFtpService: Ftp Service closeService
08-25 03:25:00.565  3750  3750 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-25 03:25:00.573  3750  3750 V BluetoothFtpService: successfully stopped ftp service
,08-25 03:25:00.574  3750  3750 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 03:25:00.574  3750  3750 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 03:25:00.574  3750  3750 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 03:25:00.574  3750  3750 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:00.574  3750  3750 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-25 03:25:00.574  3750  3750 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 03:25:00.576  3750  3750 V BluetoothFtpService: Ftp Service onDestroy
08-25 03:25:00.576  3750  3750 V BluetoothFtpService: Ftp Service closeService
,08-25 03:25:00.643  1069  1918 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=6363 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 03:25:00.644  3750  3750 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:00.644  3750  3750 V BluetoothSapService: state: 13
08-25 03:25:00.645  3750  3750 V BluetoothSapService: Stopping SAP server process
08-25 03:25:00.646  3750  3750 V BluetoothSapService: Sap Service closeSapService in
08-25 03:25:00.646  3750  3750 V BluetoothSapService: Close listen Socket : 
08-25 03:25:00.647  3750  3750 V BluetoothSapService: Close rfcomm Socket : 
08-25 03:25:00.647  3750  3750 V BluetoothSapService: Close sapd  Socket : 
08-25 03:25:00.648  3750  3750 V BluetoothSapService: Sap Service closeSapService out
08-25 03:25:00.649  3750  3750 V BluetoothSapService: Sap Service onDestroy
08-25 03:25:00.649  3750  3750 V BluetoothSapService: Sap Service closeSapService in
08-25 03:25:00.649  3750  3750 V BluetoothSapService: Close listen Socket : 
08-25 03:25:00.649  3750  3750 V BluetoothSapService: Close rfcomm Socket : 
08-25 03:25:00.649  3750  3750 V BluetoothSapService: Close sapd  Socket : 
08-25 03:25:00.655  3750  3750 V BluetoothSapService: Sap Service closeSapService out
,08-25 03:25:00.680  6343  6343 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 03:25:00.711  6363  6363 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 03:25:00.717  6343  6343 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
08-25 03:25:00.728  1069  1896 I ActivityManager: Killing 5627:com.android.defcontainer/u0a4 (adj 15): empty #17
,08-25 03:25:00.768  6343  6343 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
,08-25 03:25:00.769  6343  6343 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-25 03:25:00.769  6343  6343 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-25 03:25:00.770  6343  6343 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
08-25 03:25:00.770  6343  6343 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-25 03:25:00.773  6343  6343 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-25 03:25:00.779  6343  6343 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-25 03:25:00.792  1069  2611 W libprocessgroup: failed to open /acct/uid_10004/pid_5627/cgroup.procs: No such file or directory
,08-25 03:25:00.808  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 03:25:00.814  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 03:25:00.838  6343  6343 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 03:25:00.842  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 03:25:00.847  6294  6294 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 03:25:00.847  6294  6294 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 03:25:00.847  6294  6294 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 03:25:00.849  6343  6343 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-25 03:25:00.851  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 03:25:00.854  6343  6343 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-25 03:25:00.861  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:00.871  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 03:25:00.872  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 03:25:00.874  6343  6343 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 03:25:00.948  1069  2025 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=6383 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
,08-25 03:25:00.967  3750  3828 D bt_hci_bdroid: cleanup
08-25 03:25:00.967  3750  3893 W bt-btif : ag scb idx 1 not allocated
08-25 03:25:00.967  3750  3893 E bt-btif : BTA AG is already disabled, ignoring ...
08-25 03:25:00.967  3750  3893 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 03:25:00.967  3750  3893 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 03:25:00.967  3750  3893 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 03:25:00.967  3750  3893 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 03:25:00.967  3750  3893 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 03:25:00.967  3750  3893 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 03:25:00.967  3750  3893 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 03:25:00.967  3750  3893 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 03:25:00.967  3750  3893 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 03:25:00.967  3750  3893 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 03:25:00.967  3750  3893 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 03:25:00.967  3750  3893 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 03:25:00.967  3750  3893 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 03:25:00.967  3750  3893 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 03:25:00.967  3750  3893 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 03:25:00.968  3750  3895 I bt_lpm  : LPM is already off!!!
08-25 03:25:00.968  3750  3893 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 03:25:00.968  3750  3893 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 03:25:00.968  3750  4085 I bt_userial_mct: exiting userial_read_thread
08-25 03:25:00.968  3750  4085 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 03:25:00.968  3750  3893 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 03:25:00.968  3750  3893 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 03:25:00.968  3750  3828 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-25 03:25:00.968  3750  3895 I bt_vendor: hw_epilog_process
08-25 03:25:00.968  3750  3828 D bt_hci_bdroid: cleanup Finalizing cleanup
08-25 03:25:00.968  3750  3828 D bt_userial_mct: userial_close
08-25 03:25:00.968  3750  3828 E bt_userial_mct: pthread_join() FAILED result:3
08-25 03:25:00.968  3750  3828 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
,08-25 03:25:01.071  3750  3828 D bt_hci_bdroid: set_power 0
,08-25 03:25:01.071  3750  3828 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
,08-25 03:25:01.071  3750  3828 I bt_vendor: bluetooth satus is on
08-25 03:25:01.071  3750  3828 I bt_vendor: bt-vendor : resetting BT status
08-25 03:25:01.071  3750  3828 I bt_vendor: Starting hciattach daemon
08-25 03:25:01.071  3750  3828 I bt_vendor: try to set false
08-25 03:25:01.075  3750  3828 I bt_vendor: Starting hciattach daemon
08-25 03:25:01.075  3750  3828 I bt_vendor: try to set false
08-25 03:25:01.077  3750  3828 I bt_vendor: cleanup
08-25 03:25:01.078  3750  3893 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-25 03:25:01.082  6294  6294 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 03:25:01.088  3750  3828 I GKI_LINUX: GKI_exit_task 0 done
08-25 03:25:01.088  3750  3828 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-25 03:25:01.091  3750  3824 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
,08-25 03:25:01.094  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 03:25:01.096  3750  3750 D HeadsetService: Received stop request...Stopping profile...
08-25 03:25:01.097  3750  3750 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 03:25:01.097  3750  3750 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 03:25:01.097  3750  3750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3991f83f
08-25 03:25:01.097  3750  3842 D HeadsetStateMachine: Exit Disconnected: -1
08-25 03:25:01.099  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-25 03:25:01.099  3750  3750 D A2dpService: Received stop request...Stopping profile...
08-25 03:25:01.099  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-25 03:25:01.099  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-25 03:25:01.100  3750  3878 D A2dpStateMachine: Exit Disconnected: -1
08-25 03:25:01.100  3750  3750 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-25 03:25:01.102  1069  1069 D BluetoothHeadset: Proxy object disconnected
08-25 03:25:01.103  1069  1069 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-25 03:25:01.103  3750  3750 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-25 03:25:01.103  3750  3750 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 03:25:01.103  3750  3750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3991f83f
,08-25 03:25:01.106  1069  1069 D BluetoothA2dp: Proxy object disconnected
08-25 03:25:01.106  1069  1069 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-25 03:25:01.107  3750  3750 D HidService: Received stop request...Stopping profile...
08-25 03:25:01.107  3750  3750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3991f83f
08-25 03:25:01.112  3750  3750 D HeadsetStateMachine: Unbinding service...
08-25 03:25:01.113  3750  3824 D BluetoothAdapterState: Stopping profile services that were post enabled
08-25 03:25:01.113  3750  3750 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 03:25:01.114  3750  3750 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 03:25:01.114  3750  3750 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 03:25:01.114  3750  3750 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 03:25:01.114  3750  3750 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 03:25:01.114  3750  3750 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 03:25:01.114  3750  3750 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 03:25:01.115  3750  3750 D HealthService: Received stop request...Stopping profile...
08-25 03:25:01.115  3750  3750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3991f83f
08-25 03:25:01.116  3750  3750 D PanService: Received stop request...Stopping profile...
08-25 03:25:01.117  3750  3750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3991f83f
,08-25 03:25:01.118  3750  3750 I BluetoothA2dpServiceJni: cleanupNative
08-25 03:25:01.118  3750  3879 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-25 03:25:01.118  3750  3750 I GKI_LINUX: GKI_exit_task 2 done
08-25 03:25:01.119  3750  3750 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-25 03:25:01.120  3750  3750 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 03:25:01.120  3750  3750 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 03:25:01.120  3750  3750 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 03:25:01.120  3750  3750 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 03:25:01.120  3750  3750 D BtGatt.GattService: stop()
08-25 03:25:01.120  3750  3750 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 03:25:01.121  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:01.121  3750  3750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3991f83f
08-25 03:25:01.123  3750  3750 D BluetoothMapService: Received stop request...Stopping profile...
08-25 03:25:01.123  3750  3750 D BluetoothMapService: stop()
08-25 03:25:01.127  6274  6274 D BluetoothInputDevice: Proxy object disconnected
08-25 03:25:01.127  6274  6274 D HidProfile: Bluetooth service disconnected
08-25 03:25:01.127  6274  6274 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-25 03:25:01.127  6274  6274 D PanProfile: Bluetooth service disconnected
08-25 03:25:01.128  3750  3750 D BluetoothMapEmailAppObserver: deinitObservers()
08-25 03:25:01.128  3750  3750 D BluetoothMapEmailAppObserver: removeReceiver()
,08-25 03:25:01.128  3750  3750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3991f83f
08-25 03:25:01.130  3750  3750 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-25 03:25:01.130  3750  3750 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 03:25:01.130  3750  3750 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 03:25:01.130  3750  3750 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 03:25:01.130  3750  3750 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 03:25:01.132  3750  3750 V BluetoothMapService: Handler(): got msg=4
08-25 03:25:01.132  3750  3750 D BluetoothMapService: MAP Service closeService in
08-25 03:25:01.132  3750  3750 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 03:25:01.132  3750  3750 V BluetoothMapService: MAP Service closeService out
08-25 03:25:01.132  3750  3824 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-25 03:25:01.132  3750  3824 D BluetoothAdapterProperties: Setting state to 10
08-25 03:25:01.132  3750  3824 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 03:25:01.132  3750  3750 D BluetoothMapService: cleanup()
08-25 03:25:01.132  3750  3750 D BluetoothMapService: MAP Service closeService in
08-25 03:25:01.132  3750  3750 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 03:25:01.132  3750  3750 V BluetoothMapService: MAP Service closeService out
08-25 03:25:01.133  6274  6274 D BluetoothMap: Proxy object disconnected
08-25 03:25:01.133  6274  6274 D MapProfile: Bluetooth service disconnected
08-25 03:25:01.133  3750  3824 I BluetoothAdapterState: Entering OffState
08-25 03:25:01.135  1069  1176 D BluetoothManagerService: Message: 60
08-25 03:25:01.135  1069  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-25 03:25:01.135  1069  1176 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-25 03:25:01.135  6274  6293 D BluetoothMap: onBluetoothStateChange: up=false
08-25 03:25:01.136  1836  2694 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 03:25:01.137  6274  6292 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 03:25:01.137  1069  1176 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 03:25:01.137  1836  2459 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 03:25:01.138  1069  1176 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 03:25:01.138  1836  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 03:25:01.139  6274  6293 D BluetoothPan: onBluetoothStateChange on: false
08-25 03:25:01.141  6383  6403 W FormManager: Network not available. Please check & try again.
08-25 03:25:01.141  6274  6292 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-25 03:25:01.144  1069  1176 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-25 03:25:01.145  1069  1176 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-25 03:25:01.147  1069  1176 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-25 03:25:01.147  1069  1176 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-25 03:25:01.147  1069  1176 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@c90b64e mBinding = false
08-25 03:25:01.148  1069  1176 D BluetoothManagerService: Sending unbind request.
08-25 03:25:01.151  1069  1176 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-25 03:25:01.153  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 03:25:01.153  6274  6274 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 03:25:01.154  6274  6274 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 03:25:01.154  6274  6274 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 03:25:01.155  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 03:25:01.156  1925  2075 D LGBluetoothAPIService: Message: 2
08-25 03:25:01.156  1925  2075 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@3a536f30 mBinding = false
08-25 03:25:01.156  1925  2075 D LGBluetoothAPIService: Sending unbind request.
08-25 03:25:01.158  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 03:25:01.158  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:01.159  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:01.160  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:01.160  3750  3828 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-25 03:25:01.160  3750  3750 I GKI_LINUX: GKI_exit_task 1 done
08-25 03:25:01.160  3750  3750 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-25 03:25:01.161  3750  3750 I BluetoothServiceJni: cleanupNative: return from cleanup
08-25 03:25:01.161  3750  3750 I art     : --- WEIRD: removing null entry 246
08-25 03:25:01.161  3750  3750 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-25 03:25:01.161  3750  3750 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-25 03:25:01.163  1586  1586 D BluetoothAdapter: 995547574: getState() :  mService = null. Returning STATE_OFF
08-25 03:25:01.163  1586  1586 D BluetoothAdapter: 995547574: getState() :  mService = null. Returning STATE_OFF
08-25 03:25:01.163  3750  3750 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-25 03:25:01.164  6383  6404 V FormManager: Network unavailable.
08-25 03:25:01.165  3750  3750 I art     : System.exit called, status: 0
08-25 03:25:01.165  3750  3750 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-25 03:25:01.166  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 03:25:01.172  6383  6404 V FormManager: Network unavailable.
,08-25 03:25:01.183  6274  6274 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 03:25:01.183  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 03:25:01.183  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 03:25:01.183  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 03:25:01.183  6274  6274 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 03:25:01.183  6274  6274 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 03:25:01.184  6274  6274 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 03:25:01.185  6274  6274 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-25 03:25:01.185  6274  6274 D LGBluetoothEventManager: [BTUI] clear device connection state
08-25 03:25:01.186  1069  1672 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!
08-25 03:25:01.187   310  1382 V AudioFlinger: 3750 died, releasing its sessions
08-25 03:25:01.187   310  1382 V AudioFlinger:  pid 1836 @ 0
08-25 03:25:01.187   310  1382 V AudioFlinger:  pid 3384 @ 1
08-25 03:25:01.187   310  1382 V AudioFlinger:  pid 3384 @ 2
08-25 03:25:01.188  6274  6274 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 03:25:01.190  1069  1672 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.android.bluetooth/com.android.bluetooth.pbap.BluetoothPbapReceiver}
08-25 03:25:01.190  1069  1672 W BroadcastQueue: android.os.DeadObjectException
08-25 03:25:01.190  1069  1672 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
08-25 03:25:01.190  1069  1672 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:496)
08-25 03:25:01.190  1069  1672 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:857)
08-25 03:25:01.190  1069  1672 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:252)
08-25 03:25:01.190  1069  1672 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:939)
08-25 03:25:01.190  1069  1672 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:16582)
08-25 03:25:01.190  1069  1672 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:473)
08-25 03:25:01.190  1069  1672 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
08-25 03:25:01.190  1069  1672 W BroadcastQueue: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
08-25 03:25:01.190  1069  1672 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:446)
,08-25 03:25:01.211  1069  1672 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-25 03:25:01.267  1069  1672 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=6414 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-25 03:25:01.273  6274  6274 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-25 03:25:01.273  1069  1701 W ActivityManager: Spurious death for ProcessRecord{39fab956 6414:com.android.bluetooth/1002}, curProc for 3750: null
08-25 03:25:01.279  4207  4207 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
,08-25 03:25:01.280  4207  4207 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 03:25:01.280  6274  6274 D DockEventReceiver: finishStartingService: stopping service
08-25 03:25:01.282  1069  1996 I ActivityManager: Killing 5783:com.android.contacts/u0a19 (adj 15): empty #17
08-25 03:25:01.294  4207  4207 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 03:25:01.305   344   344 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 470us total 35.047ms
,08-25 03:25:01.326   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 440us total 20.452ms
,08-25 03:25:01.346   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 411us total 19.382ms
,08-25 03:25:01.363  1069  1896 W libprocessgroup: failed to open /acct/uid_10019/pid_5783/cgroup.procs: No such file or directory
,08-25 03:25:01.365  4207  4207 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 03:25:01.384  6294  6294 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-25 03:25:01.384  6294  6294 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 03:25:01.384  6294  6294 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 03:25:01.389  4207  6432 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 03:25:01.390  4207  6433 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 03:25:01.391  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 03:25:01.394  6414  6414 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-25 03:25:01.394  6414  6414 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 03:25:01.395  6414  6414 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-25 03:25:01.395  6414  6414 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-25 03:25:01.395  4207  6433 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-25 03:25:01.405  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:01.406  6383  6436 W FormManager: Network not available. Please check & try again.
08-25 03:25:01.418  6383  6437 V FormManager: Network unavailable.
08-25 03:25:01.419  6414  6414 D BluetoothAdapterApp: Loading JNI Library
,08-25 03:25:01.421  6383  6437 V FormManager: Network unavailable.
08-25 03:25:01.422  6343  6343 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-25 03:25:01.423  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-25 03:25:01.423  6343  6343 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-25 03:25:01.457  6414  6414 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@172ecb74 Instance Count = 1
,08-25 03:25:01.458  6343  6343 D LgDataFeature: LgDataFeature() Constructor: none
08-25 03:25:01.459  6343  6343 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 03:25:01.462  6414  6414 D BluetoothAdapterApp: onCreate
08-25 03:25:01.466  6343  6343 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-25 03:25:01.467  6343  6343 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-25 03:25:01.467  6343  6343 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-25 03:25:01.467  6343  6343 V SoundPool: doLoad: loading sample sampleID=1
08-25 03:25:01.467  6343  6343 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-25 03:25:01.468  6343  6440 V SoundPool: Start decode
08-25 03:25:01.468  6343  6440 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-25 03:25:01.471   310  2157 V MediaPlayerService: decode(23, 10857164, 17813)
08-25 03:25:01.471   310  2157 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-25 03:25:01.471   310  2157 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-25 03:25:01.471   310  2157 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-25 03:25:01.471   310  2157 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-25 03:25:01.471   310  2157 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-25 03:25:01.471  6041  6041 D UEI.SmartControl: QS Service created
08-25 03:25:01.471   310  2157 V MediaPlayerService: player type = 3
08-25 03:25:01.471   310  2157 V AwesomePlayer: AwesomePlayer create()
08-25 03:25:01.471   310  2157 V AwesomePlayer: reset_l() 
08-25 03:25:01.471   310  2157 V AwesomePlayer: cancelPlayerEvents
08-25 03:25:01.472   310  2157 V AwesomePlayer: setAudioSink() 
08-25 03:25:01.472   310  2157 V AwesomePlayer: reset_l() 
08-25 03:25:01.472   310  2157 V AudioCache: notify(0xb5474a80, 8, 0, 0)
08-25 03:25:01.472   310  2157 V AudioCache: ignored
08-25 03:25:01.472   310  2157 V AwesomePlayer: cancelPlayerEvents
08-25 03:25:01.472   310  2157 D Utils   : printFileName fd(24) -> /data/preload/LGQRemote/LGQRemote.apk
08-25 03:25:01.472   310  2157 V AwesomePlayer: setDataSource_l dataSource
08-25 03:25:01.472   310  2157 V LGParserOSAL: SniffLGParser start
08-25 03:25:01.472   310  2157 V LGParserOSAL: MainType:5, SubType=0
08-25 03:25:01.472   310  2157 V LGParserOSAL: #### check Mime : application/ogg
08-25 03:25:01.472   310  2157 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-25 03:25:01.472   310  2157 E MediaExtractor: Use LGExtractor :application/ogg 
,08-25 03:25:01.477  6343  6343 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-25 03:25:01.480  6343  6343 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 03:25:01.481  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-25 03:25:01.485  6041  6041 I UEI.SmartControl: Service initServices...
08-25 03:25:01.486  6041  6041 D UEI.SmartControl: QS start get config
08-25 03:25:01.497  6343  6343 V LGMDMManager: Create singleton instance
,08-25 03:25:01.500   310  2157 V LGParserOSAL: supported mime: application/ogg
08-25 03:25:01.500   310  2157 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-25 03:25:01.500   310  2157 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-25 03:25:01.500   310  2157 V AwesomePlayer: mBitrate = -1 bits/sec
08-25 03:25:01.500   310  2157 V AwesomePlayer: AudioTrack Setting
08-25 03:25:01.500   310  2157 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-25 03:25:01.500   310  2157 V AwesomePlayer: setAudioSource() 
08-25 03:25:01.500   310  2157 V MediaPlayerService: prepare
08-25 03:25:01.500   310  2157 V AwesomePlayer: prepareAsync_l() 
08-25 03:25:01.500   310  2157 V MediaPlayerService: wait for prepare
08-25 03:25:01.500   310  6442 V AwesomePlayer: onPrepareAsyncEvent() 
08-25 03:25:01.500   310  6442 V AwesomePlayer: initAudioDecoder() 
08-25 03:25:01.500   310  6442 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 03:25:01.500   310  6442 V AudioSystem: isOffloadSupported()
08-25 03:25:01.500   310  6442 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 03:25:01.500   310  6442 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 03:25:01.500   310  6442 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 03:25:01.500   310  6442 V AwesomePlayer: getUseOffload() = 0 
08-25 03:25:01.500   310  6442 V OMXCodec: OMXCodec::Create
08-25 03:25:01.500   310  6442 V OMXCodec: findMatchingCodecs()
08-25 03:25:01.500  6414  6414 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-25 03:25:01.500   310  6442 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-25 03:25:01.500   310  6442 V OMXCodec: matchingCodecs.size()=1
08-25 03:25:01.500   310  6442 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-25 03:25:01.501  6414  6414 D ProfileConfigQcom: Adding HeadsetService
08-25 03:25:01.501  6414  6414 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-25 03:25:01.501  6414  6414 D ProfileConfigQcom: Adding A2dpService
08-25 03:25:01.501  6414  6414 D ProfileConfigQcom: [BTUI] HidService is supported
08-25 03:25:01.501  6414  6414 D ProfileConfigQcom: Adding HidService
08-25 03:25:01.501  6414  6414 D ProfileConfigQcom: [BTUI] HealthService is supported
08-25 03:25:01.502  6414  6414 D ProfileConfigQcom: Adding HealthService
08-25 03:25:01.502  6414  6414 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-25 03:25:01.502   310  6442 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-25 03:25:01.502   310  6442 V LGCodecAdapter: LG Codec Adapter start
08-25 03:25:01.502   310  6442 V OMXCodec: OMXCodec Createtor
08-25 03:25:01.502   310  6442 V OMXCodec: setComponentRole
08-25 03:25:01.502   310  6442 V OMXCodec: configureCodec protected=0
08-25 03:25:01.502   310  6442 V LGCodecAdapter: called getLGCodecSpecificData
08-25 03:25:01.502   310  6442 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-25 03:25:01.502   310  6442 V LGCodecOSAL: Called LGconfigureCodecMETA
08-25 03:25:01.502   310  6442 V LGCodecOSAL: Called LGconfigureCodecMSG
08-25 03:25:01.502   310  6442 V LGCodecOSAL: Not support LGCodec
08-25 03:25:01.502   310  6442 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 03:25:01.502   310  6442 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-25 03:25:01.502   310  6442 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-25 03:25:01.502   310  6442 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-25 03:25:01.502   310  6442 W Utils   : bool android::can,OffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-25 03:25:01.502   310  6442 V AudioSystem: isOffloadSupported()
08-25 03:25:01.503   310  6442 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-25 03:25:01.503   310  6442 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-25 03:25:01.503   310  6442 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-25 03:25:01.503   310  6442 V OMXCodec: init()
08-25 03:25:01.503   310  6442 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=2
08-25 03:25:01.503   310  6442 V OMXCodec: allocateBuffers
08-25 03:25:01.503   310  6442 V OMXCodec: allocateBuffersOnPort portIndex=0
08-25 03:25:01.503   310  6442 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-25 03:25:01.503   310  6442 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on input port
08-25 03:25:01.503   310  6442 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f78d0 on input port
08-25 03:25:01.503   310  6442 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a10 on input port
08-25 03:25:01.503   310  6442 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7bf0 on input port
08-25 03:25:01.503   310  6442 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 03:25:01.503   310  6442 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 03:25:01.503   310  6442 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-25 03:25:01.503   310  6442 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
08-25 03:25:01.503   310  6442 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
08-25 03:25:01.503   310  6442 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
08-25 03:25:01.503   310  6442 V OMXCodec: init() mAsyncCompletion wait!!! 
08-25 03:25:01.503   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 03:25:01.503   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 03:25:01.503   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-25 03:25:01.503   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-25 03:25:01.503   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-25 03:25:01.503   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-25 03:25:01.504   310  6442 V OMXCodec: init() mAsyncCompletion wait free! 
08-25 03:25:01.504   310  6442 V AwesomePlayer: finishAsyncPrepare_l() 
08-25 03:25:01.504   310  6442 V AudioCache: notify(0xb5474a80, 5, 0, 0)
08-25 03:25:01.504   310  6442 V AudioCache: ignored
08-25 03:25:01.504   310  6442 V AudioCache: notify(0xb5474a80, 1, 0, 0)
08-25 03:25:01.504   310  6442 V AudioCache: prepared
08-25 03:25:01.504   310  2157 V AudioCache: wait - success
08-25 03:25:01.504   310  2157 V MediaPlayerService: start
08-25 03:25:01.504   310  2157 V AwesomePlayer: play_l() 
08-25 03:25:01.504   310  2157 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-25 03:25:01.504   310  2157 V AwesomePlayer: createAudioPlayer_l
08-25 03:25:01.504   310  2157 V AwesomePlayer: seekAudioIfNecessary_l() 
08-25 03:25:01.504   310  2157 V AwesomePlayer: startAudioPlayer_l() 
08-25 03:25:01.504   310  2157 D AudioPlayer: start of Playback, useOffload 0
08-25 03:25:01.504   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 03:25:01.504   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-25 03:25:01.505  6414  6414 D ProfileConfigQcom: [BTUI] PanService is supported
08-25 03:25:01.505  6414  6414 D ProfileConfigQcom: Adding PanService
08-25 03:25:01.505  6414  6414 D ProfileConfigQcom: [BTUI] GattService is supported
08-25 03:25:01.505  6414  6414 D ProfileConfigQcom: Adding GattService
08-25 03:25:01.505   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-25 03:25:01.505   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-25 03:25:01.505   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-25 03:25:01.505  6414  6414 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-25 03:25:01.505   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-25 03:25:01.505   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-25 03:25:01.505   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 03:25:01.506  6414  6414 D ProfileConfigQcom: Adding BluetoothMapService
08-25 03:25:01.506   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885408
08-25 03:25:01.506   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 03:25:01.506   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885728
08-25 03:25:01.506   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 03:25:01.506   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885808
08-25 03:25:01.506   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 03:25:01.506   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886128
08-25 03:25:01.506   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 03:25:01.506   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-25 03:25:01.506  6414  6414 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-25 03:25:01.506   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-25 03:25:01.506   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-25 03:25:01.506   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-25 03:25:01.506   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-25 03:25:01.506   310  6444 V OMXCodec: allocateBuffersOnPort portIndex=1
08-25 03:25:01.506   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-25 03:25:01.506   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e70 on output port
08-25 03:25:01.506   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7e20 on output port
08-25 03:25:01.506   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ce0 on output port
08-25 03:25:01.506   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb14342e0 on output port
08-25 03:25:01.506   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-25 03:25:01.506   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-25 03:25:01.507  6414  6414 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 03:25:01.507   310  2157 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-25 03:25:01.507   310  2157 V AudioCache: notify(0xb5474a80, 6, 0, 0)
08-25 03:25:01.507   310  2157 V AudioCache: ignored
08-25 03:25:01.508  6414  6414 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:01.508   310  2157 V MediaPlayerService: wait for playback complete
08-25 03:25:01.508  6414  6414 V BluetoothPbapReceiver: ***********state = 10
08-25 03:25:01.508   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.508   310  6445 V AudioCache: memcpy(0xaf006000, 0xb16e0000, 4096)
08-25 03:25:01.509   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.509  6414  6414 V LGMDMManagerInternal: Create singleton instance
08-25 03:25:01.509   310  6445 V AudioCache: memcpy(0xaf007000, 0xb16e0000, 4096)
08-25 03:25:01.510   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.510   310  6445 V AudioCache: memcpy(0xaf008000, 0xb16e0000, 4096)
08-25 03:25:01.510   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.510   310  6445 V AudioCache: memcpy(0xaf009000, 0xb16e0000, 4096)
08-25 03:25:01.510   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.511   310  6445 V AudioCache: memcpy(0xaf00a000, 0xb16e0000, 4096)
08-25 03:25:01.511   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.511   310  6445 V AudioCache: memcpy(0xaf00b000, 0xb16e0000, 4096)
08-25 03:25:01.511   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.511   310  6445 V AudioCache: memcpy(0xaf00c000, 0xb16e0000, 4096)
08-25 03:25:01.512   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.512   310  6445 V AudioCache: memcpy(0xaf00d000, 0xb16e0000, 4096)
08-25 03:25:01.512   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.512   310  6445 V AudioCache: memcpy(0xaf00e000, 0xb16e0000, 4096)
08-25 03:25:01.513   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.513   310  6445 V AudioCache: memcpy(0xaf00f000, 0xb16e0000, 4096)
08-25 03:25:01.513   310  6445 V AudioCache: write(0xb16e0000, 4096)
,08-25 03:25:01.513   310  6445 V AudioCache: memcpy(0xaf010000, 0xb16e0000, 4096)
08-25 03:25:01.513   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.513   310  6445 V AudioCache: memcpy(0xaf011000, 0xb16e0000, 4096)
08-25 03:25:01.514   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.514   310  6445 V AudioCache: memcpy(0xaf012000, 0xb16e0000, 4096)
08-25 03:25:01.514   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.514   310  6445 V AudioCache: memcpy(0xaf013000, 0xb16e0000, 4096)
08-25 03:25:01.514   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.514   310  6445 V AudioCache: memcpy(0xaf014000, 0xb16e0000, 4096)
08-25 03:25:01.515   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.515   310  6445 V AudioCache: memcpy(0xaf015000, 0xb16e0000, 4096)
08-25 03:25:01.515   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.515   310  6445 V AudioCache: memcpy(0xaf016000, 0xb16e0000, 4096)
08-25 03:25:01.515   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.516   310  6445 V AudioCache: memcpy(0xaf017000, 0xb16e0000, 4096)
08-25 03:25:01.516   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.516   310  6445 V AudioCache: memcpy(0xaf018000, 0xb16e0000, 4096)
08-25 03:25:01.516   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.516   310  6445 V AudioCache: memcpy(0xaf019000, 0xb16e0000, 4096)
08-25 03:25:01.517   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.517   310  6445 V AudioCache: memcpy(0xaf01a000, 0xb16e0000, 4096)
08-25 03:25:01.517   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.517   310  6445 V AudioCache: memcpy(0xaf01b000, 0xb16e0000, 4096)
08-25 03:25:01.517   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.517   310  6445 V AudioCache: memcpy(0xaf01c000, 0xb16e0000, 4096)
08-25 03:25:01.518   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.518   310  6445 V AudioCache: memcpy(0xaf01d000, 0xb16e0000, 4096)
08-25 03:25:01.518   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.518   310  6445 V AudioCache: memcpy(0xaf01e000, 0xb16e0000, 4096)
08-25 03:25:01.519   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.519   310  6445 V AudioCache: memcpy(0xaf01f000, 0xb16e0000, 4096)
08-25 03:25:01.519   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.519   310  6445 V AudioCache: memcpy(0xaf020000, 0xb16e0000, 4096)
08-25 03:25:01.519   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.519   310  6445 V AudioCache: memcpy(0xaf021000, 0xb16e0000, 4096)
08-25 03:25:01.519   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.519   310  6445 V AudioCache: memcpy(0xaf022000, 0xb16e0000, 4096)
08-25 03:25:01.520   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.520   310  6445 V AudioCache: memcpy(0xaf023000, 0xb16e0000, 4096)
08-25 03:25:01.520   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.520   310  6445 V AudioCache: memcpy(0xaf024000, 0xb16e0000, 4096)
08-25 03:25:01.520   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.520   310  6445 V AudioCache: memcpy(0xaf025000, 0xb16e0000, 4096)
08-25 03:25:01.520   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.520   310  6445 V AudioCache: memcpy(0xaf026000, 0xb16e0000, 4096)
08-25 03:25:01.521   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.521   310  6445 V AudioCache: memcpy(0xaf027000, 0xb16e0000, 4096)
08-25 03:25:01.522   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.522   310  6445 V AudioCache: memcpy(0xaf028000, 0xb16e0000, 4096)
08-25 03:25:01.522   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.522   310  6445 V AudioCache: memcpy(0xaf029000, 0xb16e0000, 4096)
08-25 03:25:01.522   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.522   310  6445 V AudioCache: memcpy(0xaf02a000, 0xb16e0000, 4096)
08-25 03:25:01.523   310  6445 V Au,dioCache: write(0xb16e0000, 4096)
08-25 03:25:01.523   310  6445 V AudioCache: memcpy(0xaf02b000, 0xb16e0000, 4096)
08-25 03:25:01.523   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.523   310  6445 V AudioCache: memcpy(0xaf02c000, 0xb16e0000, 4096)
08-25 03:25:01.523   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.523   310  6445 V AudioCache: memcpy(0xaf02d000, 0xb16e0000, 4096)
08-25 03:25:01.523   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.523   310  6445 V AudioCache: memcpy(0xaf02e000, 0xb16e0000, 4096)
08-25 03:25:01.524   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.524   310  6445 V AudioCache: memcpy(0xaf02f000, 0xb16e0000, 4096)
08-25 03:25:01.524   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.524   310  6445 V AudioCache: memcpy(0xaf030000, 0xb16e0000, 4096)
08-25 03:25:01.524   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.524   310  6445 V AudioCache: memcpy(0xaf031000, 0xb16e0000, 4096)
08-25 03:25:01.525   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.525   310  6445 V AudioCache: memcpy(0xaf032000, 0xb16e0000, 4096)
08-25 03:25:01.525   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.525   310  6445 V AudioCache: memcpy(0xaf033000, 0xb16e0000, 4096)
08-25 03:25:01.526   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.526   310  6445 V AudioCache: memcpy(0xaf034000, 0xb16e0000, 4096)
08-25 03:25:01.526   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.526   310  6445 V AudioCache: memcpy(0xaf035000, 0xb16e0000, 4096)
08-25 03:25:01.526   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.526   310  6445 V AudioCache: memcpy(0xaf036000, 0xb16e0000, 4096)
08-25 03:25:01.527   310  6445 V AudioCache: write(0xb16e0000, 4096)
08-25 03:25:01.527   310  6445 V AudioCache: memcpy(0xaf037000, 0xb16e0000, 4096)
08-25 03:25:01.527   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-25 03:25:01.527   310  6445 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-25 03:25:01.527   310  6445 V AwesomePlayer: postAudioEOS() 
08-25 03:25:01.527   310  6445 V AudioCache: write(0xb16e0000, 280)
08-25 03:25:01.527   310  6445 V AudioCache: memcpy(0xaf038000, 0xb16e0000, 280)
08-25 03:25:01.530   310  6442 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-25 03:25:01.530   310  6442 V AwesomePlayer: onStreamDone
08-25 03:25:01.530   310  6442 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-25 03:25:01.530   310  6442 V AudioCache: notify(0xb5474a80, 2, 0, 0)
08-25 03:25:01.530   310  6442 V AudioCache: playback complete
08-25 03:25:01.530   310  6442 V AwesomePlayer: pause_l() 
08-25 03:25:01.530   310  6442 V AudioCache: notify(0xb5474a80, 7, 0, 0)
08-25 03:25:01.530   310  2157 V AudioCache: wait - success
08-25 03:25:01.530   310  6442 V AudioCache: ignored
,08-25 03:25:01.530   310  6442 V AwesomePlayer: cancelPlayerEvents
08-25 03:25:01.530   310  2157 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-25 03:25:01.530   310  6442 D AudioPlayer: Pause Playback at 1068125
08-25 03:25:01.531   310  2157 V AwesomePlayer: reset_l() 
08-25 03:25:01.531   310  2157 V AudioCache: notify(0xb5474a80, 8, 0, 0)
08-25 03:25:01.531   310  2157 V AudioCache: ignored
08-25 03:25:01.531   310  2157 V AwesomePlayer: cancelPlayerEvents
08-25 03:25:01.531   310  2157 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-25 03:25:01.531   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-25 03:25:01.531   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-25 03:25:01.531   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-25 03:25:01.531   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 03:25:01.531   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-25 03:25:01.531   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-25 03:25:01.531   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-25 03:25:01.531   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7bf0 on port 0
,08-25 03:25:01.531   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-25 03:25:01.531   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a10 on port 0
08-25 03:25:01.531   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-25 03:25:01.531   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f78d0 on port 0
08-25 03:25:01.531   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-25 03:25:01.531   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 0
08-25 03:25:01.531   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-25 03:25:01.531   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-25 03:25:01.531   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb14342e0 on port 1
08-25 03:25:01.531   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-25 03:25:01.532   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ce0 on port 1
08-25 03:25:01.532   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-25 03:25:01.532   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e20 on port 1
08-25 03:25:01.532   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-25 03:25:01.532   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7e70 on port 1
08-25 03:25:01.532   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-25 03:25:01.532   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-25 03:25:01.532   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-25 03:25:01.532   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-25 03:25:01.532   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-25 03:25:01.532   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-25 03:25:01.532   310  6444 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-25 03:25:01.532   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
,08-25 03:25:01.532   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-25 03:25:01.532   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-25 03:25:01.533   310  2157 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-25 03:25:01.533   310  2157 D AudioPlayer: AudioPlayer releasing audio source
08-25 03:25:01.533   310  2157 D AudioPlayer: AudioPlayer done releasing audio source
08-25 03:25:01.533   310  2157 V AwesomePlayer: reset_l() 
08-25 03:25:01.533   310  2157 V AwesomePlayer: cancelPlayerEvents
08-25 03:25:01.533   310  2157 V AwesomePlayer: ~AwesomePlayer call
08-25 03:25:01.533   310  2157 V AwesomePlayer: reset_l() 
08-25 03:25:01.533   310  2157 V AwesomePlayer: cancelPlayerEvents
08-25 03:25:01.533  6343  6440 V SoundPool: close(31)
08-25 03:25:01.533  6343  6440 V SoundPool: pointer = 0x9fe47000, size = 205080, sampleRate = 48000, numChannels = 2
08-25 03:25:01.567  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-25 03:25:01.568  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-25 03:25:01.569  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3526
08-25 03:25:01.597  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 03:25:01.605  6274  6274 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-25 03:25:01.608  6274  6274 D BluetoothPermissionRequest: onReceive
08-25 03:25:01.610  6274  6274 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 03:25:01.611  6274  6274 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-25 03:25:01.614  6274  6274 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 03:25:01.616  6414  6414 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
08-25 03:25:01.619  6414  6414 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:01.621  6414  6414 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 03:25:01.621  6414  6414 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 03:25:01.621  6414  6414 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 03:25:01.622  6414  6414 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:01.622  6414  6414 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-25 03:25:01.628  6363  6363 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-25 03:25:01.813  6041  6041 I UEI.SmartControl: Supports setup maps: true
08-25 03:25:01.815  6041  6041 D UEI.SmartControl: QS start statue = true Error code = 0
08-25 03:25:01.816  6041  6041 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-25 03:25:01.816  6041  6041 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-25 03:25:01.816  6041  6041 I UEI.SmartControl: ### init IR Blaster...
,08-25 03:25:01.818  6041  6041 D serial_port: Configuring serial port
,08-25 03:25:01.819  6041  6041 E UEI.SmartControl: UEIBLaster setting for 616
08-25 03:25:01.819  6041  6041 I UEI.SmartControl: Setting serial record hearder size = 2
08-25 03:25:01.819  6041  6041 I UEI.SmartControl: configuring settings for MAXQ616
08-25 03:25:01.819  6041  6041 I UEI.SmartControl: Get version...
08-25 03:25:01.838  6041  6447 D UEI.SmartControl: serial port data available: 21
,08-25 03:25:01.865  6041  6041 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-25 03:25:01.865  6041  6041 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-25 03:25:01.865  6041  6041 I UEI.SmartControl: QS saving settings...
08-25 03:25:01.867  6041  6041 D UEI.SmartControl: IR Blaster version: 25672567
,08-25 03:25:01.884  6041  6447 D UEI.SmartControl: serial port data available: 4
,08-25 03:25:01.915  6041  6453 I UEI.SmartControl: Device manager: loading config....
08-25 03:25:01.915  6041  6453 D UEI.SmartControl: ----------- loading internal config...
08-25 03:25:01.916  6041  6041 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-25 03:25:01.920  6041  6041 E UEI.SmartControl: Services init done
,08-25 03:25:01.921  6041  6041 D UEI.SmartControl: QS Service init finished
08-25 03:25:01.923  6041  6041 D UEI.SmartControl: QS Service version name: 2.1.91
08-25 03:25:01.923  6041  6041 D UEI.SmartControl: QS Service version code: 201091
08-25 03:25:01.924  6041  6453 E UEI.SmartControl: Loading SETTINGS...
08-25 03:25:01.924  6041  6041 D UEI.SmartControl: Service requested: Control
08-25 03:25:01.927  6343  6343 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-25 03:25:01.928  6041  6041 D UEI.SmartControl: Internal service binding...
08-25 03:25:01.930  6041  6056 I UEI.SmartControl: ------ IControl API: 11
08-25 03:25:01.930  6041  6453 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-25 03:25:01.930  6041  6056 D UEI.SmartControl: File observer start...
08-25 03:25:01.931  6041  6056 E UEI.SmartControl: IR Port is disabled: false
08-25 03:25:01.931  6041  6056 D UEI.SmartControl: Starting file observer...
08-25 03:25:01.934  6041  6056 I UEI.SmartControl: Registering callback...
,08-25 03:25:01.937  6041  6057 I UEI.SmartControl: ------ IControl API: 19
08-25 03:25:01.940  6041  6057 I UEI.SmartControl: Registering Services Ready callback...
08-25 03:25:01.940  6041  6057 I UEI.SmartControl: Notify client services are ready...
08-25 03:25:01.941  6343  6361 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-25 03:25:01.941  6343  6438 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-25 03:25:01.941  6343  6438 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-25 03:25:01.942  6343  6343 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-25 03:25:01.943  6343  6343 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-25 03:25:01.943  6041  6056 I UEI.SmartControl: ------ IControl API: 8
08-25 03:25:01.947  6343  6343 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
,08-25 03:25:01.947  6343  6343 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-25 03:25:01.948  6343  6343 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-25 03:25:01.949  6343  6343 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-25 03:25:01.950  6343  6343 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-25 03:25:01.951  6343  6343 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-25 03:25:01.953  6041  6452 I UEI.SmartControl: Notify AllClients services are ready: 0
08-25 03:25:01.953  6041  6452 D UEI.SmartControl: -----service ready thread exits
08-25 03:25:01.953  6343  6362 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-25 03:25:01.954  6343  6343 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-25 03:25:01.954  6343  6438 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-25 03:25:01.954  6343  6438 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-25 03:25:01.957  6343  6343 D QRemote : [RemoteControlManager.java:327:handleMessage()] oooooo 140510:retrieveDevices already complete. Do nothing
08-25 03:25:01.958  6343  6343 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-25 03:25:01.959  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-25 03:25:01.960  6343  6343 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 03:25:01.960  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-25 03:25:01.961  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-25 03:25:01.965  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-25 03:25:01.965  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-25 03:25:01.966  6343  6343 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472088301966]
08-25 03:25:01.969  6343  6343 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-25 03:25:01.973  1069  1559 I ActivityManager: Killing 5843:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-25 03:25:02.004  6343  6455 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-25 03:25:02.011  1069  1559 I ActivityManager: Killing 5810:com.lge.email/u0a23 (adj 15): empty #18
,08-25 03:25:02.114  1069  1918 W libprocessgroup: failed to open /acct/uid_10027/pid_5843/cgroup.procs: No such file or directory
,08-25 03:25:02.132  1069  2611 W libprocessgroup: failed to open /acct/uid_10023/pid_5810/cgroup.procs: No such file or directory
08-25 03:25:02.133  6343  6343 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-25 03:25:02.135  6343  6343 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 03:25:02.136  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-25 03:25:02.137  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-25 03:25:02.138  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-25 03:25:02.138  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-25 03:25:02.139  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-25 03:25:02.163  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-25 03:25:03.223  1069  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=506181987, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1069
,08-25 03:25:03.272  2563  2563 D [Concierge]Service: onStartCommand(). Type : 9
,08-25 03:25:03.299  1069  1069 D PowerManagerServiceEx: releaseWakeLockInternal: lock=506181987 [*alarm*], flags=0x0
,08-25 03:25:04.801  1069  1374 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:04.801  1069  1374 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 03:25:04.859  1069  1097 D WifiServiceImplEx: setWifiEnabled: true pid=6126, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-25 03:25:04.866  1069  1097 D WifiService: setWifiEnabled: true pid=6126, uid=10118
08-25 03:25:04.866  1069  1097 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 03:25:04.898  1069  1069 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 03:25:04.898  1069  1069 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 03:25:04.898  1069  1069 D Ulp_jni : JNI:system_update. Event-4
08-25 03:25:04.899  1069  1376 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-25 03:25:04.899  1069  1376 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-25 03:25:04.902  1069  1376 E WifiUtil: wfc_util_ffile_check_copy(): pid[1069] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-25 03:25:04.902  1069  1376 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 03:25:04.902  1069  1376 E WifiUtil: wfc_util_ffile_check_copy(): pid[1069] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-25 03:25:04.902  1069  1376 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 03:25:04.902  1069  1376 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-25 03:25:04.902  1069  1376 E WifiHW  : unknown target_country: EU , set to default
08-25 03:25:04.902  1069  1376 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-25 03:25:04.902  1069  1376 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-25 03:25:04.902  1069  1376 I WifiUtil: gEnableBmps=1
08-25 03:25:05.542   306   911 D SoftapController: Softap fwReload - Ok
,08-25 03:25:05.547  1069  1376 E NetdConnector: NDC Command {37 softap fwreload wlan0 STA} took too long (640ms)
08-25 03:25:05.550   306   911 D CommandListener: Setting iface cfg
08-25 03:25:05.550   306   911 D CommandListener: Trying to bring down wlan0
08-25 03:25:05.555  1069  1176 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,08-25 03:25:05.577   306   911 D CommandListener: Clearing all IP addresses on wlan0
08-25 03:25:05.578   306  6475 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-25 03:25:05.582  1069  1174 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,08-25 03:25:05.584  1069  1376 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-25 03:25:05.588  6476  6476 W wpa_supplicant: type=1400 audit(0.0:163): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 03:25:05.588  6476  6476 W wpa_supplicant: type=1400 audit(0.0:164): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:05.597  1069  1376 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 03:25:05.597  1069  1376 E WifiStateMachine: useWiFiOffloading() : false
08-25 03:25:05.597  1069  1376 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 03:25:05.601  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:05.621  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
,08-25 03:25:05.642  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:25:05.650  1069  1069 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-25 03:25:05.650  1069  1376 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-25 03:25:05.650  1069  1376 D WifiMonitor: connecting to supplicant
08-25 03:25:05.652  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:05.653  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:05.654  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 03:25:05.654  6274  6274 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 03:25:05.654  6274  6274 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 03:25:05.654  6274  6274 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 03:25:05.654  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 03:25:05.655  6274  6274 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 03:25:05.655  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-25 03:25:05.655  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 03:25:05.655  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 03:25:05.655  6274  6274 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 03:25:05.656  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-25 03:25:05.656  6274  6274 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 03:25:05.670  6294  6294 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 03:25:05.682  6476  6476 I wpa_supplicant: Successfully initialized wpa_supplicant
08-25 03:25:05.683  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 03:25:05.690  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 03:25:05.701  6383  6495 W FormManager: Network not available. Please check & try again.
08-25 03:25:05.706  6383  6496 V FormManager: Network unavailable.
,08-25 03:25:05.711  6383  6496 V FormManager: Network unavailable.
,08-25 03:25:05.722  6476  6476 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-25 03:25:05.723  6476  6476 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-25 03:25:05.726  1069  1176 D Tethering: InitialState.processMessage what=4
08-25 03:25:05.727  1069  1176 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 03:25:05.729  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 03:25:05.729  6274  6274 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 03:25:05.729  6274  6274 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 03:25:05.729  6274  6274 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 03:25:05.729  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 03:25:05.730  6274  6274 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 03:25:05.730  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 03:25:05.730  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 03:25:05.730  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 03:25:05.730  6274  6274 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 03:25:05.730  6274  6274 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 03:25:05.779  6476  6476 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 03:25:05.804  6476  6476 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-25 03:25:05.811  6476  6476 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-25 03:25:05.811  1069  1376 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-25 03:25:05.812  1069  1376 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-25 03:25:05.812  1069  1376 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-25 03:25:05.812  1069  1376 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-25 03:25:05.813  1069  1376 E WifiStateMachine:  SupplicantStartingState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 03:25:05.813  1069  6497 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-25 03:25:05.813  1069  6497 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 03:25:05.813  1069  1376 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-25 03:25:05.814  1069  1376 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 03:25:05.814  1069  1376 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 03:25:05.815  1069  1376 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 03:25:05.815  1069  1376 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 03:25:05.816  1069  1376 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-25 03:25:05.816  1069  1376 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-25 03:25:05.816  1069  1376 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-25 03:25:05.816  1069  1376 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-25 03:25:05.816  1069  1376 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-25 03:25:05.817  1069  1376 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 03:25:05.817  1069  1376 E WifiStateMachine: useWiFiOffloading() : false
08-25 03:25:05.817  1069  1376 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 03:25:05.817  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:05.817  1069  1376 D WifiNative-wlan0: doBoolean: SET update_config 1
08-25 03:25:05.817  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:05.818  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:05.818  1069  1376 D WifiNative-wlan0: SET update_config 1: returned true
08-25 03:25:05.818  1069  1376 D WifiConfigStore: Loading config and enabling all networks 
08-25 03:25:05.818  1069  1376 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-25 03:25:05.818  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:05.818  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 03:25:05.818  1069  1376 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-25 03:25:05.819  1925  1925 D WfdService: Waiting for WifiP2p enabling
,08-25 03:25:05.824  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:05.825  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:05.825  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:05.825  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:05.825  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:05.825  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:25:05.825  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:25:05.825  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:25:05.825  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:25:05.825  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:25:05.825  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:05.825  6126  6126 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:25:05.829  1069  1376 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-25 03:25:05.831  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-25 03:25:05.831  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:05.831  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:05.831  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:05.831  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:25:05.831  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:25:05.831  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:25:05.831  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:25:05.831  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:25:05.831  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:05.832  6126  6126 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:25:05.834  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:05.834  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:05.834  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:05.834  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:05.834  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:25:05.834  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:25:05.834  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:25:05.834  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:25:05.834  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:25:05.834  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:05.834  6126  6126 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:25:05.842  6294  6294 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 03:25:05.843  1069  1069 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
,08-25 03:25:05.844  1069  1425 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-25 03:25:05.851  1069  1376 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,08-25 03:25:05.851  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 03:25:05.852  1069  1376 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-25 03:25:05.852  1069  6497 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 03:25:05.852  1069  6497 E WifiMonitor: WifiMonitor:wlan0 cnt=14 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 03:25:05.852  6476  6476 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-25 03:25:05.853  1069  6497 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-25 03:25:05.853  1069  6497 E WifiMonitor: WifiMonitor:wlan0 cnt=15 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-25 03:25:05.853  1069  6497 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-25 03:25:05.854  1069  6497 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-25 03:25:05.855  1069  1376 D WifiStateMachine: enableVerboseLogging : level 2
08-25 03:25:05.855  1069  1376 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-25 03:25:05.856  1069  1376 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-25 03:25:05.856  1069  1376 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-25 03:25:05.856  1069  1376 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-25 03:25:05.856  1069  1376 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-25 03:25:05.857  1069  1376 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-25 03:25:05.857  6383  6499 W FormManager: Network not available. Please check & try again.
08-25 03:25:05.857  1069  1376 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-25 03:25:05.857  1069  1376 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-25 03:25:05.857  1069  1376 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-25 03:25:05.857  1069  1376 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-25 03:25:05.857  1069  1376 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-25 03:25:05.858  1069  1376 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-25 03:25:05.858  1069  1376 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-25 03:25:05.858  1069  1376 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
,08-25 03:25:05.859  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:05.860  1069  1376 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 03:25:05.860  1069  1376 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-25 03:25:05.861  1069  1376 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-25 03:25:05.861  1069  1376 D WifiNative-HAL: Setting external_sim to 1
08-25 03:25:05.861  1069  1376 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-25 03:25:05.862  1069  1376 D WifiNative-wlan0: SET external_sim 1: returned true
,08-25 03:25:05.862  1069  1376 I WifiNative-HAL: startHal
08-25 03:25:05.862  1069  1376 D wifi    : setting scan oui 0xaf68d120
08-25 03:25:05.862  1069  1376 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 03:25:05.862  1069  1376 I WifiNative-HAL: startHal
08-25 03:25:05.862  1069  1376 D wifi    : setting scan oui 0xaf68d120
08-25 03:25:05.863  1069  1376 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-25 03:25:05.863  1925  1925 D WfdsService: Supplicant Connection state is changed : true
08-25 03:25:05.863  1925  2274 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-25 03:25:05.863  1925  2274 D WfdsService: Set the WFDS Monitor: true
08-25 03:25:05.863  1925  2274 D WfdsMonitor: WfdsMonitorThread create
08-25 03:25:05.863  1069  1376 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-25 03:25:05.863  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-25 03:25:05.863  1925  2274 D WfdsMonitor: WFDS Monitor is created and started
08-25 03:25:05.863  1925  2274 D WfdsService: WiFi: Supplicant connection re-established
08-25 03:25:05.863  6476  6476 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-25 03:25:05.864  1069  1376 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-25 03:25:05.864  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 03:25:05.864  1925  6501 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-25 03:25:05.864  6476  6476 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 03:25:05.864  1069  1376 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 03:25:05.864  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-25 03:25:05.864  1925  6501 E CtrlSupplicant: Succeed to open control connection
08-25 03:25:05.864  6476  6476 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-25 03:25:05.865  1925  6501 E CtrlSupplicant: Succeed to open monitor connection
08-25 03:25:05.865  1069  1376 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-25 03:25:05.865  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 03:25:05.865  6476  6476 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 03:25:05.865  1069  1376 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 03:25:05.865  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 03:25:05.866  6476  6476 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 03:25:05.866  1069  1376 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 03:25:05.866  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-25 03:25:05.866  6476  6476 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-25 03:25:05.866  1069  1376 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-25 03:25:05.866  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 03:25:05.866  6476  6476 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 03:25:05.867  1069  1376 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 03:25:05.868  1069  1376 E WifiNative: : [347,865,051 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-25 03:25:05.868  1069  1376 D WifiNative-wlan0: doBoolean: RECONNECT
08-25 03:25:05.868  1925  6501 D WfdsMonitor: Supplicant connection established
08-25 03:25:05.868  1925  2274 D WfdsService: Connected to the supplicant for wfds
08-25 03:25:05.868  1069  1376 D WifiNative-wlan0: RECONNECT: returned true
08-25 03:25:05.868  1069  1376 D WifiNative-wlan0: doString: [STATUS]
08-25 03:25:05.868  1069  6497 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 03:25:05.868  1069  6497 E WifiMonitor: WifiMonitor:wlan0 cnt=16 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 03:25:05.869  1069  1376 D WifiNative-wlan0:    returned wpa_state=SCANNING, p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 03:25:05.869  1069  1376 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 03:25:05.869  1069  1376 D WifiNative-wlan0: SET ps 1: returned true
08-25 03:25:05.869  1069  1374 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:05.871  6383  6500 V FormManager: Network unavailable.
08-25 03:25:05.871   306   911 D CommandListener: Setting iface cfg
08-25 03:25:05.871   306   911 D CommandListener: Trying to bring up p2p0
08-25 03:25:05.871  1069  1374 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 03:25:05.871  1069  1374 D LGWifiP2pService: P2pEnablingState
08-25 03:25:05.872  1069  1374 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:05.872  1069  1374 D LGWifiP2pService: P2p socket connection successful
08-25 03:25:05.872  1069  1374 D LGWifiP2pService: P2pEnabledState
08-25 03:25:05.872  1069  1069 D WifiScanningService: SCAN_AVAILABLE : 3
08-25 03:25:05.872  1069  1069 D RttService: SCAN_AVAILABLE : 3
08-25 03:25:05.872  1069  1540 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:05.872  1069  1540 I WifiNative-HAL: startHal
08-25 03:25:05.872  1069  1540 D wifi    : getting scan capabilities on interface[1] = 0xaf68d120
08-25 03:25:05.872  1069  1540 D wifi    : failed to get capabilities : -3
08-25 03:25:05.872  1069  1540 E WifiScanningService: could not get scan capabilities
08-25 03:25:05.872  1069  1541 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:05.873  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-25 03:25:05.873  1925  1925 D WfdsService: WifiP2pState is changed : true
08-25 03:25:05.874  1925  2274 D WfdsService: Receive the WFDS_ENABLE Method
08-25 03:25:05.874  1925  2274 D WfdsService: Set the WFDS Monitor: true
08-25 03:25:05.874  1925  2274 D WfdsService: Connected to the supplicant for wfds
08-25 03:25:05.874  1925  2274 D WfdsJNI : doCommand: WFDS_SET TRUE
08-25 03:25:05.874  6476  6476 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-25 03:25:05.874  1069  1376 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-25 03:25:05.874  1925  2274 D WfdsService: selectPreferredScanChannel [36]
08-25 03:25:05.874  1925  2274 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
,08-25 03:25:05.874  1069  1376 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-25 03:25:05.875  1069  1376 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-25 03:25:05.875  1069  1376 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-25 03:25:05.876  1069  1376 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-25 03:25:05.876  1069  1376 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-25 03:25:05.877  1069  1376 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-25 03:25:05.877  1069  1376 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-25 03:25:05.877  6476  6476 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-25 03:25:05.877  1069  1376 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-25 03:25:05.879  1069  1376 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-25 03:25:05.879  1069  1376 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-25 03:25:05.879  1069  1376 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-25 03:25:05.879  6476  6476 E wpa_supplicant: disconnect_rssi_lvl: -100
08-25 03:25:05.880  1069  1376 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=347877  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 03:25:05.882  4207  4207 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 03:25:05.883  1069  1374 D LGWifiP2pService: sending p2p connection changed broadcast
08-25 03:25:05.883  4207  4207 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 03:25:05.883  1069  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 14 0 rt=347881  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-25 03:25:05.884  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:05.884  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 03:25:05.885  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:05.885  1069  1374 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-25 03:25:05.885  1069  1374 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-25 03:25:05.885  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:05.885  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:05.886  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 03:25:05.886  1069  1374 D WifiNative-p2p0: doBoolean: SET device_name G3
08-25 03:25:05.886  1069  1374 D WifiNative-p2p0: SET device_name G3: returned true
08-25 03:25:05.886  1069  1374 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-25 03:25:05.886  1069  1374 D LGWifiP2pService: before postfix = G3
08-25 03:25:05.886  1069  1374 D WifiServerServiceExt: postfix byte check : 2
08-25 03:25:05.886  1069  1374 D LGWifiP2pService: after postfix = G3
08-25 03:25:05.886  1069  1374 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-25 03:25:05.886  1069  1374 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-25 03:25:05.887  1069  1374 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-25 03:25:05.887  1069  1374 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-25 03:25:05.887  1069  1374 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-25 03:25:05.887  1069  1374 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-25 03:25:05.887  1069  1374 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
,08-25 03:25:05.889  1925  1925 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-25 03:25:05.889  4207  4207 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 03:25:05.889  1069  1374 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-25 03:25:05.889  1069  1374 D WifiNative-HAL: p2pGetDeviceAddress
08-25 03:25:05.889  1069  1374 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-25 03:25:05.890  1069  1374 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-25 03:25:05.890  1069  1374 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-25 03:25:05.890  1069  1374 D WifiNative-p2p0: P2P_FLUSH: returned true
08-25 03:25:05.890  1069  1374 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-25 03:25:05.891  1069  1374 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-25 03:25:05.891  1069  1374 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-25 03:25:05.891  1925  1925 D WfdsService: isConnected: false
,08-25 03:25:05.891  1069  1376 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 03:25:05.892  1069  1376 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 03:25:05.892  1925  1925 I WfdStateTracker: handleP2pThisDeviceChanged
08-25 03:25:05.892  1925  1925 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-25 03:25:05.892  1925  1925 D WfdsService: Update P2p Interface State: 3
08-25 03:25:05.892  1069  1376 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-25 03:25:05.892  1069  1374 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-25 03:25:05.892  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-25 03:25:05.892  1069  1374 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-25 03:25:05.893  6476  6476 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 03:25:05.893  6476  6476 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 03:25:05.893  1069  6497 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 03:25:05.893  1069  6497 E WifiMonitor: WifiMonitor:wlan0 cnt=17 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 03:25:05.893  1069  6497 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 03:25:05.893  1069  6497 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 03:25:05.894  6476  6476 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 03:25:05.894  6476  6476 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:05.894  1069  1376 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-25 03:25:05.894  1069  6497 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 03:25:05.894  1069  6497 E WifiMonitor: WifiMonitor:p2p0 cnt=18 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:05.894  1069  6497 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:05.894  1069  6497 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:05.894  1069  1376 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-25 03:25:05.895  6476  6476 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:05.895  1069  6497 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 03:25:05.895  1069  1376 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-25 03:25:05.895  1069  6497 E WifiMonitor: WifiMonitor:p2p0 cnt=19 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:05.895  1069  6497 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:05.895  1069  6497 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:05.895  4207  4207 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 03:25:05.895  1069  1376 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-25 03:25:05.895  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-25 03:25:05.895  6383  6500 V FormManager: Network unavailable.
08-25 03:25:05.895  6476  6476 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-25 03:25:05.895  6476  6476 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 03:25:05.895  1069  6497 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-25 03:25:05.896  1069  6497 E WifiMonitor: WifiMonitor:wlan0 cn,t=20 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 03:25:05.896  1069  6497 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 03:25:05.896  1069  6497 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 03:25:05.895  1925  6501 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 03:25:05.896  1925  6501 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 03:25:05.896  1069  1376 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-25 03:25:05.896  1069  1376 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-25 03:25:05.897  1069  1376 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-25 03:25:05.897  1069  1376 D WifiNative-wlan0: doBoolean: SCAN
08-25 03:25:05.897  1069  1376 D WifiNative-wlan0: SCAN: returned false
08-25 03:25:05.898  1069  1376 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=347896  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-25 03:25:05.901  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 03:25:05.901  4207  6503 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 03:25:05.902  1069  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 16 0 rt=347900  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-25 03:25:05.904  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:05.904  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:05.905  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 03:25:05.905  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:05.906  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 03:25:05.907  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:05.908  1069  1374 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-25 03:25:05.908  1069  1374 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-25 03:25:05.908  1069  1374 D LGWifiP2pService: InactiveState
08-25 03:25:05.908  1069  1374 D LGWifiP2pService: InactiveState{ when=-17ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:05.908  1069  1376 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 03:25:05.908  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-17ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:05.908  1069  1374 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-25 03:25:05.908  1069  1376 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 03:25:05.909  6476  6476 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 03:25:05.909  1069  1376 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 03:25:05.909  1069  1376 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 03:25:05.909  6476  6476 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 03:25:05.910  1069  6497 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 03:25:05.910  1069  6497 E WifiMonitor: WifiMonitor:p2p0 cnt=21 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 03:25:05.910  1069  1376 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 03:25:05.910  1069  6497 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 03:25:05.910  1069  6497 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 03:25:05.910  6476  6476 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 03:25:05.910  6476  6476 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:05.910  1069  6497 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 03:25:05.910  1069  6497 E WifiMonitor: WifiMonitor:p2p0 cnt=22 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:05.910  1069  6497 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:05.910  1069  6497 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:05.911  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 03:25:05.911  1069  1069 D WifiServerServiceExt: setSupplicantStateSCANNING
08-25 03:25:05.911  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 03:25:05.911  1069  1069 D WifiServerServiceExt: setSupplicantStateSCANNING
08-25 03:25:05.911  6476  6476 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:05.911  1925  6501 D WfdsMonitor: Event [,CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 03:25:05.911  1925  6501 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 03:25:05.911  1925  6501 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 03:25:05.911  1069  6497 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 03:25:05.911  1069  6497 E WifiMonitor: WifiMonitor:p2p0 cnt=23 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:05.911  1069  6497 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:05.911  1069  6497 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-25 03:25:05.912  1069  1374 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-25 03:25:05.912  1069  1374 D LGWifiP2pService: InactiveState{ when=-18ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:05.912  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-18ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:05.912  1069  1374 D LGWifiP2pService: InactiveState{ when=-4ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:05.912  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:05.912  1069  1374 D LGWifiP2pService: DefaultState{ when=-5ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:05.912  1069  1374 D LGWifiP2pService: InactiveState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:05.912  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:05.913  1069  1374 D LGWifiP2pService: DefaultState{ when=-5ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:05.913  1069  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:05.913  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:05.913  1069  1069 E WifiServerServiceExt: No p2p device connected
08-25 03:25:05.913  1069  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:05.913  1069  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:05.913  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:05.913  1069  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:05.914  1925  2274 W WfdsService: DefaultState - msg [9441285] is not handled
08-25 03:25:05.915  4207  6504 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 03:25:05.915  4207  6504 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 03:25:05.915  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 03:25:05.921  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:05.929  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 03:25:05.929  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 03:25:05.931  6343  6343 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 03:25:05.934  6002  6002 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-25 03:25:05.934  6002  6002 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-25 03:25:05.938  6002  6002 V [BNRBootReceiver]: Boot Receiver Return
08-25 03:25:05.940  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 03:25:05.946  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 03:25:05.952  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:05.957  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 03:25:05.957  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 03:25:05.958  6343  6343 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 03:25:06.485  6476  6476 E wpa_supplicant: USIM:  scard_init function
,08-25 03:25:06.486  6476  6476 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-25 03:25:06.498  1069  6497 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-25 03:25:06.498  1069  6497 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-25 03:25:06.498  1069  6497 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-25 03:25:06.498  1069  6497 E WifiMonitor: WifiMonitor:wlan0 cnt=25 dispatchEvent: WPS-AP-AVAILABLE 
08-25 03:25:06.498  1069  6497 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-25 03:25:06.498  1069  6497 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-25 03:25:06.498  1069  6497 E WifiMonitor: WifiMonitor:wlan0 cnt=26 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-25 03:25:06.500  1069  1376 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-25 03:25:06.500  1069  1376 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-25 03:25:06.501  1069  1376 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-25 03:25:06.501  1069  1376 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-25 03:25:06.501  1069  1376 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-25 03:25:06.520  1069  1376 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=348518  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-25 03:25:06.528  1069  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 26 0 rt=348526  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-25 03:25:06.528  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-25 03:25:06.531  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:06.531  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:06.531  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 03:25:06.534  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:06.534  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 03:25:06.541  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 03:25:06.541  1069  1069 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-25 03:25:06.544  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 03:25:06.555  6274  6274 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-25 03:25:06.561  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 03:25:06.574  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 03:25:06.583  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:06.591  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 03:25:06.591  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 03:25:06.592  6343  6343 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 03:25:06.612  6476  6476 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-25 03:25:06.619  1069  6497 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-25 03:25:06.619  1069  6497 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-25 03:25:06.619  1069  6497 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-25 03:25:06.619  1069  6497 E WifiMonitor: WifiMonitor:wlan0 cnt=28 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-25 03:25:06.620  1069  6497 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 03:25:06.620  1069  6497 E WifiMonitor: WifiMonitor:wlan0 cnt=29 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 03:25:06.622  1069  1376 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=348620  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 03:25:06.622  1069  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 27 0 rt=348620  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 03:25:06.624  6476  6476 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 03:25:06.624  6476  6476 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-25 03:25:06.634  1069  1176 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 03:25:06.640  1069  6497 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 03:25:06.640  1069  6497 E WifiMonitor: WifiMonitor:wlan0 cnt=30 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-25 03:25:06.645  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 03:25:06.646  6274  6274 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 03:25:06.646  6274  6274 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 03:25:06.646  6274  6274 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 03:25:06.647  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 03:25:06.649  6274  6274 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-25 03:25:06.649  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-25 03:25:06.649  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 03:25:06.649  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 03:25:06.650  6274  6274 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 03:25:06.650  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-25 03:25:06.650  6274  6274 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 03:25:06.653  1069  6497 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-25 03:25:06.654  1069  6497 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 03:25:06.654  1069  6497 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 03:25:06.654  1069  6497 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-25 03:25:06.654  1069  6497 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,08-25 03:25:06.655  1069  1376 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=348653
08-25 03:25:06.657  1069  1376 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=348654
08-25 03:25:06.658  1069  1376 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=348655
08-25 03:25:06.659  1069  1376 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=348657
08-25 03:25:06.660  1069  1376 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 28 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=348658
08-25 03:25:06.663  1069  6497 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 03:25:06.663  1069  1376 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=348660  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 03:25:06.663  1069  6497 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 03:25:06.663  1069  6497 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 03:25:06.667  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:06.667  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 03:25:06.670  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:06.671  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:06.672  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:06.672  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 03:25:06.675  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 03:25:06.678  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:06.678  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:06.678  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-25 03:25:06.679  1069  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 29 0 rt=348677  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
,08-25 03:25:06.684  1069  1376 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-25 03:25:06.684  1069  1376 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-25 03:25:06.685  1069  1376 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 03:25:06.685  1069  1376 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 03:25:06.686  1069  1376 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 03:25:06.686  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 03:25:06.686  1069  1376 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=348684  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 03:25:06.687  1069  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 30 0 rt=348684  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 03:25:06.688  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 03:25:06.688  1069  1376 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=348685
08-25 03:25:06.688  1069  1069 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-25 03:25:06.688  1069  1376 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=348686
08-25 03:25:06.689  1069  1376 D WifiNative-wlan0: doString: [STATUS]
08-25 03:25:06.690  1069  1376 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 03:25:06.690  1069  6497 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 03:25:06.690  1069  6497 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-25 03:25:06.692  1069  1376 I WifiServiceExtension: setVHTCapabilityType  : false
08-25 03:25:06.694  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:06.694  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 03:25:06.695  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:06.696  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:06.701  1069  1376 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-25 03:25:06.702  1069  1376 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-25 03:25:06.705  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 03:25:06.714  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:06.714  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:06.715  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 03:25:06.715  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:06.715  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:06.715  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 03:25:06.716  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:06.716  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 03:25:06.718  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 03:25:06.719  6343  6343 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 03:25:06.721  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 03:25:06.723  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 03:25:06.724  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:06.724  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 03:25:06.728  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:06.731  1069  1376 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-25 03:25:06.732  1069  1376 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 03:25:06.732  1069  1376 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 03:25:06.732  1069  1376 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 03:25:06.733  1069  1376 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 03:25:06.733  1069  1445 D ConnectivityService: Got NetworkAgent Messenger
,08-25 03:25:06.734  1069  1445 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-25 03:25:06.734  1069  1445 D ConnectivityService: NetworkAgent connected
08-25 03:25:06.735  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 03:25:06.739  1069  1376 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 03:25:06.739  1069  1376 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 03:25:06.739  1069  1376 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 03:25:06.739  1069  1376 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 03:25:06.739  1069  1376 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 03:25:06.742  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:06.743  1069  1376 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 03:25:06.746   306   911 D CommandListener: Setting iface cfg
,08-25 03:25:06.752  1069  6533 D DhcpStateMachine: StoppedState
08-25 03:25:06.752  1069  1376 E WifiStateMachine: Start Dhcp Watchdog 1
08-25 03:25:06.752  1069  6533 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:06.752  1069  6533 D DhcpStateMachine: WaitBeforeStartState
08-25 03:25:06.753  1069  1376 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=348750  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 03:25:06.753  1069  1376 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=348751  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 03:25:06.754  1069  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=348751  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 03:25:06.754  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 03:25:06.754  1069  1069 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-25 03:25:06.755  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 03:25:06.755  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 03:25:06.755  1069  1069 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-25 03:25:06.755  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 03:25:06.755  6343  6343 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 03:25:06.755  1069  1376 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=348753  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 03:25:06.756  1069  1376 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=348753  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 03:25:06.756  1069  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=348754  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 03:25:06.758  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 03:25:06.758  1069  1376 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:-1085475770] from screen [on:0 period:-1085475770]
,08-25 03:25:06.759  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1085475769]
08-25 03:25:06.759  1069  1376 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-25 03:25:06.764  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:06.765  1069  1445 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
08-25 03:25:06.766  1069  1376 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:06.766  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:06.766  1069  1376 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:06.767  1069  1376 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:06.767  1069  1376 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:06.767  1069  1376 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:06.767  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 03:25:06.768  1069  1445 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-25 03:25:06.768  1069  1376 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-25 03:25:06.769  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=1,0,0
08-25 03:25:06.769  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-25 03:25:06.770  6476  6476 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-25 03:25:06.770  1069  1376 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-25 03:25:06.770  1069  1376 D WifiNative-wlan0: doBoolean: SET ps 0
,08-25 03:25:06.771  1069  1376 D WifiNative-wlan0: SET ps 0: returned true
,08-25 03:25:06.771  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-25 03:25:06.771  6476  6476 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-25 03:25:06.771  1069  1376 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-25 03:25:06.772  1069  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@b24f93b target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:06.772  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@b24f93b target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:06.772  1069  1376 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-25 03:25:06.772  1069  1376 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 03:25:06.772  1069  6533 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:06.772  1069  1376 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 03:25:06.772  1069  1376 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700" is not exist.
08-25 03:25:06.772  1069  6533 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-25 03:25:06.773  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:06.774  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 03:25:06.774  1069  1069 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 03:25:06.774  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 03:25:06.774  1069  1069 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 03:25:06.779  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 03:25:06.780  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 03:25:06.780  6343  6343 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 03:25:06.783  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 03:25:06.789  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 03:25:06.795  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 03:25:06.801  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 03:25:06.802  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 03:25:06.802  6343  6343 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 03:25:06.915  6041  6454 D UEI.SmartControl: Internal timer expired: 2
08-25 03:25:06.916  6041  6454 D UEI.SmartControl: unbind internal service
,08-25 03:25:06.976  1069  6533 D DhcpStateMachine: DHCPV4 request on wlan0
,08-25 03:25:06.978  1069  6533 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-25 03:25:06.978  1069  6533 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-25 03:25:06.978  6535  6535 W dhcpcd  : type=1400 audit(0.0:165): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:06.988  6535  6535 W dhcpcd  : type=1400 audit(0.0:166): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:07.017  6535  6535 I dhcpcd  : version 5.5.6 starting
,08-25 03:25:07.019  6535  6535 E dhcpcd  : get_duid: m
,08-25 03:25:07.019  6535  6535 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-25 03:25:07.019  6535  6535 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-25 03:25:07.121  6041  6448 D serial_port: close(fd = 24)
,08-25 03:25:07.126  6041  6448 I UEI.SmartControl: Serial port is closed.
,08-25 03:25:07.138  6535  6535 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 03:25:07.138  6535  6535 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 03:25:07.138  6535  6535 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
,08-25 03:25:07.142  6535  6535 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-25 03:25:07.142  6535  6535 D dhcpcd  : wlan0: sending REQUEST (xid 0x3ef14dbc), next in 3.34 seconds
,08-25 03:25:07.164  6535  6535 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
,08-25 03:25:07.168  6535  6535 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-25 03:25:07.168  6535  6535 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-25 03:25:07.169  6535  6535 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-25 03:25:07.170  6535  6535 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-25 03:25:07.170  6535  6535 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 03:25:07.171  6535  6535 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 03:25:07.171  6535  6535 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 03:25:07.171  6535  6535 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-25 03:25:07.173  1069  1376 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:07.175  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:07.176  1069  1376 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,08-25 03:25:07.182  1069  1376 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:07.183  1069  1376 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:07.185  1069  1376 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:07.192  1069  1445 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
,08-25 03:25:07.592  1069  6533 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-25 03:25:07.595  1069  6533 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-25 03:25:07.596  1069  6533 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 03:25:07.597  1069  6533 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-25 03:25:07.597  1069  6533 V LgDhcpStateMachineHelper: Add DhcpResults: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-25 03:25:07.598  1069  6533 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 03:25:07.598  1069  6533 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: true
08-25 03:25:07.598  1069  6533 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-25 03:25:07.599  1069  6533 D DhcpStateMachine: RunningState
,08-25 03:25:07.603  1069  1376 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
,08-25 03:25:07.604  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 03:25:07.604  1069  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:07.605  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:07.605  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 03:25:07.606  6476  6476 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 03:25:07.606  1069  1376 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
,08-25 03:25:07.607  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-25 03:25:07.607  6476  6476 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-25 03:25:07.608  1069  1376 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-25 03:25:07.608  1069  1376 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 03:25:07.628  1069  1376 D WifiNative-wlan0: SET ps 1: returned true
,08-25 03:25:07.633  1069  1445 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=false
08-25 03:25:07.635  1069  1376 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 03:25:07.635  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 03:25:07.636  1069  1376 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
,08-25 03:25:07.636  1069  1445 D ConnectivityService: ignoring duplicate network state non-change
,08-25 03:25:07.665  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:07.666  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:07.666  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 03:25:07.672  1069  1376 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-25 03:25:07.673  1069  1445 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-25 03:25:07.677  1069  1445 D ConnectivityService: Adding iface wlan0 to network 100
,08-25 03:25:07.696  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:07.696  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 03:25:07.716  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 03:25:07.733  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:07.733  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:07.733  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-25 03:25:07.737  1069  1069 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 03:25:07.753  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 03:25:07.758  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-25 03:25:07.762  1069  1445 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 03:25:07.763  1069  1445 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
08-25 03:25:07.765  1069  1445 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
08-25 03:25:07.766  1069  1445 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,08-25 03:25:07.770  1069  1445 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-25 03:25:07.770  1069  1445 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 100
08-25 03:25:07.770  1069  1445 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
08-25 03:25:07.772  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:07.772  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:07.772  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 03:25:07.774  1069  1069 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 03:25:07.778  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:07.778  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 03:25:07.782  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 03:25:07.791  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:07.794  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 03:25:07.795  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:07.795  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:07.795  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:07.795  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-25 03:25:07.799  1069  1445 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 03:25:07.800  1069  1445 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-25 03:25:07.800  1069  1445 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
08-25 03:25:07.806  1069  6531 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-6ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:07.806  1069  6531 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-25 03:25:07.809  1069  6531 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 03:25:07.813  1069  1445 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-25 03:25:07.814  1069  1445 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 03:25:07.814  1069  1445 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 03:25:07.814  1069  1445 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 03:25:07.815  1069  1445 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:07.815  1069  1445 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-25 03:25:07.815  1069  6531 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-25 03:25:07.825  1069  1445 D ConnectivityService: currentScore = 0, newScore = 20
,08-25 03:25:07.830  1069  1445 D ConnectivityService:    accepting network in place of null
08-25 03:25:07.831  1069  1445 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:07.832  1069  1376 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:07.832  1069  1376 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 03:25:07.832  1836  1836 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:07.833  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 03:25:07.833  1069  1445 D ConnectivityService: Setting tx/rx TCP buffers to 524288,1048576,2097152,262144,524288,1048576
08-25 03:25:07.838   306  6585 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,08-25 03:25:07.846  1069  1445 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-25 03:25:07.846  1069  1445 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-25 03:25:07.847  1069  1445 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 03:25:07.848  1069  1445 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 03:25:07.848  1069  1445 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-25 03:25:07.848  1069  1445 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-25 03:25:07.852  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 03:25:07.853  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 03:25:07.853  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:07.853  1069  1445 D ConnectivityService: validation of new default Network = false
08-25 03:25:07.853  1069  1445 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-25 03:25:07.853  1069  1445 D DSQN    : enableDataServiceNotify 
08-25 03:25:07.854   306  6590 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-25 03:25:07.855  1069  1445 D DSQN    : start dsqn bin
08-25 03:25:07.855   306  6590 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org, class = 1, type = 1
08-25 03:25:07.856  1069  1069 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-25 03:25:07.856  1069  1069 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 03:25:07.857  1069  1069 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 03:25:07.857  1069  1069 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 03:25:07.857  1069  1069 D LocSvc_java: Sending msg: 5 arg1:0 arg2:1
08-25 03:25:07.863  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 03:25:07.868   306  6592 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-25 03:25:07.868   306  6592 D libc-netbsd: res_queryN name = europe.pool.ntp.org, class = 1, type = 1
08-25 03:25:07.872  1069  1445 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-25 03:25:07.873  1069  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:07.873  1069  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 03:25:07.873  1069  1445 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 03:25:07.874  1586  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 03:25:07.868  6594  6594 W dsqn    : type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:07.876  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 03:25:07.868  6594  6594 W dsqn    : type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:07.893  6594  6594 E DSQN    : DSQN ssw
,08-25 03:25:07.894  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 03:25:07.894  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 03:25:07.902   306  6585 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-25 03:25:07.902  6343  6343 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 03:25:07.906  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 03:25:07.909  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 03:25:07.913  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 03:25:07.913  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:07.914  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:07.918  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 03:25:07.924   306  6590 D libc-netbsd: res_queryN name = 2.android.pool.ntp.org succeed
08-25 03:25:07.924   306  6592 D libc-netbsd: res_queryN name = europe.pool.ntp.org succeed
08-25 03:25:07.926  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 03:25:07.926  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 03:25:07.927  6343  6343 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 03:25:07.931  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 03:25:07.937  6294  6294 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-25 03:25:07.944  1069  1373 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-25 03:25:07.947  6294  6294 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 03:25:07.948   306  6585 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-25 03:25:07.951  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 03:25:07.956  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:07.963  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 03:25:07.964  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 03:25:07.966  6343  6343 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 03:25:07.968  6343  6343 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
,08-25 03:25:07.969  6343  6343 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 03:25:07.969   306   910 D LGDataListener: argv[0]=dsqncommand
08-25 03:25:07.969   306   910 D LGDataListener: argv[1]=wlan0
08-25 03:25:07.969   306   910 D LGDataListener: argv[2]=1
08-25 03:25:07.969   306   910 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-25 03:25:07.970  1069  1174 D DSQN    : DSQM DsqnNotification wlan0  1
08-25 03:25:07.970  1069  1174 D DSQN    : start to monitor internet connection
08-25 03:25:07.974  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 03:25:07.977  6294  6294 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-25 03:25:07.978  6294  6294 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-25 03:25:07.981  1069  6591 D LocSvc_java: NTP server : europe.pool.ntp.org
08-25 03:25:07.982  1069  6591 D LocSvc_java: NTP server returned: 1472088308057 (Thu Aug 25 03:25:08 GMT+02:00 2016) reference: 349979 certainty: 28 system time offset: 76
08-25 03:25:07.982  1069  6591 D LocSvc_java: Sending msg: 10 arg1:0 arg2:1
08-25 03:25:07.983  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 03:25:07.989  1069  6531 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 01:25:08 GMT], X-Android-Received-Millis=[1472088307988], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472088307968]}
08-25 03:25:07.989  1069  6531 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-25 03:25:07.990  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:07.990  1069  6531 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-25 03:25:07.991  1069  1445 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 100]
08-25 03:25:07.991  1069  1445 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 100]
08-25 03:25:07.991  1069  1445 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 03:25:07.991  1069  1445 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 03:25:07.992  1069  1445 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 03:25:07.992  1069  1445 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 100] was already satisfying request 1. No change.
08-25 03:25:07.992  1069  1445 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 100]
08-25 03:25:07.992  1069  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:07.992  1069  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 03:25:07.995  1069  1445 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 03:25:07.995  1069  1445 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:07.996  1586  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 03:25:07.996  1836  1836 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:07.996  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 03:25:07.997  1069  1445 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 03:25:07.997  1069  1376 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:07.997  1069  1376 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
,08-25 03:25:08.003  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 03:25:08.004  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 03:25:08.005  6343  6343 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 03:25:08.005  6343  6343 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 03:25:08.006  6343  6343 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 03:25:08.026  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
,08-25 03:25:08.028  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:08.030  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:08.609  1069  1376 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-25 03:25:08.620  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 03:25:08.622  1069  1376 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 03:25:08.623  1069  1376 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 03:25:08.623  1069  1376 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 03:25:08.623  1069  1376 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 03:25:08.624  1069  1445 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 100]; created=true
08-25 03:25:08.625  1069  1445 D ConnectivityService: identical MTU - not setting
08-25 03:25:08.625  1069  1445 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 03:25:08.625  1069  1445 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-25 03:25:08.625  1069  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:08.625  1069  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 03:25:08.626  1069  1445 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 03:25:08.627  1586  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-25 03:25:09.770  1069  1376 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1085472759] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-25 03:25:09.783  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 1 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=0.5, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:14] from screen [on:0 period:-1085472745] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-25 03:25:09.783  1069  1376 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-25 03:25:09.802  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 03:25:09.905  1069  2014 D WifiServiceImplEx: setWifiEnabled: false pid=6126, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 03:25:09.906  1069  2014 D WifiService: setWifiEnabled: false pid=6126, uid=10118
08-25 03:25:09.906  1069  2014 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 03:25:09.937  1069  1069 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 03:25:09.937  1069  1069 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 03:25:09.937  1069  1069 D Ulp_jni : JNI:system_update. Event-4
08-25 03:25:09.939  1069  1376 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 03:25:09.939  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-25 03:25:09.940  1069  1376 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-25 03:25:09.940  1069  1376 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-25 03:25:09.941  1069  1376 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-25 03:25:09.941  1069  1376 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-25 03:25:09.941  1069  1376 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 03:25:09.941  1069  1376 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 03:25:09.942  1069  1376 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 03:25:09.942  1069  1376 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 03:25:09.955  1069  1376 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 03:25:09.956  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 03:25:09.956  6476  6476 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
,08-25 03:25:09.960  1069  1374 D LGWifiP2pService: InactiveState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:09.960  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-4ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:09.961  1069  1376 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 03:25:09.961  1069  1376 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 03:25:09.962  1069  1376 D WifiNative-wlan0: SET ps 1: returned true
08-25 03:25:09.963   306   911 D CommandListener: Clearing all IP addresses on wlan0
08-25 03:25:09.972  1069  6533 D DhcpStateMachine: RunningState{ when=-11ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 03:25:10.041  1069  1445 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-25 03:25:10.041  1069  1445 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-25 03:25:10.051  1069  1069 D WifiHS20: hidePasspointNotification off =false
08-25 03:25:10.054  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:10.054  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 03:25:10.066  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 0
,08-25 03:25:10.074  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:10.074  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:10.074  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 03:25:10.096  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 03:25:10.103  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 03:25:10.104  1069  1069 D WifiHS20: hidePasspointNotification off =false
08-25 03:25:10.108  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:10.109  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:10.109  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-25 03:25:10.117  1069  1069 D WifiScanningService: SCAN_AVAILABLE : 1
08-25 03:25:10.118  1069  1540 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:10.118  1069  1374 D LGWifiP2pService: InactiveState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:10.118  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-5ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:10.119  1069  1374 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@1f46102c
08-25 03:25:10.119  1069  1376 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:10.120  1069  1376 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:10.120  1069  1376 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:10.121  1069  1376 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:10.121  1069  1376 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:10.121  1069  1376 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:10.122  1069  1376 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-25 03:25:10.122  1069  1069 D RttService: SCAN_AVAILABLE : 1
,08-25 03:25:10.123  1069  1541 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:10.123  1069  1374 D LGWifiP2pService: P2pDisablingState
08-25 03:25:10.123  1069  1374 D LGWifiP2pService: P2pDisablingState{ when=-5ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:10.124  1069  1374 D LGWifiP2pService: p2p socket connection lost
08-25 03:25:10.124  1069  1374 D LGWifiP2pService: P2pDisabledState
08-25 03:25:10.125  1069  1376 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-25 03:25:10.126  1069  1374 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:10.126  1069  1374 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:10.126  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 03:25:10.126  6476  6476 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 03:25:10.127  1069  1376 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 03:25:10.127  1069  1376 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 03:25:10.128  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:10.128  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 03:25:10.128  1069  1376 D WifiNative-wlan0: SET ps 1: returned true
,08-25 03:25:10.133  6294  6294 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 03:25:10.133  6294  6294 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 03:25:10.133  6294  6294 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 03:25:10.136  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 03:25:10.136  1925  1925 D WfdsService: WifiP2pState is changed : false
,08-25 03:25:10.136  1925  2274 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-25 03:25:10.136  1925  2274 D WfdsService: Set the WFDS Monitor: false
08-25 03:25:10.137  1925  2274 D WfdsMonitor: WFDS Monitor is stopped
08-25 03:25:10.137  1925  2274 D WfdsService: STATE : WfdsDisabledState - enter
08-25 03:25:10.138  1925  6501 D CtrlSupplicant: Received on exit socket, terminate
08-25 03:25:10.138  1925  6501 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-25 03:25:10.138  1925  6501 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-25 03:25:10.138  1925  6501 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-25 03:25:10.138  1925  2277 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-25 03:25:10.139  1925  2274 W WfdsService: DefaultState - msg [9445378] is not handled
08-25 03:25:10.141   306   911 D CommandListener: Clearing all IP addresses on wlan0
08-25 03:25:10.142  1069  1445 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-25 03:25:10.142  1069  1445 D DSQN    : disableDataServiceNotify
08-25 03:25:10.142  1069  1445 D DSQN    : stop dsqn bin
08-25 03:25:10.143  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 03:25:10.145  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 03:25:10.149  1069  1069 D WifiHS20: hidePasspointNotification off =false
08-25 03:25:10.150  1069  1445 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-25 03:25:10.150  1069  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:10.150  1069  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 03:25:10.150  1069  1445 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 03:25:10.150  1069  1445 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-25 03:25:10.151  1069  1376 D WifiNative-p2p0: doBoolean: TERMINATE
08-25 03:25:10.151  1069  1376 D WifiNative-p2p0: TERMINATE: returned true
08-25 03:25:10.151  1069  1376 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 03:25:10.151  1069  1376 E WifiStateMachine: useWiFiOffloading() : false
08-25 03:25:10.151  1069  1376 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 03:25:10.151  1069  1445 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-25 03:25:10.151  1069  1445 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-25 03:25:10.151  1069  1445 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 03:25:10.152  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:10.152  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:10.152  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 03:25:10.152  1586  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-25 03:25:10.152  1069  6531 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:10.152  1069  6531 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:10.153  1069  6531 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-25 03:25:10.155  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-25 03:25:10.155  1069  1069 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-25 03:25:10.155  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 03:25:10.155  1069  1069 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-25 03:25:10.156  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:10.156  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:10.156  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is, Wi-Fi Direct supported: true
08-25 03:25:10.156  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:10.156  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:25:10.156  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:25:10.156  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:25:10.156  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:25:10.156  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 03:25:10.156  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:10.156  6126  6126 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:25:10.157  1069  1445 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:25:10.157  1069  1445 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 03:25:10.157  1069  1069 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 03:25:10.158  1069  1069 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 03:25:10.158  1069  1069 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 03:25:10.158  1069  1069 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 03:25:10.159  1069  1373 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 03:25:10.162  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:10.162  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:10.162  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:10.162  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:10.162  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:25:10.162  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:25:10.162  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:25:10.162  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:25:10.162  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 03:25:10.162  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:10.162  6126  6126 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:25:10.163  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:10.163  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:10.163  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:10.163  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:10.163  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:25:10.163  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:25:10.163  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:25:10.163  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:25:10.163  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 03:25:10.163  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:10.163  6126  6126 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:25:10.165  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-25 03:2,5:10.165  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 03:25:10.166  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 03:25:10.168  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:10.169  1069  1069 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-25 03:25:10.169  1069  1069 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 03:25:10.169  1069  1069 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 03:25:10.169  1069  1069 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 03:25:10.171  1069  1373 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-25 03:25:10.171  1069  1445 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 03:25:10.171  1069  1445 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:10.171  1069  1445 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:10.171  1069  1376 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:10.171  1069  1445 D NetworkManagementService: Removing idletimer
08-25 03:25:10.172  1069  1376 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 03:25:10.172  1069  1445 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:10.172  1836  1836 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:10.172  1069  1445 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-25 03:25:10.172  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 03:25:10.174  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:10.181  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 03:25:10.181  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 03:25:10.185  6343  6343 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 03:25:10.188  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 03:25:10.193  6294  6294 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 03:25:10.193  6294  6294 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 03:25:10.193  6294  6294 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 03:25:10.193  1069  6533 D DhcpStateMachine: StoppedState
08-25 03:25:10.193  1069  6533 D DhcpStateMachine: StoppedState{ when=-65ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 03:25:10.198  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 03:25:10.199  1069  1376 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-25 03:25:10.200  1069  1376 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
,08-25 03:25:10.211  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 03:25:10.212  6476  6476 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-25 03:25:10.212  6476  6476 I wpa_supplicant: monitor socket send errors count : 1
08-25 03:25:10.212  6476  6476 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1925-4\x00 that cannot receive messages
08-25 03:25:10.212  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:10.213  1069  6497 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-25 03:25:10.213  1069  6497 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 03:25:10.214  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:10.215  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:10.217  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 03:25:10.217  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 03:25:10.219  6343  6343 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 03:25:10.223  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 03:25:10.228  6294  6294 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-25 03:25:10.229  6294  6294 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 03:25:10.229  6294  6294 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 03:25:10.233  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 03:25:10.240  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:10.248  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 03:25:10.248  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 03:25:10.249  6343  6343 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 03:25:10.251  6476  6476 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 03:25:10.251  1069  6497 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-25 03:25:10.251  1069  6497 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 03:25:10.252  1069  6497 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-25 03:25:10.252  1069  6497 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-25 03:25:10.252  6476  6476 W wpa_supplicant: USIM:  scard_deinit function
08-25 03:25:10.252  1069  6497 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 03:25:10.252  1069  6497 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 03:25:10.253  1069  1176 D Tethering: InitialState.processMessage what=4
08-25 03:25:10.253  1069  1376 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=352251
,08-25 03:25:10.253  1069  1376 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=352251
08-25 03:25:10.254  1069  1176 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 03:25:10.254  1069  1376 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=352251  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 03:25:10.254  1069  1376 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=352252  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-25 03:25:10.255  1069  1376 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-25 03:25:10.255  1069  1376 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 03:25:10.256  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 03:25:10.257  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:10.258  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:10.261  6294  6294 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-25 03:25:10.265  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 03:25:10.269  6383  6636 W FormManager: Network not available. Please check & try again.
08-25 03:25:10.270  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:10.279  6383  6637 V FormManager: Network unavailable.
,08-25 03:25:10.285  6383  6637 V FormManager: Network unavailable.
,08-25 03:25:10.288  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-25 03:25:10.288  6274  6274 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 03:25:10.288  6274  6274 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 03:25:10.288  6274  6274 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 03:25:10.288  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 03:25:10.290  6274  6274 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 03:25:10.290  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 03:25:10.290  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 03:25:10.290  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 03:25:10.290  6274  6274 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 03:25:10.290  6274  6274 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 03:25:10.302  6476  6476 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-25 03:25:10.302  1069  6497 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-25 03:25:10.302  1069  6497 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-TERMINATING 
08-25 03:25:10.302  1069  6497 D WifiMonitor: Disconnecting from the supplicant, no more events
08-25 03:25:10.303  1069  1376 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 37 0
,08-25 03:25:10.407  1925  1925 D WfdsService: Supplicant Connection state is changed : false
,08-25 03:25:10.407  1925  2274 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-25 03:25:10.407  1925  2274 D WfdsService: Set the WFDS Monitor: false
08-25 03:25:10.407  1925  2274 D WfdsMonitor: WFDS Monitor is stopped
08-25 03:25:10.413  1069  1376 D WifiOffDelayIfNotUsed: stopMonitoring
08-25 03:25:10.413  1069  1376 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 03:25:10.413  1069  1376 E WifiStateMachine: useWiFiOffloading() : false
08-25 03:25:10.413  1069  1376 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 03:25:10.414  4207  4207 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 03:25:10.415  4207  4207 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 03:25:10.419  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:10.419  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-25 03:25:10.421  4207  4207 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 03:25:10.422  2485  2485 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:10.423  1069  1069 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-25 03:25:10.424  1069  1425 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-25 03:25:10.424  1069  1425 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-25 03:25:10.426  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:10.426  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:10.426  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:10.426  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:10.426  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:25:10.426  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:25:10.426  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:25:10.426  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:25:10.426  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:25:10.427  4207  4207 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 03:25:10.428  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:10.429  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:10.429  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:10.429  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:10.429  6126  6126 V io.jxcore.node.C,onnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:25:10.429  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:25:10.429  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:25:10.429  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:25:10.429  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:25:10.431  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:10.431  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:10.431  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:10.431  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:10.431  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:25:10.431  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:25:10.431  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:25:10.431  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:25:10.431  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:25:10.436  4207  6638 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 03:25:10.441  4207  6639 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 03:25:10.441  4207  6639 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-25 03:25:10.445  6294  6294 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
08-25 03:25:10.445  6294  6294 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-25 03:25:10.445  6294  6294 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 03:25:10.452  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 03:25:10.452  6383  6641 W FormManager: Network not available. Please check & try again.
,08-25 03:25:10.459  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:10.465  6383  6642 V FormManager: Network unavailable.
08-25 03:25:10.468  6383  6642 V FormManager: Network unavailable.
,08-25 03:25:10.852  1069  1445 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:25:10.859  1069  1176 D Tethering: MasterInitialState.processMessage what=3
08-25 03:25:10.860  1069  1167 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 03:25:10.868  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:25:10.872  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:10.874  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:10.884  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-25 03:25:10.892  4879  6268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 03:25:10.900  5347  5347 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-25 03:25:10.927  1069  1167 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 03:25:10.955  1069  1167 E GpsLocationProvider: No APN found to select.
,08-25 03:25:10.972  2169  2169 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:25:11.026  1069  2611 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=6654 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-25 03:25:11.155  6654  6654 I AppUp4:AppBoxCP: onCreate
,08-25 03:25:11.156  6654  6654 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-25 03:25:11.166  6654  6654 I AppUp4:DB:  setFingerPrint start
,08-25 03:25:11.167  6654  6654 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-25 03:25:11.176  6654  6654 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-25 03:25:11.176  6654  6654 I AppUp4:DB:  SDK version = 21
08-25 03:25:11.176  6654  6654 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-25 03:25:11.178  6654  6654 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-25 03:25:11.179  6654  6654 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 03:25:11.180  6654  6654 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:25:11.183  6654  6654 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-25 03:25:11.183  6654  6654 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-25 03:25:11.189  6654  6654 I AppUp4:CustModeStarterReceiver: onReceive
08-25 03:25:11.235  6654  6654 D LgDataFeature: LgDataFeature() Constructor: none
08-25 03:25:11.235  6654  6654 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 03:25:11.243  6654  6654 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@29776c5e
,08-25 03:25:11.243  6654  6654 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 03:25:11.243  6654  6654 D AppUp4:CustFacade: isPhone : true
08-25 03:25:11.244  6654  6654 D AppUp4:CustModeStarterReceiver: begin check event
,08-25 03:25:11.245  6654  6654 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-25 03:25:11.245  6654  6654 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-25 03:25:11.270  6654  6688 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
,08-25 03:25:11.270  6654  6688 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-25 03:25:11.270  6654  6688 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-25 03:25:11.274  1069  2611 I ActivityManager: Killing 5904:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-25 03:25:11.314  4207  4207 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:25:11.315  4207  4207 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 03:25:11.316  1069  2025 W libprocessgroup: failed to open /acct/uid_10061/pid_5904/cgroup.procs: No such file or directory
,08-25 03:25:11.322  4207  4207 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 03:25:11.326  4207  4207 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 03:25:11.341  4207  6690 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 03:25:11.344  4207  6691 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 03:25:11.344  4207  6691 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 03:25:11.404  1069  1960 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=6695 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-25 03:25:11.504  6695  6695 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 03:25:11.504  6695  6695 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 03:25:11.506  6695  6695 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 03:25:11.507  6695  6695 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 03:25:11.602  6695  6695 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-25 03:25:11.618  6695  6695 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-25 03:25:11.665  6695  6695 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-25 03:25:11.704  6695  6695 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 03:25:11.704  6695  6695 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 03:25:11.827  6695  6695 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-25 03:25:11.863  6695  6695 I HubEmail: JNI_OnLoad()
08-25 03:25:11.863  6695  6695 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 03:25:11.863  6695  6695 I HubEmail: registerNatives()
08-25 03:25:11.863  6695  6695 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 03:25:11.863  6695  6695 I HubEmail: registerNativeMethods()
08-25 03:25:11.863  6695  6695 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 03:25:11.863  6695  6695 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-25 03:25:11.875  3384  3384 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 03:25:11.876  3384  3384 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 03:25:11.877  3384  3384 I LgeMiscReceiver: networkInfo.isConnected() = true
08-25 03:25:11.877  3384  3384 D PhoneState: setPdpRejectCasuse : false
,08-25 03:25:11.883  6383  6721 W FormManager: Network not available. Please check & try again.
08-25 03:25:11.920  1069  1896 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=6724 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-25 03:25:11.926  6383  6722 V FormManager: Network unavailable.
08-25 03:25:11.929  6383  6722 V FormManager: Network unavailable.
08-25 03:25:11.933  6695  6723 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:11.936  1069  1864 I ActivityManager: Killing 5932:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-25 03:25:11.969  1069  1096 W libprocessgroup: failed to open /acct/uid_10080/pid_5932/cgroup.procs: No such file or directory
08-25 03:25:12.036  6724  6724 D LgDataFeature: LgDataFeature() Constructor: none
08-25 03:25:12.036  6724  6724 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 03:25:12.039  6724  6724 D PhoneMonitor: Register our PhoneStateListener
,08-25 03:25:12.060  6724  6724 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-25 03:25:12.062  6724  6724 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-25 03:25:12.086  6724  6724 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-25 03:25:12.087  6724  6724 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-25 03:25:12.087  6724  6724 D TelephonyAutoProfiling: [parse] Load xml
08-25 03:25:12.090  6724  6724 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-25 03:25:12.090  6724  6724 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-25 03:25:12.090  6724  6724 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
,08-25 03:25:12.090  6724  6724 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-25 03:25:12.090  6724  6724 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-25 03:25:12.090  6724  6724 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-25 03:25:12.090  6724  6724 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-25 03:25:12.090  6724  6724 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-25 03:25:12.090  6724  6724 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-25 03:25:12.090  6724  6724 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-25 03:25:12.090  6724  6724 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-25 03:25:12.092  6724  6724 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-25 03:25:12.092  6724  6724 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-25 03:25:12.092  6724  6724 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-25 03:25:12.092  6724  6724 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-25 03:25:12.092  6724  6724 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-25 03:25:12.092  6724  6724 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
08-25 03:25:12.101  6724  6724 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
,08-25 03:25:12.119  1069  1926 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=6744 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-25 03:25:12.119  1069  1926 I ActivityManager: Killing 2138:com.lge.music/u0a34 (adj 15): empty #17
,08-25 03:25:12.152   310  1382 V AudioFlinger: 2138 died, releasing its sessions
08-25 03:25:12.152   310  1382 V AudioFlinger:  pid 1836 @ 0
08-25 03:25:12.152   310  1382 V AudioFlinger:  pid 3384 @ 1
08-25 03:25:12.152   310  1382 V AudioFlinger:  pid 3384 @ 2
,08-25 03:25:12.243  1069  1977 W libprocessgroup: failed to open /acct/uid_10034/pid_2138/cgroup.procs: No such file or directory
,08-25 03:25:12.608  1069  1977 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=6778 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
08-25 03:25:12.609  1069  1977 I ActivityManager: Killing 5980:com.lge.eula/1000 (adj 15): empty #17
,08-25 03:25:12.656  1069  1926 W libprocessgroup: failed to open /acct/uid_1000/pid_5980/cgroup.procs: No such file or directory
08-25 03:25:12.694  6778  6778 D DrmBroadcastReceiver: Receive CONNECTIVITY_ACTION
,08-25 03:25:12.696  6778  6778 D DrmBroadcastReceiver: 1  network is available. Sync DRM Time with NTP
08-25 03:25:12.704  6778  6778 V DrmService: Service onCreate
08-25 03:25:12.704  6778  6778 D DrmService: Received new request = 2
08-25 03:25:12.709  6778  6795 I DrmSntpClient: Start Sync process
08-25 03:25:12.709  6778  6795 D DrmSntpClient: Server : 0
,08-25 03:25:12.752  1069  1896 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6796 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 03:25:12.756  6778  6795 D DrmSntpClient: Automatic sync but WiFi isn't enabled
08-25 03:25:12.763  6778  6778 D DrmService: Completed !! request = 2
08-25 03:25:12.763  6778  6778 D DrmService: Request count = 0
08-25 03:25:12.766  6778  6778 V DrmService: Service onDestroy
,08-25 03:25:12.773  1069  1701 I ActivityManager: Killing 5949:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-25 03:25:12.810  1069  1376 E WifiStateMachine:  InitialState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1085469718] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-25 03:25:12.811  1069  1376 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 1 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1085469717] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 03:25:12.831  1069  1097 W libprocessgroup: failed to open /acct/uid_10097/pid_5949/cgroup.procs: No such file or directory
,08-25 03:25:12.872  6796  6796 I art     : Almond Protected OAT
,08-25 03:25:12.939  6796  6796 D WeatherApplication: removeAccount
,08-25 03:25:12.941  6796  6796 D WeatherApplication: Account.length = 0
,08-25 03:25:12.941  6796  6796 E WeatherApplication: OPERATOR:OPEN
,08-25 03:25:12.949  6796  6796 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:25:12
08-25 03:25:12.954  6796  6796 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 03:25:12.954  6796  6796 D Weather.Utils: 2 : All the weather widget is gone.
08-25 03:25:12.959  6796  6796 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 03:25:12.966  6796  6796 D WeatherAncestor: connectivity changed - connection : true
08-25 03:25:12.969  6796  6796 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-25 03:25:12.993  6796  6796 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-25 03:25:12.994  6796  6796 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-25 03:25:12.994  6796  6796 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-25 03:25:13.029  6796  6796 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 03:25:13.030  6796  6796 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:25:13
,08-25 03:25:13.089  1069  1672 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=6814 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 03:25:13.092  1069  1672 I ActivityManager: Killing 5866:com.android.vending/u0a44 (adj 15): empty #17
,08-25 03:25:13.159  1069  1445 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 03:25:13.192  1069  2611 W libprocessgroup: failed to open /acct/uid_10044/pid_5866/cgroup.procs: No such file or directory
,08-25 03:25:13.200  1069  1167 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 03:25:13.201  1069  1176 D Tethering: MasterInitialState.processMessage what=3
08-25 03:25:13.201  1069  1167 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:13.202  1069  1445 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-25 03:25:13.204  1069  1176 D Tethering: MasterInitialState.processMessage what=3
08-25 03:25:13.212  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:25:13.222  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:13.222  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:13.223  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:13.224  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:13.225  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:13.226  1069  1167 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-25 03:25:13.229  1069  1167 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 03:25:13.232  5347  5347 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-25 03:25:13.235  5347  5347 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-25 03:25:13.317  1069  1996 I art     : Explicit concurrent mark sweep GC freed 133679(6MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 2.176ms total 173.674ms
,08-25 03:25:13.402   279   346 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 03:25:13.402   279   346 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-25 03:25:13.402   279   346 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 03:25:13.405  6814  6832 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-25 03:25:13.406   279   346 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 03:25:13.406   279   346 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-25 03:25:13.406   279   346 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 03:25:13.406  6814  6832 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-25 03:25:13.424   279   346 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 03:25:13.424   279   346 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-25 03:25:13.424   279   346 W Vold    : Returning OperationFailed - no handler for errno 0
,08-25 03:25:13.428  6814  6834 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-25 03:25:13.433   279   346 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-25 03:25:13.433   279   346 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-25 03:25:13.433   279   346 W Vold    : Returning OperationFailed - no handler for errno 0
08-25 03:25:13.434  6814  6834 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-25 03:25:13.613  6814  6814 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-25 03:25:13.637  6814  6814 I LibraryLoader: Loading: webviewchromium
,08-25 03:25:13.641  6814  6814 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 5645-5650)
08-25 03:25:13.641  6814  6814 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 03:25:13.648  6814  6814 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {285dcf4b}
08-25 03:25:13.649  6814  6814 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-25 03:25:13.650  6814  6814 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-25 03:25:13.663  6814  6814 I BrowserStartupController: Initializing chromium process, renderers=0
08-25 03:25:13.664  6814  6814 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-25 03:25:13.684  6814  6814 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-25 03:25:13.685  6814  6814 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-25 03:25:13.686  6814  6814 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-25 03:25:13.692   310  1381 V AudioPolicyService: registerClient() client 0xb57c0e60, uid 10093
08-25 03:25:13.694  6814  6856 W AudioManagerAndroid: Requires BLUETOOTH permission
08-25 03:25:13.708  6814  6814 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 03:25:13.708  6814  6814 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 03:25:13.708  6814  6814 I Adreno-EGL: Build Date: 12/12/14 금
08-25 03:25:13.708  6814  6814 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 03:25:13.708  6814  6814 I Adreno-EGL: Remote Branch: 
08-25 03:25:13.708  6814  6814 I Adreno-EGL: Local Patches: 
08-25 03:25:13.708  6814  6814 I Adreno-EGL: Reconstruct Branch: 
,08-25 03:25:13.790  6814  6814 I NSApplication: Starting up...
,08-25 03:25:13.852  1069  1977 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=6869 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-25 03:25:13.854  1069  1977 I ActivityManager: Killing 6317:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-25 03:25:13.914  1069  1672 W libprocessgroup: failed to open /acct/uid_10037/pid_6317/cgroup.procs: No such file or directory
,08-25 03:25:13.949  6869  6869 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 03:25:14.243  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-25 03:25:14.248  4879  6268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 03:25:14.262  2169  2169 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:25:14.276  6654  6654 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 03:25:14.276  6654  6654 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 03:25:14.276  6654  6654 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 03:25:14.276  6654  6654 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-25 03:25:14.280  6654  6654 I AppUp4:CustModeStarterReceiver: onReceive
08-25 03:25:14.283  6654  6654 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@29776c5e
08-25 03:25:14.283  6654  6654 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 03:25:14.283  6654  6654 D AppUp4:CustFacade: isPhone : true
08-25 03:25:14.284  6654  6654 D AppUp4:CustModeStarterReceiver: begin check event
08-25 03:25:14.284  6654  6654 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 03:25:14.287  4207  4207 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 03:25:14.288  4207  4207 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 03:25:14.291  4207  4207 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 03:25:14.294  4207  4207 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 03:25:14.309  4207  6898 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 03:25:14.310  6695  6695 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-25 03:25:14.323  4207  6899 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:25:14.324  4207  6899 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 03:25:14.332  6695  6901 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:14.338  3384  3384 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 03:25:14.338  3384  3384 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 03:25:14.338  3384  3384 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-25 03:25:14.340  6383  6903 W FormManager: Network not available. Please check & try again.
08-25 03:25:14.346  6383  6904 V FormManager: Network unavailable.
08-25 03:25:14.352  6724  6724 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-25 03:25:14.352  6724  6724 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 03:25:14.364  6383  6904 V FormManager: Network unavailable.
,08-25 03:25:14.369  6796  6796 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:25:14
08-25 03:25:14.376  6796  6796 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 03:25:14.376  6796  6796 D Weather.Utils: 2 : All the weather widget is gone.
08-25 03:25:14.377  6796  6796 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 03:25:14.377  6796  6796 D WeatherAncestor: connectivity changed - connection : true
08-25 03:25:14.377  6796  6796 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3c84150c
08-25 03:25:14.378  6796  6796 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 03:25:14.378  6796  6796 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 03:25:14.378  6796  6796 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 03:25:14.378  6796  6796 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 03:25:14.378  6796  6796 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:25:14
,08-25 03:25:14.402  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-25 03:25:14.409  4879  6268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 03:25:14.424  2169  2169 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:25:14.436  6654  6654 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 03:25:14.436  6654  6654 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:25:14.436  6654  6654 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-25 03:25:14.436  6654  6654 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 03:25:14.438  6654  6654 I AppUp4:CustModeStarterReceiver: onReceive
08-25 03:25:14.443  6654  6654 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@29776c5e
08-25 03:25:14.443  6654  6654 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 03:25:14.443  6654  6654 D AppUp4:CustFacade: isPhone : true
08-25 03:25:14.443  6654  6654 D AppUp4:CustModeStarterReceiver: begin check event
08-25 03:25:14.444  6654  6654 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-25 03:25:14.448  4207  4207 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 03:25:14.448  4207  4207 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 03:25:14.450  4207  4207 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-25 03:25:14.454  4207  4207 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 03:25:14.463  6695  6695 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-25 03:25:14.465  4207  6917 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 03:25:14.466  4207  6918 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 03:25:14.466  4207  6918 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-25 03:25:14.493  6695  6919 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 03:25:14.496  6383  6921 W FormManager: Network not available. Please check & try again.
08-25 03:25:14.498  3384  3384 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 03:25:14.498  3384  3384 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 03:25:14.498  3384  3384 I LgeMiscReceiver: networkInfo.isConnected() = false
08-25 03:25:14.506  6724  6724 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 03:25:14.506  6724  6724 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 03:25:14.519  6796  6796 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:25:14
,08-25 03:25:14.520  6383  6922 V FormManager: Network unavailable.
08-25 03:25:14.522  6796  6796 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 03:25:14.522  6796  6796 D Weather.Utils: 2 : All the weather widget is gone.
08-25 03:25:14.522  6383  6922 V FormManager: Network unavailable.
08-25 03:25:14.523  6796  6796 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-25 03:25:14.523  6796  6796 D WeatherAncestor: connectivity changed - connection : true
08-25 03:25:14.523  6796  6796 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3c84150c
08-25 03:25:14.524  6796  6796 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-25 03:25:14.524  6796  6796 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 03:25:14.524  6796  6796 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 03:25:14.524  6796  6796 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 03:25:14.525  6796  6796 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:25:14
08-25 03:25:14.946  1069  2025 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:25:14.946  1069  2025 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false,
,08-25 03:25:14.984  1069  1069 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 03:25:14.985  1069  1069 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 03:25:14.985  1069  1069 D Ulp_jni : JNI:system_update. Event-4
08-25 03:25:14.986  1069  1176 D BluetoothManagerService: Message: 1
08-25 03:25:14.986  1069  1176 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-25 03:25:15.012  1069  1176 D BluetoothManagerService: Message: 20
08-25 03:25:15.013  1069  1176 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6ee5006:true
,08-25 03:25:15.018  6414  6414 D BluetoothAdapterState: make
08-25 03:25:15.023  6414  6414 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-25 03:25:15.024  6414  6414 I bluedroid-qcom: init
08-25 03:25:15.025  6414  6934 I BluetoothAdapterState: Entering OffState
08-25 03:25:15.025  6414  6414 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 03:25:15.025  6414  6414 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 03:25:15.026  6414  6414 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 03:25:15.026  6414  6414 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 03:25:15.026  6414  6414 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-25 03:25:15.028  6414  6414 I bluedroid-qcom: get_profile_interface socket
08-25 03:25:15.028  6414  6414 I bluedroid-qcom: get_profile_interface map_client
,08-25 03:25:15.033  6414  6938 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-25 03:25:15.028  6937  6937 W bdaddr_loader: type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:15.028  6937  6937 W bdaddr_loader: type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:15.039  6414  6938 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-25 03:25:15.047  6937  6937 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-25 03:25:15.047  6937  6937 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-25 03:25:15.047  6937  6937 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-25 03:25:15.054  1069  1069 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-25 03:25:15.054  1069  1069 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 03:25:15.054  1069  1069 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 03:25:15.055  1069  1176 D BluetoothManagerService: Message: 40
08-25 03:25:15.055  1069  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-25 03:25:15.056  6414  6431 I bluedroid-qcom: config_hci_snoop_log
08-25 03:25:15.057  1069  1176 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-25 03:25:15.057  1069  1176 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-25 03:25:15.058  6937  6937 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-25 03:25:15.065  6414  6934 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
,08-25 03:25:15.069  6414  6938 D BluetoothAdapterProperties: Name is: G3
08-25 03:25:15.070  6937  6937 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-25 03:25:15.070  6937  6937 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-25 03:25:15.072  6414  6934 D BluetoothAdapterProperties: Setting state to 11
08-25 03:25:15.072  6414  6934 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-25 03:25:15.073  1069  1176 D BluetoothManagerService: Message: 60
08-25 03:25:15.073  1069  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-25 03:25:15.073  1069  1176 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-25 03:25:15.077  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-25 03:25:15.081  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 03:25:15.084  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:15.087  6274  6274 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-25 03:25:15.091  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:25:15.098  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:15.099  6414  6414 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 03:25:15.099  6414  6414 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:15.099  6414  6414 V BluetoothPbapReceiver: ***********state = 11
08-25 03:25:15.116  6414  6934 I LGBluetoothServiceJni: classInitNative: succeeds
,08-25 03:25:15.120  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 03:25:15.129  1069  1374 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:15.129  1069  1374 D LGWifiP2pService: DefaultState{ when=-5ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-25 03:25:15.154  1069  1376 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-25 03:25:15.154  1069  1376 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
,08-25 03:25:15.165  1069  2025 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=6954 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-25 03:25:15.172  6414  6934 D BluetoothBondStateMachine: make
,08-25 03:25:15.175  6414  6971 I BluetoothBondStateMachine: StableState(): Entering Off State
08-25 03:25:15.175  6414  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c84150c
08-25 03:25:15.176  6414  6934 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-25 03:25:15.176  6414  6934 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c84150c
08-25 03:25:15.176  6414  6934 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-25 03:25:15.176  6414  6934 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-25 03:25:15.181  6414  6934 E BluetoothAdapterService: File transfer profiles supported!!
08-25 03:25:15.188  6414  6934 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 03:25:15.192  6414  6414 D HeadsetService: Received start request. Starting profile...
08-25 03:25:15.192  6414  6414 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 03:25:15.193  6414  6414 D LGBluetoothHfpAdapter: Version 1.6
08-25 03:25:15.196  6414  6414 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 03:25:15.198  6414  6414 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 03:25:15.199  6414  6414 D HeadsetStateMachine: make
08-25 03:25:15.201  6414  6934 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 03:25:15.212  6414  6934 E BluetoothAdapterService: File transfer profiles supported!!
08-25 03:25:15.216  6414  6934 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 03:25:15.221  6414  6934 E BluetoothAdapterService: File transfer profiles supported!!
08-25 03:25:15.228  6414  6934 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 03:25:15.241  6414  6934 V LGMDMManager: Create singleton instance
,08-25 03:25:15.243  6414  6934 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-25 03:25:15.243  6414  6414 D LgDataFeature: LgDataFeature() Constructor: none
08-25 03:25:15.244  6414  6414 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 03:25:15.249  6414  6414 D HeadsetStateMachine: max_hf_connections = 1
08-25 03:25:15.249  6414  6414 I bluedroid-qcom: get_profile_interface handsfree
08-25 03:25:15.251  6414  6414 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-25 03:25:15.252   310  2157 V AudioPolicyService: registerClient() client 0xb558a260, uid 1002
08-25 03:25:15.252   310  1382 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-25 03:25:15.252   310  1382 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 03:25:15.252   310  1382 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 03:25:15.252  6414  6414 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 03:25:15.252   310  1381 V AudioFlinger: registerClient() client 0xb1433190, pid 6414
,08-25 03:25:15.254   310  1375 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 03:25:15.254   310  1375 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 03:25:15.254  1069  1672 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 03:25:15.254  1069  1672 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 03:25:15.254  6414  6430 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 03:25:15.254  6414  6430 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-25 03:25:15.254  3384  3400 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 03:25:15.254  3384  3400 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 03:25:15.254   310  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 03:25:15.254   310  1377 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 03:25:15.255  1069  1701 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 03:25:15.255  3384  3399 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 03:25:15.255  1069  1701 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 03:25:15.255  3384  3399 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 03:25:15.255  1586  1607 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 03:25:15.255  1586  1607 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 03:25:15.255  6414  6431 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 03:25:15.255  1586  1607 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 03:25:15.255  1586  1607 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 03:25:15.255  6414  6431 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-25 03:25:15.255  6414  6414 V ToneGenerator: Create Track: 0xb4928080
08-25 03:25:15.255  6414  6414 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-25 03:25:15.255  6414  6414 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-25 03:25:15.255   310  2157 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 03:25:15.255   310  2157 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-25 03:25:15.255   310  2157 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 03:25:15.255   310  2157 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 03:25:15.255   310  1382 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 03:25:15.256   310  2158 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 03:25:15.256   310  2158 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-25 03:25:15.256   310  2158 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 03:25:15.256  1836  1851 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 03:25:15.256   310  2158 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 03:25:15.256  1836  1851 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 03:25:15.258  6414  6414 V AudioSystem: getLatency() output 2, latency 50
08-25 03:25:15.258  1836  1851 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 03:25:15.258  6414  6414 V AudioSystem: getFrameCount() output 2, frameCount 960
08-25 03:25:15.258  1836  1851 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 03:25:15.258  6414  6414 V AudioTrack: createTrack_l() output 2 afLatency 50
08-25 03:25:15.258   310   310 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 03:25:15.258   310   310 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), ,curLvl = 31 
08-25 03:25:15.259   310   310 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 03:25:15.259   310   310 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 03:25:15.259   310   310 V AudioFlinger: createTrack() lSessionId: 20
08-25 03:25:15.260  6414  6414 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-25 03:25:15.260   310  1381 V AudioFlinger: acquiring 20 from 6414, for 6414
08-25 03:25:15.260   310  1381 V AudioFlinger:  added new entry for 20
08-25 03:25:15.260  6414  6414 V ToneGenerator: ToneGenerator INIT OK, time: 357269
08-25 03:25:15.260  6414  6414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c84150c
08-25 03:25:15.261  6414  6974 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-25 03:25:15.261  6414  6974 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 03:25:15.261  6414  6974 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 03:25:15.261  6414  6974 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-25 03:25:15.262   310  2157 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 6414
08-25 03:25:15.262  6414  6414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c84150c
08-25 03:25:15.262   310  2157 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-25 03:25:15.262   310  2157 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-25 03:25:15.262   310  2157 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-25 03:25:15.262   310  2157 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-25 03:25:15.262   310  2157 V voice   : voice_set_parameters: exit with code(0)
08-25 03:25:15.262   310  2157 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-25 03:25:15.262   310  2157 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-25 03:25:15.262   310  2157 V msm8974_platform: platform_set_parameters: exit with code(0)
08-25 03:25:15.262   310  2157 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-25 03:25:15.262   310  2157 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-25 03:25:15.262   310  2157 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-25 03:25:15.263  6414  6974 V ToneGenerator: ToneGenerator destructor
08-25 03:25:15.263  6414  6974 V ToneGenerator: stopTone
08-25 03:25:15.263  6414  6974 V ToneGenerator: Delete Track: 0xb4928080
08-25 03:25:15.263  6414  6974 V AudioTrack: ~AudioTrack, releasing session id from 6414 on behalf of 6414
08-25 03:25:15.263   310  2158 V AudioFlinger: releasing 20 from 6414 for 6414
08-25 03:25:15.263   310  2158 V AudioFlinger:  decremented refcount to 0
08-25 03:25:15.263   310  2158 V AudioFlinger: purging stale effects
08-25 03:25:15.263   310  2158 V AudioPolicyService: AudioCommandThread() adding release output 2
08-25 03:25:15.263   310  2158 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
,08-25 03:25:15.263   310  2158 V AudioFlinger: PlaybackThread::Track destructor
,08-25 03:25:15.263   310  1271 V AudioPolicyService: AudioCommandThread() waking up
08-25 03:25:15.264   310  2158 V AudioFlinger: removeClient_l() pid 6414, calling pid 310
08-25 03:25:15.264   310  1271 V AudioPolicyService: AudioCommandThread() processing release output 2
08-25 03:25:15.264   310  1271 V AudioPolicyManager: releaseOutput() 2
08-25 03:25:15.264   310  1271 V AudioPolicyService: AudioCommandThread() going to sleep
08-25 03:25:15.264  6414  6414 D A2dpService: Received start request. Starting profile...
08-25 03:25:15.265  6414  6414 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 03:25:15.266  6414  6414 V Avrcp   : make
08-25 03:25:15.266  6414  6414 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-25 03:25:15.266  6414  6414 I bluedroid-qcom: get_profile_interface avrcp
08-25 03:25:15.276  6414  6414 V AudioManager: registerRemoteController: size of Media player list: 0
,08-25 03:25:15.278  6414  6414 E AudioManager: No RCC entry present to update
08-25 03:25:15.278  6414  6414 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-25 03:25:15.281  6414  6414 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-25 03:25:15.282  6414  6414 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-25 03:25:15.282  6414  6414 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-25 03:25:15.287  6414  6414 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-25 03:25:15.336  6954  6954 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-25 03:25:15.336  6954  6954 W LG Account v2.2: No ProfileInfo entries
08-25 03:25:15.336  6954  6954 I LG Account v2.2: isEnabled: false
08-25 03:25:15.337  6954  6954 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-25 03:25:15.337  6954  6954 I Feature : [Lifetracker]Country: EU
08-25 03:25:15.337  6954  6954 I Feature : [Lifetracker]Operator: OPEN
08-25 03:25:15.337  6954  6954 I Feature : [Lifetracker]Ranking support: false
08-25 03:25:15.337  6954  6954 I Feature : [Lifetracker]Comfort support: false
08-25 03:25:15.337  6954  6954 I Feature : [Lifetracker]Accessory: true
08-25 03:25:15.337  6954  6954 I Feature : [Lifetracker]Health device: true
08-25 03:25:15.337  6954  6954 I Feature : [Lifetracker]Extra Pedometer: false
08-25 03:25:15.337  6954  6954 I Feature : [Lifetracker]Blood glucose device: false
08-25 03:25:15.337  6954  6954 I Feature : [Lifetracker]Device Number: 3
08-25 03:25:15.347  6274  6274 D BluetoothPermissionRequest: onReceive
,08-25 03:25:15.352  6274  6274 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 03:25:15.387  1069  1926 V SIM_STK : Menu title from STK is T-Mobile
08-25 03:25:15.387  1069  1926 V SIM_STK : Menu title from STK is T-Mobile
,08-25 03:25:15.493  1069  1926 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-25 03:25:15.513  6414  6414 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-25 03:25:15.520  6414  6414 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-25 03:25:15.521  6414  6414 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 03:25:15.521  6414  6414 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 03:25:15.521  6414  6414 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 03:25:15.522  6414  6414 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 03:25:15.522  6414  6414 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 03:25:15.522  6414  6414 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
,08-25 03:25:15.522  6414  6414 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 03:25:15.522  6414  6414 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 03:25:15.522  6414  6414 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 03:25:15.522  6414  6414 I BluetoothA2dpServiceJni: classInitNative
08-25 03:25:15.523  6414  6414 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 03:25:15.523  6414  6414 D A2dpStateMachine: make
08-25 03:25:15.526  6414  6414 I bluedroid-qcom: get_profile_interface a2dp
08-25 03:25:15.527  6414  6981 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
,08-25 03:25:15.533  6414  6414 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
,08-25 03:25:15.534  6414  6414 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-25 03:25:15.537  6414  6414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c84150c
08-25 03:25:15.538  6414  6980 D A2dpStateMachine: Enter Disconnected: -2
08-25 03:25:15.539  6414  6414 I BluetoothHidServiceJni: classInitNative: succeeds
08-25 03:25:15.544  6414  6414 D HidService: Received start request. Starting profile...
08-25 03:25:15.544  6414  6414 I bluedroid-qcom: get_profile_interface hidhost
,08-25 03:25:15.544  6414  6414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c84150c
08-25 03:25:15.545  6414  6414 I BluetoothHealthServiceJni: classInitNative: succeeds
,08-25 03:25:15.549  6414  6414 D HealthService: Received start request. Starting profile...
08-25 03:25:15.554  6414  6414 I bluedroid-qcom: get_profile_interface health
08-25 03:25:15.556  6414  6414 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-25 03:25:15.556  6414  6414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c84150c
08-25 03:25:15.558  6414  6414 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-25 03:25:15.562  6414  6414 D PanService: Received start request. Starting profile...
08-25 03:25:15.562  6414  6414 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 03:25:15.562  6414  6414 I bluedroid-qcom: get_profile_interface pan
,08-25 03:25:15.571  6414  6414 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-25 03:25:15.571  6414  6414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c84150c
,08-25 03:25:15.573  6414  6414 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-25 03:25:15.581  6414  6414 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 03:25:15.582  6414  6414 D BtGatt.GattService: Received start request. Starting profile...
08-25 03:25:15.582  6414  6414 D BtGatt.GattService: start()
08-25 03:25:15.582  6414  6414 I bluedroid-qcom: get_profile_interface gatt
08-25 03:25:15.583  6414  6414 D BtGatt.AdvertiseManager: advertise manager created
08-25 03:25:15.592  6414  6414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c84150c
,08-25 03:25:15.594  6414  6414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c84150c
08-25 03:25:15.595  6414  6414 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-25 03:25:15.596  6414  6414 V BluetoothMapService: BluetoothMapBinder()
08-25 03:25:15.597  6414  6414 D BluetoothMapService: Received start request. Starting profile...
08-25 03:25:15.597  6414  6414 D BluetoothMapService: start()
08-25 03:25:15.601  6414  6414 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-25 03:25:15.601  6414  6414 D BluetoothMapEmailAppObserver: createReceiver()
08-25 03:25:15.603  6414  6414 D BluetoothMapEmailAppObserver: initObservers()
08-25 03:25:15.603  6414  6414 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-25 03:25:15.613  6414  6414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c84150c
,08-25 03:25:15.614  6414  6414 D HeadsetStateMachine: Proxy object connected
08-25 03:25:15.614  6414  6414 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
,08-25 03:25:15.615  6414  6414 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-25 03:25:15.616  6414  6974 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-25 03:25:15.617  6414  6974 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 03:25:15.617  6414  6974 D HeadsetStateMachine: Disconnected process message: 11, size: 0
,08-25 03:25:15.623  6414  6414 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-25 03:25:15.629  6414  6414 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-25 03:25:15.633  6414  6414 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 03:25:15.637  6414  6414 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 03:25:15.641  6414  6414 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 03:25:15.641  6414  6414 V PanService: [BTUI] SIM Extra State :ABSENT
08-25 03:25:15.645  6414  6414 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-25 03:25:15.645  6414  6414 V BluetoothMapService: Handler(): got msg=1
08-25 03:25:15.646  6414  6934 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-25 03:25:15.646  6414  6934 I bluedroid-qcom: enable
08-25 03:25:15.647  6414  6934 I bt_hci_bdroid: init
,08-25 03:25:15.648  6414  6934 I bt_vendor: bt-vendor : init
08-25 03:25:15.648  6414  6934 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 03:25:15.648  6414  6934 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 03:25:15.648  6414  6934 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-25 03:25:15.648  6414  6934 D bt_userial_mct: userial_init
08-25 03:25:15.649  6414  6991 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-25 03:25:15.649  6414  6991 I bt-btu  : btu_task pending for preload complete event
08-25 03:25:15.650  6414  6934 D bt_hci_bdroid: set_power 1
08-25 03:25:15.650  6414  6934 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-25 03:25:15.650  6414  6934 I bt_vendor: Starting hciattach daemon
08-25 03:25:15.650  6414  6934 I bt_vendor: try to set true
08-25 03:25:15.651  6414  6414 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:15.653  6414  6414 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 03:25:15.654  6414  6414 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 03:25:15.654  6414  6414 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 03:25:15.654  6414  6414 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:15.654  6414  6414 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-25 03:25:15.648  6994  6994 W sh      : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:15.648  6994  6994 W sh      : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 03:25:15.699  6996  6996 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-25 03:25:15.816  7005  7005 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-25 03:25:15.841  7006  7006 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 03:25:15.873  7008  7008 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 03:25:15.887  7009  7009 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-25 03:25:15.900  7010  7010 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 03:25:15.917  7011  7011 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-25 03:25:15.954  7013  7013 I libmdmdetect: ESOC framework not supported
08-25 03:25:15.955  7013  7013 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-25 03:25:15.964  7013  7013 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
,08-25 03:25:15.964  7013  7013 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-25 03:25:15.964  7013  7013 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-25 03:25:15.964  7013  7013 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-25 03:25:15.964  7013  7013 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-25 03:25:15.965  7013  7013 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-25 03:25:15.965  7013  7013 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-25 03:25:16.000  7013  7014 E QC-QMI  : qmi_client [7013] 14: failed to locate client data
,08-25 03:25:16.001   470   470 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-25 03:25:16.001   470   470 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
08-25 03:25:16.047  7015  7015 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-25 03:25:16.062  7016  7016 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 03:25:16.104  6414  6934 I bt_vendor: bluetooth satus is on
08-25 03:25:16.105  6414  6934 D bt_hci_bdroid: preload
08-25 03:25:16.105  6414  6993 D bt_userial_mct: userial_open(port:0)
08-25 03:25:16.105  6414  6993 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-25 03:25:16.109  6414  6993 I bt_vendor: Done intiailizing UART
08-25 03:25:16.113  6414  6993 I bt_vendor: Done intiailizing UART
08-25 03:25:16.113  6414  6993 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-25 03:25:16.113  6414  6993 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-25 03:25:16.114  6414  7018 D bt_userial_mct: Entering userial_read_thread()
08-25 03:25:16.114  6414  6991 I bt-btu  : btu_task received preload complete event
08-25 03:25:16.114  6414  6991 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-25 03:25:16.114  6414  6991 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-25 03:25:16.120  6414  6991 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-25 03:25:16.131  6414  6991 I         : BTE_InitTraceLevels -- TRC_HCI
08-25 03:25:16.131  6414  6991 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 03:25:16.131  6414  6991 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 03:25:16.131  6414  6991 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 03:25:16.131  6414  6991 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 03:25:16.131  6414  6991 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 03:25:16.131  6414  6991 I         : BTE_InitTraceLevels -- TRC_BNEP
08-25 03:25:16.131  6414  6991 I         : BTE_InitTraceLevels -- TRC_BTM
08-25 03:25:16.131  6414  6991 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-25 03:25:16.131  6414  6991 I         : BTE_InitTraceLevels -- TRC_GAP
08-25 03:25:16.131  6414  6991 I         : BTE_InitTraceLevels -- TRC_PAN
08-25 03:25:16.131  6414  6991 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 03:25:16.131  6414  6991 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 03:25:16.131  6414  6991 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 03:25:16.131  6414  6991 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-25 03:25:16.132  6414  6991 I         : BTE_InitTraceLevels -- TRC_BTIF
08-25 03:25:16.187  6414  6991 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-25 03:25:16.187  6414  6991 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa015d061 
08-25 03:25:16.187  6414  6991 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa015d061 
,08-25 03:25:16.212  6414  6938 E bt-btif : Calling BTA_HhEnable
,08-25 03:25:16.212  6414  6938 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-25 03:25:16.212  6414  6938 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-25 03:25:16.214  1069  1069 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 03:25:16.215  1069  1069 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 03:25:16.215  6414  6938 D BluetoothAdapterProperties: Name is: G3
08-25 03:25:16.217  6414  6938 D BluetoothAdapterProperties: Scan Mode:20
08-25 03:25:16.217  6414  6938 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 03:25:16.218  6414  6938 D bt_hci_bdroid: postload
08-25 03:25:16.220  6414  6938 D bte_conf: Device ID record 1 : primary
08-25 03:25:16.220  6414  6938 D bte_conf:   vendorId            = 00c4
08-25 03:25:16.220  6414  6938 D bte_conf:   vendorIdSource      = 0001
08-25 03:25:16.220  6414  6938 D bte_conf:   product             = 13a1
08-25 03:25:16.220  6414  6938 D bte_conf:   version             = 1000
08-25 03:25:16.220  6414  6938 D bte_conf:   clientExecutableURL = 
08-25 03:25:16.220  6414  6938 D bte_conf:   serviceDescription  = 
08-25 03:25:16.220  6414  6938 D bte_conf:   documentationURL    = 
08-25 03:25:16.221  6414  6993 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 03:25:16.221  6414  6938 D bte_conf: bte_load_did_conf no section named DID2.
08-25 03:25:16.230  6414  6993 D bt_hci_bdroid: Used up Tx Cmd credits
,08-25 03:25:16.244  6414  7018 E bt_mct  : hci lib postload completed
,08-25 03:25:16.247  6414  6934 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-25 03:25:16.247  6414  6934 D BluetoothAdapterProperties: ScanMode =  20
08-25 03:25:16.248  6414  6934 D BluetoothAdapterProperties: State =  11
08-25 03:25:16.248  6414  6934 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-25 03:25:16.248  6414  6934 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-25 03:25:16.248  6414  6934 D BluetoothAdapterProperties: Setting state to 12
08-25 03:25:16.248  6414  6934 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 03:25:16.249  6414  6938 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 03:25:16.248  7024  7024 W sh      : type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:16.248  7024  7024 W sh      : type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:16.257  1069  1176 D BluetoothManagerService: Message: 60
08-25 03:25:16.257  1069  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-25 03:25:16.257  1069  1176 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
,08-25 03:25:16.271  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:16.271  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:16.271  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:16.271  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:25:16.271  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:25:16.271  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:25:16.271  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:25:16.271  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:25:16.279  6414  6934 I BluetoothAdapterState: Entering On State
08-25 03:25:16.290  6414  6934 D LGBluetoothServiceAdapter: [BTUI] OnState
08-25 03:25:16.290  6414  6934 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-25 03:25:16.290  6414  6934 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-25 03:25:16.293  6414  6934 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-25 03:25:16.295  6126  6126 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:25:16.299  6414  6938 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 03:25:16.299  6414  6938 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-25 03:25:16.307  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:16.307  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:16.307  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:16.307  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:25:16.307  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:25:16.307  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:25:16.307  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:25:16.307  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:25:16.319  6126  6126 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:25:16.325  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:16.325  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:16.325  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:16.325  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:25:16.325  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:25:16.325  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:25:16.325  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:25:16.325  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:25:16.328  6126  6126 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:25:16.333  6414  6934 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-25 03:25:16.336  6414  6991 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-25 03:25:16.336  6414  6991 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-25 03:25:16.336  6414  6991 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-25 03:25:16.336  6414  6991 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-25 03:25:16.336  6414  6991 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-25 03:25:16.336  6414  6991 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-25 03:25:16.337  6414  6938 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-25 03:25:16.337  6274  6293 D BluetoothMap: onBluetoothStateChange: up=true
08-25 03:25:16.362  7029  7029 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
,08-25 03:25:16.375  6274  6274 D BluetoothMap: Proxy object connected
08-25 03:25:16.375  6274  6274 D MapProfile: Bluetooth service connected
08-25 03:25:16.375  6274  6274 D BluetoothMap: getConnectedDevices()
08-25 03:25:16.382  1836  2694 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 03:25:16.387  6414  6430 V BluetoothMapService: getConnectedDevices()
08-25 03:25:16.387  6414  6991 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 03:25:16.387  6414  6991 W bt-smp  : Plain text(LSB ~ MSB) = 05 e3 46 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 03:25:16.387  6414  6991 W bt-smp  : Encrypted text(LSB ~ MSB) = 4c 9e 3f 12 f5 6c c8 12 cf a1 36 4a 5c 14 ff b8 
08-25 03:25:16.388  6414  6991 W bt-btm  : Stopping oneshot timer
08-25 03:25:16.389  6274  6292 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 03:25:16.392  1836  1836 D BluetoothHeadset: Proxy object connected
08-25 03:25:16.393  1069  1176 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 03:25:16.395  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 03:25:16.399  1069  1069 D BluetoothA2dp: Proxy object connected
08-25 03:25:16.399  1836  1836 D BluetoothHeadset: Proxy object connected
08-25 03:25:16.400  1069  1176 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 03:25:16.401  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 03:25:16.403  1836  1836 D BluetoothHeadset: Proxy object connected
08-25 03:25:16.403  6274  6293 D BluetoothPan: onBluetoothStateChange on: true
08-25 03:25:16.403  6274  6293 D BluetoothPan: onBluetoothStateChange call bindService
08-25 03:25:16.404  1069  1069 D BluetoothHeadset: Proxy object connected
08-25 03:25:16.406  6414  6991 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 03:25:16.406  6414  6991 W bt-smp  : Plain text(LSB ~ MSB) = a3 71 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 03:25:16.407  6414  6991 W bt-smp  : Encrypted text(LSB ~ MSB) = 55 02 83 16 2b 31 93 60 8b 95 b8 1b 1e ef 01 5c 
08-25 03:25:16.407  6414  6991 W bt-btm  : Stopping oneshot timer
08-25 03:25:16.408  6274  6274 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 03:25:16.408  6274  6274 D PanProfile: Bluetooth service connected
08-25 03:25:16.408  6274  7035 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-25 03:25:16.413  1069  1176 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-25 03:25:16.413  1069  1176 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-25 03:25:16.415  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:16.415  6274  6274 D BluetoothInputDevice: Proxy object connected
,08-25 03:25:16.415  6274  6274 D HidProfile: Bluetooth service connected
08-25 03:25:16.415  1925  2075 D LGBluetoothAPIService: Message: 1
08-25 03:25:16.416  1925  2075 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-25 03:25:16.418  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 03:25:16.424  6414  6991 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 03:25:16.424  6414  6991 W bt-smp  : Plain text(LSB ~ MSB) = 0b 6f 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 03:25:16.424  6414  6991 W bt-smp  : Encrypted text(LSB ~ MSB) = fc 4d 9b a8 67 9d 9e dc c7 5e 63 71 da b7 e5 72 
08-25 03:25:16.424  6414  6991 W bt-btm  : Stopping oneshot timer
,08-25 03:25:16.429  6126  6126 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-25 03:25:16.430  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:16.431  1069  1069 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-25 03:25:16.432  1069  1176 D BluetoothManagerService: Message: 40
08-25 03:25:16.432  1069  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-25 03:25:16.433  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:16.435  1925  2075 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-25 03:25:16.436  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:25:16.437  6414  6414 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:16.437  6414  6414 D BluetoothMapService: STATE_ON
08-25 03:25:16.438  6414  6991 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 03:25:16.438  6414  6991 W bt-smp  : Plain text(LSB ~ MSB) = c8 9b 5a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 03:25:16.438  6414  6991 W bt-smp  : Encrypted text(LSB ~ MSB) = 5c d9 e1 f3 42 76 14 91 95 91 4d b7 8b c9 a5 2f 
08-25 03:25:16.438  6414  6991 W bt-btm  : Stopping oneshot timer
08-25 03:25:16.439  6274  6274 D LocalBluetoothProfileManager: Adding local A2DP profile
08-25 03:25:16.440  6414  6414 D LGBluetoothAPIServer: [BTUI] onCreate()
08-25 03:25:16.441  6414  6414 D LGBluetoothAPIServer: [BTUI] onBind()
08-25 03:25:16.442  6414  6414 V BluetoothMapService: Handler(): got msg=1
08-25 03:25:16.442  1069  1176 D BluetoothManagerService: Message: 30
08-25 03:25:16.442  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-25 03:25:16.442  6414  6414 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-25 03:25:16.442  1925  2075 D LGBluetoothAPIService: Message: 100
,08-25 03:25:16.442  1925  2075 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-25 03:25:16.444  6414  7050 D BluetoothMapMasInstance: MAS initSocket()
08-25 03:25:16.445  6414  7050 D BluetoothMapMasInstance:   masId = 00
08-25 03:25:16.445  6414  7050 D BluetoothMapMasInstance:   msgTypes = 0e
08-25 03:25:16.445  6414  7050 D BluetoothMapMasInstance:   masName = SMS/MMS
08-25 03:25:16.445  6414  7050 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-25 03:25:16.446  1069  1559 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:25:16.446  6274  6274 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-25 03:25:16.447  6414  7050 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 03:25:16.449  1069  1176 D BluetoothManagerService: Message: 30
08-25 03:25:16.452  6414  6991 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 03:25:16.452  6414  6991 W bt-smp  : Plain text(LSB ~ MSB) = f0 0d 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 03:25:16.452  6414  6991 W bt-smp  : Encrypted text(LSB ~ MSB) = 30 c8 1b 85 aa 22 d4 7f 2e 76 53 56 15 c7 2a eb 
08-25 03:25:16.452  6414  6991 W bt-btm  : Stopping oneshot timer
08-25 03:25:16.452  6414  6938 D BluetoothAdapterProperties: Scan Mode:21
08-25 03:25:16.452  6414  6938 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
,08-25 03:25:16.453  6414  7050 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-25 03:25:16.454  6414  7050 V BluetoothMapMasInstance: Succeed to create listening socket 
08-25 03:25:16.454  6414  7050 D BluetoothMapMasInstance: Accepting socket connection...
08-25 03:25:16.456  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:16.458  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:16.460  6414  6414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c84150c
08-25 03:25:16.460  6414  6414 V BluetoothPbapService: Pbap Service onCreate
08-25 03:25:16.460  6414  6414 V BluetoothPbapService: Starting PBAP service
,08-25 03:25:16.460  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:16.462  6414  6414 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-25 03:25:16.462  6414  6414 V BluetoothPbapService: Pbap Service onBind
08-25 03:25:16.463  6414  6414 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:16.463  6414  6414 V BluetoothPbapService: state: 12
08-25 03:25:16.464  6414  6414 V BluetoothPbapService: Handler(): got msg=1
08-25 03:25:16.464  6414  6414 V BluetoothPbapService: Pbap Service startRfcommSocketListener
,08-25 03:25:16.467  6274  6274 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-25 03:25:16.469  6274  6274 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 03:25:16.471  6414  7051 V BluetoothPbapService: Pbap Service initSocket
08-25 03:25:16.472  1069  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:25:16.473  6274  6274 D BluetoothA2dp: Proxy object connected
08-25 03:25:16.474  6274  6274 D A2dpProfile: Bluetooth service connected
08-25 03:25:16.474  6414  6414 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 03:25:16.475  6414  6414 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:16.475  6414  6414 V BluetoothPbapReceiver: ***********state = 12
08-25 03:25:16.476  6274  6274 D BluetoothHeadset: Proxy object connected
08-25 03:25:16.476  6414  7051 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-25 03:25:16.477  6274  6274 D HeadsetProfile: Bluetooth service connected
08-25 03:25:16.480  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 03:25:16.481  6414  7051 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-25 03:25:16.481  6414  7051 V BluetoothPbapService: Succeed to create listening socket 
08-25 03:25:16.481  2169  2169 D c       : Getting all permits...
08-25 03:25:16.481  6414  7051 V BluetoothPbapService: Accepting socket connection...
08-25 03:25:16.481  2169  2169 D a       : Opening database...
08-25 03:25:16.485  2169  2169 D a       : Opening database auth.proximity.permit_store...
08-25 03:25:16.486  2169  2169 D a       : Closing database...
08-25 03:25:16.486  6274  6274 D BluetoothPbap: Proxy object connected
08-25 03:25:16.487  6274  6274 D PbapServerProfile: Bluetooth service connected
08-25 03:25:16.491  6274  6274 D DockEventReceiver: finishStartingService: stopping service
,08-25 03:25:16.500  6274  6274 D BluetoothPermissionRequest: onReceive
08-25 03:25:16.502  6274  6274 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
,08-25 03:25:16.504  6274  6274 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 03:25:16.508  6414  6414 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-25 03:25:16.509  6414  6414 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-25 03:25:16.518  6414  6414 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-25 03:25:16.539  6414  6414 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 03:25:16.540  6414  6414 V BtOppService: onCreate
,08-25 03:25:16.544  6414  6414 V BluetoothOppNotification: send message
08-25 03:25:16.547  6414  6414 V BtOppService: Starting RfcommListener
08-25 03:25:16.552  6414  6414 D BluetoothOppPreference: Dumping Names:  
08-25 03:25:16.552  6414  6414 D BluetoothOppPreference: {}
08-25 03:25:16.552  6414  6414 D BluetoothOppPreference: Dumping Channels:  
08-25 03:25:16.552  6414  6414 D BluetoothOppPreference: {}
,08-25 03:25:16.553  6414  6414 V BtOppService: onStartCommand
08-25 03:25:16.556  6414  7058 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
,08-25 03:25:16.557  6414  6414 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-25 03:25:16.557  6414  6414 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 03:25:16.561  6414  6414 V BluetoothOppNotification: new notify threadi!
08-25 03:25:16.562  6414  6414 V BluetoothOppNotification: send delay message
08-25 03:25:16.563  6414  6414 V BtOppService: start RfcommListener
08-25 03:25:16.565  6414  6414 V BtOppService: RfcommListener started
08-25 03:25:16.567  6414  7060 V BtOppRfcommListener: Starting RFCOMM listener....
08-25 03:25:16.568  1069  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:25:16.569  6414  7060 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 03:25:16.571  6414  7060 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
,08-25 03:25:16.577  6414  7060 V BtOppRfcommListener: Started RFCOMM listener....
08-25 03:25:16.577  6414  7060 I BtOppRfcommListener: Accept thread started.
08-25 03:25:16.577  6414  7060 V BtOppRfcommListener: Accepting connection...
08-25 03:25:16.577  6414  7055 V BtOppService: Deleted complete outbound shares, number =  0
08-25 03:25:16.578  6414  7058 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 03:25:16.578  6414  7059 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 03:25:16.580  6414  6414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c84150c
,08-25 03:25:16.580  6414  6414 V BluetoothFtpService: Ftp Service onCreate
08-25 03:25:16.580  6414  6414 I BluetoothFtpService: Ftp Service onCreate
08-25 03:25:16.581  6414  6414 V BluetoothFtpService: Ftp Service onStartCommand
08-25 03:25:16.581  6414  6414 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:16.581  6414  6414 V BluetoothFtpService: Starting Listening on sockets
08-25 03:25:16.582  6414  6414 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 03:25:16.582  6414  6414 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 03:25:16.582  6414  6414 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 03:25:16.582  6414  6414 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:16.582  6414  6414 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-25 03:25:16.582  6414  6414 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 03:25:16.583  6414  7058 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33853546 on behalf of 
08-25 03:25:16.586  6414  6414 V BtOppService: ContentObserver received notification
08-25 03:25:16.586  6414  6414 V BluetoothFtpService: Handler(): got msg=1
,08-25 03:25:16.586  6414  7055 V BtOppService: Deleted complete inbound failed shares, number = 0
08-25 03:25:16.587  6414  7055 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-25 03:25:16.589  6414  7059 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@173307 on behalf of 
08-25 03:25:16.589  6414  6414 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-25 03:25:16.589  6414  6414 V BluetoothFtpService: Ftp Service initSocket
08-25 03:25:16.591  6414  7055 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@19d70c34 on behalf of 
08-25 03:25:16.591  1069  1888 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:25:16.592  6414  7058 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 03:25:16.592  6414  7058 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 03:25:16.592  6414  6414 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 03:25:16.593  6414  6414 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=78
08-25 03:25:16.593  6414  6414 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-25 03:25:16.596  6414  7059 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 03:25:16.597  6414  7061 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-25 03:25:16.598  6414  7058 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a803a5d on behalf of 
08-25 03:25:16.600  6414  7058 V BluetoothOppNotification: update too frequent, put in queue
,08-25 03:25:16.601  6414  7059 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 03:25:16.603  6414  7059 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b4f5fd2 on behalf of 
08-25 03:25:16.603  6414  7058 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 03:25:16.604  6414  7059 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 03:25:16.605  6414  7059 V BluetoothOppNotification: outbound notification was removed.
08-25 03:25:16.605  6414  7059 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 03:25:16.606  6414  7059 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e69f8a3 on behalf of 
08-25 03:25:16.607  6414  7059 V BluetoothOppNotification: inbound: succ-0  fail-0
08-25 03:25:16.609  6414  7059 V BluetoothOppNotification: inbound notification was removed.
08-25 03:25:16.609  6414  7059 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 03:25:16.611  6414  7059 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1df2b7a0 on behalf of 
08-25 03:25:16.615  6414  6414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c84150c
,08-25 03:25:16.615  6414  6414 V BluetoothSapService: Sap Service onCreate
08-25 03:25:16.617  6414  6414 V BtOppService: ContentObserver received notification
08-25 03:25:16.618  6414  6414 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:16.618  6414  6414 V BluetoothSapService: state: 12
08-25 03:25:16.618  6414  6414 V BluetoothSapService: Starting SAP server process
08-25 03:25:16.619  6414  7062 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 03:25:16.619  6414  7062 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 03:25:16.620  6414  6414 V BluetoothSapService: SAP Service startRfcommListenerThread
08-25 03:25:16.618  7063  7063 W sapd    : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:16.618  7063  7063 W sapd    : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:16.621  6414  7064 V BluetoothSapService: Sap Service initRfcommSocket
08-25 03:25:16.622  1069  1864 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:25:16.622  6414  7062 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@a5badcc on behalf of 
08-25 03:25:16.623  6414  7062 V BluetoothOppNotification: update too frequent, put in queue
08-25 03:25:16.624  6414  7064 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 03:25:16.625  6414  7064 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=83 mFd=82
08-25 03:25:16.625  6414  7064 V BluetoothSapService: Succeed to create listening socket 
08-25 03:25:16.625  6414  7064 V BluetoothSapService: Accepting socket connection...
08-25 03:25:16.625  6414  7062 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 03:25:16.642  7063  7063 V BT_SAP  : Event pipe created
08-25 03:25:16.642  7063  7063 V BT_SAP  : create_server_socket qcom.sap.server
08-25 03:25:16.642  7063  7063 V BT_SAP  : created socket fd 6
,08-25 03:25:17.564  6414  6414 V BluetoothOppNotification: new notify threadi!
,08-25 03:25:17.565  6414  6414 V BluetoothOppNotification: send delay message
,08-25 03:25:17.578  6414  7075 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 03:25:17.582  6414  7075 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@fc55815 on behalf of 
,08-25 03:25:17.586  6414  7075 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-25 03:25:17.587  6414  7075 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 03:25:17.588  6414  7075 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d1b172a on behalf of 
08-25 03:25:17.589  6414  7075 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 03:25:17.590  6414  7075 V BluetoothOppNotification: outbound notification was removed.
08-25 03:25:17.590  6414  7075 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 03:25:17.591  6414  7075 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a13d91b on behalf of 
08-25 03:25:17.592  6414  7075 V BluetoothOppNotification: inbound: succ-0  fail-0
08-25 03:25:17.593  6414  7075 V BluetoothOppNotification: inbound notification was removed.
08-25 03:25:17.594  6414  7075 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 03:25:17.595  6414  7075 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c7bdab8 on behalf of 
,08-25 03:25:18.439  6814  6835 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-25 03:25:19.256  1069  1960 I ActivityManager: Killing 6002:com.lge.bnr/1000 (adj 15): empty #17
,08-25 03:25:19.288  1069  1096 W libprocessgroup: failed to open /acct/uid_1000/pid_6002/cgroup.procs: No such file or directory
,08-25 03:25:20.004  1069  1996 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 03:25:20.004  1069  1996 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@1579d04d mBinding = false
,08-25 03:25:20.032  1069  1069 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 03:25:20.032  1069  1069 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 03:25:20.032  1069  1069 D Ulp_jni : JNI:system_update. Event-4
,08-25 03:25:20.036  1069  1176 D BluetoothManagerService: Message: 2
08-25 03:25:20.036  1069  1176 D BluetoothManagerService: Sending off request.
08-25 03:25:20.037  6414  6431 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-25 03:25:20.038  6414  6934 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-25 03:25:20.038  6414  6934 D BluetoothAdapterProperties: Setting state to 13
08-25 03:25:20.038  6414  6934 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-25 03:25:20.039  6414  6934 D BluetoothAdapterProperties: onBluetoothDisable()
08-25 03:25:20.039  6414  6934 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-25 03:25:20.041  6414  6938 D BluetoothAdapterProperties: Scan Mode:20
08-25 03:25:20.042  6414  6934 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-25 03:25:20.044  6414  7051 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 03:25:20.046  6414  7060 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-25 03:25:20.048  6414  7061 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 03:25:20.049  6414  7064 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 03:25:20.049  6414  6991 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-25 03:25:20.049  6414  6991 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-25 03:25:20.051  6414  7050 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-25 03:25:20.051  6414  7050 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-25 03:25:20.051  6414  7050 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-25 03:25:20.051  6414  7050 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-25 03:25:20.051  6414  7050 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-25 03:25:20.051  6414  7050 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-25 03:25:20.051  6414  7050 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-25 03:25:20.051  6414  7050 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-25 03:25:20.052  6414  6934 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 03:25:20.056  6414  6991 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 03:25:20.056  6414  6991 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 03:25:20.056  6414  6991 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 03:25:20.056  6414  6991 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 03:25:20.056  6414  6991 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 03:25:20.056  6414  6991 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 03:25:20.056  6414  6991 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 03:25:20.056  6414  6991 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 03:25:20.056  6414  6991 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 03:25:20.056  6414  6991 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-25 03:25:20.056  6414  6991 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-25 03:25:20.061  6414  6991 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
,08-25 03:25:20.069  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:20.069  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:20.069  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:20.069  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:20.069  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:25:20.069  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:25:20.069  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:25:20.069  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:25:20.069  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:25:20.072  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:20.072  6126  6126 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:25:20.077  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:20.078  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:20.078  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:20.078  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:20.078  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:25:20.078  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:25:20.078  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:25:20.078  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:25:20.078  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:25:20.079  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:20.079  6126  6126 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:25:20.082  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:20.082  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:20.082  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:20.082  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:20.082  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:25:20.082  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-25 03:25:20.082  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:25:20.082  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:25:20.082  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:25:20.084  6126  6126 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-25 03:25:20.084  6126  6126 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:25:20.087  1069  1176 D BluetoothManagerService: Message: 60
08-25 03:25:20.087  1069  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-25 03:25:20.087  1069  1176 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-25 03:25:20.089  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:20.091  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 03:25:20.096  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:25:20.099  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:20.101  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:20.103  6414  6414 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:20.103  6414  6414 D BluetoothMapService: STATE_TURNING_OFF
08-25 03:25:20.103  6414  6414 V BluetoothMapService: Handler(): got msg=4
08-25 03:25:20.103  6414  6414 D BluetoothMapService: MAP Service closeService in
08-25 03:25:20.103  6414  6414 D BluetoothMapMasInstance: MAP Service shutdown
08-25 03:25:20.103  6414  6414 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 03:25:20.103  6414  6414 V BluetoothMapService: MAP Service closeService out
08-25 03:25:20.104  6414  6414 V BtOppService: Receiver DISABLED_ACTION 
08-25 03:25:20.105  6414  6414 I BtOppRfcommListener: stopping Accept Thread
08-25 03:25:20.105  6414  6414 V BtOppRfcommListener: close mBtServerSocket
08-25 03:25:20.105  6414  7060 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-25 03:25:20.106  6414  6414 V BtOppRfcommListener: waiting for thread to terminate
08-25 03:25:20.106  6414  6414 V BtOppRfcommListener: done waiting for thread to terminate
08-25 03:25:20.109  6274  6274 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
,08-25 03:25:20.119  6274  6274 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 03:25:20.121  6414  6414 V BtOppService: onDestroy
,08-25 03:25:20.125  6414  6414 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-25 03:25:20.129  6414  6414 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 03:25:20.129  6414  6414 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:20.130  6414  6414 V BluetoothPbapReceiver: ***********state = 13
08-25 03:25:20.131  6414  6414 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-25 03:25:20.133  6414  6414 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:20.133  6414  6414 V BluetoothPbapService: state: 13
08-25 03:25:20.133  6414  6414 V BluetoothPbapService: Pbap Service closeService in
,08-25 03:25:20.139  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 03:25:20.141  6414  6414 V BluetoothPbapService: successfully stopped pbap service
08-25 03:25:20.141  6414  6414 V BluetoothPbapService: Pbap Service closeService out
08-25 03:25:20.142  6414  6414 V BluetoothPbapService: Pbap Service onDestroy
08-25 03:25:20.142  6414  6414 V BluetoothPbapService: Pbap Service closeService in
08-25 03:25:20.142  6414  6414 V BluetoothPbapService: Pbap Service closeService out
08-25 03:25:20.142  6414  6414 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-25 03:25:20.169  6274  6274 D DockEventReceiver: finishStartingService: stopping service
08-25 03:25:20.172  6274  6274 D BluetoothPbap: Proxy object disconnected
08-25 03:25:20.172  6274  6274 D PbapServerProfile: Bluetooth service disconnected
,08-25 03:25:20.179  1069  1445 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
08-25 03:25:20.179  6274  6274 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-25 03:25:20.186  6274  6274 D BluetoothPermissionRequest: onReceive
08-25 03:25:20.186  6274  6274 D LGBluetoothAuthorization: [BTUI] cancel All Notification
08-25 03:25:20.191  6274  6274 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 03:25:20.194  6414  6414 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-25 03:25:20.194  6414  6414 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
08-25 03:25:20.196  6414  6414 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
,08-25 03:25:20.202  6414  6414 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:20.202  6414  6414 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 03:25:20.203  6414  6414 V BluetoothFtpService: Ftp Service onStartCommand
08-25 03:25:20.204  6414  6414 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:20.204  6414  6414 V BluetoothFtpService: Ftp Service closeService
08-25 03:25:20.204  6414  6414 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-25 03:25:20.205  6414  6414 V BluetoothFtpService: successfully stopped ftp service
08-25 03:25:20.206  6414  6414 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 03:25:20.206  6414  6414 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 03:25:20.206  6414  6414 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 03:25:20.206  6414  6414 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:20.206  6414  6414 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-25 03:25:20.206  6414  6414 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 03:25:20.207  6414  6414 V BluetoothFtpService: Ftp Service onDestroy
08-25 03:25:20.207  6414  6414 V BluetoothFtpService: Ftp Service closeService
08-25 03:25:20.213  6414  6414 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:20.213  6414  6414 V BluetoothSapService: state: 13
08-25 03:25:20.213  6414  6414 V BluetoothSapService: Stopping SAP server process
08-25 03:25:20.214  6414  6414 V BluetoothSapService: Sap Service closeSapService in
08-25 03:25:20.215  6414  6414 V BluetoothSapService: Close listen Socket : 
08-25 03:25:20.215  6414  6414 V BluetoothSapService: Close rfcomm Socket : 
08-25 03:25:20.215  6414  6414 V BluetoothSapService: Close sapd  Socket : 
08-25 03:25:20.219  6414  6414 V BluetoothSapService: Sap Service closeSapService out
,08-25 03:25:20.219  6414  6414 V BluetoothSapService: Sap Service onDestroy
,08-25 03:25:20.219  6414  6414 V BluetoothSapService: Sap Service closeSapService in
,08-25 03:25:20.219  6414  6414 V BluetoothSapService: Close listen Socket : 
08-25 03:25:20.219  6414  6414 V BluetoothSapService: Close rfcomm Socket : 
,08-25 03:25:20.219  6414  6414 V BluetoothSapService: Close sapd  Socket : 
08-25 03:25:20.220  6414  6414 V BluetoothSapService: Sap Service closeSapService out
08-25 03:25:20.955  6414  6938 D bt_hci_bdroid: cleanup
,08-25 03:25:20.965  6414  6993 I bt_lpm  : LPM is already off!!!
08-25 03:25:20.966  6414  7018 I bt_userial_mct: exiting userial_read_thread
08-25 03:25:20.966  6414  7018 D bt_userial_mct: Leaving userial_evt_read_thread()
08-25 03:25:20.967  6414  6991 W bt-btif : ag scb idx 1 not allocated
08-25 03:25:20.967  6414  6991 E bt-btif : BTA AG is already disabled, ignoring ...
08-25 03:25:20.967  6414  6991 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 03:25:20.967  6414  6991 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 03:25:20.968  6414  6991 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 03:25:20.968  6414  6991 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 03:25:20.968  6414  6991 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 03:25:20.968  6414  6991 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 03:25:20.968  6414  6991 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 03:25:20.968  6414  6991 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,08-25 03:25:20.968  6414  6991 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 03:25:20.968  6414  6991 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 03:25:20.968  6414  6991 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
,08-25 03:25:20.968  6414  6991 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-25 03:25:20.968  6414  6991 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-25 03:25:20.968  6414  6991 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-25 03:25:20.968  6414  6991 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-25 03:25:20.968  6414  6991 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-25 03:25:20.968  6414  6991 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-25 03:25:20.968  6414  6991 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-25 03:25:20.969  6414  6991 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-25 03:25:20.973  6414  6938 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-25 03:25:20.973  6414  6993 I bt_vendor: hw_epilog_process
08-25 03:25:20.973  6414  6938 D bt_hci_bdroid: cleanup Finalizing cleanup,
08-25 03:25:20.973  6414  6938 D bt_userial_mct: userial_close
08-25 03:25:20.973  6414  6938 E bt_userial_mct: pthread_join() FAILED result:3
,08-25 03:25:20.974  6414  6938 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-25 03:25:20.981  6414  6938 D bt_hci_bdroid: set_power 0
08-25 03:25:20.982  6414  6938 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-25 03:25:20.982  6414  6938 I bt_vendor: bluetooth satus is on
,08-25 03:25:20.982  6414  6938 I bt_vendor: bt-vendor : resetting BT status
08-25 03:25:20.982  6414  6938 I bt_vendor: Starting hciattach daemon
08-25 03:25:20.982  6414  6938 I bt_vendor: try to set false
,08-25 03:25:20.991  6414  6938 I bt_vendor: Starting hciattach daemon
08-25 03:25:20.991  6414  6938 I bt_vendor: try to set false
08-25 03:25:20.993  6414  6938 I bt_vendor: cleanup
08-25 03:25:20.993  6414  6991 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-25 03:25:20.994  6414  6938 I GKI_LINUX: GKI_exit_task 0 done
08-25 03:25:20.994  6414  6938 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-25 03:25:20.995  6414  6934 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-25 03:25:20.999  6414  6414 D HeadsetService: Received stop request...Stopping profile...
,08-25 03:25:21.004  6414  6414 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 03:25:21.004  6414  6414 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 03:25:21.004  6414  6414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c84150c
08-25 03:25:21.006  6414  6974 D HeadsetStateMachine: Exit Disconnected: -1
08-25 03:25:21.009  1069  1069 D BluetoothHeadset: Proxy object disconnected
08-25 03:25:21.009  1069  1069 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-25 03:25:21.009  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-25 03:25:21.010  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-25 03:25:21.010  1836  1836 D BluetoothHeadset: Proxy object disconnected
08-25 03:25:21.012  6414  6414 D A2dpService: Received stop request...Stopping profile...
,08-25 03:25:21.015  6414  6980 D A2dpStateMachine: Exit Disconnected: -1
08-25 03:25:21.018  6414  6414 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
08-25 03:25:21.021  6414  6934 D BluetoothAdapterState: Stopping profile services that were post enabled
08-25 03:25:21.021  6414  6414 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-25 03:25:21.021  6414  6414 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 03:25:21.021  6414  6414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c84150c
08-25 03:25:21.023  1069  1069 D BluetoothA2dp: Proxy object disconnected
08-25 03:25:21.023  1069  1069 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-25 03:25:21.024  6414  6414 D HidService: Received stop request...Stopping profile...
08-25 03:25:21.024  6414  6414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c84150c
,08-25 03:25:21.030  6414  6414 D HealthService: Received stop request...Stopping profile...
08-25 03:25:21.030  6414  6414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c84150c
08-25 03:25:21.033  6414  6414 D HeadsetStateMachine: Unbinding service...
08-25 03:25:21.034  6414  6414 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 03:25:21.034  6414  6414 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 03:25:21.034  6414  6414 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 03:25:21.034  6414  6414 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 03:25:21.034  6414  6414 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-25 03:25:21.034  6414  6414 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-25 03:25:21.034  6414  6414 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-25 03:25:21.035  6414  6414 D PanService: Received stop request...Stopping profile...
08-25 03:25:21.036  6414  6414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c84150c
,08-25 03:25:21.039  6414  6414 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 03:25:21.040  6414  6414 D BtGatt.GattService: Received stop request...Stopping profile...
08-25 03:25:21.040  6414  6414 D BtGatt.GattService: stop()
08-25 03:25:21.040  6414  6414 D BtGatt.AdvertiseManager: advertise clients cleared
08-25 03:25:21.041  6414  6414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c84150c
08-25 03:25:21.042  6414  6414 D BluetoothMapService: Received stop request...Stopping profile...
08-25 03:25:21.042  6414  6414 D BluetoothMapService: stop()
08-25 03:25:21.044  6414  6414 D BluetoothMapEmailAppObserver: deinitObservers()
08-25 03:25:21.044  6414  6414 D BluetoothMapEmailAppObserver: removeReceiver()
08-25 03:25:21.045  6414  6414 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@3c84150c
08-25 03:25:21.046  6414  6414 I BluetoothA2dpServiceJni: cleanupNative
08-25 03:25:21.047  6414  6981 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-25 03:25:21.047  6414  6414 I GKI_LINUX: GKI_exit_task 2 done
08-25 03:25:21.047  6414  6414 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-25 03:25:21.048  6414  6414 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-25 03:25:21.048  6414  6414 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-25 03:25:21.048  6414  6414 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,08-25 03:25:21.051  6414  6414 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 03:25:21.051  6414  6414 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-25 03:25:21.052  6414  6414 V BluetoothMapService: Handler(): got msg=4
08-25 03:25:21.052  6414  6414 D BluetoothMapService: MAP Service closeService in
08-25 03:25:21.052  6414  6414 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 03:25:21.052  6414  6414 V BluetoothMapService: MAP Service closeService out
08-25 03:25:21.054  6414  6934 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-25 03:25:21.054  6414  6934 D BluetoothAdapterProperties: Setting state to 10
08-25 03:25:21.054  6414  6934 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-25 03:25:21.057  1069  1176 D BluetoothManagerService: Message: 60
08-25 03:25:21.057  1069  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-25 03:25:21.057  1069  1176 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-25 03:25:21.059  6414  6414 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-25 03:25:21.059  6414  6414 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-25 03:25:21.061  6414  6414 D BluetoothMapService: cleanup()
08-25 03:25:21.061  6414  6414 D BluetoothMapService: MAP Service closeService in
08-25 03:25:21.061  6414  6414 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-25 03:25:21.061  6414  6414 V BluetoothMapService: MAP Service closeService out
,08-25 03:25:21.065  6414  6934 I BluetoothAdapterState: Entering OffState
08-25 03:25:21.065  6274  6292 D BluetoothMap: onBluetoothStateChange: up=false
08-25 03:25:21.066  1836  1852 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 03:25:21.067  6274  6292 D BluetoothPbap: onBluetoothStateChange: up=false
08-25 03:25:21.067  1069  1176 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 03:25:21.068  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 03:25:21.068  6274  6292 D BluetoothA2dp: onBluetoothStateChange: up=false
08-25 03:25:21.069  6274  6292 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 03:25:21.069  1069  1176 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 03:25:21.070  1836  2459 D BluetoothHeadset: onBluetoothStateChange: up=false
08-25 03:25:21.070  6274  6292 D BluetoothPan: onBluetoothStateChange on: false
08-25 03:25:21.071  6274  6292 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-25 03:25:21.072  1069  1176 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-25 03:25:21.072  1069  1176 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-25 03:25:21.074  1069  1176 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-25 03:25:21.074  1069  1176 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-25 03:25:21.074  1069  1176 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@1579d04d mBinding = false
,08-25 03:25:21.077  1069  1176 D BluetoothManagerService: Sending unbind request.
08-25 03:25:21.083  6414  6938 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-25 03:25:21.083  6414  6414 I GKI_LINUX: GKI_exit_task 1 done
08-25 03:25:21.083  6414  6414 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-25 03:25:21.084  6414  6414 I BluetoothServiceJni: cleanupNative: return from cleanup
08-25 03:25:21.084  6414  6414 I art     : --- WEIRD: removing null entry 248
08-25 03:25:21.084  6414  6414 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-25 03:25:21.084  6414  6414 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-25 03:25:21.085  6414  6414 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-25 03:25:21.086  1069  1176 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-25 03:25:21.090  6414  6414 I art     : System.exit called, status: 0
08-25 03:25:21.090  6414  6414 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-25 03:25:21.116   310  2157 V AudioFlinger: 6414 died, releasing its sessions
08-25 03:25:21.116   310  2157 V AudioFlinger:  pid 1836 @ 0
08-25 03:25:21.116   310  2157 V AudioFlinger:  pid 3384 @ 1
08-25 03:25:21.117   310  2157 V AudioFlinger:  pid 3384 @ 2
,08-25 03:25:21.119  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: disconnected from LGBluetoothAPIAdapter
08-25 03:25:21.119  1925  2075 D LGBluetoothAPIService: Message: 101
08-25 03:25:21.119  1925  2075 E LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_DISCONNECTED
08-25 03:25:21.119  1925  2075 D LGBluetoothAPIService: Calling onBluetoothServiceDown callbacks
08-25 03:25:21.120  1925  2075 D LGBluetoothAPIService: Broadcasting onBluetoothServiceDown() to 0 receivers.
08-25 03:25:21.120  6274  6274 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-25 03:25:21.261  1069  1701 I ActivityManager: Process com.android.bluetooth (pid 6414) has died
,08-25 03:25:21.261  1069  1701 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer in 1000ms
,08-25 03:25:21.262  1069  1701 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 11000ms
08-25 03:25:21.271  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:21.273  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 03:25:21.273  1925  2075 D LGBluetoothAPIService: Message: 2
08-25 03:25:21.273  1925  2075 D LGBluetoothAPIService: unbindAndFinish(): null mBinding = false
,08-25 03:25:21.282  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:21.285  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:21.285  6274  6274 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-25 03:25:21.285  6274  6274 D LGBluetoothEventManager: [BTUI] clear device connection state
08-25 03:25:21.288  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:21.289  6274  6274 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 03:25:21.289  1586  1586 D BluetoothAdapter: 995547574: getState() :  mService = null. Returning STATE_OFF
08-25 03:25:21.289  1586  1586 D BluetoothAdapter: 995547574: getState() :  mService = null. Returning STATE_OFF
08-25 03:25:21.349  1069  1918 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=7127 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
08-25 03:25:21.352  6274  6274 D DockEventReceiver: finishStartingService: stopping service
,08-25 03:25:21.417  7127  7127 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-25 03:25:21.417  7127  7127 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 03:25:21.418  7127  7127 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-25 03:25:21.419  7127  7127 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-25 03:25:21.440  7127  7127 D BluetoothAdapterApp: Loading JNI Library
,08-25 03:25:21.478  7127  7127 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@172ecb74 Instance Count = 1
,08-25 03:25:21.485  7127  7127 D BluetoothAdapterApp: onCreate
,08-25 03:25:21.512  7127  7127 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-25 03:25:21.513  7127  7127 D ProfileConfigQcom: Adding HeadsetService
,08-25 03:25:21.513  7127  7127 D ProfileConfigQcom: [BTUI] A2dpService is supported
,08-25 03:25:21.514  7127  7127 D ProfileConfigQcom: Adding A2dpService
,08-25 03:25:21.514  7127  7127 D ProfileConfigQcom: [BTUI] HidService is supported
08-25 03:25:21.515  7127  7127 D ProfileConfigQcom: Adding HidService
,08-25 03:25:21.515  7127  7127 D ProfileConfigQcom: [BTUI] HealthService is supported
08-25 03:25:21.516  7127  7127 D ProfileConfigQcom: Adding HealthService
,08-25 03:25:21.517  7127  7127 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-25 03:25:21.518  7127  7127 D ProfileConfigQcom: [BTUI] PanService is supported
08-25 03:25:21.518  7127  7127 D ProfileConfigQcom: Adding PanService
,08-25 03:25:21.519  7127  7127 D ProfileConfigQcom: [BTUI] GattService is supported
08-25 03:25:21.519  7127  7127 D ProfileConfigQcom: Adding GattService
,08-25 03:25:21.521  7127  7127 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-25 03:25:21.521  7127  7127 D ProfileConfigQcom: Adding BluetoothMapService
,08-25 03:25:21.522  7127  7127 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
,08-25 03:25:21.524  7127  7127 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-25 03:25:21.527  7127  7127 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:21.528  7127  7127 V BluetoothPbapReceiver: ***********state = 10
,08-25 03:25:21.532  7127  7127 V LGMDMManagerInternal: Create singleton instance
,08-25 03:25:21.646  7127  7127 D LGBluetoothAPIServer: [BTUI] onCreate()
,08-25 03:25:21.646  7127  7127 D LGBluetoothAPIServer: [BTUI] onBind()
,08-25 03:25:21.654  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 03:25:21.658  1925  1925 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-25 03:25:21.659  1925  2075 D LGBluetoothAPIService: Message: 100
08-25 03:25:21.659  1925  2075 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-25 03:25:21.667  6274  6274 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-25 03:25:21.679  6274  6274 D BluetoothPermissionRequest: onReceive
08-25 03:25:21.682  6274  6274 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 03:25:21.682  6274  6274 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
,08-25 03:25:21.687  6274  6274 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 03:25:21.698  7127  7127 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-25 03:25:21.706  7127  7127 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:21.710  7127  7127 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 03:25:21.711  7127  7127 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 03:25:21.711  7127  7127 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 03:25:21.712  7127  7127 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:21.713  7127  7127 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-25 03:25:21.716  6363  6363 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-25 03:25:23.787  1069  2025 I art     : Explicit concurrent mark sweep GC freed 35249(1699KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.874ms total 139.460ms
,08-25 03:25:25.102  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
,08-25 03:25:25.103  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:25:25.114  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:25:25.115  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@105a9440 removed from the list
08-25 03:25:25.115  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:25:25.115  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:25:25.115  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:25:25.118  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:25:25.118  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1574b46c added. We now have 4 listener(s)
08-25 03:25:25.118  6126  6205 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 03:25:25.122  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:25:25.122  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@1574b46c removed from the list
08-25 03:25:25.122  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:25:25.122  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:25:25.122  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:25:25.123  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:25:25.123  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2931ea35 added. We now have 4 listener(s)
08-25 03:25:25.123  6126  6205 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-25 03:25:25.127  1069  1926 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 03:25:25.127  1069  1926 D BluetoothManagerService: disable(): mBluetooth = null mBinding = false
08-25 03:25:25.129  1069  1176 D BluetoothManagerService: Message: 2
08-25 03:25:30.135  6126  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:25:30.145  1069  1672 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:25:30.145  1069  1672 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-25 03:25:30.170  1069  1069 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 03:25:30.170  1069  1069 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 03:25:30.170  1069  1069 D Ulp_jni : JNI:system_update. Event-4
08-25 03:25:30.171  1069  1176 D BluetoothManagerService: Message: 1
08-25 03:25:30.171  1069  1176 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
08-25 03:25:30.200  1069  1176 D BluetoothManagerService: Message: 20
08-25 03:25:30.200  1069  1176 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@27886b7c:true
,08-25 03:25:30.204  7127  7127 D BluetoothAdapterState: make
08-25 03:25:30.208  7127  7127 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-25 03:25:30.209  7127  7127 I bluedroid-qcom: init
08-25 03:25:30.210  7127  7157 I BluetoothAdapterState: Entering OffState
08-25 03:25:30.210  7127  7127 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-25 03:25:30.211  7127  7127 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-25 03:25:30.211  7127  7127 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-25 03:25:30.211  7127  7127 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-25 03:25:30.211  7127  7127 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-25 03:25:30.213  7127  7127 I bluedroid-qcom: get_profile_interface socket
08-25 03:25:30.213  7127  7127 I bluedroid-qcom: get_profile_interface map_client
,08-25 03:25:30.218  7127  7161 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-25 03:25:30.209  7160  7160 W bdaddr_loader: type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:30.219  7160  7160 W bdaddr_loader: type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:30.230  1069  1069 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
,08-25 03:25:30.233  1069  1176 D BluetoothManagerService: Message: 40
08-25 03:25:30.233  1069  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-25 03:25:30.234  7127  7142 I bluedroid-qcom: config_hci_snoop_log
08-25 03:25:30.235  1069  1176 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-25 03:25:30.235  1069  1176 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-25 03:25:30.239  7160  7160 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-25 03:25:30.239  7160  7160 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-25 03:25:30.239  7160  7160 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-25 03:25:30.242  7160  7160 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-25 03:25:30.245  7127  7157 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-25 03:25:30.245  7127  7157 D BluetoothAdapterProperties: Setting state to 11
08-25 03:25:30.246  7127  7157 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-25 03:25:30.249  7160  7160 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-25 03:25:30.249  7160  7160 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-25 03:25:30.251  1069  1176 D BluetoothManagerService: Message: 60
08-25 03:25:30.251  1069  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-25 03:25:30.251  1069  1176 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-25 03:25:30.255  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:30.257  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 03:25:30.261  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:25:30.267  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:30.269  7127  7157 I LGBluetoothServiceJni: classInitNative: succeeds
08-25 03:25:30.270  6274  6274 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-25 03:25:30.273  7127  7161 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-25 03:25:30.284  7127  7127 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 03:25:30.284  7127  7127 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:30.284  7127  7127 V BluetoothPbapReceiver: ***********state = 11
08-25 03:25:30.287  1069  1069 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 03:25:30.288  1069  1069 D BluetoothManagerService: Stored Bluetooth name: G3
,08-25 03:25:30.290  7127  7161 D BluetoothAdapterProperties: Name is: G3
08-25 03:25:30.300  7127  7157 D BluetoothBondStateMachine: make
,08-25 03:25:30.307  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-25 03:25:30.310  7127  7157 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15eece55
08-25 03:25:30.310  7127  7157 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-25 03:25:30.310  7127  7157 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15eece55
08-25 03:25:30.311  7127  7157 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-25 03:25:30.311  7127  7174 I BluetoothBondStateMachine: StableState(): Entering Off State
08-25 03:25:30.313  7127  7157 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-25 03:25:30.316  7127  7157 E BluetoothAdapterService: File transfer profiles supported!!
08-25 03:25:30.321  6274  6274 D BluetoothPermissionRequest: onReceive
,08-25 03:25:30.325  7127  7157 E BluetoothAdapterService: File transfer profiles supported!!
08-25 03:25:30.326  7127  7127 D HeadsetService: Received start request. Starting profile...
08-25 03:25:30.327  7127  7127 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 03:25:30.327  7127  7127 D LGBluetoothHfpAdapter: Version 1.6
08-25 03:25:30.328  6274  6274 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 03:25:30.330  7127  7127 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-25 03:25:30.332  7127  7127 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-25 03:25:30.332  7127  7157 E BluetoothAdapterService: File transfer profiles supported!!
08-25 03:25:30.332  7127  7127 D HeadsetStateMachine: make
08-25 03:25:30.345  7127  7157 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 03:25:30.355  7127  7157 E BluetoothAdapterService: File transfer profiles supported!!
08-25 03:25:30.360  7127  7157 E BluetoothAdapterService: File transfer profiles supported!!
,08-25 03:25:30.365  7127  7157 E BluetoothAdapterService: File transfer profiles supported!!
08-25 03:25:30.372  7127  7127 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 03:25:30.372  7127  7127 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 03:25:30.376  7127  7127 D HeadsetStateMachine: max_hf_connections = 1
08-25 03:25:30.376  7127  7127 I bluedroid-qcom: get_profile_interface handsfree
08-25 03:25:30.379  7127  7127 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-25 03:25:30.379   310   310 V AudioPolicyService: registerClient() client 0xb57f0c80, uid 1002
08-25 03:25:30.379   310  2158 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-25 03:25:30.379   310  2158 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 03:25:30.379   310  2158 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 03:25:30.380  7127  7127 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-25 03:25:30.380   310  2157 V AudioFlinger: registerClient() client 0xb14331c0, pid 7127
08-25 03:25:30.380   310  1375 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 03:25:30.380   310  1375 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 03:25:30.381  1069  1559 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 03:25:30.381  1586  2159 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 03:25:30.381  1069  1559 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 03:25:30.381  1586  2159 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 03:25:30.381   310  1377 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 03:25:30.381   310  1377 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 03:25:30.381  3384  3400 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 03:25:30.381  3384  3400 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 03:25:30.381  7127  7142 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 03:25:30.381  1069  1960 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 03:25:30.381  1069  1960 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 03:25:30.381  7127  7142 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-25 03:25:30.381  1586  1607 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 03:25:30.381  1586  1607 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 03:25:30.381  7127  7142 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 03:25:30.381  7127  7142 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-25 03:25:30.381  3384  3399 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 03:25:30.381  3384  3399 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 03:25:30.381  7127  7127 V ToneGenerator: Create Track: 0xb4928a80
08-25 03:25:30.381  7127  7127 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-25 03:25:30.381  7127  7127 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-25 03:25:30.381  1836  2459 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-25 03:25:30.381  1836  2459 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-25 03:25:30.382   310  1381 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 03:25:30.382  1836  2459 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-25 03:25:30.382  1836  2459 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-25 03:25:30.382   310  1381 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-25 03:25:30.382   310  1381 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 03:25:30.382   310  1381 V AudioPolicyManagerEx: getOutput() returns output, 2
08-25 03:25:30.382   310   310 I AudioFlinger: isAudioPlaybackHookOn() false
08-25 03:25:30.382   310  2158 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-25 03:25:30.382   310  2158 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-25 03:25:30.382   310  2158 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-25 03:25:30.382   310  2158 V AudioPolicyManagerEx: getOutput() returns output 2
08-25 03:25:30.382  7127  7127 V AudioSystem: getLatency() output 2, latency 50
08-25 03:25:30.382  7127  7127 V AudioSystem: getFrameCount() output 2, frameCount 960
08-25 03:25:30.382  7127  7127 V AudioTrack: createTrack_l() output 2 afLatency 50
08-25 03:25:30.383   310  2157 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 03:25:30.383   310  2157 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 03:25:30.383   310  2157 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-25 03:25:30.383   310  2157 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-25 03:25:30.383   310  2157 V AudioFlinger: createTrack() lSessionId: 21
08-25 03:25:30.384  7127  7127 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-25 03:25:30.384   310  2157 V AudioFlinger: acquiring 21 from 7127, for 7127
,08-25 03:25:30.384   310  2157 V AudioFlinger:  added new entry for 21
08-25 03:25:30.384  7127  7157 V LGMDMManager: Create singleton instance
08-25 03:25:30.384  7127  7127 V ToneGenerator: ToneGenerator INIT OK, time: 372393
08-25 03:25:30.384  7127  7127 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15eece55
08-25 03:25:30.385  7127  7178 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-25 03:25:30.385  7127  7178 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-25 03:25:30.385  7127  7178 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-25 03:25:30.385  7127  7178 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-25 03:25:30.386  7127  7127 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15eece55
08-25 03:25:30.386   310  1382 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7127
08-25 03:25:30.387   310  1382 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-25 03:25:30.387   310  1382 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-25 03:25:30.387   310  1382 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-25 03:25:30.387   310  1382 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-25 03:25:30.387   310  1382 V voice   : voice_set_parameters: exit with code(0)
08-25 03:25:30.387   310  1382 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-25 03:25:30.387   310  1382 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-25 03:25:30.387   310  1382 V msm8974_platform: platform_set_parameters: exit with code(0)
08-25 03:25:30.387   310  1382 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-25 03:25:30.387   310  1382 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-25 03:25:30.387   310  1382 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-25 03:25:30.387  7127  7178 V ToneGenerator: ToneGenerator destructor
08-25 03:25:30.387  7127  7178 V ToneGenerator: stopTone
08-25 03:25:30.387  7127  7178 V ToneGenerator: Delete Track: 0xb4928a80
08-25 03:25:30.388  7127  7178 V AudioTrack: ~AudioTrack, releasing session id from 7127 on behalf of 7127
08-25 03:25:30.388  7127  7127 D A2dpService: Received start request. Starting profile...
08-25 03:25:30.388   310  2158 V AudioFlinger: releasing 21 from 7127 for 7127
08-25 03:25:30.388   310   310 V AudioPolicyService: AudioCommandThread() adding release output 2
08-25 03:25:30.388   310  2158 V AudioFlinger:  decremented refcount to 0
08-25 03:25:30.388   310   310 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-25 03:25:30.388   310  2158 V AudioFlinger: purging stale effects
08-25 03:25:30.388   310   310 V AudioFlinger: PlaybackThread::Track destructor
08-25 03:25:30.388   310  1271 V AudioPolicyService: AudioCommandThread() waking up
08-25 03:25:30.388   310   310 V AudioFlinger: removeClient_l() pid 7127, calling pid 310
08-25 03:25:30.388   310  1271 V AudioPolicyService: AudioCommandThread() processing release output 2
08-25 03:25:30.388   310  1271 V AudioPolicyManager: releaseOutput() 2
08-25 03:25:30.388   310  1271 V AudioPolicyService: AudioCommandThread() going to sleep
08-25 03:25:30.389  7127  7127 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-25 03:25:30.389  7127  7157 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-25 03:25:30.390  7127  7127 V Avrcp   : make
08-25 03:25:30.391  7127  7127 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-25 03:25:30.391  7127  7127 I bluedroid-qcom: get_profile_interface avrcp
08-25 03:25:30.391  1069  2014 W Process : Unable to open /proc/7181/status
08-25 03:25:30.400  7127  7127 V AudioManager: registerRemoteController: size o,f Media player list: 0
,08-25 03:25:30.401  7127  7127 E AudioManager: No RCC entry present to update
08-25 03:25:30.401  7127  7127 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-25 03:25:30.404  7127  7127 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-25 03:25:30.406  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-25 03:25:30.406  7127  7127 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-25 03:25:30.409  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-25 03:25:30.538  1069  1996 V SIM_STK : Menu title from STK is T-Mobile
08-25 03:25:30.538  1069  1996 V SIM_STK : Menu title from STK is T-Mobile
,08-25 03:25:30.610  1069  2014 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-25 03:25:30.619  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-25 03:25:30.623  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-25 03:25:30.623  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 03:25:30.624  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 03:25:30.624  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 03:25:30.624  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 03:25:30.624  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 03:25:30.624  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 03:25:30.624  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
,08-25 03:25:30.624  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 03:25:30.624  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 03:25:30.624  7127  7127 I BluetoothA2dpServiceJni: classInitNative
08-25 03:25:30.625  7127  7127 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-25 03:25:30.625  7127  7127 D A2dpStateMachine: make
08-25 03:25:30.630  7127  7127 I bluedroid-qcom: get_profile_interface a2dp
08-25 03:25:30.631  7127  7186 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-25 03:25:30.633  7127  7127 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-25 03:25:30.633  7127  7127 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-25 03:25:30.634  7127  7127 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15eece55
08-25 03:25:30.634  7127  7185 D A2dpStateMachine: Enter Disconnected: -2
08-25 03:25:30.635  7127  7127 I BluetoothHidServiceJni: classInitNative: succeeds
08-25 03:25:30.636  7127  7127 D HidService: Received start request. Starting profile...
08-25 03:25:30.637  7127  7127 I bluedroid-qcom: get_profile_interface hidhost
08-25 03:25:30.637  7127  7127 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15eece55
08-25 03:25:30.637  7127  7127 I BluetoothHealthServiceJni: classInitNative: succeeds
08-25 03:25:30.638  7127  7127 D HealthService: Received start request. Starting profile...
,08-25 03:25:30.647  7127  7127 I bluedroid-qcom: get_profile_interface health
,08-25 03:25:30.647  7127  7127 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-25 03:25:30.647  7127  7127 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15eece55
08-25 03:25:30.647  7127  7127 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-25 03:25:30.649  7127  7127 D PanService: Received start request. Starting profile...
,08-25 03:25:30.649  7127  7127 D BluetoothPanServiceJni: initializeNative(L110): pan
08-25 03:25:30.649  7127  7127 I bluedroid-qcom: get_profile_interface pan
,08-25 03:25:30.657  7127  7127 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-25 03:25:30.658  7127  7127 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15eece55
08-25 03:25:30.658  7127  7127 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-25 03:25:30.661  7127  7127 D BtGatt.DebugUtils: handleDebugAction() action=null
08-25 03:25:30.662  7127  7127 D BtGatt.GattService: Received start request. Starting profile...
,08-25 03:25:30.662  7127  7127 D BtGatt.GattService: start()
08-25 03:25:30.663  7127  7127 I bluedroid-qcom: get_profile_interface gatt
08-25 03:25:30.664  7127  7127 D BtGatt.AdvertiseManager: advertise manager created
08-25 03:25:30.673  7127  7127 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15eece55
,08-25 03:25:30.677  7127  7127 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15eece55
08-25 03:25:30.678  7127  7127 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-25 03:25:30.681  7127  7127 V BluetoothMapService: BluetoothMapBinder()
08-25 03:25:30.682  7127  7127 D BluetoothMapService: Received start request. Starting profile...
08-25 03:25:30.682  7127  7127 D BluetoothMapService: start()
08-25 03:25:30.690  7127  7127 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-25 03:25:30.690  7127  7127 D BluetoothMapEmailAppObserver: createReceiver()
08-25 03:25:30.692  7127  7127 D BluetoothMapEmailAppObserver: initObservers()
08-25 03:25:30.692  7127  7127 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
,08-25 03:25:30.701  7127  7127 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15eece55
08-25 03:25:30.701  7127  7127 D HeadsetStateMachine: Proxy object connected
08-25 03:25:30.702  7127  7127 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-25 03:25:30.703  7127  7127 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-25 03:25:30.708  7127  7127 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-25 03:25:30.709  7127  7178 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-25 03:25:30.711  7127  7178 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-25 03:25:30.712  7127  7127 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 03:25:30.712  7127  7178 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-25 03:25:30.716  7127  7127 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 03:25:30.718  7127  7127 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:30.727  7127  7127 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-25 03:25:30.733  7127  7127 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-25 03:25:30.734  7127  7127 V PanService: [BTUI] SIM Extra State :ABSENT
08-25 03:25:30.738  7127  7127 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-25 03:25:30.738  7127  7127 V BluetoothMapService: Handler(): got msg=1
08-25 03:25:30.739  7127  7127 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 03:25:30.740  7127  7127 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 03:25:30.740  7127  7127 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 03:25:30.740  7127  7127 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:30.740  7127  7157 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-25 03:25:30.740  7127  7127 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-25 03:25:30.740  7127  7157 I bluedroid-qcom: enable
08-25 03:25:30.742  7127  7157 I bt_hci_bdroid: init
08-25 03:25:30.747  7127  7157 I bt_vendor: bt-vendor : init
08-25 03:25:30.747  7127  7157 I bt_vendor: bt-vendor : get_bt_soc_type
08-25 03:25:30.747  7127  7157 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-25 03:25:30.747  7127  7157 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-25 03:25:30.747  7127  7157 D bt_userial_mct: userial_init
08-25 03:25:30.748  7127  7157 D bt_hci_bdroid: set_power 1
08-25 03:25:30.748  7127  7157 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-25 03:25:30.748  7127  7157 I bt_vendor: Starting hciattach daemon
08-25 03:25:30.749  7127  7157 I bt_vendor: try to set true
08-25 03:25:30.750  7127  7196 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-25 03:25:30.750  7127  7196 I bt-btu  : btu_task pending for preload complete event
,08-25 03:25:30.748  7199  7199 W sh      : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:30.748  7199  7199 W sh      : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:30.788  7200  7200 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-25 03:25:30.903  7211  7211 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-25 03:25:30.932  7212  7212 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 03:25:30.969  7214  7214 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 03:25:30.984  7215  7215 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-25 03:25:31.011  7216  7216 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-25 03:25:31.025  7217  7217 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-25 03:25:31.049  7219  7219 I libmdmdetect: ESOC framework not supported
08-25 03:25:31.050  7219  7219 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-25 03:25:31.062  7219  7219 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-25 03:25:31.062  7219  7219 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-25 03:25:31.062  7219  7219 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
,08-25 03:25:31.062  7219  7219 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-25 03:25:31.062  7219  7219 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-25 03:25:31.063  7219  7219 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-25 03:25:31.063  7219  7219 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-25 03:25:31.102  7219  7220 E QC-QMI  : qmi_client [7219] 15: failed to locate client data
,08-25 03:25:31.103   470   470 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-25 03:25:31.103   470   470 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
08-25 03:25:31.168  7227  7227 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-25 03:25:31.197  7231  7231 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-25 03:25:31.253  7127  7157 I bt_vendor: bluetooth satus is on
,08-25 03:25:31.254  7127  7157 D bt_hci_bdroid: preload
,08-25 03:25:31.260  7127  7198 D bt_userial_mct: userial_open(port:0)
,08-25 03:25:31.260  7127  7198 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
08-25 03:25:31.267  7127  7198 I bt_vendor: Done intiailizing UART
08-25 03:25:31.273  7127  7198 I bt_vendor: Done intiailizing UART
08-25 03:25:31.273  7127  7198 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-25 03:25:31.274  7127  7198 I bt_vendor: Bluetooth Firmware and transport layer are initialized
,08-25 03:25:31.280  7127  7196 I bt-btu  : btu_task received preload complete event
,08-25 03:25:31.283  7127  7196 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-25 03:25:31.283  7127  7196 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
,08-25 03:25:31.290  7127  7233 D bt_userial_mct: Entering userial_read_thread()
,08-25 03:25:31.297  7127  7196 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
,08-25 03:25:31.305  7127  7196 I         : BTE_InitTraceLevels -- TRC_HCI
08-25 03:25:31.305  7127  7196 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-25 03:25:31.305  7127  7196 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-25 03:25:31.305  7127  7196 I         : BTE_InitTraceLevels -- TRC_AVDT
08-25 03:25:31.305  7127  7196 I         : BTE_InitTraceLevels -- TRC_AVRC
08-25 03:25:31.305  7127  7196 I         : BTE_InitTraceLevels -- TRC_A2D
08-25 03:25:31.305  7127  7196 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-25 03:25:31.305  7127  7196 I         : BTE_InitTraceLevels -- TRC_BTM,
08-25 03:25:31.305  7127  7196 I         : BTE_InitTraceLevels -- TRC_HID_HOST
,08-25 03:25:31.305  7127  7196 I         : BTE_InitTraceLevels -- TRC_GAP
,08-25 03:25:31.305  7127  7196 I         : BTE_InitTraceLevels -- TRC_PAN,
08-25 03:25:31.305  7127  7196 I         : BTE_InitTraceLevels -- TRC_SDP
08-25 03:25:31.305  7127  7196 I         : BTE_InitTraceLevels -- TRC_GATT
08-25 03:25:31.305  7127  7196 I         : BTE_InitTraceLevels -- TRC_SMP
08-25 03:25:31.305  7127  7196 I         : BTE_InitTraceLevels -- TRC_BTAPP,
08-25 03:25:31.305  7127  7196 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-25 03:25:31.400  7127  7196 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled,
,08-25 03:25:31.400  7127  7196 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa015d061 ,
08-25 03:25:31.400  7127  7196 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa015d061 ,
,08-25 03:25:31.462  7127  7161 E bt-btif : Calling BTA_HhEnable
08-25 03:25:31.462  7127  7161 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-25 03:25:31.462  7127  7161 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-25 03:25:31.467  7127  7196 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-25 03:25:31.468  7127  7196 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-25 03:25:31.468  7127  7196 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-25 03:25:31.468  7127  7196 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-25 03:25:31.468  7127  7196 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-25 03:25:31.471  7127  7161 D BluetoothAdapterProperties: Name is: G3
08-25 03:25:31.475  1069  1069 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-25 03:25:31.479  7127  7161 D BluetoothAdapterProperties: Scan Mode:20
08-25 03:25:31.479  7127  7161 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 03:25:31.480  7127  7161 D bt_hci_bdroid: postload
,08-25 03:25:31.484  7127  7198 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 03:25:31.485  7127  7196 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-25 03:25:31.486  7127  7161 D bte_conf: Device ID record 1 : primary
08-25 03:25:31.486  7127  7161 D bte_conf:   vendorId            = 00c4
08-25 03:25:31.487  7127  7161 D bte_conf:   vendorIdSource      = 0001
08-25 03:25:31.487  7127  7161 D bte_conf:   product             = 13a1
08-25 03:25:31.487  7127  7161 D bte_conf:   version             = 1000
08-25 03:25:31.487  7127  7161 D bte_conf:   clientExecutableURL = 
08-25 03:25:31.487  7127  7161 D bte_conf:   serviceDescription  = 
08-25 03:25:31.487  7127  7161 D bte_conf:   documentationURL    = 
08-25 03:25:31.487  7127  7161 D bte_conf: bte_load_did_conf no section named DID2.
08-25 03:25:31.489  7127  7196 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 03:25:31.489  7127  7196 W bt-smp  : Plain text(LSB ~ MSB) = ef 7f 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 03:25:31.489  7127  7196 W bt-smp  : Encrypted text(LSB ~ MSB) = cb bd 15 bb 69 c9 73 ea b7 c7 6f b1 3d 43 33 21 
08-25 03:25:31.491  7127  7198 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 03:25:31.491  7127  7196 W bt-btm  : Stopping oneshot timer
08-25 03:25:31.492  7127  7198 D bt_hci_bdroid: Used up Tx Cmd credits
,08-25 03:25:31.495  7127  7198 D bt_hci_bdroid: Used up Tx Cmd credits
08-25 03:25:31.498  7127  7157 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-25 03:25:31.498  7127  7157 D BluetoothAdapterProperties: ScanMode =  20
08-25 03:25:31.498  7127  7157 D BluetoothAdapterProperties: State =  11
08-25 03:25:31.498  7127  7157 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-25 03:25:31.499  7127  7157 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-25 03:25:31.499  7127  7157 D BluetoothAdapterProperties: Setting state to 12
08-25 03:25:31.499  7127  7157 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-25 03:25:31.499  7127  7161 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-25 03:25:31.499  7127  7161 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-25 03:25:31.498  7235  7235 W sh      : type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:31.498  7235  7235 W sh      : type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 03:25:31.506  1069  1176 D BluetoothManagerService: Message: 60
08-25 03:25:31.506  1069  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-25 03:25:31.506  1069  1176 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-25 03:25:31.507  7127  7233 E bt_mct  : hci lib postload completed
08-25 03:25:31.523  7127  7157 I BluetoothAdapterState: Entering On State
,08-25 03:25:31.531  7127  7157 D LGBluetoothServiceAdapter: [BTUI] OnState
08-25 03:25:31.531  7127  7157 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-25 03:25:31.531  7127  7157 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-25 03:25:31.534  7127  7157 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-25 03:25:31.543  7127  7196 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 03:25:31.543  7127  7196 W bt-smp  : Plain text(LSB ~ MSB) = 08 c3 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 03:25:31.543  7127  7196 W bt-smp  : Encrypted text(LSB ~ MSB) = 3e 95 46 bd 2c 8c 9e 81 57 c4 a3 05 a7 1f a5 82 
,08-25 03:25:31.545  7127  7196 W bt-btm  : Stopping oneshot timer
08-25 03:25:31.550  7127  7161 D BluetoothAdapterProperties: Discoverable Timeout:120
08-25 03:25:31.550  7127  7161 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-25 03:25:31.551  1069  1069 D BluetoothManagerService: Stored Bluetooth name: G3
08-25 03:25:31.552  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:31.552  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:31.552  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:31.552  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:25:31.552  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:25:31.552  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:25:31.552  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:25:31.552  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:25:31.558  6126  6126 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:25:31.561  7127  7196 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 03:25:31.561  7127  7196 W bt-smp  : Plain text(LSB ~ MSB) = a6 59 5f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 03:25:31.561  7127  7196 W bt-smp  : Encrypted text(LSB ~ MSB) = 58 be 9d ee a8 54 33 f4 0e 7f 72 45 b4 c5 d1 13 
08-25 03:25:31.562  7127  7196 W bt-btm  : Stopping oneshot timer
08-25 03:25:31.569  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:31.569  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:31.569  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:31.569  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:25:31.569  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:25:31.569  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:25:31.569  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:25:31.569  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:25:31.573  7127  7157 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-25 03:25:31.576  7127  7196 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 03:25:31.576  7127  7196 W bt-smp  : Plain text(LSB ~ MSB) = d2 f5 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 03:25:31.576  7127  7196 W bt-smp  : Encrypted text(LSB ~ MSB) = 7e a6 0c 74 57 08 76 a0 0b 5d 4a d2 40 2f fb a1 
08-25 03:25:31.577  7127  7196 W bt-btm  : Stopping oneshot timer
08-25 03:25:31.581  6126  6126 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:25:31.583  6274  6292 D BluetoothMap: onBluetoothStateChange: up=true
08-25 03:25:31.591  7127  7196 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-25 03:25:31.591  7127  7196 W bt-smp  : Plain text(LSB ~ MSB) = bf cb 6c 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-25 03:25:31.591  7127  7196 W bt-smp  : Encrypted text(LSB ~ MSB) = db 1b b4 11 06 43 39 81 c8 50 ca c2 92 c9 1d 1b 
,08-25 03:25:31.594  7127  7196 W bt-btm  : Stopping oneshot timer
08-25 03:25:31.595  1836  1852 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 03:25:31.606  1836  1836 D BluetoothHeadset: Proxy object connected
,08-25 03:25:31.610  6274  7035 D BluetoothPbap: onBluetoothStateChange: up=true
08-25 03:25:31.613  1069  1176 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 03:25:31.637  1836  2459 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 03:25:31.637  6274  6274 D BluetoothMap: Proxy object connected
08-25 03:25:31.637  6274  6274 D MapProfile: Bluetooth service connected
08-25 03:25:31.637  6274  6274 D BluetoothMap: getConnectedDevices()
08-25 03:25:31.639  7245  7245 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-25 03:25:31.644  7127  7143 V BluetoothMapService: getConnectedDevices()
08-25 03:25:31.645  1836  1836 D BluetoothHeadset: Proxy object connected
08-25 03:25:31.646  1069  1069 D BluetoothA2dp: Proxy object connected
08-25 03:25:31.647  6274  6292 D BluetoothA2dp: onBluetoothStateChange: up=true
08-25 03:25:31.651  6274  6293 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-25 03:25:31.653  1069  1176 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 03:25:31.654  6274  6274 D BluetoothA2dp: Proxy object connected
08-25 03:25:31.654  6274  6274 D A2dpProfile: Bluetooth service connected
08-25 03:25:31.654  1069  1069 D BluetoothHeadset: Proxy object connected
08-25 03:25:31.655  1836  1851 D BluetoothHeadset: onBluetoothStateChange: up=true
08-25 03:25:31.655  6274  6274 D BluetoothHeadset: Proxy object connected
08-25 03:25:31.655  6274  6274 D HeadsetProfile: Bluetooth service connected
08-25 03:25:31.658  1836  1836 D BluetoothHeadset: Proxy object connected
08-25 03:25:31.658  6274  7035 D BluetoothPan: onBluetoothStateChange on: true
08-25 03:25:31.658  6274  7035 D BluetoothPan: onBluetoothStateChange call bindService
08-25 03:25:31.660  6274  6292 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-25 03:25:31.661  6274  6274 D BluetoothPan: BluetoothPAN Proxy object connected
08-25 03:25:31.661  6274  6274 D PanProfile: Bluetooth service connected
08-25 03:25:31.663  1069  1176 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-25 03:25:31.663  1069  1176 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
,08-25 03:25:31.666  1069  1069 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-25 03:25:31.666  1069  1176 D BluetoothManagerService: Message: 40
08-25 03:25:31.666  1069  1176 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-25 03:25:31.667  6274  6274 D BluetoothInputDevice: Proxy object connected
08-25 03:25:31.667  6274  6274 D HidProfile: Bluetooth service connected
,08-25 03:25:31.668  1925  1925 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:31.668  1925  2075 D LGBluetoothAPIService: Message: 1
08-25 03:25:31.668  1925  2075 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-25 03:25:31.668  1925  2075 D LGBluetoothAPIService: Calling onBluetoothServiceUp callbacks
08-25 03:25:31.668  1925  2075 D LGBluetoothAPIService: Broadcasting onBluetoothServiceUp() to 0 receivers.
08-25 03:25:31.669  1586  1586 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-25 03:25:31.674  7127  7127 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:31.675  7127  7127 D BluetoothMapService: STATE_ON
08-25 03:25:31.677  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:25:31.679  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:31.683  6274  6274 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-25 03:25:31.685  6274  6274 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-25 03:25:31.692  7127  7127 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15eece55
,08-25 03:25:31.692  7127  7127 V BluetoothPbapService: Pbap Service onCreate
08-25 03:25:31.692  7127  7127 V BluetoothPbapService: Starting PBAP service
,08-25 03:25:31.695  7127  7127 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-25 03:25:31.695  7127  7127 V BluetoothMapService: Handler(): got msg=1
08-25 03:25:31.696  7127  7127 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-25 03:25:31.696  6274  6274 D DockEventReceiver: finishStartingService: stopping service
08-25 03:25:31.697  7127  7127 V BluetoothPbapService: Pbap Service onBind
08-25 03:25:31.697  7127  7259 D BluetoothMapMasInstance: MAS initSocket()
08-25 03:25:31.698  7127  7259 D BluetoothMapMasInstance:   masId = 00
08-25 03:25:31.698  7127  7259 D BluetoothMapMasInstance:   msgTypes = 0e
08-25 03:25:31.698  7127  7259 D BluetoothMapMasInstance:   masName = SMS/MMS
08-25 03:25:31.698  7127  7259 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-25 03:25:31.698  7127  7127 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:31.698  7127  7127 V BluetoothPbapService: state: 12
08-25 03:25:31.699  7127  7127 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-25 03:25:31.699  7127  7127 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:31.699  7127  7127 V BluetoothPbapReceiver: ***********state = 12
08-25 03:25:31.700  1069  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:25:31.701  6274  6274 D BluetoothPbap: Proxy object connected
08-25 03:25:31.701  6274  6274 D PbapServerProfile: Bluetooth service connected
08-25 03:25:31.701  7127  7127 V BluetoothPbapService: Handler(): got msg=1
08-25 03:25:31.702  7127  7127 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-25 03:25:31.702  7127  7259 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 03:25:31.703  7127  7260 V BluetoothPbapService: Pbap Service initSocket
08-25 03:25:31.705  2169  2169 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-25 03:25:31.706  2169  2169 D c       : Getting all permits...
08-25 03:25:31.706  2169  2169 D a       : Opening database...
08-25 03:25:31.710  2169  2169 D a       : Opening database auth.proximity.permit_store...
08-25 03:25:31.710  1069  1977 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:25:31.712  7127  7259 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-25 03:25:31.712  7127  7259 V BluetoothMapMasInstance: Succeed to create listening socket 
08-25 03:25:31.712  7127  7259 D BluetoothMapMasInstance: Accepting socket connection...
08-25 03:25:31.713  2169  2169 D a       : Closing database...
08-25 03:25:31.714  7127  7161 D BluetoothAdapterProperties: Scan Mode:21
08-25 03:25:31.714  7127  7161 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-25 03:25:31.716  7127  7260 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 03:25:31.718  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:31.718  7127  7260 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-25 03:25:31.718  7127  7260 V BluetoothPbapService: Succeed to create listening socket 
08-25 03:25:31.718  7127  7260 V BluetoothPbapService: Accepting socket connection...
08-25 03:25:31.720  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:25:31.727  6274  6274 D BluetoothPermissionRequest: onReceive
08-25 03:25:31.728  6274  6274 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-25 03:25:31.730  6274  6274 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-25 03:25:31.734  7127  7127 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
,08-25 03:25:31.735  7127  7127 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-25 03:25:31.741  7127  7127 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
08-25 03:25:31.759  7127  7127 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-25 03:25:31.760  7127  7127 V BtOppService: onCreate
,08-25 03:25:31.764  7127  7127 V BluetoothOppNotification: send message
08-25 03:25:31.768  7127  7127 V BtOppService: Starting RfcommListener
08-25 03:25:31.774  7127  7127 D BluetoothOppPreference: Dumping Names:  
08-25 03:25:31.774  7127  7127 D BluetoothOppPreference: {}
08-25 03:25:31.774  7127  7127 D BluetoothOppPreference: Dumping Channels:  
08-25 03:25:31.774  7127  7127 D BluetoothOppPreference: {}
,08-25 03:25:31.776  7127  7127 V BtOppService: onStartCommand
08-25 03:25:31.780  7127  7127 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:31.780  7127  7127 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-25 03:25:31.782  7127  7269 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 03:25:31.784  7127  7127 V BluetoothOppNotification: new notify threadi!
08-25 03:25:31.784  7127  7266 V BtOppService: Deleted complete outbound shares, number =  0
08-25 03:25:31.785  7127  7127 V BluetoothOppNotification: send delay message
08-25 03:25:31.785  7127  7127 V BtOppService: start RfcommListener
08-25 03:25:31.786  7127  7269 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 03:25:31.786  7127  7270 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 03:25:31.787  7127  7266 V BtOppService: Deleted complete inbound failed shares, number = 0
08-25 03:25:31.788  7127  7127 V BtOppService: RfcommListener started
08-25 03:25:31.789  7127  7266 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
,08-25 03:25:31.792  7127  7271 V BtOppRfcommListener: Starting RFCOMM listener....
08-25 03:25:31.792  1069  1864 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:25:31.793  7127  7269 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b82ed21 on behalf of 
08-25 03:25:31.793  7127  7271 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 03:25:31.794  7127  7271 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-25 03:25:31.795  7127  7271 V BtOppRfcommListener: Started RFCOMM listener....
08-25 03:25:31.795  7127  7271 I BtOppRfcommListener: Accept thread started.
08-25 03:25:31.795  7127  7271 V BtOppRfcommListener: Accepting connection...
08-25 03:25:31.795  7127  7266 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@33853546 on behalf of 
08-25 03:25:31.799  7127  7270 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@173307 on behalf of 
08-25 03:25:31.801  7127  7270 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-25 03:25:31.803  7127  7269 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 03:25:31.806  7127  7127 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15eece55
08-25 03:25:31.807  7127  7127 V BluetoothFtpService: Ftp Service onCreate
08-25 03:25:31.807  7127  7127 I BluetoothFtpService: Ftp Service onCreate
08-25 03:25:31.807  7127  7127 V BluetoothFtpService: Ftp Service onStartCommand
08-25 03:25:31.807  7127  7127 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:31.808  7127  7270 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 03:25:31.808  7127  7127 V BluetoothFtpService: Starting Listening on sockets
08-25 03:25:31.808  7127  7127 V BtOppService: ContentObserver received notification
08-25 03:25:31.809  7127  7270 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a803a5d on behalf of 
08-25 03:25:31.809  7127  7127 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-25 03:25:31.809  7127  7127 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-25 03:25:31.809  7127  7127 V BluetoothSapReceiver: SapReceiver onReceive 
08-25 03:25:31.810  7127  7127 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:31.810  7127  7127 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-25 03:25:31.810  7127  7270 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 03:25:31.810  7127  7127 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-25 03:25:31.810  7127  7272 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 03:25:31.811  7127  7272 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 03:25:31.812  7127  7272 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2b4f5fd2 on behalf of 
08-25 03:25:31.812  7127  7127 V BtOppService: ContentObserver received notification
08-25 03:25:31.813  7127  7127 V BluetoothFtpService: Handler(): got msg=1
08-25 03:25:31.813  7127  7272 V BluetoothOppNotification: update too frequent, put in queue
08-25 03:25:31.813  7127  7270 V BluetoothOppNotification: outbound notification was removed.
08-25 03:25:31.813  7127  7270 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 03:25:31.813  7127  7127 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-25 03:25:31.814  7127  7127 V BluetoothFtpService: Ftp Service initSocket
08-25 03:25:31.815  7127  7270 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e69f8a3 on behalf of 
,08-25 03:25:31.817  7127  7272 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-25 03:25:31.817  7127  7272 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-25 03:25:31.818  7127  7270 V BluetoothOppNotification: inbound: succ-0  fail-0
08-25 03:25:31.819  7127  7272 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1df2b7a0 on behalf of 
08-25 03:25:31.820  7127  7272 V BluetoothOppNotification: update too frequent, put in queue
08-25 03:25:31.821  7127  7270 V BluetoothOppNotification: inbound notification was removed.
08-25 03:25:31.821  7127  7272 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-25 03:25:31.821  1069  1097 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:25:31.821  7127  7270 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 03:25:31.822  7127  7127 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 03:25:31.823  7127  7270 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1a0b1f59 on behalf of 
08-25 03:25:31.823  7127  7127 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=79
08-25 03:25:31.823  7127  7127 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-25 03:25:31.825  7127  7273 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
08-25 03:25:31.839  7127  7127 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@15eece55
08-25 03:25:31.839  7127  7127 V BluetoothSapService: Sap Service onCreate
,08-25 03:25:31.841  7127  7127 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-25 03:25:31.841  7127  7127 V BluetoothSapService: state: 12
08-25 03:25:31.841  7127  7127 V BluetoothSapService: Starting SAP server process
08-25 03:25:31.842  7127  7127 V BluetoothSapService: SAP Service startRfcommListenerThread
08-25 03:25:31.838  7274  7274 W sapd    : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:31.838  7274  7274 W sapd    : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:31.844  7127  7275 V BluetoothSapService: Sap Service initRfcommSocket
08-25 03:25:31.844  1069  1918 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:25:31.845  7127  7275 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 03:25:31.846  7127  7275 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-25 03:25:31.846  7127  7275 V BluetoothSapService: Succeed to create listening socket 
08-25 03:25:31.846  7127  7275 V BluetoothSapService: Accepting socket connection...
08-25 03:25:31.856  7274  7274 V BT_SAP  : Event pipe created
08-25 03:25:31.856  7274  7274 V BT_SAP  : create_server_socket qcom.sap.server
08-25 03:25:31.856  7274  7274 V BT_SAP  : created socket fd 6
,08-25 03:25:32.787  7127  7127 V BluetoothOppNotification: new notify threadi!
,08-25 03:25:32.788  7127  7127 V BluetoothOppNotification: send delay message
,08-25 03:25:32.800  7127  7285 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-25 03:25:32.804  7127  7285 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@fc55815 on behalf of 
08-25 03:25:32.809  7127  7285 V BluetoothOppNotification: mUpdateCompleteNotification = true
,08-25 03:25:32.814  7127  7285 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-25 03:25:32.815  7127  7285 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@d1b172a on behalf of 
08-25 03:25:32.816  7127  7285 V BluetoothOppNotification: outbound: succ-0  fail-0
08-25 03:25:32.817  7127  7285 V BluetoothOppNotification: outbound notification was removed.
08-25 03:25:32.817  7127  7285 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-25 03:25:32.819  7127  7285 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a13d91b on behalf of 
08-25 03:25:32.819  7127  7285 V BluetoothOppNotification: inbound: succ-0  fail-0
08-25 03:25:32.822  7127  7285 V BluetoothOppNotification: inbound notification was removed.
08-25 03:25:32.822  7127  7285 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-25 03:25:32.824  7127  7285 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@3c7bdab8 on behalf of 
,08-25 03:25:35.199  6126  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:35.199  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:35.199  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:35.199  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-25 03:25:35.199  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:25:35.199  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:25:35.199  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:25:35.199  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-25 03:25:35.206  6126  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-25 03:25:35.207  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:25:35.207  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2931ea35 removed from the list
08-25 03:25:35.207  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:25:35.207  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:25:35.207  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:25:35.208  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:25:35.208  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@199b0eca added. We now have 4 listener(s)
08-25 03:25:35.208  6126  6205 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 03:25:35.211  1069  1096 D WifiServiceImplEx: setWifiEnabled: false pid=6126, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 03:25:35.211  1069  1096 D WifiService: setWifiEnabled: false pid=6126, uid=10118
08-25 03:25:35.211  1069  1096 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-25 03:25:40.219  6126  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:25:40.234  1069  1996 D WifiServiceImplEx: setWifiEnabled: true pid=6126, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-25 03:25:40.235  1069  1996 D WifiService: setWifiEnabled: true pid=6126, uid=10118
08-25 03:25:40.235  1069  1996 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-25 03:25:40.253  1069  1069 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-25 03:25:40.254  1069  1069 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-25 03:25:40.254  1069  1069 D Ulp_jni : JNI:system_update. Event-4
08-25 03:25:40.255  1069  1376 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-25 03:25:40.255  1069  1376 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-25 03:25:40.258  1069  1376 E WifiUtil: wfc_util_ffile_check_copy(): pid[1069] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-25 03:25:40.258  1069  1376 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 03:25:40.258  1069  1376 E WifiUtil: wfc_util_ffile_check_copy(): pid[1069] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-25 03:25:40.258  1069  1376 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-25 03:25:40.258  1069  1376 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-25 03:25:40.258  1069  1376 E WifiHW  : unknown target_country: EU , set to default
08-25 03:25:40.258  1069  1376 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-25 03:25:40.258  1069  1376 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-25 03:25:40.258  1069  1376 I WifiUtil: gEnableBmps=1
08-25 03:25:40.839   306   911 D SoftapController: Softap fwReload - Ok
,08-25 03:25:40.847  1069  1376 E NetdConnector: NDC Command {67 softap fwreload wlan0 STA} took too long (584ms)
08-25 03:25:40.851   306   911 D CommandListener: Setting iface cfg
08-25 03:25:40.851   306   911 D CommandListener: Trying to bring down wlan0
08-25 03:25:40.852  1069  1176 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-25 03:25:40.852  1069  1176 D Tethering: InitialState.processMessage what=4
08-25 03:25:40.853  1069  1176 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-25 03:25:40.875   306   911 D CommandListener: Clearing all IP addresses on wlan0
08-25 03:25:40.878  1069  1376 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-25 03:25:40.888  7296  7296 W wpa_supplicant: type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-25 03:25:40.898  7296  7296 W wpa_supplicant: type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:40.911  1069  1376 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 03:25:40.911  1069  1376 E WifiStateMachine: useWiFiOffloading() : false
08-25 03:25:40.911  1069  1376 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-25 03:25:40.932  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 03:25:40.941  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-25 03:25:40.955  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:25:40.959  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:40.959  1069  1069 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-25 03:25:40.963  7296  7296 I wpa_supplicant: Successfully initialized wpa_supplicant
08-25 03:25:40.977  1069  1376 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-25 03:25:40.978  1069  1376 D WifiMonitor: connecting to supplicant
08-25 03:25:40.979  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 03:25:40.979  6274  6274 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 03:25:40.979  6274  6274 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 03:25:40.979  6274  6274 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
,08-25 03:25:40.987  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 03:25:40.988  6274  6274 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 03:25:40.989  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 03:25:40.989  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 03:25:40.989  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 03:25:40.989  6274  6274 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 03:25:40.990  6274  6274 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 03:25:40.994  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 03:25:40.994  6274  6274 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 03:25:40.994  6274  6274 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 03:25:40.994  6274  6274 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 03:25:40.995  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 03:25:41.002  6274  6274 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 03:25:41.002  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-25 03:25:41.002  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 03:25:41.002  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 03:25:41.002  6274  6274 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 03:25:41.002  6274  6274 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-25 03:25:41.010  6294  6294 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 03:25:41.014  7296  7296 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-25 03:25:41.014  7296  7296 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-25 03:25:41.018  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-25 03:25:41.026  6383  7315 W FormManager: Network not available. Please check & try again.
08-25 03:25:41.026  6383  7316 V FormManager: Network unavailable.
08-25 03:25:41.027  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:41.035  6383  7316 V FormManager: Network unavailable.
,08-25 03:25:41.144  7296  7296 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-25 03:25:41.162  7296  7296 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-25 03:25:41.169  7296  7296 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-25 03:25:41.169  7296  7296 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-25 03:25:41.170  1069  1376 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-25 03:25:41.171  1069  1376 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-25 03:25:41.171  1069  1376 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-25 03:25:41.172  1069  1376 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-25 03:25:41.172  1069  7318 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-25 03:25:41.172  1069  7318 D WifiMonitor: Dropping event because (p2p0) is stopped
08-25 03:25:41.172  1069  7318 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-25 03:25:41.172  1069  1376 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-25 03:25:41.172  1069  7318 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-25 03:25:41.173  1069  7318 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-25 03:25:41.173  1069  7318 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-25 03:25:41.173  1069  1376 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 03:25:41.173  1069  1376 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-25 03:25:41.173  1069  1376 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-25 03:25:41.174  1069  1376 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-25 03:25:41.174  1069  1376 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
,08-25 03:25:41.175  1069  1376 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-25 03:25:41.176  1069  1376 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-25 03:25:41.176  1069  1376 E WifiStateMachine: useWiFiOffloading() : false
08-25 03:25:41.176  1069  1376 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-25 03:25:41.177  1069  1376 D WifiNative-wlan0: doBoolean: SET update_config 1
08-25 03:25:41.179  1069  1376 D WifiNative-wlan0: SET update_config 1: returned true
08-25 03:25:41.179  1069  1376 D WifiConfigStore: Loading config and enabling all networks 
08-25 03:25:41.179  1069  1376 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-25 03:25:41.179  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:41.179  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:41.179  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:41.179  1069  1376 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-25 03:25:41.180  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:41.180  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-25 03:25:41.180  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:41.182  1925  1925 D WfdService: Waiting for WifiP2p enabling
08-25 03:25:41.187  1069  1069 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
,08-25 03:25:41.187  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:41.187  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:41.187  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:41.187  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:25:41.187  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:25:41.187  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:25:41.187  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:25:41.187  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:25:41.188  1069  1425 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-25 03:25:41.192  1069  1376 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
,08-25 03:25:41.195  6126  6126 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:25:41.199  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:41.199  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:41.199  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:41.199  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:25:41.199  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:25:41.199  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-25 03:25:41.199  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-25 03:25:41.199  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-25 03:25:41.201  1069  1376 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
,08-25 03:25:41.201  1069  1376 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-25 03:25:41.202  6126  6126 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-25 03:25:41.203  1069  1376 D WifiStateMachine: enableVerboseLogging : level 2
08-25 03:25:41.203  1069  1376 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
,08-25 03:25:41.204  1069  1376 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-25 03:25:41.204  1069  1376 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-25 03:25:41.205  1069  1376 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-25 03:25:41.205  1069  1376 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-25 03:25:41.206  1069  1376 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-25 03:25:41.206  1069  1376 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-25 03:25:41.206  1069  1376 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-25 03:25:41.206  1069  1376 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-25 03:25:41.206  1069  1376 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-25 03:25:41.206  1069  1376 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-25 03:25:41.207  1069  1376 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-25 03:25:41.207  1069  1376 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-25 03:25:41.207  1069  1376 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-25 03:25:41.208  1069  1376 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 03:25:41.208  1069  1376 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-25 03:25:41.209  1069  1376 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-25 03:25:41.209  1069  1376 D WifiNative-HAL: Setting external_sim to 1
08-25 03:25:41.209  1069  1376 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-25 03:25:41.209  1069  1376 D WifiNative-wlan0: SET external_sim 1: returned true
08-25 03:25:41.209  1069  1376 I WifiNative-HAL: startHal
08-25 03:25:41.209  1069  1376 D wifi    : setting scan oui 0xaf68d120
08-25 03:25:41.210  1069  1376 D WifiStateMachine: Setting OUI to DA-A1-19
08-25 03:25:41.210  1069  1376 I WifiNative-HAL: startHal
08-25 03:25:41.210  1069  1376 D wifi    : setting scan oui 0xaf68d120
08-25 03:25:41.210  1069  1376 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-25 03:25:41.211  1069  1376 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-25 03:25:41.211  1925  1925 D WfdsService: Supplicant Connection state is changed : true
08-25 03:25:41.211  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-25 03:25:41.211  1925  2274 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-25 03:25:41.211  1925  2274 D WfdsService: Set the WFDS Monitor: true
,08-25 03:25:41.211  1925  2274 D WfdsMonitor: WfdsMonitorThread create
08-25 03:25:41.211  7296  7296 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-25 03:25:41.212  1925  2274 D WfdsMonitor: WFDS Monitor is created and started
08-25 03:25:41.212  1925  2274 D WfdsService: WiFi: Supplicant connection re-established
08-25 03:25:41.212  1069  1376 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
,08-25 03:25:41.212  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 03:25:41.212  7296  7296 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-25 03:25:41.213  1925  7319 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-25 03:25:41.213  1069  1376 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
,08-25 03:25:41.213  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-25 03:25:41.213  1925  7319 E CtrlSupplicant: Succeed to open control connection
08-25 03:25:41.213  7296  7296 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-25 03:25:41.214  1925  7319 E CtrlSupplicant: Succeed to open monitor connection
08-25 03:25:41.214  1925  7319 D WfdsMonitor: Supplicant connection established
08-25 03:25:41.214  1069  1376 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-25 03:25:41.214  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 03:25:41.214  7296  7296 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-25 03:25:41.214  1925  2274 D WfdsService: Connected to the supplicant for wfds
08-25 03:25:41.214  1069  1376 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 03:25:41.214  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-25 03:25:41.214  7296  7296 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
,08-25 03:25:41.215  1069  1376 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-25 03:25:41.215  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-25 03:25:41.215  7296  7296 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-25 03:25:41.215  1069  1376 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-25 03:25:41.215  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-25 03:25:41.215  7296  7296 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
,08-25 03:25:41.216  1069  1376 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-25 03:25:41.216  1069  1376 E WifiNative: : [383,213,883 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-25 03:25:41.216  1069  1376 D WifiNative-wlan0: doBoolean: RECONNECT
08-25 03:25:41.217  1069  1376 D WifiNative-wlan0: RECONNECT: returned true
08-25 03:25:41.217  1069  1376 D WifiNative-wlan0: doString: [STATUS]
08-25 03:25:41.217  1069  7318 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-25 03:25:41.217  1069  7318 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-25 03:25:41.217  1069  1376 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-25 03:25:41.218  1069  1376 D WifiNative-wlan0: doBoolean: SET ps 1
08-25 03:25:41.218  1069  1376 D WifiNative-wlan0: SET ps 1: returned true
08-25 03:25:41.218  1069  1374 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:41.220   306   911 D CommandListener: Setting iface cfg
08-25 03:25:41.220   306   911 D CommandListener: Trying to bring up p2p0
08-25 03:25:41.220  1069  1374 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-25 03:25:41.220  1069  1374 D LGWifiP2pService: P2pEnablingState
,08-25 03:25:41.221  1069  1374 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:41.221  1069  1374 D LGWifiP2pService: P2p socket connection successful
08-25 03:25:41.221  1069  1374 D LGWifiP2pService: P2pEnabledState
08-25 03:25:41.221  1069  1374 D LGWifiP2pService: sending p2p connection changed broadcast
08-25 03:25:41.221  6294  6294 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-25 03:25:41.222  1925  1925 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-25 03:25:41.222  1925  1925 D WfdsService: WifiP2pState is changed : true
,08-25 03:25:41.223  1069  1374 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-25 03:25:41.223  1925  2274 D WfdsService: Receive the WFDS_ENABLE Method
,08-25 03:25:41.223  1925  2274 D WfdsService: Set the WFDS Monitor: true
08-25 03:25:41.223  1925  2274 D WfdsService: Connected to the supplicant for wfds
08-25 03:25:41.223  1069  1374 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-25 03:25:41.223  1925  2274 D WfdsJNI : doCommand: WFDS_SET TRUE
08-25 03:25:41.223  7296  7296 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-25 03:25:41.223  1069  1374 D WifiNative-p2p0: doBoolean: SET device_name G3
08-25 03:25:41.223  1925  2274 D WfdsService: selectPreferredScanChannel [36]
08-25 03:25:41.223  1925  2274 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-25 03:25:41.223  1925  1925 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-25 03:25:41.224  1069  1374 D WifiNative-p2p0: SET device_name G3: returned true
08-25 03:25:41.224  1069  1374 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-25 03:25:41.224  1069  1374 D LGWifiP2pService: before postfix = G3
08-25 03:25:41.224  1069  1374 D WifiServerServiceExt: postfix byte check : 2
08-25 03:25:41.224  1069  1374 D LGWifiP2pService: after postfix = G3
08-25 03:25:41.224  1069  1374 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-25 03:25:41.224  1925  1925 D WfdsService: isConnected: false
08-25 03:25:41.225  1069  1374 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-25 03:25:41.225  1069  1374 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-25 03:25:41.225  1069  1374 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-25 03:25:41.225  1069  1374 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-25 03:25:41.226  1069  1374 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-25 03:25:41.226  1069  1374 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-25 03:25:41.226  1069  1374 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-25 03:25:41.226  1069  1374 D WifiNative-HAL: p2pGetDeviceAddress
08-25 03:25:41.227  1069  1374 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-25 03:25:41.227  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-25 03:25:41.228  1069  1376 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-25 03:25:41.228  1069  1376 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-25 03:25:41.229  1069  1069 D WifiScanningService: SCAN_AVAILABLE : 3
08-25 03:25:41.229  1069  1069 D RttService: SCAN_AVAILABLE : 3
08-25 03:25:41.229  1069  1541 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:41.229  1069  1374 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-25 03:25:41.229  1069  1374 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-25 03:25:41.229  1069  1376 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-25 03:25:41.229  1069  1540 D WifiScanningService: DefaultState got{ when=-1ms what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:41.229  1069  1540 I WifiNative-HAL: startHal
08-25 03:25:41.230  1069  1374 D WifiNative-p2p0: P2P_FLUSH: returned true
08-25 03:25:41.230  1069  1374 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-25 03:25:41.230  1069  1540 D wifi    : getting scan capabilities on interface[1] = 0xaf68d120
08-25 03:25:41.230  1069  1540 D wifi    : failed to get capabilities : -3
08-25 03:25:41.230  1069  1540 E WifiScanningService: could not get scan capabilities
08-25 03:25:41.230  1069  1376 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-25 03:25:41.230  1069  1374 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-25 03:25:41.230  1069  1374 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-25 03:25:41.231  1069  1376 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-25 03:25:41.232  1069  1376 E WifiStateMachine:  ConnectModeState what:132106 1 0,
08-25 03:25:41.233  1925  1925 I WfdStateTracker: handleP2pThisDeviceChanged
08-25 03:25:41.233  1925  1925 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-25 03:25:41.233  1069  1374 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-25 03:25:41.233  1069  1374 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-25 03:25:41.233  1925  1925 D WfdsService: Update P2p Interface State: 3
08-25 03:25:41.233  1069  1376 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-25 03:25:41.233  1069  1376 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-25 03:25:41.237  6383  7322 V FormManager: Network unavailable.
08-25 03:25:41.241  6383  7322 V FormManager: Network unavailable.
08-25 03:25:41.241  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 03:25:41.244  7296  7296 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-25 03:25:41.244  1069  1374 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-25 03:25:41.244  1069  1374 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-25 03:25:41.245  6383  7321 W FormManager: Network not available. Please check & try again.
08-25 03:25:41.245  1069  1374 D LGWifiP2pService: InactiveState
08-25 03:25:41.245  1069  1376 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-25 03:25:41.245  1069  1374 D LGWifiP2pService: InactiveState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:41.245  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-15ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:41.245  1069  1374 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-25 03:25:41.245  1069  1376 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-25 03:25:41.246  1069  1376 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-25 03:25:41.246  1069  1376 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-25 03:25:41.246  7296  7296 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 03:25:41.247  7296  7296 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 03:25:41.247  7296  7296 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 03:25:41.247  7296  7296 E wpa_supplicant: disconnect_rssi_lvl: -100
08-25 03:25:41.248  7296  7296 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:41.248  1069  1374 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-25 03:25:41.248  1069  1376 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 03:25:41.248  1069  1374 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:41.248  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:41.248  1069  1374 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:41.248  7296  7296 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:41.248  1069  1376 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 03:25:41.248  1069  1374 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:41.248  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:41.248  1069  1374 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:41.248  1069  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:41.248  1069  1376 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-25 03:25:41.248  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:41.249  1069  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:41.249  1069  1374 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:41.249  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:41.249  1069  1374 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:41.249  1925  7319 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ],
08-25 03:25:41.249  1925  7319 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 03:25:41.249  1925  2274 W WfdsService: DefaultState - msg [9441285] is not handled
08-25 03:25:41.249  1925  7319 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 03:25:41.249  1069  7318 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 03:25:41.249  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-25 03:25:41.249  1069  7318 E WifiMonitor: WifiMonitor:p2p0 cnt=39 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 03:25:41.249  1069  7318 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 03:25:41.249  1069  7318 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 03:25:41.249  7296  7296 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-25 03:25:41.250  7296  7296 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 03:25:41.250  1069  7318 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 03:25:41.250  1069  7318 E WifiMonitor: WifiMonitor:p2p0 cnt=40 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:41.250  1069  7318 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:41.250  1069  7318 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:41.250  1069  7318 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 03:25:41.250  1069  7318 E WifiMonitor: WifiMonitor:p2p0 cnt=41 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:41.250  7296  7296 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-25 03:25:41.250  7296  7296 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:41.251  1069  1069 E WifiServerServiceExt: No p2p device connected
08-25 03:25:41.250  1069  7318 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:41.251  1925  7319 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 03:25:41.251  1069  7318 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:41.251  1069  7318 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-25 03:25:41.251  1069  7318 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 03:25:41.251  1069  7318 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 03:25:41.251  1069  7318 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-25 03:25:41.251  1069  7318 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 03:25:41.251  1069  7318 E WifiMonitor: WifiMonitor:p2p0 cnt=43 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:41.251  7296  7296 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:41.251  1069  7318 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:41.251  1069  7318 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:41.251  1069  7318 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-25 03:25:41.251  1069  7318 E WifiMonitor: WifiMonitor:p2p0 cnt=44 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:41.251  1069  7318 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:41.251  1069  7318 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-25 03:25:41.252  1925  7319 D WfdsMonitor: Event [CTRL-EVENT-REGD,OM-CHANGE init=DRIVER type=WORLD]
08-25 03:25:41.252  1069  1376 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-25 03:25:41.252  1069  1374 D LGWifiP2pService: InactiveState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:41.252  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:41.252  1069  1376 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-25 03:25:41.253  1069  1376 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-25 03:25:41.253  1069  1376 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-25 03:25:41.253  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-25 03:25:41.253  7296  7296 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-25 03:25:41.253  7296  7296 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 03:25:41.253  1069  7318 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-25 03:25:41.253  1069  7318 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 03:25:41.253  1069  7318 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 03:25:41.253  1069  7318 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-25 03:25:41.254  1069  1376 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-25 03:25:41.254  1069  1376 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
08-25 03:25:41.254  1069  1376 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-25 03:25:41.254  1069  1376 D WifiNative-wlan0: doBoolean: SCAN
08-25 03:25:41.255  1069  1376 D WifiNative-wlan0: SCAN: returned false
08-25 03:25:41.256  1069  1376 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=383253  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 03:25:41.257  1069  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 38 0 rt=383254  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-25 03:25:41.257  1069  1376 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 03:25:41.257  1069  1376 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 03:25:41.258  1069  1376 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 03:25:41.259  1069  1376 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 03:25:41.259  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:41.259  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:41.259  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-25 03:25:41.259  1069  1376 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-25 03:25:41.260  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:41.260  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 03:25:41.260  4207  4207 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 03:25:41.261  4207  4207 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 03:25:41.261  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:41.262  4207  4207 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 03:25:41.262  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 03:25:41.262  1069  1069 D WifiServerServiceExt: setSupplicantStateSCANNING
08-25 03:25:41.263  4207  4207 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 03:25:41.266  4207  7323 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-25 03:25:41.270  4207  7324 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-25 03:25:41.270  4207  7324 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 03:25:41.311  1069  1977 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7325 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-25 03:25:41.330   344   344 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 361us total 17.530ms
,08-25 03:25:41.347   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 304us total 15.716ms
,08-25 03:25:41.362   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 550us total 15.028ms
,08-25 03:25:41.398  7325  7325 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-25 03:25:41.398  7325  7325 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-25 03:25:41.407  7325  7325 V [BNRBootReceiver]: Boot Receiver Return
08-25 03:25:41.408  7325  7325 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-25 03:25:41.413  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 03:25:41.427  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 03:25:41.432  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 03:25:41.442  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 03:25:41.443  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 03:25:41.446  6343  6343 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-25 03:25:41.447  1069  1960 I ActivityManager: Killing 6654:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-25 03:25:41.504  1069  1864 W libprocessgroup: failed to open /acct/uid_10011/pid_6654/cgroup.procs: No such file or directory
,08-25 03:25:41.829  7296  7296 E wpa_supplicant: USIM:  scard_init function
08-25 03:25:41.830  7296  7296 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-25 03:25:41.839  1069  7318 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-25 03:25:41.839  1069  7318 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-25 03:25:41.840  1069  7318 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-25 03:25:41.840  1069  7318 E WifiMonitor: WifiMonitor:wlan0 cnt=47 dispatchEvent: WPS-AP-AVAILABLE 
08-25 03:25:41.840  1069  7318 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-25 03:25:41.842  1069  1376 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-25 03:25:41.843  1069  1376 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-25 03:25:41.843  1069  1376 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-25 03:25:41.843  1069  1376 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=11 bcn=0
08-25 03:25:41.843  1069  1376 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-25 03:25:41.849  1069  7318 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-25 03:25:41.849  1069  7318 E WifiMonitor: WifiMonitor:wlan0 cnt=48 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
,08-25 03:25:41.867  1069  1376 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=383864  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-25 03:25:41.874  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:41.875  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 03:25:41.878  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:41.881  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:41.881  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:41.881  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
,08-25 03:25:41.890  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:41.890  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:41.891  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 03:25:41.891  1069  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 48 0 rt=383889  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-25 03:25:41.892  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 03:25:41.892  1069  1069 D WifiServerServiceExt: setSupplicantStateASSOCIATING
08-25 03:25:41.895  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-25 03:25:41.899  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:41.899  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-25 03:25:41.905  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 03:25:41.917  6274  6274 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-25 03:25:41.923  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 03:25:41.936  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 03:25:41.944  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:41.951  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 03:25:41.952  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 03:25:41.957  6343  6343 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-25 03:25:41.962  7296  7296 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-25 03:25:41.967  1069  7318 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-25 03:25:41.967  1069  7318 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-25 03:25:41.967  1069  7318 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-25 03:25:41.967  1069  7318 E WifiMonitor: WifiMonitor:wlan0 cnt=50 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-25 03:25:41.967  1069  7318 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 03:25:41.967  1069  7318 E WifiMonitor: WifiMonitor:wlan0 cnt=51 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-25 03:25:41.975  1069  7318 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 03:25:41.975  1069  7318 E WifiMonitor: WifiMonitor:wlan0 cnt=52 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-25 03:25:41.976  7296  7296 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 03:25:41.978  7296  7296 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 03:25:41.985  1069  7318 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-25 03:25:41.985  1069  7318 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,08-25 03:25:41.987  1069  1376 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=383985  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 03:25:41.989  1069  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 49 0 rt=383986  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-25 03:25:41.990  1069  7318 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-25 03:25:41.990  1069  7318 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-25 03:25:41.990  1069  7318 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 03:25:41.990  1069  7318 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-25 03:25:41.991  1069  1376 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=383989
08-25 03:25:41.992  1069  1376 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=383989
08-25 03:25:41.992  1069  1376 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=383990
08-25 03:25:41.993  1069  1376 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=383990
08-25 03:25:41.993  1069  1376 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 50 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=383991
08-25 03:25:41.994  1069  1376 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=383991  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 03:25:41.995  1069  7318 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 03:25:41.995  1069  7318 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 03:25:41.997  1069  1176 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-25 03:25:41.998  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 03:25:41.999  1069  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 51 0 rt=383996  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-25 03:25:41.999  1069  1376 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=383997  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 03:25:42.000  1069  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 52 0 rt=383998  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-25 03:25:42.001  1069  1376 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=383999
08-25 03:25:42.001  1069  1376 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=383999
08-25 03:25:42.002  1069  1376 D WifiNative-wlan0: doString: [STATUS]
08-25 03:25:42.004  1069  1376 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
,08-25 03:25:42.005  1069  7318 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-25 03:25:42.005  1069  7318 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-25 03:25:42.007  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:42.007  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 03:25:42.008  1069  1376 I WifiServiceExtension: setVHTCapabilityType  : false
08-25 03:25:42.008  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:42.011  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:42.011  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:42.011  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-25 03:25:42.017  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:42.017  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:42.017  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-25 03:25:42.018  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 03:25:42.018  1069  1069 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-25 03:25:42.022  1069  1376 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
08-25 03:25:42.022  1069  1376 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
,08-25 03:25:42.031  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:42.031  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:42.032  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 03:25:42.032  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:42.032  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:42.032  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-25 03:25:42.032  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:42.032  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 03:25:42.038  1069  1376 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,08-25 03:25:42.038  1069  1445 D ConnectivityService: Got NetworkAgent Messenger
08-25 03:25:42.038  1069  1445 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-25 03:25:42.038  1069  1445 D ConnectivityService: NetworkAgent connected
08-25 03:25:42.038  1069  1376 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 03:25:42.038  1069  1376 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 03:25:42.039  1069  1376 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 03:25:42.039  1069  1376 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 03:25:42.041  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:42.042  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 03:25:42.044  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:42.044  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 03:25:42.045  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:42.045  1069  1376 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-25 03:25:42.045  1069  1376 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-25 03:25:42.045  1069  1376 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-25 03:25:42.046  1069  1376 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-25 03:25:42.046  1069  1376 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-25 03:25:42.047  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:42.047  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 03:25:42.048  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:42.051  1069  1376 D WifiNative-wlan0: SAVE_CONFIG: returned true
,08-25 03:25:42.053   306   911 D CommandListener: Setting iface cfg
08-25 03:25:42.057  1069  1376 E WifiStateMachine: Start Dhcp Watchdog 2
08-25 03:25:42.057  1069  7370 D DhcpStateMachine: StoppedState
08-25 03:25:42.057  1069  7370 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:42.057  1069  7370 D DhcpStateMachine: WaitBeforeStartState
08-25 03:25:42.057  1069  1376 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=384055  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 03:25:42.058  1069  1376 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=384055  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 03:25:42.058  1069  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=384056  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 03:25:42.059  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 03:25:42.059  1069  1069 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-25 03:25:42.060  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:42.060  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 03:25:42.060  1069  1069 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-25 03:25:42.061  1069  1376 E WifiStateMachine:  ObtainingIpState CMD_TETHER_STATE_CHANGE 0 0
08-25 03:25:42.061  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_TETHER_STATE_CHANGE 0 0
08-25 03:25:42.062  1069  1376 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-25 03:25:42.062  1069  1376 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
,08-25 03:25:42.062  1069  1376 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-25 03:25:42.063  1069  1376 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-25 03:25:42.063  1069  1376 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=384061  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 03:25:42.064  1069  1376 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=384061  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 03:25:42.064  1069  1376 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=384062  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-25 03:25:42.065  1069  1376 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:29254] from screen [on:0 period:-1085440463] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 03:25:42.066  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1085440462] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 03:25:42.066  1069  1376 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-25 03:25:42.068  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 03:25:42.068  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 03:25:42.068  6343  6343 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 03:25:42.072  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-25 03:25:42.072  6274  6274 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-25 03:25:42.072  6274  6274 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-25 03:25:42.072  6274  6274 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-25 03:25:42.073  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-25 03:25:42.074  1069  1445 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-25 03:25:42.074  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:42.074  1069  1376 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:42.075  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:42.075  1069  1376 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
,08-25 03:25:42.076  1069  1376 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:42.076  1069  1376 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:42.076  1069  1376 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:42.076  6274  6274 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-25 03:25:42.076  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-25 03:25:42.076  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-25 03:25:42.076  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-25 03:25:42.076  6274  6274 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-25 03:25:42.077  6274  6274 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-25 03:25:42.077  1069  1445 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 03:25:42.077  6274  6274 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-25 03:25:42.077  1069  1376 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=15,0,0
08-25 03:25:42.077  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=15,0,0
08-25 03:25:42.077  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-25 03:25:42.078  7296  7296 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-25 03:25:42.078  1069  1376 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-25 03:25:42.078  1069  1376 D WifiNative-wlan0: doBoolean: SET ps 0
08-25 03:25:42.078  1069  1376 D WifiNative-wlan0: SET ps 0: returned true
08-25 03:25:42.078  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-25 03:25:42.079  7296  7296 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-25 03:25:42.079  1069  1376 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-25 03:25:42.079  1069  1376 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-25 03:25:42.079  1069  1376 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 03:25:42.079  1069  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@38bc13cd target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:42.079  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@38bc13cd target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:42.079  1069  1376 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 03:25:42.079  1069  7370 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:42.079  1069  7370 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-25 03:25:42.080   306   911 D CommandListener: Setting iface cfg
08-25 03:25:42.081   306   911 D CommandListener: Trying to bring up wlan0
08-25 03:25:42.082  1069  1376 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.108/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-25 03:25:42.083  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 03:25:42.084  1069  1376 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:42.084  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
,08-25 03:25:42.085  1069  1376 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:42.085  1069  1376 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:42.086  1069  1376 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:42.086  1069  1376 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-25 03:25:42.086  1069  1069 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-25 03:25:42.086  1069  1069 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-25 03:25:42.086  1069  1445 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 03:25:42.087  1069  1376 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 03:25:42.087  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-25 03:25:42.087  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-25 03:25:42.087  1069  1374 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:42.087  1069  1374 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:42.087  7296  7296 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-25 03:25:42.087  1069  1376 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-25 03:25:42.087  1069  1376 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-25 03:25:42.088  7296  7296 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-25 03:25:42.088  1069  1376 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-25 03:25:42.088  1069  1376 D WifiNative-wlan0: doBoolean: SET ps 1
,08-25 03:25:42.093  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 03:25:42.098  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:42.103  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 03:25:42.104  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 03:25:42.104  6343  6343 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 03:25:42.104  1069  1376 D WifiNative-wlan0: SET ps 1: returned true
08-25 03:25:42.105  1069  1445 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-25 03:25:42.105  1069  1376 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 03:25:42.106  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-25 03:25:42.106  1069  1376 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-25 03:25:42.106  1069  1445 D ConnectivityService: ignoring duplicate network state non-change
08-25 03:25:42.109  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 03:25:42.112  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:42.112  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 03:25:42.113  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-25 03:25:42.115  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:42.115  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:42.115  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 03:25:42.118  1069  1445 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-25 03:25:42.119  1069  1445 D ConnectivityService: Adding iface wlan0 to network 101
08-25 03:25:42.122  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:42.122  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:42.122  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-25 03:25:42.124  1069  1376 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-25 03:25:42.124  1069  1069 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-25 03:25:42.126  1925  1925 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-25 03:25:42.128  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:42.128  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:42.128  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 03:25:42.129  1069  1069 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
,08-25 03:25:42.135  1069  1069 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:42.135  1069  1069 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:42.135  1069  1069 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-25 03:25:42.137  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:42.137  1586  1586 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-25 03:25:42.138  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:42.139  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 03:25:42.139  1069  1445 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-25 03:25:42.139  1069  1445 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-25 03:25:42.140  1069  1445 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-25 03:25:42.141  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:42.141  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 03:25:42.141  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:42.141   306   911 E Netd    : netlink response contains error (File exists)
,08-25 03:25:42.143  1069  1445 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-25 03:25:42.143  1586  1586 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-25 03:25:42.144  1586  1586 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-25 03:25:42.144  1069  1445 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-25 03:25:42.144  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:42.144  1069  1445 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-25 03:25:42.144  1069  1445 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-25 03:25:42.145  1069  1445 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 03:25:42.145  1069  1445 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-25 03:25:42.145  1069  1445 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
08-25 03:25:42.145  1069  1445 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-25 03:25:42.145  1069  1445 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 03:25:42.145  1069  1445 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 03:25:42.145  1069  1445 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 03:25:42.145  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:42.145  1069  1445 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:42.145  1069  1445 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-25 03:25:42.145  1069  1445 D ConnectivityService: currentScore = 0, newScore = 20
08-25 03:25:42.145  1069  1445 D ConnectivityService:    accepting network in place of null
08-25 03:25:42.145  1069  1445 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:42.146  1069  7369 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:42.146  1069  7369 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-25 03:25:42.146  1069  7369 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:42.146  1069  7369 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-25 03:25:42.146  1836  1836 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:42.147  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 03:25:42.147  1069  1376 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:42.148  1069  1376 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=104857,6Kbps]
08-25 03:25:42.148  1069  1445 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-25 03:25:42.148  1069  1445 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-25 03:25:42.149  1069  1445 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-25 03:25:42.149  1069  1445 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-25 03:25:42.149  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 03:25:42.149  1069  1445 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-25 03:25:42.149  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 03:25:42.149  1069  1445 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.108/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-25 03:25:42.149  6343  6343 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 03:25:42.150  1069  1445 D ConnectivityService: validation of new default Network = false
08-25 03:25:42.150  1069  1445 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-25 03:25:42.150  1069  1445 D DSQN    : enableDataServiceNotify 
08-25 03:25:42.150  1069  1445 D DSQN    : start dsqn bin
08-25 03:25:42.151   306  7375 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
,08-25 03:25:42.156  1069  1069 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-25 03:25:42.156  1069  1069 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-25 03:25:42.156  1069  1069 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-25 03:25:42.156  1069  1069 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-25 03:25:42.148  7376  7376 W dsqn    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:42.158  1069  1445 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-25 03:25:42.158  1069  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:42.159  1069  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 03:25:42.159  1069  1445 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 03:25:42.159  1586  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 03:25:42.148  7376  7376 W dsqn    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:42.164  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 03:25:42.174  7376  7376 E DSQN    : DSQN ssw
08-25 03:25:42.181  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 03:25:42.186  1069  1373 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-25 03:25:42.189  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:42.196  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 03:25:42.196  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 03:25:42.197  6343  6343 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-25 03:25:42.201  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 03:25:42.206  1801  7380 I CheckinService: active receiver: enabled
08-25 03:25:42.213   306  7375 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
,08-25 03:25:42.217  1801  7380 I CheckinService: Preparing to send checkin request
08-25 03:25:42.217  1801  7380 I EventLogService: Accumulating logs since 1472086790805
08-25 03:25:42.220  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 03:25:42.225  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 03:25:42.226  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:42.226  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:42.227  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:42.232  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 03:25:42.233  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 03:25:42.233  6343  6343 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 03:25:42.236  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 03:25:42.242  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-25 03:25:42.246  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:42.251  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 03:25:42.251   306  7375 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-25 03:25:42.251  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-25 03:25:42.253  6343  6343 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 03:25:42.257  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 03:25:42.264  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 03:25:42.267   306   910 D LGDataListener: argv[0]=dsqncommand
08-25 03:25:42.267   306   910 D LGDataListener: argv[1]=wlan0
08-25 03:25:42.267   306   910 D LGDataListener: argv[2]=1
08-25 03:25:42.267   306   910 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-25 03:25:42.267  1069  1174 D DSQN    : DSQM DsqnNotification wlan0  1
08-25 03:25:42.267  1069  1174 D DSQN    : start to monitor internet connection
08-25 03:25:42.270  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:42.276  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-25 03:25:42.277  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 03:25:42.278  6343  6343 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-25 03:25:42.278  7383  7383 W dhcpcd  : type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:42.278  7383  7383 W dhcpcd  : type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6850 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-25 03:25:42.281  1069  7370 D DhcpStateMachine: DHCPV4 request on wlan0
08-25 03:25:42.282  1069  7369 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 01:25:42 GMT], X-Android-Received-Millis=[1472088342281], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472088342266]}
08-25 03:25:42.282  1069  7369 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-25 03:25:42.282  1069  7369 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-25 03:25:42.282  1069  1445 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-25 03:25:42.282  1069  1445 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-25 03:25:42.282  1069  1445 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 03:25:42.282  1069  7370 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-25 03:25:42.282  1069  7370 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-25 03:25:42.282  1069  1445 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 03:25:42.282  1069  1445 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 03:25:42.282  1069  1445 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-25 03:25:42.283  1069  1445 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-25 03:25:42.283  1069  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:42.283  1069  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 03:25:42.283  1069  1445 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 03:25:42.283  1069  1445 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:42.283  1069  1445 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-25 03:25:42.284  1069  1376 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:42.284  1069  1376 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 03:25:42.284  1586  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 03:25:42.284  1836  1836 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:42.284  1836  1836 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&B,IP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-25 03:25:42.290  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-25 03:25:42.294  7383  7383 I dhcpcd  : version 5.5.6 starting
08-25 03:25:42.296  7383  7383 E dhcpcd  : get_duid: m
08-25 03:25:42.296  7383  7383 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-25 03:25:42.296  7383  7383 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-25 03:25:42.296  1801  7380 W EventLogAggregator: Unknown tag: snet_gcore
08-25 03:25:42.296  1801  7380 W EventLogAggregator: Unknown tag: snet_launch_service
08-25 03:25:42.297  6294  6294 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-25 03:25:42.298  6294  6294 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-25 03:25:42.300  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 03:25:42.305  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-25 03:25:42.317  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 03:25:42.317  1586  1586 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-25 03:25:42.317  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 03:25:42.318  6343  6343 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 03:25:42.318  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:42.318  6343  6343 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 03:25:42.319  6343  6343 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 03:25:42.319  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:42.323  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-25 03:25:42.326  6294  6294 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-25 03:25:42.326  6294  6294 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-25 03:25:42.329  6274  6274 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-25 03:25:42.334  6274  6274 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-25 03:25:42.338  6343  6343 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-25 03:25:42.338  6343  6343 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-25 03:25:42.338  6343  6343 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-25 03:25:42.339  6343  6343 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-25 03:25:42.339  6343  6343 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-25 03:25:42.352  7383  7383 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 03:25:42.352  7383  7383 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 03:25:42.352  7383  7383 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 03:25:42.352  7383  7383 I dhcpcd  : wlan0: rebinding lease of 192.168.1.108
08-25 03:25:42.352  7383  7383 D dhcpcd  : wlan0: sending REQUEST (xid 0x9eeb5274), next in 3.72 seconds
,08-25 03:25:42.370  1801  7380 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-25 03:25:42.375  7383  7383 I dhcpcd  : wlan0: acknowledged 192.168.1.108 from 192.168.1.1
08-25 03:25:42.378  1069  1428 D WifiService: New client listening to asynchronous messages
,08-25 03:25:42.381  7383  7383 I dhcpcd  : wlan0: leased 192.168.1.108 for 172800 seconds
08-25 03:25:42.381  7383  7383 D dhcpcd  : wlan0: adding IP address 192.168.1.108/24
08-25 03:25:42.381  7383  7383 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-25 03:25:42.381  7383  7383 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-25 03:25:42.381  7383  7383 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-25 03:25:42.382  7383  7383 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-25 03:25:42.382  7383  7383 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-25 03:25:42.382  7383  7383 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
,08-25 03:25:42.534  1069  1096 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7401 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-25 03:25:42.596  7401  7401 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-25 03:25:42.596  7401  7401 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-25 03:25:42.628  7401  7401 I MultiDex: VM with version 2.1.0 has multidex support
08-25 03:25:42.628  7401  7401 I MultiDex: install
08-25 03:25:42.628  7401  7401 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-25 03:25:42.640  7401  7401 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-25 03:25:42.646  2169  2169 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-25 03:25:42.666  2169  2169 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-25 03:25:42.666  2169  2169 D c       : Getting all permits...
08-25 03:25:42.666  2169  2169 D a       : Opening database...
08-25 03:25:42.672  2169  2169 D a       : Opening database auth.proximity.permit_store...
08-25 03:25:42.673  2169  2169 D a       : Closing database...
08-25 03:25:42.686  1069  7370 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-25 03:25:42.686  1069  7370 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-25 03:25:42.687  1069  7370 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-25 03:25:42.687  1069  7370 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.108
08-25 03:25:42.687  1069  7370 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-25 03:25:42.687  1069  7370 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-25 03:25:42.687  1069  7370 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-25 03:25:42.687  1069  7370 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-25 03:25:42.688  1069  7370 D DhcpStateMachine: RunningState
08-25 03:25:42.741  7401  7418 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-25 03:25:42.776   306  7437 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-25 03:25:42.776   306  7437 D libc-netbsd: res_queryN name = www.googleapis.com, class = 1, type = 1
,08-25 03:25:42.834   306  7437 D libc-netbsd: res_queryN name = www.googleapis.com succeed
,08-25 03:25:43.764  1069  1376 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 03:25:43.764  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 03:25:43.765  1069  1376 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 03:25:43.765  1069  1376 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 03:25:43.766  1069  1376 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-25 03:25:43.766  1069  1376 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-25 03:25:43.770  1069  1445 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-25 03:25:43.770  1069  1445 D ConnectivityService: identical MTU - not setting
08-25 03:25:43.771  1069  1445 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-25 03:25:43.771  1069  1445 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-25 03:25:43.771  1069  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:43.771  1069  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 03:25:43.772  1069  1445 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 03:25:43.773  1586  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-25 03:25:44.020  7444  7444 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=38 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-25 03:25:44.122  7444  7444 I dex2oat : dex2oat took 102.200ms (threads: 4)
,08-25 03:25:44.144  7401  7418 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 03:25:44.144  7401  7418 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 03:25:44.144  7401  7418 I Adreno-EGL: Build Date: 12/12/14 금
08-25 03:25:44.144  7401  7418 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 03:25:44.144  7401  7418 I Adreno-EGL: Remote Branch: 
08-25 03:25:44.144  7401  7418 I Adreno-EGL: Local Patches: 
08-25 03:25:44.144  7401  7418 I Adreno-EGL: Reconstruct Branch: 
,08-25 03:25:44.295  7401  7418 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 03:25:44.295  7401  7418 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 03:25:44.295  7401  7418 I Adreno-EGL: Build Date: 12/12/14 금
08-25 03:25:44.295  7401  7418 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 03:25:44.295  7401  7418 I Adreno-EGL: Remote Branch: 
08-25 03:25:44.295  7401  7418 I Adreno-EGL: Local Patches: 
08-25 03:25:44.295  7401  7418 I Adreno-EGL: Reconstruct Branch: 
,08-25 03:25:44.346  7401  7418 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-25 03:25:44.346  7401  7418 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-25 03:25:44.346  7401  7418 I Adreno-EGL: Build Date: 12/12/14 금
08-25 03:25:44.346  7401  7418 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-25 03:25:44.346  7401  7418 I Adreno-EGL: Remote Branch: 
08-25 03:25:44.346  7401  7418 I Adreno-EGL: Local Patches: 
08-25 03:25:44.346  7401  7418 I Adreno-EGL: Reconstruct Branch: 
,08-25 03:25:44.414  7401  7418 D LgDataFeature: LgDataFeature() Constructor: none
08-25 03:25:44.414  7401  7418 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 03:25:44.506   306  7473 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-25 03:25:44.506   306  7473 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-25 03:25:44.555   306  7473 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-25 03:25:44.833  1801  7380 I CheckinTask: Sending checkin request (8023 bytes)
,08-25 03:25:45.039  1801  7380 I CheckinResponseProcessor: From server: 2 gservices updates and 0 deletes
,08-25 03:25:45.076  1069  1376 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=7.5, 0.0, 0.0  rx=10.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1085437452] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 03:25:45.077  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=7.5, 0.0, 0.0  rx=10.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1085437451] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 03:25:45.077  1069  1376 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-25 03:25:45.085  1586  1586 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-25 03:25:45.127  1069  1421 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-25 03:25:45.150  1069  1445 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:25:45.158  1069  1176 D Tethering: MasterInitialState.processMessage what=3
08-25 03:25:45.167  1069  1808 D AlarmManagerService: Setting time of day to sec=1472088345
,08-25 03:25:45.244  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:45.244  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:45.244  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:45.244  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:25:45.244  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:25:45.244  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:25:45.244  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:25:45.244  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 03:25:45.245  6126  6126 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 03:25:45.251  1069  1808 W AlarmManagerService: Unable to set rtc to 1472088345: Invalid argument
,08-25 03:25:45.257  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:45.257  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:45.257  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:45.257  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:25:45.257  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:25:45.257  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:25:45.257  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:25:45.257  6126  6126 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 03:25:45.259  6126  6126 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 03:25:45.286  1586  1586 D KeyguardUpdateMonitor: handleTimeUpdate
,08-25 03:25:45.290  1925  1925 I SecureClockService: Intent.ACTION_TIME_CHANGED 
08-25 03:25:45.291  1586  1586 I [SystemUI]Clock: onReceive = android.intent.action.TIME_SET
08-25 03:25:45.296  2739  2739 D LIA_Informant_Tips_DateChangeManager: onReceive() : ACTION_TIME_CHANGED
08-25 03:25:45.297  2739  2739 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] Time Change Event Received : 2016-08-25 03:25:45...... Request
08-25 03:25:45.297  2739  2739 I LIA_Informant_Tips_LogTracer: [Log Tracer - Schedule Transition] UserGuide, DATE_UPDATE : working count : 7, total count : 66, new day : false...... Request
08-25 03:25:45.298  2739  2739 D LIA_Informant_Tips_DateChangeManager: DateInfo : SmartTips Total Working Day Count = 66
08-25 03:25:45.298  2739  2739 D LIA_Informant_Tips_DateChangeManager: DateInfo : UserGuide Working Duration Count = 7
08-25 03:25:45.298  2739  2739 D LIA_Informant_Tips_DateChangeManager: DateInfo : Last Date Check Time = 2016-08-25 03:25:45
08-25 03:25:45.302  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-25 03:25:45.308  4879  6268 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-25 03:25:45.310  1586  1586 I LgeClockWidgetControlView: time changed, timezoneChanged : false
08-25 03:25:45.315  1069  1167 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:25:45.341  6126  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-25 03:25:45.341  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:45.341  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:45.341  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:25:45.341  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:25:45.341  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:25:45.341  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:25:45.341  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:25:45.344  6126  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 03:25:45.345  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:25:45.345  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@199b0eca removed from the list
08-25 03:25:45.345  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:25:45.345  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:25:45.345  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:25:45.350  1069  1096 W ActivityManager: getTasks: caller 10029 is using old GET_TASKS but privileged; allowing
08-25 03:25:45.351  6126  7487 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-25 03:25:45.351  6126  7487 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-25 03:25:45.356  2016  2016 I [LGHome]LGDateChangeReceiver: [LGDateChangeReceiver.java:78:updateCalendarShortcut()]date=25 currentDate=-1 dayofweek=5 currentDayOfWeek=-1
08-25 03:25:45.359  2016  2016 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 25
08-25 03:25:45.359  5347  5347 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-25 03:25:45.369  2016  2016 I [LGHome]LGCalendarIcon: [LGCalendarIcon.java:214:makeCalendarBitmap()]Locale = en_US dayofweek= Thu date= 25
08-25 03:25:45.370  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 03:25:45.379  1069  1167 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-25 03:25:45.396  2563  2563 D [Concierge]Service: onStartCommand(). Type : 9
,08-25 03:25:45.399  2169  2169 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
08-25 03:25:45.406   306  7496 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-25 03:25:45.406   306  7496 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-25 03:25:45.407  1069  2025 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
08-25 03:25:45.407  1069  7369 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:45.408  1069  7369 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:45.408  1069  7369 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-25 03:25:45.408  1069  7369 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:25:45.408  1069  7369 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
,08-25 03:25:45.417  1069  7369 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 01:25:45 GMT], X-Android-Received-Millis=[1472088345417], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472088345409]}
08-25 03:25:45.417  1069  7369 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-25 03:25:45.417  1069  7369 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-25 03:25:45.418  1069  1445 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-25 03:25:45.418  1069  1445 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-25 03:25:45.418  1069  1445 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 03:25:45.418  1069  1445 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
,08-25 03:25:45.418  1069  1445 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 03:25:45.418  1069  1445 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-25 03:25:45.418  1069  1445 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-25 03:25:45.419  1069  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:25:45.419  1069  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 03:25:45.420  1069  1445 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 03:25:45.420  1586  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
,08-25 03:25:45.454   306  7496 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-25 03:25:45.462  1069  2611 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7498 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-25 03:25:45.510  1069  7515 I CertBlacklister: Certificate blacklist changed, updating...
08-25 03:25:45.521  1069  7515 I CertBlacklister: Certificate blacklist updated
,08-25 03:25:45.524  2169  2294 I GservicesProvider: main difference update completed
,08-25 03:25:45.540  7498  7498 I AppUp4:AppBoxCP: onCreate
,08-25 03:25:45.541  7498  7498 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-25 03:25:45.549  7498  7498 I AppUp4:DB:  setFingerPrint start
08-25 03:25:45.550  7498  7498 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-25 03:25:45.557  7498  7498 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-25 03:25:45.557  7498  7498 I AppUp4:DB:  SDK version = 21
08-25 03:25:45.557  7498  7498 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-25 03:25:45.558  7498  7498 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-25 03:25:45.559  7498  7498 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-25 03:25:45.559  7498  7498 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-25 03:25:45.562  7498  7498 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
,08-25 03:25:45.563  7498  7498 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-25 03:25:45.566  7498  7498 I AppUp4:CustModeStarterReceiver: onReceive
08-25 03:25:45.577  2169  7495 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,08-25 03:25:45.601  7498  7498 D LgDataFeature: LgDataFeature() Constructor: none
08-25 03:25:45.601  7498  7498 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 03:25:45.607  7498  7498 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@29776c5e
08-25 03:25:45.607  7498  7498 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 03:25:45.607  7498  7498 D AppUp4:CustFacade: isPhone : true
08-25 03:25:45.607  7498  7498 D AppUp4:CustModeStarterReceiver: begin check event
08-25 03:25:45.608  7498  7498 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-25 03:25:45.608  7498  7498 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-25 03:25:45.608  7498  7516 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-25 03:25:45.608  7498  7516 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-25 03:25:45.609  7498  7516 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-25 03:25:45.610  1069  1097 I ActivityManager: Killing 6695:com.lge.email/u0a23 (adj 15): empty #17
08-25 03:25:45.653  4207  4207 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-25 03:25:45.653  4207  4207 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-25 03:25:45.654  1069  1672 W libprocessgroup: failed to open /acct/uid_10023/pid_6695/cgroup.procs: No such file or directory
,08-25 03:25:45.656  4207  4207 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 03:25:45.666  4207  4207 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-25 03:25:45.676  4207  7520 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-25 03:25:45.678  2832  2832 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
,08-25 03:25:45.683  4207  7520 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-25 03:25:45.688  2832  2832 V DownloadManager: DownloadService onCreate
08-25 03:25:45.693  1801  7380 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-25 03:25:45.696  2832  7522 I DownloadManager: in removeSpuriousFiles
08-25 03:25:45.697  4207  7521 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-25 03:25:45.697  2832  7522 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-25 03:25:45.698  4207  7521 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-25 03:25:45.700  2832  7522 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@13e61b35 on behalf of 2832
08-25 03:25:45.701  2832  7522 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-25 03:25:45.701  2832  7522 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-25 03:25:45.701  2832  7522 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-25 03:25:45.701  2832  7522 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-25 03:25:45.701  2832  7522 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-25 03:25:45.701  2832  7522 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-25 03:25:45.701  2832  7522 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-25 03:25:45.702  2832  7522 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-25 03:25:45.702  2832  7522 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-25 03:25:45.702  2832  7522 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-25 03:25:45.702  2832  7522 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
08-25 03:25:45.705  2832  7522 I DownloadManager: in trimDatabase
08-25 03:25:45.705  2832  7522 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-25 03:25:45.710  2832  7522 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@b25213b on behalf of 2832
08-25 03:25:45.745  1069  1672 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7526 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-25 03:25:45.747  2832  2832 V DownloadManager: DownloadService onStartCommand
08-25 03:25:45.748  2832  7523 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
,08-25 03:25:45.751  2832  7523 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@396a35b1 on behalf of 2832
08-25 03:25:45.755  4207  7520 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-25 03:25:45.756  2832  7523 V DownloadManager: processing inserted download 1
08-25 03:25:45.758  2832  7523 V DownloadManager: processing inserted download 4
08-25 03:25:45.759  2832  7523 V DownloadManager: processing inserted download 7
08-25 03:25:45.760  2832  7523 V DownloadManager: processing inserted download 8
08-25 03:25:45.761  2832  7523 V DownloadManager: processing inserted download 9
08-25 03:25:45.762  4207  4207 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-25 03:25:45.763  2832  7523 V DownloadManager: processing inserted download 10
08-25 03:25:45.763  4207  4207 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-25 03:25:45.765  4207  4207 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-25 03:25:45.765  2832  7523 V DownloadManager: processing inserted download 11
08-25 03:25:45.766  2832  7523 V DownloadManager: processing inserted download 12
08-25 03:25:45.767  4207  4207 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
08-25 03:25:45.767  2832  7523 V DownloadManager: processing inserted download 13
08-25 03:25:45.768  2832  7523 V DownloadManager: processing inserted download 14
08-25 03:25:45.770  2832  7523 V DownloadManager: processing inserted download 16
08-25 03:25:45.771  4207  4207 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-25 03:25:45.774  2832  2832 V DownloadManager: DownloadService onDestroy
08-25 03:25:45.779  1801  7380 I CheckinService: active receiver: disabled
,08-25 03:25:45.813  1801  7544 I CheckinService: active receiver: disabled
08-25 03:25:45.819  7526  7526 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 03:25:45.820  7526  7526 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 03:25:45.822  7526  7526 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 03:25:45.822  7526  7526 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 03:25:45.914  7526  7526 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-25 03:25:45.929  7526  7526 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-25 03:25:45.982  7526  7526 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-25 03:25:46.028  7526  7526 D LgDataFeature: LgDataFeature() Constructor: none
,08-25 03:25:46.028  7526  7526 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 03:25:46.169  7526  7526 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69),
,08-25 03:25:46.218  3384  3384 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-25 03:25:46.219  3384  3384 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-25 03:25:46.219  3384  3384 I LgeMiscReceiver: networkInfo.isConnected() = true
08-25 03:25:46.219  3384  3384 D PhoneState: setPdpRejectCasuse : false
,08-25 03:25:46.223  6724  6724 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-25 03:25:46.223  6724  6724 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-25 03:25:46.246  6796  6796 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:25:46
,08-25 03:25:46.252  6796  6796 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 03:25:46.252  6796  6796 D Weather.Utils: 2 : All the weather widget is gone.
08-25 03:25:46.253  6796  6796 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 03:25:46.253  6796  6796 D WeatherAncestor: connectivity changed - connection : true
08-25 03:25:46.253  6796  6796 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3c84150c
08-25 03:25:46.254  6796  6796 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-25 03:25:46.254  6796  6796 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-25 03:25:46.254  6796  6796 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-25 03:25:46.254  6796  6796 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-25 03:25:46.254  6796  6796 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 3:25:46
08-25 03:25:46.291  4879  4879 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.TIME_SET'.
,08-25 03:25:46.319  1801  7565 I CheckinService: active receiver: disabled
,08-25 03:25:46.321   306  7567 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-25 03:25:46.322   306  7567 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-25 03:25:46.358  1069  1097 I art     : Explicit concurrent mark sweep GC freed 80708(3MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 1.618ms total 128.469ms
,08-25 03:25:46.363  7526  7526 I HubEmail: JNI_OnLoad()
08-25 03:25:46.363  7526  7526 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 03:25:46.363  7526  7526 I HubEmail: registerNatives()
08-25 03:25:46.363  7526  7526 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 03:25:46.363  7526  7526 I HubEmail: registerNativeMethods()
08-25 03:25:46.363  7526  7526 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-25 03:25:46.363  7526  7526 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-25 03:25:46.368   306  7567 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
08-25 03:25:46.374  1069  1096 I ActivityManager: Start proc com.lge.clock for broadcast com.lge.clock/.alarmclock.ALBootInit: pid=7575 uid=10010 gids={50010, 9997, 3003, 1028, 4002} abi=armeabi-v7a
,08-25 03:25:46.378  7526  7574 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-25 03:25:46.405  6383  7558 V FormManager: There are no updated forms. The schedule will be deleted.
08-25 03:25:46.409  6383  7558 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-25 03:25:46.413   306  7593 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-25 03:25:46.413   306  7593 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
08-25 03:25:46.429  1069  1559 I ActivityManager: Killing 6954:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-25 03:25:46.452   306  7593 D libc-netbsd: res_queryN name = www.google.com succeed
,08-25 03:25:46.456   306  7596 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-25 03:25:46.457   306  7596 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-25 03:25:46.458   306  7596 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-25 03:25:46.463  1069  1097 W libprocessgroup: failed to open /acct/uid_10037/pid_6954/cgroup.procs: No such file or directory
,08-25 03:25:46.472  7575  7597 D ALBootInit: ====action==>android.intent.action.TIME_SET
08-25 03:25:46.474  1069  1422 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
08-25 03:25:46.479  7575  7597 D ALBootInit: Alarm ALBootInit: TIME_SET
,08-25 03:25:46.486  7575  7597 D Alarms  : [setNextAlert] start
,08-25 03:25:46.503  7575  7597 D Alarms  : [setNextAlert] (1)
,08-25 03:25:46.506  7575  7597 D Alarms  :  minTime  = 0
,08-25 03:25:46.509  7575  7597 D Alarms  :  -- OK multi -- 0
08-25 03:25:46.509  7575  7597 E jeny.kim: [setNextAlert] setNextAlert  temp_Alarmlink + 
08-25 03:25:46.510  7575  7597 E jeny.kim: [setNextAlert]setNextAlert temp_AlarmLinkText + 
,08-25 03:25:46.542  7575  7597 I CommonUtil: BUILD Country: EU
08-25 03:25:46.544  7575  7597 D Alarms  : broadcastToWidgetProvider : false
,08-25 03:25:46.551  7575  7597 D Alarms  : Enter formatDayAndTime(final Context context, long timeInMiliSec)
,08-25 03:25:46.573  1069  1559 V SettingsProvider: call_put(system:next_alarm_formatted=) for 0 calling package = com.lge.clock
,08-25 03:25:46.584  7575  7575 I DigitalAppWidgetProvider: onReceive: android.intent.action.TIME_SET
08-25 03:25:46.587  7575  7575 V DigitalAppWidgetProvider: cancelAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3991f83f
08-25 03:25:46.590  7575  7575 V DigitalAppWidgetProvider: startAlarmOnQuarterHour android.app.ReceiverRestrictedContext@3991f83f
,08-25 03:25:46.596  7575  7575 D QuickCoverProvider: onReceiver
08-25 03:25:46.611  1542  1542 I indal   : SmartCoverWidgetContext createApplicationContext
,08-25 03:25:46.612  1542  1542 I indal   : SmartCoverWidgetContext createApplicationContext
08-25 03:25:46.639  6796  6796 D WeatherAncestor: 2 : onReceive, action: android.intent.action.TIME_SET, Time(hour:min:sec) 3:25:46
,08-25 03:25:46.641  6796  6796 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 03:25:46.642  6796  6796 D Weather.Utils: 2 : All the weather widget is gone.
08-25 03:25:46.642  6796  6796 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 03:25:46.650  6796  6796 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@3c84150c
08-25 03:25:46.651  6796  6796 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-25 03:25:46.651  6796  6796 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
,08-25 03:25:46.652  6796  6796 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
,08-25 03:25:46.658  6796  6796 D Weather_cast: 2 : set auto-update time : 8/25 6:25
08-25 03:25:46.672  6796  6796 D WeatherAncestor: 2 : onReceive has processed, action: android.intent.action.TIME_SET, Time(hour:min:sec) 3:25:46
,08-25 03:25:46.752  1069  1097 I ActivityManager: Start proc com.qualcomm.timeservice for broadcast com.qualcomm.timeservice/.TimeServiceBroadcastReceiver: pid=7602 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-25 03:25:46.753  1069  1097 I ActivityManager: Killing 6363:com.lge.settings.easy/1000 (adj 15): empty #17
08-25 03:25:46.803  1069  1559 W libprocessgroup: failed to open /acct/uid_1000/pid_6363/cgroup.procs: No such file or directory
,08-25 03:25:46.826  1069  1376 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,08-25 03:25:46.826  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
08-25 03:25:46.827  1069  1376 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
08-25 03:25:46.827  1069  1376 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
08-25 03:25:46.828  1069  1376 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
08-25 03:25:46.828  1069  1376 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 1 0
,08-25 03:25:46.870  7602  7602 D TimeService: Receivedandroid.intent.action.TIME_SET intent. Current Time is 1472088346870
,08-25 03:25:46.870  7602  7602 D         : TimeServiceNative: User Time to be set is 1472088346870
08-25 03:25:46.870  7602  7602 D QC-time-services: Lib:time_genoff_operation: pargs->base = 2
08-25 03:25:46.870  7602  7602 D QC-time-services: Lib:time_genoff_operation: pargs->operation = 0
08-25 03:25:46.870  7602  7602 D QC-time-services: Lib:time_genoff_operation: pargs->ts_val = 1472088346870
08-25 03:25:46.870  7602  7602 D QC-time-services: Lib:time_genoff_operation: Send to server  passed!!
08-25 03:25:46.871   369  1033 D QC-time-services: Daemon: Connection accepted:time_genoff
08-25 03:25:46.871   369  7619 D QC-time-services: Daemon:Received base = 2, unit = 1, operation = 0,value = 1472088346870
,08-25 03:25:46.871   369  7619 D QC-time-services: Daemon:genoff_opr: Base = 2, val = 1472088346870, operation = 0
08-25 03:25:46.871   369  7619 D QC-time-services: Daemon:rtc_get: Time read from RTC -- MM/DD/YY HH:MM:SS2/6/70 19:53:18
08-25 03:25:46.871   369  7619 D QC-time-services: Daemon:Value read from RTC seconds = 5601198000
08-25 03:25:46.871   369  7619 D QC-time-services: Daemon:new time 1472088346870 
08-25 03:25:46.871   369  7619 D QC-time-services: Daemon: delta 1466487148870 genoff 1466487148870 
08-25 03:25:46.871   369  7619 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487148870 to memory
08-25 03:25:46.871   369  7619 D QC-time-services: Daemon:Opening File: /data/time/ats_2
08-25 03:25:46.871   369  7619 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
08-25 03:25:46.878   369  7619 D QC-time-services: Updating the TOD offset
08-25 03:25:46.878   369  7619 D QC-time-services: Daemon:genoff_persistent_update: Writing genoff = 1466487148870 to memory
08-25 03:25:46.878   369  7619 D QC-time-services: Daemon:Opening File: /data/time/ats_1
08-25 03:25:46.878   369  7619 D QC-time-services: Daemon:time_persistent_memory_opr:Genoff write operation 
08-25 03:25:46.883  7602  7602 E QC-time-services: Receive Passed == base = 2, unit = 1, operation = 0, result = 0
08-25 03:25:46.883   369  7619 E QC-time-services: Daemon:Update to modem bit set
08-25 03:25:46.883   369  7619 D QC-time-services: Daemon:genoff_send_modem: Sending data to MODEM !
08-25 03:25:46.883   369  7619 D QC-time-services: Daemon: Base = 2, Value being sent to MODEM = 1150522348870
08-25 03:25:46.888   369  1031 E QC-time-services: Daemon:tod_update_ind_cb: Got Update from modem msg_id 40
,08-25 03:25:46.891  7325  7325 V [BNRBootReceiver]: boot receiver action = android.intent.action.TIME_SET
,08-25 03:25:46.891   369  1033 E QC-time-services: Daemon: Time-services: Waiting to acceptconnection
08-25 03:25:46.894  7325  7325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
08-25 03:25:46.896  1586  1586 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
08-25 03:25:46.896  1586  1586 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
08-25 03:25:46.896  1586  1586 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
08-25 03:25:46.901  7325  7325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:230 com.lge.bnr.service.BNRBootReceiver.onReceive:121 
08-25 03:25:46.903  7325  7325 V [BNRBootReceiver]: Boot Receiver Return
,08-25 03:25:46.964  1069  1926 I ActivityManager: Start proc com.android.calendar for broadcast com.android.calendar/.widget.CalendarAppWidgetProvider: pid=7623 uid=10013 gids={50013, 9997, 3003, 1028, 1015} abi=armeabi
08-25 03:25:46.966  1069  1926 I ActivityManager: Killing 6294:com.lge.sync/1000 (adj 15): empty #17
08-25 03:25:47.065  1069  1672 W libprocessgroup: failed to open /acct/uid_1000/pid_6294/cgroup.procs: No such file or directory
,08-25 03:25:47.113  7623  7623 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 03:25:47.147  7623  7623 D CalendarApplication: CalendarApplication.onCreate()
,08-25 03:25:47.161  7623  7623 D PreferenceKeysParser: [debug_displayParseInfos] preference keys.size() = 44
08-25 03:25:47.162  7623  7623 D PreferenceKeysParser: [debug_displayParseInfos] preference keys = {lg_preferences_tardis_1=com.android.calendar.adaptation.PreferenceKey$KeyData@23d95112, lg_preferences_hide_declined=com.android.calendar.adaptation.PreferenceKey$KeyData@2730e3, lg_preferences_default_reminder=com.android.calendar.adaptation.PreferenceKey$KeyData@34272ae0, lg_preferences_month_view_style=com.android.calendar.adaptation.PreferenceKey$KeyData@2cfdb199, lg_preferences_alerts_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@29776c5e, lg_preferences_device_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@3991f83f, lg_preferences_debug_datesearch=com.android.calendar.adaptation.PreferenceKey$KeyData@3c84150c, lg_preferences_debug_country=com.android.calendar.adaptation.PreferenceKey$KeyData@15eece55, lg_preferences_display_weather_information=com.android.calendar.adaptation.PreferenceKey$KeyData@449f06a, lg_preferences_alerts_vibrateWhen=com.android.calendar.adaptation.PreferenceKey$KeyData@36b7d95b, lg_preferences_debug_rtl=com.android.calendar.adaptation.PreferenceKey$KeyData@7e375f8, lg_preferences_alerts_type=com.android.calendar.adaptation.PreferenceKey$KeyData@1f9afad1, lg_preferrences_country_code=com.android.calendar.adaptation.PreferenceKey$KeyData@3c0ea936, lg_preferences_weather_info=com.android.calendar.adaptation.PreferenceKey$KeyData@1f90b037, lg_preference_holiday_calendar_ver=com.android.calendar.adaptation.PreferenceKey$KeyData@7d5f9a4, lg_preferences_show_controls=com.android.calendar.adaptation.PreferenceKey$KeyData@103730d, lg_preferences_user_select_noti_sound=com.android.calendar.adaptation.PreferenceKey$KeyData@49422c2, lg_preference_default_myphonebook=com.android.calendar.adaptation.PreferenceKey$KeyData@39b618d3, lg_preferences_skip_setup=com.android.calendar.adaptation.PreferenceKey$KeyData@144b0c10, lg_preferred_startView=com.android.calendar.adaptation.PreferenceKey$KeyData@26013309, lg_preferences_debug_operator=com.android.calendar.adaptation.PreferenceKey$KeyData@e05a90e, lg_preferences_exclude_sticker_list=com.android.calendar.adaptation.PreferenceKey$KeyData@bf6f2f, lg_preferences_writable_calendars_count=com.android.calendar.adaptation.PreferenceKey$KeyData@12bcd93c, lg_preferred_detailedView=com.android.calendar.adaptation.PreferenceKey$KeyData@500f6c5, lg_preferences_debug_floating=com.android.calendar.adaptation.PreferenceKey$KeyData@df7481a, lg_preferences_home_tz=com.android.calendar.adaptation.PreferenceKey$KeyData@285dcf4b, lg_preferences_home_tz_enabled=com.android.calendar.adaptation.PreferenceKey$KeyData@241c4d28, lg_preference_received_provider_reminder_broadcast=com.android.calendar.adaptation.PreferenceKey$KeyData@147f3a41, lg_preferences_default_cell_height=com.android.calendar.adaptation.PreferenceKey$KeyData@d31cbe6, lg_preferences_notification_type=com.android.calendar.adaptation.PreferenceKey$KeyData@24381527, lg_preferences_show_week_num=com.android.calendar.adaptation.PreferenceKey$KeyData@57d13d4, lg_preferences_dont_show_again_no_online_account=com.android.calendar.adaptation.PreferenceKey$KeyData@1c44397d, lg_preferences_alerts_popup=com.android.calendar.adaptation.PreferenceKey$KeyData@63ec072, lg_preferences_week_start_day=com.android.calendar.adaptation.PreferenceKey$KeyData@1186dcc3, lg_preferences_app_version=com.android.calendar.adaptation.PreferenceKey$KeyData@f819940, lg_preferences_alerts=com.android.calendar.adaptation.PreferenceKey$KeyData@1e5ff079, lg_preferences_select_aux_calendar=com.android.calendar.adaptation.PreferenceKey$KeyData@20b471be, lg_preferences_widget_info_calendars=com.android.calendar.adaptation.PreferenceKey$KeyData@1e70821f, lg_preferences_alerts_default_ringtone=com.android.calendar.adaptation.PreferenceKey$KeyData@87096c, lg_preference_defaultCalendar=com.android.calendar.adaptation.PreferenceKey$KeyData@13e61b35, lg_preferences_alerts_vibratetype=com.android.calendar.adaptation.PreferenceKe,y$KeyData@1541ebca, lg_preferences_recent_timezones=com.android.calendar.adaptation.PreferenceKey$KeyData@b25213b, lg_pref
08-25 03:25:47.167  7623  7623 D GeneralPreferenceUtils: [migratePrefrenceKeys] Exit: Version(44001600) >= 42001300
08-25 03:25:47.177  7623  7623 D Config  : [init]
08-25 03:25:47.178  7623  7623 I Config  : LGCalendar ver.4.40.16
08-25 03:25:47.178  7623  7623 I Config  : start check model
08-25 03:25:47.178  7623  7623 I Config  : start check native_ca
08-25 03:25:47.179  7623  7623 I Config  : Config Operator=OPEN, Country=EU
08-25 03:25:47.179  7623  7623 D Config  : [setDefaultValuesToPref]
08-25 03:25:47.179  7623  7623 D Config  : [parseProfiles]
08-25 03:25:47.184  7623  7623 D ProfilesParser: [debug_displayParseInfos] profile.country = null
08-25 03:25:47.184  7623  7623 D ProfilesParser: [debug_displayParseInfos] profile.operator = null
08-25 03:25:47.184  7623  7623 D Config  : [updateProfiletoCountryInfo]
08-25 03:25:47.185  7623  7623 D GeneralPreference: [checkAndMigrateOldPreference]
08-25 03:25:47.197  7623  7623 E AgendaWidgetManager: [updateWidgets] 
,08-25 03:25:47.325  7623  7645 I InitNotificationRingtoneService: Start InitializeAlertRingtoneService.onHandleIntent
,08-25 03:25:47.329  7623  7645 I AlertUtils: [setFormatNotificationSound] current noti URI = content://media/internal/audio/media/41
08-25 03:25:47.331  7623  7623 D MonthWidgetProvider: [onReceive]
08-25 03:25:47.331  7623  7623 D CalendarWidgetProvider: [onReceive]
08-25 03:25:47.332  7623  7623 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.MonthWidgetProvider }
08-25 03:25:47.334  7623  7623 D CalendarTypeController: [onUpdateAndInitCalendarTime],
08-25 03:25:47.335  7623  7646 W HolidayIntentService: onHandleIntent
08-25 03:25:47.337  7623  7646 D HolidayDataLoader: readJsonAsset : holiday.json
08-25 03:25:47.350  7623  7623 D WeekWidgetProvider: [onReceive]
08-25 03:25:47.350  7623  7623 D CalendarWidgetProvider: [onReceive]
08-25 03:25:47.350  7623  7623 D CalendarWidgetProvider: [CalendarWidgetProvider] got the intent: Intent { act=android.intent.action.TIME_SET flg=0x24000010 cmp=com.android.calendar/.widget.WeekWidgetProvider }
,08-25 03:25:47.354  7623  7623 D CalendarTypeController: [onUpdateAndInitCalendarTime]
08-25 03:25:47.358  6343  6343 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-25 03:25:47.359  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:3526
08-25 03:25:47.366  7623  7645 I AlertUtils: [getCalendarNotiSoundURIFromCursor] getCount()= 21
,08-25 03:25:47.374  7623  7645 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Arpeggio.ogg
08-25 03:25:47.378  7623  7645 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Country_Blues.ogg
08-25 03:25:47.381  7623  7645 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Crystal.ogg
,08-25 03:25:47.385  7623  7645 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Dewdrop.ogg
08-25 03:25:47.391  7623  7645 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Ding_Dong.ogg
08-25 03:25:47.394  7623  7645 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Echo.ogg
,08-25 03:25:47.397  7623  7645 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Email.ogg
08-25 03:25:47.400  7623  7645 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Game_Over.ogg
08-25 03:25:47.403  7623  7645 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Gayageum.ogg
08-25 03:25:47.409  7623  7645 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/alarms/Afternoon_Walk.ogg
,08-25 03:25:47.414  7623  7645 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Harmonics.ogg
08-25 03:25:47.427  7623  7645 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Idea.ogg
08-25 03:25:47.427  1801  1801 I SystemUpdateService: receiver: Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.update.SystemUpdateService$Receiver }
08-25 03:25:47.433  7623  7645 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/News.ogg
,08-25 03:25:47.439  7623  7646 E HolidayIntentService: onHandleIntent:holiday data empty
08-25 03:25:47.439  1801  1801 D SystemUpdateService: onCreate
08-25 03:25:47.445  7623  7645 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Pebble.ogg
,08-25 03:25:47.446  2169  2169 D GCM     : GcmService start Intent { act=com.google.gservices.intent.action.GSERVICES_CHANGED flg=0x10 cmp=com.google.android.gms/.gcm.GcmService } com.google.gservices.intent.action.GSERVICES_CHANGED
08-25 03:25:47.451  7623  7645 I AlertUtils: [getMediaFilepathFromContentUri] filepath = /system/media/audio/notifications/Schedule.ogg
08-25 03:25:47.452  7623  7645 I AlertUtils: [getCalendarNotiSoundURIFromCursor] filePath = /system/media/audio/notifications/Schedule.ogg, new URI = content://media/internal/audio/media/41
08-25 03:25:47.452  1801  1801 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
08-25 03:25:47.452  1801  7647 V GA-SERVICE: Thread[IntentService[RefreshEnabledStateService],5,main]: Update service enabled state to: 1
08-25 03:25:47.453  1801  7649 I CheckinService: active receiver: disabled
08-25 03:25:47.459  7623  7645 I AlertUtils: set default noti to content://media/internal/audio/media/41
,08-25 03:25:47.469  7623  7645 I InitNotificationRingtoneService: End InitializeAlertRingtoneService.onHandleIntent
08-25 03:25:47.471  1069  2014 I ActivityManager: Killing 6274:com.android.settings/1000 (adj 15): empty #17
,08-25 03:25:47.481  2169  2169 I GCM     : GCM config loaded
08-25 03:25:47.489   306  7665 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-25 03:25:47.489   306  7665 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-25 03:25:47.489   306  7665 D libc-netbsd: res_queryN name = mtalk.google.com succeed
,08-25 03:25:47.500  1069  1559 W libprocessgroup: failed to open /acct/uid_1000/pid_6274/cgroup.procs: No such file or directory
,08-25 03:25:47.506  1801  7655 I SystemUpdateService: cancelUpdate (empty URL)
08-25 03:25:47.506  1801  7655 I SystemUpdateService: active receiver: disabled
,08-25 03:25:47.558  1801  1801 D SystemUpdateService: onDestroy
,08-25 03:25:47.588  1801  1801 D SystemEventReceiver: Received GSERVICES_CHANGED broadcast
,08-25 03:25:47.598  1801  1801 I OcrUtils: Updating ocr activity enabled=false
08-25 03:25:47.604  2485  2485 I GCoreUlr: Starting service, intent=Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) }, extras=Bundle[{receiverAction=com.google.gservices.intent.action.GSERVICES_CHANGED}]
,08-25 03:25:47.692  1069  2014 I ActivityManager: Start proc com.google.android.partnersetup for broadcast com.google.android.partnersetup/.GservicesChangedReceiver: pid=7668 uid=10008 gids={50008, 9997, 3003} abi=armeabi-v7a
,08-25 03:25:47.697  2485  2555 I GCoreUlr: WorldUpdater received intent Intent { act=com.google.android.location.reporting.ACTION_UPDATE_WORLD cmp=com.google.android.gms/com.google.android.location.reporting.service.DispatchingService (has extras) } with receiverAction com.google.gservices.intent.action.GSERVICES_CHANGED
,08-25 03:25:47.804  2169  7677 D GCM     : Connected
,08-25 03:25:47.810  2485  2555 I GCoreUlr: No GCM registration ID
08-25 03:25:47.832  4481  7696 I ContactAccountLoggerTas: canRun() : Opted Out
,08-25 03:25:47.839  7668  7690 D LgDataFeature: LgDataFeature() Constructor: none
08-25 03:25:47.839  7668  7690 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 03:25:47.858  1069  2025 I ActivityManager: Start proc com.google.android.configupdater for broadcast com.google.android.configupdater/.CertPin.CertPinUpdateRequestReceiver: pid=7697 uid=10059 gids={50059, 9997, 3003} abi=armeabi-v7a
,08-25 03:25:47.867  4481  7696 I Search.GservicesUpdateTask: Updating Gservices keys
,08-25 03:25:47.887  2169  7677 D GCM     : Message class com.google.e.a.a.q
08-25 03:25:47.898  2485  2555 I GCoreUlr: Ensuring that reporting is stopped because of reasons: (no Google accounts)
,08-25 03:25:47.900  2485  2561 D GCoreFlp: Unknown pending intent to remove.
08-25 03:25:47.905  2485  2555 I GCoreUlr: Unbound from all location providers
08-25 03:25:47.906  2485  2555 I BleScanCompatLib: Scan : No clients left, canceling alarm.
08-25 03:25:47.945  4481  7711 I ContactAccountLoggerTas: canRun() : Opted Out
,08-25 03:25:47.947  4481  7707 I ContactAccountLoggerTas: canRun() : Opted Out
08-25 03:25:47.950  7697  7697 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
08-25 03:25:47.955  4481  7707 I ContactAccountLoggerTas: canRun() : Opted Out
08-25 03:25:47.963  7697  7697 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
,08-25 03:25:47.967  7697  7697 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
08-25 03:25:47.972  7697  7697 E UpdateRequestReceiver: Received malformed URL while handling Gservices.CHANGED_ACTION
08-25 03:25:48.007  4481  7707 I ContactAccountLoggerTas: canRun() : Opted Out
,08-25 03:25:48.058  1069  1097 I ActivityManager: Killing 7498:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-25 03:25:48.097  2169  7715 I art     : Explicit concurrent mark sweep GC freed 14218(809KB) AllocSpace objects, 6(96KB) LOS objects, 52% free, 29MB/61MB, paused 1.309ms total 41.528ms
,08-25 03:25:48.118  1069  1888 W libprocessgroup: failed to open /acct/uid_10011/pid_7498/cgroup.procs: No such file or directory
,08-25 03:25:48.125  2169  2169 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-25 03:25:48.142  2169  2169 I GCM     : GCM config loaded
,08-25 03:25:48.157  1069  1376 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=31.8, 0.0, 0.0  rx=36.5 bcn=0 [on:0 tx:0 rx:0 period:3073] from screen [on:0 period:-1085434371] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 03:25:48.158  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=31.8, 0.0, 0.0  rx=36.5 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1085434370] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-25 03:25:48.159  1069  1376 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-25 03:25:48.186  6724  6724 V SetupWizard: Connected to Gservices successfully
,08-25 03:25:48.189  1069  2611 I ActivityManager: Killing 6383:com.lge.formmanager/u0a26 (adj 15): empty #17
08-25 03:25:48.287  1069  2025 W libprocessgroup: failed to open /acct/uid_10026/pid_6383/cgroup.procs: No such file or directory
,08-25 03:25:48.309  2169  2169 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-25 03:25:48.340  7575  7575 I DigitalAppWidgetProvider: onReceive: android.intent.action.ALARM_CHANGED
,08-25 03:25:48.350  6796  6796 D WeatherAncestor: 2 : onReceive, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 3:25:48
08-25 03:25:48.355  6796  6796 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 03:25:48.355  6796  6796 D Weather.Utils: 2 : All the weather widget is gone.
,08-25 03:25:48.356  6796  6796 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-25 03:25:48.359  6796  6796 D Weather_cast: 2 : Update is Canceled by com.lge.sizechangable.weather.action.alarm
08-25 03:25:48.360  6796  6796 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.sizechangable.weather.action.setweathercast, Time(hour:min:sec) 3:25:48
08-25 03:25:48.364  2016  2016 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
08-25 03:25:48.365  6126  7487 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
08-25 03:25:48.365  6126  7487 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-25 03:25:48.366  6126  7487 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-25 03:25:48.367  6126  7487 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-25 03:25:48.369  6126  7736 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-25 03:25:48.369  6126  7736 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
,08-25 03:25:48.369  2016  2824 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
08-25 03:25:48.369  2016  2824 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
08-25 03:25:48.369  6126  7487 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-25 03:25:48.370  2016  2824 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
08-25 03:25:48.370  2016  2824 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
08-25 03:25:48.370  2016  2824 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
08-25 03:25:48.371  7325  7325 V [BNRBootReceiver]: boot receiver action = com.lge.bnr.releasebadge
08-25 03:25:48.373  6126  7736 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-25 03:25:48.374  7325  7325 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.lge.bnr.service.BNRBootReceiver.setHomeBadgeCount:192 com.lge.bnr.service.BNRBootReceiver.setBadgeStatus:225 
08-25 03:25:48.375  6126  7739 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 798, name: OutgoingSocketThread/Receiver)
08-25 03:25:48.375  6126  7736 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-25 03:25:48.377  1586  1586 D KeyguardModel: mReceiver, received action: android.intent.action.BADGE_COUNT_UPDATE, sendingUserId:0
08-25 03:25:48.377  1586  1586 D KeyguardModel: ACTION_GENERAL_UPDATE_NOTIFICATION received! package: com.lge.bnr.launcher, class: com.lge.bnr.launcher.BNRLauncherActivity, unread_count: 0
08-25 03:25:48.377  1586  1586 D KeyguardModel: putThirdPartyNotificationIntoList Number: 0 Id: 12 UserId: 0
08-25 03:25:48.379  6126  7738 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 797, name: OutgoingSocketThread/Sender)
08-25 03:25:48.379  6126  7736 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-25 03:25:48.379  7325  7325 V [BNRBootReceiver]: Boot Receiver Return
08-25 03:25:48.382  6126  7739 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 798, thread name: OutgoingSocketThread/Receiver)
,08-25 03:25:48.383  6126  7739 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-25 03:25:48.383  6126  7739 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 798, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-25 03:25:48.384  6126  7741 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 799, name: IncomingSocketThread/Sender)
,08-25 03:25:48.390  6126  7742 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 800, name: IncomingSocketThread/Receiver)
08-25 03:25:48.391  6126  7742 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 800, thread name: IncomingSocketThread/Receiver)
08-25 03:25:48.391  6126  7742 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-25 03:25:48.391  6126  7742 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 800, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-25 03:25:48.391  2169  2169 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
08-25 03:25:48.416  2016  2016 I [LGHome]LGNumberBadgeReceiver: [LGNumberBadgeReceiver.java:64:onReceive()]LGNumberBadgeReceiver.onReceive() is called : action = android.intent.action.BADGE_COUNT_UPDATE
,08-25 03:25:48.421  2016  5390 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.ui.ConversationList = 0
08-25 03:25:48.422  2016  5390 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.message.activity.MainMenuActivity = 0
08-25 03:25:48.422  2016  5390 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.android.mms.ui.ConversationList = 0
08-25 03:25:48.424  2016  5390 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.updatecenter.UpdateCenterPrfActivity = 1
08-25 03:25:48.424  2016  5390 I [LGHome]NumberBadge.LGBroadCastBadge: [LGBroadCastBadge.java:53:updateBadgeIcon()][updateClassList : com.lge.bnr.launcher.BNRLauncherActivity = 0
08-25 03:25:49.544  1069  2611 I ActivityManager: Killing 6744:com.android.chrome/u0a57 (adj 15): empty #17
,08-25 03:25:49.578  1069  1977 W libprocessgroup: failed to open /acct/uid_10057/pid_6744/cgroup.procs: No such file or directory
,08-25 03:25:51.176  1069  1376 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=29.9, 0.0, 0.0  rx=29.8 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1085431352] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-25 03:25:51.179  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=29.9, 0.0, 0.0  rx=29.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1085431349] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 03:25:51.179  1069  1376 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-25 03:25:51.377  6126  6205 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-25 03:25:51.377  6126  6205 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-25 03:25:51.379  6126  6205 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@144b0c10 Bundle[{}]
08-25 03:25:51.380  6126  6205 I io.jxcore.node.LifeCycleMonitor: start: OK
08-25 03:25:51.380  6126  6205 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-25 03:25:51.381  6126  6205 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-25 03:25:51.382  6126  6205 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,08-25 03:25:51.386  6126  6205 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-25 03:25:51.388  6126  6205 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
08-25 03:25:51.394  6126  6205 I System.out: Running OutgoingSocketThread
08-25 03:25:51.398  6126  7753 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-25 03:25:51.398  6126  7753 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-25 03:25:52.359  1586  1586 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-25 03:25:52.404  1069  1364 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-25 03:25:52.462  1069  1069 D administrator: Handling package changes for user 0
,08-25 03:25:52.490  1069  1171 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7754 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-25 03:25:52.503  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
08-25 03:25:52.521  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-25 03:25:52.522  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
,08-25 03:25:52.563  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-25 03:25:52.590  7754  7754 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-25 03:25:52.616  1069  1069 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-25 03:25:52.616  1069  1069 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-25 03:25:52.664  1069  1167 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 03:25:52.669  1069  1167 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-25 03:25:52.677  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-25 03:25:52.677  2485  2485 V GmsNetworkLocationProvi: DISABLE
,08-25 03:25:52.686  7754  7754 D LgDataFeature: LgDataFeature() Constructor: none
08-25 03:25:52.687  7754  7754 D LgDataFeature: LgDataFeature() Constructor Done, null
08-25 03:25:52.757  1069  1167 I art     : Explicit concurrent mark sweep GC freed 21743(1099KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/65MB, paused 1.430ms total 75.704ms
,08-25 03:25:52.782  2485  2485 E GCoreFlp: Bound FusedProviderService with LocationManager
08-25 03:25:52.784  1069  1167 D LocationProviderProxy: applying state to connected service
,08-25 03:25:52.872  7754  7800 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-25 03:25:52.872  7754  7800 I Babel   : MmsConfig.loadMmsSettings
,08-25 03:25:52.881  7754  7800 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-25 03:25:52.881  7754  7800 I Babel   : MmsConfig.loadFromDatabase
,08-25 03:25:52.903  7754  7754 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-25 03:25:52.904  7754  7800 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-25 03:25:52.904  7754  7800 I Babel   : MmsConfig.loadFromResources
08-25 03:25:52.913  7754  7800 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-25 03:25:52.914  7754  7800 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
,08-25 03:25:52.933  7754  7798 W AudioCapabilities: Unsupported mime audio/evrc
,08-25 03:25:52.934  7754  7798 W AudioCapabilities: Unsupported mime audio/qcelp
08-25 03:25:52.936  7754  7798 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-25 03:25:52.947  7754  7798 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-25 03:25:52.948  7754  7798 W AudioCapabilities: Unsupported mime audio/qcelp
08-25 03:25:52.950  7754  7798 W AudioCapabilities: Unsupported mime audio/evrc
08-25 03:25:52.958  1801  7801 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-25 03:25:52.958  1801  7801 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-25 03:25:52.969  7754  7798 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-25 03:25:52.971  7754  7798 W VideoCapabilities: Unsupported mime video/divx
,08-25 03:25:52.973  7754  7798 W VideoCapabilities: Unsupported mime video/divx311
08-25 03:25:52.975  7754  7798 W VideoCapabilities: Unsupported mime video/divx4
08-25 03:25:52.980  7754  7798 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-25 03:25:53.016  1069  2025 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.manager.PreloadListManagerHelper: pid=7804 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-25 03:25:53.026  1069  1097 I ActivityManager: Killing 6778:com.lge.drmservice/u0a62 (adj 15): empty #17
08-25 03:25:53.031  1801  4573 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-25 03:25:53.049  7754  7798 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
,08-25 03:25:53.055  7754  7798 W AudioCapabilities: Unsupported mime audio/eac3
08-25 03:25:53.056  7754  7798 W AudioCapabilities: Unsupported mime audio/ac3
08-25 03:25:53.057  7754  7798 W AudioCapabilities: Unsupported mime audio/g726
08-25 03:25:53.058  7754  7798 W AudioCapabilities: Unsupported mime audio/wma-voice
08-25 03:25:53.059  7754  7798 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-25 03:25:53.060  7754  7798 W AudioCapabilities: Unsupported mime audio/adpcm
,08-25 03:25:53.062  7754  7798 W VideoCapabilities: Unsupported mime video/theora
08-25 03:25:53.072  7754  7798 W VideoCapabilities: Unsupported mime video/mjpg
,08-25 03:25:53.083  1069  2611 W libprocessgroup: failed to open /acct/uid_10062/pid_6778/cgroup.procs: No such file or directory
,08-25 03:25:53.103  6869  7732 I GAV2    : Thread[GAThread,5,main]: No campaign data found.
,08-25 03:25:53.121  7804  7804 I AppUp4:AppBoxCP: onCreate
,08-25 03:25:53.121  7804  7804 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
08-25 03:25:53.128  7804  7804 I AppUp4:DB:  setFingerPrint start
08-25 03:25:53.128  7804  7804 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
08-25 03:25:53.133  7804  7804 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-25 03:25:53.133  7804  7804 I AppUp4:DB:  SDK version = 21
08-25 03:25:53.133  7804  7804 I AppUp4:DB:  beforefinger == newfinger no write in DB
,08-25 03:25:53.134  7804  7804 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-25 03:25:53.140  7804  7804 I AppUp4:CustModeStarterReceiver: onReceive
08-25 03:25:53.164  7804  7804 D LgDataFeature: LgDataFeature() Constructor: none
08-25 03:25:53.164  7804  7804 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 03:25:53.171  7804  7804 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@2730e3
08-25 03:25:53.171  7804  7804 D AppUp4:CustFacade: isCustomizationCompleted : false
08-25 03:25:53.171  7804  7804 D AppUp4:CustFacade: isPhone : true
08-25 03:25:53.171  7804  7804 D AppUp4:CustModeStarterReceiver: begin check event
08-25 03:25:53.171  7804  7804 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-25 03:25:53.212  1069  1896 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7827 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-25 03:25:53.213  1069  1896 I ActivityManager: Killing 6814:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
,08-25 03:25:53.251   344   344 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 447us total 36.864ms
,08-25 03:25:53.271   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 410us total 19.478ms
,08-25 03:25:53.290   344   344 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 366us total 18.069ms
,08-25 03:25:53.421  1069  1896 E libprocessgroup: failed to kill 1 processes for processgroup 6814
,08-25 03:25:53.529  7827  7827 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 03:25:53.530  7827  7827 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-25 03:25:53.530  7827  7827 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-25 03:25:53.531  7827  7827 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-25 03:25:53.532  7827  7827 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-25 03:25:53.613  7827  7827 I SystemConfig: BUILD Country: EU
08-25 03:25:53.613  7827  7827 I SystemConfig: BUILD Operator: OPEN
,08-25 03:25:53.672  1069  1096 I ActivityManager: Killing 7526:com.lge.email/u0a23 (adj 15): empty #17
,08-25 03:25:53.767  1069  2611 W libprocessgroup: failed to open /acct/uid_10023/pid_7526/cgroup.procs: No such file or directory
,08-25 03:25:53.786  7827  7847 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-25 03:25:53.786  7827  7847 I SystemConfig: existFile = false
08-25 03:25:53.786  7827  7847 I SystemConfig: canReadFile = false
08-25 03:25:53.787  7827  7847 I SystemConfig: systemFeature RCS result false
08-25 03:25:53.787  7827  7847 D SystemConfig: refreshRcsSupport() :false
,08-25 03:25:53.835  1069  1096 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7849 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-25 03:25:53.900  7849  7849 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 03:25:53.900  7849  7849 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-25 03:25:53.900  7849  7849 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-25 03:25:53.901  7849  7849 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-25 03:25:54.028  7849  7849 I AppConfig: Total System Memory = 2995761152
,08-25 03:25:54.040  7849  7849 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
08-25 03:25:54.127  1069  1559 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7871 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-25 03:25:54.129  1069  1559 I ActivityManager: Killing 4879:com.wsandroid.suite.lge/1000 (adj 15): empty #17
08-25 03:25:54.189  1069  2025 W libprocessgroup: failed to open /acct/uid_1000/pid_4879/cgroup.procs: No such file or directory
,08-25 03:25:54.203  1069  1376 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=16.4, 0.0, 0.0  rx=15.4 bcn=0 [on:0 tx:0 rx:0 period:3000] from screen [on:0 period:-1085428325] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 03:25:54.204  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=16.4, 0.0, 0.0  rx=15.4 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1085428324] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 03:25:54.204  1069  1376 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-25 03:25:54.414  6126  7753 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-25 03:25:54.415  6126  7753 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-25 03:25:54.415  6126  7753 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-25 03:25:54.416  6126  7753 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-25 03:25:54.417  6126  7753 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-25 03:25:54.418  6126  7902 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
,08-25 03:25:54.418  6126  7902 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-25 03:25:54.419  7871  7871 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-25 03:25:54.420  6126  7902 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-25 03:25:54.421  6126  7905 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 809, name: OutgoingSocketThread/Sender)
08-25 03:25:54.424  6126  7906 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 810, name: OutgoingSocketThread/Receiver)
08-25 03:25:54.425  6126  7902 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-25 03:25:54.432  6126  7906 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 810, thread name: OutgoingSocketThread/Receiver)
08-25 03:25:54.432  6126  7902 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-25 03:25:54.432  6126  7906 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-25 03:25:54.432  6126  7906 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 810, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-25 03:25:54.437  6126  7908 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 811, name: IncomingSocketThread/Sender)
,08-25 03:25:54.441  6126  7909 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 812, name: IncomingSocketThread/Receiver)
08-25 03:25:54.442  6126  7909 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 812, thread name: IncomingSocketThread/Receiver)
08-25 03:25:54.442  6126  7909 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-25 03:25:54.442  6126  7909 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 812, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-25 03:25:54.533  7871  7871 D LgDataFeature: LgDataFeature() Constructor: none
08-25 03:25:54.533  7871  7871 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-25 03:25:54.601  7871  7871 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-25 03:25:54.625  7871  7871 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-25 03:25:54.626  7871  7871 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-25 03:25:54.644  7871  7871 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
08-25 03:25:54.644  7871  7871 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-25 03:25:54.677  2832  2848 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-25 03:25:54.683  1069  1672 I ActivityManager: Killing 7602:com.qualcomm.timeservice/1000 (adj 15): empty #17
08-25 03:25:54.683  2832  2848 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@20ba9617 on behalf of 7871
08-25 03:25:54.715  1069  1888 W libprocessgroup: failed to open /acct/uid_1000/pid_7602/cgroup.procs: No such file or directory
,08-25 03:25:54.731  4481  7929 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,08-25 03:25:54.742  7871  7871 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-25 03:25:54.795  1069  2014 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=7934 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-25 03:25:54.850  7871  7871 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-25 03:25:54.881  7934  7934 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-25 03:25:54.908  7934  7934 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-25 03:25:54.908  7934  7934 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-25 03:25:54.909  7934  7934 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
,08-25 03:25:54.909  7934  7934 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-25 03:25:54.909  7934  7934 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-25 03:25:54.909  7934  7934 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-25 03:25:54.930  1069  1977 I ActivityManager: Killing 6041:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
,08-25 03:25:54.949  6343  6343 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-25 03:25:54.949  6343  6343 W System.err: android.os.DeadObjectException
,08-25 03:25:54.949  6343  6343 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-25 03:25:54.950  6343  6343 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-25 03:25:54.950  6343  6343 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-25 03:25:54.950  6343  6343 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-25 03:25:54.951  6343  6343 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-25 03:25:54.951  6343  6343 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-25 03:25:54.951  6343  6343 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 03:25:54.951  6343  6343 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 03:25:54.951  6343  6343 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 03:25:54.951  6343  6343 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 03:25:54.951  6343  6343 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:25:54.951  6343  6343 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 03:25:54.951  6343  6343 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 03:25:54.951  6343  6343 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 03:25:54.951  6343  6343 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-25 03:25:54.952  6343  6343 W System.err: android.os.DeadObjectException
08-25 03:25:54.952  6343  6343 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-25 03:25:54.952  6343  6343 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-25 03:25:54.952  6343  6343 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-25 03:25:54.952  6343  6343 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-25 03:25:54.952  6343  6343 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-25 03:25:54.952  6343  6343 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-25 03:25:54.952  6343  6343 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 03:25:54.952  6343  6343 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 03:25:54.952  6343  6343 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 03:25:54.953  6343  6343 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 03:25:54.953  6343  6343 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:25:54.953  6343  6343 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 03:25:54.953  6343  6343 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 03:25:54.953  6343  6343 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-25 03:25:54.953  6343  6343 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-25 03:25:54.953  6343  6343 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-25 03:25:55.067  1069  1996 W libprocessgroup: failed to open /acct/uid_1000/pid_6041/cgroup.procs: No such file or directory
08-25 03:25:55.068  1069  1996 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-25 03:25:55.076  6343  6343 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-25 03:25:55.077  6343  6343 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
,08-25 03:25:55.176  1069  1926 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7967 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-25 03:25:55.179  6343  6343 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-25 03:25:55.277  7967  7967 D UEI.SmartControl: Quickset Services start...
,08-25 03:25:55.279  7967  7967 I UEI.SmartControl: Manufacture = LGE
08-25 03:25:55.279  7967  7967 D UEI.SmartControl: Id = LGNevo
08-25 03:25:55.281  7967  7967 D UEI.SmartControl: File observer start...
08-25 03:25:55.281  7967  7967 E UEI.SmartControl: IR Port is disabled: false
08-25 03:25:55.282  7967  7967 D UEI.SmartControl: Starting file observer...
08-25 03:25:55.282  7967  7967 D UEI.SmartControl: Extracting JNI libs...
08-25 03:25:55.282  7967  7967 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-25 03:25:55.391  1069  1918 V SIM_STK : Menu title from STK is T-Mobile
,08-25 03:25:55.397  7967  7967 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-25 03:25:55.397  7967  7967 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-25 03:25:55.397  7967  7967 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-25 03:25:55.414  4481  7929 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 683 ms] updated apps [took 682 ms] 
,08-25 03:25:55.438  7967  7967 I UEI.SmartControl: --- Selecting new region: 6
,08-25 03:25:55.441  7967  7967 I UEI.SmartControl: Model = LG-D855
,08-25 03:25:55.443  7967  7967 D UEI.SmartControl: QS Service created
08-25 03:25:55.461  7967  7967 I UEI.SmartControl: Service initServices...
,08-25 03:25:55.466  7967  7967 D UEI.SmartControl: QS start get config
,08-25 03:25:55.547  7967  7967 D UEI.SmartControl: Loading JNI Libs...
,08-25 03:25:55.966  7967  7967 I UEI.SmartControl: Supports setup maps: true
,08-25 03:25:55.972  7967  7967 D UEI.SmartControl: QS start statue = true Error code = 0
,08-25 03:25:55.976  7967  7967 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-25 03:25:55.976  7967  7967 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-25 03:25:55.976  7967  7967 I UEI.SmartControl: ### init IR Blaster...
08-25 03:25:55.983  7967  7967 D serial_port: Configuring serial port
08-25 03:25:55.988  7967  7967 E UEI.SmartControl: UEIBLaster setting for 616
08-25 03:25:55.988  7967  7967 I UEI.SmartControl: Setting serial record hearder size = 2
08-25 03:25:55.988  7967  7967 I UEI.SmartControl: configuring settings for MAXQ616
08-25 03:25:55.989  7967  7967 I UEI.SmartControl: Get version...
08-25 03:25:56.006  7967  7994 D UEI.SmartControl: serial port data available: 21
,08-25 03:25:56.038  7967  7967 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-25 03:25:56.039  7967  7967 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-25 03:25:56.039  7967  7967 I UEI.SmartControl: QS saving settings...
08-25 03:25:56.041  7967  7967 D UEI.SmartControl: IR Blaster version: 25672567
,08-25 03:25:56.073  7967  7994 D UEI.SmartControl: serial port data available: 4
,08-25 03:25:56.117  7967  7967 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-25 03:25:56.126  7967  7997 I UEI.SmartControl: Device manager: loading config....
08-25 03:25:56.126  7967  7997 D UEI.SmartControl: ----------- loading internal config...
08-25 03:25:56.132  7967  7967 E UEI.SmartControl: Services init done
08-25 03:25:56.133  7967  7967 D UEI.SmartControl: QS Service init finished
08-25 03:25:56.135  7967  7967 D UEI.SmartControl: QS Service version name: 2.1.91
08-25 03:25:56.136  7967  7967 D UEI.SmartControl: QS Service version code: 201091
,08-25 03:25:56.139  7967  7967 D UEI.SmartControl: Service requested: Control
08-25 03:25:56.140  7967  7997 E UEI.SmartControl: Loading SETTINGS...
08-25 03:25:56.144  7967  7967 D UEI.SmartControl: Request IControl service: devices are loaded...
08-25 03:25:56.149  1069  2014 I ActivityManager: Killing 7623:com.android.calendar/u0a13 (adj 15): empty #17
,08-25 03:25:56.159  6343  6343 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-25 03:25:56.161  7967  7986 I UEI.SmartControl: ------ IControl API: 11
08-25 03:25:56.162  7967  7986 I UEI.SmartControl: Registering callback...
,08-25 03:25:56.166  7967  7985 I UEI.SmartControl: ------ IControl API: 19
08-25 03:25:56.167  7967  7985 I UEI.SmartControl: Registering Services Ready callback...
08-25 03:25:56.168  7967  7997 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-25 03:25:56.193  7967  7996 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-25 03:25:56.196  6343  6361 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-25 03:25:56.196  6343  6438 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-25 03:25:56.197  6343  6438 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-25 03:25:56.197  6343  6343 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-25 03:25:56.197  6343  6343 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-25 03:25:56.198  7967  7986 I UEI.SmartControl: ------ IControl API: 8
08-25 03:25:56.198  7967  7996 D UEI.SmartControl: -----service ready thread exits
08-25 03:25:56.199  6343  6343 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-25 03:25:56.199  6343  6343 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-25 03:25:56.199  6343  6343 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-25 03:25:56.200  6343  6343 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-25 03:25:56.201  6343  6343 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-25 03:25:56.201  6343  6343 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-25 03:25:56.206  1069  1701 W libprocessgroup: failed to open /acct/uid_10013/pid_7623/cgroup.procs: No such file or directory
,08-25 03:25:56.221  7967  7967 D UEI.SmartControl: Internal service binding...
,08-25 03:25:56.225  6343  6343 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-25 03:25:56.226  6343  6343 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-25 03:25:56.227  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-25 03:25:56.228  6343  6343 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 03:25:56.228  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-25 03:25:56.229  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-25 03:25:56.230  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-25 03:25:56.230  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-25 03:25:56.230  6343  6343 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1472088356230]
08-25 03:25:56.242  6343  7999 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-25 03:25:56.250  6343  6343 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
,08-25 03:25:56.251  6343  6343 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-25 03:25:56.251  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,08-25 03:25:56.251  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-25 03:25:56.252  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-25 03:25:56.252  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-25 03:25:56.252  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-25 03:25:56.254  6343  6343 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
08-25 03:25:57.225  1069  1376 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=8.7, 0.0, 0.0  rx=7.7 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1085425303] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 03:25:57.228  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=8.7, 0.0, 0.0  rx=7.7 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1085425300] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 03:25:57.229  1069  1376 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-25 03:25:57.414  6126  6205 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 821)
08-25 03:25:57.415  6126  6205 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-25 03:25:57.415  6126  6205 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 822)
08-25 03:25:57.418  6126  6205 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 03:25:57.418  6126  6205 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fc3083b added. We now have 3 listener(s)
,08-25 03:25:57.422  1069  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:25:57.425  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 03:25:57.425  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 03:25:57.425  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 03:25:57.426  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:25:57.426  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2eab58 added. We now have 4 listener(s)
08-25 03:25:57.426  6126  6205 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 03:25:57.426  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 03:25:57.430  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:25:57.434  6126  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:25:57.434  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:57.434  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:57.434  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:25:57.434  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:25:57.434  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:25:57.434  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:25:57.434  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:25:57.440  6126  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 03:25:57.440  6126  6205 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:25:57.442  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:57.444  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:57.444  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:25:57.445  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:25:57.445  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:25:57.445  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:25:57.445  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:25:57.445  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:25:57.445  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 03:25:57.445  6126  6205 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fc3083b removed from the list
08-25 03:25:57.445  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:25:57.445  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2eab58 removed from the list
,08-25 03:25:57.445  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:25:57.445  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:25:57.446  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:25:57.446  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:25:57.449  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:25:57.449  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:25:57.449  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:25:57.449  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2eab58 not in the list
08-25 03:25:57.449  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:25:57.449  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:25:57.454  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:25:57.454  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:25:57.454  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:25:57.454  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b2eab58 not in the list
08-25 03:25:57.455  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:25:57.455  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:25:57.455  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:25:57.455  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1fc3083b not in the list
08-25 03:25:57.456  6126  6205 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 03:25:57.456  6126  6205 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac34d96 added. We now have 3 listener(s)
08-25 03:25:57.457  1069  2611 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:25:57.459  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 03:25:57.459  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 03:25:57.459  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 03:25:57.459  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:25:57.459  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ecfed17 added. We now have 4 listener(s)
08-25 03:25:57.459  6126  6205 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 03:25:57.461  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 03:25:57.465  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:25:57.471  6126  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:25:57.471  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:25:57.471  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:25:57.471  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:25:57.471  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:25:57.471  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:25:57.471  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:25:57.471  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 03:25:57.473  6126  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 03:25:57.473  6126  6205 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:25:57.476  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:25:57.477  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:25:57.479  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 03:25:57.479  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 03:25:57.479  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 03:25:57.479  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:25:57.479  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 03:25:57.484  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 03:25:57.484  1069  1896 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:25:57.489  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 03:25:57.491  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 03:25:57.493  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 03:25:57.494  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:25:57.495  6126  6205 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 03:25:57.497  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:25:57.497  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 03:26:00.115  1586  1586 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
,08-25 03:26:00.115  1586  1586 I KeyguardUpdateMonitor: called onTimeUpdated()
08-25 03:26:00.115  1586  1586 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-25 03:26:00.116  1586  1586 I [SystemUI]Clock: called onTimeUpdated()
,08-25 03:26:00.130  1586  1586 I LgeClockWidgetControlView: called onTimeUpdated()
08-25 03:26:00.131  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
08-25 03:26:00.136  1586  1586 I [SystemUI]DateView: called onTimeUpdated()
,08-25 03:26:00.138  1586  1586 D KeyguardUpdateMonitor: handleTimeUpdate
08-25 03:26:00.251  1069  1376 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1085422277] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-25 03:26:00.258  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=4.4, 0.0, 0.0  rx=3.8 bcn=0 [on:0 tx:0 rx:0 period:7] from screen [on:0 period:-1085422270] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-25 03:26:00.258  1069  1376 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-25 03:26:00.498  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:26:00.498  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:26:00.498  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 03:26:00.509  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:26:00.509  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:26:00.510  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:26:00.510  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 03:26:00.510  6126  6205 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac34d96 removed from the list
08-25 03:26:00.510  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:26:00.510  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ecfed17 removed from the list
08-25 03:26:00.510  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:26:00.511  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:26:00.513  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:26:00.513  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:26:00.524  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:26:00.524  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-25 03:26:00.528  6126  6205 D BluetoothLeScanner: could not find callback wrapper
08-25 03:26:00.528  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:26:00.528  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:26:00.528  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ecfed17 not in the list
08-25 03:26:00.528  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:26:00.528  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:26:00.529  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:26:00.530  6126  6205 D BluetoothLeScanner: could not find callback wrapper
08-25 03:26:00.530  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:26:00.530  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:26:00.530  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:26:00.530  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ecfed17 not in the list
08-25 03:26:00.530  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:26:00.530  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:26:00.530  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:26:00.530  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1ac34d96 not in the list
08-25 03:26:00.531  6126  6205 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 03:26:00.531  6126  6205 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195c43b3 added. We now have 3 listener(s)
08-25 03:26:00.532  1069  2611 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:26:00.536  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 03:26:00.536  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 03:26:00.536  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 03:26:00.536  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:26:00.536  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@385b8d70 added. We now have 4 listener(s)
08-25 03:26:00.536  6126  6205 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 03:26:00.537  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 03:26:00.545  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:26:00.550  6126  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:26:00.550  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:26:00.550  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:26:00.550  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:26:00.550  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:26:00.550  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:26:00.550  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:26:00.550  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:26:00.554  6126  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 03:26:00.554  6126  6205 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:26:00.556  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:26:00.558  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:26:00.559  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-25 03:26:00.560  6126  6205 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-25 03:26:00.560  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-25 03:26:00.563  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-25 03:26:00.563  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,08-25 03:26:00.566  6126  6205 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-25 03:26:00.566  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:26:00.567  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-25 03:26:00.567  6126  6205 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-25 03:26:00.568  6126  6205 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-25 03:26:00.568  6126  6126 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-25 03:26:00.570  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-25 03:26:00.570  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-25 03:26:00.570  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:26:00.570  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 03:26:00.575  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 03:26:00.576  1069  2025 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:26:00.579  1069  1672 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 03:26:00.584  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-25 03:26:00.585  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 03:26:00.586  6126  8000 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-25 03:26:00.588  7127  7253 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-25 03:26:00.590  6126  8000 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-25 03:26:00.590  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 03:26:00.590  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-25 03:26:00.592  6126  6205 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
,08-25 03:26:01.116  7967  7998 D UEI.SmartControl: Internal timer expired: 1
,08-25 03:26:01.116  7967  7998 D UEI.SmartControl: unbind internal service
,08-25 03:26:01.358  7967  7995 D serial_port: close(fd = 25)
,08-25 03:26:01.369  7967  7995 I UEI.SmartControl: Serial port is closed.
,08-25 03:26:03.277  1069  1376 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1085419251] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-25 03:26:03.280  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=2.2, 0.0, 0.0  rx=1.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1085419248] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-25 03:26:03.280  1069  1376 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-25 03:26:03.597  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-25 03:26:03.597  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:26:03.598  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-25 03:26:03.598  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-25 03:26:03.598  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-25 03:26:03.598  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
,08-25 03:26:03.610  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 03:26:03.610  6126  6205 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-25 03:26:03.611  6126  8000 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,08-25 03:26:03.611  6126  8000 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-25 03:26:03.611  6126  8000 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-25 03:26:03.612  6126  6126 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-25 03:26:03.616  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-25 03:26:03.617  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:26:03.617  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-25 03:26:03.626  6126  6126 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:26:03.627  6126  6126 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-25 03:26:03.627  6126  6126 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-25 03:26:03.628  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:26:03.628  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:26:03.628  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:26:03.628  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 03:26:03.628  6126  6205 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195c43b3 removed from the list
08-25 03:26:03.628  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:26:03.628  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@385b8d70 removed from the list
08-25 03:26:03.629  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:26:03.629  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:26:03.629  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:26:03.630  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:26:03.631  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:26:03.631  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:26:03.631  6126  6205 D BluetoothLeScanner: could not find callback wrapper
08-25 03:26:03.631  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:26:03.631  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:26:03.631  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@385b8d70 not in the list
08-25 03:26:03.632  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:26:03.632  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:26:03.633  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:26:03.633  6126  6205 D BluetoothLeScanner: could not find callback wrapper
08-25 03:26:03.633  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:26:03.633  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:26:03.633  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:26:03.634  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@385b8d70 not in the list
08-25 03:26:03.634  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:26:03.634  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already r,emoved
08-25 03:26:03.634  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:26:03.634  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@195c43b3 not in the list
08-25 03:26:03.635  6126  6205 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 03:26:03.635  6126  6205 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3044109c added. We now have 3 listener(s)
08-25 03:26:03.635  1069  1559 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-25 03:26:03.643  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 03:26:03.643  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 03:26:03.643  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 03:26:03.643  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:26:03.643  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eb2caa5 added. We now have 4 listener(s)
08-25 03:26:03.643  6126  6205 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 03:26:03.646  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-25 03:26:03.650  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-25 03:26:03.657  6126  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:26:03.657  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:26:03.657  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:26:03.657  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:26:03.657  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:26:03.657  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:26:03.657  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:26:03.657  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-25 03:26:03.660  6126  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 03:26:03.660  6126  6205 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:26:03.662  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:26:03.664  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-25 03:26:03.666  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 03:26:03.666  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-25 03:26:03.666  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-25 03:26:03.666  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:26:03.666  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-25 03:26:03.670  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-25 03:26:03.672  1069  1960 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:26:03.676  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-25 03:26:03.678  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-25 03:26:03.680  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-25 03:26:03.681  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:26:03.683  6126  6205 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-25 03:26:05.656  1069  1559 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
,08-25 03:26:05.659  1069  7369 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler },
08-25 03:26:05.659  1069  7369 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:26:05.659  1069  7369 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-25 03:26:05.659  1069  7369 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-25 03:26:05.660  1069  7369 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-25 03:26:05.669  1069  7369 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 25 Aug 2016 01:26:05 GMT], X-Android-Received-Millis=[1472088365669], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1472088365663]}
08-25 03:26:05.669  1069  7369 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-25 03:26:05.669  1069  7369 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-25 03:26:05.674  1069  1445 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-25 03:26:05.674  1069  1445 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-25 03:26:05.674  1069  1445 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-25 03:26:05.675  1069  1445 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 03:26:05.675  1069  1445 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-25 03:26:05.675  1069  1445 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-25 03:26:05.675  1069  1445 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-25 03:26:05.675  1069  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-25 03:26:05.675  1069  1445 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 03:26:05.676  1069  1445 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-25 03:26:05.676  1586  2076 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-25 03:26:06.308  1069  1376 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1085416222] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-25 03:26:06.317  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=1.1, 0.0, 0.0  rx=1.0 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1085416211] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-25 03:26:06.317  1069  1376 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-25 03:26:06.690  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:26:06.690  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:26:06.690  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-25 03:26:06.700  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:26:06.701  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:26:06.701  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:26:06.701  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 03:26:06.701  6126  6205 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3044109c removed from the list
08-25 03:26:06.701  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:26:06.701  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eb2caa5 removed from the list
08-25 03:26:06.702  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:26:06.702  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:26:06.704  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:26:06.704  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:26:06.705  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:26:06.705  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:26:06.706  6126  6205 D BluetoothLeScanner: could not find callback wrapper
08-25 03:26:06.706  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:26:06.706  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:26:06.706  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eb2caa5 not in the list
08-25 03:26:06.706  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:26:06.706  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:26:06.707  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:26:06.708  6126  6205 D BluetoothLeScanner: could not find callback wrapper
08-25 03:26:06.708  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-25 03:26:06.708  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:26:06.708  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:26:06.708  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3eb2caa5 not in the list
08-25 03:26:06.708  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:26:06.708  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:26:06.708  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:26:06.708  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3044109c not in the list
,08-25 03:26:06.714  6126  6205 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-25 03:26:06.714  6126  6205 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18aa6c21 added. We now have 3 listener(s)
08-25 03:26:06.718  1069  1096 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-25 03:26:06.720  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-25 03:26:06.720  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-25 03:26:06.720  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-25 03:26:06.721  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-25 03:26:06.721  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30084846 added. We now have 4 listener(s)
08-25 03:26:06.721  6126  6205 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-25 03:26:06.723  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-25 03:26:06.729  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-25 03:26:06.734  6126  6205 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-25 03:26:06.734  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-25 03:26:06.734  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-25 03:26:06.734  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-25 03:26:06.734  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-25 03:26:06.734  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-25 03:26:06.734  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-25 03:26:06.734  6126  6205 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-25 03:26:06.738  6126  6205 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-25 03:26:06.739  6126  6205 D io.jxcore.node.ConnectivityMonitor: start: OK
08-25 03:26:06.741  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:26:06.743  6126  6126 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-25 03:26:06.745  6126  6205 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-25 03:26:06.745  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-25 03:26:06.745  6126  6205 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-25 03:26:06.745  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:26:06.745  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:26:06.745  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-25 03:26:06.745  6126  6205 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-25 03:26:06.745  6126  6205 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18aa6c21 removed from the list
08-25 03:26:06.745  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:26:06.746  6126  6205 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30084846 removed from the list
08-25 03:26:06.746  6126  6205 D io.jxcore.node.ConnectivityMonitor: stop
08-25 03:26:06.746  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:26:06.746  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:26:06.746  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-25 03:26:06.750  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:26:06.750  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:26:06.750  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:26:06.750  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30084846 not in the list
08-25 03:26:06.750  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:26:06.750  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:26:06.751  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-25 03:26:06.751  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-25 03:26:06.751  6126  6205 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-25 03:26:06.751  6126  6205 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@30084846 not in the list
08-25 03:26:06.751  6126  6205 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-25 03:26:06.751  6126  6205 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-25 03:26:06.751  6126  6205 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-25 03:26:06.751  6126  6205 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@18aa6c21 not in the list
08-25 03:26:06.753  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-25 03:26:06.753  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-25 03:26:06.753  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-25 03:26:06.753  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-25 03:26:06.753  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-25 03:26:06.754  6126  6205 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-25 03:26:08.774  6126  8001 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 831, name: My test thread name)
,08-25 03:26:08.917  1069  1362 D PowerManagerServiceEx: acquireWakeLockInternal: lock=506181987, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1069
,08-25 03:26:08.929  1069  1362 V AlarmManager: ELAPSED_WAKEUP set : Alarm{832ffbe type 2 when 410840 com.google.android.gms} when 410840
08-25 03:26:08.943   306  8003 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-25 03:26:08.946   306  8003 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-25 03:26:08.946   306  8003 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-25 03:26:08.965  2563  2563 D [Concierge]Service: onStartCommand(). Type : 9
,08-25 03:26:08.991  1069  1069 D PowerManagerServiceEx: releaseWakeLockInternal: lock=506181987 [*alarm*], flags=0x0
,08-25 03:26:09.256  2169  8004 D GCM     : Connected
,08-25 03:26:09.286  2169  8004 D GCM     : Message class com.google.e.a.a.q
,08-25 03:26:09.337  1069  1376 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3007] from screen [on:0 period:-1085413191] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-25 03:26:09.340  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=3.0, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1085413188] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-25 03:26:09.340  1069  1376 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-25 03:26:10.771  6126  6205 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 831
,08-25 03:26:10.772  6126  6205 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 831, name: My test thread name)
,08-25 03:26:10.788  6126  8005 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 832, name: My test thread name)
08-25 03:26:10.788  6126  8005 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 832, thread name: My test thread name)
08-25 03:26:10.788  6126  8005 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 832, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-25 03:26:10.795  6126  6205 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-25 03:26:10.800  6126  8006 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 836, name: My test thread name)
08-25 03:26:10.801  6126  8006 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 836, thread name: My test thread name): Test exception.
08-25 03:26:10.801  6126  8006 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 836, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
08-25 03:26:10.804  6126  6205 I jxcore-log: Total number of executed tests:  82
08-25 03:26:10.804  6126  6205 I jxcore-log: 
08-25 03:26:10.805  6126  6205 I jxcore-log: Number of passed tests:  82
08-25 03:26:10.805  6126  6205 I jxcore-log: 
08-25 03:26:10.805  6126  6205 I jxcore-log: Number of failed tests:  0
08-25 03:26:10.805  6126  6205 I jxcore-log: 
08-25 03:26:10.805  6126  6205 I jxcore-log: Number of ignored tests:  0
08-25 03:26:10.805  6126  6205 I jxcore-log: 
08-25 03:26:10.806  6126  6205 I jxcore-log: Total duration:  101483
08-25 03:26:10.806  6126  6205 I jxcore-log: 
08-25 03:26:10.808  6126  6205 I jxcore-log: Unit Test app is loaded
08-25 03:26:10.808  6126  6205 I jxcore-log: 
08-25 03:26:10.831  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 03:26:10.831  6126  6205 I jxcore-log: 
,08-25 03:26:10.847  6126  6126 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-25 03:26:10.850  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 03:26:10.850  6126  6205 I jxcore-log: 
08-25 03:26:10.852  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 03:26:10.852  6126  6205 I jxcore-log: 
08-25 03:26:10.853  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 03:26:10.853  6126  6205 I jxcore-log: 
08-25 03:26:10.854  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 03:26:10.854  6126  6205 I jxcore-log: 
08-25 03:26:10.855  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 03:26:10.855  6126  6205 I jxcore-log: 
08-25 03:26:10.859  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-25 03:26:10.859  6126  6205 I jxcore-log: 
08-25 03:26:10.861  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 03:26:10.861  6126  6205 I jxcore-log: 
08-25 03:26:10.862  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 03:26:10.862  6126  6205 I jxcore-log: 
08-25 03:26:10.863  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 03:26:10.863  6126  6205 I jxcore-log: 
08-25 03:26:10.864  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 03:26:10.864  6126  6205 I jxcore-log: 
08-25 03:26:10.865  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 03:26:10.865  6126  6205 I jxcore-log: 
08-25 03:26:10.866  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 03:26:10.866  6126  6205 I jxcore-log: 
08-25 03:26:10.867  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 03:26:10.867  6126  6205 I jxcore-log: 
08-25 03:26:10.868  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 03:26:10.868  6126  6205 I jxcore-log: 
08-25 03:26:10.869  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-25 03:26:10.869  6126  6205 I jxcore-log: 
08-25 03:26:10.870  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 03:26:10.870  6126  6205 I jxcore-log: 
08-25 03:26:10.871  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 03:26:10.871  6126  6205 I jxcore-log: 
08-25 03:26:10.871  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 03:26:10.871  6126  6205 I jxcore-log: 
,08-25 03:26:10.877  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 03:26:10.877  6126  6205 I jxcore-log: 
08-25 03:26:10.878  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 03:26:10.878  6126  6205 I jxcore-log: 
08-25 03:26:10.879  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 03:26:10.879  6126  6205 I jxcore-log: 
08-25 03:26:10.880  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 03:26:10.880  6126  6205 I jxcore-log: 
08-25 03:26:10.880  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 03:26:10.880  6126  6205 I jxcore-log: 
08-25 03:26:10.881  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-25 03:26:10.881  6126  6205 I jxcore-log: 
08-25 03:26:10.882  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 03:26:10.882  6126  6205 I jxcore-log: 
08-25 03:26:10.883  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 03:26:10.883  6126  6205 I jxcore-log: 
08-25 03:26:10.884  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-25 03:26:10.884  6126  6205 I jxcore-log: 
08-25 03:26:10.885  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 03:26:10.885  6126  6205 I jxcore-log: 
08-25 03:26:10.885  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-25 03:26:10.885  6126  6205 I jxcore-log: 
08-25 03:26:10.887  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:26:10.887  6126  6205 I jxcore-log: 
08-25 03:26:10.888  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:26:10.888  6126  6205 I jxcore-log: 
08-25 03:26:10.888  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:26:10.888  6126  6205 I jxcore-log: 
08-25 03:26:10.889  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:26:10.889  6126  6205 I jxcore-log: 
08-25 03:26:10.890  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:26:10.890  6126  6205 I jxcore-log: 
08-25 03:26:10.891  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:26:10.891  6126  6205 I jxcore-log: 
08-25 03:26:10.892  6126  6205 I jxcore-log: DEBUG, thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:26:10.892  6126  6205 I jxcore-log: 
08-25 03:26:10.893  6126  6205 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-25 03:26:10.893  6126  6205 I jxcore-log: 
08-25 03:26:10.896  6126  6205 I jxcore-log: My device name is: LGE-LG-D855
08-25 03:26:10.896  6126  6205 I jxcore-log: 
08-25 03:26:10.897  6126  6205 I jxcore-log: WARN testUtils: myNameCallback not set!
08-25 03:26:10.897  6126  6205 I jxcore-log: 
,08-25 03:26:10.996  6126  8001 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 831, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,08-25 03:26:12.361  1069  1376 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=6.5, 0.0, 0.0  rx=5.7 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1085410167] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 03:26:12.363  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=6.5, 0.0, 0.0  rx=5.7 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1085410165] gl rssi=-41 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-25 03:26:12.364  1069  1376 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-25 03:26:13.481  6126  6205 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-25 03:26:13.481  6126  6205 I jxcore-log: 
,08-25 03:26:13.925  6126  6205 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-25 03:26:13.925  6126  6205 I jxcore-log: 
,08-25 03:26:13.950  6126  6205 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-25 03:26:13.950  6126  6205 I jxcore-log: 
,08-25 03:26:15.310  6126  6205 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-25 03:26:15.310  6126  6205 I jxcore-log: 
,08-25 03:26:15.383  1069  1376 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1085407146] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-25 03:26:15.385  1069  1376 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 2 0 "NG700" f4:f2:6d:22:99:3e rssi=-41 f=2412 sc=60 link=72 tx=3.3, 0.0, 0.0  rx=2.9 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1085407143] gl rssi=-41 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-25 03:26:15.385  1069  1376 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-25 03:26:15.546  6126  6205 I jxcore-log: ERROR runTests: 
08-25 03:26:15.546  6126  6205 I jxcore-log: 
,08-25 03:26:15.549  6126  6205 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-25 03:26:15.549  6126  6205 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-25 03:26:15.550  6126  6205 I jxcore-log: WARN testUtils: logCallback not set!
08-25 03:26:15.550  6126  6205 I jxcore-log: 
08-25 03:26:15.562  6126  6205 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-25 03:26:15.562  6126  6205 I jxcore-log:     _functionName: 'loadFile',
08-25 03:26:15.562  6126  6205 I jxcore-log:     _lineNumber: '26',
08-25 03:26:15.562  6126  6205 I jxcore-log:     _columnNumber: '11',
08-25 03:26:15.562  6126  6205 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-25 03:26:15.562  6126  6205 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-25 03:26:15.562  6126  6205 I jxcore-log:     _functionName: '',
08-25 03:26:15.562  6126  6205 I jxcore-log:     _lineNumber: '38',
08-25 03:26:15.562  6126  6205 I jxcore-log:     _columnNumber: '7',
08-25 03:26:15.562  6126  6205 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-25 03:26:15.562  6126  6205 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-25 03:26:15.562  6126  6205 I jxcore-log:     _functionName: '',
08-25 03:26:15.562  6126  6205 I jxcore-log:     _lineNumber: '35',
08-25 03:26:15.562  6126  6205 I jxcore-log:     _columnNumber: '3',
08-25 03:26:15.562  6126  6205 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-25 03:26:15.562  6126  6205 I jxcore-log:   { _fileName: 'module.js',
08-25 03:26:15.562  6126  6205 I jxcore-log:     _functionName: '$w.prototype._compile',
08-25 03:26:15.562  6126  6205 I jxcore-log:     _lineNumber: '621',
08-25 03:26:15.562  6126  6205 I jxcore-log:     _columnNumber: '8',
08-25 03:26:15.562  6126  6205 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-25 03:26:15.562  6126  6205 I jxcore-log:   { _fileName: 'module.js',
08-25 03:26:15.562  6126  6205 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-25 03:26:15.562  6126  6205 I jxcore-log:     _lineNumber: '651',
08-25 03:26:15.562  6126  6205 I jxcore-log:     _columnNumber: '1',
08-25 03:26:15.562  6126  6205 I jxcore-log:    
,08-25 03:26:15.563  6126  6205 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-25 03:26:15.563  6126  6205 I jxcore-log: 
08-25 03:26:15.563  6126  6205 E jxcore-log: Error: 
,08-25 03:26:15.564  6126  6205 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-25 03:26:15.564  6126  6205 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-25 03:26:15.564  6126  6205 E jxcore-log: 
,08-25 03:26:15.940  8013  8013 D AndroidRuntime: 
08-25 03:26:15.940  8013  8013 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-25 03:26:15.948  8013  8013 D AndroidRuntime: CheckJNI is OFF
08-25 03:26:16.156  8013  8013 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-25 03:26:16.174  1069  1171 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-25 03:26:16.175  1069  1171 I ActivityManager: Killing 6126:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-25 03:26:16.243  1069  1096 I WindowState: WIN DEATH: Window{1c3e6533 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-25 03:26:16.249  1069  1428 D WifiService: Client connection lost with reason: 4
08-25 03:26:16.254  1069  1096 D InputDispatcher: Window went away: Window{1c3e6533 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-25 03:26:16.314  1069  1171 I ActivityManager:   Force finishing activity ActivityRecord{3d23ffbc u0 com.test.thalitest/.MainActivity t6}
,08-25 03:26:16.460   340   355 E GBMv2   : DFP En is all cleared set to be enabled
08-25 03:26:16.477  1069  1559 W ActivityManager: Spurious death for ProcessRecord{1296f81f 6126:com.test.thalitest/u0a118}, curProc for 6126: null
,08-25 03:26:16.481  2016  2016 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-25 03:26:16.483  2016  2016 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-25 03:26:16.486  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-25 03:26:16.488  2016  2055 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-25 03:26:16.492  1889  1889 D ActionManagerService: notifyUserLog: 1000003
,08-25 03:26:16.495  2739  4366 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-25 03:26:16.497  2016  2016 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-25 03:26:16.498  2016  2016 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-25 03:26:16.499  2016  2016 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-25 03:26:16.500  2016  2016 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-25 03:26:16.504  1889  1889 D ActionManagerService: notifyUserLog: 1000004
,08-25 03:26:16.508  2739  4366 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-25 03:26:16.509  2016  2016 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-25 03:26:16.512  1925  1942 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-25 03:26:16.516  2739  2776 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 03:26:16.525  1925  1942 D SplitWindowPolicy: topRunningActivity=ActivityInfo{341904cf co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-25 03:26:16.531  1925  1941 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-25 03:26:16.533  1925  1941 D SplitWindowPolicy: topRunningActivity=ActivityInfo{15384e5c co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-25 03:26:16.533  2016  2016 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-25 03:26:16.533  2016  2016 I GBoardWebViewUtils: , create_time: 1430832262123
08-25 03:26:16.533  2016  2016 I GBoardWebViewUtils: , expire_time: 0
08-25 03:26:16.533  2016  2016 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-25 03:26:16.533  2016  2016 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-25 03:26:16.533  2016  2016 I GBoardWebViewUtils: , display: false
08-25 03:26:16.533  2016  2016 I GBoardWebViewUtils: , animation: false }
08-25 03:26:16.533  2016  2016 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-25 03:26:16.533  2016  2016 I GBoardWebViewUtils: , create_time: 1430832262287
08-25 03:26:16.533  2016  2016 I GBoardWebViewUtils: , expire_time: 0
08-25 03:26:16.533  2016  2016 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-25 03:26:16.533  2016  2016 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-25 03:26:16.533  2016  2016 I GBoardWebViewUtils: , display: false
08-25 03:26:16.533  2016  2016 I GBoardWebViewUtils: , animation: false }
08-25 03:26:16.533  2016  2016 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-25 03:26:16.533  2016  2016 I GBoardWebViewUtils: , create_time: 1471602816196
08-25 03:26:16.533  2016  2016 I GBoardWebViewUtils: , expire_time: 0
08-25 03:26:16.533  2016  2016 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-25 03:26:16.533  2016  2016 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-25 03:26:16.533  2016  2016 I GBoardWebViewUtils: , display: false
08-25 03:26:16.533  2016  2016 I GBoardWebViewUtils: , animation: false }
,08-25 03:26:16.551  2016  8040 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-25 03:26:16.553  1069  1253 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-25 03:26:16.556  6796  6796 D WeatherAncestor: 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 3:26:16
08-25 03:26:16.558  6796  6796 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 03:26:16.558  6796  6796 D Weather.Utils: 2 : All the weather widget is gone.
08-25 03:26:16.559  6796  6796 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-25 03:26:16.563  6796  6796 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-25 03:26:16.563  6796  6796 D Weather.Utils: 2 : All the weather widget is gone.
08-25 03:26:16.563  6796  6796 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 3:26:16
,08-25 03:26:16.585  2016  2016 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-25 03:26:16.616  1069  1364 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-25 03:26:16.618  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-25 03:26:16.625  2485  2619 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-25 03:26:16.625  2739  2739 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-25 03:26:16.626  1979  1979 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-25 03:26:16.628  4481  4481 I art     : Explicit concurrent mark sweep GC freed 9964(622KB) AllocSpace objects, 5(99KB) LOS objects, 34% free, 29MB/45MB, paused 887us total 49.496ms
,08-25 03:26:16.634  7127  7127 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-25 03:26:16.634  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-25 03:26:16.652  1069  2611 V SIM_STK : Menu title from STK is T-Mobile
,08-25 03:26:16.689  4374  4374 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-25 03:26:16.689  4374  4374 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-25 03:26:16.689  4374  4374 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-25 03:26:16.689  4374  4374 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-25 03:26:16.689  4374  4374 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-25 03:26:16.689  4374  4374 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-25 03:26:16.689  4374  4374 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-25 03:26:16.689  4374  4374 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 03:26:16.689  4374  4374 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:26:16.690  4374  4374 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 03:26:16.690  4374  4374 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 03:26:16.690  4374  4374 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-25 03:26:16.724  1069  1069 I art     : Explicit concurrent mark sweep GC freed 35699(2MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 2.050ms total 118.657ms
,08-25 03:26:16.725  1069  1559 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8049 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-25 03:26:16.738  2016  2016 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-25 03:26:16.746  1586  1649 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
,08-25 03:26:16.746  1586  1649 D KeyguardModel: createShortcutInfo...
08-25 03:26:16.747  1586  1586 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-25 03:26:16.752  1586  1649 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-25 03:26:16.752  1586  1649 D KeyguardModel: createShortcutInfo...
08-25 03:26:16.756  1586  1586 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-25 03:26:16.756  1586  1586 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-25 03:26:16.758  1586  1649 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-25 03:26:16.759  1586  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 03:26:16.759  1586  1649 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-25 03:26:16.759  1586  1649 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 03:26:16.760  1586  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 03:26:16.760  1586  1649 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-25 03:26:16.771  1069  1918 V SIM_STK : Menu title from STK is T-Mobile
,08-25 03:26:16.772  1069  1918 V SIM_STK : Menu title from STK is T-Mobile
08-25 03:26:16.774  1586  1649 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-25 03:26:16.774  1586  1649 D KeyguardModel: createShortcutInfo...
08-25 03:26:16.777  1853  1853 D SplitUIManager: split_name #11 / not available #0
08-25 03:26:16.777  1853  1853 D SplitUIService: removed split : 
08-25 03:26:16.780  1586  1649 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-25 03:26:16.780  1586  1649 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 03:26:16.781  1069  1960 V SIM_STK : Menu title from STK is T-Mobile
08-25 03:26:16.783  1586  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 03:26:16.783  1586  1649 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-25 03:26:16.786  1586  1649 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-25 03:26:16.786  1586  1649 D KeyguardModel: createShortcutInfo...
,08-25 03:26:16.789  1586  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-25 03:26:16.789  1586  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-25 03:26:16.789  1586  1649 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-25 03:26:16.790  1586  1649 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-25 03:26:16.797  1586  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 03:26:16.797  1586  1649 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-25 03:26:16.798  1586  1649 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-25 03:26:16.798  1586  1649 D KeyguardModel: createShortcutInfo...
08-25 03:26:16.802  1853  1853 D SplitUIManager: split_name #11 / not available #0
08-25 03:26:16.802  1853  1853 I SplitUIService: split app #11
08-25 03:26:16.805  1586  1586 D KeyguardModel: handleShortcutListChanged...
08-25 03:26:16.805  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-25 03:26:16.811  1586  1649 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-25 03:26:16.811  1586  1649 D KeyguardModel: createShortcutInfo...
08-25 03:26:16.813  1586  1649 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-25 03:26:16.813  1586  1649 D KeyguardModel: createShortcutInfo...
08-25 03:26:16.818  1069  1069 D administrator: Handling package changes for user 0
,08-25 03:26:16.823  1586  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 03:26:16.823  1586  1649 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-25 03:26:16.827  8049  8049 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-25 03:26:16.829  1586  1649 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-25 03:26:16.829  1586  1649 D KeyguardModel: createShortcutInfo...
08-25 03:26:16.829  1586  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 03:26:16.829  1586  1649 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-25 03:26:16.830  1586  1649 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-25 03:26:16.830  1586  1649 D KeyguardModel: createShortcutInfo...
08-25 03:26:16.836  1586  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-25 03:26:16.836  1586  1649 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-25 03:26:16.838  1069  2025 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-25 03:26:16.838  1586  1649 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-25 03:26:16.838  1586  1649 D KeyguardModel: createShortcutInfo...
08-25 03:26:16.839  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-25 03:26:16.839  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-25 03:26:16.839  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-25 03:26:16.839  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-25 03:26:16.839  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-25 03:26:16.839  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 03:26:16.839  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-25 03:26:16.839  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-25 03:26:16.839  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-25 03:26:16.839  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-25 03:26:16.839  7127  7127 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-25 03:26:16.857  1586  1586 D KeyguardModel: handleShortcutListChanged...
08-25 03:26:16.857  1586  1586 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-25 03:26:16.879  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-25 03:26:16.883  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 03:26:16.884  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-25 03:26:16.885  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-25 03:26:16.886  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-25 03:26:16.887  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-25 03:26:16.890  8049  8049 D PluginManager: init()
08-25 03:26:16.900  1069  1069 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-25 03:26:16.900  1069  1069 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
,08-25 03:26:16.900  1069  1069 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-25 03:26:16.902  1069  1561 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-25 03:26:16.902  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-25 03:26:16.904  1069  1167 W InputMethodInfo: Duplicated subtype definition found: , voice
08-25 03:26:16.915  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-25 03:26:16.915  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 03:26:16.916  1069  1177 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3b0fe206 u0 com.lge.launcher2/.Launcher t5} time:418853
,08-25 03:26:16.917   326   440 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-25 03:26:16.919  3142  8069 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-25 03:26:16.923  2016  2100 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-25 03:26:16.923  2016  2100 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-25 03:26:16.931  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-25 03:26:16.931  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-25 03:26:16.931  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-25 03:26:16.935  1069  1253 I art     : Explicit concurrent mark sweep GC freed 8663(631KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 8.934ms total 159.840ms
08-25 03:26:16.941  2016  2016 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-25 03:26:16.942  2563  2563 D [Concierge]Service: onStartCommand(). Type : 8
08-25 03:26:16.942  2563  2563 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-25 03:26:16.943  2563  2563 D [Concierge]Service: Update widget ID : 11
,08-25 03:26:16.944  2016  2016 D [Concierge]WidgetView: change position of spinner
08-25 03:26:16.945  2016  2016 I [Concierge]WidgetView: initWebView(). Time : 1472088376945
08-25 03:26:16.945  2563  2563 D [Concierge]Service: onStartCommand(). Type : 0
08-25 03:26:16.957  2016  2016 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 248049565
08-25 03:26:16.958  2016  2016 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
,08-25 03:26:16.958  2016  2016 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-25 03:26:16.960  2016  2016 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@c7a6dc7
08-25 03:26:16.960  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-25 03:26:16.961  2016  2016 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-25 03:26:16.961  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 03:26:16.966  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-25 03:26:16.966  2016  2016 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-25 03:26:16.966  2016  2016 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-25 03:26:16.967  2016  2016 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472087986199, New one : 1472088376945
08-25 03:26:16.967  2016  2016 D [Concierge]WidgetView: Unregister all receivers
08-25 03:26:16.967  2016  2016 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-25 03:26:16.967  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 03:26:16.969  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-25 03:26:16.970  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-25 03:26:16.971  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,08-25 03:26:16.972  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-25 03:26:16.974  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-25 03:26:16.978  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 03:26:16.978  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 03:26:17.020  2016  2016 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-25 03:26:17.028  2016  2016 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-25 03:26:17.028  2016  2016 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-25 03:26:17.029  2016  2016 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-25 03:26:17.050  2016  2016 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2d9213ce time:418987
,08-25 03:26:17.053  8013  8013 D AndroidRuntime: Shutting down VM
08-25 03:26:17.082  1069  1253 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=8071 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-25 03:26:17.109  1069  1167 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-25 03:26:17.114  1069  1167 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-25 03:26:17.116  2016  2016 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-25 03:26:17.141  1069  1996 I ActivityManager: Killing 7668:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-25 03:26:17.172  2016  2016 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-25 03:26:17.186  8049  8049 W ExternalStrings: load override strings
08-25 03:26:17.186  8049  8049 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-25 03:26:17.186  8049  8049 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-25 03:26:17.186  8049  8049 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-25 03:26:17.186  8049  8049 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-25 03:26:17.186  8049  8049 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-25 03:26:17.186  8049  8049 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-25 03:26:17.186  8049  8049 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-25 03:26:17.186  8049  8049 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-25 03:26:17.186  8049  8049 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-25 03:26:17.186  8049  8049 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-25 03:26:17.186  8049  8049 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-25 03:26:17.186  8049  8049 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-25 03:26:17.186  8049  8049 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-25 03:26:17.186  8049  8049 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-25 03:26:17.186  8049  8049 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-25 03:26:17.186  8049  8049 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-25 03:26:17.186  8049  8049 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-25 03:26:17.186  8049  8049 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-25 03:26:17.187  8049  8049 D StatusProvider: onCreate
08-25 03:26:17.208  2016  2899 I GBoardtInterface: onReloaded()
,08-25 03:26:17.210  2016  2016 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,08-25 03:26:17.315  1069  1926 W libprocessgroup: failed to open /acct/uid_10008/pid_7668/cgroup.procs: No such file or directory
,08-25 03:26:17.319  2739  2755 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 03:26:17.322  2739  2775 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 03:26:17.327  1889  1889 D ActionManagerService: notifyUserLog: 1000001
08-25 03:26:17.328  2739  4366 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-25 03:26:17.328  2739  4366 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-25 03:26:17.331  1889  1889 D ActionManagerService: notifyUserLog: 1000001
,08-25 03:26:17.333  2739  4366 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-25 03:26:17.333  2739  4366 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-25 03:26:17.333  2739  4366 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-25 03:26:17.333  2739  4366 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-25 03:26:17.333  2739  2775 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-25 03:26:17.336  2016  2016 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-25 03:26:17.336  2016  2016 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-25 03:26:17.337  2016  2016 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-25 03:26:17.337  2016  2016 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-25 03:26:17.339  2016  2016 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-25 03:26:17.339  2016  2016 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-25 03:26:17.354  8049  8049 V Signer  : override build config not found
08-25 03:26:17.354  8049  8049 D Signer  : value of property debug is false
,08-25 03:26:17.381  8049  8049 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-25 03:26:17.382  8049  8049 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-25 03:26:17.382  8049  8049 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-25 03:26:17.382  8049  8049 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-25 03:26:17.382  8049  8049 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-25 03:26:17.382  8049  8049 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-25 03:26:17.383  8049  8049 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-25 03:26:17.383  8049  8049 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-25 03:26:17.383  8049  8049 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-25 03:26:17.383  8049  8049 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-25 03:26:17.383  8049  8049 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-25 03:26:17.383  8049  8049 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
,08-25 03:26:17.383  8049  8049 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-25 03:26:17.390  8049  8049 V LGMDMManager: Create singleton instance
08-25 03:26:17.425  8049  8049 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.

```
