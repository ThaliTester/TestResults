#### Test 83243049e1001da_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
08-30 06:40:41.632   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:40:42.633   541   541 I ServiceManager: Waiting for service AtCmdFwd...
08-30 06:40:42.735  5678  5678 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-30 06:40:42.742  5678  5678 D AndroidRuntime: CheckJNI is OFF
08-30 06:40:42.770  5678  5678 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-30 06:40:42.806  5678  5678 I Radio-JNI: register_android_hardware_Radio DONE
08-30 06:40:42.823  5678  5678 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-30 06:40:42.828   928  3597 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-30 06:40:42.870   928  3597 I ActivityManager: Start proc 5687:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
08-30 06:40:42.874  5678  5678 D AndroidRuntime: Shutting down VM
08-30 06:40:42.956  5687  5687 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
08-30 06:40:42.977  5687  5687 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-30 06:40:43.001  5687  5687 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 7860-7878)
08-30 06:40:43.001  5687  5687 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 06:40:43.017  5687  5687 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {b35e700}
08-30 06:40:43.017  5687  5687 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-30 06:40:43.017  5687  5687 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-30 06:40:43.021  5687  5687 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-30 06:40:43.021  5687  5687 E SysUtils: ApplicationContext is null in ApplicationStatus
08-30 06:40:43.052  5687  5687 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-30 06:40:43.065  5687  5687 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 06:40:43.065  5687  5687 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-30 06:40:43.065  5687  5687 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
08-30 06:40:43.065  5687  5687 I Adreno  : Build Date                       : 10/21/15
08-30 06:40:43.065  5687  5687 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-30 06:40:43.065  5687  5687 I Adreno  : Local Branch                     : 
08-30 06:40:43.065  5687  5687 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
08-30 06:40:43.065  5687  5687 I Adreno  : Remote Branch                    : NONE
08-30 06:40:43.065  5687  5687 I Adreno  : Reconstruct Branch               : NOTHING
,08-30 06:40:43.107   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@600701f:true
,08-30 06:40:43.158  5687  5687 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-30 06:40:43.171  5687  5687 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,08-30 06:40:43.204  5687  5724 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-30 06:40:43.212  5687  5711 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-30 06:40:43.249  5687  5724 I OpenGLRenderer: Initialized EGL, version 1.4
,08-30 06:40:43.341   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +433ms (total +492ms)
,08-30 06:40:43.364  5687  5687 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5687
,08-30 06:40:43.447  5687  5687 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-30 06:40:43.570  5687  5727 D jxcore_app_log: JniHelper::setJavaVM(0xf507c000), pthread_self() = -583268048
,08-30 06:40:43.574  5687  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-30 06:40:43.574  5687  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-30 06:40:43.574  5687  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-30 06:40:43.574  5687  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-30 06:40:43.574  5687  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-30 06:40:43.574  5687  5727 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2e40916 added. We now have 1 listener(s)
,08-30 06:40:43.577  5687  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,08-30 06:40:43.577  5687  5727 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-30 06:40:43.578  5687  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-30 06:40:43.578  5687  5727 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-30 06:40:43.580  5687  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-30 06:40:43.580  5687  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-30 06:40:43.580  5687  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-30 06:40:43.580  5687  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
08-30 06:40:43.580  5687  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-30 06:40:43.580  5687  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-30 06:40:43.580  5687  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-30 06:40:43.580  5687  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-30 06:40:43.580  5687  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-30 06:40:43.580  5687  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-30 06:40:43.580  5687  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-30 06:40:43.580  5687  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-30 06:40:43.580  5687  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-30 06:40:43.580  5687  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-30 06:40:43.580  5687  5727 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8a8bc6d added. We now have 1 listener(s)
08-30 06:40:43.580  5687  5727 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-30 06:40:43.582   928  3017 D WifiService: New client listening to asynchronous messages
,08-30 06:40:43.583  5687  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-30 06:40:43.583  5687  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-30 06:40:43.583  5687  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-30 06:40:43.583  5687  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-30 06:40:43.583  5687  5727 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-30 06:40:43.585  5687  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-30 06:40:43.585  5687  5727 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,08-30 06:40:43.589  5687  5727 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-30 06:40:43.589  5687  5727 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 06:40:43.589  5687  5727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:40:43.589  5687  5727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:40:43.589  5687  5727 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:40:43.589  5687  5727 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:40:43.589  5687  5727 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 06:40:43.589  5687  5727 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 06:40:43.589  5687  5727 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-30 06:40:43.589  5687  5727 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-30 06:40:43.589  5687  5727 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-30 06:40:43.589  5687  5727 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-30 06:40:43.592  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 06:40:43.595  5687  5687 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-30 06:40:43.607  5687  5687 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-30 06:40:43.634   541   541 I ServiceManager: Waiting for service AtCmdFwd...
,08-30 06:40:43.883  5687  5733 W jxcore-log: Initializing JXcore engine
08-30 06:40:43.884  5687  5733 W jxcore-log: JXcore engine is ready
,08-30 06:40:43.900  5687  5696 I art     : Background sticky concurrent mark sweep GC freed 85076(8MB) AllocSpace objects, 18(1892KB) LOS objects, 26% free, 24MB/32MB, paused 1.784ms total 100.514ms
,08-30 06:40:43.901  5733  5733 W Thread-57: type=1400 audit(0.0:67): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=13553 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-30 06:40:43.901  5733  5733 W Thread-57: type=1400 audit(0.0:68): avc: denied { ioctl } for path="socket:[12742]" dev="sockfs" ino=12742 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-30 06:40:43.901  5733  5733 W Thread-57: type=1400 audit(0.0:69): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5901 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-30 06:40:43.901  5733  5733 W Thread-57: type=1400 audit(0.0:70): avc: denied { ioctl } for path="socket:[31695]" dev="sockfs" ino=31695 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-30 06:40:43.916  5687  5733 W jxcore-log: Starting JXcore engine
,08-30 06:40:43.969  5687  5733 W jxcore-log: Platform android
08-30 06:40:43.969  5687  5733 W jxcore-log: 
,08-30 06:40:43.969  5687  5733 W jxcore-log: Process ARCH arm
08-30 06:40:43.969  5687  5733 W jxcore-log: 
,08-30 06:40:44.064  5687  5733 I jxcore-log: JXcore Cordova bridge is ready!
08-30 06:40:44.064  5687  5733 I jxcore-log: 
,08-30 06:40:44.064  5687  5733 W jxcore-log: JXcore engine is started
,08-30 06:40:44.071  5687  5727 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-30 06:40:44.076  5687  5687 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-30 06:40:44.634   541   541 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-30 06:40:53.857  5687  5733 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-30 06:40:53.857  5687  5733 I jxcore-log: 
,08-30 06:40:53.859  5687  5733 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-30 06:40:53.859  5687  5733 I jxcore-log: 
,08-30 06:40:53.863  5687  5733 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-30 06:40:53.863  5687  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-30 06:40:53.863  5687  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-30 06:40:53.863  5687  5733 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-30 06:40:53.863  5687  5733 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-30 06:40:53.863  5687  5733 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-30 06:40:53.863  5687  5733 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-30 06:40:53.863  5687  5733 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-30 06:40:53.868  5687  5733 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-30 06:40:53.872  5687  5733 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-30 06:40:53.872  5687  5733 I jxcore-log: 
,08-30 06:40:53.875  5687  5733 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-30 06:40:53.875  5687  5733 I jxcore-log: 
,08-30 06:40:54.124  5687  5733 I jxcore-log: Running unit tests
08-30 06:40:54.124  5687  5733 I jxcore-log: 
,08-30 06:40:54.125  5687  5733 E JX-Cordova: JavaCall recevied a call for unknown method ExecuteNativeTests
08-30 06:40:54.125  5687  5733 I jxcore-log: Failed to execute UT.
08-30 06:40:54.125  5687  5733 I jxcore-log: 
08-30 06:40:54.126  5687  5733 I jxcore-log: Unit Test app is loaded
08-30 06:40:54.126  5687  5733 I jxcore-log: 
,08-30 06:40:54.130  5687  5733 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-30 06:40:54.130  5687  5733 I jxcore-log: 
,08-30 06:40:54.133  5687  5733 I jxcore-log: My device name is: Huawei-Nexus 6P
08-30 06:40:54.133  5687  5733 I jxcore-log: 
,08-30 06:40:54.134  5687  5733 I jxcore-log: WARN testUtils: myNameCallback not set!
08-30 06:40:54.134  5687  5733 I jxcore-log: 
,08-30 06:40:54.144   928  5271 D NetlinkSocketObserver: NeighborEvent{elapsedMs=289020, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_PROBE}
,08-30 06:40:54.151  5687  5687 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,08-30 06:40:55.906  5687  5733 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js
08-30 06:40:55.906  5687  5733 I jxcore-log: 
,08-30 06:40:56.224  5687  5733 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js
08-30 06:40:56.224  5687  5733 I jxcore-log: 
,08-30 06:40:56.242  5687  5733 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js
08-30 06:40:56.242  5687  5733 I jxcore-log: 
,08-30 06:40:57.239  5687  5733 I jxcore-log: Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js
08-30 06:40:57.239  5687  5733 I jxcore-log: 
,08-30 06:40:57.398  5687  5733 I jxcore-log: ERROR runTests: 
08-30 06:40:57.398  5687  5733 I jxcore-log: 
,08-30 06:40:57.400  5687  5733 E jxcore  : Error!: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 06:40:57.400  5687  5733 E jxcore  : Stack: [{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"loadFile","_lineNumber":"26","_columnNumber":"11","_msg":"    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"38","_columnNumber":"7","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/runTests.js","_functionName":"","_lineNumber":"35","_columnNumber":"3","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"}]
08-30 06:40:57.401  5687  5733 I jxcore-log: WARN testUtils: logCallback not set!
08-30 06:40:57.401  5687  5733 I jxcore-log: 
,08-30 06:40:57.408  5687  5733 I jxcore-log: [ { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 06:40:57.408  5687  5733 I jxcore-log:     _functionName: 'loadFile',
08-30 06:40:57.408  5687  5733 I jxcore-log:     _lineNumber: '26',
08-30 06:40:57.408  5687  5733 I jxcore-log:     _columnNumber: '11',
08-30 06:40:57.408  5687  5733 I jxcore-log:     _msg: '    at loadFile@/data/data/com.test.thalitest/files/www/jxcore/runTests.js:26:11' },
08-30 06:40:57.408  5687  5733 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 06:40:57.408  5687  5733 I jxcore-log:     _functionName: '',
08-30 06:40:57.408  5687  5733 I jxcore-log:     _lineNumber: '38',
08-30 06:40:57.408  5687  5733 I jxcore-log:     _columnNumber: '7',
08-30 06:40:57.408  5687  5733 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:38:7' },
08-30 06:40:57.408  5687  5733 I jxcore-log:   { _fileName: '/data/data/com.test.thalitest/files/www/jxcore/runTests.js',
08-30 06:40:57.408  5687  5733 I jxcore-log:     _functionName: '',
08-30 06:40:57.408  5687  5733 I jxcore-log:     _lineNumber: '35',
08-30 06:40:57.408  5687  5733 I jxcore-log:     _columnNumber: '3',
08-30 06:40:57.408  5687  5733 I jxcore-log:     _msg: '    at @/data/data/com.test.thalitest/files/www/jxcore/runTests.js:35:3' },
08-30 06:40:57.408  5687  5733 I jxcore-log:   { _fileName: 'module.js',
08-30 06:40:57.408  5687  5733 I jxcore-log:     _functionName: '$w.prototype._compile',
08-30 06:40:57.408  5687  5733 I jxcore-log:     _lineNumber: '621',
08-30 06:40:57.408  5687  5733 I jxcore-log:     _columnNumber: '8',
08-30 06:40:57.408  5687  5733 I jxcore-log:     _msg: '    at $w.prototype._compile@module.js:621:8' },
08-30 06:40:57.408  5687  5733 I jxcore-log:   { _fileName: 'module.js',
08-30 06:40:57.408  5687  5733 I jxcore-log:     _functionName: '$w._extensions[".js"]',
08-30 06:40:57.408  5687  5733 I jxcore-log:     _lineNumber: '651',
08-30 06:40:57.408  5687  5733 I jxcore-log:     _columnNumber: '1',
08-30 06:40:57.408  5687  5733 I jxcore-log:    
,08-30 06:40:57.408  5687  5733 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-30 06:40:57.408  5687  5733 I jxcore-log: 
,08-30 06:40:57.408  5687  5733 E jxcore-log: Error: 
08-30 06:40:57.408  5687  5733 E jxcore-log: Error when loading file /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js: Error: Cannot find module '../../thalilogger'
08-30 06:40:57.408  5687  5733 E jxcore-log:  (/data/data/com.test.thalitest/files/www/jxcore/runTests.js 26:11)
08-30 06:40:57.408  5687  5733 E jxcore-log: 
,08-30 06:40:57.850  5734  5734 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-30 06:40:57.855  5734  5734 D AndroidRuntime: CheckJNI is OFF
,08-30 06:40:57.886  5734  5734 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-30 06:40:57.920  5734  5734 I Radio-JNI: register_android_hardware_Radio DONE
,08-30 06:40:57.937  5734  5734 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-30 06:40:57.945   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
08-30 06:40:57.946   928   941 I ActivityManager: Killing 5687:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,08-30 06:40:58.046   928  3597 I WindowState: WIN DEATH: Window{32b9f0f u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-30 06:40:58.046   928   939 D GraphicsStats: Buffer count: 2
08-30 06:40:58.046   928  3017 D WifiService: Client connection lost with reason: 4
,08-30 06:40:58.066   928   951 I art     : Starting a blocking GC Explicit
,08-30 06:40:58.074   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
08-30 06:40:58.074   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-30 06:40:58.075   928   941 E ActivityManager: Failure starting process com.test.thalitest
08-30 06:40:58.075   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-30 06:40:58.075   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-30 06:40:58.075   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-30 06:40:58.075   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-30 06:40:58.075   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-30 06:40:58.075   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-30 06:40:58.075   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-30 06:40:58.075   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-30 06:40:58.075   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-30 06:40:58.075   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-30 06:40:58.075   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-30 06:40:58.075   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-30 06:40:58.075   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-30 06:40:58.075   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-30 06:40:58.075   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-30 06:40:58.075   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 06:40:58.075   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-30 06:40:58.075   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 06:40:58.075   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-30 06:40:58.075   928   941 I ActivityManager:   Force finishing activity ActivityRecord{25e8328 u0 com.test.thalitest/.MainActivity t4}
,08-30 06:40:58.084   928  3581 W ActivityManager: Spurious death for ProcessRecord{e3e185d 0:com.test.thalitest/u0a77}, curProc for 5687: null
,08-30 06:40:58.145   928   951 I art     : Explicit concurrent mark sweep GC freed 40421(2MB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 28MB/42MB, paused 1.560ms total 79.209ms
,08-30 06:40:58.168   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-30 06:40:58.171  5734  5734 I art     : System.exit called, status: 0
,08-30 06:40:58.172  5734  5734 I AndroidRuntime: VM exiting with result code 0.
,08-30 06:40:58.176   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,08-30 06:40:58.180   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-30 06:40:58.184  4464  4464 D BluetoothMapAppObserver: onReceive
08-30 06:40:58.185  4464  4464 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-30 06:40:58.196  3677  3971 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-30 06:40:58.198  3473  3473 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-30 06:40:58.198   928  3007 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-30 06:40:58.213  3473  5745 I Keyboard.Facilitator.DecoderInitializer: run()
,08-30 06:40:58.219  5403  5746 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-30 06:40:58.227  3473  5745 I Decoder : createOrResetDecoder
,08-30 06:40:58.253  3583  3583 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-30 06:40:58.262  3656  3656 I ConfigService: onCreate
,08-30 06:40:58.277  3473  5745 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-30 06:40:58.278   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-30 06:40:58.290  3656  3656 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,08-30 06:40:58.290  3656  3656 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,08-30 06:40:58.304  3932  5753 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-30 06:40:58.301    27    27 W kworker/2:1: type=1400 audit(0.0:71): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-30 06:40:58.311    27    27 W kworker/2:1: type=1400 audit(0.0:72): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-30 06:40:58.321    27    27 W kworker/2:1: type=1400 audit(0.0:73): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-30 06:40:58.334  3932  5753 D AccountUtils: Clearing selected account for com.test.thalitest
,08-30 06:40:58.336  5403  5746 E SQLiteLog: (3850) statement aborts at 16: [DELETE FROM voicemail_status WHERE (((source_package = 'com.test.thalitest')))] disk I/O error
,--------- beginning of crash
08-30 06:40:58.338  5403  5746 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-30 06:40:58.338  5403  5746 E AndroidRuntime: Process: android.process.acore, PID: 5403
08-30 06:40:58.338  5403  5746 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-30 06:40:58.338  5403  5746 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-30 06:40:58.338  5403  5746 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-30 06:40:58.338  5403  5746 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-30 06:40:58.338  5403  5746 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-30 06:40:58.338  5403  5746 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-30 06:40:58.338  5403  5746 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-30 06:40:58.338  5403  5746 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailStatusTable.delete(VoicemailStatusTable.java:80)
08-30 06:40:58.338  5403  5746 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-30 06:40:58.338  5403  5746 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-30 06:40:58.338  5403  5746 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-30 06:40:58.338  5403  5746 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:52)
08-30 06:40:58.338  5403  5746 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-30 06:40:58.338  5403  5746 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 06:40:58.338  5403  5746 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 06:40:58.338  5403  5746 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-30 06:40:58.338  5403  5746 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-30 06:40:58.341   928  5756 E DropBoxManagerService: Can't write: system_app_crash
08-30 06:40:58.341   928  5756 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop102.tmp: open failed: EROFS (Read-only file system)
08-30 06:40:58.341   928  5756 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-30 06:40:58.341   928  5756 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-30 06:40:58.341   928  5756 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-30 06:40:58.341   928  5756 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-30 06:40:58.341   928  5756 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-30 06:40:58.341   928  5756 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-30 06:40:58.341   928  5756 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-30 06:40:58.341   928  5756 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-30 06:40:58.341   928  5756 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-30 06:40:58.341   928  5756 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-30 06:40:58.341   928  5756 E DropBoxManagerService: 	... 5 more
,08-30 06:40:58.347  3473  5745 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /system/app/LatinImeGoogle/LatinImeGoogle.apk (offset=3195532, length=4014912) with up to date LoudsLmContentVersion = 20150512
,08-30 06:40:58.349  3473  5745 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-30 06:40:58.349  3473  5745 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-30 06:40:58.350  5403  5746 I Process : Sending signal. PID: 5403 SIG: 9
,08-30 06:40:58.363  3932  5753 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
08-30 06:40:58.369  3473  5745 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-30 06:40:58.370  3473  5745 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
,08-30 06:40:58.370  3473  5745 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-30 06:40:58.370  3473  5745 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-30 06:40:58.371  3473  5745 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-30 06:40:58.371  3473  5745 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-30 06:40:58.371  3473  5745 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-30 06:40:58.371  3473  5745 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-30 06:40:58.371  3473  5745 I StatsUtilsManager: startPeriodStatsRecorder() : Success
,08-30 06:40:58.371  3473  5745 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-30 06:40:58.394  3932  5753 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
08-30 06:40:58.394  3932  5753 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 06:40:58.394  3932  5753 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 06:40:58.394  3932  5753 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 06:40:58.394  3932  5753 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 06:40:58.394  3932  5753 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 06:40:58.394  3932  5753 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 06:40:58.394  3932  5753 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 06:40:58.394  3932  5753 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 06:40:58.394  3932  5753 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 06:40:58.394  3932  5753 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 06:40:58.394  3932  5753 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 06:40:58.394  3932  5753 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 06:40:58.394  3932  5753 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 06:40:58.394  3932  5753 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 06:40:58.394  3932  5753 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 06:40:58.394  3932  5753 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-30 06:40:58.394  3932  5753 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 06:40:58.394  3932  5753 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 06:40:58.394  3932  5753 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-30 06:40:58.394  3932  5753 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 06:40:58.395  3932  5753 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
08-30 06:40:58.395  3932  5753 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-30 06:40:58.395  3932  5753 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-30 06:40:58.395  3932  5753 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-30 06:40:58.395  3932  5753 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-30 06:40:58.395  3932  5753 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-30 06:40:58.395  3932  5753 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-30 06:40:58.395  3932  5753 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-30 06:40:58.395  3932  5753 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-30 06:40:58.395  3932  5753 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-30 06:40:58.395  3932  5753 E ,SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-30 06:40:58.395  3932  5753 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-30 06:40:58.395  3932  5753 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 06:40:58.395  3932  5753 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-30 06:40:58.395  3932  5753 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-30 06:40:58.395  3932  5753 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
08-30 06:40:58.395  3932  5753 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
08-30 06:40:58.395  3932  5753 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-30 06:40:58.395  3932  5753 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-30 06:40:58.395  3932  5753 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
08-30 06:40:58.395  3932  5753 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-30 06:40:58.396  3932  5753 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
08-30 06:40:58.410   381   479 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
