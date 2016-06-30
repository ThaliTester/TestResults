#### Test 7578926851a8f91_thali05_LGE-LG-D855 Logs


```
--------- beginning of system
06-30 12:54:10.984  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1041000597 [*alarm*], flags=0x0
,--------- beginning of main
06-30 12:54:33.261  6080  6080 D AndroidRuntime: 
06-30 12:54:33.261  6080  6080 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
06-30 12:54:33.267  6080  6080 D AndroidRuntime: CheckJNI is OFF
06-30 12:54:33.391  6080  6080 D AndroidRuntime: Calling main entry com.android.commands.am.Am
06-30 12:54:33.396  1037  1911 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
06-30 12:54:33.405  1929  1944 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
06-30 12:54:33.409  1037  1911 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
06-30 12:54:33.410  1037  1911 D ActivityManager: setTaskToReturnTo : TaskRecord{1cb12eec #12 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
06-30 12:54:33.410  1037  1911 D ActivityManager: setTaskToReturnTo : TaskRecord{1cb12eec #12 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
06-30 12:54:33.411  1037  1911 D WindowStateEx: AppWindowTokenEx init.. 
06-30 12:54:33.412   338   367 E GBMv2   : DFP En is all cleared set to be enabled
06-30 12:54:33.434  1037  1911 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6095 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
06-30 12:54:33.435  6080  6080 D AndroidRuntime: Shutting down VM
06-30 12:54:33.491  1929  1945 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
06-30 12:54:33.491  1929  1945 D SplitWindowPolicy: topRunningActivity=ActivityInfo{9842b7 co.....MainActivity}, taskId=12, activityType=0, bIsSplit=false
06-30 12:54:33.492  1929  2708 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
06-30 12:54:33.492  1929  2708 D SplitWindowPolicy: topRunningActivity=ActivityInfo{35b25a24 co.....MainActivity}, taskId=12, activityType=0, bIsSplit=false
06-30 12:54:33.525  6095  6095 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
06-30 12:54:33.589  6095  6095 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
06-30 12:54:33.596  6095  6095 I LibraryLoader: Loading: webviewchromium
06-30 12:54:33.598  6095  6095 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4641-4644)
06-30 12:54:33.598  6095  6095 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 12:54:33.612  6095  6095 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {21a7c3}
06-30 12:54:33.613  6095  6095 I LibraryLoader: Expected native library version number "",actual native library version number ""
06-30 12:54:33.613  6095  6095 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
06-30 12:54:33.622  6095  6095 I BrowserStartupController: Initializing chromium process, renderers=0
06-30 12:54:33.622  6095  6095 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 12:54:33.631  6095  6130 W chromium: [WARNING:dns_config_service_posix.cc(293)] Failed to read DnsConfig.
06-30 12:54:33.636  6095  6095 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
06-30 12:54:33.637  6095  6095 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
06-30 12:54:33.637  6095  6095 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
06-30 12:54:33.654  6095  6095 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
06-30 12:54:33.654  6095  6095 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
06-30 12:54:33.654  6095  6095 I Adreno-EGL: Build Date: 12/12/14 금
06-30 12:54:33.654  6095  6095 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
06-30 12:54:33.654  6095  6095 I Adreno-EGL: Remote Branch: 
06-30 12:54:33.654  6095  6095 I Adreno-EGL: Local Patches: 
06-30 12:54:33.654  6095  6095 I Adreno-EGL: Reconstruct Branch: 
06-30 12:54:33.654   316  2116 V AudioPolicyService: registerClient() client 0xb558a2c0, uid 10118
,06-30 12:54:33.668  1037  1120 D BluetoothManagerService: Message: 20
06-30 12:54:33.668  1037  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3837f416:true
06-30 12:54:33.846  1037  1893 I art     : Explicit concurrent mark sweep GC freed 28656(1382KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.008ms total 139.033ms
06-30 12:54:33.873  6095  6140 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
06-30 12:54:33.882  6095  6095 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
06-30 12:54:33.899  6095  6095 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 12:54:33.904  6095  6095 W AwContents: onDetachedFromWindow called when already detached. Ignoring
06-30 12:54:33.908  6095  6095 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
06-30 12:54:33.911  6095  6095 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
06-30 12:54:33.911  6095  6095 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
06-30 12:54:33.926  6095  6095 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
06-30 12:54:33.933  6095  6095 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 12:54:33.933  6095  6095 W art     : Attempt to remove local handle scope entry from IRT, ignoring
06-30 12:54:33.974  6095  6156 D OpenGLRenderer: Render dirty regions requested: true
06-30 12:54:33.974  6095  6156 I OpenGLRenderer: Initialized EGL, version 1.4
06-30 12:54:33.991  1037  1112 W ActivityManager: Activity pause timeout for ActivityRecord{2a4512b5 u0 com.test.thalitest/.MainActivity t12}
06-30 12:54:33.995  6095  6156 D OpenGLRenderer: Enabling debug mode 0
06-30 12:54:34.006  6095  6095 D Atlas   : Validating map...
06-30 12:54:34.014  1037  1893 D SplitWindow: check instance of lgWin Window{2ef24520 u0 com.test.thalitest/com.test.thalitest.MainActivity}
06-30 12:54:34.055  6095  6154 D LgDataFeature: LgDataFeature() Constructor: none
06-30 12:54:34.055  6095  6154 D LgDataFeature: LgDataFeature() Constructor Done, null
06-30 12:54:34.141  1037  1121 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +651ms (total +729ms)
06-30 12:54:34.142  6095  6095 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3c340d6e time:275188
06-30 12:54:34.144  1037  1121 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2a4512b5 u0 com.test.thalitest/.MainActivity t12} time:275190
06-30 12:54:34.308  6095  6095 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
06-30 12:54:34.414  6095  6154 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
06-30 12:54:34.414  6095  6154 I chromium: 
,06-30 12:54:34.544  6095  6169 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435141120
,06-30 12:54:34.559  6095  6169 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
06-30 12:54:34.559  6095  6169 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
06-30 12:54:34.559  6095  6169 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
06-30 12:54:34.559  6095  6169 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
06-30 12:54:34.559  6095  6169 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
06-30 12:54:34.559  6095  6169 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f11f6d2 added. We now have 1 listener(s)
,06-30 12:54:34.560  1037  2019 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 12:54:34.568  6095  6169 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
06-30 12:54:34.572  6095  6169 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,06-30 12:54:34.573  6095  6169 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
06-30 12:54:34.573  6095  6169 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
06-30 12:54:34.579  6095  6095 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
06-30 12:54:34.579  6095  6095 I chromium: 
06-30 12:54:34.580  6095  6169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
06-30 12:54:34.580  6095  6169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
06-30 12:54:34.580  6095  6169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
06-30 12:54:34.580  6095  6169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
06-30 12:54:34.580  6095  6169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
06-30 12:54:34.580  6095  6169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
06-30 12:54:34.580  6095  6169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
06-30 12:54:34.580  6095  6169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
06-30 12:54:34.580  6095  6169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
06-30 12:54:34.580  6095  6169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
06-30 12:54:34.580  6095  6169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
06-30 12:54:34.580  6095  6169 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@483e259 added. We now have 1 listener(s)
06-30 12:54:34.583  6095  6169 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
06-30 12:54:34.591  1037  1531 D WifiService: New client listening to asynchronous messages
,06-30 12:54:34.596  6095  6169 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: isBleMultipleAdvertisementSupported: Storing the value (NOT_SUPPORTED) in persistent storage
,06-30 12:54:34.602  6095  6169 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is not supported; BLE advertisement supported: false, Wi-Fi supported: true
06-30 12:54:34.602  6095  6169 E io.jxcore.node.ConnectionHelper: Constructor: Bluetooth LE discovery mode is not supported
06-30 12:54:34.606  6095  6169 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,06-30 12:54:34.608  1037  1947 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
06-30 12:54:34.609  6095  6169 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
06-30 12:54:34.614  6095  6169 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 12:54:34.614  6095  6169 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 12:54:34.614  6095  6169 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 12:54:34.614  6095  6169 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 12:54:34.614  6095  6169 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 12:54:34.614  6095  6169 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 12:54:34.614  6095  6169 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 12:54:34.614  6095  6169 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 12:54:34.615  6095  6169 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
06-30 12:54:34.615  6095  6169 D io.jxcore.node.ConnectivityMonitor: start: OK
06-30 12:54:34.616  6095  6169 I io.jxcore.node.LifeCycleMonitor: start: OK
06-30 12:54:34.616  6095  6095 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,06-30 12:54:34.653  6095  6095 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,06-30 12:54:34.748   338   369 E GBMv2   : DFP En is all cleared set to be enabled
06-30 12:54:34.748   338   369 E GBMv2   : Set value is all cleared set the max
06-30 12:54:34.748   338   369 I GBMv2   : DFP Enabled. Ignore VFP set
,06-30 12:54:35.461  6095  6172 W jxcore-log: Initializing JXcore engine
06-30 12:54:35.461  6095  6172 W jxcore-log: JXcore engine is ready
,06-30 12:54:35.498  6172  6172 W Thread-697: type=1400 audit(0.0:158): avc: denied { ioctl } for path="socket:[7072]" dev="sockfs" ino=7072 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
06-30 12:54:35.498  6172  6172 W Thread-697: type=1400 audit(0.0:159): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2864 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
06-30 12:54:35.498  6172  6172 W Thread-697: type=1400 audit(0.0:160): avc: denied { ioctl } for path="socket:[8622]" dev="sockfs" ino=8622 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
06-30 12:54:35.498  6172  6172 W Thread-697: type=1400 audit(0.0:161): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
06-30 12:54:35.498  6172  6172 W Thread-697: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[29520]" dev="sockfs" ino=29520 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,06-30 12:54:35.526  6095  6172 W jxcore-log: Starting JXcore engine
06-30 12:54:35.616  6095  6172 W jxcore-log: Platform android
06-30 12:54:35.616  6095  6172 W jxcore-log: 
06-30 12:54:35.616  6095  6172 W jxcore-log: Process ARCH arm
06-30 12:54:35.616  6095  6172 W jxcore-log: 
,06-30 12:54:35.802  6095  6172 I jxcore-log: JXcore Cordova bridge is ready!
06-30 12:54:35.802  6095  6172 I jxcore-log: 
06-30 12:54:35.802  6095  6172 W jxcore-log: JXcore engine is started
,06-30 12:54:35.815  6095  6169 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,06-30 12:54:35.823  6095  6095 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,06-30 12:54:45.655  6095  6172 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
06-30 12:54:45.655  6095  6172 I jxcore-log: 
,06-30 12:54:45.657  6095  6172 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
06-30 12:54:45.657  6095  6172 I jxcore-log: 
,06-30 12:54:45.661  6095  6172 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
06-30 12:54:45.661  6095  6172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
06-30 12:54:45.661  6095  6172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
06-30 12:54:45.661  6095  6172 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
06-30 12:54:45.661  6095  6172 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
06-30 12:54:45.661  6095  6172 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
06-30 12:54:45.661  6095  6172 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
06-30 12:54:45.661  6095  6172 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
06-30 12:54:45.663  6095  6172 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
06-30 12:54:45.665  6095  6172 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
06-30 12:54:45.665  6095  6172 I jxcore-log: 
06-30 12:54:45.666  6095  6172 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
06-30 12:54:45.666  6095  6172 I jxcore-log: 
06-30 12:54:45.988  6095  6172 I jxcore-log: Unit Test app is loaded
06-30 12:54:45.988  6095  6172 I jxcore-log: 
,06-30 12:54:45.998  6095  6095 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
06-30 12:54:46.007  6095  6172 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
06-30 12:54:46.007  6095  6172 I jxcore-log: 
06-30 12:54:46.012  6095  6172 I jxcore-log: My device name is: LGE-LG-D855
06-30 12:54:46.012  6095  6172 I jxcore-log: 
,06-30 12:54:49.805  6095  6172 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
06-30 12:54:49.805  6095  6172 I jxcore-log: 
,06-30 12:54:50.188  6095  6172 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
06-30 12:54:50.188  6095  6172 I jxcore-log: 
,06-30 12:54:50.214  6095  6172 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js
06-30 12:54:50.214  6095  6172 I jxcore-log: 
,06-30 12:54:50.219  6095  6172 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js
06-30 12:54:50.219  6095  6172 I jxcore-log: 
,06-30 12:54:50.234  6095  6172 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js
06-30 12:54:50.234  6095  6172 I jxcore-log: 
,06-30 12:54:50.238  6095  6172 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js
06-30 12:54:50.238  6095  6172 I jxcore-log: 
06-30 12:54:52.209  6095  6172 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js
06-30 12:54:52.209  6095  6172 I jxcore-log: 
,06-30 12:54:52.222  6095  6172 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js
06-30 12:54:52.222  6095  6172 I jxcore-log: 
,06-30 12:54:52.232  6095  6172 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js
06-30 12:54:52.232  6095  6172 I jxcore-log: 
,06-30 12:54:52.384  6095  6172 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js
06-30 12:54:52.384  6095  6172 I jxcore-log: 
,06-30 12:54:52.468  6095  6172 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js
06-30 12:54:52.468  6095  6172 I jxcore-log: 
,06-30 12:54:52.525  6095  6172 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js
06-30 12:54:52.525  6095  6172 I jxcore-log: 
,06-30 12:54:52.532  6095  6172 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js
06-30 12:54:52.532  6095  6172 I jxcore-log: 
,06-30 12:54:52.722  6095  6172 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js
06-30 12:54:52.722  6095  6172 I jxcore-log: 
,06-30 12:54:52.745  6095  6172 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js
06-30 12:54:52.745  6095  6172 I jxcore-log: 
,06-30 12:54:52.749  6095  6172 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js
06-30 12:54:52.749  6095  6172 I jxcore-log: 
,06-30 12:54:52.755  6095  6172 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js
06-30 12:54:52.755  6095  6172 I jxcore-log: 
,06-30 12:54:52.769  6095  6172 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js
06-30 12:54:52.769  6095  6172 I jxcore-log: 
,06-30 12:54:52.788  6095  6172 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js
06-30 12:54:52.788  6095  6172 I jxcore-log: 
,06-30 12:54:52.870  6095  6172 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js
06-30 12:54:52.870  6095  6172 I jxcore-log: 
,06-30 12:54:52.877  6095  6172 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js
06-30 12:54:52.877  6095  6172 I jxcore-log: 
,06-30 12:54:52.903  6095  6172 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testthaliPeerPoolDefault.js
06-30 12:54:52.903  6095  6172 I jxcore-log: 
,06-30 12:54:52.913  6095  6172 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: NOT_SUPPORTED
06-30 12:54:52.915  6095  6172 I jxcore-log: INFO testUtils: BLE multiple advertisement not supported
06-30 12:54:52.915  6095  6172 I jxcore-log: 
06-30 12:55:00.049  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 12:55:00.049  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 12:55:00.050  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 12:55:00.050  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,06-30 12:55:00.061  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 12:55:00.061  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:55:00.064  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:55:00.067  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 12:55:33.713  1037  3505 I LocationManagerService: remove 2568c20d
,06-30 12:55:33.719  1037  3505 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
06-30 12:55:33.721  1037  3505 D LocationManagerService: getAllProviders()=[passive, gps, network]
06-30 12:55:33.722  1037  3505 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
06-30 12:55:33.725  1037  3505 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
06-30 12:55:33.726  1037  3505 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,06-30 12:55:44.557  1037  1366 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1041000597, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,06-30 12:55:44.609  2563  2563 D [Concierge]Service: onStartCommand(). Type : 9
,06-30 12:55:44.640  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1041000597 [*alarm*], flags=0x0
,06-30 12:56:00.052  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 12:56:00.053  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 12:56:00.053  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 12:56:00.053  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,06-30 12:56:00.066  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
,06-30 12:56:00.066  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:56:00.068  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:56:00.070  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 12:57:00.051  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 12:57:00.052  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 12:57:00.052  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 12:57:00.052  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,06-30 12:57:00.065  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 12:57:00.065  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:57:00.068  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:57:00.069  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 12:58:00.051  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 12:58:00.052  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 12:58:00.052  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 12:58:00.052  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,06-30 12:58:00.057  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 12:58:00.057  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:58:00.058  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:58:00.059  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 12:59:00.045  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 12:59:00.046  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 12:59:00.046  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 12:59:00.046  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,06-30 12:59:00.058  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 12:59:00.058  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:59:00.061  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 12:59:00.062  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:00:00.096  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:00:00.097  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:00:00.097  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 13:00:00.097  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:00:00.109  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:00:00.109  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:00:00.112  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:00:00.114  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:01:00.050  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:01:00.050  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:01:00.051  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 13:01:00.051  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:01:00.063  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:01:00.063  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:01:00.065  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:01:00.067  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:02:00.051  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:02:00.051  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:02:00.052  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 13:02:00.052  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:02:00.064  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:02:00.064  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:02:00.066  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:02:00.068  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:03:00.051  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:03:00.051  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:03:00.051  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 13:03:00.052  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:03:00.063  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:03:00.064  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:03:00.066  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:03:00.068  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:04:00.051  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:04:00.051  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:04:00.052  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 13:04:00.052  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:04:00.064  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:04:00.064  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:04:00.066  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:04:00.068  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:05:00.051  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:05:00.051  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:05:00.051  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 13:05:00.052  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:05:00.063  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:05:00.064  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:05:00.066  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:05:00.068  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:05:34.509  1037  1366 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1041000597, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,06-30 13:05:34.525  1037  1366 V AlarmManager: RTC_WAKEUP set : Alarm{25633576 type 0 when 1467284544691 com.google.android.gms} when 1467284544691
,06-30 13:05:34.532  1037  1366 V AlarmManager: ELAPSED_WAKEUP set : Alarm{34cbe777 type 2 when 930352 com.google.android.gms} when 930352
06-30 13:05:34.572  2563  2563 D [Concierge]Service: onStartCommand(). Type : 9
,06-30 13:05:34.608  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1041000597 [*alarm*], flags=0x0
,06-30 13:05:34.622  1805  6195 I EventLogService: Aggregate from 1467282744628 (log), 1467282744628 (data)
,06-30 13:05:34.627   310  6196 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
06-30 13:05:34.628  1037  1118 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
,06-30 13:05:34.715  1805  6195 W EventLogAggregator: Unknown tag: snet_gcore
06-30 13:05:34.715  1805  6195 W EventLogAggregator: Unknown tag: snet_launch_service
,06-30 13:05:41.447  1037  1366 V AlarmManager: ELAPSED_WAKEUP set : Alarm{c099c4d type 2 when 942459 com.android.bluetooth} when 942459
,06-30 13:05:41.452  3797  3982 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
06-30 13:05:41.452  3797  3982 W bt-smp  : Plain text(LSB ~ MSB) = 8d 21 5d 00 00 00 00 00 00 00 00 00 00 00 00 00 
06-30 13:05:41.452  3797  3982 W bt-smp  : Encrypted text(LSB ~ MSB) = fc 27 96 38 45 a8 a1 16 b4 6e b9 b1 8f 8c 5b 68 
06-30 13:05:41.452  3797  3982 W bt-btm  : Stopping oneshot timer
06-30 13:06:00.052  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:06:00.052  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:06:00.052  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 13:06:00.052  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:06:00.065  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:06:00.065  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:06:00.067  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:06:00.069  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:07:00.069  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:07:00.069  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:07:00.069  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 13:07:00.070  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:07:00.082  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:07:00.082  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:07:00.086  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:07:00.086  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 13:08:00.051  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:08:00.051  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:08:00.051  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 13:08:00.052  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:08:00.063  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:08:00.063  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:08:00.065  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:08:00.067  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:09:00.050  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:09:00.050  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:09:00.051  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 13:09:00.051  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:09:00.063  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:09:00.063  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:09:00.065  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:09:00.067  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:10:00.051  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:10:00.051  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:10:00.052  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 13:10:00.052  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:10:00.064  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:10:00.064  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:10:00.066  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:10:00.068  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:10:18.883  1037  1110 I UsageStatsService: User[0] Flushing usage stats to disk
,06-30 13:11:00.051  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:11:00.051  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:11:00.052  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 13:11:00.052  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:11:00.063  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated(),
06-30 13:11:00.063  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:11:00.066  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:11:00.067  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:11:43.495  1037  1366 D PowerManagerServiceEx: acquireWakeLockInternal: lock=1041000597, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1037
,06-30 13:11:43.512  1037  1366 V AlarmManager: ELAPSED_WAKEUP set : Alarm{3e453302 type 2 when 1304524 com.google.android.gms} when 1304524
,06-30 13:11:43.559  2563  2563 D [Concierge]Service: onStartCommand(). Type : 9
,06-30 13:11:43.585  1037  1037 D PowerManagerServiceEx: releaseWakeLockInternal: lock=1041000597 [*alarm*], flags=0x0
,06-30 13:12:00.049  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:12:00.049  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:12:00.050  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 13:12:00.050  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:12:00.061  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:12:00.061  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:12:00.063  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:12:00.067  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
,06-30 13:12:10.356  1589  1589 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
06-30 13:12:10.356  1589  1589 I [SystemUI]LGPowerUI: On Skip Timer : true
,06-30 13:12:10.372  1929  2097 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
06-30 13:12:10.372  1929  2097 D LEDHandler: Battery Level Remaining: 100%
06-30 13:12:10.372  1929  2097 D LEDHandler: Battery Temp: 277, mChargingStatus=5, mChargingStop=false
,06-30 13:12:10.375  1589  1589 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 277
06-30 13:12:10.375  1589  1589 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
06-30 13:12:10.379  1037  1037 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:12:10.379  1037  1037 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
06-30 13:12:10.379  1037  1531 D WifiController: battery changed pluggedType: 2
06-30 13:12:10.381  1589  1589 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
06-30 13:12:10.383  3797  3904 D HeadsetStateMachine: Disconnected process message: 10, size: 0
06-30 13:12:10.387  6008  6008 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,06-30 13:13:00.055  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:13:00.055  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:13:00.055  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 13:13:00.056  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:13:00.067  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:13:00.067  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:13:00.069  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:13:00.071  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:14:00.063  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:14:00.063  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:14:00.063  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
,06-30 13:14:00.070  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
06-30 13:14:00.077  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:14:00.078  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:14:00.080  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:14:00.082  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:15:00.071  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:15:00.071  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:15:00.072  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 13:15:00.072  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:15:00.085  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:15:00.085  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:15:00.087  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:15:00.089  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:16:00.080  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:16:00.081  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:16:00.081  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 13:16:00.081  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:16:00.093  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:16:00.093  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:16:00.097  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
,06-30 13:16:00.105  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:17:00.089  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:17:00.089  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:17:00.089  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 13:17:00.090  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:17:00.101  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:17:00.102  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:17:00.105  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
,06-30 13:17:00.113  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
06-30 13:18:00.098  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
06-30 13:18:00.098  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
06-30 13:18:00.099  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
06-30 13:18:00.099  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,06-30 13:18:00.110  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
06-30 13:18:00.110  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:18:00.113  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
06-30 13:18:00.116  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
,TIME-OUT KILL (timeout was 1400000ms)
```
