#### Test 82642184cbac892_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
08-29 20:49:04.184   572   572 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 20:49:04.687  5504  5504 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 20:49:04.693  5504  5504 D AndroidRuntime: CheckJNI is OFF
08-29 20:49:04.724  5504  5504 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 20:49:04.760  5504  5504 I Radio-JNI: register_android_hardware_Radio DONE
08-29 20:49:04.775  5504  5504 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 20:49:04.788   929  3440 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 20:49:04.836   929  3440 I ActivityManager: Start proc 5513:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
08-29 20:49:04.841  5504  5504 D AndroidRuntime: Shutting down VM
08-29 20:49:04.934  5513  5513 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
08-29 20:49:04.952  5513  5513 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 20:49:04.976  5513  5513 I LibraryLoader: Time to load native libraries: 19 ms (timestamps 7788-7807)
08-29 20:49:04.976  5513  5513 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 20:49:04.997  5513  5513 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {48819d6}
08-29 20:49:04.997  5513  5513 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 20:49:04.997  5513  5513 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 20:49:05.001  5513  5513 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 20:49:05.002  5513  5513 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 20:49:05.041  5513  5513 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-29 20:49:05.055  5513  5513 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 20:49:05.056  5513  5513 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 20:49:05.056  5513  5513 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
08-29 20:49:05.056  5513  5513 I Adreno  : Build Date                       : 10/21/15
08-29 20:49:05.056  5513  5513 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 20:49:05.056  5513  5513 I Adreno  : Local Branch                     : 
08-29 20:49:05.056  5513  5513 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
08-29 20:49:05.056  5513  5513 I Adreno  : Remote Branch                    : NONE
08-29 20:49:05.056  5513  5513 I Adreno  : Reconstruct Branch               : NOTHING
,08-29 20:49:05.114   929   946 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6724838:true
,08-29 20:49:05.171  5513  5513 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 20:49:05.185   572   572 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 20:49:05.189  5513  5513 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,08-29 20:49:05.222  5513  5550 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 20:49:05.232  5513  5537 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 20:49:05.266  5513  5550 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 20:49:05.359   929   947 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +474ms (total +550ms)
,08-29 20:49:05.385  5513  5513 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5513
,08-29 20:49:05.474  5513  5513 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 20:49:05.641  5513  5553 D jxcore_app_log: JniHelper::setJavaVM(0xf52bc000), pthread_self() = -581166800
,08-29 20:49:05.647  5513  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 20:49:05.647  5513  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 20:49:05.647  5513  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 20:49:05.647  5513  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 20:49:05.647  5513  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 20:49:05.647  5513  5553 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@532c79c added. We now have 1 listener(s)
08-29 20:49:05.651  5513  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,08-29 20:49:05.652  5513  5553 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 20:49:05.653  5513  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 20:49:05.653  5513  5553 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 20:49:05.657  5513  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 20:49:05.657  5513  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 20:49:05.657  5513  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 20:49:05.657  5513  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
08-29 20:49:05.657  5513  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 20:49:05.657  5513  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 20:49:05.657  5513  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 20:49:05.657  5513  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 20:49:05.657  5513  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 20:49:05.657  5513  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 20:49:05.657  5513  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 20:49:05.657  5513  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 20:49:05.657  5513  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 20:49:05.657  5513  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-29 20:49:05.657  5513  5553 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5add92b added. We now have 1 listener(s)
08-29 20:49:05.657  5513  5553 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 20:49:05.660   929  2982 D WifiService: New client listening to asynchronous messages
,08-29 20:49:05.661  5513  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 20:49:05.661  5513  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 20:49:05.661  5513  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-29 20:49:05.662  5513  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 20:49:05.662  5513  5553 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 20:49:05.665  5513  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 20:49:05.665  5513  5553 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,08-29 20:49:05.672  5513  5553 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 20:49:05.672  5513  5553 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 20:49:05.672  5513  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 20:49:05.672  5513  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 20:49:05.672  5513  5553 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 20:49:05.672  5513  5553 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 20:49:05.672  5513  5553 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 20:49:05.672  5513  5553 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 20:49:05.672  5513  5553 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 20:49:05.672  5513  5553 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 20:49:05.672  5513  5553 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 20:49:05.674  5513  5553 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 20:49:05.675  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 20:49:05.679  5513  5513 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 20:49:05.698  5513  5513 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 20:49:06.185   572   572 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 20:49:06.191  5513  5522 I art     : Background sticky concurrent mark sweep GC freed 77364(7MB) AllocSpace objects, 18(1892KB) LOS objects, 28% free, 23MB/32MB, paused 1.561ms total 292.370ms
,08-29 20:49:06.708  5513  5559 W jxcore-log: Initializing JXcore engine
,08-29 20:49:06.709  5513  5559 W jxcore-log: JXcore engine is ready
,08-29 20:49:06.765  5559  5559 W Thread-57: type=1400 audit(0.0:67): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=1276 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-29 20:49:06.765  5559  5559 W Thread-57: type=1400 audit(0.0:68): avc: denied { ioctl } for path="socket:[16393]" dev="sockfs" ino=16393 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-29 20:49:06.765  5559  5559 W Thread-57: type=1400 audit(0.0:69): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5913 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-29 20:49:06.765  5559  5559 W Thread-57: type=1400 audit(0.0:70): avc: denied { ioctl } for path="socket:[29667]" dev="sockfs" ino=29667 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 20:49:06.785  5513  5559 W jxcore-log: Starting JXcore engine
,08-29 20:49:06.855  5513  5559 W jxcore-log: Platform android
08-29 20:49:06.855  5513  5559 W jxcore-log: 
,08-29 20:49:06.855  5513  5559 W jxcore-log: Process ARCH arm
08-29 20:49:06.855  5513  5559 W jxcore-log: 
,08-29 20:49:06.950  5513  5559 I jxcore-log: JXcore Cordova bridge is ready!
08-29 20:49:06.950  5513  5559 I jxcore-log: 
,08-29 20:49:06.950  5513  5559 W jxcore-log: JXcore engine is started
,08-29 20:49:06.960  5513  5553 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 20:49:06.965  5513  5513 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 20:49:07.187   572   572 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 20:49:08.188   572   572 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 20:49:15.469   929  5270 D NetlinkSocketObserver: NeighborEvent{elapsedMs=288300, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-29 20:49:16.704  5513  5559 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 20:49:16.704  5513  5559 I jxcore-log: 
,08-29 20:49:16.706  5513  5559 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 20:49:16.706  5513  5559 I jxcore-log: 
,08-29 20:49:16.710  5513  5559 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 20:49:16.710  5513  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 20:49:16.710  5513  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 20:49:16.710  5513  5559 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 20:49:16.710  5513  5559 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 20:49:16.710  5513  5559 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 20:49:16.710  5513  5559 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 20:49:16.710  5513  5559 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 20:49:16.712  5513  5559 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 20:49:16.713  5513  5559 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 20:49:16.713  5513  5559 I jxcore-log: 
,08-29 20:49:16.715  5513  5559 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 20:49:16.715  5513  5559 I jxcore-log: 
,08-29 20:49:16.964  5513  5559 I jxcore-log: Running unit tests
08-29 20:49:16.964  5513  5559 I jxcore-log: 
,08-29 20:49:16.964  5513  5559 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-29 20:49:16.965  5513  5559 I jxcore-log: Failed to execute UT.
08-29 20:49:16.965  5513  5559 I jxcore-log: 
08-29 20:49:16.966  5513  5559 I jxcore-log: Unit Test app is loaded
08-29 20:49:16.966  5513  5559 I jxcore-log: 
,08-29 20:49:16.970  5513  5559 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 20:49:16.970  5513  5559 I jxcore-log: 
,08-29 20:49:16.973  5513  5559 I jxcore-log: My device name is: Huawei-Nexus 6P
08-29 20:49:16.973  5513  5559 I jxcore-log: 
,08-29 20:49:16.974  5513  5559 I jxcore-log: WARN testUtils: myNameCallback not set!
08-29 20:49:16.974  5513  5559 I jxcore-log: 
,08-29 20:49:16.990  5513  5513 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-29 20:49:18.739  5513  5559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-29 20:49:18.739  5513  5559 I jxcore-log: 
,08-29 20:49:19.056  5513  5559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-29 20:49:19.056  5513  5559 I jxcore-log: 
,08-29 20:49:19.075  5513  5559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-29 20:49:19.075  5513  5559 I jxcore-log: 
,08-29 20:49:20.061  5513  5559 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-29 20:49:20.061  5513  5559 I jxcore-log: 
,08-29 20:49:20.218  5513  5559 I jxcore-log: ERROR runTests: 
08-29 20:49:20.218  5513  5559 I jxcore-log: 
,08-29 20:49:20.220  5513  5559 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-29 20:49:20.220  5513  5559 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
,08-29 20:49:20.220  5513  5559 I jxcore-log: WARN testUtils: logCallback not set!
08-29 20:49:20.220  5513  5559 I jxcore-log: 
,08-29 20:49:20.227  5513  5559 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-29 20:49:20.227  5513  5559 I jxcore-log:     _functionName: 'loadFile',
08-29 20:49:20.227  5513  5559 I jxcore-log:     _lineNumber: '26',
08-29 20:49:20.227  5513  5559 I jxcore-log:     _columnNumber: '11',
08-29 20:49:20.227  5513  5559 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-29 20:49:20.227  5513  5559 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-29 20:49:20.227  5513  5559 I jxcore-log:     _functionName: '',
08-29 20:49:20.227  5513  5559 I jxcore-log:     _lineNumber: '38',
08-29 20:49:20.227  5513  5559 I jxcore-log:     _columnNumber: '7',
08-29 20:49:20.227  5513  5559 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-29 20:49:20.227  5513  5559 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-29 20:49:20.227  5513  5559 I jxcore-log:     _functionName: '',
08-29 20:49:20.227  5513  5559 I jxcore-log:     _lineNumber: '35',
08-29 20:49:20.227  5513  5559 I jxcore-log:     _columnNumber: '3',
08-29 20:49:20.227  5513  5559 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-29 20:49:20.227  5513  5559 I jxcore-log:   { _fileName: 'module.js',
08-29 20:49:20.227  5513  5559 I jxcore-log:     _functionName: '$w.prototype._compile',
08-29 20:49:20.227  5513  5559 I jxcore-log:     _lineNumber: '621',
08-29 20:49:20.227  5513  5559 I jxcore-log:     _columnNumber: '8',
08-29 20:49:20.227  5513  5559 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-29 20:49:20.227  5513  5559 I jxcore-log:   { _fileName: 'module.js',
08-29 20:49:20.227  5513  5559 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-29 20:49:20.227  5513  5559 I jxcore-log:     _lineNumber: '651',
08-29 20:49:20.227  5513  5559 I jxcore-log:     _columnNumber: '1',
08-29 20:49:20.227  5513  5559 I jxcore-log:    
,08-29 20:49:20.228  5513  5559 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-29 20:49:20.228  5513  5559 I jxcore-log: 
08-29 20:49:20.228  5513  5559 E jxcore-log: Error: 
08-29 20:49:20.228  5513  5559 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
,08-29 20:49:20.228  5513  5559 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-29 20:49:20.228  5513  5559 E jxcore-log: 
,08-29 20:49:20.693  5560  5560 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-29 20:49:20.700  5560  5560 D AndroidRuntime: CheckJNI is OFF
,08-29 20:49:20.724  5560  5560 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-29 20:49:20.753  5560  5560 I Radio-JNI: register_android_hardware_Radio DONE
,08-29 20:49:20.769  5560  5560 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 20:49:20.776   929   942 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,08-29 20:49:20.777   929   942 I ActivityManager: Killing 5513:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,08-29 20:49:20.871   929  3546 D GraphicsStats: Buffer count: 2
,08-29 20:49:20.871   929  3589 I WindowState: WIN DEATH: Window{3320c67 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-29 20:49:20.871   929  2982 D WifiService: Client connection lost with reason: 4
,08-29 20:49:20.897   929   942 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-29 20:49:20.898   929   942 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-29 20:49:20.898   929   952 I art     : Starting a blocking GC Explicit
,08-29 20:49:20.899   929   942 E ActivityManager: Failure starting process com.test.thalitest
08-29 20:49:20.899   929   942 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-29 20:49:20.899   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-29 20:49:20.899   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-29 20:49:20.899   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-29 20:49:20.899   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-29 20:49:20.899   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-29 20:49:20.899   929   942 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-29 20:49:20.899   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-29 20:49:20.899   929   942 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-29 20:49:20.899   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-29 20:49:20.899   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 20:49:20.899   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-29 20:49:20.899   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-29 20:49:20.899   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-29 20:49:20.899   929   942 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-29 20:49:20.899   929   942 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 20:49:20.899   929   942 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 20:49:20.899   929   942 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 20:49:20.899   929   942 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-29 20:49:20.899   929   942 I ActivityManager:   Force finishing activity ActivityRecord{b4ef520 u0 com.test.thalitest/.MainActivity t4}
08-29 20:49:20.903   929   939 W ActivityManager: Spurious death for ProcessRecord{b74ec75 0:com.test.thalitest/u0a77}, curProc for 5513: null
,08-29 20:49:20.973   929   952 I art     : Explicit concurrent mark sweep GC freed 32553(2MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 28MB/42MB, paused 1.409ms total 74.673ms
,08-29 20:49:20.994   929   952 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-29 20:49:20.997  5560  5560 I art     : System.exit called, status: 0
08-29 20:49:20.998  5560  5560 I AndroidRuntime: VM exiting with result code 0.
,08-29 20:49:21.001   929   952 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,08-29 20:49:21.009   929   942 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-29 20:49:21.014  3407  3407 I Keyboard.Facilitator: resetDictionaries() : en_US
08-29 20:49:21.015  4345  4345 D BluetoothMapAppObserver: onReceive
08-29 20:49:21.015  4345  4345 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-29 20:49:21.019   929  2945 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-29 20:49:21.022  3464  3913 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 20:49:21.046  3529  3529 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-29 20:49:21.049  3407  5571 I Keyboard.Facilitator.DecoderInitializer: run()
,08-29 20:49:21.064  4817  5572 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-29 20:49:21.076  3407  5571 I Decoder : createOrResetDecoder
,08-29 20:49:21.077   929   929 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-29 20:49:21.086  3614  3614 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
08-29 20:49:21.086  3614  3614 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-29 20:49:21.095    27    27 W kworker/2:1: type=1400 audit(0.0:71): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 20:49:21.103  3868  5577 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-29 20:49:21.105  3868  5577 D AccountUtils: Clearing selected account for com.test.thalitest
,08-29 20:49:21.115    27    27 W kworker/2:1: type=1400 audit(0.0:72): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 20:49:21.121  3614  3614 I ConfigService: onCreate
,08-29 20:49:21.134  3407  5571 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-29 20:49:21.135    27    27 W kworker/2:1: type=1400 audit(0.0:73): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 20:49:21.147  3868  5577 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,08-29 20:49:21.174  3868  5577 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-29 20:49:21.174  3868  5577 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 20:49:21.174  3868  5577 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 20:49:21.174  3868  5577 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 20:49:21.174  3868  5577 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 20:49:21.174  3868  5577 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 20:49:21.174  3868  5577 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 20:49:21.174  3868  5577 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 20:49:21.174  3868  5577 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 20:49:21.174  3868  5577 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 20:49:21.174  3868  5577 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 20:49:21.174  3868  5577 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 20:49:21.174  3868  5577 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 20:49:21.174  3868  5577 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 20:49:21.174  3868  5577 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 20:49:21.174  3868  5577 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 20:49:21.174  3868  5577 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-29 20:49:21.174  3868  5577 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 20:49:21.174  3868  5577 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 20:49:21.174  3868  5577 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-29 20:49:21.174  3868  5577 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 20:49:21.174  3868  5577 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-29 20:49:21.174  3868  5577 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-29 20:49:21.174  3868  5577 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-29 20:49:21.174  3868  5577 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-29 20:49:21.174  3868  5577 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-29 20:49:21.174  3868  5577 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-29 20:49:21.174  3868  5577 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-29 20:49:21.174  3868  5577 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-29 20:49:21.174  3868  5577 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-29 20:49:21.174  3868  5577 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-29 20:49:21.174  3868  5577 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-29 20:49:21.174  3868  5577 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-29 20:49:21.174  3868  5577 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 20:49:21.174  3868  5577 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-29 20:49:21.174  3868  5577 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-29 20:49:21.174  3868  5577 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-29 20:49:21.174  3868  5577 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-29 20:49:21.174  3868  5577 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 20:49:21.174  3868  5577 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 20:49:21.174  3868  5577 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-29 20:49:21.174  3868  5577 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 20:49:21.186  3868  5577 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,08-29 20:49:21.196  4817  5572 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
08-29 20:49:21.197  4817  5572 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-29 20:49:21.197  4817  5572 E AndroidRuntime: Process: android.process.acore, PID: 4817
08-29 20:49:21.197  4817  5572 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 20:49:21.197  4817  5572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 20:49:21.197  4817  5572 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 20:49:21.197  4817  5572 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 20:49:21.197  4817  5572 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 20:49:21.197  4817  5572 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 20:49:21.197  4817  5572 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-29 20:49:21.197  4817  5572 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-29 20:49:21.197  4817  5572 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-29 20:49:21.197  4817  5572 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-29 20:49:21.197  4817  5572 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-29 20:49:21.197  4817  5572 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-29 20:49:21.197  4817  5572 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-29 20:49:21.197  4817  5572 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-29 20:49:21.197  4817  5572 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 20:49:21.197  4817  5572 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 20:49:21.197  4817  5572 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 20:49:21.203   929  5585 E DropBoxManagerService: Can't write: system_app_crash
08-29 20:49:21.203   929  5585 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop106.tmp: open failed: EROFS (Read-only file system)
08-29 20:49:21.203   929  5585 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-29 20:49:21.203   929  5585 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-29 20:49:21.203   929  5585 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-29 20:49:21.203   929  5585 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-29 20:49:21.203   929  5585 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-29 20:49:21.203   929  5585 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-29 20:49:21.203   929  5585 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-29 20:49:21.203   929  5585 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-29 20:49:21.203   929  5585 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-29 20:49:21.203   929  5585 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 20:49:21.203   929  5585 E DropBoxManagerService: 	... 5 more
,08-29 20:49:21.205  4817  5572 I Process : Sending signal. PID: 4817 SIG: 9
,08-29 20:49:21.210   384   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0
,08-29 20:49:21.210   384   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
